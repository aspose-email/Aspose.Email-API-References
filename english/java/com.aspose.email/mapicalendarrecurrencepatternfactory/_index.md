---
title: MapiCalendarRecurrencePatternFactory
second_title: Aspose.Email for Java API Reference
description: Creates recurrence patterns from iCalendar recurrence rules.
type: docs
weight: 426
url: /java/com.aspose.email/mapicalendarrecurrencepatternfactory/
---

**Inheritance:**
java.lang.Object
```
public class MapiCalendarRecurrencePatternFactory
```

Creates recurrence patterns from iCalendar recurrence rules.

This example creates a weekly meeting that occurs on Mondays and Wednesdays, ten times.

```

 java.util.Calendar cal = java.util.Calendar.getInstance(TimeZone.getTimeZone("UTC"));
 cal.set(2026, java.util.Calendar.NOVEMBER, 2, 10, 0, 0);
 Date start = cal.getTime();
 cal.add(java.util.Calendar.HOUR_OF_DAY, 1);
 MapiCalendar meeting = new MapiCalendar("Room 1", "Team sync", "Weekly sync-up", start, cal.getTime());

 SimpleDateFormat utc = new SimpleDateFormat("yyyyMMdd'T'HHmmss'Z'");
 utc.setTimeZone(TimeZone.getTimeZone("UTC"));
 String rule = "DTSTART:" + utc.format(start) + "\r\n" +
         "RRULE:FREQ=WEEKLY;BYDAY=MO,WE;COUNT=10";
 MapiCalendarEventRecurrence recurrence = new MapiCalendarEventRecurrence();
 recurrence.setRecurrencePattern(MapiCalendarRecurrencePatternFactory.fromString(rule));
 meeting.setRecurrence(recurrence);

 meeting.save("meeting.msg", AppointmentSaveFormat.Msg);
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendarRecurrencePatternFactory()](#MapiCalendarRecurrencePatternFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromString(String pattern)](#fromString-java.lang.String-) | Creates a recurrence pattern from an iCalendar recurrence rule. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarRecurrencePatternFactory() {#MapiCalendarRecurrencePatternFactory--}
```
public MapiCalendarRecurrencePatternFactory()
```


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
### fromString(String pattern) {#fromString-java.lang.String-}
```
public static MapiCalendarRecurrencePattern fromString(String pattern)
```


Creates a recurrence pattern from an iCalendar recurrence rule.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pattern | java.lang.String | The rule in iCalendar format: a  DTSTART  line followed by an  RRULE  line, and optionally  EXDATE  lines, for example  DTSTART:20261102T100000Z  and  RRULE:FREQ=WEEKLY;BYDAY=MO;COUNT=10 . |

**Returns:**
[MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern) - The pattern for the first  RRULE , with the  EXDATE  dates added to its deleted occurrences;  null  if  pattern  is  null  or has no  RRULE .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

