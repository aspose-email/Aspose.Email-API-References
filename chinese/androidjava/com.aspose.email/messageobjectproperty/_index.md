---
title: MessageObjectProperty
second_title: Aspose.Email for Android via Java API 参考
description: 表示位于 . 的属性。
type: docs
weight: 314
url: /zh/androidjava/com.aspose.email/messageobjectproperty/
---

**Inheritance:**
java.lang.Object
```
public final class MessageObjectProperty
```

表示位于 [MessageObject](../../com.aspose.email/messageobject) 上的属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MessageObjectProperty(long propertyTag, int flags, Object value)](#MessageObjectProperty-long-int-java.lang.Object-) | 初始化 [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) 类的新实例。 |
| [MessageObjectProperty(int id, int type, int flags, Object value)](#MessageObjectProperty-int-int-int-java.lang.Object-) | 初始化 [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAtomic()](#getAtomic--) | 获取一个值，指示此 [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) 是否为原子。 |
| [getClass()](#getClass--) |  |
| [getFlags()](#getFlags--) | 获取属性上设置的标志。 |
| [getGuid()](#getGuid--) | 获取或设置已命名属性的 GUID。 |
| [getId()](#getId--) | 获取属性的 ID。 |
| [getName()](#getName--) | 获取或设置属性的名称（如果已命名）。 |
| [getNameId()](#getNameId--) | 获取或设置属性的名称 ID（如果已命名）。 |
| [getNamed()](#getNamed--) | 获取一个值，指示此 [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) 是否为已命名属性。 |
| [getPropertyKind()](#getPropertyKind--) | 获取或设置属性的类型（如果已命名）。 |
| [getPropertyTag()](#getPropertyTag--) | 获取属性标签，这是一个包含 Id (\#getId.getId) 和 PropertyType (\#getPropertyType.getPropertyType) 的组合值。 |
| [getPropertyType()](#getPropertyType--) | 获取属性的类型。 |
| [getValue()](#getValue--) | 获取或设置属性的值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(UUID value)](#setGuid-java.util.UUID-) | 获取或设置已命名属性的 GUID。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置属性的名称（如果已命名）。 |
| [setNameId(long value)](#setNameId-long-) | 获取或设置属性的名称 ID（如果已命名）。 |
| [setPropertyKind(int value)](#setPropertyKind-int-) | 获取或设置属性的类型（如果已命名）。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 获取或设置属性的值。 |
| [toDateTime()](#toDateTime--) | 将属性的值转换为 DateTime。 |
| [toGuid()](#toGuid--) | 将属性的值转换为 Guid (\#getGuid.getGuid/\#setGuid(Guid).setGuid(Guid))。 |
| [toInt()](#toInt--) | 将属性的值转换为整数。 |
| [toList()](#toList--) | 将属性的值转换为值列表。 |
| [toString()](#toString--) |  |
| [toStringRepresentation()](#toStringRepresentation--) | 将属性的值转换为字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageObjectProperty(long propertyTag, int flags, Object value) {#MessageObjectProperty-long-int-java.lang.Object-}
```
public MessageObjectProperty(long propertyTag, int flags, Object value)
```


初始化 [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyTag | long | 属性标签。 |
| flags | int | 要设置的标志。 |
| value | java.lang.Object | 属性的值。 |

### MessageObjectProperty(int id, int type, int flags, Object value) {#MessageObjectProperty-int-int-int-java.lang.Object-}
```
public MessageObjectProperty(int id, int type, int flags, Object value)
```


初始化 [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | int | ID。 |
| type | int | 属性的类型。 |
| flags | int | 要设置的标志。 |
| value | java.lang.Object | 属性的值。 |

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
### getAtomic() {#getAtomic--}
```
public final boolean getAtomic()
```


获取一个值，指示此 [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) 是否为原子。

值：  true  如果是原子；否则，  false 。

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFlags() {#getFlags--}
```
public final int getFlags()
```


获取属性上设置的标志。

值： 标志。

**Returns:**
int
### getGuid() {#getGuid--}
```
public final UUID getGuid()
```


获取或设置已命名属性的 GUID。

值： GUID。

**Returns:**
java.util.UUID
### getId() {#getId--}
```
public final int getId()
```


获取属性的 ID。

值： 属性的 ID。

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


获取或设置属性的名称（如果已命名）。

值：名称。

**Returns:**
java.lang.String
### getNameId() {#getNameId--}
```
public final long getNameId()
```


获取或设置属性的名称 ID（如果已命名）。

值： 名称 ID。

**Returns:**
long
### getNamed() {#getNamed--}
```
public final boolean getNamed()
```


获取一个值，指示此 [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) 是否为已命名属性。

值：  true  如果已命名；否则，  false 。

--------------------

已命名属性由其 ID 决定，此类 ID 的范围是 [0x8000,0xfffe]。

**Returns:**
boolean
### getPropertyKind() {#getPropertyKind--}
```
public final int getPropertyKind()
```


获取或设置属性的类型（如果已命名）。

Value: 属性的种类。

**Returns:**
int
### getPropertyTag() {#getPropertyTag--}
```
public final long getPropertyTag()
```


获取属性标签，这是一个包含 Id (\#getId.getId) 和 PropertyType (\#getPropertyType.getPropertyType) 的组合值。

Value: 属性标签。

**Returns:**
long
### getPropertyType() {#getPropertyType--}
```
public final int getPropertyType()
```


获取属性的类型。

Value: 属性的类型。

**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


获取或设置属性的值。

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setGuid(UUID value) {#setGuid-java.util.UUID-}
```
public final void setGuid(UUID value)
```


获取或设置已命名属性的 GUID。

值： GUID。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


获取或设置属性的名称（如果已命名）。

值：名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameId(long value) {#setNameId-long-}
```
public final void setNameId(long value)
```


获取或设置属性的名称 ID（如果已命名）。

值： 名称 ID。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### setPropertyKind(int value) {#setPropertyKind-int-}
```
public final void setPropertyKind(int value)
```


获取或设置属性的类型（如果已命名）。

Value: 属性的种类。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


获取或设置属性的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDateTime() {#toDateTime--}
```
public final Date toDateTime()
```


将属性的值转换为 DateTime。

**Returns:**
java.util.Date - DateTime 值，如果类型无法转换为 DateTime，则返回 java.util.Date\#MinValue.MinValue。

--------------------

此方法不提供数据类型的自动转换，例如，如果 MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) 属性的类型为默认，则返回默认值。
### toGuid() {#toGuid--}
```
public final UUID toGuid()
```


将属性的值转换为 Guid (\#getGuid.getGuid/\#setGuid(Guid).setGuid(Guid))。

**Returns:**
java.util.UUID - Guid 对象，如果类型无法转换为 Guid，则返回空 GUID。

--------------------

此方法不提供数据类型的自动转换，例如，如果 MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) 属性的类型为默认，则返回默认值。
### toInt() {#toInt--}
```
public final int toInt()
```


将属性的值转换为整数。

**Returns:**
int - 整数值，如果类型无法转换为整数，则返回 0。
### toList() {#toList--}
```
public System.Collections.IList toList()
```


将属性的值转换为值列表。

**Returns:**
com.aspose.ms.System.Collections.IList - IList 实现，如果类型无法转换为 IList，则返回空列表实现。

--------------------

此方法不提供数据类型的自动转换，例如，如果 MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) 属性的类型为默认，则返回默认值。
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toStringRepresentation() {#toStringRepresentation--}
```
public final String toStringRepresentation()
```


将属性的值转换为字符串。

**Returns:**
java.lang.String - 字符串值，如果类型无法转换为字符串，则返回空字符串。

--------------------

此方法不提供数据类型的自动转换，例如，如果 MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) 属性的类型为默认，则返回默认值。
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

