---
title: Class MapiNamedProperty
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiNamedProperty class. A named property a MAPI property identified by a property set GUID and a name or numeric ID rather than by a fixed tag
type: docs
weight: 17350
url: /net/aspose.email.mapi/mapinamedproperty/
---
## MapiNamedProperty class

A named property: a MAPI property identified by a property set GUID and a name or numeric ID rather than by a fixed tag.

```csharp
public sealed class MapiNamedProperty : MapiProperty
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiNamedProperty](mapinamedproperty/#constructor)() | Initializes a new instance of the `MapiNamedProperty` class. |
| [MapiNamedProperty](mapinamedproperty/#constructor_1)(INamedPropertyTagProvider, PidLidPropertyDescriptor, object) | Initializes a new instance of the `MapiNamedProperty` class from a descriptor of a property with a numeric ID. |
| [MapiNamedProperty](mapinamedproperty/#constructor_2)(INamedPropertyTagProvider, PidNamePropertyDescriptor, object) | Initializes a new instance of the `MapiNamedProperty` class from a descriptor of a property with a string name. |
| [MapiNamedProperty](mapinamedproperty/#constructor_3)(long, long, Guid, byte[]) | Initializes a new instance of the `MapiNamedProperty` class for a property identified by a numeric ID. |
| [MapiNamedProperty](mapinamedproperty/#constructor_4)(long, string, Guid, byte[]) | Initializes a new instance of the `MapiNamedProperty` class for a property identified by a string name. |

## Properties

| Name | Description |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data/) { get; } | Gets the value of the property as bytes. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype/) { get; } | Gets the data type of the property: the low-order 16 bits of [`Tag`](../mapiproperty/tag/). |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor/) { get; } | Gets the descriptor of the property. |
| [Guid](../../aspose.email.mapi/mapinamedproperty/guid/) { get; } | Gets the GUID of the property set the property belongs to. |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier/) { get; } | Gets the property ID: the high-order 16 bits of [`Tag`](../mapiproperty/tag/). |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed/) { get; } | Gets a value indicating whether the property is a named property. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned/) { get; set; } | Gets or sets a value indicating whether the value is a signed number. |
| [Kind](../../aspose.email.mapi/mapinamedproperty/kind/) { get; } | Gets how the property is identified within its property set: 0 by a numeric ID, 1 by a string name. |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries/) { get; } | Gets the values of a multi-valued property. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name/) { get; } | Gets the name of the property. |
| [NameId](../../aspose.email.mapi/mapinamedproperty/nameid/) { get; } | Gets the name of the property, or its numeric ID in hexadecimal when [`Kind`](./kind/) is 0. |
| [Oom](../../aspose.email.mapi/mapinamedproperty/oom/) { get; } | Gets the name of the property in the Outlook Object Model, if it has one; otherwise an empty string. |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname/) { get; } | Gets the name of the tag of the property, such as `PR_SUBJECT`, if it is known. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag/) { get; } | Gets the tag of the property: the property ID in the high-order 16 bits and the data type in the low-order 16 bits. |

## Methods

| Name | Description |
| --- | --- |
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
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring/)() | Gets the value as a string. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring/)(int) | Gets the value as a string, decoding an ANSI string with the specified code page. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue/)() | Gets the value as an object of the .NET type that matches the data type. |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring/)() | Returns a string that represents the property. |

## Remarks

Inside a message a named property is stored under a tag that the message assigns. Read the identity of the property with [`Guid`](./guid/), [`Kind`](./kind/) and [`NameId`](./nameid/).

### See Also

* class [MapiProperty](../mapiproperty/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


