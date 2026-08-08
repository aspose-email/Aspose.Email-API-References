---
title: PropertyDescriptor
second_title: Aspose.Email for Android via Java API 参考
description: 类包含属性描述信息。
type: docs
weight: 359
url: /zh/androidjava/com.aspose.email/propertydescriptor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class PropertyDescriptor implements System.IEquatable<PropertyDescriptor>
```

类包含属性描述信息。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | 指示当前对象是否等于同类型的另一个对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanonicalName()](#getCanonicalName--) | 文档中用于引用该属性的名称。 |
| [getClass()](#getClass--) |  |
| [getDataType()](#getDataType--) | 属性值类型，如 [MS-OXCDATA] 中所述，指定该属性允许的值的类型。 |
| [getInstance(MapiProperty property)](#getInstance-com.aspose.email.MapiProperty-) | 从 MAPI 属性检索 [PropertyDescriptor](../../com.aspose.email/propertydescriptor) 对象 |
| [getInstance(int id, int dataType)](#getInstance-int-int-) | 检索 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 对象 |
| [getInstance(String name, int dataType, UUID propertySet)](#getInstance-java.lang.String-int-java.util.UUID-) | 检索 [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) 对象 |
| [getInstance(long tag)](#getInstance-long-) | 检索 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 对象 |
| [getInstance(long lid, int dataType, UUID propertySet)](#getInstance-long-int-java.util.UUID-) | 检索 [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) 对象 |
| [getMultipleValuesDataType()](#getMultipleValuesDataType--) | 指示数据类型是否包含多个值 |
| [getName()](#getName--) | 获取标识属性的字符串。 |
| [getUse8BitStringAsUnicode()](#getUse8BitStringAsUnicode--) | 指定是否应将 PropertyDataType.String8 解释为 PropertyDataType.String |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | 确定指定的对象是否相互等价。 |
| [op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | 确定指定的对象是否相互不等。 |
| [parse(String data)](#parse-java.lang.String-) | 初始化一个新的 [PropertyDescriptor](../../com.aspose.email/propertydescriptor) 类实例 |
| [setUse8BitStringAsUnicode(boolean value)](#setUse8BitStringAsUnicode-boolean-) | 指定是否应将 PropertyDataType.String8 解释为 PropertyDataType.String |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(PropertyDescriptor other) {#equals-com.aspose.email.PropertyDescriptor-}
```
public abstract boolean equals(PropertyDescriptor other)
```


指示当前对象是否等于同类型的另一个对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 用于与此对象比较的对象。 |

**Returns:**
布尔值 - 如果当前对象等于另一个参数则为 true；否则为 false。
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
### getCanonicalName() {#getCanonicalName--}
```
public final String getCanonicalName()
```


文档中用于引用该属性的名称。规范名称的前缀标识实现者对属性的基本特性。规范命名结构使用三类前缀来标识规范属性名称：
* PidLid 前缀：通过无符号 32 位数量以及属性集标识的属性。
* PidName 前缀：通过字符串名称以及属性集标识的属性。
* PidTag 前缀：通过无符号 16 位数量标识的属性。

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataType() {#getDataType--}
```
public final int getDataType()
```


属性值类型，如 [MS-OXCDATA] 中所述，指定该属性允许的值的类型。

**Returns:**
int
### getInstance(MapiProperty property) {#getInstance-com.aspose.email.MapiProperty-}
```
public static PropertyDescriptor getInstance(MapiProperty property)
```


从 MAPI 属性检索 [PropertyDescriptor](../../com.aspose.email/propertydescriptor) 对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | [MapiProperty](../../com.aspose.email/mapiproperty) 对象 |

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor)
### getInstance(int id, int dataType) {#getInstance-int-int-}
```
public static PidTagPropertyDescriptor getInstance(int id, int dataType)
```


检索 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | int | 属性的 Id |
| dataType | int | 属性的数据类型 |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) - [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object
### getInstance(String name, int dataType, UUID propertySet) {#getInstance-java.lang.String-int-java.util.UUID-}
```
public static PidNamePropertyDescriptor getInstance(String name, int dataType, UUID propertySet)
```


检索 [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) 对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 属性的名称 |
| dataType | int | 属性的数据类型 |
| propertySet | java.util.UUID | 属性的 PropertySet |

**Returns:**
[PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) - [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) object
### getInstance(long tag) {#getInstance-long-}
```
public static PidTagPropertyDescriptor getInstance(long tag)
```


检索 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 属性的标签 |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) - [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object
### getInstance(long lid, int dataType, UUID propertySet) {#getInstance-long-int-java.util.UUID-}
```
public static PidLidPropertyDescriptor getInstance(long lid, int dataType, UUID propertySet)
```


检索 [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) 对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标识符 | long | 属性的长标识符 |
| dataType | int | 属性的数据类型 |
| propertySet | java.util.UUID | 属性的 PropertySet |

**Returns:**
[PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) - [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) object
### getMultipleValuesDataType() {#getMultipleValuesDataType--}
```
public final boolean getMultipleValuesDataType()
```


指示数据类型是否包含多个值

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


获取标识属性的字符串。

**Returns:**
java.lang.String
### getUse8BitStringAsUnicode() {#getUse8BitStringAsUnicode--}
```
public static boolean getUse8BitStringAsUnicode()
```


指定是否应将 PropertyDataType.String8 解释为 PropertyDataType.String

**Returns:**
boolean
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




### op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)
```


确定指定的对象是否相互等价。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd1 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 用于与另一个对象比较的对象。 |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 用于与另一个对象比较的对象。 |

**Returns:**
boolean - 如果指定的 PropertyDescriptor 等于另一个 PropertyDescriptor，则为 true；否则为 false。
### op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)
```


确定指定的对象是否相互不等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd1 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 用于与另一个对象比较的对象。 |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 用于与另一个对象比较的对象。 |

**Returns:**
boolean - 如果指定的 PropertyDescriptor 不等于另一个 PropertyDescriptor，则为 true；否则为 false。
### parse(String data) {#parse-java.lang.String-}
```
public static PropertyDescriptor parse(String data)
```


初始化一个新的 [PropertyDescriptor](../../com.aspose.email/propertydescriptor) 类实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | java.lang.String | 表示属性描述的字符串。 |

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor)
### setUse8BitStringAsUnicode(boolean value) {#setUse8BitStringAsUnicode-boolean-}
```
public static void setUse8BitStringAsUnicode(boolean value)
```


指定是否应将 PropertyDataType.String8 解释为 PropertyDataType.String

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

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

