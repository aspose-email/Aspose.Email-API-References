---
title: Enum PropertyDataType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.PropertyDataType enum. MSOXCDATA Data Structures
type: docs
weight: 19180
url: /net/aspose.email.mapi/propertydatatype/
---
## PropertyDataType enumeration

[MS-OXCDATA]: Data Structures

```csharp
public enum PropertyDataType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Unspecified | `0` | Any: this property type value matches any type; a server MUST return the actual type in its response. Servers MUST NOT return this type in response to a client request other than NspiGetIDsFromNames or the RopGetPropertyIdsFromNames ROP request ([MS-OXCROPS] section 2.2.8.1). Specification name: PtypUnspecified; Alternate names: PT_UNSPECIFIED; |
| Null | `1` | None: This property is a placeholder. Specification name: PtypNull; Alternate names: PT_NULL; |
| Integer16 | `2` | 2 bytes; a 16-bit integer Specification name: PtypInteger16; Alternate names: PT_SHORT, PT_I2, i2, ui2; |
| Integer32 | `3` | 4 bytes; a 32-bit integer Specification name: PtypInteger32; Alternate names: PT_LONG, PT_I4, int, ui4; |
| Floating32 | `4` | 4 bytes; a 32-bit floating point number Specification name: PtypFloating32; Alternate names: PT_FLOAT, PT_R4, float, r4; |
| Floating64 | `5` | 8 bytes; a 64-bit floating point number Specification name: PtypFloating64; Alternate names: PT_DOUBLE, PT_R8, r8; |
| Currency | `6` | 8 bytes; a 64-bit signed, scaled integer representation of a decimal currency value, with four places to the right of the decimal point Specification name: PtypCurrency; Alternate names: PT_CURRENCY, fixed.14.4; |
| FloatingTime | `7` | 8 bytes; a 64-bit floating point number in which the whole number part represents the number of days since December 30, 1899, and the fractional part represents the fraction of a day since midnight Specification name: PtypFloatingTime; Alternate names: PT_APPTIME; The date information is represented by whole-number increments, starting with December 30, 1899 midnight as time zero. The time information is represented by the fraction of a day since the preceding midnight. For example, 6:00 A.M. on January 4, 1900 would be represented by the value 5.25 (5 and 1/4 of a day past December 30, 1899). |
| ErrorCode | `10` | 4 bytes; a 32-bit integer encoding error information Specification name: PtypErrorCode; Alternate names: PT_ERROR; |
| Boolean | `11` | 1 byte; restricted to 1 or 0 Specification name: PtypBoolean; Alternate names: PT_BOOLEAN. bool; |
| Integer64 | `20` | 8 bytes; a 64-bit integer Specification name: PtypInteger64; Alternate names: PT_LONGLONG, PT_I8, i8, ui8; |
| String | `31` | Variable size; a string of Unicode characters in UTF-16LE format encoding with terminating null character (0x0000). Specification name: PtypString; Alternate names: PT_UNICODE, string; |
| String8 | `30` | Variable size; a string of multibyte characters in externally specified encoding with terminating null character (single 0 byte). Specification name: PtypString8; Alternate names: PT_STRING8; |
| Time | `64` | 8 bytes; a 64-bit integer representing the number of 100-nanosecond intervals since January 1, 1601 Specification name: PtypTime; Alternate names: PT_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz; |
| Guid | `72` | 16 bytes; a GUID with Data1, Data2, and Data3 fields in little-endian format Specification name: PtypGuid; Alternate names: PT_CLSID, UUID; |
| ServerId | `251` | Variable size; a 16-bit COUNT field followed by a structure Specification name: PtypServerId; Alternate names: PT_SVREID; |
| Restriction | `253` | Variable size; a byte array representing one or more Restriction structures Specification name: PtypRestriction; Alternate names: PT_SRESTRICT; |
| RuleAction | `254` | Variable size; a 16-bit COUNT field followed by that many rule action structures Specification name: PtypRuleAction; Alternate names: PT_ACTIONS; |
| Binary | `258` | Variable size; a COUNT field followed by that many bytes. Specification name: PtypBinary; Alternate names: PT_BINARY; |
| MultipleInteger16 | `4098` | Variable size; a COUNT field followed by that many PtypInteger16 values. Specification name: PtypMultipleInteger16; Alternate names: PT_MV_SHORT, PT_MV_I2, mv.i2; |
| MultipleInteger32 | `4099` | Variable size; a COUNT field followed by that many PtypInteger32 values. Specification name: PtypMultipleInteger32; Alternate names: PT_MV_LONG, PT_MV_I4, mv.i4; |
| MultipleFloating32 | `4100` | Variable size; a COUNT field followed by that many PtypFloating32 values. Specification name: PtypMultipleFloating32; Alternate names: PT_MV_FLOAT, PT_MV_R4, mv.float; |
| MultipleFloating64 | `4101` | Variable size; a COUNT field followed by that many PtypFloating64 values. Specification name: PtypMultipleFloating64; Alternate names: PT_MV_DOUBLE, PT_MV_R8; |
| MultipleCurrency | `4102` | Variable size; a COUNT field followed by that many PtypCurrency values. Specification name: PtypMultipleCurrency; Alternate names: PT_MV_CURRENCY, mv.fixed.14.4; |
| MultipleFloatingTime | `4103` | Variable size; a COUNT field followed by that many PtypFloatingTime values. Specification name: PtypMultipleFloatingTime; Alternate names: PT_MV_APPTIME; |
| MultipleBoolean | `4107` | Variable size; a COUNT field followed by that many PtypBoolean values. Specification name: PtypMultipleBoolean; Alternate names: PT_MV_BOOLEAN; |
| MultipleInteger64 | `4116` | Variable size; a COUNT field followed by that many PtypInteger64 values. Specification name: PtypMultipleInteger64; Alternate names: PT_MV_I8, PT_MV_LONGLONG; |
| MultipleString | `4127` | Variable size; a COUNT field followed by that many PtypString values. Specification name: PtypMultipleString; Alternate names: PT_MV_UNICODE; |
| MultipleString8 | `4126` | Variable size; a COUNT field followed by that many PtypString8 values. Specification name: PtypMultipleString8; Alternate names: PT_MV_STRING8, mv.string; |
| MultipleTime | `4160` | Variable size; a COUNT field followed by that many PtypTime values. Specification name: PtypMultipleTime; Alternate names: PT_MV_SYSTIME; |
| MultipleGuid | `4168` | Variable size; a COUNT field followed by that many PtypGuid values. Specification name: PtypMultipleGuid; Alternate names: PT_MV_CLSID, mv.uuid; |
| MultipleBinary | `4354` | Variable size; a COUNT field followed by that many PtypBinary values. Specification name: PtypMultipleBinary; Alternate names: PT_MV_BINARY, mv.bin.hex; |
| Object | `13` | The property value is a Component Object Model (COM) object. Specification name: PtypObject or PtypEmbeddedTable; Alternate names: PT_OBJECT; |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


