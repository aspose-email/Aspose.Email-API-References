---
title: PropertyDataType
second_title: Aspose.Email for Android via Java API 参考
description: MS-OXCDATA 数据结构
type: docs
weight: 358
url: /zh/androidjava/com.aspose.email/propertydatatype/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PropertyDataType extends System.Enum
```

[MS-OXCDATA]: Data Structures
## 字段

| 字段 | 描述 |
| --- | --- |
| [Binary](#Binary) | 可变大小；一个 COUNT 字段后跟相应数量的字节。 |
| [Boolean](#Boolean) | 1 字节；限制为 1 或 0 规范名称: PtypBoolean; 替代名称: PT\_BOOLEAN. |
| [Currency](#Currency) | 8 字节；一个 64 位有符号、缩放的整数表示十进制货币值，小数点右侧保留四位 规范名称: PtypCurrency; 替代名称: PT\_CURRENCY, fixed.14.4; |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ErrorCode](#ErrorCode) | 4 字节；一个 32 位整数用于编码错误信息 规范名称: PtypErrorCode; 替代名称: PT\_ERROR; |
| [Floating32](#Floating32) | 4 字节；一个 32 位浮点数 规范名称: PtypFloating32; 替代名称: PT\_FLOAT, PT\_R4, float, r4; |
| [Floating64](#Floating64) | 8 字节；一个 64 位浮点数 规范名称: PtypFloating64; 替代名称: PT\_DOUBLE, PT\_R8, r8; |
| [FloatingTime](#FloatingTime) | 8 字节；一个 64 位浮点数，其中整数部分表示自 1899 年 12 月 30 日起的天数，小数部分表示自午夜起的一天的分数 规范名称: PtypFloatingTime; 替代名称: PT\_APPTIME; 日期信息通过整数递增表示，起始于 1899 年 12 月 30 日午夜，作为时间零点。 |
| [Guid](#Guid) | 16 字节；一个 GUID，Data1、Data2 和 Data3 字段采用小端格式 规范名称: PtypGuid; 替代名称: PT\_CLSID, UUID; |
| [Integer16](#Integer16) | 2 字节；一个 16 位整数 规范名称: PtypInteger16; 替代名称: PT\_SHORT, PT\_I2, i2, ui2; |
| [Integer32](#Integer32) | 4 字节；一个 32 位整数 规范名称: PtypInteger32; 替代名称: PT\_LONG, PT\_I4, int, ui4; |
| [Integer64](#Integer64) | 8 字节；一个 64 位整数 规范名称：PtypInteger64；别名：PT\\_LONGLONG, PT\\_I8, i8, ui8； |
| [MultipleBinary](#MultipleBinary) | 可变大小；一个 COUNT 字段后跟该数量的 PtypBinary 值。 |
| [MultipleBoolean](#MultipleBoolean) | 可变大小；一个 COUNT 字段后跟该数量的 PtypBoolean 值。 |
| [MultipleCurrency](#MultipleCurrency) | 可变大小；一个 COUNT 字段后跟该数量的 PtypCurrency 值。 |
| [MultipleFloating32](#MultipleFloating32) | 可变大小；一个 COUNT 字段后跟该数量的 PtypFloating32 值。 |
| [MultipleFloating64](#MultipleFloating64) | 可变大小；一个 COUNT 字段后跟该数量的 PtypFloating64 值。 |
| [MultipleFloatingTime](#MultipleFloatingTime) | 可变大小；一个 COUNT 字段后跟该数量的 PtypFloatingTime 值。 |
| [MultipleGuid](#MultipleGuid) | 可变大小；一个 COUNT 字段后跟该数量的 PtypGuid 值。 |
| [MultipleInteger16](#MultipleInteger16) | 可变大小；一个 COUNT 字段后跟该数量的 PtypInteger16 值。 |
| [MultipleInteger32](#MultipleInteger32) | 可变大小；一个 COUNT 字段后跟该数量的 PtypInteger32 值。 |
| [MultipleInteger64](#MultipleInteger64) | 可变大小；一个 COUNT 字段后跟该数量的 PtypInteger64 值。 |
| [MultipleString](#MultipleString) | 可变大小；一个 COUNT 字段后跟该数量的 PtypString 值。 |
| [MultipleString8](#MultipleString8) | 可变大小；一个 COUNT 字段后跟该数量的 PtypString8 值。 |
| [MultipleTime](#MultipleTime) | 可变大小；一个 COUNT 字段后跟该数量的 PtypTime 值。 |
| [Null](#Null) | 无：此属性是占位符。 |
| [Object](#Object) | 属性值是组件对象模型 (COM) 对象。 |
| [Restriction](#Restriction) | 可变大小；一个字节数组，表示一个或多个 Restriction 结构体 规范名称：PtypRestriction；别名：PT\\_SRESTRICT； |
| [RuleAction](#RuleAction) | 可变大小；一个 16 位 COUNT 字段后跟该数量的 rule action 结构体 规范名称：PtypRuleAction；别名：PT\\_ACTIONS； |
| [ServerId](#ServerId) | 可变大小；一个 16 位 COUNT 字段后跟一个结构体 规范名称：PtypServerId；别名：PT\\_SVREID； |
| [String](#String) | 可变大小；一个 Unicode 字符串，采用 UTF-16LE 编码，带有终止空字符 (0x0000)。 |
| [String8](#String8) | 可变大小；一个多字节字符字符串，使用外部指定的编码，带有终止空字符（单个 0 字节）。 |
| [Time](#Time) | 8 字节；一个 64 位整数，表示自 1601 年 1 月 1 日起的 100 纳秒间隔数 规范名称：PtypTime；别名：PT\\_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz； |
| [Unspecified](#Unspecified) | 任意：此属性类型值匹配任何类型；服务器必须在响应中返回实际类型。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Binary {#Binary}
```
public static final int Binary
```


可变大小；一个 COUNT 字段后跟该数量的字节。规范名称：PtypBinary；别名：PT\\_BINARY；

### Boolean {#Boolean}
```
public static final int Boolean
```


1 字节；限制为 1 或 0 规范名称：PtypBoolean；别名：PT\\_BOOLEAN。bool；

### Currency {#Currency}
```
public static final int Currency
```


8 字节；一个 64 位有符号、缩放的整数表示十进制货币值，小数点右侧保留四位 规范名称: PtypCurrency; 替代名称: PT\_CURRENCY, fixed.14.4;

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ErrorCode {#ErrorCode}
```
public static final int ErrorCode
```


4 字节；一个 32 位整数用于编码错误信息 规范名称: PtypErrorCode; 替代名称: PT\_ERROR;

### Floating32 {#Floating32}
```
public static final int Floating32
```


4 字节；一个 32 位浮点数 规范名称: PtypFloating32; 替代名称: PT\_FLOAT, PT\_R4, float, r4;

### Floating64 {#Floating64}
```
public static final int Floating64
```


8 字节；一个 64 位浮点数 规范名称: PtypFloating64; 替代名称: PT\_DOUBLE, PT\_R8, r8;

### FloatingTime {#FloatingTime}
```
public static final int FloatingTime
```


8 字节；一种 64 位浮点数，其中整数部分表示自 1899 年 12 月 30 日起的天数，小数部分表示自午夜起的一天的分数。规范名称：PtypFloatingTime；别名：PT\_APPTIME；日期信息通过整数递增表示，起始于 1899 年 12 月 30 日午夜作为时间零点。时间信息通过自前一午夜起的一天的分数表示。例如，1900 年 1 月 4 日上午 6:00 将表示为值 5.25（即自 1899 年 12 月 30 日起 5 又 1/4 天）。

### Guid {#Guid}
```
public static final int Guid
```


16 字节；一个 GUID，Data1、Data2 和 Data3 字段采用小端格式 规范名称: PtypGuid; 替代名称: PT\_CLSID, UUID;

### Integer16 {#Integer16}
```
public static final int Integer16
```


2 字节；一个 16 位整数 规范名称: PtypInteger16; 替代名称: PT\_SHORT, PT\_I2, i2, ui2;

### Integer32 {#Integer32}
```
public static final int Integer32
```


4 字节；一个 32 位整数 规范名称: PtypInteger32; 替代名称: PT\_LONG, PT\_I4, int, ui4;

### Integer64 {#Integer64}
```
public static final int Integer64
```


8 字节；一个 64 位整数 规范名称：PtypInteger64；别名：PT\\_LONGLONG, PT\\_I8, i8, ui8；

### MultipleBinary {#MultipleBinary}
```
public static final int MultipleBinary
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypBinary 值。规范名称：PtypMultipleBinary；别名：PT\_MV\_BINARY, mv.bin.hex；

