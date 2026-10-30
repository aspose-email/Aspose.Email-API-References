---
title: Class FollowUpOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.FollowUpOptions class. The followup settings of a message flag dates reminder categories and voting buttons
type: docs
weight: 16600
url: /net/aspose.email.mapi/followupoptions/
---
## FollowUpOptions class

The follow-up settings of a message: flag, dates, reminder, categories and voting buttons.

```csharp
public sealed class FollowUpOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [FollowUpOptions](followupoptions/#constructor)() | Initializes a new instance of the `FollowUpOptions` class. |
| [FollowUpOptions](followupoptions/#constructor_1)(string) | Initializes a new instance of the `FollowUpOptions` class with the requested action. |
| [FollowUpOptions](followupoptions/#constructor_2)(string, DateTime, DateTime) | Initializes a new instance of the `FollowUpOptions` class with the requested action and its dates. |
| [FollowUpOptions](followupoptions/#constructor_3)(string, DateTime, DateTime, DateTime) | Initializes a new instance of the `FollowUpOptions` class with the requested action, its dates and a reminder. |

## Properties

| Name | Description |
| --- | --- |
| [Categories](../../aspose.email.mapi/followupoptions/categories/) { get; set; } | Gets or sets the categories, separated by semicolons (`;`). |
| [CodePage](../../aspose.email.mapi/followupoptions/codepage/) { get; set; } | Gets or sets the code page used to encode the strings of the options in an ANSI message. |
| [DueDate](../../aspose.email.mapi/followupoptions/duedate/) { get; set; } | Gets or sets the date the follow-up is due. |
| [FlagRequest](../../aspose.email.mapi/followupoptions/flagrequest/) { get; set; } | Gets or sets the requested action that Outlook shows with the flag, for example `Follow up`. |
| [IsCompleted](../../aspose.email.mapi/followupoptions/iscompleted/) { get; } | Gets a value indicating whether the flag is marked as completed. |
| [RecipientsFlagRequest](../../aspose.email.mapi/followupoptions/recipientsflagrequest/) { get; set; } | Gets or sets the requested action that the recipients of the message see with the flag. |
| [RecipientsReminderTime](../../aspose.email.mapi/followupoptions/recipientsremindertime/) { get; set; } | Gets or sets the date and time the recipients of the message are reminded. |
| [ReminderTime](../../aspose.email.mapi/followupoptions/remindertime/) { get; set; } | Gets or sets the date and time of the reminder. |
| [StartDate](../../aspose.email.mapi/followupoptions/startdate/) { get; set; } | Gets or sets the date the follow-up starts. |
| [VotingButtons](../../aspose.email.mapi/followupoptions/votingbuttons/) { get; set; } | Gets or sets the texts of the voting buttons, separated by semicolons (`;`). |

## Remarks

Fill an instance and pass it to [`SetOptions`](../followupmanager/setoptions/), or read the settings of a message with [`GetOptions`](../followupmanager/getoptions/).

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


