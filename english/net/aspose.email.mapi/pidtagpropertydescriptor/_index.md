---
title: Class PidTagPropertyDescriptor
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.PidTagPropertyDescriptor class. Describes a tagged property a property with a fixed 16bit ID and a 16bit data type
type: docs
weight: 17840
url: /net/aspose.email.mapi/pidtagpropertydescriptor/
---
## PidTagPropertyDescriptor class

Describes a tagged property: a property with a fixed 16-bit ID and a 16-bit data type.

```csharp
public class PidTagPropertyDescriptor : PropertyDescriptor
```

## Constructors

| Name | Description |
| --- | --- |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor/#constructor_1)(long) | Initializes a new instance of the `PidTagPropertyDescriptor` class. |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor/#constructor)(int, PropertyDataType) | Initializes a new instance of the `PidTagPropertyDescriptor` class. |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor/#constructor_2)(string, int, PropertyDataType) | Initializes a new instance of the `PidTagPropertyDescriptor` class. |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor/#constructor_4)(string, string, long) | Initializes a new instance of the `PidTagPropertyDescriptor` class. |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor/#constructor_3)(string, string, int, PropertyDataType) | Initializes a new instance of the `PidTagPropertyDescriptor` class. |

## Properties

| Name | Description |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname/) { get; } | Gets the canonical name of the property, as in [MS-OXPROPS]. The prefix tells how the property is identified: `PidLid` by a numeric ID within a property set, `PidName` by a string name within a property set, `PidTag` by a fixed 16-bit ID. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype/) { get; } | Gets the data type of the property value. |
| [Id](../../aspose.email.mapi/pidtagpropertydescriptor/id/) { get; } | Gets the 16-bit ID of the property. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype/) { get; } | Gets a value indicating whether the property is multi-valued. |
| [Name](../../aspose.email.mapi/propertydescriptor/name/) { get; } | Gets the alternate name of the property, such as `PR_SUBJECT`, or the name of a named property. |
| [Tag](../../aspose.email.mapi/pidtagpropertydescriptor/tag/) { get; } | Gets the tag of the property: the ID in the high-order 16 bits and the data type in the low-order 16 bits. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals/#equals_1)(object) | Determines whether the specified object is equal to this descriptor. |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals/#equals)(PropertyDescriptor) | Determines whether the specified descriptor describes the same property. |
| override [GetHashCode](../../aspose.email.mapi/pidtagpropertydescriptor/gethashcode/)() | Returns the hash code of the descriptor. |
| override [ToString](../../aspose.email.mapi/pidtagpropertydescriptor/tostring/)() | Returns a string that describes the property, in the form that [`Parse`](../propertydescriptor/parse/) accepts. |
| [operator ==](../../aspose.email.mapi/pidtagpropertydescriptor/op_equality/) | Determines whether the specified objects are equal to each another. |
| [explicit operator](../../aspose.email.mapi/pidtagpropertydescriptor/op_explicit/) | Converts tag value to tagged property |
| [operator !=](../../aspose.email.mapi/pidtagpropertydescriptor/op_inequality/) | Determines whether the specified objects are not equal to each another. |

## Remarks

Tagged properties have IDs from `0x0001` to `0x7FFF`; IDs from `0x8000` up are assigned to named properties, which are described by [`PidLidPropertyDescriptor`](../pidlidpropertydescriptor/) and [`PidNamePropertyDescriptor`](../pidnamepropertydescriptor/). Descriptors of the known properties are defined in [`KnownPropertyList`](../knownpropertylist/).

### See Also

* class [PropertyDescriptor](../propertydescriptor/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


