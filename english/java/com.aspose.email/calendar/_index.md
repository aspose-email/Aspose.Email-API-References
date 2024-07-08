---
title: Calendar
second_title: Aspose.Email for Java API Reference
description: A set of metadata such as a description for a single calendar.
type: docs
weight: 92
url: /java/com.aspose.email/calendar/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.BaseDataObject](../../com.aspose.email/basedataobject)
```
public class Calendar extends BaseDataObject
```

A set of metadata, such as a description, for a single calendar.
## Constructors

| Constructor | Description |
| --- | --- |
| [Calendar()](#Calendar--) | Initializes a new instance of the Calendar class. |
| [Calendar(String summary)](#Calendar-java.lang.String-) | Initializes a new instance of the Calendar class. |
| [Calendar(String id, String summary)](#Calendar-java.lang.String-java.lang.String-) | Initializes a new instance of the Calendar class. |
| [Calendar(String summary, String description, String location, String timeZone)](#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the Calendar class. |
| [Calendar(String id, String summary, String description, String location, String timeZone)](#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the Calendar class. |
| [Calendar(String id, String eTag, String summary, String description, String location, String timeZone)](#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the Calendar class. |
## Fields

| Field | Description |
| --- | --- |
| [CALENDAR_KIND](#CALENDAR-KIND) | Type of the resource 'calendar\#calendar'. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConferenceProperties()](#getConferenceProperties--) | Gets conferencing properties for this calendar. |
| [getDescription()](#getDescription--) | Description of the calendar. |
| [getETag()](#getETag--) | An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. |
| [getId()](#getId--) | Identifier of the resource. |
| [getKind()](#getKind--) | Type of the resource |
| [getLocation()](#getLocation--) | Geographic location of the calendar as free-form text. |
| [getSummary()](#getSummary--) | Title of the calendar. |
| [getTimeZone()](#getTimeZone--) | The time zone of the calendar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Description of the calendar. |
| [setETag(String value)](#setETag-java.lang.String-) | An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. |
| [setId(String value)](#setId-java.lang.String-) | Identifier of the resource. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Geographic location of the calendar as free-form text. |
| [setSummary(String value)](#setSummary-java.lang.String-) | Title of the calendar. |
| [setTimeZone(String value)](#setTimeZone-java.lang.String-) | The time zone of the calendar. |
| [toString()](#toString--) | Returns a string which represents the object instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Calendar() {#Calendar--}
```
public Calendar()
```


Initializes a new instance of the Calendar class.

### Calendar(String summary) {#Calendar-java.lang.String-}
```
public Calendar(String summary)
```


Initializes a new instance of the Calendar class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| summary | java.lang.String | Title of the calendar. |

### Calendar(String id, String summary) {#Calendar-java.lang.String-java.lang.String-}
```
public Calendar(String id, String summary)
```


Initializes a new instance of the Calendar class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | Identifier of the resource. |
| summary | java.lang.String | Title of the calendar. |

### Calendar(String summary, String description, String location, String timeZone) {#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public Calendar(String summary, String description, String location, String timeZone)
```


Initializes a new instance of the Calendar class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| summary | java.lang.String | Title of the calendar. |
| description | java.lang.String | Description of the calendar. |
| location | java.lang.String | Geographic location of the calendar as free-form text. |
| timeZone | java.lang.String | The time zone of the calendar. |

### Calendar(String id, String summary, String description, String location, String timeZone) {#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public Calendar(String id, String summary, String description, String location, String timeZone)
```


Initializes a new instance of the Calendar class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | Identifier of the resource. |
| summary | java.lang.String | Title of the calendar. |
| description | java.lang.String | Description of the calendar. |
| location | java.lang.String | Geographic location of the calendar as free-form text. |
| timeZone | java.lang.String | The time zone of the calendar. |

### Calendar(String id, String eTag, String summary, String description, String location, String timeZone) {#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public Calendar(String id, String eTag, String summary, String description, String location, String timeZone)
```


Initializes a new instance of the Calendar class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | Identifier of the resource. |
| eTag | java.lang.String | An entity tag |
| summary | java.lang.String | Title of the calendar. |
| description | java.lang.String | Description of the calendar. |
| location | java.lang.String | Geographic location of the calendar as free-form text. |
| timeZone | java.lang.String | The time zone of the calendar. |

### CALENDAR_KIND {#CALENDAR-KIND}
```
public static final String CALENDAR_KIND
```


Type of the resource 'calendar\#calendar'.

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
### getConferenceProperties() {#getConferenceProperties--}
```
public ConferenceProperties getConferenceProperties()
```


Gets conferencing properties for this calendar.

**Returns:**
[ConferenceProperties](../../com.aspose.email/conferenceproperties)
### getDescription() {#getDescription--}
```
public String getDescription()
```


Description of the calendar.

**Returns:**
java.lang.String
### getETag() {#getETag--}
```
public String getETag()
```


An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. This allows caches to be more efficient, and saves bandwidth, as a web server does not need to send a full response if the content has not changed. ETags can also be used for optimistic concurrency control, as a way to help prevent simultaneous updates of a resource from overwriting each other.

**Returns:**
java.lang.String
### getId() {#getId--}
```
public String getId()
```


Identifier of the resource.

**Returns:**
java.lang.String
### getKind() {#getKind--}
```
public String getKind()
```


Type of the resource

**Returns:**
java.lang.String
### getLocation() {#getLocation--}
```
public String getLocation()
```


Geographic location of the calendar as free-form text.

**Returns:**
java.lang.String
### getSummary() {#getSummary--}
```
public String getSummary()
```


Title of the calendar.

**Returns:**
java.lang.String
### getTimeZone() {#getTimeZone--}
```
public String getTimeZone()
```


The time zone of the calendar.

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




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Description of the calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setETag(String value) {#setETag-java.lang.String-}
```
public void setETag(String value)
```


An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. This allows caches to be more efficient, and saves bandwidth, as a web server does not need to send a full response if the content has not changed. ETags can also be used for optimistic concurrency control, as a way to help prevent simultaneous updates of a resource from overwriting each other.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setId(String value) {#setId-java.lang.String-}
```
public void setId(String value)
```


Identifier of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public void setLocation(String value)
```


Geographic location of the calendar as free-form text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSummary(String value) {#setSummary-java.lang.String-}
```
public void setSummary(String value)
```


Title of the calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTimeZone(String value) {#setTimeZone-java.lang.String-}
```
public void setTimeZone(String value)
```


The time zone of the calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string which represents the object instance.

**Returns:**
java.lang.String - Returns a string which represents the object instance.
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

