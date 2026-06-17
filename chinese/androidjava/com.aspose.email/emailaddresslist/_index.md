---
title: EmailAddressList
second_title: Aspose.Email for Android via Java API 参考
description: 联系人电子邮件地址列表
type: docs
weight: 116
url: /zh/androidjava/com.aspose.email/emailaddresslist/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public class EmailAddressList implements System.Collections.Generic.IGenericList<EmailAddress>
```

联系人电子邮件地址列表
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmailAddressList()](#EmailAddressList--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(EmailAddress value)](#add-com.aspose.email.EmailAddress-) | 向列表添加一个项。 |
| [addItem(EmailAddress value)](#addItem-com.aspose.email.EmailAddress-) |  |
| [clear()](#clear--) | 从列表中移除所有项。 |
| [contains(EmailAddress value)](#contains-com.aspose.email.EmailAddress-) | 确定列表是否包含特定值。 |
| [containsItem(EmailAddress value)](#containsItem-com.aspose.email.EmailAddress-) |  |
| [copyTo(EmailAddress[] array, int index)](#copyTo-com.aspose.email.EmailAddress---int-) | 将元素复制到数组中，从特定的数组索引开始。 |
| [copyToTArray(EmailAddress[] array, int index)](#copyToTArray-com.aspose.email.EmailAddress---int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmail1()](#getEmail1--) | 默认 email1 地址。 |
| [getEmail2()](#getEmail2--) | 默认 email2 地址。 |
| [getEmail3()](#getEmail3--) | 默认 email3 地址。 |
| [getHome()](#getHome--) | 默认家庭电子邮件地址。 |
| [getSyncRoot()](#getSyncRoot--) | 获取可用于同步访问 ICollection 的对象。 |
| [getWork()](#getWork--) | 默认工作电子邮件地址。 |
| [get_Item(EmailAddressCategory category)](#get-Item-com.aspose.email.EmailAddressCategory-) | 指定类别的默认电子邮件地址。 |
| [get_Item(int index)](#get-Item-int-) | 获取或设置指定索引处的元素。 |
| [hashCode()](#hashCode--) |  |
| [indexOf(EmailAddress value)](#indexOf-com.aspose.email.EmailAddress-) | 确定列表中特定项的索引。 |
| [indexOfItem(EmailAddress value)](#indexOfItem-com.aspose.email.EmailAddress-) |  |
| [insert(int index, EmailAddress value)](#insert-int-com.aspose.email.EmailAddress-) | 在指定索引处向列表插入项。 |
| [insertItem(int index, EmailAddress value)](#insertItem-int-com.aspose.email.EmailAddress-) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，指示列表是否为只读。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(EmailAddress value)](#remove-com.aspose.email.EmailAddress-) | 从列表中删除特定对象的第一次出现。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的列表项。 |
| [removeItem(EmailAddress value)](#removeItem-com.aspose.email.EmailAddress-) |  |
| [setEmail1(EmailAddress value)](#setEmail1-com.aspose.email.EmailAddress-) | 默认 email1 地址。 |
| [setEmail2(EmailAddress value)](#setEmail2-com.aspose.email.EmailAddress-) | 默认 email2 地址。 |
| [setEmail3(EmailAddress value)](#setEmail3-com.aspose.email.EmailAddress-) | 默认 email3 地址。 |
| [setHome(EmailAddress value)](#setHome-com.aspose.email.EmailAddress-) | 默认家庭电子邮件地址。 |
| [setWork(EmailAddress value)](#setWork-com.aspose.email.EmailAddress-) | 默认工作电子邮件地址。 |
| [set_Item(EmailAddressCategory category, EmailAddress value)](#set-Item-com.aspose.email.EmailAddressCategory-com.aspose.email.EmailAddress-) | 指定类别的默认电子邮件地址。 |
| [set_Item(int index, EmailAddress value)](#set-Item-int-com.aspose.email.EmailAddress-) | 获取或设置指定索引处的元素。 |
| [size()](#size--) | 获取 ICollection 中包含的元素数量。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmailAddressList() {#EmailAddressList--}
```
public EmailAddressList()
```


### add(EmailAddress value) {#add-com.aspose.email.EmailAddress-}
```
public final void add(EmailAddress value)
```


向列表添加一个项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) | 要添加到列表的对象。 |

### addItem(EmailAddress value) {#addItem-com.aspose.email.EmailAddress-}
```
public void addItem(EmailAddress value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### clear() {#clear--}
```
public final void clear()
```


从列表中移除所有项。

### contains(EmailAddress value) {#contains-com.aspose.email.EmailAddress-}
```
public final boolean contains(EmailAddress value)
```


确定列表是否包含特定值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) | 要在列表中定位的对象。 |

