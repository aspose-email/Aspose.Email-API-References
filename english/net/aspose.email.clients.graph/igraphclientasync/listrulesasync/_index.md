---
title: IGraphClientAsync.ListRulesAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously lists inbox rules
type: docs
weight: 410
url: /net/aspose.email.clients.graph/igraphclientasync/listrulesasync/
---
## IGraphClientAsync.ListRulesAsync method

Asynchronously lists inbox rules.

```csharp
public Task<List<InboxRule>> ListRulesAsync(ODataQueryBuilder queryBuilder = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering rules. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the list of [`InboxRule`](../../../aspose.email.clients.exchange/inboxrule/).

### See Also

* class [InboxRule](../../../aspose.email.clients.exchange/inboxrule/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


