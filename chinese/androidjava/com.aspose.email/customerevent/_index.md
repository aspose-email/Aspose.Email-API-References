---
title: CustomerEvent
second_title: Aspose.Email for Android via Java API 参考
description: 表示一个事件。
type: docs
weight: 89
url: /zh/androidjava/com.aspose.email/customerevent/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.ms.System.IEquatable
```
public class CustomerEvent implements Comparable<CustomerEvent>, System.IEquatable<CustomerEvent>
```

表示一个事件。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CustomerEvent()](#CustomerEvent--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [compareTo(CustomerEvent obj)](#compareTo-com.aspose.email.CustomerEvent-) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于另一个对象之前、之后，还是与其处于相同位置。 |
| [equals(CustomerEvent obj)](#equals-com.aspose.email.CustomerEvent-) | 确定指定的 Object 是否等于当前 Object。 |
| [equals(CustomerEvent x, CustomerEvent y)](#equals-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-) | 确定指定的对象实例是否被视为相等。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于当前 Object。 |
| [getCategory()](#getCategory--) | 获取或设置对象类别 |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | 获取或设置事件的日期和时间。 |
| [hashCode()](#hashCode--) | GetHashCode 为此对象返回哈希函数。 |
| [hashCode(CustomerEvent obj)](#hashCode-com.aspose.email.CustomerEvent-) | GetHashCode 为指定对象返回哈希函数。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(CustomerEvent a, CustomerEvent b)](#op-Equality-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-) | 确定指定的对象是否相等。 |
| [op_Inequality(CustomerEvent a, CustomerEvent b)](#op-Inequality-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-) | 确定指定的对象是否不相等。 |
| [setCategory(EventCategory value)](#setCategory-com.aspose.email.EventCategory-) | 获取或设置对象类别 |
| [setDate(Date value)](#setDate-java.util.Date-) | 获取或设置事件的日期和时间。 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomerEvent() {#CustomerEvent--}
```
public CustomerEvent()
```


### compareTo(CustomerEvent obj) {#compareTo-com.aspose.email.CustomerEvent-}
```
public int compareTo(CustomerEvent obj)
```


比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于另一个对象之前、之后，还是与其处于相同位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [CustomerEvent](../../com.aspose.email/customerevent) | 用于与此实例比较的对象，或 null。 |

**Returns:**
int - 此方法返回：如果此值小于 value，则返回小于 0 的值；如果此值等于 value，则返回 0；如果此值大于 value，则返回大于 0 的值。
### equals(CustomerEvent obj) {#equals-com.aspose.email.CustomerEvent-}
```
public final boolean equals(CustomerEvent obj)
```


确定指定的 Object 是否等于当前 Object。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [CustomerEvent](../../com.aspose.email/customerevent) | 用于与当前对象比较的对象。 |

**Returns:**
boolean - 返回一个布尔值，指示传入的对象 obj 是否等于此对象。
### equals(CustomerEvent x, CustomerEvent y) {#equals-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-}
```
public final boolean equals(CustomerEvent x, CustomerEvent y)
```


确定指定的对象实例是否被视为相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | [CustomerEvent](../../com.aspose.email/customerevent) | 要比较的第一个对象。 |
| y | [CustomerEvent](../../com.aspose.email/customerevent) | 要比较的第二个对象。 |

**Returns:**
boolean - 如果对象被视为相等，则为 true；否则为 false。如果 objA 和 objB 均为 null，方法返回 true。
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
### getCategory() {#getCategory--}
```
public final EventCategory getCategory()
```


获取或设置对象类别

**Returns:**
[EventCategory](../../com.aspose.email/eventcategory)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDate() {#getDate--}
```
public final Date getDate()
```


获取或设置事件的日期和时间。

**Returns:**
java.util.Date
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 为此对象返回哈希函数。

**Returns:**
int - 返回此对象的哈希函数。
### hashCode(CustomerEvent obj) {#hashCode-com.aspose.email.CustomerEvent-}
```
public final int hashCode(CustomerEvent obj)
```


GetHashCode 为指定对象返回哈希函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [CustomerEvent](../../com.aspose.email/customerevent) | 要返回哈希码的对象。 |

**Returns:**
int - 为指定对象返回哈希函数。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(CustomerEvent a, CustomerEvent b) {#op-Equality-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-}
```
public static boolean op_Equality(CustomerEvent a, CustomerEvent b)
```


确定指定的对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [CustomerEvent](../../com.aspose.email/customerevent) | 要比较的第一个对象 |
| b | [CustomerEvent](../../com.aspose.email/customerevent) | 要比较的第二个对象 |

**Returns:**
boolean - 如果对象相等则返回 true，否则返回 false。
### op_Inequality(CustomerEvent a, CustomerEvent b) {#op-Inequality-com.aspose.email.CustomerEvent-com.aspose.email.CustomerEvent-}
```
public static boolean op_Inequality(CustomerEvent a, CustomerEvent b)
```


确定指定的对象是否不相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [CustomerEvent](../../com.aspose.email/customerevent) | 要比较的第一个对象 |
| b | [CustomerEvent](../../com.aspose.email/customerevent) | 要比较的第二个对象 |

**Returns:**
boolean - 如果对象不相等则返回 true，否则返回 false。
### setCategory(EventCategory value) {#setCategory-com.aspose.email.EventCategory-}
```
public final void setCategory(EventCategory value)
```


获取或设置对象类别

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EventCategory](../../com.aspose.email/eventcategory) |  |

### setDate(Date value) {#setDate-java.util.Date-}
```
public final void setDate(Date value)
```


获取或设置事件的日期和时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。

**Returns:**
java.lang.String - 返回表示当前对象的字符串。
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

