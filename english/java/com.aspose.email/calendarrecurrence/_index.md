---
title: CalendarRecurrence
second_title: Aspose.Email for Java API Reference
description: The main class represents an iCalendar recurrence.
type: docs
weight: 96
url: /java/com.aspose.email/calendarrecurrence/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class CalendarRecurrence implements System.IEquatable<CalendarRecurrence>
```

The main class, represents an iCalendar recurrence.
## Constructors

| Constructor | Description |
| --- | --- |
| [CalendarRecurrence()](#CalendarRecurrence--) | Initializes a new instance of the [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) class. |
| [CalendarRecurrence(String pattern)](#CalendarRecurrence-java.lang.String-) | Initializes a new instance of the [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(CalendarRecurrence other)](#equals-com.aspose.email.CalendarRecurrence-) | Determines whether the specified [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) is equal to this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [fromRecurrence(System.Xml.XmlElement xmlElement)](#fromRecurrence-com.aspose.ms.System.Xml.XmlElement-) | Gets a recurrence pattern from XmlElement. |
| [fromRecurrence(String xmlString)](#fromRecurrence-java.lang.String-) | Gets a recurrence pattern from XML pattern string. |
| [fromiCalendar(String pattern)](#fromiCalendar-java.lang.String-) | Gets a recurrence pattern from iCalendar string. |
| [generateOccurrences()](#generateOccurrences--) | Generates the occurrences. |
| [generateOccurrences(int nNextOccurrences)](#generateOccurrences-int-) | Generates n next occurrences. |
| [generateOccurrences(Date rangeStart, Date rangeEnd)](#generateOccurrences-java.util.Date-java.util.Date-) | Generates the occurrences. |
| [generateOccurrences(Date rangeStart, Date rangeEnd, int nNextOccurrences)](#generateOccurrences-java.util.Date-java.util.Date-int-) | Generates n next occurrences. |
| [getClass()](#getClass--) |  |
| [getEndDate()](#getEndDate--) | Gets or sets the end date. |
| [getExDates()](#getExDates--) | Gets the ex dates. |
| [getExRules()](#getExRules--) | Gets the ex rules. |
| [getRDates()](#getRDates--) | Gets the R dates. |
| [getRRules()](#getRRules--) | Gets the R rules. |
| [getStartDate()](#getStartDate--) | Gets or sets the start date. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(CalendarRecurrence left, CalendarRecurrence right)](#op-Equality-com.aspose.email.CalendarRecurrence-com.aspose.email.CalendarRecurrence-) | Implements the operator ==. |
| [op_Inequality(CalendarRecurrence left, CalendarRecurrence right)](#op-Inequality-com.aspose.email.CalendarRecurrence-com.aspose.email.CalendarRecurrence-) | Implements the operator !=. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Gets or sets the end date. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets the start date. |
| [toString()](#toString--) |  |
| [toiCalendar()](#toiCalendar--) | To iCalendar string. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CalendarRecurrence() {#CalendarRecurrence--}
```
public CalendarRecurrence()
```


Initializes a new instance of the [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) class.

### CalendarRecurrence(String pattern) {#CalendarRecurrence-java.lang.String-}
```
public CalendarRecurrence(String pattern)
```


Initializes a new instance of the [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pattern | java.lang.String | The pattern. |

### equals(CalendarRecurrence other) {#equals-com.aspose.email.CalendarRecurrence-}
```
public boolean equals(CalendarRecurrence other)
```


Determines whether the specified [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) to compare with this instance. |

**Returns:**
boolean -  true  if the specified [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) is equal to this instance; otherwise,  false .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object is equal to the current Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with the current Object. |

**Returns:**
boolean - Returns a boolean indicating if the passed in object obj is Equal to this.
### fromRecurrence(System.Xml.XmlElement xmlElement) {#fromRecurrence-com.aspose.ms.System.Xml.XmlElement-}
```
public static CalendarRecurrence fromRecurrence(System.Xml.XmlElement xmlElement)
```


Gets a recurrence pattern from XmlElement.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlElement | com.aspose.ms.System.Xml.XmlElement | XmlElementXmlElement of pattern. |

**Returns:**
[CalendarRecurrence](../../com.aspose.email/calendarrecurrence) - Recurrence pattern[CalendarRecurrence](../../com.aspose.email/calendarrecurrence).
### fromRecurrence(String xmlString) {#fromRecurrence-java.lang.String-}
```
public static CalendarRecurrence fromRecurrence(String xmlString)
```


Gets a recurrence pattern from XML pattern string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlString | java.lang.String | XML stringString of pattern. |

**Returns:**
[CalendarRecurrence](../../com.aspose.email/calendarrecurrence) - Recurrence pattern[CalendarRecurrence](../../com.aspose.email/calendarrecurrence).
### fromiCalendar(String pattern) {#fromiCalendar-java.lang.String-}
```
public static CalendarRecurrence fromiCalendar(String pattern)
```


Gets a recurrence pattern from iCalendar string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pattern | java.lang.String | StringString representation of iCalendar. |

**Returns:**
[CalendarRecurrence](../../com.aspose.email/calendarrecurrence) - Recurrence pattern[CalendarRecurrence](../../com.aspose.email/calendarrecurrence).
### generateOccurrences() {#generateOccurrences--}
```
public final DateCollection generateOccurrences()
```


Generates the occurrences.

**Returns:**
[DateCollection](../../com.aspose.email/datecollection) - Collection of dates[DateCollection](../../com.aspose.email/datecollection).
### generateOccurrences(int nNextOccurrences) {#generateOccurrences-int-}
```
public final DateCollection generateOccurrences(int nNextOccurrences)
```


Generates n next occurrences.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nNextOccurrences | int | The amount of needed occurrences. |

**Returns:**
[DateCollection](../../com.aspose.email/datecollection) - Collection of dates[DateCollection](../../com.aspose.email/datecollection).
### generateOccurrences(Date rangeStart, Date rangeEnd) {#generateOccurrences-java.util.Date-java.util.Date-}
```
public final DateCollection generateOccurrences(Date rangeStart, Date rangeEnd)
```


Generates the occurrences.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rangeStart | java.util.Date | The range start. |
| rangeEnd | java.util.Date | The range end. |

**Returns:**
[DateCollection](../../com.aspose.email/datecollection) - Collection of dates[DateCollection](../../com.aspose.email/datecollection).
### generateOccurrences(Date rangeStart, Date rangeEnd, int nNextOccurrences) {#generateOccurrences-java.util.Date-java.util.Date-int-}
```
public final DateCollection generateOccurrences(Date rangeStart, Date rangeEnd, int nNextOccurrences)
```


Generates n next occurrences.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rangeStart | java.util.Date | The range start. |
| rangeEnd | java.util.Date | The range end. |
| nNextOccurrences | int | The amount of needed occurrences. |

**Returns:**
[DateCollection](../../com.aspose.email/datecollection) - Collection of dates[DateCollection](../../com.aspose.email/datecollection).
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Gets or sets the end date.

Value: The end date.

**Returns:**
java.util.Date
### getExDates() {#getExDates--}
```
public final DateCollection getExDates()
```


Gets the ex dates.

Value: The ex dates.

**Returns:**
[DateCollection](../../com.aspose.email/datecollection)
### getExRules() {#getExRules--}
```
public final RecurrenceRuleCollection getExRules()
```


Gets the ex rules.

Value: The ex rules.

**Returns:**
[RecurrenceRuleCollection](../../com.aspose.email/recurrencerulecollection)
### getRDates() {#getRDates--}
```
public final DateCollection getRDates()
```


Gets the R dates.

Value: The R dates.

**Returns:**
[DateCollection](../../com.aspose.email/datecollection)
### getRRules() {#getRRules--}
```
public final RecurrenceRuleCollection getRRules()
```


Gets the R rules.

Value: The R rules.

**Returns:**
[RecurrenceRuleCollection](../../com.aspose.email/recurrencerulecollection)
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets the start date.

Value: The start date.

**Returns:**
java.util.Date
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(CalendarRecurrence left, CalendarRecurrence right) {#op-Equality-com.aspose.email.CalendarRecurrence-com.aspose.email.CalendarRecurrence-}
```
public static boolean op_Equality(CalendarRecurrence left, CalendarRecurrence right)
```


Implements the operator ==.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The left. |
| right | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The right. |

**Returns:**
boolean - The result of the operator.
### op_Inequality(CalendarRecurrence left, CalendarRecurrence right) {#op-Inequality-com.aspose.email.CalendarRecurrence-com.aspose.email.CalendarRecurrence-}
```
public static boolean op_Inequality(CalendarRecurrence left, CalendarRecurrence right)
```


Implements the operator !=.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The left. |
| right | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The right. |

**Returns:**
boolean - The result of the operator.
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Gets or sets the end date.

Value: The end date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets the start date.

Value: The start date.

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
### toiCalendar() {#toiCalendar--}
```
public final String toiCalendar()
```


To iCalendar string.

**Returns:**
java.lang.String - StringString representation of RecurrencePattern.
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

