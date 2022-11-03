---
title: Appointment
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 10
url: /email/python-net/aspose.email.calendar/appointment/
---

## Appointment class

Represents a calendar to an e-mail.

The Appointment type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Appointment(location, start_date, end_date, organizer, attendees)|Initializes a new instance of the Appointment class|
|Appointment(location, summary, description, start_date, end_date, organizer, attendees)|Initializes a new instance of the Appointment class|
|Appointment(location, summary, description, start_date, end_date, organizer, attendees, uid)|Initializes a new instance of the Appointment class|
|Appointment(location, summary, description, start_date, end_date, organizer, attendees, recurrence_pattern)|Initializes a new instance of the Appointment class|
|Appointment(location, summary, description, start_date, end_date, organizer, attendees, uid, recurrence_pattern)|Initializes a new instance of the Appointment class|
## Properties
| Name | Description |
| :- | :- |
|location|Gets or sets the location.|
|microsoft_importance|Specifies the importance of an appointment.|
|microsoft_busy_status|Specifies the BUSY status of an appointment.|
|microsoft_intended_status|Specifies the INTENDED status of an appointment.|
|transparency|Specifies whether or not this appointment is intended to be visible in availability searches.|
|status|Gets or sets the overall status or confirmation for the object.|
|summary|Gets or sets the summary.|
|description|Gets or sets the description.|
|html_description|Gets or sets html representation of description.|
|is_description_html|Gets or sets value which indicates if description is in HTML format|
|start_date|Gets or sets the start date.|
|end_date|Gets or sets the end date.|
|date_time_stamp|Gets or sets date/time that the instance of the iCalendar object was created..|
|created_date|Gets or sets the date and time that calendar information was created.|
|last_modified_date|Gets or sets the date and time that calendar information was last revised.|
|attendees|Gets or sets the attendees.|
|optional_attendees|Gets the optional attendees.|
|organizer|Gets or sets the organizer.|
|recurrence|Gets or sets the recurrence pattern.|
|sequence_id|Gets the sequence id.|
|flags|Gets or sets appointment flags.|
|method_type|Gets or sets the iCalendar object method type associated <br/>            with the calendar object.|
|reminders|Contains collection of AppointmentReminder|
|attachments|Gets the collection of attachments of appointment.|
|start_time_zone|Start time zone|
|end_time_zone|End time zone|
|unique_id|Gets or sets a string value that contains the GUID for the calendar item.<br/>            In MS Exchange this is PidLidGlobalObjectId mapi property.|
## Methods
| Name | Description |
| :- | :- |
|request_apointment()|  |
|request_apointment(seq_id)|  |
|cancel_appointment()|  |
|cancel_appointment(seq_id)|  |
|update_appointment()|  |
|update_appointment(seq_id)|  |
|get_appointment_text()|  |
|get_appointment_text(formatting_options)|  |
|save(file_path)|  |
|save(file_path, save_format)|  |
|save(file_path, save_options)|  |
|save(stream)|  |
|save(stream, save_format)|  |
|save(stream, save_options)|  |
|load(file_path)|Loads|
|load(file_path, options)|Loads|
|load(stream)|Loads|
|load(stream, apply_local_time_zone)|Loads|
|load(stream, options)|Loads|
|reset_time_zone()|  |
|set_time_zone(tz_name)|  |
|get_appointment_html()|  |

### See Also

* namespace [aspose.email.calendar](/email/python-net/aspose.email.calendar/)
* assembly [Aspose.Email](/slides/python-net/)

