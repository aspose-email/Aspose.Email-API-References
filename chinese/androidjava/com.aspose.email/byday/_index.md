---
title: ByDay
second_title: Aspose.Email for Android via Java API 参考
description: 表示指定星期几的第 N 次出现或所有出现。
type: docs
weight: 62
url: /zh/androidjava/com.aspose.email/byday/
---

**Inheritance:**
java.lang.Object
```
public class ByDay
```

表示指定星期几的第 N 次出现（或所有出现）。

--------------------



对应于在重复规则的 BYDAY 部分中指定的一天。

 

可在月度或年度重复规则中使用，以指定月份或年份中指定星期几的第 N 次出现（或所有出现）。

 

BYDAY=MO 表示该月或该年的所有星期一。要表示所有出现，请将 NthOccurrence 设置为 0。

 

BYDAY=2MO 表示该月或该年的第二个星期一。

 

BYDAY=-1MO 表示该月或该年的最后一个星期一。


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ByDay(int dayOfWeek)](#ByDay-int-) | 初始化 ByDay 类的新实例。 |
| [ByDay(int nthOccurrence, int dayOfWeek)](#ByDay-int-int-) | 初始化 ByDay 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于当前 Object。 |
| [getClass()](#getClass--) |  |
| [getDayOfWeek()](#getDayOfWeek--) | 获取或设置星期几。 |
| [getNthOccurrence()](#getNthOccurrence--) | 获取或设置该星期几的第 N 次出现。 |
| [hashCode()](#hashCode--) | GetHashCode 为此对象返回哈希函数。 |
| [isAllOccurrences()](#isAllOccurrences--) | 当 NthOccurrence 为零时返回 True（表示该星期几的所有出现）。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDayOfWeek(int value)](#setDayOfWeek-int-) | 获取或设置星期几。 |
| [setNthOccurrence(int value)](#setNthOccurrence-int-) | 获取或设置该星期几的第 N 次出现。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ByDay(int dayOfWeek) {#ByDay-int-}
```
public ByDay(int dayOfWeek)
```


初始化 ByDay 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dayOfWeek | int | 一周中的某天。 |

### ByDay(int nthOccurrence, int dayOfWeek) {#ByDay-int-int-}
```
public ByDay(int nthOccurrence, int dayOfWeek)
```


初始化 ByDay 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nthOccurrence | int | 该星期几的第 N 次出现。 |
| dayOfWeek | int | 一周中的某天。 |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDayOfWeek() {#getDayOfWeek--}
```
public final int getDayOfWeek()
```


获取或设置星期几。

**Returns:**
int
### getNthOccurrence() {#getNthOccurrence--}
```
public final int getNthOccurrence()
```


获取或设置该星期几的第 N 次出现。

--------------------



此属性的有效范围是 -53 到 53。

 

正值表示从周期开始的第 N 次出现，例如 NthOccurrence = 1，表示该星期几的第一次出现。

 

负值表示从周期结束的第 N 次出现，例如 NthOccurrence = -1，表示该星期几的最后一次出现。

 

当 NthOccurrence 为零时，它表示指定星期几的所有出现。例如，BYDAY=MO 的 NthOccurrence 为零，表示集合中的所有星期一。



**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 为此对象返回哈希函数。

**Returns:**
int - 返回此对象的哈希函数。
### isAllOccurrences() {#isAllOccurrences--}
```
public final boolean isAllOccurrences()
```


当 NthOccurrence 为零时返回 True（表示该星期几的所有出现）。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDayOfWeek(int value) {#setDayOfWeek-int-}
```
public final void setDayOfWeek(int value)
```


获取或设置星期几。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setNthOccurrence(int value) {#setNthOccurrence-int-}
```
public final void setNthOccurrence(int value)
```


获取或设置该星期几的第 N 次出现。

--------------------



此属性的有效范围是 -53 到 53。

 

正值表示从周期开始的第 N 次出现，例如 NthOccurrence = 1，表示该星期几的第一次出现。

 

负值表示从周期结束的第 N 次出现，例如 NthOccurrence = -1，表示该星期几的最后一次出现。

 

当 NthOccurrence 为零时，它表示指定星期几的所有出现。例如，BYDAY=MO 的 NthOccurrence 为零，表示集合中的所有星期一。



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

