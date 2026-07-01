---
title: Class FollowUpManager
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.FollowUpManager class. Provides methods for managing Outlook followup flags categories and voting options on MAPI messages. This static class enables setting and removing followup flags managing categories keywords setting due dates and reminders and configuring voting buttons on MapiMessageItemBase objects
type: docs
weight: 16590
url: /net/aspose.email.mapi/followupmanager/
---
## FollowUpManager class

Provides methods for managing Outlook follow-up flags, categories, and voting options on MAPI messages. This static class enables setting and removing follow-up flags, managing categories (keywords), setting due dates and reminders, and configuring voting buttons on [`MapiMessageItemBase`](../mapimessageitembase/) objects.

```csharp
public static class FollowUpManager
```

## Methods

| Name | Description |
| --- | --- |
| static [AddCategory](../../aspose.email.mapi/followupmanager/addcategory/)(MapiMessageItemBase, string) | Adds the category for a message. |
| static [AddVotingButton](../../aspose.email.mapi/followupmanager/addvotingbutton/)(MapiMessageItemBase, string) | Adds the voting button. |
| static [ClearCategories](../../aspose.email.mapi/followupmanager/clearcategories/)(MapiMessageItemBase) | Clears the categories. |
| static [ClearFlag](../../aspose.email.mapi/followupmanager/clearflag/)(MapiMessageItemBase) | Clears the follow-up flag and reminder. |
| static [ClearVotingButtons](../../aspose.email.mapi/followupmanager/clearvotingbuttons/)(MapiMessageItemBase) | Deletes the voting buttons. |
| static [GetCategories](../../aspose.email.mapi/followupmanager/getcategories/)(MapiMessageItemBase) | Get the available message categories. |
| static [GetOptions](../../aspose.email.mapi/followupmanager/getoptions/)(MapiMessageItemBase) | Gets the follow-up options of a message. |
| static [GetReactions](../../aspose.email.mapi/followupmanager/getreactions/)(MapiMessageItemBase) | Get the available message reactions. |
| static [GetVotingButtons](../../aspose.email.mapi/followupmanager/getvotingbuttons/)(MapiMessageItemBase) | Get the available message voting buttons. |
| static [MarkAsCompleted](../../aspose.email.mapi/followupmanager/markascompleted/)(MapiMessageItemBase) | Marks the flagged message as completed. |
| static [RemoveCategory](../../aspose.email.mapi/followupmanager/removecategory/)(MapiMessageItemBase, string) | Removes the category. |
| static [RemoveVotingButton](../../aspose.email.mapi/followupmanager/removevotingbutton/)(MapiMessageItemBase, string) | Removes the voting button. |
| static [SetFlag](../../aspose.email.mapi/followupmanager/setflag/#setflag)(MapiMessageItemBase, string) | Sets the follow-up flag for a message. |
| static [SetFlag](../../aspose.email.mapi/followupmanager/setflag/#setflag_1)(MapiMessageItemBase, string, DateTime, DateTime) | Sets the follow-up flag for a message. |
| static [SetFlagForRecipients](../../aspose.email.mapi/followupmanager/setflagforrecipients/#setflagforrecipients)(MapiMessageItemBase, string) | Sets the flag for a draft message to remind recipients to follow-up. |
| static [SetFlagForRecipients](../../aspose.email.mapi/followupmanager/setflagforrecipients/#setflagforrecipients_1)(MapiMessageItemBase, string, DateTime) | Sets the flag for a draft message to remind recipients to follow-up. |
| static [SetOptions](../../aspose.email.mapi/followupmanager/setoptions/)(MapiMessageItemBase, FollowUpOptions) | Sets the additional follow-up options for a message. |

## Remarks

Use [`SetFlag`](./setflag/) to add follow-up flags to messages, String) and [`RemoveCategory`](./removecategory/) to manage message categories, !:MarkAsComplete to mark flagged messages as completed, and [`SetOptions`](./setoptions/) to configure multiple follow-up properties at once. The class works with Outlook-specific MAPI properties and is designed for use with [`MapiMessage`](../mapimessage/) and related message types.

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


