---
title: MapiCalendar
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 140
url: /python-net/aspose.email.mapi/mapicalendar/
---

## MapiCalendar class

Represents the mapi calendar object

The MapiCalendar type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MapiCalendar()|Initializes a new instance of the [MapiCalendar](/email/python-net/aspose.email.mapi/mapicalendar/) class|
|MapiCalendar(location, summary, description, start_date, end_date)|Initializes a new instance of the MapiCalendar class|
|MapiCalendar(location, summary, description, start_date, end_date, organizer, attendees)|Initializes a new instance of the MapiCalendar class|
|MapiCalendar(location, summary, description, start_date, end_date, organizer, attendees)|Initializes a new instance of the MapiCalendar class|
## Properties
| Name | Description |
| :- | :- |
|properties|  |
|code_page|  |
|item_id|The item id, uses with a server|
|attachments|Gets the attachment collection.|
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
|organizer|Gets or sets the organizer.|
|reminder_delta|Gets or sets the interval, in minutes, between the time at which the reminder first becomes overdue and the start time of the Calendar object|
|reminder_set|Gets or sets a value indicating whether a reminder is set on the object|
|reminder_file_parameter|Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue.|
|appointment_counter_proposal|Gets or sets a value indicating whether a Meeting Response object is a counter proposal.|
|client_intent|Gets or sets the actions the user has taken on this Meeting object.|
|start_date_time_zone|Gets or sets time zone information that indicates the time zone of the StartDate property|
|end_date_time_zone|Gets or sets time zone information that indicates the time zone of the EndDate property|
|attendees|Gets or sets the attendees|
|recurrence|Gets or sets the recurrence properties|
|is_all_day|Gets or sets a value indicating whether the event is an all-day event|
|key_words|Gets or sets the categories of the calendar object|
|start_date|Gets or sets the start date and time of the event.<br/>            If the date is not set, default value for datetime is returned.|
|end_date|Gets or sets the end date and time of the event.<br/>            If the date is not set, default value for datetime is returned.|
|sequence|Gets or sets the sequence number|
|busy_status|Gets or sets the busy status|
|location|Gets or sets the location of the event|
|uid|Gets the unique identifier|
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
|save(file_path, save_options)|  |
|save(stream, save_options)|  |
|save(file_path)|  |
|save(file_path, save_format)|  |
|save(stream)|  |
|save(stream, save_format)|  |
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

