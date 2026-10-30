---
title: Appointment.CancelAppointment
second_title: Aspose.Email for .NET API Reference
description: Appointment method. Creates a cancellation of this meeting iCalendar METHODCANCEL to send to its attendees
type: docs
weight: 330
url: /net/aspose.email.calendar/appointment/cancelappointment/
---
## CancelAppointment() {#cancelappointment}

Creates a cancellation of this meeting (iCalendar METHOD:CANCEL) to send to its attendees.

```csharp
public AlternateView CancelAppointment()
```

### Return Value

An [`AlternateView`](../../../aspose.email/alternateview/) with the iCalendar data (text/calendar) to add to a [`MailMessage`](../../../aspose.email/mailmessage/).

## Remarks

The cancellation gets sequence number 2. Use the overload with a sequence number to set it explicitly.

### See Also

* class [AlternateView](../../../aspose.email/alternateview/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## CancelAppointment(int) {#cancelappointment_1}

Creates a cancellation of this meeting (iCalendar METHOD:CANCEL) with the specified sequence number.

```csharp
public AlternateView CancelAppointment(int seqId)
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


