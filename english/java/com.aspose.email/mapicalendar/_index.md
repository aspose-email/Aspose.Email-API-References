---
title: MapiCalendar
second_title: Aspose.Email for Java API Reference
description:  Represents the mapi calendar object
type: docs
weight: 387
url: /java/com.aspose.email/mapicalendar/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiCalendar extends MapiMessageItemBase
```

Represents the mapi calendar object
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendar()](#MapiCalendar--) | Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class |
| [MapiCalendar(String location, String summary, String description, Date startDate, Date endDate)](#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-) | Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class. |
| [MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, String organizer, MapiRecipientCollection attendees)](#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-java.lang.String-com.aspose.email.MapiRecipientCollection-) | Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class. |
| [MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, MapiElectronicAddress organizer, MapiRecipientCollection attendees)](#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MapiElectronicAddress-com.aspose.email.MapiRecipientCollection-) | Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class. |
## Methods

| Method | Description |
| --- | --- |
| [getOrganizer()](#getOrganizer--) | Gets or sets the organizer. |
| [setOrganizer(MapiElectronicAddress value)](#setOrganizer-com.aspose.email.MapiElectronicAddress-) | Gets or sets the organizer. |
| [getReminderDelta()](#getReminderDelta--) | Gets or sets the interval, in minutes, between the time at which the reminder first becomes overdue and the start time of the Calendar object |
| [setReminderDelta(int value)](#setReminderDelta-int-) | Gets or sets the interval, in minutes, between the time at which the reminder first becomes overdue and the start time of the Calendar object |
| [getReminderSet()](#getReminderSet--) | Gets or sets a value indicating whether a reminder is set on the object |
| [setReminderSet(boolean value)](#setReminderSet-boolean-) | Gets or sets a value indicating whether a reminder is set on the object |
| [getReminderFileParameter()](#getReminderFileParameter--) | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [setReminderFileParameter(String value)](#setReminderFileParameter-java.lang.String-) | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [getAppointmentCounterProposal()](#getAppointmentCounterProposal--) | Gets or sets a value indicating whether a Meeting Response object is a counter proposal. |
| [setAppointmentCounterProposal(boolean value)](#setAppointmentCounterProposal-boolean-) | Gets or sets a value indicating whether a Meeting Response object is a counter proposal. |
| [getClientIntent()](#getClientIntent--) | Gets or sets the actions the user has taken on this Meeting object. |
| [setClientIntent(int value)](#setClientIntent-int-) | Gets or sets the actions the user has taken on this Meeting object. |
| [getStartDateTimeZone()](#getStartDateTimeZone--) | Gets or sets time zone information that indicates the time zone of the StartDate property |
| [setStartDateTimeZone(MapiCalendarTimeZone value)](#setStartDateTimeZone-com.aspose.email.MapiCalendarTimeZone-) | Gets or sets time zone information that indicates the time zone of the StartDate property |
| [getEndDateTimeZone()](#getEndDateTimeZone--) | Gets or sets time zone information that indicates the time zone of the EndDate property |
| [setEndDateTimeZone(MapiCalendarTimeZone value)](#setEndDateTimeZone-com.aspose.email.MapiCalendarTimeZone-) | Gets or sets time zone information that indicates the time zone of the EndDate property |
| [getAttendees()](#getAttendees--) | Gets or sets the attendees |
| [setAttendees(MapiCalendarAttendees value)](#setAttendees-com.aspose.email.MapiCalendarAttendees-) | Gets or sets the attendees |
| [getRecurrence()](#getRecurrence--) | Gets or sets the recurrence properties |
| [setRecurrence(MapiCalendarEventRecurrence value)](#setRecurrence-com.aspose.email.MapiCalendarEventRecurrence-) | Gets or sets the recurrence properties |
| [isAllDay()](#isAllDay--) | Gets or sets a value indicating whether the event is an all-day event |
| [setAllDay(boolean value)](#setAllDay-boolean-) | Gets or sets a value indicating whether the event is an all-day event |
| [getKeyWords()](#getKeyWords--) | Gets or sets the categories of the calendar object |
| [setKeyWords(String value)](#setKeyWords-java.lang.String-) | Gets or sets the categories of the calendar object |
| [getStartDate()](#getStartDate--) | Gets or sets the start date and time of the event. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets the start date and time of the event. |
| [getEndDate()](#getEndDate--) | Gets or sets the end date and time of the event. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Gets or sets the end date and time of the event. |
| [getSequence()](#getSequence--) | Gets or sets the sequence number |
| [setSequence(int value)](#setSequence-int-) | Gets or sets the sequence number |
| [getBusyStatus()](#getBusyStatus--) | Gets or sets the busy status |
| [setBusyStatus(int value)](#setBusyStatus-int-) | Gets or sets the busy status |
| [getLocation()](#getLocation--) | Gets or sets the location of the event |
| [setLocation(String value)](#setLocation-java.lang.String-) | Gets or sets the location of the event |
| [getUid()](#getUid--) | Gets the unique identifier |
| [setUid(String value)](#setUid-java.lang.String-) | Gets the unique identifier |
| [save(String filePath, MapiCalendarSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.MapiCalendarSaveOptions-) | Saves calendar object to the file with specified format using te default save options |
| [save(OutputStream stream, MapiCalendarSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.MapiCalendarSaveOptions-) | Saves calendar to the stream with specified save options |
| [save(String filePath)](#save-java.lang.String-) | Saves calendar object to the file with iCalendar format using te default save options |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves calendar object to the file with specified format using te default save options |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves calendar object to the file with iCalendar format using te default save options |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves calendar object to the stream with specified format using te default save options |
| [dispose()](#dispose--) | Releases all resources. |
### MapiCalendar() {#MapiCalendar--}
```
public MapiCalendar()
```


Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class

### MapiCalendar(String location, String summary, String description, Date startDate, Date endDate) {#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-}
```
public MapiCalendar(String location, String summary, String description, Date startDate, Date endDate)
```


Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The appointment location. |
| summary | java.lang.String | The appointment summary. |
| description | java.lang.String | The appointment description. |
| startDate | java.util.Date | The start date. |
| endDate | java.util.Date | The end date. |

### MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, String organizer, MapiRecipientCollection attendees) {#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-java.lang.String-com.aspose.email.MapiRecipientCollection-}
```
public MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, String organizer, MapiRecipientCollection attendees)
```


Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The meeting location. |
| summary | java.lang.String | The meeting summary. |
| description | java.lang.String | The meeting description. |
| startDate | java.util.Date | The start date. |
| endDate | java.util.Date | The end date. |
| organizer | java.lang.String | The meeting organizer address. |
| attendees | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) | The meeting attendees. |

### MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, MapiElectronicAddress organizer, MapiRecipientCollection attendees) {#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MapiElectronicAddress-com.aspose.email.MapiRecipientCollection-}
```
public MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, MapiElectronicAddress organizer, MapiRecipientCollection attendees)
```


Initializes a new instance of the [MapiCalendar](../../com.aspose.email/mapicalendar) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The meeting location. |
| summary | java.lang.String | The meeting summary. |
| description | java.lang.String | The meeting description. |
| startDate | java.util.Date | The start date. |
| endDate | java.util.Date | The end date. |
| organizer | [MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress) | The meeting organizer. |
| attendees | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) | The meeting attendees. |

### getOrganizer() {#getOrganizer--}
```
public final MapiElectronicAddress getOrganizer()
```


Gets or sets the organizer.

**Returns:**
[MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress)
### setOrganizer(MapiElectronicAddress value) {#setOrganizer-com.aspose.email.MapiElectronicAddress-}
```
public final void setOrganizer(MapiElectronicAddress value)
```


Gets or sets the organizer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress) |  |

### getReminderDelta() {#getReminderDelta--}
```
public final int getReminderDelta()
```


Gets or sets the interval, in minutes, between the time at which the reminder first becomes overdue and the start time of the Calendar object

**Returns:**
int
### setReminderDelta(int value) {#setReminderDelta-int-}
```
public final void setReminderDelta(int value)
```


Gets or sets the interval, in minutes, between the time at which the reminder first becomes overdue and the start time of the Calendar object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReminderSet() {#getReminderSet--}
```
public final boolean getReminderSet()
```


Gets or sets a value indicating whether a reminder is set on the object

**Returns:**
boolean
### setReminderSet(boolean value) {#setReminderSet-boolean-}
```
public final void setReminderSet(boolean value)
```


Gets or sets a value indicating whether a reminder is set on the object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getReminderFileParameter() {#getReminderFileParameter--}
```
public final String getReminderFileParameter()
```


Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue.

**Returns:**
java.lang.String
### setReminderFileParameter(String value) {#setReminderFileParameter-java.lang.String-}
```
public final void setReminderFileParameter(String value)
```


Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAppointmentCounterProposal() {#getAppointmentCounterProposal--}
```
public final boolean getAppointmentCounterProposal()
```


Gets or sets a value indicating whether a Meeting Response object is a counter proposal.

**Returns:**
boolean
### setAppointmentCounterProposal(boolean value) {#setAppointmentCounterProposal-boolean-}
```
public final void setAppointmentCounterProposal(boolean value)
```


Gets or sets a value indicating whether a Meeting Response object is a counter proposal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getClientIntent() {#getClientIntent--}
```
public final int getClientIntent()
```


Gets or sets the actions the user has taken on this Meeting object.

**Returns:**
int
### setClientIntent(int value) {#setClientIntent-int-}
```
public final void setClientIntent(int value)
```


Gets or sets the actions the user has taken on this Meeting object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStartDateTimeZone() {#getStartDateTimeZone--}
```
public final MapiCalendarTimeZone getStartDateTimeZone()
```


Gets or sets time zone information that indicates the time zone of the StartDate property

**Returns:**
[MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone)
### setStartDateTimeZone(MapiCalendarTimeZone value) {#setStartDateTimeZone-com.aspose.email.MapiCalendarTimeZone-}
```
public final void setStartDateTimeZone(MapiCalendarTimeZone value)
```


Gets or sets time zone information that indicates the time zone of the StartDate property

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone) |  |

### getEndDateTimeZone() {#getEndDateTimeZone--}
```
public final MapiCalendarTimeZone getEndDateTimeZone()
```


Gets or sets time zone information that indicates the time zone of the EndDate property

**Returns:**
[MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone)
### setEndDateTimeZone(MapiCalendarTimeZone value) {#setEndDateTimeZone-com.aspose.email.MapiCalendarTimeZone-}
```
public final void setEndDateTimeZone(MapiCalendarTimeZone value)
```


Gets or sets time zone information that indicates the time zone of the EndDate property

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone) |  |

### getAttendees() {#getAttendees--}
```
public final MapiCalendarAttendees getAttendees()
```


Gets or sets the attendees

**Returns:**
[MapiCalendarAttendees](../../com.aspose.email/mapicalendarattendees)
### setAttendees(MapiCalendarAttendees value) {#setAttendees-com.aspose.email.MapiCalendarAttendees-}
```
public final void setAttendees(MapiCalendarAttendees value)
```


Gets or sets the attendees

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarAttendees](../../com.aspose.email/mapicalendarattendees) |  |

### getRecurrence() {#getRecurrence--}
```
public final MapiCalendarEventRecurrence getRecurrence()
```


Gets or sets the recurrence properties

**Returns:**
[MapiCalendarEventRecurrence](../../com.aspose.email/mapicalendareventrecurrence)
### setRecurrence(MapiCalendarEventRecurrence value) {#setRecurrence-com.aspose.email.MapiCalendarEventRecurrence-}
```
public final void setRecurrence(MapiCalendarEventRecurrence value)
```


Gets or sets the recurrence properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarEventRecurrence](../../com.aspose.email/mapicalendareventrecurrence) |  |

### isAllDay() {#isAllDay--}
```
public final boolean isAllDay()
```


Gets or sets a value indicating whether the event is an all-day event

**Returns:**
boolean
### setAllDay(boolean value) {#setAllDay-boolean-}
```
public final void setAllDay(boolean value)
```


Gets or sets a value indicating whether the event is an all-day event

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getKeyWords() {#getKeyWords--}
```
public final String getKeyWords()
```


Gets or sets the categories of the calendar object

**Returns:**
java.lang.String
### setKeyWords(String value) {#setKeyWords-java.lang.String-}
```
public final void setKeyWords(String value)
```


Gets or sets the categories of the calendar object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets the start date and time of the event. If the date is not set, default value for java.util.Date is returned.

**Returns:**
java.util.Date
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets the start date and time of the event. If the date is not set, default value for java.util.Date is returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Gets or sets the end date and time of the event. If the date is not set, default value for java.util.Date is returned.

**Returns:**
java.util.Date
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Gets or sets the end date and time of the event. If the date is not set, default value for java.util.Date is returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSequence() {#getSequence--}
```
public final int getSequence()
```


Gets or sets the sequence number

**Returns:**
int
### setSequence(int value) {#setSequence-int-}
```
public final void setSequence(int value)
```


Gets or sets the sequence number

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBusyStatus() {#getBusyStatus--}
```
public final int getBusyStatus()
```


Gets or sets the busy status

**Returns:**
int
### setBusyStatus(int value) {#setBusyStatus-int-}
```
public final void setBusyStatus(int value)
```


Gets or sets the busy status

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Gets or sets the location of the event

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Gets or sets the location of the event

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getUid() {#getUid--}
```
public final String getUid()
```


Gets the unique identifier

**Returns:**
java.lang.String
### setUid(String value) {#setUid-java.lang.String-}
```
public final void setUid(String value)
```


Gets the unique identifier

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### save(String filePath, MapiCalendarSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.MapiCalendarSaveOptions-}
```
public final void save(String filePath, MapiCalendarSaveOptions saveOptions)
```


Saves calendar object to the file with specified format using te default save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file path |
| saveOptions | [MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions) | A save options |

### save(OutputStream stream, MapiCalendarSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.MapiCalendarSaveOptions-}
```
public final void save(OutputStream stream, MapiCalendarSaveOptions saveOptions)
```


Saves calendar to the stream with specified save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |
| saveOptions | [MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions) | A save options |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Saves calendar object to the file with iCalendar format using te default save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file path |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Saves calendar object to the file with specified format using te default save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file path |
| saveFormat | int | A save format |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves calendar object to the file with iCalendar format using te default save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Saves calendar object to the stream with specified format using te default save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |
| saveFormat | int | A save format |

### dispose() {#dispose--}
```
public void dispose()
```


Releases all resources.

