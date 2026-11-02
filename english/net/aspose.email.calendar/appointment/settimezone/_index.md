---
title: Appointment.SetTimeZone
second_title: Aspose.Email for .NET API Reference
description: Appointment method. Sets both the start and the end time zone of the event
type: docs
weight: 390
url: /net/aspose.email.calendar/appointment/settimezone/
---
## Appointment.SetTimeZone method

Sets both the start and the end time zone of the event.

```csharp
public void SetTimeZone(string tzName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tzName | String | An IANA time zone name, such as `America/New_York`, or a Windows time zone ID, such as `Eastern Standard Time`. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *tzName* is `null`. |
| [AsposeException](../../../aspose.email/asposeexception/) | *tzName* is not a recognized time zone. |

### See Also

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)


