---
title: FollowUpManager.SetFlagForRecipients
second_title: Aspose.Email for .NET API Reference
description: FollowUpManager method. Sets the flag for a draft message to remind recipients to followup
type: docs
weight: 130
url: /net/aspose.email.mapi/followupmanager/setflagforrecipients/
---
## SetFlagForRecipients(MapiMessageItemBase, string) {#setflagforrecipients}

Sets the flag for a draft message to remind recipients to follow-up.

```csharp
public static void SetFlagForRecipients(MapiMessageItemBase message, string flagRequest)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessageItemBase | The [`MapiMessageItemBase`](../../mapimessageitembase/) in which a flag will be set. |
| flagRequest | String | A string indicating the requested action action for recipients of an e-mail message. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *message* is null. |
| ArgumentException | If *flagRequest* is null or empty. |
| InvalidOperationException | If message is not set on a draft mode. |

### See Also

* class [MapiMessageItemBase](../../mapimessageitembase/)
* class [FollowUpManager](../)
* namespace [Aspose.Email.Mapi](../../followupmanager/)
* assembly [Aspose.Email](../../../)

---

## SetFlagForRecipients(MapiMessageItemBase, string, DateTime) {#setflagforrecipients_1}

Sets the flag for a draft message to remind recipients to follow-up.

```csharp
public static void SetFlagForRecipients(MapiMessageItemBase message, string flagRequest, 
    DateTime reminderTime)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessageItemBase | The [`MapiMessageItemBase`](../../mapimessageitembase/) in which a flag will be set. |
| flagRequest | String | A string indicating the requested action action for recipients of an e-mail message. |
| reminderTime | DateTime | A date indicating the date and time at which the reminder should occur. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *message* is null. |
| ArgumentException | If *flagRequest* is null or empty. |
| InvalidOperationException | If message is not set on a draft mode. |

### See Also

* class [MapiMessageItemBase](../../mapimessageitembase/)
* class [FollowUpManager](../)
* namespace [Aspose.Email.Mapi](../../followupmanager/)
* assembly [Aspose.Email](../../../)


