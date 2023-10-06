---
title: Class PropertyDescriptor
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.PropertyDescriptor class. Class contains property description information
type: docs
weight: 19060
url: /net/aspose.email.mapi/propertydescriptor/
---
## PropertyDescriptor class

Class contains property description information.

```csharp
public abstract class PropertyDescriptor : IEquatable<PropertyDescriptor>
```

## Properties

| Name | Description |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname/) { get; } | The name used to refer to the property in the documentation. The prefix of the canonical name identifies the basic characteristics of a property to the implementer. The canonical naming structure uses three categories that are denoted by the following prefixes to the canonical property name: * PidLid prefix: Properties identified by an unsigned 32-bit quantity along with a property set. * PidName prefix: Properties identified by a string name along with a property set. * PidTag prefix: Properties identified by an unsigned 16-bit quantity. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype/) { get; } | The property value type, as described in [MS-OXCDATA], that specifies the type of values allowed for the property. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype/) { get; } | Indicates if data type contains of multiple values |
| [Name](../../aspose.email.mapi/propertydescriptor/name/) { get; } | Gets string that, identifies a property. |
| static [Use8BitStringAsUnicode](../../aspose.email.mapi/propertydescriptor/use8bitstringasunicode/) { get; set; } | Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String |

## Methods

| Name | Description |
| --- | --- |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance/#getinstance_4)(MapiProperty) | Retrieves `PropertyDescriptor` object from MAPI property |
| static [Parse](../../aspose.email.mapi/propertydescriptor/parse/)(string) | Initializes a new instance of the `PropertyDescriptor` class |
| abstract [Equals](../../aspose.email.mapi/propertydescriptor/equals/#equals)(PropertyDescriptor) | Indicates whether the current object is equal to another object of the same type. |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance/#getinstance_3)(long) | Retrieves [`PidTagPropertyDescriptor`](../pidtagpropertydescriptor/) object |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance/#getinstance_2)(int, PropertyDataType) | Retrieves [`PidTagPropertyDescriptor`](../pidtagpropertydescriptor/) object |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance/#getinstance)(long, PropertyDataType, Guid) | Retrieves [`PidLidPropertyDescriptor`](../pidlidpropertydescriptor/) object |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance/#getinstance_1)(string, PropertyDataType, Guid) | Retrieves [`PidNamePropertyDescriptor`](../pidnamepropertydescriptor/) object |
| [operator ==](../../aspose.email.mapi/propertydescriptor/op_equality/) | Determines whether the specified objects are equal to each another. |
| [operator !=](../../aspose.email.mapi/propertydescriptor/op_inequality/) | Determines whether the specified objects are not equal to each another. |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


