---
title: Class MapiCalendar
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendar class. Represents an Outlook calendar item an appointment or a meeting
type: docs
weight: 16700
url: /net/aspose.email.mapi/mapicalendar/
---
## MapiCalendar class

Represents an Outlook calendar item: an appointment or a meeting.

```csharp
public sealed class MapiCalendar : MapiMessageItemBase
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendar](mapicalendar/#constructor)() | Initializes a new instance of the `MapiCalendar` class. |
| [MapiCalendar](mapicalendar/#constructor_1)(string, string, string, DateTime, DateTime) | Initializes a new instance of the `MapiCalendar` class that represents an appointment. |
| [MapiCalendar](mapicalendar/#constructor_2)(string, string, string, DateTime, DateTime, MapiElectronicAddress, MapiRecipientCollection) | Initializes a new instance of the `MapiCalendar` class that represents a meeting. |
| [MapiCalendar](mapicalendar/#constructor_3)(string, string, string, DateTime, DateTime, string, MapiRecipientCollection) | Initializes a new instance of the `MapiCalendar` class that represents a meeting. |

## Properties

| Name | Description |
| --- | --- |
| [AppointmentCounterProposal](../../aspose.email.mapi/mapicalendar/appointmentcounterproposal/) { get; set; } | Gets or sets a value indicating whether a meeting response proposes a new time for the meeting. |
| [Attachments](../../aspose.email.mapi/mapicalendar/attachments/) { get; } | Gets the attachments of the calendar item. |
| [Attendees](../../aspose.email.mapi/mapicalendar/attendees/) { get; set; } | Gets or sets the attendees of the meeting. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing/) { get; set; } | Gets or sets the billing information of the item. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body/) { get; set; } | Gets or sets the plain-text body of the item. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml/) { get; } | Gets the body of the item as HTML, converted from [`BodyRtf`](../mapimessageitembase/bodyrtf/); an empty string when there is no RTF body. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf/) { get; set; } | Gets or sets the body of the item in RTF format. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype/) { get; } | Gets the format of the body: plain text, HTML or RTF. |
| [BusyStatus](../../aspose.email.mapi/mapicalendar/busystatus/) { get; set; } | Gets or sets how the time of the event is shown in the calendar: free, tentative, busy or out of office. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories/) { get; set; } | Gets or sets the categories of the item. |
| [ClientIntent](../../aspose.email.mapi/mapicalendar/clientintent/) { get; set; } | Gets or sets the actions the user has taken on the meeting. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page of the ANSI strings of the object. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies/) { get; set; } | Gets or sets the names of the companies associated with the item. |
| [EndDate](../../aspose.email.mapi/mapicalendar/enddate/) { get; set; } | Gets or sets the end date and time of the event. Returns `DateTime.MinValue` when the date is not set. |
| [EndDateTimeZone](../../aspose.email.mapi/mapicalendar/enddatetimezone/) { get; set; } | Gets or sets the time zone of [`EndDate`](./enddate/). |
| [IsAllDay](../../aspose.email.mapi/mapicalendar/isallday/) { get; set; } | Gets or sets a value indicating whether the event lasts all day. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid/) { get; } | Gets the identifier of the item on the mail server, for items obtained from a server; `null` otherwise. |
| [KeyWords](../../aspose.email.mapi/mapicalendar/keywords/) { get; set; } | Gets or sets the categories of the calendar item. |
| [Location](../../aspose.email.mapi/mapicalendar/location/) { get; set; } | Gets or sets the location of the event. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass/) { get; set; } | Gets or sets the message class of the item, such as `IPM.Note` for an e-mail message. The class determines the type of the item. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage/) { get; set; } | Gets or sets the mileage information of the item. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties/) { get; } | Gets the named properties of the item. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping/) { get; } | Gets the mapping between the named properties and the tags they are stored under. |
| [Organizer](../../aspose.email.mapi/mapicalendar/organizer/) { get; set; } | Gets or sets the organizer of the meeting. |
| [ProductId](../../aspose.email.mapi/mapicalendar/productid/) { get; set; } | Gets or sets the identifier of the product that created the calendar item. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets all properties of the object. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream/) { get; } | Gets the property stream of the item. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients/) { get; set; } | Gets or sets the recipients of the item. |
| [Recurrence](../../aspose.email.mapi/mapicalendar/recurrence/) { get; set; } | Gets or sets the recurrence of the event; `null` for a single event. |
| [ReminderDelta](../../aspose.email.mapi/mapicalendar/reminderdelta/) { get; set; } | Gets or sets how many minutes before the start of the event the reminder is due. |
| [ReminderFileParameter](../../aspose.email.mapi/mapicalendar/reminderfileparameter/) { get; set; } | Gets or sets the full path of the sound file that is played when the reminder is due. |
| [ReminderSet](../../aspose.email.mapi/mapicalendar/reminderset/) { get; set; } | Gets or sets a value indicating whether a reminder is set. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity/) { get; set; } | Gets or sets the sensitivity of the item: normal, personal, private or confidential. |
| [Sequence](../../aspose.email.mapi/mapicalendar/sequence/) { get; set; } | Gets or sets the sequence number of the meeting, which is increased each time the organizer sends an update. |
| [StartDate](../../aspose.email.mapi/mapicalendar/startdate/) { get; set; } | Gets or sets the start date and time of the event. Returns `DateTime.MinValue` when the date is not set. |
| [StartDateTimeZone](../../aspose.email.mapi/mapicalendar/startdatetimezone/) { get; set; } | Gets or sets the time zone of [`StartDate`](./startdate/). |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject/) { get; set; } | Gets or sets the subject of the message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix/) { get; } | Gets the prefix of the subject, such as `RE: ` or `FW: `. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages/) { get; } | Gets the sub-storages of the item. |
| [SupportedType](../../aspose.email.mapi/mapimessageitembase/supportedtype/) { get; } | Gets the type of the item, as determined by its message class. |
| [Uid](../../aspose.email.mapi/mapicalendar/uid/) { get; set; } | Gets or sets the unique identifier of the event, which links a meeting request, its updates and responses. |

## Methods

| Name | Description |
| --- | --- |
| static [FromIcs](../../aspose.email.mapi/mapicalendar/fromics/#fromics)(Stream) | Creates an instance of `MapiCalendar` from the specified stream. |
| static [FromIcs](../../aspose.email.mapi/mapicalendar/fromics/#fromics_2)(string) | Creates an instance of `MapiCalendar` from the specified .ics file. |
| static [FromIcs](../../aspose.email.mapi/mapicalendar/fromics/#fromics_1)(Stream, bool) | Creates an instance of `MapiCalendar` from the specified stream. |
| static [FromIcs](../../aspose.email.mapi/mapicalendar/fromics/#fromics_3)(string, bool) | Creates an instance of `MapiCalendar` from the specified .ics file. |
| static [Load](../../aspose.email.mapi/mapicalendar/load/#load)(Stream) | Loads a `MapiCalendar` from the specified stream. |
| static [Load](../../aspose.email.mapi/mapicalendar/load/#load_1)(string) | Loads a `MapiCalendar` from the specified file. |
| override [Dispose](../../aspose.email.mapi/mapicalendar/dispose/)() | Releases all resources used by the calendar item. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty/)(PropertyDescriptor) | Gets a MAPI property of the item by its descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of a property as a Boolean. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the value of a property as bytes. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of a property as a date and time. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the value of a property as a 32-bit integer. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of a property as a 64-bit integer. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of a property as a 16-bit integer. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long) | Gets the value of a property as a string. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [GetUnderlyingMessage](../../aspose.email.mapi/mapicalendar/getunderlyingmessage/)() | Retrieves the underlying MapiMessage object. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines whether the string properties of the object are stored in Unicode. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty/)(long) | Removes a property from the item, including its named-property mapping. |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save)(Stream) | Saves the calendar item to a stream in iCalendar format with the default options. |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save_3)(string) | Saves the calendar item to an iCalendar (.ics) file with the default options. |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save_1)(Stream, AppointmentSaveFormat) | Saves the calendar item to a stream in the specified format with the default options. |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save_2)(Stream, MapiCalendarSaveOptions) | Saves the calendar item to a stream with the specified options. |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save_4)(string, AppointmentSaveFormat) | Saves the calendar item to a file in the specified format with the default options. |
| [Save](../../aspose.email.mapi/mapicalendar/save/#save_5)(string, MapiCalendarSaveOptions) | Saves the calendar item to a file with the specified options. |
| [SaveAsync](../../aspose.email.mapi/mapicalendar/saveasync/#saveasync_2)(Stream, CancellationToken) | Saves calendar object to the file with iCalendar format using the default save options asynchronously. |
| [SaveAsync](../../aspose.email.mapi/mapicalendar/saveasync/#saveasync_5)(string, CancellationToken) | Saves calendar object to the file with iCalendar format using the default save options asynchronously. |
| [SaveAsync](../../aspose.email.mapi/mapicalendar/saveasync/#saveasync)(Stream, AppointmentSaveFormat, CancellationToken) | Saves calendar object to the stream with specified format using the default save options asynchronously. |
| [SaveAsync](../../aspose.email.mapi/mapicalendar/saveasync/#saveasync_1)(Stream, MapiCalendarSaveOptions, CancellationToken) | Saves calendar to the stream with specified save options asynchronously. |
| [SaveAsync](../../aspose.email.mapi/mapicalendar/saveasync/#saveasync_3)(string, AppointmentSaveFormat, CancellationToken) | Saves calendar object to the file with specified format using the default save options asynchronously. |
| [SaveAsync](../../aspose.email.mapi/mapicalendar/saveasync/#saveasync_4)(string, MapiCalendarSaveOptions, CancellationToken) | Saves calendar to the file with specified save options asynchronously. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType) | Sets the body of the item in the specified format. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType, bool) | Sets the body of the item in the specified format, optionally compressing it. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf/)(string, bool) | Sets the body of the item in RTF format, optionally compressing it. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags/)(MapiMessageFlags) | Sets the flags of the message, such as read or unsent. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(MapiProperty) | Adds the property, or replaces the property with the same tag. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty/)(PropertyDescriptor, object) | Sets the value of a MAPI property of the item. |
| [SetStateForced](../../aspose.email.mapi/mapicalendar/setstateforced/)(MapiCalendarState) | Sets the state of the calendar object, overriding any default behavior. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Gets the value of a property as bytes. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of a property as a date and time, if the property exists. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long) | Gets the value of a property as a string. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string) | Gets the value of a property as a string, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string, int) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |
| static [FromIcsAsync](../../aspose.email.mapi/mapicalendar/fromicsasync/#fromicsasync_1)(Stream, CancellationToken) | Creates an instance of `MapiCalendar` from the specified stream asynchronously. |
| static [FromIcsAsync](../../aspose.email.mapi/mapicalendar/fromicsasync/#fromicsasync_3)(string, CancellationToken) | Creates an instance of `MapiCalendar` from the specified .ics file asynchronously. |
| static [FromIcsAsync](../../aspose.email.mapi/mapicalendar/fromicsasync/#fromicsasync)(Stream, bool, CancellationToken) | Creates an instance of `MapiCalendar` from the specified stream asynchronously. |
| static [FromIcsAsync](../../aspose.email.mapi/mapicalendar/fromicsasync/#fromicsasync_2)(string, bool, CancellationToken) | Creates an instance of `MapiCalendar` from the specified .ics file asynchronously. |
| static [LoadAsync](../../aspose.email.mapi/mapicalendar/loadasync/#loadasync)(Stream, CancellationToken) | Loads a `MapiCalendar` from the specified stream asynchronously. |
| static [LoadAsync](../../aspose.email.mapi/mapicalendar/loadasync/#loadasync_1)(string, CancellationToken) | Loads a `MapiCalendar` from the specified file asynchronously. |

## Remarks

This class serves as a wrapper for [`MapiMessage`](../mapimessage/) to simplify the process of handling calendar information from MAPI properties. It provides a more intuitive interface for accessing and manipulating calendar data within the MAPI message.

## Examples

The following example demonstrates how to get a `MapiCalendar` object from a [`MapiMessage`](../mapimessage/).

[C#]

```csharp
var msg = MapiMessage.Load("calendar.msg");

// Check if the loaded message is a supported calendar type
if (msg.SupportedType == MapiItemType.Calendar)
{
    // Convert the MAPI message to a MapiCalendar object
    var mapiCalendar = (MapiCalendar)msg.ToMapiMessageItem();
    
    // Display some calendar info
    Console.WriteLine(mapiCalendar.Subject);
    Console.WriteLine(mapiCalendar.StartDate);
}
```

[Visual Basic]

```csharp
Dim msg = MapiMessage.Load("calendar.msg")

' Check if the loaded message is a supported calendar type
If msg.SupportedType = MapiItemType.Calendar Then
    ' Convert the MAPI message to a MapiCalendar object
    Dim mapiCalendar = DirectCast(msg.ToMapiMessageItem(), MapiCalendar)
    
    ' Display some calendar info
    Console.WriteLine(mapiCalendar.Subject)
    Console.WriteLine(mapiCalendar.StartDate)
End If
```

### See Also

* class [MapiMessageItemBase](../mapimessageitembase/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


