---
title: Class PidLidPropertyDescriptor
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.PidLidPropertyDescriptor class. Describes a named property identified by a numeric ID LID within a property set
type: docs
weight: 17820
url: /net/aspose.email.mapi/pidlidpropertydescriptor/
---
## PidLidPropertyDescriptor class

Describes a named property identified by a numeric ID (LID) within a property set.

```csharp
public class PidLidPropertyDescriptor : PropertyDescriptor
```

## Constructors

| Name | Description |
| --- | --- |
| [PidLidPropertyDescriptor](pidlidpropertydescriptor/#constructor)(long, PropertyDataType, Guid) | Initializes a new instance of the `PidLidPropertyDescriptor` class. |
| [PidLidPropertyDescriptor](pidlidpropertydescriptor/#constructor_1)(string, long, PropertyDataType, Guid) | Initializes a new instance of the `PidLidPropertyDescriptor` class. |
| [PidLidPropertyDescriptor](pidlidpropertydescriptor/#constructor_2)(string, string, long, PropertyDataType, Guid) | Initializes a new instance of the `PidLidPropertyDescriptor` class. |

## Properties

| Name | Description |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname/) { get; } | Gets the canonical name of the property, as in [MS-OXPROPS]. The prefix tells how the property is identified: `PidLid` by a numeric ID within a property set, `PidName` by a string name within a property set, `PidTag` by a fixed 16-bit ID. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype/) { get; } | Gets the data type of the property value. |
| [LongId](../../aspose.email.mapi/pidlidpropertydescriptor/longid/) { get; } | Gets the numeric ID (LID) of the property within its property set. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype/) { get; } | Gets a value indicating whether the property is multi-valued. |
| [Name](../../aspose.email.mapi/propertydescriptor/name/) { get; } | Gets the alternate name of the property, such as `PR_SUBJECT`, or the name of a named property. |
| [PropertySet](../../aspose.email.mapi/pidlidpropertydescriptor/propertyset/) { get; } | Gets the GUID of the property set the property belongs to. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidlidpropertydescriptor/equals/#equals_1)(object) | Determines whether the specified object is equal to this descriptor. |
| override [Equals](../../aspose.email.mapi/pidlidpropertydescriptor/equals/#equals)(PropertyDescriptor) | Determines whether the specified descriptor describes the same property. |
| override [GetHashCode](../../aspose.email.mapi/pidlidpropertydescriptor/gethashcode/)() | Returns the hash code of the descriptor. |
| override [ToString](../../aspose.email.mapi/pidlidpropertydescriptor/tostring/)() | Returns a string that describes the property, in the form that [`Parse`](../propertydescriptor/parse/) accepts. |
| [operator ==](../../aspose.email.mapi/pidlidpropertydescriptor/op_equality/) | Determines whether the specified objects are equal to each another. |
| [operator !=](../../aspose.email.mapi/pidlidpropertydescriptor/op_inequality/) | Determines whether the specified objects are not equal to each another. |

## Remarks

A named property has no fixed tag: it is identified by the GUID of its property set, such as `PSETID_Appointment`, and an ID within it. Pass the descriptor to [`SetProperty`](../mapipropertycontainer/setproperty/) or [`GetProperty`](../mapipropertycontainer/getproperty/) and the tag is resolved for you. For properties identified by a string name use [`PidNamePropertyDescriptor`](../pidnamepropertydescriptor/), for tagged properties [`PidTagPropertyDescriptor`](../pidtagpropertydescriptor/). Descriptors of the known properties are defined in [`KnownPropertyList`](../knownpropertylist/).

### See Also

* class [PropertyDescriptor](../propertydescriptor/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


