---
title: EmailAddress
second_title: Aspose.Email for Android via Java API 参考
description: 表示一个电子邮件地址
type: docs
weight: 114
url: /zh/androidjava/com.aspose.email/emailaddress/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailAddress](../../com.aspose.email/mailaddress)

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.ms.System.IEquatable
```
public class EmailAddress extends MailAddress implements Comparable<EmailAddress>, System.IEquatable<EmailAddress>
```

表示一个电子邮件地址
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmailAddress()](#EmailAddress--) | 初始化 [EmailAddress](../../com.aspose.email/emailaddress) 类的新实例。 |
| [EmailAddress(String address)](#EmailAddress-java.lang.String-) | 初始化 [EmailAddress](../../com.aspose.email/emailaddress) 类的新实例。 |
| [EmailAddress(String address, String displayName)](#EmailAddress-java.lang.String-java.lang.String-) | 初始化 [EmailAddress](../../com.aspose.email/emailaddress) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [compareTo(EmailAddress obj)](#compareTo-com.aspose.email.EmailAddress-) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于另一个对象之前、之后，还是与其处于相同位置。 |
| [equals(EmailAddress obj)](#equals-com.aspose.email.EmailAddress-) | 确定指定的 Object 是否等于当前 Object。 |
| [equals(EmailAddress x, EmailAddress y)](#equals-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | 确定指定的对象实例是否被视为相等。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于当前 Object。 |
| [getAddress()](#getAddress--) | 获取或设置电子邮件地址。 |
| [getCategory()](#getCategory--) | 获取或设置对象类别 |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 包含邮件地址的计数。 |
| [getDisplayName()](#getDisplayName--) | 获取或设置显示名称。 |
| [getHost()](#getHost--) | 获取地址的主机部分。 |
| [getId()](#getId--) | Gets object identification information |
| [getOriginalAddressString()](#getOriginalAddressString--) | 获取或设置原始电子邮件地址字符串。 |
| [getParticipationStatus()](#getParticipationStatus--) | 获取或设置日历用户的参与状态。 |
| [getPrefered()](#getPrefered--) | 获取或设置一个值，以定义是否首选电子邮件地址。 |
| [getRoutingType()](#getRoutingType--) | 获取或设置电子邮件的路由类型。 |
| [getUser()](#getUser--) | 获取用户名。 |
| [get_Item(int i)](#get-Item-int-) | 获取指定索引处的元素。 |
| [hashCode()](#hashCode--) | GetHashCode 为此对象返回哈希函数。 |
| [hashCode(EmailAddress obj)](#hashCode-com.aspose.email.EmailAddress-) | GetHashCode 为指定对象返回哈希函数。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(EmailAddress a, EmailAddress b)](#op-Equality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | 确定指定的对象是否相等。 |
| [op_Inequality(EmailAddress a, EmailAddress b)](#op-Inequality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | 确定指定的对象是否不相等。 |
| [setAddress(String value)](#setAddress-java.lang.String-) | 获取或设置电子邮件地址。 |
| [setCategory(EmailAddressCategory value)](#setCategory-com.aspose.email.EmailAddressCategory-) | 获取或设置对象类别 |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | 获取或设置显示名称。 |
| [setParticipationStatus(int value)](#setParticipationStatus-int-) | 获取或设置日历用户的参与状态。 |
| [setPrefered(boolean value)](#setPrefered-boolean-) | 获取或设置一个值，以定义是否首选电子邮件地址。 |
| [setRoutingType(String value)](#setRoutingType-java.lang.String-) | 获取或设置电子邮件的路由类型。 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [to_MailAddress(MailAddressCollection addresses)](#to-MailAddress-com.aspose.email.MailAddressCollection-) | 执行从 [MailAddressCollection](../../com.aspose.email/mailaddresscollection) 到 [MailAddress](../../com.aspose.email/mailaddress) 的隐式转换。 |
| [to_MailAddress(String address)](#to-MailAddress-java.lang.String-) | 执行从 String 到 [MailAddress](../../com.aspose.email/mailaddress) 的隐式转换。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmailAddress() {#EmailAddress--}
```
public EmailAddress()
```


初始化 [EmailAddress](../../com.aspose.email/emailaddress) 类的新实例。

### EmailAddress(String address) {#EmailAddress-java.lang.String-}
```
public EmailAddress(String address)
```


初始化 [EmailAddress](../../com.aspose.email/emailaddress) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | java.lang.String | 邮件地址。 |

### EmailAddress(String address, String displayName) {#EmailAddress-java.lang.String-java.lang.String-}
```
public EmailAddress(String address, String displayName)
```


初始化 [EmailAddress](../../com.aspose.email/emailaddress) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | java.lang.String | 邮件地址。 |
| displayName | java.lang.String | 显示名称。 |

### compareTo(EmailAddress obj) {#compareTo-com.aspose.email.EmailAddress-}
```
public int compareTo(EmailAddress obj)
```


比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于另一个对象之前、之后，还是与其处于相同位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [EmailAddress](../../com.aspose.email/emailaddress) | 用于与此实例比较的对象，或 null。 |

**Returns:**
int - 此方法返回：如果此值小于 value，则返回小于 0 的值；如果此值等于 value，则返回 0；如果此值大于 value，则返回大于 0 的值。
### equals(EmailAddress obj) {#equals-com.aspose.email.EmailAddress-}
```
public final boolean equals(EmailAddress obj)
```


确定指定的 Object 是否等于当前 Object。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [EmailAddress](../../com.aspose.email/emailaddress) | 用于与当前对象比较的对象。 |

**Returns:**
boolean - 返回一个布尔值，指示传入的对象 obj 是否等于此对象。
### equals(EmailAddress x, EmailAddress y) {#equals-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-}
```
public final boolean equals(EmailAddress x, EmailAddress y)
```


确定指定的对象实例是否被视为相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | [EmailAddress](../../com.aspose.email/emailaddress) | 要比较的第一个对象。 |
| y | [EmailAddress](../../com.aspose.email/emailaddress) | 要比较的第二个对象。 |

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
### getAddress() {#getAddress--}
```
public final String getAddress()
```


获取或设置电子邮件地址。

值：包含电子邮件地址的字符串。

**Returns:**
java.lang.String
### getCategory() {#getCategory--}
```
public final EmailAddressCategory getCategory()
```


获取或设置对象类别

**Returns:**
[EmailAddressCategory](../../com.aspose.email/emailaddresscategory)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public final int getCount()
```


包含邮件地址的计数。

**Returns:**
int
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


获取或设置显示名称。

值：包含显示名称的字符串。

**Returns:**
java.lang.String
### getHost() {#getHost--}
```
public final String getHost()
```


获取地址的主机部分。

值：包含主机名的字符串。

**Returns:**
java.lang.String
### getId() {#getId--}
```
public final ObjectIdentifier getId()
```


Gets object identification information

**Returns:**
[ObjectIdentifier](../../com.aspose.email/objectidentifier)
### getOriginalAddressString() {#getOriginalAddressString--}
```
public final String getOriginalAddressString()
```


获取或设置原始电子邮件地址字符串。

值：包含原始电子邮件地址的字符串。

**Returns:**
java.lang.String
### getParticipationStatus() {#getParticipationStatus--}
```
public final int getParticipationStatus()
```


获取或设置日历用户的参与状态。

**Returns:**
int
### getPrefered() {#getPrefered--}
```
public final boolean getPrefered()
```


获取或设置一个值，以定义是否首选电子邮件地址。

**Returns:**
boolean
### getRoutingType() {#getRoutingType--}
```
public final String getRoutingType()
```


获取或设置电子邮件的路由类型。

**Returns:**
java.lang.String
### getUser() {#getUser--}
```
public final String getUser()
```


获取用户名。

值：包含用户名的字符串。

**Returns:**
java.lang.String
### get_Item(int i) {#get-Item-int-}
```
public final MailAddress get_Item(int i)
```


获取指定索引处的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| i | int | 要获取或设置的元素的零基索引。 |

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress) - Returns the element at the specified index.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 为此对象返回哈希函数。

**Returns:**
int - 返回此对象的哈希函数。
### hashCode(EmailAddress obj) {#hashCode-com.aspose.email.EmailAddress-}
```
public final int hashCode(EmailAddress obj)
```


GetHashCode 为指定对象返回哈希函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [EmailAddress](../../com.aspose.email/emailaddress) | 要返回哈希码的对象。 |

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




### op_Equality(EmailAddress a, EmailAddress b) {#op-Equality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-}
```
public static boolean op_Equality(EmailAddress a, EmailAddress b)
```


确定指定的对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [EmailAddress](../../com.aspose.email/emailaddress) | 要比较的第一个对象 |
| b | [EmailAddress](../../com.aspose.email/emailaddress) | 要比较的第二个对象 |

**Returns:**
boolean - 如果对象相等则返回 true，否则返回 false。
### op_Inequality(EmailAddress a, EmailAddress b) {#op-Inequality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-}
```
public static boolean op_Inequality(EmailAddress a, EmailAddress b)
```


确定指定的对象是否不相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [EmailAddress](../../com.aspose.email/emailaddress) | 要比较的第一个对象 |
| b | [EmailAddress](../../com.aspose.email/emailaddress) | 要比较的第二个对象 |

**Returns:**
boolean - 如果对象不相等则返回 true，否则返回 false。
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


获取或设置电子邮件地址。

值：包含电子邮件地址的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCategory(EmailAddressCategory value) {#setCategory-com.aspose.email.EmailAddressCategory-}
```
public final void setCategory(EmailAddressCategory value)
```


获取或设置对象类别

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailAddressCategory](../../com.aspose.email/emailaddresscategory) |  |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


获取或设置显示名称。

值：包含显示名称的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setParticipationStatus(int value) {#setParticipationStatus-int-}
```
public final void setParticipationStatus(int value)
```


获取或设置日历用户的参与状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setPrefered(boolean value) {#setPrefered-boolean-}
```
public final void setPrefered(boolean value)
```


获取或设置一个值，以定义是否首选电子邮件地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setRoutingType(String value) {#setRoutingType-java.lang.String-}
```
public final void setRoutingType(String value)
```


获取或设置电子邮件的路由类型。

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
java.lang.String - 返回表示当前对象的字符串。
### to_MailAddress(MailAddressCollection addresses) {#to-MailAddress-com.aspose.email.MailAddressCollection-}
```
public static MailAddress to_MailAddress(MailAddressCollection addresses)
```


执行从 [MailAddressCollection](../../com.aspose.email/mailaddresscollection) 到 [MailAddress](../../com.aspose.email/mailaddress) 的隐式转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| addresses | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | 地址集合。 |

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress) - The result of the conversion.
### to_MailAddress(String address) {#to-MailAddress-java.lang.String-}
```
public static MailAddress to_MailAddress(String address)
```


执行从 String 到 [MailAddress](../../com.aspose.email/mailaddress) 的隐式转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | java.lang.String | 地址。 |

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress) - The result of the conversion.
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

