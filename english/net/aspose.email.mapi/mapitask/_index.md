---
title: Class MapiTask
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiTask class. Represents a MAPI task item
type: docs
weight: 17510
url: /net/aspose.email.mapi/mapitask/
---
## MapiTask class

Represents a MAPI task item.

```csharp
public class MapiTask : MapiMessageItemBase
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiTask](mapitask/#constructor)() | Initializes a new instance of the `MapiTask` class. |
| [MapiTask](mapitask/#constructor_1)(string, string, DateTime, DateTime) | Initializes a new instance of the `MapiTask` class with a subject, a body and dates. |

## Properties

| Name | Description |
| --- | --- |
| [AcceptanceState](../../aspose.email.mapi/mapitask/acceptancestate/) { get; set; } | Gets or sets whether the assignee has accepted or rejected the task. |
| [ActualEffort](../../aspose.email.mapi/mapitask/actualeffort/) { get; set; } | Gets or sets the time actually spent on the task, in minutes. |
| [Attachments](../../aspose.email.mapi/mapitask/attachments/) { get; } | Gets the attachments of the task. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing/) { get; set; } | Gets or sets the billing information of the item. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body/) { get; set; } | Gets or sets the plain-text body of the item. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml/) { get; } | Gets the body of the item as HTML, converted from [`BodyRtf`](../mapimessageitembase/bodyrtf/); an empty string when there is no RTF body. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf/) { get; set; } | Gets or sets the body of the item in RTF format. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype/) { get; } | Gets the format of the body: plain text, HTML or RTF. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories/) { get; set; } | Gets or sets the categories of the item. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page of the ANSI strings of the object. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies/) { get; set; } | Gets or sets the names of the companies associated with the item. |
| [DateCompleted](../../aspose.email.mapi/mapitask/datecompleted/) { get; set; } | Gets or sets the date the work on the task was completed. |
| [DueDate](../../aspose.email.mapi/mapitask/duedate/) { get; set; } | Gets or sets the date the task is due. |
| [EstimatedEffort](../../aspose.email.mapi/mapitask/estimatedeffort/) { get; set; } | Gets or sets the expected time of work on the task, in minutes. |
| [Flags](../../aspose.email.mapi/mapitask/flags/) { get; } | Gets the flags of the task, such as complete or recurring. |
| [History](../../aspose.email.mapi/mapitask/history/) { get; set; } | Gets or sets the last change made to the task. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid/) { get; } | Gets the identifier of the item on the mail server, for items obtained from a server; `null` otherwise. |
| [LastUpdate](../../aspose.email.mapi/mapitask/lastupdate/) { get; set; } | Gets or sets the date and time of the last change made to the task. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass/) { get; set; } | Gets or sets the message class of the item, such as `IPM.Note` for an e-mail message. The class determines the type of the item. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage/) { get; set; } | Gets or sets the mileage information of the item. |
| [Mode](../../aspose.email.mapi/mapitask/mode/) { get; set; } | Gets or sets the assignment status of the task. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties/) { get; } | Gets the named properties of the item. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping/) { get; } | Gets the mapping between the named properties and the tags they are stored under. |
| [PercentComplete](../../aspose.email.mapi/mapitask/percentcomplete/) { get; set; } | Gets or sets the progress of the task, from 0 to 100 percent. |
| [Priority](../../aspose.email.mapi/mapitask/priority/) { get; set; } | Gets or sets the priority of the task. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets all properties of the object. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream/) { get; } | Gets the property stream of the item. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients/) { get; set; } | Gets or sets the recipients of the item. |
| [Recurrence](../../aspose.email.mapi/mapitask/recurrence/) { get; set; } | Gets or sets the recurrence of the task; `null` for a single task. |
| [ReminderFileParameter](../../aspose.email.mapi/mapitask/reminderfileparameter/) { get; set; } | Gets or sets the full path of the sound file that is played when the reminder is due. |
| [ReminderSet](../../aspose.email.mapi/mapitask/reminderset/) { get; set; } | Gets or sets a value indicating whether a reminder is set. |
| [ReminderTime](../../aspose.email.mapi/mapitask/remindertime/) { get; set; } | Gets or sets the date and time of the reminder. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity/) { get; set; } | Gets or sets the sensitivity of the item: normal, personal, private or confidential. |
| [StartDate](../../aspose.email.mapi/mapitask/startdate/) { get; set; } | Gets or sets the date the work on the task starts. |
| [State](../../aspose.email.mapi/mapitask/state/) { get; set; } | Gets or sets the assignment state of the task. |
| [Status](../../aspose.email.mapi/mapitask/status/) { get; set; } | Gets or sets the progress status of the task: not started, in progress, complete and so on. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject/) { get; set; } | Gets or sets the subject of the message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix/) { get; } | Gets the prefix of the subject, such as `RE: ` or `FW: `. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages/) { get; } | Gets the sub-storages of the item. |
| [SupportedType](../../aspose.email.mapi/mapimessageitembase/supportedtype/) { get; } | Gets the type of the item, as determined by its message class. |
| [Users](../../aspose.email.mapi/mapitask/users/) { get; set; } | Gets or sets the people involved in the task: owner, assigner, delegator and so on. |

## Methods

| Name | Description |
| --- | --- |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo/#fromvtodo)(Stream) | Loads a task from a stream that contains an iCalendar VTODO. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo/#fromvtodo_2)(string) | Loads a task from an iCalendar (.ics) file with a VTODO. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo/#fromvtodo_1)(Stream, bool) | Loads a task from a stream that contains an iCalendar VTODO, optionally detecting the encoding. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo/#fromvtodo_3)(string, bool) | Loads a task from an iCalendar (.ics) file with a VTODO, optionally detecting the encoding. |
| static [Load](../../aspose.email.mapi/mapitask/load/#load)(Stream) | Loads a `MapiTask` from the specified stream. |
| static [Load](../../aspose.email.mapi/mapitask/load/#load_1)(string) | Loads a `MapiTask` from the specified file. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose/)() | Releases the resources used by the item. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty/)(PropertyDescriptor) | Gets a MAPI property of the item by its descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of a property as a Boolean. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the value of a property as bytes. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of a property as a date and time. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the value of a property as a 32-bit integer. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of a property as a 64-bit integer. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of a property as a 16-bit integer. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long) | Gets the value of a property as a string. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [GetUnderlyingMessage](../../aspose.email.mapi/mapitask/getunderlyingmessage/)() | Retrieves the underlying MapiMessage object. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines whether the string properties of the object are stored in Unicode. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty/)(long) | Removes a property from the item, including its named-property mapping. |
| [Save](../../aspose.email.mapi/mapitask/save/#save)(Stream) | Saves this `MapiTask` to the given stream. |
| [Save](../../aspose.email.mapi/mapitask/save/#save_2)(string) | Saves this `MapiTask` to the given file. |
| [Save](../../aspose.email.mapi/mapitask/save/#save_1)(Stream, TaskSaveFormat) | Saves the task to a stream in the specified format. Only MSG is supported. |
| [Save](../../aspose.email.mapi/mapitask/save/#save_3)(string, TaskSaveFormat) | Saves the task to a file in the specified format. Only MSG is supported. |
| [SaveAsync](../../aspose.email.mapi/mapitask/saveasync/#saveasync_1)(Stream, CancellationToken) | Saves this `MapiTask` to the given stream asynchronously. The supported save format is MSG. |
| [SaveAsync](../../aspose.email.mapi/mapitask/saveasync/#saveasync_3)(string, CancellationToken) | Saves this `MapiTask` into file asynchronously. The supported save format is MSG. |
| [SaveAsync](../../aspose.email.mapi/mapitask/saveasync/#saveasync)(Stream, TaskSaveFormat, CancellationToken) | Saves this `MapiTask` to the given stream using specified format asynchronously. The supported save format is MSG. |
| [SaveAsync](../../aspose.email.mapi/mapitask/saveasync/#saveasync_2)(string, TaskSaveFormat, CancellationToken) | Saves this `MapiTask` into file using specified format asynchronously. The supported save format is MSG. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType) | Sets the body of the item in the specified format. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType, bool) | Sets the body of the item in the specified format, optionally compressing it. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf/)(string, bool) | Sets the body of the item in RTF format, optionally compressing it. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags/)(MapiMessageFlags) | Sets the flags of the message, such as read or unsent. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(MapiProperty) | Adds the property, or replaces the property with the same tag. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty/)(PropertyDescriptor, object) | Sets the value of a MAPI property of the item. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Gets the value of a property as bytes. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of a property as a date and time, if the property exists. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long) | Gets the value of a property as a string. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string) | Gets the value of a property as a string, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string, int) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |
| static [FromVTodoAsync](../../aspose.email.mapi/mapitask/fromvtodoasync/#fromvtodoasync_1)(Stream, CancellationToken) | Creates an instance of MapiTask from the specified stream asynchronously. |
| static [FromVTodoAsync](../../aspose.email.mapi/mapitask/fromvtodoasync/#fromvtodoasync_3)(string, CancellationToken) | Creates an instance of MapiTask from the specified .ics file asynchronously. |
| static [FromVTodoAsync](../../aspose.email.mapi/mapitask/fromvtodoasync/#fromvtodoasync)(Stream, bool, CancellationToken) | Creates an instance of MapiTask from the specified stream asynchronously. |
| static [FromVTodoAsync](../../aspose.email.mapi/mapitask/fromvtodoasync/#fromvtodoasync_2)(string, bool, CancellationToken) | Creates an instance of MapiTask from the specified .ics file asynchronously. |
| static [LoadAsync](../../aspose.email.mapi/mapitask/loadasync/#loadasync)(Stream, CancellationToken) | Loads a `MapiTask` from the specified stream asynchronously. |
| static [LoadAsync](../../aspose.email.mapi/mapitask/loadasync/#loadasync_1)(string, CancellationToken) | Loads a `MapiTask` from the specified file asynchronously. |

## Remarks

This class serves as a wrapper for [`MapiMessage`](../mapimessage/) to simplify the process of handling task information from MAPI properties. It provides a more intuitive interface for accessing and manipulating task data within the MAPI message.

## Examples

The following example demonstrates how to get a `MapiTask` object from a [`MapiMessage`](../mapimessage/).

[C#]

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

[Visual Basic]

```csharp
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

### See Also

* class [MapiMessageItemBase](../mapimessageitembase/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