### MultipleBoolean {#MultipleBoolean}
```
public static final int MultipleBoolean
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypBoolean 值。规范名称：PtypMultipleBoolean；别名：PT\_MV\_BOOLEAN；

### MultipleCurrency {#MultipleCurrency}
```
public static final int MultipleCurrency
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypCurrency 值。规范名称：PtypMultipleCurrency；别名：PT\_MV\_CURRENCY, mv.fixed.14.4；

### MultipleFloating32 {#MultipleFloating32}
```
public static final int MultipleFloating32
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypFloating32 值。规范名称：PtypMultipleFloating32；别名：PT\_MV\_FLOAT, PT\_MV\_R4, mv.float；

### MultipleFloating64 {#MultipleFloating64}
```
public static final int MultipleFloating64
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypFloating64 值。规范名称：PtypMultipleFloating64；别名：PT\_MV\_DOUBLE, PT\_MV\_R8；

### MultipleFloatingTime {#MultipleFloatingTime}
```
public static final int MultipleFloatingTime
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypFloatingTime 值。规范名称：PtypMultipleFloatingTime；别名：PT\_MV\_APPTIME；

### MultipleGuid {#MultipleGuid}
```
public static final int MultipleGuid
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypGuid 值。规范名称：PtypMultipleGuid；别名：PT\_MV\_CLSID, mv.uuid；

