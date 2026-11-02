---
title: Class PropertyDescriptor
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.PropertyDescriptor class. The base class of property descriptors the identity and data type of a MAPI property
type: docs
weight: 17860
url: /net/aspose.email.mapi/propertydescriptor/
---
## PropertyDescriptor class

The base class of property descriptors: the identity and data type of a MAPI property.

```csharp
public abstract class PropertyDescriptor : IEquatable<PropertyDescriptor>
```

## Properties

| Name | Description |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname/) { get; } | Gets the canonical name of the property, as in [MS-OXPROPS]. The prefix tells how the property is identified: `PidLid` by a numeric ID within a property set, `PidName` by a string name within a property set, `PidTag` by a fixed 16-bit ID. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype/) { get; } | Gets the data type of the property value. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype/) { get; } | Gets a value indicating whether the property is multi-valued. |
| [Name](../../aspose.email.mapi/propertydescriptor/name/) { get; } | Gets the alternate name of the property, such as `PR_SUBJECT`, or the name of a named property. |
| static [Use8BitStringAsUnicode](../../aspose.email.mapi/propertydescriptor/use8bitstringasunicode/) { get; set; } | Gets or sets a value indicating whether `String8` (ANSI) values are read as `String` (Unicode). The default is `true`. |

## Methods

| Name | Description |
| --- | --- |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance/#getinstance_4)(MapiProperty) | Gets the descriptor of a MAPI property. |
| static [Parse](../../aspose.email.mapi/propertydescriptor/parse/)(string) | Creates a descriptor from its string form, as returned by `ToString`, for example `Tag:'PidTagSubject':0x37:String`. |
| abstract [Equals](../../aspose.email.mapi/propertydescriptor/equals/#equals)(PropertyDescriptor) | Determines whether the specified descriptor describes the same property. |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance/#getinstance_3)(long) | Gets the descriptor of a tagged property by its tag. |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance/#getinstance_2)(int, PropertyDataType) | Gets the descriptor of a tagged property by its ID and data type. |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance/#getinstance)(long, PropertyDataType, Guid) | Gets the descriptor of a named property by its numeric ID (LID). |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance/#getinstance_1)(string, PropertyDataType, Guid) | Gets the descriptor of a named property by its name. |
| [operator ==](../../aspose.email.mapi/propertydescriptor/op_equality/) | Determines whether the specified objects are equal to each another. |
| [operator !=](../../aspose.email.mapi/propertydescriptor/op_inequality/) | Determines whether the specified objects are not equal to each another. |

## Remarks

Use [`PidTagPropertyDescriptor`](../pidtagpropertydescriptor/) for tagged properties, and [`PidLidPropertyDescriptor`](../pidlidpropertydescriptor/) or [`PidNamePropertyDescriptor`](../pidnamepropertydescriptor/) for named properties. Descriptors of the known properties are defined in [`KnownPropertyList`](../knownpropertylist/).

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


