---
title: IGmailClientAsync.ListCalendarsAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously retrieves the list of calendars for the user
type: docs
weight: 370
url: /net/aspose.email.clients.google/igmailclientasync/listcalendarsasync/
---
## ListCalendarsAsync(CancellationToken) {#listcalendarsasync_1}

Asynchronously retrieves the list of calendars for the user.

```csharp
public Task<ExtendedCalendar[]> ListCalendarsAsync(CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains an array of [`ExtendedCalendar`](../../extendedcalendar/).

### See Also

* class [ExtendedCalendar](../../extendedcalendar/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)

---

## ListCalendarsAsync(AccessRole, bool, CancellationToken) {#listcalendarsasync}

Asynchronously retrieves the list of calendars for the user.

```csharp
public Task<ExtendedCalendar[]> ListCalendarsAsync(AccessRole minAccessRole, bool showHidden, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| minAccessRole | AccessRole | The minimum access role required. |
| showHidden | Boolean | Whether to include hidden calendars. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains an array of [`ExtendedCalendar`](../../extendedcalendar/).

### See Also

* class [ExtendedCalendar](../../extendedcalendar/)
* enum [AccessRole](../../accessrole/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


