---
title: MapiPropertyType
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 1120
url: /python-net/aspose.email.mapi/mapipropertytype/
---

## MapiPropertyType enumeration

Represents the data type of MapiProperty data.

## Members
| Member name | Description |
| :- | :- |
|NONE|No values are set.|
|SHORT|Signed 16-bit integer. This property type is the same as PT_SHORT and the OLE type VT_I2.|
|LONG|Signed or unsigned 32-bit integer. This property type is the same as PT_I4 and the OLE type VT_I4.|
|ERROR|SCODE value; 32-bit unsigned integer. This property type is the same as the OLE type VT_ERROR.|
|BOOLEAN|16-bit Boolean value where zero equals FALSE and non-zero equals TRUE. This property type is the same as the OLE type VT_BOOL.|
|OBJECT|Pointer to an object that implements the IUnknown interface. This property type is similar to several OLE types such as VT_UNKNOWN.|
|LONGLONG|Signed or unsigned 64-bit integer. This property type is the same as PT_I8 and the OLE type VT_I8.|
|STRING8|Null-terminated 8-bit character string. This property type is the same as the OLE type VT_LPSTR.|
|UNICODE|PT_UNICODE|
|SYSTIME|64-bit integer data and time value in the form of a FILETIME structure. This property type is the same as the OLE type VT_FILETIME.|
|CLSID|CLSID structure value. This property type is the same as the OLE type VT_CLSID.|
|SRESTRICTION|PT_SRESTRICTION|
|ACTIONS|PT_ACTIONS|
|BINARY|SBinary structure value, a counted byte array.|
|MV_XXX|PT_MV_xxx|
|MV_STRING8|A count field followed by that many PT_STRING8 values.|
|MV_UNICODE|A count field followed by that many PT_UNICODE values.|
|MV_BINARY|A count field followed by that many PT_BINARY values.|
|DOUBLE|A 64-bit floating point number.|
|FLOAT|A 32-bit floating point number.|
|MV_FLOAT|A count field followed by that many PT_FLOAT values.|
|MV_DOUBLE|A count field followed by that many PT_DOUBLE values.|
|MV_CURRENCY|A count field followed by that many PT_CURRENCY values.|
|MV_APPTIME|A count field followed by that many PtypFloatingTime values.|
|MV_LONGLONG|A count field followed by that many PT_LONGLONG values.|
|MV_CLSID|A count field followed by that many PT_CLSID values.|
|MV_SHORT|A count field followed by that many PT_SHORT values.|
|MV_SYSTIME|A count field followed by that many PT_SYSTIME values.|
|MV_BOOLEAN|A count field followed by that many PT_BOOLEAN values.|
|SVREID|Variable size, a 16-bit (2-byte) count followed by a structure.|
|UNSPECIFIED|Indicates that the property type is unknown.|
|NULL|Indicates no property value.|
|MV_LONG|A count field followed by that many PT_LONG values.|

### See Also

* namespace [aspose.email.mapi](/email/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/email/python-net/)

