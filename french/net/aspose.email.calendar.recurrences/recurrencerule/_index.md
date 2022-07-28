---
title: RecurrenceRule
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente une récurrence ou une règle dexception dans un modèle de récurrence.
type: docs
weight: 770
url: /fr/net/aspose.email.calendar.recurrences/recurrencerule/
---
## RecurrenceRule class

Représente une récurrence ou une règle d'exception dans un modèle de récurrence.

```csharp
public class RecurrenceRule
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [RecurrenceRule](recurrencerule)() | Initialise une nouvelle instance du[`RecurrenceRule`](../recurrencerule) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ByDay](../../aspose.email.calendar.recurrences/recurrencerule/byday) { get; } | Obtient le par jour. |
| [ByHour](../../aspose.email.calendar.recurrences/recurrencerule/byhour) { get; } | Obtient le par heure. |
| [ByMinute](../../aspose.email.calendar.recurrences/recurrencerule/byminute) { get; } | Obtient le par minute. |
| [ByMonth](../../aspose.email.calendar.recurrences/recurrencerule/bymonth) { get; } | Obtient le par mois. |
| [ByMonthDay](../../aspose.email.calendar.recurrences/recurrencerule/bymonthday) { get; } | Obtient le jour par mois. |
| [BySecond](../../aspose.email.calendar.recurrences/recurrencerule/bysecond) { get; } | Obtient le par seconde. |
| [BySetPos](../../aspose.email.calendar.recurrences/recurrencerule/bysetpos) { get; } | Obtient la position par ensemble. |
| [ByWeekNo](../../aspose.email.calendar.recurrences/recurrencerule/byweekno) { get; } | Obtient le numéro de semaine par semaine |
| [ByYearDay](../../aspose.email.calendar.recurrences/recurrencerule/byyearday) { get; } | Obtient le jour de l'année. |
| [Count](../../aspose.email.calendar.recurrences/recurrencerule/count) { get; set; } | Obtient ou définit le nombre. |
| [EndType](../../aspose.email.calendar.recurrences/recurrencerule/endtype) { get; set; } | Obtient ou définit le type de fin. |
| [Frequency](../../aspose.email.calendar.recurrences/recurrencerule/frequency) { get; set; } | Obtient ou définit le type de la règle de récurrence. |
| [FriendlyText](../../aspose.email.calendar.recurrences/recurrencerule/friendlytext) { get; } | Obtient le texte convivial de la règle. |
| [Interval](../../aspose.email.calendar.recurrences/recurrencerule/interval) { get; set; } | Obtient ou définit l'intervalle. |
| [Until](../../aspose.email.calendar.recurrences/recurrencerule/until) { get; set; } | Obtient ou définit jusqu'à. |
| [WeekStart](../../aspose.email.calendar.recurrences/recurrencerule/weekstart) { get; set; } | Obtient ou définit le premier jour de la semaine. |

### Remarques

Correspond à la partie RRULE ou EXRULE dans iCalendar.

Pour construire une règle de récurrence, vous devez généralement :

1. Spécifiez le type de règle dans[`Frequency`](./frequency).

2. Spécifiez comment le modèle de récurrence se termine à l'aide de[`EndType`](./endtype) , [`Count`](./count)ou[`Until`](./until).

3. Spécifiez des valeurs dans une ou plusieurs collections ByXXX.

Notez que si des valeurs de partie de règle ByXXX sont trouvées qui sont au-delà de la portée available (c'est-à-dire, BYMONTHDAY=30 en février), elles sont simplement ignorées.

Informations, non contenues dans la règle, nécessaires pour déterminer les différentes instances de récurrence dont l'heure et les dates de début sont dérivées[`StartDate`](../calendarrecurrence/startdate). Par exemple, "FREQ=YEARLY;BYMONTH=1" ne spécifie pas un jour spécifique dans le mois ou une heure. Cette information serait la même que celle spécifiée pour DTSTART.

Les parties de règle ByXXX modifient la récurrence d'une manière ou d'une autre. Les parties de règle ByXXX pour une période de temps égale ou supérieure à la fréquence réduisent ou limitent généralement le nombre d'occurrences de la récurrence générée. Par exemple, "FREQ=DAILY;BYMONTH=1" réduit le nombre d'instances de récurrence de tous les jours (si la balise BYMONTH n'est pas présente) à tous les jours de janvier. Les parties de règle ByXXX pendant une période de temps inférieure à la fréquence augmentent ou augmentent généralement le nombre d'occurrences de la récurrence. Par exemple, "FREQ=YEARLY;BYMONTH=1,2" augmente le nombre de jours dans l'ensemble de récurrence annuel de 1 (si la balise BYMONTH n'est pas présente) à 2.

Si plusieurs parties de règle ByXXX sont spécifiées, après avoir évalué les parties de règle Frequency et Interval spécifiées, les parties de règle ByXXX sont appliquées à l'ensemble actuel d'occurrences évaluées dans l'ordre suivant :[`ByMonth`](./bymonth) ,[`ByWeekNo`](./byweekno) ,[`ByYearDay`](./byyearday) ,[`ByMonthDay`](./bymonthday) , [`ByDay`](./byday) ,[`ByHour`](./byhour) ,[`ByMinute`](./byminute) ,[`BySecond`](./bysecond) et [`BySetPos`](./bysetpos) ; alors[`Count`](./count) et[`Until`](./until) sont évalués.

### Voir également

* espace de noms [Aspose.Email.Calendar.Recurrences](../../aspose.email.calendar.recurrences)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
