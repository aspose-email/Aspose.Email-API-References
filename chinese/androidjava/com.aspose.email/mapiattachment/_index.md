---
title: MapiAttachment
second_title: Aspose.Email for Android via Java API 参考
description: 表示电子邮件中的附件。
type: docs
weight: 203
url: /zh/androidjava/com.aspose.email/mapiattachment/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer)
```
public class MapiAttachment extends MapiPropertyContainer
```

表示电子邮件中的附件。
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | 创建 mapi 节点。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBinaryData()](#getBinaryData--) | 获取或设置二进制附件数据。 |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | 获取代码页。 |
| [getContent()](#getContent--) | 获取内容。 |
| [getDisplayName()](#getDisplayName--) | 获取附件中 OLE 对象的显示名称。 |
| [getExtension()](#getExtension--) | 获取指示附件文档类型的文件名扩展名。 |
| [getFileName()](#getFileName--) | 获取附件的基本文件名和扩展名（不包括路径）。 |
| [getItemId()](#getItemId--) | 项目 ID，供服务器使用。 |
| [getLongFileName()](#getLongFileName--) | 获取附件的完整文件名和扩展名（不包括路径）。 |
| [getMimeTag()](#getMimeTag--) | 获取关于多用途互联网邮件扩展（MIME）附件的格式信息。 |
| [getNamedProperties()](#getNamedProperties--) | 获取消息的命名属性。 |
| [getObjectData()](#getObjectData--) | 获取通常通过 OLE IStorage 接口访问的附件对象。 |
| [getProperties()](#getProperties--) | 获取属性的集合。 |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | 通过属性描述符获取 MAPI 属性。 |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | 获取由标签指定的属性值，类型为 Boolean。 |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | 获取由标签指定的属性的字符串值。 |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | 获取由标签指定的属性值，类型为 DateTime。 |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | 获取由标签指定的属性的 int32 值。 |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | 获取由标签指定的属性值，类型为 Long（int64）。 |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | 获取由标签指定的属性值，类型为 Short。 |
| [getPropertyStream()](#getPropertyStream--) | 获取属性流。 |
| [getPropertyString(long tag)](#getPropertyString-long-) | 获取由标签指定的属性的字符串值。 |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | 获取由标签指定的属性的字符串值。 |
| [getSubStorages()](#getSubStorages--) | 获取子存储。 |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | 确定字符串属性是否为 Unicode 编码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(long tag)](#removeProperty-long-) | 正确地从所有集合中移除属性。 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 保存附件内容。 |
| [save(String filename)](#save-java.lang.String-) | 保存附件内容。 |
| [setBinaryData(byte[] value)](#setBinaryData-byte---) | 获取或设置二进制附件数据。 |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | 获取附件中 OLE 对象的显示名称。 |
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
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


获取或设置二进制附件数据。

值：二进制数据。

**Returns:**
byte[]
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


获取内容。

值：内容。

**Returns:**
java.lang.Object
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


获取附件中 OLE 对象的显示名称。

值：显示名称。

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


获取指示附件文档类型的文件名扩展名。

值：扩展名。

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


获取附件的基本文件名和扩展名（不包括路径）。

值：文件名。

**Returns:**
java.lang.String
### getItemId() {#getItemId--}
```
public String getItemId()
```


项目 ID，供服务器使用。

**Returns:**
java.lang.String
### getLongFileName() {#getLongFileName--}
```
public final String getLongFileName()
```


获取附件的完整文件名和扩展名（不包括路径）。

值：完整文件名。

**Returns:**
java.lang.String
### getMimeTag() {#getMimeTag--}
```
public final String getMimeTag()
```


获取关于多用途互联网邮件扩展（MIME）附件的格式信息。

值：MIME 标记。

**Returns:**
java.lang.String
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


获取消息的命名属性。

值：已命名属性的集合。

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getObjectData() {#getObjectData--}
```
public final MapiObjectProperty getObjectData()
```


获取通常通过 OLE IStorage 接口访问的附件对象。

值：对象数据。

**Returns:**
[MapiObjectProperty](../../com.aspose.email/mapiobjectproperty)
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
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


获取属性流。

值：属性流。

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream)
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
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


获取子存储。

值：子存储。

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
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




### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


正确地从所有集合中移除属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MapiProperty 的标签。 |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


保存附件内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 要保存的流。 |

### save(String filename) {#save-java.lang.String-}
```
public final void save(String filename)
```


保存附件内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 要保存的文件名。 |

### setBinaryData(byte[] value) {#setBinaryData-byte---}
```
public final void setBinaryData(byte[] value)
```


获取或设置二进制附件数据。

值：二进制数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


获取附件中 OLE 对象的显示名称。

值：显示名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

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

