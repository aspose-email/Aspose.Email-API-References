---
title: MapiType
second_title: Aspose.Email for Java API Reference
description: Contains possible MAPI property types which can be stored with message object.
type: docs
weight: 480
url: /java/com.aspose.email/mapitype/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MapiType extends System.Enum
```

Contains possible MAPI property types which can be stored with message object.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiType()](#MapiType--) | Constructor for MapiType. |
## Fields

| Field | Description |
| --- | --- |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [None](#None) | No values are set. |
| [PT_APPTIME](#PT-APPTIME) | 8 bytes, a 64-bit floating point number in which the whole number part represents the number of days since December 30, 1899, and the fractional part represents the fraction of a day since midnight |
| [PT_BINARY](#PT-BINARY) | Variable size, a byte array |
| [PT_BOOLEAN](#PT-BOOLEAN) | 1 byte, restricted to 1 or 0 |
| [PT_CLSID](#PT-CLSID) | 16 bytes, a GUID with Data1, Data2, and Data3 fields in little-endian format |
| [PT_CURRENCY](#PT-CURRENCY) | 8 bytes, a 64-bit signed, scaled integer representation of a decimal currency value, with 4 places to the right of the decimal point |
| [PT_DOUBLE](#PT-DOUBLE) | 8 bytes, a 64-bit floating point number |
| [PT_ERROR](#PT-ERROR) | 4 bytes, a 32-bit integer encoding error information |
| [PT_FLOAT](#PT-FLOAT) | 4 bytes, a 32-bit floating point number |
| [PT_LONG](#PT-LONG) | 4 bytes, a 32-bit integer |
| [PT_LONGLONG](#PT-LONGLONG) | 8 bytes, a 64-bit integer |
| [PT_MV_APPTIME](#PT-MV-APPTIME) | Variable size, a set of [PT\_APPTIME](../../com.aspose.email/mapitype\#PT-APPTIME) values. |
| [PT_MV_BINARY](#PT-MV-BINARY) | Variable size, a set of [PT\_BINARY](../../com.aspose.email/mapitype\#PT-BINARY) values. |
| [PT_MV_CLSID](#PT-MV-CLSID) | Variable size, a set of [PT\_CLSID](../../com.aspose.email/mapitype\#PT-CLSID) values. |
| [PT_MV_CURRENCY](#PT-MV-CURRENCY) | Variable size, a set of [PT\_CURRENCY](../../com.aspose.email/mapitype\#PT-CURRENCY) values. |
| [PT_MV_DOUBLE](#PT-MV-DOUBLE) | Variable size, a set of [PT\_DOUBLE](../../com.aspose.email/mapitype\#PT-DOUBLE) values. |
| [PT_MV_FLOAT](#PT-MV-FLOAT) | Variable size, a set of [PT\_FLOAT](../../com.aspose.email/mapitype\#PT-FLOAT) values. |
| [PT_MV_LONG](#PT-MV-LONG) | Variable size, a set of [PT\_LONG](../../com.aspose.email/mapitype\#PT-LONG) values. |
| [PT_MV_LONGLONG](#PT-MV-LONGLONG) | Variable size, a set of [PT\_LONGLONG](../../com.aspose.email/mapitype\#PT-LONGLONG) values. |
| [PT_MV_SHORT](#PT-MV-SHORT) | Variable size, a set of [PT\_SHORT](../../com.aspose.email/mapitype\#PT-SHORT) values. |
| [PT_MV_STRING8](#PT-MV-STRING8) | Variable size, a set of [PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8) values. |
| [PT_MV_SYSTIME](#PT-MV-SYSTIME) | Variable size, a set of [PT\_SYSTIME](../../com.aspose.email/mapitype\#PT-SYSTIME) values. |
| [PT_MV_UNICODE](#PT-MV-UNICODE) | Variable size, a set of [PT\_UNICODE](../../com.aspose.email/mapitype\#PT-UNICODE) values. |
| [PT_OBJECT](#PT-OBJECT) | The property value is a COM object |
| [PT_SHORT](#PT-SHORT) | 2 bytes, a 16-bit integer |
| [PT_STRING8](#PT-STRING8) | Variable size, a string of multi-byte characters in externally specified encoding with terminating null character (single 0 byte). |
| [PT_SYSTIME](#PT-SYSTIME) | 8 bytes, a 64-bit integer representing the number of 100-nanosecond intervals since January 1, 1601 |
| [PT_UNICODE](#PT-UNICODE) | Variable size, a string of Unicode characters in UTF-16LE encoding with terminating null character(0x0000) |
## Methods

| Method | Description |
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


Constructor for MapiType.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### None {#None}
```
public static final int None
```


No values are set.

### PT_APPTIME {#PT-APPTIME}
```
public static final int PT_APPTIME
```


8 bytes, a 64-bit floating point number in which the whole number part represents the number of days since December 30, 1899, and the fractional part represents the fraction of a day since midnight

### PT_BINARY {#PT-BINARY}
```
public static final int PT_BINARY
```


Variable size, a byte array

### PT_BOOLEAN {#PT-BOOLEAN}
```
public static final int PT_BOOLEAN
```


1 byte, restricted to 1 or 0

### PT_CLSID {#PT-CLSID}
```
public static final int PT_CLSID
```


16 bytes, a GUID with Data1, Data2, and Data3 fields in little-endian format

### PT_CURRENCY {#PT-CURRENCY}
```
public static final int PT_CURRENCY
```


8 bytes, a 64-bit signed, scaled integer representation of a decimal currency value, with 4 places to the right of the decimal point

### PT_DOUBLE {#PT-DOUBLE}
```
public static final int PT_DOUBLE
```


8 bytes, a 64-bit floating point number

### PT_ERROR {#PT-ERROR}
```
public static final int PT_ERROR
```


4 bytes, a 32-bit integer encoding error information

### PT_FLOAT {#PT-FLOAT}
```
public static final int PT_FLOAT
```


4 bytes, a 32-bit floating point number

### PT_LONG {#PT-LONG}
```
public static final int PT_LONG
```


4 bytes, a 32-bit integer

### PT_LONGLONG {#PT-LONGLONG}
```
public static final int PT_LONGLONG
```


8 bytes, a 64-bit integer

### PT_MV_APPTIME {#PT-MV-APPTIME}
```
public static final int PT_MV_APPTIME
```


Variable size, a set of [PT\_APPTIME](../../com.aspose.email/mapitype\#PT-APPTIME) values.

### PT_MV_BINARY {#PT-MV-BINARY}
```
public static final int PT_MV_BINARY
```


Variable size, a set of [PT\_BINARY](../../com.aspose.email/mapitype\#PT-BINARY) values.

### PT_MV_CLSID {#PT-MV-CLSID}
```
public static final int PT_MV_CLSID
```


Variable size, a set of [PT\_CLSID](../../com.aspose.email/mapitype\#PT-CLSID) values.

### PT_MV_CURRENCY {#PT-MV-CURRENCY}
```
public static final int PT_MV_CURRENCY
```


Variable size, a set of [PT\_CURRENCY](../../com.aspose.email/mapitype\#PT-CURRENCY) values.

### PT_MV_DOUBLE {#PT-MV-DOUBLE}
```
public static final int PT_MV_DOUBLE
```


Variable size, a set of [PT\_DOUBLE](../../com.aspose.email/mapitype\#PT-DOUBLE) values.

### PT_MV_FLOAT {#PT-MV-FLOAT}
```
public static final int PT_MV_FLOAT
```


Variable size, a set of [PT\_FLOAT](../../com.aspose.email/mapitype\#PT-FLOAT) values.

### PT_MV_LONG {#PT-MV-LONG}
```
public static final int PT_MV_LONG
```


Variable size, a set of [PT\_LONG](../../com.aspose.email/mapitype\#PT-LONG) values.

### PT_MV_LONGLONG {#PT-MV-LONGLONG}
```
public static final int PT_MV_LONGLONG
```


Variable size, a set of [PT\_LONGLONG](../../com.aspose.email/mapitype\#PT-LONGLONG) values.

### PT_MV_SHORT {#PT-MV-SHORT}
```
public static final int PT_MV_SHORT
```


Variable size, a set of [PT\_SHORT](../../com.aspose.email/mapitype\#PT-SHORT) values.

### PT_MV_STRING8 {#PT-MV-STRING8}
```
public static final int PT_MV_STRING8
```


Variable size, a set of [PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8) values.

### PT_MV_SYSTIME {#PT-MV-SYSTIME}
```
public static final int PT_MV_SYSTIME
```


Variable size, a set of [PT\_SYSTIME](../../com.aspose.email/mapitype\#PT-SYSTIME) values.

### PT_MV_UNICODE {#PT-MV-UNICODE}
```
public static final int PT_MV_UNICODE
```


Variable size, a set of [PT\_UNICODE](../../com.aspose.email/mapitype\#PT-UNICODE) values.

### PT_OBJECT {#PT-OBJECT}
```
public static final int PT_OBJECT
```


The property value is a COM object

### PT_SHORT {#PT-SHORT}
```
public static final int PT_SHORT
```


2 bytes, a 16-bit integer

### PT_STRING8 {#PT-STRING8}
```
public static final int PT_STRING8
```


Variable size, a string of multi-byte characters in externally specified encoding with terminating null character (single 0 byte).

### PT_SYSTIME {#PT-SYSTIME}
```
public static final int PT_SYSTIME
```


8 bytes, a 64-bit integer representing the number of 100-nanosecond intervals since January 1, 1601

### PT_UNICODE {#PT-UNICODE}
```
public static final int PT_UNICODE
```


Variable size, a string of Unicode characters in UTF-16LE encoding with terminating null character(0x0000)

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

