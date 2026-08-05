---
title: "MapiPropertyType Enum"
linktitle: "MapiPropertyType"
articleTitle: "MapiPropertyType"
second_title: "Aspose.Email for C++"
description: "Represents the data type of MapiProperty data."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapipropertytype/
---

## MapiPropertyType enumeration (33 values)

Represents the data type of MapiProperty data.

| Value | Description |
| --- | --- |
| None | No values are set. |
| PT_SHORT | Signed 16-bit integer. This property type is the same as PT_SHORT and the OLE type VT_I2. |
| PT_LONG | Signed or unsigned 32-bit integer. This property type is the same as PT_I4 and the OLE type VT_I4. |
| PT_ERROR | SCODE value; 32-bit unsigned integer. This property type is the same as the OLE type VT_ERROR. |
| PT_BOOLEAN | 16-bit Boolean value where zero equals FALSE and non-zero equals TRUE. This property type is the same as the OLE type VT_BOOL. |
| PT_OBJECT | Pointer to an object that implements the IUnknown interface. This property type is similar to several OLE types such as VT_UNKNOWN. |
| PT_LONGLONG | Signed or unsigned 64-bit integer. This property type is the same as PT_I8 and the OLE type VT_I8. |
| PT_STRING8 | Null-terminated 8-bit character string. This property type is the same as the OLE type VT_LPSTR. |
| PT_UNICODE | PT_UNICODE |
| PT_SYSTIME | 64-bit integer data and time value in the form of a FILETIME structure. This property type is the same as the OLE type VT_FILETIME. |
| PT_CLSID | CLSID structure value. This property type is the same as the OLE type VT_CLSID. |
| PT_SRESTRICTION | PT_SRESTRICTION |
| PT_ACTIONS | PT_ACTIONS |
| PT_BINARY | SBinary structure value, a counted byte array. |
| PT_MV_xxx | PT_MV_xxx |
| PT_MV_STRING8 | A count field followed by that many PT_STRING8 values. |
| PT_MV_UNICODE | A count field followed by that many PT_UNICODE values. |
| PT_MV_BINARY | A count field followed by that many PT_BINARY values. |
| PT_DOUBLE | A 64-bit floating point number. |
| PT_FLOAT | A 32-bit floating point number. |
| PT_MV_FLOAT | A count field followed by that many PT_FLOAT values. |
| PT_MV_DOUBLE | A count field followed by that many PT_DOUBLE values. |
| PT_MV_CURRENCY | A count field followed by that many PT_CURRENCY values. |
| PT_MV_APPTIME | A count field followed by that many PtypFloatingTime values. |
| PT_MV_LONGLONG | A count field followed by that many PT_LONGLONG values. |
| PT_MV_CLSID | A count field followed by that many PT_CLSID values. |
| PT_MV_SHORT | A count field followed by that many PT_SHORT values. |
| PT_MV_SYSTIME | A count field followed by that many PT_SYSTIME values. |
| PT_MV_BOOLEAN | A count field followed by that many PT_BOOLEAN values. |
| PT_SVREID | Variable size, a 16-bit (2-byte) count followed by a structure. |
| PT_UNSPECIFIED | Indicates that the property type is unknown. |
| PT_NULL | Indicates no property value. |
| PT_MV_LONG | A count field followed by that many PT_LONG values. |

