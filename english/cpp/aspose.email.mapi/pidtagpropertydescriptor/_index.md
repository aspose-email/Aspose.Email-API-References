---
title: "Aspose::Email::Mapi::PidTagPropertyDescriptor class"
linktitle: "PidTagPropertyDescriptor"
articleTitle: "PidTagPropertyDescriptor"
second_title: "Aspose.Email for C++"
description: "Class contains property description information."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/pidtagpropertydescriptor/
---

## PidTagPropertyDescriptor class

**Inherits:** Aspose::Email::Mapi::PropertyDescriptor

Class contains property description information.

## Constructors

| Name | Description |
| --- | --- |
| [PidTagPropertyDescriptor (5 overloads)](./pidtagpropertydescriptor/) | Initializes a new instance of the PidTagPropertyDescriptor class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 � 0x7FFF. Property IDs in the range 0x8000 � 0x8FFF are reserved for assignment to named properties |

## Methods

| Name | Description |
| --- | --- |
| [Equals (2 overloads)](./equals/) | Indicates whether the current object is equal to another object of the same type. |
| [get_Id](./get_id/) | Gets an unsigned 16-bit quantity that identifies a tagged property. Property IDs are not necessarily unique. With the exception of property IDs in the range from 0x6800 to 0x7BFF, the combination of property ID and data type are unique. Property IDs in the range from 0x6800 to 0x7BFF are defined by the message class. |
| [get_Tag](./get_tag/) | A property tag is a 32-bit number that contains a unique property identifier in bits 16 through 31 and a property type in bits 0 through 15. |
| [GetHashCode](./gethashcode/) | Serves as a hash function for a type. |
| [to_PidTagPropertyDescriptor](./to_pidtagpropertydescriptor/) | Converts tag value to tagged property |
| [ToString](./tostring/) | Returns a string that represents the property description. |
| [operator!=](./operator/) | Determines whether the specified objects are not equal to each another. |
| [operator==](./operator/) | Determines whether the specified objects are equal to each another. |

