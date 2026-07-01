---
title: IGmailClientAsync.MoveAppointmentAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously moves an appointment to another calendar
type: docs
weight: 400
url: /net/aspose.email.clients.google/igmailclientasync/moveappointmentasync/
---
## MoveAppointmentAsync(string, string, string, CancellationToken) {#moveappointmentasync_1}

Asynchronously moves an appointment to another calendar.

```csharp
public Task<Appointment> MoveAppointmentAsync(string sourceCalendarId, 
    string destinationCalendarId, string appointmentId, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceCalendarId | String | The ID of the source calendar. |
| destinationCalendarId | String | The ID of the destination calendar. |
| appointmentId | String | The ID of the appointment. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the moved [`Appointment`](../../../aspose.email.calendar/appointment/).

### See Also

* class [Appointment](../../../aspose.email.calendar/appointment/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)

---

## MoveAppointmentAsync(string, string, string, bool, CancellationToken) {#moveappointmentasync}

Asynchronously moves an appointment to another calendar with notification option.

```csharp
public Task<Appointment> MoveAppointmentAsync(string sourceCalendarId, 
    string destinationCalendarId, string appointmentId, bool sendNotifications, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceCalendarId | String | The ID of the source calendar. |
| destinationCalendarId | String | The ID of the destination calendar. |
| appointmentId | String | The ID of the appointment. |
| sendNotifications | Boolean | Whether to send notifications. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the moved [`Appointment`](../../../aspose.email.calendar/appointment/).

### See Also

* class [Appointment](../../../aspose.email.calendar/appointment/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


