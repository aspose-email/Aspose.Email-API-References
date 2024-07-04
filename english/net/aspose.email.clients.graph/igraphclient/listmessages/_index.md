---
title: IGraphClient.ListMessages
second_title: Aspose.Email for .NET API Reference
description: IGraphClient method. List MessageInfo from the parent folder
type: docs
weight: 420
url: /net/aspose.email.clients.graph/igraphclient/listmessages/
---
## ListMessages(string) {#listmessages_1}

List MessageInfo from the parent folder.

```csharp
public MessageInfoCollection ListMessages(string id)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Parent folder id |

### Return Value

Returns list of MessageInfo of the folder

### See Also

* class [MessageInfoCollection](../../messageinfocollection/)
* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, PageInfo, MailQuery) {#listmessages}

List MessageInfo from the parent folder.

```csharp
public GraphMessagePageInfo ListMessages(string id, PageInfo page, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Parent folder id |
| page | PageInfo | A page info |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query |

### Return Value

Returns list of MessageInfo of the folder

### See Also

* class [GraphMessagePageInfo](../../graphmessagepageinfo/)
* class [PageInfo](../../../aspose.email.clients/pageinfo/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)


