---
title: FollowUpManager.SetFlag
second_title: Aspose.Email for .NET API Reference
description: FollowUpManager method. Sets the followup flag for a message
type: docs
weight: 130
url: /net/aspose.email.mapi/followupmanager/setflag/
---
## SetFlag(MapiMessageItemBase, string) {#setflag}

Sets the follow-up flag for a message.

```csharp
public static void SetFlag(MapiMessageItemBase message, string flagRequest)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessageItemBase | The [`MapiMessageItemBase`](../../mapimessageitembase/) in which a flag will be set. |
| flagRequest | String | A string indicating the requested action for an e-mail message. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If *flagRequest* is null or empty. |
| ArgumentNullException | If *message* is null. |

### See Also

* class [MapiMessageItemBase](../../mapimessageitembase/)
* class [FollowUpManager](../)
* namespace [Aspose.Email.Mapi](../../followupmanager/)
* assembly [Aspose.Email](../../../)

---

## SetFlag(MapiMessageItemBase, string, DateTime, DateTime) {#setflag_1}

Sets the follow-up flag for a message.

```csharp
public static void SetFlag(MapiMessageItemBase message, string flagRequest, DateTime startDate, 
    DateTime dueDate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessageItemBase | The [`MapiMessageItemBase`](../../mapimessageitembase/) in which a flag will be set. |
| flagRequest | String | A string indicating the requested action for an e-mail message. |
| startDate | DateTime | The start date. |
| dueDate | DateTime | The due date. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If *flagRequest* is null or empty. |
| ArgumentNullException | If *message* is null. |

### See Also

* class [MapiMessageItemBase](../../mapimessageitembase/)
* class [FollowUpManager](../)
* namespace [Aspose.Email.Mapi](../../followupmanager/)
* assembly [Aspose.Email](../../../)


