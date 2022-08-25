---
title: PropertyDataType
second_title: Aspose.Email for Java API Reference
description:  MS-OXCDATA Data Structures
type: docs
weight: 576
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
| [Unspecified](#Unspecified) | Any: this property type value matches any type; a server MUST return the actual type in its response. |
| [Null](#Null) | None: This property is a placeholder. |
| [Integer16](#Integer16) | 2 bytes; a 16-bit integer Specification name: PtypInteger16; Alternate names: PT\_SHORT, PT\_I2, i2, ui2; |
| [Integer32](#Integer32) | 4 bytes; a 32-bit integer Specification name: PtypInteger32; Alternate names: PT\_LONG, PT\_I4, int, ui4; |
| [Floating32](#Floating32) | 4 bytes; a 32-bit floating point number Specification name: PtypFloating32; Alternate names: PT\_FLOAT, PT\_R4, float, r4; |
| [Floating64](#Floating64) | 8 bytes; a 64-bit floating point number Specification name: PtypFloating64; Alternate names: PT\_DOUBLE, PT\_R8, r8; |
| [Currency](#Currency) | 8 bytes; a 64-bit signed, scaled integer representation of a decimal currency value, with four places to the right of the decimal point Specification name: PtypCurrency; Alternate names: PT\_CURRENCY, fixed.14.4; |
| [FloatingTime](#FloatingTime) | 8 bytes; a 64-bit floating point number in which the whole number part represents the number of days since December 30, 1899, and the fractional part represents the fraction of a day since midnight Specification name: PtypFloatingTime; Alternate names: PT\_APPTIME; The date information is represented by whole-number increments, starting with December 30, 1899 midnight as time zero. |
| [ErrorCode](#ErrorCode) | 4 bytes; a 32-bit integer encoding error information Specification name: PtypErrorCode; Alternate names: PT\_ERROR; |
| [Boolean](#Boolean) | 1 byte; restricted to 1 or 0 Specification name: PtypBoolean; Alternate names: PT\_BOOLEAN. |
| [Integer64](#Integer64) | 8 bytes; a 64-bit integer Specification name: PtypInteger64; Alternate names: PT\_LONGLONG, PT\_I8, i8, ui8; |
| [String](#String) | Variable size; a string of Unicode characters in UTF-16LE format encoding with terminating null character (0x0000). |
| [String8](#String8) | Variable size; a string of multibyte characters in externally specified encoding with terminating null character (single 0 byte). |
| [Time](#Time) | 8 bytes; a 64-bit integer representing the number of 100-nanosecond intervals since January 1, 1601 Specification name: PtypTime; Alternate names: PT\_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz; |
| [Guid](#Guid) | 16 bytes; a GUID with Data1, Data2, and Data3 fields in little-endian format Specification name: PtypGuid; Alternate names: PT\_CLSID, UUID; |
| [ServerId](#ServerId) | Variable size; a 16-bit COUNT field followed by a structure Specification name: PtypServerId; Alternate names: PT\_SVREID; |
| [Restriction](#Restriction) | Variable size; a byte array representing one or more Restriction structures Specification name: PtypRestriction; Alternate names: PT\_SRESTRICT; |
| [RuleAction](#RuleAction) | Variable size; a 16-bit COUNT field followed by that many rule action structures Specification name: PtypRuleAction; Alternate names: PT\_ACTIONS; |
| [Binary](#Binary) | Variable size; a COUNT field followed by that many bytes. |
| [MultipleInteger16](#MultipleInteger16) | Variable size; a COUNT field followed by that many PtypInteger16 values. |
| [MultipleInteger32](#MultipleInteger32) | Variable size; a COUNT field followed by that many PtypInteger32 values. |
| [MultipleFloating32](#MultipleFloating32) | Variable size; a COUNT field followed by that many PtypFloating32 values. |
| [MultipleFloating64](#MultipleFloating64) | Variable size; a COUNT field followed by that many PtypFloating64 values. |
| [MultipleCurrency](#MultipleCurrency) | Variable size; a COUNT field followed by that many PtypCurrency values. |
| [MultipleFloatingTime](#MultipleFloatingTime) | Variable size; a COUNT field followed by that many PtypFloatingTime values. |
| [MultipleBoolean](#MultipleBoolean) | Variable size; a COUNT field followed by that many PtypBoolean values. |
| [MultipleInteger64](#MultipleInteger64) | Variable size; a COUNT field followed by that many PtypInteger64 values. |
| [MultipleString](#MultipleString) | Variable size; a COUNT field followed by that many PtypString values. |
| [MultipleString8](#MultipleString8) | Variable size; a COUNT field followed by that many PtypString8 values. |
| [MultipleTime](#MultipleTime) | Variable size; a COUNT field followed by that many PtypTime values. |
| [MultipleGuid](#MultipleGuid) | Variable size; a COUNT field followed by that many PtypGuid values. |
| [MultipleBinary](#MultipleBinary) | Variable size; a COUNT field followed by that many PtypBinary values. |
| [Object](#Object) | The property value is a Component Object Model (COM) object. |
### Unspecified {#Unspecified}
```
public static final int Unspecified
```


Any: this property type value matches any type; a server MUST return the actual type in its response. Servers MUST NOT return this type in response to a client request other than NspiGetIDsFromNames or the RopGetPropertyIdsFromNames ROP request ([MS-OXCROPS] section 2.2.8.1). Specification name: PtypUnspecified; Alternate names: PT\_UNSPECIFIED;

### Null {#Null}
```
public static final int Null
```


None: This property is a placeholder. Specification name: PtypNull; Alternate names: PT\_NULL;

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

### Currency {#Currency}
```
public static final int Currency
```


8 bytes; a 64-bit signed, scaled integer representation of a decimal currency value, with four places to the right of the decimal point Specification name: PtypCurrency; Alternate names: PT\_CURRENCY, fixed.14.4;

### FloatingTime {#FloatingTime}
```
public static final int FloatingTime
```


8 bytes; a 64-bit floating point number in which the whole number part represents the number of days since December 30, 1899, and the fractional part represents the fraction of a day since midnight Specification name: PtypFloatingTime; Alternate names: PT\_APPTIME; The date information is represented by whole-number increments, starting with December 30, 1899 midnight as time zero. The time information is represented by the fraction of a day since the preceding midnight. For example, 6:00 A.M. on January 4, 1900 would be represented by the value 5.25 (5 and 1/4 of a day past December 30, 1899).

### ErrorCode {#ErrorCode}
```
public static final int ErrorCode
```


4 bytes; a 32-bit integer encoding error information Specification name: PtypErrorCode; Alternate names: PT\_ERROR;

### Boolean {#Boolean}
```
public static final int Boolean
```


1 byte; restricted to 1 or 0 Specification name: PtypBoolean; Alternate names: PT\_BOOLEAN. bool;

### Integer64 {#Integer64}
```
public static final int Integer64
```


8 bytes; a 64-bit integer Specification name: PtypInteger64; Alternate names: PT\_LONGLONG, PT\_I8, i8, ui8;

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

### Guid {#Guid}
```
public static final int Guid
```


16 bytes; a GUID with Data1, Data2, and Data3 fields in little-endian format Specification name: PtypGuid; Alternate names: PT\_CLSID, UUID;

### ServerId {#ServerId}
```
public static final int ServerId
```


Variable size; a 16-bit COUNT field followed by a structure Specification name: PtypServerId; Alternate names: PT\_SVREID;

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

### Binary {#Binary}
```
public static final int Binary
```


Variable size; a COUNT field followed by that many bytes. Specification name: PtypBinary; Alternate names: PT\_BINARY;

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

### MultipleCurrency {#MultipleCurrency}
```
public static final int MultipleCurrency
```


Variable size; a COUNT field followed by that many PtypCurrency values. Specification name: PtypMultipleCurrency; Alternate names: PT\_MV\_CURRENCY, mv.fixed.14.4;

### MultipleFloatingTime {#MultipleFloatingTime}
```
public static final int MultipleFloatingTime
```


Variable size; a COUNT field followed by that many PtypFloatingTime values. Specification name: PtypMultipleFloatingTime; Alternate names: PT\_MV\_APPTIME;

### MultipleBoolean {#MultipleBoolean}
```
public static final int MultipleBoolean
```


Variable size; a COUNT field followed by that many PtypBoolean values. Specification name: PtypMultipleBoolean; Alternate names: PT\_MV\_BOOLEAN;

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

### MultipleGuid {#MultipleGuid}
```
public static final int MultipleGuid
```


Variable size; a COUNT field followed by that many PtypGuid values. Specification name: PtypMultipleGuid; Alternate names: PT\_MV\_CLSID, mv.uuid;

### MultipleBinary {#MultipleBinary}
```
public static final int MultipleBinary
```


Variable size; a COUNT field followed by that many PtypBinary values. Specification name: PtypMultipleBinary; Alternate names: PT\_MV\_BINARY, mv.bin.hex;

### Object {#Object}
```
public static final int Object
```


The property value is a Component Object Model (COM) object. Specification name: PtypObject or PtypEmbeddedTable; Alternate names: PT\_OBJECT;

