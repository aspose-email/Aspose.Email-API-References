---
title: IGmailClientAsync.ListAppointmentInstancesAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously retrieves all instances of a recurring appointment
type: docs
weight: 350
url: /net/aspose.email.clients.google/igmailclientasync/listappointmentinstancesasync/
---
## IGmailClientAsync.ListAppointmentInstancesAsync method

Asynchronously retrieves all instances of a recurring appointment.

```csharp
public Task<Appointment[]> ListAppointmentInstancesAsync(string calendarId, string appointmentId, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | String | The ID of the calendar. |
| appointmentId | String | The ID of the appointment. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains an array of [`Appointment`](../../../aspose.email.calendar/appointment/).

### See Also

* class [Appointment](../../../aspose.email.calendar/appointment/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


