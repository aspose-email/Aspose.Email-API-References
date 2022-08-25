---
title: ExtendedCalendar
second_title: Aspose.Email for Java API Reference
description:  A set of extended metadata such as a colors for a single calendar.
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
| [EXTENDED_CALENDAR_KIND](#EXTENDED-CALENDAR-KIND) | Type of the resource 'calendar\#calendarListEntry'. |
| [LIST_KIND](#LIST-KIND) | Type of the resources list 'calendar\#calendarList'. |
## Methods

| Method | Description |
| --- | --- |
| [getSummaryOverride()](#getSummaryOverride--) | The summary that the authenticated user has set for this calendar. |
| [setSummaryOverride(String value)](#setSummaryOverride-java.lang.String-) | The summary that the authenticated user has set for this calendar. |
| [getColorId()](#getColorId--) | The color of the calendar. |
| [setColorId(String value)](#setColorId-java.lang.String-) | The color of the calendar. |
| [getBackgroundColor()](#getBackgroundColor--) | The main color of the calendar in the format '\#0088aa'. |
| [setBackgroundColor(String value)](#setBackgroundColor-java.lang.String-) | The main color of the calendar in the format '\#0088aa'. |
| [getForegroundColor()](#getForegroundColor--) | The foreground color of the calendar in the format '\#ffffff'. |
| [setForegroundColor(String value)](#setForegroundColor-java.lang.String-) | The foreground color of the calendar in the format '\#ffffff'. |
| [getHidden()](#getHidden--) | Whether the calendar has been hidden from the list. |
| [setHidden(boolean value)](#setHidden-boolean-) | Whether the calendar has been hidden from the list. |
| [getSelected()](#getSelected--) | Whether the calendar content shows up in the calendar UI. |
| [setSelected(boolean value)](#setSelected-boolean-) | Whether the calendar content shows up in the calendar UI. |
| [getAccessRole()](#getAccessRole--) | The effective access role that the authenticated user has on the calendar. |
| [getDefaultReminders()](#getDefaultReminders--) | The default reminders that the authenticated user has for this calendar. |
| [setDefaultReminders(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value)](#setDefaultReminders-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----) | The default reminders that the authenticated user has for this calendar. |
| [getNotificationSettings()](#getNotificationSettings--) | The notifications that the authenticated user is receiving for this calendar. |
| [setNotificationSettings(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value)](#setNotificationSettings-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----) | The notifications that the authenticated user is receiving for this calendar. |
| [getPrimary()](#getPrimary--) | Whether the calendar is the primary calendar of the authenticated user. |
| [setPrimary(boolean value)](#setPrimary-boolean-) | Whether the calendar is the primary calendar of the authenticated user. |
| [toString()](#toString--) | Returns a string which represents the object instance. |
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

### getSummaryOverride() {#getSummaryOverride--}
```
public String getSummaryOverride()
```


The summary that the authenticated user has set for this calendar.

**Returns:**
java.lang.String
### setSummaryOverride(String value) {#setSummaryOverride-java.lang.String-}
```
public void setSummaryOverride(String value)
```


The summary that the authenticated user has set for this calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getColorId() {#getColorId--}
```
public String getColorId()
```


The color of the calendar. This is an ID referring to an entry in the 'calendar' section of the colors definition (see the 'colors' endpoint).

**Returns:**
java.lang.String
### setColorId(String value) {#setColorId-java.lang.String-}
```
public void setColorId(String value)
```


The color of the calendar. This is an ID referring to an entry in the 'calendar' section of the colors definition (see the 'colors' endpoint).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public String getBackgroundColor()
```


The main color of the calendar in the format '\#0088aa'. This property supersedes the index-based colorId property.

**Returns:**
java.lang.String
### setBackgroundColor(String value) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String value)
```


The main color of the calendar in the format '\#0088aa'. This property supersedes the index-based colorId property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getForegroundColor() {#getForegroundColor--}
```
public String getForegroundColor()
```


The foreground color of the calendar in the format '\#ffffff'. This property supersedes the index-based colorId property.

**Returns:**
java.lang.String
### setForegroundColor(String value) {#setForegroundColor-java.lang.String-}
```
public void setForegroundColor(String value)
```


The foreground color of the calendar in the format '\#ffffff'. This property supersedes the index-based colorId property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHidden() {#getHidden--}
```
public boolean getHidden()
```


Whether the calendar has been hidden from the list. The default is False.

**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public void setHidden(boolean value)
```


Whether the calendar has been hidden from the list. The default is False.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSelected() {#getSelected--}
```
public boolean getSelected()
```


Whether the calendar content shows up in the calendar UI. The default is False.

**Returns:**
boolean
### setSelected(boolean value) {#setSelected-boolean-}
```
public void setSelected(boolean value)
```


Whether the calendar content shows up in the calendar UI. The default is False.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAccessRole() {#getAccessRole--}
```
public int getAccessRole()
```


The effective access role that the authenticated user has on the calendar. Read-only. Possible values are:

**Returns:**
int
### getDefaultReminders() {#getDefaultReminders--}
```
public System.Collections.Generic.KeyValuePair<Integer,Integer>[] getDefaultReminders()
```


The default reminders that the authenticated user has for this calendar.

**Returns:**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Integer,java.lang.Integer>[]
### setDefaultReminders(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value) {#setDefaultReminders-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----}
```
public void setDefaultReminders(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value)
```


The default reminders that the authenticated user has for this calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Integer,java.lang.Integer>[] |  |

### getNotificationSettings() {#getNotificationSettings--}
```
public System.Collections.Generic.KeyValuePair<Integer,Integer>[] getNotificationSettings()
```


The notifications that the authenticated user is receiving for this calendar.

**Returns:**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Integer,java.lang.Integer>[]
### setNotificationSettings(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value) {#setNotificationSettings-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.Integer-java.lang.Integer----}
```
public void setNotificationSettings(System.Collections.Generic.KeyValuePair<Integer,Integer>[] value)
```


The notifications that the authenticated user is receiving for this calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Integer,java.lang.Integer>[] |  |

### getPrimary() {#getPrimary--}
```
public boolean getPrimary()
```


Whether the calendar is the primary calendar of the authenticated user. Read-only. The default is False.

**Returns:**
boolean
### setPrimary(boolean value) {#setPrimary-boolean-}
```
public void setPrimary(boolean value)
```


Whether the calendar is the primary calendar of the authenticated user. Read-only. The default is False.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string which represents the object instance.

**Returns:**
java.lang.String - Returns a string which represents the object instance.
