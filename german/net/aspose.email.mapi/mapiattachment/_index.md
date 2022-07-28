---
title: MapiAttachment
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt den Anhang in der E-Mail-Nachricht dar.
type: docs
weight: 17880
url: /de/net/aspose.email.mapi/mapiattachment/
---
## MapiAttachment class

Stellt den Anhang in der E-Mail-Nachricht dar.

```csharp
public class MapiAttachment : MapiPropertyContainer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BinaryData](../../aspose.email.mapi/mapiattachment/binarydata) { get; set; } | Ruft binäre Anhangsdaten ab oder legt sie fest. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ruft die Codepage ab. |
| [Content](../../aspose.email.mapi/mapiattachment/content) { get; } | Ruft den Inhalt ab. |
| [DisplayName](../../aspose.email.mapi/mapiattachment/displayname) { get; } | Ruft den Anzeigenamen des Ole-Objekts in einem Anhang ab. |
| [Extension](../../aspose.email.mapi/mapiattachment/extension) { get; } | Ruft eine Dateinamenerweiterung ab, die den Dokumenttyp eines Anhangs angibt. |
| [FileName](../../aspose.email.mapi/mapiattachment/filename) { get; } | Ruft den Basisdateinamen und die Erweiterung eines Anhangs ohne Pfad ab. |
| virtual [ItemId](../../aspose.email.mapi/mapiattachment/itemid) { get; } | Die Artikel-ID, verwendet mit einem Server |
| [LongFileName](../../aspose.email.mapi/mapiattachment/longfilename) { get; } | Ruft den langen Dateinamen und die Erweiterung eines Anhangs ab, ohne Pfad. |
| [MimeTag](../../aspose.email.mapi/mapiattachment/mimetag) { get; } | Ruft Formatierungsinformationen zu einem MIME-Anhang (Multipurpose Internet Mail Extensions) ab. |
| [NamedProperties](../../aspose.email.mapi/mapiattachment/namedproperties) { get; } | Ruft die benannten Eigenschaften der Nachricht ab. |
| [ObjectData](../../aspose.email.mapi/mapiattachment/objectdata) { get; } | Ruft ein Anlageobjekt ab, auf das normalerweise über die OLE IStorage-Schnittstelle zugegriffen wird. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ruft die Sammlung von Eigenschaften ab. |
| [PropertyStream](../../aspose.email.mapi/mapiattachment/propertystream) { get; } | Ruft den Eigenschaftsstream ab. |
| [SubStorages](../../aspose.email.mapi/mapiattachment/substorages) { get; } | Ruft die Unterspeicher ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetProperty](../../aspose.email.mapi/mapiattachment/getproperty)(PropertyDescriptor) | Ruft MAPI-Eigenschaft nach Eigenschaftsdeskriptor ab. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als booleschen Typ ab. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als DateTime-Typ ab. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Ruft den int32-Wert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als Typ Long (int64) ab. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als Short-Typ ab. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestimmt, ob Zeichenfolgeneigenschaften Unicode-codiert sind oder nicht. |
| [RemoveProperty](../../aspose.email.mapi/mapiattachment/removeproperty)(long) | Ermöglicht das korrekte Entfernen von Eigentum aus allen Sammlungen. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save)(Stream) | Inhalt des Anhangs speichern. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save_1)(string) | Inhalt des Anhangs speichern. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty)(MapiProperty) | Legt die Eigenschaft fest. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty_1)(PropertyDescriptor, object) | Legt die MAPI-Eigenschaft fest. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Versuchen Sie, die Eigenschaftsdaten mit dem angegebenen Tag-Schlüssel abzurufen. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Ruft den Wert der angegebenen Eigenschaft als DateTime-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Ruft den Wert der angegebenen Eigenschaft als Int32-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Ruft den Wert der angegebenen Eigenschaft als Long-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Versuchen Sie, Eigenschaftsdaten als Zeichenfolge mit dem angegebenen Tag zu erhalten. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Versuchen Sie, Eigenschaftsdaten als Zeichenfolge mit angegebenem Tag und Codepage abzurufen. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Ruft den Wert der angegebenen Eigenschaft als String-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Ruft den Wert der angegebenen Eigenschaft als String-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |

### Siehe auch

* class [MapiPropertyContainer](../mapipropertycontainer)
* namensraum [Aspose.Email.Mapi](../../aspose.email.mapi)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
