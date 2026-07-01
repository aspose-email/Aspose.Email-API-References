---
title: IGmailClientAsync.CreateAppointmentAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously creates an appointment in the specified calendar
type: docs
weight: 40
url: /net/aspose.email.clients.google/igmailclientasync/createappointmentasync/
---
## IGmailClientAsync.CreateAppointmentAsync method

Asynchronously creates an appointment in the specified calendar.

```csharp
public Task<Appointment> CreateAppointmentAsync(string calendarId, Appointment appointment, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | String | The ID of the calendar. |
| appointment | Appointment | The appointment to create. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created [`Appointment`](../../../aspose.email.calendar/appointment/).

### See Also

* class [Appointment](../../../aspose.email.calendar/appointment/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


