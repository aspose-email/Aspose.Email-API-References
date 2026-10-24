---
title: CalendarReader
second_title: Aspose.Email for Java API Reference
description: Provides functionality to read and extract events from an ICS iCalendar file.
type: docs
weight: 98
url: /java/com.aspose.email/calendarreader/
---

**Inheritance:**
java.lang.Object
```
public class CalendarReader
```

Provides functionality to read and extract events from an ICS (iCalendar) file.

The [CalendarReader](../../com.aspose.email/calendarreader) class allows sequential reading of events from an iCalendar (.ics) file. It is designed to parse and access event details such as appointments, meetings, and other calendar items.

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
| [CalendarReader(String path)](#CalendarReader-java.lang.String-) | Initializes a new instance of CalendarReader with source file and default Appointment LoadOptions. |
| [CalendarReader(String path, AppointmentLoadOptions options)](#CalendarReader-java.lang.String-com.aspose.email.AppointmentLoadOptions-) | Initializes a new instance of CalendarReader with source file and Appointment LoadOptions. |
| [CalendarReader(InputStream stream)](#CalendarReader-java.io.InputStream-) | Initializes a new instance of CalendarReader with source stream and default Appointment LoadOptions. |
| [CalendarReader(InputStream stream, AppointmentLoadOptions options)](#CalendarReader-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-) | Initializes a new instance of CalendarReader with source stream and Appointment LoadOptions. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the number of Vevent components. |
| [getCurrent()](#getCurrent--) | Current read event. |
| [getMethod()](#getMethod--) | Gets the iCalendar object method type associated with the calendar object. |
| [getVersion()](#getVersion--) | Gets the Version of calendar. |
| [hashCode()](#hashCode--) |  |
| [isMultiEvents()](#isMultiEvents--) | Gets whether calendar contains multi events. |
| [loadAsMultiple()](#loadAsMultiple--) | Loads a list of events from a calendar with multiple events. |
| [nextEvent()](#nextEvent--) | Reads next Event from source and save it to the Current. |
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


Initializes a new instance of CalendarReader with source file and default Appointment LoadOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Path to source file. |

### CalendarReader(String path, AppointmentLoadOptions options) {#CalendarReader-java.lang.String-com.aspose.email.AppointmentLoadOptions-}
```
public CalendarReader(String path, AppointmentLoadOptions options)
```


Initializes a new instance of CalendarReader with source file and Appointment LoadOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Path to source file. |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Additional LoadOptions. |

### CalendarReader(InputStream stream) {#CalendarReader-java.io.InputStream-}
```
public CalendarReader(InputStream stream)
```


Initializes a new instance of CalendarReader with source stream and default Appointment LoadOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source stream. |

### CalendarReader(InputStream stream, AppointmentLoadOptions options) {#CalendarReader-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-}
```
public CalendarReader(InputStream stream, AppointmentLoadOptions options)
```


Initializes a new instance of CalendarReader with source stream and Appointment LoadOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source stream. |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Additional LoadOptions. |

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


Gets the number of Vevent components.

**Returns:**
int
### getCurrent() {#getCurrent--}
```
public final Appointment getCurrent()
```


Current read event.

**Returns:**
[Appointment](../../com.aspose.email/appointment)
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Gets the iCalendar object method type associated with the calendar object.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Gets the Version of calendar.

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


Gets whether calendar contains multi events.

**Returns:**
boolean
### loadAsMultiple() {#loadAsMultiple--}
```
public final List<Appointment> loadAsMultiple()
```


Loads a list of events from a calendar with multiple events.

**Returns:**
java.util.List<com.aspose.email.Appointment> - 
### nextEvent() {#nextEvent--}
```
public final boolean nextEvent()
```


Reads next Event from source and save it to the Current.

**Returns:**
boolean - True if success otherwise false.
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

