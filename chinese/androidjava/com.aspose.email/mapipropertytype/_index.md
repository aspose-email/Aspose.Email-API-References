---
title: MapiPropertyType
second_title: Aspose.Email for Android via Java API 参考
description: 表示 MapiProperty 数据的数据类型。
type: docs
weight: 277
url: /zh/androidjava/com.aspose.email/mapipropertytype/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MapiPropertyType extends System.Enum
```

表示 MapiProperty 数据的数据类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [None](#None) | 未设置任何值。 |
| [PT_ACTIONS](#PT-ACTIONS) | PT\_ACTIONS |
| [PT_BINARY](#PT-BINARY) | SBinary 结构值，计数的字节数组。 |
| [PT_BOOLEAN](#PT-BOOLEAN) | 16 位布尔值，其中零等于 FALSE，非零等于 TRUE。 |
| [PT_CLSID](#PT-CLSID) | CLSID 结构值。 |
| [PT_DOUBLE](#PT-DOUBLE) | 64 位浮点数。 |
| [PT_ERROR](#PT-ERROR) | SCODE 值；32 位无符号整数。 |
| [PT_FLOAT](#PT-FLOAT) | 一个 32 位浮点数。 |
| [PT_LONG](#PT-LONG) | 有符号或无符号 32 位整数。 |
| [PT_LONGLONG](#PT-LONGLONG) | 有符号或无符号 64 位整数。 |
| [PT_MV_APPTIME](#PT-MV-APPTIME) | 一个计数字段，后面跟随相应数量的 PtypFloatingTime 值。 |
| [PT_MV_BINARY](#PT-MV-BINARY) | 一个计数字段，后面跟随相应数量的 PT\_BINARY 值。 |
| [PT_MV_BOOLEAN](#PT-MV-BOOLEAN) | 一个计数字段，后面跟随相应数量的 PT\_BOOLEAN 值。 |
| [PT_MV_CLSID](#PT-MV-CLSID) | 一个计数字段，后面跟随相应数量的 PT\_CLSID 值。 |
| [PT_MV_CURRENCY](#PT-MV-CURRENCY) | 一个计数字段，后面跟随相应数量的 PT\_CURRENCY 值。 |
| [PT_MV_DOUBLE](#PT-MV-DOUBLE) | 一个计数字段，后面跟随相应数量的 PT\_DOUBLE 值。 |
| [PT_MV_FLOAT](#PT-MV-FLOAT) | 一个计数字段，后面跟随相应数量的 PT\_FLOAT 值。 |
| [PT_MV_LONG](#PT-MV-LONG) | 一个计数字段，后面跟随相应数量的 PT\_LONG 值。 |
| [PT_MV_LONGLONG](#PT-MV-LONGLONG) | 一个计数字段，后面跟随相应数量的 PT\_LONGLONG 值。 |
| [PT_MV_SHORT](#PT-MV-SHORT) | 一个计数字段，后面跟随相应数量的 PT\_SHORT 值。 |
| [PT_MV_STRING8](#PT-MV-STRING8) | 一个计数字段，后面跟随相应数量的 PT\_STRING8 值。 |
| [PT_MV_SYSTIME](#PT-MV-SYSTIME) | 一个计数字段，后面跟随相应数量的 PT\_SYSTIME 值。 |
| [PT_MV_UNICODE](#PT-MV-UNICODE) | 一个计数字段，后面跟随相应数量的 PT\_UNICODE 值。 |
| [PT_MV_xxx](#PT-MV-xxx) | PT\_MV\_xxx |
| [PT_NULL](#PT-NULL) | 表示没有属性值。 |
| [PT_OBJECT](#PT-OBJECT) | 指向实现 IUnknown 接口的对象的指针。 |
| [PT_SHORT](#PT-SHORT) | 有符号 16 位整数。 |
| [PT_SRESTRICTION](#PT-SRESTRICTION) | PT\_SRESTRICTION |
| [PT_STRING8](#PT-STRING8) | 以空字符结尾的 8 位字符字符串。 |
| [PT_SVREID](#PT-SVREID) | 可变大小，先是 16 位（2 字节）计数，后跟一个结构体。 |
| [PT_SYSTIME](#PT-SYSTIME) | 以 FILETIME 结构形式的 64 位整数日期时间值。 |
| [PT_UNICODE](#PT-UNICODE) | PT\_UNICODE |
| [PT_UNSPECIFIED](#PT-UNSPECIFIED) | 指示属性类型未知。 |
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
### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### None {#None}
```
public static final int None
```


未设置任何值。

### PT_ACTIONS {#PT-ACTIONS}
```
public static final int PT_ACTIONS
```


PT\_ACTIONS

### PT_BINARY {#PT-BINARY}
```
public static final int PT_BINARY
```


SBinary 结构值，计数的字节数组。

### PT_BOOLEAN {#PT-BOOLEAN}
```
public static final int PT_BOOLEAN
```


16 位布尔值，零等于 FALSE，非零等于 TRUE。此属性类型与 OLE 类型 VT\_BOOL 相同。

### PT_CLSID {#PT-CLSID}
```
public static final int PT_CLSID
```


CLSID 结构体值。此属性类型与 OLE 类型 VT\_CLSID 相同。

### PT_DOUBLE {#PT-DOUBLE}
```
public static final int PT_DOUBLE
```


64 位浮点数。

### PT_ERROR {#PT-ERROR}
```
public static final int PT_ERROR
```


SCODE 值；32 位无符号整数。此属性类型与 OLE 类型 VT\_ERROR 相同。

### PT_FLOAT {#PT-FLOAT}
```
public static final int PT_FLOAT
```


一个 32 位浮点数。

### PT_LONG {#PT-LONG}
```
public static final int PT_LONG
```


有符号或无符号 32 位整数。此属性类型与 PT\_I4 和 OLE 类型 VT\_I4 相同。

### PT_LONGLONG {#PT-LONGLONG}
```
public static final int PT_LONGLONG
```


有符号或无符号 64 位整数。此属性类型与 PT\_I8 和 OLE 类型 VT\_I8 相同。

### PT_MV_APPTIME {#PT-MV-APPTIME}
```
public static final int PT_MV_APPTIME
```


一个计数字段，后面跟随相应数量的 PtypFloatingTime 值。

### PT_MV_BINARY {#PT-MV-BINARY}
```
public static final int PT_MV_BINARY
```


一个计数字段，后面跟随相应数量的 PT\_BINARY 值。

### PT_MV_BOOLEAN {#PT-MV-BOOLEAN}
```
public static final int PT_MV_BOOLEAN
```


一个计数字段，后面跟随相应数量的 PT\_BOOLEAN 值。

### PT_MV_CLSID {#PT-MV-CLSID}
```
public static final int PT_MV_CLSID
```


一个计数字段，后面跟随相应数量的 PT\_CLSID 值。

### PT_MV_CURRENCY {#PT-MV-CURRENCY}
```
public static final int PT_MV_CURRENCY
```


一个计数字段，后面跟随相应数量的 PT\_CURRENCY 值。

### PT_MV_DOUBLE {#PT-MV-DOUBLE}
```
public static final int PT_MV_DOUBLE
```


一个计数字段，后面跟随相应数量的 PT\_DOUBLE 值。

### PT_MV_FLOAT {#PT-MV-FLOAT}
```
public static final int PT_MV_FLOAT
```


一个计数字段，后面跟随相应数量的 PT\_FLOAT 值。

### PT_MV_LONG {#PT-MV-LONG}
```
public static final int PT_MV_LONG
```


一个计数字段，后面跟随相应数量的 PT\_LONG 值。

### PT_MV_LONGLONG {#PT-MV-LONGLONG}
```
public static final int PT_MV_LONGLONG
```


一个计数字段，后面跟随相应数量的 PT\_LONGLONG 值。

### PT_MV_SHORT {#PT-MV-SHORT}
```
public static final int PT_MV_SHORT
```


一个计数字段，后面跟随相应数量的 PT\_SHORT 值。

### PT_MV_STRING8 {#PT-MV-STRING8}
```
public static final int PT_MV_STRING8
```


一个计数字段，后面跟随相应数量的 PT\_STRING8 值。

### PT_MV_SYSTIME {#PT-MV-SYSTIME}
```
public static final int PT_MV_SYSTIME
```


一个计数字段，后面跟随相应数量的 PT\_SYSTIME 值。

### PT_MV_UNICODE {#PT-MV-UNICODE}
```
public static final int PT_MV_UNICODE
```


一个计数字段，后面跟随相应数量的 PT\_UNICODE 值。

### PT_MV_xxx {#PT-MV-xxx}
```
public static final int PT_MV_xxx
```


PT\_MV\_xxx

### PT_NULL {#PT-NULL}
```
public static final int PT_NULL
```


表示没有属性值。

### PT_OBJECT {#PT-OBJECT}
```
public static final int PT_OBJECT
```


指向实现 IUnknown 接口的对象的指针。此属性类型类似于多个 OLE 类型，例如 VT\_UNKNOWN。

### PT_SHORT {#PT-SHORT}
```
public static final int PT_SHORT
```


有符号 16 位整数。此属性类型与 PT\_SHORT 和 OLE 类型 VT\_I2 相同。

### PT_SRESTRICTION {#PT-SRESTRICTION}
```
public static final int PT_SRESTRICTION
```


PT\_SRESTRICTION

### PT_STRING8 {#PT-STRING8}
```
public static final int PT_STRING8
```


以空字符结尾的 8 位字符字符串。此属性类型与 OLE 类型 VT\_LPSTR 相同。

### PT_SVREID {#PT-SVREID}
```
public static final int PT_SVREID
```


可变大小，先是 16 位（2 字节）计数，后跟一个结构体。

### PT_SYSTIME {#PT-SYSTIME}
```
public static final int PT_SYSTIME
```


以 FILETIME 结构形式的 64 位整数日期时间值。此属性类型与 OLE 类型 VT\_FILETIME 相同。

### PT_UNICODE {#PT-UNICODE}
```
public static final int PT_UNICODE
```


PT\_UNICODE

### PT_UNSPECIFIED {#PT-UNSPECIFIED}
```
public static final int PT_UNSPECIFIED
```


指示属性类型未知。

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

