---
title: RecurrenceRule
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt eine Wiederholungs- oder Ausnahmeregel in einem Wiederholungsmuster dar.
type: docs
weight: 770
url: /de/net/aspose.email.calendar.recurrences/recurrencerule/
---
## RecurrenceRule class

Stellt eine Wiederholungs- oder Ausnahmeregel in einem Wiederholungsmuster dar.

```csharp
public class RecurrenceRule
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [RecurrenceRule](recurrencerule)() | Initialisiert eine neue Instanz von[`RecurrenceRule`](../recurrencerule) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ByDay](../../aspose.email.calendar.recurrences/recurrencerule/byday) { get; } | Ruft die nach Tag ab. |
| [ByHour](../../aspose.email.calendar.recurrences/recurrencerule/byhour) { get; } | Ruft die Stunden ab. |
| [ByMinute](../../aspose.email.calendar.recurrences/recurrencerule/byminute) { get; } | Ruft minutengenau ab. |
| [ByMonth](../../aspose.email.calendar.recurrences/recurrencerule/bymonth) { get; } | Ruft die nach Monat ab. |
| [ByMonthDay](../../aspose.email.calendar.recurrences/recurrencerule/bymonthday) { get; } | Ruft den Monatstag ab. |
| [BySecond](../../aspose.email.calendar.recurrences/recurrencerule/bysecond) { get; } | Ruft sekündlich ab. |
| [BySetPos](../../aspose.email.calendar.recurrences/recurrencerule/bysetpos) { get; } | Ruft die By-Set-Position ab. |
| [ByWeekNo](../../aspose.email.calendar.recurrences/recurrencerule/byweekno) { get; } | Ruft die Wochennummer ab. |
| [ByYearDay](../../aspose.email.calendar.recurrences/recurrencerule/byyearday) { get; } | Ruft den Tag nach Jahr ab. |
| [Count](../../aspose.email.calendar.recurrences/recurrencerule/count) { get; set; } | Ruft die Anzahl ab oder legt sie fest. |
| [EndType](../../aspose.email.calendar.recurrences/recurrencerule/endtype) { get; set; } | Ruft den Endtyp ab oder legt ihn fest. |
| [Frequency](../../aspose.email.calendar.recurrences/recurrencerule/frequency) { get; set; } | Ruft den Typ der Wiederholungsregel ab oder legt ihn fest. |
| [FriendlyText](../../aspose.email.calendar.recurrences/recurrencerule/friendlytext) { get; } | Ruft benutzerfreundlichen Regeltext ab. |
| [Interval](../../aspose.email.calendar.recurrences/recurrencerule/interval) { get; set; } | Ruft das Intervall ab oder legt es fest. |
| [Until](../../aspose.email.calendar.recurrences/recurrencerule/until) { get; set; } | Holt oder setzt das until. |
| [WeekStart](../../aspose.email.calendar.recurrences/recurrencerule/weekstart) { get; set; } | Ruft den Starttag der Woche ab oder legt ihn fest. |

### Bemerkungen

Entspricht dem RRULE- oder EXRULE-Teil in iCalendar.

Um eine Wiederholungsregel zu erstellen, müssen Sie normalerweise Folgendes tun:

1. Geben Sie den Typ der Regel an in[`Frequency`](./frequency).

2. Geben Sie an, wie das Wiederholungsmuster mit endet[`EndType`](./endtype) , [`Count`](./count)oder[`Until`](./until).

3. Geben Sie Werte in einer oder mehreren ByXXX-Sammlungen an.

Beachten Sie, dass wenn ByXXX-Regelteilwerte gefunden werden, die außerhalb des Bereichs available liegen (dh BYMONTHDAY=30 im Februar), sie einfach ignoriert werden.

Informationen, die nicht in der Regel enthalten sind und zur Bestimmung der verschiedenen Wiederholungsinstanzen erforderlich sind, aus denen Startzeit und Daten abgeleitet werden[`StartDate`](../calendarrecurrence/startdate). Beispiel: "FREQ=YEARLY;BYMONTH=1" gibt keinen bestimmten Tag innerhalb des Monats oder eine Uhrzeit an. Diese Information wäre die gleiche wie die, die für DTSTART angegeben ist.

ByXXX-Regelteile modifizieren die Wiederholung auf irgendeine Weise. ByXXX-Regelteile für einen Zeitraum, der gleich oder größer als die Häufigkeit ist, reduzieren oder begrenzen im Allgemeinen die Anzahl der Vorkommen der erzeugten -Wiederholung. Beispiel: „FREQ=DAILY;BYMONTH=1“ reduziert die Anzahl der Wiederholungsinstanzen von allen Tagen (wenn das Tag BYMONTH nicht vorhanden ist) auf alle Tage im Januar. ByXXX-Regelteile für einen Zeitraum von Mal weniger als die Häufigkeit erhöhen oder erweitern im Allgemeinen die Anzahl der Vorkommen der Wiederholung. Beispiel: „FREQ=YEARLY;BYMONTH=1,2“ erhöht die Anzahl der Tage innerhalb des jährlichen Wiederholungssatzes von 1 (wenn das Tag BYMONTH nicht vorhanden ist) auf 2.

Wenn mehrere ByXXX-Regelteile angegeben sind, werden nach Auswertung der angegebenen Regelteile Frequency und Interval die ByXXX-Regelteile auf den aktuellen Satz ausgewerteter Vorkommen in der folgenden -Reihenfolge angewendet:[`ByMonth`](./bymonth) ,[`ByWeekNo`](./byweekno) ,[`ByYearDay`](./byyearday) ,[`ByMonthDay`](./bymonthday) , [`ByDay`](./byday) ,[`ByHour`](./byhour) ,[`ByMinute`](./byminute) ,[`BySecond`](./bysecond) und [`BySetPos`](./bysetpos) ; dann[`Count`](./count) und[`Until`](./until) werden ausgewertet.

### Siehe auch

* namensraum [Aspose.Email.Calendar.Recurrences](../../aspose.email.calendar.recurrences)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
