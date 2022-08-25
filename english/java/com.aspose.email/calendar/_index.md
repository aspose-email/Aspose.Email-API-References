---
title: Calendar
second_title: Aspose.Email for Java API Reference
description:  A set of metadata such as a description for a single calendar.
type: docs
weight: 90
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
| [getSummary()](#getSummary--) | Title of the calendar. |
| [setSummary(String value)](#setSummary-java.lang.String-) | Title of the calendar. |
| [getDescription()](#getDescription--) | Description of the calendar. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Description of the calendar. |
| [getLocation()](#getLocation--) | Geographic location of the calendar as free-form text. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Geographic location of the calendar as free-form text. |
| [getTimeZone()](#getTimeZone--) | The time zone of the calendar. |
| [setTimeZone(String value)](#setTimeZone-java.lang.String-) | The time zone of the calendar. |
| [getConferenceProperties()](#getConferenceProperties--) | Gets conferencing properties for this calendar. |
| [toString()](#toString--) | Returns a string which represents the object instance. |
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

### getSummary() {#getSummary--}
```
public String getSummary()
```


Title of the calendar.

**Returns:**
java.lang.String
### setSummary(String value) {#setSummary-java.lang.String-}
```
public void setSummary(String value)
```


Title of the calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public String getDescription()
```


Description of the calendar.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Description of the calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLocation() {#getLocation--}
```
public String getLocation()
```


Geographic location of the calendar as free-form text.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public void setLocation(String value)
```


Geographic location of the calendar as free-form text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTimeZone() {#getTimeZone--}
```
public String getTimeZone()
```


The time zone of the calendar.

**Returns:**
java.lang.String
### setTimeZone(String value) {#setTimeZone-java.lang.String-}
```
public void setTimeZone(String value)
```


The time zone of the calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getConferenceProperties() {#getConferenceProperties--}
```
public ConferenceProperties getConferenceProperties()
```


Gets conferencing properties for this calendar.

**Returns:**
[ConferenceProperties](../../com.aspose.email/conferenceproperties)
### toString() {#toString--}
```
public String toString()
```


Returns a string which represents the object instance.

**Returns:**
java.lang.String - Returns a string which represents the object instance.
