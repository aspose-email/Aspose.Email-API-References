---
title: CalendarReader
second_title: Aspose.Email for Java API Reference
description: Reads the events of an iCalendar ICS file or stream one by one.
type: docs
weight: 98
url: /java/com.aspose.email/calendarreader/
---

**Inheritance:**
java.lang.Object
```
public class CalendarReader
```

Reads the events of an iCalendar (ICS) file or stream one by one.

The calendar is parsed when the reader is created. Call \#nextEvent().nextEvent() until it returns  false  and take each event from \#getCurrent().getCurrent(), or call \#loadAsMultiple().loadAsMultiple() to get all events at once. Only events (VEVENT components) are read.

This example demonstrates how to read multiple events from an ICS file and store them in a list of [Appointment](../../com.aspose.email/appointment) objects.

```

 // Create a list to hold the appointments
 List appointments = new ArrayList();

 // Initialize CalendarReader with the ICS file path
 CalendarReader reader = new CalendarReader("US-Holidays.ics");

 // Iterate through the events in the ICS file
 while (reader.nextEvent()) {
     // Add the current event to the appointments list
     appointments.add(reader.getCurrent());
 }

 // Working with the appointments...
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [CalendarReader(String path)](#CalendarReader-java.lang.String-) | Initializes a new instance of the [CalendarReader](../../com.aspose.email/calendarreader) class that reads the specified file with the default options. |
| [CalendarReader(String path, AppointmentLoadOptions options)](#CalendarReader-java.lang.String-com.aspose.email.AppointmentLoadOptions-) | Initializes a new instance of the [CalendarReader](../../com.aspose.email/calendarreader) class that reads the specified file with the specified options. |
| [CalendarReader(InputStream stream)](#CalendarReader-java.io.InputStream-) | Initializes a new instance of the [CalendarReader](../../com.aspose.email/calendarreader) class that reads the specified stream with the default options. |
| [CalendarReader(InputStream stream, AppointmentLoadOptions options)](#CalendarReader-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-) | Initializes a new instance of the [CalendarReader](../../com.aspose.email/calendarreader) class that reads the specified stream with the specified options. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the number of events (VEVENT components) in the calendar. |
| [getCurrent()](#getCurrent--) | Gets the event read by the last call to \#nextEvent().nextEvent(), or  null  before the first call. |
| [getMethod()](#getMethod--) | Gets the iCalendar METHOD of the calendar. |
| [getVersion()](#getVersion--) | Gets the version of the calendar: 2.0 for iCalendar, 1.0 for vCalendar. |
| [hashCode()](#hashCode--) |  |
| [isMultiEvents()](#isMultiEvents--) | Gets a value indicating whether the calendar contains more than one event. |
| [loadAsMultiple()](#loadAsMultiple--) | Reads all events of the calendar. |
| [nextEvent()](#nextEvent--) | Reads the next event and makes it available in \#getCurrent().getCurrent(). |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CalendarReader(String path) {#CalendarReader-java.lang.String-}
```
public CalendarReader(String path)
```


Initializes a new instance of the [CalendarReader](../../com.aspose.email/calendarreader) class that reads the specified file with the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path of the ICS file. |

### CalendarReader(String path, AppointmentLoadOptions options) {#CalendarReader-java.lang.String-com.aspose.email.AppointmentLoadOptions-}
```
public CalendarReader(String path, AppointmentLoadOptions options)
```


Initializes a new instance of the [CalendarReader](../../com.aspose.email/calendarreader) class that reads the specified file with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path of the ICS file. |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Options that control loading, or  null  to use the defaults. |

### CalendarReader(InputStream stream) {#CalendarReader-java.io.InputStream-}
```
public CalendarReader(InputStream stream)
```


Initializes a new instance of the [CalendarReader](../../com.aspose.email/calendarreader) class that reads the specified stream with the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream of iCalendar data. |

### CalendarReader(InputStream stream, AppointmentLoadOptions options) {#CalendarReader-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-}
```
public CalendarReader(InputStream stream, AppointmentLoadOptions options)
```


Initializes a new instance of the [CalendarReader](../../com.aspose.email/calendarreader) class that reads the specified stream with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream of iCalendar data. |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Options that control loading, or  null  to use the defaults. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public final int getCount()
```


Gets the number of events (VEVENT components) in the calendar.

**Returns:**
int
### getCurrent() {#getCurrent--}
```
public final Appointment getCurrent()
```


Gets the event read by the last call to \#nextEvent().nextEvent(), or  null  before the first call.

**Returns:**
[Appointment](../../com.aspose.email/appointment)
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Gets the iCalendar METHOD of the calendar.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Gets the version of the calendar: 2.0 for iCalendar, 1.0 for vCalendar.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isMultiEvents() {#isMultiEvents--}
```
public final boolean isMultiEvents()
```


Gets a value indicating whether the calendar contains more than one event.

**Returns:**
boolean
### loadAsMultiple() {#loadAsMultiple--}
```
public final List<Appointment> loadAsMultiple()
```


Reads all events of the calendar.

Reading starts from the first event regardless of the event index of  AppointmentLoadOptions , and the position used by \#nextEvent().nextEvent() does not change.

**Returns:**
java.util.List<com.aspose.email.Appointment> - The events, in the order they appear in the calendar.
### nextEvent() {#nextEvent--}
```
public final boolean nextEvent()
```


Reads the next event and makes it available in \#getCurrent().getCurrent().

**Returns:**
boolean -  true  if an event was read;  false  if there are no more events.
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

