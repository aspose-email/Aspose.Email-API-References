---
title: MapiTask
second_title: Aspose.Email für .NET-API-Referenz
description: Repräsentiert das Outlook-Aufgabenobjekt.
type: docs
weight: 18670
url: /de/net/aspose.email.mapi/mapitask/
---
## MapiTask class

Repräsentiert das Outlook-Aufgabenobjekt.

```csharp
public class MapiTask : MapiMessageItemBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MapiTask](mapitask#constructor)() | Initialisiert eine neue Instanz von[`MapiTask`](../mapitask) Klasse. |
| [MapiTask](mapitask#constructor_1)(string, string, DateTime, DateTime) | Initialisiert eine neue Instanz von[`MapiTask`](../mapitask) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AcceptanceState](../../aspose.email.mapi/mapitask/acceptancestate) { get; set; } | Ruft den Akzeptanzstatus der Aufgabe ab oder legt ihn fest. |
| [ActualEffort](../../aspose.email.mapi/mapitask/actualeffort) { get; set; } | Ruft die Anzahl der Minuten ab oder legt sie fest, die der Benutzer tatsächlich mit der Arbeit an einer Aufgabe verbracht hat. |
| [Attachments](../../aspose.email.mapi/mapitask/attachments) { get; } | Ruft die Anhängesammlung ab. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Enthält die mit einem Artikel verknüpften Rechnungsinformationen. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Ruft den Nachrichtentext ab. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Ruft die ab[`BodyRtf`](../mapimessageitembase/bodyrtf) der in HTML konvertierten Nachricht, falls vorhanden, ansonsten ein leerer String. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Ruft den RTF-formatierten Nachrichtentext ab oder legt ihn fest. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Ruft den Typ des Körpers ab. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Enthält Schlüsselwörter oder Kategorien für das Nachrichtenobjekt. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ruft die Codepage ab. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Enthält die Namen der Firmen, die einem Artikel zugeordnet sind. |
| [DateCompleted](../../aspose.email.mapi/mapitask/datecompleted) { get; set; } | Ruft das Datum ab oder legt es fest, an dem der Benutzer die Arbeit an der Aufgabe abgeschlossen hat. |
| [DueDate](../../aspose.email.mapi/mapitask/duedate) { get; set; } | Ruft das Datum ab oder legt es fest, bis zu dem der Benutzer erwartet, dass die Arbeit an der Aufgabe abgeschlossen ist. |
| [EstimatedEffort](../../aspose.email.mapi/mapitask/estimatedeffort) { get; set; } | Ruft die Anzahl der Minuten ab oder legt sie fest, die der Benutzer voraussichtlich an einer Aufgabe arbeiten wird. |
| [Flags](../../aspose.email.mapi/mapitask/flags) { get; } | Ruft die Anzeige-Flags des Task-Objekts ab. |
| [History](../../aspose.email.mapi/mapitask/history) { get; set; } | Ruft den Änderungstyp ab oder legt ihn fest, der zuletzt am Task-Objekt vorgenommen wurde. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Die Artikel-ID, verwendet mit einem Server |
| [LastUpdate](../../aspose.email.mapi/mapitask/lastupdate) { get; set; } | Ruft das Datum und die Uhrzeit der letzten am Task-Objekt vorgenommenen Änderung ab oder legt sie fest. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Ruft eine Zeichenfolge mit Berücksichtigung der Groß-/Kleinschreibung ab, die die vom Absender definierte Nachrichtenklasse identifiziert, z. B. IPM.Hinweis. Die Nachrichtenklasse gibt den Typ, Zweck oder Inhalt der Nachricht an. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Enthält die Kilometerinformationen, die einem Artikel zugeordnet sind. |
| [Mode](../../aspose.email.mapi/mapitask/mode) { get; set; } | Ruft den Zuweisungsstatus des Task-Objekts ab oder setzt ihn. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Ruft die benannten Eigenschaften der Nachricht ab. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Ruft die benannte Eigenschaftszuordnung ab. |
| [PercentComplete](../../aspose.email.mapi/mapitask/percentcomplete) { get; set; } | Ruft den Fortschritt ab, den der Benutzer bei einer Aufgabe gemacht hat, oder legt ihn fest. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ruft die Sammlung von Eigenschaften ab. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Ruft den Eigenschaftsstream ab. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Ruft die Empfänger der Nachricht ab. |
| [Recurrence](../../aspose.email.mapi/mapitask/recurrence) { get; set; } | Ruft die Wiederholungseigenschaften ab oder legt sie fest. |
| [ReminderFileParameter](../../aspose.email.mapi/mapitask/reminderfileparameter) { get; set; } | Gibt den vollständigen Pfad des Tons an, den ein Client abspielen SOLLTE, wenn die Erinnerung überfällig wird. |
| [ReminderSet](../../aspose.email.mapi/mapitask/reminderset) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob eine Erinnerung für das Objekt festgelegt ist |
| [ReminderTime](../../aspose.email.mapi/mapitask/remindertime) { get; set; } | Liest oder setzt die Anfangssignalzeit für eine Erinnerung |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Ruft die Empfindlichkeit ab. |
| [StartDate](../../aspose.email.mapi/mapitask/startdate) { get; set; } | Ruft das Datum ab oder legt es fest, an dem der Benutzer den Beginn der Arbeit an der Aufgabe erwartet. |
| [State](../../aspose.email.mapi/mapitask/state) { get; set; } | Ruft den aktuellen Zuweisungsstatus des Task-Objekts ab oder legt ihn fest. |
| [Status](../../aspose.email.mapi/mapitask/status) { get; set; } | Ruft den Fortschrittsstatus des Benutzers bei der Aufgabe ab oder legt ihn fest. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Ruft den Betreff der Nachricht ab oder legt ihn fest. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Ruft ein Betreff-Präfix ab, das normalerweise eine Aktion für eine Nachricht angibt, z. B. "FW: " zum Weiterleiten. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Ruft die Unterspeicher ab. |
| [Users](../../aspose.email.mapi/mapitask/users) { get; set; } | Ruft Informationen über Aufgabenbenutzer ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo)(Stream) | Erstellt eine Instanz von MapiTask aus dem angegebenen Stream. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_2)(string) | Erstellt eine Instanz von MapiTask aus der angegebenen ICS-Datei. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_1)(Stream, bool) | Erstellt eine Instanz von MapiTask aus dem angegebenen Stream. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_3)(string, bool) | Erstellt eine Instanz von MapiTask aus der angegebenen ICS-Datei. |
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
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestimmt, ob Zeichenfolgeneigenschaften Unicode-codiert sind oder nicht. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Ermöglicht das korrekte Entfernen von Eigentum aus allen Sammlungen. |
| [Save](../../aspose.email.mapi/mapitask/save#save)(Stream, TaskSaveFormat) | Speichert dies[`MapiTask`](../mapitask) zum angegebenen Stream im angegebenen Format. |
| [Save](../../aspose.email.mapi/mapitask/save#save_1)(string, TaskSaveFormat) | Speichert dies[`MapiTask`](../mapitask) in Datei unter Verwendung des angegebenen Formats. |
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
