---
title: Appointment
second_title: Aspose.Email for Java API Reference
description: Represents a calendar event such as a meeting or an appointment that can be read from and saved to iCalendar ICS or Outlook MSG or sent by email as a meeting request.
type: docs
weight: 33
url: /java/com.aspose.email/appointment/
---

**Inheritance:**
java.lang.Object
```
public class Appointment
```

Represents a calendar event, such as a meeting or an appointment, that can be read from and saved to iCalendar (ICS) or Outlook MSG, or sent by email as a meeting request.

Use \#load(String).load(String) to read an event from an .ics file or stream and \#save(String).save(String) to write it. To send a meeting request, add the view returned by \#requestApointment().requestApointment() to a [MailMessage](../../com.aspose.email/mailmessage), or call \#toMailMessage().toMailMessage().

This example demonstrates how to add a calendar to an E-Mail message.

```

 MailMessage msg = new MailMessage();

 //attendees for the event
 MailAddressCollection attendees = new MailAddressCollection();
 attendees.addMailAddress(new MailAddress("person1@domain.com"));
 attendees.addMailAddress(new MailAddress("person2@domain.com"));
 attendees.addMailAddress(new MailAddress("person3@domain.com"));

 //create appointment
 java.util.Date startDate = new java.util.GregorianCalendar(2006, java.util.Calendar.JULY, 17, 13, 0, 0).getTime();
 java.util.Date endDate = new java.util.GregorianCalendar(2006, java.util.Calendar.JULY, 17, 14, 0, 0).getTime();
 Appointment app = new Appointment("Room 112", startDate, endDate,
         new MailAddress("somebody@domain.com"), attendees);
 app.setSummary("Release Meeting");
 app.setDescription("Discuss for the next release");

 //add calendar to the message
 msg.addAlternateView(app.requestApointment());

 //send the email message
 SmtpClient smtp = new SmtpClient("smtp.server.com", 25, "user", "password");
 smtp.send(msg);
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)](#Appointment-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-) | Initializes a new instance of the [Appointment](../../com.aspose.email/appointment) class with the location, time, organizer and attendees of the event. |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-) | Initializes a new instance of the [Appointment](../../com.aspose.email/appointment) class with the location, summary, description, time, organizer and attendees of the event. |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-) | Initializes a new instance of the [Appointment](../../com.aspose.email/appointment) class with an explicit unique identifier. |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-com.aspose.email.RecurrencePattern-) | Initializes a new instance of the [Appointment](../../com.aspose.email/appointment) class for a recurring event. |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-com.aspose.email.RecurrencePattern-) | Initializes a new instance of the [Appointment](../../com.aspose.email/appointment) class for a recurring event with an explicit unique identifier. |
## Methods

| Method | Description |
| --- | --- |
| [cancelAppointment()](#cancelAppointment--) | Creates a cancellation of this meeting (iCalendar METHOD:CANCEL) to send to its attendees. |
| [cancelAppointment(int seqId)](#cancelAppointment-int-) | Creates a cancellation of this meeting (iCalendar METHOD:CANCEL) with the specified sequence number. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppointmentClass()](#getAppointmentClass--) | Specifies the access classification for the appointment. |
| [getAppointmentHtml()](#getAppointmentHtml--) | Returns the details of the appointment as HTML. |
| [getAppointmentText()](#getAppointmentText--) | Returns the details of the appointment as plain text. |
| [getAppointmentText(AppointmentFormattingOptions formattingOptions)](#getAppointmentText-com.aspose.email.AppointmentFormattingOptions-) | Returns the details of the appointment, formatted with the specified templates. |
| [getAttachments()](#getAttachments--) | Gets the files attached to the event. |
| [getAttendees()](#getAttendees--) | Gets the attendees of the event, except the optional ones, which are in \#getOptionalAttendees().getOptionalAttendees(). |
| [getClass()](#getClass--) |  |
| [getCreatedDate()](#getCreatedDate--) | Gets the date and time the event was created (the iCalendar CREATED property). |
| [getDateTimeStamp()](#getDateTimeStamp--) | Gets the date and time the iCalendar object was created (the iCalendar DTSTAMP property). |
| [getDescription()](#getDescription--) | Gets the plain-text description of the event. |
| [getEndDate()](#getEndDate--) | Gets the end date and time of the event. |
| [getEndTimeZone()](#getEndTimeZone--) | Gets the time zone of the end of the event. |
| [getFlags()](#getFlags--) | Gets the flags of the event, such as whether it lasts all day. |
| [getHtmlDescription()](#getHtmlDescription--) | Gets the HTML version of the description. |
| [getLastModifiedDate()](#getLastModifiedDate--) | Gets the date and time the event was last modified (the iCalendar LAST-MODIFIED property). |
| [getLocation()](#getLocation--) | Gets the location of the event. |
| [getMSProperties()](#getMSProperties--) | Gets the Microsoft-specific properties of the event (those whose names start with X-MICROSOFT), keyed by property name. |
| [getMethodType()](#getMethodType--) | Gets the iCalendar METHOD of the event, such as a request or a cancellation. |
| [getMicrosoftBusyStatus()](#getMicrosoftBusyStatus--) | Gets how the time of the event is shown in the calendar of the organizer, such as busy or free (the X-MICROSOFT-CDO-BUSYSTATUS property). |
| [getMicrosoftImportance()](#getMicrosoftImportance--) | Gets the importance of the event (the X-MICROSOFT-CDO-IMPORTANCE property). |
| [getMicrosoftIntendedStatus()](#getMicrosoftIntendedStatus--) | Gets how the organizer wants attendees to show the time of the meeting, such as busy or free (the X-MICROSOFT-CDO-INTENDEDSTATUS property). |
| [getOptionalAttendees()](#getOptionalAttendees--) | Gets the optional attendees of the event (those with ROLE=OPT-PARTICIPANT). |
| [getOrganizer()](#getOrganizer--) | Gets the organizer of the event. |
| [getProductId()](#getProductId--) | Gets the identifier of the product that created the event (the iCalendar PRODID property). |
| [getRecurrence()](#getRecurrence--) | Gets the recurrence pattern of the event, or  null  if it does not repeat. |
| [getReminders()](#getReminders--) | Gets the reminders (alarms) of the event. |
| [getSequenceId()](#getSequenceId--) | Gets the revision sequence number of the event (the iCalendar SEQUENCE property), as read from the source. |
| [getStartDate()](#getStartDate--) | Gets the start date and time of the event. |
| [getStartTimeZone()](#getStartTimeZone--) | Gets the time zone of the start of the event. |
| [getStatus()](#getStatus--) | Gets the status of the event, such as tentative or confirmed (the iCalendar STATUS property). |
| [getSummary()](#getSummary--) | Gets the summary (subject) of the event. |
| [getTransparency()](#getTransparency--) | Gets whether the event blocks time in free/busy searches (the iCalendar TRANSP property). |
| [getUniqueId()](#getUniqueId--) | Gets the unique identifier of the event (the iCalendar UID property). |
| [getVersion()](#getVersion--) | Gets the version of the calendar the event was read from: 2.0 for iCalendar (ICS), 1.0 for vCalendar (VCS). |
| [hashCode()](#hashCode--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads an appointment from a stream of iCalendar (ICS) data. |
| [load(InputStream stream, boolean applyLocalTimeZone)](#load-java.io.InputStream-boolean-) | Loads an appointment from a stream of iCalendar (ICS) data, optionally converting its times to the local time zone. |
| [load(InputStream stream, AppointmentLoadOptions options)](#load-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-) | Loads an appointment from a stream of iCalendar (ICS) data with the specified options. |
| [load(String filePath)](#load-java.lang.String-) | Loads an appointment from an iCalendar (ICS) file. |
| [load(String filePath, AppointmentLoadOptions options)](#load-java.lang.String-com.aspose.email.AppointmentLoadOptions-) | Loads an appointment from an iCalendar (ICS) file with the specified options. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [requestApointment()](#requestApointment--) | Creates a meeting request for this appointment, with the METHOD set in \#getMethodType().getMethodType() and sequence number 0. |
| [requestApointment(int seqId)](#requestApointment-int-) | Creates a meeting request for this appointment with the specified sequence number. |
| [requestApointmentByMethodType(int methodType)](#requestApointmentByMethodType-int-) | Creates a meeting request for this appointment with the specified iCalendar METHOD. |
| [resetTimeZone()](#resetTimeZone--) | Sets the start and end time zones of the event to the local time zone of the computer. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the appointment to a stream in iCalendar (ICS) format. |
| [save(OutputStream stream, AppointmentSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.AppointmentSaveOptions-) | Saves the appointment to a stream with the specified options. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves the appointment to a stream in the specified format, with default options. |
| [save(String filePath)](#save-java.lang.String-) | Saves the appointment to an iCalendar (ICS) file. |
| [save(String filePath, AppointmentSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.AppointmentSaveOptions-) | Saves the appointment to a file with the specified options. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves the appointment to a file in the specified format, with default options. |
| [setAppointmentClass(int value)](#setAppointmentClass-int-) | Specifies the access classification for the appointment. |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | Sets the attendees of the event, except the optional ones, which are in \#getOptionalAttendees().getOptionalAttendees(). |
| [setCreatedDate(Date value)](#setCreatedDate-java.util.Date-) | Sets the date and time the event was created (the iCalendar CREATED property). |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | Sets the date and time the iCalendar object was created (the iCalendar DTSTAMP property). |
| [setDescription(String value)](#setDescription-java.lang.String-) | Sets the plain-text description of the event. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Sets the end date and time of the event. |
| [setEndTimeZone(String value)](#setEndTimeZone-java.lang.String-) | Sets the time zone of the end of the event. |
| [setFlags(int value)](#setFlags-int-) | Sets the flags of the event, such as whether it lasts all day. |
| [setHtmlDescription(String value)](#setHtmlDescription-java.lang.String-) | Sets the HTML version of the description. |
| [setLastModifiedDate(Date value)](#setLastModifiedDate-java.util.Date-) | Sets the date and time the event was last modified (the iCalendar LAST-MODIFIED property). |
| [setLocation(String value)](#setLocation-java.lang.String-) | Sets the location of the event. |
| [setMethodType(int value)](#setMethodType-int-) | Sets the iCalendar METHOD of the event, such as a request or a cancellation. |
| [setMicrosoftBusyStatus(int value)](#setMicrosoftBusyStatus-int-) | Sets how the time of the event is shown in the calendar of the organizer, such as busy or free (the X-MICROSOFT-CDO-BUSYSTATUS property). |
| [setMicrosoftImportance(int value)](#setMicrosoftImportance-int-) | Sets the importance of the event (the X-MICROSOFT-CDO-IMPORTANCE property). |
| [setMicrosoftIntendedStatus(int value)](#setMicrosoftIntendedStatus-int-) | Sets how the organizer wants attendees to show the time of the meeting, such as busy or free (the X-MICROSOFT-CDO-INTENDEDSTATUS property). |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | Sets the organizer of the event. |
| [setProductId(String value)](#setProductId-java.lang.String-) | Sets the identifier of the product that created the event (the iCalendar PRODID property). |
| [setRecurrence(RecurrencePattern value)](#setRecurrence-com.aspose.email.RecurrencePattern-) | Sets the recurrence pattern of the event, or  null  if it does not repeat. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Sets the start date and time of the event. |
| [setStartTimeZone(String value)](#setStartTimeZone-java.lang.String-) | Sets the time zone of the start of the event. |
| [setStatus(int value)](#setStatus-int-) | Sets the status of the event, such as tentative or confirmed (the iCalendar STATUS property). |
| [setSummary(String value)](#setSummary-java.lang.String-) | Sets the summary (subject) of the event. |
| [setTimeZone(String tzName)](#setTimeZone-java.lang.String-) | Sets both the start and the end time zone of the event. |
| [setTransparency(int value)](#setTransparency-int-) | Sets whether the event blocks time in free/busy searches (the iCalendar TRANSP property). |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | Sets the unique identifier of the event (the iCalendar UID property). |
| [toMailMessage()](#toMailMessage--) | Creates an email message that carries this appointment as a meeting request. |
| [toMailMessage(int action)](#toMailMessage-int-) | Creates an email message that carries this appointment as a meeting request, update or cancellation. |
| [toMailMessage(int action, int seqId)](#toMailMessage-int-int-) | Creates an email message that carries this appointment as a meeting request, update or cancellation. |
| [toMapiMessage()](#toMapiMessage--) | Converts the appointment to an Outlook message, which can then be saved as an .msg file. |
| [toString()](#toString--) |  |
| [updateAppointment()](#updateAppointment--) | Creates an update of this meeting to send to its attendees. |
| [updateAppointment(int seqId)](#updateAppointment-int-) | Creates an update of this meeting with the specified sequence number. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees) {#Appointment-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-}
```
public Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)
```


Initializes a new instance of the [Appointment](../../com.aspose.email/appointment) class with the location, time, organizer and attendees of the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the event. |
| startDate | java.util.Date | The start date and time of the event. |
| endDate | java.util.Date | The end date and time of the event. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | The organizer of the event. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The attendees of the event. |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)
```


