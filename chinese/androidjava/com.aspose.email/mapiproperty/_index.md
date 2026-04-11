---
title: MapiProperty
second_title: Aspose.Email for Android via Java API 参考
description: 表示 MAPI 属性。
type: docs
weight: 271
url: /zh/androidjava/com.aspose.email/mapiproperty/
---

**Inheritance:**
java.lang.Object
```
public class MapiProperty
```

表示 MAPI 属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiProperty(long tag, byte[] data)](#MapiProperty-long-byte---) | 初始化 MapiProperty 类的新实例。 |
| [MapiProperty(long tag)](#MapiProperty-long-) | 初始化 MapiProperty 类的新实例。 |
| [MapiProperty(PidTagPropertyDescriptor pd, Object data)](#MapiProperty-com.aspose.email.PidTagPropertyDescriptor-java.lang.Object-) | 初始化 MapiProperty 类的新实例。 |
| [MapiProperty(PidLidPropertyDescriptor pd, Object data)](#MapiProperty-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-) | 初始化 MapiProperty 类的新实例。 |
| [MapiProperty(long tag, Iterable<?> values)](#MapiProperty-long-java.lang.Iterable----) | 初始化 [MapiProperty](../../com.aspose.email/mapiproperty) 类的新实例。 |
| [MapiProperty(long tag, long signedParam, byte[] data)](#MapiProperty-long-long-byte---) | 初始化 [MapiProperty](../../com.aspose.email/mapiproperty) 类的新实例。 |
| [MapiProperty(String name, long tag, long signedParam, byte[] data)](#MapiProperty-java.lang.String-long-long-byte---) | 初始化 MapiProperty 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMapiPropertyFromBytes(long tag, byte[] data)](#createMapiPropertyFromBytes-long-byte---) | 从字节创建 mapi 属性。 |
| [createMapiPropertyFromDateTime(long tag, Date data)](#createMapiPropertyFromDateTime-long-java.util.Date-) | 从日期时间创建 mapi 属性。 |
| [createMapiPropertyFromLong(long tag, long data)](#createMapiPropertyFromLong-long-long-) | 从 long 创建 mapi 属性。 |
| [createMapiPropertyFromLong(long tag, long data, long delimiter)](#createMapiPropertyFromLong-long-long-long-) | 从 long 创建 mapi 属性。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBoolean()](#getBoolean--) | 获取二进制数据的前几个字节，作为布尔值。 |
| [getClass()](#getClass--) |  |
| [getCurrency()](#getCurrency--) | 使用指定的代码页获取货币的字符串表示。 |
| [getData()](#getData--) | 获取二进制数据。 |
| [getDataType()](#getDataType--) | 获取数据类型。 |
| [getDateTime()](#getDateTime--) | 获取二进制数据的前几个字节，作为日期时间。 |
| [getDescriptor()](#getDescriptor--) | 获取 MAPI 属性的描述符 |
| [getDouble()](#getDouble--) | 获取二进制数据的字节，作为 double。 |
| [getFloat()](#getFloat--) | 获取二进制数据的字节，作为 float。 |
| [getFloatingDate()](#getFloatingDate--) | 获取二进制数据的字节，作为 DateTime。 |
| [getGuidValue()](#getGuidValue--) | 获取二进制数据的字节，作为 Guid。 |
| [getIdentifier()](#getIdentifier--) | 获取标识符。 |
| [getInt32()](#getInt32--) | 获取二进制数据的前 4 个字节，作为 int32。 |
| [getLong()](#getLong--) | 获取二进制数据的前 8 个字节，作为 long。 |
| [getMVEntries()](#getMVEntries--) | 获取 MV 条目的列表。 |
| [getMultipleBinary()](#getMultipleBinary--) | 获取多个二进制数据。 |
| [getMultipleBoolean()](#getMultipleBoolean--) | 获取多个布尔值。 |
| [getMultipleCurrency()](#getMultipleCurrency--) | 获取多个十进制值。 |
| [getMultipleFloating32()](#getMultipleFloating32--) | 获取多个 float 值。 |
| [getMultipleFloating64()](#getMultipleFloating64--) | 获取多个 double 值。 |
| [getMultipleFloatingTime()](#getMultipleFloatingTime--) | 获取多个 DateTime 值。 |
| [getMultipleGuid()](#getMultipleGuid--) | 获取多个 Guid 值。 |
| [getMultipleInteger16()](#getMultipleInteger16--) | 获取多个 Int16 值。 |
| [getMultipleInteger32()](#getMultipleInteger32--) | 获取多个 Int32 值。 |
| [getMultipleInteger64()](#getMultipleInteger64--) | 获取多个 Int64 值。 |
| [getMultipleString()](#getMultipleString--) | 获取多个字符串数据。 |
| [getMultipleTime()](#getMultipleTime--) | 获取多个 DateTime 值。 |
| [getName()](#getName--) | 获取名称。 |
| [getPropertyTagName()](#getPropertyTagName--) | 获取 PropertyName。 |
| [getShort()](#getShort--) | 获取二进制数据的前 2 字节，作为 short。 |
| [getString()](#getString--) | 获取二进制数据为字符串。 |
| [getString(int codepage)](#getString-int-) | 使用指定代码页获取二进制数据为字符串。 |
| [getTag()](#getTag--) | 获取标签。 |
| [getValue()](#getValue--) | 获取值为对象 |
| [hashCode()](#hashCode--) |  |
| [isNamed()](#isNamed--) | 指示该属性是否为已命名属性。 |
| [isSigned()](#isSigned--) | 指示二进制数据是否已签名。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setSigned(boolean value)](#setSigned-boolean-) | 指示二进制数据是否已签名。 |
| [toString()](#toString--) | 返回表示当前 Object 的 String。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiProperty(long tag, byte[] data) {#MapiProperty-long-byte---}
```
public MapiProperty(long tag, byte[] data)
```


初始化 MapiProperty 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 属性的标签键。 |
| 数据 | byte[] | 属性的二进制数据。 |

### MapiProperty(long tag) {#MapiProperty-long-}
```
public MapiProperty(long tag)
```


初始化 MapiProperty 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 属性的标签键。 |

### MapiProperty(PidTagPropertyDescriptor pd, Object data) {#MapiProperty-com.aspose.email.PidTagPropertyDescriptor-java.lang.Object-}
```
public MapiProperty(PidTagPropertyDescriptor pd, Object data)
```


初始化 MapiProperty 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd | [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) | 属性描述符 |
| 数据 | java.lang.Object | 属性的数据。 |

### MapiProperty(PidLidPropertyDescriptor pd, Object data) {#MapiProperty-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-}
```
public MapiProperty(PidLidPropertyDescriptor pd, Object data)
```


初始化 MapiProperty 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd | [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) | 属性描述符 |
| 数据 | java.lang.Object | 属性的数据。 |

### MapiProperty(long tag, Iterable<?> values) {#MapiProperty-long-java.lang.Iterable----}
```
public MapiProperty(long tag, Iterable<?> values)
```


初始化 [MapiProperty](../../com.aspose.email/mapiproperty) 类的新实例。此重载用于创建多值属性，PT\_MV\_\*。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 属性标签。 |
| 值 | java.lang.Iterable<?> | 这些值。 |

### MapiProperty(long tag, long signedParam, byte[] data) {#MapiProperty-long-long-byte---}
```
public MapiProperty(long tag, long signedParam, byte[] data)
```


初始化 [MapiProperty](../../com.aspose.email/mapiproperty) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 属性标签。 |
| signedParam | long | 已签名。 |
| 数据 | byte[] | 属性数据。 |

### MapiProperty(String name, long tag, long signedParam, byte[] data) {#MapiProperty-java.lang.String-long-long-byte---}
```
public MapiProperty(String name, long tag, long signedParam, byte[] data)
```


初始化 MapiProperty 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 名称。 |
| tag | long | 属性的标签键。 |
| signedParam | long | 指示数据是否已签名。 |
| 数据 | byte[] | 属性的二进制数据。 |

### createMapiPropertyFromBytes(long tag, byte[] data) {#createMapiPropertyFromBytes-long-byte---}
```
public static MapiProperty createMapiPropertyFromBytes(long tag, byte[] data)
```


从字节创建 mapi 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 标签。 |
| 数据 | byte[] | 数据。 |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
### createMapiPropertyFromDateTime(long tag, Date data) {#createMapiPropertyFromDateTime-long-java.util.Date-}
```
public static MapiProperty createMapiPropertyFromDateTime(long tag, Date data)
```


从日期时间创建 mapi 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 标签。 |
| 数据 | java.util.Date | 数据。 |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
### createMapiPropertyFromLong(long tag, long data) {#createMapiPropertyFromLong-long-long-}
```
public static MapiProperty createMapiPropertyFromLong(long tag, long data)
```


从 long 创建 mapi 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 标签。 |
| 数据 | long | 数据。 |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
### createMapiPropertyFromLong(long tag, long data, long delimiter) {#createMapiPropertyFromLong-long-long-long-}
```
public static MapiProperty createMapiPropertyFromLong(long tag, long data, long delimiter)
```


从 long 创建 mapi 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 标签。 |
| 数据 | long | 数据。 |
| 分隔符 | long | 分隔符。 |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
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
### getBoolean() {#getBoolean--}
```
public boolean getBoolean()
```


获取二进制数据的前几个字节，作为布尔值。

**Returns:**
boolean - 布尔值。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrency() {#getCurrency--}
```
public BigDecimal getCurrency()
```


使用指定的代码页获取货币的字符串表示。

**Returns:**
java.math.BigDecimal - 字符串包含二进制数据。
### getData() {#getData--}
```
public byte[] getData()
```


获取二进制数据。

**Returns:**
byte[]
### getDataType() {#getDataType--}
```
public int getDataType()
```


获取数据类型。

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public Date getDateTime()
```


获取二进制数据的前几个字节，作为日期时间。

**Returns:**
java.util.Date - 日期时间值。
### getDescriptor() {#getDescriptor--}
```
public final PropertyDescriptor getDescriptor()
```


获取 MAPI 属性的描述符

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor)
### getDouble() {#getDouble--}
```
public double getDouble()
```


获取二进制数据的字节，作为 double。

**Returns:**
double - 双精度值。
### getFloat() {#getFloat--}
```
public float getFloat()
```


获取二进制数据的字节，作为 float。

**Returns:**
float - 双精度值。
### getFloatingDate() {#getFloatingDate--}
```
public Date getFloatingDate()
```


获取二进制数据的字节，作为 DateTime。

**Returns:**
java.util.Date - DateTime 值。
### getGuidValue() {#getGuidValue--}
```
public UUID getGuidValue()
```


获取二进制数据的字节，作为 Guid。

**Returns:**
java.util.UUID - Guid 值。
### getIdentifier() {#getIdentifier--}
```
public long getIdentifier()
```


获取标识符。

**Returns:**
long
### getInt32() {#getInt32--}
```
public int getInt32()
```


获取二进制数据的前 4 个字节，作为 int32。

**Returns:**
int - int32 值。
### getLong() {#getLong--}
```
public long getLong()
```


获取二进制数据的前 8 个字节，作为 long。

**Returns:**
long - long 值。
### getMVEntries() {#getMVEntries--}
```
public final System.Collections.IList getMVEntries()
```


获取 MV 条目的列表。

**Returns:**
com.aspose.ms.System.Collections.IList
### getMultipleBinary() {#getMultipleBinary--}
```
public final byte[][] getMultipleBinary()
```


获取多个二进制数据。

**Returns:**
byte[][] - 多个字节数组。
### getMultipleBoolean() {#getMultipleBoolean--}
```
public final boolean[] getMultipleBoolean()
```


获取多个布尔值。

**Returns:**
boolean[] - 布尔数组。
### getMultipleCurrency() {#getMultipleCurrency--}
```
public final BigDecimal[] getMultipleCurrency()
```


获取多个十进制值。

**Returns:**
java.math.BigDecimal[] - 十进制数组。
### getMultipleFloating32() {#getMultipleFloating32--}
```
public final float[] getMultipleFloating32()
```


获取多个 float 值。

**Returns:**
float[] - 浮点数组。
### getMultipleFloating64() {#getMultipleFloating64--}
```
public final double[] getMultipleFloating64()
```


获取多个 double 值。

**Returns:**
double[] - 双精度数组。
### getMultipleFloatingTime() {#getMultipleFloatingTime--}
```
public final Date[] getMultipleFloatingTime()
```


获取多个 DateTime 值。

**Returns:**
java.util.Date[] - DateTime 数组。
### getMultipleGuid() {#getMultipleGuid--}
```
public final UUID[] getMultipleGuid()
```


获取多个 Guid 值。

**Returns:**
java.util.UUID[] - Guid 数组。
### getMultipleInteger16() {#getMultipleInteger16--}
```
public final short[] getMultipleInteger16()
```


获取多个 Int16 值。

**Returns:**
short[] - Int16 数组。
### getMultipleInteger32() {#getMultipleInteger32--}
```
public final int[] getMultipleInteger32()
```


获取多个 Int32 值。

**Returns:**
int[] - Int32 数组。
### getMultipleInteger64() {#getMultipleInteger64--}
```
public final long[] getMultipleInteger64()
```


获取多个 Int64 值。

**Returns:**
long[] - Int64 数组。
### getMultipleString() {#getMultipleString--}
```
public final String[] getMultipleString()
```


获取多个字符串数据。

**Returns:**
java.lang.String[] - 字符串数组。
### getMultipleTime() {#getMultipleTime--}
```
public final Date[] getMultipleTime()
```


获取多个 DateTime 值。

**Returns:**
java.util.Date[] - DateTime 数组。
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String
### getPropertyTagName() {#getPropertyTagName--}
```
public String getPropertyTagName()
```


获取 PropertyName。

**Returns:**
java.lang.String
### getShort() {#getShort--}
```
public short getShort()
```


获取二进制数据的前 2 字节，作为 short。

**Returns:**
short - short 值。
### getString() {#getString--}
```
public String getString()
```


获取二进制数据为字符串。

**Returns:**
java.lang.String - 字符串包含二进制数据。
### getString(int codepage) {#getString-int-}
```
public String getString(int codepage)
```


使用指定代码页获取二进制数据为字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 代码页 | int | 代码页。 |

**Returns:**
java.lang.String - 字符串包含二进制数据。
### getTag() {#getTag--}
```
public long getTag()
```


获取标签。

**Returns:**
long
### getValue() {#getValue--}
```
public final Object getValue()
```


获取值为对象

**Returns:**
java.lang.Object - 属性的值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNamed() {#isNamed--}
```
public final boolean isNamed()
```


指示该属性是否为已命名属性。

**Returns:**
boolean
### isSigned() {#isSigned--}
```
public boolean isSigned()
```


指示二进制数据是否已签名。

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




### setSigned(boolean value) {#setSigned-boolean-}
```
public void setSigned(boolean value)
```


指示二进制数据是否已签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```


返回表示当前 Object 的 String。

**Returns:**
java.lang.String - 表示当前 Object 的 String。
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

