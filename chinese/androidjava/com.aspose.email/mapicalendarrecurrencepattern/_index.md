---
title: MapiCalendarRecurrencePattern
second_title: Aspose.Email for Android via Java API 参考
description: 表示 mapi 重复模式
type: docs
weight: 221
url: /zh/androidjava/com.aspose.email/mapicalendarrecurrencepattern/
---

**Inheritance:**
java.lang.Object
```
public abstract class MapiCalendarRecurrencePattern
```

表示 mapi 重复模式
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiCalendarRecurrencePattern()](#MapiCalendarRecurrencePattern--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendarType()](#getCalendarType--) | 获取或设置使用的日历类型。 |
| [getClass()](#getClass--) |  |
| [getDeletedInstanceDates()](#getDeletedInstanceDates--) | 一个日期数组，其中每个日期都是此重复模式中已删除实例或已修改实例的原始实例日期。 |
| [getEndDate()](#getEndDate--) | 获取或设置项目重复模式的结束日期。 |
| [getEndType()](#getEndType--) | 获取或设置重复的结束类型。 |
| [getExceptions()](#getExceptions--) | 异常指定对重复系列实例的更改。 |
| [getFrequency()](#getFrequency--) | 获取或设置重复系列的频率。 |
| [getModifiedInstanceDates()](#getModifiedInstanceDates--) | 日期数组，其中每个日期对应一个已修改实例的日期。 |
| [getOccurrenceCount()](#getOccurrenceCount--) | 获取或设置重复中的出现次数。 |
| [getPatternType()](#getPatternType--) | 获取或设置重复模式的类型 |
| [getPeriod()](#getPeriod--) | 获取或设置会议模式重复的间隔。 |
| [getSlidingFlag()](#getSlidingFlag--) | 定义模式是否为滑动模式。 |
| [getStartDate()](#getStartDate--) | 获取或设置项目重复模式的开始日期。 |
| [getWeekStartDay()](#getWeekStartDay--) | 获取或设置日历周的第一天。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendarType(int value)](#setCalendarType-int-) | 获取或设置使用的日历类型。 |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | 获取或设置项目重复模式的结束日期。 |
| [setEndType(int value)](#setEndType-int-) | 获取或设置重复的结束类型。 |
| [setOccurrenceCount(long value)](#setOccurrenceCount-long-) | 获取或设置重复中的出现次数。 |
| [setPatternType(int value)](#setPatternType-int-) | 获取或设置重复模式的类型 |
| [setPeriod(long value)](#setPeriod-long-) | 获取或设置会议模式重复的间隔。 |
| [setSlidingFlag(boolean value)](#setSlidingFlag-boolean-) | 定义模式是否为滑动模式。 |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | 获取或设置项目重复模式的开始日期。 |
| [setWeekStartDay(int value)](#setWeekStartDay-int-) | 获取或设置日历周的第一天。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarRecurrencePattern() {#MapiCalendarRecurrencePattern--}
```
public MapiCalendarRecurrencePattern()
```


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
### getCalendarType() {#getCalendarType--}
```
public final int getCalendarType()
```


获取或设置使用的日历类型。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeletedInstanceDates() {#getDeletedInstanceDates--}
```
public System.Collections.Generic.IGenericList<Date> getDeletedInstanceDates()
```


一个日期数组，其中每个日期都是此重复模式中已删除实例或已修改实例的原始实例日期。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.util.Date>
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


获取或设置项目重复模式的结束日期。

**Returns:**
java.util.Date
### getEndType() {#getEndType--}
```
public final int getEndType()
```


获取或设置重复的结束类型。

**Returns:**
int
### getExceptions() {#getExceptions--}
```
public final System.Collections.Generic.IGenericList<MapiCalendarExceptionInfo> getExceptions()
```


异常指定对重复系列实例的更改。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MapiCalendarExceptionInfo>
### getFrequency() {#getFrequency--}
```
public int getFrequency()
```


获取或设置重复系列的频率。

**Returns:**
int
### getModifiedInstanceDates() {#getModifiedInstanceDates--}
```
public System.Collections.Generic.IGenericList<Date> getModifiedInstanceDates()
```


日期数组，其中每个日期对应一个已修改实例的日期。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.util.Date>
### getOccurrenceCount() {#getOccurrenceCount--}
```
public final long getOccurrenceCount()
```


获取或设置重复中的出现次数。

**Returns:**
long
### getPatternType() {#getPatternType--}
```
public final int getPatternType()
```


获取或设置重复模式的类型

**Returns:**
int
### getPeriod() {#getPeriod--}
```
public abstract long getPeriod()
```


获取或设置会议模式重复的间隔。

**Returns:**
long
### getSlidingFlag() {#getSlidingFlag--}
```
public final boolean getSlidingFlag()
```


定义模式是否为滑动模式。

**Returns:**
boolean
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


获取或设置项目重复模式的开始日期。

**Returns:**
java.util.Date
### getWeekStartDay() {#getWeekStartDay--}
```
public final int getWeekStartDay()
```


获取或设置日历周的第一天。

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




### setCalendarType(int value) {#setCalendarType-int-}
```
public final void setCalendarType(int value)
```


获取或设置使用的日历类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


获取或设置项目重复模式的结束日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setEndType(int value) {#setEndType-int-}
```
public final void setEndType(int value)
```


获取或设置重复的结束类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setOccurrenceCount(long value) {#setOccurrenceCount-long-}
```
public final void setOccurrenceCount(long value)
```


获取或设置重复中的出现次数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### setPatternType(int value) {#setPatternType-int-}
```
public final void setPatternType(int value)
```


获取或设置重复模式的类型

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setPeriod(long value) {#setPeriod-long-}
```
public abstract void setPeriod(long value)
```


获取或设置会议模式重复的间隔。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### setSlidingFlag(boolean value) {#setSlidingFlag-boolean-}
```
public final void setSlidingFlag(boolean value)
```


定义模式是否为滑动模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


获取或设置项目重复模式的开始日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setWeekStartDay(int value) {#setWeekStartDay-int-}
```
public final void setWeekStartDay(int value)
```


获取或设置日历周的第一天。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

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