Initializes a new instance of the [Appointment](../../com.aspose.email/appointment) class with the location, summary, description, time, organizer and attendees of the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the event. |
| summary | java.lang.String | The summary (subject) of the event. |
| description | java.lang.String | The plain-text description of the event. |
| startDate | java.util.Date | The start date and time of the event. |
| endDate | java.util.Date | The end date and time of the event. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | The organizer of the event. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The attendees of the event. |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid)
```


Initializes a new instance of the [Appointment](../../com.aspose.email/appointment) class with an explicit unique identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the event. |
| summary | java.lang.String | The summary (subject) of the event. |
| description | java.lang.String | The plain-text description of the event. |
| startDate | java.util.Date | The start date and time of the event. |
| endDate | java.util.Date | The end date and time of the event. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | The organizer of the event. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The attendees of the event. |
| uid | java.lang.String | The unique identifier of the event (the iCalendar UID property). |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-com.aspose.email.RecurrencePattern-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern)
```


Initializes a new instance of the [Appointment](../../com.aspose.email/appointment) class for a recurring event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the event. |
| summary | java.lang.String | The summary (subject) of the event. |
| description | java.lang.String | The plain-text description of the event. |
| startDate | java.util.Date | The start date and time of the event. |
| endDate | java.util.Date | The end date and time of the event. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | The organizer of the event. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The attendees of the event. |
| recurrencePattern | [RecurrencePattern](../../com.aspose.email/recurrencepattern) | The recurrence pattern of the event, or  null  for a single occurrence. |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-com.aspose.email.RecurrencePattern-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern)
```


Initializes a new instance of the [Appointment](../../com.aspose.email/appointment) class for a recurring event with an explicit unique identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the event. |
| summary | java.lang.String | The summary (subject) of the event. |
| description | java.lang.String | The plain-text description of the event. |
| startDate | java.util.Date | The start date and time of the event. |
| endDate | java.util.Date | The end date and time of the event. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | The organizer of the event. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The attendees of the event. |
| uid | java.lang.String | The unique identifier of the event (the iCalendar UID property). |
| recurrencePattern | [RecurrencePattern](../../com.aspose.email/recurrencepattern) | The recurrence pattern of the event, or  null  for a single occurrence. |

### cancelAppointment() {#cancelAppointment--}
```
public final AlternateView cancelAppointment()
```


Creates a cancellation of this meeting (iCalendar METHOD:CANCEL) to send to its attendees.

The cancellation gets sequence number 2. Use the overload with a sequence number to set it explicitly.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An [AlternateView](../../com.aspose.email/alternateview) with the iCalendar data (text/calendar) to add to a [MailMessage](../../com.aspose.email/mailmessage).
### cancelAppointment(int seqId) {#cancelAppointment-int-}
```
public final AlternateView cancelAppointment(int seqId)
```


Creates a cancellation of this meeting (iCalendar METHOD:CANCEL) with the specified sequence number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seqId | int | The sequence number to write (the iCalendar SEQUENCE property). |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An [AlternateView](../../com.aspose.email/alternateview) with the iCalendar data (text/calendar) to add to a [MailMessage](../../com.aspose.email/mailmessage).
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAppointmentClass() {#getAppointmentClass--}
```
public final int getAppointmentClass()
```


Specifies the access classification for the appointment.

**Returns:**
int
### getAppointmentHtml() {#getAppointmentHtml--}
```
public final String getAppointmentHtml()
```


Returns the details of the appointment as HTML.

**Returns:**
java.lang.String - \#getHtmlDescription().getHtmlDescription() if it is set; otherwise the title, organizer, start and end time, time zone, location and description, formatted with the templates of  AppointmentFormattingOptions.createAsHtml() .
### getAppointmentText() {#getAppointmentText--}
```
public final String getAppointmentText()
```


Returns the details of the appointment as plain text.

**Returns:**
java.lang.String - The title, organizer, start and end time, time zone, location and description of the appointment, formatted with the default plain-text templates.
### getAppointmentText(AppointmentFormattingOptions formattingOptions) {#getAppointmentText-com.aspose.email.AppointmentFormattingOptions-}
```
public final String getAppointmentText(AppointmentFormattingOptions formattingOptions)
```


Returns the details of the appointment, formatted with the specified templates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattingOptions | [AppointmentFormattingOptions](../../com.aspose.email/appointmentformattingoptions) | The templates to format the details with. Use  AppointmentFormattingOptions.createAsHtml()  to get HTML. |

**Returns:**
java.lang.String - The title, organizer, start and end time, time zone, location and description of the appointment.
### getAttachments() {#getAttachments--}
```
public final AttachmentCollection getAttachments()
```


Gets the files attached to the event.

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getAttendees() {#getAttendees--}
```
public final MailAddressCollection getAttendees()
```


Gets the attendees of the event, except the optional ones, which are in \#getOptionalAttendees().getOptionalAttendees().

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreatedDate() {#getCreatedDate--}
```
public final Date getCreatedDate()
```


Gets the date and time the event was created (the iCalendar CREATED property).

**Returns:**
java.util.Date - The java.util.Date that represents creation date and time.
### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


Gets the date and time the iCalendar object was created (the iCalendar DTSTAMP property).

**Returns:**
java.util.Date
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets the plain-text description of the event.

**Returns:**
java.lang.String
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Gets the end date and time of the event.

**Returns:**
java.util.Date
### getEndTimeZone() {#getEndTimeZone--}
```
public final String getEndTimeZone()
```


Gets the time zone of the end of the event.

**Returns:**
java.lang.String
### getFlags() {#getFlags--}
```
public final int getFlags()
```


Gets the flags of the event, such as whether it lasts all day.

**Returns:**
int
### getHtmlDescription() {#getHtmlDescription--}
```
public final String getHtmlDescription()
```


Gets the HTML version of the description.

**Returns:**
java.lang.String
### getLastModifiedDate() {#getLastModifiedDate--}
```
public final Date getLastModifiedDate()
```


Gets the date and time the event was last modified (the iCalendar LAST-MODIFIED property).

**Returns:**
java.util.Date - The java.util.Date that represents modification date and time.
### getLocation() {#getLocation--}
```
public final String getLocation()
```


Gets the location of the event.

**Returns:**
java.lang.String
### getMSProperties() {#getMSProperties--}
```
public final System.Collections.Generic.Dictionary<String,String> getMSProperties()
```


Gets the Microsoft-specific properties of the event (those whose names start with X-MICROSOFT), keyed by property name.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String>
### getMethodType() {#getMethodType--}
```
public final int getMethodType()
```


Gets the iCalendar METHOD of the event, such as a request or a cancellation. The default for a new appointment is  AppointmentMethodType.Request .

**Returns:**
int
### getMicrosoftBusyStatus() {#getMicrosoftBusyStatus--}
```
public final int getMicrosoftBusyStatus()
```


Gets how the time of the event is shown in the calendar of the organizer, such as busy or free (the X-MICROSOFT-CDO-BUSYSTATUS property).

**Returns:**
int
### getMicrosoftImportance() {#getMicrosoftImportance--}
```
public final int getMicrosoftImportance()
```


Gets the importance of the event (the X-MICROSOFT-CDO-IMPORTANCE property).

**Returns:**
int
### getMicrosoftIntendedStatus() {#getMicrosoftIntendedStatus--}
```
public final int getMicrosoftIntendedStatus()
```


Gets how the organizer wants attendees to show the time of the meeting, such as busy or free (the X-MICROSOFT-CDO-INTENDEDSTATUS property).

**Returns:**
int
### getOptionalAttendees() {#getOptionalAttendees--}
```
public final MailAddressCollection getOptionalAttendees()
```


Gets the optional attendees of the event (those with ROLE=OPT-PARTICIPANT).

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection) - The address collection of optional attendees.
### getOrganizer() {#getOrganizer--}
```
public final MailAddress getOrganizer()
```


Gets the organizer of the event.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getProductId() {#getProductId--}
```
public final String getProductId()
```


Gets the identifier of the product that created the event (the iCalendar PRODID property).

**Returns:**
java.lang.String
### getRecurrence() {#getRecurrence--}
```
public final RecurrencePattern getRecurrence()
```


Gets the recurrence pattern of the event, or  null  if it does not repeat.

**Returns:**
[RecurrencePattern](../../com.aspose.email/recurrencepattern) - The recurrence pattern.
### getReminders() {#getReminders--}
```
public final AppointmentReminderCollection getReminders()
```


Gets the reminders (alarms) of the event.

**Returns:**
[AppointmentReminderCollection](../../com.aspose.email/appointmentremindercollection)
### getSequenceId() {#getSequenceId--}
```
public final String getSequenceId()
```


Gets the revision sequence number of the event (the iCalendar SEQUENCE property), as read from the source.

**Returns:**
java.lang.String - The sequence id.
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets the start date and time of the event.

**Returns:**
java.util.Date
### getStartTimeZone() {#getStartTimeZone--}
```
public final String getStartTimeZone()
```


Gets the time zone of the start of the event.

**Returns:**
java.lang.String
### getStatus() {#getStatus--}
```
public final int getStatus()
```


Gets the status of the event, such as tentative or confirmed (the iCalendar STATUS property). The default for a new appointment is  AppointmentStatus.Tentative .

**Returns:**
int
### getSummary() {#getSummary--}
```
public final String getSummary()
```


Gets the summary (subject) of the event.

**Returns:**
java.lang.String
### getTransparency() {#getTransparency--}
```
public final int getTransparency()
```


Gets whether the event blocks time in free/busy searches (the iCalendar TRANSP property). The default for a new appointment is  AppointmentTransparency.Opaque .

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Gets the unique identifier of the event (the iCalendar UID property). In Microsoft Exchange it corresponds to the PidLidGlobalObjectId MAPI property.

**Returns:**
java.lang.String - The unique id.
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Gets the version of the calendar the event was read from: 2.0 for iCalendar (ICS), 1.0 for vCalendar (VCS).

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Appointment load(InputStream stream)
```


