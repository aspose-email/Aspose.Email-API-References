---
title: ByDayCollection
second_title: Aspose.Email for Android via Java API 参考
description: 表示对象的集合。
type: docs
weight: 63
url: /zh/androidjava/com.aspose.email/bydaycollection/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection
```
public class ByDayCollection extends System.Collections.ObjectModel.Collection<ByDay>
```

表示 [ByDay](../../com.aspose.email/byday) 对象的集合。

--------------------



对应于重复规则的 BYDAY 部分。

 

BYDAY 规则指定每月或每年重复规则中的一周中的天列表。

 

对于一周中的每一天，可以指定特定的第 N 次出现或全部出现。


## 方法

| 方法 | 描述 |
| --- | --- |
| [add(ByDay byDay)](#add-com.aspose.email.ByDay-) | 向集合中添加一个 [ByDay](../../com.aspose.email/byday)。 |
| [add(int dayOfWeek)](#add-int-) | 创建并向集合中添加一个表示一周中所有该天出现的 [ByDay](../../com.aspose.email/byday)。 |
| [add(int nthOccurrence, int dayOfWeek)](#add-int-int-) | 创建并向集合中添加一个 [ByDay](../../com.aspose.email/byday)。 |
| [addItem(T arg0)](#addItem-T-) |  |
| [clear()](#clear--) |  |
| [contains(int dayOfWeek)](#contains-int-) | 返回一个值，指示集合中是否存在指定的星期几。 |
| [containsItem(T arg0)](#containsItem-T-) |  |
| [copyToTArray(T[] arg0, int arg1)](#copyToTArray-T---int-) |  |
| [equals(ByDayCollection other)](#equals-com.aspose.email.ByDayCollection-) | 确定指定的 [ByDayCollection](../../com.aspose.email/bydaycollection) 是否等于此实例。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于当前 Object。 |
| [get(int index)](#get-int-) | 获取或设置集合中的 ByDay。 |
| [getClass()](#getClass--) |  |
| [getICollection()](#getICollection--) |  |
| [getIList()](#getIList--) |  |
| [getSyncRoot()](#getSyncRoot--) |  |
| [get_Item(int arg0)](#get-Item-int-) |  |
| [hashCode()](#hashCode--) | GetHashCode 为此对象返回哈希函数。 |
| [indexOfItem(T arg0)](#indexOfItem-T-) |  |
| [insertItem(int arg0, T arg1)](#insertItem-int-T-) |  |
| [isReadOnly()](#isReadOnly--) |  |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int arg0)](#removeAt-int-) |  |
| [removeItem(T arg0)](#removeItem-T-) |  |
| [set(int index, ByDay value)](#set-int-com.aspose.email.ByDay-) | 获取或设置集合中的 ByDay。 |
| [set_Item(int arg0, T arg1)](#set-Item-int-T-) |  |
| [size()](#size--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ByDay byDay) {#add-com.aspose.email.ByDay-}
```
public final int add(ByDay byDay)
```


向集合中添加一个 [ByDay](../../com.aspose.email/byday)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| byDay | [ByDay](../../com.aspose.email/byday) | 要添加到集合的项。 |

**Returns:**
int - 新添加项的零基索引。
### add(int dayOfWeek) {#add-int-}
```
public final int add(int dayOfWeek)
```


创建并向集合中添加一个表示一周中所有该天出现的 [ByDay](../../com.aspose.email/byday)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dayOfWeek | int | 一周中的某天。 |

**Returns:**
int - 新添加项的零基索引。
### add(int nthOccurrence, int dayOfWeek) {#add-int-int-}
```
public final int add(int nthOccurrence, int dayOfWeek)
```


创建并向集合中添加一个 [ByDay](../../com.aspose.email/byday)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nthOccurrence | int | 该星期几的第 N 次出现。 |
| dayOfWeek | int | 一周中的某天。 |

**Returns:**
int - 新添加项的零基索引。
### addItem(T arg0) {#addItem-T-}
```
public void addItem(T arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### clear() {#clear--}
```
public void clear()
```




### contains(int dayOfWeek) {#contains-int-}
```
public final boolean contains(int dayOfWeek)
```


返回一个值，指示集合中是否存在指定的星期几。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dayOfWeek | int | 星期几[DayOfWeek](../../com.aspose.email/dayofweek)。 |

**Returns:**
boolean - 如果该值参数存在于此集合中则为 True，否则为 false。
### containsItem(T arg0) {#containsItem-T-}
```
public boolean containsItem(T arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### copyToTArray(T[] arg0, int arg1) {#copyToTArray-T---int-}
```
public void copyToTArray(T[] arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T[] |  |
| arg1 | int |  |

### equals(ByDayCollection other) {#equals-com.aspose.email.ByDayCollection-}
```
public boolean equals(ByDayCollection other)
```


确定指定的 [ByDayCollection](../../com.aspose.email/bydaycollection) 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [ByDayCollection](../../com.aspose.email/bydaycollection) | 用于与此实例比较的 [ByDayCollection](../../com.aspose.email/bydaycollection)。 |

**Returns:**
boolean - 如果指定的 [ByDayCollection](../../com.aspose.email/bydaycollection) 等于此实例则为 true；否则为 false。
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
### get(int index) {#get-int-}
```
public ByDay get(int index)
```


获取或设置集合中的 ByDay。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 一个 int。 |

**Returns:**
[ByDay](../../com.aspose.email/byday) - a [ByDay](../../com.aspose.email/byday) object.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getICollection() {#getICollection--}
```
public System.Collections.ICollection getICollection()
```




**Returns:**
com.aspose.ms.System.Collections.ICollection
### getIList() {#getIList--}
```
public System.Collections.IList getIList()
```




**Returns:**
com.aspose.ms.System.Collections.IList
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```




**Returns:**
java.lang.Object
### get_Item(int arg0) {#get-Item-int-}
```
public T get_Item(int arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
T
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 为此对象返回哈希函数。

**Returns:**
int - 返回此对象的哈希函数。
### indexOfItem(T arg0) {#indexOfItem-T-}
```
public int indexOfItem(T arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
int
### insertItem(int arg0, T arg1) {#insertItem-int-T-}
```
public void insertItem(int arg0, T arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**Returns:**
boolean
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<T> iterator()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<T>
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAt(int arg0) {#removeAt-int-}
```
public void removeAt(int arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |

### removeItem(T arg0) {#removeItem-T-}
```
public boolean removeItem(T arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### set(int index, ByDay value) {#set-int-com.aspose.email.ByDay-}
```
public void set(int index, ByDay value)
```


获取或设置集合中的 ByDay。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 一个 int。 |
| value | [ByDay](../../com.aspose.email/byday) | 一个 [ByDay](../../com.aspose.email/byday) 对象。 |

### set_Item(int arg0, T arg1) {#set-Item-int-T-}
```
public void set_Item(int arg0, T arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### size() {#size--}
```
public int size()
```




**Returns:**
int
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

