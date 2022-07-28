---
title: MapiContact
second_title: Aspose.Email für .NET-API-Referenz
description: Repräsentiert Outlook-Kontaktinformationen
type: docs
weight: 18190
url: /de/net/aspose.email.mapi/mapicontact/
---
## MapiContact class

Repräsentiert Outlook-Kontaktinformationen

```csharp
public sealed class MapiContact : MapiMessageItemBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MapiContact](mapicontact#constructor)() | Initialisiert eine neue Instanz von[`MapiContact`](../mapicontact) Klasse |
| [MapiContact](mapicontact#constructor_1)(string, string) | Initialisiert eine neue Instanz von[`MapiContact`](../mapicontact) Klasse. |
| [MapiContact](mapicontact#constructor_2)(string, string, string) | Initialisiert eine neue Instanz von[`MapiContact`](../mapicontact) Klasse. |
| [MapiContact](mapicontact#constructor_3)(string, string, string, string) | Initialisiert eine neue Instanz von[`MapiContact`](../mapicontact) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapicontact/attachments) { get; } | Ruft die Anhänge im Kontakt ab. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Enthält die mit einem Artikel verknüpften Rechnungsinformationen. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Ruft den Nachrichtentext ab. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Ruft die ab[`BodyRtf`](../mapimessageitembase/bodyrtf) der in HTML konvertierten Nachricht, falls vorhanden, ansonsten ein leerer String. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Ruft den RTF-formatierten Nachrichtentext ab oder legt ihn fest. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Ruft den Typ des Körpers ab. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Enthält Schlüsselwörter oder Kategorien für das Nachrichtenobjekt. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ruft die Codepage ab. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Enthält die Namen der Firmen, die einem Artikel zugeordnet sind. |
| [ElectronicAddresses](../../aspose.email.mapi/mapicontact/electronicaddresses) { get; set; } | Geben Sie Eigenschaften für bis zu drei verschiedene E-Mail-Adressen und drei verschiedene Faxadressen an |
| [Events](../../aspose.email.mapi/mapicontact/events) { get; set; } | Geben Sie Ereignisse an, die einem Kontakt zugeordnet sind |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Die Artikel-ID, verwendet mit einem Server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Ruft eine Zeichenfolge mit Berücksichtigung der Groß-/Kleinschreibung ab, die die vom Absender definierte Nachrichtenklasse identifiziert, z. B. IPM.Hinweis. Die Nachrichtenklasse gibt den Typ, Zweck oder Inhalt der Nachricht an. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Enthält die Kilometerinformationen, die einem Artikel zugeordnet sind. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Ruft die benannten Eigenschaften der Nachricht ab. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Ruft die benannte Eigenschaftszuordnung ab. |
| [NameInfo](../../aspose.email.mapi/mapicontact/nameinfo) { get; set; } | Die Eigenschaften werden verwendet, um den Namen der Person anzugeben, die durch den Kontakt repräsentiert wird |
| [OtherFields](../../aspose.email.mapi/mapicontact/otherfields) { get; set; } | Andere Kontaktfelder angeben. |
| [PersonalInfo](../../aspose.email.mapi/mapicontact/personalinfo) { get; set; } | Geben Sie weitere zusätzliche Kontaktinformationen an |
| [Photo](../../aspose.email.mapi/mapicontact/photo) { get; set; } | Enthält Kontaktfoto[`MapiContactPhoto`](../mapicontactphoto) . |
| [PhysicalAddresses](../../aspose.email.mapi/mapicontact/physicaladdresses) { get; set; } | Geben Sie drei physische Adressen an: Privatadresse, Arbeitsadresse und andere Adresse. Eine der Adressen kann als Postanschrift markiert werden |
| [ProfessionalInfo](../../aspose.email.mapi/mapicontact/professionalinfo) { get; set; } | -Eigenschaften werden verwendet, um berufliche -Details für die Person zu speichern, die durch den Kontakt vertreten wird |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ruft die Sammlung von Eigenschaften ab. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Ruft den Eigenschaftsstream ab. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Ruft die Empfänger der Nachricht ab. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Ruft die Empfindlichkeit ab. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Ruft den Betreff der Nachricht ab oder legt ihn fest. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Ruft ein Betreff-Präfix ab, das normalerweise eine Aktion für eine Nachricht angibt, z. B. "FW: " zum Weiterleiten. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Ruft die Unterspeicher ab. |
| [Telephones](../../aspose.email.mapi/mapicontact/telephones) { get; set; } | Geben Sie Telefonnummern für den Kontakt an |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard)(Stream) | liest[`MapiContact`](../mapicontact) aus dem angegebenen Stream, der vCard enthält. Die unterstützten vCard-Versionen sind 2.1 und 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_2)(string) | liest[`MapiContact`](../mapicontact) aus der angegebenen vCard-Datei Die unterstützten vCard-Versionen sind 2.1 und 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_1)(Stream, Encoding) | liest[`MapiContact`](../mapicontact) aus dem angegebenen Stream, der vCard enthält. Die unterstützten vCard-Versionen sind 2.1 und 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_3)(string, Encoding) | liest[`MapiContact`](../mapicontact) aus der angegebenen vCard-Datei Die unterstützten vCard-Versionen sind 2.1 und 3.0 |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Ruft MAPI-Eigenschaft nach Eigenschaftsdeskriptor ab. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als booleschen Typ ab. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als DateTime-Typ ab. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Ruft den int32-Wert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als Typ Long (int64) ab. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als Short-Typ ab. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [GetUnderlyingMessage](../../aspose.email.mapi/mapicontact/getunderlyingmessage)() | Holen Sie sich die MapiMessage, die den Kontakt darstellt. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestimmt, ob Zeichenfolgeneigenschaften Unicode-codiert sind oder nicht. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Ermöglicht das korrekte Entfernen von Eigentum aus allen Sammlungen. |
| [Save](../../aspose.email.mapi/mapicontact/save#save)(Stream) | Speichert dies[`MapiContact`](../mapicontact) in den angegebenen Stream mit vCard-Format. Die unterstützte vCard-Version ist 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_3)(string) | Speichert dies[`MapiContact`](../mapicontact) in die vCard-Datei mit Standardoptionen. Die unterstützte vCard-Version ist 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_1)(Stream, ContactSaveFormat) | Speichert dies[`MapiContact`](../mapicontact) zum gegebenen Stream mit einem Format, das die Standardoptionen verwendet. Das unterstützte Speicherformat ist vCard |
| [Save](../../aspose.email.mapi/mapicontact/save#save_2)(Stream, ContactSaveOptions) | Speichert dies[`MapiContact`](../mapicontact) zum gegebenen Stream mit spezifizierten Speicheroptionen. Die unterstützten Speicheroptionen sind[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| [Save](../../aspose.email.mapi/mapicontact/save#save_4)(string, ContactSaveFormat) | Speichert dies[`MapiContact`](../mapicontact)in die angegebene Datei mit einem Format unter Verwendung der Standardoptionen. Das unterstützte Speicherformat ist vCard. |
| [Save](../../aspose.email.mapi/mapicontact/save#save_5)(string, ContactSaveOptions) | Speichert dies[`MapiContact`](../mapicontact) in Datei mit angegebenen Speicheroptionen. Die unterstützten Speicheroptionen sind[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| override [SetBodyContent](../../aspose.email.mapi/mapicontact/setbodycontent#setbodycontent)(string, BodyContentType) | Legt den Inhalt des Körpers fest. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Legt den Inhalt des Körpers fest. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Ruft den RTF-formatierten Nachrichtentext ab oder legt ihn fest. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Setzt die Meldungsflags. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Legt die Eigenschaft fest. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Legt die MAPI-Eigenschaft fest. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Versuchen Sie, die Eigenschaftsdaten mit dem angegebenen Tag-Schlüssel abzurufen. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Ruft den Wert der angegebenen Eigenschaft als DateTime-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Ruft den Wert der angegebenen Eigenschaft als Int32-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Ruft den Wert der angegebenen Eigenschaft als Long-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Versuchen Sie, Eigenschaftsdaten als Zeichenfolge mit dem angegebenen Tag zu erhalten. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Versuchen Sie, Eigenschaftsdaten als Zeichenfolge mit angegebenem Tag und Codepage abzurufen. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Ruft den Wert der angegebenen Eigenschaft als String-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Ruft den Wert der angegebenen Eigenschaft als String-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war. |

### Siehe auch

* class [MapiMessageItemBase](../mapimessageitembase)
* namensraum [Aspose.Email.Mapi](../../aspose.email.mapi)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
