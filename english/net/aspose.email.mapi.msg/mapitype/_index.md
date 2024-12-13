---
title: Enum MapiType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.Msg.MapiType enum. Contains possible MAPI property types which can be stored with message object
type: docs
weight: 18990
url: /net/aspose.email.mapi.msg/mapitype/
---
## MapiType enumeration

Contains possible MAPI property types which can be stored with message object.

```csharp
public enum MapiType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No values are set. |
| PT_SHORT | `2` | 2 bytes, a 16-bit integer |
| PT_LONG | `3` | 4 bytes, a 32-bit integer |
| PT_FLOAT | `4` | 4 bytes, a 32-bit floating point number |
| PT_DOUBLE | `5` | 8 bytes, a 64-bit floating point number |
| PT_CURRENCY | `6` | 8 bytes, a 64-bit signed, scaled integer representation of a decimal currency value, with 4 places to the right of the decimal point |
| PT_APPTIME | `7` | 8 bytes, a 64-bit floating point number in which the whole number part represents the number of days since December 30, 1899, and the fractional part represents the fraction of a day since midnight |
| PT_ERROR | `10` | 4 bytes, a 32-bit integer encoding error information |
| PT_BOOLEAN | `11` | 1 byte, restricted to 1 or 0 |
| PT_OBJECT | `13` | The property value is a COM object |
| PT_LONGLONG | `20` | 8 bytes, a 64-bit integer |
| PT_UNICODE | `31` | Variable size, a string of Unicode characters in UTF-16LE encoding with terminating null character(0x0000) |
| PT_STRING8 | `30` | Variable size, a string of multi-byte characters in externally specified encoding with terminating null character (single 0 byte). |
| PT_SYSTIME | `64` | 8 bytes, a 64-bit integer representing the number of 100-nanosecond intervals since January 1, 1601 |
| PT_CLSID | `72` | 16 bytes, a GUID with Data1, Data2, and Data3 fields in little-endian format |
| PT_BINARY | `258` | Variable size, a byte array |
| PT_MV_SHORT | `4098` | Variable size, a set of PT_SHORT values. |
| PT_MV_LONG | `4099` | Variable size, a set of PT_LONG values. |
| PT_MV_FLOAT | `4100` | Variable size, a set of PT_FLOAT values. |
| PT_MV_DOUBLE | `4101` | Variable size, a set of PT_DOUBLE values. |
| PT_MV_CURRENCY | `4102` | Variable size, a set of PT_CURRENCY values. |
| PT_MV_APPTIME | `4103` | Variable size, a set of PT_APPTIME values. |
| PT_MV_LONGLONG | `4116` | Variable size, a set of PT_LONGLONG values. |
| PT_MV_UNICODE | `4127` | Variable size, a set of PT_UNICODE values. |
| PT_MV_STRING8 | `4126` | Variable size, a set of PT_STRING8 values. |
| PT_MV_SYSTIME | `4160` | Variable size, a set of PT_SYSTIME values. |
| PT_MV_CLSID | `4168` | Variable size, a set of PT_CLSID values. |
| PT_MV_BINARY | `4354` | Variable size, a set of PT_BINARY values. |

### See Also

* namespace [Aspose.Email.Mapi.Msg](../../aspose.email.mapi.msg/)
* assembly [Aspose.Email](../../)


