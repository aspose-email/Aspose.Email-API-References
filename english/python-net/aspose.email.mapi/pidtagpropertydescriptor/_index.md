---
title: PidTagPropertyDescriptor
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 780
url: /python-net/aspose.email.mapi/pidtagpropertydescriptor/
---

## PidTagPropertyDescriptor class

Class contains property description information.

The PidTagPropertyDescriptor type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PidTagPropertyDescriptor(id, type)|Initializes a new instance of the PidTagPropertyDescriptor class|
|PidTagPropertyDescriptor(canonical_name, id, type)|Initializes a new instance of the PidTagPropertyDescriptor class|
|PidTagPropertyDescriptor(canonical_name, name, id, type)|Initializes a new instance of the PidTagPropertyDescriptor class|
|PidTagPropertyDescriptor(tag)|Initializes a new instance of the PidTagPropertyDescriptor class|
|PidTagPropertyDescriptor(canonical_name, name, tag)|Initializes a new instance of the PidTagPropertyDescriptor class|
## Properties
| Name | Description |
| :- | :- |
|use_8_bit_string_as_unicode|Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String|
|data_type|The property value type, as described in [MS-OXCDATA], that specifies the type of values allowed for the property.|
|multiple_values_data_type|Indicates if data type contains of multiple values|
|canonical_name|The name used to refer to the property in the documentation.<br/>            The prefix of the canonical name identifies the basic characteristics of a property to the implementer. <br/>            The canonical naming structure uses three categories that are denoted by the following prefixes to the canonical property name: <br/>            * PidLid prefix: Properties identified by an unsigned 32-bit quantity along with a property set. <br/>            * PidName prefix: Properties identified by a string name along with a property set.<br/>            * PidTag prefix: Properties identified by an unsigned 16-bit quantity.|
|name|Gets string that, identifies a property.|
|id|Gets an unsigned 16-bit quantity that identifies a tagged property. <br/>            Property IDs are not necessarily unique. <br/>            With the exception of property IDs in the range from 0x6800 to 0x7BFF, <br/>            the combination of property ID and data type are unique. <br/>            Property IDs in the range from 0x6800 to 0x7BFF are defined by the message class.|
|tag|A property tag is a 32-bit number that contains a unique property identifier in bits 16 through 31 and a property type in bits 0 through 15.|
## Methods
| Name | Description |
| :- | :- |
|get_instance(id, data_type)|  |
|get_instance(tag)|  |
|get_instance(lid, data_type, property_set)|  |
|get_instance(name, data_type, property_set)|  |
|get_instance(property)|  |
|parse(data)|  |
|equals(other)|  |

### See Also

* namespace [aspose.email.mapi](/email/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/email/python-net/)

