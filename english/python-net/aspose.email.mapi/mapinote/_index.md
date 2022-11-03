---
title: MapiNote
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 590
url: /email/python-net/aspose.email.mapi/mapinote/
---

## MapiNote class

Represents outlook Note object ("sticky note")

The MapiNote type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MapiNote()|Initializes a new instance of the|
|MapiNote(subject, body)|Initializes a new instance of the MapiNote class|
## Properties
| Name | Description |
| :- | :- |
|properties|  |
|code_page|  |
|item_id|The item id, uses with a server|
|attachments|Gets the attachments in the message.|
|property_stream|Gets the property stream.|
|named_properties|Gets the named properties of message.|
|recipients|Gets the recipients of the message.|
|sub_storages|Gets the sub storages.|
|named_property_mapping|Gets the named property mapping.|
|subject_prefix|Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding.|
|body_type|Gets the type of the body.|
|body_rtf|Gets or sets the RTF formatted message text.|
|body_html|Gets the|
|companies|Contains the names of the companies that are associated with an item.|
|categories|Contains keywords or categories for the message object.|
|mileage|Contains the mileage information that is associated with an item.|
|billing|Contains the billing information associated with an item.|
|sensitivity|Gets the Sensitivity.|
|message_class|Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note.<br/>            The message class specifies the type, purpose, or content of the message.|
|body|Gets the message text.|
|subject|Gets or sets the subject of the message.|
|creation_date|Gets or sets the creation date of note|
|color|Gets or sets the suggested background color of the Note object|
|width|Gets or sets width of the visible message window in pixels|
|height|Gets or sets height of the visible message window in pixels|
|x_position|Gets or sets the distance, in pixels, <br/>            from the left edge of the screen <br/>            that a user interface displays a Note object|
|y_position|Gets or sets the distance, in pixels, <br/>            from the top edge of the screen <br/>            that a user interface displays a Note object|
## Methods
| Name | Description |
| :- | :- |
|set_property(pd, value)|  |
|set_property(value)|  |
|try_get_property_string(tag, codepage)|  |
|try_get_property_string(tag)|  |
|try_get_property_string(tag, value, codepage)|  |
|try_get_property_string(tag, value)|  |
|get_property_string(tag, codepage)|  |
|get_property_string(tag)|  |
|set_body_content(content, content_type)|  |
|set_body_content(content, content_type, compression)|  |
|save(stream, save_format)|Saves this|
|save(file_path, save_format)|Saves this|
|get_property(pd)|  |
|try_get_property_data(tag)|  |
|get_property_bytes(tag)|  |
|get_property_int32(tag)|  |
|get_property_long(tag)|  |
|get_property_short(tag)|  |
|get_property_boolean(tag)|  |
|get_property_date_time(key)|  |
|is_store_unicode_ok()|  |
|try_get_property_date_time(tag, value)|  |
|try_get_property_long(tag, value)|  |
|try_get_property_int32(tag, value)|  |
|set_body_rtf(content, compression)|  |
|set_message_flags(flags)|  |
|remove_property(tag)|  |

### See Also

* namespace [aspose.email.mapi](/email/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/slides/python-net/)

