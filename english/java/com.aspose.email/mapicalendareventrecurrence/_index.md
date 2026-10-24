---
title: MapiCalendarEventRecurrence
second_title: Aspose.Email for Java API Reference
description: Represents the recurrence properties of a calendar object including the recurrence pattern time zone information and the date range of recurrence.
type: docs
weight: 415
url: /java/com.aspose.email/mapicalendareventrecurrence/
---

**Inheritance:**
java.lang.Object
```
public final class MapiCalendarEventRecurrence
```

Represents the recurrence properties of a calendar object, including the recurrence pattern, time zone information, and the date range of recurrence. This class encapsulates all the data needed to define how recurring calendar events repeat over time.

--------------------

This class is used with [MapiCalendar](../../com.aspose.email/mapicalendar) to manage recurring meeting patterns. The  RecurrencePattern ([getRecurrencePattern](../../com.aspose.email/mapicalendareventrecurrence\#getRecurrencePattern)/[setRecurrencePattern(MapiCalendarRecurrencePattern)](../../com.aspose.email/mapicalendareventrecurrence\#setRecurrencePattern-MapiCalendarRecurrencePattern-)) property defines the type and frequency of recurrence (daily, weekly, monthly, or yearly). The  ClipStart ([getClipStart](../../com.aspose.email/mapicalendareventrecurrence\#getClipStart)/[setClipStart(DateTime)](../../com.aspose.email/mapicalendareventrecurrence\#setClipStart-DateTime-)) and  ClipEnd ([getClipEnd](../../com.aspose.email/mapicalendareventrecurrence\#getClipEnd)/[setClipEnd(DateTime)](../../com.aspose.email/mapicalendareventrecurrence\#setClipEnd-DateTime-)) properties specify the date range for the recurrence, and the time zone properties ensure proper time conversion across different time zones. Exception meetings have a different recurrence structure than the main series.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendarEventRecurrence()](#MapiCalendarEventRecurrence--) | Initializes a new instance of the [MapiCalendarEventRecurrence](../../com.aspose.email/mapicalendareventrecurrence) class |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppointmentTimeZoneDefinitionRecur()](#getAppointmentTimeZoneDefinitionRecur--) | Gets or sets time zone information that describes how to convert the meeting date and time on a recurring series to and from UTC. |
| [getClass()](#getClass--) |  |
| [getClipEnd()](#getClipEnd--) | Gets or sets the date of the last instance |
| [getClipStart()](#getClipStart--) | Gets or sets the date of the first instance |
| [getRecurrencePattern()](#getRecurrencePattern--) | Gets or sets the recurrence pattern |
| [getTimeZoneStruct()](#getTimeZoneStruct--) | Gets or sets the time zone information for a recurring meeting. |
| [hashCode()](#hashCode--) |  |
| [isException()](#isException--) | Gets or sets a value indicating whether the object represents an exception |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAppointmentTimeZoneDefinitionRecur(MapiCalendarTimeZone value)](#setAppointmentTimeZoneDefinitionRecur-com.aspose.email.MapiCalendarTimeZone-) | Gets or sets time zone information that describes how to convert the meeting date and time on a recurring series to and from UTC. |
| [setClipEnd(Date value)](#setClipEnd-java.util.Date-) | Gets or sets the date of the last instance |
| [setClipStart(Date value)](#setClipStart-java.util.Date-) | Gets or sets the date of the first instance |
| [setException(boolean value)](#setException-boolean-) | Gets or sets a value indicating whether the object represents an exception |
| [setRecurrencePattern(MapiCalendarRecurrencePattern value)](#setRecurrencePattern-com.aspose.email.MapiCalendarRecurrencePattern-) | Gets or sets the recurrence pattern |
| [setTimeZoneStruct(MapiCalendarTimeZone value)](#setTimeZoneStruct-com.aspose.email.MapiCalendarTimeZone-) | Gets or sets the time zone information for a recurring meeting. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarEventRecurrence() {#MapiCalendarEventRecurrence--}
```
public MapiCalendarEventRecurrence()
```


Initializes a new instance of the [MapiCalendarEventRecurrence](../../com.aspose.email/mapicalendareventrecurrence) class

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
### getAppointmentTimeZoneDefinitionRecur() {#getAppointmentTimeZoneDefinitionRecur--}
```
public final MapiCalendarTimeZone getAppointmentTimeZoneDefinitionRecur()
```


Gets or sets time zone information that describes how to convert the meeting date and time on a recurring series to and from UTC.

**Returns:**
[MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClipEnd() {#getClipEnd--}
```
public final Date getClipEnd()
```


Gets or sets the date of the last instance

**Returns:**
java.util.Date
### getClipStart() {#getClipStart--}
```
public final Date getClipStart()
```


Gets or sets the date of the first instance

**Returns:**
java.util.Date
### getRecurrencePattern() {#getRecurrencePattern--}
```
public final MapiCalendarRecurrencePattern getRecurrencePattern()
```


Gets or sets the recurrence pattern

**Returns:**
[MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern)
### getTimeZoneStruct() {#getTimeZoneStruct--}
```
public final MapiCalendarTimeZone getTimeZoneStruct()
```


Gets or sets the time zone information for a recurring meeting.

**Returns:**
[MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isException() {#isException--}
```
public final boolean isException()
```


Gets or sets a value indicating whether the object represents an exception

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAppointmentTimeZoneDefinitionRecur(MapiCalendarTimeZone value) {#setAppointmentTimeZoneDefinitionRecur-com.aspose.email.MapiCalendarTimeZone-}
```
public final void setAppointmentTimeZoneDefinitionRecur(MapiCalendarTimeZone value)
```


Gets or sets time zone information that describes how to convert the meeting date and time on a recurring series to and from UTC.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone) |  |

### setClipEnd(Date value) {#setClipEnd-java.util.Date-}
```
public final void setClipEnd(Date value)
```


Gets or sets the date of the last instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setClipStart(Date value) {#setClipStart-java.util.Date-}
```
public final void setClipStart(Date value)
```


Gets or sets the date of the first instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setException(boolean value) {#setException-boolean-}
```
public final void setException(boolean value)
```


Gets or sets a value indicating whether the object represents an exception

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRecurrencePattern(MapiCalendarRecurrencePattern value) {#setRecurrencePattern-com.aspose.email.MapiCalendarRecurrencePattern-}
```
public final void setRecurrencePattern(MapiCalendarRecurrencePattern value)
```


Gets or sets the recurrence pattern

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern) |  |

### setTimeZoneStruct(MapiCalendarTimeZone value) {#setTimeZoneStruct-com.aspose.email.MapiCalendarTimeZone-}
```
public final void setTimeZoneStruct(MapiCalendarTimeZone value)
```


Gets or sets the time zone information for a recurring meeting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

