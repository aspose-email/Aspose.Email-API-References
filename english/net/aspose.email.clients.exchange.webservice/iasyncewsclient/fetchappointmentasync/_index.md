---
title: IAsyncEwsClient.FetchAppointmentAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Fetch the specified appointment from server
type: docs
weight: 220
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchappointmentasync/
---
## IAsyncEwsClient.FetchAppointmentAsync method

Fetch the specified appointment from server.

```csharp
public Task<Appointment> FetchAppointmentAsync(string appointmentUri, string folderUri, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| appointmentUri | String | An uri of appointment to be fetched. |
| folderUri | String | An uri of appointments parent folder. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A fetched [`Appointment`](../../../aspose.email.calendar/appointment/).

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *appointmentUri* is `null` or `empty`. |

### See Also

* class [Appointment](../../../aspose.email.calendar/appointment/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


