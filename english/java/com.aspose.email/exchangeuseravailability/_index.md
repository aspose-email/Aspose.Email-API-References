---
title: ExchangeUserAvailability
second_title: Aspose.Email for Java API Reference
description: Represents user availability information
type: docs
weight: 230
url: /java/com.aspose.email/exchangeuseravailability/
---

**Inheritance:**
java.lang.Object
```
public final class ExchangeUserAvailability
```

Represents user availability information
## Constructors

| Constructor | Description |
| --- | --- |
| [ExchangeUserAvailability()](#ExchangeUserAvailability--) | Initializes a new instance of the [ExchangeUserAvailability](../../com.aspose.email/exchangeuseravailability) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendarAppointments()](#getCalendarAppointments--) | Gets the calendar appointments in the user's calendar. |
| [getClass()](#getClass--) |  |
| [getUser()](#getUser--) | Gets the user smtp address. |
| [getWorkingHours()](#getWorkingHours--) | Gets the working hours. |
| [getWorkingHours(Date date)](#getWorkingHours-java.util.Date-) | Gets the working hours in the specified date taking into account the user's timezone. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExchangeUserAvailability() {#ExchangeUserAvailability--}
```
public ExchangeUserAvailability()
```


Initializes a new instance of the [ExchangeUserAvailability](../../com.aspose.email/exchangeuseravailability) class.

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
### getCalendarAppointments() {#getCalendarAppointments--}
```
public final ExchangeCalendarEventCollection getCalendarAppointments()
```


Gets the calendar appointments in the user's calendar.

**Returns:**
[ExchangeCalendarEventCollection](../../com.aspose.email/exchangecalendareventcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getUser() {#getUser--}
```
public final String getUser()
```


Gets the user smtp address.

**Returns:**
java.lang.String
### getWorkingHours() {#getWorkingHours--}
```
public final ExchangeUserWorkingHoursCollection getWorkingHours()
```


Gets the working hours.

**Returns:**
[ExchangeUserWorkingHoursCollection](../../com.aspose.email/exchangeuserworkinghourscollection)
### getWorkingHours(Date date) {#getWorkingHours-java.util.Date-}
```
public final DateRange getWorkingHours(Date date)
```


Gets the working hours in the specified date taking into account the user's timezone.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| date | java.util.Date | The date to get information for. |

**Returns:**
[DateRange](../../com.aspose.email/daterange) - A start and end time of the working day for the specified date.
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

