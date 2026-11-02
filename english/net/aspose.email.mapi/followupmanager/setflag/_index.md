---
title: FollowUpManager.SetFlag
second_title: Aspose.Email for .NET API Reference
description: FollowUpManager method. Sets a followup flag on the message
type: docs
weight: 130
url: /net/aspose.email.mapi/followupmanager/setflag/
---
## SetFlag(MapiMessageItemBase, string) {#setflag}

Sets a follow-up flag on the message.

```csharp
public static void SetFlag(MapiMessageItemBase message, string flagRequest)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessageItemBase | The message to flag. |
| flagRequest | String | The requested action that Outlook shows with the flag, for example `Follow up`. |

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

Sets a follow-up flag with a start date and a due date on the message.

```csharp
public static void SetFlag(MapiMessageItemBase message, string flagRequest, DateTime startDate, 
    DateTime dueDate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessageItemBase | The message to flag. |
| flagRequest | String | The requested action that Outlook shows with the flag, for example `Follow up`. |
| startDate | DateTime | The date the follow-up starts. |
| dueDate | DateTime | The date the follow-up is due. |

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


