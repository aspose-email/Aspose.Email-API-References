---
title: Appointment.RequestApointment
second_title: Aspose.Email for .NET API Reference
description: Appointment method. Creates a meeting request for this appointment with the specified iCalendar METHOD
type: docs
weight: 360
url: /net/aspose.email.calendar/appointment/requestapointment/
---
## RequestApointment(AppointmentMethodType) {#requestapointment_1}

Creates a meeting request for this appointment with the specified iCalendar METHOD.

```csharp
public AlternateView RequestApointment(AppointmentMethodType methodType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| methodType | AppointmentMethodType | The iCalendar METHOD to use, such as `AppointmentMethodType.Request`. |

### Return Value

An [`AlternateView`](../../../aspose.email/alternateview/) with the iCalendar data (text/calendar) to add to a [`MailMessage`](../../../aspose.email/mailmessage/).

### See Also

* class [AlternateView](../../../aspose.email/alternateview/)
* enum [AppointmentMethodType](../../appointmentmethodtype/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## RequestApointment() {#requestapointment}

Creates a meeting request for this appointment, with the METHOD set in `MethodType` and sequence number 0.

```csharp
public AlternateView RequestApointment()
```

### Return Value

An [`AlternateView`](../../../aspose.email/alternateview/) with the iCalendar data (text/calendar) to add to a [`MailMessage`](../../../aspose.email/mailmessage/).

### See Also

* class [AlternateView](../../../aspose.email/alternateview/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## RequestApointment(int) {#requestapointment_2}

Creates a meeting request for this appointment with the specified sequence number.

```csharp
public AlternateView RequestApointment(int seqId)
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


