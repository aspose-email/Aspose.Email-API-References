---
title: PidTagPropertyDescriptor
second_title: Aspose.Email for Android via Java API 参考
description: 类包含属性描述信息。
type: docs
weight: 352
url: /zh/androidjava/com.aspose.email/pidtagpropertydescriptor/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.PropertyDescriptor](../../com.aspose.email/propertydescriptor)
```
public class PidTagPropertyDescriptor extends PropertyDescriptor
```

类包含属性描述信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PidTagPropertyDescriptor(int id, int type)](#PidTagPropertyDescriptor-int-int-) | 初始化一个新的 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 类实例，该属性由 16 位属性 ID 和 16 位属性类型定义。 |
| [PidTagPropertyDescriptor(String canonicalName, int id, int type)](#PidTagPropertyDescriptor-java.lang.String-int-int-) | 初始化一个新的 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 类实例，该属性由 16 位属性 ID 和 16 位属性类型定义。 |
| [PidTagPropertyDescriptor(String canonicalName, String name, int id, int type)](#PidTagPropertyDescriptor-java.lang.String-java.lang.String-int-int-) | 初始化一个新的 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 类实例，该属性由 16 位属性 ID 和 16 位属性类型定义。 |
| [PidTagPropertyDescriptor(long tag)](#PidTagPropertyDescriptor-long-) | 初始化一个新的 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 类实例，该属性由 16 位属性 ID 和 16 位属性类型定义。 |
| [PidTagPropertyDescriptor(String canonicalName, String name, long tag)](#PidTagPropertyDescriptor-java.lang.String-java.lang.String-long-) | 初始化一个新的 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 类实例，该属性由 16 位属性 ID 和 16 位属性类型定义。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | 指示当前对象是否等于同类型的另一个对象。 |
| [equals(Object other)](#equals-java.lang.Object-) | 确定指定的 System.Object 是否等于当前的 System.Object。 |
| [getCanonicalName()](#getCanonicalName--) | 文档中用于引用该属性的名称。 |
| [getClass()](#getClass--) |  |
| [getDataType()](#getDataType--) | 属性值类型，如 [MS-OXCDATA] 中所述，指定该属性允许的值的类型。 |
| [getId()](#getId--) | 获取标记属性的无符号 16 位数量。 |
| [getInstance(MapiProperty property)](#getInstance-com.aspose.email.MapiProperty-) | 从 MAPI 属性检索 [PropertyDescriptor](../../com.aspose.email/propertydescriptor) 对象 |
| [getInstance(int id, int dataType)](#getInstance-int-int-) | 检索 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 对象 |
| [getInstance(String name, int dataType, UUID propertySet)](#getInstance-java.lang.String-int-java.util.UUID-) | 检索 [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) 对象 |
| [getInstance(long tag)](#getInstance-long-) | 检索 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 对象 |
| [getInstance(long lid, int dataType, UUID propertySet)](#getInstance-long-int-java.util.UUID-) | 检索 [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) 对象 |
| [getMultipleValuesDataType()](#getMultipleValuesDataType--) | 指示数据类型是否包含多个值 |
| [getName()](#getName--) | 获取标识属性的字符串。 |
| [getTag()](#getTag--) | 属性标签是一个 32 位数字，其中位 16 到 31 包含唯一的属性标识符，位 0 到 15 包含属性类型。 |
| [getUse8BitStringAsUnicode()](#getUse8BitStringAsUnicode--) | 指定是否应将 PropertyDataType.String8 解释为 PropertyDataType.String |
| [hashCode()](#hashCode--) | 作为一种类型的哈希函数。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | 确定指定的对象是否相互等价。 |
| [op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | 确定指定的对象是否相互等价。 |
| [op_Inequality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | 确定指定的对象是否相互不等。 |
| [op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | 确定指定的对象是否相互不等。 |
| [parse(String data)](#parse-java.lang.String-) | 初始化一个新的 [PropertyDescriptor](../../com.aspose.email/propertydescriptor) 类实例 |
| [setUse8BitStringAsUnicode(boolean value)](#setUse8BitStringAsUnicode-boolean-) | 指定是否应将 PropertyDataType.String8 解释为 PropertyDataType.String |
| [toString()](#toString--) | 返回表示属性描述的字符串。 |
| [to_PidTagPropertyDescriptor(long tag)](#to-PidTagPropertyDescriptor-long-) | 将标签值转换为已标记属性 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PidTagPropertyDescriptor(int id, int type) {#PidTagPropertyDescriptor-int-int-}
```
public PidTagPropertyDescriptor(int id, int type)
```


初始化一个新的 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 类实例。该属性由 16 位属性 ID 和 16 位属性类型定义。已标记属性的属性 ID 范围为 0x001 – 0x7FFF。属性 ID 范围 0x8000 – 0x8FFF 保留用于分配给命名属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | int | 标识已标记属性的无符号 16 位数量。 |
| type | int | 指定属性允许的值的类型。 |

### PidTagPropertyDescriptor(String canonicalName, int id, int type) {#PidTagPropertyDescriptor-java.lang.String-int-int-}
```
public PidTagPropertyDescriptor(String canonicalName, int id, int type)
```


初始化一个新的 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 类实例。该属性由 16 位属性 ID 和 16 位属性类型定义。已标记属性的属性 ID 范围为 0x001 – 0x7FFF。属性 ID 范围 0x8000 – 0x8FFF 保留用于分配给命名属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| canonicalName | java.lang.String | 文档中用于引用该属性的名称。 |
| id | int | 标识已标记属性的无符号 16 位数量。 |
| type | int | 指定属性允许的值的类型。 |

### PidTagPropertyDescriptor(String canonicalName, String name, int id, int type) {#PidTagPropertyDescriptor-java.lang.String-java.lang.String-int-int-}
```
public PidTagPropertyDescriptor(String canonicalName, String name, int id, int type)
```


初始化一个新的 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 类实例。该属性由 16 位属性 ID 和 16 位属性类型定义。已标记属性的属性 ID 范围为 0x001 – 0x7FFF。属性 ID 范围 0x8000 – 0x8FFF 保留用于分配给命名属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| canonicalName | java.lang.String | 文档中用于引用该属性的名称。 |
| name | java.lang.String | 文档中用于引用该属性的 MAPI 名称。 |
| id | int | 标识已标记属性的无符号 16 位数量。 |
| type | int | 指定属性允许的值的类型。 |

### PidTagPropertyDescriptor(long tag) {#PidTagPropertyDescriptor-long-}
```
public PidTagPropertyDescriptor(long tag)
```


初始化一个新的 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 类实例。该属性由 16 位属性 ID 和 16 位属性类型定义。已标记属性的属性 ID 范围为 0x001 – 0x7FFF。属性 ID 范围 0x8000 – 0x8FFF 保留用于分配给命名属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 标签是一个 32 位数字，其中位 16 到 31 包含唯一的属性标识符，位 0 到 15 包含属性类型。 |

### PidTagPropertyDescriptor(String canonicalName, String name, long tag) {#PidTagPropertyDescriptor-java.lang.String-java.lang.String-long-}
```
public PidTagPropertyDescriptor(String canonicalName, String name, long tag)
```


初始化一个新的 [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) 类实例。该属性由 16 位属性 ID 和 16 位属性类型定义。已标记属性的属性 ID 范围为 0x001 – 0x7FFF。属性 ID 范围 0x8000 – 0x8FFF 保留用于分配给命名属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| canonicalName | java.lang.String | 文档中用于引用该属性的名称。 |
| name | java.lang.String | 文档中用于引用该属性的 MAPI 名称。 |
| tag | long | 标签是一个 32 位数字，其中位 16 到 31 包含唯一的属性标识符，位 0 到 15 包含属性类型。 |

### equals(PropertyDescriptor other) {#equals-com.aspose.email.PropertyDescriptor-}
```
public boolean equals(PropertyDescriptor other)
```


指示当前对象是否等于同类型的另一个对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 用于与此对象比较的对象。 |

**Returns:**
布尔值 - 如果当前对象等于另一个参数则为 true；否则为 false。
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


确定指定的 System.Object 是否等于当前的 System.Object。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | java.lang.Object |  |

**Returns:**
布尔值 - 如果指定的 System.Object 等于当前的 System.Object 则为 true；否则为 false。
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
### getId() {#getId--}
```
public final int getId()
```


获取标识已标记属性的无符号 16 位数量。属性 ID 并非一定唯一。除 0x6800 到 0x7BFF 范围的属性 ID 外，属性 ID 与数据类型的组合是唯一的。0x6800 到 0x7BFF 范围的属性 ID 由消息类定义。

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
### getTag() {#getTag--}
```
public final long getTag()
```


属性标签是一个 32 位数字，其中位 16 到 31 包含唯一的属性标识符，位 0 到 15 包含属性类型。

**Returns:**
long
### getUse8BitStringAsUnicode() {#getUse8BitStringAsUnicode--}
```
public static boolean getUse8BitStringAsUnicode()
```


指定是否应将 PropertyDataType.String8 解释为 PropertyDataType.String

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


作为一种类型的哈希函数。

**Returns:**
int - 当前对象的哈希码。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Equality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Equality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)
```


确定指定的对象是否相互等价。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd1 | [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) | 用于与另一个对象比较的对象。 |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 用于与另一个对象比较的对象。 |

**Returns:**
boolean - 如果指定的 PropertyDescriptor 等于另一个 PropertyDescriptor，则为 true；否则为 false。
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
### op_Inequality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Inequality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Inequality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)
```


确定指定的对象是否相互不等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd1 | [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) | 用于与另一个对象比较的对象。 |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 用于与另一个对象比较的对象。 |

**Returns:**
boolean - 如果指定的 PropertyDescriptor 不等于另一个 PropertyDescriptor，则为 true；否则为 false。
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


返回表示属性描述的字符串。

**Returns:**
java.lang.String - 表示属性描述的字符串。
### to_PidTagPropertyDescriptor(long tag) {#to-PidTagPropertyDescriptor-long-}
```
public static PidTagPropertyDescriptor to_PidTagPropertyDescriptor(long tag)
```


将标签值转换为已标记属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 标签属性的标签值 |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor)
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

