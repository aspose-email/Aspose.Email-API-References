---
title: PropertyDataType
second_title: Aspose.Email for Java API Reference
description: MS-OXCDATA Data Structures
type: docs
weight: 581
url: /java/com.aspose.email/propertydatatype/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PropertyDataType extends System.Enum
```

[MS-OXCDATA]: Data Structures
## Fields

| Field | Description |
| --- | --- |
| [Binary](#Binary) | Variable size; a COUNT field followed by that many bytes. |
| [Boolean](#Boolean) | 1 byte; restricted to 1 or 0 Specification name: PtypBoolean; Alternate names: PT\_BOOLEAN. |
| [Currency](#Currency) | 8 bytes; a 64-bit signed, scaled integer representation of a decimal currency value, with four places to the right of the decimal point Specification name: PtypCurrency; Alternate names: PT\_CURRENCY, fixed.14.4; |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ErrorCode](#ErrorCode) | 4 bytes; a 32-bit integer encoding error information Specification name: PtypErrorCode; Alternate names: PT\_ERROR; |
| [Floating32](#Floating32) | 4 bytes; a 32-bit floating point number Specification name: PtypFloating32; Alternate names: PT\_FLOAT, PT\_R4, float, r4; |
| [Floating64](#Floating64) | 8 bytes; a 64-bit floating point number Specification name: PtypFloating64; Alternate names: PT\_DOUBLE, PT\_R8, r8; |
| [FloatingTime](#FloatingTime) | 8 bytes; a 64-bit floating point number in which the whole number part represents the number of days since December 30, 1899, and the fractional part represents the fraction of a day since midnight Specification name: PtypFloatingTime; Alternate names: PT\_APPTIME; The date information is represented by whole-number increments, starting with December 30, 1899 midnight as time zero. |
| [Guid](#Guid) | 16 bytes; a GUID with Data1, Data2, and Data3 fields in little-endian format Specification name: PtypGuid; Alternate names: PT\_CLSID, UUID; |
| [Integer16](#Integer16) | 2 bytes; a 16-bit integer Specification name: PtypInteger16; Alternate names: PT\_SHORT, PT\_I2, i2, ui2; |
| [Integer32](#Integer32) | 4 bytes; a 32-bit integer Specification name: PtypInteger32; Alternate names: PT\_LONG, PT\_I4, int, ui4; |
| [Integer64](#Integer64) | 8 bytes; a 64-bit integer Specification name: PtypInteger64; Alternate names: PT\_LONGLONG, PT\_I8, i8, ui8; |
| [MultipleBinary](#MultipleBinary) | Variable size; a COUNT field followed by that many PtypBinary values. |
| [MultipleBoolean](#MultipleBoolean) | Variable size; a COUNT field followed by that many PtypBoolean values. |
| [MultipleCurrency](#MultipleCurrency) | Variable size; a COUNT field followed by that many PtypCurrency values. |
| [MultipleFloating32](#MultipleFloating32) | Variable size; a COUNT field followed by that many PtypFloating32 values. |
| [MultipleFloating64](#MultipleFloating64) | Variable size; a COUNT field followed by that many PtypFloating64 values. |
| [MultipleFloatingTime](#MultipleFloatingTime) | Variable size; a COUNT field followed by that many PtypFloatingTime values. |
| [MultipleGuid](#MultipleGuid) | Variable size; a COUNT field followed by that many PtypGuid values. |
| [MultipleInteger16](#MultipleInteger16) | Variable size; a COUNT field followed by that many PtypInteger16 values. |
| [MultipleInteger32](#MultipleInteger32) | Variable size; a COUNT field followed by that many PtypInteger32 values. |
| [MultipleInteger64](#MultipleInteger64) | Variable size; a COUNT field followed by that many PtypInteger64 values. |
| [MultipleString](#MultipleString) | Variable size; a COUNT field followed by that many PtypString values. |
| [MultipleString8](#MultipleString8) | Variable size; a COUNT field followed by that many PtypString8 values. |
| [MultipleTime](#MultipleTime) | Variable size; a COUNT field followed by that many PtypTime values. |
| [Null](#Null) | None: This property is a placeholder. |
| [Object](#Object) | The property value is a Component Object Model (COM) object. |
| [Restriction](#Restriction) | Variable size; a byte array representing one or more Restriction structures Specification name: PtypRestriction; Alternate names: PT\_SRESTRICT; |
| [RuleAction](#RuleAction) | Variable size; a 16-bit COUNT field followed by that many rule action structures Specification name: PtypRuleAction; Alternate names: PT\_ACTIONS; |
| [ServerId](#ServerId) | Variable size; a 16-bit COUNT field followed by a structure Specification name: PtypServerId; Alternate names: PT\_SVREID; |
| [String](#String) | Variable size; a string of Unicode characters in UTF-16LE format encoding with terminating null character (0x0000). |
| [String8](#String8) | Variable size; a string of multibyte characters in externally specified encoding with terminating null character (single 0 byte). |
| [Time](#Time) | 8 bytes; a 64-bit integer representing the number of 100-nanosecond intervals since January 1, 1601 Specification name: PtypTime; Alternate names: PT\_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz; |
| [Unspecified](#Unspecified) | Any: this property type value matches any type; a server MUST return the actual type in its response. |
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
### Binary {#Binary}
```
public static final int Binary
```


Variable size; a COUNT field followed by that many bytes. Specification name: PtypBinary; Alternate names: PT\_BINARY;

### Boolean {#Boolean}
```
public static final int Boolean
```


1 byte; restricted to 1 or 0 Specification name: PtypBoolean; Alternate names: PT\_BOOLEAN. bool;

### Currency {#Currency}
```
public static final int Currency
```


8 bytes; a 64-bit signed, scaled integer representation of a decimal currency value, with four places to the right of the decimal point Specification name: PtypCurrency; Alternate names: PT\_CURRENCY, fixed.14.4;

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ErrorCode {#ErrorCode}
```
public static final int ErrorCode
```


4 bytes; a 32-bit integer encoding error information Specification name: PtypErrorCode; Alternate names: PT\_ERROR;

### Floating32 {#Floating32}
```
public static final int Floating32
```


4 bytes; a 32-bit floating point number Specification name: PtypFloating32; Alternate names: PT\_FLOAT, PT\_R4, float, r4;

### Floating64 {#Floating64}
```
public static final int Floating64
```


8 bytes; a 64-bit floating point number Specification name: PtypFloating64; Alternate names: PT\_DOUBLE, PT\_R8, r8;

### FloatingTime {#FloatingTime}
```
public static final int FloatingTime
```


8 bytes; a 64-bit floating point number in which the whole number part represents the number of days since December 30, 1899, and the fractional part represents the fraction of a day since midnight Specification name: PtypFloatingTime; Alternate names: PT\_APPTIME; The date information is represented by whole-number increments, starting with December 30, 1899 midnight as time zero. The time information is represented by the fraction of a day since the preceding midnight. For example, 6:00 A.M. on January 4, 1900 would be represented by the value 5.25 (5 and 1/4 of a day past December 30, 1899).

### Guid {#Guid}
```
public static final int Guid
```


16 bytes; a GUID with Data1, Data2, and Data3 fields in little-endian format Specification name: PtypGuid; Alternate names: PT\_CLSID, UUID;

### Integer16 {#Integer16}
```
public static final int Integer16
```


2 bytes; a 16-bit integer Specification name: PtypInteger16; Alternate names: PT\_SHORT, PT\_I2, i2, ui2;

### Integer32 {#Integer32}
```
public static final int Integer32
```


4 bytes; a 32-bit integer Specification name: PtypInteger32; Alternate names: PT\_LONG, PT\_I4, int, ui4;

### Integer64 {#Integer64}
```
public static final int Integer64
```


8 bytes; a 64-bit integer Specification name: PtypInteger64; Alternate names: PT\_LONGLONG, PT\_I8, i8, ui8;

### MultipleBinary {#MultipleBinary}
```
public static final int MultipleBinary
```


Variable size; a COUNT field followed by that many PtypBinary values. Specification name: PtypMultipleBinary; Alternate names: PT\_MV\_BINARY, mv.bin.hex;

### MultipleBoolean {#MultipleBoolean}
```
public static final int MultipleBoolean
```


Variable size; a COUNT field followed by that many PtypBoolean values. Specification name: PtypMultipleBoolean; Alternate names: PT\_MV\_BOOLEAN;

### MultipleCurrency {#MultipleCurrency}
```
public static final int MultipleCurrency
```


Variable size; a COUNT field followed by that many PtypCurrency values. Specification name: PtypMultipleCurrency; Alternate names: PT\_MV\_CURRENCY, mv.fixed.14.4;

### MultipleFloating32 {#MultipleFloating32}
```
public static final int MultipleFloating32
```


Variable size; a COUNT field followed by that many PtypFloating32 values. Specification name: PtypMultipleFloating32; Alternate names: PT\_MV\_FLOAT, PT\_MV\_R4, mv.float;

### MultipleFloating64 {#MultipleFloating64}
```
public static final int MultipleFloating64
```


Variable size; a COUNT field followed by that many PtypFloating64 values. Specification name: PtypMultipleFloating64; Alternate names: PT\_MV\_DOUBLE, PT\_MV\_R8;

### MultipleFloatingTime {#MultipleFloatingTime}
```
public static final int MultipleFloatingTime
```


Variable size; a COUNT field followed by that many PtypFloatingTime values. Specification name: PtypMultipleFloatingTime; Alternate names: PT\_MV\_APPTIME;

### MultipleGuid {#MultipleGuid}
```
public static final int MultipleGuid
```


Variable size; a COUNT field followed by that many PtypGuid values. Specification name: PtypMultipleGuid; Alternate names: PT\_MV\_CLSID, mv.uuid;

### MultipleInteger16 {#MultipleInteger16}
```
public static final int MultipleInteger16
```


Variable size; a COUNT field followed by that many PtypInteger16 values. Specification name: PtypMultipleInteger16; Alternate names: PT\_MV\_SHORT, PT\_MV\_I2, mv.i2;

### MultipleInteger32 {#MultipleInteger32}
```
public static final int MultipleInteger32
```


Variable size; a COUNT field followed by that many PtypInteger32 values. Specification name: PtypMultipleInteger32; Alternate names: PT\_MV\_LONG, PT\_MV\_I4, mv.i4;

### MultipleInteger64 {#MultipleInteger64}
```
public static final int MultipleInteger64
```


Variable size; a COUNT field followed by that many PtypInteger64 values. Specification name: PtypMultipleInteger64; Alternate names: PT\_MV\_I8, PT\_MV\_LONGLONG;

### MultipleString {#MultipleString}
```
public static final int MultipleString
```


Variable size; a COUNT field followed by that many PtypString values. Specification name: PtypMultipleString; Alternate names: PT\_MV\_UNICODE;

### MultipleString8 {#MultipleString8}
```
public static final int MultipleString8
```


Variable size; a COUNT field followed by that many PtypString8 values. Specification name: PtypMultipleString8; Alternate names: PT\_MV\_STRING8, mv.string;

### MultipleTime {#MultipleTime}
```
public static final int MultipleTime
```


Variable size; a COUNT field followed by that many PtypTime values. Specification name: PtypMultipleTime; Alternate names: PT\_MV\_SYSTIME;

### Null {#Null}
```
public static final int Null
```


None: This property is a placeholder. Specification name: PtypNull; Alternate names: PT\_NULL;

### Object {#Object}
```
public static final int Object
```


The property value is a Component Object Model (COM) object. Specification name: PtypObject or PtypEmbeddedTable; Alternate names: PT\_OBJECT;

### Restriction {#Restriction}
```
public static final int Restriction
```


Variable size; a byte array representing one or more Restriction structures Specification name: PtypRestriction; Alternate names: PT\_SRESTRICT;

### RuleAction {#RuleAction}
```
public static final int RuleAction
```


Variable size; a 16-bit COUNT field followed by that many rule action structures Specification name: PtypRuleAction; Alternate names: PT\_ACTIONS;

### ServerId {#ServerId}
```
public static final int ServerId
```


Variable size; a 16-bit COUNT field followed by a structure Specification name: PtypServerId; Alternate names: PT\_SVREID;

### String {#String}
```
public static final int String
```


Variable size; a string of Unicode characters in UTF-16LE format encoding with terminating null character (0x0000). Specification name: PtypString; Alternate names: PT\_UNICODE, string;

### String8 {#String8}
```
public static final int String8
```


Variable size; a string of multibyte characters in externally specified encoding with terminating null character (single 0 byte). Specification name: PtypString8; Alternate names: PT\_STRING8;

### Time {#Time}
```
public static final int Time
```


8 bytes; a 64-bit integer representing the number of 100-nanosecond intervals since January 1, 1601 Specification name: PtypTime; Alternate names: PT\_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz;

### Unspecified {#Unspecified}
```
public static final int Unspecified
```


Any: this property type value matches any type; a server MUST return the actual type in its response. Servers MUST NOT return this type in response to a client request other than NspiGetIDsFromNames or the RopGetPropertyIdsFromNames ROP request ([MS-OXCROPS] section 2.2.8.1). Specification name: PtypUnspecified; Alternate names: PT\_UNSPECIFIED;

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

