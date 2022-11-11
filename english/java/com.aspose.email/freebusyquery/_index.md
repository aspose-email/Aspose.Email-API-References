---
title: FreebusyQuery
second_title: Aspose.Email for Java API Reference
description: Request free/busy information for a set of calendars.
type: docs
weight: 267
url: /java/com.aspose.email/freebusyquery/
---
**Inheritance:**
java.lang.Object
```
public class FreebusyQuery
```

Request free/busy information for a set of calendars.
## Constructors

| Constructor | Description |
| --- | --- |
| [FreebusyQuery()](#FreebusyQuery--) | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery(Date timeMin, Date timeMax, Iterable<String> items)](#FreebusyQuery-java.util.Date-java.util.Date-java.lang.Iterable-java.lang.String--) | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery(Date timeMin, Date timeMax, String timeZone, Iterable<String> items)](#FreebusyQuery-java.util.Date-java.util.Date-java.lang.String-java.lang.Iterable-java.lang.String--) | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery(Date timeMin, Date timeMax, String timeZone, Integer groupExpansionMax, Integer calendarExpansionMax, Iterable<String> items)](#FreebusyQuery-java.util.Date-java.util.Date-java.lang.String-java.lang.Integer-java.lang.Integer-java.lang.Iterable-java.lang.String--) | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery(Date timeMin, Date timeMax, String[] items)](#FreebusyQuery-java.util.Date-java.util.Date-java.lang.String...-) | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery(Date timeMin, Date timeMax, String timeZone, String[] items)](#FreebusyQuery-java.util.Date-java.util.Date-java.lang.String-java.lang.String...-) | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery(Date timeMin, Date timeMax, String timeZone, Integer groupExpansionMax, Integer calendarExpansionMax, String[] items)](#FreebusyQuery-java.util.Date-java.util.Date-java.lang.String-java.lang.Integer-java.lang.Integer-java.lang.String...-) | Initializes a new instance of the FreebusyQuery class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendarExpansionMax()](#getCalendarExpansionMax--) | Maximal number of calendars for which FreeBusy information is to be provided. |
| [getClass()](#getClass--) |  |
| [getGroupExpansionMax()](#getGroupExpansionMax--) | Maximal number of calendar identifiers to be provided for a single group. |
| [getItems()](#getItems--) | List of calendars and/or groups to query. |
| [getTimeMax()](#getTimeMax--) | The end of the interval for the query. |
| [getTimeMin()](#getTimeMin--) | The start of the interval for the query. |
| [getTimeZone()](#getTimeZone--) | Time zone used in the response. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendarExpansionMax(Integer value)](#setCalendarExpansionMax-java.lang.Integer-) | Maximal number of calendars for which FreeBusy information is to be provided. |
| [setGroupExpansionMax(Integer value)](#setGroupExpansionMax-java.lang.Integer-) | Maximal number of calendar identifiers to be provided for a single group. |
| [setTimeMax(Date value)](#setTimeMax-java.util.Date-) | The end of the interval for the query. |
| [setTimeMin(Date value)](#setTimeMin-java.util.Date-) | The start of the interval for the query. |
| [setTimeZone(String value)](#setTimeZone-java.lang.String-) | Time zone used in the response. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FreebusyQuery() {#FreebusyQuery--}
```
public FreebusyQuery()
```


Initializes a new instance of the FreebusyQuery class.

### FreebusyQuery(Date timeMin, Date timeMax, Iterable<String> items) {#FreebusyQuery-java.util.Date-java.util.Date-java.lang.Iterable-java.lang.String--}
```
public FreebusyQuery(Date timeMin, Date timeMax, Iterable<String> items)
```


Initializes a new instance of the FreebusyQuery class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeMin | java.util.Date | The end of the interval for the query. |
| timeMax | java.util.Date | The end of the interval for the query. |
| items | java.lang.Iterable<java.lang.String> | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

### FreebusyQuery(Date timeMin, Date timeMax, String timeZone, Iterable<String> items) {#FreebusyQuery-java.util.Date-java.util.Date-java.lang.String-java.lang.Iterable-java.lang.String--}
```
public FreebusyQuery(Date timeMin, Date timeMax, String timeZone, Iterable<String> items)
```


Initializes a new instance of the FreebusyQuery class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeMin | java.util.Date | The end of the interval for the query. |
| timeMax | java.util.Date | The end of the interval for the query. |
| timeZone | java.lang.String | Time zone used in the response. Optional. The default is UTC. |
| items | java.lang.Iterable<java.lang.String> | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

### FreebusyQuery(Date timeMin, Date timeMax, String timeZone, Integer groupExpansionMax, Integer calendarExpansionMax, Iterable<String> items) {#FreebusyQuery-java.util.Date-java.util.Date-java.lang.String-java.lang.Integer-java.lang.Integer-java.lang.Iterable-java.lang.String--}
```
public FreebusyQuery(Date timeMin, Date timeMax, String timeZone, Integer groupExpansionMax, Integer calendarExpansionMax, Iterable<String> items)
```


Initializes a new instance of the FreebusyQuery class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeMin | java.util.Date | The end of the interval for the query. |
| timeMax | java.util.Date | The end of the interval for the query. |
| timeZone | java.lang.String | Time zone used in the response. Optional. The default is UTC. |
| groupExpansionMax | java.lang.Integer | Maximal number of calendar identifiers to be provided for a single group. Optional. An error will be returned for a group with more members than this value. |
| calendarExpansionMax | java.lang.Integer | Maximal number of calendars for which FreeBusy information is to be provided. Optional. |
| items | java.lang.Iterable<java.lang.String> | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

### FreebusyQuery(Date timeMin, Date timeMax, String[] items) {#FreebusyQuery-java.util.Date-java.util.Date-java.lang.String...-}
```
public FreebusyQuery(Date timeMin, Date timeMax, String[] items)
```


Initializes a new instance of the FreebusyQuery class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeMin | java.util.Date | The end of the interval for the query. |
| timeMax | java.util.Date | The end of the interval for the query. |
| items | java.lang.String[] | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

### FreebusyQuery(Date timeMin, Date timeMax, String timeZone, String[] items) {#FreebusyQuery-java.util.Date-java.util.Date-java.lang.String-java.lang.String...-}
```
public FreebusyQuery(Date timeMin, Date timeMax, String timeZone, String[] items)
```


Initializes a new instance of the FreebusyQuery class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeMin | java.util.Date | The end of the interval for the query. |
| timeMax | java.util.Date | The end of the interval for the query. |
| timeZone | java.lang.String | Time zone used in the response. Optional. The default is UTC. |
| items | java.lang.String[] | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

### FreebusyQuery(Date timeMin, Date timeMax, String timeZone, Integer groupExpansionMax, Integer calendarExpansionMax, String[] items) {#FreebusyQuery-java.util.Date-java.util.Date-java.lang.String-java.lang.Integer-java.lang.Integer-java.lang.String...-}
```
public FreebusyQuery(Date timeMin, Date timeMax, String timeZone, Integer groupExpansionMax, Integer calendarExpansionMax, String[] items)
```


Initializes a new instance of the FreebusyQuery class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeMin | java.util.Date | The end of the interval for the query. |
| timeMax | java.util.Date | The end of the interval for the query. |
| timeZone | java.lang.String | Time zone used in the response. Optional. The default is UTC. |
| groupExpansionMax | java.lang.Integer | Maximal number of calendar identifiers to be provided for a single group. Optional. An error will be returned for a group with more members than this value. |
| calendarExpansionMax | java.lang.Integer | Maximal number of calendars for which FreeBusy information is to be provided. Optional. |
| items | java.lang.String[] | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

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
### getCalendarExpansionMax() {#getCalendarExpansionMax--}
```
public final Integer getCalendarExpansionMax()
```


Maximal number of calendars for which FreeBusy information is to be provided. Optional.

**Returns:**
java.lang.Integer
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGroupExpansionMax() {#getGroupExpansionMax--}
```
public final Integer getGroupExpansionMax()
```


Maximal number of calendar identifiers to be provided for a single group. Optional. An error will be returned for a group with more members than this value.

**Returns:**
java.lang.Integer
### getItems() {#getItems--}
```
public final List<String> getItems()
```


List of calendars and/or groups to query. Contains identifiers of a calendar or a group.

**Returns:**
java.util.List<java.lang.String>
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
### getTimeZone() {#getTimeZone--}
```
public final String getTimeZone()
```


Time zone used in the response. Optional. The default is UTC.

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




### setCalendarExpansionMax(Integer value) {#setCalendarExpansionMax-java.lang.Integer-}
```
public final void setCalendarExpansionMax(Integer value)
```


Maximal number of calendars for which FreeBusy information is to be provided. Optional.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### setGroupExpansionMax(Integer value) {#setGroupExpansionMax-java.lang.Integer-}
```
public final void setGroupExpansionMax(Integer value)
```


Maximal number of calendar identifiers to be provided for a single group. Optional. An error will be returned for a group with more members than this value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

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

### setTimeZone(String value) {#setTimeZone-java.lang.String-}
```
public final void setTimeZone(String value)
```


Time zone used in the response. Optional. The default is UTC.

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

