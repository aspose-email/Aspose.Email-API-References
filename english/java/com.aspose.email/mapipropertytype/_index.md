---
title: MapiPropertyType
second_title: Aspose.Email for Java API Reference
description:  Represents the data type of MapiProperty data.
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
| [None](#None) | No values are set. |
| [PT_SHORT](#PT-SHORT) | Signed 16-bit integer. |
| [PT_LONG](#PT-LONG) | Signed or unsigned 32-bit integer. |
| [PT_ERROR](#PT-ERROR) | SCODE value; 32-bit unsigned integer. |
| [PT_BOOLEAN](#PT-BOOLEAN) | 16-bit Boolean value where zero equals FALSE and non-zero equals TRUE. |
| [PT_OBJECT](#PT-OBJECT) | Pointer to an object that implements the IUnknown interface. |
| [PT_LONGLONG](#PT-LONGLONG) | Signed or unsigned 64-bit integer. |
| [PT_STRING8](#PT-STRING8) | Null-terminated 8-bit character string. |
| [PT_UNICODE](#PT-UNICODE) | PT\_UNICODE |
| [PT_SYSTIME](#PT-SYSTIME) | 64-bit integer data and time value in the form of a FILETIME structure. |
| [PT_CLSID](#PT-CLSID) | CLSID structure value. |
| [PT_SRESTRICTION](#PT-SRESTRICTION) | PT\_SRESTRICTION |
| [PT_ACTIONS](#PT-ACTIONS) | PT\_ACTIONS |
| [PT_BINARY](#PT-BINARY) | SBinary structure value, a counted byte array. |
| [PT_MV_xxx](#PT-MV-xxx) | PT\_MV\_xxx |
| [PT_MV_STRING8](#PT-MV-STRING8) | A count field followed by that many PT\_STRING8 values. |
| [PT_MV_UNICODE](#PT-MV-UNICODE) | A count field followed by that many PT\_UNICODE values. |
| [PT_MV_BINARY](#PT-MV-BINARY) | A count field followed by that many PT\_BINARY values. |
| [PT_DOUBLE](#PT-DOUBLE) | A 64-bit floating point number. |
| [PT_FLOAT](#PT-FLOAT) | A 32-bit floating point number. |
| [PT_MV_FLOAT](#PT-MV-FLOAT) | A count field followed by that many PT\_FLOAT values. |
| [PT_MV_DOUBLE](#PT-MV-DOUBLE) | A count field followed by that many PT\_DOUBLE values. |
| [PT_MV_CURRENCY](#PT-MV-CURRENCY) | A count field followed by that many PT\_CURRENCY values. |
| [PT_MV_APPTIME](#PT-MV-APPTIME) | A count field followed by that many PtypFloatingTime values. |
| [PT_MV_LONGLONG](#PT-MV-LONGLONG) | A count field followed by that many PT\_LONGLONG values. |
| [PT_MV_CLSID](#PT-MV-CLSID) | A count field followed by that many PT\_CLSID values. |
| [PT_MV_SHORT](#PT-MV-SHORT) | A count field followed by that many PT\_SHORT values. |
| [PT_MV_SYSTIME](#PT-MV-SYSTIME) | A count field followed by that many PT\_SYSTIME values. |
| [PT_MV_BOOLEAN](#PT-MV-BOOLEAN) | A count field followed by that many PT\_BOOLEAN values. |
| [PT_SVREID](#PT-SVREID) | Variable size, a 16-bit (2-byte) count followed by a structure. |
| [PT_UNSPECIFIED](#PT-UNSPECIFIED) | Indicates that the property type is unknown. |
| [PT_NULL](#PT-NULL) | Indicates no property value. |
| [PT_MV_LONG](#PT-MV-LONG) | A count field followed by that many PT\_LONG values. |
### None {#None}
```
public static final int None
```


No values are set.

### PT_SHORT {#PT-SHORT}
```
public static final int PT_SHORT
```


Signed 16-bit integer. This property type is the same as PT\_SHORT and the OLE type VT\_I2.

### PT_LONG {#PT-LONG}
```
public static final int PT_LONG
```


Signed or unsigned 32-bit integer. This property type is the same as PT\_I4 and the OLE type VT\_I4.

### PT_ERROR {#PT-ERROR}
```
public static final int PT_ERROR
```


SCODE value; 32-bit unsigned integer. This property type is the same as the OLE type VT\_ERROR.

### PT_BOOLEAN {#PT-BOOLEAN}
```
public static final int PT_BOOLEAN
```


16-bit Boolean value where zero equals FALSE and non-zero equals TRUE. This property type is the same as the OLE type VT\_BOOL.

### PT_OBJECT {#PT-OBJECT}
```
public static final int PT_OBJECT
```


Pointer to an object that implements the IUnknown interface. This property type is similar to several OLE types such as VT\_UNKNOWN.

### PT_LONGLONG {#PT-LONGLONG}
```
public static final int PT_LONGLONG
```


Signed or unsigned 64-bit integer. This property type is the same as PT\_I8 and the OLE type VT\_I8.

### PT_STRING8 {#PT-STRING8}
```
public static final int PT_STRING8
```


Null-terminated 8-bit character string. This property type is the same as the OLE type VT\_LPSTR.

### PT_UNICODE {#PT-UNICODE}
```
public static final int PT_UNICODE
```


PT\_UNICODE

### PT_SYSTIME {#PT-SYSTIME}
```
public static final int PT_SYSTIME
```


64-bit integer data and time value in the form of a FILETIME structure. This property type is the same as the OLE type VT\_FILETIME.

### PT_CLSID {#PT-CLSID}
```
public static final int PT_CLSID
```


CLSID structure value. This property type is the same as the OLE type VT\_CLSID.

### PT_SRESTRICTION {#PT-SRESTRICTION}
```
public static final int PT_SRESTRICTION
```


PT\_SRESTRICTION

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

### PT_MV_xxx {#PT-MV-xxx}
```
public static final int PT_MV_xxx
```


PT\_MV\_xxx

### PT_MV_STRING8 {#PT-MV-STRING8}
```
public static final int PT_MV_STRING8
```


A count field followed by that many PT\_STRING8 values.

### PT_MV_UNICODE {#PT-MV-UNICODE}
```
public static final int PT_MV_UNICODE
```


A count field followed by that many PT\_UNICODE values.

### PT_MV_BINARY {#PT-MV-BINARY}
```
public static final int PT_MV_BINARY
```


A count field followed by that many PT\_BINARY values.

### PT_DOUBLE {#PT-DOUBLE}
```
public static final int PT_DOUBLE
```


A 64-bit floating point number.

### PT_FLOAT {#PT-FLOAT}
```
public static final int PT_FLOAT
```


A 32-bit floating point number.

### PT_MV_FLOAT {#PT-MV-FLOAT}
```
public static final int PT_MV_FLOAT
```


A count field followed by that many PT\_FLOAT values.

### PT_MV_DOUBLE {#PT-MV-DOUBLE}
```
public static final int PT_MV_DOUBLE
```


A count field followed by that many PT\_DOUBLE values.

### PT_MV_CURRENCY {#PT-MV-CURRENCY}
```
public static final int PT_MV_CURRENCY
```


A count field followed by that many PT\_CURRENCY values.

### PT_MV_APPTIME {#PT-MV-APPTIME}
```
public static final int PT_MV_APPTIME
```


A count field followed by that many PtypFloatingTime values.

### PT_MV_LONGLONG {#PT-MV-LONGLONG}
```
public static final int PT_MV_LONGLONG
```


A count field followed by that many PT\_LONGLONG values.

### PT_MV_CLSID {#PT-MV-CLSID}
```
public static final int PT_MV_CLSID
```


A count field followed by that many PT\_CLSID values.

### PT_MV_SHORT {#PT-MV-SHORT}
```
public static final int PT_MV_SHORT
```


A count field followed by that many PT\_SHORT values.

### PT_MV_SYSTIME {#PT-MV-SYSTIME}
```
public static final int PT_MV_SYSTIME
```


A count field followed by that many PT\_SYSTIME values.

### PT_MV_BOOLEAN {#PT-MV-BOOLEAN}
```
public static final int PT_MV_BOOLEAN
```


A count field followed by that many PT\_BOOLEAN values.

### PT_SVREID {#PT-SVREID}
```
public static final int PT_SVREID
```


Variable size, a 16-bit (2-byte) count followed by a structure.

### PT_UNSPECIFIED {#PT-UNSPECIFIED}
```
public static final int PT_UNSPECIFIED
```


Indicates that the property type is unknown.

### PT_NULL {#PT-NULL}
```
public static final int PT_NULL
```


Indicates no property value.

### PT_MV_LONG {#PT-MV-LONG}
```
public static final int PT_MV_LONG
```


A count field followed by that many PT\_LONG values.

