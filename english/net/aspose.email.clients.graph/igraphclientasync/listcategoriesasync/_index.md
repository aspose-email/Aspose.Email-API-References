---
title: IGraphClientAsync.ListCategoriesAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously lists Outlook categories
type: docs
weight: 330
url: /net/aspose.email.clients.graph/igraphclientasync/listcategoriesasync/
---
## IGraphClientAsync.ListCategoriesAsync method

Asynchronously lists Outlook categories.

```csharp
public Task<List<OutlookCategory>> ListCategoriesAsync(ODataQueryBuilder queryBuilder = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering categories. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the list of [`OutlookCategory`](../../outlookcategory/).

### See Also

* class [OutlookCategory](../../outlookcategory/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


