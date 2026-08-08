---
title: 电话号码列表
second_title: Aspose.Email for Android via Java API 参考
description: 联系人电话号码列表。
type: docs
weight: 349
url: /zh/androidjava/com.aspose.email/phonenumberlist/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public class PhoneNumberList implements System.Collections.Generic.IGenericList<PhoneNumber>
```

联系人电话号码列表。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PhoneNumberList()](#PhoneNumberList--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(PhoneNumber value)](#add-com.aspose.email.PhoneNumber-) | 向列表添加一个项。 |
| [addItem(PhoneNumber value)](#addItem-com.aspose.email.PhoneNumber-) |  |
| [clear()](#clear--) | 从列表中移除所有项。 |
| [contains(PhoneNumber value)](#contains-com.aspose.email.PhoneNumber-) | 确定列表是否包含特定值。 |
| [containsItem(PhoneNumber value)](#containsItem-com.aspose.email.PhoneNumber-) |  |
| [copyTo(PhoneNumber[] array, int index)](#copyTo-com.aspose.email.PhoneNumber---int-) | 将元素复制到数组中，从特定的数组索引开始。 |
| [copyToTArray(PhoneNumber[] array, int index)](#copyToTArray-com.aspose.email.PhoneNumber---int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssistant()](#getAssistant--) | 默认助理电话号码 |
| [getCallback()](#getCallback--) | 默认回拨电话号码 |
| [getCar()](#getCar--) | 默认车载电话号码 |
| [getClass()](#getClass--) |  |
| [getCompany()](#getCompany--) | 默认公司电话号码 |
| [getCustom()](#getCustom--) | 默认自定义电话类别 |
| [getFax()](#getFax--) | 默认传真号码 |
| [getHome()](#getHome--) | 默认住宅电话号码 |
| [getHomeFax()](#getHomeFax--) | 默认住宅传真号码 |
| [getIsdn()](#getIsdn--) | 默认 ISDN 电话号码 |
| [getMobile()](#getMobile--) | 默认移动电话号码 |
| [getPager()](#getPager--) | 默认传呼号码 |
| [getPrefered()](#getPrefered--) | 默认主要电话号码 |
| [getRadio()](#getRadio--) | 默认无线电话号码 |
| [getTelex()](#getTelex--) | 默认电传 |
| [getTtyTdd()](#getTtyTdd--) | 默认 TTY/TDD |
| [getWork()](#getWork--) | 默认工作电话号码 |
| [getWorkFax()](#getWorkFax--) | 默认工作传真号码 |
| [get_Item(int index)](#get-Item-int-) | 获取或设置指定索引处的元素。 |
| [hashCode()](#hashCode--) |  |
| [indexOf(PhoneNumber value)](#indexOf-com.aspose.email.PhoneNumber-) | 确定列表中特定项的索引。 |
| [indexOfItem(PhoneNumber value)](#indexOfItem-com.aspose.email.PhoneNumber-) |  |
| [insert(int index, PhoneNumber value)](#insert-int-com.aspose.email.PhoneNumber-) | 在指定索引处向列表插入项。 |
| [insertItem(int index, PhoneNumber value)](#insertItem-int-com.aspose.email.PhoneNumber-) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，指示列表是否为只读。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(PhoneNumber value)](#remove-com.aspose.email.PhoneNumber-) | 从列表中删除特定对象的第一次出现。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的列表项。 |
| [removeItem(PhoneNumber value)](#removeItem-com.aspose.email.PhoneNumber-) |  |
| [setAssistant(String value)](#setAssistant-java.lang.String-) | 默认助理电话号码 |
| [setCallback(String value)](#setCallback-java.lang.String-) | 默认回拨电话号码 |
| [setCar(String value)](#setCar-java.lang.String-) | 默认车载电话号码 |
| [setCompany(String value)](#setCompany-java.lang.String-) | 默认公司电话号码 |
| [setCustom(String value)](#setCustom-java.lang.String-) | 默认自定义电话类别 |
| [setFax(String value)](#setFax-java.lang.String-) | 默认传真号码 |
| [setHome(String value)](#setHome-java.lang.String-) | 默认住宅电话号码 |
| [setHomeFax(String value)](#setHomeFax-java.lang.String-) | 默认住宅传真号码 |
| [setIsdn(String value)](#setIsdn-java.lang.String-) | 默认 ISDN 电话号码 |
| [setMobile(String value)](#setMobile-java.lang.String-) | 默认移动电话号码 |
| [setPager(String value)](#setPager-java.lang.String-) | 默认传呼号码 |
| [setPrefered(String value)](#setPrefered-java.lang.String-) | 默认主要电话号码 |
| [setRadio(String value)](#setRadio-java.lang.String-) | 默认无线电话号码 |
| [setTelex(String value)](#setTelex-java.lang.String-) | 默认电传 |
| [setTtyTdd(String value)](#setTtyTdd-java.lang.String-) | 默认 TTY/TDD |
| [setWork(String value)](#setWork-java.lang.String-) | 默认工作电话号码 |
| [setWorkFax(String value)](#setWorkFax-java.lang.String-) | 默认工作传真号码 |
| [set_Item(int index, PhoneNumber value)](#set-Item-int-com.aspose.email.PhoneNumber-) | 获取或设置指定索引处的元素。 |
| [size()](#size--) | 获取 ICollection 中包含的元素数量。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhoneNumberList() {#PhoneNumberList--}
```
public PhoneNumberList()
```


### add(PhoneNumber value) {#add-com.aspose.email.PhoneNumber-}
```
public final void add(PhoneNumber value)
```


向列表添加一个项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) | 要添加到列表的对象。 |

### addItem(PhoneNumber value) {#addItem-com.aspose.email.PhoneNumber-}
```
public void addItem(PhoneNumber value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

### clear() {#clear--}
```
public final void clear()
```


从列表中移除所有项。

### contains(PhoneNumber value) {#contains-com.aspose.email.PhoneNumber-}
```
public final boolean contains(PhoneNumber value)
```


确定列表是否包含特定值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) | 要在列表中定位的对象。 |

