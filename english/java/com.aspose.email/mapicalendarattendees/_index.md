---
title: MapiCalendarAttendees
second_title: Aspose.Email for Java API Reference
description: The attendees of a meeting and the settings of their responses.
type: docs
weight: 409
url: /java/com.aspose.email/mapicalendarattendees/
---

**Inheritance:**
java.lang.Object
```
public final class MapiCalendarAttendees
```

The attendees of a meeting and the settings of their responses.

Returned by [MapiCalendar.getAttendees()](../../com.aspose.email/mapicalendar\#getAttendees--). \#getAppointmentRecipients().getAppointmentRecipients() holds the attendees the meeting is sent to; \#getAppointmentUnsendableRecipients().getAppointmentUnsendableRecipients() holds the attendees it cannot be sent to, such as removed attendees. \#getNotAllowPropose().getNotAllowPropose() and \#getResponseRequested().getResponseRequested() control how attendees may respond.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendarAttendees()](#MapiCalendarAttendees--) | Initializes a new instance of the [MapiCalendarAttendees](../../com.aspose.email/mapicalendarattendees) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppointmentRecipients()](#getAppointmentRecipients--) | Gets the attendees the meeting is sent to. |
| [getAppointmentUnsendableRecipients()](#getAppointmentUnsendableRecipients--) | Gets the attendees the meeting cannot be sent to, such as attendees that were removed from it. |
| [getClass()](#getClass--) |  |
| [getNotAllowPropose()](#getNotAllowPropose--) | Gets a value indicating whether attendees are prevented from proposing a new time for the meeting. |
| [getResponseRequested()](#getResponseRequested--) | Gets a value indicating whether the organizer asks attendees to respond. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAppointmentRecipients(MapiRecipientCollection value)](#setAppointmentRecipients-com.aspose.email.MapiRecipientCollection-) | Sets the attendees the meeting is sent to. |
| [setAppointmentUnsendableRecipients(MapiRecipientCollection value)](#setAppointmentUnsendableRecipients-com.aspose.email.MapiRecipientCollection-) | Sets the attendees the meeting cannot be sent to, such as attendees that were removed from it. |
| [setNotAllowPropose(boolean value)](#setNotAllowPropose-boolean-) | Sets a value indicating whether attendees are prevented from proposing a new time for the meeting. |
| [setResponseRequested(boolean value)](#setResponseRequested-boolean-) | Sets a value indicating whether the organizer asks attendees to respond. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarAttendees() {#MapiCalendarAttendees--}
```
public MapiCalendarAttendees()
```


Initializes a new instance of the [MapiCalendarAttendees](../../com.aspose.email/mapicalendarattendees) class.

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
### getAppointmentRecipients() {#getAppointmentRecipients--}
```
public final MapiRecipientCollection getAppointmentRecipients()
```


Gets the attendees the meeting is sent to.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection)
### getAppointmentUnsendableRecipients() {#getAppointmentUnsendableRecipients--}
```
public final MapiRecipientCollection getAppointmentUnsendableRecipients()
```


Gets the attendees the meeting cannot be sent to, such as attendees that were removed from it.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getNotAllowPropose() {#getNotAllowPropose--}
```
public final boolean getNotAllowPropose()
```


Gets a value indicating whether attendees are prevented from proposing a new time for the meeting.

**Returns:**
boolean
### getResponseRequested() {#getResponseRequested--}
```
public final boolean getResponseRequested()
```


Gets a value indicating whether the organizer asks attendees to respond.

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




### setAppointmentRecipients(MapiRecipientCollection value) {#setAppointmentRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setAppointmentRecipients(MapiRecipientCollection value)
```


Sets the attendees the meeting is sent to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) |  |

### setAppointmentUnsendableRecipients(MapiRecipientCollection value) {#setAppointmentUnsendableRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setAppointmentUnsendableRecipients(MapiRecipientCollection value)
```


Sets the attendees the meeting cannot be sent to, such as attendees that were removed from it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) |  |

### setNotAllowPropose(boolean value) {#setNotAllowPropose-boolean-}
```
public final void setNotAllowPropose(boolean value)
```


Sets a value indicating whether attendees are prevented from proposing a new time for the meeting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setResponseRequested(boolean value) {#setResponseRequested-boolean-}
```
public final void setResponseRequested(boolean value)
```


Sets a value indicating whether the organizer asks attendees to respond.

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

