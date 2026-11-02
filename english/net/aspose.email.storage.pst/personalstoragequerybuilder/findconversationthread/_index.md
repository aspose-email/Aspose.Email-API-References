---
title: PersonalStorageQueryBuilder.FindConversationThread
second_title: Aspose.Email for .NET API Reference
description: PersonalStorageQueryBuilder method. Adds a condition that finds the messages of the same conversation as the specified message
type: docs
weight: 110
url: /net/aspose.email.storage.pst/personalstoragequerybuilder/findconversationthread/
---
## PersonalStorageQueryBuilder.FindConversationThread method

Adds a condition that finds the messages of the same conversation as the specified message.

```csharp
public MailQuery FindConversationThread(MessageInfo relatedMessage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| relatedMessage | MessageInfo | A message of the conversation. |

### Return Value

The query for the conversation, or `null` if *relatedMessage* has no conversation index or topic.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *relatedMessage* is `null`. |

### See Also

* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [MessageInfo](../../messageinfo/)
* class [PersonalStorageQueryBuilder](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstoragequerybuilder/)
* assembly [Aspose.Email](../../../)


