---
title: FollowUpManager.GetReactions
second_title: Aspose.Email for .NET API Reference
description: FollowUpManager method. Gets the reactions like heart and so on that users have left on the message
type: docs
weight: 80
url: /net/aspose.email.mapi/followupmanager/getreactions/
---
## FollowUpManager.GetReactions method

Gets the reactions (like, heart and so on) that users have left on the message.

```csharp
public static IList<UserReaction> GetReactions(MapiMessageItemBase message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessageItemBase | The message to read. |

### Return Value

The reactions of the message; an empty list if there are none.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *message* is null. |

### See Also

* class [UserReaction](../../userreaction/)
* class [MapiMessageItemBase](../../mapimessageitembase/)
* class [FollowUpManager](../)
* namespace [Aspose.Email.Mapi](../../followupmanager/)
* assembly [Aspose.Email](../../../)


