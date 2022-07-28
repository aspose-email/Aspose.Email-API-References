---
title: PidTagPropertyDescriptor
second_title: Aspose.Email für .NET-API-Referenz
description: Klasse enthält Eigenschaftsbeschreibungsinformationen.
type: docs
weight: 18990
url: /de/net/aspose.email.mapi/pidtagpropertydescriptor/
---
## PidTagPropertyDescriptor class

Klasse enthält Eigenschaftsbeschreibungsinformationen.

```csharp
public class PidTagPropertyDescriptor : PropertyDescriptor
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_1)(long) | Initialisiert eine neue Instanz von[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Eine Eigenschaft, die durch eine 16-Bit-Eigenschafts-ID und einen 16-Bit-Eigenschaftstyp definiert ist. Die Eigenschafts-ID für eine Eigenschaft mit Tag liegt im Bereich 0x001 � 0x7FFF. Property-IDs im Bereich 0x8000 � 0x8FFF sind reserviert für die Zuordnung zu benannten Properties |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor)(int, PropertyDataType) | Initialisiert eine neue Instanz von[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Eine Eigenschaft, die durch eine 16-Bit-Eigenschafts-ID und einen 16-Bit-Eigenschaftstyp definiert ist. Die Eigenschafts-ID für eine Eigenschaft mit Tag liegt im Bereich 0x001 � 0x7FFF. Property-IDs im Bereich 0x8000 � 0x8FFF sind reserviert für die Zuordnung zu benannten Properties |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_2)(string, int, PropertyDataType) | Initialisiert eine neue Instanz von[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Eine Eigenschaft, die durch eine 16-Bit-Eigenschafts-ID und einen 16-Bit-Eigenschaftstyp definiert ist. Die Eigenschafts-ID für eine Eigenschaft mit Tag liegt im Bereich 0x001 � 0x7FFF. Property-IDs im Bereich 0x8000 � 0x8FFF sind reserviert für die Zuordnung zu benannten Properties |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_4)(string, string, long) | Initialisiert eine neue Instanz von[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Eine Eigenschaft, die durch eine 16-Bit-Eigenschafts-ID und einen 16-Bit-Eigenschaftstyp definiert ist. Die Eigenschafts-ID für eine Eigenschaft mit Tag liegt im Bereich 0x001 � 0x7FFF. Property-IDs im Bereich 0x8000 � 0x8FFF sind reserviert für die Zuordnung zu benannten Properties |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_3)(string, string, int, PropertyDataType) | Initialisiert eine neue Instanz von[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Eine Eigenschaft, die durch eine 16-Bit-Eigenschafts-ID und einen 16-Bit-Eigenschaftstyp definiert ist. Die Eigenschafts-ID für eine Eigenschaft mit Tag liegt im Bereich 0x001 � 0x7FFF. Property-IDs im Bereich 0x8000 � 0x8FFF sind reserviert für die Zuordnung zu benannten Properties |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname) { get; } | Der Name, der verwendet wird, um auf die Eigenschaft in der Dokumentation zu verweisen. Das Präfix des kanonischen Namens identifiziert die grundlegenden Merkmale einer Eigenschaft für den Implementierer. Die kanonische Namensstruktur verwendet drei Kategorien, die durch die folgenden Präfixe für den kanonischen Eigenschaftsnamen gekennzeichnet sind: * PidLid-Präfix: Eigenschaften, die durch eine vorzeichenlose 32-Bit-Menge zusammen mit einem Eigenschaftssatz identifiziert werden. * PidName-Präfix: Eigenschaften, die durch einen Zeichenfolgennamen zusammen mit einem Eigenschaftssatz identifiziert werden. * PidTag-Präfix: Eigenschaften, die durch eine vorzeichenlose 16-Bit-Menge identifiziert werden. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype) { get; } | Der Eigenschaftswerttyp, wie in [MS-OXCDATA] beschrieben, der den für die Eigenschaft zulässigen Wertetyp angibt. |
| [Id](../../aspose.email.mapi/pidtagpropertydescriptor/id) { get; } | Ruft eine vorzeichenlose 16-Bit-Menge ab, die eine gekennzeichnete Eigenschaft identifiziert. Eigenschafts-IDs sind nicht unbedingt eindeutig. Mit Ausnahme von Property-IDs im Bereich von 0x6800 bis 0x7BFF, ist die Kombination aus Property-ID und Datentyp eindeutig. Property-IDs im Bereich von 0x6800 bis 0x7BFF werden durch die Nachrichtenklasse definiert. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype) { get; } | Gibt an, ob der Datentyp mehrere Werte enthält |
| [Name](../../aspose.email.mapi/propertydescriptor/name) { get; } | Ruft eine Zeichenfolge ab, die eine Eigenschaft identifiziert. |
| [Tag](../../aspose.email.mapi/pidtagpropertydescriptor/tag) { get; } | Ein Eigenschafts-Tag ist eine 32-Bit-Zahl, die eine eindeutige Eigenschaftskennung in den Bits 16 bis 31 und einen Eigenschaftstyp in den Bits 0 bis 15 enthält. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals_1)(object) | Bestimmt, ob das angegebene System.Object gleich dem aktuellen System.Object ist. |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals)(PropertyDescriptor) | Gibt an, ob das aktuelle Objekt gleich einem anderen Objekt desselben Typs ist. |
| override [GetHashCode](../../aspose.email.mapi/pidtagpropertydescriptor/gethashcode)() | Dient als Hash-Funktion für einen Typ. |
| override [ToString](../../aspose.email.mapi/pidtagpropertydescriptor/tostring)() | Gibt eine Zeichenfolge zurück, die die Eigenschaftsbeschreibung darstellt. |
| [operator ==](../../aspose.email.mapi/pidtagpropertydescriptor/op_equality) | Bestimmt, ob die angegebenen Objekte einander gleich sind. |
| [explicit operator](../../aspose.email.mapi/pidtagpropertydescriptor/op_explicit) | Konvertiert Tag-Wert in markierte Eigenschaft |
| [operator !=](../../aspose.email.mapi/pidtagpropertydescriptor/op_inequality) | Ermittelt, ob die angegebenen Objekte ungleich sind. |

### Siehe auch

* class [PropertyDescriptor](../propertydescriptor)
* namensraum [Aspose.Email.Mapi](../../aspose.email.mapi)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
