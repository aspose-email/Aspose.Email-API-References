---
title: DataColumnCollection
second_title: Aspose.Email for Android via Java API 参考
description: DataColumnCollection 类。
type: docs
weight: 95
url: /zh/androidjava/com.aspose.email/datacolumncollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection
```
public class DataColumnCollection implements System.Collections.ICollection<DataColumn>
```

DataColumnCollection 类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DataColumnCollection(DataTable dataTable)](#DataColumnCollection-com.aspose.email.DataTable-) | DataColumnCollection 的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(DataColumn dataColumn)](#add-com.aspose.email.DataColumn-) | 添加。 |
| [add(String columnName)](#add-java.lang.String-) | 添加。 |
| [contains(String name)](#contains-java.lang.String-) | 包含。 |
| [copyTo(System.Array arg0, int arg1)](#copyTo-com.aspose.ms.System.Array-int-) | \\{@inheritDoc\\} |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColumnName(int ordinal)](#getColumnName-int-) | getColumnName. |
| [getSyncRoot()](#getSyncRoot--) | 获取同步根 |
| [hashCode()](#hashCode--) |  |
| [isSynchronized()](#isSynchronized--) | 定义是否同步 |
| [iterator()](#iterator--) | 获取迭代器 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [size()](#size--) | 获取大小 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataColumnCollection(DataTable dataTable) {#DataColumnCollection-com.aspose.email.DataTable-}
```
public DataColumnCollection(DataTable dataTable)
```


DataColumnCollection 的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataTable | [DataTable](../../com.aspose.email/datatable) | 一个 [DataTable](../../com.aspose.email/datatable) 对象。 |

### add(DataColumn dataColumn) {#add-com.aspose.email.DataColumn-}
```
public void add(DataColumn dataColumn)
```


添加。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataColumn | [DataColumn](../../com.aspose.email/datacolumn) | 一个 [DataColumn](../../com.aspose.email/datacolumn) 对象。 |

### add(String columnName) {#add-java.lang.String-}
```
public void add(String columnName)
```


添加。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnName | java.lang.String | 一个 java.lang.String 对象。 |

### contains(String name) {#contains-java.lang.String-}
```
public boolean contains(String name)
```


包含。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 一个 java.lang.String 对象。 |

**Returns:**
boolean - 一个布尔值。
### copyTo(System.Array arg0, int arg1) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Array |  |
| arg1 | int |  |

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
### getColumnName(int ordinal) {#getColumnName-int-}
```
public String getColumnName(int ordinal)
```


getColumnName.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ordinal | int | 一个 int。 |

**Returns:**
java.lang.String - 一个 java.lang.String 对象。
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取同步根

**Returns:**
java.lang.Object - 一个对象。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


定义是否同步

**Returns:**
boolean - 一个布尔值。
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<DataColumn> iterator()
```


获取迭代器

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.email.DataColumn> - 一个迭代器。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### size() {#size--}
```
public int size()
```


获取大小

**Returns:**
int - 一个整数。
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

