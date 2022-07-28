---
title: MapiJournal
second_title: Aspose.Email für .NET-API-Referenz
description: Repräsentiert das Outlook-Journalobjekt.
type: docs
weight: 18420
url: /de/net/aspose.email.mapi/mapijournal/
---
## MapiJournal class

Repräsentiert das Outlook-Journalobjekt.

```csharp
public sealed class MapiJournal : MapiMessageItemBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MapiJournal](mapijournal#constructor)() | Initialisiert eine neue Instanz von[`MapiJournal`](../mapijournal) Klasse. |
| [MapiJournal](mapijournal#constructor_1)(string, string, string, string) | Initialisiert eine neue Instanz von[`MapiJournal`](../mapijournal) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Ruft die Anhänge in der Nachricht ab. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Enthält die mit einem Artikel verknüpften Rechnungsinformationen. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Ruft den Nachrichtentext ab. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Ruft die ab[`BodyRtf`](../mapimessageitembase/bodyrtf) der in HTML konvertierten Nachricht, falls vorhanden, ansonsten ein leerer String. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Ruft den RTF-formatierten Nachrichtentext ab oder legt ihn fest. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Ruft den Typ des Körpers ab. |
| [BriefDescription](../../aspose.email.mapi/mapijournal/briefdescription) { get; set; } | Ruft die Kurzbeschreibung der aufgezeichneten Aktivität ab oder legt sie fest. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Enthält Schlüsselwörter oder Kategorien für das Nachrichtenobjekt. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ruft die Codepage ab. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Enthält die Namen der Firmen, die einem Artikel zugeordnet sind. |
| [Description](../../aspose.email.mapi/mapijournal/description) { get; set; } | Ruft die Beschreibung der aufgezeichneten Aktivität ab oder legt sie fest. |
| [DocumentStatus](../../aspose.email.mapi/mapijournal/documentstatus) { get; set; } | Ruft den Status des Dokuments ab oder legt ihn fest. |
| [Duration](../../aspose.email.mapi/mapijournal/duration) { get; } | Ruft die Dauer der Aktivität ab. |
| [EndTime](../../aspose.email.mapi/mapijournal/endtime) { get; set; } | Ruft die Uhrzeit ab, zu der die Aktivität beendet wurde, oder legt sie fest. |
| [Flags](../../aspose.email.mapi/mapijournal/flags) { get; set; } | Ruft ein Flag ab oder setzt es, das Metadaten über das Journal-Objekt enthält. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Die Artikel-ID, verwendet mit einem Server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Ruft eine Zeichenfolge mit Berücksichtigung der Groß-/Kleinschreibung ab, die die vom Absender definierte Nachrichtenklasse identifiziert, z. B. IPM.Hinweis. Die Nachrichtenklasse gibt den Typ, Zweck oder Inhalt der Nachricht an. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Enthält die Kilometerinformationen, die einem Artikel zugeordnet sind. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Ruft die benannten Eigenschaften der Nachricht ab. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Ruft die benannte Eigenschaftszuordnung ab. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ruft die Sammlung von Eigenschaften ab. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Ruft den Eigenschaftsstream ab. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Ruft die Empfänger der Nachricht ab. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Ruft die Empfindlichkeit ab. |
| [StartTime](../../aspose.email.mapi/mapijournal/starttime) { get; set; } | Ruft die Uhrzeit ab, zu der die Aktivität begonnen hat, oder legt sie fest. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Ruft den Betreff der Nachricht ab oder legt ihn fest. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Ruft ein Betreff-Präfix ab, das normalerweise eine Aktion für eine Nachricht angibt, z. B. "FW: " zum Weiterleiten. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Ruft die Unterspeicher ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
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
| [Save](../../aspose.email.mapi/mapijournal/save#save)(Stream) | Speichert den angegebenen Stream. |
| [Save](../../aspose.email.mapi/mapijournal/save#save_1)(string) | Speichert den angegebenen Dateinamen. |
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