Loads an appointment from a stream of iCalendar (ICS) data.

If there are several events, the first one is loaded. Use [CalendarReader](../../com.aspose.email/calendarreader) to read all of them, or set  AppointmentLoadOptions.setEventIndex(\\u2026)  to pick another one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read from. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - The appointment read from the stream.
### load(InputStream stream, boolean applyLocalTimeZone) {#load-java.io.InputStream-boolean-}
```
public static Appointment load(InputStream stream, boolean applyLocalTimeZone)
```


Loads an appointment from a stream of iCalendar (ICS) data, optionally converting its times to the local time zone.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read from. |
| applyLocalTimeZone | boolean |  true  to convert the start and end times to the local time zone of the computer. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - The appointment read from the stream.
### load(InputStream stream, AppointmentLoadOptions options) {#load-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-}
```
public static Appointment load(InputStream stream, AppointmentLoadOptions options)
```


Loads an appointment from a stream of iCalendar (ICS) data with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read from. |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Options that control loading, or  null  to use the defaults. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - The appointment read from the stream.
### load(String filePath) {#load-java.lang.String-}
```
public static Appointment load(String filePath)
```


Loads an appointment from an iCalendar (ICS) file.

If there are several events, the first one is loaded. Use [CalendarReader](../../com.aspose.email/calendarreader) to read all of them, or set  AppointmentLoadOptions.setEventIndex(\\u2026)  to pick another one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the ICS file. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - The appointment read from the file.
### load(String filePath, AppointmentLoadOptions options) {#load-java.lang.String-com.aspose.email.AppointmentLoadOptions-}
```
public static Appointment load(String filePath, AppointmentLoadOptions options)
```


