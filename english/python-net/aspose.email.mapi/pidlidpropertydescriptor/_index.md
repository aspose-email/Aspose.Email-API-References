---
title: PidLidPropertyDescriptor
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 720
url: /email/python-net/aspose.email.mapi/pidlidpropertydescriptor/
---

## PidLidPropertyDescriptor class

Class contains property description information.

The PidLidPropertyDescriptor type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PidLidPropertyDescriptor(long_id, type, property_set)|Initializes a new instance of the PidLidPropertyDescriptor class|
|PidLidPropertyDescriptor(canonical_name, long_id, type, property_set)|Initializes a new instance of the PidLidPropertyDescriptor class|
|PidLidPropertyDescriptor(canonical_name, name, long_id, type, property_set)|Initializes a new instance of the PidLidPropertyDescriptor class|
## Properties
| Name | Description |
| :- | :- |
|use_8_bit_string_as_unicode|Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String|
|data_type|The property value type, as described in [MS-OXCDATA], that specifies the type of values allowed for the property.|
|multiple_values_data_type|Indicates if data type contains of multiple values|
|canonical_name|The name used to refer to the property in the documentation.<br/>            The prefix of the canonical name identifies the basic characteristics of a property to the implementer. <br/>            The canonical naming structure uses three categories that are denoted by the following prefixes to the canonical property name: <br/>            * PidLid prefix: Properties identified by an unsigned 32-bit quantity along with a property set. <br/>            * PidName prefix: Properties identified by a string name along with a property set.<br/>            * PidTag prefix: Properties identified by an unsigned 16-bit quantity.|
|name|Gets string that, identifies a property.|
|long_id|Gets an unsigned 32-bit quantity that, along with the property set, identifies a named property.|
|property_set|A GUID that identifies a group of properties with a similar purpose.|
## Methods
| Name | Description |
| :- | :- |
|get_instance(id, data_type)|Retrieves|
|get_instance(tag)|  |
|get_instance(lid, data_type, property_set)|  |
|get_instance(name, data_type, property_set)|Retrieves|
|get_instance(property)|Retrieves|
|parse(data)|Initializes a new instance of the|
|equals(other)|  |

### See Also

* namespace [aspose.email.mapi](/email/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/slides/python-net/)

