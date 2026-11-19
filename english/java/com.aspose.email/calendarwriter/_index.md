---
title: CalendarWriter
second_title: Aspose.Email for Java API Reference
description: Writes events to an iCalendar ICS file or stream one after another.
type: docs
weight: 101
url: /java/com.aspose.email/calendarwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class CalendarWriter implements System.IDisposable, Closeable
```

Writes events to an iCalendar (ICS) file or stream, one after another.

By default the writer starts a new calendar. With the  CreateNew  option of  AppointmentIcsSaveOptions  set to  false , it adds the events to the end of an existing one. Close the writer (\#close().close()) when you are done; this also closes the stream.

This example demonstrates how to generate and write multiple appointments into an ICS file.

```

 try (CalendarWriter writer = new CalendarWriter("MultipleEvents.ics")) {
     // Generate and write 10 appointments to the ICS file
     for (int i = 0; i < 10; i++) {
         Appointment app = new Appointment("",
                 new Date(),
                 new Date(),
                 MailAddress.to_MailAddress("sender@domain.com"),
                 MailAddressCollection.to_MailAddressCollection("receiver@domain.com"));
         app.setDescription("Appointment Example " + i);
         app.setSummary("Appointment: " + i);

         // Write the appointment to the ICS file
         writer.write(app);
     }
 } catch (Exception e) {
     e.printStackTrace();
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [CalendarWriter(String path)](#CalendarWriter-java.lang.String-) | Initializes a new instance of the [CalendarWriter](../../com.aspose.email/calendarwriter) class that creates the specified file with the default options. |
| [CalendarWriter(System.IO.Stream stream)](#CalendarWriter-com.aspose.ms.System.IO.Stream-) | Initializes a new instance of the [CalendarWriter](../../com.aspose.email/calendarwriter) class that writes to the specified stream with the default options. |
| [CalendarWriter(OutputStream stream)](#CalendarWriter-java.io.OutputStream-) |  |
| [CalendarWriter(String path, AppointmentIcsSaveOptions icsSaveOptions)](#CalendarWriter-java.lang.String-com.aspose.email.AppointmentIcsSaveOptions-) | Initializes a new instance of the [CalendarWriter](../../com.aspose.email/calendarwriter) class that writes to the specified file with the specified options. |
| [CalendarWriter(System.IO.Stream stream, AppointmentIcsSaveOptions icsSaveOptions)](#CalendarWriter-com.aspose.ms.System.IO.Stream-com.aspose.email.AppointmentIcsSaveOptions-) | Initializes a new instance of the [CalendarWriter](../../com.aspose.email/calendarwriter) class that writes to the specified stream with the specified options. |
| [CalendarWriter(OutputStream stream, AppointmentIcsSaveOptions icsSaveOptions)](#CalendarWriter-java.io.OutputStream-com.aspose.email.AppointmentIcsSaveOptions-) |  |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Closes the underlying stream, including a stream passed to the constructor. |
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
| [write(Appointment appointment)](#write-com.aspose.email.Appointment-) | Writes an event to the calendar. |
### CalendarWriter(String path) {#CalendarWriter-java.lang.String-}
```
public CalendarWriter(String path)
```


Initializes a new instance of the [CalendarWriter](../../com.aspose.email/calendarwriter) class that creates the specified file with the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path of the ICS file to create. An existing file is overwritten. |

### CalendarWriter(System.IO.Stream stream) {#CalendarWriter-com.aspose.ms.System.IO.Stream-}
```
public CalendarWriter(System.IO.Stream stream)
```


Initializes a new instance of the [CalendarWriter](../../com.aspose.email/calendarwriter) class that writes to the specified stream with the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream to write to. It must be empty. |

### CalendarWriter(OutputStream stream) {#CalendarWriter-java.io.OutputStream-}
```
public CalendarWriter(OutputStream stream)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### CalendarWriter(String path, AppointmentIcsSaveOptions icsSaveOptions) {#CalendarWriter-java.lang.String-com.aspose.email.AppointmentIcsSaveOptions-}
```
public CalendarWriter(String path, AppointmentIcsSaveOptions icsSaveOptions)
```


Initializes a new instance of the [CalendarWriter](../../com.aspose.email/calendarwriter) class that writes to the specified file with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path of the ICS file. When the  CreateNew  option is  false , the file must exist and the events are added to it. |
| icsSaveOptions | [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) | The save options, or  null  to use the defaults. |

### CalendarWriter(System.IO.Stream stream, AppointmentIcsSaveOptions icsSaveOptions) {#CalendarWriter-com.aspose.ms.System.IO.Stream-com.aspose.email.AppointmentIcsSaveOptions-}
```
public CalendarWriter(System.IO.Stream stream, AppointmentIcsSaveOptions icsSaveOptions)
```


Initializes a new instance of the [CalendarWriter](../../com.aspose.email/calendarwriter) class that writes to the specified stream with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream to write to. When the  CreateNew  option is  true , the default, it must be empty. |
| icsSaveOptions | [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) | The save options, or  null  to use the defaults. |

### CalendarWriter(OutputStream stream, AppointmentIcsSaveOptions icsSaveOptions) {#CalendarWriter-java.io.OutputStream-com.aspose.email.AppointmentIcsSaveOptions-}
```
public CalendarWriter(OutputStream stream, AppointmentIcsSaveOptions icsSaveOptions)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| icsSaveOptions | [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) |  |

### close() {#close--}
```
public void close()
```


Closes the underlying stream, including a stream passed to the constructor.

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


Writes an event to the calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [Appointment](../../com.aspose.email/appointment) | The appointment to write. |

