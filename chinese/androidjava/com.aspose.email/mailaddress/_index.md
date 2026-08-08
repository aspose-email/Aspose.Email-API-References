---
title: MailAddress
second_title: Aspose.Email for Android via Java API 参考
description: 表示消息的地址。
type: docs
weight: 188
url: /zh/androidjava/com.aspose.email/mailaddress/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IMailAddress](../../com.aspose.email/imailaddress)
```
public class MailAddress implements IMailAddress
```

表示消息的地址。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MailAddress(String address, boolean ignoreSmtpCheck)](#MailAddress-java.lang.String-boolean-) | 初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。 |
| [MailAddress(String address, String displayName, boolean ignoreSmtpCheck)](#MailAddress-java.lang.String-java.lang.String-boolean-) | 初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。 |
| [MailAddress(String address, String displayName, Charset displayNameEncoding)](#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-) | 初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。 |
| [MailAddress(String address, String displayName, Charset displayNameEncoding, boolean ignoreSmtpCheck)](#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-boolean-) | 初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。 |
| [MailAddress(String address)](#MailAddress-java.lang.String-) | 初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。 |
| [MailAddress(String address, String displayName)](#MailAddress-java.lang.String-java.lang.String-) | 初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于此实例。 |
| [getAddress()](#getAddress--) | 获取或设置电子邮件地址。 |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 包含邮件地址的计数。 |
| [getDisplayName()](#getDisplayName--) | 获取或设置显示名称。 |
| [getHost()](#getHost--) | 获取地址的主机部分。 |
| [getId()](#getId--) | Gets object identification information |
| [getOriginalAddressString()](#getOriginalAddressString--) | 获取或设置原始电子邮件地址字符串。 |
| [getParticipationStatus()](#getParticipationStatus--) | 获取或设置日历用户的参与状态。 |
| [getUser()](#getUser--) | 获取用户名。 |
| [get_Item(int i)](#get-Item-int-) | 获取指定索引处的元素。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddress(String value)](#setAddress-java.lang.String-) | 获取或设置电子邮件地址。 |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | 获取或设置显示名称。 |
| [setParticipationStatus(int value)](#setParticipationStatus-int-) | 获取或设置日历用户的参与状态。 |
| [toString()](#toString--) | 返回表示此实例的 String。 |
| [to_MailAddress(MailAddressCollection addresses)](#to-MailAddress-com.aspose.email.MailAddressCollection-) | 执行从 [MailAddressCollection](../../com.aspose.email/mailaddresscollection) 到 [MailAddress](../../com.aspose.email/mailaddress) 的隐式转换。 |
| [to_MailAddress(String address)](#to-MailAddress-java.lang.String-) | 执行从 String 到 [MailAddress](../../com.aspose.email/mailaddress) 的隐式转换。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailAddress(String address, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-boolean-}
```
public MailAddress(String address, boolean ignoreSmtpCheck)
```


初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | java.lang.String | 邮件地址。 |
| ignoreSmtpCheck | boolean | 如果设置为  true  则会省略 SMTP 检查。 |

### MailAddress(String address, String displayName, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-java.lang.String-boolean-}
```
public MailAddress(String address, String displayName, boolean ignoreSmtpCheck)
```


初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | java.lang.String | 邮件地址。 |
| displayName | java.lang.String | 显示名称。 |
| ignoreSmtpCheck | boolean | 如果设置为  true  则会省略 SMTP 检查。 |

### MailAddress(String address, String displayName, Charset displayNameEncoding) {#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public MailAddress(String address, String displayName, Charset displayNameEncoding)
```


初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | java.lang.String | 邮件地址。 |
| displayName | java.lang.String | 显示名称。 |
| displayNameEncoding | java.nio.charset.Charset | 显示名称编码。 |

### MailAddress(String address, String displayName, Charset displayNameEncoding, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-boolean-}
```
public MailAddress(String address, String displayName, Charset displayNameEncoding, boolean ignoreSmtpCheck)
```


初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | java.lang.String | 邮件地址。 |
| displayName | java.lang.String | 显示名称。 |
| displayNameEncoding | java.nio.charset.Charset | 显示名称编码。 |
| ignoreSmtpCheck | boolean | 如果设置为  true  则会省略 SMTP 检查。 |

### MailAddress(String address) {#MailAddress-java.lang.String-}
```
public MailAddress(String address)
```


初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | java.lang.String | 邮件地址。 |

### MailAddress(String address, String displayName) {#MailAddress-java.lang.String-java.lang.String-}
```
public MailAddress(String address, String displayName)
```


初始化 [MailAddress](../../com.aspose.email/mailaddress) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | java.lang.String | 邮件地址。 |
| displayName | java.lang.String | 显示名称。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 Object 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 Object。 |

**Returns:**
boolean - 如果指定的 Object 等于此实例则为 true；否则为 false。
### getAddress() {#getAddress--}
```
public final String getAddress()
```


获取或设置电子邮件地址。

值：包含电子邮件地址的字符串。

**Returns:**
java.lang.String
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


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### toString() {#toString--}
```
public String toString()
```


返回表示此实例的 String。

**Returns:**
java.lang.String - 表示此实例的 String。
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

