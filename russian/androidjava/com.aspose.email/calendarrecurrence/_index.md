---
title: CalendarRecurrence
second_title: Aspose.Email for Android via Java API Reference
description: Основной класс представляет повтор iCalendar.
type: docs
weight: 69
url: /ru/androidjava/com.aspose.email/calendarrecurrence/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class CalendarRecurrence implements System.IEquatable<CalendarRecurrence>
```

Основной класс, представляет повтор iCalendar.
## Constructors

| Constructor | Описание |
| --- | --- |
| [CalendarRecurrence()](#CalendarRecurrence--) | Инициализирует новый экземпляр класса [CalendarRecurrence](../../com.aspose.email/calendarrecurrence). |
| [CalendarRecurrence(String pattern)](#CalendarRecurrence-java.lang.String-) | Инициализирует новый экземпляр класса [CalendarRecurrence](../../com.aspose.email/calendarrecurrence). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(CalendarRecurrence other)](#equals-com.aspose.email.CalendarRecurrence-) | Определяет, равен ли указанный [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) этому экземпляру. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный Object текущему Object. |
| [fromRecurrence(String xmlString)](#fromRecurrence-java.lang.String-) | Получает шаблон повторения из строки шаблона XML. |
| [fromRecurrence(Element xmlElement)](#fromRecurrence-org.w3c.dom.Element-) | Получает шаблон повторения из XmlElement. |
| [fromiCalendar(String pattern)](#fromiCalendar-java.lang.String-) | Получает шаблон повторения из строки iCalendar. |
| [generateOccurrences()](#generateOccurrences--) | Генерирует вхождения. |
| [generateOccurrences(int nNextOccurrences)](#generateOccurrences-int-) | Генерирует n следующих вхождений. |
| [generateOccurrences(Date rangeStart, Date rangeEnd)](#generateOccurrences-java.util.Date-java.util.Date-) | Генерирует вхождения. |
| [generateOccurrences(Date rangeStart, Date rangeEnd, int nNextOccurrences)](#generateOccurrences-java.util.Date-java.util.Date-int-) | Генерирует n следующих вхождений. |
| [getClass()](#getClass--) |  |
| [getEndDate()](#getEndDate--) | Получает или задает конечную дату. |
| [getExDates()](#getExDates--) | Получает даты исключений. |
| [getExRules()](#getExRules--) | Получает правила исключений. |
| [getRDates()](#getRDates--) | Получает даты R. |
| [getRRules()](#getRRules--) | Получает правила R. |
| [getStartDate()](#getStartDate--) | Получает или задает дату начала. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(CalendarRecurrence left, CalendarRecurrence right)](#op-Equality-com.aspose.email.CalendarRecurrence-com.aspose.email.CalendarRecurrence-) | Реализует оператор ==. |
| [op_Inequality(CalendarRecurrence left, CalendarRecurrence right)](#op-Inequality-com.aspose.email.CalendarRecurrence-com.aspose.email.CalendarRecurrence-) | Реализует оператор !=. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Получает или задает конечную дату. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Получает или задает дату начала. |
| [toString()](#toString--) |  |
| [toiCalendar()](#toiCalendar--) | В строку iCalendar. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CalendarRecurrence() {#CalendarRecurrence--}
```
public CalendarRecurrence()
```


Инициализирует новый экземпляр класса [CalendarRecurrence](../../com.aspose.email/calendarrecurrence).

### CalendarRecurrence(String pattern) {#CalendarRecurrence-java.lang.String-}
```
public CalendarRecurrence(String pattern)
```


Инициализирует новый экземпляр класса [CalendarRecurrence](../../com.aspose.email/calendarrecurrence).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| шаблон | java.lang.String | Шаблон. |

### equals(CalendarRecurrence other) {#equals-com.aspose.email.CalendarRecurrence-}
```
public boolean equals(CalendarRecurrence other)
```


Определяет, равен ли указанный [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) этому экземпляру.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| other | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | Объект [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) для сравнения с этим экземпляром. |

**Returns:**
boolean -  true  если указанный [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) равен этому экземпляру; иначе  false .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный Object текущему Object.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с текущим объектом. |

**Returns:**
boolean - Возвращает логическое значение, указывающее, равен ли переданный объект obj этому.
### fromRecurrence(String xmlString) {#fromRecurrence-java.lang.String-}
```
public static CalendarRecurrence fromRecurrence(String xmlString)
```


Получает шаблон повторения из строки шаблона XML.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| xmlString | java.lang.String | XML-строка шаблона. |

**Returns:**
[CalendarRecurrence](../../com.aspose.email/calendarrecurrence) - Recurrence pattern[CalendarRecurrence](../../com.aspose.email/calendarrecurrence).
### fromRecurrence(Element xmlElement) {#fromRecurrence-org.w3c.dom.Element-}
```
public static CalendarRecurrence fromRecurrence(Element xmlElement)
```


Получает шаблон повторения из XmlElement.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| xmlElement | org.w3c.dom.Element | XmlElementXmlElement of pattern. |

**Returns:**
[CalendarRecurrence](../../com.aspose.email/calendarrecurrence) - Recurrence pattern[CalendarRecurrence](../../com.aspose.email/calendarrecurrence).
### fromiCalendar(String pattern) {#fromiCalendar-java.lang.String-}
```
public static CalendarRecurrence fromiCalendar(String pattern)
```


Получает шаблон повторения из строки iCalendar.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| шаблон | java.lang.String | StringString representation of iCalendar. |

**Returns:**
[CalendarRecurrence](../../com.aspose.email/calendarrecurrence) - Recurrence pattern[CalendarRecurrence](../../com.aspose.email/calendarrecurrence).
### generateOccurrences() {#generateOccurrences--}
```
public final DateCollection generateOccurrences()
```


Генерирует вхождения.

**Returns:**
[DateCollection](../../com.aspose.email/datecollection) - Collection of dates[DateCollection](../../com.aspose.email/datecollection).
### generateOccurrences(int nNextOccurrences) {#generateOccurrences-int-}
```
public final DateCollection generateOccurrences(int nNextOccurrences)
```


Генерирует n следующих вхождений.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| nNextOccurrences | int | The amount of needed occurrences. |

**Returns:**
[DateCollection](../../com.aspose.email/datecollection) - Collection of dates[DateCollection](../../com.aspose.email/datecollection).
### generateOccurrences(Date rangeStart, Date rangeEnd) {#generateOccurrences-java.util.Date-java.util.Date-}
```
public final DateCollection generateOccurrences(Date rangeStart, Date rangeEnd)
```


Генерирует вхождения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| rangeStart | java.util.Date | The range start. |
| rangeEnd | java.util.Date | The range end. |

**Returns:**
[DateCollection](../../com.aspose.email/datecollection) - Collection of dates[DateCollection](../../com.aspose.email/datecollection).
### generateOccurrences(Date rangeStart, Date rangeEnd, int nNextOccurrences) {#generateOccurrences-java.util.Date-java.util.Date-int-}
```
public final DateCollection generateOccurrences(Date rangeStart, Date rangeEnd, int nNextOccurrences)
```


Генерирует n следующих вхождений.

**Parameters:**
| Parameter | Type | Описание |
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


Получает или задает конечную дату.

Значение: Конечная дата.

**Returns:**
java.util.Date
### getExDates() {#getExDates--}
```
public final DateCollection getExDates()
```


Получает даты исключений.

Value: The ex dates.

**Returns:**
[DateCollection](../../com.aspose.email/datecollection)
### getExRules() {#getExRules--}
```
public final RecurrenceRuleCollection getExRules()
```


Получает правила исключений.

Value: The ex rules.

**Returns:**
[RecurrenceRuleCollection](../../com.aspose.email/recurrencerulecollection)
### getRDates() {#getRDates--}
```
public final DateCollection getRDates()
```


Получает даты R.

Value: The R dates.

**Returns:**
[DateCollection](../../com.aspose.email/datecollection)
### getRRules() {#getRRules--}
```
public final RecurrenceRuleCollection getRRules()
```


Получает правила R.

Value: The R rules.

**Returns:**
[RecurrenceRuleCollection](../../com.aspose.email/recurrencerulecollection)
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Получает или задает дату начала.

Value: The start date.

**Returns:**
java.util.Date
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — Хеш‑код этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш‑таблица.
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


Реализует оператор ==.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| left | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The left. |
| right | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The right. |

**Returns:**
boolean - The result of the operator.
### op_Inequality(CalendarRecurrence left, CalendarRecurrence right) {#op-Inequality-com.aspose.email.CalendarRecurrence-com.aspose.email.CalendarRecurrence-}
```
public static boolean op_Inequality(CalendarRecurrence left, CalendarRecurrence right)
```


Реализует оператор !=.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| left | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The left. |
| right | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The right. |

**Returns:**
boolean - The result of the operator.
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Получает или задает конечную дату.

Значение: Конечная дата.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Получает или задает дату начала.

Value: The start date.

**Parameters:**
| Parameter | Type | Описание |
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


В строку iCalendar.

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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

