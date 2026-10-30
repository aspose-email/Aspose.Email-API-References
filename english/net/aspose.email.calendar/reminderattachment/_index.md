---
title: Class ReminderAttachment
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.ReminderAttachment class. A file attached to a reminder such as the sound of an audio reminder given either as inline data or as a URI
type: docs
weight: 800
url: /net/aspose.email.calendar/reminderattachment/
---
## ReminderAttachment class

A file attached to a reminder, such as the sound of an audio reminder, given either as inline data or as a URI.

```csharp
public class ReminderAttachment
```

## Constructors

| Name | Description |
| --- | --- |
| [ReminderAttachment](reminderattachment/#constructor)(byte[]) | Initializes a new instance of the `ReminderAttachment` class with inline content. |
| [ReminderAttachment](reminderattachment/#constructor_1)(Uri) | Initializes a new instance of the `ReminderAttachment` class that refers to its content by URI. |

## Properties

| Name | Description |
| --- | --- |
| [BinaryData](../../aspose.email.calendar/reminderattachment/binarydata/) { get; set; } | Gets or sets the content of the attachment, embedded in the calendar. Setting it clears `Uri`. |
| [Uri](../../aspose.email.calendar/reminderattachment/uri/) { get; set; } | Gets or sets the location of the attachment content. Setting it clears `BinaryData`. |

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


