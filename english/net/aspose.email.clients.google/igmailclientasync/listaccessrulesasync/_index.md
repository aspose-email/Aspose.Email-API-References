---
title: IGmailClientAsync.ListAccessRulesAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously retrieves all access control rules for a calendar
type: docs
weight: 340
url: /net/aspose.email.clients.google/igmailclientasync/listaccessrulesasync/
---
## IGmailClientAsync.ListAccessRulesAsync method

Asynchronously retrieves all access control rules for a calendar.

```csharp
public Task<AccessControlRule[]> ListAccessRulesAsync(string calendarId, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | String | The ID of the calendar. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains an array of [`AccessControlRule`](../../accesscontrolrule/).

### See Also

* class [AccessControlRule](../../accesscontrolrule/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


