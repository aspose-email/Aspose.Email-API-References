---
title: IGmailClientAsync.ImportAppointmentAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously imports an appointment into the specified calendar
type: docs
weight: 330
url: /net/aspose.email.clients.google/igmailclientasync/importappointmentasync/
---
## IGmailClientAsync.ImportAppointmentAsync method

Asynchronously imports an appointment into the specified calendar.

```csharp
public Task<Appointment> ImportAppointmentAsync(string calendarId, Appointment appointment, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | String | The ID of the calendar. |
| appointment | Appointment | The appointment to import. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the imported [`Appointment`](../../../aspose.email.calendar/appointment/).

### See Also

* class [Appointment](../../../aspose.email.calendar/appointment/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


