---
title: MapiTask
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 720
url: /python-net/aspose.email.mapi/mapitask/
---

## MapiTask class

Represents the Outlook Task object.

The MapiTask type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MapiTask()|Initializes a new instance of the [MapiTask](/email/python-net/aspose.email.mapi/mapitask/) class.|
|MapiTask(subject, body, start_date, due_date)|Initializes a new instance of the MapiTask class|
## Properties
| Name | Description |
| :- | :- |
|properties|  |
|code_page|  |
|item_id|The item id, uses with a server|
|attachments|Gets the attachments collection.|
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
|percent_complete|Gets or sets the progress the user has made on a task.|
|actual_effort|Gets or sets the number of minutes that <br/>            the user actually spent working on a task.|
|estimated_effort|Gets or sets the number of minutes <br/>            that the user expects to work on a task.|
|due_date|Gets or sets the date by which the user expects work <br/>            on the task to be complete.|
|start_date|Gets or sets the date on which the user <br/>            expects work on the task to begin.|
|date_completed|Gets or sets the date when <br/>            the user completed work on the task.|
|last_update|Gets or sets the date and time of the most <br/>            recent change made to the Task object.|
|recurrence|Gets or sets the recurrence properties.|
|history|Gets or sets the type of change <br/>            that was last made to the Task object.|
|users|Gets or sets information about task users.|
|status|Gets or sets the status of the user's progress on the task.|
|mode|Gets or sets the assignment status of the Task object.|
|state|Gets or sets the current assignment <br/>            state of the Task object.|
|priority|Gets or sets the current Priority of the Task object.|
|acceptance_state|Gets or sets the acceptance state of the task.|
|flags|Gets the indication flags of the Task object.|
|reminder_time|Gets or sets the initial signal time for a reminder|
|reminder_set|Gets or sets a value indicating whether a reminder is set on the object|
|reminder_file_parameter|Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue.|
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
|save(stream, save_format)|  |
|save(file_path, save_format)|  |
|from_v_todo(file_path)|  |
|from_v_todo(file_path, detect_encoding)|  |
|from_v_todo(stream)|  |
|from_v_todo(stream, detect_encoding)|  |
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

* namespace [aspose.email.mapi](/email/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/email/python-net/)

