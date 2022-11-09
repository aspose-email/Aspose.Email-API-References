---
title: MapiContact
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 320
url: /python-net/aspose.email.mapi/mapicontact/
---

## MapiContact class

Represents outlook contact information

The MapiContact type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MapiContact()|Initializes a new instance of the [MapiContact](/python-net/aspose.email.mapi/mapicontact/) class|
|MapiContact(display_name, electonic_address)|Initializes a new instance of the MapiContact class|
|MapiContact(display_name, electonic_address, company_name)|Initializes a new instance of the MapiContact class|
|MapiContact(display_name, electonic_address, company_name, primary_telephone_number)|Initializes a new instance of the MapiContact class|
## Properties
| Name | Description |
| :- | :- |
|properties|  |
|code_page|  |
|item_id|The item id, uses with a server|
|attachments|Gets the attachments in the contact.|
|property_stream|Gets the property stream.|
|named_properties|Gets the named properties of message.|
|recipients|Gets the recipients of the message.|
|sub_storages|Gets the sub storages.|
|named_property_mapping|Gets the named property mapping.|
|subject_prefix|Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding.|
|body_type|Gets the type of the body.|
|body_rtf|Gets or sets the RTF formatted message text.|
|body_html|Gets the [body_rtf](/python-net/aspose.email.mapi/mapimessageitembase/) of the message converted to HTML, if present, otherwise an empty string.|
|companies|Contains the names of the companies that are associated with an item.|
|categories|Contains keywords or categories for the message object.|
|mileage|Contains the mileage information that is associated with an item.|
|billing|Contains the billing information associated with an item.|
|sensitivity|Gets the Sensitivity.|
|message_class|Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note.<br/>            The message class specifies the type, purpose, or content of the message.|
|body|Gets the message text.|
|subject|Gets or sets the subject of the message.|
|name_info|The properties are used to specify the name <br/>            of the person represented by the contact|
|personal_info|Specify other additional contact information|
|professional_info|Properties are used to store professional <br/>            details for the person represented by the contact|
|telephones|Specify telephone numbers <br/>            for the contact|
|electronic_addresses|Specify properties for up to three different <br/>            e-mail addresses  <br/>            and three different fax addresses|
|physical_addresses|Specify three physical addresses: <br/>            Home Address, Work Address, and Other Address.<br/>            One of the addresses can be marked as the Mailing Address|
|events|Specify events associated with a contact|
|other_fields|Specify other fields of conhtact.|
|photo|Contains contact photo[MapiContactPhoto](/python-net/aspose.email.mapi/mapicontactphoto/).|
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
|from_v_card(file_path)|  |
|from_v_card(file_path, encoding)|  |
|from_v_card(stream)|  |
|from_v_card(stream, encoding)|  |
|save(file_path)|  |
|save(file_path, save_format)|  |
|save(file_path, save_options)|  |
|save(stream)|  |
|save(stream, save_format)|  |
|save(stream, save_options)|  |
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
|get_underlying_message()|  |

### See Also

* namespace [aspose.email.mapi](/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/python-net/)