Loads an appointment from an iCalendar (ICS) file with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the ICS file. |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Options that control loading, such as which event of the file to read. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - The appointment read from the file.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### requestApointment() {#requestApointment--}
```
public final AlternateView requestApointment()
```


Creates a meeting request for this appointment, with the METHOD set in \#getMethodType().getMethodType() and sequence number 0.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An [AlternateView](../../com.aspose.email/alternateview) with the iCalendar data (text/calendar) to add to a [MailMessage](../../com.aspose.email/mailmessage).
### requestApointment(int seqId) {#requestApointment-int-}
```
public final AlternateView requestApointment(int seqId)
```


Creates a meeting request for this appointment with the specified sequence number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seqId | int | The sequence number to write (the iCalendar SEQUENCE property). |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An [AlternateView](../../com.aspose.email/alternateview) with the iCalendar data (text/calendar) to add to a [MailMessage](../../com.aspose.email/mailmessage).
### requestApointmentByMethodType(int methodType) {#requestApointmentByMethodType-int-}
```
public final AlternateView requestApointmentByMethodType(int methodType)
```


Creates a meeting request for this appointment with the specified iCalendar METHOD.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| methodType | int | The iCalendar METHOD to use, such as  AppointmentMethodType.Request . |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An [AlternateView](../../com.aspose.email/alternateview) with the iCalendar data (text/calendar) to add to a [MailMessage](../../com.aspose.email/mailmessage).
### resetTimeZone() {#resetTimeZone--}
```
public final void resetTimeZone()
```


