---
title: Class PidNamePropertyDescriptor
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.PidNamePropertyDescriptor class. Describes a named property identified by a string name within a property set
type: docs
weight: 17830
url: /net/aspose.email.mapi/pidnamepropertydescriptor/
---
## PidNamePropertyDescriptor class

Describes a named property identified by a string name within a property set.

```csharp
public class PidNamePropertyDescriptor : PropertyDescriptor
```

## Constructors

| Name | Description |
| --- | --- |
| [PidNamePropertyDescriptor](pidnamepropertydescriptor/#constructor)(string, PropertyDataType, Guid) | Initializes a new instance of the `PidNamePropertyDescriptor` class. |
| [PidNamePropertyDescriptor](pidnamepropertydescriptor/#constructor_1)(string, string, PropertyDataType, Guid) | Initializes a new instance of the `PidNamePropertyDescriptor` class. |

## Properties

| Name | Description |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname/) { get; } | Gets the canonical name of the property, as in [MS-OXPROPS]. The prefix tells how the property is identified: `PidLid` by a numeric ID within a property set, `PidName` by a string name within a property set, `PidTag` by a fixed 16-bit ID. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype/) { get; } | Gets the data type of the property value. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype/) { get; } | Gets a value indicating whether the property is multi-valued. |
| [Name](../../aspose.email.mapi/propertydescriptor/name/) { get; } | Gets the alternate name of the property, such as `PR_SUBJECT`, or the name of a named property. |
| [PropertySet](../../aspose.email.mapi/pidnamepropertydescriptor/propertyset/) { get; } | Gets the GUID of the property set the property belongs to. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidnamepropertydescriptor/equals/#equals_1)(object) | Determines whether the specified object is equal to this descriptor. |
| override [Equals](../../aspose.email.mapi/pidnamepropertydescriptor/equals/#equals)(PropertyDescriptor) | Determines whether the specified descriptor describes the same property. |
| override [GetHashCode](../../aspose.email.mapi/pidnamepropertydescriptor/gethashcode/)() | Returns the hash code of the descriptor. |
| override [ToString](../../aspose.email.mapi/pidnamepropertydescriptor/tostring/)() | Returns a string that describes the property, in the form that [`Parse`](../propertydescriptor/parse/) accepts. |
| [operator ==](../../aspose.email.mapi/pidnamepropertydescriptor/op_equality/) | Determines whether the specified objects are equal to each another. |
| [operator !=](../../aspose.email.mapi/pidnamepropertydescriptor/op_inequality/) | Determines whether the specified objects are not equal to each another. |

## Remarks

A named property has no fixed tag: it is identified by the GUID of its property set, such as `PS_PUBLIC_STRINGS`, and its name. Custom properties are usually of this kind. Pass the descriptor to [`SetProperty`](../mapipropertycontainer/setproperty/) or [`GetProperty`](../mapipropertycontainer/getproperty/) and the tag is resolved for you; see the example of [`MapiPropertyContainer`](../mapipropertycontainer/). Descriptors of the known properties are defined in [`KnownPropertyList`](../knownpropertylist/).

### See Also

* class [PropertyDescriptor](../propertydescriptor/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


