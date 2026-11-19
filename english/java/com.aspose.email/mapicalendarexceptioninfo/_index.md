---
title: MapiCalendarExceptionInfo
second_title: Aspose.Email for Java API Reference
description: An exception of a recurring series an occurrence whose time subject or other details differ from the series.
type: docs
weight: 416
url: /java/com.aspose.email/mapicalendarexceptioninfo/
---

**Inheritance:**
java.lang.Object
```
public final class MapiCalendarExceptionInfo
```

An exception of a recurring series: an occurrence whose time, subject or other details differ from the series.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendarExceptionInfo()](#MapiCalendarExceptionInfo--) | Initializes a new instance of the [MapiCalendarExceptionInfo](../../com.aspose.email/mapicalendarexceptioninfo) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | Gets the attachments of the exception. |
| [getBody()](#getBody--) | Gets the body of the exception. |
| [getBusyStatus()](#getBusyStatus--) | Gets the busy status of the exception. |
| [getClass()](#getClass--) |  |
| [getEndDateTime()](#getEndDateTime--) | Gets the end date and time of the exception. |
| [getLocation()](#getLocation--) | Gets the location of the exception. |
| [getMeetingType()](#getMeetingType--) | Gets the meeting state of the exception. |
| [getOriginalStartDate()](#getOriginalStartDate--) | Gets the date and time the occurrence was originally scheduled for. |
| [getOverrideFlags()](#getOverrideFlags--) | Gets which details of the exception differ from the series. |
| [getReminderDelta()](#getReminderDelta--) | Gets how many minutes before the start of the exception the reminder is due. |
| [getReminderSet()](#getReminderSet--) | Gets a value indicating whether a reminder is set for the exception. |
| [getStartDateTime()](#getStartDateTime--) | Gets the start date and time of the exception. |
| [getSubType()](#getSubType--) | Gets a value indicating whether the exception is an all-day event: nonzero for an all-day event. |
| [getSubject()](#getSubject--) | Gets the subject of the exception. |
| [hasAttachment()](#hasAttachment--) | Gets a value indicating whether the exception has attachments. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttachments(MapiAttachmentCollection value)](#setAttachments-com.aspose.email.MapiAttachmentCollection-) | Sets the attachments of the exception. |
| [setBody(String value)](#setBody-java.lang.String-) | Sets the body of the exception. |
| [setBusyStatus(int value)](#setBusyStatus-int-) | Sets the busy status of the exception. |
| [setEndDateTime(Date value)](#setEndDateTime-java.util.Date-) | Sets the end date and time of the exception. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Sets the location of the exception. |
| [setMeetingType(int value)](#setMeetingType-int-) | Sets the meeting state of the exception. |
| [setOriginalStartDate(Date value)](#setOriginalStartDate-java.util.Date-) | Sets the date and time the occurrence was originally scheduled for. |
| [setReminderDelta(int value)](#setReminderDelta-int-) | Sets how many minutes before the start of the exception the reminder is due. |
| [setReminderSet(boolean value)](#setReminderSet-boolean-) | Sets a value indicating whether a reminder is set for the exception. |
| [setStartDateTime(Date value)](#setStartDateTime-java.util.Date-) | Sets the start date and time of the exception. |
| [setSubType(int value)](#setSubType-int-) | Sets a value indicating whether the exception is an all-day event: nonzero for an all-day event. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the exception. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarExceptionInfo() {#MapiCalendarExceptionInfo--}
```
public MapiCalendarExceptionInfo()
```


Initializes a new instance of the [MapiCalendarExceptionInfo](../../com.aspose.email/mapicalendarexceptioninfo) class.

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
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


Gets the attachments of the exception.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The attachments.
### getBody() {#getBody--}
```
public final String getBody()
```


Gets the body of the exception.

**Returns:**
java.lang.String - The body.
### getBusyStatus() {#getBusyStatus--}
```
public final int getBusyStatus()
```


Gets the busy status of the exception.

**Returns:**
int - The busy status.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEndDateTime() {#getEndDateTime--}
```
public final Date getEndDateTime()
```


Gets the end date and time of the exception.

**Returns:**
java.util.Date - The end date and time.
### getLocation() {#getLocation--}
```
public final String getLocation()
```


Gets the location of the exception.

**Returns:**
java.lang.String - The location.
### getMeetingType() {#getMeetingType--}
```
public final int getMeetingType()
```


Gets the meeting state of the exception.

**Returns:**
int - The meeting state.
### getOriginalStartDate() {#getOriginalStartDate--}
```
public final Date getOriginalStartDate()
```


Gets the date and time the occurrence was originally scheduled for.

**Returns:**
java.util.Date - The original start date and time.
### getOverrideFlags() {#getOverrideFlags--}
```
public final int getOverrideFlags()
```


Gets which details of the exception differ from the series.

**Returns:**
int - The flags of the changed details.
### getReminderDelta() {#getReminderDelta--}
```
public final int getReminderDelta()
```


Gets how many minutes before the start of the exception the reminder is due.

**Returns:**
int - The number of minutes.
### getReminderSet() {#getReminderSet--}
```
public final boolean getReminderSet()
```


Gets a value indicating whether a reminder is set for the exception.

**Returns:**
boolean -  true  if a reminder is set; otherwise,  false .
### getStartDateTime() {#getStartDateTime--}
```
public final Date getStartDateTime()
```


Gets the start date and time of the exception.

**Returns:**
java.util.Date - The start date and time.
### getSubType() {#getSubType--}
```
public final int getSubType()
```


Gets a value indicating whether the exception is an all-day event: nonzero for an all-day event.

**Returns:**
int - The subtype.
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject of the exception.

**Returns:**
java.lang.String - The subject.
### hasAttachment() {#hasAttachment--}
```
public final boolean hasAttachment()
```


Gets a value indicating whether the exception has attachments.

**Returns:**
boolean -  true  if the exception has attachments; otherwise,  false .
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




### setAttachments(MapiAttachmentCollection value) {#setAttachments-com.aspose.email.MapiAttachmentCollection-}
```
public final void setAttachments(MapiAttachmentCollection value)
```


Sets the attachments of the exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) | The attachments. |

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Sets the body of the exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The body. |

### setBusyStatus(int value) {#setBusyStatus-int-}
```
public final void setBusyStatus(int value)
```


Sets the busy status of the exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The busy status. |

### setEndDateTime(Date value) {#setEndDateTime-java.util.Date-}
```
public final void setEndDateTime(Date value)
```


Sets the end date and time of the exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The end date and time. |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Sets the location of the exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The location. |

### setMeetingType(int value) {#setMeetingType-int-}
```
public final void setMeetingType(int value)
```


Sets the meeting state of the exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The meeting state. |

### setOriginalStartDate(Date value) {#setOriginalStartDate-java.util.Date-}
```
public final void setOriginalStartDate(Date value)
```


Sets the date and time the occurrence was originally scheduled for.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The original start date and time. |

### setReminderDelta(int value) {#setReminderDelta-int-}
```
public final void setReminderDelta(int value)
```


Sets how many minutes before the start of the exception the reminder is due.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The number of minutes. |

### setReminderSet(boolean value) {#setReminderSet-boolean-}
```
public final void setReminderSet(boolean value)
```


Sets a value indicating whether a reminder is set for the exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if a reminder is set; otherwise,  false . |

### setStartDateTime(Date value) {#setStartDateTime-java.util.Date-}
```
public final void setStartDateTime(Date value)
```


Sets the start date and time of the exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The start date and time. |

### setSubType(int value) {#setSubType-int-}
```
public final void setSubType(int value)
```


Sets a value indicating whether the exception is an all-day event: nonzero for an all-day event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The subtype. |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets the subject of the exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The subject. |

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

