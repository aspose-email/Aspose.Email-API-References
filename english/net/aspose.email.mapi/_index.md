---
title: Aspose.Email.Mapi
second_title: Aspose.Email for .NET API Reference
description: The **Aspose.Email.Mapi** namespace contains classes that represent Outlook messages, contacts, appointments and classes for work with Microsoft Outlook PST\OST file format.
type: docs
weight: 230
url: /net/aspose.email.mapi/
---
The **Aspose.Email.Mapi** namespace contains classes that represent Outlook messages, contacts, appointments and classes for work with Microsoft Outlook PST\OST file format.

## Classes

| Class | Description |
| --- | --- |
| abstract class [ContactSaveOptions](./contactsaveoptions) | Represents the base contact save options |
| class [FileAccessViolationException](./fileaccessviolationexception) | This exception wile be thrown when the file open and locked by another caller. |
| static class [FollowUpManager](./followupmanager) | Provides the ability to set and handle follow-up Outlook flags and categories. Supports the features to add and remove a flag in [`MapiMessage`](aspose.email.mapi/mapimessage), and mark it as completed as well. |
| class [FollowUpOptions](./followupoptions) | Represents options for using follow-up flags and reminders in a message. |
| static class [InlineAttachmentExtractor](./inlineattachmentextractor) | Provides ability to extract files from MSO packages. Can be used to process "oledata.mso" and similar files typically attached to messages created using Outlook. |
| class [KnownPropertyList](./knownpropertylist) | The read-only Master Property List provides implementers with a single source of information about all the properties that are described by the specifications that comprise the Exchange Server Protocols documentation (MS-OXPROPS). Coincides MS-OXPROPS revision 16.2 from 7/31/2014 |
| static class [KnownPropertySets](./knownpropertysets) | [MS-OXCDATA]: Commonly Used Property Sets |
| class [MailConversionOptions](./mailconversionoptions) | Specify additional options when converting from MapiMessage to MailMessage. |
| class [MapiAttachment](./mapiattachment) | Represents the attachment in the E-mail message. |
| class [MapiAttachmentCollection](./mapiattachmentcollection) | Represents a collection of MapiAttachment objects. |
| class [MapiAttachmentPropertyStream](./mapiattachmentpropertystream) | Represents the property stream of attachment object. |
| class [MapiCalendar](./mapicalendar) | Represents the mapi calendar object |
| class [MapiCalendarAttendees](./mapicalendarattendees) | Represents the mapi calendar attendees |
| class [MapiCalendarDailyRecurrencePattern](./mapicalendardailyrecurrencepattern) | Represents the daily recurrence pattern of the mapi calendar |
| class [MapiCalendarEventRecurrence](./mapicalendareventrecurrence) | Represents the recurrence properties of calendar object |
| class [MapiCalendarExceptionInfo](./mapicalendarexceptioninfo) | An exception specifies changes to an instance of a recurring series. |
| class [MapiCalendarMonthlyNthRecurrencePattern](./mapicalendarmonthlynthrecurrencepattern) | Represents the monthly nth recurrence pattern of the mapi calendar |
| class [MapiCalendarMonthlyRecurrencePattern](./mapicalendarmonthlyrecurrencepattern) | Represents the monthly recurrence pattern of the mapi calendar |
| abstract class [MapiCalendarRecurrencePattern](./mapicalendarrecurrencepattern) | Represents the mapi recurrence pattern |
| static class [MapiCalendarRecurrencePatternFactory](./mapicalendarrecurrencepatternfactory) | Represents the factory of MapiCalendarRecurrencePattern |
| class [MapiCalendarTimeZone](./mapicalendartimezone) | Represents the mapi calendar time zone information |
| class [MapiCalendarTimeZoneInfo](./mapicalendartimezoneinfo) | Represents the mapi calendar time zone rule |
| class [MapiCalendarTimeZoneInfoCollection](./mapicalendartimezoneinfocollection) | Represents a collection of MapiCalendarTimeZoneInfo |
| class [MapiCalendarTimeZoneRule](./mapicalendartimezonerule) | Represents time zone rule that indicate when to begin using the Standard/Daylight time. |
| class [MapiCalendarWeeklyRecurrencePattern](./mapicalendarweeklyrecurrencepattern) | Represents the weekly recurrence pattern of the mapi calendar |
| class [MapiCalendarYearlyAndMonthlyRecurrencePattern](./mapicalendaryearlyandmonthlyrecurrencepattern) | Represents the yearly and monthly recurrence pattern of the mapi calendar |
| class [MapiContact](./mapicontact) | Represents outlook contact information |
| class [MapiContactCollection](./mapicontactcollection) | Represents the collection of [`MapiContact`](aspose.email.mapi/mapicontact) |
| class [MapiContactElectronicAddress](./mapicontactelectronicaddress) | Refers to the group of properties that define the e-mail address or fax address for a contact. |
| class [MapiContactElectronicAddressPropertySet](./mapicontactelectronicaddresspropertyset) | Specify properties for up to three different e-mail addresses (Email1, Email2, and Email3) and three different fax addresses (Primary Fax, Business Fax, and Home Fax) |
| class [MapiContactEventPropertySet](./mapicontacteventpropertyset) | Specify events associated with a contact |
| class [MapiContactNamePropertySet](./mapicontactnamepropertyset) | The properties are used to specify the name of the person represented by the contact |
| class [MapiContactOtherPropertySet](./mapicontactotherpropertyset) | The properties are used to specify additional properies of contact. |
| class [MapiContactPersonalInfoPropertySet](./mapicontactpersonalinfopropertyset) | Specify other additional contact information |
| class [MapiContactPhoto](./mapicontactphoto) | Contains data and type of contact's photo. |
| class [MapiContactPhysicalAddress](./mapicontactphysicaladdress) | Refers to the group of properties that define physical address for a contact. |
| class [MapiContactPhysicalAddressPropertySet](./mapicontactphysicaladdresspropertyset) | Specify three physical addresses: Home Address, Work Address, and Other Address. One of the addresses can be marked as the Mailing Address |
| class [MapiContactProfessionalPropertySet](./mapicontactprofessionalpropertyset) | Properties are used to store professional details for the person represented by the contact |
| class [MapiContactSaveOptions](./mapicontactsaveoptions) | Specifies the contact save options. |
| class [MapiContactTelephonePropertySet](./mapicontacttelephonepropertyset) | Specify optional telephone numbers for the contact |
| class [MapiConversionOptions](./mapiconversionoptions) | This class allows the user to specify additional options when converting from MailMessage to MapiMessage. |
| class [MapiDistributionList](./mapidistributionlist) | Represents the Personal Distribution List object. |
| class [MapiDistributionListMember](./mapidistributionlistmember) | Represents the members of the personal distribution list. |
| class [MapiDistributionListMemberCollection](./mapidistributionlistmembercollection) | Represents a collection of [`MapiDistributionListMember`](aspose.email.mapi/mapidistributionlistmember) objects. |
| class [MapiElectronicAddress](./mapielectronicaddress) | Refers to the group of properties that define the e-mail address or fax address. |
| class [MapiJournal](./mapijournal) | Represents the Outlook Journal object. |
| class [MapiMessage](./mapimessage) | Represents an Outlook Message format document that can be parsed. |
| abstract class [MapiMessageItemBase](./mapimessageitembase) | Represents the base class for all MapiMessageItem classes and keeps common collections of mapi properties, attachments, recipients. |
| class [MapiMessageParseException](./mapimessageparseexception) | This exception is thrown when errors occur in parsing MapiMessage. |
| class [MapiMessagePropertyStream](./mapimessagepropertystream) | Represents the property stream. |
| class [MapiMessageReader](./mapimessagereader) | Represents a reader that can read a Microsoft Outlook Message format document. |
| class [MapiNamedProperty](./mapinamedproperty) | Represents the data type of Named Property. |
| class [MapiNamedPropertyMappingStorage](./mapinamedpropertymappingstorage) | Represents the named property mapping |
| class [MapiNote](./mapinote) | Represents outlook Note object ("sticky note") |
| class [MapiObjectProperty](./mapiobjectproperty) | Represents a Custom object included in Outlook Message documents. |
| class [MapiProperty](./mapiproperty) | Represents the mapi property. |
| class [MapiPropertyCollection](./mapipropertycollection) | Represents the collection of MapiProperty items. |
| class [MapiPropertyContainer](./mapipropertycontainer) | Represents the base class for [`MapiAttachment`](aspose.email.mapi/mapiattachment), [`MapiRecipient`](aspose.email.mapi/mapirecipient), [`MapiMessage`](aspose.email.mapi/mapimessage). |
| abstract class [MapiPropertyStream](./mapipropertystream) | Represents the property stream. |
| static class [MapiPropertyTag](./mapipropertytag) | Represents the MAPI property tags definition. |
| class [MapiRecipient](./mapirecipient) | Represents the recipient information in the Microsoft Outlook Message. |
| class [MapiRecipientCollection](./mapirecipientcollection) | Represents a collection of MapiRecipient objects. |
| class [MapiRecipientPropertyStream](./mapirecipientpropertystream) | Represents the property stream of recipient object. |
| class [MapiTask](./mapitask) | Represents the Outlook Task object. |
| class [MapiTaskUsers](./mapitaskusers) | Represents information about task users. |
| class [OleDocumentFormat](./oledocumentformat) | Represents the format for OLE document. |
| class [PidLidPropertyDescriptor](./pidlidpropertydescriptor) | Class contains property description information. |
| class [PidNamePropertyDescriptor](./pidnamepropertydescriptor) | Class contains property description information. |
| class [PidTagPropertyDescriptor](./pidtagpropertydescriptor) | Class contains property description information. |
| abstract class [PropertyDescriptor](./propertydescriptor) | Class contains property description information. |
| class [WebDavContactSaveOptions](./webdavcontactsaveoptions) | Specifies the contact save options. |
## Interfaces

