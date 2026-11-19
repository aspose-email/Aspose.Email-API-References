---
title: AppointmentIcsSaveOptions
second_title: Aspose.Email for Java API Reference
description: Represents options for saving an appointment or meeting to an ICS iCalendar file.
type: docs
weight: 39
url: /java/com.aspose.email/appointmenticssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions)
```
public final class AppointmentIcsSaveOptions extends AppointmentSaveOptions
```

Represents options for saving an appointment or meeting to an ICS (iCalendar) file.

The [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) class allows specifying various settings for controlling how appointments or meetings are saved to an iCalendar file. These options include setting the creation mode, specifying the method type, product identifier, and action to be taken when saving the file.

This example demonstrates how to create and save a meeting to an ICS file using [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions).

```

 // Create a new appointment for a meeting
 Appointment meeting = new Appointment(
         "Meeting Room 3 at Office Headquarters",                                       // Location
         "Monthly Meeting",                                                             // Summary
         "Please confirm your availability.",                                           // Description
         new java.util.GregorianCalendar(2015, java.util.Calendar.FEBRUARY, 8, 13, 0, 0).getTime(), // Start date
         new java.util.GregorianCalendar(2015, java.util.Calendar.FEBRUARY, 8, 14, 0, 0).getTime(), // End date
         MailAddress.to_MailAddress("from@domain.com"),                                 // Organizer
         MailAddressCollection.to_MailAddressCollection("attendees@domain.com"));       // Attendees

 // Set the save options for ICS file
 AppointmentIcsSaveOptions saveOptions = new AppointmentIcsSaveOptions();
 saveOptions.setCreateNew(true);
 saveOptions.setMethodType(AppointmentMethodType.Request);
 saveOptions.setProductId("Aspose.Email");
 saveOptions.setAction(AppointmentAction.Create);

 // Save the meeting to an ICS file
 meeting.save("meeting.ics", saveOptions);
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AppointmentIcsSaveOptions()](#AppointmentIcsSaveOptions--) | Initializes a new instance of the [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) class with the default settings. |
| [AppointmentIcsSaveOptions(int method)](#AppointmentIcsSaveOptions-int-) | Initializes a new instance of the [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) class for the specified action. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Gets whether the event is saved as new, as an update or as a cancellation. |
| [getClass()](#getClass--) |  |
| [getCreateNew()](#getCreateNew--) | Gets whether to create a new calendar ( true , the default) or to add the event to the end of an existing one ( false ). |
| [getDefault()](#getDefault--) | Gets a new instance of the default iCalendar save options, with the action set to  AppointmentAction.Create . |
| [getEndTimeZone()](#getEndTimeZone--) | Gets the time zone for the end of the event. |
| [getMethodType()](#getMethodType--) | Gets the iCalendar METHOD to write. |
| [getProductId()](#getProductId--) | Gets the identifier of the product that creates the calendar (the iCalendar PRODID property). |
| [getSaveFormat()](#getSaveFormat--) | Gets the format these options save to. |
| [getSequenceId()](#getSequenceId--) | Gets the sequence number to write (the iCalendar SEQUENCE property). |
| [getStartTimeZone()](#getStartTimeZone--) | Gets the time zone for the start of the event. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | Sets whether the event is saved as new, as an update or as a cancellation. |
| [setCreateNew(boolean value)](#setCreateNew-boolean-) | Sets whether to create a new calendar ( true , the default) or to add the event to the end of an existing one ( false ). |
| [setEndTimeZone(String value)](#setEndTimeZone-java.lang.String-) | Sets the time zone for the end of the event. |
| [setMethodType(int value)](#setMethodType-int-) | Sets the iCalendar METHOD to write. |
| [setProductId(String value)](#setProductId-java.lang.String-) | Sets the identifier of the product that creates the calendar (the iCalendar PRODID property). |
| [setSequenceId(int value)](#setSequenceId-int-) | Sets the sequence number to write (the iCalendar SEQUENCE property). |
| [setStartTimeZone(String value)](#setStartTimeZone-java.lang.String-) | Sets the time zone for the start of the event. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AppointmentIcsSaveOptions() {#AppointmentIcsSaveOptions--}
```
public AppointmentIcsSaveOptions()
```


Initializes a new instance of the [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) class with the default settings.

### AppointmentIcsSaveOptions(int method) {#AppointmentIcsSaveOptions-int-}
```
public AppointmentIcsSaveOptions(int method)
```


Initializes a new instance of the [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) class for the specified action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| method | int | Whether the event is saved as new, as an update or as a cancellation (an [AppointmentAction](../../com.aspose.email/appointmentaction) value). |

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
### getAction() {#getAction--}
```
public final int getAction()
```


Gets whether the event is saved as new, as an update or as a cancellation. The default is  AppointmentAction.Create .

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreateNew() {#getCreateNew--}
```
public final boolean getCreateNew()
```


Gets whether to create a new calendar ( true , the default) or to add the event to the end of an existing one ( false ).

**Returns:**
boolean
### getDefault() {#getDefault--}
```
public static AppointmentIcsSaveOptions getDefault()
```


Gets a new instance of the default iCalendar save options, with the action set to  AppointmentAction.Create .

**Returns:**
[AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions)
### getEndTimeZone() {#getEndTimeZone--}
```
public final String getEndTimeZone()
```


Gets the time zone for the end of the event. When set, it is assigned to the end time zone ([Appointment.setEndTimeZone(String)](../../com.aspose.email/appointment\#setEndTimeZone-String-)) of each appointment written.

**Returns:**
java.lang.String
### getMethodType() {#getMethodType--}
```
public final int getMethodType()
```


Gets the iCalendar METHOD to write.  AppointmentMethodType.None , the default, keeps the method type of the appointment.

**Returns:**
int
### getProductId() {#getProductId--}
```
public final String getProductId()
```


Gets the identifier of the product that creates the calendar (the iCalendar PRODID property).

**Returns:**
java.lang.String - The product identifier.
### getSaveFormat() {#getSaveFormat--}
```
public final int getSaveFormat()
```


Gets the format these options save to.

**Returns:**
int
### getSequenceId() {#getSequenceId--}
```
public final int getSequenceId()
```


Gets the sequence number to write (the iCalendar SEQUENCE property). A negative value, the default, keeps the sequence id of the appointment.

**Returns:**
int - The sequence id.
### getStartTimeZone() {#getStartTimeZone--}
```
public final String getStartTimeZone()
```


Gets the time zone for the start of the event. When set, it is assigned to the start time zone ([Appointment.setStartTimeZone(String)](../../com.aspose.email/appointment\#setStartTimeZone-String-)) of each appointment written.

**Returns:**
java.lang.String
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




### setAction(int value) {#setAction-int-}
```
public final void setAction(int value)
```


Sets whether the event is saved as new, as an update or as a cancellation. The default is  AppointmentAction.Create .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCreateNew(boolean value) {#setCreateNew-boolean-}
```
public final void setCreateNew(boolean value)
```


Sets whether to create a new calendar ( true , the default) or to add the event to the end of an existing one ( false ).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setEndTimeZone(String value) {#setEndTimeZone-java.lang.String-}
```
public final void setEndTimeZone(String value)
```


Sets the time zone for the end of the event. When set, it is assigned to the end time zone ([Appointment.setEndTimeZone(String)](../../com.aspose.email/appointment\#setEndTimeZone-String-)) of each appointment written.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMethodType(int value) {#setMethodType-int-}
```
public final void setMethodType(int value)
```


Sets the iCalendar METHOD to write.  AppointmentMethodType.None , the default, keeps the method type of the appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setProductId(String value) {#setProductId-java.lang.String-}
```
public final void setProductId(String value)
```


Sets the identifier of the product that creates the calendar (the iCalendar PRODID property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The product identifier. |

### setSequenceId(int value) {#setSequenceId-int-}
```
public final void setSequenceId(int value)
```


Sets the sequence number to write (the iCalendar SEQUENCE property). A negative value, the default, keeps the sequence id of the appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The sequence id. |

### setStartTimeZone(String value) {#setStartTimeZone-java.lang.String-}
```
public final void setStartTimeZone(String value)
```


Sets the time zone for the start of the event. When set, it is assigned to the start time zone ([Appointment.setStartTimeZone(String)](../../com.aspose.email/appointment\#setStartTimeZone-String-)) of each appointment written.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

