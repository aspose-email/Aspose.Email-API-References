---
title: Class MapiCalendar
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendar class. Represents the mapi calendar object
type: docs
weight: 17970
url: /net/aspose.email.mapi/mapicalendar/
---
## MapiCalendar class

Represents the mapi calendar object

```csharp
public sealed class MapiCalendar : MapiMessageItemBase
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendar](mapicalendar/#constructor)() | Initializes a new instance of the `MapiCalendar` class |
| [MapiCalendar](mapicalendar/#constructor_1)(string, string, string, DateTime, DateTime) | Initializes a new instance of the `MapiCalendar` class. |
| [MapiCalendar](mapicalendar/#constructor_2)(string, string, string, DateTime, DateTime, MapiElectronicAddress, MapiRecipientCollection) | Initializes a new instance of the `MapiCalendar` class. |
| [MapiCalendar](mapicalendar/#constructor_3)(string, string, string, DateTime, DateTime, string, MapiRecipientCollection) | Initializes a new instance of the `MapiCalendar` class. |

## Properties

| Name | Description |
| --- | --- |
| [AppointmentCounterProposal](../../aspose.email.mapi/mapicalendar/appointmentcounterproposal/) { get; set; } | Gets or sets a value indicating whether a Meeting Response object is a counter proposal. |
| [Attachments](../../aspose.email.mapi/mapicalendar/attachments/) { get; } | Gets the attachment collection. |
| [Attendees](../../aspose.email.mapi/mapicalendar/attendees/) { get; set; } | Gets or sets the attendees |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing/) { get; set; } | Contains the billing information associated with an item. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body/) { get; set; } | Gets the message text. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml/) { get; } | Gets the [`BodyRtf`](../mapimessageitembase/bodyrtf/) of the message converted to HTML, if present, otherwise an empty string. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf/) { get; set; } | Gets or sets the RTF formatted message text. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype/) { get; } | Gets the type of the body. |
| [BusyStatus](../../aspose.email.mapi/mapicalendar/busystatus/) { get; set; } | Gets or sets the busy status |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories/) { get; set; } | Contains keywords or categories for the message object. |
| [ClientIntent](../../aspose.email.mapi/mapicalendar/clientintent/) { get; set; } | Gets or sets the actions the user has taken on this Meeting object. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies/) { get; set; } | Contains the names of the companies that are associated with an item. |
| [EndDate](../../aspose.email.mapi/mapicalendar/enddate/) { get; set; } | Gets or sets the end date and time of the event. If the date is not set, default value for DateTime is returned. |
| [EndDateTimeZone](../../aspose.email.mapi/mapicalendar/enddatetimezone/) { get; set; } | Gets or sets time zone information that indicates the time zone of the EndDate property |
| [IsAllDay](../../aspose.email.mapi/mapicalendar/isallday/) { get; set; } | Gets or sets a value indicating whether the event is an all-day event |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid/) { get; } | The item id, uses with a server |
| [KeyWords](../../aspose.email.mapi/mapicalendar/keywords/) { get; set; } | Gets or sets the categories of the calendar object |
| [Location](../../aspose.email.mapi/mapicalendar/location/) { get; set; } | Gets or sets the location of the event |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass/) { get; set; } | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage/) { get; set; } | Contains the mileage information that is associated with an item. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties/) { get; } | Gets the named properties of message. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping/) { get; } | Gets the named property mapping. |
| [Organizer](../../aspose.email.mapi/mapicalendar/organizer/) { get; set; } | Gets or sets the organizer. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets the collection of properties. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream/) { get; } | Gets the property stream. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients/) { get; set; } | Gets the recipients of the message. |
| [Recurrence](../../aspose.email.mapi/mapicalendar/recurrence/) { get; set; } | Gets or sets the recurrence properties |
| [ReminderDelta](../../aspose.email.mapi/mapicalendar/reminderdelta/) { get; set; } | Gets or sets the interval, in minutes, between the time at which the reminder first becomes overdue and the start time of the Calendar object |
| [ReminderFileParameter](../../aspose.email.mapi/mapicalendar/reminderfileparameter/) { get; set; } | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [ReminderSet](../../aspose.email.mapi/mapicalendar/reminderset/) { get; set; } | Gets or sets a value indicating whether a reminder is set on the object |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity/) { get; set; } | Gets the Sensitivity. |
| [Sequence](../../aspose.email.mapi/mapicalendar/sequence/) { get; set; } | Gets or sets the sequence number |
| [StartDate](../../aspose.email.mapi/mapicalendar/startdate/) { get; set; } | Gets or sets the start date and time of the event. If the date is not set, default value for DateTime is returned. |
| [StartDateTimeZone](../../aspose.email.mapi/mapicalendar/startdatetimezone/) { get; set; } | Gets or sets time zone information that indicates the time zone of the StartDate property |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject/) { get; set; } | Gets or sets the subject of the message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix/) { get; } | Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages/) { get; } | Gets the sub storages. |
| [SupportedType](../../aspose.email.mapi/mapimessageitembase/supportedtype/) { get; } | Gets the supported item type. |
| [Uid](../../aspose.email.mapi/mapicalendar/uid/) { get; set; } | Gets the unique identifier |

## Methods

| Name | Description |
| --- | --- |
| override [Dispose](../../aspose.email.mapi/mapicalendar/dispose/)() | Releases all resources. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty/)(PropertyDescriptor) | Gets MAPI property by property descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of the property specified by tag as Boolean type. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of the property specified by tag as DateTime type. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the int32 value of the property specified by tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of the property specified by tag as Long (int64) type. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of the property specified by tag as Short type. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long, int) | Gets the string value of the property specified by tag. |
| [GetUnderlyingMessage](../../aspose.email.mapi/mapicalendar/getunderlyingmessage/)() | Retrieves the underlying MapiMessage object. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines if string properties are Unicode encoded or not. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty/)(long) | Provides correctly removing property from all collections. |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save)(Stream) | Saves calendar object to the file with iCalendar format using te default save options |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save_3)(string) | Saves calendar object to the file with iCalendar format using te default save options |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save_1)(Stream, AppointmentSaveFormat) | Saves calendar object to the stream with specified format using te default save options |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save_2)(Stream, MapiCalendarSaveOptions) | Saves calendar to the stream with specified save options |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save_4)(string, AppointmentSaveFormat) | Saves calendar object to the file with specified format using te default save options |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save_5)(string, MapiCalendarSaveOptions) | Saves calendar object to the file with specified format using te default save options |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType) | Sets the content of the body. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType, bool) | Sets the content of the body. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf/)(string, bool) | Gets or sets the RTF formatted message text. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags/)(MapiMessageFlags) | Sets the message flags. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(MapiProperty) | Sets the property. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty/)(PropertyDescriptor, object) | Sets MAPI property. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Try to get the property data with specified tag key. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of the specified property as DateTime type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of the specified property as Int32 type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of the specified property as Long type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long) | Try to get a property data as string with specified tag. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, int) | Try to get a property data as string with specified tag and code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string, int) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |

### See Also

* class [MapiMessageItemBase](../mapimessageitembase/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


