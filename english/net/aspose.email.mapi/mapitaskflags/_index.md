---
title: Enum MapiTaskFlags
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiTaskFlags enum. Defines the flags of a task. The values can be combined
type: docs
weight: 17540
url: /net/aspose.email.mapi/mapitaskflags/
---
## MapiTaskFlags enumeration

Defines the flags of a task. The values can be combined.

```csharp
[Flags]
public enum MapiTaskFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Complete | `1` | The task is complete. |
| Accepted | `2` | The assignee has replied to the task request. |
| Updates | `4` | The assignee is asked to send an update when the task changes. |
| Recurring | `8` | The task has a recurrence. |
| StatusOnComplete | `10` | The assignee is asked to send a status report when the task is complete. |
| DeadOccurrence | `20` | No more occurrences of the recurring task are to be generated. |
| ResetReminder | `40` | The future occurrences of the recurring task need reminders. |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


