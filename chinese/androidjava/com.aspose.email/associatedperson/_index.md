---
title: AssociatedPerson
second_title: Aspose.Email for Android via Java API 参考
description: 描述与个人关联的组织。
type: docs
weight: 49
url: /zh/androidjava/com.aspose.email/associatedperson/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.ms.System.IEquatable
```
public class AssociatedPerson implements Comparable<AssociatedPerson>, System.IEquatable<AssociatedPerson>
```

描述与个人关联的组织。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AssociatedPerson()](#AssociatedPerson--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [compareTo(AssociatedPerson obj)](#compareTo-com.aspose.email.AssociatedPerson-) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于另一个对象之前、之后，还是与其处于相同位置。 |
| [equals(AssociatedPerson obj)](#equals-com.aspose.email.AssociatedPerson-) | 确定指定的 Object 是否等于当前 Object。 |
| [equals(AssociatedPerson x, AssociatedPerson y)](#equals-com.aspose.email.AssociatedPerson-com.aspose.email.AssociatedPerson-) | 确定指定的对象实例是否被视为相等。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于当前 Object。 |
| [getCategory()](#getCategory--) | 获取或设置对象类别 |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 获取或设置一个人的姓名 |
| [getPrefered()](#getPrefered--) | 获取或设置一个值，以定义对象是否为首选。 |
| [hashCode()](#hashCode--) | GetHashCode 为此对象返回哈希函数。 |
| [hashCode(AssociatedPerson obj)](#hashCode-com.aspose.email.AssociatedPerson-) | GetHashCode 为指定对象返回哈希函数。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(AssociatedPerson a, AssociatedPerson b)](#op-Equality-com.aspose.email.AssociatedPerson-com.aspose.email.AssociatedPerson-) | 确定指定的对象是否相等。 |
| [op_Inequality(AssociatedPerson a, AssociatedPerson b)](#op-Inequality-com.aspose.email.AssociatedPerson-com.aspose.email.AssociatedPerson-) | 确定指定的对象是否不相等。 |
| [setCategory(AssociatedPersonCategory value)](#setCategory-com.aspose.email.AssociatedPersonCategory-) | 获取或设置对象类别 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置一个人的姓名 |
| [setPrefered(boolean value)](#setPrefered-boolean-) | 获取或设置一个值，以定义对象是否为首选。 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssociatedPerson() {#AssociatedPerson--}
```
public AssociatedPerson()
```


### compareTo(AssociatedPerson obj) {#compareTo-com.aspose.email.AssociatedPerson-}
```
public int compareTo(AssociatedPerson obj)
```


比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于另一个对象之前、之后，还是与其处于相同位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [AssociatedPerson](../../com.aspose.email/associatedperson) | 用于与此实例比较的对象，或 null。 |

**Returns:**
int - 此方法返回：如果此值小于 value，则返回小于 0 的值；如果此值等于 value，则返回 0；如果此值大于 value，则返回大于 0 的值。
### equals(AssociatedPerson obj) {#equals-com.aspose.email.AssociatedPerson-}
```
public final boolean equals(AssociatedPerson obj)
```


确定指定的 Object 是否等于当前 Object。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [AssociatedPerson](../../com.aspose.email/associatedperson) | 用于与当前对象比较的对象。 |

**Returns:**
boolean - 返回一个布尔值，指示传入的对象 obj 是否等于此对象。
### equals(AssociatedPerson x, AssociatedPerson y) {#equals-com.aspose.email.AssociatedPerson-com.aspose.email.AssociatedPerson-}
```
public final boolean equals(AssociatedPerson x, AssociatedPerson y)
```


确定指定的对象实例是否被视为相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | [AssociatedPerson](../../com.aspose.email/associatedperson) | 要比较的第一个对象。 |
| y | [AssociatedPerson](../../com.aspose.email/associatedperson) | 要比较的第二个对象。 |

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
### getCategory() {#getCategory--}
```
public final AssociatedPersonCategory getCategory()
```


获取或设置对象类别

**Returns:**
[AssociatedPersonCategory](../../com.aspose.email/associatedpersoncategory)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName() {#getName--}
```
public final String getName()
```


获取或设置一个人的姓名

**Returns:**
java.lang.String
### getPrefered() {#getPrefered--}
```
public final boolean getPrefered()
```


获取或设置一个值，以定义对象是否为首选。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 为此对象返回哈希函数。

**Returns:**
int - 返回此对象的哈希函数。
### hashCode(AssociatedPerson obj) {#hashCode-com.aspose.email.AssociatedPerson-}
```
public int hashCode(AssociatedPerson obj)
```


GetHashCode 为指定对象返回哈希函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [AssociatedPerson](../../com.aspose.email/associatedperson) | 要返回哈希码的对象。 |

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




### op_Equality(AssociatedPerson a, AssociatedPerson b) {#op-Equality-com.aspose.email.AssociatedPerson-com.aspose.email.AssociatedPerson-}
```
public static boolean op_Equality(AssociatedPerson a, AssociatedPerson b)
```


确定指定的对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [AssociatedPerson](../../com.aspose.email/associatedperson) | 要比较的第一个对象 |
| b | [AssociatedPerson](../../com.aspose.email/associatedperson) | 要比较的第二个对象 |

**Returns:**
boolean - 如果对象相等则返回 true，否则返回 false。
### op_Inequality(AssociatedPerson a, AssociatedPerson b) {#op-Inequality-com.aspose.email.AssociatedPerson-com.aspose.email.AssociatedPerson-}
```
public static boolean op_Inequality(AssociatedPerson a, AssociatedPerson b)
```


确定指定的对象是否不相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [AssociatedPerson](../../com.aspose.email/associatedperson) | 要比较的第一个对象 |
| b | [AssociatedPerson](../../com.aspose.email/associatedperson) | 要比较的第二个对象 |

**Returns:**
boolean - 如果对象不相等则返回 true，否则返回 false。
### setCategory(AssociatedPersonCategory value) {#setCategory-com.aspose.email.AssociatedPersonCategory-}
```
public final void setCategory(AssociatedPersonCategory value)
```


获取或设置对象类别

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AssociatedPersonCategory](../../com.aspose.email/associatedpersoncategory) |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


获取或设置一个人的姓名

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setPrefered(boolean value) {#setPrefered-boolean-}
```
public final void setPrefered(boolean value)
```


获取或设置一个值，以定义对象是否为首选。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

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

