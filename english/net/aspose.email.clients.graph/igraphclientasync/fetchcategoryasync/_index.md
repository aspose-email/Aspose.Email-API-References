---
title: IGraphClientAsync.FetchCategoryAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously fetches an Outlook category by its ID
type: docs
weight: 200
url: /net/aspose.email.clients.graph/igraphclientasync/fetchcategoryasync/
---
## IGraphClientAsync.FetchCategoryAsync method

Asynchronously fetches an Outlook category by its ID.

```csharp
public Task<OutlookCategory> FetchCategoryAsync(string itemId, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| itemId | String | The ID of the category to fetch. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the fetched [`OutlookCategory`](../../outlookcategory/).

### See Also

* class [OutlookCategory](../../outlookcategory/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


