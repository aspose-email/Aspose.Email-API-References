---
title: MapiContactElectronicAddress
second_title: Aspose.Email for Android via Java API 参考
description: 引用定义联系人电子邮件地址或传真地址的属性组。
type: docs
weight: 234
url: /zh/androidjava/com.aspose.email/mapicontactelectronicaddress/
---

**Inheritance:**
java.lang.Object
```
public final class MapiContactElectronicAddress
```

指代定义联系人电子邮件地址或传真地址的一组属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiContactElectronicAddress()](#MapiContactElectronicAddress--) | 初始化 [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) 类的新实例。 |
| [MapiContactElectronicAddress(String displayName, String addressType, String emailAddress)](#MapiContactElectronicAddress-java.lang.String-java.lang.String-java.lang.String-) | 初始化 [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) 类的新实例。 |
| [MapiContactElectronicAddress(String emailAddress)](#MapiContactElectronicAddress-java.lang.String-) | 初始化 [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) 类的新实例。 |
| [MapiContactElectronicAddress(String faxNumber, String emailAddress)](#MapiContactElectronicAddress-java.lang.String-java.lang.String-) | 初始化 [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的对象是否等于当前对象。 |
| [getAddressType()](#getAddressType--) | 获取或设置电子地址的地址类型 |
| [getClass()](#getClass--) |  |
| [getDisplayName()](#getDisplayName--) | 获取或设置电子邮件地址的用户可读显示名称 |
| [getEmailAddress()](#getEmailAddress--) | 获取或设置联系人的电子邮件地址 |
| [getFaxNumber()](#getFaxNumber--) | 获取或设置邮件用户主传真机的电话号码 |
| [getOriginalDisplayName()](#getOriginalDisplayName--) | 获取或设置与 Contact 对象的电子邮件地址对应的 SMTP 电子邮件地址。 |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | 显示 MapiContactElectronicAddress 是否为空 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressType(String value)](#setAddressType-java.lang.String-) | 获取或设置电子地址的地址类型 |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | 获取或设置电子邮件地址的用户可读显示名称 |
| [setEmailAddress(String value)](#setEmailAddress-java.lang.String-) | 获取或设置联系人的电子邮件地址 |
| [setFaxNumber(String value)](#setFaxNumber-java.lang.String-) | 获取或设置邮件用户主传真机的电话号码 |
| [setOriginalDisplayName(String value)](#setOriginalDisplayName-java.lang.String-) | 获取或设置与 Contact 对象的电子邮件地址对应的 SMTP 电子邮件地址。 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [to_MapiContactElectronicAddress(String emailAddress)](#to-MapiContactElectronicAddress-java.lang.String-) | 执行从 String 到 [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) 的隐式转换。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiContactElectronicAddress() {#MapiContactElectronicAddress--}
```
public MapiContactElectronicAddress()
```


初始化 [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) 类的新实例。

### MapiContactElectronicAddress(String displayName, String addressType, String emailAddress) {#MapiContactElectronicAddress-java.lang.String-java.lang.String-java.lang.String-}
```
public MapiContactElectronicAddress(String displayName, String addressType, String emailAddress)
```


初始化 [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| displayName | java.lang.String | 显示名称。 |
| addressType | java.lang.String | 地址的类型。 |
| emailAddress | java.lang.String | 电子邮件地址。 |

### MapiContactElectronicAddress(String emailAddress) {#MapiContactElectronicAddress-java.lang.String-}
```
public MapiContactElectronicAddress(String emailAddress)
```


初始化 [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| emailAddress | java.lang.String | 电子邮件地址。 |

### MapiContactElectronicAddress(String faxNumber, String emailAddress) {#MapiContactElectronicAddress-java.lang.String-java.lang.String-}
```
public MapiContactElectronicAddress(String faxNumber, String emailAddress)
```


初始化 [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| faxNumber | java.lang.String | 传真号码。 |
| emailAddress | java.lang.String | 电子邮件地址。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的对象是否等于当前对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与当前对象比较的对象。 |

**Returns:**
boolean - 如果指定的对象等于当前对象则为 true；否则为 false。
### getAddressType() {#getAddressType--}
```
public final String getAddressType()
```


获取或设置电子地址的地址类型

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


获取或设置电子邮件地址的用户可读显示名称

**Returns:**
java.lang.String
### getEmailAddress() {#getEmailAddress--}
```
public final String getEmailAddress()
```


获取或设置联系人的电子邮件地址

**Returns:**
java.lang.String
### getFaxNumber() {#getFaxNumber--}
```
public final String getFaxNumber()
```


获取或设置邮件用户主传真机的电话号码

**Returns:**
java.lang.String
### getOriginalDisplayName() {#getOriginalDisplayName--}
```
public final String getOriginalDisplayName()
```


获取或设置与 Contact 对象的电子邮件地址对应的 SMTP 电子邮件地址。

值：SMTP 电子邮件地址。

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


显示 MapiContactElectronicAddress 是否为空

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




### setAddressType(String value) {#setAddressType-java.lang.String-}
```
public final void setAddressType(String value)
```


获取或设置电子地址的地址类型

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


获取或设置电子邮件地址的用户可读显示名称

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setEmailAddress(String value) {#setEmailAddress-java.lang.String-}
```
public final void setEmailAddress(String value)
```


获取或设置联系人的电子邮件地址

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFaxNumber(String value) {#setFaxNumber-java.lang.String-}
```
public final void setFaxNumber(String value)
```


获取或设置邮件用户主传真机的电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setOriginalDisplayName(String value) {#setOriginalDisplayName-java.lang.String-}
```
public final void setOriginalDisplayName(String value)
```


获取或设置与 Contact 对象的电子邮件地址对应的 SMTP 电子邮件地址。

值：SMTP 电子邮件地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。

**Returns:**
java.lang.String - 表示当前对象的字符串。
### to_MapiContactElectronicAddress(String emailAddress) {#to-MapiContactElectronicAddress-java.lang.String-}
```
public static MapiContactElectronicAddress to_MapiContactElectronicAddress(String emailAddress)
```


执行从 String 到 [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) 的隐式转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| emailAddress | java.lang.String | 电子邮件地址。 |

**Returns:**
[MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) - The result of the conversion.
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

