---
title: Appointment.ToMailMessage
second_title: Aspose.Email for .NET API Reference
description: Appointment method. Creates an email message that carries this appointment as a meeting request update or cancellation
type: docs
weight: 400
url: /net/aspose.email.calendar/appointment/tomailmessage/
---
## ToMailMessage(AppointmentAction, int) {#tomailmessage_2}

Creates an email message that carries this appointment as a meeting request, update or cancellation.

```csharp
public MailMessage ToMailMessage(AppointmentAction action, int seqId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| action | AppointmentAction | Whether the message requests, updates or cancels the meeting. |
| seqId | Int32 | The sequence number (the iCalendar SEQUENCE property): the revision of the event within a sequence of updates. |

### Return Value

A [`MailMessage`](../../../aspose.email/mailmessage/) that carries the event as a text/calendar alternate view.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* enum [AppointmentAction](../../appointmentaction/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## ToMailMessage(AppointmentAction) {#tomailmessage_1}

Creates an email message that carries this appointment as a meeting request, update or cancellation.

```csharp
public MailMessage ToMailMessage(AppointmentAction action)
```

| Parameter | Type | Description |
| --- | --- | --- |
| action | AppointmentAction | Whether the message requests, updates or cancels the meeting. |

### Return Value

A [`MailMessage`](../../../aspose.email/mailmessage/) that carries the event as a text/calendar alternate view.

## Remarks

The sequence number is 0 for a request, 1 for an update and 2 for a cancellation.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* enum [AppointmentAction](../../appointmentaction/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## ToMailMessage() {#tomailmessage}

Creates an email message that carries this appointment as a meeting request.

```csharp
public MailMessage ToMailMessage()
```

### Return Value

A [`MailMessage`](../../../aspose.email/mailmessage/) that carries the event as a text/calendar alternate view.

## Remarks

The METHOD is taken from `MethodType`, or is REQUEST when that is `AppointmentMethodType.None`; the sequence number is 0.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)


