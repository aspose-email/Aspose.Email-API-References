---
title: PostalAddress
second_title: Aspose.Email for Android via Java API 参考
description: 表示邮政地址。
type: docs
weight: 353
url: /zh/androidjava/com.aspose.email/postaladdress/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.ms.System.IEquatable
```
public class PostalAddress implements Comparable<PostalAddress>, System.IEquatable<PostalAddress>
```

表示邮政地址。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PostalAddress()](#PostalAddress--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [compareTo(PostalAddress obj)](#compareTo-com.aspose.email.PostalAddress-) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于另一个对象之前、之后，还是与其处于相同位置。 |
| [equals(PostalAddress obj)](#equals-com.aspose.email.PostalAddress-) |  |
| [equals(PostalAddress x, PostalAddress y)](#equals-com.aspose.email.PostalAddress-com.aspose.email.PostalAddress-) | 确定指定的对象实例是否被视为相等。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于当前 Object。 |
| [getAddress()](#getAddress--) | 获取或设置地址 |
| [getCategory()](#getCategory--) | 获取或设置对象类别 |
| [getCity()](#getCity--) | 获取或设置城市 |
| [getClass()](#getClass--) |  |
| [getCountry()](#getCountry--) | 获取或设置国家 |
| [getCountryCode()](#getCountryCode--) | 获取或设置国家代码 |
| [getPostOfficeBox()](#getPostOfficeBox--) | 获取或设置邮政信箱 |
| [getPostalCode()](#getPostalCode--) | 获取或设置邮政编码 |
| [getPrefered()](#getPrefered--) | 获取或设置一个定义是否首选邮寄地址的值. |
| [getStateOrProvince()](#getStateOrProvince--) | 获取或设置地区 |
| [getStreet()](#getStreet--) | 获取或设置街道 |
| [hashCode()](#hashCode--) | GetHashCode 为此对象返回哈希函数。 |
| [hashCode(PostalAddress obj)](#hashCode-com.aspose.email.PostalAddress-) | GetHashCode 为指定对象返回哈希函数。 |
| [isMailingAddress()](#isMailingAddress--) | 获取或设置一个定义地址是否可用于邮件投递的值. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PostalAddress a, PostalAddress b)](#op-Equality-com.aspose.email.PostalAddress-com.aspose.email.PostalAddress-) | 确定指定的对象是否相等。 |
| [op_Inequality(PostalAddress a, PostalAddress b)](#op-Inequality-com.aspose.email.PostalAddress-com.aspose.email.PostalAddress-) | 确定指定的对象是否不相等。 |
| [setAddress(String value)](#setAddress-java.lang.String-) | 获取或设置地址 |
| [setCategory(PostalAddressCategory value)](#setCategory-com.aspose.email.PostalAddressCategory-) | 获取或设置对象类别 |
| [setCity(String value)](#setCity-java.lang.String-) | 获取或设置城市 |
| [setCountry(String value)](#setCountry-java.lang.String-) | 获取或设置国家 |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | 获取或设置国家代码 |
| [setMailingAddress(boolean value)](#setMailingAddress-boolean-) | 获取或设置一个定义地址是否可用于邮件投递的值. |
| [setPostOfficeBox(String value)](#setPostOfficeBox-java.lang.String-) | 获取或设置邮政信箱 |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | 获取或设置邮政编码 |
| [setPrefered(boolean value)](#setPrefered-boolean-) | 获取或设置一个定义是否首选邮寄地址的值. |
| [setStateOrProvince(String value)](#setStateOrProvince-java.lang.String-) | 获取或设置地区 |
| [setStreet(String value)](#setStreet-java.lang.String-) | 获取或设置街道 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PostalAddress() {#PostalAddress--}
```
public PostalAddress()
```


### compareTo(PostalAddress obj) {#compareTo-com.aspose.email.PostalAddress-}
```
public int compareTo(PostalAddress obj)
```


比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于另一个对象之前、之后，还是与其处于相同位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [PostalAddress](../../com.aspose.email/postaladdress) | 用于与此实例比较的对象，或 null。 |

**Returns:**
int - 此方法返回：如果此值小于 value，则返回小于 0 的值；如果此值等于 value，则返回 0；如果此值大于 value，则返回大于 0 的值。
### equals(PostalAddress obj) {#equals-com.aspose.email.PostalAddress-}
```
public final boolean equals(PostalAddress obj)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [PostalAddress](../../com.aspose.email/postaladdress) |  |

**Returns:**
boolean
### equals(PostalAddress x, PostalAddress y) {#equals-com.aspose.email.PostalAddress-com.aspose.email.PostalAddress-}
```
public final boolean equals(PostalAddress x, PostalAddress y)
```


确定指定的对象实例是否被视为相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | [PostalAddress](../../com.aspose.email/postaladdress) | 要比较的第一个对象。 |
| y | [PostalAddress](../../com.aspose.email/postaladdress) | 要比较的第二个对象。 |

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


获取或设置地址

**Returns:**
java.lang.String
### getCategory() {#getCategory--}
```
public final PostalAddressCategory getCategory()
```


获取或设置对象类别

**Returns:**
[PostalAddressCategory](../../com.aspose.email/postaladdresscategory)
### getCity() {#getCity--}
```
public final String getCity()
```


获取或设置城市

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountry() {#getCountry--}
```
public final String getCountry()
```


获取或设置国家

**Returns:**
java.lang.String
### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


获取或设置国家代码

**Returns:**
java.lang.String
### getPostOfficeBox() {#getPostOfficeBox--}
```
public final String getPostOfficeBox()
```


获取或设置邮政信箱

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


获取或设置邮政编码

**Returns:**
java.lang.String
### getPrefered() {#getPrefered--}
```
public final boolean getPrefered()
```


获取或设置一个定义是否首选邮寄地址的值.

**Returns:**
boolean
### getStateOrProvince() {#getStateOrProvince--}
```
public final String getStateOrProvince()
```


获取或设置地区

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public final String getStreet()
```


获取或设置街道

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 为此对象返回哈希函数。

**Returns:**
int - 返回此对象的哈希函数。
### hashCode(PostalAddress obj) {#hashCode-com.aspose.email.PostalAddress-}
```
public int hashCode(PostalAddress obj)
```


GetHashCode 为指定对象返回哈希函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [PostalAddress](../../com.aspose.email/postaladdress) | 要返回哈希码的对象。 |

**Returns:**
int - 为指定对象返回哈希函数。
### isMailingAddress() {#isMailingAddress--}
```
public final boolean isMailingAddress()
```


获取或设置一个定义地址是否可用于邮件投递的值.

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




### op_Equality(PostalAddress a, PostalAddress b) {#op-Equality-com.aspose.email.PostalAddress-com.aspose.email.PostalAddress-}
```
public static boolean op_Equality(PostalAddress a, PostalAddress b)
```


确定指定的对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [PostalAddress](../../com.aspose.email/postaladdress) | 要比较的第一个对象 |
| b | [PostalAddress](../../com.aspose.email/postaladdress) | 要比较的第二个对象 |

**Returns:**
boolean - 如果对象相等则返回 true，否则返回 false。
### op_Inequality(PostalAddress a, PostalAddress b) {#op-Inequality-com.aspose.email.PostalAddress-com.aspose.email.PostalAddress-}
```
public static boolean op_Inequality(PostalAddress a, PostalAddress b)
```


确定指定的对象是否不相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [PostalAddress](../../com.aspose.email/postaladdress) | 要比较的第一个对象 |
| b | [PostalAddress](../../com.aspose.email/postaladdress) | 要比较的第二个对象 |

**Returns:**
boolean - 如果对象不相等则返回 true，否则返回 false。
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


获取或设置地址

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCategory(PostalAddressCategory value) {#setCategory-com.aspose.email.PostalAddressCategory-}
```
public final void setCategory(PostalAddressCategory value)
```


获取或设置对象类别

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PostalAddressCategory](../../com.aspose.email/postaladdresscategory) |  |

### setCity(String value) {#setCity-java.lang.String-}
```
public final void setCity(String value)
```


获取或设置城市

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCountry(String value) {#setCountry-java.lang.String-}
```
public final void setCountry(String value)
```


获取或设置国家

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


获取或设置国家代码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMailingAddress(boolean value) {#setMailingAddress-boolean-}
```
public final void setMailingAddress(boolean value)
```


获取或设置一个定义地址是否可用于邮件投递的值.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setPostOfficeBox(String value) {#setPostOfficeBox-java.lang.String-}
```
public final void setPostOfficeBox(String value)
```


获取或设置邮政信箱

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


获取或设置邮政编码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setPrefered(boolean value) {#setPrefered-boolean-}
```
public final void setPrefered(boolean value)
```


获取或设置一个定义是否首选邮寄地址的值.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setStateOrProvince(String value) {#setStateOrProvince-java.lang.String-}
```
public final void setStateOrProvince(String value)
```


获取或设置地区

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


获取或设置街道

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

