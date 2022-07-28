---
title: MapiCalendar
second_title: Aspose.Email für .NET-API-Referenz
description: Repräsentiert das Mapi-Kalenderobjekt
type: docs
weight: 17910
url: /de/net/aspose.email.mapi/mapicalendar/
---
## MapiCalendar class

Repräsentiert das Mapi-Kalenderobjekt

```csharp
public sealed class MapiCalendar : MapiMessageItemBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MapiCalendar](mapicalendar#constructor)() | Initialisiert eine neue Instanz von[`MapiCalendar`](../mapicalendar) Klasse |
| [MapiCalendar](mapicalendar#constructor_1)(string, string, string, DateTime, DateTime) | Initialisiert eine neue Instanz von[`MapiCalendar`](../mapicalendar) Klasse. |
| [MapiCalendar](mapicalendar#constructor_2)(string, string, string, DateTime, DateTime, MapiElectronicAddress, MapiRecipientCollection) | Initialisiert eine neue Instanz von[`MapiCalendar`](../mapicalendar) Klasse. |
| [MapiCalendar](mapicalendar#constructor_3)(string, string, string, DateTime, DateTime, string, MapiRecipientCollection) | Initialisiert eine neue Instanz von[`MapiCalendar`](../mapicalendar) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AppointmentCounterProposal](../../aspose.email.mapi/mapicalendar/appointmentcounterproposal) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob ein Besprechungsantwortobjekt ein Gegenvorschlag ist. |
| [Attachments](../../aspose.email.mapi/mapicalendar/attachments) { get; } | Ruft die Anlagensammlung ab. |
| [Attendees](../../aspose.email.mapi/mapicalendar/attendees) { get; set; } | Ruft die Teilnehmer ab oder legt sie fest |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Enthält die mit einem Artikel verknüpften Rechnungsinformationen. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Ruft den Nachrichtentext ab. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Ruft die ab[`BodyRtf`](../mapimessageitembase/bodyrtf) der in HTML konvertierten Nachricht, falls vorhanden, ansonsten ein leerer String. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Ruft den RTF-formatierten Nachrichtentext ab oder legt ihn fest. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Ruft den Typ des Körpers ab. |
| [BusyStatus](../../aspose.email.mapi/mapicalendar/busystatus) { get; set; } | Ruft den Besetztstatus ab oder setzt ihn |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Enthält Schlüsselwörter oder Kategorien für das Nachrichtenobjekt. |
| [ClientIntent](../../aspose.email.mapi/mapicalendar/clientintent) { get; set; } | Ruft die Aktionen ab, die der Benutzer für dieses Besprechungsobjekt ausgeführt hat, oder legt diese fest. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ruft die Codepage ab. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Enthält die Namen der Firmen, die einem Artikel zugeordnet sind. |
| [EndDate](../../aspose.email.mapi/mapicalendar/enddate) { get; set; } | Ruft das Enddatum und die Uhrzeit des Ereignisses ab oder legt sie fest. Wenn das Datum nicht festgelegt ist, wird der Standardwert fürDateTime wird zurückgegeben. |
| [EndDateTimeZone](../../aspose.email.mapi/mapicalendar/enddatetimezone) { get; set; } | Ruft Zeitzoneninformationen ab oder legt diese fest, die die Zeitzone der EndDate-Eigenschaft angeben |
| [IsAllDay](../../aspose.email.mapi/mapicalendar/isallday) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob es sich bei dem Ereignis um ein ganztägiges Ereignis handelt |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Die Artikel-ID, verwendet mit einem Server |
| [KeyWords](../../aspose.email.mapi/mapicalendar/keywords) { get; set; } | Holt oder setzt die Kategorien des Kalenderobjekts |
| [Location](../../aspose.email.mapi/mapicalendar/location) { get; set; } | Ruft den Ort des Ereignisses ab oder legt ihn fest |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Ruft eine Zeichenfolge mit Berücksichtigung der Groß-/Kleinschreibung ab, die die vom Absender definierte Nachrichtenklasse identifiziert, z. B. IPM.Hinweis. Die Nachrichtenklasse gibt den Typ, Zweck oder Inhalt der Nachricht an. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Enthält die Kilometerinformationen, die einem Artikel zugeordnet sind. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Ruft die benannten Eigenschaften der Nachricht ab. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Ruft die benannte Eigenschaftszuordnung ab. |
| [Organizer](../../aspose.email.mapi/mapicalendar/organizer) { get; set; } | Ruft den Organisator ab oder legt ihn fest. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ruft die Sammlung von Eigenschaften ab. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Ruft den Eigenschaftsstream ab. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Ruft die Empfänger der Nachricht ab. |
| [Recurrence](../../aspose.email.mapi/mapicalendar/recurrence) { get; set; } | Ruft die Wiederholungseigenschaften ab oder legt sie fest |
| [ReminderDelta](../../aspose.email.mapi/mapicalendar/reminderdelta) { get; set; } | Ruft das Intervall in Minuten zwischen dem Zeitpunkt, zu dem die Erinnerung zum ersten Mal überfällig wird, und der Startzeit des Kalenderobjekts ab oder legt es fest. |
| [ReminderFileParameter](../../aspose.email.mapi/mapicalendar/reminderfileparameter) { get; set; } | Gibt den vollständigen Pfad des Tons an, den ein Client abspielen SOLLTE, wenn die Erinnerung überfällig wird. |
| [ReminderSet](../../aspose.email.mapi/mapicalendar/reminderset) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob eine Erinnerung für das Objekt festgelegt ist |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Ruft die Empfindlichkeit ab. |
| [Sequence](../../aspose.email.mapi/mapicalendar/sequence) { get; set; } | Ruft die Sequenznummer ab oder setzt sie |
| [StartDate](../../aspose.email.mapi/mapicalendar/startdate) { get; set; } | Ruft das Startdatum und die Uhrzeit des Ereignisses ab oder legt sie fest. Wenn das Datum nicht festgelegt ist, Standardwert fürDateTime wird zurückgegeben. |
| [StartDateTimeZone](../../aspose.email.mapi/mapicalendar/startdatetimezone) { get; set; } | Ruft Zeitzoneninformationen ab oder legt diese fest, die die Zeitzone der StartDate-Eigenschaft angeben |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Ruft den Betreff der Nachricht ab oder legt ihn fest. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Ruft ein Betreff-Präfix ab, das normalerweise eine Aktion für eine Nachricht angibt, z. B. "FW: " zum Weiterleiten. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Ruft die Unterspeicher ab. |
| [Uid](../../aspose.email.mapi/mapicalendar/uid) { get; set; } | Ruft die eindeutige Kennung ab |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Dispose](../../aspose.email.mapi/mapicalendar/dispose)() | Gibt alle Ressourcen frei. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Ruft MAPI-Eigenschaft nach Eigenschaftsdeskriptor ab. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als booleschen Typ ab. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als DateTime-Typ ab. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Ruft den int32-Wert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als Typ Long (int64) ab. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Ruft den Wert der durch das Tag angegebenen Eigenschaft als Short-Typ ab. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Ruft den Zeichenfolgenwert der durch das Tag angegebenen Eigenschaft ab. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestimmt, ob Zeichenfolgeneigenschaften Unicode-codiert sind oder nicht. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Ermöglicht das korrekte Entfernen von Eigentum aus allen Sammlungen. |
| [Save](../../aspose.email.mapi/mapicalendar/save#save)(Stream) | Speichert das Kalenderobjekt in der Datei im iCalendar-Format unter Verwendung der Standardspeicheroptionen |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_3)(string) | Speichert das Kalenderobjekt in der Datei im iCalendar-Format unter Verwendung der Standardspeicheroptionen |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_1)(Stream, AppointmentSaveFormat) | Speichert das Kalenderobjekt im Stream mit dem angegebenen Format unter Verwendung der Standardspeicheroptionen |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_2)(Stream, MapiCalendarSaveOptions) | Speichert den Kalender mit den angegebenen Speicheroptionen im Stream |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_4)(string, AppointmentSaveFormat) | Speichert das Kalenderobjekt in der Datei mit dem angegebenen Format unter Verwendung der Standardspeicheroptionen |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_5)(string, MapiCalendarSaveOptions) | Speichert das Kalenderobjekt in der Datei mit dem angegebenen Format unter Verwendung der Standardspeicheroptionen |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Legt den Inhalt des Körpers fest. |
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
