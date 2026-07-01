---
title: IGmailClientAsync.CreateAccessRuleAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously creates an access control rule for a calendar
type: docs
weight: 30
url: /net/aspose.email.clients.google/igmailclientasync/createaccessruleasync/
---
## IGmailClientAsync.CreateAccessRuleAsync method

Asynchronously creates an access control rule for a calendar.

```csharp
public Task<AccessControlRule> CreateAccessRuleAsync(string calendarId, AccessControlRule role, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | String | The ID of the calendar. |
| role | AccessControlRule | The access control rule to create. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created [`AccessControlRule`](../../accesscontrolrule/).

### See Also

* class [AccessControlRule](../../accesscontrolrule/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


