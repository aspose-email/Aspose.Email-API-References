---
title: MapiCalendar
second_title: Aspose.Email for Java API Reference
description: Represents an Outlook calendar item an appointment or a meeting.
type: docs
weight: 408
url: /java/com.aspose.email/mapicalendar/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiCalendar extends MapiMessageItemBase
```

Represents an Outlook calendar item: an appointment or a meeting.

This class serves as a wrapper for [MapiMessage](../../com.aspose.email/mapimessage) to simplify the process of handling calendar information from MAPI properties. It provides a more intuitive interface for accessing and manipulating calendar data within the MAPI message.

The following example demonstrates how to get a [MapiCalendar](../../com.aspose.email/mapicalendar) object from a [MapiMessage](../../com.aspose.email/mapimessage).

```

 MapiMessage msg = MapiMessage.load("calendar.msg");

 // Check if the loaded message is a supported calendar type
 if (msg.getSupportedType() == MapiItemType.Calendar) {
     // Convert the MAPI message to a MapiCalendar object
     MapiCalendar mapiCalendar = (MapiCalendar) msg.toMapiMessageItem();

     // Display some calendar info
     System.out.println(mapiCalendar.getSubject());
     System.out.println(mapiCalendar.getStartDate());
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendar()](#MapiCalendar--) | Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class. |
| [MapiCalendar(String location, String summary, String description, Date startDate, Date endDate)](#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-) | Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class that represents an appointment. |
| [MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, String organizer, MapiRecipientCollection attendees)](#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-java.lang.String-com.aspose.email.MapiRecipientCollection-) | Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class that represents a meeting. |
| [MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, MapiElectronicAddress organizer, MapiRecipientCollection attendees)](#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MapiElectronicAddress-com.aspose.email.MapiRecipientCollection-) | Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class that represents a meeting. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Releases the resources used by the item. |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [dispose()](#dispose--) | Releases all resources used by the calendar item. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromIcs(InputStream stream)](#fromIcs-java.io.InputStream-) | Creates an instance of [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified stream. |
| [fromIcs(InputStream stream, boolean detectEncoding)](#fromIcs-java.io.InputStream-boolean-) | Creates an instance of [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified stream. |
| [fromIcs(String filePath)](#fromIcs-java.lang.String-) | Creates an instance of [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified .ics file. |
| [fromIcs(String filePath, boolean detectEncoding)](#fromIcs-java.lang.String-boolean-) | Creates an instance of [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified .ics file. |
| [getAppointmentCounterProposal()](#getAppointmentCounterProposal--) | Gets a value indicating whether a meeting response proposes a new time for the meeting. |
| [getAttachments()](#getAttachments--) | Gets the attachments of the item. |
| [getAttendees()](#getAttendees--) | Gets the attendees of the meeting. |
| [getBilling()](#getBilling--) | Gets the billing information of the item. |
| [getBody()](#getBody--) | Gets the plain-text body of the item. |
| [getBodyHtml()](#getBodyHtml--) | Gets the body of the item as HTML, converted from \#getBodyRtf().getBodyRtf(); an empty string when there is no RTF body. |
| [getBodyRtf()](#getBodyRtf--) | Gets the body of the item in RTF format. |
| [getBodyType()](#getBodyType--) | Gets the format of the body: plain text, HTML or RTF. |
| [getBusyStatus()](#getBusyStatus--) | Gets how the time of the event is shown in the calendar: free, tentative, busy or out of office. |
| [getCategories()](#getCategories--) | Gets the categories of the item. |
| [getClass()](#getClass--) |  |
| [getClientIntent()](#getClientIntent--) | Gets the actions the user has taken on the meeting. |
| [getCodePage()](#getCodePage--) | Gets the code page of the ANSI strings of the object. |
| [getCompanies()](#getCompanies--) | Gets the names of the companies associated with the item. |
| [getEndDate()](#getEndDate--) | Gets the end date and time of the event. |
| [getEndDateTimeZone()](#getEndDateTimeZone--) | Gets the time zone of \#getEndDate().getEndDate(). |
| [getItemId()](#getItemId--) | Gets the identifier of the item on the mail server, for items obtained from a server;  null  otherwise. |
| [getKeyWords()](#getKeyWords--) | Gets the categories of the calendar item. |
| [getLocation()](#getLocation--) | Gets the location of the event. |
| [getMessageClass()](#getMessageClass--) | Gets the message class of the item, such as  IPM.Note  for an e-mail message. |
| [getMileage()](#getMileage--) | Gets the mileage information of the item. |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of the item. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Gets the mapping between the named properties and the tags they are stored under. |
| [getOrganizer()](#getOrganizer--) | Gets the organizer of the meeting. |
| [getProductId()](#getProductId--) | Gets the identifier of the product that created the calendar item. |
| [getProperties()](#getProperties--) | Gets all properties of the object. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets a MAPI property of the item by its descriptor. |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | Gets the value of a property as a Boolean. |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | Gets the value of a property as bytes. |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | Gets the value of a property as a date and time. |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | Gets the value of a property as a 32-bit integer. |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | Gets the value of a property as a 64-bit integer. |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | Gets the value of a property as a 16-bit integer. |
| [getPropertyStream()](#getPropertyStream--) | Gets the property stream of the item. |
| [getPropertyString(long tag)](#getPropertyString-long-) | Gets the value of a property as a string. |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [getRecipients()](#getRecipients--) | Gets the recipients of the item. |
| [getRecurrence()](#getRecurrence--) | Gets the recurrence of the event;  null  for a single event. |
| [getReminderDelta()](#getReminderDelta--) | Gets how many minutes before the start of the event the reminder is due. |
| [getReminderFileParameter()](#getReminderFileParameter--) | Gets the full path of the sound file that is played when the reminder is due. |
| [getReminderSet()](#getReminderSet--) | Gets a value indicating whether a reminder is set. |
| [getSensitivity()](#getSensitivity--) | Gets the sensitivity of the item: normal, personal, private or confidential. |
| [getSequence()](#getSequence--) | Gets the sequence number of the meeting, which is increased each time the organizer sends an update. |
| [getStartDate()](#getStartDate--) | Gets the start date and time of the event. |
| [getStartDateTimeZone()](#getStartDateTimeZone--) | Gets the time zone of \#getStartDate().getStartDate(). |
| [getSubStorages()](#getSubStorages--) | Gets the sub-storages of the item. |
| [getSubject()](#getSubject--) | Gets the subject of the message. |
| [getSubjectPrefix()](#getSubjectPrefix--) | Gets the prefix of the subject, such as  RE:  or  FW: . |
| [getSupportedType()](#getSupportedType--) | Gets the type of the item, as determined by its message class. |
| [getUid()](#getUid--) | Gets the unique identifier of the event, which links a meeting request, its updates and responses. |
| [getUnderlyingMessage()](#getUnderlyingMessage--) | Retrieves the underlying MapiMessage object. |
| [hashCode()](#hashCode--) |  |
| [isAllDay()](#isAllDay--) | Gets a value indicating whether the event lasts all day. |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Determines whether the string properties of the object are stored in Unicode. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads a [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified stream. |
| [load(String filePath)](#load-java.lang.String-) | Loads a [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified file. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(long tag)](#removeProperty-long-) | Removes a property from the item, including its named-property mapping. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the calendar item to a stream in iCalendar format with the default options. |
| [save(OutputStream stream, MapiCalendarSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.MapiCalendarSaveOptions-) | Saves the calendar item to a stream with the specified options. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves the calendar item to a stream in the specified format with the default options. |
| [save(String filePath)](#save-java.lang.String-) | Saves the calendar item to an iCalendar (.ics) file with the default options. |
| [save(String filePath, MapiCalendarSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.MapiCalendarSaveOptions-) | Saves the calendar item to a file with the specified options. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves the calendar item to a file in the specified format with the default options. |
| [setAllDay(boolean value)](#setAllDay-boolean-) | Sets a value indicating whether the event lasts all day. |
| [setAppointmentCounterProposal(boolean value)](#setAppointmentCounterProposal-boolean-) | Sets a value indicating whether a meeting response proposes a new time for the meeting. |
| [setAttendees(MapiCalendarAttendees value)](#setAttendees-com.aspose.email.MapiCalendarAttendees-) | Sets the attendees of the meeting. |
| [setBilling(String value)](#setBilling-java.lang.String-) | Sets the billing information of the item. |
| [setBody(String value)](#setBody-java.lang.String-) | Sets the plain-text body of the item. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Sets the body of the item in the specified format. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Sets the body of the item in the specified format, optionally compressing it. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Sets the body of the item in RTF format. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Sets the body of the item in RTF format, optionally compressing it. |
| [setBusyStatus(int value)](#setBusyStatus-int-) | Sets how the time of the event is shown in the calendar: free, tentative, busy or out of office. |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Sets the categories of the item. |
| [setClientIntent(int value)](#setClientIntent-int-) | Sets the actions the user has taken on the meeting. |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Sets the names of the companies associated with the item. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Sets the end date and time of the event. |
| [setEndDateTimeZone(MapiCalendarTimeZone value)](#setEndDateTimeZone-com.aspose.email.MapiCalendarTimeZone-) | Sets the time zone of \#getEndDate().getEndDate(). |
| [setKeyWords(String value)](#setKeyWords-java.lang.String-) | Sets the categories of the calendar item. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Sets the location of the event. |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Sets the message class of the item, such as  IPM.Note  for an e-mail message. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Sets the flags of the message, such as read or unsent. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Sets the mileage information of the item. |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Sets the named property mapping. |
| [setOrganizer(MapiElectronicAddress value)](#setOrganizer-com.aspose.email.MapiElectronicAddress-) | Sets the organizer of the meeting. |
| [setProductId(String value)](#setProductId-java.lang.String-) | Sets the identifier of the product that created the calendar item. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Adds the property, or replaces the property with the same tag. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets the value of a MAPI property of the item. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Sets the recipients of the item. |
| [setRecurrence(MapiCalendarEventRecurrence value)](#setRecurrence-com.aspose.email.MapiCalendarEventRecurrence-) | Sets the recurrence of the event;  null  for a single event. |
| [setReminderDelta(int value)](#setReminderDelta-int-) | Sets how many minutes before the start of the event the reminder is due. |
| [setReminderFileParameter(String value)](#setReminderFileParameter-java.lang.String-) | Sets the full path of the sound file that is played when the reminder is due. |
| [setReminderSet(boolean value)](#setReminderSet-boolean-) | Sets a value indicating whether a reminder is set. |
| [setSensitivity(int value)](#setSensitivity-int-) | Sets the sensitivity of the item: normal, personal, private or confidential. |
| [setSequence(int value)](#setSequence-int-) | Sets the sequence number of the meeting, which is increased each time the organizer sends an update. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Sets the start date and time of the event. |
| [setStartDateTimeZone(MapiCalendarTimeZone value)](#setStartDateTimeZone-com.aspose.email.MapiCalendarTimeZone-) | Sets the time zone of \#getStartDate().getStartDate(). |
| [setStateForced(int state)](#setStateForced-int-) | Sets the state of the calendar object, overriding any default behavior. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the message. |
| [setUid(String value)](#setUid-java.lang.String-) | Sets the unique identifier of the event, which links a meeting request, its updates and responses. |
| [toMvPropertyList(Object obj)](#toMvPropertyList-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | Gets the value of a property as bytes. |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | Gets the value of a property as a date and time, if the property exists. |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | Gets the value of a property as a string. |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | Gets the value of a property as a string, if the property exists. |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendar() {#MapiCalendar--}
```
public MapiCalendar()
```


Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class.

### MapiCalendar(String location, String summary, String description, Date startDate, Date endDate) {#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-}
```
public MapiCalendar(String location, String summary, String description, Date startDate, Date endDate)
```


Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class that represents an appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the appointment. |
| summary | java.lang.String | The subject of the appointment. |
| description | java.lang.String | The body of the appointment. |
| startDate | java.util.Date | The start date and time. |
| endDate | java.util.Date | The end date and time. |

### MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, String organizer, MapiRecipientCollection attendees) {#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-java.lang.String-com.aspose.email.MapiRecipientCollection-}
```
public MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, String organizer, MapiRecipientCollection attendees)
```


Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class that represents a meeting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the meeting. |
| summary | java.lang.String | The subject of the meeting. |
| description | java.lang.String | The body of the meeting. |
| startDate | java.util.Date | The start date and time. |
| endDate | java.util.Date | The end date and time. |
| organizer | java.lang.String | The e-mail address of the organizer. |
| attendees | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) | The attendees. |

### MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, MapiElectronicAddress organizer, MapiRecipientCollection attendees) {#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MapiElectronicAddress-com.aspose.email.MapiRecipientCollection-}
```
public MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, MapiElectronicAddress organizer, MapiRecipientCollection attendees)
```


Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class that represents a meeting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the meeting. |
| summary | java.lang.String | The subject of the meeting. |
| description | java.lang.String | The body of the meeting. |
| startDate | java.util.Date | The start date and time. |
| endDate | java.util.Date | The end date and time. |
| organizer | [MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress) | The organizer. |
| attendees | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) | The attendees. |

### close() {#close--}
```
public void close()
```


Releases the resources used by the item.

### createMapiNode(String key) {#createMapiNode-java.lang.String-}
```
public IMapiNode createMapiNode(String key)
```


Creates the mapi node.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The node key. |

**Returns:**
com.aspose.email.IMapiNode - The IMapiNode interface.
### dispose() {#dispose--}
```
public void dispose()
```


Releases all resources used by the calendar item.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromIcs(InputStream stream) {#fromIcs-java.io.InputStream-}
```
public static MapiCalendar fromIcs(InputStream stream)
```


Creates an instance of [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to be loaded. |

**Returns:**
[MapiCalendar](../../com.aspose.email/mapicalendar) - Returns a [MapiCalendar](../../com.aspose.email/mapicalendar) instance loaded from the specified stream.
### fromIcs(InputStream stream, boolean detectEncoding) {#fromIcs-java.io.InputStream-boolean-}
```
public static MapiCalendar fromIcs(InputStream stream, boolean detectEncoding)
```


Creates an instance of [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to be loaded. |
| detectEncoding | boolean | Determines a data encoding by analyzing its byte order mark (BOM). |

**Returns:**
[MapiCalendar](../../com.aspose.email/mapicalendar) - Returns a [MapiCalendar](../../com.aspose.email/mapicalendar) instance loaded from the specified stream.
### fromIcs(String filePath) {#fromIcs-java.lang.String-}
```
public static MapiCalendar fromIcs(String filePath)
```


Creates an instance of [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified .ics file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file to be loaded. |

**Returns:**
[MapiCalendar](../../com.aspose.email/mapicalendar) - Returns a [MapiCalendar](../../com.aspose.email/mapicalendar) instance loaded from the specified file.
### fromIcs(String filePath, boolean detectEncoding) {#fromIcs-java.lang.String-boolean-}
```
public static MapiCalendar fromIcs(String filePath, boolean detectEncoding)
```


Creates an instance of [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified .ics file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file to be loaded. |
| detectEncoding | boolean | Determines a data encoding by analyzing its byte order mark (BOM). |

**Returns:**
[MapiCalendar](../../com.aspose.email/mapicalendar) - Returns a [MapiCalendar](../../com.aspose.email/mapicalendar) instance loaded from the specified file.
### getAppointmentCounterProposal() {#getAppointmentCounterProposal--}
```
public final boolean getAppointmentCounterProposal()
```


Gets a value indicating whether a meeting response proposes a new time for the meeting.

**Returns:**
boolean
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


Gets the attachments of the item.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The attachments.
### getAttendees() {#getAttendees--}
```
public final MapiCalendarAttendees getAttendees()
```


Gets the attendees of the meeting.

**Returns:**
[MapiCalendarAttendees](../../com.aspose.email/mapicalendarattendees)
### getBilling() {#getBilling--}
```
public final String getBilling()
```


Gets the billing information of the item.

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public String getBody()
```


Gets the plain-text body of the item.

**Returns:**
java.lang.String - The body.
### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


Gets the body of the item as HTML, converted from \#getBodyRtf().getBodyRtf(); an empty string when there is no RTF body.

**Returns:**
java.lang.String
### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


Gets the body of the item in RTF format.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int), which encapsulates HTML in RTF as Outlook does. Setting  null  or an empty string clears both bodies.

**Returns:**
java.lang.String - The RTF body.
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Gets the format of the body: plain text, HTML or RTF.

**Returns:**
int - The format of the body.
### getBusyStatus() {#getBusyStatus--}
```
public final int getBusyStatus()
```


Gets how the time of the event is shown in the calendar: free, tentative, busy or out of office.

**Returns:**
int
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Gets the categories of the item.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClientIntent() {#getClientIntent--}
```
public final int getClientIntent()
```


Gets the actions the user has taken on the meeting.

**Returns:**
int
### getCodePage() {#getCodePage--}
```
public int getCodePage()
```


Gets the code page of the ANSI strings of the object.

**Returns:**
int - The code page.
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Gets the names of the companies associated with the item.

**Returns:**
java.lang.String[]
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Gets the end date and time of the event. Returns  DateTime.MinValue  when the date is not set.

**Returns:**
java.util.Date
### getEndDateTimeZone() {#getEndDateTimeZone--}
```
public final MapiCalendarTimeZone getEndDateTimeZone()
```


Gets the time zone of \#getEndDate().getEndDate().

**Returns:**
[MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone)
### getItemId() {#getItemId--}
```
public String getItemId()
```


Gets the identifier of the item on the mail server, for items obtained from a server;  null  otherwise.

**Returns:**
java.lang.String
### getKeyWords() {#getKeyWords--}
```
public final String getKeyWords()
```


Gets the categories of the calendar item.

**Returns:**
java.lang.String
### getLocation() {#getLocation--}
```
public final String getLocation()
```


Gets the location of the event.

**Returns:**
java.lang.String
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets the message class of the item, such as  IPM.Note  for an e-mail message. The class determines the type of the item.

**Returns:**
java.lang.String - The message class. It is case-sensitive.
### getMileage() {#getMileage--}
```
public final String getMileage()
```


Gets the mileage information of the item.

**Returns:**
java.lang.String
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of the item.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The named properties.
### getNamedPropertyMapping() {#getNamedPropertyMapping--}
```
public final MapiNamedPropertyMappingStorage getNamedPropertyMapping()
```


Gets the mapping between the named properties and the tags they are stored under.

**Returns:**
[MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) - The named property mapping.
### getOrganizer() {#getOrganizer--}
```
public final MapiElectronicAddress getOrganizer()
```


Gets the organizer of the meeting.

**Returns:**
[MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress)
### getProductId() {#getProductId--}
```
public final String getProductId()
```


Gets the identifier of the product that created the calendar item.

**Returns:**
java.lang.String
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Gets all properties of the object.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The properties.
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Gets a MAPI property of the item by its descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The property, or  null  if the item does not have it.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


Gets the value of a property as a Boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Boolean - The value, or  null  if the property does not exist.
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


Gets the value of a property as bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
byte[] - The value, or  null  if the property does not exist.
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


Gets the value of a property as a date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The tag of the property. |

**Returns:**
java.util.Date - The value, or  null  if the property does not exist.
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


Gets the value of a property as a 32-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Integer - The value, or  null  if the property does not exist.
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


Gets the value of a property as a 64-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Long - The value, or  null  if the property does not exist.
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


Gets the value of a property as a 16-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Short - The value, or  null  if the property does not exist.
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Gets the property stream of the item.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream) - The property stream.
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


Gets the value of a property as a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


Gets the value of a property as a string, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


Gets the recipients of the item.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) - The recipients.
### getRecurrence() {#getRecurrence--}
```
public final MapiCalendarEventRecurrence getRecurrence()
```


Gets the recurrence of the event;  null  for a single event.

**Returns:**
[MapiCalendarEventRecurrence](../../com.aspose.email/mapicalendareventrecurrence)
### getReminderDelta() {#getReminderDelta--}
```
public final int getReminderDelta()
```


Gets how many minutes before the start of the event the reminder is due.

**Returns:**
int
### getReminderFileParameter() {#getReminderFileParameter--}
```
public final String getReminderFileParameter()
```


Gets the full path of the sound file that is played when the reminder is due.

**Returns:**
java.lang.String
### getReminderSet() {#getReminderSet--}
```
public final boolean getReminderSet()
```


Gets a value indicating whether a reminder is set.

**Returns:**
boolean
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the sensitivity of the item: normal, personal, private or confidential.

**Returns:**
int - The sensitivity.
### getSequence() {#getSequence--}
```
public final int getSequence()
```


Gets the sequence number of the meeting, which is increased each time the organizer sends an update.

**Returns:**
int
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets the start date and time of the event. Returns  DateTime.MinValue  when the date is not set.

**Returns:**
java.util.Date
### getStartDateTimeZone() {#getStartDateTimeZone--}
```
public final MapiCalendarTimeZone getStartDateTimeZone()
```


Gets the time zone of \#getStartDate().getStartDate().

**Returns:**
[MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone)
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Gets the sub-storages of the item.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The sub-storages.
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject of the message.

Setting the subject also sets the subject prefix (such as  RE: ) and the normalized subject (the subject without the prefix). Setting  null  or an empty string clears all three.

**Returns:**
java.lang.String - The subject.
### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


Gets the prefix of the subject, such as  RE:  or  FW: .

**Returns:**
java.lang.String - The subject prefix.
### getSupportedType() {#getSupportedType--}
```
public final int getSupportedType()
```


Gets the type of the item, as determined by its message class.

**Returns:**
int - The item type.
### getUid() {#getUid--}
```
public final String getUid()
```


Gets the unique identifier of the event, which links a meeting request, its updates and responses.

**Returns:**
java.lang.String
### getUnderlyingMessage() {#getUnderlyingMessage--}
```
public final MapiMessage getUnderlyingMessage()
```


Retrieves the underlying MapiMessage object.

Retrieves the underlying MAPI message from a MapiCalendar object and prints out its message class.

```

 // Retrieve the underlying MAPI message from the MapiCalendar object
 MapiMessage msg = mapiCalendar.getUnderlyingMessage();

 // Print out the message class of the MAPI message
 // Will output "IPM.Appointment"
 System.out.println(msg.getMessageClass());
 
```

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The [MapiMessage](../../com.aspose.email/mapimessage) object.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAllDay() {#isAllDay--}
```
public final boolean isAllDay()
```


Gets a value indicating whether the event lasts all day.

**Returns:**
boolean
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


Determines whether the string properties of the object are stored in Unicode.

**Returns:**
boolean -  true  if the strings are Unicode;  false  if they are ANSI.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static MapiCalendar load(InputStream stream)
```


Loads a [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified stream.

Accepts both formats \#save(String).save(String) can produce: an Outlook MSG file holding a calendar item, and an iCalendar file (read as \#fromIcs(InputStream, boolean).fromIcs(InputStream, boolean) would, with encoding detection). This makes  MapiCalendar.load(path)  the inverse of  calendar.save(path) , which writes iCalendar by default.

The stream is read from its beginning, whatever its current position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to be loaded. |

**Returns:**
[MapiCalendar](../../com.aspose.email/mapicalendar) - Returns a [MapiCalendar](../../com.aspose.email/mapicalendar) instance loaded from the specified stream.
### load(String filePath) {#load-java.lang.String-}
```
public static MapiCalendar load(String filePath)
```


Loads a [MapiCalendar](../../com.aspose.email/mapicalendar) from the specified file.

Accepts both formats \#save(String).save(String) can produce: an Outlook MSG file holding a calendar item, and an iCalendar file (read as \#fromIcs(InputStream, boolean).fromIcs(InputStream, boolean) would, with encoding detection). This makes  MapiCalendar.load(path)  the inverse of  calendar.save(path) , which writes iCalendar by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file to be loaded. |

**Returns:**
[MapiCalendar](../../com.aspose.email/mapicalendar) - Returns a [MapiCalendar](../../com.aspose.email/mapicalendar) instance loaded from the specified file.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Removes a property from the item, including its named-property mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property to remove. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves the calendar item to a stream in iCalendar format with the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### save(OutputStream stream, MapiCalendarSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.MapiCalendarSaveOptions-}
```
public final void save(OutputStream stream, MapiCalendarSaveOptions saveOptions)
```


Saves the calendar item to a stream with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |
| saveOptions | [MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions) | The options; they also select the format: [MapiCalendarIcsSaveOptions](../../com.aspose.email/mapicalendaricssaveoptions) for iCalendar, [MapiCalendarMsgSaveOptions](../../com.aspose.email/mapicalendarmsgsaveoptions) for MSG. |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Saves the calendar item to a stream in the specified format with the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |
| saveFormat | int | The format: ICS or MSG. |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Saves the calendar item to an iCalendar (.ics) file with the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file to write. |

### save(String filePath, MapiCalendarSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.MapiCalendarSaveOptions-}
```
public final void save(String filePath, MapiCalendarSaveOptions saveOptions)
```


Saves the calendar item to a file with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file to write. |
| saveOptions | [MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions) | The options; they also select the format: [MapiCalendarIcsSaveOptions](../../com.aspose.email/mapicalendaricssaveoptions) for iCalendar, [MapiCalendarMsgSaveOptions](../../com.aspose.email/mapicalendarmsgsaveoptions) for MSG. |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Saves the calendar item to a file in the specified format with the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file to write. |
| saveFormat | int | The format: ICS or MSG. |

### setAllDay(boolean value) {#setAllDay-boolean-}
```
public final void setAllDay(boolean value)
```


Sets a value indicating whether the event lasts all day.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAppointmentCounterProposal(boolean value) {#setAppointmentCounterProposal-boolean-}
```
public final void setAppointmentCounterProposal(boolean value)
```


Sets a value indicating whether a meeting response proposes a new time for the meeting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAttendees(MapiCalendarAttendees value) {#setAttendees-com.aspose.email.MapiCalendarAttendees-}
```
public final void setAttendees(MapiCalendarAttendees value)
```


Sets the attendees of the meeting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarAttendees](../../com.aspose.email/mapicalendarattendees) |  |

### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


Sets the billing information of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


Sets the plain-text body of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The body. |

### setBodyContent(String content, int contentType) {#setBodyContent-java.lang.String-int-}
```
public void setBodyContent(String content, int contentType)
```


Sets the body of the item in the specified format.

The plain-text body, the RTF body and the compressed RTF property are all updated. After HTML content is set, \#getBodyRtf().getBodyRtf() returns that HTML encapsulated in RTF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The text of the body. |
| contentType | int | The format of  content . |

### setBodyContent(String content, int contentType, boolean compression) {#setBodyContent-java.lang.String-int-boolean-}
```
public void setBodyContent(String content, int contentType, boolean compression)
```


Sets the body of the item in the specified format, optionally compressing it.

The plain-text body, the RTF body and the compressed RTF property are all updated. After HTML content is set, \#getBodyRtf().getBodyRtf() returns that HTML encapsulated in RTF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The text of the body. |
| contentType | int | The format of  content . |
| compression | boolean |  true  to store the RTF body compressed. |

### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


Sets the body of the item in RTF format.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int), which encapsulates HTML in RTF as Outlook does. Setting  null  or an empty string clears both bodies.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The RTF body. |

### setBodyRtf(String value, boolean compression) {#setBodyRtf-java.lang.String-boolean-}
```
public final void setBodyRtf(String value, boolean compression)
```


Sets the body of the item in RTF format, optionally compressing it.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int). Setting  null  or an empty string clears both bodies.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The body in RTF. |
| compression | boolean |  true  to store the RTF body compressed. |

### setBusyStatus(int value) {#setBusyStatus-int-}
```
public final void setBusyStatus(int value)
```


Sets how the time of the event is shown in the calendar: free, tentative, busy or out of office.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


Sets the categories of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setClientIntent(int value) {#setClientIntent-int-}
```
public final void setClientIntent(int value)
```


Sets the actions the user has taken on the meeting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Sets the names of the companies associated with the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Sets the end date and time of the event. Returns  DateTime.MinValue  when the date is not set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setEndDateTimeZone(MapiCalendarTimeZone value) {#setEndDateTimeZone-com.aspose.email.MapiCalendarTimeZone-}
```
public final void setEndDateTimeZone(MapiCalendarTimeZone value)
```


Sets the time zone of \#getEndDate().getEndDate().

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone) |  |

### setKeyWords(String value) {#setKeyWords-java.lang.String-}
```
public final void setKeyWords(String value)
```


Sets the categories of the calendar item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Sets the location of the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessageClass(String value) {#setMessageClass-java.lang.String-}
```
public final void setMessageClass(String value)
```


Sets the message class of the item, such as  IPM.Note  for an e-mail message. The class determines the type of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The message class. It is case-sensitive. |

### setMessageFlags(long flags) {#setMessageFlags-long-}
```
public final void setMessageFlags(long flags)
```


Sets the flags of the message, such as read or unsent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The flags to set. |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Sets the mileage information of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNamedPropertyMapping(MapiNamedPropertyMappingStorage value) {#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-}
```
public final void setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)
```


Sets the named property mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) | The MapiNamedPropertyMappingStorage. |

### setOrganizer(MapiElectronicAddress value) {#setOrganizer-com.aspose.email.MapiElectronicAddress-}
```
public final void setOrganizer(MapiElectronicAddress value)
```


Sets the organizer of the meeting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress) |  |

### setProductId(String value) {#setProductId-java.lang.String-}
```
public final void setProductId(String value)
```


Sets the identifier of the product that created the calendar item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


Adds the property, or replaces the property with the same tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | The property to set. |

### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


Sets the value of a MAPI property of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |
| value | java.lang.Object | The value, of a Java type that matches the data type of the property. |

### setRecipients(MapiRecipientCollection value) {#setRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setRecipients(MapiRecipientCollection value)
```


Sets the recipients of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) | The recipients. |

### setRecurrence(MapiCalendarEventRecurrence value) {#setRecurrence-com.aspose.email.MapiCalendarEventRecurrence-}
```
public final void setRecurrence(MapiCalendarEventRecurrence value)
```


Sets the recurrence of the event;  null  for a single event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarEventRecurrence](../../com.aspose.email/mapicalendareventrecurrence) |  |

### setReminderDelta(int value) {#setReminderDelta-int-}
```
public final void setReminderDelta(int value)
```


Sets how many minutes before the start of the event the reminder is due.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setReminderFileParameter(String value) {#setReminderFileParameter-java.lang.String-}
```
public final void setReminderFileParameter(String value)
```


Sets the full path of the sound file that is played when the reminder is due.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setReminderSet(boolean value) {#setReminderSet-boolean-}
```
public final void setReminderSet(boolean value)
```


Sets a value indicating whether a reminder is set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


Sets the sensitivity of the item: normal, personal, private or confidential.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The sensitivity. |

### setSequence(int value) {#setSequence-int-}
```
public final void setSequence(int value)
```


Sets the sequence number of the meeting, which is increased each time the organizer sends an update.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Sets the start date and time of the event. Returns  DateTime.MinValue  when the date is not set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartDateTimeZone(MapiCalendarTimeZone value) {#setStartDateTimeZone-com.aspose.email.MapiCalendarTimeZone-}
```
public final void setStartDateTimeZone(MapiCalendarTimeZone value)
```


Sets the time zone of \#getStartDate().getStartDate().

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone) |  |

### setStateForced(int state) {#setStateForced-int-}
```
public final void setStateForced(int state)
```


Sets the state of the calendar object, overriding any default behavior.

By default, when a meeting is created, its state is [MapiCalendarState.Meeting](../../com.aspose.email/mapicalendarstate\#Meeting). When the meeting is received in a recipient's inbox, it changes to [MapiCalendarState.Received](../../com.aspose.email/mapicalendarstate\#Received) and its message class is set to "IPM.Schedule.Meeting.Request". Using this method to set the state to [MapiCalendarState.Received](../../com.aspose.email/mapicalendarstate\#Received) manually may prevent the item from being sent to other recipients correctly. However, it allows the organizer information to be visible in the saved MSG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| state | int | The new state to apply to the calendar object. |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets the subject of the message.

Setting the subject also sets the subject prefix (such as  RE: ) and the normalized subject (the subject without the prefix). Setting  null  or an empty string clears all three.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The subject. |

### setUid(String value) {#setUid-java.lang.String-}
```
public final void setUid(String value)
```


Sets the unique identifier of the event, which links a meeting request, its updates and responses.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toMvPropertyList(Object obj) {#toMvPropertyList-java.lang.Object-}
```
public static System.Collections.Generic.IGenericList<Object> toMvPropertyList(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Object>
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetPropertyData(long tag) {#tryGetPropertyData-long-}
```
public final byte[] tryGetPropertyData(long tag)
```


Gets the value of a property as bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
byte[] - The value, or  null  if the property does not exist.
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


Gets the value of a property as a date and time, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.util.Date[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


Gets the value of a property as a 32-bit integer, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | int[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


Gets the value of a property as a 64-bit integer, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | long[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


Gets the value of a property as a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


Gets the value of a property as a string, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


Gets the value of a property as a string, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.lang.String[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.lang.String[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

