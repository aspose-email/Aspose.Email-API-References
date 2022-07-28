---
title: MapiRecipient
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt die Empfängerinformationen in der Microsoft Outlook-Nachricht dar.
type: docs
weight: 18620
url: /de/net/aspose.email.mapi/mapirecipient/
---
## MapiRecipient class

Stellt die Empfängerinformationen in der Microsoft Outlook-Nachricht dar.

```csharp
public class MapiRecipient : MapiPropertyContainer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AddressType](../../aspose.email.mapi/mapirecipient/addresstype) { get; } | Ruft den Typ der Adresse von dem Empfänger oder Absender der Nachricht ab. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ruft die Codepage ab. |
| [Content](../../aspose.email.mapi/mapirecipient/content) { get; } | Ruft den Inhalt ab. |
| [DisplayName](../../aspose.email.mapi/mapirecipient/displayname) { get; set; } | Ruft den Anzeigenamen des Empfängers oder Absenders der Nachricht ab oder legt ihn fest. |
| [EmailAddress](../../aspose.email.mapi/mapirecipient/emailaddress) { get; set; } | Ruft die E-Mail-Adresse des Empfängers oder Absenders der -Nachricht ab oder legt sie fest. |
| [NamedProperties](../../aspose.email.mapi/mapirecipient/namedproperties) { get; } | Ruft die benannten Eigenschaften der Nachricht ab. |
| [OrganizationEmailAddress](../../aspose.email.mapi/mapirecipient/organizationemailaddress) { get; } | Ruft die E-Mail-Adresse der Organisation ab. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ruft die Sammlung von Eigenschaften ab. |
| [PropertyStream](../../aspose.email.mapi/mapirecipient/propertystream) { get; } | Ruft den Eigenschaftsstream ab. |
| [RecipientClass](../../aspose.email.mapi/mapirecipient/recipientclass) { get; } | Ruft den Typ des Rezepts ab. |
| [RecipientTrackStatus](../../aspose.email.mapi/mapirecipient/recipienttrackstatus) { get; set; } | Status der Antwort des Empfängers auf eine Besprechungsanfrage. |
| [RecipientType](../../aspose.email.mapi/mapirecipient/recipienttype) { get; } | Ruft den Typ des Empfängers oder Absenders ab. |
| [SubStorages](../../aspose.email.mapi/mapirecipient/substorages) { get; } | Ruft die Unterspeicher ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycontainer/getproperty)(PropertyDescriptor) | Ruft MAPI-Eigenschaft nach Eigenschaftsdeskriptor ab. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als booleschen Typ ab. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als DateTime-Typ ab. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Ruft den int32-Wert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als Typ Long (int64) ab. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als Short-Typ ab. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestimmt, ob Zeichenfolgeneigenschaften Unicode-codiert sind oder nicht. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Legt die Eigenschaft fest. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(PropertyDescriptor, object) | Legt die MAPI-Eigenschaft fest. |
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
