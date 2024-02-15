---
title: MapiMessage
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 550
url: /python-net/aspose.email.mapi/mapimessage/
---

## MapiMessage class

Represents an Outlook Message format document that can be parsed.

The MapiMessage type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MapiMessage()|Initializes a new instance of the [MapiMessage](/email/python-net/aspose.email.mapi/mapimessage/) class.|
|MapiMessage(format)|Initializes a new instance of the MapiMessage class|
|MapiMessage(from_address, to, subject, body, format)|Initializes a new instance of the MapiMessage class|
|MapiMessage(from_address, to, subject, body)|Initializes a new instance of the MapiMessage class|
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
|body_html|Gets the [body_rtf](/email/python-net/aspose.email.mapi/mapimessageitembase/) of the message converted to HTML, if present, otherwise an empty string.|
|companies|Contains the names of the companies that are associated with an item.|
|categories|Contains keywords or categories for the message object.|
|mileage|Contains the mileage information that is associated with an item.|
|billing|Contains the billing information associated with an item.|
|sensitivity|Gets the Sensitivity.|
|message_class|Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note.<br/>            The message class specifies the type, purpose, or content of the message.|
|supported_type|Gets the supported item type.|
|body|Gets the message text.|
|subject|Gets or sets the subject of the message.|
|is_signed|Gets a value indicating whether the message is signed.|
|is_encrypted|Gets a value indicating whether the message is encrypted.|
|reply_to|Gets or sets the reply to names.|
|normalized_subject|Gets normalized subject of the message.|
|display_to|Gets a list of the display names of the primary (To) message recipients, separated by semicolons (;).|
|display_name_prefix|Gets a prefix of the display name.|
|display_name|Gets the display name for the message.|
|display_cc|Gets a list of the display names of any carbon copy (CC) message recipients, separated by semicolons (;).|
|display_bcc|Gets a list of the display names of any blind carbon copy (BCC) message recipients, separated by semicolons (;).|
|sender_email_address|Gets or sets the message sender's e-mail address.|
|sender_smtp_address|Gets or sets the message sender's e-mail address.|
|sender_address_type|Gets the message sender's e-mail address type.|
|sender_name|Gets or sets the message sender's display name.|
|transport_message_headers|Gets the transport-specific message envelope information.|
|internet_message_id|Gets the message id of the message.|
|conversation_topic|Gets the topic of the first message in a conversation thread.|
|sent_representing_email_address|Gets or sets the e-mail address for the messaging user represented by the sender.|
|sent_representing_smtp_address|Gets or sets the e-mail address for the messaging user represented by the sender.|
|sent_representing_address_type|Gets the address type for the messaging user represented by the sender.|
|sent_representing_name|Gets or sets the display name for the messaging user represented by the sender.|
|client_submit_time|Gets or sets the date and time <br/>            the message sender submitted a message.|
|delivery_time|Gets or sets the date and time <br/>            a message was delivered.|
|headers|Gets the transport message headers|
|flags|Gets the message flags.|
|read_receipt_requested|Gets or sets a value indicating whether the read receipt is requested.|
|message_format|Gets the outlook message format.|
|is_template|Determines whether the message is Outlook template (.oft).|
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
|decrypt()|  |
|decrypt(certificate)|  |
|load(file_name)|  |
|load(stream)|  |
|load(stream, options)|  |
|load(file_name, options)|  |
|from_mail_message(file_name)|  |
|from_mail_message(stream)|  |
|from_mail_message(message)|  |
|from_mail_message(message, options)|  |
|load_from_tnef(stream)|  |
|load_from_tnef(file_name)|  |
|is_msg_format(file_name)|  |
|is_msg_format(stream)|  |
|add_custom_property(property, string_name_id)|  |
|add_custom_property(type, data, string_name_id)|  |
|save(file_name, options)|  |
|save(stream, options)|  |
|save(file_name)|  |
|save(stream)|  |
|save_as_tnef(stream)|  |
|save_as_tnef(file_name)|  |
|save_as_template(file_name)|  |
|save_as_template(stream)|  |
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
|remove_signature()|  |
|check_signature()|  |
|from_properties(properties)|  |
|remove_attachments(path)|  |
|destroy_attachments(path)|  |
|set_string_property_value(tag, value)|  |
|get_custom_properties()|  |
|to_mapi_message_item()|  |
|to_mail_message(options)|  |
|check_bounced()|  |
|clone()|  |

### See Also

* namespace [aspose.email.mapi](/email/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/email/python-net/)

