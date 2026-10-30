---
title: Appointment.UpdateAppointment
second_title: Aspose.Email for .NET API Reference
description: Appointment method. Creates an update of this meeting to send to its attendees
type: docs
weight: 420
url: /net/aspose.email.calendar/appointment/updateappointment/
---
## UpdateAppointment() {#updateappointment}

Creates an update of this meeting to send to its attendees.

```csharp
public AlternateView UpdateAppointment()
```

### Return Value

An [`AlternateView`](../../../aspose.email/alternateview/) with the iCalendar data (text/calendar) to add to a [`MailMessage`](../../../aspose.email/mailmessage/).

## Remarks

The update gets sequence number 1. Use the overload with a sequence number to set it explicitly.

### See Also

* class [AlternateView](../../../aspose.email/alternateview/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## UpdateAppointment(int) {#updateappointment_1}

Creates an update of this meeting with the specified sequence number.

```csharp
public AlternateView UpdateAppointment(int seqId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| seqId | Int32 | The sequence number to write (the iCalendar SEQUENCE property). |

### Return Value

An [`AlternateView`](../../../aspose.email/alternateview/) with the iCalendar data (text/calendar) to add to a [`MailMessage`](../../../aspose.email/mailmessage/).

### See Also

* class [AlternateView](../../../aspose.email/alternateview/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)


