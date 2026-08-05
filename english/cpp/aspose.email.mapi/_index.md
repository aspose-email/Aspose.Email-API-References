---
title: "Aspose::Email::Mapi namespace"
linktitle: "Aspose::Email::Mapi"
articleTitle: "Aspose::Email::Mapi"
second_title: "Aspose.Email for C++"
description: "Provides classes and interfaces for creating, parsing, and managing MAPI objects such as messages, contacts, and follow‑up information."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/
---

## Aspose::Email::Mapi namespace

The Aspose::Email::Mapi namespace groups the API surface that enables developers to work with Microsoft Outlook MAPI data structures directly from C++. It includes utilities for handling contacts, message parsing errors, follow‑up management, property tagging, and inline attachment extraction.


## Classes

| Name | Description |
| --- | --- |
| [ContactSaveOptions](./contactsaveoptions/) | Represents the base contact save options |
| [Details_FileAccessViolationException](./details_fileaccessviolationexception/) | This exception wile be thrown when the file open and locked by another caller. |
| [Details_MapiMessageParseException](./details_mapimessageparseexception/) | This exception is thrown when errors occur in parsing MapiMessage . |
| [FollowUpManager](./followupmanager/) | Provides the ability to set and handle follow-up Outlook flags and categories. S |
| [FollowUpOptions](./followupoptions/) | Represents options for using follow-up flags and reminders in a message. |
| [IMapiMessageItem](./imapimessageitem/) | Base interface for all message items in Outlook |
| [INamedPropertyTagProvider](./inamedpropertytagprovider/) | Interface of named mapi property tag provider. |
| [InlineAttachmentExtractor](./inlineattachmentextractor/) | Provides ability to extract files from MSO packages. Can be used to process "ole |
| [KnownPropertyList](./knownpropertylist/) | The read-only Master Property List provides implementers with a single source of |
| [KnownPropertySets](./knownpropertysets/) | [MS-OXCDATA]: Commonly Used Property Sets |
| [MailConversionOptions](./mailconversionoptions/) | Specify additional options when converting from MapiMessage to MailMessage . |
| [MapiAttachment](./mapiattachment/) | Represents a message attachment. |
| [MapiAttachmentCollection](./mapiattachmentcollection/) | Represents a collection of MapiAttachment objects. |
| [MapiAttachmentPropertyStream](./mapiattachmentpropertystream/) | Represents the property stream of attachment object. |
| [MapiCalendar](./mapicalendar/) | Represents a MAPI calendar item. |
| [MapiCalendarAttendees](./mapicalendarattendees/) | Represents the mapi calendar attendees |
| [MapiCalendarCollection](./mapicalendarcollection/) | Represents the collection of MapiCalendar |
| [MapiCalendarDailyRecurrencePattern](./mapicalendardailyrecurrencepattern/) | Represents the daily recurrence pattern of the mapi calendar |
| [MapiCalendarEventRecurrence](./mapicalendareventrecurrence/) | Represents the recurrence properties of calendar object |
| [MapiCalendarExceptionInfo](./mapicalendarexceptioninfo/) | An exception specifies changes to an instance of a recurring series. |
| [MapiCalendarIcsSaveOptions](./mapicalendaricssaveoptions/) |  |
| [MapiCalendarMonthlyNthRecurrencePattern](./mapicalendarmonthlynthrecurrencepattern/) | Represents the monthly nth recurrence pattern of the mapi calendar |
| [MapiCalendarMonthlyRecurrencePattern](./mapicalendarmonthlyrecurrencepattern/) | Represents the monthly recurrence pattern of the mapi calendar |
| [MapiCalendarMsgSaveOptions](./mapicalendarmsgsaveoptions/) |  |
| [MapiCalendarRecurrencePattern](./mapicalendarrecurrencepattern/) | Represents the mapi recurrence pattern |
| [MapiCalendarRecurrencePatternFactory](./mapicalendarrecurrencepatternfactory/) | Represents the factory of MapiCalendarRecurrencePattern |
| [MapiCalendarSaveOptions](./mapicalendarsaveoptions/) |  |
| [MapiCalendarTimeZone](./mapicalendartimezone/) | Represents the mapi calendar time zone information |
| [MapiCalendarTimeZoneInfo](./mapicalendartimezoneinfo/) | Represents the mapi calendar time zone rule |
| [MapiCalendarTimeZoneInfoCollection](./mapicalendartimezoneinfocollection/) | Represents a collection of MapiCalendarTimeZoneInfo |
| [MapiCalendarTimeZoneRule](./mapicalendartimezonerule/) | Represents time zone rule that indicate when to begin using the Standard/Dayligh |
| [MapiCalendarWeeklyRecurrencePattern](./mapicalendarweeklyrecurrencepattern/) | Represents the weekly recurrence pattern of the mapi calendar |
| [MapiCalendarYearlyAndMonthlyRecurrencePattern](./mapicalendaryearlyandmonthlyrecurrencepattern/) | Represents the yearly and monthly recurrence pattern of the mapi calendar |
| [MapiContact](./mapicontact/) | Represents a MAPI contact item. |
| [MapiContactAddress](./mapicontactaddress/) | Base abstract class for MapiContactElectronicAddress and MapiContactPhysicalAddr |
| [MapiContactCollection](./mapicontactcollection/) | Represents the collection of MapiContact |
| [MapiContactElectronicAddress](./mapicontactelectronicaddress/) | Refers to the group of properties that define the e-mail address or fax address  |
| [MapiContactElectronicAddressPropertySet](./mapicontactelectronicaddresspropertyset/) | Specify properties for up to three different e-mail addresses (Email1, Email2, a |
| [MapiContactEventPropertySet](./mapicontacteventpropertyset/) | Specify events associated with a contact |
| [MapiContactNamePropertySet](./mapicontactnamepropertyset/) | The properties are used to specify the name of the person represented by the con |
| [MapiContactOtherPropertySet](./mapicontactotherpropertyset/) | The properties are used to specify additional properies of contact. |
| [MapiContactPersonalInfoPropertySet](./mapicontactpersonalinfopropertyset/) | Specify other additional contact information |
| [MapiContactPhoto](./mapicontactphoto/) | Contains data and type of contact's photo. |
| [MapiContactPhysicalAddress](./mapicontactphysicaladdress/) | Refers to the group of properties that define physical address for a contact. |
| [MapiContactPhysicalAddressPropertySet](./mapicontactphysicaladdresspropertyset/) | Specify three physical addresses: Home Address, Work Address, and Other Address. |
| [MapiContactProfessionalPropertySet](./mapicontactprofessionalpropertyset/) | Properties are used to store professional details for the person represented by  |
| [MapiContactPropertySet](./mapicontactpropertyset/) | Base class for all sets of MapiContact properties. |
| [MapiContactSaveOptions](./mapicontactsaveoptions/) | Specifies the contact save options. |
| [MapiContactTelephonePropertySet](./mapicontacttelephonepropertyset/) | Specify optional telephone numbers for the contact |
| [MapiConversionOptions](./mapiconversionoptions/) | This class allows the user to specify additional options when converting from Ma |
| [MapiDistributionList](./mapidistributionlist/) | Represents a MAPI distribution list item. |
| [MapiDistributionListMember](./mapidistributionlistmember/) | Represents the members of the personal distribution list. |
| [MapiDistributionListMemberCollection](./mapidistributionlistmembercollection/) | Represents a collection of MapiDistributionListMember objects. |
| [MapiDistributionListSaveOptions](./mapidistributionlistsaveoptions/) | Specifies the DistributionList save options. |
| [MapiElectronicAddress](./mapielectronicaddress/) | Refers to the group of properties that define the e-mail address or fax address. |
| [MapiJournal](./mapijournal/) | Represents a MAPI journal item. |
| [MapiLazyRtfProperty](./mapilazyrtfproperty/) | Inherits Aspose::Email::Mapi::MapiProperty . |
| [MapiMessage](./mapimessage/) | Represents an Outlook Message format document that can be parsed. |
| [MapiMessageItemBase](./mapimessageitembase/) | Represents the base class for all MapiMessageItem classes and keeps common colle |
| [MapiMessagePropertyStream](./mapimessagepropertystream/) | Represents the property stream. |
| [MapiMessageReader](./mapimessagereader/) | Represents a reader that can read a Microsoft Outlook Message format document. |
| [MapiNamedProperty](./mapinamedproperty/) | Represents the data type of Named Property. |
| [MapiNamedPropertyMappingStorage](./mapinamedpropertymappingstorage/) | Represents the named property mapping |
| [MapiNote](./mapinote/) | Represents a MAPI note ("sticky note") item. |
| [MapiObjectProperty](./mapiobjectproperty/) | Represents a Custom object included in Outlook Message documents. |
| [MapiProperty](./mapiproperty/) | Represents the mapi property. |
| [MapiPropertyCollection](./mapipropertycollection/) | Represents the collection of MapiProperty items. |
| [MapiPropertyContainer](./mapipropertycontainer/) | Represents the base class for MapiAttachment , MapiRecipient , MapiMessage . |
| [MapiPropertyStream](./mapipropertystream/) | Represents the property stream. |
| [MapiPropertyTag](./mapipropertytag/) | Represents the MAPI property tags definition. |
| [MapiRecipient](./mapirecipient/) | Represents the recipient information in the Microsoft Outlook Message. |
| [MapiRecipientCollection](./mapirecipientcollection/) | Represents a collection of MapiRecipient objects. |
| [MapiRecipientPropertyStream](./mapirecipientpropertystream/) | Represents the property stream of recipient object. |
| [MapiTask](./mapitask/) | Represents a MAPI task item. |
| [MapiTaskCollection](./mapitaskcollection/) | Represents the collection of MapiTask |
| [MapiTaskUsers](./mapitaskusers/) | Represents information about task users. |
| [OleDocumentFormat](./oledocumentformat/) | Represents the format for OLE document. |
| [PidLidPropertyDescriptor](./pidlidpropertydescriptor/) | Class contains property description information. |
| [PidNamePropertyDescriptor](./pidnamepropertydescriptor/) | Class contains property description information. |
| [PidTagPropertyDescriptor](./pidtagpropertydescriptor/) | Class contains property description information. |
| [PropertyDescriptor](./propertydescriptor/) | Class contains property description information. |
| [ReferenceAttachmentOptions](./referenceattachmentoptions/) | Represents configuration options for adding a reference attachment to a MAPI mes |
| [UserReaction](./userreaction/) | Represents a user's reaction. |
| [WebDavContactSaveOptions](./webdavcontactsaveoptions/) | Specifies the contact save options. |

## Enumerations

| Name | Description |
| --- | --- |
| [BodyContentType](./bodycontenttype/) | The content type of message body. |
| [ContactSaveFormat](./contactsaveformat/) | Enumerates contact save formats |
| [MapiCalendarBusyStatus](./mapicalendarbusystatus/) | Enumerates the mapi calendar possible busy status |
| [MapiCalendarClientIntent](./mapicalendarclientintent/) | Enumerates the actions the user can taken on the Meeting object |
| [MapiCalendarDayOfWeek](./mapicalendardayofweek/) | Enumerates the days of week of the mapi calendar recurrence pattern |
| [MapiCalendarOverrideFlags](./mapicalendaroverrideflags/) | Specifies what data in the MapiCalendarOverrideFlags structure has a value diffe |
| [MapiCalendarRecurrenceCalendarType](./mapicalendarrecurrencecalendartype/) | Enumerated the calendar type of the mapi recurrence |
| [MapiCalendarRecurrenceEndType](./mapicalendarrecurrenceendtype/) | Enumerates the ending type for the recurrence. |
| [MapiCalendarRecurrenceFrequency](./mapicalendarrecurrencefrequency/) | Enumerates mapi calendar recurrence frequency |
| [MapiCalendarRecurrencePatternType](./mapicalendarrecurrencepatterntype/) | Enumerates the mapi calendar recurrence pattern types |
| [MapiCalendarState](./mapicalendarstate/) | Enumerates the appointment state |
| [MapiCalendarTimeZoneFlags](./mapicalendartimezoneflags/) | Enumerates the individual bit flags that specify information about TimeZoneRule |
| [MapiContactGender](./mapicontactgender/) | Gender of the contact |
| [MapiContactPhotoImageFormat](./mapicontactphotoimageformat/) | Enumerates MapiContact photo image format. |
| [MapiDistributionListContactAddressType](./mapidistributionlistcontactaddresstype/) | Represents the address type of a personal distribution list member. |
| [MapiDistributionListEntryIdType](./mapidistributionlistentryidtype/) | Specifies the type of EntryID. |
| [MapiItemType](./mapiitemtype/) | Represents a MAPI item type that can be explicitly converted into an object of t |
| [MapiJournalDocumentStatus](./mapijournaldocumentstatus/) | Indicates the status of document. |
| [MapiJournalFlags](./mapijournalflags/) | Contains metadata about the Journal object. Must be either zero or the following |
| [MapiMessageFlags](./mapimessageflags/) | MapiMessageFlags. |
| [MapiObjectType](./mapiobjecttype/) | Represents the mapi object type. |
| [MapiPropertyType](./mapipropertytype/) | Represents the data type of MapiProperty data. |
| [MapiRecipientTrackStatus](./mapirecipienttrackstatus/) | Represents the response status returned by the attendee. |
| [MapiRecipientType](./mapirecipienttype/) | Represent the PR_RECIPIENT_TYPE property which contains the recipient type for a |
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

