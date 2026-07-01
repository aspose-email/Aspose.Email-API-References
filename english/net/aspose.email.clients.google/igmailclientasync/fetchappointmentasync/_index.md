---
title: IGmailClientAsync.FetchAppointmentAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously fetches an appointment by its ID from the specified calendar
type: docs
weight: 190
url: /net/aspose.email.clients.google/igmailclientasync/fetchappointmentasync/
---
## IGmailClientAsync.FetchAppointmentAsync method

Asynchronously fetches an appointment by its ID from the specified calendar.

```csharp
public Task<Appointment> FetchAppointmentAsync(string calendarId, string appointmentId, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | String | The ID of the calendar. |
| appointmentId | String | The ID of the appointment. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the fetched [`Appointment`](../../../aspose.email.calendar/appointment/).

### See Also

* class [Appointment](../../../aspose.email.calendar/appointment/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