**Returns:**
boolean - 如果在列表中找到对象则为 true；否则为 false。
### containsItem(PhoneNumber value) {#containsItem-com.aspose.email.PhoneNumber-}
```
public boolean containsItem(PhoneNumber value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

**Returns:**
boolean
### copyTo(PhoneNumber[] array, int index) {#copyTo-com.aspose.email.PhoneNumber---int-}
```
public final void copyTo(PhoneNumber[] array, int index)
```


将元素复制到数组中，从特定的数组索引开始。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [PhoneNumber\[\]](../../com.aspose.email/phonenumber) | 一维数组，用作从集合复制的元素的目标。该数组必须使用零基索引。 |
| 索引 | int | 复制开始时数组中的零基索引。 |

### copyToTArray(PhoneNumber[] array, int index) {#copyToTArray-com.aspose.email.PhoneNumber---int-}
```
public void copyToTArray(PhoneNumber[] array, int index)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [PhoneNumber\[\]](../../com.aspose.email/phonenumber) |  |
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
### getAssistant() {#getAssistant--}
```
public final String getAssistant()
```


默认助理电话号码

**Returns:**
java.lang.String
### getCallback() {#getCallback--}
```
public final String getCallback()
```


默认回拨电话号码

**Returns:**
java.lang.String
### getCar() {#getCar--}
```
public final String getCar()
```


