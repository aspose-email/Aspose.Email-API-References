---
title: Class MapiProperty
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiProperty class. A MAPI property a value identified by a tag that holds the property ID and the data type
type: docs
weight: 17400
url: /net/aspose.email.mapi/mapiproperty/
---
## MapiProperty class

A MAPI property: a value identified by a tag that holds the property ID and the data type.

```csharp
public class MapiProperty
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiProperty](mapiproperty/#constructor_2)(long) | Initializes a new instance of the `MapiProperty` class without a value. |
| [MapiProperty](mapiproperty/#constructor_3)(long, byte[]) | Initializes a new instance of the `MapiProperty` class with a binary value. |
| [MapiProperty](mapiproperty/#constructor_5)(long, IList&lt;object&gt;) | Initializes a new instance of the `MapiProperty` class with several values, for a multi-valued (PT_MV_*) property. |
| [MapiProperty](mapiproperty/#constructor)(PidLidPropertyDescriptor, object) | Initializes a new instance of the `MapiProperty` class from a property descriptor. |
| [MapiProperty](mapiproperty/#constructor_1)(PidTagPropertyDescriptor, object) | Initializes a new instance of the `MapiProperty` class from a property descriptor. |
| [MapiProperty](mapiproperty/#constructor_4)(long, long, byte[]) | Initializes a new instance of the `MapiProperty` class with a binary value and a signed flag. |
| [MapiProperty](mapiproperty/#constructor_6)(string, long, long, byte[]) | Initializes a new instance of the `MapiProperty` class with a name, a binary value and a signed flag. |

## Properties

| Name | Description |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data/) { get; } | Gets the value of the property as bytes. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype/) { get; } | Gets the data type of the property: the low-order 16 bits of [`Tag`](./tag/). |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor/) { get; } | Gets the descriptor of the property. |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier/) { get; } | Gets the property ID: the high-order 16 bits of [`Tag`](./tag/). |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed/) { get; } | Gets a value indicating whether the property is a named property. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned/) { get; set; } | Gets or sets a value indicating whether the value is a signed number. |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries/) { get; } | Gets the values of a multi-valued property. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name/) { get; } | Gets the name of the property. |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname/) { get; } | Gets the name of the tag of the property, such as `PR_SUBJECT`, if it is known. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag/) { get; } | Gets the tag of the property: the property ID in the high-order 16 bits and the data type in the low-order 16 bits. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateMapiPropertyFromBytes](../../aspose.email.mapi/mapiproperty/createmapipropertyfrombytes/)(long, byte[]) | Creates a property with a binary value. |
| static [CreateMapiPropertyFromDateTime](../../aspose.email.mapi/mapiproperty/createmapipropertyfromdatetime/)(long, DateTime) | Creates a property with a date and time value. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong/#createmapipropertyfromlong)(long, long) | Creates a property with an integer value. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong/#createmapipropertyfromlong_1)(long, long, long) | Creates a property with an integer value and a signed flag. |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean/)() | Gets the value as a Boolean. |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency/)() | Gets the value of a currency property. |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime/)() | Gets the value of a date and time (PT_SYSTIME) property. |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble/)() | Gets the value as a 64-bit floating-point number. |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat/)() | Gets the value as a 32-bit floating-point number. |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate/)() | Gets the value of a floating date (PT_APPTIME) property: a number of days since December 30, 1899. |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid/)() | Gets the value as a GUID. |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32/)() | Gets the value as a 32-bit integer. |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong/)() | Gets the value as a 64-bit integer. |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort/)() | Gets the value as a 16-bit integer. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring/#getstring)() | Gets the value as a string. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring/#getstring_1)(int) | Gets the value as a string, decoding an ANSI string with the specified code page. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue/)() | Gets the value as an object of the .NET type that matches the data type. |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring/)() | Returns a string that represents the property. |

## Remarks

The value is kept as bytes in [`Data`](./data/). Read it with the typed getters, such as [`GetString`](./getstring/), [`GetInt32`](./getint32/) or [`GetDateTime`](./getdatetime/), or with [`GetValue`](./getvalue/), which returns an object of the matching .NET type.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


