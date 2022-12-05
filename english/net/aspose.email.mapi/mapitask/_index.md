---
title: MapiTask
second_title: Aspose.Email for .NET API Reference
description: Represents the Outlook Task object.
type: docs
weight: 18690
url: /net/aspose.email.mapi/mapitask/
---
## MapiTask class

Represents the Outlook Task object.

```csharp
public class MapiTask : MapiMessageItemBase
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiTask](mapitask#constructor)() | Initializes a new instance of the [`MapiTask`](../mapitask) class. |
| [MapiTask](mapitask#constructor_1)(string, string, DateTime, DateTime) | Initializes a new instance of the [`MapiTask`](../mapitask) class. |

## Properties

| Name | Description |
| --- | --- |
| [AcceptanceState](../../aspose.email.mapi/mapitask/acceptancestate) { get; set; } | Gets or sets the acceptance state of the task. |
| [ActualEffort](../../aspose.email.mapi/mapitask/actualeffort) { get; set; } | Gets or sets the number of minutes that the user actually spent working on a task. |
| [Attachments](../../aspose.email.mapi/mapitask/attachments) { get; } | Gets the attachments collection. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contains the billing information associated with an item. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Gets the message text. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Gets the [`BodyRtf`](../mapimessageitembase/bodyrtf) of the message converted to HTML, if present, otherwise an empty string. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Gets or sets the RTF formatted message text. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Gets the type of the body. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contains keywords or categories for the message object. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Gets the code page. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contains the names of the companies that are associated with an item. |
| [DateCompleted](../../aspose.email.mapi/mapitask/datecompleted) { get; set; } | Gets or sets the date when the user completed work on the task. |
| [DueDate](../../aspose.email.mapi/mapitask/duedate) { get; set; } | Gets or sets the date by which the user expects work on the task to be complete. |
| [EstimatedEffort](../../aspose.email.mapi/mapitask/estimatedeffort) { get; set; } | Gets or sets the number of minutes that the user expects to work on a task. |
| [Flags](../../aspose.email.mapi/mapitask/flags) { get; } | Gets the indication flags of the Task object. |
| [History](../../aspose.email.mapi/mapitask/history) { get; set; } | Gets or sets the type of change that was last made to the Task object. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | The item id, uses with a server |
| [LastUpdate](../../aspose.email.mapi/mapitask/lastupdate) { get; set; } | Gets or sets the date and time of the most recent change made to the Task object. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contains the mileage information that is associated with an item. |
| [Mode](../../aspose.email.mapi/mapitask/mode) { get; set; } | Gets or sets the assignment status of the Task object. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Gets the named properties of message. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Gets the named property mapping. |
| [PercentComplete](../../aspose.email.mapi/mapitask/percentcomplete) { get; set; } | Gets or sets the progress the user has made on a task. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Gets the collection of properties. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Gets the property stream. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Gets the recipients of the message. |
| [Recurrence](../../aspose.email.mapi/mapitask/recurrence) { get; set; } | Gets or sets the recurrence properties. |
| [ReminderFileParameter](../../aspose.email.mapi/mapitask/reminderfileparameter) { get; set; } | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [ReminderSet](../../aspose.email.mapi/mapitask/reminderset) { get; set; } | Gets or sets a value indicating whether a reminder is set on the object |
| [ReminderTime](../../aspose.email.mapi/mapitask/remindertime) { get; set; } | Gets or sets the initial signal time for a reminder |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Gets the Sensitivity. |
| [StartDate](../../aspose.email.mapi/mapitask/startdate) { get; set; } | Gets or sets the date on which the user expects work on the task to begin. |
| [State](../../aspose.email.mapi/mapitask/state) { get; set; } | Gets or sets the current assignment state of the Task object. |
| [Status](../../aspose.email.mapi/mapitask/status) { get; set; } | Gets or sets the status of the user's progress on the task. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Gets or sets the subject of the message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Gets the sub storages. |
| [SupportedType](../../aspose.email.mapi/mapimessageitembase/supportedtype) { get; } | Gets the supported item type. |
| [Users](../../aspose.email.mapi/mapitask/users) { get; set; } | Gets or sets information about task users. |

## Methods

| Name | Description |
| --- | --- |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo)(Stream) | Creates an instance of MapiTask from the specified stream. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_2)(string) | Creates an instance of MapiTask from the specified .ics file. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_1)(Stream, bool) | Creates an instance of MapiTask from the specified stream. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_3)(string, bool) | Creates an instance of MapiTask from the specified .ics file. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Gets MAPI property by property descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Gets the value of the property specified by tag as Boolean type. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Gets the value of the property specified by tag as DateTime type. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Gets the int32 value of the property specified by tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Gets the value of the property specified by tag as Long (int64) type. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Gets the value of the property specified by tag as Short type. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Gets the string value of the property specified by tag. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determines if string properties are Unicode encoded or not. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Provides correctly removing property from all collections. |
| [Save](../../aspose.email.mapi/mapitask/save#save)(Stream, TaskSaveFormat) | Saves this [`MapiTask`](../mapitask) to the given stream using specified format. |
| [Save](../../aspose.email.mapi/mapitask/save#save_1)(string, TaskSaveFormat) | Saves this [`MapiTask`](../mapitask) into file using specified format. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Sets the content of the body. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Sets the content of the body. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Gets or sets the RTF formatted message text. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Sets the message flags. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Sets the property. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Sets MAPI property. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Try to get the property data with specified tag key. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Gets the value of the specified property as DateTime type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Gets the value of the specified property as Int32 type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Gets the value of the specified property as Long type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Try to get a property data as string with specified tag. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Try to get a property data as string with specified tag and code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |

### See Also

* class [MapiMessageItemBase](../mapimessageitembase)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
