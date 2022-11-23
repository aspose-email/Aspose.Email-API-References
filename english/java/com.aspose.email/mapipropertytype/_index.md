---
title: MapiPropertyType
second_title: Aspose.Email for Java API Reference
description: Represents the data type of MapiProperty data.
type: docs
weight: 460
url: /java/com.aspose.email/mapipropertytype/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MapiPropertyType extends System.Enum
```

Represents the data type of MapiProperty data.
## Fields

| Field | Description |
| --- | --- |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [None](#None) | No values are set. |
| [PT_ACTIONS](#PT-ACTIONS) | PT\_ACTIONS |
| [PT_BINARY](#PT-BINARY) | SBinary structure value, a counted byte array. |
| [PT_BOOLEAN](#PT-BOOLEAN) | 16-bit Boolean value where zero equals FALSE and non-zero equals TRUE. |
| [PT_CLSID](#PT-CLSID) | CLSID structure value. |
| [PT_DOUBLE](#PT-DOUBLE) | A 64-bit floating point number. |
| [PT_ERROR](#PT-ERROR) | SCODE value; 32-bit unsigned integer. |
| [PT_FLOAT](#PT-FLOAT) | A 32-bit floating point number. |
| [PT_LONG](#PT-LONG) | Signed or unsigned 32-bit integer. |
| [PT_LONGLONG](#PT-LONGLONG) | Signed or unsigned 64-bit integer. |
| [PT_MV_APPTIME](#PT-MV-APPTIME) | A count field followed by that many PtypFloatingTime values. |
| [PT_MV_BINARY](#PT-MV-BINARY) | A count field followed by that many PT\_BINARY values. |
| [PT_MV_BOOLEAN](#PT-MV-BOOLEAN) | A count field followed by that many PT\_BOOLEAN values. |
| [PT_MV_CLSID](#PT-MV-CLSID) | A count field followed by that many PT\_CLSID values. |
| [PT_MV_CURRENCY](#PT-MV-CURRENCY) | A count field followed by that many PT\_CURRENCY values. |
| [PT_MV_DOUBLE](#PT-MV-DOUBLE) | A count field followed by that many PT\_DOUBLE values. |
| [PT_MV_FLOAT](#PT-MV-FLOAT) | A count field followed by that many PT\_FLOAT values. |
| [PT_MV_LONG](#PT-MV-LONG) | A count field followed by that many PT\_LONG values. |
| [PT_MV_LONGLONG](#PT-MV-LONGLONG) | A count field followed by that many PT\_LONGLONG values. |
| [PT_MV_SHORT](#PT-MV-SHORT) | A count field followed by that many PT\_SHORT values. |
| [PT_MV_STRING8](#PT-MV-STRING8) | A count field followed by that many PT\_STRING8 values. |
| [PT_MV_SYSTIME](#PT-MV-SYSTIME) | A count field followed by that many PT\_SYSTIME values. |
| [PT_MV_UNICODE](#PT-MV-UNICODE) | A count field followed by that many PT\_UNICODE values. |
| [PT_MV_xxx](#PT-MV-xxx) | PT\_MV\_xxx |
| [PT_NULL](#PT-NULL) | Indicates no property value. |
| [PT_OBJECT](#PT-OBJECT) | Pointer to an object that implements the IUnknown interface. |
| [PT_SHORT](#PT-SHORT) | Signed 16-bit integer. |
| [PT_SRESTRICTION](#PT-SRESTRICTION) | PT\_SRESTRICTION |
| [PT_STRING8](#PT-STRING8) | Null-terminated 8-bit character string. |
| [PT_SVREID](#PT-SVREID) | Variable size, a 16-bit (2-byte) count followed by a structure. |
| [PT_SYSTIME](#PT-SYSTIME) | 64-bit integer data and time value in the form of a FILETIME structure. |
| [PT_UNICODE](#PT-UNICODE) | PT\_UNICODE |
| [PT_UNSPECIFIED](#PT-UNSPECIFIED) | Indicates that the property type is unknown. |
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
### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### None {#None}
```
public static final int None
```


No values are set.

### PT_ACTIONS {#PT-ACTIONS}
```
public static final int PT_ACTIONS
```


PT\_ACTIONS

### PT_BINARY {#PT-BINARY}
```
public static final int PT_BINARY
```


SBinary structure value, a counted byte array.

### PT_BOOLEAN {#PT-BOOLEAN}
```
public static final int PT_BOOLEAN
```


16-bit Boolean value where zero equals FALSE and non-zero equals TRUE. This property type is the same as the OLE type VT\_BOOL.

### PT_CLSID {#PT-CLSID}
```
public static final int PT_CLSID
```


CLSID structure value. This property type is the same as the OLE type VT\_CLSID.

### PT_DOUBLE {#PT-DOUBLE}
```
public static final int PT_DOUBLE
```


A 64-bit floating point number.

### PT_ERROR {#PT-ERROR}
```
public static final int PT_ERROR
```


SCODE value; 32-bit unsigned integer. This property type is the same as the OLE type VT\_ERROR.

### PT_FLOAT {#PT-FLOAT}
```
public static final int PT_FLOAT
```


A 32-bit floating point number.

### PT_LONG {#PT-LONG}
```
public static final int PT_LONG
```


Signed or unsigned 32-bit integer. This property type is the same as PT\_I4 and the OLE type VT\_I4.

### PT_LONGLONG {#PT-LONGLONG}
```
public static final int PT_LONGLONG
```


Signed or unsigned 64-bit integer. This property type is the same as PT\_I8 and the OLE type VT\_I8.

### PT_MV_APPTIME {#PT-MV-APPTIME}
```
public static final int PT_MV_APPTIME
```


A count field followed by that many PtypFloatingTime values.

### PT_MV_BINARY {#PT-MV-BINARY}
```
public static final int PT_MV_BINARY
```


A count field followed by that many PT\_BINARY values.

### PT_MV_BOOLEAN {#PT-MV-BOOLEAN}
```
public static final int PT_MV_BOOLEAN
```


A count field followed by that many PT\_BOOLEAN values.

### PT_MV_CLSID {#PT-MV-CLSID}
```
public static final int PT_MV_CLSID
```


A count field followed by that many PT\_CLSID values.

### PT_MV_CURRENCY {#PT-MV-CURRENCY}
```
public static final int PT_MV_CURRENCY
```


A count field followed by that many PT\_CURRENCY values.

### PT_MV_DOUBLE {#PT-MV-DOUBLE}
```
public static final int PT_MV_DOUBLE
```


A count field followed by that many PT\_DOUBLE values.

### PT_MV_FLOAT {#PT-MV-FLOAT}
```
public static final int PT_MV_FLOAT
```


A count field followed by that many PT\_FLOAT values.

### PT_MV_LONG {#PT-MV-LONG}
```
public static final int PT_MV_LONG
```


A count field followed by that many PT\_LONG values.

### PT_MV_LONGLONG {#PT-MV-LONGLONG}
```
public static final int PT_MV_LONGLONG
```


A count field followed by that many PT\_LONGLONG values.

### PT_MV_SHORT {#PT-MV-SHORT}
```
public static final int PT_MV_SHORT
```


A count field followed by that many PT\_SHORT values.

### PT_MV_STRING8 {#PT-MV-STRING8}
```
public static final int PT_MV_STRING8
```


A count field followed by that many PT\_STRING8 values.

### PT_MV_SYSTIME {#PT-MV-SYSTIME}
```
public static final int PT_MV_SYSTIME
```


A count field followed by that many PT\_SYSTIME values.

### PT_MV_UNICODE {#PT-MV-UNICODE}
```
public static final int PT_MV_UNICODE
```


A count field followed by that many PT\_UNICODE values.

### PT_MV_xxx {#PT-MV-xxx}
```
public static final int PT_MV_xxx
```


PT\_MV\_xxx

### PT_NULL {#PT-NULL}
```
public static final int PT_NULL
```


Indicates no property value.

### PT_OBJECT {#PT-OBJECT}
```
public static final int PT_OBJECT
```


Pointer to an object that implements the IUnknown interface. This property type is similar to several OLE types such as VT\_UNKNOWN.

### PT_SHORT {#PT-SHORT}
```
public static final int PT_SHORT
```


Signed 16-bit integer. This property type is the same as PT\_SHORT and the OLE type VT\_I2.

### PT_SRESTRICTION {#PT-SRESTRICTION}
```
public static final int PT_SRESTRICTION
```


PT\_SRESTRICTION

### PT_STRING8 {#PT-STRING8}
```
public static final int PT_STRING8
```


Null-terminated 8-bit character string. This property type is the same as the OLE type VT\_LPSTR.

### PT_SVREID {#PT-SVREID}
```
public static final int PT_SVREID
```


Variable size, a 16-bit (2-byte) count followed by a structure.

### PT_SYSTIME {#PT-SYSTIME}
```
public static final int PT_SYSTIME
```


64-bit integer data and time value in the form of a FILETIME structure. This property type is the same as the OLE type VT\_FILETIME.

### PT_UNICODE {#PT-UNICODE}
```
public static final int PT_UNICODE
```


PT\_UNICODE

### PT_UNSPECIFIED {#PT-UNSPECIFIED}
```
public static final int PT_UNSPECIFIED
```


Indicates that the property type is unknown.

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

