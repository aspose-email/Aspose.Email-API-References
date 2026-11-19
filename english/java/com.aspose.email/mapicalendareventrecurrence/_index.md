---
title: MapiCalendarEventRecurrence
second_title: Aspose.Email for Java API Reference
description: The recurrence of a calendar event the pattern the time zone and the range of the series.
type: docs
weight: 415
url: /java/com.aspose.email/mapicalendareventrecurrence/
---

**Inheritance:**
java.lang.Object
```
public final class MapiCalendarEventRecurrence
```

The recurrence of a calendar event: the pattern, the time zone and the range of the series.

Assign an instance to [MapiCalendar.getRecurrence()](../../com.aspose.email/mapicalendar\#getRecurrence--). \#getRecurrencePattern().getRecurrencePattern() defines how the event repeats; create it with one of the pattern classes or with [MapiCalendarRecurrencePatternFactory](../../com.aspose.email/mapicalendarrecurrencepatternfactory).
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendarEventRecurrence()](#MapiCalendarEventRecurrence--) | Initializes a new instance of the [MapiCalendarEventRecurrence](../../com.aspose.email/mapicalendareventrecurrence) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppointmentTimeZoneDefinitionRecur()](#getAppointmentTimeZoneDefinitionRecur--) | Gets the time zone used to convert the times of the recurring series to and from UTC. |
| [getClass()](#getClass--) |  |
| [getClipEnd()](#getClipEnd--) | Gets the date of the last occurrence. |
| [getClipStart()](#getClipStart--) | Gets the date of the first occurrence. |
| [getRecurrencePattern()](#getRecurrencePattern--) | Gets the recurrence pattern. |
| [getTimeZoneStruct()](#getTimeZoneStruct--) | Gets the time zone of the recurring meeting. |
| [hashCode()](#hashCode--) |  |
| [isException()](#isException--) | Gets a value indicating whether the object is an exception: a changed occurrence of a series. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAppointmentTimeZoneDefinitionRecur(MapiCalendarTimeZone value)](#setAppointmentTimeZoneDefinitionRecur-com.aspose.email.MapiCalendarTimeZone-) | Sets the time zone used to convert the times of the recurring series to and from UTC. |
| [setClipEnd(Date value)](#setClipEnd-java.util.Date-) | Sets the date of the last occurrence. |
| [setClipStart(Date value)](#setClipStart-java.util.Date-) | Sets the date of the first occurrence. |
| [setException(boolean value)](#setException-boolean-) | Sets a value indicating whether the object is an exception: a changed occurrence of a series. |
| [setRecurrencePattern(MapiCalendarRecurrencePattern value)](#setRecurrencePattern-com.aspose.email.MapiCalendarRecurrencePattern-) | Sets the recurrence pattern. |
| [setTimeZoneStruct(MapiCalendarTimeZone value)](#setTimeZoneStruct-com.aspose.email.MapiCalendarTimeZone-) | Sets the time zone of the recurring meeting. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarEventRecurrence() {#MapiCalendarEventRecurrence--}
```
public MapiCalendarEventRecurrence()
```


Initializes a new instance of the [MapiCalendarEventRecurrence](../../com.aspose.email/mapicalendareventrecurrence) class.

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


Gets the time zone used to convert the times of the recurring series to and from UTC.

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


Gets the date of the last occurrence.

**Returns:**
java.util.Date
### getClipStart() {#getClipStart--}
```
public final Date getClipStart()
```


Gets the date of the first occurrence.

**Returns:**
java.util.Date
### getRecurrencePattern() {#getRecurrencePattern--}
```
public final MapiCalendarRecurrencePattern getRecurrencePattern()
```


Gets the recurrence pattern.

**Returns:**
[MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern)
### getTimeZoneStruct() {#getTimeZoneStruct--}
```
public final MapiCalendarTimeZone getTimeZoneStruct()
```


Gets the time zone of the recurring meeting.

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


Gets a value indicating whether the object is an exception: a changed occurrence of a series.

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


Sets the time zone used to convert the times of the recurring series to and from UTC.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone) |  |

### setClipEnd(Date value) {#setClipEnd-java.util.Date-}
```
public final void setClipEnd(Date value)
```


Sets the date of the last occurrence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setClipStart(Date value) {#setClipStart-java.util.Date-}
```
public final void setClipStart(Date value)
```


Sets the date of the first occurrence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setException(boolean value) {#setException-boolean-}
```
public final void setException(boolean value)
```


Sets a value indicating whether the object is an exception: a changed occurrence of a series.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRecurrencePattern(MapiCalendarRecurrencePattern value) {#setRecurrencePattern-com.aspose.email.MapiCalendarRecurrencePattern-}
```
public final void setRecurrencePattern(MapiCalendarRecurrencePattern value)
```


Sets the recurrence pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern) |  |

### setTimeZoneStruct(MapiCalendarTimeZone value) {#setTimeZoneStruct-com.aspose.email.MapiCalendarTimeZone-}
```
public final void setTimeZoneStruct(MapiCalendarTimeZone value)
```


Sets the time zone of the recurring meeting.

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

