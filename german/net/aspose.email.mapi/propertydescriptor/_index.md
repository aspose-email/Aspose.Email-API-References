---
title: PropertyDescriptor
second_title: Aspose.Email für .NET-API-Referenz
description: Klasse enthält Eigenschaftsbeschreibungsinformationen.
type: docs
weight: 19010
url: /de/net/aspose.email.mapi/propertydescriptor/
---
## PropertyDescriptor class

Klasse enthält Eigenschaftsbeschreibungsinformationen.

```csharp
public abstract class PropertyDescriptor : IEquatable<PropertyDescriptor>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname) { get; } | Der Name, der verwendet wird, um auf die Eigenschaft in der Dokumentation zu verweisen. Das Präfix des kanonischen Namens identifiziert die grundlegenden Merkmale einer Eigenschaft für den Implementierer. Die kanonische Namensstruktur verwendet drei Kategorien, die durch die folgenden Präfixe für den kanonischen Eigenschaftsnamen gekennzeichnet sind: * PidLid-Präfix: Eigenschaften, die durch eine vorzeichenlose 32-Bit-Menge zusammen mit einem Eigenschaftssatz identifiziert werden. * PidName-Präfix: Eigenschaften, die durch einen Zeichenfolgennamen zusammen mit einem Eigenschaftssatz identifiziert werden. * PidTag-Präfix: Eigenschaften, die durch eine vorzeichenlose 16-Bit-Menge identifiziert werden. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype) { get; } | Der Eigenschaftswerttyp, wie in [MS-OXCDATA] beschrieben, der den für die Eigenschaft zulässigen Wertetyp angibt. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype) { get; } | Gibt an, ob der Datentyp mehrere Werte enthält |
| [Name](../../aspose.email.mapi/propertydescriptor/name) { get; } | Ruft eine Zeichenfolge ab, die eine Eigenschaft identifiziert. |
| static [Use8BitStringAsUnicode](../../aspose.email.mapi/propertydescriptor/use8bitstringasunicode) { get; set; } | Gibt an, ob PropertyDataType.String8 als PropertyDataType.String interpretiert werden muss |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance#getinstance_4)(MapiProperty) | Ruft ab[`PropertyDescriptor`](../propertydescriptor) Objekt aus MAPI property |
| static [Parse](../../aspose.email.mapi/propertydescriptor/parse)(string) | Initialisiert eine neue Instanz von[`PropertyDescriptor`](../propertydescriptor) Klasse |
| abstract [Equals](../../aspose.email.mapi/propertydescriptor/equals#equals)(PropertyDescriptor) | Gibt an, ob das aktuelle Objekt gleich einem anderen Objekt desselben Typs ist. |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance#getinstance_3)(long) | Ruft ab[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) Objekt |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance#getinstance_2)(int, PropertyDataType) | Ruft ab[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) Objekt |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance#getinstance)(long, PropertyDataType, Guid) | Ruft ab[`PidLidPropertyDescriptor`](../pidlidpropertydescriptor) Objekt |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance#getinstance_1)(string, PropertyDataType, Guid) | Ruft ab[`PidNamePropertyDescriptor`](../pidnamepropertydescriptor) Objekt |
| [operator ==](../../aspose.email.mapi/propertydescriptor/op_equality) | Bestimmt, ob die angegebenen Objekte einander gleich sind. |
| [operator !=](../../aspose.email.mapi/propertydescriptor/op_inequality) | Ermittelt, ob die angegebenen Objekte ungleich sind. |

### Siehe auch

* namensraum [Aspose.Email.Mapi](../../aspose.email.mapi)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->