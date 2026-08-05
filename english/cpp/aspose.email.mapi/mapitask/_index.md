---
title: "Aspose::Email::Mapi::MapiTask class"
linktitle: "MapiTask"
articleTitle: "MapiTask"
second_title: "Aspose.Email for C++"
description: "Represents a MAPI task item."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapitask/
---

## MapiTask class

**Inherits:** Aspose::Email::Mapi::MapiMessageItemBase

Represents a MAPI task item.

This class serves as a wrapper for MapiMessage to simplify the process of handling task information from MAPI properties. It provides a more intuitive interface for accessing and manipulating task data within the MAPI message.

The following example demonstrates how to get a MapiTask object from a MapiMessage .

```csharp
var msg = MapiMessage.Load("task.msg");
 
// Check if the loaded message is a supported task type
if (msg.SupportedType == MapiItemType.Task)
{
 // Convert the MAPI message to a MapiTask object
    var mapiTask = (MapiTask)msg.ToMapiMessageItem();
 
 // Display some task info
    Console.WriteLine(mapiTask.Subject);
    Console.WriteLine(mapiTask.DueDate);
}
```

```vb
Dim msg = MapiMessage.Load("task.msg")
 
' Check if the loaded message is a supported task type
If msg.SupportedType = MapiItemType.Task Then
    ' Convert the MAPI message to a MapiTask object
    Dim mapiTask = DirectCast(msg.ToMapiMessageItem(), MapiTask)
 
 ' Display some task info
    Console.WriteLine(mapiTask.Subject)
    Console.WriteLine(mapiTask.DueDate)
End If
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiTask (3 overloads)](./mapitask/) | Initializes a new instance of the MapiTask class. |

## Methods

| Name | Description |
| --- | --- |
| [ConvertToMapiMessage](./converttomapimessage/) | Converts the task object to mapi message |
| [FromVTodo (4 overloads)](./fromvtodo/) | Creates an instance of MapiTask from the specified stream. |
| [get_AcceptanceState](./get_acceptancestate/) | Gets the acceptance state of the task. |
| [get_ActualEffort](./get_actualeffort/) | Gets the number of minutes that the user actually spent working on a task. |
| [get_Attachments](./get_attachments/) | Gets the attachments collection. |
| [get_DateCompleted](./get_datecompleted/) | Gets the date when the user completed work on the task. |
| [get_DueDate](./get_duedate/) | Gets the date by which the user expects work on the task to be complete. |
| [get_EstimatedEffort](./get_estimatedeffort/) | Gets the number of minutes that the user expects to work on a task. |
| [get_Flags](./get_flags/) | Gets the indication flags of the Task object. |
| [get_History](./get_history/) | Gets the type of change that was last made to the Task object. |
| [get_LastUpdate](./get_lastupdate/) | Gets the date and time of the most recent change made to the Task object. |
| [get_Mode](./get_mode/) | Gets the assignment status of the Task object. |
| [get_PercentComplete](./get_percentcomplete/) | Gets the progress the user has made on a task. |
| [get_Priority](./get_priority/) | Gets the current Priority of the Task object. |
| [get_Recurrence](./get_recurrence/) | Gets the recurrence properties. |
| [get_ReminderFileParameter](./get_reminderfileparameter/) | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [get_ReminderSet](./get_reminderset/) | Gets a value indicating whether a reminder is set on the object |
| [get_ReminderTime](./get_remindertime/) | Gets the initial signal time for a reminder |
| [get_StartDate](./get_startdate/) | Gets the date on which the user expects work on the task to begin. |
| [get_State](./get_state/) | Gets the current assignment state of the Task object. |
| [get_Status](./get_status/) | Gets the status of the user's progress on the task. |
| [get_Users](./get_users/) | Gets information about task users. |
| [GetsFlags](./getsflags/) | Gets the flags. |
| [GetUnderlyingMessage](./getunderlyingmessage/) | Retrieves the underlying MapiMessage object. |
| [Save (2 overloads)](./save/) | Saves this MapiTask to the given stream using specified format. |
| [set_AcceptanceState](./set_acceptancestate/) | Sets the acceptance state of the task. |
| [set_ActualEffort](./set_actualeffort/) | Sets the number of minutes that the user actually spent working on a task. |
| [set_DateCompleted](./set_datecompleted/) | Sets the date when the user completed work on the task. |
| [set_DueDate](./set_duedate/) | Sets the date by which the user expects work on the task to be complete. |
| [set_EstimatedEffort](./set_estimatedeffort/) | Sets the number of minutes that the user expects to work on a task. |
| [set_Flags](./set_flags/) | Gets the indication flags of the Task object. |
| [set_History](./set_history/) | Sets the type of change that was last made to the Task object. |
| [set_LastUpdate](./set_lastupdate/) | Sets the date and time of the most recent change made to the Task object. |
| [set_Mode](./set_mode/) | Sets the assignment status of the Task object. |
| [set_PercentComplete](./set_percentcomplete/) | Sets the progress the user has made on a task. |
| [set_Priority](./set_priority/) | Sets the current Priority of the Task object. |
| [set_Recurrence](./set_recurrence/) | Sets the recurrence properties. |
| [set_ReminderFileParameter](./set_reminderfileparameter/) | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [set_ReminderSet](./set_reminderset/) | Sets a value indicating whether a reminder is set on the object |
| [set_ReminderTime](./set_remindertime/) | Sets the initial signal time for a reminder |
| [set_StartDate](./set_startdate/) | Sets the date on which the user expects work on the task to begin. |
| [set_State](./set_state/) | Sets the current assignment state of the Task object. |
| [set_Status](./set_status/) | Sets the status of the user's progress on the task. |
| [set_Users](./set_users/) | Sets information about task users. |
| [ToIcalendar](./toicalendar/) |  |
| [Aspose::Email::Tools::TaskConverter](./asposeemailtoolstaskconverter/) |  |

