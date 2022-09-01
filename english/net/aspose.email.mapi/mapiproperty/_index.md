---
title: MapiProperty
second_title: Aspose.Email for .NET API Reference
description: Represents the mapi property.
type: docs
weight: 18570
url: /net/aspose.email.mapi/mapiproperty/
---
## MapiProperty class

Represents the mapi property.

```csharp
public class MapiProperty
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiProperty](mapiproperty#constructor_2)(long) | Initializes a new instance of the MapiProperty class. |
| [MapiProperty](mapiproperty#constructor_3)(long, byte[]) | Initializes a new instance of the MapiProperty class. |
| [MapiProperty](mapiproperty#constructor_5)(long, IList&lt;object&gt;) | Initializes a new instance of the [`MapiProperty`](../mapiproperty) class. This overload is used to create a multiple valued property, PT_MV_*. |
| [MapiProperty](mapiproperty#constructor)(PidLidPropertyDescriptor, object) | Initializes a new instance of the MapiProperty class. |
| [MapiProperty](mapiproperty#constructor_1)(PidTagPropertyDescriptor, object) | Initializes a new instance of the MapiProperty class. |
| [MapiProperty](mapiproperty#constructor_4)(long, long, byte[]) | Initializes a new instance of the [`MapiProperty`](../mapiproperty) class. |
| [MapiProperty](mapiproperty#constructor_6)(string, long, long, byte[]) | Initializes a new instance of the MapiProperty class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data) { get; } | Gets the binary data. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype) { get; } | Gets the data type. |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor) { get; } | Gets descriptor of MAPI property |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier) { get; } | Gets the indifier. |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed) { get; } | Indicates whether the property is a named property. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned) { get; set; } | Indicates whether the binary data is signed. |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries) { get; } | Gets the MV entries list. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name) { get; } | Gets the name. |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname) { get; } | Gets the PropertyName. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag) { get; } | Gets the tag. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateMapiPropertyFromBytes](../../aspose.email.mapi/mapiproperty/createmapipropertyfrombytes)(long, byte[]) | Creates the mapi property from bytes. |
| static [CreateMapiPropertyFromDateTime](../../aspose.email.mapi/mapiproperty/createmapipropertyfromdatetime)(long, DateTime) | Creates the mapi property from date time. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong)(long, long) | Creates the mapi property from long. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong_1)(long, long, long) | Creates the mapi property from long. |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean)() | Gets the first bytes of the binary data as boolean. |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency)() | Gets the Currency as string using the specified code page. |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime)() | Gets the first bytes of the binary data as datetime. |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble)() | Gets the bytes of the binary data as double. |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat)() | Gets the bytes of the binary data as float. |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate)() | Gets the bytes of the binary data as DateTime. |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid)() | Gets the bytes of the binary data as Guid. |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32)() | Gets the first 4 bytes of the binary data as int32. |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong)() | Gets the first 8 bytes of the binary data as long. |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort)() | Gets the first 2 bytes of the binary data as short. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring)() | Gets the binary data as string. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring_1)(int) | Gets the binary data as string using the specified code page. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue)() | Gets value as object |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring)() | Returns a String that represents the current Object. |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
