---
title: IEWSClient.DeleteConversationItems
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Deletes all items of the specified conversation
type: docs
weight: 580
url: /net/aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems/
---
## DeleteConversationItems(string) {#deleteconversationitems}

Deletes all items of the specified conversation

```csharp
public void DeleteConversationItems(string conversationId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | String | Id of conversation to delete |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *conversationId* is `null` or `empty` |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteConversationItems(string, string) {#deleteconversationitems_1}

Deletes the conversation items, which are located in the specified folder

```csharp
public void DeleteConversationItems(string conversationId, string contextFolderId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | String | Id of conversation to delete |
| contextFolderId | String | Id of folder in which delete conversation items. Note: If it's set to null(or empty), all conversation items will be deleted |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *conversationId* is `null` or `empty` |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


