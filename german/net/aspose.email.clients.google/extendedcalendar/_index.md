---
title: ExtendedCalendar
second_title: Aspose.Email für .NET-API-Referenz
description: Ein Satz erweiterter Metadaten z. B. Farben für einen einzelnen Kalender.
type: docs
weight: 15700
url: /de/net/aspose.email.clients.google/extendedcalendar/
---
## ExtendedCalendar class

Ein Satz erweiterter Metadaten, z. B. Farben, für einen einzelnen Kalender.

```csharp
public class ExtendedCalendar : Calendar
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ExtendedCalendar](extendedcalendar#constructor)() | Initialisiert eine neue Instanz der ExtendedCalendar-Klasse. |
| [ExtendedCalendar](extendedcalendar#constructor_1)(string) | Initialisiert eine neue Instanz der ExtendedCalendar-Klasse. |
| [ExtendedCalendar](extendedcalendar#constructor_2)(string, string) | Initialisiert eine neue Instanz der ExtendedCalendar-Klasse. |
| [ExtendedCalendar](extendedcalendar#constructor_3)(string, string, string, string) | Initialisiert eine neue Instanz der ExtendedCalendar-Klasse. |
| [ExtendedCalendar](extendedcalendar#constructor_4)(string, string, string, string, string) | Initialisiert eine neue Instanz der ExtendedCalendar-Klasse. |
| [ExtendedCalendar](extendedcalendar#constructor_5)(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Initialisiert eine neue Instanz der ExtendedCalendar-Klasse. |
| [ExtendedCalendar](extendedcalendar#constructor_6)(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Initialisiert eine neue Instanz der ExtendedCalendar-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [AccessRole](../../aspose.email.clients.google/extendedcalendar/accessrole) { get; } | Die effektive Zugriffsrolle, die der authentifizierte Benutzer für den Kalender hat. Schreibgeschützt. Mögliche Werte sind: |
| virtual [BackgroundColor](../../aspose.email.clients.google/extendedcalendar/backgroundcolor) { get; set; } | Die Hauptfarbe des Kalenders im Format '#0088aa'. Diese Eigenschaft ersetzt die indexbasierte colorId-Eigenschaft. |
| virtual [ColorId](../../aspose.email.clients.google/extendedcalendar/colorid) { get; set; } | Die Farbe des Kalenders. Dies ist eine ID, die auf einen Eintrag im Abschnitt "Kalender" der Farbdefinition verweist (siehe Endpunkt "Farben"). |
| virtual [ConferenceProperties](../../aspose.email.clients.google/calendar/conferenceproperties) { get; } | Ruft Konferenzeigenschaften für diesen Kalender ab. |
| virtual [DefaultReminders](../../aspose.email.clients.google/extendedcalendar/defaultreminders) { get; set; } | Die Standarderinnerungen, die der authentifizierte Benutzer für diesen Kalender hat. |
| virtual [Description](../../aspose.email.clients.google/calendar/description) { get; set; } | Beschreibung des Kalenders. |
| virtual [ETag](../../aspose.email.clients.google/basedataobject/etag) { get; set; } | Ein ETag oder Entity-Tag ist einer von mehreren Mechanismen, die HTTP für die Web-Cache-Validierung bereitstellt und die es einem Client ermöglichen, bedingte Anforderungen zu stellen. Dadurch können Caches effizienter sein und Bandbreite gespart werden, da ein Webserver keine vollständige Antwort senden muss, wenn sich der Inhalt nicht geändert hat. ETags können auch für die optimistische Parallelitätssteuerung verwendet werden, um zu verhindern, dass sich gleichzeitige Aktualisierungen einer Ressource gegenseitig überschreiben. |
| virtual [ForegroundColor](../../aspose.email.clients.google/extendedcalendar/foregroundcolor) { get; set; } | Die Vordergrundfarbe des Kalenders im Format '#ffffff'. Diese Eigenschaft ersetzt die indexbasierte colorId-Eigenschaft. |
| virtual [Hidden](../../aspose.email.clients.google/extendedcalendar/hidden) { get; set; } | Ob der Kalender aus der Liste ausgeblendet wurde. Der Standardwert ist „Falsch“. |
| virtual [Id](../../aspose.email.clients.google/basedataobject/id) { get; set; } | Kennung der Ressource. |
| virtual [Kind](../../aspose.email.clients.google/basedataobject/kind) { get; } | Art der Ressource |
| virtual [Location](../../aspose.email.clients.google/calendar/location) { get; set; } | Geografischer Standort des Kalenders als Freitext. |
| virtual [NotificationSettings](../../aspose.email.clients.google/extendedcalendar/notificationsettings) { get; set; } | Die Benachrichtigungen, die der authentifizierte Benutzer für diesen Kalender erhält. |
| virtual [Primary](../../aspose.email.clients.google/extendedcalendar/primary) { get; set; } | Ob der Kalender der primäre Kalender des authentifizierten Benutzers ist. Schreibgeschützt. Der Standardwert ist „Falsch“. |
| virtual [Selected](../../aspose.email.clients.google/extendedcalendar/selected) { get; set; } | Ob der Kalenderinhalt in der Kalender-Benutzeroberfläche angezeigt wird. Der Standardwert ist „Falsch“. |
| virtual [Summary](../../aspose.email.clients.google/calendar/summary) { get; set; } | Titel des Kalenders. |
| virtual [SummaryOverride](../../aspose.email.clients.google/extendedcalendar/summaryoverride) { get; set; } | Die Zusammenfassung, die der authentifizierte Benutzer für diesen Kalender festgelegt hat. |
| virtual [TimeZone](../../aspose.email.clients.google/calendar/timezone) { get; set; } | Die Zeitzone des Kalenders. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.email.clients.google/extendedcalendar/tostring)() | Gibt eine Zeichenfolge zurück, die die Objektinstanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [ExtendedCalendarKind](../../aspose.email.clients.google/extendedcalendar/extendedcalendarkind) | Typ der Ressource „calendar#calendarListEntry“. |
| const [ListKind](../../aspose.email.clients.google/extendedcalendar/listkind) | Typ der Ressourcenliste "calendar#calendarList". |

### Siehe auch

* class [Calendar](../calendar)
* namensraum [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
