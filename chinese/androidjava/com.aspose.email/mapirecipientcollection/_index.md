---
title: MapiRecipientCollection
second_title: Aspose.Email for Android via Java API 参考
description: 表示 MapiRecipient 对象的集合。
type: docs
weight: 279
url: /zh/androidjava/com.aspose.email/mapirecipientcollection/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection
```
public class MapiRecipientCollection extends System.Collections.ObjectModel.Collection<MapiRecipient>
```

表示 MapiRecipient 对象的集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiRecipientCollection()](#MapiRecipientCollection--) | 初始化 [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(String address, String displayName, int recipientType)](#add-java.lang.String-java.lang.String-int-) | 添加新的收件人。 |
| [add(String address, String addressType, String displayName, int recipientType)](#add-java.lang.String-java.lang.String-java.lang.String-int-) | 添加新的收件人。 |
| [addItem(T arg0)](#addItem-T-) |  |
| [addMapiRecipient(MapiRecipient item)](#addMapiRecipient-com.aspose.email.MapiRecipient-) | 将对象添加到 System.Collections.ObjectModel.Collection1 的末尾。 |
| [clear()](#clear--) |  |
| [containsItem(T arg0)](#containsItem-T-) |  |
| [copyToTArray(T[] arg0, int arg1)](#copyToTArray-T---int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getICollection()](#getICollection--) |  |
| [getIList()](#getIList--) |  |
| [getSyncRoot()](#getSyncRoot--) |  |
| [get_Item(int arg0)](#get-Item-int-) |  |
| [hashCode()](#hashCode--) |  |
| [indexOfItem(T arg0)](#indexOfItem-T-) |  |
| [insertItem(int arg0, T arg1)](#insertItem-int-T-) |  |
| [insertMapiRecipient(int index, MapiRecipient item)](#insertMapiRecipient-int-com.aspose.email.MapiRecipient-) | 在指定索引处将元素插入到 System.Collections.ObjectModel.Collection1 中。 |
| [isReadOnly()](#isReadOnly--) |  |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int arg0)](#removeAt-int-) |  |
| [removeItem(T arg0)](#removeItem-T-) |  |
| [set_Item(int arg0, T arg1)](#set-Item-int-T-) |  |
| [size()](#size--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiRecipientCollection() {#MapiRecipientCollection--}
```
public MapiRecipientCollection()
```


初始化 [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) 类的新实例。

### add(String address, String displayName, int recipientType) {#add-java.lang.String-java.lang.String-int-}
```
public final void add(String address, String displayName, int recipientType)
```


添加新的收件人。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | java.lang.String | 收件人的邮件地址。 |
| displayName | java.lang.String | 收件人的显示名称。 |
|  | recipientType | int | 收件人的类型。 |

--------------------

添加新收件人时，依据收件人的类型，MapiMessage.DisplayTo、MapiMessage.DisplayBcc 或 MapiMessage.DisplayCC 的值也会相应更新。 |

### add(String address, String addressType, String displayName, int recipientType) {#add-java.lang.String-java.lang.String-java.lang.String-int-}
```
public final void add(String address, String addressType, String displayName, int recipientType)
```


添加新的收件人。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | java.lang.String | 收件人的邮件地址。 |
| addressType | java.lang.String | 地址的类型。 |
| displayName | java.lang.String | 收件人的显示名称。 |
|  | recipientType | int | 收件人的类型。 |

--------------------

添加新收件人时，依据收件人的类型，MapiMessage.DisplayTo、MapiMessage.DisplayBcc 或 MapiMessage.DisplayCC 的值也会相应更新。 |

### addItem(T arg0) {#addItem-T-}
```
public void addItem(T arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### addMapiRecipient(MapiRecipient item) {#addMapiRecipient-com.aspose.email.MapiRecipient-}
```
public final void addMapiRecipient(MapiRecipient item)
```


将对象添加到 System.Collections.ObjectModel.Collection1 的末尾。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [MapiRecipient](../../com.aspose.email/mapirecipient) | 要添加到 System.Collections.ObjectModel.Collection1 末尾的对象。对于引用类型，该值可以为 null。 |

### clear() {#clear--}
```
public void clear()
```




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
public native int hashCode()
```




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
### insertItem(int arg0, T arg1) {#insertItem-int-T-}
```
public void insertItem(int arg0, T arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### insertMapiRecipient(int index, MapiRecipient item) {#insertMapiRecipient-int-com.aspose.email.MapiRecipient-}
```
public final void insertMapiRecipient(int index, MapiRecipient item)
```


在指定索引处将元素插入到 System.Collections.ObjectModel.Collection1 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 应插入 item 的基于零的索引。 |
| item | [MapiRecipient](../../com.aspose.email/mapirecipient) | 要插入的对象。对于引用类型，该值可以为 null。 |

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

