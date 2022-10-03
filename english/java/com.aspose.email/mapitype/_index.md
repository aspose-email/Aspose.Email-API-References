---
title: MapiType
second_title: Aspose.Email for Java API Reference
description: Contains possible MAPI property types which can be stored with message object.
type: docs
weight: 477
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
| [None](#None) | No values are set. |
| [PT_SHORT](#PT-SHORT) | 2 bytes, a 16-bit integer |
| [PT_LONG](#PT-LONG) | 4 bytes, a 32-bit integer |
| [PT_FLOAT](#PT-FLOAT) | 4 bytes, a 32-bit floating point number |
| [PT_DOUBLE](#PT-DOUBLE) | 8 bytes, a 64-bit floating point number |
| [PT_CURRENCY](#PT-CURRENCY) | 8 bytes, a 64-bit signed, scaled integer representation of a decimal currency value, with 4 places to the right of the decimal point |
| [PT_APPTIME](#PT-APPTIME) | 8 bytes, a 64-bit floating point number in which the whole number part represents the number of days since December 30, 1899, and the fractional part represents the fraction of a day since midnight |
| [PT_ERROR](#PT-ERROR) | 4 bytes, a 32-bit integer encoding error information |
| [PT_BOOLEAN](#PT-BOOLEAN) | 1 byte, restricted to 1 or 0 |
| [PT_OBJECT](#PT-OBJECT) | The property value is a COM object |
| [PT_LONGLONG](#PT-LONGLONG) | 8 bytes, a 64-bit integer |
| [PT_UNICODE](#PT-UNICODE) | Variable size, a string of Unicode characters in UTF-16LE encoding with terminating null character(0x0000) |
| [PT_STRING8](#PT-STRING8) | Variable size, a string of multi-byte characters in externally specified encoding with terminating null character (single 0 byte). |
| [PT_SYSTIME](#PT-SYSTIME) | 8 bytes, a 64-bit integer representing the number of 100-nanosecond intervals since January 1, 1601 |
| [PT_CLSID](#PT-CLSID) | 16 bytes, a GUID with Data1, Data2, and Data3 fields in little-endian format |
| [PT_BINARY](#PT-BINARY) | Variable size, a byte array |
| [PT_MV_SHORT](#PT-MV-SHORT) | Variable size, a set of [PT\_SHORT](../../com.aspose.email/mapitype\#PT-SHORT) values. |
| [PT_MV_LONG](#PT-MV-LONG) | Variable size, a set of [PT\_LONG](../../com.aspose.email/mapitype\#PT-LONG) values. |
| [PT_MV_FLOAT](#PT-MV-FLOAT) | Variable size, a set of [PT\_FLOAT](../../com.aspose.email/mapitype\#PT-FLOAT) values. |
| [PT_MV_DOUBLE](#PT-MV-DOUBLE) | Variable size, a set of [PT\_DOUBLE](../../com.aspose.email/mapitype\#PT-DOUBLE) values. |
| [PT_MV_CURRENCY](#PT-MV-CURRENCY) | Variable size, a set of [PT\_CURRENCY](../../com.aspose.email/mapitype\#PT-CURRENCY) values. |
| [PT_MV_APPTIME](#PT-MV-APPTIME) | Variable size, a set of [PT\_APPTIME](../../com.aspose.email/mapitype\#PT-APPTIME) values. |
| [PT_MV_LONGLONG](#PT-MV-LONGLONG) | Variable size, a set of [PT\_LONGLONG](../../com.aspose.email/mapitype\#PT-LONGLONG) values. |
| [PT_MV_UNICODE](#PT-MV-UNICODE) | Variable size, a set of [PT\_UNICODE](../../com.aspose.email/mapitype\#PT-UNICODE) values. |
| [PT_MV_STRING8](#PT-MV-STRING8) | Variable size, a set of [PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8) values. |
| [PT_MV_SYSTIME](#PT-MV-SYSTIME) | Variable size, a set of [PT\_SYSTIME](../../com.aspose.email/mapitype\#PT-SYSTIME) values. |
| [PT_MV_CLSID](#PT-MV-CLSID) | Variable size, a set of [PT\_CLSID](../../com.aspose.email/mapitype\#PT-CLSID) values. |
| [PT_MV_BINARY](#PT-MV-BINARY) | Variable size, a set of [PT\_BINARY](../../com.aspose.email/mapitype\#PT-BINARY) values. |
### MapiType() {#MapiType--}
```
public MapiType()
```


Constructor for MapiType.

### None {#None}
```
public static final int None
```


No values are set.

### PT_SHORT {#PT-SHORT}
```
public static final int PT_SHORT
```


2 bytes, a 16-bit integer

### PT_LONG {#PT-LONG}
```
public static final int PT_LONG
```


4 bytes, a 32-bit integer

### PT_FLOAT {#PT-FLOAT}
```
public static final int PT_FLOAT
```


4 bytes, a 32-bit floating point number

### PT_DOUBLE {#PT-DOUBLE}
```
public static final int PT_DOUBLE
```


8 bytes, a 64-bit floating point number

### PT_CURRENCY {#PT-CURRENCY}
```
public static final int PT_CURRENCY
```


8 bytes, a 64-bit signed, scaled integer representation of a decimal currency value, with 4 places to the right of the decimal point

### PT_APPTIME {#PT-APPTIME}
```
public static final int PT_APPTIME
```


8 bytes, a 64-bit floating point number in which the whole number part represents the number of days since December 30, 1899, and the fractional part represents the fraction of a day since midnight

### PT_ERROR {#PT-ERROR}
```
public static final int PT_ERROR
```


4 bytes, a 32-bit integer encoding error information

### PT_BOOLEAN {#PT-BOOLEAN}
```
public static final int PT_BOOLEAN
```


1 byte, restricted to 1 or 0

### PT_OBJECT {#PT-OBJECT}
```
public static final int PT_OBJECT
```


The property value is a COM object

### PT_LONGLONG {#PT-LONGLONG}
```
public static final int PT_LONGLONG
```


8 bytes, a 64-bit integer

### PT_UNICODE {#PT-UNICODE}
```
public static final int PT_UNICODE
```


Variable size, a string of Unicode characters in UTF-16LE encoding with terminating null character(0x0000)

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

### PT_CLSID {#PT-CLSID}
```
public static final int PT_CLSID
```


16 bytes, a GUID with Data1, Data2, and Data3 fields in little-endian format

### PT_BINARY {#PT-BINARY}
```
public static final int PT_BINARY
```


Variable size, a byte array

### PT_MV_SHORT {#PT-MV-SHORT}
```
public static final int PT_MV_SHORT
```


Variable size, a set of [PT\_SHORT](../../com.aspose.email/mapitype\#PT-SHORT) values.

### PT_MV_LONG {#PT-MV-LONG}
```
public static final int PT_MV_LONG
```


Variable size, a set of [PT\_LONG](../../com.aspose.email/mapitype\#PT-LONG) values.

### PT_MV_FLOAT {#PT-MV-FLOAT}
```
public static final int PT_MV_FLOAT
```


Variable size, a set of [PT\_FLOAT](../../com.aspose.email/mapitype\#PT-FLOAT) values.

### PT_MV_DOUBLE {#PT-MV-DOUBLE}
```
public static final int PT_MV_DOUBLE
```


Variable size, a set of [PT\_DOUBLE](../../com.aspose.email/mapitype\#PT-DOUBLE) values.

### PT_MV_CURRENCY {#PT-MV-CURRENCY}
```
public static final int PT_MV_CURRENCY
```


Variable size, a set of [PT\_CURRENCY](../../com.aspose.email/mapitype\#PT-CURRENCY) values.

### PT_MV_APPTIME {#PT-MV-APPTIME}
```
public static final int PT_MV_APPTIME
```


Variable size, a set of [PT\_APPTIME](../../com.aspose.email/mapitype\#PT-APPTIME) values.

### PT_MV_LONGLONG {#PT-MV-LONGLONG}
```
public static final int PT_MV_LONGLONG
```


Variable size, a set of [PT\_LONGLONG](../../com.aspose.email/mapitype\#PT-LONGLONG) values.

### PT_MV_UNICODE {#PT-MV-UNICODE}
```
public static final int PT_MV_UNICODE
```


Variable size, a set of [PT\_UNICODE](../../com.aspose.email/mapitype\#PT-UNICODE) values.

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

### PT_MV_CLSID {#PT-MV-CLSID}
```
public static final int PT_MV_CLSID
```


Variable size, a set of [PT\_CLSID](../../com.aspose.email/mapitype\#PT-CLSID) values.

### PT_MV_BINARY {#PT-MV-BINARY}
```
public static final int PT_MV_BINARY
```


Variable size, a set of [PT\_BINARY](../../com.aspose.email/mapitype\#PT-BINARY) values.

