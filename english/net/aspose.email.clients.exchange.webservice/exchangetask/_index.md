---
title: Class ExchangeTask
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.WebService.ExchangeTask class. Represents the exchange task information
type: docs
weight: 2430
url: /net/aspose.email.clients.exchange.webservice/exchangetask/
---
## ExchangeTask class

Represents the exchange task information.

```csharp
public sealed class ExchangeTask : Task
```

## Constructors

| Name | Description |
| --- | --- |
| [ExchangeTask](exchangetask/)() | Initializes a new instance of the `ExchangeTask` class. |

## Properties

| Name | Description |
| --- | --- |
| [ActualWork](../../aspose.email.clients.exchange.webservice/exchangetask/actualwork/) { get; set; } | Gets or sets an actual amount of time that is spent on a task (minutes). |
| [Attachments](../../aspose.email.calendar/task/attachments/) { get; set; } | Gets or sets the files attached to the task. |
| [Attendees](../../aspose.email.calendar/task/attendees/) { get; set; } | Gets or sets the attendees (assignees) of the task. |
| [BillingInformation](../../aspose.email.clients.exchange.webservice/exchangetask/billinginformation/) { get; set; } | Gets or sets a billing information for the task. |
| [Body](../../aspose.email.calendar/task/body/) { get; set; } | Gets or sets the plain-text body of the task. |
| [Companies](../../aspose.email.clients.exchange.webservice/exchangetask/companies/) { get; set; } | Gets or sets a collection of companies that are associated with a task. |
| [CompletionDate](../../aspose.email.clients.exchange.webservice/exchangetask/completiondate/) { get; set; } | Gets or sets the date when the user completed work on the task. |
| [DueDate](../../aspose.email.calendar/task/duedate/) { get; set; } | Gets or sets the date by which the user expects work on the task to be complete. |
| [HtmlBody](../../aspose.email.calendar/task/htmlbody/) { get; set; } | Gets or sets the HTML body of the task. |
| [IsBodyHtml](../../aspose.email.clients.exchange.webservice/exchangetask/isbodyhtml/) { get; set; } | Gets or sets a value indicating whether the task body is html-formatted. |
| [Location](../../aspose.email.calendar/task/location/) { get; set; } | Gets or sets the location of the task. |
| [Method](../../aspose.email.calendar/task/method/) { get; set; } | Gets or sets the iTIP method of the task, such as a request or a publication. |
| [Mileage](../../aspose.email.clients.exchange.webservice/exchangetask/mileage/) { get; set; } | Gets or sets a mileage for a task. |
| [Organizer](../../aspose.email.calendar/task/organizer/) { get; set; } | Gets or sets the organizer of the task. |
| [PercentComplete](../../aspose.email.calendar/task/percentcomplete/) { get; set; } | Gets or sets how much of the task is complete, in percent. |
| [Priority](../../aspose.email.calendar/task/priority/) { get; set; } | Gets or sets the priority of the task. |
| [RecurrencePattern](../../aspose.email.clients.exchange.webservice/exchangetask/recurrencepattern/) { get; set; } | Gets or sets a recurrence information for a recurring task. |
| [RelatedTo](../../aspose.email.calendar/task/relatedto/) { get; set; } | Gets or sets the unique identifier of a related calendar item (the iCalendar RELATED-TO property). |
| [ReminderDate](../../aspose.email.clients.exchange.webservice/exchangetask/reminderdate/) { get; set; } | Gets or sets a task reminder date. |
| [SequenceId](../../aspose.email.calendar/task/sequenceid/) { get; set; } | Gets or sets the revision sequence number of the task (the iCalendar SEQUENCE property). |
| [StartDate](../../aspose.email.calendar/task/startdate/) { get; set; } | Gets or sets the start date of the task. |
| [Status](../../aspose.email.clients.exchange.webservice/exchangetask/status/) { get; set; } | Gets or sets a task status. (2 properties) |
| [Subject](../../aspose.email.calendar/task/subject/) { get; set; } | Gets or sets the subject of the task. |
| [TotalWork](../../aspose.email.clients.exchange.webservice/exchangetask/totalwork/) { get; set; } | Gets or sets a total amount of work that the user expects to work on a task. |
| [UniqueId](../../aspose.email.calendar/task/uniqueid/) { get; set; } | Gets or sets the unique identifier of the task (the iCalendar UID property). |
| [UniqueUri](../../aspose.email.clients.exchange.webservice/exchangetask/uniqueuri/) { get; set; } | Gets or sets an unique uri of the task. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.email.calendar/task/dispose/)() | Releases the resources used by the task, including its attachments. |
| [Request](../../aspose.email.calendar/task/request/)() | Creates a task request to send by email. |
| virtual [Save](../../aspose.email.calendar/task/save/)(Stream) | Saves the task to a stream in iCalendar (ICS) format. |
| virtual [Save](../../aspose.email.calendar/task/save/)(string) | Saves the task to an iCalendar (ICS) file. |
| override [Save](../../aspose.email.clients.exchange.webservice/exchangetask/save/#save_2)(Stream, TaskSaveFormat) | Saves current object to the given stream using specified format. |
| virtual [Save](../../aspose.email.calendar/task/save/)(Stream, TaskSaveOptions) | Saves the task to a stream with the specified options. |
| override [Save](../../aspose.email.clients.exchange.webservice/exchangetask/save/#save_5)(string, TaskSaveFormat) | Saves current object into file using specified format. |
| virtual [Save](../../aspose.email.calendar/task/save/)(string, TaskSaveOptions) | Saves the task to a file with the specified options. |

### See Also

* class [Task](../../aspose.email.calendar/task/)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice/)
* assembly [Aspose.Email](../../)


