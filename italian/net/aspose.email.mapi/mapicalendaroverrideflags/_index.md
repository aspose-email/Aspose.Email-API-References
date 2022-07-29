---
title: MapiCalendarOverrideFlags
second_title: Aspose.Email per riferimento all'API .NET
description: Specifica quali dati nella struttura MapiCalendarOverrideFlags hanno un valore diverso dalle serie ricorrenti.
type: docs
weight: 18030
url: /it/net/aspose.email.mapi/mapicalendaroverrideflags/
---
## MapiCalendarOverrideFlags enumeration

Specifica quali dati nella struttura MapiCalendarOverrideFlags hanno un valore diverso dalle serie ricorrenti.

```csharp
[Flags]
public enum MapiCalendarOverrideFlags
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Subject | `1` | Indica che sono presenti i campi Subject, SubjectLength e SubjectLength2. |
| MeetingType | `2` | Indica che il campo MeetingType è presente. |
| ReminderDelta | `4` | Indica che il campo ReminderDelta è presente. |
| Reminder | `8` | Indica che il campo ReminderSet è presente. |
| Location | `10` | Indica che sono presenti i campi Location, LocationLength e LocationLength2. |
| BusyStatus | `20` | Indica che il campo BusyStatus è presente. |
| Attachment | `40` | Indica che il campo allegato è presente. |
| Subtype | `80` | Indica che il campo Sottotipo è presente. |
| AppointmentColor | `100` | Riservato per uso futuro e NON DEVE essere impostato. |
| ExceptionalBody | `200` | Indica che l'oggetto Exception Embedded Message ha la proprietà PidTagRtfCompressed impostata su di esso. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Mapi](../../aspose.email.mapi)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->