默认车载电话号码

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompany() {#getCompany--}
```
public final String getCompany()
```


默认公司电话号码

**Returns:**
java.lang.String
### getCustom() {#getCustom--}
```
public final String getCustom()
```


默认自定义电话类别

**Returns:**
java.lang.String
### getFax() {#getFax--}
```
public final String getFax()
```


默认传真号码

**Returns:**
java.lang.String
### getHome() {#getHome--}
```
public final String getHome()
```


默认住宅电话号码

**Returns:**
java.lang.String
### getHomeFax() {#getHomeFax--}
```
public final String getHomeFax()
```


默认住宅传真号码

**Returns:**
java.lang.String
### getIsdn() {#getIsdn--}
```
public final String getIsdn()
```


默认 ISDN 电话号码

**Returns:**
java.lang.String
### getMobile() {#getMobile--}
```
public final String getMobile()
```


默认移动电话号码

**Returns:**
java.lang.String
### getPager() {#getPager--}
```
public final String getPager()
```


默认传呼号码

**Returns:**
java.lang.String
### getPrefered() {#getPrefered--}
```
public final String getPrefered()
```


默认主要电话号码

**Returns:**
java.lang.String
### getRadio() {#getRadio--}
```
public final String getRadio()
```


默认无线电话号码

**Returns:**
java.lang.String
### getTelex() {#getTelex--}
```
public final String getTelex()
```


默认电传

**Returns:**
java.lang.String
### getTtyTdd() {#getTtyTdd--}
```
public final String getTtyTdd()
```


默认 TTY/TDD

**Returns:**
java.lang.String
### getWork() {#getWork--}
```
public final String getWork()
```


默认工作电话号码

**Returns:**
java.lang.String
### getWorkFax() {#getWorkFax--}
```
public final String getWorkFax()
```


默认工作传真号码

**Returns:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final PhoneNumber get_Item(int index)
```


获取或设置指定索引处的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 要获取或设置的元素的零基索引。 |

**Returns:**
[PhoneNumber](../../com.aspose.email/phonenumber) - The element at the specified index.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(PhoneNumber value) {#indexOf-com.aspose.email.PhoneNumber-}
```
public final int indexOf(PhoneNumber value)
```


确定列表中特定项的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) | 要在列表中定位的对象。 |

**Returns:**
int - 如果在列表中找到 value，则返回其索引；否则返回 -1。
### indexOfItem(PhoneNumber value) {#indexOfItem-com.aspose.email.PhoneNumber-}
```
public int indexOfItem(PhoneNumber value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

**Returns:**
int
### insert(int index, PhoneNumber value) {#insert-int-com.aspose.email.PhoneNumber-}
```
public final void insert(int index, PhoneNumber value)
```


在指定索引处向列表插入项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 应插入 value 的零基索引。 |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) | 要插入到列表中的对象。 |

### insertItem(int index, PhoneNumber value) {#insertItem-int-com.aspose.email.PhoneNumber-}
```
public void insertItem(int index, PhoneNumber value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int |  |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


获取一个值，指示列表是否为只读。

**Returns:**
boolean - 如果列表是只读的则为 true；否则为 false。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<PhoneNumber> iterator()
```


返回一个遍历集合的枚举器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.email.PhoneNumber> - 可用于遍历集合的 IEnumerator 对象。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(PhoneNumber value) {#remove-com.aspose.email.PhoneNumber-}
```
public final boolean remove(PhoneNumber value)
```


从列表中删除特定对象的第一次出现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) | 要从列表中删除的对象。 |

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

### removeItem(PhoneNumber value) {#removeItem-com.aspose.email.PhoneNumber-}
```
public boolean removeItem(PhoneNumber value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

**Returns:**
boolean
### setAssistant(String value) {#setAssistant-java.lang.String-}
```
public final void setAssistant(String value)
```


默认助理电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCallback(String value) {#setCallback-java.lang.String-}
```
public final void setCallback(String value)
```


默认回拨电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCar(String value) {#setCar-java.lang.String-}
```
public final void setCar(String value)
```


默认车载电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


默认公司电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCustom(String value) {#setCustom-java.lang.String-}
```
public final void setCustom(String value)
```


默认自定义电话类别

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFax(String value) {#setFax-java.lang.String-}
```
public final void setFax(String value)
```


默认传真号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setHome(String value) {#setHome-java.lang.String-}
```
public final void setHome(String value)
```


默认住宅电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setHomeFax(String value) {#setHomeFax-java.lang.String-}
```
public final void setHomeFax(String value)
```


默认住宅传真号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setIsdn(String value) {#setIsdn-java.lang.String-}
```
public final void setIsdn(String value)
```


默认 ISDN 电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMobile(String value) {#setMobile-java.lang.String-}
```
public final void setMobile(String value)
```


默认移动电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setPager(String value) {#setPager-java.lang.String-}
```
public final void setPager(String value)
```


默认传呼号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setPrefered(String value) {#setPrefered-java.lang.String-}
```
public final void setPrefered(String value)
```


默认主要电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setRadio(String value) {#setRadio-java.lang.String-}
```
public final void setRadio(String value)
```


默认无线电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setTelex(String value) {#setTelex-java.lang.String-}
```
public final void setTelex(String value)
```


默认电传

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setTtyTdd(String value) {#setTtyTdd-java.lang.String-}
```
public final void setTtyTdd(String value)
```


默认 TTY/TDD

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setWork(String value) {#setWork-java.lang.String-}
```
public final void setWork(String value)
```


默认工作电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setWorkFax(String value) {#setWorkFax-java.lang.String-}
```
public final void setWorkFax(String value)
```


默认工作传真号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### set_Item(int index, PhoneNumber value) {#set-Item-int-com.aspose.email.PhoneNumber-}
```
public final void set_Item(int index, PhoneNumber value)
```


获取或设置指定索引处的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 要获取或设置的元素的零基索引。 |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

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

