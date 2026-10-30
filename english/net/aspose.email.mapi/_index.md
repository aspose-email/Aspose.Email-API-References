---
title: Aspose.Email.Mapi
second_title: Aspose.Email for .NET API Reference
description: Work with Outlook items  messages contacts appointments tasks and notes  and their MAPI properties
type: docs
weight: 300
url: /net/aspose.email.mapi/
---
Work with Outlook items - messages, contacts, appointments, tasks and notes - and their MAPI properties.

## Classes

| Class | Description |
| --- | --- |
| [ContactSaveOptions](./contactsaveoptions/) | The base class for the options that control how a contact is saved. The derived classes select the format: [`VCardSaveOptions`](../aspose.email.personalinfo.vcard/vcardsaveoptions/) for vCard, [`WebDavContactSaveOptions`](../aspose.email.mapi/webdavcontactsaveoptions/) for WebDAV and [`MapiContactSaveOptions`](../aspose.email.mapi/mapicontactsaveoptions/) for MSG. |
| [FileAccessViolationException](./fileaccessviolationexception/) | The exception that is thrown when a file cannot be opened because another process has opened and locked it. |
| [FollowUpManager](./followupmanager/) | Manages Outlook follow-up flags, reminders, categories and voting buttons of a message. |
| [FollowUpOptions](./followupoptions/) | The follow-up settings of a message: flag, dates, reminder, categories and voting buttons. |
| [InlineAttachmentExtractor](./inlineattachmentextractor/) | Extracts the files packed into an MSO package, such as the `oledata.mso` attachment that Outlook adds to messages with embedded images or objects. |
| [KnownPropertyList](./knownpropertylist/) | The read-only Master Property List provides implementers with a single source of information about all the properties that are described by the specifications that comprise the Exchange Server Protocols documentation (MS-OXPROPS). Coincides MS-OXPROPS revision 16.2 from 7/31/2014 |
| [KnownPropertySets](./knownpropertysets/) | The GUIDs of the commonly used property sets, as listed in [MS-OXCDATA]. A property set GUID together with a name or numeric ID identifies a named property. |
| [MailConversionOptions](./mailconversionoptions/) | Options that control how a [`MapiMessage`](../aspose.email.mapi/mapimessage/) is converted to a [`MailMessage`](../aspose.email/mailmessage/). |
| [MapiAttachment](./mapiattachment/) | Represents an attachment of an Outlook item. |
| [MapiAttachmentCollection](./mapiattachmentcollection/) | The attachments of an Outlook item. |
| [MapiAttachmentPropertyStream](./mapiattachmentpropertystream/) | The property stream of an attachment. |
| [MapiCalendar](./mapicalendar/) | Represents an Outlook calendar item: an appointment or a meeting. |
| [MapiCalendarAttendees](./mapicalendarattendees/) | The attendees of a meeting and the settings of their responses. |
| [MapiCalendarCollection](./mapicalendarcollection/) | A collection of [`MapiCalendar`](../aspose.email.mapi/mapicalendar/) items. |
| [MapiCalendarDailyRecurrencePattern](./mapicalendardailyrecurrencepattern/) | A recurrence that repeats every N days, or on selected days of the week. |
| [MapiCalendarEventRecurrence](./mapicalendareventrecurrence/) | The recurrence of a calendar event: the pattern, the time zone and the range of the series. |
| [MapiCalendarExceptionInfo](./mapicalendarexceptioninfo/) | An exception of a recurring series: an occurrence whose time, subject or other details differ from the series. |
| [MapiCalendarIcsSaveOptions](./mapicalendaricssaveoptions/) | Options for saving a [`MapiCalendar`](../aspose.email.mapi/mapicalendar/) to iCalendar (.ics) format. |
| [MapiCalendarMonthlyNthRecurrencePattern](./mapicalendarmonthlynthrecurrencepattern/) | A recurrence on the Nth weekday of every N months, such as "the second Monday of every month". |
| [MapiCalendarMonthlyRecurrencePattern](./mapicalendarmonthlyrecurrencepattern/) | A recurrence on a given day of every N months, such as "the 15th of every month". |
| [MapiCalendarMsgSaveOptions](./mapicalendarmsgsaveoptions/) | Options for saving a [`MapiCalendar`](../aspose.email.mapi/mapicalendar/) to Outlook MSG format. |
| [MapiCalendarRecurrencePattern](./mapicalendarrecurrencepattern/) | The base class of the recurrence patterns: how often a series repeats, from when, and until when. |
| [MapiCalendarRecurrencePatternFactory](./mapicalendarrecurrencepatternfactory/) | Creates recurrence patterns from iCalendar recurrence rules. |
| [MapiCalendarSaveOptions](./mapicalendarsaveoptions/) | The base class for the options of saving a [`MapiCalendar`](../aspose.email.mapi/mapicalendar/). The derived class selects the format. |
| [MapiCalendarTimeZone](./mapicalendartimezone/) | The time zone of a calendar item, with its standard and daylight time rules. |
| [MapiCalendarTimeZoneInfo](./mapicalendartimezoneinfo/) | A rule of a time zone: its offsets and when daylight saving time begins and ends. |
| [MapiCalendarTimeZoneInfoCollection](./mapicalendartimezoneinfocollection/) | A collection of the rules of a time zone. |
| [MapiCalendarTimeZoneRule](./mapicalendartimezonerule/) | The moment at which standard or daylight saving time begins. |
| [MapiCalendarWeeklyRecurrencePattern](./mapicalendarweeklyrecurrencepattern/) | A recurrence on selected days of every N weeks, such as "every two weeks on Monday and Friday". |
| [MapiCalendarYearlyAndMonthlyRecurrencePattern](./mapicalendaryearlyandmonthlyrecurrencepattern/) | A recurrence every N months: on a given day of the month or on the Nth weekday of the month. A period that is a multiple of 12 makes it a yearly recurrence. |
| [MapiContact](./mapicontact/) | Represents a MAPI contact item. |
| [MapiContactAddress](./mapicontactaddress/) | The base class of the addresses of a contact: e-mail and fax addresses ([`MapiContactElectronicAddress`](../aspose.email.mapi/mapicontactelectronicaddress/)) and postal addresses ([`MapiContactPhysicalAddress`](../aspose.email.mapi/mapicontactphysicaladdress/)). |
| [MapiContactCollection](./mapicontactcollection/) | A collection of [`MapiContact`](../aspose.email.mapi/mapicontact/) items. |
| [MapiContactElectronicAddress](./mapicontactelectronicaddress/) | An e-mail address or fax number of a contact. |
| [MapiContactElectronicAddressPropertySet](./mapicontactelectronicaddresspropertyset/) | The e-mail addresses (Email1, Email2, Email3) and fax numbers (primary, business, home) of a contact. |
| [MapiContactEventPropertySet](./mapicontacteventpropertyset/) | The dates associated with a contact. |
| [MapiContactNamePropertySet](./mapicontactnamepropertyset/) | The name of a contact: given name, surname, title and so on. |
| [MapiContactOtherPropertySet](./mapicontactotherpropertyset/) | Other fields of a contact: reminder, privacy, journaling and four user-defined fields. |
| [MapiContactPersonalInfoPropertySet](./mapicontactpersonalinfopropertyset/) | The personal details of a contact, such as web pages, spouse, children, hobbies and notes. |
| [MapiContactPhoto](./mapicontactphoto/) | The photo of a contact: the image data and its format. |
| [MapiContactPhysicalAddress](./mapicontactphysicaladdress/) | A postal address of a contact: street, city, state or province, postal code and country. |
| [MapiContactPhysicalAddressPropertySet](./mapicontactphysicaladdresspropertyset/) | The postal addresses of a contact: home, work and other. One of them can be marked as the mailing address. |
| [MapiContactProfessionalPropertySet](./mapicontactprofessionalpropertyset/) | The professional details of a contact: company, job title, department, office, manager and assistant. |
| [MapiContactPropertySet](./mapicontactpropertyset/) | The base class of the groups of contact properties, such as names, addresses and telephone numbers. |
| [MapiContactSaveOptions](./mapicontactsaveoptions/) | Options for saving a contact to Outlook MSG format. |
| [MapiContactTelephonePropertySet](./mapicontacttelephonepropertyset/) | The telephone numbers of a contact. |
| [MapiConversionOptions](./mapiconversionoptions/) | Options that control how a [`MailMessage`](../aspose.email/mailmessage/) is converted to a [`MapiMessage`](../aspose.email.mapi/mapimessage/). |
| [MapiDistributionList](./mapidistributionlist/) | Represents a MAPI distribution list item. |
| [MapiDistributionListMember](./mapidistributionlistmember/) | A member of a personal distribution list. |
| [MapiDistributionListMemberCollection](./mapidistributionlistmembercollection/) | The members of a distribution list. |
| [MapiDistributionListSaveOptions](./mapidistributionlistsaveoptions/) | Options for saving a distribution list. |
| [MapiElectronicAddress](./mapielectronicaddress/) | An e-mail address or fax number, such as the organizer of a meeting. |
| [MapiJournal](./mapijournal/) | Represents a MAPI journal item. |
| [MapiMessage](./mapimessage/) | Represents an Outlook message: the content of an MSG file. |
| [MapiMessageItemBase](./mapimessageitembase/) | The base class of Outlook items: messages, appointments, tasks, contacts and so on. Holds their properties, attachments and recipients. |
| [MapiMessageParseException](./mapimessageparseexception/) | The exception that is thrown when a message cannot be parsed. |
| [MapiMessagePropertyStream](./mapimessagepropertystream/) | The property stream of a message. |
| [MapiMessageReader](./mapimessagereader/) | Reads Outlook messages (MSG files) from a file or a stream. |
| [MapiNamedProperty](./mapinamedproperty/) | A named property: a MAPI property identified by a property set GUID and a name or numeric ID rather than by a fixed tag. |
| [MapiNamedPropertyMappingStorage](./mapinamedpropertymappingstorage/) | The mapping between the named properties of a message and the tags they are stored under. |
| [MapiNote](./mapinote/) | Represents a MAPI note ("sticky note") item. |
| [MapiObjectProperty](./mapiobjectproperty/) | An object embedded in an attachment, such as an attached Outlook message or an OLE document. |
| [MapiProperty](./mapiproperty/) | A MAPI property: a value identified by a tag that holds the property ID and the data type. |
| [MapiPropertyCollection](./mapipropertycollection/) | The MAPI properties of a message, attachment or recipient, keyed by tag. |
| [MapiPropertyContainer](./mapipropertycontainer/) | The base class of the objects that consist of MAPI properties: messages, attachments and recipients. |
| [MapiPropertyStream](./mapipropertystream/) | The base class of the property streams of messages, attachments and recipients: the storage that holds their fixed-size properties. |
| [MapiPropertyTag](./mapipropertytag/) | Represents the MAPI property tags definition. |
| [MapiRecipient](./mapirecipient/) | A recipient of an Outlook message, or of another item such as a meeting. |
| [MapiRecipientCollection](./mapirecipientcollection/) | The recipients of an Outlook item. |
| [MapiRecipientPropertyStream](./mapirecipientpropertystream/) | The property stream of a recipient. |
| [MapiTask](./mapitask/) | Represents a MAPI task item. |
| [MapiTaskCollection](./mapitaskcollection/) | A collection of [`MapiTask`](../aspose.email.mapi/mapitask/) items. |
| [MapiTaskUsers](./mapitaskusers/) | The people involved in a task: owner, assigner, delegator and the other users. |
| [OleDocumentFormat](./oledocumentformat/) | The format of an OLE document embedded in an attachment, identified by its class GUID. |
| [PidLidPropertyDescriptor](./pidlidpropertydescriptor/) | Describes a named property identified by a numeric ID (LID) within a property set. |
| [PidNamePropertyDescriptor](./pidnamepropertydescriptor/) | Describes a named property identified by a string name within a property set. |
| [PidTagPropertyDescriptor](./pidtagpropertydescriptor/) | Describes a tagged property: a property with a fixed 16-bit ID and a 16-bit data type. |
| [PropertyDescriptor](./propertydescriptor/) | The base class of property descriptors: the identity and data type of a MAPI property. |
| [ReferenceAttachmentOptions](./referenceattachmentoptions/) | Options of a reference attachment: a link to a file in a cloud storage, such as OneDrive, instead of the file itself. |
| [UserReaction](./userreaction/) | A reaction of a user to a message: who reacted, how and when. |
| [WebDavContactSaveOptions](./webdavcontactsaveoptions/) | Options for saving a contact to the WebDAV XML format of Exchange Server. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IMapiMessageItem](./imapimessageitem/) | The common interface of Outlook items: messages, appointments, tasks, contacts, notes, journal entries and distribution lists. |
| [INamedPropertyTagProvider](./inamedpropertytagprovider/) | Provides property tags for named properties, so that a named property can be stored in a property collection. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [BodyContentType](./bodycontenttype/) | Specifies the format of a message body. |
| [ContactSaveFormat](./contactsaveformat/) | Defines the formats a contact can be saved to. |
| [MapiCalendarBusyStatus](./mapicalendarbusystatus/) | Defines how the time of an event is shown in the calendar. |
| [MapiCalendarClientIntent](./mapicalendarclientintent/) | Defines the actions the user has taken on a meeting. The values can be combined. |
| [MapiCalendarDayOfWeek](./mapicalendardayofweek/) | Defines the days of the week of a recurrence. The values can be combined. |
| [MapiCalendarOverrideFlags](./mapicalendaroverrideflags/) | Defines which details of an exception differ from the recurring series. The values can be combined. |
| [MapiCalendarRecurrenceCalendarType](./mapicalendarrecurrencecalendartype/) | Defines the calendar system a recurrence is calculated in. |
| [MapiCalendarRecurrenceEndType](./mapicalendarrecurrenceendtype/) | Defines how a recurring series ends. |
| [MapiCalendarRecurrenceFrequency](./mapicalendarrecurrencefrequency/) | Defines how often a recurring series repeats. |
| [MapiCalendarRecurrencePatternType](./mapicalendarrecurrencepatterntype/) | Defines the type of a recurrence pattern. |
| [MapiCalendarState](./mapicalendarstate/) | Defines the state of a calendar item. The values can be combined. |
| [MapiCalendarTimeZoneFlags](./mapicalendartimezoneflags/) | Defines flags of a time zone rule. The values can be combined. |
| [MapiContactGender](./mapicontactgender/) | Defines the gender of a contact. |
| [MapiContactPhotoImageFormat](./mapicontactphotoimageformat/) | Defines the image formats of a contact photo. |
| [MapiDistributionListContactAddressType](./mapidistributionlistcontactaddresstype/) | Defines which address of a contact a member of a distribution list refers to. |
| [MapiDistributionListEntryIdType](./mapidistributionlistentryidtype/) | Defines what the EntryID of a distribution list member refers to. |
| [MapiItemType](./mapiitemtype/) | Defines the type of an Outlook item, which determines the class [`ToMapiMessageItem`](../aspose.email.mapi/mapimessage/tomapimessageitem/) converts it to. |
| [MapiJournalDocumentStatus](./mapijournaldocumentstatus/) | Defines what happened to a document during a journaled activity. The values can be combined. |
| [MapiJournalFlags](./mapijournalflags/) | Defines the flags of a journal entry. |
| [MapiMessageFlags](./mapimessageflags/) | Defines the flags of a message, such as read, unsent or has attachments. The values can be combined. |
| [MapiObjectType](./mapiobjecttype/) | Defines the types of MAPI objects. |
| [MapiPropertyType](./mapipropertytype/) | Defines the data types of MAPI properties: the low-order 16 bits of a property tag. |
| [MapiRecipientTrackStatus](./mapirecipienttrackstatus/) | Defines the responses of an attendee to a meeting request. |
| [MapiRecipientType](./mapirecipienttype/) | Defines the types of message recipients (the `PR_RECIPIENT_TYPE` property). |
| [MapiTaskAcceptanceState](./mapitaskacceptancestate/) | Defines whether the assignee has accepted a task. |
| [MapiTaskFlags](./mapitaskflags/) | Defines the flags of a task. The values can be combined. |
| [MapiTaskHistory](./mapitaskhistory/) | Defines the last change made to a task. |
| [MapiTaskMode](./mapitaskmode/) | Defines the assignment status of a task. |
| [MapiTaskOwnership](./mapitaskownership/) | Defines the role of the current user in a task. |
| [MapiTaskPriority](./mapitaskpriority/) | Defines the priorities of a task. |
| [MapiTaskState](./mapitaskstate/) | Defines the assignment state of a task. |
| [MapiTaskStatus](./mapitaskstatus/) | Defines the progress status of a task. |
| [NoteColor](./notecolor/) | Defines the background colors of a note. |
| [NoteSaveFormat](./notesaveformat/) | Defines the formats a note can be saved to. |
| [OutlookMessageFormat](./outlookmessageformat/) | Defines the string formats of an Outlook message. |
| [PropertyDataType](./propertydatatype/) | Defines the data types of property values, as specified in [MS-OXCDATA]. |
| [ReactionType](./reactiontype/) | Defines the reactions a user can leave on a message. |
| [TaskSaveFormat](./tasksaveformat/) | Defines the formats of a task. |


