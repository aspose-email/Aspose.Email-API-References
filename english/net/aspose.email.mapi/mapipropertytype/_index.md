---
title: Enum MapiPropertyType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiPropertyType enum. Defines the data types of MAPI properties the loworder 16 bits of a property tag
type: docs
weight: 17450
url: /net/aspose.email.mapi/mapipropertytype/
---
## MapiPropertyType enumeration

Defines the data types of MAPI properties: the low-order 16 bits of a property tag.

```csharp
public enum MapiPropertyType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | Not set. |
| PT_SHORT | `2` | A signed 16-bit integer. The same as `PT_I2` and the OLE type `VT_I2`. |
| PT_LONG | `3` | Signed or unsigned 32-bit integer. This property type is the same as PT_I4 and the OLE type VT_I4. |
| PT_ERROR | `10` | SCODE value; 32-bit unsigned integer. This property type is the same as the OLE type VT_ERROR. |
| PT_BOOLEAN | `11` | 16-bit Boolean value where zero equals FALSE and non-zero equals TRUE. This property type is the same as the OLE type VT_BOOL. |
| PT_OBJECT | `13` | Pointer to an object that implements the IUnknown interface. This property type is similar to several OLE types such as VT_UNKNOWN. |
| PT_LONGLONG | `20` | Signed or unsigned 64-bit integer. This property type is the same as PT_I8 and the OLE type VT_I8. |
| PT_STRING8 | `30` | Null-terminated 8-bit character string. This property type is the same as the OLE type VT_LPSTR. |
| PT_UNICODE | `31` | A null-terminated Unicode (UTF-16LE) string. |
| PT_SYSTIME | `64` | 64-bit integer data and time value in the form of a FILETIME structure. This property type is the same as the OLE type VT_FILETIME. |
| PT_CLSID | `72` | CLSID structure value. This property type is the same as the OLE type VT_CLSID. |
| PT_SRESTRICTION | `253` | A restriction: the criteria of a search. |
| PT_ACTIONS | `254` | The actions of a rule. |
| PT_BINARY | `258` | SBinary structure value, a counted byte array. |
| PT_MV_xxx | `4096` | The flag that makes any type multi-valued, combined with that type. |
| PT_MV_STRING8 | `4126` | A count field followed by that many PT_STRING8 values. |
| PT_MV_UNICODE | `4127` | A count field followed by that many PT_UNICODE values. |
| PT_MV_BINARY | `4354` | A count field followed by that many PT_BINARY values. |
| PT_DOUBLE | `5` | A 64-bit floating point number. |
| PT_FLOAT | `4` | A 32-bit floating point number. |
| PT_MV_FLOAT | `4100` | A count field followed by that many PT_FLOAT values. |
| PT_MV_DOUBLE | `4101` | A count field followed by that many PT_DOUBLE values. |
| PT_MV_CURRENCY | `4102` | A count field followed by that many PT_CURRENCY values. |
| PT_MV_APPTIME | `4103` | A count field followed by that many PtypFloatingTime values. |
| PT_MV_LONGLONG | `4116` | A count field followed by that many PT_LONGLONG values. |
| PT_MV_CLSID | `4168` | A count field followed by that many PT_CLSID values. |
| PT_MV_SHORT | `4098` | A count field followed by that many PT_SHORT values. |
| PT_MV_SYSTIME | `4160` | A count field followed by that many PT_SYSTIME values. |
| PT_MV_BOOLEAN | `4107` | A count field followed by that many PT_BOOLEAN values. |
| PT_SVREID | `251` | Variable size, a 16-bit (2-byte) count followed by a structure. |
| PT_UNSPECIFIED | `0` | Indicates that the property type is unknown. |
| PT_NULL | `1` | Indicates no property value. |
| PT_MV_LONG | `4099` | A count field followed by that many PT_LONG values. |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


