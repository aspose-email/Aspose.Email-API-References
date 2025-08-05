---
title: Class MapiNamedProperty
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiNamedProperty class. Represents the data type of Named Property
type: docs
weight: 17250
url: /net/aspose.email.mapi/mapinamedproperty/
---
## MapiNamedProperty class

Represents the data type of Named Property.

```csharp
public sealed class MapiNamedProperty : MapiProperty
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiNamedProperty](mapinamedproperty/#constructor)() | Initializes a new instance of the `MapiNamedProperty` class. |
| [MapiNamedProperty](mapinamedproperty/#constructor_1)(INamedPropertyTagProvider, PidLidPropertyDescriptor, object) | Initializes a new instance of the `MapiNamedProperty` class. |
| [MapiNamedProperty](mapinamedproperty/#constructor_2)(INamedPropertyTagProvider, PidNamePropertyDescriptor, object) | Initializes a new instance of the `MapiNamedProperty` class. |
| [MapiNamedProperty](mapinamedproperty/#constructor_3)(long, long, Guid, byte[]) | Initializes a new instance of the `MapiNamedProperty` class. |
| [MapiNamedProperty](mapinamedproperty/#constructor_4)(long, string, Guid, byte[]) | Initializes a new instance of the `MapiNamedProperty` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data/) { get; } | Gets the binary data. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype/) { get; } | Gets the data type. |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor/) { get; } | Gets descriptor of MAPI property |
| [Guid](../../aspose.email.mapi/mapinamedproperty/guid/) { get; } | gets named property GUID |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier/) { get; } | Gets the indifier. |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed/) { get; } | Indicates whether the property is a named property. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned/) { get; set; } | Indicates whether the binary data is signed. |
| [Kind](../../aspose.email.mapi/mapinamedproperty/kind/) { get; } | gets named property kind |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries/) { get; } | Gets the MV entries list. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name/) { get; } | Gets the name. |
| [NameId](../../aspose.email.mapi/mapinamedproperty/nameid/) { get; } | gets named property ID |
| [Oom](../../aspose.email.mapi/mapinamedproperty/oom/) { get; } | gets OOM value |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname/) { get; } | Gets the PropertyName. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag/) { get; } | Gets the tag. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean/)() | Gets the first bytes of the binary data as boolean. |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency/)() | Gets the Currency as string using the specified code page. |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime/)() | Gets the first bytes of the binary data as datetime. |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble/)() | Gets the bytes of the binary data as double. |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat/)() | Gets the bytes of the binary data as float. |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate/)() | Gets the bytes of the binary data as DateTime. |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid/)() | Gets the bytes of the binary data as Guid. |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32/)() | Gets the first 4 bytes of the binary data as int32. |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong/)() | Gets the first 8 bytes of the binary data as long. |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort/)() | Gets the first 2 bytes of the binary data as short. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring/)() | Gets the binary data as string. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring/)(int) | Gets the binary data as string using the specified code page. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue/)() | Gets value as object |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring/)() | Returns a String that represents the current Object. |

### See Also

* class [MapiProperty](../mapiproperty/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


