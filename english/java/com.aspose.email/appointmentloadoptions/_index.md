---
title: AppointmentLoadOptions
second_title: Aspose.Email for Java API Reference
description: Represents options for loading an appointment from an ICS iCalendar file.
type: docs
weight: 40
url: /java/com.aspose.email/appointmentloadoptions/
---

**Inheritance:**
java.lang.Object
```
public class AppointmentLoadOptions
```

Represents options for loading an appointment from an ICS (iCalendar) file.

The [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) class provides configurable options for customizing how appointments are loaded from an iCalendar file. These options include detecting the file encoding, applying the local time zone, and ignoring SMTP address validation during the load process.

This example demonstrates how to configure and use [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) to load an appointment with custom settings.

```

 // Create an instance of AppointmentLoadOptions with custom settings
 AppointmentLoadOptions loadOptions = new AppointmentLoadOptions();
 loadOptions.setDetectEncoding(true);
 loadOptions.setApplyLocalTZ(true);
 loadOptions.setIgnoreSmtpAddressCheck(true);

 // Load the appointment from the ICS file using the specified load options
 Appointment appointment = Appointment.load("appRequest.ics", loadOptions);
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AppointmentLoadOptions()](#AppointmentLoadOptions--) | Initializes a new instance of the [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) class with the default settings. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyLocalTZ()](#getApplyLocalTZ--) | Gets whether to convert the start and end times of the event to the local time zone of the computer. |
| [getClass()](#getClass--) |  |
| [getDetectEncoding()](#getDetectEncoding--) | Gets whether to detect the text encoding of the data from its byte order mark (BOM). |
| [getEventIndex()](#getEventIndex--) | Gets the zero-based index of the event (VEVENT) to load when the calendar contains several. |
| [getIgnoreSmtpAddressCheck()](#getIgnoreSmtpAddressCheck--) | Gets whether to skip the validation of attendee email addresses. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyLocalTZ(boolean value)](#setApplyLocalTZ-boolean-) | Sets whether to convert the start and end times of the event to the local time zone of the computer. |
| [setDetectEncoding(boolean value)](#setDetectEncoding-boolean-) | Sets whether to detect the text encoding of the data from its byte order mark (BOM). |
| [setEventIndex(int value)](#setEventIndex-int-) | Sets the zero-based index of the event (VEVENT) to load when the calendar contains several. |
| [setIgnoreSmtpAddressCheck(boolean value)](#setIgnoreSmtpAddressCheck-boolean-) | Sets whether to skip the validation of attendee email addresses. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AppointmentLoadOptions() {#AppointmentLoadOptions--}
```
public AppointmentLoadOptions()
```


Initializes a new instance of the [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) class with the default settings.

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
### getApplyLocalTZ() {#getApplyLocalTZ--}
```
public final boolean getApplyLocalTZ()
```


Gets whether to convert the start and end times of the event to the local time zone of the computer. The default is  false .

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDetectEncoding() {#getDetectEncoding--}
```
public final boolean getDetectEncoding()
```


Gets whether to detect the text encoding of the data from its byte order mark (BOM). The default is  false .

**Returns:**
boolean
### getEventIndex() {#getEventIndex--}
```
public final int getEventIndex()
```


Gets the zero-based index of the event (VEVENT) to load when the calendar contains several. For [CalendarReader](../../com.aspose.email/calendarreader) it is the index of the first event to read. The default is 0.

**Returns:**
int
### getIgnoreSmtpAddressCheck() {#getIgnoreSmtpAddressCheck--}
```
public final boolean getIgnoreSmtpAddressCheck()
```


Gets whether to skip the validation of attendee email addresses. When  false , an attendee address that is not a valid SMTP address causes an exception. The default is  true .

**Returns:**
boolean
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




### setApplyLocalTZ(boolean value) {#setApplyLocalTZ-boolean-}
```
public final void setApplyLocalTZ(boolean value)
```


Sets whether to convert the start and end times of the event to the local time zone of the computer. The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDetectEncoding(boolean value) {#setDetectEncoding-boolean-}
```
public final void setDetectEncoding(boolean value)
```


Sets whether to detect the text encoding of the data from its byte order mark (BOM). The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setEventIndex(int value) {#setEventIndex-int-}
```
public final void setEventIndex(int value)
```


Sets the zero-based index of the event (VEVENT) to load when the calendar contains several. For [CalendarReader](../../com.aspose.email/calendarreader) it is the index of the first event to read. The default is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setIgnoreSmtpAddressCheck(boolean value) {#setIgnoreSmtpAddressCheck-boolean-}
```
public final void setIgnoreSmtpAddressCheck(boolean value)
```


Sets whether to skip the validation of attendee email addresses. When  false , an attendee address that is not a valid SMTP address causes an exception. The default is  true .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

