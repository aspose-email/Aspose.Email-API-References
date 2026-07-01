---
title: IGmailClientAsync.UpdateAccessRuleAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously updates an access control rule for a calendar
type: docs
weight: 420
url: /net/aspose.email.clients.google/igmailclientasync/updateaccessruleasync/
---
## IGmailClientAsync.UpdateAccessRuleAsync method

Asynchronously updates an access control rule for a calendar.

```csharp
public Task<AccessControlRule> UpdateAccessRuleAsync(string calendarId, AccessControlRule role, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | String | The ID of the calendar. |
| role | AccessControlRule | The access control rule to update. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the updated [`AccessControlRule`](../../accesscontrolrule/).

### See Also

* class [AccessControlRule](../../accesscontrolrule/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


