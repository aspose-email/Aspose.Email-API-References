---
title: FreebusyResponse
second_title: Aspose.Email for Java API Reference
description: Freebusy response
type: docs
weight: 268
url: /java/com.aspose.email/freebusyresponse/
---

**Inheritance:**
java.lang.Object
```
public class FreebusyResponse
```

Freebusy response
## Constructors

| Constructor | Description |
| --- | --- |
| [FreebusyResponse()](#FreebusyResponse--) | Initializes a new instance of the FreebusyResponse class. |
| [FreebusyResponse(Date timeMin, Date timeMax)](#FreebusyResponse-java.util.Date-java.util.Date-) | Initializes a new instance of the FreebusyResponse class. |
| [FreebusyResponse(Date timeMin, Date timeMax, System.Collections.Generic.Dictionary<String,FreebusyGroupInfo> groups, System.Collections.Generic.Dictionary<String,FreebusyCalendarInfo> calendars)](#FreebusyResponse-java.util.Date-java.util.Date-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.email.FreebusyGroupInfo--com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.email.FreebusyCalendarInfo--) | Initializes a new instance of the FreebusyResponse class. |
## Fields

| Field | Description |
| --- | --- |
| [KIND](#KIND) | Type of the resource 'calendar\#freeBusy'. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendars()](#getCalendars--) | List of free/busy information for calendars. |
| [getClass()](#getClass--) |  |
| [getGroups()](#getGroups--) | Expansion of groups. |
| [getTimeMax()](#getTimeMax--) | The end of the interval for the query. |
| [getTimeMin()](#getTimeMin--) | The start of the interval for the query. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setTimeMax(Date value)](#setTimeMax-java.util.Date-) | The end of the interval for the query. |
| [setTimeMin(Date value)](#setTimeMin-java.util.Date-) | The start of the interval for the query. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FreebusyResponse() {#FreebusyResponse--}
```
public FreebusyResponse()
```


Initializes a new instance of the FreebusyResponse class.

### FreebusyResponse(Date timeMin, Date timeMax) {#FreebusyResponse-java.util.Date-java.util.Date-}
```
public FreebusyResponse(Date timeMin, Date timeMax)
```


Initializes a new instance of the FreebusyResponse class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeMin | java.util.Date | The start of the interval for the query. |
| timeMax | java.util.Date | The end of the interval for the query. |

### FreebusyResponse(Date timeMin, Date timeMax, System.Collections.Generic.Dictionary<String,FreebusyGroupInfo> groups, System.Collections.Generic.Dictionary<String,FreebusyCalendarInfo> calendars) {#FreebusyResponse-java.util.Date-java.util.Date-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.email.FreebusyGroupInfo--com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.email.FreebusyCalendarInfo--}
```
public FreebusyResponse(Date timeMin, Date timeMax, System.Collections.Generic.Dictionary<String,FreebusyGroupInfo> groups, System.Collections.Generic.Dictionary<String,FreebusyCalendarInfo> calendars)
```


Initializes a new instance of the FreebusyResponse class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeMin | java.util.Date | The start of the interval for the query. |
| timeMax | java.util.Date | The end of the interval for the query. |
| groups | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.email.FreebusyGroupInfo> | Expansion of groups. |
| calendars | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.email.FreebusyCalendarInfo> | List of free/busy information for calendars. |

### KIND {#KIND}
```
public static final String KIND
```


Type of the resource 'calendar\#freeBusy'.

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
### getCalendars() {#getCalendars--}
```
public final System.Collections.Generic.Dictionary<String,FreebusyCalendarInfo> getCalendars()
```


List of free/busy information for calendars.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.email.FreebusyCalendarInfo>
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGroups() {#getGroups--}
```
public final System.Collections.Generic.Dictionary<String,FreebusyGroupInfo> getGroups()
```


Expansion of groups.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.email.FreebusyGroupInfo>
### getTimeMax() {#getTimeMax--}
```
public final Date getTimeMax()
```


The end of the interval for the query.

**Returns:**
java.util.Date
### getTimeMin() {#getTimeMin--}
```
public final Date getTimeMin()
```


The start of the interval for the query.

**Returns:**
java.util.Date
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




### setTimeMax(Date value) {#setTimeMax-java.util.Date-}
```
public final void setTimeMax(Date value)
```


The end of the interval for the query.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setTimeMin(Date value) {#setTimeMin-java.util.Date-}
```
public final void setTimeMin(Date value)
```


The start of the interval for the query.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

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

