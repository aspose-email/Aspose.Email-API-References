---
title: ReminderTrigger.ReminderTrigger
second_title: Aspose.Email for .NET API Reference
description: ReminderTrigger constructor. Initializes a new instance of the ReminderTrigger class that triggers at an absolute date and time
type: docs
weight: 10
url: /net/aspose.email.calendar/remindertrigger/remindertrigger/
---
## ReminderTrigger(DateTime) {#constructor_1}

Initializes a new instance of the [`ReminderTrigger`](../) class that triggers at an absolute date and time.

```csharp
public ReminderTrigger(DateTime dateTime)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dateTime | DateTime | The date and time of the trigger. |

### See Also

* class [ReminderTrigger](../)
* namespace [Aspose.Email.Calendar](../../remindertrigger/)
* assembly [Aspose.Email](../../../)

---

## ReminderTrigger(ReminderDuration, ReminderRelated) {#constructor}

Initializes a new instance of the [`ReminderTrigger`](../) class that triggers at a time relative to the event.

```csharp
public ReminderTrigger(ReminderDuration duration, ReminderRelated related)
```

| Parameter | Type | Description |
| --- | --- | --- |
| duration | ReminderDuration | The offset from the start or end of the event; negative for a time before it. |
| related | ReminderRelated | Whether *duration* is measured from the start or from the end of the event. |

### See Also

* class [ReminderDuration](../../reminderduration/)
* enum [ReminderRelated](../../reminderrelated/)
* class [ReminderTrigger](../)
* namespace [Aspose.Email.Calendar](../../remindertrigger/)
* assembly [Aspose.Email](../../../)


