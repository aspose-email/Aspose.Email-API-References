---
title: CalendarWriter
second_title: Aspose.Email for Android via Java API Reference
description: Allows write the set of Events in one ics file or stream.
type: docs
weight: 71
url: /androidjava/com.aspose.email/calendarwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class CalendarWriter implements System.IDisposable, Closeable
```

Allows write the set of Events in one ics file or stream.
## Constructors

| Constructor | Description |
| --- | --- |
| [CalendarWriter(String path)](#CalendarWriter-java.lang.String-) | Initializes a new instance of CalendarReader with source file and default AppointmentIcsSaveOptions. |
| [CalendarWriter(System.IO.Stream stream)](#CalendarWriter-com.aspose.ms.System.IO.Stream-) | Initializes a new instance of CalendarReader with source stream and default AppointmentIcsSaveOptions. |
| [CalendarWriter(String path, AppointmentIcsSaveOptions icsSaveOptions)](#CalendarWriter-java.lang.String-com.aspose.email.AppointmentIcsSaveOptions-) | Initializes a new instance of CalendarReader with source file and additional AppointmentIcsSaveOptions. |
| [CalendarWriter(System.IO.Stream stream, AppointmentIcsSaveOptions icsSaveOptions)](#CalendarWriter-com.aspose.ms.System.IO.Stream-com.aspose.email.AppointmentIcsSaveOptions-) | Initializes a new instance of CalendarReader with source file and additional AppointmentIcsSaveOptions. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(Appointment appointment)](#write-com.aspose.email.Appointment-) | Writes appointment in underlying stream. |
### CalendarWriter(String path) {#CalendarWriter-java.lang.String-}
```
public CalendarWriter(String path)
```


Initializes a new instance of CalendarReader with source file and default AppointmentIcsSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Path to source file. |

### CalendarWriter(System.IO.Stream stream) {#CalendarWriter-com.aspose.ms.System.IO.Stream-}
```
public CalendarWriter(System.IO.Stream stream)
```


Initializes a new instance of CalendarReader with source stream and default AppointmentIcsSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Source stream. |

### CalendarWriter(String path, AppointmentIcsSaveOptions icsSaveOptions) {#CalendarWriter-java.lang.String-com.aspose.email.AppointmentIcsSaveOptions-}
```
public CalendarWriter(String path, AppointmentIcsSaveOptions icsSaveOptions)
```


Initializes a new instance of CalendarReader with source file and additional AppointmentIcsSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Path to source file. |
| icsSaveOptions | [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) | Additional AppointmentIcsSaveOptions. |

### CalendarWriter(System.IO.Stream stream, AppointmentIcsSaveOptions icsSaveOptions) {#CalendarWriter-com.aspose.ms.System.IO.Stream-com.aspose.email.AppointmentIcsSaveOptions-}
```
public CalendarWriter(System.IO.Stream stream, AppointmentIcsSaveOptions icsSaveOptions)
```


Initializes a new instance of CalendarReader with source file and additional AppointmentIcsSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Source stream. |
| icsSaveOptions | [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) | Additional AppointmentIcsSaveOptions. |

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

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

### write(Appointment appointment) {#write-com.aspose.email.Appointment-}
```
public final void write(Appointment appointment)
```


Writes appointment in underlying stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [Appointment](../../com.aspose.email/appointment) | Source appointment |