**Returns:**
boolean - 如果在列表中找到对象则为 true；否则为 false。
### containsItem(EmailAddress value) {#containsItem-com.aspose.email.EmailAddress-}
```
public boolean containsItem(EmailAddress value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

**Returns:**
boolean
### copyTo(EmailAddress[] array, int index) {#copyTo-com.aspose.email.EmailAddress---int-}
```
public final void copyTo(EmailAddress[] array, int index)
```


将元素复制到数组中，从特定的数组索引开始。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [EmailAddress\[\]](../../com.aspose.email/emailaddress) | 一维数组，用作从集合复制的元素的目标。该数组必须使用零基索引。 |
| 索引 | int | 复制开始时数组中的零基索引。 |

### copyToTArray(EmailAddress[] array, int index) {#copyToTArray-com.aspose.email.EmailAddress---int-}
```
public void copyToTArray(EmailAddress[] array, int index)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [EmailAddress\[\]](../../com.aspose.email/emailaddress) |  |
| 索引 | int |  |

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
### getEmail1() {#getEmail1--}
```
public final EmailAddress getEmail1()
```


默认 email1 地址。

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress)
### getEmail2() {#getEmail2--}
```
public final EmailAddress getEmail2()
```


默认 email2 地址。

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress)
### getEmail3() {#getEmail3--}
```
public final EmailAddress getEmail3()
```


默认 email3 地址。

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress)
### getHome() {#getHome--}
```
public final EmailAddress getHome()
```


默认家庭电子邮件地址。

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress)
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


获取可用于同步访问 ICollection 的对象。

**Returns:**
java.lang.Object - 可用于同步访问 ICollection 的对象。
### getWork() {#getWork--}
```
public final EmailAddress getWork()
```


默认工作电子邮件地址。

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress)
### get_Item(EmailAddressCategory category) {#get-Item-com.aspose.email.EmailAddressCategory-}
```
public final EmailAddress get_Item(EmailAddressCategory category)
```


指定类别的默认电子邮件地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| category | [EmailAddressCategory](../../com.aspose.email/emailaddresscategory) | 电子邮件地址的类别 |

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress) - default email address for specified category.
### get_Item(int index) {#get-Item-int-}
```
public final EmailAddress get_Item(int index)
```


获取或设置指定索引处的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 要获取或设置的元素的零基索引。 |

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress) - The element at the specified index.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(EmailAddress value) {#indexOf-com.aspose.email.EmailAddress-}
```
public final int indexOf(EmailAddress value)
```


确定列表中特定项的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) | 要在列表中定位的对象。 |

**Returns:**
int - 如果在列表中找到 value，则返回其索引；否则返回 -1。
### indexOfItem(EmailAddress value) {#indexOfItem-com.aspose.email.EmailAddress-}
```
public int indexOfItem(EmailAddress value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

**Returns:**
int
### insert(int index, EmailAddress value) {#insert-int-com.aspose.email.EmailAddress-}
```
public final void insert(int index, EmailAddress value)
```


在指定索引处向列表插入项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 应插入 value 的零基索引。 |
| value | [EmailAddress](../../com.aspose.email/emailaddress) | 要插入到列表中的对象。 |

### insertItem(int index, EmailAddress value) {#insertItem-int-com.aspose.email.EmailAddress-}
```
public void insertItem(int index, EmailAddress value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int |  |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


获取一个值，指示列表是否为只读。

**Returns:**
boolean - 如果列表是只读的则为 true；否则为 false。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<EmailAddress> iterator()
```


返回一个遍历集合的枚举器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.email.EmailAddress> - 可用于遍历集合的 IEnumerator 对象。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(EmailAddress value) {#remove-com.aspose.email.EmailAddress-}
```
public final boolean remove(EmailAddress value)
```


从列表中删除特定对象的第一次出现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) | 要从列表中删除的对象。 |

**Returns:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


删除指定索引处的列表项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 要删除的项的零基索引。 |

### removeItem(EmailAddress value) {#removeItem-com.aspose.email.EmailAddress-}
```
public boolean removeItem(EmailAddress value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

**Returns:**
boolean
### setEmail1(EmailAddress value) {#setEmail1-com.aspose.email.EmailAddress-}
```
public final void setEmail1(EmailAddress value)
```


默认 email1 地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### setEmail2(EmailAddress value) {#setEmail2-com.aspose.email.EmailAddress-}
```
public final void setEmail2(EmailAddress value)
```


默认 email2 地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### setEmail3(EmailAddress value) {#setEmail3-com.aspose.email.EmailAddress-}
```
public final void setEmail3(EmailAddress value)
```


默认 email3 地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### setHome(EmailAddress value) {#setHome-com.aspose.email.EmailAddress-}
```
public final void setHome(EmailAddress value)
```


默认家庭电子邮件地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### setWork(EmailAddress value) {#setWork-com.aspose.email.EmailAddress-}
```
public final void setWork(EmailAddress value)
```


默认工作电子邮件地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### set_Item(EmailAddressCategory category, EmailAddress value) {#set-Item-com.aspose.email.EmailAddressCategory-com.aspose.email.EmailAddress-}
```
public final void set_Item(EmailAddressCategory category, EmailAddress value)
```


指定类别的默认电子邮件地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| category | [EmailAddressCategory](../../com.aspose.email/emailaddresscategory) | 电子邮件地址的类别 |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### set_Item(int index, EmailAddress value) {#set-Item-int-com.aspose.email.EmailAddress-}
```
public final void set_Item(int index, EmailAddress value)
```


获取或设置指定索引处的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 要获取或设置的元素的零基索引。 |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### size() {#size--}
```
public final int size()
```


获取 ICollection 中包含的元素数量。

**Returns:**
int - ICollection 中包含的元素数量。
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