Sets the start and end time zones of the event to the local time zone of the computer.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves the appointment to a stream in iCalendar (ICS) format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### save(OutputStream stream, AppointmentSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.AppointmentSaveOptions-}
```
public final void save(OutputStream stream, AppointmentSaveOptions saveOptions)
```


Saves the appointment to a stream with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |
| saveOptions | [AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions) | The save options. Their type, [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) or [AppointmentMsgSaveOptions](../../com.aspose.email/appointmentmsgsaveoptions), selects the format. |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Saves the appointment to a stream in the specified format, with default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |
| saveFormat | int | The format to save in. |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Saves the appointment to an iCalendar (ICS) file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file to create. An existing file is overwritten. |

### save(String filePath, AppointmentSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.AppointmentSaveOptions-}
```
public final void save(String filePath, AppointmentSaveOptions saveOptions)
```


Saves the appointment to a file with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file to create. An existing file is overwritten. |
| saveOptions | [AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions) | The save options. Their type, [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) or [AppointmentMsgSaveOptions](../../com.aspose.email/appointmentmsgsaveoptions), selects the format. |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Saves the appointment to a file in the specified format, with default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file to create. An existing file is overwritten. |
| saveFormat | int | The format to save in. |

### setAppointmentClass(int value) {#setAppointmentClass-int-}
```
public final void setAppointmentClass(int value)
```


