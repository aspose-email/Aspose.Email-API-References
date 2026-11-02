---
title: Class FollowUpManager
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.FollowUpManager class. Manages Outlook followup flags reminders categories and voting buttons of a message
type: docs
weight: 16590
url: /net/aspose.email.mapi/followupmanager/
---
## FollowUpManager class

Manages Outlook follow-up flags, reminders, categories and voting buttons of a message.

```csharp
public static class FollowUpManager
```

## Methods

| Name | Description |
| --- | --- |
| static [AddCategory](../../aspose.email.mapi/followupmanager/addcategory/)(MapiMessageItemBase, string) | Adds a category to the message. |
| static [AddVotingButton](../../aspose.email.mapi/followupmanager/addvotingbutton/)(MapiMessageItemBase, string) | Adds a voting button to the message. |
| static [ClearCategories](../../aspose.email.mapi/followupmanager/clearcategories/)(MapiMessageItemBase) | Removes all categories from the message. |
| static [ClearFlag](../../aspose.email.mapi/followupmanager/clearflag/)(MapiMessageItemBase) | Removes the follow-up flag and the reminder from the message. |
| static [ClearVotingButtons](../../aspose.email.mapi/followupmanager/clearvotingbuttons/)(MapiMessageItemBase) | Removes all voting buttons from the message. |
| static [GetCategories](../../aspose.email.mapi/followupmanager/getcategories/)(MapiMessageItemBase) | Gets the categories of the message. |
| static [GetOptions](../../aspose.email.mapi/followupmanager/getoptions/)(MapiMessageItemBase) | Gets the follow-up flag, reminder, categories and voting buttons of the message. |
| static [GetReactions](../../aspose.email.mapi/followupmanager/getreactions/)(MapiMessageItemBase) | Gets the reactions (like, heart and so on) that users have left on the message. |
| static [GetVotingButtons](../../aspose.email.mapi/followupmanager/getvotingbuttons/)(MapiMessageItemBase) | Gets the voting buttons of the message. |
| static [MarkAsCompleted](../../aspose.email.mapi/followupmanager/markascompleted/)(MapiMessageItemBase) | Marks the follow-up flag of the message as completed. |
| static [RemoveCategory](../../aspose.email.mapi/followupmanager/removecategory/)(MapiMessageItemBase, string) | Removes a category from the message. |
| static [RemoveVotingButton](../../aspose.email.mapi/followupmanager/removevotingbutton/)(MapiMessageItemBase, string) | Removes a voting button from the message. |
| static [SetFlag](../../aspose.email.mapi/followupmanager/setflag/#setflag)(MapiMessageItemBase, string) | Sets a follow-up flag on the message. |
| static [SetFlag](../../aspose.email.mapi/followupmanager/setflag/#setflag_1)(MapiMessageItemBase, string, DateTime, DateTime) | Sets a follow-up flag with a start date and a due date on the message. |
| static [SetFlagForRecipients](../../aspose.email.mapi/followupmanager/setflagforrecipients/#setflagforrecipients)(MapiMessageItemBase, string) | Sets a flag on a draft message that reminds its recipients to follow up. |
| static [SetFlagForRecipients](../../aspose.email.mapi/followupmanager/setflagforrecipients/#setflagforrecipients_1)(MapiMessageItemBase, string, DateTime) | Sets a flag with a reminder on a draft message that reminds its recipients to follow up. |
| static [SetOptions](../../aspose.email.mapi/followupmanager/setoptions/)(MapiMessageItemBase, FollowUpOptions) | Sets the follow-up flag, reminder, categories and voting buttons of the message in one call. |

## Remarks

The methods work with any [`MapiMessageItemBase`](../mapimessageitembase/) — a [`MapiMessage`](../mapimessage/), [`MapiContact`](../mapicontact/), [`MapiTask`](../mapitask/) and so on — and write the same MAPI properties that Outlook uses, so the result is shown in Outlook as if it had been set there.

* follow-up flags: [`SetFlag`](./setflag/), [`SetFlagForRecipients`](./setflagforrecipients/), [`MarkAsCompleted`](./markascompleted/), [`ClearFlag`](./clearflag/); * several settings at once: [`SetOptions`](./setoptions/) and [`GetOptions`](./getoptions/) with [`FollowUpOptions`](../followupoptions/); * categories: [`AddCategory`](./addcategory/), [`RemoveCategory`](./removecategory/), [`GetCategories`](./getcategories/), [`ClearCategories`](./clearcategories/); * voting buttons: [`AddVotingButton`](./addvotingbutton/), [`RemoveVotingButton`](./removevotingbutton/), [`GetVotingButtons`](./getvotingbuttons/), [`ClearVotingButtons`](./clearvotingbuttons/); * reactions: [`GetReactions`](./getreactions/).

## Examples

The following example shows how to use FollowUpManager to add follow-up flags and categories to a MAPI message.

[C#]

```csharp
// Create a MapiMessage from MailMessage
MailMessage mailMessage = MailMessage.Load("message.eml");
MapiMessage mapiMessage = MapiMessage.FromMailMessage(mailMessage);

// Set a follow-up flag
FollowUpManager.SetFlag(mapiMessage, "This is a follow-up message");

// Set categories
FollowUpManager.SetCategory(mapiMessage, "Important");
FollowUpManager.SetCategory(mapiMessage, "Work");

// Mark as complete
FollowUpManager.MarkAsComplete(mapiMessage);

// Save the message with follow-up information
mapiMessage.Save("message_with_flag.msg", SaveOptions.DefaultMsgUnicode);
```

[Visual Basic]

```csharp
' Create a MapiMessage from MailMessage
Dim mailMessage As MailMessage = MailMessage.Load("message.eml")
Dim mapiMessage As MapiMessage = MapiMessage.FromMailMessage(mailMessage)

' Set a follow-up flag
FollowUpManager.SetFlag(mapiMessage, "This is a follow-up message")

' Set categories
FollowUpManager.SetCategory(mapiMessage, "Important")
FollowUpManager.SetCategory(mapiMessage, "Work")

' Mark as complete
FollowUpManager.MarkAsComplete(mapiMessage)

' Save the message with follow-up information
mapiMessage.Save("message_with_flag.msg", SaveOptions.DefaultMsgUnicode)
```

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


