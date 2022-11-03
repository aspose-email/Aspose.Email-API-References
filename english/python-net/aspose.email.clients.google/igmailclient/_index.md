---
title: IGmailClient
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 190
url: /email/python-net/aspose.email.clients.google/igmailclient/
---

## IGmailClient class

Represents the interface for Gmail client

The IGmailClient type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|access_token|Gets or sets OAuth 2.0 bearer token|
|timeout|Gets or sets the number of milliseconds to wait before the operation times out.<br/>            The default value is 100,000 milliseconds (100 seconds).|
|default_email|Gets default email address|
## Methods
| Name | Description |
| :- | :- |
|list_calendars()|  |
|list_calendars(min_access_role, show_hidden)|  |
|create_calendar(calendar)|  |
|create_calendar(calendar, use_color_rgb_format)|  |
|update_calendar(calendar)|  |
|update_calendar(calendar, use_color_rgb_format)|  |
|move_appointment(source_calendar_id, destination_calendar_id, appointment_id)|  |
|move_appointment(source_calendar_id, destination_calendar_id, appointment_id, send_notifications)|  |
|get_contact(contact_uri)|  |
|get_contact(contact)|  |
|get_photo(photo)|  |
|get_photo(photo_uri)|  |
|create_contact(contact)|  |
|create_contact(contact, email_address)|  |
|fetch_calendar(calendar_id)|  |
|delete_calendar(calendar_id)|  |
|clear_calendar(calendar_id)|  |
|list_appointments(calendar_id)|  |
|list_appointment_instances(calendar_id, appointment_id)|  |
|create_appointment(calendar_id, appointment)|  |
|import_appointment(calendar_id, appointment)|  |
|fetch_appointment(calendar_id, appointment_id)|  |
|update_appointment(calendar_id, appointment)|  |
|delete_appointment(calendar_id, appointment_id)|  |
|create_access_rule(calendar_id, role)|  |
|update_access_rule(calendar_id, role)|  |
|fetch_access_rule(calendar_id, role_id)|  |
|delete_access_rule(calendar_id, role_id)|  |
|list_access_rules(calendar_id)|  |
|get_setting(setting)|  |
|get_freebusy_info(query)|  |
|get_colors()|  |
|get_all_groups()|  |
|get_contacts_from_group(group_id)|  |
|get_all_contacts()|  |
|update_contact(contact)|  |
|delete_contact(contact_uri)|  |
|delete_contact_photo(contact_photo)|  |
|update_contact_photo(contact_photo)|  |
|create_contact_photo(contact, image_data)|  |
|refresh_token()|  |

### See Also

* namespace [aspose.email.clients.google](/email/python-net/aspose.email.clients.google/)
* assembly [Aspose.Email](/slides/python-net/)

