---
title: IEWSClient.CopyConversationItems
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Copies the conversation items into the specified target folder
type: docs
weight: 440
url: /net/aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems/
---
## CopyConversationItems(string, string) {#copyconversationitems}

Copies the conversation items into the specified target folder

```csharp
public void CopyConversationItems(string conversationId, string destinationFolderId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | String | Id of conversation to copy |
| destinationFolderId | String | Id of folder into which copy items |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *conversationId* is `null` or `empty` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *destinationFolderId* is `null` or `empty` |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## CopyConversationItems(string, string, string) {#copyconversationitems_1}

Copies the conversation items, which are located in the specified folder, into the specified target folder

```csharp
public void CopyConversationItems(string conversationId, string contextFolderId, 
    string destinationFolderId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | String | Id of conversation to copy |
| contextFolderId | String | Id of folder in which conversation items are located. Note: If it's set to null(or empty), all conversation items will be copied |
| destinationFolderId | String | Id of folder into which copy items |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *conversationId* is `null` or `empty` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *destinationFolderId* is `null` or `empty` |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


