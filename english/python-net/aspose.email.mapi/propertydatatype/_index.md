---
title: PropertyDataType
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 1290
url: /python-net/aspose.email.mapi/propertydatatype/
---

## PropertyDataType enumeration

[MS-OXCDATA]: Data Structures

## Members
| Member name | Description |
| :- | :- |
|UNSPECIFIED|Any: this property type value matches any type; <br/>            a server MUST return the actual type in its response. <br/>            Servers MUST NOT return this type in response to a client request other than NspiGetIDsFromNames <br/>            or the RopGetPropertyIdsFromNames ROP request ([MS-OXCROPS] section 2.2.8.1).<br/>            Specification name: PtypUnspecified; Alternate names: PT_UNSPECIFIED;|
|NULL|None: This property is a placeholder. <br/>            Specification name: PtypNull; Alternate names: PT_NULL;|
|INTEGER16|2 bytes; a 16-bit integer <br/>            Specification name: PtypInteger16; Alternate names: PT_SHORT, PT_I2, i2, ui2;|
|INTEGER32|4 bytes; a 32-bit integer <br/>            Specification name: PtypInteger32; Alternate names: PT_LONG, PT_I4, int, ui4;|
|FLOATING32|4 bytes; a 32-bit floating point number<br/>            Specification name: PtypFloating32; Alternate names: PT_FLOAT, PT_R4, float, r4;|
|FLOATING64|8 bytes; a 64-bit floating point number <br/>            Specification name: PtypFloating64; Alternate names: PT_DOUBLE, PT_R8, r8;|
|CURRENCY|8 bytes; a 64-bit signed, <br/>            scaled integer representation of a decimal currency value, <br/>            with four places to the right of the decimal point<br/>            Specification name: PtypCurrency; Alternate names: PT_CURRENCY, fixed.14.4;|
|FLOATING_TIME|8 bytes; a 64-bit floating point number in which the whole number part represents the number of days since December 30, 1899, <br/>            and the fractional part represents the fraction of a day since midnight<br/>            Specification name: PtypFloatingTime; Alternate names: PT_APPTIME;<br/>            The date information is represented by whole-number increments, starting with December 30, 1899 midnight as time zero. <br/>            The time information is represented by the fraction of a day since the preceding midnight. <br/>            For example, 6:00 A.M. on January 4, 1900 would be represented by the value 5.25 (5 and 1/4 of a day past December 30, 1899).|
|ERROR_CODE|4 bytes; a 32-bit integer encoding error information <br/>            Specification name: PtypErrorCode; Alternate names: PT_ERROR;|
|BOOLEAN|1 byte; restricted to 1 or 0 <br/>            Specification name: PtypBoolean; Alternate names: PT_BOOLEAN. bool;|
|INTEGER64|8 bytes; a 64-bit integer  <br/>            Specification name: PtypInteger64; Alternate names: PT_LONGLONG, PT_I8, i8, ui8;|
|STRING|Variable size; a string of Unicode characters in UTF-16LE format encoding with terminating null character (0x0000).<br/>            Specification name: PtypString; Alternate names: PT_UNICODE, string;|
|STRING8|Variable size; a string of multibyte characters in externally specified encoding with terminating null character (single 0 byte).<br/>            Specification name: PtypString8; Alternate names: PT_STRING8;|
|TIME|8 bytes; a 64-bit integer representing the number of 100-nanosecond intervals since January 1, 1601 <br/>            Specification name: PtypTime; Alternate names: PT_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz;|
|GUID|16 bytes; a GUID with Data1, Data2, and Data3 fields in little-endian format <br/>            Specification name: PtypGuid; Alternate names: PT_CLSID, UUID;|
|SERVER_ID|Variable size; a 16-bit COUNT field followed by a structure <br/>            Specification name: PtypServerId; Alternate names: PT_SVREID;|
|RESTRICTION|Variable size; a byte array representing one or more Restriction structures <br/>            Specification name: PtypRestriction; Alternate names: PT_SRESTRICT;|
|RULE_ACTION|Variable size; a 16-bit COUNT field followed by that many rule action structures <br/>            Specification name: PtypRuleAction; Alternate names: PT_ACTIONS;|
|BINARY|Variable size; a COUNT field followed by that many bytes. <br/>            Specification name: PtypBinary; Alternate names: PT_BINARY;|
|MULTIPLE_INTEGER16|Variable size; a COUNT field followed by that many PtypInteger16 values. <br/>            Specification name: PtypMultipleInteger16; Alternate names: PT_MV_SHORT, PT_MV_I2, mv.i2;|
|MULTIPLE_INTEGER32|Variable size; a COUNT field followed by that many PtypInteger32 values. <br/>            Specification name: PtypMultipleInteger32; Alternate names: PT_MV_LONG, PT_MV_I4, mv.i4;|
|MULTIPLE_FLOATING32|Variable size; a COUNT field followed by that many PtypFloating32 values. <br/>            Specification name: PtypMultipleFloating32; Alternate names: PT_MV_FLOAT, PT_MV_R4, mv.float;|
|MULTIPLE_FLOATING64|Variable size; a COUNT field followed by that many PtypFloating64 values. <br/>            Specification name: PtypMultipleFloating64; Alternate names: PT_MV_DOUBLE, PT_MV_R8;|
|MULTIPLE_CURRENCY|Variable size; a COUNT field followed by that many PtypCurrency values. <br/>            Specification name: PtypMultipleCurrency; Alternate names: PT_MV_CURRENCY, mv.fixed.14.4;|
|MULTIPLE_FLOATING_TIME|Variable size; a COUNT field followed by that many PtypFloatingTime values. <br/>            Specification name: PtypMultipleFloatingTime; Alternate names: PT_MV_APPTIME;|
|MULTIPLE_BOOLEAN|Variable size; a COUNT field followed by that many PtypBoolean values. <br/>            Specification name: PtypMultipleBoolean; Alternate names: PT_MV_BOOLEAN;|
|MULTIPLE_INTEGER64|Variable size; a COUNT field followed by that many PtypInteger64 values. <br/>            Specification name: PtypMultipleInteger64; Alternate names: PT_MV_I8, PT_MV_LONGLONG;|
|MULTIPLE_STRING|Variable size; a COUNT field followed by that many PtypString values. <br/>            Specification name: PtypMultipleString; Alternate names: PT_MV_UNICODE;|
|MULTIPLE_STRING8|Variable size; a COUNT field followed by that many PtypString8 values. <br/>            Specification name: PtypMultipleString8; Alternate names: PT_MV_STRING8, mv.string;|
|MULTIPLE_TIME|Variable size; a COUNT field followed by that many PtypTime values. <br/>            Specification name: PtypMultipleTime; Alternate names: PT_MV_SYSTIME;|
|MULTIPLE_GUID|Variable size; a COUNT field followed by that many PtypGuid values. <br/>            Specification name: PtypMultipleGuid; Alternate names: PT_MV_CLSID, mv.uuid;|
|MULTIPLE_BINARY|Variable size; a COUNT field followed by that many PtypBinary values. <br/>            Specification name: PtypMultipleBinary; Alternate names: PT_MV_BINARY, mv.bin.hex;|
|OBJECT|The property value is a Component Object Model (COM) object. <br/>            Specification name: PtypObject or PtypEmbeddedTable; Alternate names: PT_OBJECT;|

### See Also

* namespace [aspose.email.mapi](/email/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/email/python-net/)

