---
title: IGmailClientAsync.FetchAccessRuleAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously fetches an access control rule by its ID from a calendar
type: docs
weight: 180
url: /net/aspose.email.clients.google/igmailclientasync/fetchaccessruleasync/
---
## IGmailClientAsync.FetchAccessRuleAsync method

Asynchronously fetches an access control rule by its ID from a calendar.

```csharp
public Task<AccessControlRule> FetchAccessRuleAsync(string calendarId, string roleId, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | String | The ID of the calendar. |
| roleId | String | The ID of the access control rule. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the fetched [`AccessControlRule`](../../accesscontrolrule/).

### See Also

* class [AccessControlRule](../../accesscontrolrule/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


