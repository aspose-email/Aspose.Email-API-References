---
title: FollowUpManager.SetFlagForRecipients
second_title: Aspose.Email for .NET API Reference
description: FollowUpManager method. Sets a flag on a draft message that reminds its recipients to follow up
type: docs
weight: 140
url: /net/aspose.email.mapi/followupmanager/setflagforrecipients/
---
## SetFlagForRecipients(MapiMessageItemBase, string) {#setflagforrecipients}

Sets a flag on a draft message that reminds its recipients to follow up.

```csharp
public static void SetFlagForRecipients(MapiMessageItemBase message, string flagRequest)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessageItemBase | The draft message to flag. |
| flagRequest | String | The requested action that recipients see with the flag. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *message* is `null`. |
| ArgumentException | *flagRequest* is `null` or empty. |
| InvalidOperationException | The message is not a draft (it has already been sent). |

### See Also

* class [MapiMessageItemBase](../../mapimessageitembase/)
* class [FollowUpManager](../)
* namespace [Aspose.Email.Mapi](../../followupmanager/)
* assembly [Aspose.Email](../../../)

---

## SetFlagForRecipients(MapiMessageItemBase, string, DateTime) {#setflagforrecipients_1}

Sets a flag with a reminder on a draft message that reminds its recipients to follow up.

```csharp
public static void SetFlagForRecipients(MapiMessageItemBase message, string flagRequest, 
    DateTime reminderTime)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessageItemBase | The draft message to flag. |
| flagRequest | String | The requested action that recipients see with the flag. |
| reminderTime | DateTime | The date and time the recipients are reminded. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *message* is `null`. |
| ArgumentException | *flagRequest* is `null` or empty. |
| InvalidOperationException | The message is not a draft (it has already been sent). |

### See Also

* class [MapiMessageItemBase](../../mapimessageitembase/)
* class [FollowUpManager](../)
* namespace [Aspose.Email.Mapi](../../followupmanager/)
* assembly [Aspose.Email](../../../)


