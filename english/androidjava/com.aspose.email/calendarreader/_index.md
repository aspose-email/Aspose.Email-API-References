---
title: CalendarReader
second_title: Aspose.Email for Android via Java API Reference
description:  Allows read the calendar with multi events to the Appointment object from a file or stream.
type: docs
weight: 68
url: /java/com.aspose.email/calendarreader/
---
**Inheritance:**
java.lang.Object
```
public class CalendarReader
```

Allows read the calendar with multi events to the Appointment object from a file or stream.
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
| [getCurrent()](#getCurrent--) | Current read event. |
| [nextEvent()](#nextEvent--) | Reads next Event from source and save it to the Current. |
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

### getCurrent() {#getCurrent--}
```
public final Appointment getCurrent()
```


Current read event.

**Returns:**
[Appointment](../../com.aspose.email/appointment)
### nextEvent() {#nextEvent--}
```
public final boolean nextEvent()
```


Reads next Event from source and save it to the Current.

**Returns:**
boolean - True if success otherwise false.