Specifies the access classification for the appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setAttendees(MailAddressCollection value) {#setAttendees-com.aspose.email.MailAddressCollection-}
```
public final void setAttendees(MailAddressCollection value)
```


Sets the attendees of the event, except the optional ones, which are in \#getOptionalAttendees().getOptionalAttendees().

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setCreatedDate(Date value) {#setCreatedDate-java.util.Date-}
```
public final void setCreatedDate(Date value)
```


Sets the date and time the event was created (the iCalendar CREATED property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The java.util.Date that represents creation date and time. |

### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


Sets the date and time the iCalendar object was created (the iCalendar DTSTAMP property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Sets the plain-text description of the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Sets the end date and time of the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setEndTimeZone(String value) {#setEndTimeZone-java.lang.String-}
```
public final void setEndTimeZone(String value)
```


Sets the time zone of the end of the event.

Accepts an IANA time zone name, such as  America/New\_York , or a Windows time zone ID, such as  Eastern Standard Time .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFlags(int value) {#setFlags-int-}
```
public final void setFlags(int value)
```


Sets the flags of the event, such as whether it lasts all day.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHtmlDescription(String value) {#setHtmlDescription-java.lang.String-}
```
public final void setHtmlDescription(String value)
```


Sets the HTML version of the description.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLastModifiedDate(Date value) {#setLastModifiedDate-java.util.Date-}
```
public final void setLastModifiedDate(Date value)
```


Sets the date and time the event was last modified (the iCalendar LAST-MODIFIED property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The java.util.Date that represents modification date and time. |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Sets the location of the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMethodType(int value) {#setMethodType-int-}
```
public final void setMethodType(int value)
```


Sets the iCalendar METHOD of the event, such as a request or a cancellation. The default for a new appointment is  AppointmentMethodType.Request .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMicrosoftBusyStatus(int value) {#setMicrosoftBusyStatus-int-}
```
public final void setMicrosoftBusyStatus(int value)
```


Sets how the time of the event is shown in the calendar of the organizer, such as busy or free (the X-MICROSOFT-CDO-BUSYSTATUS property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMicrosoftImportance(int value) {#setMicrosoftImportance-int-}
```
public final void setMicrosoftImportance(int value)
```


Sets the importance of the event (the X-MICROSOFT-CDO-IMPORTANCE property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMicrosoftIntendedStatus(int value) {#setMicrosoftIntendedStatus-int-}
```
public final void setMicrosoftIntendedStatus(int value)
```


Sets how the organizer wants attendees to show the time of the meeting, such as busy or free (the X-MICROSOFT-CDO-INTENDEDSTATUS property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOrganizer(MailAddress value) {#setOrganizer-com.aspose.email.MailAddress-}
```
public final void setOrganizer(MailAddress value)
```


Sets the organizer of the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setProductId(String value) {#setProductId-java.lang.String-}
```
public final void setProductId(String value)
```


Sets the identifier of the product that created the event (the iCalendar PRODID property).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setRecurrence(RecurrencePattern value) {#setRecurrence-com.aspose.email.RecurrencePattern-}
```
public final void setRecurrence(RecurrencePattern value)
```


Sets the recurrence pattern of the event, or  null  if it does not repeat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RecurrencePattern](../../com.aspose.email/recurrencepattern) | The recurrence pattern. |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Sets the start date and time of the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartTimeZone(String value) {#setStartTimeZone-java.lang.String-}
```
public final void setStartTimeZone(String value)
```


Sets the time zone of the start of the event.

Accepts an IANA time zone name, such as  America/New\_York , or a Windows time zone ID, such as  Eastern Standard Time .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Sets the status of the event, such as tentative or confirmed (the iCalendar STATUS property). The default for a new appointment is  AppointmentStatus.Tentative .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSummary(String value) {#setSummary-java.lang.String-}
```
public final void setSummary(String value)
```


Sets the summary (subject) of the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTimeZone(String tzName) {#setTimeZone-java.lang.String-}
```
public final void setTimeZone(String tzName)
```


Sets both the start and the end time zone of the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tzName | java.lang.String | An IANA time zone name, such as  America/New\_York , or a Windows time zone ID, such as  Eastern Standard Time . |

### setTransparency(int value) {#setTransparency-int-}
```
public final void setTransparency(int value)
```


Sets whether the event blocks time in free/busy searches (the iCalendar TRANSP property). The default for a new appointment is  AppointmentTransparency.Opaque .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


Sets the unique identifier of the event (the iCalendar UID property). In Microsoft Exchange it corresponds to the PidLidGlobalObjectId MAPI property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The unique id. |

### toMailMessage() {#toMailMessage--}
```
public final MailMessage toMailMessage()
```


Creates an email message that carries this appointment as a meeting request.

The METHOD is taken from \#getMethodType().getMethodType(), or is REQUEST when that is  AppointmentMethodType.None ; the sequence number is 0.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) that carries the event as a text/calendar alternate view.
### toMailMessage(int action) {#toMailMessage-int-}
```
public final MailMessage toMailMessage(int action)
```


Creates an email message that carries this appointment as a meeting request, update or cancellation.

The sequence number is 0 for a request, 1 for an update and 2 for a cancellation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| action | int | Whether the message requests, updates or cancels the meeting (an [AppointmentAction](../../com.aspose.email/appointmentaction) value). |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) that carries the event as a text/calendar alternate view.
### toMailMessage(int action, int seqId) {#toMailMessage-int-int-}
```
public final MailMessage toMailMessage(int action, int seqId)
```


Creates an email message that carries this appointment as a meeting request, update or cancellation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| action | int | Whether the message requests, updates or cancels the meeting (an [AppointmentAction](../../com.aspose.email/appointmentaction) value). |
| seqId | int | The sequence number (the iCalendar SEQUENCE property): the revision of the event within a sequence of updates. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) that carries the event as a text/calendar alternate view.
### toMapiMessage() {#toMapiMessage--}
```
public final MapiMessage toMapiMessage()
```


Converts the appointment to an Outlook message, which can then be saved as an .msg file.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A [MapiMessage](../../com.aspose.email/mapimessage) that represents the appointment.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAppointment() {#updateAppointment--}
```
public final AlternateView updateAppointment()
```


Creates an update of this meeting to send to its attendees.

The update gets sequence number 1. Use the overload with a sequence number to set it explicitly.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An [AlternateView](../../com.aspose.email/alternateview) with the iCalendar data (text/calendar) to add to a [MailMessage](../../com.aspose.email/mailmessage).
### updateAppointment(int seqId) {#updateAppointment-int-}
```
public final AlternateView updateAppointment(int seqId)
```


Creates an update of this meeting with the specified sequence number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seqId | int | The sequence number to write (the iCalendar SEQUENCE property). |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An [AlternateView](../../com.aspose.email/alternateview) with the iCalendar data (text/calendar) to add to a [MailMessage](../../com.aspose.email/mailmessage).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

