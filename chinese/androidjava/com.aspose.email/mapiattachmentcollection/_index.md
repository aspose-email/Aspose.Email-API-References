---
title: MapiAttachmentCollection
second_title: Aspose.Email for Android via Java API 参考
description: 表示一组 MapiAttachment 对象。
type: docs
weight: 204
url: /zh/androidjava/com.aspose.email/mapiattachmentcollection/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.List
```
public class MapiAttachmentCollection extends System.Collections.Generic.List<MapiAttachment>
```

表示一组 MapiAttachment 对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiAttachmentCollection()](#MapiAttachmentCollection--) | 初始化一个新的 [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) 类的实例。 |
| [MapiAttachmentCollection(MapiMessageItemBase owner)](#MapiAttachmentCollection-com.aspose.email.MapiMessageItemBase-) | 初始化 MapiAttachmentCollection 类的一个新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>fromJava(List<T> arg0)](#-T-fromJava-java.util.List-T--) |  |
| [<T>toArray(T[] arg0)](#-T-toArray-T---) |  |
| [<T>toJava(System.Collections.Generic.List<T> arg0)](#-T-toJava-com.aspose.ms.System.Collections.Generic.List-T--) |  |
| [<TOutput>convertAll(System.Converter<T,TOutput> arg0)](#-TOutput-convertAll-com.aspose.ms.System.Converter-T-TOutput--) |  |
| [add(T arg0)](#add-T-) |  |
| [add(int arg0, T arg1)](#add-int-T-) |  |
| [add(String name, byte[] data)](#add-java.lang.String-byte---) | 添加新的附件。 |
| [add(String name, MapiMessage msg)](#add-java.lang.String-com.aspose.email.MapiMessage-) | 将新附件添加为嵌入的消息。 |
| [addAll(int arg0, Collection<? extends T> arg1)](#addAll-int-java.util.Collection---extends-T--) |  |
| [addAll(Collection<? extends T> arg0)](#addAll-java.util.Collection---extends-T--) |  |
| [addItem(T arg0)](#addItem-T-) |  |
| [addMapiAttachment(MapiAttachment item)](#addMapiAttachment-com.aspose.email.MapiAttachment-) | 将对象添加到 System.Collections.ObjectModel.Collection1 的末尾。 |
| [addRange(T[] arg0)](#addRange-T---) |  |
| [addRange(System.Collections.Generic.IGenericEnumerable<T> arg0)](#addRange-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-T--) |  |
| [asReadOnly()](#asReadOnly--) |  |
| [binarySearch(T arg0)](#binarySearch-T-) |  |
| [binarySearch(T arg0, Comparator<T> arg1)](#binarySearch-T-java.util.Comparator-T--) |  |
| [binarySearch(int arg0, int arg1, T arg2, Comparator<T> arg3)](#binarySearch-int-int-T-java.util.Comparator-T--) |  |
| [clear()](#clear--) |  |
| [contains(Object arg0)](#contains-java.lang.Object-) |  |
| [containsAll(Collection<?> arg0)](#containsAll-java.util.Collection----) |  |
| [containsItem(T arg0)](#containsItem-T-) |  |
| [copyTo(T[] arg0)](#copyTo-T---) |  |
| [copyTo(System.Array arg0, int arg1)](#copyTo-com.aspose.ms.System.Array-int-) |  |
| [copyTo(int arg0, T[] arg1, int arg2, int arg3)](#copyTo-int-T---int-int-) |  |
| [copyToTArray(T[] arg0, int arg1)](#copyToTArray-T---int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exists(System.Predicate<T> arg0)](#exists-com.aspose.ms.System.Predicate-T--) |  |
| [find(System.Predicate<T> arg0)](#find-com.aspose.ms.System.Predicate-T--) |  |
| [findAll(System.Predicate<T> arg0)](#findAll-com.aspose.ms.System.Predicate-T--) |  |
| [findIndex(System.Predicate<T> arg0)](#findIndex-com.aspose.ms.System.Predicate-T--) |  |
| [findIndex(int arg0, System.Predicate<T> arg1)](#findIndex-int-com.aspose.ms.System.Predicate-T--) |  |
| [findIndex(int arg0, int arg1, System.Predicate<T> arg2)](#findIndex-int-int-com.aspose.ms.System.Predicate-T--) |  |
| [findLast(System.Predicate<T> arg0)](#findLast-com.aspose.ms.System.Predicate-T--) |  |
| [findLastIndex(System.Predicate<T> arg0)](#findLastIndex-com.aspose.ms.System.Predicate-T--) |  |
| [findLastIndex(int arg0, System.Predicate<T> arg1)](#findLastIndex-int-com.aspose.ms.System.Predicate-T--) |  |
| [findLastIndex(int arg0, int arg1, System.Predicate<T> arg2)](#findLastIndex-int-int-com.aspose.ms.System.Predicate-T--) |  |
| [forEach(System.Action<T> arg0)](#forEach-com.aspose.ms.System.Action-T--) |  |
| [get(int arg0)](#get-int-) |  |
| [getCapacity()](#getCapacity--) |  |
| [getClass()](#getClass--) |  |
| [getRange(int arg0, int arg1)](#getRange-int-int-) |  |
| [getSyncRoot()](#getSyncRoot--) |  |
| [get_Item(int arg0)](#get-Item-int-) |  |
| [hashCode()](#hashCode--) |  |
| [indexOf(T arg0, int arg1)](#indexOf-T-int-) |  |
| [indexOf(T arg0, int arg1, int arg2)](#indexOf-T-int-int-) |  |
| [indexOf(Object arg0)](#indexOf-java.lang.Object-) |  |
| [indexOfItem(T arg0)](#indexOfItem-T-) |  |
| [insert(int index, String name, MapiMessage msg)](#insert-int-java.lang.String-com.aspose.email.MapiMessage-) | 在指定索引处将消息作为附件插入到 [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) 中。 |
| [insertItem(int arg0, T arg1)](#insertItem-int-T-) |  |
| [insertMapiAttachment(int index, MapiAttachment item)](#insertMapiAttachment-int-com.aspose.email.MapiAttachment-) | 在指定索引处将元素插入到 System.Collections.ObjectModel.Collection1 中。 |
| [insertRange(int arg0, System.Collections.Generic.IGenericEnumerable<T> arg1)](#insertRange-int-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-T--) |  |
| [isEmpty()](#isEmpty--) |  |
| [isFixedSize()](#isFixedSize--) |  |
| [isReadOnly()](#isReadOnly--) |  |
| [isSynchronized()](#isSynchronized--) |  |
| [iterator()](#iterator--) |  |
| [lastIndexOf(T arg0, int arg1)](#lastIndexOf-T-int-) |  |
| [lastIndexOf(T arg0, int arg1, int arg2)](#lastIndexOf-T-int-int-) |  |
| [lastIndexOf(Object arg0)](#lastIndexOf-java.lang.Object-) |  |
| [listIterator()](#listIterator--) |  |
| [listIterator(int arg0)](#listIterator-int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(int arg0)](#remove-int-) |  |
| [remove(Object arg0)](#remove-java.lang.Object-) |  |
| [removeAll(System.Predicate<T> arg0)](#removeAll-com.aspose.ms.System.Predicate-T--) |  |
| [removeAll(Collection<?> arg0)](#removeAll-java.util.Collection----) |  |
| [removeAt(int index)](#removeAt-int-) | 移除 MapiAttachmentCollection 中指定索引处的元素。 |
| [removeItem(T arg0)](#removeItem-T-) |  |
| [removeMapiAttachment(MapiAttachment item)](#removeMapiAttachment-com.aspose.email.MapiAttachment-) | 从 MapiAttachmentCollection 中移除特定对象的第一次出现。 |
| [removeRange(int arg0, int arg1)](#removeRange-int-int-) |  |
| [replace(int index, String name, MapiMessage msg)](#replace-int-java.lang.String-com.aspose.email.MapiMessage-) | 替换指定索引处的元素。 |
| [retainAll(Collection<?> arg0)](#retainAll-java.util.Collection----) |  |
| [reverse()](#reverse--) |  |
| [reverse(int arg0, int arg1)](#reverse-int-int-) |  |
| [set(int arg0, T arg1)](#set-int-T-) |  |
| [setCapacity(int arg0)](#setCapacity-int-) |  |
| [set_Item(int arg0, T arg1)](#set-Item-int-T-) |  |
| [size()](#size--) |  |
| [sort()](#sort--) |  |
| [sort(System.Comparison<T> arg0)](#sort-com.aspose.ms.System.Comparison-T--) |  |
| [sort(int arg0, int arg1, Comparator<T> arg2)](#sort-int-int-java.util.Comparator-T--) |  |
| [sort(Comparator<? super T> arg0)](#sort-java.util.Comparator---super-T--) |  |
| [subList(int arg0, int arg1)](#subList-int-int-) |  |
| [toArray()](#toArray--) |  |
| [toString()](#toString--) |  |
| [trimExcess()](#trimExcess--) |  |
| [trueForAll(System.Predicate<T> arg0)](#trueForAll-com.aspose.ms.System.Predicate-T--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiAttachmentCollection() {#MapiAttachmentCollection--}
```
public MapiAttachmentCollection()
```


初始化一个新的 [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) 类的实例。

### MapiAttachmentCollection(MapiMessageItemBase owner) {#MapiAttachmentCollection-com.aspose.email.MapiMessageItemBase-}
```
public MapiAttachmentCollection(MapiMessageItemBase owner)
```


初始化 MapiAttachmentCollection 类的一个新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| owner | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | 所有者消息。 |

### <T>fromJava(List<T> arg0) {#-T-fromJava-java.util.List-T--}
```
public static System.Collections.Generic.List<T> <T>fromJava(List<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.util.List<T> |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<T>
### <T>toArray(T[] arg0) {#-T-toArray-T---}
```
public T[] <T>toArray(T[] arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T[] |  |

**Returns:**
T[]
### <T>toJava(System.Collections.Generic.List<T> arg0) {#-T-toJava-com.aspose.ms.System.Collections.Generic.List-T--}
```
public static List<T> <T>toJava(System.Collections.Generic.List<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.List<T> |  |

**Returns:**
java.util.List<T>
### <TOutput>convertAll(System.Converter<T,TOutput> arg0) {#-TOutput-convertAll-com.aspose.ms.System.Converter-T-TOutput--}
```
public System.Collections.Generic.List<TOutput> <TOutput>convertAll(System.Converter<T,TOutput> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Converter<T,TOutput> |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<TOutput>
### add(T arg0) {#add-T-}
```
public boolean add(T arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### add(int arg0, T arg1) {#add-int-T-}
```
public void add(int arg0, T arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### add(String name, byte[] data) {#add-java.lang.String-byte---}
```
public final void add(String name, byte[] data)
```


添加新的附件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 附件的名称。 |
| 数据 | byte[] | 附件数据。 |

### add(String name, MapiMessage msg) {#add-java.lang.String-com.aspose.email.MapiMessage-}
```
public final void add(String name, MapiMessage msg)
```


将新附件添加为嵌入的消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 附件的名称。 |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | 表示附件消息的 [MapiMessage](../../com.aspose.email/mapimessage)。 |

### addAll(int arg0, Collection<? extends T> arg1) {#addAll-int-java.util.Collection---extends-T--}
```
public boolean addAll(int arg0, Collection<? extends T> arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | java.util.Collection<? extends T> |  |

**Returns:**
boolean
### addAll(Collection<? extends T> arg0) {#addAll-java.util.Collection---extends-T--}
```
public boolean addAll(Collection<? extends T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.util.Collection<? extends T> |  |

**Returns:**
boolean
### addItem(T arg0) {#addItem-T-}
```
public void addItem(T arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### addMapiAttachment(MapiAttachment item) {#addMapiAttachment-com.aspose.email.MapiAttachment-}
```
public final void addMapiAttachment(MapiAttachment item)
```


将对象添加到 System.Collections.ObjectModel.Collection1 的末尾。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [MapiAttachment](../../com.aspose.email/mapiattachment) | 要添加到 System.Collections.ObjectModel.Collection1 末尾的对象。对于引用类型，该值可以为 null。 |

### addRange(T[] arg0) {#addRange-T---}
```
public void addRange(T[] arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T[] |  |

### addRange(System.Collections.Generic.IGenericEnumerable<T> arg0) {#addRange-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-T--}
```
public void addRange(System.Collections.Generic.IGenericEnumerable<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T> |  |

### asReadOnly() {#asReadOnly--}
```
public System.Collections.ObjectModel.ReadOnlyCollection<T> asReadOnly()
```




**Returns:**
com.aspose.ms.System.Collections.ObjectModel.ReadOnlyCollection<T>
### binarySearch(T arg0) {#binarySearch-T-}
```
public int binarySearch(T arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
int
### binarySearch(T arg0, Comparator<T> arg1) {#binarySearch-T-java.util.Comparator-T--}
```
public int binarySearch(T arg0, Comparator<T> arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |
| arg1 | java.util.Comparator<T> |  |

**Returns:**
int
### binarySearch(int arg0, int arg1, T arg2, Comparator<T> arg3) {#binarySearch-int-int-T-java.util.Comparator-T--}
```
public int binarySearch(int arg0, int arg1, T arg2, Comparator<T> arg3)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | T |  |
| arg3 | java.util.Comparator<T> |  |

**Returns:**
int
### clear() {#clear--}
```
public void clear()
```




### contains(Object arg0) {#contains-java.lang.Object-}
```
public boolean contains(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### containsAll(Collection<?> arg0) {#containsAll-java.util.Collection----}
```
public boolean containsAll(Collection<?> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.util.Collection<?> |  |

**Returns:**
boolean
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
### copyTo(T[] arg0) {#copyTo-T---}
```
public void copyTo(T[] arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T[] |  |

### copyTo(System.Array arg0, int arg1) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Array |  |
| arg1 | int |  |

### copyTo(int arg0, T[] arg1, int arg2, int arg3) {#copyTo-int-T---int-int-}
```
public void copyTo(int arg0, T[] arg1, int arg2, int arg3)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T[] |  |
| arg2 | int |  |
| arg3 | int |  |

### copyToTArray(T[] arg0, int arg1) {#copyToTArray-T---int-}
```
public void copyToTArray(T[] arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T[] |  |
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
### exists(System.Predicate<T> arg0) {#exists-com.aspose.ms.System.Predicate-T--}
```
public boolean exists(System.Predicate<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
boolean
### find(System.Predicate<T> arg0) {#find-com.aspose.ms.System.Predicate-T--}
```
public T find(System.Predicate<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
T
### findAll(System.Predicate<T> arg0) {#findAll-com.aspose.ms.System.Predicate-T--}
```
public System.Collections.Generic.List<T> findAll(System.Predicate<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<T>
### findIndex(System.Predicate<T> arg0) {#findIndex-com.aspose.ms.System.Predicate-T--}
```
public int findIndex(System.Predicate<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### findIndex(int arg0, System.Predicate<T> arg1) {#findIndex-int-com.aspose.ms.System.Predicate-T--}
```
public int findIndex(int arg0, System.Predicate<T> arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### findIndex(int arg0, int arg1, System.Predicate<T> arg2) {#findIndex-int-int-com.aspose.ms.System.Predicate-T--}
```
public int findIndex(int arg0, int arg1, System.Predicate<T> arg2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### findLast(System.Predicate<T> arg0) {#findLast-com.aspose.ms.System.Predicate-T--}
```
public T findLast(System.Predicate<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
T
### findLastIndex(System.Predicate<T> arg0) {#findLastIndex-com.aspose.ms.System.Predicate-T--}
```
public int findLastIndex(System.Predicate<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### findLastIndex(int arg0, System.Predicate<T> arg1) {#findLastIndex-int-com.aspose.ms.System.Predicate-T--}
```
public int findLastIndex(int arg0, System.Predicate<T> arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### findLastIndex(int arg0, int arg1, System.Predicate<T> arg2) {#findLastIndex-int-int-com.aspose.ms.System.Predicate-T--}
```
public int findLastIndex(int arg0, int arg1, System.Predicate<T> arg2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### forEach(System.Action<T> arg0) {#forEach-com.aspose.ms.System.Action-T--}
```
public void forEach(System.Action<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Action<T> |  |

### get(int arg0) {#get-int-}
```
public T get(int arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
T
### getCapacity() {#getCapacity--}
```
public int getCapacity()
```




**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getRange(int arg0, int arg1) {#getRange-int-int-}
```
public System.Collections.Generic.List<T> getRange(int arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<T>
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
public native int hashCode()
```




**Returns:**
int
### indexOf(T arg0, int arg1) {#indexOf-T-int-}
```
public int indexOf(T arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |
| arg1 | int |  |

**Returns:**
int
### indexOf(T arg0, int arg1, int arg2) {#indexOf-T-int-int-}
```
public int indexOf(T arg0, int arg1, int arg2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |
| arg1 | int |  |
| arg2 | int |  |

**Returns:**
int
### indexOf(Object arg0) {#indexOf-java.lang.Object-}
```
public int indexOf(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
int
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
### insert(int index, String name, MapiMessage msg) {#insert-int-java.lang.String-com.aspose.email.MapiMessage-}
```
public final void insert(int index, String name, MapiMessage msg)
```


在指定索引处将消息作为附件插入到 [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 应插入的基于零的索引。 |
| name | java.lang.String | 附件的名称。 |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | 表示附件消息的 [MapiMessage](../../com.aspose.email/mapimessage)。 |

### insertItem(int arg0, T arg1) {#insertItem-int-T-}
```
public void insertItem(int arg0, T arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### insertMapiAttachment(int index, MapiAttachment item) {#insertMapiAttachment-int-com.aspose.email.MapiAttachment-}
```
public final void insertMapiAttachment(int index, MapiAttachment item)
```


在指定索引处将元素插入到 System.Collections.ObjectModel.Collection1 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 应插入 item 的基于零的索引。 |
| item | [MapiAttachment](../../com.aspose.email/mapiattachment) | 要插入的对象。对于引用类型，该值可以为 null。 |

### insertRange(int arg0, System.Collections.Generic.IGenericEnumerable<T> arg1) {#insertRange-int-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-T--}
```
public void insertRange(int arg0, System.Collections.Generic.IGenericEnumerable<T> arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T> |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```




**Returns:**
boolean
### isFixedSize() {#isFixedSize--}
```
public boolean isFixedSize()
```




**Returns:**
boolean
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




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
public System.Collections.Generic.List.Enumerator<T> iterator()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List.Enumerator<T>
### lastIndexOf(T arg0, int arg1) {#lastIndexOf-T-int-}
```
public int lastIndexOf(T arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |
| arg1 | int |  |

**Returns:**
int
### lastIndexOf(T arg0, int arg1, int arg2) {#lastIndexOf-T-int-int-}
```
public int lastIndexOf(T arg0, int arg1, int arg2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |
| arg1 | int |  |
| arg2 | int |  |

**Returns:**
int
### lastIndexOf(Object arg0) {#lastIndexOf-java.lang.Object-}
```
public int lastIndexOf(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
int
### listIterator() {#listIterator--}
```
public ListIterator listIterator()
```




**Returns:**
java.util.ListIterator
### listIterator(int arg0) {#listIterator-int-}
```
public ListIterator listIterator(int arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
java.util.ListIterator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(int arg0) {#remove-int-}
```
public T remove(int arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
T
### remove(Object arg0) {#remove-java.lang.Object-}
```
public boolean remove(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### removeAll(System.Predicate<T> arg0) {#removeAll-com.aspose.ms.System.Predicate-T--}
```
public int removeAll(System.Predicate<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### removeAll(Collection<?> arg0) {#removeAll-java.util.Collection----}
```
public boolean removeAll(Collection<?> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.util.Collection<?> |  |

**Returns:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


移除 MapiAttachmentCollection 中指定索引处的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 要移除的元素的基于零的索引。 |

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
### removeMapiAttachment(MapiAttachment item) {#removeMapiAttachment-com.aspose.email.MapiAttachment-}
```
public final boolean removeMapiAttachment(MapiAttachment item)
```


从 MapiAttachmentCollection 中移除特定对象的第一次出现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [MapiAttachment](../../com.aspose.email/mapiattachment) | 要从 MapiAttachmentCollection 中移除的对象。 |

**Returns:**
boolean - 如果成功移除项则为 true；否则为 false。
### removeRange(int arg0, int arg1) {#removeRange-int-int-}
```
public void removeRange(int arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

### replace(int index, String name, MapiMessage msg) {#replace-int-java.lang.String-com.aspose.email.MapiMessage-}
```
public final void replace(int index, String name, MapiMessage msg)
```


替换指定索引处的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 应替换的基于零的索引。 |
| name | java.lang.String | 附件的名称。 |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | 表示附件消息的 [MapiMessage](../../com.aspose.email/mapimessage)。 |

### retainAll(Collection<?> arg0) {#retainAll-java.util.Collection----}
```
public boolean retainAll(Collection<?> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.util.Collection<?> |  |

**Returns:**
boolean
### reverse() {#reverse--}
```
public void reverse()
```




### reverse(int arg0, int arg1) {#reverse-int-int-}
```
public void reverse(int arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

### set(int arg0, T arg1) {#set-int-T-}
```
public T set(int arg0, T arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

**Returns:**
T
### setCapacity(int arg0) {#setCapacity-int-}
```
public void setCapacity(int arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |

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
### sort() {#sort--}
```
public void sort()
```




### sort(System.Comparison<T> arg0) {#sort-com.aspose.ms.System.Comparison-T--}
```
public void sort(System.Comparison<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Comparison<T> |  |

### sort(int arg0, int arg1, Comparator<T> arg2) {#sort-int-int-java.util.Comparator-T--}
```
public void sort(int arg0, int arg1, Comparator<T> arg2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | java.util.Comparator<T> |  |

### sort(Comparator<? super T> arg0) {#sort-java.util.Comparator---super-T--}
```
public void sort(Comparator<? super T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.util.Comparator<? super T> |  |

### subList(int arg0, int arg1) {#subList-int-int-}
```
public List<T> subList(int arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
java.util.List<T>
### toArray() {#toArray--}
```
public Object[] toArray()
```




**Returns:**
java.lang.Object[]
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### trimExcess() {#trimExcess--}
```
public void trimExcess()
```




### trueForAll(System.Predicate<T> arg0) {#trueForAll-com.aspose.ms.System.Predicate-T--}
```
public boolean trueForAll(System.Predicate<T> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
boolean
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

