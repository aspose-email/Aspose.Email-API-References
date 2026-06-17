---
title: DailyRecurrencePattern
second_title: Aspose.Email for Android via Java API 参考
description: 表示每日类型的重复模式。
type: docs
weight: 93
url: /zh/androidjava/com.aspose.email/dailyrecurrencepattern/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.RecurrencePattern](../../com.aspose.email/recurrencepattern)
```
public class DailyRecurrencePattern extends RecurrencePattern
```

表示每日类型的重复模式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DailyRecurrencePattern(Date endDate)](#DailyRecurrencePattern-java.util.Date-) | 初始化 [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern) 类的新实例。 |
| [DailyRecurrencePattern(int occurs)](#DailyRecurrencePattern-int-) | 初始化 [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern) 类的新实例。 |
| [DailyRecurrencePattern(Date endDate, int interval)](#DailyRecurrencePattern-java.util.Date-int-) | 初始化 [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern) 类的新实例。 |
| [DailyRecurrencePattern(int occurs, int interval)](#DailyRecurrencePattern-int-int-) | 初始化 [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndDate()](#getEndDate--) | 获取或设置结束日期。 |
| [getInterval()](#getInterval--) | 获取或设置循环单位的数量。 |
| [getOccurs()](#getOccurs--) | 获取或设置循环模式的出现次数。 |
| [getWeekStart()](#getWeekStart--) | 获取或设置周的起始日。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | 获取或设置结束日期。 |
| [setInterval(int value)](#setInterval-int-) | 获取或设置循环单位的数量。 |
| [setOccurs(int value)](#setOccurs-int-) | 获取或设置循环模式的出现次数。 |
| [setWeekStart(int value)](#setWeekStart-int-) | 获取或设置周的起始日。 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [to_RecurrencePattern(String value)](#to-RecurrencePattern-java.lang.String-) | 将 ICalendar 格式的循环模式字符串表示转换为对象 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DailyRecurrencePattern(Date endDate) {#DailyRecurrencePattern-java.util.Date-}
```
public DailyRecurrencePattern(Date endDate)
```


初始化 [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| endDate | java.util.Date | 结束日期。 |

### DailyRecurrencePattern(int occurs) {#DailyRecurrencePattern-int-}
```
public DailyRecurrencePattern(int occurs)
```


初始化 [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 发生 | int | 表示出现次数的 Int32 值。 |

### DailyRecurrencePattern(Date endDate, int interval) {#DailyRecurrencePattern-java.util.Date-int-}
```
public DailyRecurrencePattern(Date endDate, int interval)
```


初始化 [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| endDate | java.util.Date | 结束日期。 |
| 间隔 | int | 循环单位的数量。 |

### DailyRecurrencePattern(int occurs, int interval) {#DailyRecurrencePattern-int-int-}
```
public DailyRecurrencePattern(int occurs, int interval)
```


初始化 [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 发生 | int | 表示出现次数的 Int32 值。 |
| 间隔 | int | 循环单位的数量。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
### getInterval() {#getInterval--}
```
public final int getInterval()
```


获取或设置循环单位的数量。

值：循环单位的数量。

**Returns:**
int
### getOccurs() {#getOccurs--}
```
public final int getOccurs()
```


获取或设置循环模式的出现次数。

值：出现次数。

**Returns:**
int
### getWeekStart() {#getWeekStart--}
```
public final int getWeekStart()
```


获取或设置周的起始日。

值：周开始。

**Returns:**
int
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

### setInterval(int value) {#setInterval-int-}
```
public final void setInterval(int value)
```


获取或设置循环单位的数量。

值：循环单位的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setOccurs(int value) {#setOccurs-int-}
```
public final void setOccurs(int value)
```


获取或设置循环模式的出现次数。

值：出现次数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setWeekStart(int value) {#setWeekStart-int-}
```
public final void setWeekStart(int value)
```


获取或设置周的起始日。

值：周开始。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。

**Returns:**
java.lang.String - 表示当前对象的字符串。
### to_RecurrencePattern(String value) {#to-RecurrencePattern-java.lang.String-}
```
public static RecurrencePattern to_RecurrencePattern(String value)
```


将 ICalendar 格式的循环模式字符串表示转换为对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 返回 RecurrencePattern 对象 |

**Returns:**
[RecurrencePattern](../../com.aspose.email/recurrencepattern)
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

