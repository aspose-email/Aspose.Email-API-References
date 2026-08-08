---
title: CalendarRecurrence
second_title: Aspose.Email for Android via Java API 参考
description: 主类表示 iCalendar 循环。
type: docs
weight: 69
url: /zh/androidjava/com.aspose.email/calendarrecurrence/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class CalendarRecurrence implements System.IEquatable<CalendarRecurrence>
```

主要类，表示 iCalendar 循环。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CalendarRecurrence()](#CalendarRecurrence--) | 初始化一个新的 [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) 类实例。 |
| [CalendarRecurrence(String pattern)](#CalendarRecurrence-java.lang.String-) | 初始化一个新的 [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(CalendarRecurrence other)](#equals-com.aspose.email.CalendarRecurrence-) | 确定指定的 [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) 是否等于此实例。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于当前 Object。 |
| [fromRecurrence(String xmlString)](#fromRecurrence-java.lang.String-) | 从 XML 模式字符串获取循环模式。 |
| [fromRecurrence(Element xmlElement)](#fromRecurrence-org.w3c.dom.Element-) | 从 XmlElement 获取循环模式。 |
| [fromiCalendar(String pattern)](#fromiCalendar-java.lang.String-) | 从 iCalendar 字符串获取循环模式。 |
| [generateOccurrences()](#generateOccurrences--) | 生成出现的实例。 |
| [generateOccurrences(int nNextOccurrences)](#generateOccurrences-int-) | 生成接下来的 n 个出现。 |
| [generateOccurrences(Date rangeStart, Date rangeEnd)](#generateOccurrences-java.util.Date-java.util.Date-) | 生成出现的实例。 |
| [generateOccurrences(Date rangeStart, Date rangeEnd, int nNextOccurrences)](#generateOccurrences-java.util.Date-java.util.Date-int-) | 生成接下来的 n 个出现。 |
| [getClass()](#getClass--) |  |
| [getEndDate()](#getEndDate--) | 获取或设置结束日期。 |
| [getExDates()](#getExDates--) | 获取 ex dates。 |
| [getExRules()](#getExRules--) | 获取 ex rules。 |
| [getRDates()](#getRDates--) | 获取 R dates。 |
| [getRRules()](#getRRules--) | 获取 R rules。 |
| [getStartDate()](#getStartDate--) | 获取或设置开始日期。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(CalendarRecurrence left, CalendarRecurrence right)](#op-Equality-com.aspose.email.CalendarRecurrence-com.aspose.email.CalendarRecurrence-) | 实现运算符 ==。 |
| [op_Inequality(CalendarRecurrence left, CalendarRecurrence right)](#op-Inequality-com.aspose.email.CalendarRecurrence-com.aspose.email.CalendarRecurrence-) | 实现运算符 !=。 |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | 获取或设置结束日期。 |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | 获取或设置开始日期。 |
| [toString()](#toString--) |  |
| [toiCalendar()](#toiCalendar--) | 转换为 iCalendar 字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CalendarRecurrence() {#CalendarRecurrence--}
```
public CalendarRecurrence()
```


初始化一个新的 [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) 类实例。

### CalendarRecurrence(String pattern) {#CalendarRecurrence-java.lang.String-}
```
public CalendarRecurrence(String pattern)
```


初始化一个新的 [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 模式 | java.lang.String | 该模式。 |

### equals(CalendarRecurrence other) {#equals-com.aspose.email.CalendarRecurrence-}
```
public boolean equals(CalendarRecurrence other)
```


确定指定的 [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | 用于与此实例比较的 [CalendarRecurrence](../../com.aspose.email/calendarrecurrence)。 |

**Returns:**
布尔值 - 如果指定的 [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) 等于此实例，则为 true；否则为 false。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 Object 是否等于当前 Object。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与当前对象比较的对象。 |

**Returns:**
boolean - 返回一个布尔值，指示传入的对象 obj 是否等于此对象。
### fromRecurrence(String xmlString) {#fromRecurrence-java.lang.String-}
```
public static CalendarRecurrence fromRecurrence(String xmlString)
```


从 XML 模式字符串获取循环模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlString | java.lang.String | 模式的 XML stringString。 |

**Returns:**
[CalendarRecurrence](../../com.aspose.email/calendarrecurrence) - Recurrence pattern[CalendarRecurrence](../../com.aspose.email/calendarrecurrence).
### fromRecurrence(Element xmlElement) {#fromRecurrence-org.w3c.dom.Element-}
```
public static CalendarRecurrence fromRecurrence(Element xmlElement)
```


从 XmlElement 获取循环模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlElement | org.w3c.dom.Element | XmlElementXmlElement of pattern. |

**Returns:**
[CalendarRecurrence](../../com.aspose.email/calendarrecurrence) - Recurrence pattern[CalendarRecurrence](../../com.aspose.email/calendarrecurrence).
### fromiCalendar(String pattern) {#fromiCalendar-java.lang.String-}
```
public static CalendarRecurrence fromiCalendar(String pattern)
```


从 iCalendar 字符串获取循环模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 模式 | java.lang.String | StringString representation of iCalendar. |

**Returns:**
[CalendarRecurrence](../../com.aspose.email/calendarrecurrence) - Recurrence pattern[CalendarRecurrence](../../com.aspose.email/calendarrecurrence).
### generateOccurrences() {#generateOccurrences--}
```
public final DateCollection generateOccurrences()
```


生成出现的实例。

**Returns:**
[DateCollection](../../com.aspose.email/datecollection) - Collection of dates[DateCollection](../../com.aspose.email/datecollection).
### generateOccurrences(int nNextOccurrences) {#generateOccurrences-int-}
```
public final DateCollection generateOccurrences(int nNextOccurrences)
```


生成接下来的 n 个出现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nNextOccurrences | int | The amount of needed occurrences. |

**Returns:**
[DateCollection](../../com.aspose.email/datecollection) - Collection of dates[DateCollection](../../com.aspose.email/datecollection).
### generateOccurrences(Date rangeStart, Date rangeEnd) {#generateOccurrences-java.util.Date-java.util.Date-}
```
public final DateCollection generateOccurrences(Date rangeStart, Date rangeEnd)
```


生成出现的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rangeStart | java.util.Date | The range start. |
| rangeEnd | java.util.Date | The range end. |

**Returns:**
[DateCollection](../../com.aspose.email/datecollection) - Collection of dates[DateCollection](../../com.aspose.email/datecollection).
### generateOccurrences(Date rangeStart, Date rangeEnd, int nNextOccurrences) {#generateOccurrences-java.util.Date-java.util.Date-int-}
```
public final DateCollection generateOccurrences(Date rangeStart, Date rangeEnd, int nNextOccurrences)
```


生成接下来的 n 个出现。

**Parameters:**
| 参数 | 类型 | 描述 |
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


获取或设置结束日期。

值：结束日期。

**Returns:**
java.util.Date
### getExDates() {#getExDates--}
```
public final DateCollection getExDates()
```


获取 ex dates。

Value: The ex dates.

**Returns:**
[DateCollection](../../com.aspose.email/datecollection)
### getExRules() {#getExRules--}
```
public final RecurrenceRuleCollection getExRules()
```


获取 ex rules。

Value: The ex rules.

**Returns:**
[RecurrenceRuleCollection](../../com.aspose.email/recurrencerulecollection)
### getRDates() {#getRDates--}
```
public final DateCollection getRDates()
```


获取 R dates。

Value: The R dates.

**Returns:**
[DateCollection](../../com.aspose.email/datecollection)
### getRRules() {#getRRules--}
```
public final RecurrenceRuleCollection getRRules()
```


获取 R rules。

Value: The R rules.

**Returns:**
[RecurrenceRuleCollection](../../com.aspose.email/recurrencerulecollection)
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


获取或设置开始日期。

Value: The start date.

**Returns:**
java.util.Date
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
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


实现运算符 ==。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The left. |
| right | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The right. |

**Returns:**
boolean - The result of the operator.
### op_Inequality(CalendarRecurrence left, CalendarRecurrence right) {#op-Inequality-com.aspose.email.CalendarRecurrence-com.aspose.email.CalendarRecurrence-}
```
public static boolean op_Inequality(CalendarRecurrence left, CalendarRecurrence right)
```


实现运算符 !=。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The left. |
| right | [CalendarRecurrence](../../com.aspose.email/calendarrecurrence) | The right. |

**Returns:**
boolean - The result of the operator.
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


获取或设置结束日期。

值：结束日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


获取或设置开始日期。

Value: The start date.

**Parameters:**
| 参数 | 类型 | 描述 |
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


转换为 iCalendar 字符串。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

