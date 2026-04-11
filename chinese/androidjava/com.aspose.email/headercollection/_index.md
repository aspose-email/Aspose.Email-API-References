---
title: HeaderCollection
second_title: Aspose.Email for Android via Java API 参考
description: 定义标题字段的集合
type: docs
weight: 155
url: /zh/androidjava/com.aspose.email/headercollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection
```
public class HeaderCollection implements System.Collections.ICollection<String>
```

定义标题字段的集合
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HeaderCollection(HeaderCollection col)](#HeaderCollection-com.aspose.email.HeaderCollection-) | 初始化一个新的 [HeaderCollection](../../com.aspose.email/headercollection) 类的实例。 |
| [HeaderCollection()](#HeaderCollection--) | 初始化一个新的 [HeaderCollection](../../com.aspose.email/headercollection) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(HeaderCollection c)](#add-com.aspose.email.HeaderCollection-) | 向集合添加标头。 |
| [add(String item)](#add-java.lang.String-) | 添加不带值的标头。 |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 添加标头。 |
| [add_(String name, String value)](#add--java.lang.String-java.lang.String-) | 添加标头。 |
| [clear()](#clear--) | 清除所有标头。 |
| [contains(String item)](#contains-java.lang.String-) | 获取一个值，指示指定的标头是否包含在集合中 |
| [copyTo(System.Array dest, int index)](#copyTo-com.aspose.ms.System.Array-int-) |  |
| [copyTo(String[] array, int arrayIndex)](#copyTo-java.lang.String---int-) | 将当前集合的所有元素复制到指定的字符串数组中，从指定的目标索引开始。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | 获取指定索引处的值。 |
| [get(String name)](#get-java.lang.String-) | 通过给定的标头名称获取标头值。 |
| [getAllKeys()](#getAllKeys--) | 获取包含集合中所有标头键的字符串数组 |
| [getClass()](#getClass--) |  |
| [getDecodedValue(String name)](#getDecodedValue-java.lang.String-) | 获取标头值。 |
| [getKey(int index)](#getKey-int-) | 获取集合中指定索引处的键。 |
| [getKeys()](#getKeys--) | 获取一个  System.Collections.ObjectModel.ReadOnlyCollection\{string\} ，其中包含集合中所有标头键 |
| [getSyncRoot()](#getSyncRoot--) |  |
| [getValues(String name)](#getValues-java.lang.String-) | 获取标头值。 |
| [get_Item(int index)](#get-Item-int-) | 通过索引从集合中获取值。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 通过名称从集合中获取值。 |
| [hasKeys()](#hasKeys--) | 获取一个值，指示集合是否包含键。 |
| [hashCode()](#hashCode--) |  |
| [insert(String name, String value)](#insert-java.lang.String-java.lang.String-) | 在集合中插入标头。 |
| [isReadOnly()](#isReadOnly--) | 集合是否只读 |
| [isSynchronized()](#isSynchronized--) |  |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String item)](#remove-java.lang.String-) | 通过给定的标头名称从集合中移除标头。 |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | 设置标头。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 通过名称从集合中获取值。 |
| [size()](#size--) | 获取标头的数量 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HeaderCollection(HeaderCollection col) {#HeaderCollection-com.aspose.email.HeaderCollection-}
```
public HeaderCollection(HeaderCollection col)
```


初始化一个新的 [HeaderCollection](../../com.aspose.email/headercollection) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| col | [HeaderCollection](../../com.aspose.email/headercollection) | 集合。 |

### HeaderCollection() {#HeaderCollection--}
```
public HeaderCollection()
```


初始化一个新的 [HeaderCollection](../../com.aspose.email/headercollection) 类的实例。

### add(HeaderCollection c) {#add-com.aspose.email.HeaderCollection-}
```
public final void add(HeaderCollection c)
```


向集合添加标头。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | [HeaderCollection](../../com.aspose.email/headercollection) | 用于添加的 HeaderCollection。 |

### add(String item) {#add-java.lang.String-}
```
public final void add(String item)
```


添加不带值的标头。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 项 | java.lang.String |  |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```


添加标头。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 标头名称。 |
| value | java.lang.String | 标头值。 |

### add_(String name, String value) {#add--java.lang.String-java.lang.String-}
```
public void add_(String name, String value)
```


添加标头。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 标头名称。 |
| value | java.lang.String | 标头值。 |

### clear() {#clear--}
```
public void clear()
```


清除所有标头。

### contains(String item) {#contains-java.lang.String-}
```
public final boolean contains(String item)
```


获取一个值，指示指定的标头是否包含在集合中

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 项 | java.lang.String | 要搜索的标头 |

**Returns:**
boolean - 如果集合包含指定的项则为 True；否则为 false
### copyTo(System.Array dest, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array dest, int index)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 目标 | com.aspose.ms.System.Array |  |
| 索引 | int |  |

### copyTo(String[] array, int arrayIndex) {#copyTo-java.lang.String---int-}
```
public final void copyTo(String[] array, int arrayIndex)
```


将当前集合的所有元素复制到指定的字符串数组中，从指定的目标索引开始。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数组 | java.lang.String[] | 从当前集合复制的元素的目标位置。 |
| arrayIndex | int | 一个整数，表示复制开始的数组索引。 |

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
### get(int index) {#get-int-}
```
public String get(int index)
```


获取指定索引处的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 一个整数，表示要获取的元素位置。 |

**Returns:**
java.lang.String - 当前集合中指定位置的值。
### get(String name) {#get-java.lang.String-}
```
public final String get(String name)
```


通过给定的标头名称获取标头值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 该 haeader 名称。 |

**Returns:**
java.lang.String - 标头值。
### getAllKeys() {#getAllKeys--}
```
public String[] getAllKeys()
```


获取包含集合中所有标头键的字符串数组

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecodedValue(String name) {#getDecodedValue-java.lang.String-}
```
public final String getDecodedValue(String name)
```


获取标头值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 文本标头名称。 |

**Returns:**
java.lang.String - 解码后的文本值
### getKey(int index) {#getKey-int-}
```
public String getKey(int index)
```


获取集合中指定索引处的键。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 键的索引。 |

**Returns:**
java.lang.String - 指定索引处的键。
### getKeys() {#getKeys--}
```
public List<String> getKeys()
```


获取一个  System.Collections.ObjectModel.ReadOnlyCollection\{string\} ，其中包含集合中所有标头键

**Returns:**
java.util.List<java.lang.String>
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```




**Returns:**
java.lang.Object
### getValues(String name) {#getValues-java.lang.String-}
```
public final String[] getValues(String name)
```


获取标头值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 标头名称。 |

**Returns:**
java.lang.String[] - 标头值的集合。
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


通过索引从集合中获取值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 集合中项目的索引。 |

**Returns:**
java.lang.String - 返回指定的项目
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


通过名称从集合中获取值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 集合中项目的名称（键）。 |

**Returns:**
java.lang.String - 返回指定的项目
### hasKeys() {#hasKeys--}
```
public final boolean hasKeys()
```


获取一个值，指示集合是否包含键。

**Returns:**
boolean - 如果集合有项目则返回 true，否则返回 false。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### insert(String name, String value) {#insert-java.lang.String-java.lang.String-}
```
public final void insert(String name, String value)
```


在集合中插入标头。如果集合中已存在同名标头，则此标头会插入到其他同名标头之前。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 标头名称。 |
| value | java.lang.String | 标头值。 |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


集合是否只读

**Returns:**
boolean
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```




**Returns:**
boolean
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<String> iterator()
```


返回一个遍历集合的枚举器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<java.lang.String> - 一个可用于遍历集合的 System.Collections.Generic.IEnumerator\{string\} 对象。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String item) {#remove-java.lang.String-}
```
public final boolean remove(String item)
```


通过给定的标头名称从集合中移除标头。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 项 | java.lang.String | 标头名称。 |

**Returns:**
boolean - 如果成功从集合中移除项目则为 true。
### set(String name, String value) {#set-java.lang.String-java.lang.String-}
```
public final void set(String name, String value)
```


设置标头。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 标头名称。 |
| value | java.lang.String | 标头值。 |

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


通过名称从集合中获取值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 集合中项目的名称（键）。 |
| value | java.lang.String |  |

### size() {#size--}
```
public int size()
```


获取标头的数量

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

