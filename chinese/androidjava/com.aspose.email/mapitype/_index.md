---
title: MapiType
second_title: Aspose.Email for Android via Java API 参考
description: 包含可以与消息对象一起存储的可能的 MAPI 属性类型。
type: docs
weight: 294
url: /zh/androidjava/com.aspose.email/mapitype/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MapiType extends System.Enum
```

包含可以与消息对象一起存储的可能的 MAPI 属性类型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiType()](#MapiType--) | MapiType 的构造函数。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [None](#None) | 未设置任何值。 |
| [PT_APPTIME](#PT-APPTIME) | 8 字节，64 位浮点数，其中整数部分表示自 1899 年 12 月 30 日起的天数，小数部分表示自午夜起的天数小数部分。 |
| [PT_BINARY](#PT-BINARY) | 可变大小的字节数组 |
| [PT_BOOLEAN](#PT-BOOLEAN) | 1 字节，仅限于 1 或 0 |
| [PT_CLSID](#PT-CLSID) | 16 字节，一个 GUID，Data1、Data2 和 Data3 字段采用小端格式 |
| [PT_CURRENCY](#PT-CURRENCY) | 8 字节，一个 64 位有符号、缩放整数，表示十进制货币值，小数点右侧保留 4 位 |
| [PT_DOUBLE](#PT-DOUBLE) | 8 字节，一个 64 位浮点数 |
| [PT_ERROR](#PT-ERROR) | 4 字节，一个 32 位整数，用于编码错误信息 |
| [PT_FLOAT](#PT-FLOAT) | 4 字节，一个 32 位浮点数 |
| [PT_LONG](#PT-LONG) | 4 字节，一个 32 位整数 |
| [PT_LONGLONG](#PT-LONGLONG) | 8 字节，一个 64 位整数 |
| [PT_MV_APPTIME](#PT-MV-APPTIME) | 可变大小，一组 [PT\_APPTIME](../../com.aspose.email/mapitype\#PT-APPTIME) 值。 |
| [PT_MV_BINARY](#PT-MV-BINARY) | 可变大小，一组 [PT\_BINARY](../../com.aspose.email/mapitype\#PT-BINARY) 值。 |
| [PT_MV_CLSID](#PT-MV-CLSID) | 可变大小，一组 [PT\_CLSID](../../com.aspose.email/mapitype\#PT-CLSID) 值。 |
| [PT_MV_CURRENCY](#PT-MV-CURRENCY) | 可变大小，一组 [PT\_CURRENCY](../../com.aspose.email/mapitype\#PT-CURRENCY) 值。 |
| [PT_MV_DOUBLE](#PT-MV-DOUBLE) | 可变大小，一组 [PT\_DOUBLE](../../com.aspose.email/mapitype\#PT-DOUBLE) 值。 |
| [PT_MV_FLOAT](#PT-MV-FLOAT) | 可变大小，一组 [PT\_FLOAT](../../com.aspose.email/mapitype\#PT-FLOAT) 值。 |
| [PT_MV_LONG](#PT-MV-LONG) | 可变大小，一组 [PT\_LONG](../../com.aspose.email/mapitype\#PT-LONG) 值。 |
| [PT_MV_LONGLONG](#PT-MV-LONGLONG) | 可变大小，一组 [PT\_LONGLONG](../../com.aspose.email/mapitype\#PT-LONGLONG) 值。 |
| [PT_MV_SHORT](#PT-MV-SHORT) | 可变大小，一组 [PT\_SHORT](../../com.aspose.email/mapitype\#PT-SHORT) 值。 |
| [PT_MV_STRING8](#PT-MV-STRING8) | 可变大小，一组 [PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8) 值。 |
| [PT_MV_SYSTIME](#PT-MV-SYSTIME) | 可变大小，一组 [PT\_SYSTIME](../../com.aspose.email/mapitype\#PT-SYSTIME) 值。 |
| [PT_MV_UNICODE](#PT-MV-UNICODE) | 可变大小，一组 [PT\_UNICODE](../../com.aspose.email/mapitype\#PT-UNICODE) 值。 |
| [PT_OBJECT](#PT-OBJECT) | 属性值是 COM 对象 |
| [PT_SHORT](#PT-SHORT) | 2 字节，一个 16 位整数 |
| [PT_STRING8](#PT-STRING8) | 可变大小，一个使用外部指定编码的多字节字符字符串，带有终止空字符（单个 0 字节）。 |
| [PT_SYSTIME](#PT-SYSTIME) | 8 字节，一个 64 位整数，表示自 1601 年 1 月 1 日起的 100 纳秒间隔数 |
| [PT_UNICODE](#PT-UNICODE) | 可变大小，一个使用 UTF-16LE 编码的 Unicode 字符串，带有终止空字符 (0x0000) |
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
### MapiType() {#MapiType--}
```
public MapiType()
```


MapiType 的构造函数。

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### None {#None}
```
public static final int None
```


未设置任何值。

### PT_APPTIME {#PT-APPTIME}
```
public static final int PT_APPTIME
```


8 字节，64 位浮点数，其中整数部分表示自 1899 年 12 月 30 日起的天数，小数部分表示自午夜起的天数小数部分。

### PT_BINARY {#PT-BINARY}
```
public static final int PT_BINARY
```


可变大小的字节数组

### PT_BOOLEAN {#PT-BOOLEAN}
```
public static final int PT_BOOLEAN
```


1 字节，仅限于 1 或 0

### PT_CLSID {#PT-CLSID}
```
public static final int PT_CLSID
```


16 字节，一个 GUID，Data1、Data2 和 Data3 字段采用小端格式

### PT_CURRENCY {#PT-CURRENCY}
```
public static final int PT_CURRENCY
```


8 字节，一个 64 位有符号、缩放整数，表示十进制货币值，小数点右侧保留 4 位

### PT_DOUBLE {#PT-DOUBLE}
```
public static final int PT_DOUBLE
```


8 字节，一个 64 位浮点数

### PT_ERROR {#PT-ERROR}
```
public static final int PT_ERROR
```


4 字节，一个 32 位整数，用于编码错误信息

### PT_FLOAT {#PT-FLOAT}
```
public static final int PT_FLOAT
```


4 字节，一个 32 位浮点数

### PT_LONG {#PT-LONG}
```
public static final int PT_LONG
```


4 字节，一个 32 位整数

### PT_LONGLONG {#PT-LONGLONG}
```
public static final int PT_LONGLONG
```


8 字节，一个 64 位整数

### PT_MV_APPTIME {#PT-MV-APPTIME}
```
public static final int PT_MV_APPTIME
```


可变大小，一组 [PT\_APPTIME](../../com.aspose.email/mapitype\#PT-APPTIME) 值。

### PT_MV_BINARY {#PT-MV-BINARY}
```
public static final int PT_MV_BINARY
```


可变大小，一组 [PT\_BINARY](../../com.aspose.email/mapitype\#PT-BINARY) 值。

### PT_MV_CLSID {#PT-MV-CLSID}
```
public static final int PT_MV_CLSID
```


可变大小，一组 [PT\_CLSID](../../com.aspose.email/mapitype\#PT-CLSID) 值。

### PT_MV_CURRENCY {#PT-MV-CURRENCY}
```
public static final int PT_MV_CURRENCY
```


可变大小，一组 [PT\_CURRENCY](../../com.aspose.email/mapitype\#PT-CURRENCY) 值。

### PT_MV_DOUBLE {#PT-MV-DOUBLE}
```
public static final int PT_MV_DOUBLE
```


可变大小，一组 [PT\_DOUBLE](../../com.aspose.email/mapitype\#PT-DOUBLE) 值。

### PT_MV_FLOAT {#PT-MV-FLOAT}
```
public static final int PT_MV_FLOAT
```


可变大小，一组 [PT\_FLOAT](../../com.aspose.email/mapitype\#PT-FLOAT) 值。

### PT_MV_LONG {#PT-MV-LONG}
```
public static final int PT_MV_LONG
```


可变大小，一组 [PT\_LONG](../../com.aspose.email/mapitype\#PT-LONG) 值。

### PT_MV_LONGLONG {#PT-MV-LONGLONG}
```
public static final int PT_MV_LONGLONG
```


可变大小，一组 [PT\_LONGLONG](../../com.aspose.email/mapitype\#PT-LONGLONG) 值。

### PT_MV_SHORT {#PT-MV-SHORT}
```
public static final int PT_MV_SHORT
```


可变大小，一组 [PT\_SHORT](../../com.aspose.email/mapitype\#PT-SHORT) 值。

### PT_MV_STRING8 {#PT-MV-STRING8}
```
public static final int PT_MV_STRING8
```


可变大小，一组 [PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8) 值。

### PT_MV_SYSTIME {#PT-MV-SYSTIME}
```
public static final int PT_MV_SYSTIME
```


可变大小，一组 [PT\_SYSTIME](../../com.aspose.email/mapitype\#PT-SYSTIME) 值。

### PT_MV_UNICODE {#PT-MV-UNICODE}
```
public static final int PT_MV_UNICODE
```


可变大小，一组 [PT\_UNICODE](../../com.aspose.email/mapitype\#PT-UNICODE) 值。

### PT_OBJECT {#PT-OBJECT}
```
public static final int PT_OBJECT
```


属性值是 COM 对象

### PT_SHORT {#PT-SHORT}
```
public static final int PT_SHORT
```


2 字节，一个 16 位整数

### PT_STRING8 {#PT-STRING8}
```
public static final int PT_STRING8
```


可变大小，一个使用外部指定编码的多字节字符字符串，带有终止空字符（单个 0 字节）。

### PT_SYSTIME {#PT-SYSTIME}
```
public static final int PT_SYSTIME
```


8 字节，一个 64 位整数，表示自 1601 年 1 月 1 日起的 100 纳秒间隔数

### PT_UNICODE {#PT-UNICODE}
```
public static final int PT_UNICODE
```


可变大小，一个使用 UTF-16LE 编码的 Unicode 字符串，带有终止空字符 (0x0000)

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