| Interface | Description |
| --- | --- |
| interface [IMapiMessageItem](./imapimessageitem) | Base interface for all message items in Outlook |
| interface [INamedPropertyTagProvider](./inamedpropertytagprovider) | Interface of named mapi property tag provider. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| enum [BodyContentType](./bodycontenttype) | The content type of message body. |
| enum [ContactSaveFormat](./contactsaveformat) | Enumerates contact save formats |
| enum [MapiCalendarBusyStatus](./mapicalendarbusystatus) | Enumerates the mapi calendar possible busy status |
| enum [MapiCalendarClientIntent](./mapicalendarclientintent) | Enumerates the actions the user can taken on the Meeting object |
| enum [MapiCalendarDayOfWeek](./mapicalendardayofweek) | Enumerates the days of week of the mapi calendar recurrence pattern |
| enum [MapiCalendarOverrideFlags](./mapicalendaroverrideflags) | Specifies what data in the MapiCalendarOverrideFlags structure has a value different from the recurring series. |
| enum [MapiCalendarRecurrenceCalendarType](./mapicalendarrecurrencecalendartype) | Enumerated the calendar type of the mapi recurrence |
| enum [MapiCalendarRecurrenceEndType](./mapicalendarrecurrenceendtype) | Enumerates the ending type for the recurrence. |
| enum [MapiCalendarRecurrenceFrequency](./mapicalendarrecurrencefrequency) | Enumerates mapi calendar recurrence frequency |
| enum [MapiCalendarRecurrencePatternType](./mapicalendarrecurrencepatterntype) | Enumerates the mapi calendar recurrence pattern types |
| enum [MapiCalendarState](./mapicalendarstate) | Enumerates the appointment state |
| enum [MapiCalendarTimeZoneFlags](./mapicalendartimezoneflags) | Enumerates the individual bit flags that specify information about TimeZoneRule |
| enum [MapiContactGender](./mapicontactgender) | Gender of the contact |
| enum [MapiContactPhotoImageFormat](./mapicontactphotoimageformat) | Enumerates MapiContact photo image format. |
| enum [MapiDistributionListContactAddressType](./mapidistributionlistcontactaddresstype) | Represents the address type of a personal distribution list member. |
| enum [MapiDistributionListEntryIdType](./mapidistributionlistentryidtype) | Specifies the type of EntryID. |
| enum [MapiJournalDocumentStatus](./mapijournaldocumentstatus) | Indicates the status of document. |
| enum [MapiJournalFlags](./mapijournalflags) | Contains metadata about the Journal object. Must be either zero or the following values. |
| enum [MapiMessageFlags](./mapimessageflags) | MapiMessageFlags. |
| enum [MapiObjectType](./mapiobjecttype) | Represents the mapi object type. |
| enum [MapiPropertyType](./mapipropertytype) | Represents the data type of MapiProperty data. |
| enum [MapiRecipientTrackStatus](./mapirecipienttrackstatus) | Represents the response status returned by the attendee. |
| enum [MapiRecipientType](./mapirecipienttype) | Represent the PR_RECIPIENT_TYPE property which contains the recipient type for a message recipient. |
| enum [MapiTaskAcceptanceState](./mapitaskacceptancestate) | Indicates the acceptance state of the task. |
| enum [MapiTaskFlags](./mapitaskflags) | Contains indication flags of the Task object. |
| enum [MapiTaskHistory](./mapitaskhistory) | Indicates the type of change that was last made to the Task object. |
| enum [MapiTaskMode](./mapitaskmode) | Represents the assignment statuses of the task object. |
| enum [MapiTaskOwnership](./mapitaskownership) | Indicates the role of the current user relative to the Task object. |
| enum [MapiTaskPriority](./mapitaskpriority) | Represents the priority on the task. |
| enum [MapiTaskState](./mapitaskstate) | Indicates the assignment state of the Task object. |
| enum [MapiTaskStatus](./mapitaskstatus) | Represents the statuses of the user's progress on the task. |
| enum [NoteColor](./notecolor) | Specifies the suggested background color of the Note object |
| enum [NoteSaveFormat](./notesaveformat) | Enumerates NoteSaveFormat |
| enum [OutlookMessageFormat](./outlookmessageformat) | Represents outlook message format. |
| enum [PropertyDataType](./propertydatatype) | [MS-OXCDATA]: Data Structures |
| enum [TaskSaveFormat](./tasksaveformat) | Enumerates TaskSaveFormat |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