### MultipleInteger16 {#MultipleInteger16}
```
public static final int MultipleInteger16
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypInteger16 值。规范名称：PtypMultipleInteger16；别名：PT\_MV\_SHORT, PT\_MV\_I2, mv.i2；

### MultipleInteger32 {#MultipleInteger32}
```
public static final int MultipleInteger32
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypInteger32 值。规范名称：PtypMultipleInteger32；别名：PT\_MV\_LONG, PT\_MV\_I4, mv.i4；

### MultipleInteger64 {#MultipleInteger64}
```
public static final int MultipleInteger64
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypInteger64 值。规范名称：PtypMultipleInteger64；别名：PT\_MV\_I8, PT\_MV\_LONGLONG；

### MultipleString {#MultipleString}
```
public static final int MultipleString
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypString 值。规范名称：PtypMultipleString；别名：PT\_MV\_UNICODE；

### MultipleString8 {#MultipleString8}
```
public static final int MultipleString8
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypString8 值。规范名称：PtypMultipleString8；别名：PT\_MV\_STRING8, mv.string；

### MultipleTime {#MultipleTime}
```
public static final int MultipleTime
```


可变大小；一个 COUNT 字段后跟相应数量的 PtypTime 值。规范名称：PtypMultipleTime；别名：PT\_MV\_SYSTIME；

### Null {#Null}
```
public static final int Null
```


无：此属性是占位符。规范名称：PtypNull；别名：PT\_NULL；

### Object {#Object}
```
public static final int Object
```


属性值是组件对象模型 (COM) 对象。规范名称：PtypObject 或 PtypEmbeddedTable；别名：PT\_OBJECT；

### Restriction {#Restriction}
```
public static final int Restriction
```


可变大小；一个字节数组，表示一个或多个 Restriction 结构体 规范名称：PtypRestriction；别名：PT\\_SRESTRICT；

### RuleAction {#RuleAction}
```
public static final int RuleAction
```


可变大小；一个 16 位 COUNT 字段后跟该数量的 rule action 结构体 规范名称：PtypRuleAction；别名：PT\\_ACTIONS；

### ServerId {#ServerId}
```
public static final int ServerId
```


可变大小；一个 16 位 COUNT 字段后跟一个结构体 规范名称：PtypServerId；别名：PT\\_SVREID；

### String {#String}
```
public static final int String
```


可变大小；一个以 UTF-16LE 格式编码的 Unicode 字符串，带有终止空字符 (0x0000)。规范名称：PtypString；别名：PT\_UNICODE, string；

### String8 {#String8}
```
public static final int String8
```


可变大小；一个使用外部指定编码的多字节字符字符串，带有终止空字符（单个 0 字节）。规范名称：PtypString8；别名：PT\_STRING8；

### Time {#Time}
```
public static final int Time
```


8 字节；一个 64 位整数，表示自 1601 年 1 月 1 日起的 100 纳秒间隔数 规范名称：PtypTime；别名：PT\\_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz；

### Unspecified {#Unspecified}
```
public static final int Unspecified
```


任意：此属性类型值匹配任何类型；服务器必须在响应中返回实际类型。服务器不得在除 NspiGetIDsFromNames 或 RopGetPropertyIdsFromNames ROP 请求（[MS-OXCROPS] 第 2.2.8.1 节）之外的客户端请求中返回此类型。规范名称：PtypUnspecified；别名：PT\_UNSPECIFIED；

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

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
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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

