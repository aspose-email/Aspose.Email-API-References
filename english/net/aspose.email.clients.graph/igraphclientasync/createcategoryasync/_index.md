---
title: IGraphClientAsync.CreateCategoryAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously creates a new Outlook category
type: docs
weight: 60
url: /net/aspose.email.clients.graph/igraphclientasync/createcategoryasync/
---
## IGraphClientAsync.CreateCategoryAsync method

Asynchronously creates a new Outlook category.

```csharp
public Task<OutlookCategory> CreateCategoryAsync(string displayName, CategoryPreset preset, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| displayName | String | The display name of the category. |
| preset | CategoryPreset | The category preset. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created [`OutlookCategory`](../../outlookcategory/).

### See Also

* class [OutlookCategory](../../outlookcategory/)
* enum [CategoryPreset](../../categorypreset/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


