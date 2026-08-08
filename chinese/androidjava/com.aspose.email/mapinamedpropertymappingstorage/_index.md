---
title: MapiNamedPropertyMappingStorage
second_title: Aspose.Email for Android via Java API 参考
description: 表示已命名属性的映射
type: docs
weight: 267
url: /zh/androidjava/com.aspose.email/mapinamedpropertymappingstorage/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer)
```
public final class MapiNamedPropertyMappingStorage extends MapiPropertyContainer
```

表示已命名属性的映射
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiNamedPropertyMappingStorage()](#MapiNamedPropertyMappingStorage--) | 初始化一个新的 [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addNamedPropertyMapping(MapiProperty property, String nameId, UUID guid)](#addNamedPropertyMapping-com.aspose.email.MapiProperty-java.lang.String-java.util.UUID-) | 为字符串命名属性添加命名属性映射。 |
| [addNamedPropertyMapping(MapiProperty property, long nameId, UUID guid)](#addNamedPropertyMapping-com.aspose.email.MapiProperty-long-java.util.UUID-) | 为数值命名属性添加命名属性映射。 |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | 创建 mapi 节点。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | 获取代码页。 |
| [getContent()](#getContent--) | 获取内容 |
| [getName()](#getName--) | 获取名称 |
| [getNextAvailablePropertyId(int dataType)](#getNextAvailablePropertyId-int-) | 根据属性数据类型获取条目流中下一个可用的属性 ID。 |
| [getProperties()](#getProperties--) | 获取属性的集合。 |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | 通过属性描述符获取 MAPI 属性。 |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | 获取由标签指定的属性值，类型为 Boolean。 |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | 获取由标签指定的属性的字符串值。 |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | 获取由标签指定的属性值，类型为 DateTime。 |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | 获取由标签指定的属性的 int32 值。 |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | 获取由标签指定的属性值，类型为 Long（int64）。 |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | 获取由标签指定的属性值，类型为 Short。 |
| [getPropertyString(long tag)](#getPropertyString-long-) | 获取由标签指定的属性的字符串值。 |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | 获取由标签指定的属性的字符串值。 |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | 确定字符串属性是否为 Unicode 编码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | 设置属性。 |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | 设置 MAPI 属性。 |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | 尝试使用指定的标签键获取属性数据。 |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | 获取指定属性的值，类型为 DateTime。 |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | 获取指定属性的值，类型为 Int32。 |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | 获取指定属性的值，类型为 Long。 |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | 尝试使用指定的标签获取属性数据为字符串。 |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | 尝试使用指定的标签和代码页获取属性数据为字符串。 |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | 获取指定属性的值，类型为 String。 |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | 获取指定属性的值，类型为 String。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiNamedPropertyMappingStorage() {#MapiNamedPropertyMappingStorage--}
```
public MapiNamedPropertyMappingStorage()
```


初始化一个新的 [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) 类实例。

### addNamedPropertyMapping(MapiProperty property, String nameId, UUID guid) {#addNamedPropertyMapping-com.aspose.email.MapiProperty-java.lang.String-java.util.UUID-}
```
public final void addNamedPropertyMapping(MapiProperty property, String nameId, UUID guid)
```


为字符串命名属性添加命名属性映射。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | 要添加映射的属性。 |
| nameId | java.lang.String | 名称 ID。 |
|  | guid | java.util.UUID | 标识属性集的 GUID。 |

--------------------

属性 应具有有效的命名属性 ID，\#getNextAvailablePropertyId(int).getNextAvailablePropertyId(int) 可用于生成一个。否则将抛出异常。

\{@link ArgumentNullException\} 如果 nameId 为 null。\{@link ArgumentNullException\} 如果 \{@code property\} 为 null。\{@link ArgumentException\} 如果 \{@code MapiProperty.Tag\}(\{@link MapiProperty\#getTag\}) 可用于命名属性映射。命名属性标识符的范围在 0x8000 到 0xFFFE 之间。   |

### addNamedPropertyMapping(MapiProperty property, long nameId, UUID guid) {#addNamedPropertyMapping-com.aspose.email.MapiProperty-long-java.util.UUID-}
```
public final void addNamedPropertyMapping(MapiProperty property, long nameId, UUID guid)
```


为数值命名属性添加命名属性映射。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | 要添加映射的属性。 |
| nameId | long | 名称 ID。 |
|  | guid | java.util.UUID | 标识属性集的 GUID。 |

--------------------

属性 应具有有效的命名属性 ID，\#getNextAvailablePropertyId(int).getNextAvailablePropertyId(int) 可用于生成一个。否则将抛出异常。

\{@link ArgumentNullException\} 如果 \{@code property\} 为 null。\{@link ArgumentException\} 如果 \{@code MapiProperty.Tag\}(\{@link MapiProperty\#getTag\}) 可用于命名属性映射。命名属性标识符的范围在 0x8000 到 0xFFFE 之间。   |

### createMapiNode(String key) {#createMapiNode-java.lang.String-}
```
public IMapiNode createMapiNode(String key)
```


创建 mapi 节点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 节点键。 |

**Returns:**
com.aspose.email.IMapiNode - IMapiNode 接口。
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
### getCodePage() {#getCodePage--}
```
public int getCodePage()
```


获取代码页。

值：代码页。

**Returns:**
int
### getContent() {#getContent--}
```
public final Object getContent()
```


获取内容

Value: 内容

**Returns:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```


获取名称

Value: 名称

**Returns:**
java.lang.String
### getNextAvailablePropertyId(int dataType) {#getNextAvailablePropertyId-int-}
```
public final long getNextAvailablePropertyId(int dataType)
```


根据属性数据类型获取条目流中下一个可用的属性 ID。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataType | int | 属性的数据类型。 |

**Returns:**
long - 一个可以稍后用于添加属性映射的 ID。
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


获取属性的集合。

值：属性。

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


通过属性描述符获取 MAPI 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 已查找属性的属性描述符 |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - Mapi property if it is found, otherwise null.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


获取由标签指定的属性值，类型为 Boolean。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
java.lang.Boolean - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


获取由标签指定的属性的字符串值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
byte[] - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


获取由标签指定的属性值，类型为 DateTime。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | long | MAPI 属性标签。 |

**Returns:**
java.util.Date - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


获取由标签指定的属性的 int32 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
java.lang.Integer - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


获取由标签指定的属性值，类型为 Long（int64）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
java.lang.Long - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


获取由标签指定的属性值，类型为 Short。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
java.lang.Short - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


获取由标签指定的属性的字符串值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
java.lang.String - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


获取由标签指定的属性的字符串值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| 代码页 | int | 用于获取字符串值的指定代码页。 |

**Returns:**
java.lang.String - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


确定字符串属性是否为 Unicode 编码。

**Returns:**
布尔型 - 如果字符串属性为 Unicode 编码，则为 True。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


设置属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | 属性。 |

### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


设置 MAPI 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 属性描述符。 |
| value | java.lang.Object | 属性数据。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetPropertyData(long tag) {#tryGetPropertyData-long-}
```
public final byte[] tryGetPropertyData(long tag)
```


尝试使用指定的标签键获取属性数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 标签键。 |

**Returns:**
byte[] - 属性数据。
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


获取指定属性的值，类型为 DateTime。返回值指示操作是否成功。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| value | java.util.Date[] | 当此方法返回时，如果属性存在，则包含指定属性的值。此参数以未初始化的形式传递。 |

**Returns:**
boolean - 如果 s 转换成功则为 true；否则为 false。
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


获取指定属性的值，类型为 Int32。返回值指示操作是否成功。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| value | int[] | 当此方法返回时，如果属性存在，则包含指定属性的值。此参数以未初始化的形式传递。 |

**Returns:**
boolean - 如果 s 转换成功则为 true；否则为 false。
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


获取指定属性的值，类型为 Long。返回值指示操作是否成功。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| value | long[] | 当此方法返回时，如果属性存在，则包含指定属性的值。此参数以未初始化的形式传递。 |

**Returns:**
boolean - 如果 s 转换成功则为 true；否则为 false。
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


尝试使用指定的标签获取属性数据为字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 属性标签键。 |

**Returns:**
java.lang.String - 包含属性数据内容的字符串。
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


尝试使用指定的标签和代码页获取属性数据为字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 属性标签键。 |
| 代码页 | int | 代码页。 |

**Returns:**
java.lang.String - 包含属性数据内容的字符串。
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


获取指定属性的值，类型为 String。返回值指示操作是否成功。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| value | java.lang.String[] | 当此方法返回时，如果属性存在，则包含指定属性的值。此参数以未初始化的形式传递。 |

**Returns:**
boolean - 如果 s 转换成功则为 true；否则为 false。
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


获取指定属性的值，类型为 String。返回值指示操作是否成功。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| value | java.lang.String[] | 当此方法返回时，如果属性存在，则包含指定属性的值。此参数以未初始化的形式传递。 |
| 代码页 | int | 用于获取字符串值的指定代码页。 |

**Returns:**
boolean - 如果 s 转换成功则为 true；否则为 false。
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

