---
title: IGmailClientAsync.CreateCalendarAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously creates a calendar
type: docs
weight: 50
url: /net/aspose.email.clients.google/igmailclientasync/createcalendarasync/
---
## CreateCalendarAsync(Calendar, CancellationToken) {#createcalendarasync}

Asynchronously creates a calendar.

```csharp
public Task<Calendar> CreateCalendarAsync(Calendar calendar, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| calendar | Calendar | The calendar to create. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created [`Calendar`](../../calendar/).

### See Also

* class [Calendar](../../calendar/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)

---

## CreateCalendarAsync(Calendar, bool, CancellationToken) {#createcalendarasync_1}

Asynchronously creates a calendar and optionally an extended calendar.

```csharp
public Task<string> CreateCalendarAsync(Calendar calendar, bool useColorRgbFormat, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| calendar | Calendar | The calendar to create. |
| useColorRgbFormat | Boolean | Whether to use RGB color format for the extended calendar. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the ID of the created calendar.

### See Also

* class [Calendar](../../calendar/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


