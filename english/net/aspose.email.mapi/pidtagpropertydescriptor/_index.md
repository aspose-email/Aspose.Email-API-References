---
title: Class PidTagPropertyDescriptor
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.PidTagPropertyDescriptor class. Class contains property description information
type: docs
weight: 19100
url: /net/aspose.email.mapi/pidtagpropertydescriptor/
---
## PidTagPropertyDescriptor class

Class contains property description information.

```csharp
public class PidTagPropertyDescriptor : PropertyDescriptor
```

## Constructors

| Name | Description |
| --- | --- |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor/#constructor_1)(long) | Initializes a new instance of the `PidTagPropertyDescriptor` class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 � 0x7FFF. Property IDs in the range 0x8000 � 0x8FFF are reserved for assignment to named properties |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor/#constructor)(int, PropertyDataType) | Initializes a new instance of the `PidTagPropertyDescriptor` class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 � 0x7FFF. Property IDs in the range 0x8000 � 0x8FFF are reserved for assignment to named properties |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor/#constructor_2)(string, int, PropertyDataType) | Initializes a new instance of the `PidTagPropertyDescriptor` class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 � 0x7FFF. Property IDs in the range 0x8000 � 0x8FFF are reserved for assignment to named properties |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor/#constructor_4)(string, string, long) | Initializes a new instance of the `PidTagPropertyDescriptor` class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 � 0x7FFF. Property IDs in the range 0x8000 � 0x8FFF are reserved for assignment to named properties |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor/#constructor_3)(string, string, int, PropertyDataType) | Initializes a new instance of the `PidTagPropertyDescriptor` class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 � 0x7FFF. Property IDs in the range 0x8000 � 0x8FFF are reserved for assignment to named properties |

## Properties

| Name | Description |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname/) { get; } | The name used to refer to the property in the documentation. The prefix of the canonical name identifies the basic characteristics of a property to the implementer. The canonical naming structure uses three categories that are denoted by the following prefixes to the canonical property name: * PidLid prefix: Properties identified by an unsigned 32-bit quantity along with a property set. * PidName prefix: Properties identified by a string name along with a property set. * PidTag prefix: Properties identified by an unsigned 16-bit quantity. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype/) { get; } | The property value type, as described in [MS-OXCDATA], that specifies the type of values allowed for the property. |
| [Id](../../aspose.email.mapi/pidtagpropertydescriptor/id/) { get; } | Gets an unsigned 16-bit quantity that identifies a tagged property. Property IDs are not necessarily unique. With the exception of property IDs in the range from 0x6800 to 0x7BFF, the combination of property ID and data type are unique. Property IDs in the range from 0x6800 to 0x7BFF are defined by the message class. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype/) { get; } | Indicates if data type contains of multiple values |
| [Name](../../aspose.email.mapi/propertydescriptor/name/) { get; } | Gets string that, identifies a property. |
| [Tag](../../aspose.email.mapi/pidtagpropertydescriptor/tag/) { get; } | A property tag is a 32-bit number that contains a unique property identifier in bits 16 through 31 and a property type in bits 0 through 15. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals/#equals_1)(object) | Determines whether the specified System.Object is equal to the current System.Object. |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals/#equals)(PropertyDescriptor) | Indicates whether the current object is equal to another object of the same type. |
| override [GetHashCode](../../aspose.email.mapi/pidtagpropertydescriptor/gethashcode/)() | Serves as a hash function for a type. |
| override [ToString](../../aspose.email.mapi/pidtagpropertydescriptor/tostring/)() | Returns a string that represents the property description. |
| [operator ==](../../aspose.email.mapi/pidtagpropertydescriptor/op_equality/) | Determines whether the specified objects are equal to each another. |
| [explicit operator](../../aspose.email.mapi/pidtagpropertydescriptor/op_explicit/) | Converts tag value to tagged property |
| [operator !=](../../aspose.email.mapi/pidtagpropertydescriptor/op_inequality/) | Determines whether the specified objects are not equal to each another. |

### See Also

* class [PropertyDescriptor](../propertydescriptor/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


