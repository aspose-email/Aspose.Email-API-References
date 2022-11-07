---
title: ExtendedCalendar
second_title: Aspose.Email for Java API Reference
description: A set of extended metadata such as a colors for a single calendar.
type: docs
weight: 236
url: /java/com.aspose.email/extendedcalendar/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.BaseDataObject](../../com.aspose.email/basedataobject), [com.aspose.email.Calendar](../../com.aspose.email/calendar)
```
public class ExtendedCalendar extends Calendar
```

A set of extended metadata, such as a colors, for a single calendar.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExtendedCalendar()](#ExtendedCalendar--) | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar(String summary)](#ExtendedCalendar-java.lang.String-) | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar(String id, String summary)](#ExtendedCalendar-java.lang.String-java.lang.String-) | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar(String summary, String description, String location, String timeZone)](#ExtendedCalendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar(String id, String summary, String description, String location, String timeZone)](#ExtendedCalendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar(String id, String summary, String description, String location, String timeZone, String summaryOverride, String colorId, String backgroundColor, String foregroundColor, boolean hidden, boolean selected, int accessRole, System.Collections.Generic.KeyValuePair<Integer,Integer>[] defaultReminders, boolean primary)](#ExtendedCalendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-boolean-int-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----boolean-) | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar(String id, String eTag, String summary, String description, String location, String timeZone, String summaryOverride, String colorId, String backgroundColor, String foregroundColor, boolean hidden, boolean selected, int accessRole, System.Collections.Generic.KeyValuePair<Integer,Integer>[] defaultReminders, boolean primary)](#ExtendedCalendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-boolean-int-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----boolean-) | Initializes a new instance of the ExtendedCalendar class. |
## Fields

| Field | Description |
| --- | --- |
| [CALENDAR_KIND](#CALENDAR-KIND) | Type of the resource 'calendar\#calendar'. |
| [EXTENDED_CALENDAR_KIND](#EXTENDED-CALENDAR-KIND) | Type of the resource 'calendar\#calendarListEntry'. |
| [LIST_KIND](#LIST-KIND) | Type of the resources list 'calendar\#calendarList'. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccessRole()](#getAccessRole--) | The effective access role that the authenticated user has on the calendar. |
| [getBackgroundColor()](#getBackgroundColor--) | The main color of the calendar in the format '\#0088aa'. |
| [getClass()](#getClass--) |  |
| [getColorId()](#getColorId--) | The color of the calendar. |
| [getConferenceProperties()](#getConferenceProperties--) | Gets conferencing properties for this calendar. |
| [getDefaultReminders()](#getDefaultReminders--) | The default reminders that the authenticated user has for this calendar. |
| [getDescription()](#getDescription--) | Description of the calendar. |
| [getETag()](#getETag--) | An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. |
| [getForegroundColor()](#getForegroundColor--) | The foreground color of the calendar in the format '\#ffffff'. |
| [getHidden()](#getHidden--) | Whether the calendar has been hidden from the list. |
| [getId()](#getId--) | Identifier of the resource. |
| [getKind()](#getKind--) | Type of the resource |
| [getLocation()](#getLocation--) | Geographic location of the calendar as free-form text. |
| [getNotificationSettings()](#getNotificationSettings--) | The notifications that the authenticated user is receiving for this calendar. |
| [getPrimary()](#getPrimary--) | Whether the calendar is the primary calendar of the authenticated user. |
| [getSelected()](#getSelected--) | Whether the calendar content shows up in the calendar UI. |
| [getSummary()](#getSummary--) | Title of the calendar. |
| [getSummaryOverride()](#getSummaryOverride--) | The summary that the authenticated user has set for this calendar. |
| [getTimeZone()](#getTimeZone--) | The time zone of the calendar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(String value)](#setBackgroundColor-java.lang.String-) | The main color of the calendar in the format '\#0088aa'. |
| [setColorId(String value)](#setColorId-java.lang.String-) | The color of the calendar. |
| [setDefaultReminders(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value)](#setDefaultReminders-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----) | The default reminders that the authenticated user has for this calendar. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Description of the calendar. |
| [setETag(String value)](#setETag-java.lang.String-) | An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. |
| [setForegroundColor(String value)](#setForegroundColor-java.lang.String-) | The foreground color of the calendar in the format '\#ffffff'. |
| [setHidden(boolean value)](#setHidden-boolean-) | Whether the calendar has been hidden from the list. |
| [setId(String value)](#setId-java.lang.String-) | Identifier of the resource. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Geographic location of the calendar as free-form text. |
| [setNotificationSettings(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value)](#setNotificationSettings-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----) | The notifications that the authenticated user is receiving for this calendar. |
| [setPrimary(boolean value)](#setPrimary-boolean-) | Whether the calendar is the primary calendar of the authenticated user. |
| [setSelected(boolean value)](#setSelected-boolean-) | Whether the calendar content shows up in the calendar UI. |
| [setSummary(String value)](#setSummary-java.lang.String-) | Title of the calendar. |
| [setSummaryOverride(String value)](#setSummaryOverride-java.lang.String-) | The summary that the authenticated user has set for this calendar. |
| [setTimeZone(String value)](#setTimeZone-java.lang.String-) | The time zone of the calendar. |
| [toString()](#toString--) | Returns a string which represents the object instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtendedCalendar() {#ExtendedCalendar--}
```
public ExtendedCalendar()
```


Initializes a new instance of the ExtendedCalendar class.

### ExtendedCalendar(String summary) {#ExtendedCalendar-java.lang.String-}
```
public ExtendedCalendar(String summary)
```


Initializes a new instance of the ExtendedCalendar class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| summary | java.lang.String | Title of the calendar. |

### ExtendedCalendar(String id, String summary) {#ExtendedCalendar-java.lang.String-java.lang.String-}
```
public ExtendedCalendar(String id, String summary)
```


Initializes a new instance of the ExtendedCalendar class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | Identifier of the resource. |
| summary | java.lang.String | Title of the calendar. |

### ExtendedCalendar(String summary, String description, String location, String timeZone) {#ExtendedCalendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public ExtendedCalendar(String summary, String description, String location, String timeZone)
```


Initializes a new instance of the ExtendedCalendar class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| summary | java.lang.String | Title of the calendar. |
| description | java.lang.String | Description of the calendar. |
| location | java.lang.String | Geographic location of the calendar as free-form text. |
| timeZone | java.lang.String | The time zone of the calendar. |

### ExtendedCalendar(String id, String summary, String description, String location, String timeZone) {#ExtendedCalendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public ExtendedCalendar(String id, String summary, String description, String location, String timeZone)
```


Initializes a new instance of the ExtendedCalendar class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | Identifier of the resource. |
| summary | java.lang.String | Title of the calendar. |
| description | java.lang.String | Description of the calendar. |
| location | java.lang.String | Geographic location of the calendar as free-form text. |
| timeZone | java.lang.String | The time zone of the calendar. |

### ExtendedCalendar(String id, String summary, String description, String location, String timeZone, String summaryOverride, String colorId, String backgroundColor, String foregroundColor, boolean hidden, boolean selected, int accessRole, System.Collections.Generic.KeyValuePair<Integer,Integer>[] defaultReminders, boolean primary) {#ExtendedCalendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-boolean-int-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----boolean-}
```
public ExtendedCalendar(String id, String summary, String description, String location, String timeZone, String summaryOverride, String colorId, String backgroundColor, String foregroundColor, boolean hidden, boolean selected, int accessRole, System.Collections.Generic.KeyValuePair<Integer,Integer>[] defaultReminders, boolean primary)
```


Initializes a new instance of the ExtendedCalendar class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | Identifier of the resource. |
| summary | java.lang.String | Title of the calendar. |
| description | java.lang.String | Description of the calendar. |
| location | java.lang.String | Geographic location of the calendar as free-form text. |
| timeZone | java.lang.String | The time zone of the calendar. |
| summaryOverride | java.lang.String | The summary that the authenticated user has set for this calendar. |
| colorId | java.lang.String | The color of the calendar. This is an ID referring to an entry in the 'calendar' section of the colors definition (see the 'colors' endpoint). |
| backgroundColor | java.lang.String | The main color of the calendar in the format '\#0088aa'. This property supersedes the index-based colorId property. |
| foregroundColor | java.lang.String | The foreground color of the calendar in the format '\#ffffff'. This property supersedes the index-based colorId property. |
| hidden | boolean | Whether the calendar has been hidden from the list. The default is False. |
| selected | boolean | Whether the calendar content shows up in the calendar UI. The default is False. |
| accessRole | int | The effective access role that the authenticated user has on the calendar. Read-only. Possible values are: |
| defaultReminders | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Integer,java.lang.Integer>[] | The default reminders that the authenticated user has for this calendar. |
| primary | boolean | Whether the calendar is the primary calendar of the authenticated user. Read-only. The default is False. |

### ExtendedCalendar(String id, String eTag, String summary, String description, String location, String timeZone, String summaryOverride, String colorId, String backgroundColor, String foregroundColor, boolean hidden, boolean selected, int accessRole, System.Collections.Generic.KeyValuePair<Integer,Integer>[] defaultReminders, boolean primary) {#ExtendedCalendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-boolean-int-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----boolean-}
```
public ExtendedCalendar(String id, String eTag, String summary, String description, String location, String timeZone, String summaryOverride, String colorId, String backgroundColor, String foregroundColor, boolean hidden, boolean selected, int accessRole, System.Collections.Generic.KeyValuePair<Integer,Integer>[] defaultReminders, boolean primary)
```


Initializes a new instance of the ExtendedCalendar class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | Identifier of the resource. |
| eTag | java.lang.String | An entity tag |
| summary | java.lang.String | Title of the calendar. |
| description | java.lang.String | Description of the calendar. |
| location | java.lang.String | Geographic location of the calendar as free-form text. |
| timeZone | java.lang.String | The time zone of the calendar. |
| summaryOverride | java.lang.String | The summary that the authenticated user has set for this calendar. |
| colorId | java.lang.String | The color of the calendar. This is an ID referring to an entry in the 'calendar' section of the colors definition (see the 'colors' endpoint). |
| backgroundColor | java.lang.String | The main color of the calendar in the format '\#0088aa'. This property supersedes the index-based colorId property. |
| foregroundColor | java.lang.String | The foreground color of the calendar in the format '\#ffffff'. This property supersedes the index-based colorId property. |
| hidden | boolean | Whether the calendar has been hidden from the list. The default is False. |
| selected | boolean | Whether the calendar content shows up in the calendar UI. The default is False. |
| accessRole | int | The effective access role that the authenticated user has on the calendar. Read-only. Possible values are: |
| defaultReminders | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Integer,java.lang.Integer>[] | The default reminders that the authenticated user has for this calendar. |
| primary | boolean | Whether the calendar is the primary calendar of the authenticated user. Read-only. The default is False. |

### CALENDAR_KIND {#CALENDAR-KIND}
```
public static final String CALENDAR_KIND
```


Type of the resource 'calendar\#calendar'.

### EXTENDED_CALENDAR_KIND {#EXTENDED-CALENDAR-KIND}
```
public static final String EXTENDED_CALENDAR_KIND
```


Type of the resource 'calendar\#calendarListEntry'.

### LIST_KIND {#LIST-KIND}
```
public static final String LIST_KIND
```


Type of the resources list 'calendar\#calendarList'.

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
### getAccessRole() {#getAccessRole--}
```
public int getAccessRole()
```


The effective access role that the authenticated user has on the calendar. Read-only. Possible values are:

**Returns:**
int
### getBackgroundColor() {#getBackgroundColor--}
```
public String getBackgroundColor()
```


The main color of the calendar in the format '\#0088aa'. This property supersedes the index-based colorId property.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorId() {#getColorId--}
```
public String getColorId()
```


The color of the calendar. This is an ID referring to an entry in the 'calendar' section of the colors definition (see the 'colors' endpoint).

**Returns:**
java.lang.String
### getConferenceProperties() {#getConferenceProperties--}
```
public ConferenceProperties getConferenceProperties()
```


Gets conferencing properties for this calendar.

**Returns:**
[ConferenceProperties](../../com.aspose.email/conferenceproperties)
### getDefaultReminders() {#getDefaultReminders--}
```
public System.Collections.Generic.KeyValuePair<Integer,Integer>[] getDefaultReminders()
```


The default reminders that the authenticated user has for this calendar.

**Returns:**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Integer,java.lang.Integer>[]
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
### getForegroundColor() {#getForegroundColor--}
```
public String getForegroundColor()
```


The foreground color of the calendar in the format '\#ffffff'. This property supersedes the index-based colorId property.

**Returns:**
java.lang.String
### getHidden() {#getHidden--}
```
public boolean getHidden()
```


Whether the calendar has been hidden from the list. The default is False.

**Returns:**
boolean
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
### getNotificationSettings() {#getNotificationSettings--}
```
public System.Collections.Generic.KeyValuePair<Integer,Integer>[] getNotificationSettings()
```


The notifications that the authenticated user is receiving for this calendar.

**Returns:**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Integer,java.lang.Integer>[]
### getPrimary() {#getPrimary--}
```
public boolean getPrimary()
```


Whether the calendar is the primary calendar of the authenticated user. Read-only. The default is False.

**Returns:**
boolean
### getSelected() {#getSelected--}
```
public boolean getSelected()
```


Whether the calendar content shows up in the calendar UI. The default is False.

**Returns:**
boolean
### getSummary() {#getSummary--}
```
public String getSummary()
```


Title of the calendar.

**Returns:**
java.lang.String
### getSummaryOverride() {#getSummaryOverride--}
```
public String getSummaryOverride()
```


The summary that the authenticated user has set for this calendar.

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




### setBackgroundColor(String value) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String value)
```


The main color of the calendar in the format '\#0088aa'. This property supersedes the index-based colorId property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setColorId(String value) {#setColorId-java.lang.String-}
```
public void setColorId(String value)
```


The color of the calendar. This is an ID referring to an entry in the 'calendar' section of the colors definition (see the 'colors' endpoint).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDefaultReminders(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value) {#setDefaultReminders-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----}
```
public void setDefaultReminders(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value)
```


The default reminders that the authenticated user has for this calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Integer,java.lang.Integer>[] |  |

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

### setForegroundColor(String value) {#setForegroundColor-java.lang.String-}
```
public void setForegroundColor(String value)
```


The foreground color of the calendar in the format '\#ffffff'. This property supersedes the index-based colorId property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setHidden(boolean value) {#setHidden-boolean-}
```
public void setHidden(boolean value)
```


Whether the calendar has been hidden from the list. The default is False.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### setNotificationSettings(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value) {#setNotificationSettings-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----}
```
public void setNotificationSettings(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value)
```


The notifications that the authenticated user is receiving for this calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Integer,java.lang.Integer>[] |  |

### setPrimary(boolean value) {#setPrimary-boolean-}
```
public void setPrimary(boolean value)
```


Whether the calendar is the primary calendar of the authenticated user. Read-only. The default is False.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSelected(boolean value) {#setSelected-boolean-}
```
public void setSelected(boolean value)
```


Whether the calendar content shows up in the calendar UI. The default is False.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSummary(String value) {#setSummary-java.lang.String-}
```
public void setSummary(String value)
```


Title of the calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSummaryOverride(String value) {#setSummaryOverride-java.lang.String-}
```
public void setSummaryOverride(String value)
```


The summary that the authenticated user has set for this calendar.

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

