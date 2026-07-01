---
title: Aspose.Email.Mapi
second_title: Aspose.Email for .NET API Reference
description: The Aspose.Email.Mapi namespace contains classes that represent Outlook messages contacts appointments and classes for work with Microsoft Outlook PSTOST file format
type: docs
weight: 300
url: /net/aspose.email.mapi/
---
The **Aspose.Email.Mapi** namespace contains classes that represent Outlook messages, contacts, appointments and classes for work with Microsoft Outlook PST\OST file format.

## Classes

| Class | Description |
| --- | --- |
| [ContactSaveOptions](./contactsaveoptions/) | Serves as the abstract base class for contact save options when saving contact objects to various formats. This class provides common configuration properties such as save format and vCard version for contact serialization. |
| [FileAccessViolationException](./fileaccessviolationexception/) | This exception wile be thrown when the file open and locked by another caller. |
| [FollowUpManager](./followupmanager/) | Provides methods for managing Outlook follow-up flags, categories, and voting options on MAPI messages. This static class enables setting and removing follow-up flags, managing categories (keywords), setting due dates and reminders, and configuring voting buttons on [`MapiMessageItemBase`](../aspose.email.mapi/mapimessageitembase/) objects. |
| [FollowUpOptions](./followupoptions/) | Represents configuration options for follow-up flags, reminders, categories, and voting buttons in Outlook messages. This class encapsulates all the properties needed to set follow-up behavior on [`MapiMessage`](../aspose.email.mapi/mapimessage/) objects through the [`FollowUpManager`](../aspose.email.mapi/followupmanager/) class. |
| [InlineAttachmentExtractor](./inlineattachmentextractor/) | Provides ability to extract files from MSO packages. Can be used to process "oledata.mso" and similar files typically attached to messages created using Outlook. |
| [KnownPropertyList](./knownpropertylist/) | The read-only Master Property List provides implementers with a single source of information about all the properties that are described by the specifications that comprise the Exchange Server Protocols documentation (MS-OXPROPS). Coincides MS-OXPROPS revision 16.2 from 7/31/2014 |
| [KnownPropertySets](./knownpropertysets/) | [MS-OXCDATA]: Commonly Used Property Sets |
| [MailConversionOptions](./mailconversionoptions/) | Provides options for controlling how [`MapiMessage`](../aspose.email.mapi/mapimessage/) instances are converted to [`MailMessage`](../aspose.email/mailmessage/) objects. This class allows you to customize the conversion behavior for TNEF handling, embedded message format preservation, RTF content, and email address management. |
| [MapiAttachment](./mapiattachment/) |  |
| [MapiAttachmentCollection](./mapiattachmentcollection/) | Represents a strongly-typed collection of [`MapiAttachment`](../aspose.email.mapi/mapiattachment/) objects that belong to a MAPI message or item. This collection class provides methods for adding, removing, and managing attachments in Outlook messages, including support for embedded messages and file attachments. |
| [MapiAttachmentPropertyStream](./mapiattachmentpropertystream/) | Represents the property stream of attachment object. |
| [MapiCalendar](./mapicalendar/) | Represents a MAPI calendar item. |
| [MapiCalendarAttendees](./mapicalendarattendees/) | Represents the attendees and related properties for a MAPI calendar item (meeting request, appointment). This class manages recipient information for calendar events, including required and optional attendees, unsendable recipients, and meeting-specific options like proposal restrictions. |
| [MapiCalendarCollection](./mapicalendarcollection/) | Represents a strongly-typed collection of [`MapiCalendar`](../aspose.email.mapi/mapicalendar/) objects for managing multiple calendar items in a single collection. This class provides standard collection operations while maintaining type safety for MAPI calendar entries. |
| [MapiCalendarDailyRecurrencePattern](./mapicalendardailyrecurrencepattern/) | Represents a daily recurrence pattern for MAPI calendar items, allowing you to define how recurring meetings or events repeat on a daily basis. This class provides properties to configure the recurrence interval and specific days of the week for weekly-based daily patterns. |
| [MapiCalendarEventRecurrence](./mapicalendareventrecurrence/) | Represents the recurrence properties of a calendar object, including the recurrence pattern, time zone information, and the date range of recurrence. This class encapsulates all the data needed to define how recurring calendar events repeat over time. |
| [MapiCalendarExceptionInfo](./mapicalendarexceptioninfo/) | An exception specifies changes to an instance of a recurring series. |
| [MapiCalendarIcsSaveOptions](./mapicalendaricssaveoptions/) | Provides options for controlling how [`MapiCalendar`](../aspose.email.mapi/mapicalendar/) instances are saved to iCalendar (ICS) format. This class extends [`MapiCalendarSaveOptions`](../aspose.email.mapi/mapicalendarsaveoptions/) and adds iCalendar-specific configuration options for date/time handling and product identification. |
| [MapiCalendarMonthlyNthRecurrencePattern](./mapicalendarmonthlynthrecurrencepattern/) | Represents a monthly recurrence pattern that occurs on the Nth occurrence of specific days of the week (e.g., "the 2nd Monday of each month"). This class inherits from [`MapiCalendarYearlyAndMonthlyRecurrencePattern`](../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/) and provides the base functionality for monthly recurrence patterns in MAPI calendar items. |
| [MapiCalendarMonthlyRecurrencePattern](./mapicalendarmonthlyrecurrencepattern/) | Represents a monthly recurrence pattern for MAPI calendar items, allowing events to repeat on a specific day of each month. This class inherits from [`MapiCalendarYearlyAndMonthlyRecurrencePattern`](../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/) and provides the base functionality for monthly recurrence patterns in MAPI calendar items. |
| [MapiCalendarMsgSaveOptions](./mapicalendarmsgsaveoptions/) | Provides options for controlling how [`MapiCalendar`](../aspose.email.mapi/mapicalendar/) instances are saved to Outlook MSG format. This class extends [`MapiCalendarSaveOptions`](../aspose.email.mapi/mapicalendarsaveoptions/) and is specifically designed for saving calendar items in the native Outlook message format. |
| [MapiCalendarRecurrencePattern](./mapicalendarrecurrencepattern/) | Serves as the abstract base class for all MAPI calendar recurrence patterns. This class provides common properties and functionality for defining how calendar events repeat over time, including frequency, date ranges, occurrence counts, and exception handling. |
| [MapiCalendarRecurrencePatternFactory](./mapicalendarrecurrencepatternfactory/) | Represents the factory of MapiCalendarRecurrencePattern |
| [MapiCalendarSaveOptions](./mapicalendarsaveoptions/) | Serves as the abstract base class for format-specific options when saving [`MapiCalendar`](../aspose.email.mapi/mapicalendar/) objects to various formats (ICS, MSG). This class provides common configuration properties such as save format and factory methods for creating format-specific save options. |
| [MapiCalendarTimeZone](./mapicalendartimezone/) | Represents the mapi calendar time zone information |
| [MapiCalendarTimeZoneInfo](./mapicalendartimezoneinfo/) | Represents the mapi calendar time zone rule |
| [MapiCalendarTimeZoneInfoCollection](./mapicalendartimezoneinfocollection/) | Represents a collection of MapiCalendarTimeZoneInfo |
| [MapiCalendarTimeZoneRule](./mapicalendartimezonerule/) | Represents time zone rule that indicate when to begin using the Standard/Daylight time. |
| [MapiCalendarWeeklyRecurrencePattern](./mapicalendarweeklyrecurrencepattern/) | Represents a weekly recurrence pattern for MAPI calendar items, allowing events to repeat on specific days of the week at regular weekly intervals. This class provides properties to configure the recurrence interval and the specific days of the week when the event occurs. |
| [MapiCalendarYearlyAndMonthlyRecurrencePattern](./mapicalendaryearlyandmonthlyrecurrencepattern/) | Represents the base class for yearly and monthly recurrence patterns in MAPI calendar items. This abstract class provides common properties and functionality for patterns that can recur either monthly (on a specific day) or yearly (on a specific day of a specific month). |
| [MapiContact](./mapicontact/) | Represents a MAPI contact item. |
| [MapiContactAddress](./mapicontactaddress/) | Serves as the abstract base class for contact address types in MAPI contact items. This class provides common functionality for managing electronic addresses ([`MapiContactElectronicAddress`](../aspose.email.mapi/mapicontactelectronicaddress/)) and physical addresses ([`MapiContactPhysicalAddress`](../aspose.email.mapi/mapicontactphysicaladdress/)) through shared property access methods. |
| [MapiContactCollection](./mapicontactcollection/) | Represents a strongly-typed collection of [`MapiContact`](../aspose.email.mapi/mapicontact/) objects for managing multiple contacts in a single collection. This class provides standard collection operations while maintaining type safety for MAPI contact entries. |
| [MapiContactElectronicAddress](./mapicontactelectronicaddress/) | Represents a group of properties that define an electronic address (email or fax) for a contact. This class provides functionality for managing contact email addresses and fax numbers through properties such as display name, address type, email address, and fax number. |
| [MapiContactElectronicAddressPropertySet](./mapicontactelectronicaddresspropertyset/) | Specify properties for up to three different e-mail addresses (Email1, Email2, and Email3) and three different fax addresses (Primary Fax, Business Fax, and Home Fax) |
| [MapiContactEventPropertySet](./mapicontacteventpropertyset/) | Specify events associated with a contact |
| [MapiContactNamePropertySet](./mapicontactnamepropertyset/) | The properties are used to specify the name of the person represented by the contact |
| [MapiContactOtherPropertySet](./mapicontactotherpropertyset/) | The properties are used to specify additional properies of contact. |
| [MapiContactPersonalInfoPropertySet](./mapicontactpersonalinfopropertyset/) | Specify other additional contact information |
| [MapiContactPhoto](./mapicontactphoto/) | Contains data and type of contact's photo. |
| [MapiContactPhysicalAddress](./mapicontactphysicaladdress/) | Represents a group of properties that define a physical address for a contact. This class provides functionality for managing contact physical addresses through properties such as street, city, state, postal code, country, and mail address flags. |
| [MapiContactPhysicalAddressPropertySet](./mapicontactphysicaladdresspropertyset/) | Specify three physical addresses: Home Address, Work Address, and Other Address. One of the addresses can be marked as the Mailing Address |
| [MapiContactProfessionalPropertySet](./mapicontactprofessionalpropertyset/) | Properties are used to store professional details for the person represented by the contact |
| [MapiContactPropertySet](./mapicontactpropertyset/) | Base class for all sets of MapiContact properties. |
| [MapiContactSaveOptions](./mapicontactsaveoptions/) | Specifies the contact save options. |
| [MapiContactTelephonePropertySet](./mapicontacttelephonepropertyset/) | Specify optional telephone numbers for the contact |
| [MapiConversionOptions](./mapiconversionoptions/) | This class allows the user to specify additional options when converting from MailMessage to MapiMessage. |
| [MapiDistributionList](./mapidistributionlist/) | Represents a MAPI distribution list item. |
| [MapiDistributionListMember](./mapidistributionlistmember/) | Represents the members of the personal distribution list. |
| [MapiDistributionListMemberCollection](./mapidistributionlistmembercollection/) | Represents a collection of [`MapiDistributionListMember`](../aspose.email.mapi/mapidistributionlistmember/) objects. |
| [MapiDistributionListSaveOptions](./mapidistributionlistsaveoptions/) | Specifies the DistributionList save options. |
| [MapiElectronicAddress](./mapielectronicaddress/) | Refers to the group of properties that define the e-mail address or fax address. |
| [MapiJournal](./mapijournal/) | Represents a MAPI journal item. |
| [MapiMessage](./mapimessage/) | Represents an Outlook Message format document that can be parsed. |
| [MapiMessageItemBase](./mapimessageitembase/) | Represents the base class for all MapiMessageItem classes and keeps common collections of mapi properties, attachments, recipients. |
| [MapiMessageParseException](./mapimessageparseexception/) | This exception is thrown when errors occur in parsing MapiMessage. |
| [MapiMessagePropertyStream](./mapimessagepropertystream/) | Represents the property stream. |
| [MapiMessageReader](./mapimessagereader/) | Represents a reader that can read a Microsoft Outlook Message format document. |
| [MapiNamedProperty](./mapinamedproperty/) | Represents the data type of Named Property. |
| [MapiNamedPropertyMappingStorage](./mapinamedpropertymappingstorage/) | Represents the named property mapping |
| [MapiNote](./mapinote/) | Represents a MAPI note ("sticky note") item. |
| [MapiObjectProperty](./mapiobjectproperty/) | Represents a Custom object included in Outlook Message documents. |
| [MapiProperty](./mapiproperty/) | Represents the mapi property. |
| [MapiPropertyCollection](./mapipropertycollection/) | Represents the collection of MapiProperty items. |
| [MapiPropertyContainer](./mapipropertycontainer/) | Represents the base class for [`MapiAttachment`](../aspose.email.mapi/mapiattachment/), [`MapiRecipient`](../aspose.email.mapi/mapirecipient/), [`MapiMessage`](../aspose.email.mapi/mapimessage/). |
| [MapiPropertyStream](./mapipropertystream/) | Represents the property stream. |
| [MapiPropertyTag](./mapipropertytag/) | Represents the MAPI property tags definition. |
| [MapiRecipient](./mapirecipient/) | Represents the recipient information in the Microsoft Outlook Message. |
| [MapiRecipientCollection](./mapirecipientcollection/) | Represents a collection of MapiRecipient objects. |
| [MapiRecipientPropertyStream](./mapirecipientpropertystream/) | Represents the property stream of recipient object. |
| [MapiTask](./mapitask/) | Represents a MAPI task item. |
| [MapiTaskCollection](./mapitaskcollection/) | Represents the collection of [`MapiTask`](../aspose.email.mapi/mapitask/) |
| [MapiTaskUsers](./mapitaskusers/) | Represents information about task users. |
| [OleDocumentFormat](./oledocumentformat/) | Represents the format for OLE document. |
| [PidLidPropertyDescriptor](./pidlidpropertydescriptor/) | Contains descriptive information about a MAPI named property. This class provides properties and functionality for working with properties identified by a 32-bit long ID (LID) combined with a property set GUID, typically used for custom or non-standard MAPI properties. |
| [PidNamePropertyDescriptor](./pidnamepropertydescriptor/) | Contains descriptive information about a MAPI named property identified by a string name. This class provides properties and functionality for working with properties identified by a string name combined with a property set GUID, typically used for custom or non-standard MAPI properties with string-based identifiers. |
| [PidTagPropertyDescriptor](./pidtagpropertydescriptor/) | Contains descriptive information about a MAPI tagged property. This class provides properties and functionality for working with properties identified by a 16-bit property ID and 16-bit property type, typically used for standard MAPI properties. |
| [PropertyDescriptor](./propertydescriptor/) | Class contains property description information. |
| [ReferenceAttachmentOptions](./referenceattachmentoptions/) | Represents configuration options for adding a reference attachment to a MAPI message. |
| [UserReaction](./userreaction/) | Represents a user's reaction. |
| [WebDavContactSaveOptions](./webdavcontactsaveoptions/) | Specifies the contact save options. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IMapiMessageItem](./imapimessageitem/) | Defines the base interface for all Outlook message item types including messages, appointments, tasks, contacts, and notes. This interface provides common properties for accessing message class, item type, body content, and subject across different Outlook item types. |
| [INamedPropertyTagProvider](./inamedpropertytagprovider/) | Interface of named mapi property tag provider. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [BodyContentType](./bodycontenttype/) | Specifies the content type format of a message body in MAPI messages. |
| [ContactSaveFormat](./contactsaveformat/) | Enumerates contact save formats |
| [MapiCalendarBusyStatus](./mapicalendarbusystatus/) | Enumerates the mapi calendar possible busy status |
| [MapiCalendarClientIntent](./mapicalendarclientintent/) | Enumerates the actions the user can taken on the Meeting object |
| [MapiCalendarDayOfWeek](./mapicalendardayofweek/) | Enumerates the days of week of the mapi calendar recurrence pattern |
| [MapiCalendarOverrideFlags](./mapicalendaroverrideflags/) | Specifies what data in the MapiCalendarOverrideFlags structure has a value different from the recurring series. |
| [MapiCalendarRecurrenceCalendarType](./mapicalendarrecurrencecalendartype/) | Specifies the calendar type used for MAPI calendar recurrence patterns. This enumeration supports multiple calendar systems including Gregorian, Hijri, Hebrew, lunar, and various regional calendars used around the world. |
| [MapiCalendarRecurrenceEndType](./mapicalendarrecurrenceendtype/) | Enumerates the ending type for the recurrence. |
| [MapiCalendarRecurrenceFrequency](./mapicalendarrecurrencefrequency/) | Enumerates mapi calendar recurrence frequency |
| [MapiCalendarRecurrencePatternType](./mapicalendarrecurrencepatterntype/) | Specifies the type of recurrence pattern for MAPI calendar items. |
| [MapiCalendarState](./mapicalendarstate/) | Enumerates the appointment state |
| [MapiCalendarTimeZoneFlags](./mapicalendartimezoneflags/) | Enumerates the individual bit flags that specify information about TimeZoneRule |
| [MapiContactGender](./mapicontactgender/) | Gender of the contact |
| [MapiContactPhotoImageFormat](./mapicontactphotoimageformat/) | Enumerates MapiContact photo image format. |
| [MapiDistributionListContactAddressType](./mapidistributionlistcontactaddresstype/) | Represents the address type of a personal distribution list member. |
| [MapiDistributionListEntryIdType](./mapidistributionlistentryidtype/) | Specifies the type of EntryID. |
| [MapiItemType](./mapiitemtype/) | Represents a MAPI item type that can be explicitly converted into an object of the corresponding class derived from the [`IMapiMessageItem`](../aspose.email.mapi/imapimessageitem/) interface. |
| [MapiJournalDocumentStatus](./mapijournaldocumentstatus/) | Indicates the status of document. |
| [MapiJournalFlags](./mapijournalflags/) | Contains metadata about the Journal object. Must be either zero or the following values. |
| [MapiMessageFlags](./mapimessageflags/) | MapiMessageFlags. |
| [MapiObjectType](./mapiobjecttype/) | Represents the mapi object type. |
| [MapiPropertyType](./mapipropertytype/) | Represents the data type of MapiProperty data. |
| [MapiRecipientTrackStatus](./mapirecipienttrackstatus/) | Represents the response status returned by the attendee. |
| [MapiRecipientType](./mapirecipienttype/) | Represent the PR_RECIPIENT_TYPE property which contains the recipient type for a message recipient. |
| [MapiTaskAcceptanceState](./mapitaskacceptancestate/) | Indicates the acceptance state of the task. |
| [MapiTaskFlags](./mapitaskflags/) | Contains indication flags of the Task object. |
| [MapiTaskHistory](./mapitaskhistory/) | Indicates the type of change that was last made to the Task object. |
| [MapiTaskMode](./mapitaskmode/) | Represents the assignment statuses of the task object. |
| [MapiTaskOwnership](./mapitaskownership/) | Indicates the role of the current user relative to the Task object. |
| [MapiTaskPriority](./mapitaskpriority/) | Represents the priority on the task. |
| [MapiTaskState](./mapitaskstate/) | Indicates the assignment state of the Task object. |
| [MapiTaskStatus](./mapitaskstatus/) | Represents the statuses of the user's progress on the task. |
| [NoteColor](./notecolor/) | Specifies the suggested background color of the Note object |
| [NoteSaveFormat](./notesaveformat/) | Enumerates NoteSaveFormat |
| [OutlookMessageFormat](./outlookmessageformat/) | Represents outlook message format. |
| [PropertyDataType](./propertydatatype/) | [MS-OXCDATA]: Data Structures |
| [ReactionType](./reactiontype/) | Specifies the type of reaction a user can have on a message. |
| [TaskSaveFormat](./tasksaveformat/) | Enumerates TaskSaveFormat |


