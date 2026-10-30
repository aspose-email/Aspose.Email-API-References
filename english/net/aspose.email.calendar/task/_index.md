---
title: Class Task
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.Task class. Represents a task an iCalendar VTODO component that can be read from iCalendar and saved to iCalendar or Outlook MSG
type: docs
weight: 880
url: /net/aspose.email.calendar/task/
---
## Task class

Represents a task (an iCalendar VTODO component) that can be read from iCalendar and saved to iCalendar or Outlook MSG.

```csharp
public class Task : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Task](task/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.email.calendar/task/attachments/) { get; set; } | Gets or sets the files attached to the task. |
| [Attendees](../../aspose.email.calendar/task/attendees/) { get; set; } | Gets or sets the attendees (assignees) of the task. |
| [Body](../../aspose.email.calendar/task/body/) { get; set; } | Gets or sets the plain-text body of the task. |
| [DueDate](../../aspose.email.calendar/task/duedate/) { get; set; } | Gets or sets the date by which the user expects work on the task to be complete. |
| [HtmlBody](../../aspose.email.calendar/task/htmlbody/) { get; set; } | Gets or sets the HTML body of the task. |
| [Location](../../aspose.email.calendar/task/location/) { get; set; } | Gets or sets the location of the task. |
| [Method](../../aspose.email.calendar/task/method/) { get; set; } | Gets or sets the iTIP method of the task, such as a request or a publication. |
| [Organizer](../../aspose.email.calendar/task/organizer/) { get; set; } | Gets or sets the organizer of the task. |
| [PercentComplete](../../aspose.email.calendar/task/percentcomplete/) { get; set; } | Gets or sets how much of the task is complete, in percent. |
| [Priority](../../aspose.email.calendar/task/priority/) { get; set; } | Gets or sets the priority of the task. |
| [RelatedTo](../../aspose.email.calendar/task/relatedto/) { get; set; } | Gets or sets the unique identifier of a related calendar item (the iCalendar RELATED-TO property). |
| [SequenceId](../../aspose.email.calendar/task/sequenceid/) { get; set; } | Gets or sets the revision sequence number of the task (the iCalendar SEQUENCE property). |
| [StartDate](../../aspose.email.calendar/task/startdate/) { get; set; } | Gets or sets the start date of the task. |
| [Status](../../aspose.email.calendar/task/status/) { get; set; } | Gets or sets the status of the user's progress on the task. |
| [Subject](../../aspose.email.calendar/task/subject/) { get; set; } | Gets or sets the subject of the task. |
| [UniqueId](../../aspose.email.calendar/task/uniqueid/) { get; set; } | Gets or sets the unique identifier of the task (the iCalendar UID property). |

## Methods

| Name | Description |
| --- | --- |
| static [Load](../../aspose.email.calendar/task/load/#load)(Stream) | Loads a task from a stream of iCalendar (ICS) data. |
| static [Load](../../aspose.email.calendar/task/load/#load_1)(string) | Loads a task from an iCalendar (ICS) file. |
| [Dispose](../../aspose.email.calendar/task/dispose/)() | Releases the resources used by the task, including its attachments. |
| [Request](../../aspose.email.calendar/task/request/)() | Creates a task request to send by email. |
| virtual [Save](../../aspose.email.calendar/task/save/#save)(Stream) | Saves the task to a stream in iCalendar (ICS) format. |
| virtual [Save](../../aspose.email.calendar/task/save/#save_3)(string) | Saves the task to an iCalendar (ICS) file. |
| virtual [Save](../../aspose.email.calendar/task/save/#save_1)(Stream, TaskSaveOptions) | Saves the task to a stream with the specified options. |
| virtual [Save](../../aspose.email.calendar/task/save/#save_4)(string, TaskSaveOptions) | Saves the task to a file with the specified options. |

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


