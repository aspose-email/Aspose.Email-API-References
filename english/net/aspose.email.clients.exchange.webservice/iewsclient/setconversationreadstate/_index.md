---
title: IEWSClient.SetConversationReadState
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Set read state of the conversation items to the specified value
type: docs
weight: 1410
url: /net/aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate/
---
## SetConversationReadState(string, bool) {#setconversationreadstate}

Set read state of the conversation items to the specified value

```csharp
public void SetConversationReadState(string conversationId, bool isRead)
```

| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | String | Id of conversation to be changed |
| isRead | Boolean | A flag that enables setting the read state of items in a conversation. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *conversationId* is `null` or `empty` |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## SetConversationReadState(string, string, bool) {#setconversationreadstate_1}

Set read state of the conversation items, which are located in the specified folder, to the specified value

```csharp
public void SetConversationReadState(string conversationId, string contextFolderId, bool isRead)
```

| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | String | Id of conversation to be changed |
| contextFolderId | String | Id of folder in which conversation items are located. Note: If it's set to null(or empty), all conversation items will be copied |
| isRead | Boolean | A flag that enables setting the read state of items in a conversation. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *conversationId* is `null` or `empty` |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


