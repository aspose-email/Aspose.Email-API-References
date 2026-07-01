---
title: Class FollowUpOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.FollowUpOptions class. Represents configuration options for followup flags reminders categories and voting buttons in Outlook messages. This class encapsulates all the properties needed to set followup behavior on MapiMessage objects through the FollowUpManager class
type: docs
weight: 16600
url: /net/aspose.email.mapi/followupoptions/
---
## FollowUpOptions class

Represents configuration options for follow-up flags, reminders, categories, and voting buttons in Outlook messages. This class encapsulates all the properties needed to set follow-up behavior on [`MapiMessage`](../mapimessage/) objects through the [`FollowUpManager`](../followupmanager/) class.

```csharp
public sealed class FollowUpOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [FollowUpOptions](followupoptions/#constructor)() | Initializes a new instance of the `FollowUpOptions` class. |
| [FollowUpOptions](followupoptions/#constructor_1)(string) | Initializes a new instance of the `FollowUpOptions` class. |
| [FollowUpOptions](followupoptions/#constructor_2)(string, DateTime, DateTime) | Initializes a new instance of the `FollowUpOptions` class. |
| [FollowUpOptions](followupoptions/#constructor_3)(string, DateTime, DateTime, DateTime) | Initializes a new instance of the `FollowUpOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [Categories](../../aspose.email.mapi/followupoptions/categories/) { get; set; } | Gets or sets string that represents list of the categories, separated by semicolons (;). |
| [CodePage](../../aspose.email.mapi/followupoptions/codepage/) { get; set; } | Gets or sets the code page. |
| [DueDate](../../aspose.email.mapi/followupoptions/duedate/) { get; set; } | Gets or sets a date indicating the due date for the flagged message. |
| [FlagRequest](../../aspose.email.mapi/followupoptions/flagrequest/) { get; set; } | Gets or sets a string indicating the requested action for an e-mail message. |
| [IsCompleted](../../aspose.email.mapi/followupoptions/iscompleted/) { get; } | Gets a value indicating whether the Message object was flagged as completed. |
| [RecipientsFlagRequest](../../aspose.email.mapi/followupoptions/recipientsflagrequest/) { get; set; } | Gets or sets a string indicating the requested action for recipients of an e-mail message. |
| [RecipientsReminderTime](../../aspose.email.mapi/followupoptions/recipientsremindertime/) { get; set; } | Gets or sets a date for recipients indicating the date and time at which the reminder should occur. |
| [ReminderTime](../../aspose.email.mapi/followupoptions/remindertime/) { get; set; } | Gets or sets a date indicating the date and time at which the reminder should occur. |
| [StartDate](../../aspose.email.mapi/followupoptions/startdate/) { get; set; } | Gets or sets a date specifying the starting date and time for the flagged message. |
| [VotingButtons](../../aspose.email.mapi/followupoptions/votingbuttons/) { get; set; } | Gets or sets string that represents list of the voting buttons names, separated by semicolons (;). |

## Remarks

Use this class to configure follow-up settings such as flag request text, start date, due date, reminder time, categories, and voting buttons. The [`FlagRequest`](./flagrequest/) property sets the follow-up text, [`StartDate`](./startdate/) and [`DueDate`](./duedate/) define the task timeline, [`Categories`](./categories/) specifies message categories, and [`VotingButtons`](./votingbuttons/) configures voting response options.

## Examples

The following example shows how to use FollowUpOptions to configure follow-up settings for a message.

[C#]

```csharp
// Create follow-up options with flag request
var options = new FollowUpOptions("Follow up on this message")
{
    StartDate = DateTime.Now,
    DueDate = DateTime.Now.AddDays(7),
    ReminderTime = DateTime.Now.AddHours(1),
    Categories = "Important;Work",
    VotingButtons = "Approve;Reject;More Information"
};

// Mark as completed
options.MarkAsCompleted(true);

// Apply options to a MapiMessage
MapiMessage message = MapiMessage.FromFile("message.msg");
FollowUpManager.SetOptions(message, options);

// Save the message with follow-up settings
message.Save("message_with_options.msg", SaveOptions.DefaultMsgUnicode);
```

[Visual Basic]

```csharp
' Create follow-up options with flag request
Dim options As New FollowUpOptions("Follow up on this message") With {
    .StartDate = DateTime.Now,
    .DueDate = DateTime.Now.AddDays(7),
    .ReminderTime = DateTime.Now.AddHours(1),
    .Categories = "Important;Work",
    .VotingButtons = "Approve;Reject;More Information"
}

' Mark as completed
options.MarkAsCompleted(True)

' Apply options to a MapiMessage
Dim message As MapiMessage = MapiMessage.FromFile("message.msg")
FollowUpManager.SetOptions(message, options)

' Save the message with follow-up settings
message.Save("message_with_options.msg", SaveOptions.DefaultMsgUnicode)
```

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


