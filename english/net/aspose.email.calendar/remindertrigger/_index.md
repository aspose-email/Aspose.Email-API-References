---
title: Class ReminderTrigger
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.ReminderTrigger class. Defines when a reminder triggers at an absolute date and time or at a time relative to the start or end of the event
type: docs
weight: 860
url: /net/aspose.email.calendar/remindertrigger/
---
## ReminderTrigger class

Defines when a reminder triggers: at an absolute date and time, or at a time relative to the start or end of the event.

```csharp
public class ReminderTrigger
```

## Constructors

| Name | Description |
| --- | --- |
| [ReminderTrigger](remindertrigger/#constructor_1)(DateTime) | Initializes a new instance of the `ReminderTrigger` class that triggers at an absolute date and time. |
| [ReminderTrigger](remindertrigger/#constructor)(ReminderDuration, ReminderRelated) | Initializes a new instance of the `ReminderTrigger` class that triggers at a time relative to the event. |

## Properties

| Name | Description |
| --- | --- |
| [DateTime](../../aspose.email.calendar/remindertrigger/datetime/) { get; set; } | Gets or sets the absolute date and time of the trigger. Setting it clears `Duration`; `DateTime.MinValue` means it is not set. |
| [Duration](../../aspose.email.calendar/remindertrigger/duration/) { get; set; } | Gets or sets the time of the trigger relative to the start or end of the event. Setting it clears `DateTime`. |
| [Related](../../aspose.email.calendar/remindertrigger/related/) { get; set; } | Gets or sets whether `Duration` is measured from the start or from the end of the event. It is not used with an absolute `DateTime`. |

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


