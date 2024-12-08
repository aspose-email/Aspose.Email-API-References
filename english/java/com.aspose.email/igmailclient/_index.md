---
title: IGmailClient
second_title: Aspose.Email for Java API Reference
description: Represents the interface for Gmail client
type: docs
weight: 772
url: /java/com.aspose.email/igmailclient/
---

**All Implemented Interfaces:**
[com.aspose.email.IBaseGmailClient](../../com.aspose.email/ibasegmailclient)
```
public interface IGmailClient extends IBaseGmailClient
```

Represents the interface for Gmail client
## Methods

| Method | Description |
| --- | --- |
| [clearCalendar(String calendarId)](#clearCalendar-java.lang.String-) | Clears a calendar. |
| [createAccessRule(String calendarId, AccessControlRule role)](#createAccessRule-java.lang.String-com.aspose.email.AccessControlRule-) | Creates access rule |
| [createAppointment(String calendarId, Appointment appointment)](#createAppointment-java.lang.String-com.aspose.email.Appointment-) | Creates an appointment. |
| [createCalendar(Calendar calendar)](#createCalendar-com.aspose.email.Calendar-) | Creates a calendar. |
| [createCalendar(Calendar calendar, boolean useColorRgbFormat)](#createCalendar-com.aspose.email.Calendar-boolean-) | Creates a calendar. |
| [createContact(Contact contact)](#createContact-com.aspose.email.Contact-) | Creates contact for specified email |
| [createContact(Contact contact, String emailAddress)](#createContact-com.aspose.email.Contact-java.lang.String-) | Creates contact for specified email |
| [createContactPhoto(Contact contact, byte[] imageData)](#createContactPhoto-com.aspose.email.Contact-byte---) | Creates contact photo |
| [deleteAccessRule(String calendarId, String roleId)](#deleteAccessRule-java.lang.String-java.lang.String-) | Deletes access rule |
| [deleteAppointment(String calendarId, String appointmentId)](#deleteAppointment-java.lang.String-java.lang.String-) | Deletes an appointment. |
| [deleteCalendar(String calendarId)](#deleteCalendar-java.lang.String-) | Deletes a calendar. |
| [deleteContact(String contactUri)](#deleteContact-java.lang.String-) | Deletes specified contact |
| [deleteContactPhoto(ContactPhoto contactPhoto)](#deleteContactPhoto-com.aspose.email.ContactPhoto-) | Deletes contact photo |
| [fetchAccessRule(String calendarId, String roleId)](#fetchAccessRule-java.lang.String-java.lang.String-) | Fetches access rule |
| [fetchAppointment(String calendarId, String appointmentId)](#fetchAppointment-java.lang.String-java.lang.String-) | Fetches appointment by identifier. |
| [fetchCalendar(String calendarId)](#fetchCalendar-java.lang.String-) | Fetches calendar by identifier. |
| [getAllContacts()](#getAllContacts--) | Fetches all contacts. |
| [getAllGroups()](#getAllGroups--) | Fetches all contact groups. |
| [getColors()](#getColors--) | Gets color information |
| [getContact(Contact contact)](#getContact-com.aspose.email.Contact-) |  |
| [getContact(String contactUri)](#getContact-java.lang.String-) | Fetches contact |
| [getContactsFromGroup(String groupId)](#getContactsFromGroup-java.lang.String-) | Fetches contacts belonging to the group specified. |
| [getFreebusyInfo(FreebusyQuery query)](#getFreebusyInfo-com.aspose.email.FreebusyQuery-) | Gets free/busy information |
| [getPhoto(ContactPhoto photo)](#getPhoto-com.aspose.email.ContactPhoto-) | Fetches a contact photo |
| [getPhoto(String photoUri)](#getPhoto-java.lang.String-) | Fetches a contact photo |
| [getSetting(String setting)](#getSetting-java.lang.String-) | Gets settings by the name |
| [getSettings()](#getSettings--) | Gets settings dictionary |
| [importAppointment(String calendarId, Appointment appointment)](#importAppointment-java.lang.String-com.aspose.email.Appointment-) | Imports appointment to calendar |
| [listAccessRules(String calendarId)](#listAccessRules-java.lang.String-) | Gets list of access rules |
| [listAppointmentInstances(String calendarId, String appointmentId)](#listAppointmentInstances-java.lang.String-java.lang.String-) | Gets list of an appointment instances for calendar. |
| [listAppointments(String calendarId)](#listAppointments-java.lang.String-) | Gets list of an appointments for calendar. |
| [listCalendars()](#listCalendars--) | Gets array of calendars. |
| [listCalendars(int minAccessRole, boolean showHidden)](#listCalendars-int-boolean-) | Gets array of calendars. |
| [moveAppointment(String sourceCalendarId, String destinationCalendarId, String appointmentId)](#moveAppointment-java.lang.String-java.lang.String-java.lang.String-) | Moves an appointment to another calendar. |
| [moveAppointment(String sourceCalendarId, String destinationCalendarId, String appointmentId, boolean sendNotifications)](#moveAppointment-java.lang.String-java.lang.String-java.lang.String-boolean-) | Moves an appointment to another calendar. |
| [updateAccessRule(String calendarId, AccessControlRule role)](#updateAccessRule-java.lang.String-com.aspose.email.AccessControlRule-) | Updates access rule |
| [updateAppointment(String calendarId, Appointment appointment)](#updateAppointment-java.lang.String-com.aspose.email.Appointment-) | Updates an appointment. |
| [updateCalendar(Calendar calendar)](#updateCalendar-com.aspose.email.Calendar-) | Updates a calendar |
| [updateCalendar(Calendar calendar, boolean useColorRgbFormat)](#updateCalendar-com.aspose.email.Calendar-boolean-) | Updates a calendar |
| [updateContact(Contact contact)](#updateContact-com.aspose.email.Contact-) | Updates contact |
| [updateContactPhoto(ContactPhoto contactPhoto)](#updateContactPhoto-com.aspose.email.ContactPhoto-) | Creates or updates contact photo |
### clearCalendar(String calendarId) {#clearCalendar-java.lang.String-}
```
public abstract void clearCalendar(String calendarId)
```


Clears a calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |

### createAccessRule(String calendarId, AccessControlRule role) {#createAccessRule-java.lang.String-com.aspose.email.AccessControlRule-}
```
public abstract AccessControlRule createAccessRule(String calendarId, AccessControlRule role)
```


Creates access rule

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |
| role | [AccessControlRule](../../com.aspose.email/accesscontrolrule) | Access control rule |

**Returns:**
[AccessControlRule](../../com.aspose.email/accesscontrolrule) - Returns created access rule
### createAppointment(String calendarId, Appointment appointment) {#createAppointment-java.lang.String-com.aspose.email.Appointment-}
```
public abstract Appointment createAppointment(String calendarId, Appointment appointment)
```


Creates an appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |
| appointment | [Appointment](../../com.aspose.email/appointment) | An instance of appointment object to create. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - Returns the created appointment.
### createCalendar(Calendar calendar) {#createCalendar-com.aspose.email.Calendar-}
```
public abstract String createCalendar(Calendar calendar)
```


Creates a calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendar | [Calendar](../../com.aspose.email/calendar) | An instance of calendar object to create. |

**Returns:**
java.lang.String - Returns calendar identifier
### createCalendar(Calendar calendar, boolean useColorRgbFormat) {#createCalendar-com.aspose.email.Calendar-boolean-}
```
public abstract String createCalendar(Calendar calendar, boolean useColorRgbFormat)
```


Creates a calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendar | [Calendar](../../com.aspose.email/calendar) | An instance of calendar object to create. |
| useColorRgbFormat | boolean | Indicates whether color rgb format is used. |

**Returns:**
java.lang.String - Returns calendar identifier
### createContact(Contact contact) {#createContact-com.aspose.email.Contact-}
```
public abstract String createContact(Contact contact)
```


Creates contact for specified email

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [Contact](../../com.aspose.email/contact) | A contact to create. |

**Returns:**
java.lang.String - Returns contact uri
### createContact(Contact contact, String emailAddress) {#createContact-com.aspose.email.Contact-java.lang.String-}
```
public abstract String createContact(Contact contact, String emailAddress)
```


Creates contact for specified email

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [Contact](../../com.aspose.email/contact) | A contact to create. |
| emailAddress | java.lang.String | Email address |

**Returns:**
java.lang.String - Returns contact uri
### createContactPhoto(Contact contact, byte[] imageData) {#createContactPhoto-com.aspose.email.Contact-byte---}
```
public abstract ContactPhoto createContactPhoto(Contact contact, byte[] imageData)
```


Creates contact photo

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [Contact](../../com.aspose.email/contact) | contact photo |
| imageData | byte[] | image data |

**Returns:**
[ContactPhoto](../../com.aspose.email/contactphoto)
### deleteAccessRule(String calendarId, String roleId) {#deleteAccessRule-java.lang.String-java.lang.String-}
```
public abstract void deleteAccessRule(String calendarId, String roleId)
```


Deletes access rule

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |
| roleId | java.lang.String | Role identifier. |

### deleteAppointment(String calendarId, String appointmentId) {#deleteAppointment-java.lang.String-java.lang.String-}
```
public abstract void deleteAppointment(String calendarId, String appointmentId)
```


Deletes an appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |
| appointmentId | java.lang.String | Appointment identifier. |

### deleteCalendar(String calendarId) {#deleteCalendar-java.lang.String-}
```
public abstract void deleteCalendar(String calendarId)
```


Deletes a calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |

### deleteContact(String contactUri) {#deleteContact-java.lang.String-}
```
public abstract void deleteContact(String contactUri)
```


Deletes specified contact

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contactUri | java.lang.String | Contact uri |

### deleteContactPhoto(ContactPhoto contactPhoto) {#deleteContactPhoto-com.aspose.email.ContactPhoto-}
```
public abstract void deleteContactPhoto(ContactPhoto contactPhoto)
```


Deletes contact photo

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contactPhoto | [ContactPhoto](../../com.aspose.email/contactphoto) | contact photo |

### fetchAccessRule(String calendarId, String roleId) {#fetchAccessRule-java.lang.String-java.lang.String-}
```
public abstract AccessControlRule fetchAccessRule(String calendarId, String roleId)
```


Fetches access rule

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |
| roleId | java.lang.String | Role identifier. |

**Returns:**
[AccessControlRule](../../com.aspose.email/accesscontrolrule) - Returns fetched access rule
### fetchAppointment(String calendarId, String appointmentId) {#fetchAppointment-java.lang.String-java.lang.String-}
```
public abstract Appointment fetchAppointment(String calendarId, String appointmentId)
```


Fetches appointment by identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |
| appointmentId | java.lang.String | Appointment identifier. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - Returns fetched appointment.
### fetchCalendar(String calendarId) {#fetchCalendar-java.lang.String-}
```
public abstract ExtendedCalendar fetchCalendar(String calendarId)
```


Fetches calendar by identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |

**Returns:**
[ExtendedCalendar](../../com.aspose.email/extendedcalendar) - Returns fetched calendar.
### getAllContacts() {#getAllContacts--}
```
public abstract Contact[] getAllContacts()
```


Fetches all contacts.

**Returns:**
com.aspose.email.Contact[] - Contacts array
### getAllGroups() {#getAllGroups--}
```
public abstract ContactGroupCollection getAllGroups()
```


Fetches all contact groups.

**Returns:**
[ContactGroupCollection](../../com.aspose.email/contactgroupcollection) - Contact groups collection
### getColors() {#getColors--}
```
public abstract ColorsInfo getColors()
```


Gets color information

**Returns:**
[ColorsInfo](../../com.aspose.email/colorsinfo) - Returns color information
### getContact(Contact contact) {#getContact-com.aspose.email.Contact-}
```
public abstract Contact getContact(Contact contact)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [Contact](../../com.aspose.email/contact) | Contact to refresh |

**Returns:**
[Contact](../../com.aspose.email/contact) - [Contact](../../com.aspose.email/contact) object, that represents a contact of gmail
### getContact(String contactUri) {#getContact-java.lang.String-}
```
public abstract Contact getContact(String contactUri)
```


Fetches contact

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contactUri | java.lang.String | String, that represents contact's uri |

**Returns:**
[Contact](../../com.aspose.email/contact) - [Contact](../../com.aspose.email/contact) object, that represents a contact of gmail
### getContactsFromGroup(String groupId) {#getContactsFromGroup-java.lang.String-}
```
public abstract Contact[] getContactsFromGroup(String groupId)
```


Fetches contacts belonging to the group specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| groupId | java.lang.String | string that represents group id for a contact |

**Returns:**
com.aspose.email.Contact[] - Contacts array
### getFreebusyInfo(FreebusyQuery query) {#getFreebusyInfo-com.aspose.email.FreebusyQuery-}
```
public abstract FreebusyResponse getFreebusyInfo(FreebusyQuery query)
```


Gets free/busy information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [FreebusyQuery](../../com.aspose.email/freebusyquery) | Query to get free/busy information |

**Returns:**
[FreebusyResponse](../../com.aspose.email/freebusyresponse) - Returns free/busy information.
### getPhoto(ContactPhoto photo) {#getPhoto-com.aspose.email.ContactPhoto-}
```
public abstract ContactPhoto getPhoto(ContactPhoto photo)
```


Fetches a contact photo

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| photo | [ContactPhoto](../../com.aspose.email/contactphoto) | ContactPhoto object with identifier |

**Returns:**
[ContactPhoto](../../com.aspose.email/contactphoto) - Returns a contact photo
### getPhoto(String photoUri) {#getPhoto-java.lang.String-}
```
public abstract ContactPhoto getPhoto(String photoUri)
```


Fetches a contact photo

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| photoUri | java.lang.String | Uri of an image. |

**Returns:**
[ContactPhoto](../../com.aspose.email/contactphoto) - Returns a contact photo
### getSetting(String setting) {#getSetting-java.lang.String-}
```
public abstract String getSetting(String setting)
```


Gets settings by the name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| setting | java.lang.String | Setting name |

**Returns:**
java.lang.String - Returns settings value
### getSettings() {#getSettings--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getSettings()
```


Gets settings dictionary

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Returns settings dictionary
### importAppointment(String calendarId, Appointment appointment) {#importAppointment-java.lang.String-com.aspose.email.Appointment-}
```
public abstract Appointment importAppointment(String calendarId, Appointment appointment)
```


Imports appointment to calendar

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |
| appointment | [Appointment](../../com.aspose.email/appointment) | An instance of appointment object to import. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - Returns the imported appointment.
### listAccessRules(String calendarId) {#listAccessRules-java.lang.String-}
```
public abstract AccessControlRule[] listAccessRules(String calendarId)
```


Gets list of access rules

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |

**Returns:**
com.aspose.email.AccessControlRule[] - Returns list of access rules
### listAppointmentInstances(String calendarId, String appointmentId) {#listAppointmentInstances-java.lang.String-java.lang.String-}
```
public abstract Appointment[] listAppointmentInstances(String calendarId, String appointmentId)
```


Gets list of an appointment instances for calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |
| appointmentId | java.lang.String | Appointment identifier. |

**Returns:**
com.aspose.email.Appointment[] - Returns list of an appointment instances for calendar.
### listAppointments(String calendarId) {#listAppointments-java.lang.String-}
```
public abstract Appointment[] listAppointments(String calendarId)
```


Gets list of an appointments for calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |

**Returns:**
com.aspose.email.Appointment[] - Returns list of an appointments for calendar.
### listCalendars() {#listCalendars--}
```
public abstract ExtendedCalendar[] listCalendars()
```


Gets array of calendars.

**Returns:**
com.aspose.email.ExtendedCalendar[] - Returns array of calendars.
### listCalendars(int minAccessRole, boolean showHidden) {#listCalendars-int-boolean-}
```
public abstract ExtendedCalendar[] listCalendars(int minAccessRole, boolean showHidden)
```


Gets array of calendars.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| minAccessRole | int | The effective access role that the authenticated user has on the calendar. |
| showHidden | boolean | Show hidden calendars |

**Returns:**
com.aspose.email.ExtendedCalendar[] - Returns array of calendars.
### moveAppointment(String sourceCalendarId, String destinationCalendarId, String appointmentId) {#moveAppointment-java.lang.String-java.lang.String-java.lang.String-}
```
public abstract Appointment moveAppointment(String sourceCalendarId, String destinationCalendarId, String appointmentId)
```


Moves an appointment to another calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceCalendarId | java.lang.String | Identifier of source calendar. |
| destinationCalendarId | java.lang.String | Identifier of destination calendar. |
| appointmentId | java.lang.String | Appointment identifier. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - Returns moved appointment.
### moveAppointment(String sourceCalendarId, String destinationCalendarId, String appointmentId, boolean sendNotifications) {#moveAppointment-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public abstract Appointment moveAppointment(String sourceCalendarId, String destinationCalendarId, String appointmentId, boolean sendNotifications)
```


Moves an appointment to another calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceCalendarId | java.lang.String | Identifier of source calendar. |
| destinationCalendarId | java.lang.String | Identifier of destination calendar. |
| appointmentId | java.lang.String | Appointment identifier. |
| sendNotifications | boolean | Specifies whether notification should be sent. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - Returns moved appointment.
### updateAccessRule(String calendarId, AccessControlRule role) {#updateAccessRule-java.lang.String-com.aspose.email.AccessControlRule-}
```
public abstract AccessControlRule updateAccessRule(String calendarId, AccessControlRule role)
```


Updates access rule

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |
| role | [AccessControlRule](../../com.aspose.email/accesscontrolrule) | Access control rule |

**Returns:**
[AccessControlRule](../../com.aspose.email/accesscontrolrule) - Returns updated access rule
### updateAppointment(String calendarId, Appointment appointment) {#updateAppointment-java.lang.String-com.aspose.email.Appointment-}
```
public abstract Appointment updateAppointment(String calendarId, Appointment appointment)
```


Updates an appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar identifier. |
| appointment | [Appointment](../../com.aspose.email/appointment) | An instance of appointment object to update. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - Returns updated appointment.
### updateCalendar(Calendar calendar) {#updateCalendar-com.aspose.email.Calendar-}
```
public abstract void updateCalendar(Calendar calendar)
```


Updates a calendar

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendar | [Calendar](../../com.aspose.email/calendar) | An instance of calendar object to update. |

### updateCalendar(Calendar calendar, boolean useColorRgbFormat) {#updateCalendar-com.aspose.email.Calendar-boolean-}
```
public abstract void updateCalendar(Calendar calendar, boolean useColorRgbFormat)
```


Updates a calendar

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendar | [Calendar](../../com.aspose.email/calendar) | An instance of calendar object to update. |
| useColorRgbFormat | boolean | Indicates whether color rgb format is used. |

### updateContact(Contact contact) {#updateContact-com.aspose.email.Contact-}
```
public abstract Contact updateContact(Contact contact)
```


Updates contact

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [Contact](../../com.aspose.email/contact) | A contact to update. |

**Returns:**
[Contact](../../com.aspose.email/contact)
### updateContactPhoto(ContactPhoto contactPhoto) {#updateContactPhoto-com.aspose.email.ContactPhoto-}
```
public abstract void updateContactPhoto(ContactPhoto contactPhoto)
```


Creates or updates contact photo

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contactPhoto | [ContactPhoto](../../com.aspose.email/contactphoto) | contact photo |

