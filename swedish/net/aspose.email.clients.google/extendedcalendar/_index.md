---
title: ExtendedCalendar
second_title: Aspose.Email för .NET API-referens
description: En uppsättning utökad metadata till exempel en färg för en enda kalender.
type: docs
weight: 15700
url: /sv/net/aspose.email.clients.google/extendedcalendar/
---
## ExtendedCalendar class

En uppsättning utökad metadata, till exempel en färg, för en enda kalender.

```csharp
public class ExtendedCalendar : Calendar
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ExtendedCalendar](extendedcalendar#constructor)() | Initierar en ny instans av klassen ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_1)(string) | Initierar en ny instans av klassen ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_2)(string, string) | Initierar en ny instans av klassen ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_3)(string, string, string, string) | Initierar en ny instans av klassen ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_4)(string, string, string, string, string) | Initierar en ny instans av klassen ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_5)(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Initierar en ny instans av klassen ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_6)(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Initierar en ny instans av klassen ExtendedCalendar. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [AccessRole](../../aspose.email.clients.google/extendedcalendar/accessrole) { get; } | Den effektiva åtkomstrollen som den autentiserade användaren har i kalendern. Skrivskyddad. Möjliga värden är: |
| virtual [BackgroundColor](../../aspose.email.clients.google/extendedcalendar/backgroundcolor) { get; set; } | Kalenderns huvudfärg i formatet '#0088aa'. Den här egenskapen ersätter den indexbaserade egenskapen colorId. |
| virtual [ColorId](../../aspose.email.clients.google/extendedcalendar/colorid) { get; set; } | Färgen på kalendern. Detta är ett ID som hänvisar till en post i avsnittet "kalender" i färgdefinitionen (se slutpunkten för "färger"). |
| virtual [ConferenceProperties](../../aspose.email.clients.google/calendar/conferenceproperties) { get; } | Får konferensegenskaper för den här kalendern. |
| virtual [DefaultReminders](../../aspose.email.clients.google/extendedcalendar/defaultreminders) { get; set; } | Standardpåminnelser som den autentiserade användaren har för denna kalender. |
| virtual [Description](../../aspose.email.clients.google/calendar/description) { get; set; } | Beskrivning av kalendern. |
| virtual [ETag](../../aspose.email.clients.google/basedataobject/etag) { get; set; } | En ETag eller entitetstagg är en av flera mekanismer som HTTP tillhandahåller för webbcache-validering och som tillåter en klient att göra villkorliga förfrågningar. Detta gör att cacher blir mer effektiva och sparar bandbredd, eftersom en webbserver inte behöver skicka ett fullständigt svar om innehållet inte har ändrats. ETaggar kan också användas för optimistisk samtidighetskontroll, som ett sätt att förhindra att samtidiga uppdateringar av en resurs skriver över varandra. |
| virtual [ForegroundColor](../../aspose.email.clients.google/extendedcalendar/foregroundcolor) { get; set; } | Kalenderns förgrundsfärg i formatet '#ffffff'. Den här egenskapen ersätter den indexbaserade egenskapen colorId. |
| virtual [Hidden](../../aspose.email.clients.google/extendedcalendar/hidden) { get; set; } | Om kalendern har gömts från listan. Standard är False. |
| virtual [Id](../../aspose.email.clients.google/basedataobject/id) { get; set; } | Identifierare för resursen. |
| virtual [Kind](../../aspose.email.clients.google/basedataobject/kind) { get; } | Typ av resurs |
| virtual [Location](../../aspose.email.clients.google/calendar/location) { get; set; } | Geografisk plats för kalendern som text i fritt format. |
| virtual [NotificationSettings](../../aspose.email.clients.google/extendedcalendar/notificationsettings) { get; set; } | Aviseringarna som den autentiserade användaren får för denna kalender. |
| virtual [Primary](../../aspose.email.clients.google/extendedcalendar/primary) { get; set; } | Om kalendern är den primära kalendern för den autentiserade användaren. Skrivskyddad. Standard är False. |
| virtual [Selected](../../aspose.email.clients.google/extendedcalendar/selected) { get; set; } | Om kalenderinnehållet visas i kalenderns användargränssnitt. Standard är False. |
| virtual [Summary](../../aspose.email.clients.google/calendar/summary) { get; set; } | Titel på kalendern. |
| virtual [SummaryOverride](../../aspose.email.clients.google/extendedcalendar/summaryoverride) { get; set; } | Sammanfattningen som den autentiserade användaren har angett för den här kalendern. |
| virtual [TimeZone](../../aspose.email.clients.google/calendar/timezone) { get; set; } | Tidszonen för kalendern. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.email.clients.google/extendedcalendar/tostring)() | Returnerar en sträng som representerar objektinstansen. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [ExtendedCalendarKind](../../aspose.email.clients.google/extendedcalendar/extendedcalendarkind) | Typ av resurs "calendar#calendarListEntry". |
| const [ListKind](../../aspose.email.clients.google/extendedcalendar/listkind) | Typ av resurslistan "calendar#calendarList". |

### Se även

* class [Calendar](../calendar)
* namnutrymme [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
