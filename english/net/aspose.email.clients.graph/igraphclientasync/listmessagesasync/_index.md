---
title: IGraphClientAsync.ListMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously lists MessageInfo from the parent folder
type: docs
weight: 370
url: /net/aspose.email.clients.graph/igraphclientasync/listmessagesasync/
---
## ListMessagesAsync(string, ODataQueryBuilder, CancellationToken) {#listmessagesasync_1}

Asynchronously lists MessageInfo from the parent folder.

```csharp
public Task<MessageInfoCollection> ListMessagesAsync(string id, 
    ODataQueryBuilder queryBuilder = null, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Parent folder id. |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering messages. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the list of MessageInfo of the folder.

### See Also

* class [MessageInfoCollection](../../messageinfocollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesAsync(string, PageInfo, MailQuery, CancellationToken) {#listmessagesasync}

Asynchronously lists MessageInfo from the parent folder with paging and query.

```csharp
public Task<GraphMessagePageInfo> ListMessagesAsync(string id, PageInfo page, MailQuery query, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Parent folder id. |
| page | PageInfo | A page info. |
| query | MailQuery | MailQuery that represents search query. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the list of MessageInfo of the folder.

### See Also

* class [GraphMessagePageInfo](../../graphmessagepageinfo/)
* class [PageInfo](../../../aspose.email.clients/pageinfo/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


