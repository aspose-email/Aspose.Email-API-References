---
title: ExchangeUserAvailability
second_title: Aspose.Email for Java API Reference
description:  Represents user availability information
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
| [getUser()](#getUser--) | Gets the user smtp address. |
| [getCalendarAppointments()](#getCalendarAppointments--) | Gets the calendar appointments in the user's calendar. |
| [getWorkingHours()](#getWorkingHours--) | Gets the working hours. |
| [getWorkingHours(Date date)](#getWorkingHours-java.util.Date-) | Gets the working hours in the specified date taking into account the user's timezone. |
### ExchangeUserAvailability() {#ExchangeUserAvailability--}
```
public ExchangeUserAvailability()
```


Initializes a new instance of the [ExchangeUserAvailability](../../com.aspose.email/exchangeuseravailability) class.

### getUser() {#getUser--}
```
public final String getUser()
```


Gets the user smtp address.

**Returns:**
java.lang.String
### getCalendarAppointments() {#getCalendarAppointments--}
```
public final ExchangeCalendarEventCollection getCalendarAppointments()
```


Gets the calendar appointments in the user's calendar.

**Returns:**
[ExchangeCalendarEventCollection](../../com.aspose.email/exchangecalendareventcollection)
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
