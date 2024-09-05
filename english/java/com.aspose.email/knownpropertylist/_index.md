---
title: KnownPropertyList
second_title: Aspose.Email for Java API Reference
description: The read-only Master Property List provides implementers with a single source of information about all the properties  that are described by the specifications that comprise the Exchange Server Protocols documentation MS-OXPROPS.
type: docs
weight: 347
url: /java/com.aspose.email/knownpropertylist/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class KnownPropertyList implements Iterable<PropertyDescriptor>
```

The read-only Master Property List provides implementers with a single source of information about all the properties that are described by the specifications that comprise the Exchange Server Protocols documentation (MS-OXPROPS). Coincides MS-OXPROPS revision 16.2 from 7/31/2014
## Fields

| Field | Description |
| --- | --- |
| [ABSTRACT](#ABSTRACT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [AB_DEFAULT_DIR](#AB-DEFAULT-DIR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [AB_DEFAULT_PAB](#AB-DEFAULT-PAB) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [AB_PROVIDERS](#AB-PROVIDERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [AB_PROVIDER_ID](#AB-PROVIDER-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [AB_SEARCH_PATH](#AB-SEARCH-PATH) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [AB_SEARCH_PATH_UPDATE](#AB-SEARCH-PATH-UPDATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ACCEPT_LANGUAGE](#ACCEPT-LANGUAGE) | Contains the value of the MIME Accept-Language header. |
| [ACCESS](#ACCESS) | Indicates the operations available to the client for the object. |
| [ACCESS_CONTROL_LIST_DATA](#ACCESS-CONTROL-LIST-DATA) | Contains a permissions list for a folder. |
| [ACCESS_LEVEL](#ACCESS-LEVEL) | Indicates the client's access level to the object. |
| [ACCOUNT](#ACCOUNT) | Contains the alias of an Address Book object, which is an alternative name by which the object can be identified. |
| [ACTIVE_USER_ENTRYID](#ACTIVE-USER-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ADDITIONAL_REN_ENTRY_IDS](#ADDITIONAL-REN-ENTRY-IDS) | Contains the indexed entry IDs for several special folders related to conflicts, sync issues, local failures, server failures, junk email and spam. |
| [ADDITIONAL_REN_ENTRY_IDS_EX](#ADDITIONAL-REN-ENTRY-IDS-EX) | Contains an array of blocks that specify the EntryIDs of several special folders. |
| [ADDRBOOK_FOR_LOCAL_SITE_ENTRYID](#ADDRBOOK-FOR-LOCAL-SITE-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ADDRESS_BOOK_AUTHORIZED_SENDERS](#ADDRESS-BOOK-AUTHORIZED-SENDERS) | Indicates whether delivery restrictions exist for a recipient. |
| [ADDRESS_BOOK_CONTAINER_ID](#ADDRESS-BOOK-CONTAINER-ID) | Contains the ID of a container on an NSPI server. |
| [ADDRESS_BOOK_DELIVERY_CONTENT_LENGTH](#ADDRESS-BOOK-DELIVERY-CONTENT-LENGTH) | Specifies the maximum size, in bytes, of a message that a recipient can receive. |
| [ADDRESS_BOOK_DISPLAY_NAME](#ADDRESS-BOOK-DISPLAY-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ADDRESS_BOOK_DISPLAY_NAME_PRINTABLE](#ADDRESS-BOOK-DISPLAY-NAME-PRINTABLE) | Contains the printable string version of the display name. |
| [ADDRESS_BOOK_DISPLAY_TYPE_EXTENDED](#ADDRESS-BOOK-DISPLAY-TYPE-EXTENDED) | Contains a value that indicates how to display an Address Book object in a table or as a recipient on a message. |
| [ADDRESS_BOOK_DISTRIBUTION_LIST_EXTERNAL_MEMBER_COUNT](#ADDRESS-BOOK-DISTRIBUTION-LIST-EXTERNAL-MEMBER-COUNT) | Contains the number of external recipients in the distribution list. |
| [ADDRESS_BOOK_DISTRIBUTION_LIST_MEMBER_COUNT](#ADDRESS-BOOK-DISTRIBUTION-LIST-MEMBER-COUNT) | Contains the total number of recipients in the distribution list. |
| [ADDRESS_BOOK_DISTRIBUTION_LIST_MEMBER_SUBMIT_ACCEPTED](#ADDRESS-BOOK-DISTRIBUTION-LIST-MEMBER-SUBMIT-ACCEPTED) | Indicates that delivery restrictions exist for a recipient. |
| [ADDRESS_BOOK_DISTRIBUTION_LIST_MEMBER_SUBMIT_REJECTED](#ADDRESS-BOOK-DISTRIBUTION-LIST-MEMBER-SUBMIT-REJECTED) | Indicates that delivery restrictions exist for a recipient. |
| [ADDRESS_BOOK_DISTRIBUTION_LIST_REJECT_MESSAGES_FROM_DL_MEMBERS](#ADDRESS-BOOK-DISTRIBUTION-LIST-REJECT-MESSAGES-FROM-DL-MEMBERS) | Indicates that delivery restrictions exist for a recipient. |
| [ADDRESS_BOOK_ENTRY_ID](#ADDRESS-BOOK-ENTRY-ID) | Contains the name-service EntryID of a directory object that refers to a public folder. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_1](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-1) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_10](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-10) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_11](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-11) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_12](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-12) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_13](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-13) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_14](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-14) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_15](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-15) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_2](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-2) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_3](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-3) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_4](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-4) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_5](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-5) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_6](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-6) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_7](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-7) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_8](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-8) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_EXTENSION_ATTRIBUTE_9](#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-9) | Contains custom values defined and populated by the organization that modified the display templates. |
| [ADDRESS_BOOK_FOLDER_PATHNAME](#ADDRESS-BOOK-FOLDER-PATHNAME) | This property is deprecated and is to be ignored. |
| [ADDRESS_BOOK_HIERARCHICAL_CHILD_DEPARTMENTS](#ADDRESS-BOOK-HIERARCHICAL-CHILD-DEPARTMENTS) | Contains the child departments in a hierarchy of departments. |
| [ADDRESS_BOOK_HIERARCHICAL_DEPARTMENT_MEMBERS](#ADDRESS-BOOK-HIERARCHICAL-DEPARTMENT-MEMBERS) | Contains all of the mail users that belong to this department. |
| [ADDRESS_BOOK_HIERARCHICAL_IS_HIERARCHICAL_GROUP](#ADDRESS-BOOK-HIERARCHICAL-IS-HIERARCHICAL-GROUP) | Indicates whether the distribution list represents a departmental group. |
| [ADDRESS_BOOK_HIERARCHICAL_PARENT_DEPARTMENT](#ADDRESS-BOOK-HIERARCHICAL-PARENT-DEPARTMENT) | Contains all of the departments to which this department is a child. |
| [ADDRESS_BOOK_HIERARCHICAL_ROOT_DEPARTMENT](#ADDRESS-BOOK-HIERARCHICAL-ROOT-DEPARTMENT) | Contains the distinguished name (DN) of either the root Department object or the root departmental group in the department hierarchy for the organization. |
| [ADDRESS_BOOK_HIERARCHICAL_SHOW_IN_DEPARTMENTS](#ADDRESS-BOOK-HIERARCHICAL-SHOW-IN-DEPARTMENTS) | Lists all Department objects of which the mail user is a member. |
| [ADDRESS_BOOK_HOME_MESSAGE_DATABASE](#ADDRESS-BOOK-HOME-MESSAGE-DATABASE) | Contains the DN expressed in the X500 DN format. |
| [ADDRESS_BOOK_IS_MASTER](#ADDRESS-BOOK-IS-MASTER) | Contains a Boolean value of TRUE if it is possible to create Address Book objects in that container, and FALSE otherwise. |
| [ADDRESS_BOOK_IS_MEMBER_OF_DISTRIBUTION_LIST](#ADDRESS-BOOK-IS-MEMBER-OF-DISTRIBUTION-LIST) | Lists all of the distribution lists for which the object is a member. |
| [ADDRESS_BOOK_MANAGER](#ADDRESS-BOOK-MANAGER) | Contains one row that references the mail user's manager. |
| [ADDRESS_BOOK_MANAGER_DISTINGUISHED_NAME](#ADDRESS-BOOK-MANAGER-DISTINGUISHED-NAME) | Contains the DN of the mail user's manager. |
| [ADDRESS_BOOK_MANAGE_DISTRIBUTION_LIST](#ADDRESS-BOOK-MANAGE-DISTRIBUTION-LIST) | Contains information for use in display templates for distribution lists. |
| [ADDRESS_BOOK_MEMBER](#ADDRESS-BOOK-MEMBER) | Contains the members of the distribution list. |
| [ADDRESS_BOOK_MESSAGE_ID](#ADDRESS-BOOK-MESSAGE-ID) | Contains the Short-term Message ID (MID) ([MS-OXCDATA] section 2.2.1.2) of the first message in the local site's offline address book public folder. |
| [ADDRESS_BOOK_MODERATION_ENABLED](#ADDRESS-BOOK-MODERATION-ENABLED) | Indicates whether moderation is enabled for the mail user or distribution list. |
| [ADDRESS_BOOK_NETWORK_ADDRESS](#ADDRESS-BOOK-NETWORK-ADDRESS) | Contains a list of names by which a server is known to the various transports in use by the network. |
| [ADDRESS_BOOK_OBJECT_DISTINGUISHED_NAME](#ADDRESS-BOOK-OBJECT-DISTINGUISHED-NAME) | Contains the DN of the Address Book object. |
| [ADDRESS_BOOK_OBJECT_GUID](#ADDRESS-BOOK-OBJECT-GUID) | Contains a GUID that identifies an Address Book object. |
| [ADDRESS_BOOK_ORGANIZATIONAL_UNIT_ROOT_DISTINGUISHED_NAME](#ADDRESS-BOOK-ORGANIZATIONAL-UNIT-ROOT-DISTINGUISHED-NAME) | Contains the DN of the Organization object of the mail user's organization. |
| [ADDRESS_BOOK_OWNER](#ADDRESS-BOOK-OWNER) | Contains one row that references the distribution list's owner. |
| [ADDRESS_BOOK_OWNER_BACK_LINK](#ADDRESS-BOOK-OWNER-BACK-LINK) | Contains a list of the distribution lists owned by a mail user. |
| [ADDRESS_BOOK_PARENT_ENTRY_ID](#ADDRESS-BOOK-PARENT-ENTRY-ID) | Contains the EntryID of the parent container in a hierarchy of address book containers. |
| [ADDRESS_BOOK_PHONETIC_COMPANY_NAME](#ADDRESS-BOOK-PHONETIC-COMPANY-NAME) | Contains the phonetic representation of the PidTagCompanyName property (section 2.630). |
| [ADDRESS_BOOK_PHONETIC_DEPARTMENT_NAME](#ADDRESS-BOOK-PHONETIC-DEPARTMENT-NAME) | Contains the phonetic representation of the PidTagDepartmentName property (section 2.663). |
| [ADDRESS_BOOK_PHONETIC_DISPLAY_NAME](#ADDRESS-BOOK-PHONETIC-DISPLAY-NAME) | Contains the phonetic representation of the PidTagDisplayName property (section 2.667). |
| [ADDRESS_BOOK_PHONETIC_GIVEN_NAME](#ADDRESS-BOOK-PHONETIC-GIVEN-NAME) | Contains the phonetic representation of the PidTagGivenName property (section 2.705). |
| [ADDRESS_BOOK_PHONETIC_SURNAME](#ADDRESS-BOOK-PHONETIC-SURNAME) | Contains the phonetic representation of the PidTagSurname property (section 2.1026). |
| [ADDRESS_BOOK_PROVIDER_ARRAY_TYPE](#ADDRESS-BOOK-PROVIDER-ARRAY-TYPE) | Specifies the state of the electronic addresses of the contact and represents a set of bit flags. |
| [ADDRESS_BOOK_PROVIDER_EMAIL_LIST](#ADDRESS-BOOK-PROVIDER-EMAIL-LIST) | Specifies which electronic address properties are set on the Contact object. |
| [ADDRESS_BOOK_PROXY_ADDRESSES](#ADDRESS-BOOK-PROXY-ADDRESSES) | Contains alternate email addresses for the Address Book object. |
| [ADDRESS_BOOK_PUBLIC_DELEGATES](#ADDRESS-BOOK-PUBLIC-DELEGATES) | Contains a list of mail users who are allowed to send email on behalf of the mailbox owner. |
| [ADDRESS_BOOK_REPORTS](#ADDRESS-BOOK-REPORTS) | Lists all of the mail user\\ufffds direct reports. |
| [ADDRESS_BOOK_ROOM_CAPACITY](#ADDRESS-BOOK-ROOM-CAPACITY) | Contains the maximum occupancy of the room. |
| [ADDRESS_BOOK_ROOM_CONTAINERS](#ADDRESS-BOOK-ROOM-CONTAINERS) | Contains a list of DNs that represent the address book containers that hold Resource objects, such as conference rooms and equipment. |
| [ADDRESS_BOOK_ROOM_DESCRIPTION](#ADDRESS-BOOK-ROOM-DESCRIPTION) | Contains a description of the Resource object. |
| [ADDRESS_BOOK_SENDER_HINT_TRANSLATIONS](#ADDRESS-BOOK-SENDER-HINT-TRANSLATIONS) | Contains the locale ID and translations of the default mail tip. |
| [ADDRESS_BOOK_SENIORITY_INDEX](#ADDRESS-BOOK-SENIORITY-INDEX) | Contains a signed integer that specifies the seniority order of Address Book objects that group, with larger values specifying members that are more senior. |
| [ADDRESS_BOOK_TARGET_ADDRESS](#ADDRESS-BOOK-TARGET-ADDRESS) | Contains the foreign system email address of an Address Book object. |
| [ADDRESS_BOOK_UNAUTHORIZED_SENDERS](#ADDRESS-BOOK-UNAUTHORIZED-SENDERS) | Indicates whether delivery restrictions exist for a recipient. |
| [ADDRESS_BOOK_X_509_CERTIFICATE](#ADDRESS-BOOK-X-509-CERTIFICATE) | Contains the ASN\_1 DER encoded X.509 certificates for the mail user. |
| [ADDRESS_COUNTRY_CODE](#ADDRESS-COUNTRY-CODE) | Specifies the country code portion of the mailing address of the contact. |
| [ADDRESS_TYPE](#ADDRESS-TYPE) | Contains the email address type of a Message object. |
| [AGING_DONT_AGE_ME](#AGING-DONT-AGE-ME) | Specifies whether to automatically archive the message. |
| [ALLOW_EXTERNAL_CHECK](#ALLOW-EXTERNAL-CHECK) | This property is set to TRUE. |
| [ALL_ATTENDEES_STRING](#ALL-ATTENDEES-STRING) | Specifies a list of all the attendees except for the organizer, including resources and unsendable attendees. |
| [ALTERNATE_RECIPIENT](#ALTERNATE-RECIPIENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ALTERNATE_RECIPIENT_ALLOWED](#ALTERNATE-RECIPIENT-ALLOWED) | Specifies whether the sender permits the message to be auto-forwarded. |
| [ANNIVERSARY_EVENT_ENTRY_ID](#ANNIVERSARY-EVENT-ENTRY-ID) | Specifies the EntryID of the Appointment object that represents an anniversary of the contact. |
| [ANR](#ANR) | Contains a filter value used in ambiguous name resolution. |
| [APPLICATION_NAME](#APPLICATION-NAME) | Specifies the application used to open the file attached to the Document object. |
| [APPOINTMENT_AUXILIARY_FLAGS](#APPOINTMENT-AUXILIARY-FLAGS) | Specifies a bit field that describes the auxiliary state of the object. |
| [APPOINTMENT_COLOR](#APPOINTMENT-COLOR) | Specifies the color to be used when displaying the Calendar object. |
| [APPOINTMENT_COUNTER_PROPOSAL](#APPOINTMENT-COUNTER-PROPOSAL) | Indicates whether a Meeting Response object is a counter proposal. |
| [APPOINTMENT_DURATION](#APPOINTMENT-DURATION) | Specifies the length of the event, in minutes. |
| [APPOINTMENT_END_DATE](#APPOINTMENT-END-DATE) | Indicates the date that the appointment ends. |
| [APPOINTMENT_END_TIME](#APPOINTMENT-END-TIME) | Indicates the time that the appointment ends. |
| [APPOINTMENT_END_WHOLE](#APPOINTMENT-END-WHOLE) | Specifies the end date and time for the event. |
| [APPOINTMENT_LAST_SEQUENCE](#APPOINTMENT-LAST-SEQUENCE) | Indicates to the organizer the last sequence number that was sent to any attendee. |
| [APPOINTMENT_MESSAGE_CLASS](#APPOINTMENT-MESSAGE-CLASS) | Indicates the message class of the Meeting object to be generated from the Meeting Request object. |
| [APPOINTMENT_NOT_ALLOW_PROPOSE](#APPOINTMENT-NOT-ALLOW-PROPOSE) | Indicates whether attendees are not allowed to propose a new date and/or time for the meeting. |
| [APPOINTMENT_PROPOSAL_NUMBER](#APPOINTMENT-PROPOSAL-NUMBER) | Specifies the number of attendees who have sent counter proposals that have not been accepted or rejected by the organizer. |
| [APPOINTMENT_PROPOSED_DURATION](#APPOINTMENT-PROPOSED-DURATION) | Indicates the proposed value for the PidLidAppointmentDuration property (section 2.11) for a counter proposal. |
| [APPOINTMENT_PROPOSED_END_WHOLE](#APPOINTMENT-PROPOSED-END-WHOLE) | Specifies the proposed value for the PidLidAppointmentEndWhole property (section 2.14) for a counter proposal. |
| [APPOINTMENT_PROPOSED_START_WHOLE](#APPOINTMENT-PROPOSED-START-WHOLE) | Specifies the proposed value for the PidLidAppointmentStartWhole property (section 2.29) for a counter proposal. |
| [APPOINTMENT_RECUR](#APPOINTMENT-RECUR) | Specifies the dates and times when a recurring series occurs. |
| [APPOINTMENT_REPLY_NAME](#APPOINTMENT-REPLY-NAME) | Specifies the user who last replied to the meeting request or meeting update. |
| [APPOINTMENT_REPLY_TIME](#APPOINTMENT-REPLY-TIME) | Specifies the date and time at which the attendee responded to a received meeting request or Meeting Update object. |
| [APPOINTMENT_SEQUENCE](#APPOINTMENT-SEQUENCE) | Specifies the sequence number of a Meeting object. |
| [APPOINTMENT_SEQUENCE_TIME](#APPOINTMENT-SEQUENCE-TIME) | Indicates the date and time at which the PidLidAppointmentSequence property (section 2.25) was last modified. |
| [APPOINTMENT_START_DATE](#APPOINTMENT-START-DATE) | Identifies the date that the appointment starts. |
| [APPOINTMENT_START_TIME](#APPOINTMENT-START-TIME) | Identifies the time that the appointment starts. |
| [APPOINTMENT_START_WHOLE](#APPOINTMENT-START-WHOLE) | Specifies the start date and time of the appointment. |
| [APPOINTMENT_STATE_FLAGS](#APPOINTMENT-STATE-FLAGS) | Specifies a bit field that describes the state of the object. |
| [APPOINTMENT_SUB_TYPE](#APPOINTMENT-SUB-TYPE) | Specifies whether the event is an all-day event. |
| [APPOINTMENT_TIME_ZONE_DEFINITION_END_DISPLAY](#APPOINTMENT-TIME-ZONE-DEFINITION-END-DISPLAY) | Specifies time zone information that indicates the time zone of the PidLidAppointmentEndWhole property (section 2.14). |
| [APPOINTMENT_TIME_ZONE_DEFINITION_RECUR](#APPOINTMENT-TIME-ZONE-DEFINITION-RECUR) | Specifies time zone information that describes how to convert the meeting date and time on a recurring series to and from UTC. |
| [APPOINTMENT_TIME_ZONE_DEFINITION_START_DISPLAY](#APPOINTMENT-TIME-ZONE-DEFINITION-START-DISPLAY) | Specifies time zone information that indicates the time zone of the PidLidAppointmentStartWhole property (section 2.29). |
| [APPOINTMENT_UNSENDABLE_RECIPIENTS](#APPOINTMENT-UNSENDABLE-RECIPIENTS) | Contains a list of unsendable attendees. |
| [APPOINTMENT_UPDATE_TIME](#APPOINTMENT-UPDATE-TIME) | Indicates the time at which the appointment was last updated. |
| [ARCHIVE_DATE](#ARCHIVE-DATE) | Specifies the date, in UTC, after which a Message object is archived by the server. |
| [ARCHIVE_PERIOD](#ARCHIVE-PERIOD) | Specifies the number of days that a Message object can remain unarchived. |
| [ARCHIVE_TAG](#ARCHIVE-TAG) | Specifies the GUID of an archive tag. |
| [ARRIVAL_TIME](#ARRIVAL-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ASSISTANT](#ASSISTANT) | Contains the name of the mail user's administrative assistant. |
| [ASSISTANT_TELEPHONE_NUMBER](#ASSISTANT-TELEPHONE-NUMBER) | Contains the telephone number of the mail user's administrative assistant. |
| [ASSOCIATED](#ASSOCIATED) | Specifies whether the message being synchronized is an FAI message. |
| [ASSOC_CONTENT_COUNT](#ASSOC-CONTENT-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ASSOC_MESSAGE_SIZE](#ASSOC-MESSAGE-SIZE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ASSOC_MESSAGE_SIZE_EXTENDED](#ASSOC-MESSAGE-SIZE-EXTENDED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ASSOC_MSG_W_ATTACH_COUNT](#ASSOC-MSG-W-ATTACH-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ATTACHMENT_CONTACT_PHOTO](#ATTACHMENT-CONTACT-PHOTO) | Indicates that a contact photo attachment is attached to a Contact object. |
| [ATTACHMENT_FLAGS](#ATTACHMENT-FLAGS) | Indicates special handling for an Attachment object. |
| [ATTACHMENT_HIDDEN](#ATTACHMENT-HIDDEN) | Indicates whether an Attachment object is hidden from the end user. |
| [ATTACHMENT_IS_FOLDER](#ATTACHMENT-IS-FOLDER) | A value indicating whether the attachment points to a folder. |
| [ATTACHMENT_LINK_ID](#ATTACHMENT-LINK-ID) | Contains the type of Message object to which an attachment is linked. |
| [ATTACHMENT_MAC_CONTENT_TYPE](#ATTACHMENT-MAC-CONTENT-TYPE) | Contains the Content-Type of the Mac attachment. |
| [ATTACHMENT_MAC_INFO](#ATTACHMENT-MAC-INFO) | Contains the headers and resource fork data associated with the Mac attachment. |
| [ATTACHMENT_ORIGINAL_PERMISSION_TYPE](#ATTACHMENT-ORIGINAL-PERMISSION-TYPE) | The original permission of the attachment. |
| [ATTACHMENT_ORIGINAL_URL](#ATTACHMENT-ORIGINAL-URL) | The original URL of the attachment. |
| [ATTACHMENT_PERMISSION_TYPE](#ATTACHMENT-PERMISSION-TYPE) | The permission of the attachment. |
| [ATTACHMENT_PREVIEW_URL](#ATTACHMENT-PREVIEW-URL) | The URL of the attachment preview. |
| [ATTACHMENT_PROVIDER_ENDPOINT_URL](#ATTACHMENT-PROVIDER-ENDPOINT-URL) | The URL of the attachment provider. |
| [ATTACHMENT_PROVIDER_TYPE](#ATTACHMENT-PROVIDER-TYPE) | The type of the attachment provider. |
| [ATTACHMENT_THUMBNAIL_URL](#ATTACHMENT-THUMBNAIL-URL) | The URL of the attachment thumbnail. |
| [ATTACHMENT_X_400_PARAMETERS](#ATTACHMENT-X-400-PARAMETERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ATTACH_ADDITIONAL_INFORMATION](#ATTACH-ADDITIONAL-INFORMATION) | Contains attachment encoding information. |
| [ATTACH_CONTENT_BASE](#ATTACH-CONTENT-BASE) | Contains the base of a relative URI. |
| [ATTACH_CONTENT_ID](#ATTACH-CONTENT-ID) | Contains a content identifier unique to the Message object that matches a corresponding Area: Message Attachment Properties Canonical name: PidTagAttachContentId Alternate names: PR\_ATTACH\_CONTENT\_ID, PR\_ATTACH\_CONTENT\_ID\_A, PR\_ATTACH\_CONTENT\_ID\_W |
| [ATTACH_CONTENT_LOCATION](#ATTACH-CONTENT-LOCATION) | Contains a relative or full URI that matches a corresponding reference in the HTML body of a Message object. |
| [ATTACH_DATA_BINARY](#ATTACH-DATA-BINARY) | Contains the contents of the file to be attached. |
| [ATTACH_DATA_OBJECT](#ATTACH-DATA-OBJECT) | Contains the binary representation of the Attachment object in an application-specific format. |
| [ATTACH_ENCODING](#ATTACH-ENCODING) | Contains encoding information about the Attachment object. |
| [ATTACH_EXTENSION](#ATTACH-EXTENSION) | Contains a file name extension that indicates the document type of an attachment. |
| [ATTACH_FILENAME](#ATTACH-FILENAME) | Contains the 8.3 name of the PidTagAttachLongFilename property (section 2.586). |
| [ATTACH_FLAGS](#ATTACH-FLAGS) | Indicates which body formats might reference this attachment when rendering data. |
| [ATTACH_LONG_FILENAME](#ATTACH-LONG-FILENAME) | Contains the full filename and extension of the Attachment object. |
| [ATTACH_LONG_PATHNAME](#ATTACH-LONG-PATHNAME) | Contains the fully-qualified path and file name with extension. |
| [ATTACH_METHOD](#ATTACH-METHOD) | Represents the way the contents of an attachment are accessed. |
| [ATTACH_MIME_TAG](#ATTACH-MIME-TAG) | Contains a content-type MIME header. |
| [ATTACH_NUMBER](#ATTACH-NUMBER) | Identifies the Attachment object within its Message object. |
| [ATTACH_ON_ASSOC_MSG_COUNT](#ATTACH-ON-ASSOC-MSG-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ATTACH_ON_NORMAL_MSG_COUNT](#ATTACH-ON-NORMAL-MSG-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ATTACH_PATHNAME](#ATTACH-PATHNAME) | Contains the 8.3 name of the PidTagAttachLongPathname property (section 2.587). |
| [ATTACH_PAYLOAD_CLASS](#ATTACH-PAYLOAD-CLASS) | Contains the class name of an object that can display the contents of the message. |
| [ATTACH_PAYLOAD_PROVIDER_GUID_STRING](#ATTACH-PAYLOAD-PROVIDER-GUID-STRING) | Contains the GUID of the software component that can display the contents of the message. |
| [ATTACH_RENDERING](#ATTACH-RENDERING) | Contains a Windows Metafile, as specified in [MS-WMF], for the Attachment object. |
| [ATTACH_SIZE](#ATTACH-SIZE) | Contains the size, in bytes, consumed by the Attachment object on the server. |
| [ATTACH_TAG](#ATTACH-TAG) | Contains the identifier information for the application that supplied the Attachment object data. |
| [ATTACH_TRANSPORT_NAME](#ATTACH-TRANSPORT-NAME) | Contains the name of an attachment file, modified so that it can be correlated with TNEF messages. |
| [ATTENDEE_CRITICAL_CHANGE](#ATTENDEE-CRITICAL-CHANGE) | Specifies the date and time at which the meeting-related object was sent. |
| [ATTRIBUTE_HIDDEN](#ATTRIBUTE-HIDDEN) | Specifies the hide or show status of a folder. |
| [ATTRIBUTE_READ_ONLY](#ATTRIBUTE-READ-ONLY) | Indicates whether an item can be modified or deleted. |
| [AUDIO_NOTES](#AUDIO-NOTES) | Contains textual annotations to a voice message after it has been delivered to the user's mailbox. |
| [AUTHOR](#AUTHOR) | Specifies the author of the file attached to the Document object. |
| [AUTHORIZING_USERS](#AUTHORIZING-USERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [AUTOMATIC_SPEECH_RECOGNITION_DATA](#AUTOMATIC-SPEECH-RECOGNITION-DATA) | Contains an unprotected voice message. |
| [AUTO_ADD_NEW_SUBS](#AUTO-ADD-NEW-SUBS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [AUTO_FILL_LOCATION](#AUTO-FILL-LOCATION) | Indicates whether the value of the PidLidLocation property (section 2.159) is set to the PidTagDisplayName property (section 2.667). |
| [AUTO_FORWARDED](#AUTO-FORWARDED) | Indicates that a Message object has been automatically generated or automatically forwarded. |
| [AUTO_FORWARD_COMMENT](#AUTO-FORWARD-COMMENT) | Contains text included in an automatically-generated message. |
| [AUTO_LOG](#AUTO-LOG) | Specifies to the application whether to create a Journal object for each action associated with this Contact object. |
| [AUTO_PROCESS_STATE](#AUTO-PROCESS-STATE) | Specifies the options used in the automatic processing of email messages. |
| [AUTO_RESPONSE_SUPPRESS](#AUTO-RESPONSE-SUPPRESS) | Specifies whether a client or server application should forego sending automated replies in response to this message. |
| [AUTO_START_CHECK](#AUTO-START-CHECK) | Specifies whether to automatically start the conferencing application when a reminder for the start of a meeting is executed. |
| [BILATERAL_INFO](#BILATERAL-INFO) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [BILLING](#BILLING) | Specifies billing information for the contact. |
| [BIRTHDAY](#BIRTHDAY) | Contains the date of the mail user's birthday at midnight. |
| [BIRTHDAY_EVENT_ENTRY_ID](#BIRTHDAY-EVENT-ENTRY-ID) | Specifies the EntryID of an optional Appointment object that represents the birthday of the contact. |
| [BIRTHDAY_LOCAL](#BIRTHDAY-LOCAL) | Specifies the birthday of a contact. |
| [BLOCK_STATUS](#BLOCK-STATUS) | Indicates the user's preference for viewing external content (such as links to images on an HTTP server) in the message body. |
| [BODY](#BODY) | Contains message body text in plain text format. |
| [BODY_CONTENT_ID](#BODY-CONTENT-ID) | Contains a GUID that corresponds to the current message body. |
| [BODY_CONTENT_LOCATION](#BODY-CONTENT-LOCATION) | Contains a globally unique Uniform Resource Identifier (URI) that serves as a label for the current message body. |
| [BODY_CRC](#BODY-CRC) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [BODY_HTML](#BODY-HTML) | Contains the HTML body of the Message object. |
| [BUSINESS_2_TELEPHONE_NUMBER](#BUSINESS-2-TELEPHONE-NUMBER) | Contains a secondary telephone number at the mail user's place of business. |
| [BUSINESS_2_TELEPHONE_NUMBERS](#BUSINESS-2-TELEPHONE-NUMBERS) | Contains secondary telephone numbers at the mail user's place of business. |
| [BUSINESS_CARD_CARD_PICTURE](#BUSINESS-CARD-CARD-PICTURE) | Contains the image to be used on a business card. |
| [BUSINESS_CARD_DISPLAY_DEFINITION](#BUSINESS-CARD-DISPLAY-DEFINITION) | Contains user customization details for displaying a contact as a business card. |
| [BUSINESS_FAX_NUMBER](#BUSINESS-FAX-NUMBER) | Contains the telephone number of the mail user's business fax machine. |
| [BUSINESS_HOME_PAGE](#BUSINESS-HOME-PAGE) | Contains the URL of the mail user's business home page. |
| [BUSINESS_TELEPHONE_NUMBER](#BUSINESS-TELEPHONE-NUMBER) | Contains the primary telephone number of the mail user's place of business. |
| [BUSY_STATUS](#BUSY-STATUS) | Specifies the availability of a user for the event described by the object. |
| [BYTE_COUNT](#BYTE-COUNT) | Specifies the size, in bytes, of the file attached to the Document object. |
| [CACHED_COLUMN_COUNT](#CACHED-COLUMN-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CALENDAR_ATTENDEE_ROLE](#CALENDAR-ATTENDEE-ROLE) | Specifies the role of the attendee. |
| [CALENDAR_BUSYSTATUS](#CALENDAR-BUSYSTATUS) | Specifies whether the attendee is busy at the time of an appointment on their calendar. |
| [CALENDAR_CONTACT](#CALENDAR-CONTACT) | Identifies the name of a contact who is an attendee of a meeting. |
| [CALENDAR_CONTACT_URL](#CALENDAR-CONTACT-URL) | Identifies the URL where you can access contact information in HTML format. |
| [CALENDAR_CREATED](#CALENDAR-CREATED) | Identifies the date and time, in UTC, when the organizer created the appointment or meeting. |
| [CALENDAR_DESCRIPTION_URL](#CALENDAR-DESCRIPTION-URL) | Specifies the URL of a resource that contains a description of an appointment or meeting. |
| [CALENDAR_DURATION](#CALENDAR-DURATION) | Identifies the duration, in seconds, of an appointment or meeting. |
| [CALENDAR_EXCEPTION_DATE](#CALENDAR-EXCEPTION-DATE) | Identifies a list of dates that are exceptions to a recurring appointment. |
| [CALENDAR_EXCEPTION_RULE](#CALENDAR-EXCEPTION-RULE) | Specifies an exception rule for a recurring appointment. |
| [CALENDAR_GEO_LATITUDE](#CALENDAR-GEO-LATITUDE) | Specifies the geographical latitude of the location of an appointment. |
| [CALENDAR_GEO_LONGITUDE](#CALENDAR-GEO-LONGITUDE) | Specifies the geographical longitude of the location of an appointment. |
| [CALENDAR_INSTANCE_TYPE](#CALENDAR-INSTANCE-TYPE) | Specifies the type of an appointment. |
| [CALENDAR_IS_ORGANIZER](#CALENDAR-IS-ORGANIZER) | Specifies whether an attendee is the organizer of an appointment or meeting. |
| [CALENDAR_LAST_MODIFIED](#CALENDAR-LAST-MODIFIED) | Specifies the date and time, in UTC, when an appointment was last modified. |
| [CALENDAR_LOCATION_URL](#CALENDAR-LOCATION-URL) | Specifies a URL with location information in HTML format. |
| [CALENDAR_MEETING_STATUS](#CALENDAR-MEETING-STATUS) | Specifies the status of an appointment or meeting. |
| [CALENDAR_METHOD](#CALENDAR-METHOD) | Specifies the iCalendar method that is associated with an Appointment object. |
| [CALENDAR_PRODUCT_ID](#CALENDAR-PRODUCT-ID) | Identifies the product that created the iCalendar-formatted stream. |
| [CALENDAR_RECURRENCE_ID_RANGE](#CALENDAR-RECURRENCE-ID-RANGE) | Specifies which instances of a recurring appointment are being referred to. |
| [CALENDAR_REMINDER_OFFSET](#CALENDAR-REMINDER-OFFSET) | Identifies the number of seconds before an appointment starts that a reminder is to be displayed. |
| [CALENDAR_RESOURCES](#CALENDAR-RESOURCES) | Identifies a list of resources, such as rooms and video equipment, that are available for an appointment. |
| [CALENDAR_RSVP](#CALENDAR-RSVP) | Specifies whether the organizer of an appointment or meeting requested a response. |
| [CALENDAR_SEQUENCE](#CALENDAR-SEQUENCE) | Specifies the sequence number of a version of an appointment. |
| [CALENDAR_TIME_ZONE](#CALENDAR-TIME-ZONE) | Specifies the time zone of an appointment or meeting. |
| [CALENDAR_TIME_ZONE_ID](#CALENDAR-TIME-ZONE-ID) | Specifies the time zone identifier of an appointment or meeting. |
| [CALENDAR_TRANSPARENT](#CALENDAR-TRANSPARENT) | Specifies whether an appointment or meeting is visible to busy time searches. |
| [CALENDAR_TYPE](#CALENDAR-TYPE) | Contains the value of the CalendarType field from the PidLidAppointmentRecur property (section 2.22). |
| [CALENDAR_UID](#CALENDAR-UID) | Specifies the unique identifier of an appointment or meeting. |
| [CALENDAR_VERSION](#CALENDAR-VERSION) | Identifies the version of the iCalendar specification, as specified in [MS-OXCICAL] section 2.1.3.1.1.3, that is required to correctly interpret an iCalendar object. |
| [CALLBACK_TELEPHONE_NUMBER](#CALLBACK-TELEPHONE-NUMBER) | Contains a telephone number to reach the mail user. |
| [CALL_ID](#CALL-ID) | Contains a unique identifier associated with the phone call. |
| [CAR_TELEPHONE_NUMBER](#CAR-TELEPHONE-NUMBER) | Contains the mail user's car telephone number. |
| [CATEGORIES](#CATEGORIES) | Contains the array of text labels assigned to this Message object. |
| [CATEGORY](#CATEGORY) | Specifies the category of the file attached to the Document object. |
| [CATEG_COUNT](#CATEG-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CC_ATTENDEES_STRING](#CC-ATTENDEES-STRING) | Contains a list of all the sendable attendees who are also optional attendees. |
| [CDO_RECURRENCEID](#CDO-RECURRENCEID) | Identifies a specific instance of a recurring appointment. |
| [CHANGE_ADVISOR](#CHANGE-ADVISOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CHANGE_HIGHLIGHT](#CHANGE-HIGHLIGHT) | Specifies a bit field that indicates how the Meeting object has changed. |
| [CHANGE_KEY](#CHANGE-KEY) | Contains a structure that identifies the last change to the object. |
| [CHANGE_NOTIFICATION_GUID](#CHANGE-NOTIFICATION-GUID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CHANGE_NUMBER](#CHANGE-NUMBER) | Contains a structure that identifies the last change to the message or folder that is currently being synchronized. |
| [CHARACTER_COUNT](#CHARACTER-COUNT) | Specifies the character count of the file attached to the Document object. |
| [CHILDRENS_NAMES](#CHILDRENS-NAMES) | Specifies the names of the children of the contact. |
| [CLASSIFICATION](#CLASSIFICATION) | Contains a list of the classification categories to which the associated Message object has been assigned. |
| [CLASSIFICATION_DESCRIPTION](#CLASSIFICATION-DESCRIPTION) | Contains a human-readable summary of each of the classification categories included in the PidLidClassification property (section 2.53). |
| [CLASSIFICATION_GUID](#CLASSIFICATION-GUID) | Contains the GUID that identifies the list of email classification categories used by a Message object. |
| [CLASSIFICATION_KEEP](#CLASSIFICATION-KEEP) | Indicates whether the message uses any classification categories. |
| [CLASSIFIED](#CLASSIFIED) | Indicates whether the contents of this message are regarded as classified information. |
| [CLEAN_GLOBAL_OBJECT_ID](#CLEAN-GLOBAL-OBJECT-ID) | Contains the value of the PidLidGlobalObjectId property (section 2.142) for an object all zero. |
| [CLIENT_ACTIONS](#CLIENT-ACTIONS) | Specifies the actions the client is required to take on the message. |
| [CLIENT_INTENT](#CLIENT-INTENT) | Indicates what actions the user has taken on this Meeting object. |
| [CLIENT_SUBMIT_TIME](#CLIENT-SUBMIT-TIME) | Contains the current time, in UTC, when the email message is submitted. |
| [CLIP_END](#CLIP-END) | Specifies the end date and time of the event in UTC. |
| [CLIP_START](#CLIP-START) | Specifies the start date and time of the event in UTC. |
| [CODE_PAGE_ID](#CODE-PAGE-ID) | Contains the identifier for the client code page used for Unicode to double-byte character set (DBCS) string conversion. |
| [COLLABORATE_DOC](#COLLABORATE-DOC) | Specifies the document to be launched when the user joins the meeting. |
| [COLLECTOR](#COLLECTOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [COMMENT](#COMMENT) | Contains a comment about the purpose or content of the Address Book object. |
| [COMMENTS](#COMMENTS) | Specifies the comments of the file attached to the Document object. |
| [COMMON_END](#COMMON-END) | Indicates the end time for the Message object. |
| [COMMON_START](#COMMON-START) | Indicates the start time for the Message object. |
| [COMMON_VIEWS_ENTRYID](#COMMON-VIEWS-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [COMPANIES](#COMPANIES) | Contains a list of company names, each of which is associated with a contact that is specified in the PidLidContacts property ([MS-OXCMSG] section 2.2.1.57.2). |
| [COMPANY](#COMPANY) | Specifies the company for which the file was created. |
| [COMPANY_MAIN_TELEPHONE_NUMBER](#COMPANY-MAIN-TELEPHONE-NUMBER) | Contains the main telephone number of the mail user's company. |
| [COMPANY_NAME](#COMPANY-NAME) | Contains the mail user's company name. |
| [COMPUTER_NETWORK_NAME](#COMPUTER-NETWORK-NAME) | Contains the name of the mail user's computer network. |
| [CONFERENCING_CHECK](#CONFERENCING-CHECK) | Area: Conferencing Canonical name: PidLidConferencingCheck Alternate names: dispidConfCheck |
| [CONFERENCING_TYPE](#CONFERENCING-TYPE) | Specifies the type of the meeting. |
| [CONFLICT_ENTRY_ID](#CONFLICT-ENTRY-ID) | Contains the EntryID of the conflict resolve message. |
| [CONTACTS](#CONTACTS) | Contains the PidTagDisplayName property (section 2.667) of each Address Book EntryID referenced in the value of the PidLidContactLinkEntry property (section 2.70). |
| [CONTACT_ADDRTYPES](#CONTACT-ADDRTYPES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTACT_CHARACTER_SET](#CONTACT-CHARACTER-SET) | Specifies the character set used for a Contact object. |
| [CONTACT_COUNT](#CONTACT-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTACT_DEFAULT_ADDRESS_INDEX](#CONTACT-DEFAULT-ADDRESS-INDEX) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTACT_EMAIL_ADDRESSES](#CONTACT-EMAIL-ADDRESSES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTACT_ENTRYIDS](#CONTACT-ENTRYIDS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTACT_ITEM_DATA](#CONTACT-ITEM-DATA) | Specifies the visible fields in the application's user interface that are used to help display the contact information. |
| [CONTACT_LINKED_GLOBAL_ADDRESS_LIST_ENTRY_ID](#CONTACT-LINKED-GLOBAL-ADDRESS-LIST-ENTRY-ID) | Specifies the EntryID of the GAL contact to which the duplicate contact is linked. |
| [CONTACT_LINK_ENTRY](#CONTACT-LINK-ENTRY) | Contains the elements of the PidLidContacts property (section 2.77). |
| [CONTACT_LINK_GLOBAL_ADDRESS_LIST_LINK_ID](#CONTACT-LINK-GLOBAL-ADDRESS-LIST-LINK-ID) | Specifies the GUID of the GAL contact to which the duplicate contact is linked. |
| [CONTACT_LINK_GLOBAL_ADDRESS_LIST_LINK_STATE](#CONTACT-LINK-GLOBAL-ADDRESS-LIST-LINK-STATE) | Specifies the state of the linking between the GAL contact and the duplicate contact. |
| [CONTACT_LINK_LINK_REJECT_HISTORY](#CONTACT-LINK-LINK-REJECT-HISTORY) | Contains a list of GAL contacts that were previously rejected for linking with the duplicate contact. |
| [CONTACT_LINK_NAME](#CONTACT-LINK-NAME) | Area: Contact Properties Canonical name: PidLidContactLinkName Alternate names: dispidContactLinkName |
| [CONTACT_LINK_SEARCH_KEY](#CONTACT-LINK-SEARCH-KEY) | Contains the list of SearchKeys for a Contact object linked to by the Message object. |
| [CONTACT_LINK_SMTP_ADDRESS_CACHE](#CONTACT-LINK-SMTP-ADDRESS-CACHE) | Contains a list of the SMTP addresses that are used by the contact. |
| [CONTACT_USER_FIELD_1](#CONTACT-USER-FIELD-1) | Contains text used to add custom text to a business card representation of a Contact object. |
| [CONTACT_USER_FIELD_2](#CONTACT-USER-FIELD-2) | Contains text used to add custom text to a business card representation of a Contact object. |
| [CONTACT_USER_FIELD_3](#CONTACT-USER-FIELD-3) | Contains text used to add custom text to a business card representation of a Contact object. |
| [CONTACT_USER_FIELD_4](#CONTACT-USER-FIELD-4) | Contains text used to add custom text to a business card representation of a Contact object. |
| [CONTACT_VERSION](#CONTACT-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTAINER_CLASS](#CONTAINER-CLASS) | Contains a string value that describes the type of Message object that a folder contains. |
| [CONTAINER_CONTENTS](#CONTAINER-CONTENTS) | Always empty. |
| [CONTAINER_FLAGS](#CONTAINER-FLAGS) | Contains a bitmask of flags that describe capabilities of an address book container. |
| [CONTAINER_HIERARCHY](#CONTAINER-HIERARCHY) | Identifies all of the subfolders of the current folder. |
| [CONTAINER_MODIFY_VERSION](#CONTAINER-MODIFY-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTENTS_SORT_ORDER](#CONTENTS-SORT-ORDER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTENTS_SYNCHRONIZER](#CONTENTS-SYNCHRONIZER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTENT_BASE](#CONTENT-BASE) | Specifies the value of the MIME Content-Base header, which defines the base URI for resolving relative URLs contained within the message body. |
| [CONTENT_CLASS](#CONTENT-CLASS) | Contains a string that identifies the type of content of a Message object. |
| [CONTENT_CONFIDENTIALITY_ALGORITHM_ID](#CONTENT-CONFIDENTIALITY-ALGORITHM-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTENT_CORRELATOR](#CONTENT-CORRELATOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTENT_COUNT](#CONTENT-COUNT) | Specifies the number of rows under the header row. |
| [CONTENT_FILTER_SPAM_CONFIDENCE_LEVEL](#CONTENT-FILTER-SPAM-CONFIDENCE-LEVEL) | Indicates a confidence level that the message is spam. |
| [CONTENT_IDENTIFIER](#CONTENT-IDENTIFIER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTENT_INTEGRITY_CHECK](#CONTENT-INTEGRITY-CHECK) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTENT_LENGTH](#CONTENT-LENGTH) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTENT_RETURN_REQUESTED](#CONTENT-RETURN-REQUESTED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTENT_SEARCH_KEY](#CONTENT-SEARCH-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTENT_TYPE](#CONTENT-TYPE) | Specifies the type of the body part content. |
| [CONTENT_UNREAD_COUNT](#CONTENT-UNREAD-COUNT) | Specifies the number of rows under the header row that have the PidTagRead property (section 2.869) set to FALSE. |
| [CONTROL_FLAGS](#CONTROL-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTROL_ID](#CONTROL-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTROL_STRUCTURE](#CONTROL-STRUCTURE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONTROL_TYPE](#CONTROL-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONVERSATION_ACTION_LAST_APPLIED_TIME](#CONVERSATION-ACTION-LAST-APPLIED-TIME) | Contains the time, in UTC, that an Email object was last received in the conversation, or the last time that the user modified the conversation action, whichever occurs later. |
| [CONVERSATION_ACTION_MAX_DELIVERY_TIME](#CONVERSATION-ACTION-MAX-DELIVERY-TIME) | Contains the maximum value of the PidTagMessageDeliveryTime property (section conversation action on the client. |
| [CONVERSATION_ACTION_MOVE_FOLDER_EID](#CONVERSATION-ACTION-MOVE-FOLDER-EID) | Contains the EntryID for the destination folder. |
| [CONVERSATION_ACTION_MOVE_STORE_EID](#CONVERSATION-ACTION-MOVE-STORE-EID) | Contains the EntryID for a move to a folder in a different message store. |
| [CONVERSATION_ACTION_VERSION](#CONVERSATION-ACTION-VERSION) | Contains the version of the conversation action FAI message. |
| [CONVERSATION_ID](#CONVERSATION-ID) | Contains a computed value derived from other conversation-related properties. |
| [CONVERSATION_INDEX](#CONVERSATION-INDEX) | Indicates the relative position of this message within a conversation thread. |
| [CONVERSATION_INDEX_TRACKING](#CONVERSATION-INDEX-TRACKING) | Indicates whether the GUID portion of the PidTagConversationIndex property (section 2.641) is to be used to compute the PidTagConversationId property (section 2.640). |
| [CONVERSATION_KEY](#CONVERSATION-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONVERSATION_PROCESSED](#CONVERSATION-PROCESSED) | Specifies a sequential number to be used in the processing of a conversation action. |
| [CONVERSATION_TOPIC](#CONVERSATION-TOPIC) | Contains an unchanging copy of the original subject. |
| [CONVERSION_EITS](#CONVERSION-EITS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONVERSION_PROHIBITED](#CONVERSION-PROHIBITED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONVERSION_WITH_LOSS_PROHIBITED](#CONVERSION-WITH-LOSS-PROHIBITED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CONVERTED_EITS](#CONVERTED-EITS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CORRELATE](#CORRELATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CORRELATE_MTSID](#CORRELATE-MTSID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [COUNTRY](#COUNTRY) | Contains the name of the mail user's country/region. |
| [CREATE_DATE_TIME_READ_ONLY](#CREATE-DATE-TIME-READ-ONLY) | Specifies the time, in UTC, that the file was first created. |
| [CREATE_TEMPLATES](#CREATE-TEMPLATES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CREATION_TIME](#CREATION-TIME) | Contains the time, in UTC, that the object was created. |
| [CREATION_VERSION](#CREATION-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [CREATOR_ENTRY_ID](#CREATOR-ENTRY-ID) | Specifies the original author of the message according to their Address Book EntryID. |
| [CREATOR_NAME](#CREATOR-NAME) | Contains the name of the creator of a Message object. |
| [CROSS_REFERENCE](#CROSS-REFERENCE) | Contains the name of the host (with domains omitted) and a white-space-separated list of colon-separated pairs of newsgroup names and message numbers. |
| [CURRENT_VERSION](#CURRENT-VERSION) | Specifies the build number of the client application that sent the message. |
| [CURRENT_VERSION_NAME](#CURRENT-VERSION-NAME) | Specifies the name of the client application that sent the message. |
| [CUSTOMER_ID](#CUSTOMER-ID) | Contains the mail user's customer identification number. |
| [DAM_BACK_PATCHED](#DAM-BACK-PATCHED) | Indicates whether the Deferred Action Message (DAM) was updated by the server. |
| [DAM_ORIGINAL_ENTRY_ID](#DAM-ORIGINAL-ENTRY-ID) | Contains the EntryID of the delivered message that the client has to process. |
| [DAV_ID](#DAV-ID) | Specifies a unique ID for the calendar item. |
| [DAV_IS_COLLECTION](#DAV-IS-COLLECTION) | Indicates whether a Calendar object is a collection. |
| [DAV_IS_STRUCTURED_DOCUMENT](#DAV-IS-STRUCTURED-DOCUMENT) | Indicates whether a Calendar object is a structured document. |
| [DAV_PARENT_NAME](#DAV-PARENT-NAME) | Specifies the name of the Folder object that contains the Calendar object. |
| [DAV_UID](#DAV-UID) | Specifies the unique identifier for an item. |
| [DAY_INTERVAL](#DAY-INTERVAL) | Identifies the day interval for the recurrence pattern. |
| [DAY_OF_MONTH](#DAY-OF-MONTH) | Identifies the day of the month for the appointment or meeting. |
| [DEFAULT_POST_MESSAGE_CLASS](#DEFAULT-POST-MESSAGE-CLASS) | Contains the message class of the object. |
| [DEFAULT_PROFILE](#DEFAULT-PROFILE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DEFAULT_STORE](#DEFAULT-STORE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DEFAULT_VIEW_ENTRYID](#DEFAULT-VIEW-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DEFERRED_ACTION_MESSAGE_ORIGINAL_ENTRY_ID](#DEFERRED-ACTION-MESSAGE-ORIGINAL-ENTRY-ID) | Contains the server EntryID for the DAM. |
| [DEFERRED_DELIVERY_TIME](#DEFERRED-DELIVERY-TIME) | Contains the date and time, in UTC, at which the sender prefers that the message be delivered. |
| [DEFERRED_SEND_NUMBER](#DEFERRED-SEND-NUMBER) | Contains a number used in the calculation of how long to defer sending a message. |
| [DEFERRED_SEND_TIME](#DEFERRED-SEND-TIME) | Contains the amount of time after which a client would like to defer sending the message. |
| [DEFERRED_SEND_UNITS](#DEFERRED-SEND-UNITS) | Specifies the unit of time used as a multiplier with the PidTagDeferredSendNumber property (section 2.654) value. |
| [DEF_CREATE_DL](#DEF-CREATE-DL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DEF_CREATE_MAILUSER](#DEF-CREATE-MAILUSER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DELEGATED_BY_RULE](#DELEGATED-BY-RULE) | Specifies whether the message was forwarded due to the triggering of a delegate forward rule. |
| [DELEGATE_FLAGS](#DELEGATE-FLAGS) | Indicates whether delegates can view Message objects that are marked as private. |
| [DELEGATE_MAIL](#DELEGATE-MAIL) | Indicates whether a delegate responded to the meeting request. |
| [DELEGATION](#DELEGATION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DELETED_ASSOC_MESSAGE_SIZE_EXTENDED](#DELETED-ASSOC-MESSAGE-SIZE-EXTENDED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DELETED_ASSOC_MSG_COUNT](#DELETED-ASSOC-MSG-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DELETED_COUNT_TOTAL](#DELETED-COUNT-TOTAL) | Contains the total count of messages that have been deleted from a folder, excluding messages deleted within subfolders. |
| [DELETED_FOLDER_COUNT](#DELETED-FOLDER-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DELETED_MESSAGE_SIZE_EXTENDED](#DELETED-MESSAGE-SIZE-EXTENDED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DELETED_MSG_COUNT](#DELETED-MSG-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DELETED_NORMAL_MESSAGE_SIZE_EXTENDED](#DELETED-NORMAL-MESSAGE-SIZE-EXTENDED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DELETED_ON](#DELETED-ON) | Specifies the time, in UTC, when the item or folder was soft deleted. |
| [DELETE_AFTER_SUBMIT](#DELETE-AFTER-SUBMIT) | Indicates that the original message is to be deleted after it is sent. |
| [DELIVERY_POINT](#DELIVERY-POINT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DELIVER_TIME](#DELIVER-TIME) | Contains the delivery time for a delivery status notification, as specified [RFC3464], or a message disposition notification, as specified in [RFC3798]. |
| [DELTAX](#DELTAX) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DELTAY](#DELTAY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DEPARTMENT](#DEPARTMENT) | This property is ignored by the server and is set to an empty string by the client. |
| [DEPARTMENT_NAME](#DEPARTMENT-NAME) | Contains a name for the department in which the mail user works. |
| [DEPTH](#DEPTH) | Specifies the number of nested categories in which a given row is contained. |
| [DESIGN_IN_PROGRESS](#DESIGN-IN-PROGRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DETAILS_TABLE](#DETAILS-TABLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DIRECTORY](#DIRECTORY) | Specifies the directory server to be used. |
| [DISABLE_FULL_FIDELITY](#DISABLE-FULL-FIDELITY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DISABLE_WINSOCK](#DISABLE-WINSOCK) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DISCARD_REASON](#DISCARD-REASON) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DISCLOSE_RECIPIENTS](#DISCLOSE-RECIPIENTS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DISCLOSURE_OF_RECIPIENTS](#DISCLOSURE-OF-RECIPIENTS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DISCRETE_VALUES](#DISCRETE-VALUES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DISC_VAL](#DISC-VAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DISPLAY_BCC](#DISPLAY-BCC) | Contains a list of blind carbon copy (Bcc) recipient display names. |
| [DISPLAY_CC](#DISPLAY-CC) | Contains a list of carbon copy (Cc) recipient display names. |
| [DISPLAY_NAME](#DISPLAY-NAME) | Contains the display name of the folder. |
| [DISPLAY_NAME_PREFIX](#DISPLAY-NAME-PREFIX) | Contains the mail user's honorific title. |
| [DISPLAY_TO](#DISPLAY-TO) | Contains a list of the primary recipient display names, separated by semicolons, when an email message has primary recipients . |
| [DISPLAY_TYPE](#DISPLAY-TYPE) | Contains an integer value that indicates how to display an Address Book object in a table or as an addressee on a message. |
| [DISPLAY_TYPE_EX](#DISPLAY-TYPE-EX) | Contains an integer value that indicates how to display an Address Book object in a table or as a recipient on a message. |
| [DISTRIBUTION_LIST_CHECKSUM](#DISTRIBUTION-LIST-CHECKSUM) | Specifies the 32-bit cyclic redundancy check (CRC) polynomial checksum, as property (section 2.96). |
| [DISTRIBUTION_LIST_MEMBERS](#DISTRIBUTION-LIST-MEMBERS) | Specifies the list of EntryIDs of the objects corresponding to the members of the personal distribution list. |
| [DISTRIBUTION_LIST_NAME](#DISTRIBUTION-LIST-NAME) | Specifies the name of the personal distribution list. |
| [DISTRIBUTION_LIST_ONE_OFF_MEMBERS](#DISTRIBUTION-LIST-ONE-OFF-MEMBERS) | Specifies the list of one-off EntryIDs corresponding to the members of the personal distribution list. |
| [DISTRIBUTION_LIST_STREAM](#DISTRIBUTION-LIST-STREAM) | Specifies the list of EntryIDs and one-off EntryIDs corresponding to the members of the personal distribution list. |
| [DL_EXPANSION_HISTORY](#DL-EXPANSION-HISTORY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DL_EXPANSION_PROHIBITED](#DL-EXPANSION-PROHIBITED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DL_REPORT_FLAGS](#DL-REPORT-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [DOCUMENT_PARTS](#DOCUMENT-PARTS) | Specifies the title of each part of the document. |
| [EDIT_TIME](#EDIT-TIME) | Specifies the time that the file was last edited. |
| [EFORMS_FOR_LOCALE_ENTRYID](#EFORMS-FOR-LOCALE-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EFORMS_LOCALE_ID](#EFORMS-LOCALE-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EFORMS_REGISTRY_ENTRYID](#EFORMS-REGISTRY-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMAIL_1_ADDRESS_TYPE](#EMAIL-1-ADDRESS-TYPE) | Specifies the address type of an electronic address. |
| [EMAIL_1_DISPLAY_NAME](#EMAIL-1-DISPLAY-NAME) | Specifies the user-readable display name for the email address. |
| [EMAIL_1_EMAIL_ADDRESS](#EMAIL-1-EMAIL-ADDRESS) | Specifies the email address of the contact. |
| [EMAIL_1_ORIGINAL_DISPLAY_NAME](#EMAIL-1-ORIGINAL-DISPLAY-NAME) | Specifies the SMTP email address that corresponds to the email address for the Contact object. |
| [EMAIL_1_ORIGINAL_ENTRY_ID](#EMAIL-1-ORIGINAL-ENTRY-ID) | Specifies the EntryID of the object corresponding to this electronic address. |
| [EMAIL_2_ADDRESS_TYPE](#EMAIL-2-ADDRESS-TYPE) | Specifies the address type of the electronic address. |
| [EMAIL_2_DISPLAY_NAME](#EMAIL-2-DISPLAY-NAME) | Specifies the user-readable display name for the email address. |
| [EMAIL_2_EMAIL_ADDRESS](#EMAIL-2-EMAIL-ADDRESS) | Specifies the email address of the contact. |
| [EMAIL_2_ORIGINAL_DISPLAY_NAME](#EMAIL-2-ORIGINAL-DISPLAY-NAME) | Specifies the SMTP email address that corresponds to the email address for the Contact object. |
| [EMAIL_2_ORIGINAL_ENTRY_ID](#EMAIL-2-ORIGINAL-ENTRY-ID) | Specifies the EntryID of the object that corresponds to this electronic address. |
| [EMAIL_3_ADDRESS_TYPE](#EMAIL-3-ADDRESS-TYPE) | Specifies the address type of the electronic address. |
| [EMAIL_3_DISPLAY_NAME](#EMAIL-3-DISPLAY-NAME) | Specifies the user-readable display name for the email address. |
| [EMAIL_3_EMAIL_ADDRESS](#EMAIL-3-EMAIL-ADDRESS) | Specifies the email address of the contact. |
| [EMAIL_3_ORIGINAL_DISPLAY_NAME](#EMAIL-3-ORIGINAL-DISPLAY-NAME) | Specifies the SMTP email address that corresponds to the email address for the Contact object. |
| [EMAIL_3_ORIGINAL_ENTRY_ID](#EMAIL-3-ORIGINAL-ENTRY-ID) | Specifies the EntryID of the object that corresponds to this electronic address. |
| [EMAIL_ADDRESS](#EMAIL-ADDRESS) | Contains the email address of a Message object. |
| [EMS_AB_ACCESS_CATEGORY](#EMS-AB-ACCESS-CATEGORY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ACTIVATION_SCHEDULE](#EMS-AB-ACTIVATION-SCHEDULE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ACTIVATION_STYLE](#EMS-AB-ACTIVATION-STYLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ADDRESS_ENTRY_DISPLAY_TABLE](#EMS-AB-ADDRESS-ENTRY-DISPLAY-TABLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ADDRESS_ENTRY_DISPLAY_TABLE_MSDOS](#EMS-AB-ADDRESS-ENTRY-DISPLAY-TABLE-MSDOS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ADDRESS_SYNTAX](#EMS-AB-ADDRESS-SYNTAX) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ADDRESS_TYPE](#EMS-AB-ADDRESS-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ADMD](#EMS-AB-ADMD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ADMIN_DESCRIPTION](#EMS-AB-ADMIN-DESCRIPTION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ADMIN_DISPLAY_NAME](#EMS-AB-ADMIN-DISPLAY-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ADMIN_EXTENSION_DLL](#EMS-AB-ADMIN-EXTENSION-DLL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ALIASED_OBJECT_NAME](#EMS-AB-ALIASED-OBJECT-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ALIASED_OBJECT_NAME_O](#EMS-AB-ALIASED-OBJECT-NAME-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ALT_RECIPIENT](#EMS-AB-ALT-RECIPIENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ALT_RECIPIENT_BL](#EMS-AB-ALT-RECIPIENT-BL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ALT_RECIPIENT_BL_O](#EMS-AB-ALT-RECIPIENT-BL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ALT_RECIPIENT_O](#EMS-AB-ALT-RECIPIENT-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ANCESTOR_ID](#EMS-AB-ANCESTOR-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ANONYMOUS_ACCESS](#EMS-AB-ANONYMOUS-ACCESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ANONYMOUS_ACCOUNT](#EMS-AB-ANONYMOUS-ACCOUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ASSOCIATION_LIFETIME](#EMS-AB-ASSOCIATION-LIFETIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ASSOC_NT_ACCOUNT](#EMS-AB-ASSOC-NT-ACCOUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ASSOC_PROTOCOL_CFG_NNTP](#EMS-AB-ASSOC-PROTOCOL-CFG-NNTP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ASSOC_PROTOCOL_CFG_NNTP_O](#EMS-AB-ASSOC-PROTOCOL-CFG-NNTP-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ASSOC_REMOTE_DXA](#EMS-AB-ASSOC-REMOTE-DXA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ASSOC_REMOTE_DXA_O](#EMS-AB-ASSOC-REMOTE-DXA-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ATTRIBUTE_CERTIFICATE](#EMS-AB-ATTRIBUTE-CERTIFICATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AUTHENTICATION_TO_USE](#EMS-AB-AUTHENTICATION-TO-USE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AUTHORITY_REVOCATION_LIST](#EMS-AB-AUTHORITY-REVOCATION-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AUTHORIZED_DOMAIN](#EMS-AB-AUTHORIZED-DOMAIN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AUTHORIZED_PASSWORD](#EMS-AB-AUTHORIZED-PASSWORD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AUTHORIZED_PASSWORD_CONFIRM](#EMS-AB-AUTHORIZED-PASSWORD-CONFIRM) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AUTHORIZED_USER](#EMS-AB-AUTHORIZED-USER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AUTH_ORIG_BL](#EMS-AB-AUTH-ORIG-BL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AUTH_ORIG_BL_O](#EMS-AB-AUTH-ORIG-BL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AUTOREPLY](#EMS-AB-AUTOREPLY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AUTOREPLY_MESSAGE](#EMS-AB-AUTOREPLY-MESSAGE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AUTOREPLY_SUBJECT](#EMS-AB-AUTOREPLY-SUBJECT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AVAILABLE_AUTHORIZATION_PACKAGES](#EMS-AB-AVAILABLE-AUTHORIZATION-PACKAGES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_AVAILABLE_DISTRIBUTIONS](#EMS-AB-AVAILABLE-DISTRIBUTIONS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_BRIDGEHEAD_SERVERS](#EMS-AB-BRIDGEHEAD-SERVERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_BRIDGEHEAD_SERVERS_O](#EMS-AB-BRIDGEHEAD-SERVERS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_BUSINESS_CATEGORY](#EMS-AB-BUSINESS-CATEGORY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_BUSINESS_ROLES](#EMS-AB-BUSINESS-ROLES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_CREATE_PF](#EMS-AB-CAN-CREATE-PF) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_CREATE_PF_BL](#EMS-AB-CAN-CREATE-PF-BL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_CREATE_PF_BL_O](#EMS-AB-CAN-CREATE-PF-BL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_CREATE_PF_DL](#EMS-AB-CAN-CREATE-PF-DL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_CREATE_PF_DL_BL](#EMS-AB-CAN-CREATE-PF-DL-BL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_CREATE_PF_DL_BL_O](#EMS-AB-CAN-CREATE-PF-DL-BL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_CREATE_PF_DL_O](#EMS-AB-CAN-CREATE-PF-DL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_CREATE_PF_O](#EMS-AB-CAN-CREATE-PF-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_NOT_CREATE_PF](#EMS-AB-CAN-NOT-CREATE-PF) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_NOT_CREATE_PF_BL](#EMS-AB-CAN-NOT-CREATE-PF-BL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_NOT_CREATE_PF_BL_O](#EMS-AB-CAN-NOT-CREATE-PF-BL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_NOT_CREATE_PF_DL](#EMS-AB-CAN-NOT-CREATE-PF-DL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_NOT_CREATE_PF_DL_BL](#EMS-AB-CAN-NOT-CREATE-PF-DL-BL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_NOT_CREATE_PF_DL_BL_O](#EMS-AB-CAN-NOT-CREATE-PF-DL-BL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_NOT_CREATE_PF_DL_O](#EMS-AB-CAN-NOT-CREATE-PF-DL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_NOT_CREATE_PF_O](#EMS-AB-CAN-NOT-CREATE-PF-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CAN_PRESERVE_DNS](#EMS-AB-CAN-PRESERVE-DNS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CA_CERTIFICATE](#EMS-AB-CA-CERTIFICATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CERTIFICATE_CHAIN_V_3](#EMS-AB-CERTIFICATE-CHAIN-V-3) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CERTIFICATE_REVOCATION_LIST](#EMS-AB-CERTIFICATE-REVOCATION-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CERTIFICATE_REVOCATION_LIST_V_1](#EMS-AB-CERTIFICATE-REVOCATION-LIST-V-1) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CERTIFICATE_REVOCATION_LIST_V_3](#EMS-AB-CERTIFICATE-REVOCATION-LIST-V-3) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CHARACTER_SET](#EMS-AB-CHARACTER-SET) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CHARACTER_SET_LIST](#EMS-AB-CHARACTER-SET-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CHILD_RDNS](#EMS-AB-CHILD-RDNS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CLIENT_ACCESS_ENABLED](#EMS-AB-CLIENT-ACCESS-ENABLED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CLOCK_ALERT_OFFSET](#EMS-AB-CLOCK-ALERT-OFFSET) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CLOCK_ALERT_REPAIR](#EMS-AB-CLOCK-ALERT-REPAIR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CLOCK_WARNING_OFFSET](#EMS-AB-CLOCK-WARNING-OFFSET) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CLOCK_WARNING_REPAIR](#EMS-AB-CLOCK-WARNING-REPAIR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_COMPROMISED_KEY_LIST](#EMS-AB-COMPROMISED-KEY-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_COMPUTER_NAME](#EMS-AB-COMPUTER-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CONNECTED_DOMAINS](#EMS-AB-CONNECTED-DOMAINS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CONNECTION_LIST_FILTER](#EMS-AB-CONNECTION-LIST-FILTER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CONNECTION_LIST_FILTER_TYPE](#EMS-AB-CONNECTION-LIST-FILTER-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CONNECTION_TYPE](#EMS-AB-CONNECTION-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CONTAINER_INFO](#EMS-AB-CONTAINER-INFO) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CONTENT_TYPE](#EMS-AB-CONTENT-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CONTROL_MSG_FOLDER_ID](#EMS-AB-CONTROL-MSG-FOLDER-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CONTROL_MSG_RULES](#EMS-AB-CONTROL-MSG-RULES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_COST](#EMS-AB-COST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_COUNTRY_NAME](#EMS-AB-COUNTRY-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CROSS_CERTIFICATE_CRL](#EMS-AB-CROSS-CERTIFICATE-CRL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_CROSS_CERTIFICATE_PAIR](#EMS-AB-CROSS-CERTIFICATE-PAIR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DEFAULT_MESSAGE_FORMAT](#EMS-AB-DEFAULT-MESSAGE-FORMAT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DELEGATE_USER](#EMS-AB-DELEGATE-USER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DELIVERY_MECHANISM](#EMS-AB-DELIVERY-MECHANISM) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DELIVER_AND_REDIRECT](#EMS-AB-DELIVER-AND-REDIRECT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DELIV_EITS](#EMS-AB-DELIV-EITS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DELIV_EXT_CONT_TYPES](#EMS-AB-DELIV-EXT-CONT-TYPES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DELTA_REVOCATION_LIST](#EMS-AB-DELTA-REVOCATION-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DESCRIPTION](#EMS-AB-DESCRIPTION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DESTINATION_INDICATOR](#EMS-AB-DESTINATION-INDICATOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DIAGNOSTIC_REG_KEY](#EMS-AB-DIAGNOSTIC-REG-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DISABLED_GATEWAY_PROXY](#EMS-AB-DISABLED-GATEWAY-PROXY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DISABLE_DEFERRED_COMMIT](#EMS-AB-DISABLE-DEFERRED-COMMIT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DISPLAY_NAME_OVERRIDE](#EMS-AB-DISPLAY-NAME-OVERRIDE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DISPLAY_NAME_SUFFIX](#EMS-AB-DISPLAY-NAME-SUFFIX) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DL_MEMBER_RULE](#EMS-AB-DL-MEMBER-RULE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DL_MEM_REJECT_PERMS_BL](#EMS-AB-DL-MEM-REJECT-PERMS-BL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DL_MEM_REJECT_PERMS_BL_O](#EMS-AB-DL-MEM-REJECT-PERMS-BL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DMD_NAME](#EMS-AB-DMD-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DOMAIN_DEF_ALT_RECIP](#EMS-AB-DOMAIN-DEF-ALT-RECIP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DOMAIN_DEF_ALT_RECIP_O](#EMS-AB-DOMAIN-DEF-ALT-RECIP-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DOMAIN_NAME](#EMS-AB-DOMAIN-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DO_OAB_VERSION](#EMS-AB-DO-OAB-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DSA_SIGNATURE](#EMS-AB-DSA-SIGNATURE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_ADMIN_COPY](#EMS-AB-DXA-ADMIN-COPY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_ADMIN_FORWARD](#EMS-AB-DXA-ADMIN-FORWARD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_ADMIN_UPDATE](#EMS-AB-DXA-ADMIN-UPDATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_APPEND_REQCN](#EMS-AB-DXA-APPEND-REQCN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_CONF_CONTAINER_LIST](#EMS-AB-DXA-CONF-CONTAINER-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_CONF_CONTAINER_LIST_O](#EMS-AB-DXA-CONF-CONTAINER-LIST-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_CONF_REQ_TIME](#EMS-AB-DXA-CONF-REQ-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_CONF_SEQ](#EMS-AB-DXA-CONF-SEQ) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_CONF_SEQ_USN](#EMS-AB-DXA-CONF-SEQ-USN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_EXCHANGE_OPTIONS](#EMS-AB-DXA-EXCHANGE-OPTIONS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_EXPORT_NOW](#EMS-AB-DXA-EXPORT-NOW) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_FLAGS](#EMS-AB-DXA-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_IMPORT_NOW](#EMS-AB-DXA-IMPORT-NOW) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_IMP_SEQ](#EMS-AB-DXA-IMP-SEQ) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_IMP_SEQ_TIME](#EMS-AB-DXA-IMP-SEQ-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_IMP_SEQ_USN](#EMS-AB-DXA-IMP-SEQ-USN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_IN_TEMPLATE_MAP](#EMS-AB-DXA-IN-TEMPLATE-MAP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_LOCAL_ADMIN](#EMS-AB-DXA-LOCAL-ADMIN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_LOCAL_ADMIN_O](#EMS-AB-DXA-LOCAL-ADMIN-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_LOGGING_LEVEL](#EMS-AB-DXA-LOGGING-LEVEL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_NATIVE_ADDRESS_TYPE](#EMS-AB-DXA-NATIVE-ADDRESS-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_OUT_TEMPLATE_MAP](#EMS-AB-DXA-OUT-TEMPLATE-MAP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_PASSWORD](#EMS-AB-DXA-PASSWORD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_PREV_EXCHANGE_OPTIONS](#EMS-AB-DXA-PREV-EXCHANGE-OPTIONS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_PREV_EXPORT_NATIVE_ONLY](#EMS-AB-DXA-PREV-EXPORT-NATIVE-ONLY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_PREV_IN_EXCHANGE_SENSITIVITY](#EMS-AB-DXA-PREV-IN-EXCHANGE-SENSITIVITY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_PREV_REMOTE_ENTRIES](#EMS-AB-DXA-PREV-REMOTE-ENTRIES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_PREV_REMOTE_ENTRIES_O](#EMS-AB-DXA-PREV-REMOTE-ENTRIES-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_PREV_REPLICATION_SENSITIVITY](#EMS-AB-DXA-PREV-REPLICATION-SENSITIVITY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_PREV_TEMPLATE_OPTIONS](#EMS-AB-DXA-PREV-TEMPLATE-OPTIONS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_PREV_TYPES](#EMS-AB-DXA-PREV-TYPES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_RECIPIENT_CP](#EMS-AB-DXA-RECIPIENT-CP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_REMOTE_CLIENT](#EMS-AB-DXA-REMOTE-CLIENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_REMOTE_CLIENT_O](#EMS-AB-DXA-REMOTE-CLIENT-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_REQNAME](#EMS-AB-DXA-REQNAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_REQ_SEQ](#EMS-AB-DXA-REQ-SEQ) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_REQ_SEQ_TIME](#EMS-AB-DXA-REQ-SEQ-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_REQ_SEQ_USN](#EMS-AB-DXA-REQ-SEQ-USN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_SVR_SEQ](#EMS-AB-DXA-SVR-SEQ) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_SVR_SEQ_TIME](#EMS-AB-DXA-SVR-SEQ-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_SVR_SEQ_USN](#EMS-AB-DXA-SVR-SEQ-USN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_TASK](#EMS-AB-DXA-TASK) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_TEMPLATE_OPTIONS](#EMS-AB-DXA-TEMPLATE-OPTIONS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_TEMPLATE_TIMESTAMP](#EMS-AB-DXA-TEMPLATE-TIMESTAMP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_TYPES](#EMS-AB-DXA-TYPES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_UNCONF_CONTAINER_LIST](#EMS-AB-DXA-UNCONF-CONTAINER-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_DXA_UNCONF_CONTAINER_LIST_O](#EMS-AB-DXA-UNCONF-CONTAINER-LIST-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_EMPLOYEE_NUMBER](#EMS-AB-EMPLOYEE-NUMBER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_EMPLOYEE_TYPE](#EMS-AB-EMPLOYEE-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ENABLED](#EMS-AB-ENABLED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ENABLED_AUTHORIZATION_PACKAGES](#EMS-AB-ENABLED-AUTHORIZATION-PACKAGES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ENABLED_PROTOCOLS](#EMS-AB-ENABLED-PROTOCOLS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ENABLED_PROTOCOL_CFG](#EMS-AB-ENABLED-PROTOCOL-CFG) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ENABLE_COMPATIBILITY](#EMS-AB-ENABLE-COMPATIBILITY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ENCAPSULATION_METHOD](#EMS-AB-ENCAPSULATION-METHOD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ENCRYPT](#EMS-AB-ENCRYPT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ENCRYPT_ALG_LIST_NA](#EMS-AB-ENCRYPT-ALG-LIST-NA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ENCRYPT_ALG_LIST_OTHER](#EMS-AB-ENCRYPT-ALG-LIST-OTHER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ENCRYPT_ALG_SELECTED_NA](#EMS-AB-ENCRYPT-ALG-SELECTED-NA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ENCRYPT_ALG_SELECTED_OTHER](#EMS-AB-ENCRYPT-ALG-SELECTED-OTHER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_EXPAND_DLS_LOCALLY](#EMS-AB-EXPAND-DLS-LOCALLY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_EXPIRATION_TIME](#EMS-AB-EXPIRATION-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_EXPORT_CONTAINERS](#EMS-AB-EXPORT-CONTAINERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_EXPORT_CONTAINERS_O](#EMS-AB-EXPORT-CONTAINERS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_EXPORT_CUSTOM_RECIPIENTS](#EMS-AB-EXPORT-CUSTOM-RECIPIENTS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_EXTENDED_CHARS_ALLOWED](#EMS-AB-EXTENDED-CHARS-ALLOWED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_EXTENSION_DATA](#EMS-AB-EXTENSION-DATA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_EXTENSION_NAME](#EMS-AB-EXTENSION-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_EXTENSION_NAME_INHERITED](#EMS-AB-EXTENSION-NAME-INHERITED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_FACSIMILE_TELEPHONE_NUMBER](#EMS-AB-FACSIMILE-TELEPHONE-NUMBER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_FILE_VERSION](#EMS-AB-FILE-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_FILTER_LOCAL_ADDRESSES](#EMS-AB-FILTER-LOCAL-ADDRESSES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_FOLDERS_CONTAINER](#EMS-AB-FOLDERS-CONTAINER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_FOLDERS_CONTAINER_O](#EMS-AB-FOLDERS-CONTAINER-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_FORM_DATA](#EMS-AB-FORM-DATA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_FORWARDING_ADDRESS](#EMS-AB-FORWARDING-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GARBAGE_COLL_PERIOD](#EMS-AB-GARBAGE-COLL-PERIOD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GATEWAY_LOCAL_CRED](#EMS-AB-GATEWAY-LOCAL-CRED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GATEWAY_LOCAL_DESIG](#EMS-AB-GATEWAY-LOCAL-DESIG) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GATEWAY_PROXY](#EMS-AB-GATEWAY-PROXY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GATEWAY_ROUTING_TREE](#EMS-AB-GATEWAY-ROUTING-TREE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GENERATION_QUALIFIER](#EMS-AB-GENERATION-QUALIFIER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GROUP_BY_ATTR_1](#EMS-AB-GROUP-BY-ATTR-1) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GROUP_BY_ATTR_2](#EMS-AB-GROUP-BY-ATTR-2) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GROUP_BY_ATTR_3](#EMS-AB-GROUP-BY-ATTR-3) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GROUP_BY_ATTR_4](#EMS-AB-GROUP-BY-ATTR-4) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GROUP_BY_ATTR_VALUE_DN](#EMS-AB-GROUP-BY-ATTR-VALUE-DN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GROUP_BY_ATTR_VALUE_DN_O](#EMS-AB-GROUP-BY-ATTR-VALUE-DN-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GROUP_BY_ATTR_VALUE_STR](#EMS-AB-GROUP-BY-ATTR-VALUE-STR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_GWART_LAST_MODIFIED](#EMS-AB-GWART-LAST-MODIFIED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HAS_FULL_REPLICA_NCS](#EMS-AB-HAS-FULL-REPLICA-NCS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HAS_FULL_REPLICA_NCS_O](#EMS-AB-HAS-FULL-REPLICA-NCS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HAS_MASTER_NCS](#EMS-AB-HAS-MASTER-NCS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HAS_MASTER_NCS_O](#EMS-AB-HAS-MASTER-NCS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HELP_DATA_16](#EMS-AB-HELP-DATA-16) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HELP_DATA_32](#EMS-AB-HELP-DATA-32) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HELP_FILE_NAME](#EMS-AB-HELP-FILE-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HEURISTICS](#EMS-AB-HEURISTICS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HIDE_DL_MEMBERSHIP](#EMS-AB-HIDE-DL-MEMBERSHIP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HIDE_FROM_ADDRESS_BOOK](#EMS-AB-HIDE-FROM-ADDRESS-BOOK) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HIERARCHY_PATH](#EMS-AB-HIERARCHY-PATH) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HOME_MDB_BL](#EMS-AB-HOME-MDB-BL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HOME_MDB_BL_O](#EMS-AB-HOME-MDB-BL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HOME_MTA](#EMS-AB-HOME-MTA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HOME_MTA_O](#EMS-AB-HOME-MTA-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HOME_PUBLIC_SERVER](#EMS-AB-HOME-PUBLIC-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HOME_PUBLIC_SERVER_O](#EMS-AB-HOME-PUBLIC-SERVER-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HOUSE_IDENTIFIER](#EMS-AB-HOUSE-IDENTIFIER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HTTP_PUB_AB_ATTRIBUTES](#EMS-AB-HTTP-PUB-AB-ATTRIBUTES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HTTP_PUB_GAL](#EMS-AB-HTTP-PUB-GAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HTTP_PUB_GAL_LIMIT](#EMS-AB-HTTP-PUB-GAL-LIMIT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HTTP_PUB_PF](#EMS-AB-HTTP-PUB-PF) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_HTTP_SERVERS](#EMS-AB-HTTP-SERVERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_IMPORTED_FROM](#EMS-AB-IMPORTED-FROM) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_IMPORT_CONTAINER](#EMS-AB-IMPORT-CONTAINER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_IMPORT_CONTAINER_O](#EMS-AB-IMPORT-CONTAINER-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_IMPORT_SENSITIVITY](#EMS-AB-IMPORT-SENSITIVITY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INBOUND_ACCEPT_ALL](#EMS-AB-INBOUND-ACCEPT-ALL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INBOUND_DN](#EMS-AB-INBOUND-DN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INBOUND_DN_O](#EMS-AB-INBOUND-DN-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INBOUND_HOST](#EMS-AB-INBOUND-HOST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INBOUND_NEWSFEED](#EMS-AB-INBOUND-NEWSFEED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INBOUND_NEWSFEED_TYPE](#EMS-AB-INBOUND-NEWSFEED-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INBOUND_SITES](#EMS-AB-INBOUND-SITES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INBOUND_SITES_O](#EMS-AB-INBOUND-SITES-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INCOMING_MSG_SIZE_LIMIT](#EMS-AB-INCOMING-MSG-SIZE-LIMIT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INCOMING_PASSWORD](#EMS-AB-INCOMING-PASSWORD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INSADMIN](#EMS-AB-INSADMIN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INSADMIN_O](#EMS-AB-INSADMIN-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INSTANCE_TYPE](#EMS-AB-INSTANCE-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INTERNATIONAL_ISDN_NUMBER](#EMS-AB-INTERNATIONAL-ISDN-NUMBER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_INVOCATION_ID](#EMS-AB-INVOCATION-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_IS_DELETED](#EMS-AB-IS-DELETED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_IS_SINGLE_VALUED](#EMS-AB-IS-SINGLE-VALUED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_KCC_STATUS](#EMS-AB-KCC-STATUS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_KM_SERVER](#EMS-AB-KM-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_KM_SERVER_O](#EMS-AB-KM-SERVER-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_KNOWLEDGE_INFORMATION](#EMS-AB-KNOWLEDGE-INFORMATION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LABELEDURI](#EMS-AB-LABELEDURI) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LANGUAGE](#EMS-AB-LANGUAGE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LANGUAGE_ISO_639](#EMS-AB-LANGUAGE-ISO-639) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LDAP_DISPLAY_NAME](#EMS-AB-LDAP-DISPLAY-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LDAP_SEARCH_CFG](#EMS-AB-LDAP-SEARCH-CFG) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LINE_WRAP](#EMS-AB-LINE-WRAP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LINK_ID](#EMS-AB-LINK-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LIST_PUBLIC_FOLDERS](#EMS-AB-LIST-PUBLIC-FOLDERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LOCAL_BRIDGE_HEAD](#EMS-AB-LOCAL-BRIDGE-HEAD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LOCAL_BRIDGE_HEAD_ADDRESS](#EMS-AB-LOCAL-BRIDGE-HEAD-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LOCAL_INITIAL_TURN](#EMS-AB-LOCAL-INITIAL-TURN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LOCAL_SCOPE](#EMS-AB-LOCAL-SCOPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LOCAL_SCOPE_O](#EMS-AB-LOCAL-SCOPE-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LOG_FILENAME](#EMS-AB-LOG-FILENAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_LOG_ROLLOVER_INTERVAL](#EMS-AB-LOG-ROLLOVER-INTERVAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MAIL_DROP](#EMS-AB-MAIL-DROP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MAINTAIN_AUTOREPLY_HISTORY](#EMS-AB-MAINTAIN-AUTOREPLY-HISTORY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MAPI_DISPLAY_TYPE](#EMS-AB-MAPI-DISPLAY-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MAPI_ID](#EMS-AB-MAPI-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MAXIMUM_OBJECT_ID](#EMS-AB-MAXIMUM-OBJECT-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MDB_BACKOFF_INTERVAL](#EMS-AB-MDB-BACKOFF-INTERVAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MDB_MSG_TIME_OUT_PERIOD](#EMS-AB-MDB-MSG-TIME-OUT-PERIOD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MDB_OVER_QUOTA_LIMIT](#EMS-AB-MDB-OVER-QUOTA-LIMIT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MDB_STORAGE_QUOTA](#EMS-AB-MDB-STORAGE-QUOTA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MDB_UNREAD_LIMIT](#EMS-AB-MDB-UNREAD-LIMIT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MDB_USE_DEFAULTS](#EMS-AB-MDB-USE-DEFAULTS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MESSAGE_TRACKING_ENABLED](#EMS-AB-MESSAGE-TRACKING-ENABLED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MIME_TYPES](#EMS-AB-MIME-TYPES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MODERATED](#EMS-AB-MODERATED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MODERATOR](#EMS-AB-MODERATOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORED_CONFIGURATIONS](#EMS-AB-MONITORED-CONFIGURATIONS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORED_CONFIGURATIONS_O](#EMS-AB-MONITORED-CONFIGURATIONS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORED_SERVERS](#EMS-AB-MONITORED-SERVERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORED_SERVERS_O](#EMS-AB-MONITORED-SERVERS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORED_SERVICES](#EMS-AB-MONITORED-SERVICES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_ALERT_DELAY](#EMS-AB-MONITORING-ALERT-DELAY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_ALERT_UNITS](#EMS-AB-MONITORING-ALERT-UNITS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_AVAILABILITY_STYLE](#EMS-AB-MONITORING-AVAILABILITY-STYLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_AVAILABILITY_WINDOW](#EMS-AB-MONITORING-AVAILABILITY-WINDOW) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_CACHED_VIA_MAIL](#EMS-AB-MONITORING-CACHED-VIA-MAIL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_CACHED_VIA_MAIL_O](#EMS-AB-MONITORING-CACHED-VIA-MAIL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_CACHED_VIA_RPC](#EMS-AB-MONITORING-CACHED-VIA-RPC) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_CACHED_VIA_RPC_O](#EMS-AB-MONITORING-CACHED-VIA-RPC-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_ESCALATION_PROCEDURE](#EMS-AB-MONITORING-ESCALATION-PROCEDURE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_HOTSITE_POLL_INTERVAL](#EMS-AB-MONITORING-HOTSITE-POLL-INTERVAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_HOTSITE_POLL_UNITS](#EMS-AB-MONITORING-HOTSITE-POLL-UNITS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_MAIL_UPDATE_INTERVAL](#EMS-AB-MONITORING-MAIL-UPDATE-INTERVAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_MAIL_UPDATE_UNITS](#EMS-AB-MONITORING-MAIL-UPDATE-UNITS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_NORMAL_POLL_INTERVAL](#EMS-AB-MONITORING-NORMAL-POLL-INTERVAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_NORMAL_POLL_UNITS](#EMS-AB-MONITORING-NORMAL-POLL-UNITS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_RECIPIENTS](#EMS-AB-MONITORING-RECIPIENTS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_RECIPIENTS_NDR](#EMS-AB-MONITORING-RECIPIENTS-NDR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_RECIPIENTS_NDR_O](#EMS-AB-MONITORING-RECIPIENTS-NDR-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_RECIPIENTS_O](#EMS-AB-MONITORING-RECIPIENTS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_RPC_UPDATE_INTERVAL](#EMS-AB-MONITORING-RPC-UPDATE-INTERVAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_RPC_UPDATE_UNITS](#EMS-AB-MONITORING-RPC-UPDATE-UNITS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_WARNING_DELAY](#EMS-AB-MONITORING-WARNING-DELAY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITORING_WARNING_UNITS](#EMS-AB-MONITORING-WARNING-UNITS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITOR_CLOCK](#EMS-AB-MONITOR-CLOCK) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITOR_SERVERS](#EMS-AB-MONITOR-SERVERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MONITOR_SERVICES](#EMS-AB-MONITOR-SERVICES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MTA_LOCAL_CRED](#EMS-AB-MTA-LOCAL-CRED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_MTA_LOCAL_DESIG](#EMS-AB-MTA-LOCAL-DESIG) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NEWSFEED_TYPE](#EMS-AB-NEWSFEED-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NEWSGROUP](#EMS-AB-NEWSGROUP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NEWSGROUP_LIST](#EMS-AB-NEWSGROUP-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NNTP_CHARACTER_SET](#EMS-AB-NNTP-CHARACTER-SET) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NNTP_CONTENT_FORMAT](#EMS-AB-NNTP-CONTENT-FORMAT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NNTP_DISTRIBUTIONS](#EMS-AB-NNTP-DISTRIBUTIONS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NNTP_DISTRIBUTIONS_FLAG](#EMS-AB-NNTP-DISTRIBUTIONS-FLAG) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NNTP_NEWSFEEDS](#EMS-AB-NNTP-NEWSFEEDS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NNTP_NEWSFEEDS_O](#EMS-AB-NNTP-NEWSFEEDS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NT_MACHINE_NAME](#EMS-AB-NT-MACHINE-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NT_SECURITY_DESCRIPTOR](#EMS-AB-NT-SECURITY-DESCRIPTOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NUM_OF_OPEN_RETRIES](#EMS-AB-NUM-OF-OPEN-RETRIES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_NUM_OF_TRANSFER_RETRIES](#EMS-AB-NUM-OF-TRANSFER-RETRIES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_N_ADDRESS](#EMS-AB-N-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_N_ADDRESS_TYPE](#EMS-AB-N-ADDRESS-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OBJECT_CLASS_CATEGORY](#EMS-AB-OBJECT-CLASS-CATEGORY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OBJECT_OID](#EMS-AB-OBJECT-OID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OBJECT_VERSION](#EMS-AB-OBJECT-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OBJ_VIEW_CONTAINERS](#EMS-AB-OBJ-VIEW-CONTAINERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OBJ_VIEW_CONTAINERS_O](#EMS-AB-OBJ-VIEW-CONTAINERS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OFF_LINE_AB_CONTAINERS](#EMS-AB-OFF-LINE-AB-CONTAINERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OFF_LINE_AB_CONTAINERS_O](#EMS-AB-OFF-LINE-AB-CONTAINERS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OFF_LINE_AB_SCHEDULE](#EMS-AB-OFF-LINE-AB-SCHEDULE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OFF_LINE_AB_SERVER](#EMS-AB-OFF-LINE-AB-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OFF_LINE_AB_SERVER_O](#EMS-AB-OFF-LINE-AB-SERVER-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OFF_LINE_AB_STYLE](#EMS-AB-OFF-LINE-AB-STYLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OID_TYPE](#EMS-AB-OID-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OM_OBJECT_CLASS](#EMS-AB-OM-OBJECT-CLASS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OM_SYNTAX](#EMS-AB-OM-SYNTAX) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OOF_REPLY_TO_ORIGINATOR](#EMS-AB-OOF-REPLY-TO-ORIGINATOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OPEN_RETRY_INTERVAL](#EMS-AB-OPEN-RETRY-INTERVAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ORGANIZATIONAL_UNIT_NAME](#EMS-AB-ORGANIZATIONAL-UNIT-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ORGANIZATION_NAME](#EMS-AB-ORGANIZATION-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ORIGINAL_DISPLAY_TABLE](#EMS-AB-ORIGINAL-DISPLAY-TABLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ORIGINAL_DISPLAY_TABLE_MSDOS](#EMS-AB-ORIGINAL-DISPLAY-TABLE-MSDOS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OTHER_RECIPS](#EMS-AB-OTHER-RECIPS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OUTBOUND_HOST](#EMS-AB-OUTBOUND-HOST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OUTBOUND_HOST_TYPE](#EMS-AB-OUTBOUND-HOST-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OUTBOUND_NEWSFEED](#EMS-AB-OUTBOUND-NEWSFEED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OUTBOUND_SITES](#EMS-AB-OUTBOUND-SITES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OUTBOUND_SITES_O](#EMS-AB-OUTBOUND-SITES-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OUTGOING_MSG_SIZE_LIMIT](#EMS-AB-OUTGOING-MSG-SIZE-LIMIT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OVERRIDE_NNTP_CONTENT_FORMAT](#EMS-AB-OVERRIDE-NNTP-CONTENT-FORMAT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_OWA_SERVER](#EMS-AB-OWA-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PERIOD_REPL_STAGGER](#EMS-AB-PERIOD-REPL-STAGGER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PERIOD_REP_SYNC_TIMES](#EMS-AB-PERIOD-REP-SYNC-TIMES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PERSONAL_TITLE](#EMS-AB-PERSONAL-TITLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PER_MSG_DIALOG_DISPLAY_TABLE](#EMS-AB-PER-MSG-DIALOG-DISPLAY-TABLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PER_RECIP_DIALOG_DISPLAY_TABLE](#EMS-AB-PER-RECIP-DIALOG-DISPLAY-TABLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PF_CONTACTS](#EMS-AB-PF-CONTACTS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PF_CONTACTS_O](#EMS-AB-PF-CONTACTS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_POP_CHARACTER_SET](#EMS-AB-POP-CHARACTER-SET) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_POP_CONTENT_FORMAT](#EMS-AB-POP-CONTENT-FORMAT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PORT_NUMBER](#EMS-AB-PORT-NUMBER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_POSTAL_ADDRESS](#EMS-AB-POSTAL-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PREFERRED_DELIVERY_METHOD](#EMS-AB-PREFERRED-DELIVERY-METHOD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PRESERVE_INTERNET_CONTENT](#EMS-AB-PRESERVE-INTERNET-CONTENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PRMD](#EMS-AB-PRMD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PROMO_EXPIRATION](#EMS-AB-PROMO-EXPIRATION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PROTOCOL_SETTINGS](#EMS-AB-PROTOCOL-SETTINGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PROXY_GENERATION_ENABLED](#EMS-AB-PROXY-GENERATION-ENABLED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PROXY_GENERATOR_DLL](#EMS-AB-PROXY-GENERATOR-DLL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PUBLIC_DELEGATES_BL](#EMS-AB-PUBLIC-DELEGATES-BL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_PUBLIC_DELEGATES_BL_O](#EMS-AB-PUBLIC-DELEGATES-BL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_P_SELECTOR](#EMS-AB-P-SELECTOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_P_SELECTOR_INBOUND](#EMS-AB-P-SELECTOR-INBOUND) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_QUOTA_NOTIFICATION_SCHEDULE](#EMS-AB-QUOTA-NOTIFICATION-SCHEDULE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_QUOTA_NOTIFICATION_STYLE](#EMS-AB-QUOTA-NOTIFICATION-STYLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RANGE_LOWER](#EMS-AB-RANGE-LOWER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RANGE_UPPER](#EMS-AB-RANGE-UPPER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RAS_ACCOUNT](#EMS-AB-RAS-ACCOUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RAS_CALLBACK_NUMBER](#EMS-AB-RAS-CALLBACK-NUMBER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RAS_PASSWORD](#EMS-AB-RAS-PASSWORD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RAS_PHONEBOOK_ENTRY_NAME](#EMS-AB-RAS-PHONEBOOK-ENTRY-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RAS_PHONE_NUMBER](#EMS-AB-RAS-PHONE-NUMBER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RAS_REMOTE_SRVR_NAME](#EMS-AB-RAS-REMOTE-SRVR-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REFERRAL_LIST](#EMS-AB-REFERRAL-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REGISTERED_ADDRESS](#EMS-AB-REGISTERED-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REMOTE_BRIDGE_HEAD](#EMS-AB-REMOTE-BRIDGE-HEAD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REMOTE_BRIDGE_HEAD_ADDRESS](#EMS-AB-REMOTE-BRIDGE-HEAD-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REMOTE_OUT_BH_SERVER](#EMS-AB-REMOTE-OUT-BH-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REMOTE_OUT_BH_SERVER_O](#EMS-AB-REMOTE-OUT-BH-SERVER-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REMOTE_SITE](#EMS-AB-REMOTE-SITE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REMOTE_SITE_O](#EMS-AB-REMOTE-SITE-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REPLICATED_OBJECT_VERSION](#EMS-AB-REPLICATED-OBJECT-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REPLICATION_MAIL_MSG_SIZE](#EMS-AB-REPLICATION-MAIL-MSG-SIZE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REPLICATION_SENSITIVITY](#EMS-AB-REPLICATION-SENSITIVITY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REPLICATION_STAGGER](#EMS-AB-REPLICATION-STAGGER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REPORT_TO_ORIGINATOR](#EMS-AB-REPORT-TO-ORIGINATOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REPORT_TO_OWNER](#EMS-AB-REPORT-TO-OWNER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REQUIRE_SSL](#EMS-AB-REQUIRE-SSL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_REQ_SEQ](#EMS-AB-REQ-SEQ) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RESPONSIBLE_LOCAL_DXA](#EMS-AB-RESPONSIBLE-LOCAL-DXA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RESPONSIBLE_LOCAL_DXA_O](#EMS-AB-RESPONSIBLE-LOCAL-DXA-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RETURN_EXACT_MSG_SIZE](#EMS-AB-RETURN-EXACT-MSG-SIZE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RID_SERVER](#EMS-AB-RID-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RID_SERVER_O](#EMS-AB-RID-SERVER-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ROLE_OCCUPANT](#EMS-AB-ROLE-OCCUPANT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ROLE_OCCUPANT_O](#EMS-AB-ROLE-OCCUPANT-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ROOT_NEWSGROUPS_FOLDER_ID](#EMS-AB-ROOT-NEWSGROUPS-FOLDER-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_ROUTING_LIST](#EMS-AB-ROUTING-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RTS_CHECKPOINT_SIZE](#EMS-AB-RTS-CHECKPOINT-SIZE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RTS_RECOVERY_TIMEOUT](#EMS-AB-RTS-RECOVERY-TIMEOUT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RTS_WINDOW_SIZE](#EMS-AB-RTS-WINDOW-SIZE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RUNS_ON](#EMS-AB-RUNS-ON) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_RUNS_ON_O](#EMS-AB-RUNS-ON-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SCHEMA_FLAGS](#EMS-AB-SCHEMA-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SCHEMA_VERSION](#EMS-AB-SCHEMA-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SEARCH_FLAGS](#EMS-AB-SEARCH-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SEARCH_GUIDE](#EMS-AB-SEARCH-GUIDE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SECURITY_POLICY](#EMS-AB-SECURITY-POLICY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SECURITY_PROTOCOL](#EMS-AB-SECURITY-PROTOCOL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SEE_ALSO](#EMS-AB-SEE-ALSO) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SEE_ALSO_O](#EMS-AB-SEE-ALSO-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SEND_EMAIL_MESSAGE](#EMS-AB-SEND-EMAIL-MESSAGE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SEND_TNEF](#EMS-AB-SEND-TNEF) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SERIAL_NUMBER](#EMS-AB-SERIAL-NUMBER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SERVER](#EMS-AB-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SERVICE_ACTION_FIRST](#EMS-AB-SERVICE-ACTION-FIRST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SERVICE_ACTION_OTHER](#EMS-AB-SERVICE-ACTION-OTHER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SERVICE_ACTION_SECOND](#EMS-AB-SERVICE-ACTION-SECOND) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SERVICE_RESTART_DELAY](#EMS-AB-SERVICE-RESTART-DELAY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SERVICE_RESTART_MESSAGE](#EMS-AB-SERVICE-RESTART-MESSAGE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SESSION_DISCONNECT_TIMER](#EMS-AB-SESSION-DISCONNECT-TIMER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SITE_AFFINITY](#EMS-AB-SITE-AFFINITY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SITE_FOLDER_GUID](#EMS-AB-SITE-FOLDER-GUID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SITE_FOLDER_SERVER](#EMS-AB-SITE-FOLDER-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SITE_FOLDER_SERVER_O](#EMS-AB-SITE-FOLDER-SERVER-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SITE_PROXY_SPACE](#EMS-AB-SITE-PROXY-SPACE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SMIME_ALG_LIST_NA](#EMS-AB-SMIME-ALG-LIST-NA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SMIME_ALG_LIST_OTHER](#EMS-AB-SMIME-ALG-LIST-OTHER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SMIME_ALG_SELECTED_NA](#EMS-AB-SMIME-ALG-SELECTED-NA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SMIME_ALG_SELECTED_OTHER](#EMS-AB-SMIME-ALG-SELECTED-OTHER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SPACE_LAST_COMPUTED](#EMS-AB-SPACE-LAST-COMPUTED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_STREET_ADDRESS](#EMS-AB-STREET-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SUBMISSION_CONT_LENGTH](#EMS-AB-SUBMISSION-CONT-LENGTH) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SUB_REFS](#EMS-AB-SUB-REFS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SUB_REFS_O](#EMS-AB-SUB-REFS-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SUB_SITE](#EMS-AB-SUB-SITE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SUPPORTED_ALGORITHMS](#EMS-AB-SUPPORTED-ALGORITHMS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SUPPORTED_APPLICATION_CONTEXT](#EMS-AB-SUPPORTED-APPLICATION-CONTEXT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SUPPORTING_STACK](#EMS-AB-SUPPORTING-STACK) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SUPPORTING_STACK_BL](#EMS-AB-SUPPORTING-STACK-BL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SUPPORTING_STACK_BL_O](#EMS-AB-SUPPORTING-STACK-BL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SUPPORTING_STACK_O](#EMS-AB-SUPPORTING-STACK-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_SUPPORT_SMIME_SIGNATURES](#EMS-AB-SUPPORT-SMIME-SIGNATURES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_S_SELECTOR](#EMS-AB-S-SELECTOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_S_SELECTOR_INBOUND](#EMS-AB-S-SELECTOR-INBOUND) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TARGET_MTAS](#EMS-AB-TARGET-MTAS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TELEPHONE_NUMBER](#EMS-AB-TELEPHONE-NUMBER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TELEPHONE_PERSONAL_PAGER](#EMS-AB-TELEPHONE-PERSONAL-PAGER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TELETEX_TERMINAL_IDENTIFIER](#EMS-AB-TELETEX-TERMINAL-IDENTIFIER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TEMP_ASSOC_THRESHOLD](#EMS-AB-TEMP-ASSOC-THRESHOLD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TOMBSTONE_LIFETIME](#EMS-AB-TOMBSTONE-LIFETIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TRACKING_LOG_PATH_NAME](#EMS-AB-TRACKING-LOG-PATH-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TRANSFER_RETRY_INTERVAL](#EMS-AB-TRANSFER-RETRY-INTERVAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TRANSFER_TIMEOUT_NON_URGENT](#EMS-AB-TRANSFER-TIMEOUT-NON-URGENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TRANSFER_TIMEOUT_NORMAL](#EMS-AB-TRANSFER-TIMEOUT-NORMAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TRANSFER_TIMEOUT_URGENT](#EMS-AB-TRANSFER-TIMEOUT-URGENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TRANSLATION_TABLE_USED](#EMS-AB-TRANSLATION-TABLE-USED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TRANSPORT_EXPEDITED_DATA](#EMS-AB-TRANSPORT-EXPEDITED-DATA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TRANS_RETRY_MINS](#EMS-AB-TRANS-RETRY-MINS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TRANS_TIMEOUT_MINS](#EMS-AB-TRANS-TIMEOUT-MINS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TRUST_LEVEL](#EMS-AB-TRUST-LEVEL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TURN_REQUEST_THRESHOLD](#EMS-AB-TURN-REQUEST-THRESHOLD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TWO_WAY_ALTERNATE_FACILITY](#EMS-AB-TWO-WAY-ALTERNATE-FACILITY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_TYPE](#EMS-AB-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_T_SELECTOR](#EMS-AB-T-SELECTOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_T_SELECTOR_INBOUND](#EMS-AB-T-SELECTOR-INBOUND) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_UNAUTH_ORIG_BL](#EMS-AB-UNAUTH-ORIG-BL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_UNAUTH_ORIG_BL_O](#EMS-AB-UNAUTH-ORIG-BL-O) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_USENET_SITE_NAME](#EMS-AB-USENET-SITE-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_USER_PASSWORD](#EMS-AB-USER-PASSWORD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_USE_SERVER_VALUES](#EMS-AB-USE-SERVER-VALUES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_USE_SITE_VALUES](#EMS-AB-USE-SITE-VALUES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_USN_CHANGED](#EMS-AB-USN-CHANGED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_USN_CREATED](#EMS-AB-USN-CREATED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_USN_DSA_LAST_OBJ_REMOVED](#EMS-AB-USN-DSA-LAST-OBJ-REMOVED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_USN_INTERSITE](#EMS-AB-USN-INTERSITE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_USN_LAST_OBJ_REM](#EMS-AB-USN-LAST-OBJ-REM) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_USN_SOURCE](#EMS-AB-USN-SOURCE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VIEW_CONTAINER_1](#EMS-AB-VIEW-CONTAINER-1) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VIEW_CONTAINER_2](#EMS-AB-VIEW-CONTAINER-2) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VIEW_CONTAINER_3](#EMS-AB-VIEW-CONTAINER-3) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VIEW_DEFINITION](#EMS-AB-VIEW-DEFINITION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VIEW_FLAGS](#EMS-AB-VIEW-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VIEW_SITE](#EMS-AB-VIEW-SITE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VOICE_MAIL_FLAGS](#EMS-AB-VOICE-MAIL-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VOICE_MAIL_GREETINGS](#EMS-AB-VOICE-MAIL-GREETINGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VOICE_MAIL_PASSWORD](#EMS-AB-VOICE-MAIL-PASSWORD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VOICE_MAIL_RECORDED_NAME](#EMS-AB-VOICE-MAIL-RECORDED-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VOICE_MAIL_RECORDING_LENGTH](#EMS-AB-VOICE-MAIL-RECORDING-LENGTH) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VOICE_MAIL_SPEED](#EMS-AB-VOICE-MAIL-SPEED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VOICE_MAIL_SYSTEM_GUID](#EMS-AB-VOICE-MAIL-SYSTEM-GUID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VOICE_MAIL_USER_ID](#EMS-AB-VOICE-MAIL-USER-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_VOICE_MAIL_VOLUME](#EMS-AB-VOICE-MAIL-VOLUME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_WWW_HOME_PAGE](#EMS-AB-WWW-HOME-PAGE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_XMIT_TIMEOUT_NON_URGENT](#EMS-AB-XMIT-TIMEOUT-NON-URGENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_XMIT_TIMEOUT_NORMAL](#EMS-AB-XMIT-TIMEOUT-NORMAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_XMIT_TIMEOUT_URGENT](#EMS-AB-XMIT-TIMEOUT-URGENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_121_ADDRESS](#EMS-AB-X-121-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_25_CALL_USER_DATA_INCOMING](#EMS-AB-X-25-CALL-USER-DATA-INCOMING) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_25_CALL_USER_DATA_OUTGOING](#EMS-AB-X-25-CALL-USER-DATA-OUTGOING) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_25_FACILITIES_DATA_INCOMING](#EMS-AB-X-25-FACILITIES-DATA-INCOMING) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_25_FACILITIES_DATA_OUTGOING](#EMS-AB-X-25-FACILITIES-DATA-OUTGOING) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_25_LEASED_LINE_PORT](#EMS-AB-X-25-LEASED-LINE-PORT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_25_LEASED_OR_SWITCHED](#EMS-AB-X-25-LEASED-OR-SWITCHED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_25_REMOTE_MTA_PHONE](#EMS-AB-X-25-REMOTE-MTA-PHONE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_400_ATTACHMENT_TYPE](#EMS-AB-X-400-ATTACHMENT-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_400_SELECTOR_SYNTAX](#EMS-AB-X-400-SELECTOR-SYNTAX) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_500_ACCESS_CONTROL_LIST](#EMS-AB-X-500-ACCESS-CONTROL-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_500_NC](#EMS-AB-X-500-NC) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EMS_AB_X_500_RDN](#EMS-AB-X-500-RDN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [END_DATE](#END-DATE) | Contains the value of the PidLidAppointmentEndWhole property (section 2.14). |
| [END_RECURRENCE_DATE](#END-RECURRENCE-DATE) | Identifies the end date of the recurrence range. |
| [END_RECURRENCE_TIME](#END-RECURRENCE-TIME) | Identifies the end time of the recurrence range. |
| [ENTRY_ID](#ENTRY-ID) | Contains the information to identify many different types of messaging objects. |
| [EVENTS_ROOT_FOLDER_ENTRYID](#EVENTS-ROOT-FOLDER-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EXCEPTION_END_TIME](#EXCEPTION-END-TIME) | Contains the end date and time of the exception in the local time zone of the computer when the exception is created. |
| [EXCEPTION_REPLACE_TIME](#EXCEPTION-REPLACE-TIME) | Specifies the date and time, in UTC, within a recurrence pattern that an exception will replace. |
| [EXCEPTION_START_TIME](#EXCEPTION-START-TIME) | Contains the start date and time of the exception in the local time zone of the computer when the exception is created. |
| [EXCESS_STORAGE_USED](#EXCESS-STORAGE-USED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EXCHANGE_INTENDED_BUSY_STATUS](#EXCHANGE-INTENDED-BUSY-STATUS) | Specifies the intended free/busy status of a meeting in a Meeting request. |
| [EXCHANGE_JUNK_EMAIL_MOVE_STAMP](#EXCHANGE-JUNK-EMAIL-MOVE-STAMP) | Indicates that the message is not to be processed by a spam filter. |
| [EXCHANGE_MODIFY_EXCEPTION_STRUCTURE](#EXCHANGE-MODIFY-EXCEPTION-STRUCTURE) | Specifies a structure that modifies an exception to the recurrence. |
| [EXCHANGE_NO_MODIFY_EXCEPTIONS](#EXCHANGE-NO-MODIFY-EXCEPTIONS) | Indicates whether exceptions to a recurring appointment can be modified. |
| [EXCHANGE_NT_SECURITY_DESCRIPTOR](#EXCHANGE-NT-SECURITY-DESCRIPTOR) | Contains the calculated security descriptor for the item. |
| [EXCHANGE_PATTERN_END](#EXCHANGE-PATTERN-END) | Identifies the maximum time when an instance of a recurring appointment ends. |
| [EXCHANGE_PATTERN_START](#EXCHANGE-PATTERN-START) | Identifies the absolute minimum time when an instance of a recurring appointment starts. |
| [EXCHANGE_REMINDER_INTERVAL](#EXCHANGE-REMINDER-INTERVAL) | Identifies the time, in seconds, between reminders. |
| [EXCH_DATABASE_SCHEMA](#EXCH-DATABASE-SCHEMA) | Specifies an array of URLs that identifies other folders within the same message store that contain schema definition items. |
| [EXCH_DATA_EXPECTED_CONTENT_CLASS](#EXCH-DATA-EXPECTED-CONTENT-CLASS) | Specifies an array of names that indicates the expected content classes of items within a folder. |
| [EXCH_DATA_SCHEMA_COLLECTION_REFERENCE](#EXCH-DATA-SCHEMA-COLLECTION-REFERENCE) | Specifies an array of names that indicates the expected content classes of items within a folder. |
| [EXPIRY_NUMBER](#EXPIRY-NUMBER) | Contains an integer value that is used along with the PidTagExpiryUnits property (section 2.681) to define the expiry send time. |
| [EXPIRY_TIME](#EXPIRY-TIME) | Contains the time, in UTC, after which a client wants to receive an expiry event if the message arrives late. |
| [EXPIRY_UNITS](#EXPIRY-UNITS) | Contains the unit of time that the value of the PidTagExpiryNumber property (section 2.679) multiplies. |
| [EXPLICIT_CONVERSION](#EXPLICIT-CONVERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EXTENDED_ACL_DATA](#EXTENDED-ACL-DATA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EXTENDED_FOLDER_FLAGS](#EXTENDED-FOLDER-FLAGS) | Contains encoded sub-properties for a folder. |
| [EXTENDED_RULE_MESSAGE_ACTIONS](#EXTENDED-RULE-MESSAGE-ACTIONS) | Contains action information about named properties used in the rule. |
| [EXTENDED_RULE_MESSAGE_CONDITION](#EXTENDED-RULE-MESSAGE-CONDITION) | Contains condition information about named properties used in the rule. |
| [EXTENDED_RULE_SIZE_LIMIT](#EXTENDED-RULE-SIZE-LIMIT) | Contains the maximum size, in bytes, that the user is allowed to accumulate for a single extended rule. |
| [EXTRACTED_ADDRESSES](#EXTRACTED-ADDRESSES) | Contains an XML document with a single AddressSet element. |
| [EXTRACTED_CONTACTS](#EXTRACTED-CONTACTS) | Contains an XML document with a single ContactSet element. |
| [EXTRACTED_EMAILS](#EXTRACTED-EMAILS) | Contains an XML document with a single EmailSet element. |
| [EXTRACTED_MEETINGS](#EXTRACTED-MEETINGS) | Contains an XML document with a single MeetingSet element. |
| [EXTRACTED_PHONES](#EXTRACTED-PHONES) | Contains an XML document with a single PhoneSet element. |
| [EXTRACTED_TASKS](#EXTRACTED-TASKS) | Contains an XML document with a single TaskSet element. |
| [EXTRACTED_URLS](#EXTRACTED-URLS) | Contains an XML document with a single UrlSet element. |
| [EX_CURRENT_VERSION](#EX-CURRENT-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [EX_SECURITY](#EX-SECURITY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FAST_TRANSFER](#FAST-TRANSFER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FAVORITES_DEFAULT_NAME](#FAVORITES-DEFAULT-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FAX_1_ADDRESS_TYPE](#FAX-1-ADDRESS-TYPE) | Contains the string value "FAX". |
| [FAX_1_EMAIL_ADDRESS](#FAX-1-EMAIL-ADDRESS) | Contains a user-readable display name, followed by the "@" character, followed by a fax number. |
| [FAX_1_ORIGINAL_DISPLAY_NAME](#FAX-1-ORIGINAL-DISPLAY-NAME) | Contains the same value as the PidTagNormalizedSubject property (section 2.803). |
| [FAX_1_ORIGINAL_ENTRY_ID](#FAX-1-ORIGINAL-ENTRY-ID) | Specifies a one-off EntryID that corresponds to this fax address. |
| [FAX_2_ADDRESS_TYPE](#FAX-2-ADDRESS-TYPE) | Contains the string value "FAX". |
| [FAX_2_EMAIL_ADDRESS](#FAX-2-EMAIL-ADDRESS) | Contains a user-readable display name, followed by the "@" character, followed by a fax number. |
| [FAX_2_ORIGINAL_DISPLAY_NAME](#FAX-2-ORIGINAL-DISPLAY-NAME) | Contains the same value as the PidTagNormalizedSubject property (section 2.803). |
| [FAX_2_ORIGINAL_ENTRY_ID](#FAX-2-ORIGINAL-ENTRY-ID) | Specifies a one-off EntryID corresponding to this fax address. |
| [FAX_3_ADDRESS_TYPE](#FAX-3-ADDRESS-TYPE) | Contains the string value "FAX". |
| [FAX_3_EMAIL_ADDRESS](#FAX-3-EMAIL-ADDRESS) | Contains a user-readable display name, followed by the "@" character, followed by a fax number. |
| [FAX_3_ORIGINAL_DISPLAY_NAME](#FAX-3-ORIGINAL-DISPLAY-NAME) | Contains the same value as the PidTagNormalizedSubject property (section 2.803). |
| [FAX_3_ORIGINAL_ENTRY_ID](#FAX-3-ORIGINAL-ENTRY-ID) | Specifies a one-off EntryID that corresponds to this fax address. |
| [FAX_NUMBER_OF_PAGES](#FAX-NUMBER-OF-PAGES) | Contains the number of pages in a Fax object. |
| [FILE_UNDER](#FILE-UNDER) | Specifies the name under which to file a contact when displaying a list of contacts. |
| [FILE_UNDER_ID](#FILE-UNDER-ID) | Specifies how to generate and recompute the value of the PidLidFileUnder property (section 2.132) when other contact name properties change. |
| [FILE_UNDER_LIST](#FILE-UNDER-LIST) | Specifies a list of possible values for the PidLidFileUnderId property (section 2.133). |
| [FILTERING_HOOKS](#FILTERING-HOOKS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FINDER_ENTRYID](#FINDER-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FLAG_COMPLETE_TIME](#FLAG-COMPLETE-TIME) | Specifies the date and time, in UTC, that the Message object was flagged as complete. |
| [FLAG_REQUEST](#FLAG-REQUEST) | Contains user-specifiable text to be associated with the flag. |
| [FLAG_STATUS](#FLAG-STATUS) | Specifies the flag state of the Message object. |
| [FLAG_STRING](#FLAG-STRING) | Contains an index identifying one of a set of pre-defined text strings to be associated with the flag. |
| [FLAT_URL_NAME](#FLAT-URL-NAME) | Contains a unique identifier for an item across the message store. |
| [FOLDER_ASSOCIATED_CONTENTS](#FOLDER-ASSOCIATED-CONTENTS) | Identifies all FAI messages in the current folder. |
| [FOLDER_CHILD_COUNT](#FOLDER-CHILD-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FOLDER_DESIGN_FLAGS](#FOLDER-DESIGN-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FOLDER_FLAGS](#FOLDER-FLAGS) | Contains a computed value to specify the type or state of a folder. |
| [FOLDER_ID](#FOLDER-ID) | Contains the Folder ID (FID) ([MS-OXCDATA] section 2.2.1.1) of the folder. |
| [FOLDER_PATHNAME](#FOLDER-PATHNAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FOLDER_TYPE](#FOLDER-TYPE) | Specifies the type of a folder that includes the Root folder, Generic folder, and Search folder. |
| [FOLLOWUP_ICON](#FOLLOWUP-ICON) | Specifies the flag color of the Message object. |
| [FOREIGN_ID](#FOREIGN-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FOREIGN_REPORT_ID](#FOREIGN-REPORT-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FOREIGN_SUBJECT_ID](#FOREIGN-SUBJECT-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FORM_CATEGORY](#FORM-CATEGORY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FORM_CATEGORY_SUB](#FORM-CATEGORY-SUB) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FORM_CLSID](#FORM-CLSID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FORM_CONTACT_NAME](#FORM-CONTACT-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FORM_DESIGNER_GUID](#FORM-DESIGNER-GUID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FORM_DESIGNER_NAME](#FORM-DESIGNER-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FORM_HIDDEN](#FORM-HIDDEN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FORM_HOST_MAP](#FORM-HOST-MAP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FORM_MESSAGE_BEHAVIOR](#FORM-MESSAGE-BEHAVIOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FORM_VERSION](#FORM-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FORWARD_INSTANCE](#FORWARD-INSTANCE) | Indicates whether the Meeting Request object represents an exception to a recurring invitation sent by the organizer. |
| [FORWARD_NOTIFICATION_RECIPIENTS](#FORWARD-NOTIFICATION-RECIPIENTS) | Contains a list of RecipientRow structures, as described in [MS-OXCDATA] section 2.8.3, that indicate the recipients of a meeting forward. |
| [FREE_BUSY_COUNT_MONTHS](#FREE-BUSY-COUNT-MONTHS) | Contains an integer value used to calculate the start and end dates of the range of free/busy data to be published to the public folders. |
| [FREE_BUSY_ENTRY_IDS](#FREE-BUSY-ENTRY-IDS) | Contains EntryIDs of the Delegate Information object, the free/busy message of the "Freebusy Data". |
| [FREE_BUSY_FOR_LOCAL_SITE_ENTRYID](#FREE-BUSY-FOR-LOCAL-SITE-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [FREE_BUSY_LOCATION](#FREE-BUSY-LOCATION) | Specifies a URL path from which a client can retrieve free/busy status information for the contact. |
| [FREE_BUSY_MESSAGE_EMAIL_ADDRESS](#FREE-BUSY-MESSAGE-EMAIL-ADDRESS) | Specifies the email address of the user or resource to whom this free/busy message applies. |
| [FREE_BUSY_PUBLISH_END](#FREE-BUSY-PUBLISH-END) | Specifies the end time, in UTC, of the publishing range. |
| [FREE_BUSY_PUBLISH_START](#FREE-BUSY-PUBLISH-START) | Specifies the start time, in UTC, of the publishing range. |
| [FREE_BUSY_RANGE_TIMESTAMP](#FREE-BUSY-RANGE-TIMESTAMP) | Specifies the time, in UTC, that the data was published. |
| [FROM](#FROM) | Specifies the SMTP email alias of the organizer of an appointment or meeting. |
| [FTP_SITE](#FTP-SITE) | Contains the File Transfer Protocol (FTP) site address of the mail user. |
| [F_EXCEPTIONAL_ATTENDEES](#F-EXCEPTIONAL-ATTENDEES) | Indicates that the object is a Recurring Calendar object with one or more exceptions, structure, as described in [MS-OXCDATA] section 2.8.3. |
| [F_EXCEPTIONAL_BODY](#F-EXCEPTIONAL-BODY) | Indicates that the Exception Embedded Message object has a body that differs from the Recurring Calendar object. |
| [F_INVITED](#F-INVITED) | Indicates whether invitations have been sent for the meeting that this Meeting object represents. |
| [F_OTHERS_APPOINTMENT](#F-OTHERS-APPOINTMENT) | Indicates whether the Calendar folder from which the meeting was opened is another user's calendar. |
| [GATEWAY_NEEDS_TO_REFRESH](#GATEWAY-NEEDS-TO-REFRESH) | This property is deprecated and SHOULD NOT be used. |
| [GDATA_CONTACT_VERSION](#GDATA-CONTACT-VERSION) | Contains GData contact version (ETag). |
| [GDATA_PHOTO_VERSION](#GDATA-PHOTO-VERSION) | Contains GData photo version (ETag). |
| [GENDER](#GENDER) | Contains a value that represents the mail user's gender. |
| [GENERATION](#GENERATION) | Contains a generational abbreviation that follows the full name of the mail user. |
| [GIVEN_NAME](#GIVEN-NAME) | Contains the mail user's given name. |
| [GLOBAL_OBJECT_ID](#GLOBAL-OBJECT-ID) | Contains an ID for an object that represents an exception to a recurring series. |
| [GOVERNMENT_ID_NUMBER](#GOVERNMENT-ID-NUMBER) | Contains a government identifier for the mail user. |
| [GW_ADMIN_OPERATIONS](#GW-ADMIN-OPERATIONS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [GW_MTSIN_ENTRYID](#GW-MTSIN-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [GW_MTSOUT_ENTRYID](#GW-MTSOUT-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [HAS_ATTACHMENTS](#HAS-ATTACHMENTS) | Indicates whether the Message object contains at least one attachment. |
| [HAS_DEFERRED_ACTION_MESSAGES](#HAS-DEFERRED-ACTION-MESSAGES) | Indicates whether a Message object has a deferred action message associated with it. |
| [HAS_MODERATOR_RULES](#HAS-MODERATOR-RULES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [HAS_NAMED_PROPERTIES](#HAS-NAMED-PROPERTIES) | Indicates whether the Message object has a named property. |
| [HAS_PICTURE](#HAS-PICTURE) | Specifies whether the attachment has a picture. |
| [HAS_RULES](#HAS-RULES) | Indicates whether a Folder object has rules. |
| [HEADER_FOLDER_ENTRYID](#HEADER-FOLDER-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [HEADING_PAIRS](#HEADING-PAIRS) | Specifies which group of headings are indented in the document. |
| [HIDDEN_COUNT](#HIDDEN-COUNT) | Specifies the hidden value of the file attached to the Document object. |
| [HIERARCHY_CHANGE_NUMBER](#HIERARCHY-CHANGE-NUMBER) | Contains a number that monotonically increases every time a subfolder is added to, or deleted from, this folder. |
| [HIERARCHY_SERVER](#HIERARCHY-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [HIERARCHY_SYNCHRONIZER](#HIERARCHY-SYNCHRONIZER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [HIER_REV](#HIER-REV) | Specifies the time, in UTC, to trigger the client in cached mode to synchronize the folder hierarchy. |
| [HOBBIES](#HOBBIES) | Contains the names of the mail user's hobbies. |
| [HOME_2_TELEPHONE_NUMBER](#HOME-2-TELEPHONE-NUMBER) | Contains a secondary telephone number at the mail user's home. |
| [HOME_2_TELEPHONE_NUMBERS](#HOME-2-TELEPHONE-NUMBERS) | Contains secondary telephone numbers at the mail user's home. |
| [HOME_ADDRESS](#HOME-ADDRESS) | Specifies the complete address of the home address of the contact. |
| [HOME_ADDRESS_CITY](#HOME-ADDRESS-CITY) | Contains the name of the mail user's home locality, such as the town or city. |
| [HOME_ADDRESS_COUNTRY](#HOME-ADDRESS-COUNTRY) | Contains the name of the mail user's home country/region. |
| [HOME_ADDRESS_COUNTRY_CODE](#HOME-ADDRESS-COUNTRY-CODE) | Specifies the country code portion of the home address of the contact. |
| [HOME_ADDRESS_POSTAL_CODE](#HOME-ADDRESS-POSTAL-CODE) | Contains the postal code for the mail user's home postal address. |
| [HOME_ADDRESS_POST_OFFICE_BOX](#HOME-ADDRESS-POST-OFFICE-BOX) | Contains the number or identifier of the mail user's home post office box. |
| [HOME_ADDRESS_STATE_OR_PROVINCE](#HOME-ADDRESS-STATE-OR-PROVINCE) | Contains the name of the mail user's home state or province. |
| [HOME_ADDRESS_STREET](#HOME-ADDRESS-STREET) | Contains the mail user's home street address. |
| [HOME_FAX_NUMBER](#HOME-FAX-NUMBER) | Contains the telephone number of the mail user's home fax machine. |
| [HOME_TELEPHONE_NUMBER](#HOME-TELEPHONE-NUMBER) | Contains the primary telephone number of the mail user's home. |
| [HTML](#HTML) | Specifies the business webpage URL of the contact. |
| [HTTPMAIL_CALENDAR](#HTTPMAIL-CALENDAR) | Specifies the URL for the Calendar folder for a particular user. |
| [HTTPMAIL_HTML_DESCRIPTION](#HTTPMAIL-HTML-DESCRIPTION) | Specifies the HTML content of the message. |
| [HTTPMAIL_SEND_MESSAGE](#HTTPMAIL-SEND-MESSAGE) | Specifies the email submission URI to which outgoing email is submitted. |
| [ICON](#ICON) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ICON_INDEX](#ICON-INDEX) | Specifies which icon is to be used by a user interface when displaying a group of Message objects. |
| [IDENTITY_DISPLAY](#IDENTITY-DISPLAY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IDENTITY_ENTRYID](#IDENTITY-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IDENTITY_SEARCH_KEY](#IDENTITY-SEARCH-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IMAP_INTERNAL_DATE](#IMAP-INTERNAL-DATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IMPLICIT_CONVERSION_PROHIBITED](#IMPLICIT-CONVERSION-PROHIBITED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IMPORTANCE](#IMPORTANCE) | Indicates the level of importance assigned by the end user to the Message object. |
| [INBOUND_I_CAL_STREAM](#INBOUND-I-CAL-STREAM) | Contains the contents of the iCalendar MIME part of the original MIME message. |
| [INBOUND_NEWSFEED_DN](#INBOUND-NEWSFEED-DN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INCOMPLETE_COPY](#INCOMPLETE-COPY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INFO_PATH_FORM_NAME](#INFO-PATH-FORM-NAME) | Contains the name of the form associated with this message. |
| [INITIALS](#INITIALS) | Contains the initials for parts of the full name of the mail user. |
| [INITIAL_DETAILS_PANE](#INITIAL-DETAILS-PANE) | Indicates which page of a display template to display first. |
| [INSTANCE_KEY](#INSTANCE-KEY) | Contains an object on an NSPI server. |
| [INSTANCE_NUM](#INSTANCE-NUM) | Contains an identifier for a single instance of a row in the table. |
| [INSTANT_MESSAGING_ADDRESS](#INSTANT-MESSAGING-ADDRESS) | Specifies the instant messaging address of the contact. |
| [INST_ID](#INST-ID) | Contains an identifier for all instances of a row in the table. |
| [INTENDED_BUSY_STATUS](#INTENDED-BUSY-STATUS) | Contains the value of the PidLidBusyStatus property (section 2.47) on the Meeting object was sent. |
| [INTERNET_ACCOUNT_NAME](#INTERNET-ACCOUNT-NAME) | Specifies the user-visible email account name through which the email message is sent. |
| [INTERNET_ACCOUNT_STAMP](#INTERNET-ACCOUNT-STAMP) | Specifies the email account ID through which the email message is sent. |
| [INTERNET_APPROVED](#INTERNET-APPROVED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_ARTICLE_NUMBER](#INTERNET-ARTICLE-NUMBER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_CHARSET](#INTERNET-CHARSET) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_CODEPAGE](#INTERNET-CODEPAGE) | Indicates the code page used for the PidTagBody property (section 2.609) or the PidTagBodyHtml property (section 2.612). |
| [INTERNET_CONTROL](#INTERNET-CONTROL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_DISTRIBUTION](#INTERNET-DISTRIBUTION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_FOLLOWUP_TO](#INTERNET-FOLLOWUP-TO) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_LINES](#INTERNET-LINES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_MAIL_OVERRIDE_FORMAT](#INTERNET-MAIL-OVERRIDE-FORMAT) | Indicates the encoding method and HTML inclusion for attachments. |
| [INTERNET_MESSAGE_ID](#INTERNET-MESSAGE-ID) | Corresponds to the message-id field. |
| [INTERNET_NEWSGROUPS](#INTERNET-NEWSGROUPS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_NEWSGROUP_NAME](#INTERNET-NEWSGROUP-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_NNTP_PATH](#INTERNET-NNTP-PATH) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_ORGANIZATION](#INTERNET-ORGANIZATION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_PRECEDENCE](#INTERNET-PRECEDENCE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [INTERNET_REFERENCES](#INTERNET-REFERENCES) | Contains a list of message IDs that specify the messages to which this reply is related. |
| [INTERNET_SUBJECT](#INTERNET-SUBJECT) | Specifies the subject of the message. |
| [IN_CONFLICT](#IN-CONFLICT) | Specifies whether the attachment represents an alternate replica. |
| [IN_REPLY_TO_ID](#IN-REPLY-TO-ID) | Contains the value of the original message's PidTagInternetMessageId property (section 2.739) value. |
| [IN_TRANSIT](#IN-TRANSIT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_APPOINTMENT_ENTRY_ID](#IPM-APPOINTMENT-ENTRY-ID) | Contains the EntryID of the Calendar folder. |
| [IPM_CONTACT_ENTRY_ID](#IPM-CONTACT-ENTRY-ID) | Contains the EntryID of the Contacts folder. |
| [IPM_DAF_ENTRYID](#IPM-DAF-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_DRAFTS_ENTRY_ID](#IPM-DRAFTS-ENTRY-ID) | Contains the EntryID of the Drafts folder. |
| [IPM_FAVORITES_ENTRYID](#IPM-FAVORITES-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_ID](#IPM-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_JOURNAL_ENTRY_ID](#IPM-JOURNAL-ENTRY-ID) | Contains the EntryID of the Journal folder. |
| [IPM_NOTE_ENTRY_ID](#IPM-NOTE-ENTRY-ID) | Contains the EntryID of the Notes folder. |
| [IPM_OUTBOX_ENTRYID](#IPM-OUTBOX-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_OUTBOX_SEARCH_KEY](#IPM-OUTBOX-SEARCH-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_PUBLIC_FOLDERS_ENTRYID](#IPM-PUBLIC-FOLDERS-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_RETURN_REQUESTED](#IPM-RETURN-REQUESTED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_SENTMAIL_ENTRYID](#IPM-SENTMAIL-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_SENTMAIL_SEARCH_KEY](#IPM-SENTMAIL-SEARCH-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_SUBTREE_ENTRYID](#IPM-SUBTREE-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_SUBTREE_SEARCH_KEY](#IPM-SUBTREE-SEARCH-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_TASK_ENTRY_ID](#IPM-TASK-ENTRY-ID) | Contains the EntryID of the Tasks folder. |
| [IPM_WASTEBASKET_ENTRYID](#IPM-WASTEBASKET-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IPM_WASTEBASKET_SEARCH_KEY](#IPM-WASTEBASKET-SEARCH-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ISDN_NUMBER](#ISDN-NUMBER) | Contains the Integrated Services Digital Network (ISDN) telephone number of the mail user. |
| [IS_CONTACT_LINKED](#IS-CONTACT-LINKED) | Specifies whether the contact is linked to other contacts. |
| [IS_EXCEPTION](#IS-EXCEPTION) | Indicates whether the object represents an exception (including an orphan instance). |
| [IS_NEWSGROUP](#IS-NEWSGROUP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IS_NEWSGROUP_ANCHOR](#IS-NEWSGROUP-ANCHOR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [IS_RECURRING](#IS-RECURRING) | Specifies whether the object is associated with a recurring series. |
| [IS_SILENT](#IS-SILENT) | Indicates whether the user did not include any text in the body of the Meeting Response object. |
| [I_CALENDAR_DAY_OF_WEEK_MASK](#I-CALENDAR-DAY-OF-WEEK-MASK) | Identifies the day of the week for the appointment or meeting. |
| [I_CALENDAR_END_TIME](#I-CALENDAR-END-TIME) | Contains the date and time, in UTC, when an appointment or meeting ends. |
| [I_CALENDAR_RECURRENCE_DATE](#I-CALENDAR-RECURRENCE-DATE) | Identifies an array of instances of a recurring appointment. |
| [I_CALENDAR_RECURRENCE_RULE](#I-CALENDAR-RECURRENCE-RULE) | Specifies the rule for the pattern that defines a recurring appointment. |
| [I_CALENDAR_REMINDER_NEXT_TIME](#I-CALENDAR-REMINDER-NEXT-TIME) | Contains the date and time, in UTC, for the activation of the next reminder. |
| [I_CALENDAR_START_TIME](#I-CALENDAR-START-TIME) | Contains the date and time, in UTC, when the appointment or meeting starts. |
| [JUNK_ADD_RECIPIENTS_TO_SAFE_SENDERS_LIST](#JUNK-ADD-RECIPIENTS-TO-SAFE-SENDERS-LIST) | Indicates whether email recipients are to be added to the safe senders list. |
| [JUNK_INCLUDE_CONTACTS](#JUNK-INCLUDE-CONTACTS) | Indicates whether email addresses of the contacts in the Contacts folder are treated in a special way with respect to the spam filter. |
| [JUNK_PERMANENTLY_DELETE](#JUNK-PERMANENTLY-DELETE) | Indicates whether messages identified as spam can be permanently deleted. |
| [JUNK_PHISHING_ENABLE_LINKS](#JUNK-PHISHING-ENABLE-LINKS) | Indicated whether the phishing stamp on a message is to be ignored. |
| [JUNK_THRESHOLD](#JUNK-THRESHOLD) | Indicates how aggressively incoming email is to be sent to the Junk Email folder. |
| [KEYWORD](#KEYWORD) | Contains a keyword that identifies the mail user to the mail user's system administrator. |
| [KEYWORDS](#KEYWORDS) | Contains keywords or categories for the Message object. |
| [LANGUAGE](#LANGUAGE) | Contains a value that indicates the language in which the messaging user is writing messages. |
| [LANGUAGES](#LANGUAGES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [LAST_ACCESS_TIME](#LAST-ACCESS-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [LAST_AUTHOR](#LAST-AUTHOR) | Specifies the most recent author of the file attached to the Document object. |
| [LAST_FULL_BACKUP](#LAST-FULL-BACKUP) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [LAST_LOGOFF_TIME](#LAST-LOGOFF-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [LAST_LOGON_TIME](#LAST-LOGON-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [LAST_MODIFICATION_TIME](#LAST-MODIFICATION-TIME) | Contains the time, in UTC, of the last modification to the object. |
| [LAST_MODIFIER_ENTRY_ID](#LAST-MODIFIER-ENTRY-ID) | Specifies the Address Book EntryID of the last user to modify the contents of the message. |
| [LAST_MODIFIER_NAME](#LAST-MODIFIER-NAME) | Contains the name of the last mail user to change the Message object. |
| [LAST_PRINTED](#LAST-PRINTED) | Specifies the time, in UTC, that the file was last printed. |
| [LAST_SAVE_DATE_TIME](#LAST-SAVE-DATE-TIME) | Specifies the time, in UTC, that the file was last saved. |
| [LAST_VERB_EXECUTED](#LAST-VERB-EXECUTED) | Specifies the last verb executed for the message item to which it is related. |
| [LAST_VERB_EXECUTION_TIME](#LAST-VERB-EXECUTION-TIME) | Contains the date and time, in UTC, during which the operation represented in the PidTagLastVerbExecuted property (section 2.758) took place. |
| [LATEST_DELIVERY_TIME](#LATEST-DELIVERY-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [LINE_COUNT](#LINE-COUNT) | Specifies the number of lines in the file attached to the Document object. |
| [LINKED_TASK_ITEMS](#LINKED-TASK-ITEMS) | Indicates whether the user did not include any text in the body of the Meeting Response object. |
| [LINKS_DIRTY](#LINKS-DIRTY) | Indicates whether the links in the document are up-to-date. |
| [LIST_HELP](#LIST-HELP) | Contains a URI that provides detailed help information for the mailing list from which an email message was sent. |
| [LIST_SUBSCRIBE](#LIST-SUBSCRIBE) | Contains the URI that subscribes a recipient to a message\\ufffds associated mailing list. |
| [LIST_UNSUBSCRIBE](#LIST-UNSUBSCRIBE) | Contains the URI that unsubscribes a recipient from a message\\ufffds associated mailing list. |
| [LOCALE_ID](#LOCALE-ID) | Contains the Logon object LocaleID. |
| [LOCALITY](#LOCALITY) | Contains the name of the mail user's locality, such as the town or city. |
| [LOCAL_COMMIT_TIME](#LOCAL-COMMIT-TIME) | Specifies the time, in UTC, that a Message object or Folder object was last changed. |
| [LOCAL_COMMIT_TIME_MAX](#LOCAL-COMMIT-TIME-MAX) | Contains the time of the most recent message change within the folder container, excluding messages changed within subfolders. |
| [LOCATION](#LOCATION) | Specifies the location of the event. |
| [LOCATION_URL](#LOCATION-URL) | Area: Calendar Canonical name: PidNameLocationUrl Alternate names: urn:schemas:calendar:locationurl, LocationUrl |
| [LOG_DOCUMENT_POSTED](#LOG-DOCUMENT-POSTED) | Indicates whether the document was sent by email or posted to a server folder during journaling. |
| [LOG_DOCUMENT_PRINTED](#LOG-DOCUMENT-PRINTED) | Indicates whether the document was printed during journaling. |
| [LOG_DOCUMENT_ROUTED](#LOG-DOCUMENT-ROUTED) | Indicates whether the document was sent to a routing recipient during journaling. |
| [LOG_DOCUMENT_SAVED](#LOG-DOCUMENT-SAVED) | Indicates whether the document was saved during journaling. |
| [LOG_DURATION](#LOG-DURATION) | Contains the duration, in minutes, of the activity. |
| [LOG_END](#LOG-END) | Contains the time, in UTC, at which the activity ended. |
| [LOG_FLAGS](#LOG-FLAGS) | Contains metadata about the Journal object. |
| [LOG_START](#LOG-START) | Contains the time, in UTC, at which the activity began. |
| [LOG_TYPE](#LOG-TYPE) | Briefly describes the journal activity that is being recorded. |
| [LOG_TYPE_DESC](#LOG-TYPE-DESC) | Contains an expanded description of the journal activity that is being recorded. |
| [LONGTERM_ENTRYID_FROM_TABLE](#LONGTERM-ENTRYID-FROM-TABLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MAILBOX_OWNER_ENTRY_ID](#MAILBOX-OWNER-ENTRY-ID) | Contains the EntryID in the Global Address List (GAL) of the owner of the mailbox. |
| [MAILBOX_OWNER_NAME](#MAILBOX-OWNER-NAME) | Contains the display name of the owner of the mailbox. |
| [MAIL_PERMISSION](#MAIL-PERMISSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MANAGER](#MANAGER) | Specifies the manager of the file attached to the Document object. |
| [MANAGER_NAME](#MANAGER-NAME) | Contains the name of the mail user's manager. |
| [MAPPING_SIGNATURE](#MAPPING-SIGNATURE) | A 16-byte constant that is present on all Address Book objects, but is not present on objects in an offline address book. |
| [MAXIMUM_SUBMIT_MESSAGE_SIZE](#MAXIMUM-SUBMIT-MESSAGE-SIZE) | Maximum size, in kilobytes, of a message that a user is allowed to submit for transmission to another user. |
| [MDB_PROVIDER](#MDB-PROVIDER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MEETING_TYPE](#MEETING-TYPE) | Indicates the type of Meeting Request object or Meeting Update object. |
| [MEETING_WORKSPACE_URL](#MEETING-WORKSPACE-URL) | Specifies the URL of the Meeting Workspace that is associated with a Calendar object. |
| [MEMBER_ID](#MEMBER-ID) | Contains a unique identifier that the messaging server generates for each user. |
| [MEMBER_NAME](#MEMBER-NAME) | Contains the user-readable name of the user. |
| [MEMBER_RIGHTS](#MEMBER-RIGHTS) | Contains the permissions for the specified user. |
| [MESSAGE_ATTACHMENTS](#MESSAGE-ATTACHMENTS) | Identifies all attachments to the current message. |
| [MESSAGE_CC_ME](#MESSAGE-CC-ME) | Area: General Message Properties Canonical name: PidTagMessageCcMe Alternate names: PR\_MESSAGE\_CC\_ME, ptagMessageCcMe |
| [MESSAGE_CLASS](#MESSAGE-CLASS) | Denotes the specific type of the Message object. |
| [MESSAGE_CODEPAGE](#MESSAGE-CODEPAGE) | Specifies the code page used to encode the non-Unicode string properties on this Message object. |
| [MESSAGE_DELIVERY_ID](#MESSAGE-DELIVERY-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MESSAGE_DELIVERY_TIME](#MESSAGE-DELIVERY-TIME) | Specifies the time (in UTC) when the server received the message. |
| [MESSAGE_DOWNLOAD_TIME](#MESSAGE-DOWNLOAD-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MESSAGE_EDITOR_FORMAT](#MESSAGE-EDITOR-FORMAT) | Specifies the format that an email editor can use for editing the message body. |
| [MESSAGE_FLAGS](#MESSAGE-FLAGS) | Specifies the status of the Message object. |
| [MESSAGE_HANDLING_SYSTEM_COMMON_NAME](#MESSAGE-HANDLING-SYSTEM-COMMON-NAME) | Contains the common name of a messaging user for use in a message header. |
| [MESSAGE_LOCALE_ID](#MESSAGE-LOCALE-ID) | Contains the Windows Locale ID of the end-user who created this message. |
| [MESSAGE_PROCESSED](#MESSAGE-PROCESSED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MESSAGE_RECIPIENTS](#MESSAGE-RECIPIENTS) | Identifies all of the recipients of the current message. |
| [MESSAGE_RECIPIENT_ME](#MESSAGE-RECIPIENT-ME) | Indicates that the receiving mailbox owner is a primary or a carbon copy (Cc) recipient of this email message. |
| [MESSAGE_SECURITY_LABEL](#MESSAGE-SECURITY-LABEL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MESSAGE_SITE_NAME](#MESSAGE-SITE-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MESSAGE_SIZE](#MESSAGE-SIZE) | Contains the size, in bytes, consumed by the Message object on the server. |
| [MESSAGE_SIZE_EXTENDED](#MESSAGE-SIZE-EXTENDED) | Specifies the 64-bit version of the PidTagMessageSize property (section 2.787). |
| [MESSAGE_STATUS](#MESSAGE-STATUS) | Specifies the status of a message in a contents table. |
| [MESSAGE_SUBMISSION_ID](#MESSAGE-SUBMISSION-ID) | Contains a message identifier assigned by a message transfer agent. |
| [MESSAGE_TOKEN](#MESSAGE-TOKEN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MESSAGE_TO_ME](#MESSAGE-TO-ME) | Indicates that the receiving mailbox owner is one of the primary recipients of this email message. |
| [MID](#MID) | Contains a value that contains the MID of the message currently being synchronized. |
| [MIDDLE_NAME](#MIDDLE-NAME) | Specifies the middle name(s) of the contact. |
| [MILEAGE](#MILEAGE) | Contains the mileage information that is associated with an item. |
| [MIME_SKELETON](#MIME-SKELETON) | Contains the top-level MIME message headers, all MIME message body part headers, attachments. |
| [MINI_ICON](#MINI-ICON) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MOBILE_TELEPHONE_NUMBER](#MOBILE-TELEPHONE-NUMBER) | Contains the mail user's cellular telephone number. |
| [MODIFY_VERSION](#MODIFY-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MONTH_INTERVAL](#MONTH-INTERVAL) | Indicates the monthly interval of the appointment or meeting. |
| [MONTH_OF_YEAR](#MONTH-OF-YEAR) | Indicates the month of the year in which the appointment or meeting occurs. |
| [MONTH_OF_YEAR_MASK](#MONTH-OF-YEAR-MASK) | Indicates the calculated month of the year in which the appointment or meeting occurs. |
| [MOVE_TO_FOLDER_ENTRYID](#MOVE-TO-FOLDER-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MOVE_TO_STORE_ENTRYID](#MOVE-TO-STORE-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MSG_BODY_ID](#MSG-BODY-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MTS_SUBJECT_ID](#MTS-SUBJECT-ID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [MULTIMEDIA_CLIP_COUNT](#MULTIMEDIA-CLIP-COUNT) | Specifies the number of multimedia clips in the file attached to the Document object. |
| [NATIVE_BODY](#NATIVE-BODY) | Indicates the best available format for storing the message body. |
| [NET_SHOW_URL](#NET-SHOW-URL) | Specifies the URL to be launched when the user joins the meeting. |
| [NEWSFEED_INFO](#NEWSFEED-INFO) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NEWSGROUP_COMPONENT](#NEWSGROUP-COMPONENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NEWSGROUP_NAME](#NEWSGROUP-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NEWSGROUP_ROOT_FOLDER_ENTRYID](#NEWSGROUP-ROOT-FOLDER-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NEW_SUBS_GET_AUTO_ADD](#NEW-SUBS-GET-AUTO-ADD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NEXT_SEND_ACCT](#NEXT-SEND-ACCT) | Specifies the server that a client is currently attempting to use to send email. |
| [NICKNAME](#NICKNAME) | Contains the mail user's nickname. |
| [NNTP_ARTICLE_FOLDER_ENTRYID](#NNTP-ARTICLE-FOLDER-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NNTP_CONTROL_FOLDER_ENTRYID](#NNTP-CONTROL-FOLDER-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NNTP_XREF](#NNTP-XREF) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NON_DELIVERY_REPORT_DIAG_CODE](#NON-DELIVERY-REPORT-DIAG-CODE) | Contains the diagnostic code for a delivery status notification, as specified in [RFC3464]. |
| [NON_DELIVERY_REPORT_REASON_CODE](#NON-DELIVERY-REPORT-REASON-CODE) | Contains an integer value that indicates a reason for delivery failure. |
| [NON_DELIVERY_REPORT_STATUS_CODE](#NON-DELIVERY-REPORT-STATUS-CODE) | Contains the value of the Status field for a delivery status notification, as specified in [RFC3464]. |
| [NON_IPM_SUBTREE_ENTRYID](#NON-IPM-SUBTREE-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NON_RECEIPT_NOTIFICATION_REQUESTED](#NON-RECEIPT-NOTIFICATION-REQUESTED) | Specifies whether the client sends a non-read receipt. |
| [NON_RECEIPT_REASON](#NON-RECEIPT-REASON) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NON_SENDABLE_BCC](#NON-SENDABLE-BCC) | Contains a list of all of the unsendable attendees who are also resources. |
| [NON_SENDABLE_CC](#NON-SENDABLE-CC) | Contains a list of all of the unsendable attendees who are also optional attendees. |
| [NON_SENDABLE_TO](#NON-SENDABLE-TO) | Contains a list of all of the unsendable attendees who are also required attendees. |
| [NON_SEND_BCC_TRACK_STATUS](#NON-SEND-BCC-TRACK-STATUS) | Contains the value from the response table. |
| [NON_SEND_CC_TRACK_STATUS](#NON-SEND-CC-TRACK-STATUS) | Contains the value from the response table. |
| [NON_SEND_TO_TRACK_STATUS](#NON-SEND-TO-TRACK-STATUS) | Contains the value from the response table. |
| [NORMALIZED_SUBJECT](#NORMALIZED-SUBJECT) | Contains the normalized subject of the message. |
| [NORMAL_MESSAGE_SIZE](#NORMAL-MESSAGE-SIZE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NORMAL_MESSAGE_SIZE_EXTENDED](#NORMAL-MESSAGE-SIZE-EXTENDED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NORMAL_MSG_W_ATTACH_COUNT](#NORMAL-MSG-W-ATTACH-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [NOTE_COLOR](#NOTE-COLOR) | Specifies the suggested background color of the Note object. |
| [NOTE_COUNT](#NOTE-COUNT) | Specifies the number of notes in the file attached to the Document object. |
| [NOTE_HEIGHT](#NOTE-HEIGHT) | Specifies the height of the visible message window in pixels. |
| [NOTE_WIDTH](#NOTE-WIDTH) | Specifies the width of the visible message window in pixels. |
| [NOTE_X](#NOTE-X) | Specifies the distance, in pixels, from the left edge of the screen that a user interface displays a Note object. |
| [NOTE_Y](#NOTE-Y) | Specifies the distance, in pixels, from the top edge of the screen that a user interface displays a Note object. |
| [NO_END_DATE_FLAG](#NO-END-DATE-FLAG) | Indicates whether the recurrence pattern has an end date. |
| [NT_USER_NAME](#NT-USER-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OBJECT_TYPE](#OBJECT-TYPE) | Indicates the type of Server object. |
| [OBJECT_URI](#OBJECT-URI) | Contains exchange task uri. |
| [OBSOLETED_IPMS](#OBSOLETED-IPMS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OCCURRENCES](#OCCURRENCES) | Indicates the number of occurrences in the recurring appointment or meeting. |
| [OFFICE_LOCATION](#OFFICE-LOCATION) | Contains the mail user's office location. |
| [OFFLINE_ADDRBOOK_ENTRYID](#OFFLINE-ADDRBOOK-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OFFLINE_ADDRESS_BOOK_CONTAINER_GUID](#OFFLINE-ADDRESS-BOOK-CONTAINER-GUID) | A string-formatted GUID that represents the address list container object. |
| [OFFLINE_ADDRESS_BOOK_DISTINGUISHED_NAME](#OFFLINE-ADDRESS-BOOK-DISTINGUISHED-NAME) | Contains the DN of the address list that is contained in the OAB message. |
| [OFFLINE_ADDRESS_BOOK_MESSAGE_CLASS](#OFFLINE-ADDRESS-BOOK-MESSAGE-CLASS) | Contains the message class for full OAB messages. |
| [OFFLINE_ADDRESS_BOOK_NAME](#OFFLINE-ADDRESS-BOOK-NAME) | Contains the display name of the address list. |
| [OFFLINE_ADDRESS_BOOK_SEQUENCE](#OFFLINE-ADDRESS-BOOK-SEQUENCE) | Contains the sequence number of the OAB. |
| [OFFLINE_ADDRESS_BOOK_TRUNCATED_PROPERTIES](#OFFLINE-ADDRESS-BOOK-TRUNCATED-PROPERTIES) | Contains a list of the property tags that have been truncated or limited by the server. |
| [OFFLINE_FLAGS](#OFFLINE-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OFFLINE_MESSAGE_ENTRYID](#OFFLINE-MESSAGE-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OLDEST_DELETED_ON](#OLDEST-DELETED-ON) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OLD_LOCATION](#OLD-LOCATION) | Indicates the original value of the PidLidLocation property (section 2.159) before a meeting update. |
| [OLD_RECURRENCE_TYPE](#OLD-RECURRENCE-TYPE) | Indicates the recurrence pattern for the appointment or meeting. |
| [OLD_WHEN_END_WHOLE](#OLD-WHEN-END-WHOLE) | Indicates the original value of the PidLidAppointmentEndWhole property (section 2.14) before a meeting update. |
| [OLD_WHEN_START_WHOLE](#OLD-WHEN-START-WHOLE) | Indicates the original value of the PidLidAppointmentStartWhole property (section 2.29) before a meeting update. |
| [OMS_ACCOUNT_GUID](#OMS-ACCOUNT-GUID) | Contains the GUID of the SMS account used to deliver the message. |
| [OMS_MOBILE_MODEL](#OMS-MOBILE-MODEL) | Indicates the model of the mobile device used to send the SMS or MMS message. |
| [OMS_SCHEDULE_TIME](#OMS-SCHEDULE-TIME) | Contains the time, in UTC, at which the client requested that the service provider send the SMS or MMS message. |
| [OMS_SERVICE_TYPE](#OMS-SERVICE-TYPE) | Contains the type of service used to send an SMS or MMS message. |
| [OMS_SOURCE_TYPE](#OMS-SOURCE-TYPE) | Contains the source of an SMS or MMS message. |
| [ONLINE_PASSWORD](#ONLINE-PASSWORD) | Specifies the password for a meeting on which the PidLidConferencingType property (section 2.66) has the value 0x00000002. |
| [OPTIONAL_ATTENDEES](#OPTIONAL-ATTENDEES) | Specifies optional attendees. |
| [ORDINAL_MOST](#ORDINAL-MOST) | Contains a positive number whose negative is less than or equal to the value of the PidLidTaskOrdinal property (section 2.327) of all of the Task objects in the folder. |
| [ORGANIZATIONAL_ID_NUMBER](#ORGANIZATIONAL-ID-NUMBER) | Contains an identifier for the mail user used within the mail user's organization. |
| [ORGANIZER_ALIAS](#ORGANIZER-ALIAS) | Specifies the email address of the organizer. |
| [ORIGINALLY_INTENDED_RECIPIENT_NAME](#ORIGINALLY-INTENDED-RECIPIENT-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINALLY_INTENDED_RECIP_ADDRTYPE](#ORIGINALLY-INTENDED-RECIP-ADDRTYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINALLY_INTENDED_RECIP_EMAIL_ADDRESS](#ORIGINALLY-INTENDED-RECIP-EMAIL-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINALLY_INTENDED_RECIP_ENTRYID](#ORIGINALLY-INTENDED-RECIP-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINAL_AUTHOR_ADDRTYPE](#ORIGINAL-AUTHOR-ADDRTYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINAL_AUTHOR_EMAIL_ADDRESS](#ORIGINAL-AUTHOR-EMAIL-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINAL_AUTHOR_ENTRY_ID](#ORIGINAL-AUTHOR-ENTRY-ID) | Contains an address book EntryID structure ([MS-OXCDATA] section 2.2.5.2) and is defined in report messages to identify the user who sent the original message. |
| [ORIGINAL_AUTHOR_NAME](#ORIGINAL-AUTHOR-NAME) | Contains the display name of the sender of the original message referenced by a report message. |
| [ORIGINAL_AUTHOR_SEARCH_KEY](#ORIGINAL-AUTHOR-SEARCH-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINAL_DELIVERY_TIME](#ORIGINAL-DELIVERY-TIME) | Contains the delivery time, in UTC, from the original message. |
| [ORIGINAL_DISPLAY_BCC](#ORIGINAL-DISPLAY-BCC) | Contains the value of the PidTagDisplayBcc property (section 2.665) from the original message. |
| [ORIGINAL_DISPLAY_CC](#ORIGINAL-DISPLAY-CC) | Contains the value of the PidTagDisplayCc property(section 2.666) from the original message. |
| [ORIGINAL_DISPLAY_NAME](#ORIGINAL-DISPLAY-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINAL_DISPLAY_TO](#ORIGINAL-DISPLAY-TO) | Contains the value of the PidTagDisplayTo property (section 2.669) from the original message. |
| [ORIGINAL_EITS](#ORIGINAL-EITS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINAL_ENTRY_ID](#ORIGINAL-ENTRY-ID) | Contains the original EntryID of an object. |
| [ORIGINAL_MESSAGE_CLASS](#ORIGINAL-MESSAGE-CLASS) | Designates the PidTagMessageClass property ([MS-OXCMSG] section 2.2.1.3) from the original message. |
| [ORIGINAL_MESSAGE_ID](#ORIGINAL-MESSAGE-ID) | Contains the message ID of the original message included in replies or resent messages. |
| [ORIGINAL_SEARCH_KEY](#ORIGINAL-SEARCH-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINAL_SENDER_ADDRESS_TYPE](#ORIGINAL-SENDER-ADDRESS-TYPE) | Contains the value of the original message sender's PidTagSenderAddressType property (section 2.991). |
| [ORIGINAL_SENDER_EMAIL_ADDRESS](#ORIGINAL-SENDER-EMAIL-ADDRESS) | Contains the value of the original message sender's PidTagSenderEmailAddress property (section 2.992). |
| [ORIGINAL_SENDER_ENTRY_ID](#ORIGINAL-SENDER-ENTRY-ID) | Contains an address book EntryID that is set on delivery report messages. |
| [ORIGINAL_SENDER_NAME](#ORIGINAL-SENDER-NAME) | Contains the value of the original message sender's PidTagSenderName property (section 2.995), and is set on delivery report messages. |
| [ORIGINAL_SENDER_SEARCH_KEY](#ORIGINAL-SENDER-SEARCH-KEY) | Contains an address book search key set on the original email message. |
| [ORIGINAL_SENSITIVITY](#ORIGINAL-SENSITIVITY) | Contains the sensitivity value of the original email message. |
| [ORIGINAL_SENT_REPRESENTING_ADDRESS_TYPE](#ORIGINAL-SENT-REPRESENTING-ADDRESS-TYPE) | Contains the address type of the end user who is represented by the original email message sender. |
| [ORIGINAL_SENT_REPRESENTING_EMAIL_ADDRESS](#ORIGINAL-SENT-REPRESENTING-EMAIL-ADDRESS) | Contains the email address of the end user who is represented by the original email message sender. |
| [ORIGINAL_SENT_REPRESENTING_ENTRY_ID](#ORIGINAL-SENT-REPRESENTING-ENTRY-ID) | Identifies an address book EntryID that contains the entry identifier of the end user who is represented by the original message sender. |
| [ORIGINAL_SENT_REPRESENTING_NAME](#ORIGINAL-SENT-REPRESENTING-NAME) | Contains the display name of the end user who is represented by the original email message sender. |
| [ORIGINAL_SENT_REPRESENTING_SEARCH_KEY](#ORIGINAL-SENT-REPRESENTING-SEARCH-KEY) | Identifies an address book search key that contains the SearchKey of the end user who is represented by the original message sender. |
| [ORIGINAL_STORE_ENTRY_ID](#ORIGINAL-STORE-ENTRY-ID) | Specifies the EntryID of the delegator\\ufffds message store. |
| [ORIGINAL_SUBJECT](#ORIGINAL-SUBJECT) | Specifies the subject of the original message. |
| [ORIGINAL_SUBMIT_TIME](#ORIGINAL-SUBMIT-TIME) | Specifies the original email message's submission date and time, in UTC. |
| [ORIGINATING_MTA_CERTIFICATE](#ORIGINATING-MTA-CERTIFICATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINATOR_ADDR](#ORIGINATOR-ADDR) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINATOR_ADDRTYPE](#ORIGINATOR-ADDRTYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINATOR_AND_DL_EXPANSION_HISTORY](#ORIGINATOR-AND-DL-EXPANSION-HISTORY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINATOR_CERTIFICATE](#ORIGINATOR-CERTIFICATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINATOR_DELIVERY_REPORT_REQUESTED](#ORIGINATOR-DELIVERY-REPORT-REQUESTED) | Indicates whether an email sender requests an email delivery receipt from the messaging system. |
| [ORIGINATOR_ENTRYID](#ORIGINATOR-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINATOR_NAME](#ORIGINATOR-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINATOR_NON_DELIVERY_REPORT_REQUESTED](#ORIGINATOR-NON-DELIVERY-REPORT-REQUESTED) | Specifies whether an email sender requests suppression of nondelivery receipts. |
| [ORIGINATOR_REQUESTED_ALTERNATE_RECIPIENT](#ORIGINATOR-REQUESTED-ALTERNATE-RECIPIENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGINATOR_RETURN_ADDRESS](#ORIGINATOR-RETURN-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [ORIGIN_CHECK](#ORIGIN-CHECK) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OSC_SYNC_ENABLED](#OSC-SYNC-ENABLED) | Specifies whether contact synchronization with an external source is handled by the server. |
| [OST_ENCRYPTION](#OST-ENCRYPTION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | Specifies the complete address of the other address of the contact. |
| [OTHER_ADDRESS_CITY](#OTHER-ADDRESS-CITY) | Contains the name of the mail user's other locality, such as the town or city. |
| [OTHER_ADDRESS_COUNTRY](#OTHER-ADDRESS-COUNTRY) | Contains the name of the mail user's other country/region. |
| [OTHER_ADDRESS_COUNTRY_CODE](#OTHER-ADDRESS-COUNTRY-CODE) | Specifies the country code portion of the other address of the contact. |
| [OTHER_ADDRESS_POSTAL_CODE](#OTHER-ADDRESS-POSTAL-CODE) | Contains the postal code for the mail user's other postal address. |
| [OTHER_ADDRESS_POST_OFFICE_BOX](#OTHER-ADDRESS-POST-OFFICE-BOX) | Contains the number or identifier of the mail user's other post office box. |
| [OTHER_ADDRESS_STATE_OR_PROVINCE](#OTHER-ADDRESS-STATE-OR-PROVINCE) | Contains the name of the mail user's other state or province. |
| [OTHER_ADDRESS_STREET](#OTHER-ADDRESS-STREET) | Contains the mail user's other street address. |
| [OTHER_TELEPHONE_NUMBER](#OTHER-TELEPHONE-NUMBER) | Contains an alternate telephone number for the mail user. |
| [OUTBOUND_NEWSFEED_DN](#OUTBOUND-NEWSFEED-DN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OUT_OF_OFFICE_STATE](#OUT-OF-OFFICE-STATE) | Indicates whether the user is OOF. |
| [OVERALL_AGE_LIMIT](#OVERALL-AGE-LIMIT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OVERALL_MSG_AGE_LIMIT](#OVERALL-MSG-AGE-LIMIT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OWA_URL](#OWA-URL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OWNER_APPOINTMENT_ID](#OWNER-APPOINTMENT-ID) | Specifies a quasi-unique value among all of the Calendar objects in a user's mailbox. |
| [OWNER_COUNT](#OWNER-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [OWNER_CRITICAL_CHANGE](#OWNER-CRITICAL-CHANGE) | Specifies the date and time at which a Meeting Request object was sent by the organizer. |
| [OWNER_NAME](#OWNER-NAME) | Indicates the name of the owner of the mailbox. |
| [OWN_STORE_ENTRYID](#OWN-STORE-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [P1_CONTENT](#P1-CONTENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [P1_CONTENT_TYPE](#P1-CONTENT-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PAGER_TELEPHONE_NUMBER](#PAGER-TELEPHONE-NUMBER) | Contains the mail user's pager telephone number. |
| [PAGE_COUNT](#PAGE-COUNT) | Specifies the page count of the file attached to the Document object. |
| [PARAGRAPH_COUNT](#PARAGRAPH-COUNT) | Specifies the number of paragraphs in the file attached to the Document object. |
| [PARENT_DISPLAY](#PARENT-DISPLAY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PARENT_ENTRY_ID](#PARENT-ENTRY-ID) | Contains the EntryID of the folder where messages or subfolders reside. |
| [PARENT_FOLDER_ID](#PARENT-FOLDER-ID) | Contains a value that contains the Folder ID (FID), as specified in [MS-OXCDATA] section 2.2.1.1, that identifies the parent folder of the messaging object being synchronized. |
| [PARENT_KEY](#PARENT-KEY) | Contains the search key that is used to correlate the original message and the reports about the original message. |
| [PARENT_SOURCE_KEY](#PARENT-SOURCE-KEY) | Contains a value on a folder that contains the PidTagSourceKey property (section 2.1012) of the parent folder. |
| [PENDING_STATE_FOR_SITE_MAILBOX_DOCUMENT](#PENDING-STATE-FOR-SITE-MAILBOX-DOCUMENT) | Specifies the synchronization state of the Document object that is in the Document Libraries folder of the site mailbox. |
| [PERCENT_COMPLETE](#PERCENT-COMPLETE) | Indicates whether a time-flagged Message object is complete. |
| [PERSONAL_HOME_PAGE](#PERSONAL-HOME-PAGE) | Contains the URL of the mail user's personal home page. |
| [PHISHING_STAMP](#PHISHING-STAMP) | Indicates whether a message is likely to be phishing. |
| [PHYSICAL_DELIVERY_BUREAU_FAX_DELIVERY](#PHYSICAL-DELIVERY-BUREAU-FAX-DELIVERY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PHYSICAL_DELIVERY_MODE](#PHYSICAL-DELIVERY-MODE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PHYSICAL_DELIVERY_REPORT_REQUEST](#PHYSICAL-DELIVERY-REPORT-REQUEST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PHYSICAL_FORWARDING_ADDRESS](#PHYSICAL-FORWARDING-ADDRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PHYSICAL_FORWARDING_ADDRESS_REQUESTED](#PHYSICAL-FORWARDING-ADDRESS-REQUESTED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PHYSICAL_FORWARDING_PROHIBITED](#PHYSICAL-FORWARDING-PROHIBITED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PHYSICAL_RENDITION_ATTRIBUTES](#PHYSICAL-RENDITION-ATTRIBUTES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [POLICY_TAG](#POLICY-TAG) | Specifies the GUID of a retention tag. |
| [POSTAL_ADDRESS](#POSTAL-ADDRESS) | Contains the mail user's postal address. |
| [POSTAL_ADDRESS_ID](#POSTAL-ADDRESS-ID) | Specifies which physical address is the mailing address for this contact. |
| [POSTAL_CODE](#POSTAL-CODE) | Contains the postal code for the mail user's postal address. |
| [POST_FOLDER_ENTRIES](#POST-FOLDER-ENTRIES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [POST_FOLDER_NAMES](#POST-FOLDER-NAMES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [POST_OFFICE_BOX](#POST-OFFICE-BOX) | Contains the number or identifier of the mail user's post office box. |
| [POST_REPLY_DENIED](#POST-REPLY-DENIED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [POST_REPLY_FOLDER_ENTRIES](#POST-REPLY-FOLDER-ENTRIES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [POST_REPLY_FOLDER_NAMES](#POST-REPLY-FOLDER-NAMES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [POST_RSS_CHANNEL](#POST-RSS-CHANNEL) | Contains the contents of the title field from the XML of the Atom feed or RSS channel. |
| [POST_RSS_CHANNEL_LINK](#POST-RSS-CHANNEL-LINK) | Contains the URL of the RSS or Atom feed from which the XML file came. |
| [POST_RSS_ITEM_GUID](#POST-RSS-ITEM-GUID) | Contains a unique identifier for the RSS object. |
| [POST_RSS_ITEM_HASH](#POST-RSS-ITEM-HASH) | Contains a hash of the feed XML computed by using an implementation-dependent algorithm. |
| [POST_RSS_ITEM_LINK](#POST-RSS-ITEM-LINK) | Contains the URL of the link from an RSS or Atom item. |
| [POST_RSS_ITEM_XML](#POST-RSS-ITEM-XML) | Contains the item element and all of its sub-elements from an RSS feed, or the entry element and all of its sub-elements from an Atom feed. |
| [POST_RSS_SUBSCRIPTION](#POST-RSS-SUBSCRIPTION) | Contains the user's preferred name for the RSS or Atom subscription. |
| [PREDECESSOR_CHANGE_LIST](#PREDECESSOR-CHANGE-LIST) | Contains a value that contains a serialized representation of a PredecessorChangeList structure. |
| [PREPROCESS](#PREPROCESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PRESENTATION_FORMAT](#PRESENTATION-FORMAT) | Specifies the presentation format of the file attached to the Document object. |
| [PREVENT_MSG_CREATE](#PREVENT-MSG-CREATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PREVIEW](#PREVIEW) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PREVIEW_UNREAD](#PREVIEW-UNREAD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PRIMARY_CAPABILITY](#PRIMARY-CAPABILITY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PRIMARY_FAX_NUMBER](#PRIMARY-FAX-NUMBER) | Contains the telephone number of the mail user's primary fax machine. |
| [PRIMARY_SEND_ACCOUNT](#PRIMARY-SEND-ACCOUNT) | Specifies the first server that a client is to use to send the email with. |
| [PRIMARY_TELEPHONE_NUMBER](#PRIMARY-TELEPHONE-NUMBER) | Contains the mail user's primary telephone number. |
| [PRIORITY](#PRIORITY) | Indicates the client's request for the priority with which the message is to be sent by the messaging system. |
| [PRIVATE](#PRIVATE) | Indicates whether the end user wishes for this Message object to be hidden from other users who have access to the Message object. |
| [PROCESSED](#PROCESSED) | Indicates whether a client has already processed a received task communication. |
| [PROFESSION](#PROFESSION) | Contains the name of the mail user's line of business. |
| [PROFILE_AB_FILES_PATH](#PROFILE-AB-FILES-PATH) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_ADDR_INFO](#PROFILE-ADDR-INFO) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_ALLPUB_COMMENT](#PROFILE-ALLPUB-COMMENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_ALLPUB_DISPLAY_NAME](#PROFILE-ALLPUB-DISPLAY-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_BINDING_ORDER](#PROFILE-BINDING-ORDER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_CONFIG_FLAGS](#PROFILE-CONFIG-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_CONNECT_FLAGS](#PROFILE-CONNECT-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_FAVFLD_COMMENT](#PROFILE-FAVFLD-COMMENT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_FAVFLD_DISPLAY_NAME](#PROFILE-FAVFLD-DISPLAY-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_HOME_SERVER](#PROFILE-HOME-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_HOME_SERVER_ADDRS](#PROFILE-HOME-SERVER-ADDRS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_HOME_SERVER_DN](#PROFILE-HOME-SERVER-DN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_MAILBOX](#PROFILE-MAILBOX) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_MAX_RESTRICT](#PROFILE-MAX-RESTRICT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_MOAB](#PROFILE-MOAB) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_MOAB_GUID](#PROFILE-MOAB-GUID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_MOAB_SEQ](#PROFILE-MOAB-SEQ) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_NAME](#PROFILE-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_OFFLINE_INFO](#PROFILE-OFFLINE-INFO) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_OFFLINE_STORE_PATH](#PROFILE-OFFLINE-STORE-PATH) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_OPEN_FLAGS](#PROFILE-OPEN-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_OPTIONS_DATA](#PROFILE-OPTIONS-DATA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_SECURE_MAILBOX](#PROFILE-SECURE-MAILBOX) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_SERVER](#PROFILE-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_SERVER_DN](#PROFILE-SERVER-DN) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_TRANSPORT_FLAGS](#PROFILE-TRANSPORT-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_TYPE](#PROFILE-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_UI_STATE](#PROFILE-UI-STATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_UNRESOLVED_NAME](#PROFILE-UNRESOLVED-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_UNRESOLVED_SERVER](#PROFILE-UNRESOLVED-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_USER](#PROFILE-USER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROFILE_VERSION](#PROFILE-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROHIBIT_RECEIVE_QUOTA](#PROHIBIT-RECEIVE-QUOTA) | Maximum size, in kilobytes, that a user is allowed to accumulate in their mailbox before no further email will be delivered to their mailbox. |
| [PROHIBIT_SEND_QUOTA](#PROHIBIT-SEND-QUOTA) | Maximum size, in kilobytes, that a user is allowed to accumulate in their mailbox before the user can no longer send any more email. |
| [PROMPT_SEND_UPDATE](#PROMPT-SEND-UPDATE) | Indicates that the Meeting Response object was out-of-date when it was received. |
| [PROOF_OF_DELIVERY](#PROOF-OF-DELIVERY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROOF_OF_DELIVERY_REQUESTED](#PROOF-OF-DELIVERY-REQUESTED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROOF_OF_SUBMISSION](#PROOF-OF-SUBMISSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROOF_OF_SUBMISSION_REQUESTED](#PROOF-OF-SUBMISSION-REQUESTED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROVIDER_DISPLAY](#PROVIDER-DISPLAY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROVIDER_DLL_NAME](#PROVIDER-DLL-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROVIDER_ORDINAL](#PROVIDER-ORDINAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROVIDER_SUBMIT_TIME](#PROVIDER-SUBMIT-TIME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PROVIDER_UID](#PROVIDER-UID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PST_ENCRYPTION](#PST-ENCRYPTION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PST_PATH](#PST-PATH) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PST_PW_SZ_OLD](#PST-PW-SZ-OLD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PST_REMEMBER_PW](#PST-REMEMBER-PW) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PUBLIC_FOLDER_ENTRYID](#PUBLIC-FOLDER-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PUBLISH_IN_ADDRESS_BOOK](#PUBLISH-IN-ADDRESS-BOOK) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [PURPORTED_SENDER_DOMAIN](#PURPORTED-SENDER-DOMAIN) | Contains the domain responsible for transmitting the current message. |
| [QUARANTINE_ORIGINAL_SENDER](#QUARANTINE-ORIGINAL-SENDER) | Specifies the original sender of a message. |
| [RADIO_TELEPHONE_NUMBER](#RADIO-TELEPHONE-NUMBER) | Contains the mail user's radio telephone number. |
| [READ](#READ) | Indicates whether a message has been read. |
| [READ_RECEIPT_ADDRESS_TYPE](#READ-RECEIPT-ADDRESS-TYPE) | Contains the address type of the end user to whom a read receipt is directed. |
| [READ_RECEIPT_EMAIL_ADDRESS](#READ-RECEIPT-EMAIL-ADDRESS) | Contains the email address of the end user to whom a read receipt is directed. |
| [READ_RECEIPT_ENTRY_ID](#READ-RECEIPT-ENTRY-ID) | Contains an address book EntryID. |
| [READ_RECEIPT_NAME](#READ-RECEIPT-NAME) | Contains the display name for the end user to whom a read receipt is directed. |
| [READ_RECEIPT_REQUESTED](#READ-RECEIPT-REQUESTED) | Specifies whether the email sender requests a read receipt from all recipients when this email message is read or opened. |
| [READ_RECEIPT_SEARCH_KEY](#READ-RECEIPT-SEARCH-KEY) | Contains an address book search key. |
| [READ_RECEIPT_SMTP_ADDRESS](#READ-RECEIPT-SMTP-ADDRESS) | Contains the SMTP email address of the user to whom a read receipt is directed. |
| [RECEIPT_TIME](#RECEIPT-TIME) | Contains the sent time for a message disposition notification, as specified in [RFC3798]. |
| [RECEIVED_BY_ADDRESS_TYPE](#RECEIVED-BY-ADDRESS-TYPE) | Contains the email message receiver's email address type. |
| [RECEIVED_BY_EMAIL_ADDRESS](#RECEIVED-BY-EMAIL-ADDRESS) | Contains the email message receiver's email address. |
| [RECEIVED_BY_ENTRY_ID](#RECEIVED-BY-ENTRY-ID) | Contains the address book EntryID of the mailbox receiving the Email object. |
| [RECEIVED_BY_NAME](#RECEIVED-BY-NAME) | Contains the email message receiver's display name. |
| [RECEIVED_BY_SEARCH_KEY](#RECEIVED-BY-SEARCH-KEY) | Identifies an address book search key that contains a binary-comparable key that is used to identify correlated objects for a search. |
| [RECEIVED_BY_SMTP_ADDRESS](#RECEIVED-BY-SMTP-ADDRESS) | Contains the email message receiver's SMTP email address. |
| [RECEIVED_REPRESENTING_ADDRESS_TYPE](#RECEIVED-REPRESENTING-ADDRESS-TYPE) | Contains the email address type for the end user represented by the receiving mailbox owner. |
| [RECEIVED_REPRESENTING_EMAIL_ADDRESS](#RECEIVED-REPRESENTING-EMAIL-ADDRESS) | Contains the email address for the end user represented by the receiving mailbox owner. |
| [RECEIVED_REPRESENTING_ENTRY_ID](#RECEIVED-REPRESENTING-ENTRY-ID) | Contains an address book EntryID that identifies the end user represented by the receiving mailbox owner. |
| [RECEIVED_REPRESENTING_NAME](#RECEIVED-REPRESENTING-NAME) | Contains the display name for the end user represented by the receiving mailbox owner. |
| [RECEIVED_REPRESENTING_SEARCH_KEY](#RECEIVED-REPRESENTING-SEARCH-KEY) | Identifies an address book search key that contains a binary-comparable key of the end user represented by the receiving mailbox owner. |
| [RECEIVED_REPRESENTING_SMTP_ADDRESS](#RECEIVED-REPRESENTING-SMTP-ADDRESS) | Contains the SMTP email address of the user represented by the receiving mailbox owner. |
| [RECEIVE_FOLDER_SETTINGS](#RECEIVE-FOLDER-SETTINGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RECIPIENT_CERTIFICATE](#RECIPIENT-CERTIFICATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RECIPIENT_DISPLAY_NAME](#RECIPIENT-DISPLAY-NAME) | Specifies the display name of the recipient. |
| [RECIPIENT_ENTRY_ID](#RECIPIENT-ENTRY-ID) | Identifies an Address Book object that specifies the recipient. |
| [RECIPIENT_FLAGS](#RECIPIENT-FLAGS) | Specifies a bit field that describes the recipient status. |
| [RECIPIENT_NUMBER](#RECIPIENT-NUMBER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RECIPIENT_NUMBER_FOR_ADVICE](#RECIPIENT-NUMBER-FOR-ADVICE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RECIPIENT_ON_ASSOC_MSG_COUNT](#RECIPIENT-ON-ASSOC-MSG-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RECIPIENT_ON_NORMAL_MSG_COUNT](#RECIPIENT-ON-NORMAL-MSG-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RECIPIENT_ORDER](#RECIPIENT-ORDER) | Specifies the location of the current recipient in the recipient table. |
| [RECIPIENT_PROPOSED](#RECIPIENT-PROPOSED) | Indicates that the attendee proposed a new date and/or time. |
| [RECIPIENT_PROPOSED_END_TIME](#RECIPIENT-PROPOSED-END-TIME) | Indicates the meeting end time requested by the attendee in a counter proposal. |
| [RECIPIENT_PROPOSED_START_TIME](#RECIPIENT-PROPOSED-START-TIME) | Indicates the meeting start time requested by the attendee in a counter proposal. |
| [RECIPIENT_REASSIGNMENT_PROHIBITED](#RECIPIENT-REASSIGNMENT-PROHIBITED) | Specifies whether adding additional or different recipients is prohibited for the email message when forwarding the email message. |
| [RECIPIENT_STATUS](#RECIPIENT-STATUS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RECIPIENT_TRACK_STATUS](#RECIPIENT-TRACK-STATUS) | Indicates the response status that is returned by the attendee. |
| [RECIPIENT_TRACK_STATUS_TIME](#RECIPIENT-TRACK-STATUS-TIME) | Indicates the date and time at which the attendee responded. |
| [RECIPIENT_TYPE](#RECIPIENT-TYPE) | Represents the recipient type of a recipient on the message. |
| [RECORD_KEY](#RECORD-KEY) | Contains a unique binary-comparable identifier for a specific object. |
| [RECURRENCE_DURATION](#RECURRENCE-DURATION) | Identifies the length, in minutes, of the appointment or meeting. |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Specifies a description of the recurrence pattern of the Calendar object. |
| [RECURRENCE_TYPE](#RECURRENCE-TYPE) | Specifies the recurrence type of the recurring series. |
| [RECURRING](#RECURRING) | Specifies whether the object represents a recurring series. |
| [REDIRECTION_HISTORY](#REDIRECTION-HISTORY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REFERENCE_ENTRY_ID](#REFERENCE-ENTRY-ID) | Specifies the value of the EntryID of the Contact object unless the Contact object is a copy of an earlier original. |
| [REFERRED_BY_NAME](#REFERRED-BY-NAME) | Contains the name of the mail user's referral. |
| [REGISTERED_MAIL_TYPE](#REGISTERED-MAIL-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RELATED_IPMS](#RELATED-IPMS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REMINDERS_ONLINE_ENTRY_ID](#REMINDERS-ONLINE-ENTRY-ID) | Contains an EntryID for the Reminders folder. |
| [REMINDER_DELTA](#REMINDER-DELTA) | Specifies the interval, in minutes, between the time at which the reminder first becomes overdue and the start time of the Calendar object. |
| [REMINDER_FILE_PARAMETER](#REMINDER-FILE-PARAMETER) | Specifies the filename of the sound that a client is to play when the reminder for that object becomes overdue. |
| [REMINDER_OVERRIDE](#REMINDER-OVERRIDE) | Specifies whether the client is to respect the current values of the property (section 2.219), or use the default values for those properties. |
| [REMINDER_PLAY_SOUND](#REMINDER-PLAY-SOUND) | Specifies whether the client is to play a sound when the reminder becomes overdue. |
| [REMINDER_SET](#REMINDER-SET) | Specifies whether a reminder is set on the object. |
| [REMINDER_SIGNAL_TIME](#REMINDER-SIGNAL-TIME) | Specifies the point in time when a reminder transitions from pending to overdue. |
| [REMINDER_TIME](#REMINDER-TIME) | Specifies the initial signal time for objects that are not Calendar objects. |
| [REMINDER_TIME_DATE](#REMINDER-TIME-DATE) | Indicates the time and date of the reminder for the appointment or meeting. |
| [REMINDER_TIME_TIME](#REMINDER-TIME-TIME) | Indicates the time of the reminder for the appointment or meeting. |
| [REMINDER_TYPE](#REMINDER-TYPE) | This property is not set and, if set, is ignored. |
| [REMOTE_MESSAGE_TRANSFER_AGENT](#REMOTE-MESSAGE-TRANSFER-AGENT) | Contains the value of the Remote-MTA field for a delivery status notification, as specified in [RFC3464]. |
| [REMOTE_PROGRESS](#REMOTE-PROGRESS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REMOTE_PROGRESS_TEXT](#REMOTE-PROGRESS-TEXT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REMOTE_STATUS](#REMOTE-STATUS) | Indicates the remote status of the calendar item. |
| [REMOTE_VALIDATE_OK](#REMOTE-VALIDATE-OK) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RENDERING_POSITION](#RENDERING-POSITION) | Represents an offset, in rendered characters, to use when rendering an attachment within the main message text. |
| [REPLICATION_ALWAYS_INTERVAL](#REPLICATION-ALWAYS-INTERVAL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPLICATION_MESSAGE_PRIORITY](#REPLICATION-MESSAGE-PRIORITY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPLICATION_MSG_SIZE](#REPLICATION-MSG-SIZE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPLICATION_SCHEDULE](#REPLICATION-SCHEDULE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPLICATION_STYLE](#REPLICATION-STYLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPLICA_LIST](#REPLICA-LIST) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPLICA_SERVER](#REPLICA-SERVER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPLICA_VERSION](#REPLICA-VERSION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPLY_RECIPIENT_ENTRIES](#REPLY-RECIPIENT-ENTRIES) | Identifies a FlatEntryList structure ([MS-OXCDATA] section 2.3.3) of address book EntryIDs for recipients that are to receive a reply. |
| [REPLY_RECIPIENT_NAMES](#REPLY-RECIPIENT-NAMES) | Contains a list of display names for recipients that are to receive a reply. |
| [REPLY_RECIPIENT_SMTP_PROXIES](#REPLY-RECIPIENT-SMTP-PROXIES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPLY_REQUESTED](#REPLY-REQUESTED) | Indicates whether a reply is requested to a Message object. |
| [REPLY_TEMPLATE_ID](#REPLY-TEMPLATE-ID) | Contains the value of the GUID that points to a Reply template. |
| [REPLY_TIME](#REPLY-TIME) | Specifies the time, in UTC, that the sender has designated for an associated work item to be due. |
| [REPORTING_DL_NAME](#REPORTING-DL-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPORTING_MESSAGE_TRANSFER_AGENT](#REPORTING-MESSAGE-TRANSFER-AGENT) | Contains the value of the Reporting-MTA field for a delivery status notification, as specified in [RFC3464]. |
| [REPORTING_MTA_CERTIFICATE](#REPORTING-MTA-CERTIFICATE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPORT_DESTINATION_ENTRYID](#REPORT-DESTINATION-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPORT_DESTINATION_NAME](#REPORT-DESTINATION-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REPORT_DISPOSITION](#REPORT-DISPOSITION) | Contains a string indicating whether the original message was displayed to the user or deleted (report messages only). |
| [REPORT_DISPOSITION_MODE](#REPORT-DISPOSITION-MODE) | Contains a description of the action that a client has performed on behalf of a user (report messages only). |
| [REPORT_ENTRY_ID](#REPORT-ENTRY-ID) | Specifies an entry ID that identifies the application that generated a report message. |
| [REPORT_NAME](#REPORT-NAME) | Contains the display name for the entity (usually a server agent) that generated the report message. |
| [REPORT_SEARCH_KEY](#REPORT-SEARCH-KEY) | Contains an address book search key representing the entity (usually a server agent) that generated the report message. |
| [REPORT_TAG](#REPORT-TAG) | Contains the data that is used to correlate the report and the original message. |
| [REPORT_TEXT](#REPORT-TEXT) | Contains the optional text for a report message. |
| [REPORT_TIME](#REPORT-TIME) | Indicates the last time that the contact list that is controlled by the PidTagJunkIncludeContacts property (section 2.749) was updated. |
| [REQUESTED_DELIVERY_METHOD](#REQUESTED-DELIVERY-METHOD) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Identifies required attendees for the appointment or meeting. |
| [RESOLVE_METHOD](#RESOLVE-METHOD) | Specifies how to resolve any conflicts with the message. |
| [RESOURCE_ATTENDEES](#RESOURCE-ATTENDEES) | Identifies resource attendees for the appointment or meeting. |
| [RESOURCE_FLAGS](#RESOURCE-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RESOURCE_METHODS](#RESOURCE-METHODS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RESOURCE_PATH](#RESOURCE-PATH) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RESOURCE_TYPE](#RESOURCE-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RESPONSE_REQUESTED](#RESPONSE-REQUESTED) | Indicates whether a response is requested to a Message object. |
| [RESPONSE_STATUS](#RESPONSE-STATUS) | Specifies the response status of an attendee. |
| [RESPONSIBILITY](#RESPONSIBILITY) | Specifies whether another mail agent has ensured that the message will be delivered. |
| [RESTRICTION_COUNT](#RESTRICTION-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RETENTION_AGE_LIMIT](#RETENTION-AGE-LIMIT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RETENTION_DATE](#RETENTION-DATE) | Specifies the date, in UTC, after which a Message object is expired by the server. |
| [RETENTION_FLAGS](#RETENTION-FLAGS) | Contains flags that specify the status or nature of an item's retention tag or archive tag. |
| [RETENTION_PERIOD](#RETENTION-PERIOD) | Specifies the number of days that a Message object can remain unarchived. |
| [RETURNED_IPM](#RETURNED-IPM) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [REVISION_NUMBER](#REVISION-NUMBER) | Specifies the revision number of the file attached to the Document object. |
| [RIGHTS](#RIGHTS) | Specifies a user's folder permissions. |
| [RIGHTS_MANAGEMENT_LICENSE](#RIGHTS-MANAGEMENT-LICENSE) | Specifies the value used to cache the Use License for the rights-managed email message. |
| [ROAMING_DATATYPES](#ROAMING-DATATYPES) | Contains a bitmask that indicates which stream properties exist on the message. |
| [ROAMING_DICTIONARY](#ROAMING-DICTIONARY) | Contains a dictionary stream, as specified in [MS-OXOCFG] section 2.2.5.1. |
| [ROAMING_XML_STREAM](#ROAMING-XML-STREAM) | Contains an XML stream, as specified in [MS-OXOCFG] section 2.2.5.2. |
| [ROWID](#ROWID) | Contains a unique identifier for a recipient in a message's recipient table. |
| [ROW_TYPE](#ROW-TYPE) | Identifies the type of the row. |
| [RTF_COMPRESSED](#RTF-COMPRESSED) | Contains message body text in compressed RTF format. |
| [RTF_IN_SYNC](#RTF-IN-SYNC) | Indicates whether the PidTagBody property (section 2.609) and the PidTagRtfCompressed property (section 2.932) contain the same text (ignoring formatting). |
| [RTF_SYNC_BODY_COUNT](#RTF-SYNC-BODY-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RTF_SYNC_BODY_CRC](#RTF-SYNC-BODY-CRC) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RTF_SYNC_BODY_TAG](#RTF-SYNC-BODY-TAG) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RTF_SYNC_PREFIX_COUNT](#RTF-SYNC-PREFIX-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RTF_SYNC_TRAILING_COUNT](#RTF-SYNC-TRAILING-COUNT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RULES_DATA](#RULES-DATA) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RULES_TABLE](#RULES-TABLE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RULE_ACTIONS](#RULE-ACTIONS) | Contains the set of actions associated with the rule. |
| [RULE_ACTION_NUMBER](#RULE-ACTION-NUMBER) | Contains the index of a rule action that failed. |
| [RULE_ACTION_TYPE](#RULE-ACTION-TYPE) | Contains the ActionType field ([MS-OXORULE] section 2.2.5.1) of a rule that failed. |
| [RULE_CONDITION](#RULE-CONDITION) | Defines the conditions under which a rule action is to be executed. |
| [RULE_ERROR](#RULE-ERROR) | Contains the error code that indicates the cause of an error encountered during the execution of the rule. |
| [RULE_FOLDER_ENTRY_ID](#RULE-FOLDER-ENTRY-ID) | Contains the EntryID of the folder where the rule that triggered the generation of a DAM is stored. |
| [RULE_ID](#RULE-ID) | Specifies a unique identifier that is generated by the messaging server for each rule when the rule is first created. |
| [RULE_IDS](#RULE-IDS) | Contains a buffer that is obtained by concatenating the PidTagRuleId property (section property (section 2.625). |
| [RULE_LEVEL](#RULE-LEVEL) | Contains 0x00000000. |
| [RULE_MESSAGE_LEVEL](#RULE-MESSAGE-LEVEL) | Contains 0x00000000. |
| [RULE_MESSAGE_NAME](#RULE-MESSAGE-NAME) | Specifies the name of the rule. |
| [RULE_MESSAGE_PROVIDER](#RULE-MESSAGE-PROVIDER) | Identifies the client application that owns the rule. |
| [RULE_MESSAGE_PROVIDER_DATA](#RULE-MESSAGE-PROVIDER-DATA) | Contains opaque data set by the client for the exclusive use of the client. |
| [RULE_MESSAGE_SEQUENCE](#RULE-MESSAGE-SEQUENCE) | Contains a value used to determine the order in which rules are evaluated and executed. |
| [RULE_MESSAGE_STATE](#RULE-MESSAGE-STATE) | Contains flags that specify the state of the rule. |
| [RULE_MESSAGE_USER_FLAGS](#RULE-MESSAGE-USER-FLAGS) | Contains an opaque property that the client sets for the exclusive use of the client. |
| [RULE_NAME](#RULE-NAME) | Specifies the name of the rule. |
| [RULE_PROVIDER](#RULE-PROVIDER) | A string identifying the client application that owns a rule. |
| [RULE_PROVIDER_DATA](#RULE-PROVIDER-DATA) | Contains opaque data set by the client for the exclusive use of the client. |
| [RULE_SEQUENCE](#RULE-SEQUENCE) | Contains a value used to determine the order in which rules are evaluated and executed. |
| [RULE_STATE](#RULE-STATE) | Contains flags that specify the state of the rule. |
| [RULE_TRIGGER_HISTORY](#RULE-TRIGGER-HISTORY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [RULE_USER_FLAGS](#RULE-USER-FLAGS) | Contains an opaque property that the client sets for the exclusive use of the client. |
| [RW_RULES_STREAM](#RW-RULES-STREAM) | Contains additional rule data about the Rule FAI message. |
| [SCALE](#SCALE) | Indicates whether the image is to be scaled or cropped. |
| [SCHEDULE_FOLDER_ENTRYID](#SCHEDULE-FOLDER-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SCHEDULE_INFO_APPOINTMENT_TOMBSTONE](#SCHEDULE-INFO-APPOINTMENT-TOMBSTONE) | Contains a list of tombstones, where each tombstone represents a Meeting object that has been declined. |
| [SCHEDULE_INFO_AUTO_ACCEPT_APPOINTMENTS](#SCHEDULE-INFO-AUTO-ACCEPT-APPOINTMENTS) | Indicates whether a client or server is to automatically respond to all meeting requests for the attendee or resource. |
| [SCHEDULE_INFO_DELEGATE_ENTRY_IDS](#SCHEDULE-INFO-DELEGATE-ENTRY-IDS) | Specifies the EntryIDs of the delegates. |
| [SCHEDULE_INFO_DELEGATE_NAMES](#SCHEDULE-INFO-DELEGATE-NAMES) | Specifies the names of the delegates. |
| [SCHEDULE_INFO_DELEGATE_NAMES_W](#SCHEDULE-INFO-DELEGATE-NAMES-W) | Specifies the names of the delegates in Unicode. |
| [SCHEDULE_INFO_DELEGATOR_WANTS_COPY](#SCHEDULE-INFO-DELEGATOR-WANTS-COPY) | Indicates whether the delegator wants to receive copies of the meeting-related objects that are sent to the delegate. |
| [SCHEDULE_INFO_DELEGATOR_WANTS_INFO](#SCHEDULE-INFO-DELEGATOR-WANTS-INFO) | Indicates whether the delegator wants to receive informational updates. |
| [SCHEDULE_INFO_DISALLOW_OVERLAPPING_APPTS](#SCHEDULE-INFO-DISALLOW-OVERLAPPING-APPTS) | Indicates whether a client or server, when automatically responding to meeting requests, is to decline Meeting Request objects that overlap with previously scheduled events. |
| [SCHEDULE_INFO_DISALLOW_RECURRING_APPTS](#SCHEDULE-INFO-DISALLOW-RECURRING-APPTS) | Indicates whether a client or server, when automatically responding to meeting requests, is to decline Meeting Request objects that represent a recurring series. |
| [SCHEDULE_INFO_DONT_MAIL_DELEGATES](#SCHEDULE-INFO-DONT-MAIL-DELEGATES) | Contains a value set to TRUE by the client, regardless of user input. |
| [SCHEDULE_INFO_FREE_BUSY](#SCHEDULE-INFO-FREE-BUSY) | This property is deprecated and is not to be used. |
| [SCHEDULE_INFO_FREE_BUSY_AWAY](#SCHEDULE-INFO-FREE-BUSY-AWAY) | Specifies the times for which the free/busy status is set a value of OOF. |
| [SCHEDULE_INFO_FREE_BUSY_BUSY](#SCHEDULE-INFO-FREE-BUSY-BUSY) | Specifies the blocks of time for which the free/busy status is set to a value of busy. |
| [SCHEDULE_INFO_FREE_BUSY_MERGED](#SCHEDULE-INFO-FREE-BUSY-MERGED) | Specifies the blocks for which free/busy data of type busy or OOF is present in the free/busy message. |
| [SCHEDULE_INFO_FREE_BUSY_TENTATIVE](#SCHEDULE-INFO-FREE-BUSY-TENTATIVE) | Specifies the blocks of times for which the free/busy status is set to a value of tentative. |
| [SCHEDULE_INFO_MONTHS_AWAY](#SCHEDULE-INFO-MONTHS-AWAY) | Specifies the months for which free/busy data of type OOF is present in the free/busy message. |
| [SCHEDULE_INFO_MONTHS_BUSY](#SCHEDULE-INFO-MONTHS-BUSY) | Specifies the months for which free/busy data of type busy is present in the free/busy message. |
| [SCHEDULE_INFO_MONTHS_MERGED](#SCHEDULE-INFO-MONTHS-MERGED) | Specifies the months for which free/busy data of type busy or OOF is present in the free/busy message. |
| [SCHEDULE_INFO_MONTHS_TENTATIVE](#SCHEDULE-INFO-MONTHS-TENTATIVE) | Specifies the months for which free/busy data of type tentative is present in the free/busy message. |
| [SCHEDULE_INFO_RESOURCE_TYPE](#SCHEDULE-INFO-RESOURCE-TYPE) | Set to 0x00000000 when sending and is ignored on receipt. |
| [SCHEDULE_PLUS_FREE_BUSY_ENTRY_ID](#SCHEDULE-PLUS-FREE-BUSY-ENTRY-ID) | Contains the EntryID of the folder named "SCHEDULE+ FREE BUSY" under the non-IPM subtree of the public folder message store. |
| [SCRIPT_DATA](#SCRIPT-DATA) | Contains a series of instructions that can be executed to format an address and the data that is needed to execute those instructions. |
| [SEARCH](#SEARCH) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SEARCH_FOLDER_DEFINITION](#SEARCH-FOLDER-DEFINITION) | Specifies the search criteria and search options. |
| [SEARCH_FOLDER_EFP_FLAGS](#SEARCH-FOLDER-EFP-FLAGS) | Specifies flags that control how a folder is displayed. |
| [SEARCH_FOLDER_EXPIRATION](#SEARCH-FOLDER-EXPIRATION) | Contains the time, in UTC, at which the search folder container will be stale and has to be updated or recreated. |
| [SEARCH_FOLDER_ID](#SEARCH-FOLDER-ID) | Contains a GUID that identifies the search folder. |
| [SEARCH_FOLDER_LAST_USED](#SEARCH-FOLDER-LAST-USED) | Contains the last time, in UTC, that the folder was accessed. |
| [SEARCH_FOLDER_RECREATE_INFO](#SEARCH-FOLDER-RECREATE-INFO) | This property is not to be used. |
| [SEARCH_FOLDER_STORAGE_TYPE](#SEARCH-FOLDER-STORAGE-TYPE) | Contains flags that specify the binary large object (BLOB) data that appears in the PidTagSearchFolderDefinition (section 2.979) property. |
| [SEARCH_FOLDER_TAG](#SEARCH-FOLDER-TAG) | Contains the value of the SearchFolderTag sub-property of the PidTagExtendedFolderFlags (section 2.682) property of the search folder container. |
| [SEARCH_FOLDER_TEMPLATE_ID](#SEARCH-FOLDER-TEMPLATE-ID) | Contains the ID of the template that is being used for the search. |
| [SEARCH_KEY](#SEARCH-KEY) | Contains a unique binary-comparable key that identifies an object for a search. |
| [SECURE_IN_SITE](#SECURE-IN-SITE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SECURE_ORIGINATION](#SECURE-ORIGINATION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SECURITY](#SECURITY) | Specifies the security level of the file attached to the Document object. |
| [SECURITY_DESCRIPTOR_AS_XML](#SECURITY-DESCRIPTOR-AS-XML) | Contains security attributes in XML. |
| [SELECTABLE](#SELECTABLE) | This property is not set and, if set, is ignored. |
| [SENDER_ADDRESS_TYPE](#SENDER-ADDRESS-TYPE) | Contains the email address type of the sending mailbox owner. |
| [SENDER_EMAIL_ADDRESS](#SENDER-EMAIL-ADDRESS) | Contains the email address of the sending mailbox owner. |
| [SENDER_ENTRY_ID](#SENDER-ENTRY-ID) | Identifies an address book EntryID that contains the address book EntryID of the sending mailbox owner. |
| [SENDER_ID_STATUS](#SENDER-ID-STATUS) | Reports the results of a Sender-ID check. |
| [SENDER_NAME](#SENDER-NAME) | Contains the display name of the sending mailbox owner. |
| [SENDER_SEARCH_KEY](#SENDER-SEARCH-KEY) | Identifies an address book search key. |
| [SENDER_SMTP_ADDRESS](#SENDER-SMTP-ADDRESS) | Contains the SMTP email address format of the e\\ufffdmail address of the sending mailbox owner. |
| [SENDER_TELEPHONE_NUMBER](#SENDER-TELEPHONE-NUMBER) | Contains the telephone number of the caller associated with a voice mail message. |
| [SEND_INTERNET_ENCODING](#SEND-INTERNET-ENCODING) | Contains a bitmask of message encoding preferences for email sent to an email-enabled entity that is represented by this Address Book object. |
| [SEND_RICH_INFO](#SEND-RICH-INFO) | Indicates whether the email-enabled entity represented by the Address Book object can receive all message content, including Rich Text Format (RTF) and other embedded objects. |
| [SENSITIVITY](#SENSITIVITY) | Indicates the sender's assessment of the sensitivity of the Message object. |
| [SENTMAIL_ENTRYID](#SENTMAIL-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SENT_MAIL_SVR_EID](#SENT-MAIL-SVR-EID) | Contains an EntryID that represents the Sent Items folder for the message. |
| [SENT_REPRESENTING_ADDRESS_TYPE](#SENT-REPRESENTING-ADDRESS-TYPE) | Contains an email address type. |
| [SENT_REPRESENTING_EMAIL_ADDRESS](#SENT-REPRESENTING-EMAIL-ADDRESS) | Contains an email address for the end user who is represented by the sending mailbox owner. |
| [SENT_REPRESENTING_ENTRY_ID](#SENT-REPRESENTING-ENTRY-ID) | Contains the identifier of the end user who is represented by the sending mailbox owner. |
| [SENT_REPRESENTING_FLAGS](#SENT-REPRESENTING-FLAGS) | Area: Miscellaneous Properties Canonical name: PidTagSentRepresentingFlags Alternate names: ptagSentRepresentingFlags |
| [SENT_REPRESENTING_NAME](#SENT-REPRESENTING-NAME) | Contains the display name for the end user who is represented by the sending mailbox owner. |
| [SENT_REPRESENTING_SEARCH_KEY](#SENT-REPRESENTING-SEARCH-KEY) | Contains a binary-comparable key that represents the end user who is represented by the sending mailbox owner. |
| [SENT_REPRESENTING_SMTP_ADDRESS](#SENT-REPRESENTING-SMTP-ADDRESS) | Contains the SMTP email address of the end user who is represented by the sending mailbox owner. |
| [SERVER_PROCESSED](#SERVER-PROCESSED) | Indicates whether the Meeting Request object or Meeting Update object has been processed. |
| [SERVER_PROCESSING_ACTIONS](#SERVER-PROCESSING-ACTIONS) | Indicates what processing actions have been taken on this Meeting Request object or Meeting Update object. |
| [SERVICES](#SERVICES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SERVICE_DELETE_FILES](#SERVICE-DELETE-FILES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SERVICE_DLL_NAME](#SERVICE-DLL-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SERVICE_ENTRY_NAME](#SERVICE-ENTRY-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SERVICE_EXTRA_UIDS](#SERVICE-EXTRA-UIDS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SERVICE_NAME](#SERVICE-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SERVICE_SUPPORT_FILES](#SERVICE-SUPPORT-FILES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SERVICE_UID](#SERVICE-UID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SHARING_ANONYMITY](#SHARING-ANONYMITY) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_BINDING_ENTRY_ID](#SHARING-BINDING-ENTRY-ID) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_BROWSE_URL](#SHARING-BROWSE-URL) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_CAPABILITIES](#SHARING-CAPABILITIES) | Indicates that the Message object relates to a special folder. |
| [SHARING_CONFIGURATION_URL](#SHARING-CONFIGURATION-URL) | Contains a zero-length string. |
| [SHARING_DATA_RANGE_END](#SHARING-DATA-RANGE-END) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_DATA_RANGE_START](#SHARING-DATA-RANGE-START) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_DETAIL](#SHARING-DETAIL) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_EXTENSION_XML](#SHARING-EXTENSION-XML) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_FILTER](#SHARING-FILTER) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_FLAGS](#SHARING-FLAGS) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_FLAVOR](#SHARING-FLAVOR) | Indicates the type of Sharing Message object. |
| [SHARING_FOLDER_ENTRY_ID](#SHARING-FOLDER-ENTRY-ID) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_INDEX_ENTRY_ID](#SHARING-INDEX-ENTRY-ID) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_INITIATOR_ENTRY_ID](#SHARING-INITIATOR-ENTRY-ID) | Contains the value of the PidTagEntryId property (section 2.674) for the Address Book object of the currently logged-on user. |
| [SHARING_INITIATOR_NAME](#SHARING-INITIATOR-NAME) | Contains the value of the PidTagDisplayName property (section 2.667) from the Address Book object identified by the PidLidSharingInitiatorEntryId property (section 2.248). |
| [SHARING_INITIATOR_SMTP](#SHARING-INITIATOR-SMTP) | Contains the value of the PidTagSmtpAddress property (section 2.1010) from the Address Book object identified by the PidLidSharingInitiatorEntryId property (section 2.248). |
| [SHARING_INSTANCE_GUID](#SHARING-INSTANCE-GUID) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_LAST_AUTO_SYNC_TIME](#SHARING-LAST-AUTO-SYNC-TIME) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_LAST_SYNC_TIME](#SHARING-LAST-SYNC-TIME) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_LOCAL_COMMENT](#SHARING-LOCAL-COMMENT) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_LOCAL_LAST_MODIFICATION_TIME](#SHARING-LOCAL-LAST-MODIFICATION-TIME) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_LOCAL_NAME](#SHARING-LOCAL-NAME) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_LOCAL_PATH](#SHARING-LOCAL-PATH) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_LOCAL_STORE_UID](#SHARING-LOCAL-STORE-UID) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_LOCAL_TYPE](#SHARING-LOCAL-TYPE) | Contains the value of the PidTagContainerClass property (section 2.633) of the folder being shared. |
| [SHARING_LOCAL_UID](#SHARING-LOCAL-UID) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_ORIGINAL_MESSAGE_ENTRY_ID](#SHARING-ORIGINAL-MESSAGE-ENTRY-ID) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_PARENT_BINDING_ENTRY_ID](#SHARING-PARENT-BINDING-ENTRY-ID) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_PARTICIPANTS](#SHARING-PARTICIPANTS) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_PERMISSIONS](#SHARING-PERMISSIONS) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_PROVIDER_EXTENSION](#SHARING-PROVIDER-EXTENSION) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_PROVIDER_GUID](#SHARING-PROVIDER-GUID) | Contains the value "%xAE.F0.06.00.00.00.00.00.C0.00.00.00.00.00.00.46". |
| [SHARING_PROVIDER_NAME](#SHARING-PROVIDER-NAME) | Contains a user-displayable name of the sharing provider identified by the PidLidSharingProviderGuid property (section 2.266). |
| [SHARING_PROVIDER_URL](#SHARING-PROVIDER-URL) | Contains a URL related to the sharing provider identified by the PidLidSharingProviderGuid property (section 2.266). |
| [SHARING_RANGE_END](#SHARING-RANGE-END) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_RANGE_START](#SHARING-RANGE-START) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_RECIPROCATION](#SHARING-RECIPROCATION) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_REMOTE_BYTE_SIZE](#SHARING-REMOTE-BYTE-SIZE) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_REMOTE_COMMENT](#SHARING-REMOTE-COMMENT) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_REMOTE_CRC](#SHARING-REMOTE-CRC) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_REMOTE_LAST_MODIFICATION_TIME](#SHARING-REMOTE-LAST-MODIFICATION-TIME) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_REMOTE_MESSAGE_COUNT](#SHARING-REMOTE-MESSAGE-COUNT) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_REMOTE_NAME](#SHARING-REMOTE-NAME) | Contains the value of the PidTagDisplayName property (section 2.667) on the folder being shared. |
| [SHARING_REMOTE_PASS](#SHARING-REMOTE-PASS) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_REMOTE_PATH](#SHARING-REMOTE-PATH) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_REMOTE_STORE_UID](#SHARING-REMOTE-STORE-UID) | Contains a hexadecimal string representation of the value of the PidTagStoreEntryId property (section 2.1018) on the folder being shared. |
| [SHARING_REMOTE_TYPE](#SHARING-REMOTE-TYPE) | Contains the same value as the PidLidSharingLocalType property (section 2.259). |
| [SHARING_REMOTE_UID](#SHARING-REMOTE-UID) | Contains the EntryID of the folder being shared. |
| [SHARING_REMOTE_USER](#SHARING-REMOTE-USER) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_REMOTE_VERSION](#SHARING-REMOTE-VERSION) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_RESPONSE_TIME](#SHARING-RESPONSE-TIME) | Contains the time at which the recipient of the sharing request sent a sharing response. |
| [SHARING_RESPONSE_TYPE](#SHARING-RESPONSE-TYPE) | Contains the type of response with which the recipient of the sharing request responded. |
| [SHARING_ROAM_LOG](#SHARING-ROAM-LOG) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_START](#SHARING-START) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_STATUS](#SHARING-STATUS) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_STOP](#SHARING-STOP) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_SYNC_FLAGS](#SHARING-SYNC-FLAGS) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_SYNC_INTERVAL](#SHARING-SYNC-INTERVAL) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_TIME_TO_LIVE](#SHARING-TIME-TO-LIVE) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_TIME_TO_LIVE_AUTO](#SHARING-TIME-TO-LIVE-AUTO) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_WORKING_HOURS_DAYS](#SHARING-WORKING-HOURS-DAYS) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_WORKING_HOURS_END](#SHARING-WORKING-HOURS-END) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_WORKING_HOURS_START](#SHARING-WORKING-HOURS-START) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SHARING_WORKING_HOURS_TIME_ZONE](#SHARING-WORKING-HOURS-TIME-ZONE) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [SIDE_EFFECTS](#SIDE-EFFECTS) | Specifies how a Message object is handled by the client in relation to certain user interface actions by the user, such as deleting a message. |
| [SINGLE_BODY_I_CAL](#SINGLE-BODY-I-CAL) | Indicates that the original MIME message contained a single MIME part. |
| [SLIDE_COUNT](#SLIDE-COUNT) | Specifies the number of slides in the file attached to the Document object. |
| [SMART_NO_ATTACH](#SMART-NO-ATTACH) | Indicates whether the Message object has no end-user visible attachments. |
| [SMTP_ADDRESS](#SMTP-ADDRESS) | Contains the SMTP address of the Message object. |
| [SORT_LOCALE_ID](#SORT-LOCALE-ID) | Contains the locale identifier. |
| [SOURCE_KEY](#SOURCE-KEY) | Contains a value that contains an internal global identifier (GID) for this folder or message. |
| [SPAM_ORIGINAL_FOLDER](#SPAM-ORIGINAL-FOLDER) | Specifies which folder a message was in before it was filtered into the Junk Email folder. |
| [SPOKEN_NAME](#SPOKEN-NAME) | Contains a recording of the mail user's name pronunciation. |
| [SPOOLER_STATUS](#SPOOLER-STATUS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SPOUSE_NAME](#SPOUSE-NAME) | Contains the name of the mail user's spouse/partner. |
| [START_DATE](#START-DATE) | Contains the value of the PidLidAppointmentStartWhole property (section 2.29). |
| [START_DATE_ETC](#START-DATE-ETC) | Contains the default retention period, and the start date from which the age of a Message object is calculated. |
| [START_RECURRENCE_DATE](#START-RECURRENCE-DATE) | Identifies the start date of the recurrence pattern. |
| [START_RECURRENCE_TIME](#START-RECURRENCE-TIME) | Identifies the start time of the recurrence pattern. |
| [STATE_OR_PROVINCE](#STATE-OR-PROVINCE) | Contains the name of the mail user's state or province. |
| [STATUS](#STATUS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [STATUS_CODE](#STATUS-CODE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [STATUS_STRING](#STATUS-STRING) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [STORAGE_LIMIT_INFORMATION](#STORAGE-LIMIT-INFORMATION) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [STORAGE_QUOTA_LIMIT](#STORAGE-QUOTA-LIMIT) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [STORE_ENTRY_ID](#STORE-ENTRY-ID) | Contains the unique EntryID of the message store where an object resides. |
| [STORE_OFFLINE](#STORE-OFFLINE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [STORE_PROVIDERS](#STORE-PROVIDERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [STORE_RECORD_KEY](#STORE-RECORD-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [STORE_SLOWLINK](#STORE-SLOWLINK) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [STORE_STATE](#STORE-STATE) | Indicates whether a mailbox has any active Search folders. |
| [STORE_SUPPORT_MASK](#STORE-SUPPORT-MASK) | Indicates whether string properties within the .msg file are Unicode-encoded. |
| [STREET_ADDRESS](#STREET-ADDRESS) | Contains the mail user's street address. |
| [SUBFOLDERS](#SUBFOLDERS) | Specifies whether a folder has subfolders. |
| [SUBJECT](#SUBJECT) | Specifies the subject of the file attached to the Document object. |
| [SUBJECT_IPM](#SUBJECT-IPM) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SUBJECT_PREFIX](#SUBJECT-PREFIX) | Contains the prefix for the subject of the message. |
| [SUBJECT_TRACE_INFO](#SUBJECT-TRACE-INFO) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SUBMIT_FLAGS](#SUBMIT-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SUPERSEDES](#SUPERSEDES) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SUPPLEMENTARY_INFO](#SUPPLEMENTARY-INFO) | Contains supplementary information about a delivery status notification, as specified in [RFC3464]. |
| [SURNAME](#SURNAME) | Contains the mail user's family name. |
| [SVR_GENERATING_QUOTA_MSG](#SVR-GENERATING-QUOTA-MSG) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SWAPPED_TO_DO_DATA](#SWAPPED-TO-DO-DATA) | Contains a secondary storage location for flags when sender flags or sender reminders are supported. |
| [SWAPPED_TO_DO_STORE](#SWAPPED-TO-DO-STORE) | Contains the value of the PidTagStoreEntryId property (section 2.1018) of the message when the value of the PidTagSwappedToDoData property (section 2.1027) is set. |
| [SYNCHRONIZE_FLAGS](#SYNCHRONIZE-FLAGS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [SYS_CONFIG_FOLDER_ENTRYID](#SYS-CONFIG-FOLDER-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [TAG_EXCEPTION_REPLACE_TIME](#TAG-EXCEPTION-REPLACE-TIME) | Indicates the original date and time, in UTC, at which the instance in the recurrence pattern would have occurred if it were not an exception. |
| [TAG_HTML](#TAG-HTML) | Contains message body text in HTML format. |
| [TAG_LOCATION](#TAG-LOCATION) | Contains the location of the mail user. |
| [TAG_SUBJECT](#TAG-SUBJECT) | Contains the subject of the email message. |
| [TAG_TITLE](#TAG-TITLE) | Contains the mail user's job title. |
| [TARGET_ENTRY_ID](#TARGET-ENTRY-ID) | Contains the message ID of a Message object being submitted for optimization ([MS- OXOMSG] section 3.2.4.4). |
| [TASK_ACCEPTANCE_STATE](#TASK-ACCEPTANCE-STATE) | Indicates the acceptance state of the task. |
| [TASK_ACCEPTED](#TASK-ACCEPTED) | Indicates whether a task assignee has replied to a task request for this Task object. |
| [TASK_ACTUAL_EFFORT](#TASK-ACTUAL-EFFORT) | Indicates the number of minutes that the user actually spent working on a task. |
| [TASK_ASSIGNER](#TASK-ASSIGNER) | Specifies the name of the user that last assigned the task. |
| [TASK_ASSIGNERS](#TASK-ASSIGNERS) | Contains a stack of entries, each of which represents a task assigner. |
| [TASK_COMPLETE](#TASK-COMPLETE) | Indicates that the task is complete. |
| [TASK_CUSTOM_FLAGS](#TASK-CUSTOM-FLAGS) | The client can set this property, but it has no impact on the Task-Related Objects Protocol and is ignored by the server. |
| [TASK_DATE_COMPLETED](#TASK-DATE-COMPLETED) | Specifies the date when the user completed work on the task. |
| [TASK_DEAD_OCCURRENCE](#TASK-DEAD-OCCURRENCE) | Indicates whether new occurrences remain to be generated. |
| [TASK_DUE_DATE](#TASK-DUE-DATE) | Specifies the date by which the user expects work on the task to be complete. |
| [TASK_ESTIMATED_EFFORT](#TASK-ESTIMATED-EFFORT) | Indicates the number of minutes that the user expects to work on a task. |
| [TASK_F_CREATOR](#TASK-F-CREATOR) | Indicates that the Task object was originally created by the action of the current user or user agent instead of by the processing of a task request. |
| [TASK_F_FIX_OFFLINE](#TASK-F-FIX-OFFLINE) | Indicates the accuracy of the PidLidTaskOwner property (section 2.328). |
| [TASK_F_RECURRING](#TASK-F-RECURRING) | Indicates whether the task includes a recurrence pattern. |
| [TASK_GLOBAL_ID](#TASK-GLOBAL-ID) | Contains a unique GUID for this task, which is used to locate an existing task upon receipt of a task response or task update. |
| [TASK_HISTORY](#TASK-HISTORY) | Indicates the type of change that was last made to the Task object. |
| [TASK_LAST_DELEGATE](#TASK-LAST-DELEGATE) | Contains the name of the user who most recently assigned the task, or the user to whom it was most recently assigned. |
| [TASK_LAST_UPDATE](#TASK-LAST-UPDATE) | Contains the date and time of the most recent change made to the Task object. |
| [TASK_LAST_USER](#TASK-LAST-USER) | Contains the name of the most recent user to have been the owner of the task. |
| [TASK_MODE](#TASK-MODE) | Specifies the assignment status of the embedded Task object. |
| [TASK_MULTIPLE_RECIPIENTS](#TASK-MULTIPLE-RECIPIENTS) | Provides optimization hints about the recipients of a Task object. |
| [TASK_NO_COMPUTE](#TASK-NO-COMPUTE) | Not used. |
| [TASK_ORDINAL](#TASK-ORDINAL) | Provides an aid to custom sorting of Task objects. |
| [TASK_OWNER](#TASK-OWNER) | Contains the name of the owner of the task. |
| [TASK_OWNERSHIP](#TASK-OWNERSHIP) | Indicates the role of the current user relative to the Task object. |
| [TASK_RECURRENCE](#TASK-RECURRENCE) | Contains a RecurrencePattern structure that provides information about recurring tasks. |
| [TASK_RESET_REMINDER](#TASK-RESET-REMINDER) | Indicates whether future instances of recurring tasks need reminders, even though the value of the PidLidReminderSet property (section 2.222) is 0x00. |
| [TASK_ROLE](#TASK-ROLE) | Not used. |
| [TASK_START_DATE](#TASK-START-DATE) | Specifies the date on which the user expects work on the task to begin. |
| [TASK_STATE](#TASK-STATE) | Indicates the current assignment state of the Task object. |
| [TASK_STATUS](#TASK-STATUS) | Specifies the status of a task. |
| [TASK_STATUS_ON_COMPLETE](#TASK-STATUS-ON-COMPLETE) | Indicates whether the task assignee has been requested to send an email message update upon completion of the assigned task. |
| [TASK_UPDATES](#TASK-UPDATES) | Indicates whether the task assignee has been requested to send a task update when the assigned Task object changes. |
| [TASK_VERSION](#TASK-VERSION) | Indicates which copy is the latest update of a Task object. |
| [TEAM_TASK](#TEAM-TASK) | This property is set by the client but is ignored by the server. |
| [TELECOMMUNICATIONS_DEVICE_FOR_DEAF_TELEPHONE_NUMBER](#TELECOMMUNICATIONS-DEVICE-FOR-DEAF-TELEPHONE-NUMBER) | Contains the mail user's telecommunication device for the deaf (TTY/TDD) telephone number. |
| [TELEX_NUMBER](#TELEX-NUMBER) | Contains the mail user's telex number. |
| [TEMPLATE](#TEMPLATE) | Specifies the template of the file attached to the Document object. |
| [TEMPLATEID](#TEMPLATEID) | Contains the value of the PidTagEntryId property (section 2.674), expressed as a Permanent Entry ID format. |
| [TEMPLATE_DATA](#TEMPLATE-DATA) | Describes the controls used in the template that is used to retrieve address book information. |
| [TEST_LINE_SPEED](#TEST-LINE-SPEED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [TEXT_ATTACHMENT_CHARSET](#TEXT-ATTACHMENT-CHARSET) | Specifies the character set of an attachment received via MIME with the content-type of text. |
| [THUMBNAIL](#THUMBNAIL) | Specifies the data representing the thumbnail image of the document. |
| [THUMBNAIL_PHOTO](#THUMBNAIL-PHOTO) | Contains the mail user's photo in .jpg format. |
| [TIME_ZONE](#TIME-ZONE) | Specifies information about the time zone of a recurring meeting. |
| [TIME_ZONE_DESCRIPTION](#TIME-ZONE-DESCRIPTION) | Specifies a human-readable description of the time zone that is represented by the data in the PidLidTimeZoneStruct property (section 2.342). |
| [TIME_ZONE_STRUCT](#TIME-ZONE-STRUCT) | Specifies time zone information for a recurring meeting. |
| [TITLE](#TITLE) | Specifies the title of the file attached to the Document object. |
| [TNEF_CORRELATION_KEY](#TNEF-CORRELATION-KEY) | Contains a value that correlates a Transport Neutral Encapsulation Format (TNEF) attachment with a message. |
| [TO_ATTENDEES_STRING](#TO-ATTENDEES-STRING) | Contains a list of all of the sendable attendees who are also required attendees. |
| [TO_DO_ITEM_FLAGS](#TO-DO-ITEM-FLAGS) | Contains flags associated with objects. |
| [TO_DO_ORDINAL_DATE](#TO-DO-ORDINAL-DATE) | Contains the current time, in UTC, which is used to determine the sort order of objects in a consolidated to-do list. |
| [TO_DO_SUB_ORDINAL](#TO-DO-SUB-ORDINAL) | Contains the numerals 0 through 9 that are used to break a tie when the PidLidToDoOrdinalDate property (section 2.344) is used to perform a sort of objects. |
| [TO_DO_TITLE](#TO-DO-TITLE) | Contains user-specifiable text to identify this Message object in a consolidated to-do list. |
| [TRACE_INFO](#TRACE-INFO) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [TRANSFER_ENABLED](#TRANSFER-ENABLED) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [TRANSMITTABLE_DISPLAY_NAME](#TRANSMITTABLE-DISPLAY-NAME) | Contains an Address Book object's display name that is transmitted with the message. |
| [TRANSPORT_KEY](#TRANSPORT-KEY) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [TRANSPORT_MESSAGE_HEADERS](#TRANSPORT-MESSAGE-HEADERS) | Contains transport-specific message envelope information for email. |
| [TRANSPORT_PROVIDERS](#TRANSPORT-PROVIDERS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [TRANSPORT_STATUS](#TRANSPORT-STATUS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [TRUST_SENDER](#TRUST-SENDER) | Specifies whether the associated message was delivered through a trusted transport channel. |
| [TYPE_OF_MTS_USER](#TYPE-OF-MTS-USER) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [USER_CERTIFICATE](#USER-CERTIFICATE) | Contains an ASN.1 authentication certificate for a messaging user. |
| [USER_ENTRY_ID](#USER-ENTRY-ID) | Address book EntryID of the user logged on to the public folders. |
| [USER_NAME](#USER-NAME) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [USER_X_509_CERTIFICATE](#USER-X-509-CERTIFICATE) | Contains a list of certificates for the mail user. |
| [USE_TNEF](#USE-TNEF) | Specifies whether Transport Neutral Encapsulation Format (TNEF) is to be included on a message when the message is converted from TNEF to MIME or SMTP format. |
| [VALID_FLAG_STRING_PROOF](#VALID-FLAG-STRING-PROOF) | Contains the value of the PidTagMessageDeliveryTime property (section 2.780) when modifying the PidLidFlagRequest property (section 2.136). |
| [VALID_FOLDER_MASK](#VALID-FOLDER-MASK) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [VERB_RESPONSE](#VERB-RESPONSE) | Specifies the voting option that a respondent has selected. |
| [VERB_STREAM](#VERB-STREAM) | Specifies what voting responses the user can make in response to the message. |
| [VIEWS_ENTRYID](#VIEWS-ENTRYID) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [VIEW_DESCRIPTOR_BINARY](#VIEW-DESCRIPTOR-BINARY) | Contains view definitions. |
| [VIEW_DESCRIPTOR_NAME](#VIEW-DESCRIPTOR-NAME) | Area: MessageClassDefinedTransmittable Canonical name: PidTagViewDescriptorName Alternate names: PR\_VD\_NAME, PR\_VD\_NAME\_W |
| [VIEW_DESCRIPTOR_STRINGS](#VIEW-DESCRIPTOR-STRINGS) | Contains view definitions in string format. |
| [VIEW_DESCRIPTOR_VERSION](#VIEW-DESCRIPTOR-VERSION) | Contains the View Descriptor version. |
| [VOICE_MESSAGE_ATTACHMENT_ORDER](#VOICE-MESSAGE-ATTACHMENT-ORDER) | Contains a list of file names for the audio file attachments that are to be played as part of a message. |
| [VOICE_MESSAGE_DURATION](#VOICE-MESSAGE-DURATION) | Specifies the length of the attached audio message, in seconds. |
| [VOICE_MESSAGE_SENDER_NAME](#VOICE-MESSAGE-SENDER-NAME) | Specifies the name of the caller who left the attached voice message, as provided by the voice network's caller ID system. |
| [WEDDING_ANNIVERSARY](#WEDDING-ANNIVERSARY) | Contains the date of the mail user's wedding anniversary. |
| [WEDDING_ANNIVERSARY_LOCAL](#WEDDING-ANNIVERSARY-LOCAL) | Specifies the wedding anniversary of the contact, at midnight in the client's local time zone, and is saved without any time zone conversions. |
| [WEEK_INTERVAL](#WEEK-INTERVAL) | Identifies the number of weeks that occur between each meeting. |
| [WHERE](#WHERE) | Contains the value of the PidLidLocation property (section 2.159) from the associated Meeting object. |
| [WLINK_ADDRESS_BOOK_EID](#WLINK-ADDRESS-BOOK-EID) | Specifies the value of the PidTagEntryId property (section 2.674) of the user to whom the folder belongs. |
| [WLINK_ADDRESS_BOOK_STORE_EID](#WLINK-ADDRESS-BOOK-STORE-EID) | Specifies the value of the PidTagStoreEntryId property (section 2.1018) of the current user (not the owner of the folder). |
| [WLINK_CALENDAR_COLOR](#WLINK-CALENDAR-COLOR) | Specifies the background color of the calendar. |
| [WLINK_CLIENT_ID](#WLINK-CLIENT-ID) | Specifies the Client ID that allows the client to determine whether the shortcut was created on the current machine/user via an equality test. |
| [WLINK_ENTRY_ID](#WLINK-ENTRY-ID) | Specifies the EntryID of the folder pointed to by the shortcut. |
| [WLINK_FLAGS](#WLINK-FLAGS) | Specifies conditions associated with the shortcut. |
| [WLINK_FOLDER_TYPE](#WLINK-FOLDER-TYPE) | Specifies the type of folder pointed to by the shortcut. |
| [WLINK_GROUP_CLSID](#WLINK-GROUP-CLSID) | Specifies the value of the PidTagWlinkGroupHeaderID property (section 2.1060) of the group header associated with the shortcut. |
| [WLINK_GROUP_HEADER_ID](#WLINK-GROUP-HEADER-ID) | Specifies the ID of the navigation shortcut that groups other navigation shortcuts. |
| [WLINK_GROUP_NAME](#WLINK-GROUP-NAME) | Specifies the value of the PidTagNormalizedSubject (section 2.803) of the group header associated with the shortcut. |
| [WLINK_ORDINAL](#WLINK-ORDINAL) | Specifies a variable-length binary property to be used to sort shortcuts lexicographically. |
| [WLINK_RECORD_KEY](#WLINK-RECORD-KEY) | Specifies the value of PidTagRecordKey property (section 2.901) of the folder pointed to by the shortcut. |
| [WLINK_RO_GROUP_TYPE](#WLINK-RO-GROUP-TYPE) | Specifies the type of group header. |
| [WLINK_SAVE_STAMP](#WLINK-SAVE-STAMP) | Specifies an integer that allows a client to identify with a high probability whether the navigation shortcut was saved by the current client session. |
| [WLINK_SECTION](#WLINK-SECTION) | Specifies the section where the shortcut should be grouped. |
| [WLINK_STORE_ENTRY_ID](#WLINK-STORE-ENTRY-ID) | Specifies the value of the PidTagStoreEntryId property (section 2.1018) of the folder pointed to by the shortcut. |
| [WLINK_TYPE](#WLINK-TYPE) | Specifies the type of navigation shortcut. |
| [WORD_COUNT](#WORD-COUNT) | Specifies the word count of the file attached to the Document object. |
| [WORK_ADDRESS](#WORK-ADDRESS) | Specifies the complete address of the work address of the contact. |
| [WORK_ADDRESS_CITY](#WORK-ADDRESS-CITY) | Specifies the city or locality portion of the work address of the contact. |
| [WORK_ADDRESS_COUNTRY](#WORK-ADDRESS-COUNTRY) | Specifies the country or region portion of the work address of the contact. |
| [WORK_ADDRESS_COUNTRY_CODE](#WORK-ADDRESS-COUNTRY-CODE) | Specifies the country code portion of the work address of the contact. |
| [WORK_ADDRESS_POSTAL_CODE](#WORK-ADDRESS-POSTAL-CODE) | Specifies the postal code (ZIP code) portion of the work address of the contact. |
| [WORK_ADDRESS_POST_OFFICE_BOX](#WORK-ADDRESS-POST-OFFICE-BOX) | Specifies the post office box portion of the work address of the contact. |
| [WORK_ADDRESS_STATE](#WORK-ADDRESS-STATE) | Specifies the state or province portion of the work address of the contact. |
| [WORK_ADDRESS_STREET](#WORK-ADDRESS-STREET) | Specifies the street portion of the work address of the contact. |
| [X4_00_CONTENT_TYPE](#X4-00-CONTENT-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [X4_00_DEFERRED_DELIVERY_CANCEL](#X4-00-DEFERRED-DELIVERY-CANCEL) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [X4_00_ENVELOPE_TYPE](#X4-00-ENVELOPE-TYPE) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [XPOS](#XPOS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
| [X_CALL_ID](#X-CALL-ID) | Contains a unique identifier associated with the phone call. |
| [X_FAX_NUMBER_OF_PAGES](#X-FAX-NUMBER-OF-PAGES) | Specifies how many discrete pages are contained within an attachment representing a facsimile message. |
| [X_REQUIRE_PROTECTED_PLAY_ON_PHONE](#X-REQUIRE-PROTECTED-PLAY-ON-PHONE) | Indicates that the client only renders the message on a phone. |
| [X_SENDER_TELEPHONE_NUMBER](#X-SENDER-TELEPHONE-NUMBER) | Contains the telephone number of the caller associated with a voice mail message. |
| [X_SHARING_BROWSE_URL](#X-SHARING-BROWSE-URL) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [X_SHARING_CAPABILITIES](#X-SHARING-CAPABILITIES) | Contains a string representation of the value of the PidLidSharingCapabilities property (section 2.237). |
| [X_SHARING_CONFIG_URL](#X-SHARING-CONFIG-URL) | Contains the same value as the PidLidSharingConfigurationUrl property (section 2.238). |
| [X_SHARING_EXENDED_CAPS](#X-SHARING-EXENDED-CAPS) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [X_SHARING_FLAVOR](#X-SHARING-FLAVOR) | Contains a hexadecimal string representation of the value of the PidLidSharingFlavor property (section 2.245). |
| [X_SHARING_INSTANCE_GUID](#X-SHARING-INSTANCE-GUID) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [X_SHARING_LOCAL_TYPE](#X-SHARING-LOCAL-TYPE) | Contains the same value as the PidLidSharingLocalType property (section 2.259). |
| [X_SHARING_PROVIDER_GUID](#X-SHARING-PROVIDER-GUID) | Contains the hexadecimal string representation of the value of the PidLidSharingProviderGuid property (section 2.266). |
| [X_SHARING_PROVIDER_NAME](#X-SHARING-PROVIDER-NAME) | Contains the same value as the PidLidSharingProviderName property (section 2.267). |
| [X_SHARING_PROVIDER_URL](#X-SHARING-PROVIDER-URL) | Contains the same value as the PidLidSharingProviderUrl property (section 2.268). |
| [X_SHARING_REMOTE_NAME](#X-SHARING-REMOTE-NAME) | Contains the same value as the PidLidSharingRemoteName property (section 2.277). |
| [X_SHARING_REMOTE_PATH](#X-SHARING-REMOTE-PATH) | Contains a value that is ignored by the server no matter what value is generated by the client. |
| [X_SHARING_REMOTE_STORE_UID](#X-SHARING-REMOTE-STORE-UID) | Contains the same value as the PidLidSharingRemoteStoreUid property (section 2.282). |
| [X_SHARING_REMOTE_TYPE](#X-SHARING-REMOTE-TYPE) | Contains the same value as the PidLidSharingRemoteType property (section 2.281). |
| [X_SHARING_REMOTE_UID](#X-SHARING-REMOTE-UID) | Contains the same value as the PidLidSharingRemoteUid property (section 2.282). |
| [X_VOICE_MESSAGE_ATTACHMENT_ORDER](#X-VOICE-MESSAGE-ATTACHMENT-ORDER) | Contains the list of names for the audio file attachments that are to be played as part of a message, in reverse order. |
| [X_VOICE_MESSAGE_DURATION](#X-VOICE-MESSAGE-DURATION) | Specifies the length of the attached audio message, in seconds. |
| [X_VOICE_MESSAGE_SENDER_NAME](#X-VOICE-MESSAGE-SENDER-NAME) | Contains the name of the caller who left the attached voice message, as provided by the voice network's caller ID system. |
| [YEAR_INTERVAL](#YEAR-INTERVAL) | Indicates the yearly interval of the appointment or meeting. |
| [YOMI_COMPANY_NAME](#YOMI-COMPANY-NAME) | Specifies the phonetic pronunciation of the company name of the contact. |
| [YOMI_FIRST_NAME](#YOMI-FIRST-NAME) | Specifies the phonetic pronunciation of the given name of the contact. |
| [YOMI_LAST_NAME](#YOMI-LAST-NAME) | Specifies the phonetic pronunciation of the surname of the contact. |
| [YPOS](#YPOS) | Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. |
## Methods

| Method | Description |
| --- | --- |
| [add(PropertyDescriptor item)](#add-com.aspose.email.PropertyDescriptor-) | List is read-only. |
| [clear()](#clear--) | List is read-only. |
| [contains(PropertyDescriptor item)](#contains-com.aspose.email.PropertyDescriptor-) | Determines whether the System.Collections.Generic.ICollection contains a specific value. |
| [copyTo(PropertyDescriptor[] array, int arrayIndex)](#copyTo-com.aspose.email.PropertyDescriptor---int-) | List is read-only. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [find(System.Guid[] propertySets)](#find-com.aspose.ms.System.Guid...-) | Finds properties in list according to its PropertySet |
| [find(int id)](#find-int-) | Finds [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) properties in list |
| [find(int id, int type)](#find-int-int-) | Finds [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) property in list |
| [find(String name)](#find-java.lang.String-) | Finds property in list with specified name |
| [find(String name, int type, UUID propertySet)](#find-java.lang.String-int-java.util.UUID-) | Finds [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) property in list according to required parameters |
| [find(String name, UUID propertySet)](#find-java.lang.String-java.util.UUID-) | Finds [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) property in list according to required parameters This is simplified search operation without data type comparison. |
| [find(long tag)](#find-long-) | Finds [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) property in list |
| [find(long lid, int type, UUID propertySet)](#find-long-int-java.util.UUID-) | Finds [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) property in list according to required parameters |
| [find(long lid, UUID propertySet)](#find-long-java.util.UUID-) | Finds [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) property in list according to required parameters This is simplified search operation without data type comparison. |
| [findOrGetCurrent(PropertyDescriptor item)](#findOrGetCurrent-com.aspose.email.PropertyDescriptor-) | Finds property in list with canonical name |
| [getClass()](#getClass--) |  |
| [getDefaultValues()](#getDefaultValues--) | Gets PropertyList with all properties. |
| [getValues()](#getValues--) | Gets PropertyList with all properties. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [hashCode()](#hashCode--) |  |
| [indexOf(PropertyDescriptor item)](#indexOf-com.aspose.email.PropertyDescriptor-) | Determines the index of a specific item in the System.Collections.Generic.IList. |
| [indexOf(String name)](#indexOf-java.lang.String-) | Determines the index of a specific item in the System.Collections.Generic.IList. |
| [insert(int index, PropertyDescriptor item)](#insert-int-com.aspose.email.PropertyDescriptor-) | List is read-only. |
| [isReadOnly()](#isReadOnly--) | true if the System.Collections.Generic.ICollection is read-only; otherwise, false. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(PropertyDescriptor item)](#remove-com.aspose.email.PropertyDescriptor-) | List is read-only. |
| [removeAt(int index)](#removeAt-int-) | List is read-only. |
| [set_Item(int index, PropertyDescriptor value)](#set-Item-int-com.aspose.email.PropertyDescriptor-) | Gets the element at the specified index. |
| [size()](#size--) | Gets the number of elements contained in the System.Collections.Generic.ICollection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ABSTRACT {#ABSTRACT}
```
public static final PidTagPropertyDescriptor ABSTRACT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ABSTRACT

### AB_DEFAULT_DIR {#AB-DEFAULT-DIR}
```
public static final PidTagPropertyDescriptor AB_DEFAULT_DIR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_AB\_DEFAULT\_DIR

### AB_DEFAULT_PAB {#AB-DEFAULT-PAB}
```
public static final PidTagPropertyDescriptor AB_DEFAULT_PAB
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_AB\_DEFAULT\_PAB

### AB_PROVIDERS {#AB-PROVIDERS}
```
public static final PidTagPropertyDescriptor AB_PROVIDERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_AB\_PROVIDERS

### AB_PROVIDER_ID {#AB-PROVIDER-ID}
```
public static final PidTagPropertyDescriptor AB_PROVIDER_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_AB\_PROVIDER\_ID

### AB_SEARCH_PATH {#AB-SEARCH-PATH}
```
public static final PidTagPropertyDescriptor AB_SEARCH_PATH
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_AB\_SEARCH\_PATH

### AB_SEARCH_PATH_UPDATE {#AB-SEARCH-PATH-UPDATE}
```
public static final PidTagPropertyDescriptor AB_SEARCH_PATH_UPDATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_AB\_SEARCH\_PATH\_UPDATE

### ACCEPT_LANGUAGE {#ACCEPT-LANGUAGE}
```
public static final PidNamePropertyDescriptor ACCEPT_LANGUAGE
```


Contains the value of the MIME Accept-Language header. Area: Email Canonical name: PidNameAcceptLanguage Alternate names: AcceptLanguage

### ACCESS {#ACCESS}
```
public static final PidTagPropertyDescriptor ACCESS
```


Indicates the operations available to the client for the object. Area: Access Control Properties Canonical name: PidTagAccess Alternate names: PR\_ACCESS, ptagAccess

### ACCESS_CONTROL_LIST_DATA {#ACCESS-CONTROL-LIST-DATA}
```
public static final PidTagPropertyDescriptor ACCESS_CONTROL_LIST_DATA
```


Contains a permissions list for a folder. Area: Access Control Properties Canonical name: PidTagAccessControlListData Alternate names: PR\_ACL\_DATA, ptagACLData

### ACCESS_LEVEL {#ACCESS-LEVEL}
```
public static final PidTagPropertyDescriptor ACCESS_LEVEL
```


Indicates the client's access level to the object. Area: Access Control Properties Canonical name: PidTagAccessLevel Alternate names: PR\_ACCESS\_LEVEL, ptagAccessLevel

### ACCOUNT {#ACCOUNT}
```
public static final PidTagPropertyDescriptor ACCOUNT
```


Contains the alias of an Address Book object, which is an alternative name by which the object can be identified. Area: Address Book Canonical name: PidTagAccount Alternate names: PR\_ACCOUNT, PR\_ACCOUNT\_A, PR\_ACCOUNT\_W, urn:schemas:contacts:account

### ACTIVE_USER_ENTRYID {#ACTIVE-USER-ENTRYID}
```
public static final PidTagPropertyDescriptor ACTIVE_USER_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ACTIVE\_USER\_ENTRYID

### ADDITIONAL_REN_ENTRY_IDS {#ADDITIONAL-REN-ENTRY-IDS}
```
public static final PidTagPropertyDescriptor ADDITIONAL_REN_ENTRY_IDS
```


Contains the indexed entry IDs for several special folders related to conflicts, sync issues, local failures, server failures, junk email and spam. Area: Outlook Application Canonical name: PidTagAdditionalRenEntryIds Alternate names: PR\_ADDITIONAL\_REN\_ENTRYIDS, ptagAdditionalRenEntryIds

### ADDITIONAL_REN_ENTRY_IDS_EX {#ADDITIONAL-REN-ENTRY-IDS-EX}
```
public static final PidTagPropertyDescriptor ADDITIONAL_REN_ENTRY_IDS_EX
```


Contains an array of blocks that specify the EntryIDs of several special folders. Area: Outlook Application Canonical name: PidTagAdditionalRenEntryIdsEx Alternate names: PR\_ADDITIONAL\_REN\_ENTRYIDS\_EX, ptagAdditionalRenEntryIdsEx

### ADDRBOOK_FOR_LOCAL_SITE_ENTRYID {#ADDRBOOK-FOR-LOCAL-SITE-ENTRYID}
```
public static final PidTagPropertyDescriptor ADDRBOOK_FOR_LOCAL_SITE_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ADDRBOOK\_FOR\_LOCAL\_SITE\_ENTRYID

### ADDRESS_BOOK_AUTHORIZED_SENDERS {#ADDRESS-BOOK-AUTHORIZED-SENDERS}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_AUTHORIZED_SENDERS
```


Indicates whether delivery restrictions exist for a recipient. Area: Address Book Canonical name: PidTagAddressBookAuthorizedSenders Alternate names: PR\_EMS\_AB\_AUTH\_ORIG

### ADDRESS_BOOK_CONTAINER_ID {#ADDRESS-BOOK-CONTAINER-ID}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_CONTAINER_ID
```


Contains the ID of a container on an NSPI server. Area: Address Book Canonical name: PidTagAddressBookContainerId Alternate names: PR\_EMS\_AB\_CONTAINERID

### ADDRESS_BOOK_DELIVERY_CONTENT_LENGTH {#ADDRESS-BOOK-DELIVERY-CONTENT-LENGTH}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_DELIVERY_CONTENT_LENGTH
```


Specifies the maximum size, in bytes, of a message that a recipient can receive. Area: Address Book Canonical name: PidTagAddressBookDeliveryContentLength Alternate names: PR\_EMS\_AB\_DELIV\_CONT\_LENGTH

### ADDRESS_BOOK_DISPLAY_NAME {#ADDRESS-BOOK-DISPLAY-NAME}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_DISPLAY_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ADDRESS\_BOOK\_DISPLAY\_NAME

### ADDRESS_BOOK_DISPLAY_NAME_PRINTABLE {#ADDRESS-BOOK-DISPLAY-NAME-PRINTABLE}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_DISPLAY_NAME_PRINTABLE
```


Contains the printable string version of the display name. Area: Address Book Canonical name: PidTagAddressBookDisplayNamePrintable Alternate names: PR\_EMS\_AB\_DISPLAY\_NAME\_PRINTABLE, ptagSimpleDisplayName

### ADDRESS_BOOK_DISPLAY_TYPE_EXTENDED {#ADDRESS-BOOK-DISPLAY-TYPE-EXTENDED}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_DISPLAY_TYPE_EXTENDED
```


Contains a value that indicates how to display an Address Book object in a table or as a recipient on a message. Area: Address Book Canonical name: PidTagAddressBookDisplayTypeExtended Alternate names: PR\_EMS\_AB\_DISPLAY\_TYPE\_EX

### ADDRESS_BOOK_DISTRIBUTION_LIST_EXTERNAL_MEMBER_COUNT {#ADDRESS-BOOK-DISTRIBUTION-LIST-EXTERNAL-MEMBER-COUNT}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_DISTRIBUTION_LIST_EXTERNAL_MEMBER_COUNT
```


Contains the number of external recipients in the distribution list. Area: Address Book Canonical name: PidTagAddressBookDistributionListExternalMemberCount Alternate names: PR\_EMS\_AB\_DL\_EXTERNAL\_MEMBER\_COUNT

### ADDRESS_BOOK_DISTRIBUTION_LIST_MEMBER_COUNT {#ADDRESS-BOOK-DISTRIBUTION-LIST-MEMBER-COUNT}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_DISTRIBUTION_LIST_MEMBER_COUNT
```


Contains the total number of recipients in the distribution list. Area: Address Book Canonical name: PidTagAddressBookDistributionListMemberCount Alternate names: PR\_EMS\_AB\_DL\_TOTAL\_MEMBER\_COUNT

### ADDRESS_BOOK_DISTRIBUTION_LIST_MEMBER_SUBMIT_ACCEPTED {#ADDRESS-BOOK-DISTRIBUTION-LIST-MEMBER-SUBMIT-ACCEPTED}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_DISTRIBUTION_LIST_MEMBER_SUBMIT_ACCEPTED
```


Indicates that delivery restrictions exist for a recipient. Area: Address Book Canonical name: PidTagAddressBookDistributionListMemberSubmitAccepted Alternate names: PR\_EMS\_AB\_DL\_MEM\_SUBMIT\_PERMS\_BL\_O

### ADDRESS_BOOK_DISTRIBUTION_LIST_MEMBER_SUBMIT_REJECTED {#ADDRESS-BOOK-DISTRIBUTION-LIST-MEMBER-SUBMIT-REJECTED}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_DISTRIBUTION_LIST_MEMBER_SUBMIT_REJECTED
```


Indicates that delivery restrictions exist for a recipient. Area: Address Book Canonical name: PidTagAddressBookDistributionListMemberSubmitRejected Alternate names: PR\_EMS\_AB\_DL\_MEM\_SUBMIT\_PERMS

### ADDRESS_BOOK_DISTRIBUTION_LIST_REJECT_MESSAGES_FROM_DL_MEMBERS {#ADDRESS-BOOK-DISTRIBUTION-LIST-REJECT-MESSAGES-FROM-DL-MEMBERS}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_DISTRIBUTION_LIST_REJECT_MESSAGES_FROM_DL_MEMBERS
```


Indicates that delivery restrictions exist for a recipient. Area: Address book Canonical name: PidTagAddressBookDistributionListRejectMessagesFromDLMembers Alternate names: PR\_EMS\_AB\_DL\_MEM\_REJECT\_PERMS

### ADDRESS_BOOK_ENTRY_ID {#ADDRESS-BOOK-ENTRY-ID}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_ENTRY_ID
```


Contains the name-service EntryID of a directory object that refers to a public folder. Area: Address Book Canonical name: PidTagAddressBookEntryId Alternate names: PR\_ADDRESS\_BOOK\_ENTRYID, ptagAddressBookEntryId

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_1 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-1}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_1
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute1 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_1, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_1\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_1\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_10 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-10}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_10
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute10 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_10, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_10\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_10\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_11 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-11}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_11
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute11 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_11, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_11\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_11\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_12 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-12}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_12
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute12 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_12, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_12\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_12\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_13 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-13}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_13
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute13 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_13, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_13\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_13\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_14 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-14}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_14
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute14 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_14, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_14\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_14\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_15 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-15}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_15
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute15 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_15, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_15\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_15\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_2 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-2}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_2
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute2 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_2, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_2\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_2\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_3 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-3}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_3
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute3 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_3, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_3\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_3\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_4 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-4}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_4
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute4 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_4, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_4\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_4\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_5 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-5}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_5
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute5 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_5, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_5\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_5\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_6 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-6}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_6
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute6 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_6, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_6\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_6\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_7 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-7}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_7
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute7 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_7, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_7\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_7\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_8 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-8}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_8
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute8 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_8, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_8\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_8\_W

### ADDRESS_BOOK_EXTENSION_ATTRIBUTE_9 {#ADDRESS-BOOK-EXTENSION-ATTRIBUTE-9}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_EXTENSION_ATTRIBUTE_9
```


Contains custom values defined and populated by the organization that modified the display templates. Area: Address Book Canonical name: PidTagAddressBookExtensionAttribute9 Alternate names: PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_9, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_9\_A, PR\_EMS\_AB\_EXTENSION\_ATTRIBUTE\_9\_W

### ADDRESS_BOOK_FOLDER_PATHNAME {#ADDRESS-BOOK-FOLDER-PATHNAME}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_FOLDER_PATHNAME
```


This property is deprecated and is to be ignored. Area: Address Book Canonical name: PidTagAddressBookFolderPathname Alternate names: PR\_EMS\_AB\_FOLDER\_PATHNAME, PR\_EMS\_AB\_FOLDER\_PATHNAME\_A, PR\_EMS\_AB\_FOLDER\_PATHNAME\_W

### ADDRESS_BOOK_HIERARCHICAL_CHILD_DEPARTMENTS {#ADDRESS-BOOK-HIERARCHICAL-CHILD-DEPARTMENTS}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_HIERARCHICAL_CHILD_DEPARTMENTS
```


Contains the child departments in a hierarchy of departments. Area: Address Book Canonical name: PidTagAddressBookHierarchicalChildDepartments Alternate names: PR\_EMS\_AB\_HAB\_CHILD\_DEPARTMENTS

### ADDRESS_BOOK_HIERARCHICAL_DEPARTMENT_MEMBERS {#ADDRESS-BOOK-HIERARCHICAL-DEPARTMENT-MEMBERS}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_HIERARCHICAL_DEPARTMENT_MEMBERS
```


Contains all of the mail users that belong to this department. Area: Address Book Canonical name: PidTagAddressBookHierarchicalDepartmentMembers Alternate names: PR\_EMS\_AB\_HAB\_DEPARTMENT\_MEMBERS

### ADDRESS_BOOK_HIERARCHICAL_IS_HIERARCHICAL_GROUP {#ADDRESS-BOOK-HIERARCHICAL-IS-HIERARCHICAL-GROUP}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_HIERARCHICAL_IS_HIERARCHICAL_GROUP
```


Indicates whether the distribution list represents a departmental group. Area: Address Book Canonical name: PidTagAddressBookHierarchicalIsHierarchicalGroup Alternate names: PR\_EMS\_AB\_HAB\_IS\_HIERARCHICAL\_GROUP, PR\_EMS\_AB\_IS\_ORGANIZATIONAL

### ADDRESS_BOOK_HIERARCHICAL_PARENT_DEPARTMENT {#ADDRESS-BOOK-HIERARCHICAL-PARENT-DEPARTMENT}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_HIERARCHICAL_PARENT_DEPARTMENT
```


Contains all of the departments to which this department is a child. Area: Address Book Canonical name: PidTagAddressBookHierarchicalParentDepartment Alternate names: PR\_EMS\_AB\_HAB\_PARENT\_DEPARTMENT

### ADDRESS_BOOK_HIERARCHICAL_ROOT_DEPARTMENT {#ADDRESS-BOOK-HIERARCHICAL-ROOT-DEPARTMENT}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_HIERARCHICAL_ROOT_DEPARTMENT
```


Contains the distinguished name (DN) of either the root Department object or the root departmental group in the department hierarchy for the organization. Area: Address Book Canonical name: PidTagAddressBookHierarchicalRootDepartment Alternate names: PR\_EMS\_AB\_HAB\_ROOT\_DEPARTMENT

### ADDRESS_BOOK_HIERARCHICAL_SHOW_IN_DEPARTMENTS {#ADDRESS-BOOK-HIERARCHICAL-SHOW-IN-DEPARTMENTS}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_HIERARCHICAL_SHOW_IN_DEPARTMENTS
```


Lists all Department objects of which the mail user is a member. Area: Address Book Canonical name: PidTagAddressBookHierarchicalShowInDepartments Alternate names: PR\_EMS\_AB\_HAB\_SHOW\_IN\_DEPARTMENTS

### ADDRESS_BOOK_HOME_MESSAGE_DATABASE {#ADDRESS-BOOK-HOME-MESSAGE-DATABASE}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_HOME_MESSAGE_DATABASE
```


Contains the DN expressed in the X500 DN format. This property is returned from a PtypString8. Area: Address Book Canonical name: PidTagAddressBookHomeMessageDatabase Alternate names: PR\_EMS\_AB\_HOME\_MDB, PR\_EMS\_AB\_HOME\_MDB\_A, PR\_EMS\_AB\_HOME\_MDB\_W

### ADDRESS_BOOK_IS_MASTER {#ADDRESS-BOOK-IS-MASTER}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_IS_MASTER
```


Contains a Boolean value of TRUE if it is possible to create Address Book objects in that container, and FALSE otherwise. Area: Address Book Canonical name: PidTagAddressBookIsMaster Alternate names: PR\_EMS\_AB\_IS\_MASTER

### ADDRESS_BOOK_IS_MEMBER_OF_DISTRIBUTION_LIST {#ADDRESS-BOOK-IS-MEMBER-OF-DISTRIBUTION-LIST}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_IS_MEMBER_OF_DISTRIBUTION_LIST
```


Lists all of the distribution lists for which the object is a member. This property is returned from an NSPI server as a PtypEmbeddedTable. Otherwise, the data type is PtypString8. Area: Address Book Canonical name: PidTagAddressBookIsMemberOfDistributionList Alternate names: PR\_EMS\_AB\_IS\_MEMBER\_OF\_DL, PR\_EMS\_AB\_IS\_MEMBER\_OF\_DL\_A, PR\_EMS\_AB\_IS\_MEMBER\_OF\_DL\_W

### ADDRESS_BOOK_MANAGER {#ADDRESS-BOOK-MANAGER}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_MANAGER
```


Contains one row that references the mail user's manager. Area: Address Book Canonical name: PidTagAddressBookManager Alternate names: PR\_EMS\_AB\_MANAGER, PR\_EMS\_AB\_MANAGER\_A, PR\_EMS\_AB\_MANAGER\_W

### ADDRESS_BOOK_MANAGER_DISTINGUISHED_NAME {#ADDRESS-BOOK-MANAGER-DISTINGUISHED-NAME}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_MANAGER_DISTINGUISHED_NAME
```


Contains the DN of the mail user's manager. Area: Address Book Canonical name: PidTagAddressBookManagerDistinguishedName Alternate names: PR\_EMS\_AB\_MANAGER\_T

### ADDRESS_BOOK_MANAGE_DISTRIBUTION_LIST {#ADDRESS-BOOK-MANAGE-DISTRIBUTION-LIST}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_MANAGE_DISTRIBUTION_LIST
```


Contains information for use in display templates for distribution lists. Area: Address Book Canonical name: PidTagAddressBookManageDistributionList Alternate names: PR\_EMS\_AB\_MANAGE\_DL

### ADDRESS_BOOK_MEMBER {#ADDRESS-BOOK-MEMBER}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_MEMBER
```


Contains the members of the distribution list. Area: Address Book Canonical name: PidTagAddressBookMember Alternate names: PR\_EMS\_AB\_MEMBER, PR\_EMS\_AB\_MEMBER\_A, PR\_EMS\_AB\_MEMBER\_W

### ADDRESS_BOOK_MESSAGE_ID {#ADDRESS-BOOK-MESSAGE-ID}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_MESSAGE_ID
```


Contains the Short-term Message ID (MID) ([MS-OXCDATA] section 2.2.1.2) of the first message in the local site's offline address book public folder. Area: ProviderDefinedNonTransmittable Canonical name: PidTagAddressBookMessageId Alternate names: ptagAddrbookMID

### ADDRESS_BOOK_MODERATION_ENABLED {#ADDRESS-BOOK-MODERATION-ENABLED}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_MODERATION_ENABLED
```


Indicates whether moderation is enabled for the mail user or distribution list. Area: Address Book Canonical name: PidTagAddressBookModerationEnabled Alternate names: PR\_EMS\_AB\_ENABLE\_MODERATION

### ADDRESS_BOOK_NETWORK_ADDRESS {#ADDRESS-BOOK-NETWORK-ADDRESS}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_NETWORK_ADDRESS
```


Contains a list of names by which a server is known to the various transports in use by the network. Area: Address Book Canonical name: PidTagAddressBookNetworkAddress Alternate names: PR\_EMS\_AB\_NETWORK\_ADDRESS, PR\_EMS\_AB\_NETWORK\_ADDRESS\_A, PR\_EMS\_AB\_NETWORK\_ADDRESS\_W

### ADDRESS_BOOK_OBJECT_DISTINGUISHED_NAME {#ADDRESS-BOOK-OBJECT-DISTINGUISHED-NAME}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_OBJECT_DISTINGUISHED_NAME
```


Contains the DN of the Address Book object. Area: Address Book Canonical name: PidTagAddressBookObjectDistinguishedName Alternate names: PR\_EMS\_AB\_OBJ\_DIST\_NAME, PR\_EMS\_AB\_OBJ\_DIST\_NAME\_A, PR\_EMS\_AB\_OBJ\_DIST\_NAME\_W

### ADDRESS_BOOK_OBJECT_GUID {#ADDRESS-BOOK-OBJECT-GUID}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_OBJECT_GUID
```


Contains a GUID that identifies an Address Book object. Area: Address Book Canonical name: PidTagAddressBookObjectGuid Alternate names: PR\_EMS\_AB\_OBJECT\_GUID

### ADDRESS_BOOK_ORGANIZATIONAL_UNIT_ROOT_DISTINGUISHED_NAME {#ADDRESS-BOOK-ORGANIZATIONAL-UNIT-ROOT-DISTINGUISHED-NAME}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_ORGANIZATIONAL_UNIT_ROOT_DISTINGUISHED_NAME
```


Contains the DN of the Organization object of the mail user's organization. Area: Address Book Canonical name: PidTagAddressBookOrganizationalUnitRootDistinguishedName Alternate names: PR\_EMS\_AB\_ORG\_UNIT\_ROOT\_DN, msExchOURoot

### ADDRESS_BOOK_OWNER {#ADDRESS-BOOK-OWNER}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_OWNER
```


Contains one row that references the distribution list's owner. Area: Address Book Canonical name: PidTagAddressBookOwner Alternate names: PR\_EMS\_AB\_OWNER\_O

### ADDRESS_BOOK_OWNER_BACK_LINK {#ADDRESS-BOOK-OWNER-BACK-LINK}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_OWNER_BACK_LINK
```


Contains a list of the distribution lists owned by a mail user. Area: Address Book Canonical name: PidTagAddressBookOwnerBackLink Alternate names: PR\_EMS\_AB\_OWNER\_BL\_O

### ADDRESS_BOOK_PARENT_ENTRY_ID {#ADDRESS-BOOK-PARENT-ENTRY-ID}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_PARENT_ENTRY_ID
```


Contains the EntryID of the parent container in a hierarchy of address book containers. Area: Address Book Canonical name: PidTagAddressBookParentEntryId Alternate names: PR\_EMS\_AB\_PARENT\_ENTRYID

### ADDRESS_BOOK_PHONETIC_COMPANY_NAME {#ADDRESS-BOOK-PHONETIC-COMPANY-NAME}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_PHONETIC_COMPANY_NAME
```


Contains the phonetic representation of the PidTagCompanyName property (section 2.630). Area: Address Book Canonical name: PidTagAddressBookPhoneticCompanyName Alternate names: PR\_EMS\_AB\_PHONETIC\_COMPANY\_NAME, PR\_EMS\_AB\_PHONETIC\_COMPANY\_NAME\_A, PR\_EMS\_AB\_PHONETIC\_COMPANY\_NAME\_W

### ADDRESS_BOOK_PHONETIC_DEPARTMENT_NAME {#ADDRESS-BOOK-PHONETIC-DEPARTMENT-NAME}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_PHONETIC_DEPARTMENT_NAME
```


Contains the phonetic representation of the PidTagDepartmentName property (section 2.663). Area: Address Book Canonical name: PidTagAddressBookPhoneticDepartmentName Alternate names: PR\_EMS\_AB\_PHONETIC\_DEPARTMENT\_NAME, PR\_EMS\_AB\_PHONETIC\_DEPARTMENT\_NAME\_A, PR\_EMS\_AB\_PHONETIC\_DEPARTMENT\_NAME\_W

### ADDRESS_BOOK_PHONETIC_DISPLAY_NAME {#ADDRESS-BOOK-PHONETIC-DISPLAY-NAME}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_PHONETIC_DISPLAY_NAME
```


Contains the phonetic representation of the PidTagDisplayName property (section 2.667). Area: Address Book Canonical name: PidTagAddressBookPhoneticDisplayName Alternate names: PR\_EMS\_AB\_PHONETIC\_DISPLAY\_NAME, PR\_EMS\_AB\_PHONETIC\_DISPLAY\_NAME\_A, PR\_EMS\_AB\_PHONETIC\_DISPLAY\_NAME\_W

### ADDRESS_BOOK_PHONETIC_GIVEN_NAME {#ADDRESS-BOOK-PHONETIC-GIVEN-NAME}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_PHONETIC_GIVEN_NAME
```


Contains the phonetic representation of the PidTagGivenName property (section 2.705). Area: Address Book Canonical name: PidTagAddressBookPhoneticGivenName Alternate names: PR\_EMS\_AB\_PHONETIC\_GIVEN\_NAME, PR\_EMS\_AB\_PHONETIC\_GIVEN\_NAME\_A, PR\_EMS\_AB\_PHONETIC\_GIVEN\_NAME\_W

### ADDRESS_BOOK_PHONETIC_SURNAME {#ADDRESS-BOOK-PHONETIC-SURNAME}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_PHONETIC_SURNAME
```


Contains the phonetic representation of the PidTagSurname property (section 2.1026). Area: Address Book Canonical name: PidTagAddressBookPhoneticSurname Alternate names: PR\_EMS\_AB\_PHONETIC\_SURNAME, PR\_EMS\_AB\_PHONETIC\_SURNAME\_A, PR\_EMS\_AB\_PHONETIC\_SURNAME\_W

### ADDRESS_BOOK_PROVIDER_ARRAY_TYPE {#ADDRESS-BOOK-PROVIDER-ARRAY-TYPE}
```
public static final PidLidPropertyDescriptor ADDRESS_BOOK_PROVIDER_ARRAY_TYPE
```


Specifies the state of the electronic addresses of the contact and represents a set of bit flags. Area: Contact Properties Canonical name: PidLidAddressBookProviderArrayType Alternate names: dispidABPArrayType

### ADDRESS_BOOK_PROVIDER_EMAIL_LIST {#ADDRESS-BOOK-PROVIDER-EMAIL-LIST}
```
public static final PidLidPropertyDescriptor ADDRESS_BOOK_PROVIDER_EMAIL_LIST
```


Specifies which electronic address properties are set on the Contact object. Area: Contact Properties Canonical name: PidLidAddressBookProviderEmailList Alternate names: dispidABPEmailList

### ADDRESS_BOOK_PROXY_ADDRESSES {#ADDRESS-BOOK-PROXY-ADDRESSES}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_PROXY_ADDRESSES
```


Contains alternate email addresses for the Address Book object. Area: Address Book Canonical name: PidTagAddressBookProxyAddresses Alternate names: PR\_EMS\_AB\_PROXY\_ADDRESSES, PR\_EMS\_AB\_PROXY\_ADDRESSES\_A, PR\_EMS\_AB\_PROXY\_ADDRESSES\_W

### ADDRESS_BOOK_PUBLIC_DELEGATES {#ADDRESS-BOOK-PUBLIC-DELEGATES}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_PUBLIC_DELEGATES
```


Contains a list of mail users who are allowed to send email on behalf of the mailbox owner. Area: Address Book Canonical name: PidTagAddressBookPublicDelegates Alternate names: PR\_EMS\_AB\_PUBLIC\_DELEGATES, PR\_EMS\_AB\_PUBLIC\_DELEGATES\_A, PR\_EMS\_AB\_PUBLIC\_DELEGATES\_W

### ADDRESS_BOOK_REPORTS {#ADDRESS-BOOK-REPORTS}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_REPORTS
```


Lists all of the mail user\\ufffds direct reports. Area: Address Book Canonical name: PidTagAddressBookReports Alternate names: PR\_EMS\_AB\_REPORTS, PR\_EMS\_AB\_REPORTS\_A, PR\_EMS\_AB\_REPORTS\_W

### ADDRESS_BOOK_ROOM_CAPACITY {#ADDRESS-BOOK-ROOM-CAPACITY}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_ROOM_CAPACITY
```


Contains the maximum occupancy of the room. Area: Address Book Canonical name: PidTagAddressBookRoomCapacity Alternate names: PR\_EMS\_AB\_ROOM\_CAPACITY

### ADDRESS_BOOK_ROOM_CONTAINERS {#ADDRESS-BOOK-ROOM-CONTAINERS}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_ROOM_CONTAINERS
```


Contains a list of DNs that represent the address book containers that hold Resource objects, such as conference rooms and equipment. Area: Address Book Canonical name: PidTagAddressBookRoomContainers Alternate names: PR\_EMS\_AB\_ROOM\_CONTAINERS, PR\_EMS\_AB\_ROOM\_CONTAINERS\_A, PR\_EMS\_AB\_ROOM\_CONTAINERS\_W

### ADDRESS_BOOK_ROOM_DESCRIPTION {#ADDRESS-BOOK-ROOM-DESCRIPTION}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_ROOM_DESCRIPTION
```


Contains a description of the Resource object. Area: Address Book Canonical name: PidTagAddressBookRoomDescription Alternate names: PR\_EMS\_AB\_ROOM\_DESCRIPTION, PR\_EMS\_AB\_ROOM\_DESCRIPTION\_A, PR\_EMS\_AB\_ROOM\_DESCRIPTION\_W

### ADDRESS_BOOK_SENDER_HINT_TRANSLATIONS {#ADDRESS-BOOK-SENDER-HINT-TRANSLATIONS}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_SENDER_HINT_TRANSLATIONS
```


Contains the locale ID and translations of the default mail tip. Area: Address Book Canonical name: PidTagAddressBookSenderHintTranslations Alternate names: PR\_EMS\_AB\_DL\_SENDER\_HINT\_TRANSLATIONS\_W

### ADDRESS_BOOK_SENIORITY_INDEX {#ADDRESS-BOOK-SENIORITY-INDEX}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_SENIORITY_INDEX
```


Contains a signed integer that specifies the seniority order of Address Book objects that group, with larger values specifying members that are more senior. Area: Address Book Canonical name: PidTagAddressBookSeniorityIndex Alternate names:

### ADDRESS_BOOK_TARGET_ADDRESS {#ADDRESS-BOOK-TARGET-ADDRESS}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_TARGET_ADDRESS
```


Contains the foreign system email address of an Address Book object. Area: Address Book Canonical name: PidTagAddressBookTargetAddress Alternate names: PR\_EMS\_AB\_TARGET\_ADDRESS, PR\_EMS\_AB\_TARGET\_ADDRESS\_A, PR\_EMS\_AB\_TARGET\_ADDRESS\_W

### ADDRESS_BOOK_UNAUTHORIZED_SENDERS {#ADDRESS-BOOK-UNAUTHORIZED-SENDERS}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_UNAUTHORIZED_SENDERS
```


Indicates whether delivery restrictions exist for a recipient. Area: Address Book Canonical name: PidTagAddressBookUnauthorizedSenders Alternate names: PR\_EMS\_AB\_UNAUTH\_ORIG

### ADDRESS_BOOK_X_509_CERTIFICATE {#ADDRESS-BOOK-X-509-CERTIFICATE}
```
public static final PidTagPropertyDescriptor ADDRESS_BOOK_X_509_CERTIFICATE
```


Contains the ASN\_1 DER encoded X.509 certificates for the mail user. Area: Address Book Canonical name: PidTagAddressBookX509Certificate Alternate names: PR\_EMS\_AB\_X509\_CERT

### ADDRESS_COUNTRY_CODE {#ADDRESS-COUNTRY-CODE}
```
public static final PidLidPropertyDescriptor ADDRESS_COUNTRY_CODE
```


Specifies the country code portion of the mailing address of the contact. Area: Contact Properties Canonical name: PidLidAddressCountryCode Alternate names: dispidAddressCountryCode

### ADDRESS_TYPE {#ADDRESS-TYPE}
```
public static final PidTagPropertyDescriptor ADDRESS_TYPE
```


Contains the email address type of a Message object. Area: Address Properties Canonical name: PidTagAddressType Alternate names: PR\_ADDRTYPE, PR\_ADDRTYPE\_A, ptagAddrType, PR\_ADDRTYPE\_W

### AGING_DONT_AGE_ME {#AGING-DONT-AGE-ME}
```
public static final PidLidPropertyDescriptor AGING_DONT_AGE_ME
```


Specifies whether to automatically archive the message. Area: Common Canonical name: PidLidAgingDontAgeMe Alternate names: dispidAgingDontAgeMe

### ALLOW_EXTERNAL_CHECK {#ALLOW-EXTERNAL-CHECK}
```
public static final PidLidPropertyDescriptor ALLOW_EXTERNAL_CHECK
```


This property is set to TRUE. Area: Conferencing Canonical name: PidLidAllowExternalCheck Alternate names: dispidAllowExternCheck

### ALL_ATTENDEES_STRING {#ALL-ATTENDEES-STRING}
```
public static final PidLidPropertyDescriptor ALL_ATTENDEES_STRING
```


Specifies a list of all the attendees except for the organizer, including resources and unsendable attendees. Area: Meetings Canonical name: PidLidAllAttendeesString Alternate names: dispidAllAttendeesString

### ALTERNATE_RECIPIENT {#ALTERNATE-RECIPIENT}
```
public static final PidTagPropertyDescriptor ALTERNATE_RECIPIENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ALTERNATE\_RECIPIENT

### ALTERNATE_RECIPIENT_ALLOWED {#ALTERNATE-RECIPIENT-ALLOWED}
```
public static final PidTagPropertyDescriptor ALTERNATE_RECIPIENT_ALLOWED
```


Specifies whether the sender permits the message to be auto-forwarded. Area: Address Properties Canonical name: PidTagAlternateRecipientAllowed Alternate names: PR\_ALTERNATE\_RECIPIENT\_ALLOWED, ptagAlternateRecipientAllowed

### ANNIVERSARY_EVENT_ENTRY_ID {#ANNIVERSARY-EVENT-ENTRY-ID}
```
public static final PidLidPropertyDescriptor ANNIVERSARY_EVENT_ENTRY_ID
```


Specifies the EntryID of the Appointment object that represents an anniversary of the contact. Area: Contact Properties Canonical name: PidLidAnniversaryEventEntryId Alternate names: dispidAnniversaryEventEID

### ANR {#ANR}
```
public static final PidTagPropertyDescriptor ANR
```


Contains a filter value used in ambiguous name resolution. Area: Address Book Canonical name: PidTagAnr Alternate names: PR\_ANR, PR\_ANR\_A, PR\_ANR\_W

### APPLICATION_NAME {#APPLICATION-NAME}
```
public static final PidNamePropertyDescriptor APPLICATION_NAME
```


Specifies the application used to open the file attached to the Document object. Area: Common Canonical name: PidNameApplicationName Alternate names: urn:schemas-microsoft-com:office:office\#NameOfApplication

### APPOINTMENT_AUXILIARY_FLAGS {#APPOINTMENT-AUXILIARY-FLAGS}
```
public static final PidLidPropertyDescriptor APPOINTMENT_AUXILIARY_FLAGS
```


Specifies a bit field that describes the auxiliary state of the object. Area: Meetings Canonical name: PidLidAppointmentAuxiliaryFlags Alternate names: dispidApptAuxFlags

### APPOINTMENT_COLOR {#APPOINTMENT-COLOR}
```
public static final PidLidPropertyDescriptor APPOINTMENT_COLOR
```


Specifies the color to be used when displaying the Calendar object. Area: Calendar Canonical name: PidLidAppointmentColor Alternate names: dispidApptColor

### APPOINTMENT_COUNTER_PROPOSAL {#APPOINTMENT-COUNTER-PROPOSAL}
```
public static final PidLidPropertyDescriptor APPOINTMENT_COUNTER_PROPOSAL
```


Indicates whether a Meeting Response object is a counter proposal. Area: Meetings Canonical name: PidLidAppointmentCounterProposal Alternate names: dispidApptCounterProposal

### APPOINTMENT_DURATION {#APPOINTMENT-DURATION}
```
public static final PidLidPropertyDescriptor APPOINTMENT_DURATION
```


Specifies the length of the event, in minutes. Area: Calendar Canonical name: PidLidAppointmentDuration Alternate names: dispidApptDuration

### APPOINTMENT_END_DATE {#APPOINTMENT-END-DATE}
```
public static final PidLidPropertyDescriptor APPOINTMENT_END_DATE
```


Indicates the date that the appointment ends. Area: Calendar Canonical name: PidLidAppointmentEndDate Alternate names: dispidApptEndDate

### APPOINTMENT_END_TIME {#APPOINTMENT-END-TIME}
```
public static final PidLidPropertyDescriptor APPOINTMENT_END_TIME
```


Indicates the time that the appointment ends. Area: Calendar Canonical name: PidLidAppointmentEndTime Alternate names: dispidApptEndTime

### APPOINTMENT_END_WHOLE {#APPOINTMENT-END-WHOLE}
```
public static final PidLidPropertyDescriptor APPOINTMENT_END_WHOLE
```


Specifies the end date and time for the event. Area: Calendar Canonical name: PidLidAppointmentEndWhole Alternate names: dispidApptEndWhole

### APPOINTMENT_LAST_SEQUENCE {#APPOINTMENT-LAST-SEQUENCE}
```
public static final PidLidPropertyDescriptor APPOINTMENT_LAST_SEQUENCE
```


Indicates to the organizer the last sequence number that was sent to any attendee. Area: Meetings Canonical name: PidLidAppointmentLastSequence Alternate names: dispidApptLastSequence

### APPOINTMENT_MESSAGE_CLASS {#APPOINTMENT-MESSAGE-CLASS}
```
public static final PidLidPropertyDescriptor APPOINTMENT_MESSAGE_CLASS
```


Indicates the message class of the Meeting object to be generated from the Meeting Request object. Area: Meetings Canonical name: PidLidAppointmentMessageClass Alternate names: dispidApptMessageClass

### APPOINTMENT_NOT_ALLOW_PROPOSE {#APPOINTMENT-NOT-ALLOW-PROPOSE}
```
public static final PidLidPropertyDescriptor APPOINTMENT_NOT_ALLOW_PROPOSE
```


Indicates whether attendees are not allowed to propose a new date and/or time for the meeting. Area: Meetings Canonical name: PidLidAppointmentNotAllowPropose Alternate names: dispidApptNotAllowPropose

### APPOINTMENT_PROPOSAL_NUMBER {#APPOINTMENT-PROPOSAL-NUMBER}
```
public static final PidLidPropertyDescriptor APPOINTMENT_PROPOSAL_NUMBER
```


Specifies the number of attendees who have sent counter proposals that have not been accepted or rejected by the organizer. Area: Meetings Canonical name: PidLidAppointmentProposalNumber Alternate names: dispidApptProposalNum

### APPOINTMENT_PROPOSED_DURATION {#APPOINTMENT-PROPOSED-DURATION}
```
public static final PidLidPropertyDescriptor APPOINTMENT_PROPOSED_DURATION
```


Indicates the proposed value for the PidLidAppointmentDuration property (section 2.11) for a counter proposal. Area: Meetings Canonical name: PidLidAppointmentProposedDuration Alternate names: dispidApptProposedDuration

### APPOINTMENT_PROPOSED_END_WHOLE {#APPOINTMENT-PROPOSED-END-WHOLE}
```
public static final PidLidPropertyDescriptor APPOINTMENT_PROPOSED_END_WHOLE
```


Specifies the proposed value for the PidLidAppointmentEndWhole property (section 2.14) for a counter proposal. Area: Meetings Canonical name: PidLidAppointmentProposedEndWhole Alternate names: dispidApptProposedEndWhole

### APPOINTMENT_PROPOSED_START_WHOLE {#APPOINTMENT-PROPOSED-START-WHOLE}
```
public static final PidLidPropertyDescriptor APPOINTMENT_PROPOSED_START_WHOLE
```


Specifies the proposed value for the PidLidAppointmentStartWhole property (section 2.29) for a counter proposal. Area: Meetings Canonical name: PidLidAppointmentProposedStartWhole Alternate names: dispidApptProposedStartWhole

### APPOINTMENT_RECUR {#APPOINTMENT-RECUR}
```
public static final PidLidPropertyDescriptor APPOINTMENT_RECUR
```


Specifies the dates and times when a recurring series occurs. Area: Calendar Canonical name: PidLidAppointmentRecur Alternate names: dispidApptRecur

### APPOINTMENT_REPLY_NAME {#APPOINTMENT-REPLY-NAME}
```
public static final PidLidPropertyDescriptor APPOINTMENT_REPLY_NAME
```


Specifies the user who last replied to the meeting request or meeting update. Area: Meetings Canonical name: PidLidAppointmentReplyName Alternate names: dispidApptReplyName, http://schemas.microsoft.com/mapi/apptreplyname

### APPOINTMENT_REPLY_TIME {#APPOINTMENT-REPLY-TIME}
```
public static final PidLidPropertyDescriptor APPOINTMENT_REPLY_TIME
```


Specifies the date and time at which the attendee responded to a received meeting request or Meeting Update object. Area: Meetings Canonical name: PidLidAppointmentReplyTime Alternate names: dispidApptReplyTime

### APPOINTMENT_SEQUENCE {#APPOINTMENT-SEQUENCE}
```
public static final PidLidPropertyDescriptor APPOINTMENT_SEQUENCE
```


Specifies the sequence number of a Meeting object. Area: Meetings Canonical name: PidLidAppointmentSequence Alternate names: dispidApptSequence

### APPOINTMENT_SEQUENCE_TIME {#APPOINTMENT-SEQUENCE-TIME}
```
public static final PidLidPropertyDescriptor APPOINTMENT_SEQUENCE_TIME
```


Indicates the date and time at which the PidLidAppointmentSequence property (section 2.25) was last modified. Area: Meetings Canonical name: PidLidAppointmentSequenceTime Alternate names: dispidApptSeqTime

### APPOINTMENT_START_DATE {#APPOINTMENT-START-DATE}
```
public static final PidLidPropertyDescriptor APPOINTMENT_START_DATE
```


Identifies the date that the appointment starts. Area: Calendar Canonical name: PidLidAppointmentStartDate Alternate names: dispidApptStartDate

### APPOINTMENT_START_TIME {#APPOINTMENT-START-TIME}
```
public static final PidLidPropertyDescriptor APPOINTMENT_START_TIME
```


Identifies the time that the appointment starts. Area: Calendar Canonical name: PidLidAppointmentStartTime Alternate names: dispidApptStartTime

### APPOINTMENT_START_WHOLE {#APPOINTMENT-START-WHOLE}
```
public static final PidLidPropertyDescriptor APPOINTMENT_START_WHOLE
```


Specifies the start date and time of the appointment. Area: Calendar Canonical name: PidLidAppointmentStartWhole Alternate names: dispidApptStartWhole

### APPOINTMENT_STATE_FLAGS {#APPOINTMENT-STATE-FLAGS}
```
public static final PidLidPropertyDescriptor APPOINTMENT_STATE_FLAGS
```


Specifies a bit field that describes the state of the object. Area: Meetings Canonical name: PidLidAppointmentStateFlags Alternate names: dispidApptStateFlags

### APPOINTMENT_SUB_TYPE {#APPOINTMENT-SUB-TYPE}
```
public static final PidLidPropertyDescriptor APPOINTMENT_SUB_TYPE
```


Specifies whether the event is an all-day event. Area: Calendar Canonical name: PidLidAppointmentSubType Alternate names: dispidApptSubType

### APPOINTMENT_TIME_ZONE_DEFINITION_END_DISPLAY {#APPOINTMENT-TIME-ZONE-DEFINITION-END-DISPLAY}
```
public static final PidLidPropertyDescriptor APPOINTMENT_TIME_ZONE_DEFINITION_END_DISPLAY
```


Specifies time zone information that indicates the time zone of the PidLidAppointmentEndWhole property (section 2.14). Area: Calendar Canonical name: PidLidAppointmentTimeZoneDefinitionEndDisplay Alternate names: dispidApptTZDefEndDisplay

### APPOINTMENT_TIME_ZONE_DEFINITION_RECUR {#APPOINTMENT-TIME-ZONE-DEFINITION-RECUR}
```
public static final PidLidPropertyDescriptor APPOINTMENT_TIME_ZONE_DEFINITION_RECUR
```


Specifies time zone information that describes how to convert the meeting date and time on a recurring series to and from UTC. Area: Calendar Canonical name: PidLidAppointmentTimeZoneDefinitionRecur Alternate names: dispidApptTZDefRecur

### APPOINTMENT_TIME_ZONE_DEFINITION_START_DISPLAY {#APPOINTMENT-TIME-ZONE-DEFINITION-START-DISPLAY}
```
public static final PidLidPropertyDescriptor APPOINTMENT_TIME_ZONE_DEFINITION_START_DISPLAY
```


Specifies time zone information that indicates the time zone of the PidLidAppointmentStartWhole property (section 2.29). Area: Calendar Canonical name: PidLidAppointmentTimeZoneDefinitionStartDisplay Alternate names: dispidApptTZDefStartDisplay

### APPOINTMENT_UNSENDABLE_RECIPIENTS {#APPOINTMENT-UNSENDABLE-RECIPIENTS}
```
public static final PidLidPropertyDescriptor APPOINTMENT_UNSENDABLE_RECIPIENTS
```


Contains a list of unsendable attendees. Area: Meetings Canonical name: PidLidAppointmentUnsendableRecipients Alternate names: dispidApptUnsendableRecips

### APPOINTMENT_UPDATE_TIME {#APPOINTMENT-UPDATE-TIME}
```
public static final PidLidPropertyDescriptor APPOINTMENT_UPDATE_TIME
```


Indicates the time at which the appointment was last updated. Area: Meetings Canonical name: PidLidAppointmentUpdateTime Alternate names: dispidApptUpdateTime

### ARCHIVE_DATE {#ARCHIVE-DATE}
```
public static final PidTagPropertyDescriptor ARCHIVE_DATE
```


Specifies the date, in UTC, after which a Message object is archived by the server. Area: Archive Canonical name: PidTagArchiveDate Alternate names: PR\_ARCHIVE\_DATE, ptagArchiveDate

### ARCHIVE_PERIOD {#ARCHIVE-PERIOD}
```
public static final PidTagPropertyDescriptor ARCHIVE_PERIOD
```


Specifies the number of days that a Message object can remain unarchived. Area: Archive Canonical name: PidTagArchivePeriod Alternate names: PR\_ARCHIVE\_PERIOD, ptagArchivePeriod

### ARCHIVE_TAG {#ARCHIVE-TAG}
```
public static final PidTagPropertyDescriptor ARCHIVE_TAG
```


Specifies the GUID of an archive tag. Area: Archive Canonical name: PidTagArchiveTag Alternate names: PR\_ARCHIVE\_TAG, ptagArchiveTag

### ARRIVAL_TIME {#ARRIVAL-TIME}
```
public static final PidTagPropertyDescriptor ARRIVAL_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ARRIVAL\_TIME

### ASSISTANT {#ASSISTANT}
```
public static final PidTagPropertyDescriptor ASSISTANT
```


Contains the name of the mail user's administrative assistant. Area: Address Properties Canonical name: PidTagAssistant Alternate names: PR\_ASSISTANT, PR\_ASSISTANT\_A, PR\_ASSISTANT\_W,

### ASSISTANT_TELEPHONE_NUMBER {#ASSISTANT-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor ASSISTANT_TELEPHONE_NUMBER
```


Contains the telephone number of the mail user's administrative assistant. Area: Address Properties Canonical name: PidTagAssistantTelephoneNumber Alternate names: PR\_ASSISTANT\_TELEPHONE\_NUMBER, PR\_ASSISTANT\_TELEPHONE\_NUMBER\_A,

### ASSOCIATED {#ASSOCIATED}
```
public static final PidTagPropertyDescriptor ASSOCIATED
```


Specifies whether the message being synchronized is an FAI message. Area: Sync Canonical name: PidTagAssociated Alternate names: ptagAssociated

### ASSOC_CONTENT_COUNT {#ASSOC-CONTENT-COUNT}
```
public static final PidTagPropertyDescriptor ASSOC_CONTENT_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ASSOC\_CONTENT\_COUNT

### ASSOC_MESSAGE_SIZE {#ASSOC-MESSAGE-SIZE}
```
public static final PidTagPropertyDescriptor ASSOC_MESSAGE_SIZE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ASSOC\_MESSAGE\_SIZE

### ASSOC_MESSAGE_SIZE_EXTENDED {#ASSOC-MESSAGE-SIZE-EXTENDED}
```
public static final PidTagPropertyDescriptor ASSOC_MESSAGE_SIZE_EXTENDED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ASSOC\_MESSAGE\_SIZE\_EXTENDED

### ASSOC_MSG_W_ATTACH_COUNT {#ASSOC-MSG-W-ATTACH-COUNT}
```
public static final PidTagPropertyDescriptor ASSOC_MSG_W_ATTACH_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ASSOC\_MSG\_W\_ATTACH\_COUNT

### ATTACHMENT_CONTACT_PHOTO {#ATTACHMENT-CONTACT-PHOTO}
```
public static final PidTagPropertyDescriptor ATTACHMENT_CONTACT_PHOTO
```


Indicates that a contact photo attachment is attached to a Contact object. Area: Message Attachment Properties Canonical name: PidTagAttachmentContactPhoto Alternate names: PR\_ATTACHMENT\_CONTACTPHOTO

### ATTACHMENT_FLAGS {#ATTACHMENT-FLAGS}
```
public static final PidTagPropertyDescriptor ATTACHMENT_FLAGS
```


Indicates special handling for an Attachment object. Area: Message Attachment Properties Canonical name: PidTagAttachmentFlags Alternate names: PR\_ATTACHMENT\_FLAGS, ptagAttachmentFlags

### ATTACHMENT_HIDDEN {#ATTACHMENT-HIDDEN}
```
public static final PidTagPropertyDescriptor ATTACHMENT_HIDDEN
```


Indicates whether an Attachment object is hidden from the end user. Area: Message Attachment Properties Canonical name: PidTagAttachmentHidden Alternate names: PR\_ATTACHMENT\_HIDDEN

### ATTACHMENT_IS_FOLDER {#ATTACHMENT-IS-FOLDER}
```
public static final PidNamePropertyDescriptor ATTACHMENT_IS_FOLDER
```


A value indicating whether the attachment points to a folder.

### ATTACHMENT_LINK_ID {#ATTACHMENT-LINK-ID}
```
public static final PidTagPropertyDescriptor ATTACHMENT_LINK_ID
```


Contains the type of Message object to which an attachment is linked. Area: Message Attachment Properties Canonical name: PidTagAttachmentLinkId Alternate names: PR\_ATTACHMENT\_LINKID, ptagAttachmentLinkId

### ATTACHMENT_MAC_CONTENT_TYPE {#ATTACHMENT-MAC-CONTENT-TYPE}
```
public static final PidNamePropertyDescriptor ATTACHMENT_MAC_CONTENT_TYPE
```


Contains the Content-Type of the Mac attachment. Area: Message Attachment Properties Canonical name: PidNameAttachmentMacContentType Alternate names:

### ATTACHMENT_MAC_INFO {#ATTACHMENT-MAC-INFO}
```
public static final PidNamePropertyDescriptor ATTACHMENT_MAC_INFO
```


Contains the headers and resource fork data associated with the Mac attachment. Area: Message Attachment Properties Canonical name: PidNameAttachmentMacInfo Alternate names:

### ATTACHMENT_ORIGINAL_PERMISSION_TYPE {#ATTACHMENT-ORIGINAL-PERMISSION-TYPE}
```
public static final PidNamePropertyDescriptor ATTACHMENT_ORIGINAL_PERMISSION_TYPE
```


The original permission of the attachment.

### ATTACHMENT_ORIGINAL_URL {#ATTACHMENT-ORIGINAL-URL}
```
public static final PidNamePropertyDescriptor ATTACHMENT_ORIGINAL_URL
```


The original URL of the attachment.

### ATTACHMENT_PERMISSION_TYPE {#ATTACHMENT-PERMISSION-TYPE}
```
public static final PidNamePropertyDescriptor ATTACHMENT_PERMISSION_TYPE
```


The permission of the attachment.

### ATTACHMENT_PREVIEW_URL {#ATTACHMENT-PREVIEW-URL}
```
public static final PidNamePropertyDescriptor ATTACHMENT_PREVIEW_URL
```


The URL of the attachment preview.

### ATTACHMENT_PROVIDER_ENDPOINT_URL {#ATTACHMENT-PROVIDER-ENDPOINT-URL}
```
public static final PidNamePropertyDescriptor ATTACHMENT_PROVIDER_ENDPOINT_URL
```


The URL of the attachment provider.

### ATTACHMENT_PROVIDER_TYPE {#ATTACHMENT-PROVIDER-TYPE}
```
public static final PidNamePropertyDescriptor ATTACHMENT_PROVIDER_TYPE
```


The type of the attachment provider.

### ATTACHMENT_THUMBNAIL_URL {#ATTACHMENT-THUMBNAIL-URL}
```
public static final PidNamePropertyDescriptor ATTACHMENT_THUMBNAIL_URL
```


The URL of the attachment thumbnail.

### ATTACHMENT_X_400_PARAMETERS {#ATTACHMENT-X-400-PARAMETERS}
```
public static final PidTagPropertyDescriptor ATTACHMENT_X_400_PARAMETERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ATTACHMENT\_X400\_PARAMETERS

### ATTACH_ADDITIONAL_INFORMATION {#ATTACH-ADDITIONAL-INFORMATION}
```
public static final PidTagPropertyDescriptor ATTACH_ADDITIONAL_INFORMATION
```


Contains attachment encoding information. Area: Message Attachment Properties Canonical name: PidTagAttachAdditionalInformation Alternate names: PR\_ATTACH\_ADDITIONAL\_INFO

### ATTACH_CONTENT_BASE {#ATTACH-CONTENT-BASE}
```
public static final PidTagPropertyDescriptor ATTACH_CONTENT_BASE
```


Contains the base of a relative URI. Area: Message Attachment Properties Canonical name: PidTagAttachContentBase Alternate names:

### ATTACH_CONTENT_ID {#ATTACH-CONTENT-ID}
```
public static final PidTagPropertyDescriptor ATTACH_CONTENT_ID
```


Contains a content identifier unique to the Message object that matches a corresponding Area: Message Attachment Properties Canonical name: PidTagAttachContentId Alternate names: PR\_ATTACH\_CONTENT\_ID, PR\_ATTACH\_CONTENT\_ID\_A, PR\_ATTACH\_CONTENT\_ID\_W

### ATTACH_CONTENT_LOCATION {#ATTACH-CONTENT-LOCATION}
```
public static final PidTagPropertyDescriptor ATTACH_CONTENT_LOCATION
```


Contains a relative or full URI that matches a corresponding reference in the HTML body of a Message object. Area: Message Attachment Properties Canonical name: PidTagAttachContentLocation Alternate names: PR\_ATTACH\_CONTENT\_LOCATION, PR\_ATTACH\_CONTENT\_LOCATION\_A, PR\_ATTACH\_CONTENT\_LOCATION\_W

### ATTACH_DATA_BINARY {#ATTACH-DATA-BINARY}
```
public static final PidTagPropertyDescriptor ATTACH_DATA_BINARY
```


Contains the contents of the file to be attached. Area: Message Attachment Properties Canonical name: PidTagAttachDataBinary Alternate names: PR\_ATTACH\_DATA\_BIN, ptagAttachDataBin

### ATTACH_DATA_OBJECT {#ATTACH-DATA-OBJECT}
```
public static final PidTagPropertyDescriptor ATTACH_DATA_OBJECT
```


Contains the binary representation of the Attachment object in an application-specific format. Area: Message Attachment Properties Canonical name: PidTagAttachDataObject Alternate names: PR\_ATTACH\_DATA\_OBJ, ptagAttachDataObj

### ATTACH_ENCODING {#ATTACH-ENCODING}
```
public static final PidTagPropertyDescriptor ATTACH_ENCODING
```


Contains encoding information about the Attachment object. Area: Message Attachment Properties Canonical name: PidTagAttachEncoding Alternate names: PR\_ATTACH\_ENCODING

### ATTACH_EXTENSION {#ATTACH-EXTENSION}
```
public static final PidTagPropertyDescriptor ATTACH_EXTENSION
```


Contains a file name extension that indicates the document type of an attachment. Area: Message Attachment Properties Canonical name: PidTagAttachExtension Alternate names: PR\_ATTACH\_EXTENSION, PR\_ATTACH\_EXTENSION\_A, PR\_ATTACH\_EXTENSION\_W

### ATTACH_FILENAME {#ATTACH-FILENAME}
```
public static final PidTagPropertyDescriptor ATTACH_FILENAME
```


Contains the 8.3 name of the PidTagAttachLongFilename property (section 2.586). Area: Message Attachment Properties Canonical name: PidTagAttachFilename Alternate names: PR\_ATTACH\_FILENAME, PR\_ATTACH\_FILENAME\_A, ptagAttachFilename, PR\_ATTACH\_FILENAME\_W

### ATTACH_FLAGS {#ATTACH-FLAGS}
```
public static final PidTagPropertyDescriptor ATTACH_FLAGS
```


Indicates which body formats might reference this attachment when rendering data. Area: Message Attachment Properties Canonical name: PidTagAttachFlags Alternate names: PR\_ATTACH\_FLAGS

### ATTACH_LONG_FILENAME {#ATTACH-LONG-FILENAME}
```
public static final PidTagPropertyDescriptor ATTACH_LONG_FILENAME
```


Contains the full filename and extension of the Attachment object. Area: Message Attachment Properties Canonical name: PidTagAttachLongFilename Alternate names: PR\_ATTACH\_LONG\_FILENAME, PR\_ATTACH\_LONG\_FILENAME\_A,

### ATTACH_LONG_PATHNAME {#ATTACH-LONG-PATHNAME}
```
public static final PidTagPropertyDescriptor ATTACH_LONG_PATHNAME
```


Contains the fully-qualified path and file name with extension. Area: Message Attachment Properties Canonical name: PidTagAttachLongPathname Alternate names: PR\_ATTACH\_LONG\_PATHNAME, PR\_ATTACH\_LONG\_PATHNAME\_A, ptagAttachLongPathname, PR\_ATTACH\_LONG\_PATHNAME\_W

### ATTACH_METHOD {#ATTACH-METHOD}
```
public static final PidTagPropertyDescriptor ATTACH_METHOD
```


Represents the way the contents of an attachment are accessed. Area: Message Attachment Properties Canonical name: PidTagAttachMethod Alternate names: PR\_ATTACH\_METHOD, ptagAttachMethod

### ATTACH_MIME_TAG {#ATTACH-MIME-TAG}
```
public static final PidTagPropertyDescriptor ATTACH_MIME_TAG
```


Contains a content-type MIME header. Area: Message Attachment Properties Canonical name: PidTagAttachMimeTag Alternate names: PR\_ATTACH\_MIME\_TAG, PR\_ATTACH\_MIME\_TAG\_A, PR\_ATTACH\_MIME\_TAG\_W

### ATTACH_NUMBER {#ATTACH-NUMBER}
```
public static final PidTagPropertyDescriptor ATTACH_NUMBER
```


Identifies the Attachment object within its Message object. Area: Message Attachment Properties Canonical name: PidTagAttachNumber Alternate names: PR\_ATTACH\_NUM, ptagAttachNum

### ATTACH_ON_ASSOC_MSG_COUNT {#ATTACH-ON-ASSOC-MSG-COUNT}
```
public static final PidTagPropertyDescriptor ATTACH_ON_ASSOC_MSG_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ATTACH\_ON\_ASSOC\_MSG\_COUNT

### ATTACH_ON_NORMAL_MSG_COUNT {#ATTACH-ON-NORMAL-MSG-COUNT}
```
public static final PidTagPropertyDescriptor ATTACH_ON_NORMAL_MSG_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ATTACH\_ON\_NORMAL\_MSG\_COUNT

### ATTACH_PATHNAME {#ATTACH-PATHNAME}
```
public static final PidTagPropertyDescriptor ATTACH_PATHNAME
```


Contains the 8.3 name of the PidTagAttachLongPathname property (section 2.587). Area: Message Attachment Properties Canonical name: PidTagAttachPathname Alternate names: PR\_ATTACH\_PATHNAME, PR\_ATTACH\_PATHNAME\_A, ptagAttachPathname, PR\_ATTACH\_PATHNAME\_W

### ATTACH_PAYLOAD_CLASS {#ATTACH-PAYLOAD-CLASS}
```
public static final PidTagPropertyDescriptor ATTACH_PAYLOAD_CLASS
```


Contains the class name of an object that can display the contents of the message. Area: Outlook Application Canonical name: PidTagAttachPayloadClass Alternate names: PR\_ATTACH\_PAYLOAD\_CLASS, PR\_ATTACH\_PAYLOAD\_CLASS\_A, PR\_ATTACH\_PAYLOAD\_CLASS\_W, ptagAttachPayloadClass

### ATTACH_PAYLOAD_PROVIDER_GUID_STRING {#ATTACH-PAYLOAD-PROVIDER-GUID-STRING}
```
public static final PidTagPropertyDescriptor ATTACH_PAYLOAD_PROVIDER_GUID_STRING
```


Contains the GUID of the software component that can display the contents of the message. Area: Outlook Application Canonical name: PidTagAttachPayloadProviderGuidString Alternate names: PR\_ATTACH\_PAYLOAD\_PROV\_GUID\_STR, PR\_ATTACH\_PAYLOAD\_PROV\_GUID\_STR\_A, PR\_ATTACH\_PAYLOAD\_PROV\_GUID\_STR\_W

### ATTACH_RENDERING {#ATTACH-RENDERING}
```
public static final PidTagPropertyDescriptor ATTACH_RENDERING
```


Contains a Windows Metafile, as specified in [MS-WMF], for the Attachment object. Area: Message Attachment Properties Canonical name: PidTagAttachRendering Alternate names: PR\_ATTACH\_RENDERING, ptagAttachRendering

### ATTACH_SIZE {#ATTACH-SIZE}
```
public static final PidTagPropertyDescriptor ATTACH_SIZE
```


Contains the size, in bytes, consumed by the Attachment object on the server. Area: Message Attachment Properties Canonical name: PidTagAttachSize Alternate names: PR\_ATTACH\_SIZE, ptagAttachSize

### ATTACH_TAG {#ATTACH-TAG}
```
public static final PidTagPropertyDescriptor ATTACH_TAG
```


Contains the identifier information for the application that supplied the Attachment object data. Area: Message Attachment Properties Canonical name: PidTagAttachTag Alternate names: PR\_ATTACH\_TAG

### ATTACH_TRANSPORT_NAME {#ATTACH-TRANSPORT-NAME}
```
public static final PidTagPropertyDescriptor ATTACH_TRANSPORT_NAME
```


Contains the name of an attachment file, modified so that it can be correlated with TNEF messages. Area: Message Attachment Properties Canonical name: PidTagAttachTransportName Alternate names: PR\_ATTACH\_TRANSPORT\_NAME, PR\_ATTACH\_TRANSPORT\_NAME\_A, PR\_ATTACH\_TRANSPORT\_NAME\_W

### ATTENDEE_CRITICAL_CHANGE {#ATTENDEE-CRITICAL-CHANGE}
```
public static final PidLidPropertyDescriptor ATTENDEE_CRITICAL_CHANGE
```


Specifies the date and time at which the meeting-related object was sent. Area: Meetings Canonical name: PidLidAttendeeCriticalChange Alternate names: LID\_ATTENDEE\_CRITICAL\_CHANGE

### ATTRIBUTE_HIDDEN {#ATTRIBUTE-HIDDEN}
```
public static final PidTagPropertyDescriptor ATTRIBUTE_HIDDEN
```


Specifies the hide or show status of a folder. Area: Access Control Properties Canonical name: PidTagAttributeHidden Alternate names: PR\_ATTR\_HIDDEN, ptagAttrHidden, DAV:ishidden

### ATTRIBUTE_READ_ONLY {#ATTRIBUTE-READ-ONLY}
```
public static final PidTagPropertyDescriptor ATTRIBUTE_READ_ONLY
```


Indicates whether an item can be modified or deleted. Area: Access Control Properties Canonical name: PidTagAttributeReadOnly Alternate names: PR\_ATTR\_READONLY, ptagAttrReadonly, DAV:isreadonly

### AUDIO_NOTES {#AUDIO-NOTES}
```
public static final PidNamePropertyDescriptor AUDIO_NOTES
```


Contains textual annotations to a voice message after it has been delivered to the user's mailbox. Area: Unified Messaging Canonical name: PidNameAudioNotes Alternate names: UMAudioNotes

### AUTHOR {#AUTHOR}
```
public static final PidNamePropertyDescriptor AUTHOR
```


Specifies the author of the file attached to the Document object. Area: Common Canonical name: PidNameAuthor Alternate names: urn:schemas-microsoft-com:office:office\#Author

### AUTHORIZING_USERS {#AUTHORIZING-USERS}
```
public static final PidTagPropertyDescriptor AUTHORIZING_USERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_AUTHORIZING\_USERS

### AUTOMATIC_SPEECH_RECOGNITION_DATA {#AUTOMATIC-SPEECH-RECOGNITION-DATA}
```
public static final PidNamePropertyDescriptor AUTOMATIC_SPEECH_RECOGNITION_DATA
```


Contains an unprotected voice message. Area: Unified Messaging Canonical name: PidNameAutomaticSpeechRecognitionData Alternate names:

### AUTO_ADD_NEW_SUBS {#AUTO-ADD-NEW-SUBS}
```
public static final PidTagPropertyDescriptor AUTO_ADD_NEW_SUBS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_AUTO\_ADD\_NEW\_SUBS

### AUTO_FILL_LOCATION {#AUTO-FILL-LOCATION}
```
public static final PidLidPropertyDescriptor AUTO_FILL_LOCATION
```


Indicates whether the value of the PidLidLocation property (section 2.159) is set to the PidTagDisplayName property (section 2.667). Area: Meetings Canonical name: PidLidAutoFillLocation Alternate names: dispidAutoFillLocation

### AUTO_FORWARDED {#AUTO-FORWARDED}
```
public static final PidTagPropertyDescriptor AUTO_FORWARDED
```


Indicates that a Message object has been automatically generated or automatically forwarded. Area: General Report Properties Canonical name: PidTagAutoForwarded Alternate names: PR\_AUTO\_FORWARDED, ptagAutoForwarded

### AUTO_FORWARD_COMMENT {#AUTO-FORWARD-COMMENT}
```
public static final PidTagPropertyDescriptor AUTO_FORWARD_COMMENT
```


Contains text included in an automatically-generated message. Area: General Report Properties Canonical name: PidTagAutoForwardComment Alternate names: PR\_AUTO\_FORWARD\_COMMENT, PR\_AUTO\_FORWARD\_COMMENT\_A, PR\_AUTO\_FORWARD\_COMMENT\_W

### AUTO_LOG {#AUTO-LOG}
```
public static final PidLidPropertyDescriptor AUTO_LOG
```


Specifies to the application whether to create a Journal object for each action associated with this Contact object. Area: Contact Properties Canonical name: PidLidAutoLog Alternate names: dispidAutoLog

### AUTO_PROCESS_STATE {#AUTO-PROCESS-STATE}
```
public static final PidLidPropertyDescriptor AUTO_PROCESS_STATE
```


Specifies the options used in the automatic processing of email messages. Area: General Message Properties Canonical name: PidLidAutoProcessState Alternate names: dispidSniffState

### AUTO_RESPONSE_SUPPRESS {#AUTO-RESPONSE-SUPPRESS}
```
public static final PidTagPropertyDescriptor AUTO_RESPONSE_SUPPRESS
```


Specifies whether a client or server application should forego sending automated replies in response to this message. Area: Email Canonical name: PidTagAutoResponseSuppress Alternate names: PR\_AUTO\_RESPONSE\_SUPPRESS, ptagAutoResponseSuppress

### AUTO_START_CHECK {#AUTO-START-CHECK}
```
public static final PidLidPropertyDescriptor AUTO_START_CHECK
```


Specifies whether to automatically start the conferencing application when a reminder for the start of a meeting is executed. Area: Conferencing Canonical name: PidLidAutoStartCheck Alternate names: dispidAutoStartCheck

### BILATERAL_INFO {#BILATERAL-INFO}
```
public static final PidTagPropertyDescriptor BILATERAL_INFO
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_BILATERAL\_INFO

### BILLING {#BILLING}
```
public static final PidLidPropertyDescriptor BILLING
```


Specifies billing information for the contact. Area: General Message Properties Canonical name: PidLidBilling Alternate names: dispidBilling

### BIRTHDAY {#BIRTHDAY}
```
public static final PidTagPropertyDescriptor BIRTHDAY
```


Contains the date of the mail user's birthday at midnight. Area: Contact Properties Canonical name: PidTagBirthday Alternate names: PR\_BIRTHDAY, urn:schemas:contacts:bday

### BIRTHDAY_EVENT_ENTRY_ID {#BIRTHDAY-EVENT-ENTRY-ID}
```
public static final PidLidPropertyDescriptor BIRTHDAY_EVENT_ENTRY_ID
```


Specifies the EntryID of an optional Appointment object that represents the birthday of the contact. Area: Contact Properties Canonical name: PidLidBirthdayEventEntryId Alternate names: dispidBirthdayEventEID

### BIRTHDAY_LOCAL {#BIRTHDAY-LOCAL}
```
public static final PidLidPropertyDescriptor BIRTHDAY_LOCAL
```


Specifies the birthday of a contact. Area: Contact Properties Canonical name: PidLidBirthdayLocal Alternate names: dispidApptBirthdayLocal

### BLOCK_STATUS {#BLOCK-STATUS}
```
public static final PidTagPropertyDescriptor BLOCK_STATUS
```


Indicates the user's preference for viewing external content (such as links to images on an HTTP server) in the message body. Area: Secure Messaging Properties Canonical name: PidTagBlockStatus Alternate names: PR\_BLOCK\_STATUS, ptagBlockStatus

### BODY {#BODY}
```
public static final PidTagPropertyDescriptor BODY
```


Contains message body text in plain text format. Area: General Message Properties Canonical name: PidTagBody Alternate names: PR\_BODY, PR\_BODY\_A, ptagBody, PR\_BODY\_W,

### BODY_CONTENT_ID {#BODY-CONTENT-ID}
```
public static final PidTagPropertyDescriptor BODY_CONTENT_ID
```


Contains a GUID that corresponds to the current message body. Area: Exchange Canonical name: PidTagBodyContentId Alternate names: PR\_BODY\_CONTENT\_ID, PR\_BODY\_CONTENT\_ID\_A, PR\_BODY\_CONTENT\_ID\_W

### BODY_CONTENT_LOCATION {#BODY-CONTENT-LOCATION}
```
public static final PidTagPropertyDescriptor BODY_CONTENT_LOCATION
```


Contains a globally unique Uniform Resource Identifier (URI) that serves as a label for the current message body. Area: MIME Properties Canonical name: PidTagBodyContentLocation Alternate names: PR\_BODY\_CONTENT\_LOCATION, PR\_BODY\_CONTENT\_LOCATION\_A, PR\_BODY\_CONTENT\_LOCATION\_W

### BODY_CRC {#BODY-CRC}
```
public static final PidTagPropertyDescriptor BODY_CRC
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_BODY\_CRC

### BODY_HTML {#BODY-HTML}
```
public static final PidTagPropertyDescriptor BODY_HTML
```


Contains the HTML body of the Message object. Area: General Message Properties Canonical name: PidTagBodyHtml Alternate names: PR\_BODY\_HTML, PR\_BODY\_HTML\_A, ptagBodyHtml, PR\_BODY\_HTML\_W

### BUSINESS_2_TELEPHONE_NUMBER {#BUSINESS-2-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor BUSINESS_2_TELEPHONE_NUMBER
```


Contains a secondary telephone number at the mail user's place of business. Area: Contact Properties Canonical name: PidTagBusiness2TelephoneNumber Alternate names: "PR\_BUSINESS2\_TELEPHONE\_NUMBER, PR\_BUSINESS2\_TELEPHONE\_NUMBER\_A, PR\_BUSINESS2\_TELEPHONE\_NUMBER\_W, PR\_OFFICE2\_TELEPHONE\_NUMBER,

### BUSINESS_2_TELEPHONE_NUMBERS {#BUSINESS-2-TELEPHONE-NUMBERS}
```
public static final PidTagPropertyDescriptor BUSINESS_2_TELEPHONE_NUMBERS
```


Contains secondary telephone numbers at the mail user's place of business. Area: Contact Properties Canonical name: PidTagBusiness2TelephoneNumbers Alternate names: PR\_BUSINESS2\_TELEPHONE\_NUMBER\_A\_MV

### BUSINESS_CARD_CARD_PICTURE {#BUSINESS-CARD-CARD-PICTURE}
```
public static final PidLidPropertyDescriptor BUSINESS_CARD_CARD_PICTURE
```


Contains the image to be used on a business card. Area: Contact Properties Canonical name: PidLidBusinessCardCardPicture Alternate names: dispidBCCardPicture

### BUSINESS_CARD_DISPLAY_DEFINITION {#BUSINESS-CARD-DISPLAY-DEFINITION}
```
public static final PidLidPropertyDescriptor BUSINESS_CARD_DISPLAY_DEFINITION
```


Contains user customization details for displaying a contact as a business card. Area: Contact Properties Canonical name: PidLidBusinessCardDisplayDefinition Alternate names: dispidBCDisplayDefinition

### BUSINESS_FAX_NUMBER {#BUSINESS-FAX-NUMBER}
```
public static final PidTagPropertyDescriptor BUSINESS_FAX_NUMBER
```


Contains the telephone number of the mail user's business fax machine. Area: Contact Properties Canonical name: PidTagBusinessFaxNumber Alternate names: PR\_BUSINESS\_FAX\_NUMBER, PR\_BUSINESS\_FAX\_NUMBER\_A,

### BUSINESS_HOME_PAGE {#BUSINESS-HOME-PAGE}
```
public static final PidTagPropertyDescriptor BUSINESS_HOME_PAGE
```


Contains the URL of the mail user's business home page. Area: Contact Properties Canonical name: PidTagBusinessHomePage Alternate names: PR\_BUSINESS\_HOME\_PAGE, PR\_BUSINESS\_HOME\_PAGE\_A, PR\_BUSINESS\_HOME\_PAGE\_W,

### BUSINESS_TELEPHONE_NUMBER {#BUSINESS-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor BUSINESS_TELEPHONE_NUMBER
```


Contains the primary telephone number of the mail user's place of business. Area: Contact Properties Canonical name: PidTagBusinessTelephoneNumber Alternate names: PR\_BUSINESS\_TELEPHONE\_NUMBER, PR\_BUSINESS\_TELEPHONE\_NUMBER\_A, PR\_BUSINESS\_TELEPHONE\_NUMBER\_W, PR\_OFFICE\_TELEPHONE\_NUMBER,

### BUSY_STATUS {#BUSY-STATUS}
```
public static final PidLidPropertyDescriptor BUSY_STATUS
```


Specifies the availability of a user for the event described by the object. Area: Calendar Canonical name: PidLidBusyStatus Alternate names: dispidBusyStatus

### BYTE_COUNT {#BYTE-COUNT}
```
public static final PidNamePropertyDescriptor BYTE_COUNT
```


Specifies the size, in bytes, of the file attached to the Document object. Area: Common Canonical name: PidNameByteCount Alternate names: urn:schemas-microsoft-com:office:office\#Bytes

### CACHED_COLUMN_COUNT {#CACHED-COLUMN-COUNT}
```
public static final PidTagPropertyDescriptor CACHED_COLUMN_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CACHED\_COLUMN\_COUNT

### CALENDAR_ATTENDEE_ROLE {#CALENDAR-ATTENDEE-ROLE}
```
public static final PidNamePropertyDescriptor CALENDAR_ATTENDEE_ROLE
```


Specifies the role of the attendee. Area: Common Canonical name: PidNameCalendarAttendeeRole Alternate names: urn:schemas:calendar:attendeerole

### CALENDAR_BUSYSTATUS {#CALENDAR-BUSYSTATUS}
```
public static final PidNamePropertyDescriptor CALENDAR_BUSYSTATUS
```


Specifies whether the attendee is busy at the time of an appointment on their calendar. Area: Common Canonical name: PidNameCalendarBusystatus Alternate names: urn:schemas:calendar:busystatus

### CALENDAR_CONTACT {#CALENDAR-CONTACT}
```
public static final PidNamePropertyDescriptor CALENDAR_CONTACT
```


Identifies the name of a contact who is an attendee of a meeting. Area: Common Canonical name: PidNameCalendarContact Alternate names: urn:schemas:calendar:contact

### CALENDAR_CONTACT_URL {#CALENDAR-CONTACT-URL}
```
public static final PidNamePropertyDescriptor CALENDAR_CONTACT_URL
```


Identifies the URL where you can access contact information in HTML format. Area: Common Canonical name: PidNameCalendarContactUrl Alternate names: urn:schemas:calendar:contacturl

### CALENDAR_CREATED {#CALENDAR-CREATED}
```
public static final PidNamePropertyDescriptor CALENDAR_CREATED
```


Identifies the date and time, in UTC, when the organizer created the appointment or meeting. Area: Common Canonical name: PidNameCalendarCreated Alternate names: urn:schemas:calendar:created

### CALENDAR_DESCRIPTION_URL {#CALENDAR-DESCRIPTION-URL}
```
public static final PidNamePropertyDescriptor CALENDAR_DESCRIPTION_URL
```


Specifies the URL of a resource that contains a description of an appointment or meeting. Area: Common Canonical name: PidNameCalendarDescriptionUrl Alternate names: urn:schemas:calendar:descriptionurl

### CALENDAR_DURATION {#CALENDAR-DURATION}
```
public static final PidNamePropertyDescriptor CALENDAR_DURATION
```


Identifies the duration, in seconds, of an appointment or meeting. Area: Common Canonical name: PidNameCalendarDuration Alternate names: urn:schemas:calendar:duration

### CALENDAR_EXCEPTION_DATE {#CALENDAR-EXCEPTION-DATE}
```
public static final PidNamePropertyDescriptor CALENDAR_EXCEPTION_DATE
```


Identifies a list of dates that are exceptions to a recurring appointment. Area: Common Canonical name: PidNameCalendarExceptionDate Alternate names: urn:schemas:calendar:exdate

### CALENDAR_EXCEPTION_RULE {#CALENDAR-EXCEPTION-RULE}
```
public static final PidNamePropertyDescriptor CALENDAR_EXCEPTION_RULE
```


Specifies an exception rule for a recurring appointment. Area: Common Canonical name: PidNameCalendarExceptionRule Alternate names: urn:schemas:calendar:exrule

### CALENDAR_GEO_LATITUDE {#CALENDAR-GEO-LATITUDE}
```
public static final PidNamePropertyDescriptor CALENDAR_GEO_LATITUDE
```


Specifies the geographical latitude of the location of an appointment. Area: Common Canonical name: PidNameCalendarGeoLatitude Alternate names: urn:schemas:calendar:geolatitude

### CALENDAR_GEO_LONGITUDE {#CALENDAR-GEO-LONGITUDE}
```
public static final PidNamePropertyDescriptor CALENDAR_GEO_LONGITUDE
```


Specifies the geographical longitude of the location of an appointment. Area: Common Canonical name: PidNameCalendarGeoLongitude Alternate names: urn:schemas:calendar:geolongitude

### CALENDAR_INSTANCE_TYPE {#CALENDAR-INSTANCE-TYPE}
```
public static final PidNamePropertyDescriptor CALENDAR_INSTANCE_TYPE
```


Specifies the type of an appointment. Area: Common Canonical name: PidNameCalendarInstanceType Alternate names: urn:schemas:calendar:instancetype

### CALENDAR_IS_ORGANIZER {#CALENDAR-IS-ORGANIZER}
```
public static final PidNamePropertyDescriptor CALENDAR_IS_ORGANIZER
```


Specifies whether an attendee is the organizer of an appointment or meeting. Area: Common Canonical name: PidNameCalendarIsOrganizer Alternate names: urn:schemas:calendar:isorganizer

### CALENDAR_LAST_MODIFIED {#CALENDAR-LAST-MODIFIED}
```
public static final PidNamePropertyDescriptor CALENDAR_LAST_MODIFIED
```


Specifies the date and time, in UTC, when an appointment was last modified. Area: Common Canonical name: PidNameCalendarLastModified Alternate names: urn:schemas:calendar:lastmodified

### CALENDAR_LOCATION_URL {#CALENDAR-LOCATION-URL}
```
public static final PidNamePropertyDescriptor CALENDAR_LOCATION_URL
```


Specifies a URL with location information in HTML format. Area: Common Canonical name: PidNameCalendarLocationUrl Alternate names: urn:schemas:calendar:locationurl

### CALENDAR_MEETING_STATUS {#CALENDAR-MEETING-STATUS}
```
public static final PidNamePropertyDescriptor CALENDAR_MEETING_STATUS
```


Specifies the status of an appointment or meeting. Area: Common Canonical name: PidNameCalendarMeetingStatus Alternate names: urn:schemas:calendar:meetingstatus

### CALENDAR_METHOD {#CALENDAR-METHOD}
```
public static final PidNamePropertyDescriptor CALENDAR_METHOD
```


Specifies the iCalendar method that is associated with an Appointment object. Area: Common Canonical name: PidNameCalendarMethod Alternate names: urn:schemas:calendar:method

### CALENDAR_PRODUCT_ID {#CALENDAR-PRODUCT-ID}
```
public static final PidNamePropertyDescriptor CALENDAR_PRODUCT_ID
```


Identifies the product that created the iCalendar-formatted stream. Area: Common Canonical name: PidNameCalendarProductId Alternate names: urn:schemas:calendar:prodid

### CALENDAR_RECURRENCE_ID_RANGE {#CALENDAR-RECURRENCE-ID-RANGE}
```
public static final PidNamePropertyDescriptor CALENDAR_RECURRENCE_ID_RANGE
```


Specifies which instances of a recurring appointment are being referred to. Area: Common Canonical name: PidNameCalendarRecurrenceIdRange Alternate names: urn:schemas:calendar:recurrenceidrange

### CALENDAR_REMINDER_OFFSET {#CALENDAR-REMINDER-OFFSET}
```
public static final PidNamePropertyDescriptor CALENDAR_REMINDER_OFFSET
```


Identifies the number of seconds before an appointment starts that a reminder is to be displayed. Area: Common Canonical name: PidNameCalendarReminderOffset Alternate names: urn:schemas:calendar:reminderoffset

### CALENDAR_RESOURCES {#CALENDAR-RESOURCES}
```
public static final PidNamePropertyDescriptor CALENDAR_RESOURCES
```


Identifies a list of resources, such as rooms and video equipment, that are available for an appointment. Area: Common Canonical name: PidNameCalendarResources Alternate names: urn:schemas:calendar:resources

### CALENDAR_RSVP {#CALENDAR-RSVP}
```
public static final PidNamePropertyDescriptor CALENDAR_RSVP
```


Specifies whether the organizer of an appointment or meeting requested a response. Area: Common Canonical name: PidNameCalendarRsvp Alternate names: urn:schemas:calendar:rsvp

### CALENDAR_SEQUENCE {#CALENDAR-SEQUENCE}
```
public static final PidNamePropertyDescriptor CALENDAR_SEQUENCE
```


Specifies the sequence number of a version of an appointment. Area: Common Canonical name: PidNameCalendarSequence Alternate names: urn:schemas:calendar:sequence

### CALENDAR_TIME_ZONE {#CALENDAR-TIME-ZONE}
```
public static final PidNamePropertyDescriptor CALENDAR_TIME_ZONE
```


Specifies the time zone of an appointment or meeting. Area: Common Canonical name: PidNameCalendarTimeZone Alternate names: urn:schemas:calendar:timezone

### CALENDAR_TIME_ZONE_ID {#CALENDAR-TIME-ZONE-ID}
```
public static final PidNamePropertyDescriptor CALENDAR_TIME_ZONE_ID
```


Specifies the time zone identifier of an appointment or meeting. Area: Common Canonical name: PidNameCalendarTimeZoneId Alternate names: urn:schemas:calendar:timezoneid

### CALENDAR_TRANSPARENT {#CALENDAR-TRANSPARENT}
```
public static final PidNamePropertyDescriptor CALENDAR_TRANSPARENT
```


Specifies whether an appointment or meeting is visible to busy time searches. Area: Common Canonical name: PidNameCalendarTransparent Alternate names: urn:schemas:calendar:transparent

### CALENDAR_TYPE {#CALENDAR-TYPE}
```
public static final PidLidPropertyDescriptor CALENDAR_TYPE
```


Contains the value of the CalendarType field from the PidLidAppointmentRecur property (section 2.22). Area: Meetings Canonical name: PidLidCalendarType Alternate names: LID\_CALENDAR\_TYPE

### CALENDAR_UID {#CALENDAR-UID}
```
public static final PidNamePropertyDescriptor CALENDAR_UID
```


Specifies the unique identifier of an appointment or meeting. Area: Common Canonical name: PidNameCalendarUid Alternate names: urn:schemas:calendar:uid

### CALENDAR_VERSION {#CALENDAR-VERSION}
```
public static final PidNamePropertyDescriptor CALENDAR_VERSION
```


Identifies the version of the iCalendar specification, as specified in [MS-OXCICAL] section 2.1.3.1.1.3, that is required to correctly interpret an iCalendar object. Area: Common Canonical name: PidNameCalendarVersion Alternate names: urn:schemas:calendar:version

### CALLBACK_TELEPHONE_NUMBER {#CALLBACK-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor CALLBACK_TELEPHONE_NUMBER
```


Contains a telephone number to reach the mail user. Area: Contact Properties Canonical name: PidTagCallbackTelephoneNumber Alternate names: PR\_CALLBACK\_TELEPHONE\_NUMBER, PR\_CALLBACK\_TELEPHONE\_NUMBER\_A,

### CALL_ID {#CALL-ID}
```
public static final PidTagPropertyDescriptor CALL_ID
```


Contains a unique identifier associated with the phone call. Area: Unified Messaging Canonical name: PidTagCallId Alternate names: InternalSchemaCallID

### CAR_TELEPHONE_NUMBER {#CAR-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor CAR_TELEPHONE_NUMBER
```


Contains the mail user's car telephone number. Area: Contact Properties Canonical name: PidTagCarTelephoneNumber Alternate names: PR\_CAR\_TELEPHONE\_NUMBER, PR\_CAR\_TELEPHONE\_NUMBER\_A,

### CATEGORIES {#CATEGORIES}
```
public static final PidLidPropertyDescriptor CATEGORIES
```


Contains the array of text labels assigned to this Message object. Area: Common Canonical name: PidLidCategories Alternate names: dispidCategories

### CATEGORY {#CATEGORY}
```
public static final PidNamePropertyDescriptor CATEGORY
```


Specifies the category of the file attached to the Document object. Area: Common Canonical name: PidNameCategory Alternate names: urn:schemas-microsoft-com:office:office\#Category

### CATEG_COUNT {#CATEG-COUNT}
```
public static final PidTagPropertyDescriptor CATEG_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CATEG\_COUNT

### CC_ATTENDEES_STRING {#CC-ATTENDEES-STRING}
```
public static final PidLidPropertyDescriptor CC_ATTENDEES_STRING
```


Contains a list of all the sendable attendees who are also optional attendees. Area: Meetings Canonical name: PidLidCcAttendeesString Alternate names: dispidCCAttendeesString

### CDO_RECURRENCEID {#CDO-RECURRENCEID}
```
public static final PidTagPropertyDescriptor CDO_RECURRENCEID
```


Identifies a specific instance of a recurring appointment. Area: Exchange Canonical name: PidTagCdoRecurrenceid Alternate names: PR\_CDO\_RECURRENCEID, urn:schemas:calendar:recurrenceid

### CHANGE_ADVISOR {#CHANGE-ADVISOR}
```
public static final PidTagPropertyDescriptor CHANGE_ADVISOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CHANGE\_ADVISOR

### CHANGE_HIGHLIGHT {#CHANGE-HIGHLIGHT}
```
public static final PidLidPropertyDescriptor CHANGE_HIGHLIGHT
```


Specifies a bit field that indicates how the Meeting object has changed. Area: Meetings Canonical name: PidLidChangeHighlight Alternate names: dispidChangeHighlight

### CHANGE_KEY {#CHANGE-KEY}
```
public static final PidTagPropertyDescriptor CHANGE_KEY
```


Contains a structure that identifies the last change to the object. Area: History Properties Canonical name: PidTagChangeKey Alternate names: PR\_CHANGE\_KEY

### CHANGE_NOTIFICATION_GUID {#CHANGE-NOTIFICATION-GUID}
```
public static final PidTagPropertyDescriptor CHANGE_NOTIFICATION_GUID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CHANGE\_NOTIFICATION\_GUID

### CHANGE_NUMBER {#CHANGE-NUMBER}
```
public static final PidTagPropertyDescriptor CHANGE_NUMBER
```


Contains a structure that identifies the last change to the message or folder that is currently being synchronized. Area: Sync Canonical name: PidTagChangeNumber Alternate names: ptagCn

### CHARACTER_COUNT {#CHARACTER-COUNT}
```
public static final PidNamePropertyDescriptor CHARACTER_COUNT
```


Specifies the character count of the file attached to the Document object. Area: Common Canonical name: PidNameCharacterCount Alternate names: urn:schemas-microsoft-com:office:office\#Characters

### CHILDRENS_NAMES {#CHILDRENS-NAMES}
```
public static final PidTagPropertyDescriptor CHILDRENS_NAMES
```


Specifies the names of the children of the contact. Area: Contact Properties Canonical name: PidTagChildrensNames Alternate names: PR\_CHILDRENS\_NAMES, PR\_CHILDRENS\_NAMES\_A, PR\_CHILDRENS\_NAMES\_W,

### CLASSIFICATION {#CLASSIFICATION}
```
public static final PidLidPropertyDescriptor CLASSIFICATION
```


Contains a list of the classification categories to which the associated Message object has been assigned. Area: General Message Properties Canonical name: PidLidClassification Alternate names: dispidClassification

### CLASSIFICATION_DESCRIPTION {#CLASSIFICATION-DESCRIPTION}
```
public static final PidLidPropertyDescriptor CLASSIFICATION_DESCRIPTION
```


Contains a human-readable summary of each of the classification categories included in the PidLidClassification property (section 2.53). Area: General Message Properties Canonical name: PidLidClassificationDescription Alternate names: dispidClassDesc

### CLASSIFICATION_GUID {#CLASSIFICATION-GUID}
```
public static final PidLidPropertyDescriptor CLASSIFICATION_GUID
```


Contains the GUID that identifies the list of email classification categories used by a Message object. Area: General Message Properties Canonical name: PidLidClassificationGuid Alternate names: dispidClassGuid

### CLASSIFICATION_KEEP {#CLASSIFICATION-KEEP}
```
public static final PidLidPropertyDescriptor CLASSIFICATION_KEEP
```


Indicates whether the message uses any classification categories. Area: General Message Properties Canonical name: PidLidClassificationKeep Alternate names: dispidClassKeep

### CLASSIFIED {#CLASSIFIED}
```
public static final PidLidPropertyDescriptor CLASSIFIED
```


Indicates whether the contents of this message are regarded as classified information. Area: General Message Properties Canonical name: PidLidClassified Alternate names: dispidClassified

### CLEAN_GLOBAL_OBJECT_ID {#CLEAN-GLOBAL-OBJECT-ID}
```
public static final PidLidPropertyDescriptor CLEAN_GLOBAL_OBJECT_ID
```


Contains the value of the PidLidGlobalObjectId property (section 2.142) for an object all zero. Area: Meetings Canonical name: PidLidCleanGlobalObjectId Alternate names: dispidCleanGlobalObjId

### CLIENT_ACTIONS {#CLIENT-ACTIONS}
```
public static final PidTagPropertyDescriptor CLIENT_ACTIONS
```


Specifies the actions the client is required to take on the message. Area: Server-side Rules Properties Canonical name: PidTagClientActions Alternate names: PR\_CLIENT\_ACTIONS, ptagClientActions

### CLIENT_INTENT {#CLIENT-INTENT}
```
public static final PidLidPropertyDescriptor CLIENT_INTENT
```


Indicates what actions the user has taken on this Meeting object. Area: Calendar Canonical name: PidLidClientIntent Alternate names: dispidClientIntent

### CLIENT_SUBMIT_TIME {#CLIENT-SUBMIT-TIME}
```
public static final PidTagPropertyDescriptor CLIENT_SUBMIT_TIME
```


Contains the current time, in UTC, when the email message is submitted. Area: Message Time Properties Canonical name: PidTagClientSubmitTime Alternate names: PR\_CLIENT\_SUBMIT\_TIME, urn:schemas:httpmail:date,

### CLIP_END {#CLIP-END}
```
public static final PidLidPropertyDescriptor CLIP_END
```


Specifies the end date and time of the event in UTC. Area: Calendar Canonical name: PidLidClipEnd Alternate names: dispidClipEnd

### CLIP_START {#CLIP-START}
```
public static final PidLidPropertyDescriptor CLIP_START
```


Specifies the start date and time of the event in UTC. Area: Calendar Canonical name: PidLidClipStart Alternate names: dispidClipStart

### CODE_PAGE_ID {#CODE-PAGE-ID}
```
public static final PidTagPropertyDescriptor CODE_PAGE_ID
```


Contains the identifier for the client code page used for Unicode to double-byte character set (DBCS) string conversion. Area: Exchange Profile Configuration Canonical name: PidTagCodePageId Alternate names: PR\_CODE\_PAGE\_ID, ptagCodePageId

### COLLABORATE_DOC {#COLLABORATE-DOC}
```
public static final PidLidPropertyDescriptor COLLABORATE_DOC
```


Specifies the document to be launched when the user joins the meeting. Area: Conferencing Canonical name: PidLidCollaborateDoc Alternate names: dispidCollaborateDoc

### COLLECTOR {#COLLECTOR}
```
public static final PidTagPropertyDescriptor COLLECTOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_COLLECTOR

### COMMENT {#COMMENT}
```
public static final PidTagPropertyDescriptor COMMENT
```


Contains a comment about the purpose or content of the Address Book object. Area: Common Canonical name: PidTagComment Alternate names: PR\_COMMENT, PR\_COMMENT\_A, ptagComment, PR\_COMMENT\_W, DAV:comment,

### COMMENTS {#COMMENTS}
```
public static final PidNamePropertyDescriptor COMMENTS
```


Specifies the comments of the file attached to the Document object. Area: Common Canonical name: PidNameComments Alternate names: urn:schemas-microsoft-com:office:office\#Comments

### COMMON_END {#COMMON-END}
```
public static final PidLidPropertyDescriptor COMMON_END
```


Indicates the end time for the Message object. Area: General Message Properties Canonical name: PidLidCommonEnd Alternate names: dispidCommonEnd

### COMMON_START {#COMMON-START}
```
public static final PidLidPropertyDescriptor COMMON_START
```


Indicates the start time for the Message object. Area: General Message Properties Canonical name: PidLidCommonStart Alternate names: dispidCommonStart

### COMMON_VIEWS_ENTRYID {#COMMON-VIEWS-ENTRYID}
```
public static final PidTagPropertyDescriptor COMMON_VIEWS_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_COMMON\_VIEWS\_ENTRYID

### COMPANIES {#COMPANIES}
```
public static final PidLidPropertyDescriptor COMPANIES
```


Contains a list of company names, each of which is associated with a contact that is specified in the PidLidContacts property ([MS-OXCMSG] section 2.2.1.57.2). Area: General Message Properties Canonical name: PidLidCompanies Alternate names: dispidCompanies, http://schemas.microsoft.com/exchange/companies

### COMPANY {#COMPANY}
```
public static final PidNamePropertyDescriptor COMPANY
```


Specifies the company for which the file was created. Area: Common Canonical name: PidNameCompany Alternate names: urn:schemas-microsoft-com:office:office\#Company

### COMPANY_MAIN_TELEPHONE_NUMBER {#COMPANY-MAIN-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor COMPANY_MAIN_TELEPHONE_NUMBER
```


Contains the main telephone number of the mail user's company. Area: Contact Properties Canonical name: PidTagCompanyMainTelephoneNumber Alternate names: PR\_COMPANY\_MAIN\_PHONE\_NUMBER, PR\_COMPANY\_MAIN\_PHONE\_NUMBER\_A,

### COMPANY_NAME {#COMPANY-NAME}
```
public static final PidTagPropertyDescriptor COMPANY_NAME
```


Contains the mail user's company name. Area: Contact Properties Canonical name: PidTagCompanyName Alternate names: PR\_COMPANY\_NAME, PR\_COMPANY\_NAME\_A, PR\_COMPANY\_NAME\_W,

### COMPUTER_NETWORK_NAME {#COMPUTER-NETWORK-NAME}
```
public static final PidTagPropertyDescriptor COMPUTER_NETWORK_NAME
```


Contains the name of the mail user's computer network. Area: Contact Properties Canonical name: PidTagComputerNetworkName Alternate names: PR\_COMPUTER\_NETWORK\_NAME, PR\_COMPUTER\_NETWORK\_NAME\_A,

### CONFERENCING_CHECK {#CONFERENCING-CHECK}
```
public static final PidLidPropertyDescriptor CONFERENCING_CHECK
```


Area: Conferencing Canonical name: PidLidConferencingCheck Alternate names: dispidConfCheck

### CONFERENCING_TYPE {#CONFERENCING-TYPE}
```
public static final PidLidPropertyDescriptor CONFERENCING_TYPE
```


Specifies the type of the meeting. Area: Conferencing Canonical name: PidLidConferencingType Alternate names: dispidConfType

### CONFLICT_ENTRY_ID {#CONFLICT-ENTRY-ID}
```
public static final PidTagPropertyDescriptor CONFLICT_ENTRY_ID
```


Contains the EntryID of the conflict resolve message. Area: ICS Canonical name: PidTagConflictEntryId Alternate names: PR\_CONFLICT\_ENTRYID, ptagConflictEntryId

### CONTACTS {#CONTACTS}
```
public static final PidLidPropertyDescriptor CONTACTS
```


Contains the PidTagDisplayName property (section 2.667) of each Address Book EntryID referenced in the value of the PidLidContactLinkEntry property (section 2.70). Area: General Message Properties Canonical name: PidLidContacts Alternate names: dispidContacts

### CONTACT_ADDRTYPES {#CONTACT-ADDRTYPES}
```
public static final PidTagPropertyDescriptor CONTACT_ADDRTYPES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTACT\_ADDRTYPES

### CONTACT_CHARACTER_SET {#CONTACT-CHARACTER-SET}
```
public static final PidLidPropertyDescriptor CONTACT_CHARACTER_SET
```


Specifies the character set used for a Contact object. Area: Contact Properties Canonical name: PidLidContactCharacterSet Alternate names: dispidContactCharSet

### CONTACT_COUNT {#CONTACT-COUNT}
```
public static final PidTagPropertyDescriptor CONTACT_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTACT\_COUNT

### CONTACT_DEFAULT_ADDRESS_INDEX {#CONTACT-DEFAULT-ADDRESS-INDEX}
```
public static final PidTagPropertyDescriptor CONTACT_DEFAULT_ADDRESS_INDEX
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTACT\_DEFAULT\_ADDRESS\_INDEX

### CONTACT_EMAIL_ADDRESSES {#CONTACT-EMAIL-ADDRESSES}
```
public static final PidTagPropertyDescriptor CONTACT_EMAIL_ADDRESSES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTACT\_EMAIL\_ADDRESSES

### CONTACT_ENTRYIDS {#CONTACT-ENTRYIDS}
```
public static final PidTagPropertyDescriptor CONTACT_ENTRYIDS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTACT\_ENTRYIDS

### CONTACT_ITEM_DATA {#CONTACT-ITEM-DATA}
```
public static final PidLidPropertyDescriptor CONTACT_ITEM_DATA
```


Specifies the visible fields in the application's user interface that are used to help display the contact information. Area: Contact Properties Canonical name: PidLidContactItemData Alternate names: dispidContactItemData

### CONTACT_LINKED_GLOBAL_ADDRESS_LIST_ENTRY_ID {#CONTACT-LINKED-GLOBAL-ADDRESS-LIST-ENTRY-ID}
```
public static final PidLidPropertyDescriptor CONTACT_LINKED_GLOBAL_ADDRESS_LIST_ENTRY_ID
```


Specifies the EntryID of the GAL contact to which the duplicate contact is linked. Area: Contact Properties Canonical name: PidLidContactLinkedGlobalAddressListEntryId Alternate names: dispidContactLinkedGALEntryID

### CONTACT_LINK_ENTRY {#CONTACT-LINK-ENTRY}
```
public static final PidLidPropertyDescriptor CONTACT_LINK_ENTRY
```


Contains the elements of the PidLidContacts property (section 2.77). Area: Contact Properties Canonical name: PidLidContactLinkEntry Alternate names: dispidContactLinkEntry

### CONTACT_LINK_GLOBAL_ADDRESS_LIST_LINK_ID {#CONTACT-LINK-GLOBAL-ADDRESS-LIST-LINK-ID}
```
public static final PidLidPropertyDescriptor CONTACT_LINK_GLOBAL_ADDRESS_LIST_LINK_ID
```


Specifies the GUID of the GAL contact to which the duplicate contact is linked. Area: Contact Properties Canonical name: PidLidContactLinkGlobalAddressListLinkId Alternate names: dispidContactLinkGALLinkID

### CONTACT_LINK_GLOBAL_ADDRESS_LIST_LINK_STATE {#CONTACT-LINK-GLOBAL-ADDRESS-LIST-LINK-STATE}
```
public static final PidLidPropertyDescriptor CONTACT_LINK_GLOBAL_ADDRESS_LIST_LINK_STATE
```


Specifies the state of the linking between the GAL contact and the duplicate contact. Area: Contact Properties Canonical name: PidLidContactLinkGlobalAddressListLinkState Alternate names: dispidContactLinkGALLinkState

### CONTACT_LINK_LINK_REJECT_HISTORY {#CONTACT-LINK-LINK-REJECT-HISTORY}
```
public static final PidLidPropertyDescriptor CONTACT_LINK_LINK_REJECT_HISTORY
```


Contains a list of GAL contacts that were previously rejected for linking with the duplicate contact. Area: Contact Properties Canonical name: PidLidContactLinkLinkRejectHistory Alternate names: dispidContactLinkLinkRejectHistory

### CONTACT_LINK_NAME {#CONTACT-LINK-NAME}
```
public static final PidLidPropertyDescriptor CONTACT_LINK_NAME
```


Area: Contact Properties Canonical name: PidLidContactLinkName Alternate names: dispidContactLinkName

### CONTACT_LINK_SEARCH_KEY {#CONTACT-LINK-SEARCH-KEY}
```
public static final PidLidPropertyDescriptor CONTACT_LINK_SEARCH_KEY
```


Contains the list of SearchKeys for a Contact object linked to by the Message object. Area: Contact Properties Canonical name: PidLidContactLinkSearchKey Alternate names: dispidContactLinkSearchKey

### CONTACT_LINK_SMTP_ADDRESS_CACHE {#CONTACT-LINK-SMTP-ADDRESS-CACHE}
```
public static final PidLidPropertyDescriptor CONTACT_LINK_SMTP_ADDRESS_CACHE
```


Contains a list of the SMTP addresses that are used by the contact. Area: Contact Properties Canonical name: PidLidContactLinkSMTPAddressCache Alternate names: dispidContactLinkSMTPAddressCache

### CONTACT_USER_FIELD_1 {#CONTACT-USER-FIELD-1}
```
public static final PidLidPropertyDescriptor CONTACT_USER_FIELD_1
```


Contains text used to add custom text to a business card representation of a Contact object. Area: Contact Properties Canonical name: PidLidContactUserField1 Alternate names: dispidContactUserField1

### CONTACT_USER_FIELD_2 {#CONTACT-USER-FIELD-2}
```
public static final PidLidPropertyDescriptor CONTACT_USER_FIELD_2
```


Contains text used to add custom text to a business card representation of a Contact object. Area: Contact Properties Canonical name: PidLidContactUserField2 Alternate names: dispidContactUserField2

### CONTACT_USER_FIELD_3 {#CONTACT-USER-FIELD-3}
```
public static final PidLidPropertyDescriptor CONTACT_USER_FIELD_3
```


Contains text used to add custom text to a business card representation of a Contact object. Area: Contact Properties Canonical name: PidLidContactUserField3 Alternate names: dispidContactUserField3

### CONTACT_USER_FIELD_4 {#CONTACT-USER-FIELD-4}
```
public static final PidLidPropertyDescriptor CONTACT_USER_FIELD_4
```


Contains text used to add custom text to a business card representation of a Contact object. Area: Contact Properties Canonical name: PidLidContactUserField4 Alternate names: dispidContactUserField4

### CONTACT_VERSION {#CONTACT-VERSION}
```
public static final PidTagPropertyDescriptor CONTACT_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTACT\_VERSION

### CONTAINER_CLASS {#CONTAINER-CLASS}
```
public static final PidTagPropertyDescriptor CONTAINER_CLASS
```


Contains a string value that describes the type of Message object that a folder contains. Area: Container Properties Canonical name: PidTagContainerClass Alternate names: PR\_CONTAINER\_CLASS, PR\_CONTAINER\_CLASS\_A, ptagContainerClass, PR\_CONTAINER\_CLASS\_W,

### CONTAINER_CONTENTS {#CONTAINER-CONTENTS}
```
public static final PidTagPropertyDescriptor CONTAINER_CONTENTS
```


Always empty. An NSPI server defines this value for distribution lists and it is not present for other objects. Area: Container Properties Canonical name: PidTagContainerContents Alternate names: PR\_CONTAINER\_CONTENTS, ptagContainerContents

### CONTAINER_FLAGS {#CONTAINER-FLAGS}
```
public static final PidTagPropertyDescriptor CONTAINER_FLAGS
```


Contains a bitmask of flags that describe capabilities of an address book container. Area: Address Book Canonical name: PidTagContainerFlags Alternate names: PR\_CONTAINER\_FLAGS

### CONTAINER_HIERARCHY {#CONTAINER-HIERARCHY}
```
public static final PidTagPropertyDescriptor CONTAINER_HIERARCHY
```


Identifies all of the subfolders of the current folder. Area: Container Properties Canonical name: PidTagContainerHierarchy Alternate names: PR\_CONTAINER\_HIERARCHY, ptagContainerHierarchy

### CONTAINER_MODIFY_VERSION {#CONTAINER-MODIFY-VERSION}
```
public static final PidTagPropertyDescriptor CONTAINER_MODIFY_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTAINER\_MODIFY\_VERSION

### CONTENTS_SORT_ORDER {#CONTENTS-SORT-ORDER}
```
public static final PidTagPropertyDescriptor CONTENTS_SORT_ORDER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTENTS\_SORT\_ORDER

### CONTENTS_SYNCHRONIZER {#CONTENTS-SYNCHRONIZER}
```
public static final PidTagPropertyDescriptor CONTENTS_SYNCHRONIZER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTENTS\_SYNCHRONIZER

### CONTENT_BASE {#CONTENT-BASE}
```
public static final PidNamePropertyDescriptor CONTENT_BASE
```


Specifies the value of the MIME Content-Base header, which defines the base URI for resolving relative URLs contained within the message body. Area: Email Canonical name: PidNameContentBase Alternate names: BodyContentBase

### CONTENT_CLASS {#CONTENT-CLASS}
```
public static final PidNamePropertyDescriptor CONTENT_CLASS
```


Contains a string that identifies the type of content of a Message object. Area: Email Canonical name: PidNameContentClass Alternate names: DAV:contentclass, urn:schemas:mailheader:content-class

### CONTENT_CONFIDENTIALITY_ALGORITHM_ID {#CONTENT-CONFIDENTIALITY-ALGORITHM-ID}
```
public static final PidTagPropertyDescriptor CONTENT_CONFIDENTIALITY_ALGORITHM_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTENT\_CONFIDENTIALITY\_ALGORITHM\_ID

### CONTENT_CORRELATOR {#CONTENT-CORRELATOR}
```
public static final PidTagPropertyDescriptor CONTENT_CORRELATOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTENT\_CORRELATOR

### CONTENT_COUNT {#CONTENT-COUNT}
```
public static final PidTagPropertyDescriptor CONTENT_COUNT
```


Specifies the number of rows under the header row. Area: Folder Properties Canonical name: PidTagContentCount Alternate names: PR\_CONTENT\_COUNT, ptagContentCount, DAV:visiblecount

### CONTENT_FILTER_SPAM_CONFIDENCE_LEVEL {#CONTENT-FILTER-SPAM-CONFIDENCE-LEVEL}
```
public static final PidTagPropertyDescriptor CONTENT_FILTER_SPAM_CONFIDENCE_LEVEL
```


Indicates a confidence level that the message is spam. Area: Secure Messaging Properties Canonical name: PidTagContentFilterSpamConfidenceLevel Alternate names: PR\_CONTENT\_FILTER\_SCL, ptagContentFilterSCL

### CONTENT_IDENTIFIER {#CONTENT-IDENTIFIER}
```
public static final PidTagPropertyDescriptor CONTENT_IDENTIFIER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTENT\_IDENTIFIER

### CONTENT_INTEGRITY_CHECK {#CONTENT-INTEGRITY-CHECK}
```
public static final PidTagPropertyDescriptor CONTENT_INTEGRITY_CHECK
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTENT\_INTEGRITY\_CHECK

### CONTENT_LENGTH {#CONTENT-LENGTH}
```
public static final PidTagPropertyDescriptor CONTENT_LENGTH
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTENT\_LENGTH

### CONTENT_RETURN_REQUESTED {#CONTENT-RETURN-REQUESTED}
```
public static final PidTagPropertyDescriptor CONTENT_RETURN_REQUESTED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTENT\_RETURN\_REQUESTED

### CONTENT_SEARCH_KEY {#CONTENT-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor CONTENT_SEARCH_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTENT\_SEARCH\_KEY

### CONTENT_TYPE {#CONTENT-TYPE}
```
public static final PidNamePropertyDescriptor CONTENT_TYPE
```


Specifies the type of the body part content. Area: Email Canonical name: PidNameContentType Alternate names: urn:schemas:mailheader:content-type

### CONTENT_UNREAD_COUNT {#CONTENT-UNREAD-COUNT}
```
public static final PidTagPropertyDescriptor CONTENT_UNREAD_COUNT
```


Specifies the number of rows under the header row that have the PidTagRead property (section 2.869) set to FALSE. Area: Folder Properties Canonical name: PidTagContentUnreadCount Alternate names: PR\_CONTENT\_UNREAD, ptagContentUnread, urn:schemas:httpmail:unreadcount

### CONTROL_FLAGS {#CONTROL-FLAGS}
```
public static final PidTagPropertyDescriptor CONTROL_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTROL\_FLAGS

### CONTROL_ID {#CONTROL-ID}
```
public static final PidTagPropertyDescriptor CONTROL_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTROL\_ID

### CONTROL_STRUCTURE {#CONTROL-STRUCTURE}
```
public static final PidTagPropertyDescriptor CONTROL_STRUCTURE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTROL\_STRUCTURE

### CONTROL_TYPE {#CONTROL-TYPE}
```
public static final PidTagPropertyDescriptor CONTROL_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONTROL\_TYPE

### CONVERSATION_ACTION_LAST_APPLIED_TIME {#CONVERSATION-ACTION-LAST-APPLIED-TIME}
```
public static final PidLidPropertyDescriptor CONVERSATION_ACTION_LAST_APPLIED_TIME
```


Contains the time, in UTC, that an Email object was last received in the conversation, or the last time that the user modified the conversation action, whichever occurs later. Area: Conversation Actions Canonical name: PidLidConversationActionLastAppliedTime Alternate names: dispidConvActionLastAppliedTime

### CONVERSATION_ACTION_MAX_DELIVERY_TIME {#CONVERSATION-ACTION-MAX-DELIVERY-TIME}
```
public static final PidLidPropertyDescriptor CONVERSATION_ACTION_MAX_DELIVERY_TIME
```


Contains the maximum value of the PidTagMessageDeliveryTime property (section conversation action on the client. Area: Conversation Actions Canonical name: PidLidConversationActionMaxDeliveryTime Alternate names: dispidConvActionMaxDeliveryTime

### CONVERSATION_ACTION_MOVE_FOLDER_EID {#CONVERSATION-ACTION-MOVE-FOLDER-EID}
```
public static final PidLidPropertyDescriptor CONVERSATION_ACTION_MOVE_FOLDER_EID
```


Contains the EntryID for the destination folder. Area: Conversation Actions Canonical name: PidLidConversationActionMoveFolderEid Alternate names: dispidConvActionMoveFolderEid

### CONVERSATION_ACTION_MOVE_STORE_EID {#CONVERSATION-ACTION-MOVE-STORE-EID}
```
public static final PidLidPropertyDescriptor CONVERSATION_ACTION_MOVE_STORE_EID
```


Contains the EntryID for a move to a folder in a different message store. Area: Conversation Actions Canonical name: PidLidConversationActionMoveStoreEid Alternate names: dispidConvActionMoveStoreEid

### CONVERSATION_ACTION_VERSION {#CONVERSATION-ACTION-VERSION}
```
public static final PidLidPropertyDescriptor CONVERSATION_ACTION_VERSION
```


Contains the version of the conversation action FAI message. Area: Conversation Actions Canonical name: PidLidConversationActionVersion Alternate names: dispidConvActionVersion

### CONVERSATION_ID {#CONVERSATION-ID}
```
public static final PidTagPropertyDescriptor CONVERSATION_ID
```


Contains a computed value derived from other conversation-related properties. Area: Conversations Canonical name: PidTagConversationId Alternate names: PR\_CONVERSATION\_ID

### CONVERSATION_INDEX {#CONVERSATION-INDEX}
```
public static final PidTagPropertyDescriptor CONVERSATION_INDEX
```


Indicates the relative position of this message within a conversation thread. Area: General Message Properties Canonical name: PidTagConversationIndex Alternate names: PR\_CONVERSATION\_INDEX, ptagConversationIndex

### CONVERSATION_INDEX_TRACKING {#CONVERSATION-INDEX-TRACKING}
```
public static final PidTagPropertyDescriptor CONVERSATION_INDEX_TRACKING
```


Indicates whether the GUID portion of the PidTagConversationIndex property (section 2.641) is to be used to compute the PidTagConversationId property (section 2.640). Area: Conversations Canonical name: PidTagConversationIndexTracking Alternate names: PR\_CONVERSATION\_INDEX\_TRACKING

### CONVERSATION_KEY {#CONVERSATION-KEY}
```
public static final PidTagPropertyDescriptor CONVERSATION_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONVERSATION\_KEY

### CONVERSATION_PROCESSED {#CONVERSATION-PROCESSED}
```
public static final PidLidPropertyDescriptor CONVERSATION_PROCESSED
```


Specifies a sequential number to be used in the processing of a conversation action. Area: Conversation Actions Canonical name: PidLidConversationProcessed Alternate names: dispidConvExLegacyProcessedRand

### CONVERSATION_TOPIC {#CONVERSATION-TOPIC}
```
public static final PidTagPropertyDescriptor CONVERSATION_TOPIC
```


Contains an unchanging copy of the original subject. Area: General Message Properties Canonical name: PidTagConversationTopic Alternate names: PR\_CONVERSATION\_TOPIC, PR\_CONVERSATION\_TOPIC\_A,

### CONVERSION_EITS {#CONVERSION-EITS}
```
public static final PidTagPropertyDescriptor CONVERSION_EITS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONVERSION\_EITS

### CONVERSION_PROHIBITED {#CONVERSION-PROHIBITED}
```
public static final PidTagPropertyDescriptor CONVERSION_PROHIBITED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONVERSION\_PROHIBITED

### CONVERSION_WITH_LOSS_PROHIBITED {#CONVERSION-WITH-LOSS-PROHIBITED}
```
public static final PidTagPropertyDescriptor CONVERSION_WITH_LOSS_PROHIBITED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONVERSION\_WITH\_LOSS\_PROHIBITED

### CONVERTED_EITS {#CONVERTED-EITS}
```
public static final PidTagPropertyDescriptor CONVERTED_EITS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CONVERTED\_EITS

### CORRELATE {#CORRELATE}
```
public static final PidTagPropertyDescriptor CORRELATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CORRELATE

### CORRELATE_MTSID {#CORRELATE-MTSID}
```
public static final PidTagPropertyDescriptor CORRELATE_MTSID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CORRELATE\_MTSID

### COUNTRY {#COUNTRY}
```
public static final PidTagPropertyDescriptor COUNTRY
```


Contains the name of the mail user's country/region. Area: Contact Properties Canonical name: PidTagCountry Alternate names: PR\_COUNTRY, PR\_COUNTRY\_A, PR\_COUNTRY\_W, PR\_BUSINESS\_ADDRESS\_COUNTRY, PR\_BUSINESS\_ADDRESS\_COUNTRY\_A,

### CREATE_DATE_TIME_READ_ONLY {#CREATE-DATE-TIME-READ-ONLY}
```
public static final PidNamePropertyDescriptor CREATE_DATE_TIME_READ_ONLY
```


Specifies the time, in UTC, that the file was first created. Area: Common Canonical name: PidNameCreateDateTimeReadOnly Alternate names: urn:schemas-microsoft-com:office:office\#Created

### CREATE_TEMPLATES {#CREATE-TEMPLATES}
```
public static final PidTagPropertyDescriptor CREATE_TEMPLATES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CREATE\_TEMPLATES

### CREATION_TIME {#CREATION-TIME}
```
public static final PidTagPropertyDescriptor CREATION_TIME
```


Contains the time, in UTC, that the object was created. Area: Message Time Properties Canonical name: PidTagCreationTime Alternate names: PR\_CREATION\_TIME, ptagCreationTime, DAV:creationdate

### CREATION_VERSION {#CREATION-VERSION}
```
public static final PidTagPropertyDescriptor CREATION_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CREATION\_VERSION

### CREATOR_ENTRY_ID {#CREATOR-ENTRY-ID}
```
public static final PidTagPropertyDescriptor CREATOR_ENTRY_ID
```


Specifies the original author of the message according to their Address Book EntryID. Area: ID Properties Canonical name: PidTagCreatorEntryId Alternate names: PR\_CREATOR\_ENTRYID, ptagCreatorEntryId

### CREATOR_NAME {#CREATOR-NAME}
```
public static final PidTagPropertyDescriptor CREATOR_NAME
```


Contains the name of the creator of a Message object. Area: General Message Properties Canonical name: PidTagCreatorName Alternate names: PR\_CREATOR\_NAME, PR\_CREATOR\_NAME\_A, ptagCreatorName, PR\_CREATOR\_NAME\_W

### CROSS_REFERENCE {#CROSS-REFERENCE}
```
public static final PidNamePropertyDescriptor CROSS_REFERENCE
```


Contains the name of the host (with domains omitted) and a white-space-separated list of colon-separated pairs of newsgroup names and message numbers. Area: Email Canonical name: PidNameCrossReference Alternate names: urn:schemas:mailheader:xref

### CURRENT_VERSION {#CURRENT-VERSION}
```
public static final PidLidPropertyDescriptor CURRENT_VERSION
```


Specifies the build number of the client application that sent the message. Area: General Message Properties Canonical name: PidLidCurrentVersion Alternate names: dispidCurrentVersion

### CURRENT_VERSION_NAME {#CURRENT-VERSION-NAME}
```
public static final PidLidPropertyDescriptor CURRENT_VERSION_NAME
```


Specifies the name of the client application that sent the message. Area: General Message Properties Canonical name: PidLidCurrentVersionName Alternate names: dispidCurrentVersionName

### CUSTOMER_ID {#CUSTOMER-ID}
```
public static final PidTagPropertyDescriptor CUSTOMER_ID
```


Contains the mail user's customer identification number. Area: Contact Properties Canonical name: PidTagCustomerId Alternate names: PR\_CUSTOMER\_ID, PR\_CUSTOMER\_ID\_A, PR\_CUSTOMER\_ID\_W,

### DAM_BACK_PATCHED {#DAM-BACK-PATCHED}
```
public static final PidTagPropertyDescriptor DAM_BACK_PATCHED
```


Indicates whether the Deferred Action Message (DAM) was updated by the server. Area: Server-side Rules Properties Canonical name: PidTagDamBackPatched Alternate names: PR\_DAM\_BACK\_PATCHED, ptagDamBackPatched

### DAM_ORIGINAL_ENTRY_ID {#DAM-ORIGINAL-ENTRY-ID}
```
public static final PidTagPropertyDescriptor DAM_ORIGINAL_ENTRY_ID
```


Contains the EntryID of the delivered message that the client has to process. Area: Server-side Rules Properties Canonical name: PidTagDamOriginalEntryId Alternate names: PR\_DAM\_ORIGINAL\_ENTRYID

### DAV_ID {#DAV-ID}
```
public static final PidNamePropertyDescriptor DAV_ID
```


Specifies a unique ID for the calendar item. Area: Common Canonical name: PidNameDavId Alternate names: DAV:id

### DAV_IS_COLLECTION {#DAV-IS-COLLECTION}
```
public static final PidNamePropertyDescriptor DAV_IS_COLLECTION
```


Indicates whether a Calendar object is a collection. Area: Common Canonical name: PidNameDavIsCollection Alternate names: DAV:iscollection

### DAV_IS_STRUCTURED_DOCUMENT {#DAV-IS-STRUCTURED-DOCUMENT}
```
public static final PidNamePropertyDescriptor DAV_IS_STRUCTURED_DOCUMENT
```


Indicates whether a Calendar object is a structured document. Area: Common Canonical name: PidNameDavIsStructuredDocument Alternate names: DAV:isstructureddocument

### DAV_PARENT_NAME {#DAV-PARENT-NAME}
```
public static final PidNamePropertyDescriptor DAV_PARENT_NAME
```


Specifies the name of the Folder object that contains the Calendar object. Area: Common Canonical name: PidNameDavParentName Alternate names: DAV:parentname

### DAV_UID {#DAV-UID}
```
public static final PidNamePropertyDescriptor DAV_UID
```


Specifies the unique identifier for an item. Area: Common Canonical name: PidNameDavUid Alternate names: DAV:uid

### DAY_INTERVAL {#DAY-INTERVAL}
```
public static final PidLidPropertyDescriptor DAY_INTERVAL
```


Identifies the day interval for the recurrence pattern. Area: Meetings Canonical name: PidLidDayInterval Alternate names: LID\_DAY\_INTERVAL

### DAY_OF_MONTH {#DAY-OF-MONTH}
```
public static final PidLidPropertyDescriptor DAY_OF_MONTH
```


Identifies the day of the month for the appointment or meeting. Area: Calendar Canonical name: PidLidDayOfMonth Alternate names:

### DEFAULT_POST_MESSAGE_CLASS {#DEFAULT-POST-MESSAGE-CLASS}
```
public static final PidTagPropertyDescriptor DEFAULT_POST_MESSAGE_CLASS
```


Contains the message class of the object. Area: MapiContainer Canonical name: PidTagDefaultPostMessageClass Alternate names: PR\_DEF\_POST\_MSGCLASS

### DEFAULT_PROFILE {#DEFAULT-PROFILE}
```
public static final PidTagPropertyDescriptor DEFAULT_PROFILE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DEFAULT\_PROFILE

### DEFAULT_STORE {#DEFAULT-STORE}
```
public static final PidTagPropertyDescriptor DEFAULT_STORE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DEFAULT\_STORE

### DEFAULT_VIEW_ENTRYID {#DEFAULT-VIEW-ENTRYID}
```
public static final PidTagPropertyDescriptor DEFAULT_VIEW_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DEFAULT\_VIEW\_ENTRYID

### DEFERRED_ACTION_MESSAGE_ORIGINAL_ENTRY_ID {#DEFERRED-ACTION-MESSAGE-ORIGINAL-ENTRY-ID}
```
public static final PidTagPropertyDescriptor DEFERRED_ACTION_MESSAGE_ORIGINAL_ENTRY_ID
```


Contains the server EntryID for the DAM. Area: Server-side Rules Properties Canonical name: PidTagDeferredActionMessageOriginalEntryId Alternate names: PR\_DAM\_ORIG\_MSG\_SVREID, ptagDamOrgMsgSvrEID

### DEFERRED_DELIVERY_TIME {#DEFERRED-DELIVERY-TIME}
```
public static final PidTagPropertyDescriptor DEFERRED_DELIVERY_TIME
```


Contains the date and time, in UTC, at which the sender prefers that the message be delivered. Area: MapiEnvelope Canonical name: PidTagDeferredDeliveryTime Alternate names: PR\_DEFERRED\_DELIVERY\_TIME, ptagDeferredDeliveryTime,

### DEFERRED_SEND_NUMBER {#DEFERRED-SEND-NUMBER}
```
public static final PidTagPropertyDescriptor DEFERRED_SEND_NUMBER
```


Contains a number used in the calculation of how long to defer sending a message. Area: MapiStatus Canonical name: PidTagDeferredSendNumber Alternate names: PR\_DEFERRED\_SEND\_NUMBER

### DEFERRED_SEND_TIME {#DEFERRED-SEND-TIME}
```
public static final PidTagPropertyDescriptor DEFERRED_SEND_TIME
```


Contains the amount of time after which a client would like to defer sending the message. Area: MapiStatus Canonical name: PidTagDeferredSendTime Alternate names: PR\_DEFERRED\_SEND\_TIME, ptagDeferredSendTime

### DEFERRED_SEND_UNITS {#DEFERRED-SEND-UNITS}
```
public static final PidTagPropertyDescriptor DEFERRED_SEND_UNITS
```


Specifies the unit of time used as a multiplier with the PidTagDeferredSendNumber property (section 2.654) value. Area: MapiStatus Canonical name: PidTagDeferredSendUnits Alternate names: PR\_DEFERRED\_SEND\_UNITS

### DEF_CREATE_DL {#DEF-CREATE-DL}
```
public static final PidTagPropertyDescriptor DEF_CREATE_DL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DEF\_CREATE\_DL

### DEF_CREATE_MAILUSER {#DEF-CREATE-MAILUSER}
```
public static final PidTagPropertyDescriptor DEF_CREATE_MAILUSER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DEF\_CREATE\_MAILUSER

### DELEGATED_BY_RULE {#DELEGATED-BY-RULE}
```
public static final PidTagPropertyDescriptor DELEGATED_BY_RULE
```


Specifies whether the message was forwarded due to the triggering of a delegate forward rule. Area: MapiStatus Canonical name: PidTagDelegatedByRule Alternate names: PR\_DELEGATED\_BY\_RULE

### DELEGATE_FLAGS {#DELEGATE-FLAGS}
```
public static final PidTagPropertyDescriptor DELEGATE_FLAGS
```


Indicates whether delegates can view Message objects that are marked as private. Area: MessageClassDefinedTransmittable Canonical name: PidTagDelegateFlags Alternate names: PR\_DELEGATE\_FLAGS, ptagDelegateFlags

### DELEGATE_MAIL {#DELEGATE-MAIL}
```
public static final PidLidPropertyDescriptor DELEGATE_MAIL
```


Indicates whether a delegate responded to the meeting request. Area: Meetings Canonical name: PidLidDelegateMail Alternate names: LID\_DELEGATE\_MAIL

### DELEGATION {#DELEGATION}
```
public static final PidTagPropertyDescriptor DELEGATION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DELEGATION

### DELETED_ASSOC_MESSAGE_SIZE_EXTENDED {#DELETED-ASSOC-MESSAGE-SIZE-EXTENDED}
```
public static final PidTagPropertyDescriptor DELETED_ASSOC_MESSAGE_SIZE_EXTENDED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DELETED\_ASSOC\_MESSAGE\_SIZE\_EXTENDED

### DELETED_ASSOC_MSG_COUNT {#DELETED-ASSOC-MSG-COUNT}
```
public static final PidTagPropertyDescriptor DELETED_ASSOC_MSG_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DELETED\_ASSOC\_MSG\_COUNT

### DELETED_COUNT_TOTAL {#DELETED-COUNT-TOTAL}
```
public static final PidTagPropertyDescriptor DELETED_COUNT_TOTAL
```


Contains the total count of messages that have been deleted from a folder, excluding messages deleted within subfolders. Area: Server Canonical name: PidTagDeletedCountTotal Alternate names: PR\_DELETED\_COUNT\_TOTAL, ptagDeleteCountTotal

### DELETED_FOLDER_COUNT {#DELETED-FOLDER-COUNT}
```
public static final PidTagPropertyDescriptor DELETED_FOLDER_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DELETED\_FOLDER\_COUNT

### DELETED_MESSAGE_SIZE_EXTENDED {#DELETED-MESSAGE-SIZE-EXTENDED}
```
public static final PidTagPropertyDescriptor DELETED_MESSAGE_SIZE_EXTENDED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DELETED\_MESSAGE\_SIZE\_EXTENDED

### DELETED_MSG_COUNT {#DELETED-MSG-COUNT}
```
public static final PidTagPropertyDescriptor DELETED_MSG_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DELETED\_MSG\_COUNT

### DELETED_NORMAL_MESSAGE_SIZE_EXTENDED {#DELETED-NORMAL-MESSAGE-SIZE-EXTENDED}
```
public static final PidTagPropertyDescriptor DELETED_NORMAL_MESSAGE_SIZE_EXTENDED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DELETED\_NORMAL\_MESSAGE\_SIZE\_EXTENDED

### DELETED_ON {#DELETED-ON}
```
public static final PidTagPropertyDescriptor DELETED_ON
```


Specifies the time, in UTC, when the item or folder was soft deleted. Area: ExchangeFolder Canonical name: PidTagDeletedOn Alternate names: PR\_DELETED\_ON, ptagDeletedOn, urn:schemas:httpmail:deletedon

### DELETE_AFTER_SUBMIT {#DELETE-AFTER-SUBMIT}
```
public static final PidTagPropertyDescriptor DELETE_AFTER_SUBMIT
```


Indicates that the original message is to be deleted after it is sent. Area: MapiNonTransmittable Canonical name: PidTagDeleteAfterSubmit Alternate names: PR\_DELETE\_AFTER\_SUBMIT, ptagDeleteAfterSubmit

### DELIVERY_POINT {#DELIVERY-POINT}
```
public static final PidTagPropertyDescriptor DELIVERY_POINT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DELIVERY\_POINT

### DELIVER_TIME {#DELIVER-TIME}
```
public static final PidTagPropertyDescriptor DELIVER_TIME
```


Contains the delivery time for a delivery status notification, as specified [RFC3464], or a message disposition notification, as specified in [RFC3798]. Area: Email Canonical name: PidTagDeliverTime Alternate names: PR\_DELIVER\_TIME, ptagDeliverTime

### DELTAX {#DELTAX}
```
public static final PidTagPropertyDescriptor DELTAX
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DELTAX

### DELTAY {#DELTAY}
```
public static final PidTagPropertyDescriptor DELTAY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DELTAY

### DEPARTMENT {#DEPARTMENT}
```
public static final PidLidPropertyDescriptor DEPARTMENT
```


This property is ignored by the server and is set to an empty string by the client. Area: Contact Properties Canonical name: PidLidDepartment Alternate names: dispidDepartment

### DEPARTMENT_NAME {#DEPARTMENT-NAME}
```
public static final PidTagPropertyDescriptor DEPARTMENT_NAME
```


Contains a name for the department in which the mail user works. Area: MapiMailUser Canonical name: PidTagDepartmentName Alternate names: PR\_DEPARTMENT\_NAME, PR\_DEPARTMENT\_NAME\_A, PR\_DEPARTMENT\_NAME\_W,

### DEPTH {#DEPTH}
```
public static final PidTagPropertyDescriptor DEPTH
```


Specifies the number of nested categories in which a given row is contained. Area: MapiCommon Canonical name: PidTagDepth Alternate names: PR\_DEPTH, ptagDepth

### DESIGN_IN_PROGRESS {#DESIGN-IN-PROGRESS}
```
public static final PidTagPropertyDescriptor DESIGN_IN_PROGRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DESIGN\_IN\_PROGRESS

### DETAILS_TABLE {#DETAILS-TABLE}
```
public static final PidTagPropertyDescriptor DETAILS_TABLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DETAILS\_TABLE

### DIRECTORY {#DIRECTORY}
```
public static final PidLidPropertyDescriptor DIRECTORY
```


Specifies the directory server to be used. Area: Conferencing Canonical name: PidLidDirectory Alternate names: dispidDirectory

### DISABLE_FULL_FIDELITY {#DISABLE-FULL-FIDELITY}
```
public static final PidTagPropertyDescriptor DISABLE_FULL_FIDELITY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DISABLE\_FULL\_FIDELITY

### DISABLE_WINSOCK {#DISABLE-WINSOCK}
```
public static final PidTagPropertyDescriptor DISABLE_WINSOCK
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DISABLE\_WINSOCK

### DISCARD_REASON {#DISCARD-REASON}
```
public static final PidTagPropertyDescriptor DISCARD_REASON
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DISCARD\_REASON

### DISCLOSE_RECIPIENTS {#DISCLOSE-RECIPIENTS}
```
public static final PidTagPropertyDescriptor DISCLOSE_RECIPIENTS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DISCLOSE\_RECIPIENTS

### DISCLOSURE_OF_RECIPIENTS {#DISCLOSURE-OF-RECIPIENTS}
```
public static final PidTagPropertyDescriptor DISCLOSURE_OF_RECIPIENTS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DISCLOSURE\_OF\_RECIPIENTS

### DISCRETE_VALUES {#DISCRETE-VALUES}
```
public static final PidTagPropertyDescriptor DISCRETE_VALUES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DISCRETE\_VALUES

### DISC_VAL {#DISC-VAL}
```
public static final PidTagPropertyDescriptor DISC_VAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DISC\_VAL

### DISPLAY_BCC {#DISPLAY-BCC}
```
public static final PidTagPropertyDescriptor DISPLAY_BCC
```


Contains a list of blind carbon copy (Bcc) recipient display names. Area: Message Properties Canonical name: PidTagDisplayBcc Alternate names: PR\_DISPLAY\_BCC, PR\_DISPLAY\_BCC\_A, ptagDisplayBcc, PR\_DISPLAY\_BCC\_W,

### DISPLAY_CC {#DISPLAY-CC}
```
public static final PidTagPropertyDescriptor DISPLAY_CC
```


Contains a list of carbon copy (Cc) recipient display names. Area: Message Properties Canonical name: PidTagDisplayCc Alternate names: PR\_DISPLAY\_CC, PR\_DISPLAY\_CC\_A, ptagDisplayCc, PR\_DISPLAY\_CC\_W,

### DISPLAY_NAME {#DISPLAY-NAME}
```
public static final PidTagPropertyDescriptor DISPLAY_NAME
```


Contains the display name of the folder. Area: MapiCommon Canonical name: PidTagDisplayName Alternate names: PR\_DISPLAY\_NAME, PR\_DISPLAY\_NAME\_A, ptagDisplayName,

### DISPLAY_NAME_PREFIX {#DISPLAY-NAME-PREFIX}
```
public static final PidTagPropertyDescriptor DISPLAY_NAME_PREFIX
```


Contains the mail user's honorific title. Area: MapiMailUser Canonical name: PidTagDisplayNamePrefix Alternate names: PR\_DISPLAY\_NAME\_PREFIX, PR\_DISPLAY\_NAME\_PREFIX\_A,

### DISPLAY_TO {#DISPLAY-TO}
```
public static final PidTagPropertyDescriptor DISPLAY_TO
```


Contains a list of the primary recipient display names, separated by semicolons, when an email message has primary recipients . Area: Message Properties Canonical name: PidTagDisplayTo Alternate names: PR\_DISPLAY\_TO, PR\_DISPLAY\_TO\_A, ptagDisplayTo, PR\_DISPLAY\_TO\_W

### DISPLAY_TYPE {#DISPLAY-TYPE}
```
public static final PidTagPropertyDescriptor DISPLAY_TYPE
```


Contains an integer value that indicates how to display an Address Book object in a table or as an addressee on a message. Area: MapiAddressBook Canonical name: PidTagDisplayType Alternate names: PR\_DISPLAY\_TYPE, ptagDisplayType

### DISPLAY_TYPE_EX {#DISPLAY-TYPE-EX}
```
public static final PidTagPropertyDescriptor DISPLAY_TYPE_EX
```


Contains an integer value that indicates how to display an Address Book object in a table or as a recipient on a message. Area: MapiAddressBook Canonical name: PidTagDisplayTypeEx Alternate names: PR\_DISPLAY\_TYPE\_EX

### DISTRIBUTION_LIST_CHECKSUM {#DISTRIBUTION-LIST-CHECKSUM}
```
public static final PidLidPropertyDescriptor DISTRIBUTION_LIST_CHECKSUM
```


Specifies the 32-bit cyclic redundancy check (CRC) polynomial checksum, as property (section 2.96). Area: Contact Properties Canonical name: PidLidDistributionListChecksum Alternate names: dispidDLChecksum

### DISTRIBUTION_LIST_MEMBERS {#DISTRIBUTION-LIST-MEMBERS}
```
public static final PidLidPropertyDescriptor DISTRIBUTION_LIST_MEMBERS
```


Specifies the list of EntryIDs of the objects corresponding to the members of the personal distribution list. Area: Contact Properties Canonical name: PidLidDistributionListMembers Alternate names: dispidDLMembers

### DISTRIBUTION_LIST_NAME {#DISTRIBUTION-LIST-NAME}
```
public static final PidLidPropertyDescriptor DISTRIBUTION_LIST_NAME
```


Specifies the name of the personal distribution list. Area: Contact Properties Canonical name: PidLidDistributionListName Alternate names: dispidDLName

### DISTRIBUTION_LIST_ONE_OFF_MEMBERS {#DISTRIBUTION-LIST-ONE-OFF-MEMBERS}
```
public static final PidLidPropertyDescriptor DISTRIBUTION_LIST_ONE_OFF_MEMBERS
```


Specifies the list of one-off EntryIDs corresponding to the members of the personal distribution list. Area: Contact Properties Canonical name: PidLidDistributionListOneOffMembers Alternate names: dispidDLOneOffMembers

### DISTRIBUTION_LIST_STREAM {#DISTRIBUTION-LIST-STREAM}
```
public static final PidLidPropertyDescriptor DISTRIBUTION_LIST_STREAM
```


Specifies the list of EntryIDs and one-off EntryIDs corresponding to the members of the personal distribution list. Area: Contact Properties Canonical name: PidLidDistributionListStream Alternate names: dispidDLStream

### DL_EXPANSION_HISTORY {#DL-EXPANSION-HISTORY}
```
public static final PidTagPropertyDescriptor DL_EXPANSION_HISTORY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DL\_EXPANSION\_HISTORY

### DL_EXPANSION_PROHIBITED {#DL-EXPANSION-PROHIBITED}
```
public static final PidTagPropertyDescriptor DL_EXPANSION_PROHIBITED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DL\_EXPANSION\_PROHIBITED

### DL_REPORT_FLAGS {#DL-REPORT-FLAGS}
```
public static final PidTagPropertyDescriptor DL_REPORT_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_DL\_REPORT\_FLAGS

### DOCUMENT_PARTS {#DOCUMENT-PARTS}
```
public static final PidNamePropertyDescriptor DOCUMENT_PARTS
```


Specifies the title of each part of the document. Area: Common Canonical name: PidNameDocumentParts Alternate names: urn:schemas-microsoft-com:office:office\#PartTitles

### EDIT_TIME {#EDIT-TIME}
```
public static final PidNamePropertyDescriptor EDIT_TIME
```


Specifies the time that the file was last edited. Area: Common Canonical name: PidNameEditTime Alternate names: urn:schemas-microsoft-com:office:office\#TotalTime

### EFORMS_FOR_LOCALE_ENTRYID {#EFORMS-FOR-LOCALE-ENTRYID}
```
public static final PidTagPropertyDescriptor EFORMS_FOR_LOCALE_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EFORMS\_FOR\_LOCALE\_ENTRYID

### EFORMS_LOCALE_ID {#EFORMS-LOCALE-ID}
```
public static final PidTagPropertyDescriptor EFORMS_LOCALE_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EFORMS\_LOCALE\_ID

### EFORMS_REGISTRY_ENTRYID {#EFORMS-REGISTRY-ENTRYID}
```
public static final PidTagPropertyDescriptor EFORMS_REGISTRY_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EFORMS\_REGISTRY\_ENTRYID

### EMAIL_1_ADDRESS_TYPE {#EMAIL-1-ADDRESS-TYPE}
```
public static final PidLidPropertyDescriptor EMAIL_1_ADDRESS_TYPE
```


Specifies the address type of an electronic address. Area: Contact Properties Canonical name: PidLidEmail1AddressType Alternate names: dispidEmail1AddrType

### EMAIL_1_DISPLAY_NAME {#EMAIL-1-DISPLAY-NAME}
```
public static final PidLidPropertyDescriptor EMAIL_1_DISPLAY_NAME
```


Specifies the user-readable display name for the email address. Area: Contact Properties Canonical name: PidLidEmail1DisplayName Alternate names: dispidEmail1DisplayName

### EMAIL_1_EMAIL_ADDRESS {#EMAIL-1-EMAIL-ADDRESS}
```
public static final PidLidPropertyDescriptor EMAIL_1_EMAIL_ADDRESS
```


Specifies the email address of the contact. Area: Contact Properties Canonical name: PidLidEmail1EmailAddress Alternate names: dispidEmail1EmailAddress

### EMAIL_1_ORIGINAL_DISPLAY_NAME {#EMAIL-1-ORIGINAL-DISPLAY-NAME}
```
public static final PidLidPropertyDescriptor EMAIL_1_ORIGINAL_DISPLAY_NAME
```


Specifies the SMTP email address that corresponds to the email address for the Contact object. Area: Contact Properties Canonical name: PidLidEmail1OriginalDisplayName Alternate names: dispidEmail1OriginalDisplayName, Email1OriginalDisplayName, EXSCHEMA\_MAPI\_EMAIL1ORIGINALDISPLAYNAME

### EMAIL_1_ORIGINAL_ENTRY_ID {#EMAIL-1-ORIGINAL-ENTRY-ID}
```
public static final PidLidPropertyDescriptor EMAIL_1_ORIGINAL_ENTRY_ID
```


Specifies the EntryID of the object corresponding to this electronic address. Area: Contact Properties Canonical name: PidLidEmail1OriginalEntryId Alternate names: dispidEmail1OriginalEntryID

### EMAIL_2_ADDRESS_TYPE {#EMAIL-2-ADDRESS-TYPE}
```
public static final PidLidPropertyDescriptor EMAIL_2_ADDRESS_TYPE
```


Specifies the address type of the electronic address. Area: Contact Properties Canonical name: PidLidEmail2AddressType Alternate names: dispidEmail2AddrType

### EMAIL_2_DISPLAY_NAME {#EMAIL-2-DISPLAY-NAME}
```
public static final PidLidPropertyDescriptor EMAIL_2_DISPLAY_NAME
```


Specifies the user-readable display name for the email address. Area: Contact Properties Canonical name: PidLidEmail2DisplayName Alternate names: dispidEmail2DisplayName

### EMAIL_2_EMAIL_ADDRESS {#EMAIL-2-EMAIL-ADDRESS}
```
public static final PidLidPropertyDescriptor EMAIL_2_EMAIL_ADDRESS
```


Specifies the email address of the contact. Area: Contact Properties Canonical name: PidLidEmail2EmailAddress Alternate names: dispidEmail2EmailAddress

### EMAIL_2_ORIGINAL_DISPLAY_NAME {#EMAIL-2-ORIGINAL-DISPLAY-NAME}
```
public static final PidLidPropertyDescriptor EMAIL_2_ORIGINAL_DISPLAY_NAME
```


Specifies the SMTP email address that corresponds to the email address for the Contact object. Area: Contact Properties Canonical name: PidLidEmail2OriginalDisplayName Alternate names: dispidEmail2OriginalDisplayName

### EMAIL_2_ORIGINAL_ENTRY_ID {#EMAIL-2-ORIGINAL-ENTRY-ID}
```
public static final PidLidPropertyDescriptor EMAIL_2_ORIGINAL_ENTRY_ID
```


Specifies the EntryID of the object that corresponds to this electronic address. Area: Contact Properties Canonical name: PidLidEmail2OriginalEntryId Alternate names: dispidEmail2OriginalEntryID

### EMAIL_3_ADDRESS_TYPE {#EMAIL-3-ADDRESS-TYPE}
```
public static final PidLidPropertyDescriptor EMAIL_3_ADDRESS_TYPE
```


Specifies the address type of the electronic address. Area: Contact Properties Canonical name: PidLidEmail3AddressType Alternate names: dispidEmail3AddrType

### EMAIL_3_DISPLAY_NAME {#EMAIL-3-DISPLAY-NAME}
```
public static final PidLidPropertyDescriptor EMAIL_3_DISPLAY_NAME
```


Specifies the user-readable display name for the email address. Area: Contact Properties Canonical name: PidLidEmail3DisplayName Alternate names: dispidEmail3DisplayName

### EMAIL_3_EMAIL_ADDRESS {#EMAIL-3-EMAIL-ADDRESS}
```
public static final PidLidPropertyDescriptor EMAIL_3_EMAIL_ADDRESS
```


Specifies the email address of the contact. Area: Contact Properties Canonical name: PidLidEmail3EmailAddress Alternate names: dispidEmail3EmailAddress

### EMAIL_3_ORIGINAL_DISPLAY_NAME {#EMAIL-3-ORIGINAL-DISPLAY-NAME}
```
public static final PidLidPropertyDescriptor EMAIL_3_ORIGINAL_DISPLAY_NAME
```


Specifies the SMTP email address that corresponds to the email address for the Contact object. Area: Contact Properties Canonical name: PidLidEmail3OriginalDisplayName Alternate names: dispidEmail3OriginalDisplayName

### EMAIL_3_ORIGINAL_ENTRY_ID {#EMAIL-3-ORIGINAL-ENTRY-ID}
```
public static final PidLidPropertyDescriptor EMAIL_3_ORIGINAL_ENTRY_ID
```


Specifies the EntryID of the object that corresponds to this electronic address. Area: Contact Properties Canonical name: PidLidEmail3OriginalEntryId Alternate names: dispidEmail3OriginalEntryID

### EMAIL_ADDRESS {#EMAIL-ADDRESS}
```
public static final PidTagPropertyDescriptor EMAIL_ADDRESS
```


Contains the email address of a Message object. Area: MapiCommon Canonical name: PidTagEmailAddress Alternate names: PR\_EMAIL\_ADDRESS, PR\_EMAIL\_ADDRESS\_A, PR\_EMAIL\_ADDRESS\_W

### EMS_AB_ACCESS_CATEGORY {#EMS-AB-ACCESS-CATEGORY}
```
public static final PidTagPropertyDescriptor EMS_AB_ACCESS_CATEGORY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ACCESS\_CATEGORY

### EMS_AB_ACTIVATION_SCHEDULE {#EMS-AB-ACTIVATION-SCHEDULE}
```
public static final PidTagPropertyDescriptor EMS_AB_ACTIVATION_SCHEDULE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ACTIVATION\_SCHEDULE

### EMS_AB_ACTIVATION_STYLE {#EMS-AB-ACTIVATION-STYLE}
```
public static final PidTagPropertyDescriptor EMS_AB_ACTIVATION_STYLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ACTIVATION\_STYLE

### EMS_AB_ADDRESS_ENTRY_DISPLAY_TABLE {#EMS-AB-ADDRESS-ENTRY-DISPLAY-TABLE}
```
public static final PidTagPropertyDescriptor EMS_AB_ADDRESS_ENTRY_DISPLAY_TABLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ADDRESS\_ENTRY\_DISPLAY\_TABLE

### EMS_AB_ADDRESS_ENTRY_DISPLAY_TABLE_MSDOS {#EMS-AB-ADDRESS-ENTRY-DISPLAY-TABLE-MSDOS}
```
public static final PidTagPropertyDescriptor EMS_AB_ADDRESS_ENTRY_DISPLAY_TABLE_MSDOS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ADDRESS\_ENTRY\_DISPLAY\_TABLE\_MSDOS

### EMS_AB_ADDRESS_SYNTAX {#EMS-AB-ADDRESS-SYNTAX}
```
public static final PidTagPropertyDescriptor EMS_AB_ADDRESS_SYNTAX
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ADDRESS\_SYNTAX

### EMS_AB_ADDRESS_TYPE {#EMS-AB-ADDRESS-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_ADDRESS_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ADDRESS\_TYPE

### EMS_AB_ADMD {#EMS-AB-ADMD}
```
public static final PidTagPropertyDescriptor EMS_AB_ADMD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ADMD

### EMS_AB_ADMIN_DESCRIPTION {#EMS-AB-ADMIN-DESCRIPTION}
```
public static final PidTagPropertyDescriptor EMS_AB_ADMIN_DESCRIPTION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ADMIN\_DESCRIPTION

### EMS_AB_ADMIN_DISPLAY_NAME {#EMS-AB-ADMIN-DISPLAY-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_ADMIN_DISPLAY_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ADMIN\_DISPLAY\_NAME

### EMS_AB_ADMIN_EXTENSION_DLL {#EMS-AB-ADMIN-EXTENSION-DLL}
```
public static final PidTagPropertyDescriptor EMS_AB_ADMIN_EXTENSION_DLL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ADMIN\_EXTENSION\_DLL

### EMS_AB_ALIASED_OBJECT_NAME {#EMS-AB-ALIASED-OBJECT-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_ALIASED_OBJECT_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ALIASED\_OBJECT\_NAME

### EMS_AB_ALIASED_OBJECT_NAME_O {#EMS-AB-ALIASED-OBJECT-NAME-O}
```
public static final PidTagPropertyDescriptor EMS_AB_ALIASED_OBJECT_NAME_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ALIASED\_OBJECT\_NAME\_O

### EMS_AB_ALT_RECIPIENT {#EMS-AB-ALT-RECIPIENT}
```
public static final PidTagPropertyDescriptor EMS_AB_ALT_RECIPIENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ALT\_RECIPIENT

### EMS_AB_ALT_RECIPIENT_BL {#EMS-AB-ALT-RECIPIENT-BL}
```
public static final PidTagPropertyDescriptor EMS_AB_ALT_RECIPIENT_BL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ALT\_RECIPIENT\_BL

### EMS_AB_ALT_RECIPIENT_BL_O {#EMS-AB-ALT-RECIPIENT-BL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_ALT_RECIPIENT_BL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ALT\_RECIPIENT\_BL\_O

### EMS_AB_ALT_RECIPIENT_O {#EMS-AB-ALT-RECIPIENT-O}
```
public static final PidTagPropertyDescriptor EMS_AB_ALT_RECIPIENT_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ALT\_RECIPIENT\_O

### EMS_AB_ANCESTOR_ID {#EMS-AB-ANCESTOR-ID}
```
public static final PidTagPropertyDescriptor EMS_AB_ANCESTOR_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ANCESTOR\_ID

### EMS_AB_ANONYMOUS_ACCESS {#EMS-AB-ANONYMOUS-ACCESS}
```
public static final PidTagPropertyDescriptor EMS_AB_ANONYMOUS_ACCESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ANONYMOUS\_ACCESS

### EMS_AB_ANONYMOUS_ACCOUNT {#EMS-AB-ANONYMOUS-ACCOUNT}
```
public static final PidTagPropertyDescriptor EMS_AB_ANONYMOUS_ACCOUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ANONYMOUS\_ACCOUNT

### EMS_AB_ASSOCIATION_LIFETIME {#EMS-AB-ASSOCIATION-LIFETIME}
```
public static final PidTagPropertyDescriptor EMS_AB_ASSOCIATION_LIFETIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ASSOCIATION\_LIFETIME

### EMS_AB_ASSOC_NT_ACCOUNT {#EMS-AB-ASSOC-NT-ACCOUNT}
```
public static final PidTagPropertyDescriptor EMS_AB_ASSOC_NT_ACCOUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ASSOC\_NT\_ACCOUNT

### EMS_AB_ASSOC_PROTOCOL_CFG_NNTP {#EMS-AB-ASSOC-PROTOCOL-CFG-NNTP}
```
public static final PidTagPropertyDescriptor EMS_AB_ASSOC_PROTOCOL_CFG_NNTP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ASSOC\_PROTOCOL\_CFG\_NNTP

### EMS_AB_ASSOC_PROTOCOL_CFG_NNTP_O {#EMS-AB-ASSOC-PROTOCOL-CFG-NNTP-O}
```
public static final PidTagPropertyDescriptor EMS_AB_ASSOC_PROTOCOL_CFG_NNTP_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ASSOC\_PROTOCOL\_CFG\_NNTP\_O

### EMS_AB_ASSOC_REMOTE_DXA {#EMS-AB-ASSOC-REMOTE-DXA}
```
public static final PidTagPropertyDescriptor EMS_AB_ASSOC_REMOTE_DXA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ASSOC\_REMOTE\_DXA

### EMS_AB_ASSOC_REMOTE_DXA_O {#EMS-AB-ASSOC-REMOTE-DXA-O}
```
public static final PidTagPropertyDescriptor EMS_AB_ASSOC_REMOTE_DXA_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ASSOC\_REMOTE\_DXA\_O

### EMS_AB_ATTRIBUTE_CERTIFICATE {#EMS-AB-ATTRIBUTE-CERTIFICATE}
```
public static final PidTagPropertyDescriptor EMS_AB_ATTRIBUTE_CERTIFICATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ATTRIBUTE\_CERTIFICATE

### EMS_AB_AUTHENTICATION_TO_USE {#EMS-AB-AUTHENTICATION-TO-USE}
```
public static final PidTagPropertyDescriptor EMS_AB_AUTHENTICATION_TO_USE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AUTHENTICATION\_TO\_USE

### EMS_AB_AUTHORITY_REVOCATION_LIST {#EMS-AB-AUTHORITY-REVOCATION-LIST}
```
public static final PidTagPropertyDescriptor EMS_AB_AUTHORITY_REVOCATION_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AUTHORITY\_REVOCATION\_LIST

### EMS_AB_AUTHORIZED_DOMAIN {#EMS-AB-AUTHORIZED-DOMAIN}
```
public static final PidTagPropertyDescriptor EMS_AB_AUTHORIZED_DOMAIN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AUTHORIZED\_DOMAIN

### EMS_AB_AUTHORIZED_PASSWORD {#EMS-AB-AUTHORIZED-PASSWORD}
```
public static final PidTagPropertyDescriptor EMS_AB_AUTHORIZED_PASSWORD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AUTHORIZED\_PASSWORD

### EMS_AB_AUTHORIZED_PASSWORD_CONFIRM {#EMS-AB-AUTHORIZED-PASSWORD-CONFIRM}
```
public static final PidTagPropertyDescriptor EMS_AB_AUTHORIZED_PASSWORD_CONFIRM
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AUTHORIZED\_PASSWORD\_CONFIRM

### EMS_AB_AUTHORIZED_USER {#EMS-AB-AUTHORIZED-USER}
```
public static final PidTagPropertyDescriptor EMS_AB_AUTHORIZED_USER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AUTHORIZED\_USER

### EMS_AB_AUTH_ORIG_BL {#EMS-AB-AUTH-ORIG-BL}
```
public static final PidTagPropertyDescriptor EMS_AB_AUTH_ORIG_BL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AUTH\_ORIG\_BL

### EMS_AB_AUTH_ORIG_BL_O {#EMS-AB-AUTH-ORIG-BL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_AUTH_ORIG_BL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AUTH\_ORIG\_BL\_O

### EMS_AB_AUTOREPLY {#EMS-AB-AUTOREPLY}
```
public static final PidTagPropertyDescriptor EMS_AB_AUTOREPLY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AUTOREPLY

### EMS_AB_AUTOREPLY_MESSAGE {#EMS-AB-AUTOREPLY-MESSAGE}
```
public static final PidTagPropertyDescriptor EMS_AB_AUTOREPLY_MESSAGE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AUTOREPLY\_MESSAGE

### EMS_AB_AUTOREPLY_SUBJECT {#EMS-AB-AUTOREPLY-SUBJECT}
```
public static final PidTagPropertyDescriptor EMS_AB_AUTOREPLY_SUBJECT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AUTOREPLY\_SUBJECT

### EMS_AB_AVAILABLE_AUTHORIZATION_PACKAGES {#EMS-AB-AVAILABLE-AUTHORIZATION-PACKAGES}
```
public static final PidTagPropertyDescriptor EMS_AB_AVAILABLE_AUTHORIZATION_PACKAGES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AVAILABLE\_AUTHORIZATION\_PACKAGES

### EMS_AB_AVAILABLE_DISTRIBUTIONS {#EMS-AB-AVAILABLE-DISTRIBUTIONS}
```
public static final PidTagPropertyDescriptor EMS_AB_AVAILABLE_DISTRIBUTIONS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_AVAILABLE\_DISTRIBUTIONS

### EMS_AB_BRIDGEHEAD_SERVERS {#EMS-AB-BRIDGEHEAD-SERVERS}
```
public static final PidTagPropertyDescriptor EMS_AB_BRIDGEHEAD_SERVERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_BRIDGEHEAD\_SERVERS

### EMS_AB_BRIDGEHEAD_SERVERS_O {#EMS-AB-BRIDGEHEAD-SERVERS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_BRIDGEHEAD_SERVERS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_BRIDGEHEAD\_SERVERS\_O

### EMS_AB_BUSINESS_CATEGORY {#EMS-AB-BUSINESS-CATEGORY}
```
public static final PidTagPropertyDescriptor EMS_AB_BUSINESS_CATEGORY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_BUSINESS\_CATEGORY

### EMS_AB_BUSINESS_ROLES {#EMS-AB-BUSINESS-ROLES}
```
public static final PidTagPropertyDescriptor EMS_AB_BUSINESS_ROLES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_BUSINESS\_ROLES

### EMS_AB_CAN_CREATE_PF {#EMS-AB-CAN-CREATE-PF}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_CREATE_PF
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_CREATE\_PF

### EMS_AB_CAN_CREATE_PF_BL {#EMS-AB-CAN-CREATE-PF-BL}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_CREATE_PF_BL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_CREATE\_PF\_BL

### EMS_AB_CAN_CREATE_PF_BL_O {#EMS-AB-CAN-CREATE-PF-BL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_CREATE_PF_BL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_CREATE\_PF\_BL\_O

### EMS_AB_CAN_CREATE_PF_DL {#EMS-AB-CAN-CREATE-PF-DL}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_CREATE_PF_DL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_CREATE\_PF\_DL

### EMS_AB_CAN_CREATE_PF_DL_BL {#EMS-AB-CAN-CREATE-PF-DL-BL}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_CREATE_PF_DL_BL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_CREATE\_PF\_DL\_BL

### EMS_AB_CAN_CREATE_PF_DL_BL_O {#EMS-AB-CAN-CREATE-PF-DL-BL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_CREATE_PF_DL_BL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_CREATE\_PF\_DL\_BL\_O

### EMS_AB_CAN_CREATE_PF_DL_O {#EMS-AB-CAN-CREATE-PF-DL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_CREATE_PF_DL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_CREATE\_PF\_DL\_O

### EMS_AB_CAN_CREATE_PF_O {#EMS-AB-CAN-CREATE-PF-O}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_CREATE_PF_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_CREATE\_PF\_O

### EMS_AB_CAN_NOT_CREATE_PF {#EMS-AB-CAN-NOT-CREATE-PF}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_NOT_CREATE_PF
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_NOT\_CREATE\_PF

### EMS_AB_CAN_NOT_CREATE_PF_BL {#EMS-AB-CAN-NOT-CREATE-PF-BL}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_NOT_CREATE_PF_BL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_NOT\_CREATE\_PF\_BL

### EMS_AB_CAN_NOT_CREATE_PF_BL_O {#EMS-AB-CAN-NOT-CREATE-PF-BL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_NOT_CREATE_PF_BL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_NOT\_CREATE\_PF\_BL\_O

### EMS_AB_CAN_NOT_CREATE_PF_DL {#EMS-AB-CAN-NOT-CREATE-PF-DL}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_NOT_CREATE_PF_DL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_NOT\_CREATE\_PF\_DL

### EMS_AB_CAN_NOT_CREATE_PF_DL_BL {#EMS-AB-CAN-NOT-CREATE-PF-DL-BL}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_NOT_CREATE_PF_DL_BL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_NOT\_CREATE\_PF\_DL\_BL

### EMS_AB_CAN_NOT_CREATE_PF_DL_BL_O {#EMS-AB-CAN-NOT-CREATE-PF-DL-BL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_NOT_CREATE_PF_DL_BL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_NOT\_CREATE\_PF\_DL\_BL\_O

### EMS_AB_CAN_NOT_CREATE_PF_DL_O {#EMS-AB-CAN-NOT-CREATE-PF-DL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_NOT_CREATE_PF_DL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_NOT\_CREATE\_PF\_DL\_O

### EMS_AB_CAN_NOT_CREATE_PF_O {#EMS-AB-CAN-NOT-CREATE-PF-O}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_NOT_CREATE_PF_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_NOT\_CREATE\_PF\_O

### EMS_AB_CAN_PRESERVE_DNS {#EMS-AB-CAN-PRESERVE-DNS}
```
public static final PidTagPropertyDescriptor EMS_AB_CAN_PRESERVE_DNS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CAN\_PRESERVE\_DNS

### EMS_AB_CA_CERTIFICATE {#EMS-AB-CA-CERTIFICATE}
```
public static final PidTagPropertyDescriptor EMS_AB_CA_CERTIFICATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CA\_CERTIFICATE

### EMS_AB_CERTIFICATE_CHAIN_V_3 {#EMS-AB-CERTIFICATE-CHAIN-V-3}
```
public static final PidTagPropertyDescriptor EMS_AB_CERTIFICATE_CHAIN_V_3
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CERTIFICATE\_CHAIN\_V3

### EMS_AB_CERTIFICATE_REVOCATION_LIST {#EMS-AB-CERTIFICATE-REVOCATION-LIST}
```
public static final PidTagPropertyDescriptor EMS_AB_CERTIFICATE_REVOCATION_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CERTIFICATE\_REVOCATION\_LIST

### EMS_AB_CERTIFICATE_REVOCATION_LIST_V_1 {#EMS-AB-CERTIFICATE-REVOCATION-LIST-V-1}
```
public static final PidTagPropertyDescriptor EMS_AB_CERTIFICATE_REVOCATION_LIST_V_1
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CERTIFICATE\_REVOCATION\_LIST\_V1

### EMS_AB_CERTIFICATE_REVOCATION_LIST_V_3 {#EMS-AB-CERTIFICATE-REVOCATION-LIST-V-3}
```
public static final PidTagPropertyDescriptor EMS_AB_CERTIFICATE_REVOCATION_LIST_V_3
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CERTIFICATE\_REVOCATION\_LIST\_V3

### EMS_AB_CHARACTER_SET {#EMS-AB-CHARACTER-SET}
```
public static final PidTagPropertyDescriptor EMS_AB_CHARACTER_SET
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CHARACTER\_SET

### EMS_AB_CHARACTER_SET_LIST {#EMS-AB-CHARACTER-SET-LIST}
```
public static final PidTagPropertyDescriptor EMS_AB_CHARACTER_SET_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CHARACTER\_SET\_LIST

### EMS_AB_CHILD_RDNS {#EMS-AB-CHILD-RDNS}
```
public static final PidTagPropertyDescriptor EMS_AB_CHILD_RDNS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CHILD\_RDNS

### EMS_AB_CLIENT_ACCESS_ENABLED {#EMS-AB-CLIENT-ACCESS-ENABLED}
```
public static final PidTagPropertyDescriptor EMS_AB_CLIENT_ACCESS_ENABLED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CLIENT\_ACCESS\_ENABLED

### EMS_AB_CLOCK_ALERT_OFFSET {#EMS-AB-CLOCK-ALERT-OFFSET}
```
public static final PidTagPropertyDescriptor EMS_AB_CLOCK_ALERT_OFFSET
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CLOCK\_ALERT\_OFFSET

### EMS_AB_CLOCK_ALERT_REPAIR {#EMS-AB-CLOCK-ALERT-REPAIR}
```
public static final PidTagPropertyDescriptor EMS_AB_CLOCK_ALERT_REPAIR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CLOCK\_ALERT\_REPAIR

### EMS_AB_CLOCK_WARNING_OFFSET {#EMS-AB-CLOCK-WARNING-OFFSET}
```
public static final PidTagPropertyDescriptor EMS_AB_CLOCK_WARNING_OFFSET
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CLOCK\_WARNING\_OFFSET

### EMS_AB_CLOCK_WARNING_REPAIR {#EMS-AB-CLOCK-WARNING-REPAIR}
```
public static final PidTagPropertyDescriptor EMS_AB_CLOCK_WARNING_REPAIR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CLOCK\_WARNING\_REPAIR

### EMS_AB_COMPROMISED_KEY_LIST {#EMS-AB-COMPROMISED-KEY-LIST}
```
public static final PidTagPropertyDescriptor EMS_AB_COMPROMISED_KEY_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_COMPROMISED\_KEY\_LIST

### EMS_AB_COMPUTER_NAME {#EMS-AB-COMPUTER-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_COMPUTER_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_COMPUTER\_NAME

### EMS_AB_CONNECTED_DOMAINS {#EMS-AB-CONNECTED-DOMAINS}
```
public static final PidTagPropertyDescriptor EMS_AB_CONNECTED_DOMAINS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CONNECTED\_DOMAINS

### EMS_AB_CONNECTION_LIST_FILTER {#EMS-AB-CONNECTION-LIST-FILTER}
```
public static final PidTagPropertyDescriptor EMS_AB_CONNECTION_LIST_FILTER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CONNECTION\_LIST\_FILTER

### EMS_AB_CONNECTION_LIST_FILTER_TYPE {#EMS-AB-CONNECTION-LIST-FILTER-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_CONNECTION_LIST_FILTER_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CONNECTION\_LIST\_FILTER\_TYPE

### EMS_AB_CONNECTION_TYPE {#EMS-AB-CONNECTION-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_CONNECTION_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CONNECTION\_TYPE

### EMS_AB_CONTAINER_INFO {#EMS-AB-CONTAINER-INFO}
```
public static final PidTagPropertyDescriptor EMS_AB_CONTAINER_INFO
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CONTAINER\_INFO

### EMS_AB_CONTENT_TYPE {#EMS-AB-CONTENT-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_CONTENT_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CONTENT\_TYPE

### EMS_AB_CONTROL_MSG_FOLDER_ID {#EMS-AB-CONTROL-MSG-FOLDER-ID}
```
public static final PidTagPropertyDescriptor EMS_AB_CONTROL_MSG_FOLDER_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CONTROL\_MSG\_FOLDER\_ID

### EMS_AB_CONTROL_MSG_RULES {#EMS-AB-CONTROL-MSG-RULES}
```
public static final PidTagPropertyDescriptor EMS_AB_CONTROL_MSG_RULES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CONTROL\_MSG\_RULES

### EMS_AB_COST {#EMS-AB-COST}
```
public static final PidTagPropertyDescriptor EMS_AB_COST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_COST

### EMS_AB_COUNTRY_NAME {#EMS-AB-COUNTRY-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_COUNTRY_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_COUNTRY\_NAME

### EMS_AB_CROSS_CERTIFICATE_CRL {#EMS-AB-CROSS-CERTIFICATE-CRL}
```
public static final PidTagPropertyDescriptor EMS_AB_CROSS_CERTIFICATE_CRL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CROSS\_CERTIFICATE\_CRL

### EMS_AB_CROSS_CERTIFICATE_PAIR {#EMS-AB-CROSS-CERTIFICATE-PAIR}
```
public static final PidTagPropertyDescriptor EMS_AB_CROSS_CERTIFICATE_PAIR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_CROSS\_CERTIFICATE\_PAIR

### EMS_AB_DEFAULT_MESSAGE_FORMAT {#EMS-AB-DEFAULT-MESSAGE-FORMAT}
```
public static final PidTagPropertyDescriptor EMS_AB_DEFAULT_MESSAGE_FORMAT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DEFAULT\_MESSAGE\_FORMAT

### EMS_AB_DELEGATE_USER {#EMS-AB-DELEGATE-USER}
```
public static final PidTagPropertyDescriptor EMS_AB_DELEGATE_USER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DELEGATE\_USER

### EMS_AB_DELIVERY_MECHANISM {#EMS-AB-DELIVERY-MECHANISM}
```
public static final PidTagPropertyDescriptor EMS_AB_DELIVERY_MECHANISM
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DELIVERY\_MECHANISM

### EMS_AB_DELIVER_AND_REDIRECT {#EMS-AB-DELIVER-AND-REDIRECT}
```
public static final PidTagPropertyDescriptor EMS_AB_DELIVER_AND_REDIRECT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DELIVER\_AND\_REDIRECT

### EMS_AB_DELIV_EITS {#EMS-AB-DELIV-EITS}
```
public static final PidTagPropertyDescriptor EMS_AB_DELIV_EITS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DELIV\_EITS

### EMS_AB_DELIV_EXT_CONT_TYPES {#EMS-AB-DELIV-EXT-CONT-TYPES}
```
public static final PidTagPropertyDescriptor EMS_AB_DELIV_EXT_CONT_TYPES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DELIV\_EXT\_CONT\_TYPES

### EMS_AB_DELTA_REVOCATION_LIST {#EMS-AB-DELTA-REVOCATION-LIST}
```
public static final PidTagPropertyDescriptor EMS_AB_DELTA_REVOCATION_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DELTA\_REVOCATION\_LIST

### EMS_AB_DESCRIPTION {#EMS-AB-DESCRIPTION}
```
public static final PidTagPropertyDescriptor EMS_AB_DESCRIPTION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DESCRIPTION

### EMS_AB_DESTINATION_INDICATOR {#EMS-AB-DESTINATION-INDICATOR}
```
public static final PidTagPropertyDescriptor EMS_AB_DESTINATION_INDICATOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DESTINATION\_INDICATOR

### EMS_AB_DIAGNOSTIC_REG_KEY {#EMS-AB-DIAGNOSTIC-REG-KEY}
```
public static final PidTagPropertyDescriptor EMS_AB_DIAGNOSTIC_REG_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DIAGNOSTIC\_REG\_KEY

### EMS_AB_DISABLED_GATEWAY_PROXY {#EMS-AB-DISABLED-GATEWAY-PROXY}
```
public static final PidTagPropertyDescriptor EMS_AB_DISABLED_GATEWAY_PROXY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DISABLED\_GATEWAY\_PROXY

### EMS_AB_DISABLE_DEFERRED_COMMIT {#EMS-AB-DISABLE-DEFERRED-COMMIT}
```
public static final PidTagPropertyDescriptor EMS_AB_DISABLE_DEFERRED_COMMIT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DISABLE\_DEFERRED\_COMMIT

### EMS_AB_DISPLAY_NAME_OVERRIDE {#EMS-AB-DISPLAY-NAME-OVERRIDE}
```
public static final PidTagPropertyDescriptor EMS_AB_DISPLAY_NAME_OVERRIDE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DISPLAY\_NAME\_OVERRIDE

### EMS_AB_DISPLAY_NAME_SUFFIX {#EMS-AB-DISPLAY-NAME-SUFFIX}
```
public static final PidTagPropertyDescriptor EMS_AB_DISPLAY_NAME_SUFFIX
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DISPLAY\_NAME\_SUFFIX

### EMS_AB_DL_MEMBER_RULE {#EMS-AB-DL-MEMBER-RULE}
```
public static final PidTagPropertyDescriptor EMS_AB_DL_MEMBER_RULE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DL\_MEMBER\_RULE

### EMS_AB_DL_MEM_REJECT_PERMS_BL {#EMS-AB-DL-MEM-REJECT-PERMS-BL}
```
public static final PidTagPropertyDescriptor EMS_AB_DL_MEM_REJECT_PERMS_BL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DL\_MEM\_REJECT\_PERMS\_BL

### EMS_AB_DL_MEM_REJECT_PERMS_BL_O {#EMS-AB-DL-MEM-REJECT-PERMS-BL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_DL_MEM_REJECT_PERMS_BL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DL\_MEM\_REJECT\_PERMS\_BL\_O

### EMS_AB_DMD_NAME {#EMS-AB-DMD-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_DMD_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DMD\_NAME

### EMS_AB_DOMAIN_DEF_ALT_RECIP {#EMS-AB-DOMAIN-DEF-ALT-RECIP}
```
public static final PidTagPropertyDescriptor EMS_AB_DOMAIN_DEF_ALT_RECIP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DOMAIN\_DEF\_ALT\_RECIP

### EMS_AB_DOMAIN_DEF_ALT_RECIP_O {#EMS-AB-DOMAIN-DEF-ALT-RECIP-O}
```
public static final PidTagPropertyDescriptor EMS_AB_DOMAIN_DEF_ALT_RECIP_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DOMAIN\_DEF\_ALT\_RECIP\_O

### EMS_AB_DOMAIN_NAME {#EMS-AB-DOMAIN-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_DOMAIN_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DOMAIN\_NAME

### EMS_AB_DO_OAB_VERSION {#EMS-AB-DO-OAB-VERSION}
```
public static final PidTagPropertyDescriptor EMS_AB_DO_OAB_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DO\_OAB\_VERSION

### EMS_AB_DSA_SIGNATURE {#EMS-AB-DSA-SIGNATURE}
```
public static final PidTagPropertyDescriptor EMS_AB_DSA_SIGNATURE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DSA\_SIGNATURE

### EMS_AB_DXA_ADMIN_COPY {#EMS-AB-DXA-ADMIN-COPY}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_ADMIN_COPY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_ADMIN\_COPY

### EMS_AB_DXA_ADMIN_FORWARD {#EMS-AB-DXA-ADMIN-FORWARD}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_ADMIN_FORWARD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_ADMIN\_FORWARD

### EMS_AB_DXA_ADMIN_UPDATE {#EMS-AB-DXA-ADMIN-UPDATE}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_ADMIN_UPDATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_ADMIN\_UPDATE

### EMS_AB_DXA_APPEND_REQCN {#EMS-AB-DXA-APPEND-REQCN}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_APPEND_REQCN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_APPEND\_REQCN

### EMS_AB_DXA_CONF_CONTAINER_LIST {#EMS-AB-DXA-CONF-CONTAINER-LIST}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_CONF_CONTAINER_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_CONF\_CONTAINER\_LIST

### EMS_AB_DXA_CONF_CONTAINER_LIST_O {#EMS-AB-DXA-CONF-CONTAINER-LIST-O}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_CONF_CONTAINER_LIST_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_CONF\_CONTAINER\_LIST\_O

### EMS_AB_DXA_CONF_REQ_TIME {#EMS-AB-DXA-CONF-REQ-TIME}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_CONF_REQ_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_CONF\_REQ\_TIME

### EMS_AB_DXA_CONF_SEQ {#EMS-AB-DXA-CONF-SEQ}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_CONF_SEQ
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_CONF\_SEQ

### EMS_AB_DXA_CONF_SEQ_USN {#EMS-AB-DXA-CONF-SEQ-USN}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_CONF_SEQ_USN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_CONF\_SEQ\_USN

### EMS_AB_DXA_EXCHANGE_OPTIONS {#EMS-AB-DXA-EXCHANGE-OPTIONS}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_EXCHANGE_OPTIONS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_EXCHANGE\_OPTIONS

### EMS_AB_DXA_EXPORT_NOW {#EMS-AB-DXA-EXPORT-NOW}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_EXPORT_NOW
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_EXPORT\_NOW

### EMS_AB_DXA_FLAGS {#EMS-AB-DXA-FLAGS}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_FLAGS

### EMS_AB_DXA_IMPORT_NOW {#EMS-AB-DXA-IMPORT-NOW}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_IMPORT_NOW
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_IMPORT\_NOW

### EMS_AB_DXA_IMP_SEQ {#EMS-AB-DXA-IMP-SEQ}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_IMP_SEQ
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_IMP\_SEQ

### EMS_AB_DXA_IMP_SEQ_TIME {#EMS-AB-DXA-IMP-SEQ-TIME}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_IMP_SEQ_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_IMP\_SEQ\_TIME

### EMS_AB_DXA_IMP_SEQ_USN {#EMS-AB-DXA-IMP-SEQ-USN}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_IMP_SEQ_USN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_IMP\_SEQ\_USN

### EMS_AB_DXA_IN_TEMPLATE_MAP {#EMS-AB-DXA-IN-TEMPLATE-MAP}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_IN_TEMPLATE_MAP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_IN\_TEMPLATE\_MAP

### EMS_AB_DXA_LOCAL_ADMIN {#EMS-AB-DXA-LOCAL-ADMIN}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_LOCAL_ADMIN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_LOCAL\_ADMIN

### EMS_AB_DXA_LOCAL_ADMIN_O {#EMS-AB-DXA-LOCAL-ADMIN-O}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_LOCAL_ADMIN_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_LOCAL\_ADMIN\_O

### EMS_AB_DXA_LOGGING_LEVEL {#EMS-AB-DXA-LOGGING-LEVEL}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_LOGGING_LEVEL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_LOGGING\_LEVEL

### EMS_AB_DXA_NATIVE_ADDRESS_TYPE {#EMS-AB-DXA-NATIVE-ADDRESS-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_NATIVE_ADDRESS_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_NATIVE\_ADDRESS\_TYPE

### EMS_AB_DXA_OUT_TEMPLATE_MAP {#EMS-AB-DXA-OUT-TEMPLATE-MAP}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_OUT_TEMPLATE_MAP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_OUT\_TEMPLATE\_MAP

### EMS_AB_DXA_PASSWORD {#EMS-AB-DXA-PASSWORD}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_PASSWORD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_PASSWORD

### EMS_AB_DXA_PREV_EXCHANGE_OPTIONS {#EMS-AB-DXA-PREV-EXCHANGE-OPTIONS}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_PREV_EXCHANGE_OPTIONS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_PREV\_EXCHANGE\_OPTIONS

### EMS_AB_DXA_PREV_EXPORT_NATIVE_ONLY {#EMS-AB-DXA-PREV-EXPORT-NATIVE-ONLY}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_PREV_EXPORT_NATIVE_ONLY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_PREV\_EXPORT\_NATIVE\_ONLY

### EMS_AB_DXA_PREV_IN_EXCHANGE_SENSITIVITY {#EMS-AB-DXA-PREV-IN-EXCHANGE-SENSITIVITY}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_PREV_IN_EXCHANGE_SENSITIVITY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_PREV\_IN\_EXCHANGE\_SENSITIVITY

### EMS_AB_DXA_PREV_REMOTE_ENTRIES {#EMS-AB-DXA-PREV-REMOTE-ENTRIES}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_PREV_REMOTE_ENTRIES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_PREV\_REMOTE\_ENTRIES

### EMS_AB_DXA_PREV_REMOTE_ENTRIES_O {#EMS-AB-DXA-PREV-REMOTE-ENTRIES-O}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_PREV_REMOTE_ENTRIES_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_PREV\_REMOTE\_ENTRIES\_O

### EMS_AB_DXA_PREV_REPLICATION_SENSITIVITY {#EMS-AB-DXA-PREV-REPLICATION-SENSITIVITY}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_PREV_REPLICATION_SENSITIVITY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_PREV\_REPLICATION\_SENSITIVITY

### EMS_AB_DXA_PREV_TEMPLATE_OPTIONS {#EMS-AB-DXA-PREV-TEMPLATE-OPTIONS}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_PREV_TEMPLATE_OPTIONS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_PREV\_TEMPLATE\_OPTIONS

### EMS_AB_DXA_PREV_TYPES {#EMS-AB-DXA-PREV-TYPES}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_PREV_TYPES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_PREV\_TYPES

### EMS_AB_DXA_RECIPIENT_CP {#EMS-AB-DXA-RECIPIENT-CP}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_RECIPIENT_CP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_RECIPIENT\_CP

### EMS_AB_DXA_REMOTE_CLIENT {#EMS-AB-DXA-REMOTE-CLIENT}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_REMOTE_CLIENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_REMOTE\_CLIENT

### EMS_AB_DXA_REMOTE_CLIENT_O {#EMS-AB-DXA-REMOTE-CLIENT-O}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_REMOTE_CLIENT_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_REMOTE\_CLIENT\_O

### EMS_AB_DXA_REQNAME {#EMS-AB-DXA-REQNAME}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_REQNAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_REQNAME

### EMS_AB_DXA_REQ_SEQ {#EMS-AB-DXA-REQ-SEQ}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_REQ_SEQ
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_REQ\_SEQ

### EMS_AB_DXA_REQ_SEQ_TIME {#EMS-AB-DXA-REQ-SEQ-TIME}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_REQ_SEQ_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_REQ\_SEQ\_TIME

### EMS_AB_DXA_REQ_SEQ_USN {#EMS-AB-DXA-REQ-SEQ-USN}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_REQ_SEQ_USN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_REQ\_SEQ\_USN

### EMS_AB_DXA_SVR_SEQ {#EMS-AB-DXA-SVR-SEQ}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_SVR_SEQ
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_SVR\_SEQ

### EMS_AB_DXA_SVR_SEQ_TIME {#EMS-AB-DXA-SVR-SEQ-TIME}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_SVR_SEQ_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_SVR\_SEQ\_TIME

### EMS_AB_DXA_SVR_SEQ_USN {#EMS-AB-DXA-SVR-SEQ-USN}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_SVR_SEQ_USN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_SVR\_SEQ\_USN

### EMS_AB_DXA_TASK {#EMS-AB-DXA-TASK}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_TASK
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_TASK

### EMS_AB_DXA_TEMPLATE_OPTIONS {#EMS-AB-DXA-TEMPLATE-OPTIONS}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_TEMPLATE_OPTIONS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_TEMPLATE\_OPTIONS

### EMS_AB_DXA_TEMPLATE_TIMESTAMP {#EMS-AB-DXA-TEMPLATE-TIMESTAMP}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_TEMPLATE_TIMESTAMP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_TEMPLATE\_TIMESTAMP

### EMS_AB_DXA_TYPES {#EMS-AB-DXA-TYPES}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_TYPES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_TYPES

### EMS_AB_DXA_UNCONF_CONTAINER_LIST {#EMS-AB-DXA-UNCONF-CONTAINER-LIST}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_UNCONF_CONTAINER_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_UNCONF\_CONTAINER\_LIST

### EMS_AB_DXA_UNCONF_CONTAINER_LIST_O {#EMS-AB-DXA-UNCONF-CONTAINER-LIST-O}
```
public static final PidTagPropertyDescriptor EMS_AB_DXA_UNCONF_CONTAINER_LIST_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_DXA\_UNCONF\_CONTAINER\_LIST\_O

### EMS_AB_EMPLOYEE_NUMBER {#EMS-AB-EMPLOYEE-NUMBER}
```
public static final PidTagPropertyDescriptor EMS_AB_EMPLOYEE_NUMBER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_EMPLOYEE\_NUMBER

### EMS_AB_EMPLOYEE_TYPE {#EMS-AB-EMPLOYEE-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_EMPLOYEE_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_EMPLOYEE\_TYPE

### EMS_AB_ENABLED {#EMS-AB-ENABLED}
```
public static final PidTagPropertyDescriptor EMS_AB_ENABLED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ENABLED

### EMS_AB_ENABLED_AUTHORIZATION_PACKAGES {#EMS-AB-ENABLED-AUTHORIZATION-PACKAGES}
```
public static final PidTagPropertyDescriptor EMS_AB_ENABLED_AUTHORIZATION_PACKAGES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ENABLED\_AUTHORIZATION\_PACKAGES

### EMS_AB_ENABLED_PROTOCOLS {#EMS-AB-ENABLED-PROTOCOLS}
```
public static final PidTagPropertyDescriptor EMS_AB_ENABLED_PROTOCOLS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ENABLED\_PROTOCOLS

### EMS_AB_ENABLED_PROTOCOL_CFG {#EMS-AB-ENABLED-PROTOCOL-CFG}
```
public static final PidTagPropertyDescriptor EMS_AB_ENABLED_PROTOCOL_CFG
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ENABLED\_PROTOCOL\_CFG

### EMS_AB_ENABLE_COMPATIBILITY {#EMS-AB-ENABLE-COMPATIBILITY}
```
public static final PidTagPropertyDescriptor EMS_AB_ENABLE_COMPATIBILITY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ENABLE\_COMPATIBILITY

### EMS_AB_ENCAPSULATION_METHOD {#EMS-AB-ENCAPSULATION-METHOD}
```
public static final PidTagPropertyDescriptor EMS_AB_ENCAPSULATION_METHOD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ENCAPSULATION\_METHOD

### EMS_AB_ENCRYPT {#EMS-AB-ENCRYPT}
```
public static final PidTagPropertyDescriptor EMS_AB_ENCRYPT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ENCRYPT

### EMS_AB_ENCRYPT_ALG_LIST_NA {#EMS-AB-ENCRYPT-ALG-LIST-NA}
```
public static final PidTagPropertyDescriptor EMS_AB_ENCRYPT_ALG_LIST_NA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ENCRYPT\_ALG\_LIST\_NA

### EMS_AB_ENCRYPT_ALG_LIST_OTHER {#EMS-AB-ENCRYPT-ALG-LIST-OTHER}
```
public static final PidTagPropertyDescriptor EMS_AB_ENCRYPT_ALG_LIST_OTHER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ENCRYPT\_ALG\_LIST\_OTHER

### EMS_AB_ENCRYPT_ALG_SELECTED_NA {#EMS-AB-ENCRYPT-ALG-SELECTED-NA}
```
public static final PidTagPropertyDescriptor EMS_AB_ENCRYPT_ALG_SELECTED_NA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ENCRYPT\_ALG\_SELECTED\_NA

### EMS_AB_ENCRYPT_ALG_SELECTED_OTHER {#EMS-AB-ENCRYPT-ALG-SELECTED-OTHER}
```
public static final PidTagPropertyDescriptor EMS_AB_ENCRYPT_ALG_SELECTED_OTHER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ENCRYPT\_ALG\_SELECTED\_OTHER

### EMS_AB_EXPAND_DLS_LOCALLY {#EMS-AB-EXPAND-DLS-LOCALLY}
```
public static final PidTagPropertyDescriptor EMS_AB_EXPAND_DLS_LOCALLY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_EXPAND\_DLS\_LOCALLY

### EMS_AB_EXPIRATION_TIME {#EMS-AB-EXPIRATION-TIME}
```
public static final PidTagPropertyDescriptor EMS_AB_EXPIRATION_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_EXPIRATION\_TIME

### EMS_AB_EXPORT_CONTAINERS {#EMS-AB-EXPORT-CONTAINERS}
```
public static final PidTagPropertyDescriptor EMS_AB_EXPORT_CONTAINERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_EXPORT\_CONTAINERS

### EMS_AB_EXPORT_CONTAINERS_O {#EMS-AB-EXPORT-CONTAINERS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_EXPORT_CONTAINERS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_EXPORT\_CONTAINERS\_O

### EMS_AB_EXPORT_CUSTOM_RECIPIENTS {#EMS-AB-EXPORT-CUSTOM-RECIPIENTS}
```
public static final PidTagPropertyDescriptor EMS_AB_EXPORT_CUSTOM_RECIPIENTS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_EXPORT\_CUSTOM\_RECIPIENTS

### EMS_AB_EXTENDED_CHARS_ALLOWED {#EMS-AB-EXTENDED-CHARS-ALLOWED}
```
public static final PidTagPropertyDescriptor EMS_AB_EXTENDED_CHARS_ALLOWED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_EXTENDED\_CHARS\_ALLOWED

### EMS_AB_EXTENSION_DATA {#EMS-AB-EXTENSION-DATA}
```
public static final PidTagPropertyDescriptor EMS_AB_EXTENSION_DATA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_EXTENSION\_DATA

### EMS_AB_EXTENSION_NAME {#EMS-AB-EXTENSION-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_EXTENSION_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_EXTENSION\_NAME

### EMS_AB_EXTENSION_NAME_INHERITED {#EMS-AB-EXTENSION-NAME-INHERITED}
```
public static final PidTagPropertyDescriptor EMS_AB_EXTENSION_NAME_INHERITED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_EXTENSION\_NAME\_INHERITED

### EMS_AB_FACSIMILE_TELEPHONE_NUMBER {#EMS-AB-FACSIMILE-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor EMS_AB_FACSIMILE_TELEPHONE_NUMBER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_FACSIMILE\_TELEPHONE\_NUMBER

### EMS_AB_FILE_VERSION {#EMS-AB-FILE-VERSION}
```
public static final PidTagPropertyDescriptor EMS_AB_FILE_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_FILE\_VERSION

### EMS_AB_FILTER_LOCAL_ADDRESSES {#EMS-AB-FILTER-LOCAL-ADDRESSES}
```
public static final PidTagPropertyDescriptor EMS_AB_FILTER_LOCAL_ADDRESSES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_FILTER\_LOCAL\_ADDRESSES

### EMS_AB_FOLDERS_CONTAINER {#EMS-AB-FOLDERS-CONTAINER}
```
public static final PidTagPropertyDescriptor EMS_AB_FOLDERS_CONTAINER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_FOLDERS\_CONTAINER

### EMS_AB_FOLDERS_CONTAINER_O {#EMS-AB-FOLDERS-CONTAINER-O}
```
public static final PidTagPropertyDescriptor EMS_AB_FOLDERS_CONTAINER_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_FOLDERS\_CONTAINER\_O

### EMS_AB_FORM_DATA {#EMS-AB-FORM-DATA}
```
public static final PidTagPropertyDescriptor EMS_AB_FORM_DATA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_FORM\_DATA

### EMS_AB_FORWARDING_ADDRESS {#EMS-AB-FORWARDING-ADDRESS}
```
public static final PidTagPropertyDescriptor EMS_AB_FORWARDING_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_FORWARDING\_ADDRESS

### EMS_AB_GARBAGE_COLL_PERIOD {#EMS-AB-GARBAGE-COLL-PERIOD}
```
public static final PidTagPropertyDescriptor EMS_AB_GARBAGE_COLL_PERIOD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GARBAGE\_COLL\_PERIOD

### EMS_AB_GATEWAY_LOCAL_CRED {#EMS-AB-GATEWAY-LOCAL-CRED}
```
public static final PidTagPropertyDescriptor EMS_AB_GATEWAY_LOCAL_CRED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GATEWAY\_LOCAL\_CRED

### EMS_AB_GATEWAY_LOCAL_DESIG {#EMS-AB-GATEWAY-LOCAL-DESIG}
```
public static final PidTagPropertyDescriptor EMS_AB_GATEWAY_LOCAL_DESIG
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GATEWAY\_LOCAL\_DESIG

### EMS_AB_GATEWAY_PROXY {#EMS-AB-GATEWAY-PROXY}
```
public static final PidTagPropertyDescriptor EMS_AB_GATEWAY_PROXY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GATEWAY\_PROXY

### EMS_AB_GATEWAY_ROUTING_TREE {#EMS-AB-GATEWAY-ROUTING-TREE}
```
public static final PidTagPropertyDescriptor EMS_AB_GATEWAY_ROUTING_TREE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GATEWAY\_ROUTING\_TREE

### EMS_AB_GENERATION_QUALIFIER {#EMS-AB-GENERATION-QUALIFIER}
```
public static final PidTagPropertyDescriptor EMS_AB_GENERATION_QUALIFIER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GENERATION\_QUALIFIER

### EMS_AB_GROUP_BY_ATTR_1 {#EMS-AB-GROUP-BY-ATTR-1}
```
public static final PidTagPropertyDescriptor EMS_AB_GROUP_BY_ATTR_1
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GROUP\_BY\_ATTR\_1

### EMS_AB_GROUP_BY_ATTR_2 {#EMS-AB-GROUP-BY-ATTR-2}
```
public static final PidTagPropertyDescriptor EMS_AB_GROUP_BY_ATTR_2
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GROUP\_BY\_ATTR\_2

### EMS_AB_GROUP_BY_ATTR_3 {#EMS-AB-GROUP-BY-ATTR-3}
```
public static final PidTagPropertyDescriptor EMS_AB_GROUP_BY_ATTR_3
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GROUP\_BY\_ATTR\_3

### EMS_AB_GROUP_BY_ATTR_4 {#EMS-AB-GROUP-BY-ATTR-4}
```
public static final PidTagPropertyDescriptor EMS_AB_GROUP_BY_ATTR_4
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GROUP\_BY\_ATTR\_4

### EMS_AB_GROUP_BY_ATTR_VALUE_DN {#EMS-AB-GROUP-BY-ATTR-VALUE-DN}
```
public static final PidTagPropertyDescriptor EMS_AB_GROUP_BY_ATTR_VALUE_DN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GROUP\_BY\_ATTR\_VALUE\_DN

### EMS_AB_GROUP_BY_ATTR_VALUE_DN_O {#EMS-AB-GROUP-BY-ATTR-VALUE-DN-O}
```
public static final PidTagPropertyDescriptor EMS_AB_GROUP_BY_ATTR_VALUE_DN_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GROUP\_BY\_ATTR\_VALUE\_DN\_O

### EMS_AB_GROUP_BY_ATTR_VALUE_STR {#EMS-AB-GROUP-BY-ATTR-VALUE-STR}
```
public static final PidTagPropertyDescriptor EMS_AB_GROUP_BY_ATTR_VALUE_STR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GROUP\_BY\_ATTR\_VALUE\_STR

### EMS_AB_GWART_LAST_MODIFIED {#EMS-AB-GWART-LAST-MODIFIED}
```
public static final PidTagPropertyDescriptor EMS_AB_GWART_LAST_MODIFIED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_GWART\_LAST\_MODIFIED

### EMS_AB_HAS_FULL_REPLICA_NCS {#EMS-AB-HAS-FULL-REPLICA-NCS}
```
public static final PidTagPropertyDescriptor EMS_AB_HAS_FULL_REPLICA_NCS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HAS\_FULL\_REPLICA\_NCS

### EMS_AB_HAS_FULL_REPLICA_NCS_O {#EMS-AB-HAS-FULL-REPLICA-NCS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_HAS_FULL_REPLICA_NCS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HAS\_FULL\_REPLICA\_NCS\_O

### EMS_AB_HAS_MASTER_NCS {#EMS-AB-HAS-MASTER-NCS}
```
public static final PidTagPropertyDescriptor EMS_AB_HAS_MASTER_NCS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HAS\_MASTER\_NCS

### EMS_AB_HAS_MASTER_NCS_O {#EMS-AB-HAS-MASTER-NCS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_HAS_MASTER_NCS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HAS\_MASTER\_NCS\_O

### EMS_AB_HELP_DATA_16 {#EMS-AB-HELP-DATA-16}
```
public static final PidTagPropertyDescriptor EMS_AB_HELP_DATA_16
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HELP\_DATA16

### EMS_AB_HELP_DATA_32 {#EMS-AB-HELP-DATA-32}
```
public static final PidTagPropertyDescriptor EMS_AB_HELP_DATA_32
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HELP\_DATA32

### EMS_AB_HELP_FILE_NAME {#EMS-AB-HELP-FILE-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_HELP_FILE_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HELP\_FILE\_NAME

### EMS_AB_HEURISTICS {#EMS-AB-HEURISTICS}
```
public static final PidTagPropertyDescriptor EMS_AB_HEURISTICS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HEURISTICS

### EMS_AB_HIDE_DL_MEMBERSHIP {#EMS-AB-HIDE-DL-MEMBERSHIP}
```
public static final PidTagPropertyDescriptor EMS_AB_HIDE_DL_MEMBERSHIP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HIDE\_DL\_MEMBERSHIP

### EMS_AB_HIDE_FROM_ADDRESS_BOOK {#EMS-AB-HIDE-FROM-ADDRESS-BOOK}
```
public static final PidTagPropertyDescriptor EMS_AB_HIDE_FROM_ADDRESS_BOOK
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HIDE\_FROM\_ADDRESS\_BOOK

### EMS_AB_HIERARCHY_PATH {#EMS-AB-HIERARCHY-PATH}
```
public static final PidTagPropertyDescriptor EMS_AB_HIERARCHY_PATH
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HIERARCHY\_PATH

### EMS_AB_HOME_MDB_BL {#EMS-AB-HOME-MDB-BL}
```
public static final PidTagPropertyDescriptor EMS_AB_HOME_MDB_BL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HOME\_MDB\_BL

### EMS_AB_HOME_MDB_BL_O {#EMS-AB-HOME-MDB-BL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_HOME_MDB_BL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HOME\_MDB\_BL\_O

### EMS_AB_HOME_MTA {#EMS-AB-HOME-MTA}
```
public static final PidTagPropertyDescriptor EMS_AB_HOME_MTA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HOME\_MTA

### EMS_AB_HOME_MTA_O {#EMS-AB-HOME-MTA-O}
```
public static final PidTagPropertyDescriptor EMS_AB_HOME_MTA_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HOME\_MTA\_O

### EMS_AB_HOME_PUBLIC_SERVER {#EMS-AB-HOME-PUBLIC-SERVER}
```
public static final PidTagPropertyDescriptor EMS_AB_HOME_PUBLIC_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HOME\_PUBLIC\_SERVER

### EMS_AB_HOME_PUBLIC_SERVER_O {#EMS-AB-HOME-PUBLIC-SERVER-O}
```
public static final PidTagPropertyDescriptor EMS_AB_HOME_PUBLIC_SERVER_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HOME\_PUBLIC\_SERVER\_O

### EMS_AB_HOUSE_IDENTIFIER {#EMS-AB-HOUSE-IDENTIFIER}
```
public static final PidTagPropertyDescriptor EMS_AB_HOUSE_IDENTIFIER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HOUSE\_IDENTIFIER

### EMS_AB_HTTP_PUB_AB_ATTRIBUTES {#EMS-AB-HTTP-PUB-AB-ATTRIBUTES}
```
public static final PidTagPropertyDescriptor EMS_AB_HTTP_PUB_AB_ATTRIBUTES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HTTP\_PUB\_AB\_ATTRIBUTES

### EMS_AB_HTTP_PUB_GAL {#EMS-AB-HTTP-PUB-GAL}
```
public static final PidTagPropertyDescriptor EMS_AB_HTTP_PUB_GAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HTTP\_PUB\_GAL

### EMS_AB_HTTP_PUB_GAL_LIMIT {#EMS-AB-HTTP-PUB-GAL-LIMIT}
```
public static final PidTagPropertyDescriptor EMS_AB_HTTP_PUB_GAL_LIMIT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HTTP\_PUB\_GAL\_LIMIT

### EMS_AB_HTTP_PUB_PF {#EMS-AB-HTTP-PUB-PF}
```
public static final PidTagPropertyDescriptor EMS_AB_HTTP_PUB_PF
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HTTP\_PUB\_PF

### EMS_AB_HTTP_SERVERS {#EMS-AB-HTTP-SERVERS}
```
public static final PidTagPropertyDescriptor EMS_AB_HTTP_SERVERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_HTTP\_SERVERS

### EMS_AB_IMPORTED_FROM {#EMS-AB-IMPORTED-FROM}
```
public static final PidTagPropertyDescriptor EMS_AB_IMPORTED_FROM
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_IMPORTED\_FROM

### EMS_AB_IMPORT_CONTAINER {#EMS-AB-IMPORT-CONTAINER}
```
public static final PidTagPropertyDescriptor EMS_AB_IMPORT_CONTAINER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_IMPORT\_CONTAINER

### EMS_AB_IMPORT_CONTAINER_O {#EMS-AB-IMPORT-CONTAINER-O}
```
public static final PidTagPropertyDescriptor EMS_AB_IMPORT_CONTAINER_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_IMPORT\_CONTAINER\_O

### EMS_AB_IMPORT_SENSITIVITY {#EMS-AB-IMPORT-SENSITIVITY}
```
public static final PidTagPropertyDescriptor EMS_AB_IMPORT_SENSITIVITY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_IMPORT\_SENSITIVITY

### EMS_AB_INBOUND_ACCEPT_ALL {#EMS-AB-INBOUND-ACCEPT-ALL}
```
public static final PidTagPropertyDescriptor EMS_AB_INBOUND_ACCEPT_ALL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INBOUND\_ACCEPT\_ALL

### EMS_AB_INBOUND_DN {#EMS-AB-INBOUND-DN}
```
public static final PidTagPropertyDescriptor EMS_AB_INBOUND_DN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INBOUND\_DN

### EMS_AB_INBOUND_DN_O {#EMS-AB-INBOUND-DN-O}
```
public static final PidTagPropertyDescriptor EMS_AB_INBOUND_DN_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INBOUND\_DN\_O

### EMS_AB_INBOUND_HOST {#EMS-AB-INBOUND-HOST}
```
public static final PidTagPropertyDescriptor EMS_AB_INBOUND_HOST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INBOUND\_HOST

### EMS_AB_INBOUND_NEWSFEED {#EMS-AB-INBOUND-NEWSFEED}
```
public static final PidTagPropertyDescriptor EMS_AB_INBOUND_NEWSFEED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INBOUND\_NEWSFEED

### EMS_AB_INBOUND_NEWSFEED_TYPE {#EMS-AB-INBOUND-NEWSFEED-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_INBOUND_NEWSFEED_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INBOUND\_NEWSFEED\_TYPE

### EMS_AB_INBOUND_SITES {#EMS-AB-INBOUND-SITES}
```
public static final PidTagPropertyDescriptor EMS_AB_INBOUND_SITES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INBOUND\_SITES

### EMS_AB_INBOUND_SITES_O {#EMS-AB-INBOUND-SITES-O}
```
public static final PidTagPropertyDescriptor EMS_AB_INBOUND_SITES_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INBOUND\_SITES\_O

### EMS_AB_INCOMING_MSG_SIZE_LIMIT {#EMS-AB-INCOMING-MSG-SIZE-LIMIT}
```
public static final PidTagPropertyDescriptor EMS_AB_INCOMING_MSG_SIZE_LIMIT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INCOMING\_MSG\_SIZE\_LIMIT

### EMS_AB_INCOMING_PASSWORD {#EMS-AB-INCOMING-PASSWORD}
```
public static final PidTagPropertyDescriptor EMS_AB_INCOMING_PASSWORD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INCOMING\_PASSWORD

### EMS_AB_INSADMIN {#EMS-AB-INSADMIN}
```
public static final PidTagPropertyDescriptor EMS_AB_INSADMIN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INSADMIN

### EMS_AB_INSADMIN_O {#EMS-AB-INSADMIN-O}
```
public static final PidTagPropertyDescriptor EMS_AB_INSADMIN_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INSADMIN\_O

### EMS_AB_INSTANCE_TYPE {#EMS-AB-INSTANCE-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_INSTANCE_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INSTANCE\_TYPE

### EMS_AB_INTERNATIONAL_ISDN_NUMBER {#EMS-AB-INTERNATIONAL-ISDN-NUMBER}
```
public static final PidTagPropertyDescriptor EMS_AB_INTERNATIONAL_ISDN_NUMBER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INTERNATIONAL\_ISDN\_NUMBER

### EMS_AB_INVOCATION_ID {#EMS-AB-INVOCATION-ID}
```
public static final PidTagPropertyDescriptor EMS_AB_INVOCATION_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_INVOCATION\_ID

### EMS_AB_IS_DELETED {#EMS-AB-IS-DELETED}
```
public static final PidTagPropertyDescriptor EMS_AB_IS_DELETED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_IS\_DELETED

### EMS_AB_IS_SINGLE_VALUED {#EMS-AB-IS-SINGLE-VALUED}
```
public static final PidTagPropertyDescriptor EMS_AB_IS_SINGLE_VALUED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_IS\_SINGLE\_VALUED

### EMS_AB_KCC_STATUS {#EMS-AB-KCC-STATUS}
```
public static final PidTagPropertyDescriptor EMS_AB_KCC_STATUS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_KCC\_STATUS

### EMS_AB_KM_SERVER {#EMS-AB-KM-SERVER}
```
public static final PidTagPropertyDescriptor EMS_AB_KM_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_KM\_SERVER

### EMS_AB_KM_SERVER_O {#EMS-AB-KM-SERVER-O}
```
public static final PidTagPropertyDescriptor EMS_AB_KM_SERVER_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_KM\_SERVER\_O

### EMS_AB_KNOWLEDGE_INFORMATION {#EMS-AB-KNOWLEDGE-INFORMATION}
```
public static final PidTagPropertyDescriptor EMS_AB_KNOWLEDGE_INFORMATION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_KNOWLEDGE\_INFORMATION

### EMS_AB_LABELEDURI {#EMS-AB-LABELEDURI}
```
public static final PidTagPropertyDescriptor EMS_AB_LABELEDURI
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LABELEDURI

### EMS_AB_LANGUAGE {#EMS-AB-LANGUAGE}
```
public static final PidTagPropertyDescriptor EMS_AB_LANGUAGE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LANGUAGE

### EMS_AB_LANGUAGE_ISO_639 {#EMS-AB-LANGUAGE-ISO-639}
```
public static final PidTagPropertyDescriptor EMS_AB_LANGUAGE_ISO_639
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LANGUAGE\_ISO639

### EMS_AB_LDAP_DISPLAY_NAME {#EMS-AB-LDAP-DISPLAY-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_LDAP_DISPLAY_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LDAP\_DISPLAY\_NAME

### EMS_AB_LDAP_SEARCH_CFG {#EMS-AB-LDAP-SEARCH-CFG}
```
public static final PidTagPropertyDescriptor EMS_AB_LDAP_SEARCH_CFG
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LDAP\_SEARCH\_CFG

### EMS_AB_LINE_WRAP {#EMS-AB-LINE-WRAP}
```
public static final PidTagPropertyDescriptor EMS_AB_LINE_WRAP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LINE\_WRAP

### EMS_AB_LINK_ID {#EMS-AB-LINK-ID}
```
public static final PidTagPropertyDescriptor EMS_AB_LINK_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LINK\_ID

### EMS_AB_LIST_PUBLIC_FOLDERS {#EMS-AB-LIST-PUBLIC-FOLDERS}
```
public static final PidTagPropertyDescriptor EMS_AB_LIST_PUBLIC_FOLDERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LIST\_PUBLIC\_FOLDERS

### EMS_AB_LOCAL_BRIDGE_HEAD {#EMS-AB-LOCAL-BRIDGE-HEAD}
```
public static final PidTagPropertyDescriptor EMS_AB_LOCAL_BRIDGE_HEAD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LOCAL\_BRIDGE\_HEAD

### EMS_AB_LOCAL_BRIDGE_HEAD_ADDRESS {#EMS-AB-LOCAL-BRIDGE-HEAD-ADDRESS}
```
public static final PidTagPropertyDescriptor EMS_AB_LOCAL_BRIDGE_HEAD_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LOCAL\_BRIDGE\_HEAD\_ADDRESS

### EMS_AB_LOCAL_INITIAL_TURN {#EMS-AB-LOCAL-INITIAL-TURN}
```
public static final PidTagPropertyDescriptor EMS_AB_LOCAL_INITIAL_TURN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LOCAL\_INITIAL\_TURN

### EMS_AB_LOCAL_SCOPE {#EMS-AB-LOCAL-SCOPE}
```
public static final PidTagPropertyDescriptor EMS_AB_LOCAL_SCOPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LOCAL\_SCOPE

### EMS_AB_LOCAL_SCOPE_O {#EMS-AB-LOCAL-SCOPE-O}
```
public static final PidTagPropertyDescriptor EMS_AB_LOCAL_SCOPE_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LOCAL\_SCOPE\_O

### EMS_AB_LOG_FILENAME {#EMS-AB-LOG-FILENAME}
```
public static final PidTagPropertyDescriptor EMS_AB_LOG_FILENAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LOG\_FILENAME

### EMS_AB_LOG_ROLLOVER_INTERVAL {#EMS-AB-LOG-ROLLOVER-INTERVAL}
```
public static final PidTagPropertyDescriptor EMS_AB_LOG_ROLLOVER_INTERVAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_LOG\_ROLLOVER\_INTERVAL

### EMS_AB_MAIL_DROP {#EMS-AB-MAIL-DROP}
```
public static final PidTagPropertyDescriptor EMS_AB_MAIL_DROP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MAIL\_DROP

### EMS_AB_MAINTAIN_AUTOREPLY_HISTORY {#EMS-AB-MAINTAIN-AUTOREPLY-HISTORY}
```
public static final PidTagPropertyDescriptor EMS_AB_MAINTAIN_AUTOREPLY_HISTORY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MAINTAIN\_AUTOREPLY\_HISTORY

### EMS_AB_MAPI_DISPLAY_TYPE {#EMS-AB-MAPI-DISPLAY-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_MAPI_DISPLAY_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MAPI\_DISPLAY\_TYPE

### EMS_AB_MAPI_ID {#EMS-AB-MAPI-ID}
```
public static final PidTagPropertyDescriptor EMS_AB_MAPI_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MAPI\_ID

### EMS_AB_MAXIMUM_OBJECT_ID {#EMS-AB-MAXIMUM-OBJECT-ID}
```
public static final PidTagPropertyDescriptor EMS_AB_MAXIMUM_OBJECT_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MAXIMUM\_OBJECT\_ID

### EMS_AB_MDB_BACKOFF_INTERVAL {#EMS-AB-MDB-BACKOFF-INTERVAL}
```
public static final PidTagPropertyDescriptor EMS_AB_MDB_BACKOFF_INTERVAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MDB\_BACKOFF\_INTERVAL

### EMS_AB_MDB_MSG_TIME_OUT_PERIOD {#EMS-AB-MDB-MSG-TIME-OUT-PERIOD}
```
public static final PidTagPropertyDescriptor EMS_AB_MDB_MSG_TIME_OUT_PERIOD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MDB\_MSG\_TIME\_OUT\_PERIOD

### EMS_AB_MDB_OVER_QUOTA_LIMIT {#EMS-AB-MDB-OVER-QUOTA-LIMIT}
```
public static final PidTagPropertyDescriptor EMS_AB_MDB_OVER_QUOTA_LIMIT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MDB\_OVER\_QUOTA\_LIMIT

### EMS_AB_MDB_STORAGE_QUOTA {#EMS-AB-MDB-STORAGE-QUOTA}
```
public static final PidTagPropertyDescriptor EMS_AB_MDB_STORAGE_QUOTA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MDB\_STORAGE\_QUOTA

### EMS_AB_MDB_UNREAD_LIMIT {#EMS-AB-MDB-UNREAD-LIMIT}
```
public static final PidTagPropertyDescriptor EMS_AB_MDB_UNREAD_LIMIT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MDB\_UNREAD\_LIMIT

### EMS_AB_MDB_USE_DEFAULTS {#EMS-AB-MDB-USE-DEFAULTS}
```
public static final PidTagPropertyDescriptor EMS_AB_MDB_USE_DEFAULTS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MDB\_USE\_DEFAULTS

### EMS_AB_MESSAGE_TRACKING_ENABLED {#EMS-AB-MESSAGE-TRACKING-ENABLED}
```
public static final PidTagPropertyDescriptor EMS_AB_MESSAGE_TRACKING_ENABLED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MESSAGE\_TRACKING\_ENABLED

### EMS_AB_MIME_TYPES {#EMS-AB-MIME-TYPES}
```
public static final PidTagPropertyDescriptor EMS_AB_MIME_TYPES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MIME\_TYPES

### EMS_AB_MODERATED {#EMS-AB-MODERATED}
```
public static final PidTagPropertyDescriptor EMS_AB_MODERATED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MODERATED

### EMS_AB_MODERATOR {#EMS-AB-MODERATOR}
```
public static final PidTagPropertyDescriptor EMS_AB_MODERATOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MODERATOR

### EMS_AB_MONITORED_CONFIGURATIONS {#EMS-AB-MONITORED-CONFIGURATIONS}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORED_CONFIGURATIONS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORED\_CONFIGURATIONS

### EMS_AB_MONITORED_CONFIGURATIONS_O {#EMS-AB-MONITORED-CONFIGURATIONS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORED_CONFIGURATIONS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORED\_CONFIGURATIONS\_O

### EMS_AB_MONITORED_SERVERS {#EMS-AB-MONITORED-SERVERS}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORED_SERVERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORED\_SERVERS

### EMS_AB_MONITORED_SERVERS_O {#EMS-AB-MONITORED-SERVERS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORED_SERVERS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORED\_SERVERS\_O

### EMS_AB_MONITORED_SERVICES {#EMS-AB-MONITORED-SERVICES}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORED_SERVICES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORED\_SERVICES

### EMS_AB_MONITORING_ALERT_DELAY {#EMS-AB-MONITORING-ALERT-DELAY}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_ALERT_DELAY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_ALERT\_DELAY

### EMS_AB_MONITORING_ALERT_UNITS {#EMS-AB-MONITORING-ALERT-UNITS}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_ALERT_UNITS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_ALERT\_UNITS

### EMS_AB_MONITORING_AVAILABILITY_STYLE {#EMS-AB-MONITORING-AVAILABILITY-STYLE}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_AVAILABILITY_STYLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_AVAILABILITY\_STYLE

### EMS_AB_MONITORING_AVAILABILITY_WINDOW {#EMS-AB-MONITORING-AVAILABILITY-WINDOW}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_AVAILABILITY_WINDOW
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_AVAILABILITY\_WINDOW

### EMS_AB_MONITORING_CACHED_VIA_MAIL {#EMS-AB-MONITORING-CACHED-VIA-MAIL}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_CACHED_VIA_MAIL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_CACHED\_VIA\_MAIL

### EMS_AB_MONITORING_CACHED_VIA_MAIL_O {#EMS-AB-MONITORING-CACHED-VIA-MAIL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_CACHED_VIA_MAIL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_CACHED\_VIA\_MAIL\_O

### EMS_AB_MONITORING_CACHED_VIA_RPC {#EMS-AB-MONITORING-CACHED-VIA-RPC}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_CACHED_VIA_RPC
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_CACHED\_VIA\_RPC

### EMS_AB_MONITORING_CACHED_VIA_RPC_O {#EMS-AB-MONITORING-CACHED-VIA-RPC-O}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_CACHED_VIA_RPC_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_CACHED\_VIA\_RPC\_O

### EMS_AB_MONITORING_ESCALATION_PROCEDURE {#EMS-AB-MONITORING-ESCALATION-PROCEDURE}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_ESCALATION_PROCEDURE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_ESCALATION\_PROCEDURE

### EMS_AB_MONITORING_HOTSITE_POLL_INTERVAL {#EMS-AB-MONITORING-HOTSITE-POLL-INTERVAL}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_HOTSITE_POLL_INTERVAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_HOTSITE\_POLL\_INTERVAL

### EMS_AB_MONITORING_HOTSITE_POLL_UNITS {#EMS-AB-MONITORING-HOTSITE-POLL-UNITS}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_HOTSITE_POLL_UNITS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_HOTSITE\_POLL\_UNITS

### EMS_AB_MONITORING_MAIL_UPDATE_INTERVAL {#EMS-AB-MONITORING-MAIL-UPDATE-INTERVAL}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_MAIL_UPDATE_INTERVAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_MAIL\_UPDATE\_INTERVAL

### EMS_AB_MONITORING_MAIL_UPDATE_UNITS {#EMS-AB-MONITORING-MAIL-UPDATE-UNITS}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_MAIL_UPDATE_UNITS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_MAIL\_UPDATE\_UNITS

### EMS_AB_MONITORING_NORMAL_POLL_INTERVAL {#EMS-AB-MONITORING-NORMAL-POLL-INTERVAL}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_NORMAL_POLL_INTERVAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_NORMAL\_POLL\_INTERVAL

### EMS_AB_MONITORING_NORMAL_POLL_UNITS {#EMS-AB-MONITORING-NORMAL-POLL-UNITS}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_NORMAL_POLL_UNITS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_NORMAL\_POLL\_UNITS

### EMS_AB_MONITORING_RECIPIENTS {#EMS-AB-MONITORING-RECIPIENTS}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_RECIPIENTS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_RECIPIENTS

### EMS_AB_MONITORING_RECIPIENTS_NDR {#EMS-AB-MONITORING-RECIPIENTS-NDR}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_RECIPIENTS_NDR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_RECIPIENTS\_NDR

### EMS_AB_MONITORING_RECIPIENTS_NDR_O {#EMS-AB-MONITORING-RECIPIENTS-NDR-O}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_RECIPIENTS_NDR_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_RECIPIENTS\_NDR\_O

### EMS_AB_MONITORING_RECIPIENTS_O {#EMS-AB-MONITORING-RECIPIENTS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_RECIPIENTS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_RECIPIENTS\_O

### EMS_AB_MONITORING_RPC_UPDATE_INTERVAL {#EMS-AB-MONITORING-RPC-UPDATE-INTERVAL}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_RPC_UPDATE_INTERVAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_RPC\_UPDATE\_INTERVAL

### EMS_AB_MONITORING_RPC_UPDATE_UNITS {#EMS-AB-MONITORING-RPC-UPDATE-UNITS}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_RPC_UPDATE_UNITS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_RPC\_UPDATE\_UNITS

### EMS_AB_MONITORING_WARNING_DELAY {#EMS-AB-MONITORING-WARNING-DELAY}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_WARNING_DELAY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_WARNING\_DELAY

### EMS_AB_MONITORING_WARNING_UNITS {#EMS-AB-MONITORING-WARNING-UNITS}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITORING_WARNING_UNITS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITORING\_WARNING\_UNITS

### EMS_AB_MONITOR_CLOCK {#EMS-AB-MONITOR-CLOCK}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITOR_CLOCK
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITOR\_CLOCK

### EMS_AB_MONITOR_SERVERS {#EMS-AB-MONITOR-SERVERS}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITOR_SERVERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITOR\_SERVERS

### EMS_AB_MONITOR_SERVICES {#EMS-AB-MONITOR-SERVICES}
```
public static final PidTagPropertyDescriptor EMS_AB_MONITOR_SERVICES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MONITOR\_SERVICES

### EMS_AB_MTA_LOCAL_CRED {#EMS-AB-MTA-LOCAL-CRED}
```
public static final PidTagPropertyDescriptor EMS_AB_MTA_LOCAL_CRED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MTA\_LOCAL\_CRED

### EMS_AB_MTA_LOCAL_DESIG {#EMS-AB-MTA-LOCAL-DESIG}
```
public static final PidTagPropertyDescriptor EMS_AB_MTA_LOCAL_DESIG
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_MTA\_LOCAL\_DESIG

### EMS_AB_NEWSFEED_TYPE {#EMS-AB-NEWSFEED-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_NEWSFEED_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NEWSFEED\_TYPE

### EMS_AB_NEWSGROUP {#EMS-AB-NEWSGROUP}
```
public static final PidTagPropertyDescriptor EMS_AB_NEWSGROUP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NEWSGROUP

### EMS_AB_NEWSGROUP_LIST {#EMS-AB-NEWSGROUP-LIST}
```
public static final PidTagPropertyDescriptor EMS_AB_NEWSGROUP_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NEWSGROUP\_LIST

### EMS_AB_NNTP_CHARACTER_SET {#EMS-AB-NNTP-CHARACTER-SET}
```
public static final PidTagPropertyDescriptor EMS_AB_NNTP_CHARACTER_SET
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NNTP\_CHARACTER\_SET

### EMS_AB_NNTP_CONTENT_FORMAT {#EMS-AB-NNTP-CONTENT-FORMAT}
```
public static final PidTagPropertyDescriptor EMS_AB_NNTP_CONTENT_FORMAT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NNTP\_CONTENT\_FORMAT

### EMS_AB_NNTP_DISTRIBUTIONS {#EMS-AB-NNTP-DISTRIBUTIONS}
```
public static final PidTagPropertyDescriptor EMS_AB_NNTP_DISTRIBUTIONS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NNTP\_DISTRIBUTIONS

### EMS_AB_NNTP_DISTRIBUTIONS_FLAG {#EMS-AB-NNTP-DISTRIBUTIONS-FLAG}
```
public static final PidTagPropertyDescriptor EMS_AB_NNTP_DISTRIBUTIONS_FLAG
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NNTP\_DISTRIBUTIONS\_FLAG

### EMS_AB_NNTP_NEWSFEEDS {#EMS-AB-NNTP-NEWSFEEDS}
```
public static final PidTagPropertyDescriptor EMS_AB_NNTP_NEWSFEEDS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NNTP\_NEWSFEEDS

### EMS_AB_NNTP_NEWSFEEDS_O {#EMS-AB-NNTP-NEWSFEEDS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_NNTP_NEWSFEEDS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NNTP\_NEWSFEEDS\_O

### EMS_AB_NT_MACHINE_NAME {#EMS-AB-NT-MACHINE-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_NT_MACHINE_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NT\_MACHINE\_NAME

### EMS_AB_NT_SECURITY_DESCRIPTOR {#EMS-AB-NT-SECURITY-DESCRIPTOR}
```
public static final PidTagPropertyDescriptor EMS_AB_NT_SECURITY_DESCRIPTOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NT\_SECURITY\_DESCRIPTOR

### EMS_AB_NUM_OF_OPEN_RETRIES {#EMS-AB-NUM-OF-OPEN-RETRIES}
```
public static final PidTagPropertyDescriptor EMS_AB_NUM_OF_OPEN_RETRIES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NUM\_OF\_OPEN\_RETRIES

### EMS_AB_NUM_OF_TRANSFER_RETRIES {#EMS-AB-NUM-OF-TRANSFER-RETRIES}
```
public static final PidTagPropertyDescriptor EMS_AB_NUM_OF_TRANSFER_RETRIES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_NUM\_OF\_TRANSFER\_RETRIES

### EMS_AB_N_ADDRESS {#EMS-AB-N-ADDRESS}
```
public static final PidTagPropertyDescriptor EMS_AB_N_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_N\_ADDRESS

### EMS_AB_N_ADDRESS_TYPE {#EMS-AB-N-ADDRESS-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_N_ADDRESS_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_N\_ADDRESS\_TYPE

### EMS_AB_OBJECT_CLASS_CATEGORY {#EMS-AB-OBJECT-CLASS-CATEGORY}
```
public static final PidTagPropertyDescriptor EMS_AB_OBJECT_CLASS_CATEGORY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OBJECT\_CLASS\_CATEGORY

### EMS_AB_OBJECT_OID {#EMS-AB-OBJECT-OID}
```
public static final PidTagPropertyDescriptor EMS_AB_OBJECT_OID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OBJECT\_OID

### EMS_AB_OBJECT_VERSION {#EMS-AB-OBJECT-VERSION}
```
public static final PidTagPropertyDescriptor EMS_AB_OBJECT_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OBJECT\_VERSION

### EMS_AB_OBJ_VIEW_CONTAINERS {#EMS-AB-OBJ-VIEW-CONTAINERS}
```
public static final PidTagPropertyDescriptor EMS_AB_OBJ_VIEW_CONTAINERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OBJ\_VIEW\_CONTAINERS

### EMS_AB_OBJ_VIEW_CONTAINERS_O {#EMS-AB-OBJ-VIEW-CONTAINERS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_OBJ_VIEW_CONTAINERS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OBJ\_VIEW\_CONTAINERS\_O

### EMS_AB_OFF_LINE_AB_CONTAINERS {#EMS-AB-OFF-LINE-AB-CONTAINERS}
```
public static final PidTagPropertyDescriptor EMS_AB_OFF_LINE_AB_CONTAINERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OFF\_LINE\_AB\_CONTAINERS

### EMS_AB_OFF_LINE_AB_CONTAINERS_O {#EMS-AB-OFF-LINE-AB-CONTAINERS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_OFF_LINE_AB_CONTAINERS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OFF\_LINE\_AB\_CONTAINERS\_O

### EMS_AB_OFF_LINE_AB_SCHEDULE {#EMS-AB-OFF-LINE-AB-SCHEDULE}
```
public static final PidTagPropertyDescriptor EMS_AB_OFF_LINE_AB_SCHEDULE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OFF\_LINE\_AB\_SCHEDULE

### EMS_AB_OFF_LINE_AB_SERVER {#EMS-AB-OFF-LINE-AB-SERVER}
```
public static final PidTagPropertyDescriptor EMS_AB_OFF_LINE_AB_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OFF\_LINE\_AB\_SERVER

### EMS_AB_OFF_LINE_AB_SERVER_O {#EMS-AB-OFF-LINE-AB-SERVER-O}
```
public static final PidTagPropertyDescriptor EMS_AB_OFF_LINE_AB_SERVER_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OFF\_LINE\_AB\_SERVER\_O

### EMS_AB_OFF_LINE_AB_STYLE {#EMS-AB-OFF-LINE-AB-STYLE}
```
public static final PidTagPropertyDescriptor EMS_AB_OFF_LINE_AB_STYLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OFF\_LINE\_AB\_STYLE

### EMS_AB_OID_TYPE {#EMS-AB-OID-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_OID_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OID\_TYPE

### EMS_AB_OM_OBJECT_CLASS {#EMS-AB-OM-OBJECT-CLASS}
```
public static final PidTagPropertyDescriptor EMS_AB_OM_OBJECT_CLASS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OM\_OBJECT\_CLASS

### EMS_AB_OM_SYNTAX {#EMS-AB-OM-SYNTAX}
```
public static final PidTagPropertyDescriptor EMS_AB_OM_SYNTAX
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OM\_SYNTAX

### EMS_AB_OOF_REPLY_TO_ORIGINATOR {#EMS-AB-OOF-REPLY-TO-ORIGINATOR}
```
public static final PidTagPropertyDescriptor EMS_AB_OOF_REPLY_TO_ORIGINATOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OOF\_REPLY\_TO\_ORIGINATOR

### EMS_AB_OPEN_RETRY_INTERVAL {#EMS-AB-OPEN-RETRY-INTERVAL}
```
public static final PidTagPropertyDescriptor EMS_AB_OPEN_RETRY_INTERVAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OPEN\_RETRY\_INTERVAL

### EMS_AB_ORGANIZATIONAL_UNIT_NAME {#EMS-AB-ORGANIZATIONAL-UNIT-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_ORGANIZATIONAL_UNIT_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ORGANIZATIONAL\_UNIT\_NAME

### EMS_AB_ORGANIZATION_NAME {#EMS-AB-ORGANIZATION-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_ORGANIZATION_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ORGANIZATION\_NAME

### EMS_AB_ORIGINAL_DISPLAY_TABLE {#EMS-AB-ORIGINAL-DISPLAY-TABLE}
```
public static final PidTagPropertyDescriptor EMS_AB_ORIGINAL_DISPLAY_TABLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ORIGINAL\_DISPLAY\_TABLE

### EMS_AB_ORIGINAL_DISPLAY_TABLE_MSDOS {#EMS-AB-ORIGINAL-DISPLAY-TABLE-MSDOS}
```
public static final PidTagPropertyDescriptor EMS_AB_ORIGINAL_DISPLAY_TABLE_MSDOS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ORIGINAL\_DISPLAY\_TABLE\_MSDOS

### EMS_AB_OTHER_RECIPS {#EMS-AB-OTHER-RECIPS}
```
public static final PidTagPropertyDescriptor EMS_AB_OTHER_RECIPS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OTHER\_RECIPS

### EMS_AB_OUTBOUND_HOST {#EMS-AB-OUTBOUND-HOST}
```
public static final PidTagPropertyDescriptor EMS_AB_OUTBOUND_HOST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OUTBOUND\_HOST

### EMS_AB_OUTBOUND_HOST_TYPE {#EMS-AB-OUTBOUND-HOST-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_OUTBOUND_HOST_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OUTBOUND\_HOST\_TYPE

### EMS_AB_OUTBOUND_NEWSFEED {#EMS-AB-OUTBOUND-NEWSFEED}
```
public static final PidTagPropertyDescriptor EMS_AB_OUTBOUND_NEWSFEED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OUTBOUND\_NEWSFEED

### EMS_AB_OUTBOUND_SITES {#EMS-AB-OUTBOUND-SITES}
```
public static final PidTagPropertyDescriptor EMS_AB_OUTBOUND_SITES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OUTBOUND\_SITES

### EMS_AB_OUTBOUND_SITES_O {#EMS-AB-OUTBOUND-SITES-O}
```
public static final PidTagPropertyDescriptor EMS_AB_OUTBOUND_SITES_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OUTBOUND\_SITES\_O

### EMS_AB_OUTGOING_MSG_SIZE_LIMIT {#EMS-AB-OUTGOING-MSG-SIZE-LIMIT}
```
public static final PidTagPropertyDescriptor EMS_AB_OUTGOING_MSG_SIZE_LIMIT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OUTGOING\_MSG\_SIZE\_LIMIT

### EMS_AB_OVERRIDE_NNTP_CONTENT_FORMAT {#EMS-AB-OVERRIDE-NNTP-CONTENT-FORMAT}
```
public static final PidTagPropertyDescriptor EMS_AB_OVERRIDE_NNTP_CONTENT_FORMAT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OVERRIDE\_NNTP\_CONTENT\_FORMAT

### EMS_AB_OWA_SERVER {#EMS-AB-OWA-SERVER}
```
public static final PidTagPropertyDescriptor EMS_AB_OWA_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_OWA\_SERVER

### EMS_AB_PERIOD_REPL_STAGGER {#EMS-AB-PERIOD-REPL-STAGGER}
```
public static final PidTagPropertyDescriptor EMS_AB_PERIOD_REPL_STAGGER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PERIOD\_REPL\_STAGGER

### EMS_AB_PERIOD_REP_SYNC_TIMES {#EMS-AB-PERIOD-REP-SYNC-TIMES}
```
public static final PidTagPropertyDescriptor EMS_AB_PERIOD_REP_SYNC_TIMES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PERIOD\_REP\_SYNC\_TIMES

### EMS_AB_PERSONAL_TITLE {#EMS-AB-PERSONAL-TITLE}
```
public static final PidTagPropertyDescriptor EMS_AB_PERSONAL_TITLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PERSONAL\_TITLE

### EMS_AB_PER_MSG_DIALOG_DISPLAY_TABLE {#EMS-AB-PER-MSG-DIALOG-DISPLAY-TABLE}
```
public static final PidTagPropertyDescriptor EMS_AB_PER_MSG_DIALOG_DISPLAY_TABLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PER\_MSG\_DIALOG\_DISPLAY\_TABLE

### EMS_AB_PER_RECIP_DIALOG_DISPLAY_TABLE {#EMS-AB-PER-RECIP-DIALOG-DISPLAY-TABLE}
```
public static final PidTagPropertyDescriptor EMS_AB_PER_RECIP_DIALOG_DISPLAY_TABLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PER\_RECIP\_DIALOG\_DISPLAY\_TABLE

### EMS_AB_PF_CONTACTS {#EMS-AB-PF-CONTACTS}
```
public static final PidTagPropertyDescriptor EMS_AB_PF_CONTACTS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PF\_CONTACTS

### EMS_AB_PF_CONTACTS_O {#EMS-AB-PF-CONTACTS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_PF_CONTACTS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PF\_CONTACTS\_O

### EMS_AB_POP_CHARACTER_SET {#EMS-AB-POP-CHARACTER-SET}
```
public static final PidTagPropertyDescriptor EMS_AB_POP_CHARACTER_SET
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_POP\_CHARACTER\_SET

### EMS_AB_POP_CONTENT_FORMAT {#EMS-AB-POP-CONTENT-FORMAT}
```
public static final PidTagPropertyDescriptor EMS_AB_POP_CONTENT_FORMAT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_POP\_CONTENT\_FORMAT

### EMS_AB_PORT_NUMBER {#EMS-AB-PORT-NUMBER}
```
public static final PidTagPropertyDescriptor EMS_AB_PORT_NUMBER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PORT\_NUMBER

### EMS_AB_POSTAL_ADDRESS {#EMS-AB-POSTAL-ADDRESS}
```
public static final PidTagPropertyDescriptor EMS_AB_POSTAL_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_POSTAL\_ADDRESS

### EMS_AB_PREFERRED_DELIVERY_METHOD {#EMS-AB-PREFERRED-DELIVERY-METHOD}
```
public static final PidTagPropertyDescriptor EMS_AB_PREFERRED_DELIVERY_METHOD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PREFERRED\_DELIVERY\_METHOD

### EMS_AB_PRESERVE_INTERNET_CONTENT {#EMS-AB-PRESERVE-INTERNET-CONTENT}
```
public static final PidTagPropertyDescriptor EMS_AB_PRESERVE_INTERNET_CONTENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PRESERVE\_INTERNET\_CONTENT

### EMS_AB_PRMD {#EMS-AB-PRMD}
```
public static final PidTagPropertyDescriptor EMS_AB_PRMD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PRMD

### EMS_AB_PROMO_EXPIRATION {#EMS-AB-PROMO-EXPIRATION}
```
public static final PidTagPropertyDescriptor EMS_AB_PROMO_EXPIRATION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PROMO\_EXPIRATION

### EMS_AB_PROTOCOL_SETTINGS {#EMS-AB-PROTOCOL-SETTINGS}
```
public static final PidTagPropertyDescriptor EMS_AB_PROTOCOL_SETTINGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PROTOCOL\_SETTINGS

### EMS_AB_PROXY_GENERATION_ENABLED {#EMS-AB-PROXY-GENERATION-ENABLED}
```
public static final PidTagPropertyDescriptor EMS_AB_PROXY_GENERATION_ENABLED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PROXY\_GENERATION\_ENABLED

### EMS_AB_PROXY_GENERATOR_DLL {#EMS-AB-PROXY-GENERATOR-DLL}
```
public static final PidTagPropertyDescriptor EMS_AB_PROXY_GENERATOR_DLL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PROXY\_GENERATOR\_DLL

### EMS_AB_PUBLIC_DELEGATES_BL {#EMS-AB-PUBLIC-DELEGATES-BL}
```
public static final PidTagPropertyDescriptor EMS_AB_PUBLIC_DELEGATES_BL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PUBLIC\_DELEGATES\_BL

### EMS_AB_PUBLIC_DELEGATES_BL_O {#EMS-AB-PUBLIC-DELEGATES-BL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_PUBLIC_DELEGATES_BL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_PUBLIC\_DELEGATES\_BL\_O

### EMS_AB_P_SELECTOR {#EMS-AB-P-SELECTOR}
```
public static final PidTagPropertyDescriptor EMS_AB_P_SELECTOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_P\_SELECTOR

### EMS_AB_P_SELECTOR_INBOUND {#EMS-AB-P-SELECTOR-INBOUND}
```
public static final PidTagPropertyDescriptor EMS_AB_P_SELECTOR_INBOUND
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_P\_SELECTOR\_INBOUND

### EMS_AB_QUOTA_NOTIFICATION_SCHEDULE {#EMS-AB-QUOTA-NOTIFICATION-SCHEDULE}
```
public static final PidTagPropertyDescriptor EMS_AB_QUOTA_NOTIFICATION_SCHEDULE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_QUOTA\_NOTIFICATION\_SCHEDULE

### EMS_AB_QUOTA_NOTIFICATION_STYLE {#EMS-AB-QUOTA-NOTIFICATION-STYLE}
```
public static final PidTagPropertyDescriptor EMS_AB_QUOTA_NOTIFICATION_STYLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_QUOTA\_NOTIFICATION\_STYLE

### EMS_AB_RANGE_LOWER {#EMS-AB-RANGE-LOWER}
```
public static final PidTagPropertyDescriptor EMS_AB_RANGE_LOWER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RANGE\_LOWER

### EMS_AB_RANGE_UPPER {#EMS-AB-RANGE-UPPER}
```
public static final PidTagPropertyDescriptor EMS_AB_RANGE_UPPER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RANGE\_UPPER

### EMS_AB_RAS_ACCOUNT {#EMS-AB-RAS-ACCOUNT}
```
public static final PidTagPropertyDescriptor EMS_AB_RAS_ACCOUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RAS\_ACCOUNT

### EMS_AB_RAS_CALLBACK_NUMBER {#EMS-AB-RAS-CALLBACK-NUMBER}
```
public static final PidTagPropertyDescriptor EMS_AB_RAS_CALLBACK_NUMBER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RAS\_CALLBACK\_NUMBER

### EMS_AB_RAS_PASSWORD {#EMS-AB-RAS-PASSWORD}
```
public static final PidTagPropertyDescriptor EMS_AB_RAS_PASSWORD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RAS\_PASSWORD

### EMS_AB_RAS_PHONEBOOK_ENTRY_NAME {#EMS-AB-RAS-PHONEBOOK-ENTRY-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_RAS_PHONEBOOK_ENTRY_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RAS\_PHONEBOOK\_ENTRY\_NAME

### EMS_AB_RAS_PHONE_NUMBER {#EMS-AB-RAS-PHONE-NUMBER}
```
public static final PidTagPropertyDescriptor EMS_AB_RAS_PHONE_NUMBER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RAS\_PHONE\_NUMBER

### EMS_AB_RAS_REMOTE_SRVR_NAME {#EMS-AB-RAS-REMOTE-SRVR-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_RAS_REMOTE_SRVR_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RAS\_REMOTE\_SRVR\_NAME

### EMS_AB_REFERRAL_LIST {#EMS-AB-REFERRAL-LIST}
```
public static final PidTagPropertyDescriptor EMS_AB_REFERRAL_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REFERRAL\_LIST

### EMS_AB_REGISTERED_ADDRESS {#EMS-AB-REGISTERED-ADDRESS}
```
public static final PidTagPropertyDescriptor EMS_AB_REGISTERED_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REGISTERED\_ADDRESS

### EMS_AB_REMOTE_BRIDGE_HEAD {#EMS-AB-REMOTE-BRIDGE-HEAD}
```
public static final PidTagPropertyDescriptor EMS_AB_REMOTE_BRIDGE_HEAD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REMOTE\_BRIDGE\_HEAD

### EMS_AB_REMOTE_BRIDGE_HEAD_ADDRESS {#EMS-AB-REMOTE-BRIDGE-HEAD-ADDRESS}
```
public static final PidTagPropertyDescriptor EMS_AB_REMOTE_BRIDGE_HEAD_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REMOTE\_BRIDGE\_HEAD\_ADDRESS

### EMS_AB_REMOTE_OUT_BH_SERVER {#EMS-AB-REMOTE-OUT-BH-SERVER}
```
public static final PidTagPropertyDescriptor EMS_AB_REMOTE_OUT_BH_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REMOTE\_OUT\_BH\_SERVER

### EMS_AB_REMOTE_OUT_BH_SERVER_O {#EMS-AB-REMOTE-OUT-BH-SERVER-O}
```
public static final PidTagPropertyDescriptor EMS_AB_REMOTE_OUT_BH_SERVER_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REMOTE\_OUT\_BH\_SERVER\_O

### EMS_AB_REMOTE_SITE {#EMS-AB-REMOTE-SITE}
```
public static final PidTagPropertyDescriptor EMS_AB_REMOTE_SITE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REMOTE\_SITE

### EMS_AB_REMOTE_SITE_O {#EMS-AB-REMOTE-SITE-O}
```
public static final PidTagPropertyDescriptor EMS_AB_REMOTE_SITE_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REMOTE\_SITE\_O

### EMS_AB_REPLICATED_OBJECT_VERSION {#EMS-AB-REPLICATED-OBJECT-VERSION}
```
public static final PidTagPropertyDescriptor EMS_AB_REPLICATED_OBJECT_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REPLICATED\_OBJECT\_VERSION

### EMS_AB_REPLICATION_MAIL_MSG_SIZE {#EMS-AB-REPLICATION-MAIL-MSG-SIZE}
```
public static final PidTagPropertyDescriptor EMS_AB_REPLICATION_MAIL_MSG_SIZE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REPLICATION\_MAIL\_MSG\_SIZE

### EMS_AB_REPLICATION_SENSITIVITY {#EMS-AB-REPLICATION-SENSITIVITY}
```
public static final PidTagPropertyDescriptor EMS_AB_REPLICATION_SENSITIVITY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REPLICATION\_SENSITIVITY

### EMS_AB_REPLICATION_STAGGER {#EMS-AB-REPLICATION-STAGGER}
```
public static final PidTagPropertyDescriptor EMS_AB_REPLICATION_STAGGER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REPLICATION\_STAGGER

### EMS_AB_REPORT_TO_ORIGINATOR {#EMS-AB-REPORT-TO-ORIGINATOR}
```
public static final PidTagPropertyDescriptor EMS_AB_REPORT_TO_ORIGINATOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REPORT\_TO\_ORIGINATOR

### EMS_AB_REPORT_TO_OWNER {#EMS-AB-REPORT-TO-OWNER}
```
public static final PidTagPropertyDescriptor EMS_AB_REPORT_TO_OWNER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REPORT\_TO\_OWNER

### EMS_AB_REQUIRE_SSL {#EMS-AB-REQUIRE-SSL}
```
public static final PidTagPropertyDescriptor EMS_AB_REQUIRE_SSL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REQUIRE\_SSL

### EMS_AB_REQ_SEQ {#EMS-AB-REQ-SEQ}
```
public static final PidTagPropertyDescriptor EMS_AB_REQ_SEQ
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_REQ\_SEQ

### EMS_AB_RESPONSIBLE_LOCAL_DXA {#EMS-AB-RESPONSIBLE-LOCAL-DXA}
```
public static final PidTagPropertyDescriptor EMS_AB_RESPONSIBLE_LOCAL_DXA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RESPONSIBLE\_LOCAL\_DXA

### EMS_AB_RESPONSIBLE_LOCAL_DXA_O {#EMS-AB-RESPONSIBLE-LOCAL-DXA-O}
```
public static final PidTagPropertyDescriptor EMS_AB_RESPONSIBLE_LOCAL_DXA_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RESPONSIBLE\_LOCAL\_DXA\_O

### EMS_AB_RETURN_EXACT_MSG_SIZE {#EMS-AB-RETURN-EXACT-MSG-SIZE}
```
public static final PidTagPropertyDescriptor EMS_AB_RETURN_EXACT_MSG_SIZE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RETURN\_EXACT\_MSG\_SIZE

### EMS_AB_RID_SERVER {#EMS-AB-RID-SERVER}
```
public static final PidTagPropertyDescriptor EMS_AB_RID_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RID\_SERVER

### EMS_AB_RID_SERVER_O {#EMS-AB-RID-SERVER-O}
```
public static final PidTagPropertyDescriptor EMS_AB_RID_SERVER_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RID\_SERVER\_O

### EMS_AB_ROLE_OCCUPANT {#EMS-AB-ROLE-OCCUPANT}
```
public static final PidTagPropertyDescriptor EMS_AB_ROLE_OCCUPANT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ROLE\_OCCUPANT

### EMS_AB_ROLE_OCCUPANT_O {#EMS-AB-ROLE-OCCUPANT-O}
```
public static final PidTagPropertyDescriptor EMS_AB_ROLE_OCCUPANT_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ROLE\_OCCUPANT\_O

### EMS_AB_ROOT_NEWSGROUPS_FOLDER_ID {#EMS-AB-ROOT-NEWSGROUPS-FOLDER-ID}
```
public static final PidTagPropertyDescriptor EMS_AB_ROOT_NEWSGROUPS_FOLDER_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ROOT\_NEWSGROUPS\_FOLDER\_ID

### EMS_AB_ROUTING_LIST {#EMS-AB-ROUTING-LIST}
```
public static final PidTagPropertyDescriptor EMS_AB_ROUTING_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_ROUTING\_LIST

### EMS_AB_RTS_CHECKPOINT_SIZE {#EMS-AB-RTS-CHECKPOINT-SIZE}
```
public static final PidTagPropertyDescriptor EMS_AB_RTS_CHECKPOINT_SIZE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RTS\_CHECKPOINT\_SIZE

### EMS_AB_RTS_RECOVERY_TIMEOUT {#EMS-AB-RTS-RECOVERY-TIMEOUT}
```
public static final PidTagPropertyDescriptor EMS_AB_RTS_RECOVERY_TIMEOUT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RTS\_RECOVERY\_TIMEOUT

### EMS_AB_RTS_WINDOW_SIZE {#EMS-AB-RTS-WINDOW-SIZE}
```
public static final PidTagPropertyDescriptor EMS_AB_RTS_WINDOW_SIZE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RTS\_WINDOW\_SIZE

### EMS_AB_RUNS_ON {#EMS-AB-RUNS-ON}
```
public static final PidTagPropertyDescriptor EMS_AB_RUNS_ON
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RUNS\_ON

### EMS_AB_RUNS_ON_O {#EMS-AB-RUNS-ON-O}
```
public static final PidTagPropertyDescriptor EMS_AB_RUNS_ON_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_RUNS\_ON\_O

### EMS_AB_SCHEMA_FLAGS {#EMS-AB-SCHEMA-FLAGS}
```
public static final PidTagPropertyDescriptor EMS_AB_SCHEMA_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SCHEMA\_FLAGS

### EMS_AB_SCHEMA_VERSION {#EMS-AB-SCHEMA-VERSION}
```
public static final PidTagPropertyDescriptor EMS_AB_SCHEMA_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SCHEMA\_VERSION

### EMS_AB_SEARCH_FLAGS {#EMS-AB-SEARCH-FLAGS}
```
public static final PidTagPropertyDescriptor EMS_AB_SEARCH_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SEARCH\_FLAGS

### EMS_AB_SEARCH_GUIDE {#EMS-AB-SEARCH-GUIDE}
```
public static final PidTagPropertyDescriptor EMS_AB_SEARCH_GUIDE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SEARCH\_GUIDE

### EMS_AB_SECURITY_POLICY {#EMS-AB-SECURITY-POLICY}
```
public static final PidTagPropertyDescriptor EMS_AB_SECURITY_POLICY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SECURITY\_POLICY

### EMS_AB_SECURITY_PROTOCOL {#EMS-AB-SECURITY-PROTOCOL}
```
public static final PidTagPropertyDescriptor EMS_AB_SECURITY_PROTOCOL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SECURITY\_PROTOCOL

### EMS_AB_SEE_ALSO {#EMS-AB-SEE-ALSO}
```
public static final PidTagPropertyDescriptor EMS_AB_SEE_ALSO
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SEE\_ALSO

### EMS_AB_SEE_ALSO_O {#EMS-AB-SEE-ALSO-O}
```
public static final PidTagPropertyDescriptor EMS_AB_SEE_ALSO_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SEE\_ALSO\_O

### EMS_AB_SEND_EMAIL_MESSAGE {#EMS-AB-SEND-EMAIL-MESSAGE}
```
public static final PidTagPropertyDescriptor EMS_AB_SEND_EMAIL_MESSAGE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SEND\_EMAIL\_MESSAGE

### EMS_AB_SEND_TNEF {#EMS-AB-SEND-TNEF}
```
public static final PidTagPropertyDescriptor EMS_AB_SEND_TNEF
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SEND\_TNEF

### EMS_AB_SERIAL_NUMBER {#EMS-AB-SERIAL-NUMBER}
```
public static final PidTagPropertyDescriptor EMS_AB_SERIAL_NUMBER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SERIAL\_NUMBER

### EMS_AB_SERVER {#EMS-AB-SERVER}
```
public static final PidTagPropertyDescriptor EMS_AB_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SERVER

### EMS_AB_SERVICE_ACTION_FIRST {#EMS-AB-SERVICE-ACTION-FIRST}
```
public static final PidTagPropertyDescriptor EMS_AB_SERVICE_ACTION_FIRST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SERVICE\_ACTION\_FIRST

### EMS_AB_SERVICE_ACTION_OTHER {#EMS-AB-SERVICE-ACTION-OTHER}
```
public static final PidTagPropertyDescriptor EMS_AB_SERVICE_ACTION_OTHER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SERVICE\_ACTION\_OTHER

### EMS_AB_SERVICE_ACTION_SECOND {#EMS-AB-SERVICE-ACTION-SECOND}
```
public static final PidTagPropertyDescriptor EMS_AB_SERVICE_ACTION_SECOND
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SERVICE\_ACTION\_SECOND

### EMS_AB_SERVICE_RESTART_DELAY {#EMS-AB-SERVICE-RESTART-DELAY}
```
public static final PidTagPropertyDescriptor EMS_AB_SERVICE_RESTART_DELAY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SERVICE\_RESTART\_DELAY

### EMS_AB_SERVICE_RESTART_MESSAGE {#EMS-AB-SERVICE-RESTART-MESSAGE}
```
public static final PidTagPropertyDescriptor EMS_AB_SERVICE_RESTART_MESSAGE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SERVICE\_RESTART\_MESSAGE

### EMS_AB_SESSION_DISCONNECT_TIMER {#EMS-AB-SESSION-DISCONNECT-TIMER}
```
public static final PidTagPropertyDescriptor EMS_AB_SESSION_DISCONNECT_TIMER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SESSION\_DISCONNECT\_TIMER

### EMS_AB_SITE_AFFINITY {#EMS-AB-SITE-AFFINITY}
```
public static final PidTagPropertyDescriptor EMS_AB_SITE_AFFINITY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SITE\_AFFINITY

### EMS_AB_SITE_FOLDER_GUID {#EMS-AB-SITE-FOLDER-GUID}
```
public static final PidTagPropertyDescriptor EMS_AB_SITE_FOLDER_GUID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SITE\_FOLDER\_GUID

### EMS_AB_SITE_FOLDER_SERVER {#EMS-AB-SITE-FOLDER-SERVER}
```
public static final PidTagPropertyDescriptor EMS_AB_SITE_FOLDER_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SITE\_FOLDER\_SERVER

### EMS_AB_SITE_FOLDER_SERVER_O {#EMS-AB-SITE-FOLDER-SERVER-O}
```
public static final PidTagPropertyDescriptor EMS_AB_SITE_FOLDER_SERVER_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SITE\_FOLDER\_SERVER\_O

### EMS_AB_SITE_PROXY_SPACE {#EMS-AB-SITE-PROXY-SPACE}
```
public static final PidTagPropertyDescriptor EMS_AB_SITE_PROXY_SPACE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SITE\_PROXY\_SPACE

### EMS_AB_SMIME_ALG_LIST_NA {#EMS-AB-SMIME-ALG-LIST-NA}
```
public static final PidTagPropertyDescriptor EMS_AB_SMIME_ALG_LIST_NA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SMIME\_ALG\_LIST\_NA

### EMS_AB_SMIME_ALG_LIST_OTHER {#EMS-AB-SMIME-ALG-LIST-OTHER}
```
public static final PidTagPropertyDescriptor EMS_AB_SMIME_ALG_LIST_OTHER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SMIME\_ALG\_LIST\_OTHER

### EMS_AB_SMIME_ALG_SELECTED_NA {#EMS-AB-SMIME-ALG-SELECTED-NA}
```
public static final PidTagPropertyDescriptor EMS_AB_SMIME_ALG_SELECTED_NA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SMIME\_ALG\_SELECTED\_NA

### EMS_AB_SMIME_ALG_SELECTED_OTHER {#EMS-AB-SMIME-ALG-SELECTED-OTHER}
```
public static final PidTagPropertyDescriptor EMS_AB_SMIME_ALG_SELECTED_OTHER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SMIME\_ALG\_SELECTED\_OTHER

### EMS_AB_SPACE_LAST_COMPUTED {#EMS-AB-SPACE-LAST-COMPUTED}
```
public static final PidTagPropertyDescriptor EMS_AB_SPACE_LAST_COMPUTED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SPACE\_LAST\_COMPUTED

### EMS_AB_STREET_ADDRESS {#EMS-AB-STREET-ADDRESS}
```
public static final PidTagPropertyDescriptor EMS_AB_STREET_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_STREET\_ADDRESS

### EMS_AB_SUBMISSION_CONT_LENGTH {#EMS-AB-SUBMISSION-CONT-LENGTH}
```
public static final PidTagPropertyDescriptor EMS_AB_SUBMISSION_CONT_LENGTH
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SUBMISSION\_CONT\_LENGTH

### EMS_AB_SUB_REFS {#EMS-AB-SUB-REFS}
```
public static final PidTagPropertyDescriptor EMS_AB_SUB_REFS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SUB\_REFS

### EMS_AB_SUB_REFS_O {#EMS-AB-SUB-REFS-O}
```
public static final PidTagPropertyDescriptor EMS_AB_SUB_REFS_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SUB\_REFS\_O

### EMS_AB_SUB_SITE {#EMS-AB-SUB-SITE}
```
public static final PidTagPropertyDescriptor EMS_AB_SUB_SITE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SUB\_SITE

### EMS_AB_SUPPORTED_ALGORITHMS {#EMS-AB-SUPPORTED-ALGORITHMS}
```
public static final PidTagPropertyDescriptor EMS_AB_SUPPORTED_ALGORITHMS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SUPPORTED\_ALGORITHMS

### EMS_AB_SUPPORTED_APPLICATION_CONTEXT {#EMS-AB-SUPPORTED-APPLICATION-CONTEXT}
```
public static final PidTagPropertyDescriptor EMS_AB_SUPPORTED_APPLICATION_CONTEXT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SUPPORTED\_APPLICATION\_CONTEXT

### EMS_AB_SUPPORTING_STACK {#EMS-AB-SUPPORTING-STACK}
```
public static final PidTagPropertyDescriptor EMS_AB_SUPPORTING_STACK
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SUPPORTING\_STACK

### EMS_AB_SUPPORTING_STACK_BL {#EMS-AB-SUPPORTING-STACK-BL}
```
public static final PidTagPropertyDescriptor EMS_AB_SUPPORTING_STACK_BL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SUPPORTING\_STACK\_BL

### EMS_AB_SUPPORTING_STACK_BL_O {#EMS-AB-SUPPORTING-STACK-BL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_SUPPORTING_STACK_BL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SUPPORTING\_STACK\_BL\_O

### EMS_AB_SUPPORTING_STACK_O {#EMS-AB-SUPPORTING-STACK-O}
```
public static final PidTagPropertyDescriptor EMS_AB_SUPPORTING_STACK_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SUPPORTING\_STACK\_O

### EMS_AB_SUPPORT_SMIME_SIGNATURES {#EMS-AB-SUPPORT-SMIME-SIGNATURES}
```
public static final PidTagPropertyDescriptor EMS_AB_SUPPORT_SMIME_SIGNATURES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_SUPPORT\_SMIME\_SIGNATURES

### EMS_AB_S_SELECTOR {#EMS-AB-S-SELECTOR}
```
public static final PidTagPropertyDescriptor EMS_AB_S_SELECTOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_S\_SELECTOR

### EMS_AB_S_SELECTOR_INBOUND {#EMS-AB-S-SELECTOR-INBOUND}
```
public static final PidTagPropertyDescriptor EMS_AB_S_SELECTOR_INBOUND
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_S\_SELECTOR\_INBOUND

### EMS_AB_TARGET_MTAS {#EMS-AB-TARGET-MTAS}
```
public static final PidTagPropertyDescriptor EMS_AB_TARGET_MTAS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TARGET\_MTAS

### EMS_AB_TELEPHONE_NUMBER {#EMS-AB-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor EMS_AB_TELEPHONE_NUMBER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TELEPHONE\_NUMBER

### EMS_AB_TELEPHONE_PERSONAL_PAGER {#EMS-AB-TELEPHONE-PERSONAL-PAGER}
```
public static final PidTagPropertyDescriptor EMS_AB_TELEPHONE_PERSONAL_PAGER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TELEPHONE\_PERSONAL\_PAGER

### EMS_AB_TELETEX_TERMINAL_IDENTIFIER {#EMS-AB-TELETEX-TERMINAL-IDENTIFIER}
```
public static final PidTagPropertyDescriptor EMS_AB_TELETEX_TERMINAL_IDENTIFIER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TELETEX\_TERMINAL\_IDENTIFIER

### EMS_AB_TEMP_ASSOC_THRESHOLD {#EMS-AB-TEMP-ASSOC-THRESHOLD}
```
public static final PidTagPropertyDescriptor EMS_AB_TEMP_ASSOC_THRESHOLD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TEMP\_ASSOC\_THRESHOLD

### EMS_AB_TOMBSTONE_LIFETIME {#EMS-AB-TOMBSTONE-LIFETIME}
```
public static final PidTagPropertyDescriptor EMS_AB_TOMBSTONE_LIFETIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TOMBSTONE\_LIFETIME

### EMS_AB_TRACKING_LOG_PATH_NAME {#EMS-AB-TRACKING-LOG-PATH-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_TRACKING_LOG_PATH_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TRACKING\_LOG\_PATH\_NAME

### EMS_AB_TRANSFER_RETRY_INTERVAL {#EMS-AB-TRANSFER-RETRY-INTERVAL}
```
public static final PidTagPropertyDescriptor EMS_AB_TRANSFER_RETRY_INTERVAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TRANSFER\_RETRY\_INTERVAL

### EMS_AB_TRANSFER_TIMEOUT_NON_URGENT {#EMS-AB-TRANSFER-TIMEOUT-NON-URGENT}
```
public static final PidTagPropertyDescriptor EMS_AB_TRANSFER_TIMEOUT_NON_URGENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TRANSFER\_TIMEOUT\_NON\_URGENT

### EMS_AB_TRANSFER_TIMEOUT_NORMAL {#EMS-AB-TRANSFER-TIMEOUT-NORMAL}
```
public static final PidTagPropertyDescriptor EMS_AB_TRANSFER_TIMEOUT_NORMAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TRANSFER\_TIMEOUT\_NORMAL

### EMS_AB_TRANSFER_TIMEOUT_URGENT {#EMS-AB-TRANSFER-TIMEOUT-URGENT}
```
public static final PidTagPropertyDescriptor EMS_AB_TRANSFER_TIMEOUT_URGENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TRANSFER\_TIMEOUT\_URGENT

### EMS_AB_TRANSLATION_TABLE_USED {#EMS-AB-TRANSLATION-TABLE-USED}
```
public static final PidTagPropertyDescriptor EMS_AB_TRANSLATION_TABLE_USED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TRANSLATION\_TABLE\_USED

### EMS_AB_TRANSPORT_EXPEDITED_DATA {#EMS-AB-TRANSPORT-EXPEDITED-DATA}
```
public static final PidTagPropertyDescriptor EMS_AB_TRANSPORT_EXPEDITED_DATA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TRANSPORT\_EXPEDITED\_DATA

### EMS_AB_TRANS_RETRY_MINS {#EMS-AB-TRANS-RETRY-MINS}
```
public static final PidTagPropertyDescriptor EMS_AB_TRANS_RETRY_MINS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TRANS\_RETRY\_MINS

### EMS_AB_TRANS_TIMEOUT_MINS {#EMS-AB-TRANS-TIMEOUT-MINS}
```
public static final PidTagPropertyDescriptor EMS_AB_TRANS_TIMEOUT_MINS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TRANS\_TIMEOUT\_MINS

### EMS_AB_TRUST_LEVEL {#EMS-AB-TRUST-LEVEL}
```
public static final PidTagPropertyDescriptor EMS_AB_TRUST_LEVEL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TRUST\_LEVEL

### EMS_AB_TURN_REQUEST_THRESHOLD {#EMS-AB-TURN-REQUEST-THRESHOLD}
```
public static final PidTagPropertyDescriptor EMS_AB_TURN_REQUEST_THRESHOLD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TURN\_REQUEST\_THRESHOLD

### EMS_AB_TWO_WAY_ALTERNATE_FACILITY {#EMS-AB-TWO-WAY-ALTERNATE-FACILITY}
```
public static final PidTagPropertyDescriptor EMS_AB_TWO_WAY_ALTERNATE_FACILITY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TWO\_WAY\_ALTERNATE\_FACILITY

### EMS_AB_TYPE {#EMS-AB-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_TYPE

### EMS_AB_T_SELECTOR {#EMS-AB-T-SELECTOR}
```
public static final PidTagPropertyDescriptor EMS_AB_T_SELECTOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_T\_SELECTOR

### EMS_AB_T_SELECTOR_INBOUND {#EMS-AB-T-SELECTOR-INBOUND}
```
public static final PidTagPropertyDescriptor EMS_AB_T_SELECTOR_INBOUND
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_T\_SELECTOR\_INBOUND

### EMS_AB_UNAUTH_ORIG_BL {#EMS-AB-UNAUTH-ORIG-BL}
```
public static final PidTagPropertyDescriptor EMS_AB_UNAUTH_ORIG_BL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_UNAUTH\_ORIG\_BL

### EMS_AB_UNAUTH_ORIG_BL_O {#EMS-AB-UNAUTH-ORIG-BL-O}
```
public static final PidTagPropertyDescriptor EMS_AB_UNAUTH_ORIG_BL_O
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_UNAUTH\_ORIG\_BL\_O

### EMS_AB_USENET_SITE_NAME {#EMS-AB-USENET-SITE-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_USENET_SITE_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_USENET\_SITE\_NAME

### EMS_AB_USER_PASSWORD {#EMS-AB-USER-PASSWORD}
```
public static final PidTagPropertyDescriptor EMS_AB_USER_PASSWORD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_USER\_PASSWORD

### EMS_AB_USE_SERVER_VALUES {#EMS-AB-USE-SERVER-VALUES}
```
public static final PidTagPropertyDescriptor EMS_AB_USE_SERVER_VALUES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_USE\_SERVER\_VALUES

### EMS_AB_USE_SITE_VALUES {#EMS-AB-USE-SITE-VALUES}
```
public static final PidTagPropertyDescriptor EMS_AB_USE_SITE_VALUES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_USE\_SITE\_VALUES

### EMS_AB_USN_CHANGED {#EMS-AB-USN-CHANGED}
```
public static final PidTagPropertyDescriptor EMS_AB_USN_CHANGED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_USN\_CHANGED

### EMS_AB_USN_CREATED {#EMS-AB-USN-CREATED}
```
public static final PidTagPropertyDescriptor EMS_AB_USN_CREATED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_USN\_CREATED

### EMS_AB_USN_DSA_LAST_OBJ_REMOVED {#EMS-AB-USN-DSA-LAST-OBJ-REMOVED}
```
public static final PidTagPropertyDescriptor EMS_AB_USN_DSA_LAST_OBJ_REMOVED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_USN\_DSA\_LAST\_OBJ\_REMOVED

### EMS_AB_USN_INTERSITE {#EMS-AB-USN-INTERSITE}
```
public static final PidTagPropertyDescriptor EMS_AB_USN_INTERSITE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_USN\_INTERSITE

### EMS_AB_USN_LAST_OBJ_REM {#EMS-AB-USN-LAST-OBJ-REM}
```
public static final PidTagPropertyDescriptor EMS_AB_USN_LAST_OBJ_REM
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_USN\_LAST\_OBJ\_REM

### EMS_AB_USN_SOURCE {#EMS-AB-USN-SOURCE}
```
public static final PidTagPropertyDescriptor EMS_AB_USN_SOURCE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_USN\_SOURCE

### EMS_AB_VIEW_CONTAINER_1 {#EMS-AB-VIEW-CONTAINER-1}
```
public static final PidTagPropertyDescriptor EMS_AB_VIEW_CONTAINER_1
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VIEW\_CONTAINER\_1

### EMS_AB_VIEW_CONTAINER_2 {#EMS-AB-VIEW-CONTAINER-2}
```
public static final PidTagPropertyDescriptor EMS_AB_VIEW_CONTAINER_2
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VIEW\_CONTAINER\_2

### EMS_AB_VIEW_CONTAINER_3 {#EMS-AB-VIEW-CONTAINER-3}
```
public static final PidTagPropertyDescriptor EMS_AB_VIEW_CONTAINER_3
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VIEW\_CONTAINER\_3

### EMS_AB_VIEW_DEFINITION {#EMS-AB-VIEW-DEFINITION}
```
public static final PidTagPropertyDescriptor EMS_AB_VIEW_DEFINITION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VIEW\_DEFINITION

### EMS_AB_VIEW_FLAGS {#EMS-AB-VIEW-FLAGS}
```
public static final PidTagPropertyDescriptor EMS_AB_VIEW_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VIEW\_FLAGS

### EMS_AB_VIEW_SITE {#EMS-AB-VIEW-SITE}
```
public static final PidTagPropertyDescriptor EMS_AB_VIEW_SITE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VIEW\_SITE

### EMS_AB_VOICE_MAIL_FLAGS {#EMS-AB-VOICE-MAIL-FLAGS}
```
public static final PidTagPropertyDescriptor EMS_AB_VOICE_MAIL_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VOICE\_MAIL\_FLAGS

### EMS_AB_VOICE_MAIL_GREETINGS {#EMS-AB-VOICE-MAIL-GREETINGS}
```
public static final PidTagPropertyDescriptor EMS_AB_VOICE_MAIL_GREETINGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VOICE\_MAIL\_GREETINGS

### EMS_AB_VOICE_MAIL_PASSWORD {#EMS-AB-VOICE-MAIL-PASSWORD}
```
public static final PidTagPropertyDescriptor EMS_AB_VOICE_MAIL_PASSWORD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VOICE\_MAIL\_PASSWORD

### EMS_AB_VOICE_MAIL_RECORDED_NAME {#EMS-AB-VOICE-MAIL-RECORDED-NAME}
```
public static final PidTagPropertyDescriptor EMS_AB_VOICE_MAIL_RECORDED_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VOICE\_MAIL\_RECORDED\_NAME

### EMS_AB_VOICE_MAIL_RECORDING_LENGTH {#EMS-AB-VOICE-MAIL-RECORDING-LENGTH}
```
public static final PidTagPropertyDescriptor EMS_AB_VOICE_MAIL_RECORDING_LENGTH
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VOICE\_MAIL\_RECORDING\_LENGTH

### EMS_AB_VOICE_MAIL_SPEED {#EMS-AB-VOICE-MAIL-SPEED}
```
public static final PidTagPropertyDescriptor EMS_AB_VOICE_MAIL_SPEED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VOICE\_MAIL\_SPEED

### EMS_AB_VOICE_MAIL_SYSTEM_GUID {#EMS-AB-VOICE-MAIL-SYSTEM-GUID}
```
public static final PidTagPropertyDescriptor EMS_AB_VOICE_MAIL_SYSTEM_GUID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VOICE\_MAIL\_SYSTEM\_GUID

### EMS_AB_VOICE_MAIL_USER_ID {#EMS-AB-VOICE-MAIL-USER-ID}
```
public static final PidTagPropertyDescriptor EMS_AB_VOICE_MAIL_USER_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VOICE\_MAIL\_USER\_ID

### EMS_AB_VOICE_MAIL_VOLUME {#EMS-AB-VOICE-MAIL-VOLUME}
```
public static final PidTagPropertyDescriptor EMS_AB_VOICE_MAIL_VOLUME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_VOICE\_MAIL\_VOLUME

### EMS_AB_WWW_HOME_PAGE {#EMS-AB-WWW-HOME-PAGE}
```
public static final PidTagPropertyDescriptor EMS_AB_WWW_HOME_PAGE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_WWW\_HOME\_PAGE

### EMS_AB_XMIT_TIMEOUT_NON_URGENT {#EMS-AB-XMIT-TIMEOUT-NON-URGENT}
```
public static final PidTagPropertyDescriptor EMS_AB_XMIT_TIMEOUT_NON_URGENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_XMIT\_TIMEOUT\_NON\_URGENT

### EMS_AB_XMIT_TIMEOUT_NORMAL {#EMS-AB-XMIT-TIMEOUT-NORMAL}
```
public static final PidTagPropertyDescriptor EMS_AB_XMIT_TIMEOUT_NORMAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_XMIT\_TIMEOUT\_NORMAL

### EMS_AB_XMIT_TIMEOUT_URGENT {#EMS-AB-XMIT-TIMEOUT-URGENT}
```
public static final PidTagPropertyDescriptor EMS_AB_XMIT_TIMEOUT_URGENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_XMIT\_TIMEOUT\_URGENT

### EMS_AB_X_121_ADDRESS {#EMS-AB-X-121-ADDRESS}
```
public static final PidTagPropertyDescriptor EMS_AB_X_121_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X121\_ADDRESS

### EMS_AB_X_25_CALL_USER_DATA_INCOMING {#EMS-AB-X-25-CALL-USER-DATA-INCOMING}
```
public static final PidTagPropertyDescriptor EMS_AB_X_25_CALL_USER_DATA_INCOMING
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X25\_CALL\_USER\_DATA\_INCOMING

### EMS_AB_X_25_CALL_USER_DATA_OUTGOING {#EMS-AB-X-25-CALL-USER-DATA-OUTGOING}
```
public static final PidTagPropertyDescriptor EMS_AB_X_25_CALL_USER_DATA_OUTGOING
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X25\_CALL\_USER\_DATA\_OUTGOING

### EMS_AB_X_25_FACILITIES_DATA_INCOMING {#EMS-AB-X-25-FACILITIES-DATA-INCOMING}
```
public static final PidTagPropertyDescriptor EMS_AB_X_25_FACILITIES_DATA_INCOMING
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X25\_FACILITIES\_DATA\_INCOMING

### EMS_AB_X_25_FACILITIES_DATA_OUTGOING {#EMS-AB-X-25-FACILITIES-DATA-OUTGOING}
```
public static final PidTagPropertyDescriptor EMS_AB_X_25_FACILITIES_DATA_OUTGOING
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X25\_FACILITIES\_DATA\_OUTGOING

### EMS_AB_X_25_LEASED_LINE_PORT {#EMS-AB-X-25-LEASED-LINE-PORT}
```
public static final PidTagPropertyDescriptor EMS_AB_X_25_LEASED_LINE_PORT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X25\_LEASED\_LINE\_PORT

### EMS_AB_X_25_LEASED_OR_SWITCHED {#EMS-AB-X-25-LEASED-OR-SWITCHED}
```
public static final PidTagPropertyDescriptor EMS_AB_X_25_LEASED_OR_SWITCHED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X25\_LEASED\_OR\_SWITCHED

### EMS_AB_X_25_REMOTE_MTA_PHONE {#EMS-AB-X-25-REMOTE-MTA-PHONE}
```
public static final PidTagPropertyDescriptor EMS_AB_X_25_REMOTE_MTA_PHONE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X25\_REMOTE\_MTA\_PHONE

### EMS_AB_X_400_ATTACHMENT_TYPE {#EMS-AB-X-400-ATTACHMENT-TYPE}
```
public static final PidTagPropertyDescriptor EMS_AB_X_400_ATTACHMENT_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X400\_ATTACHMENT\_TYPE

### EMS_AB_X_400_SELECTOR_SYNTAX {#EMS-AB-X-400-SELECTOR-SYNTAX}
```
public static final PidTagPropertyDescriptor EMS_AB_X_400_SELECTOR_SYNTAX
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X400\_SELECTOR\_SYNTAX

### EMS_AB_X_500_ACCESS_CONTROL_LIST {#EMS-AB-X-500-ACCESS-CONTROL-LIST}
```
public static final PidTagPropertyDescriptor EMS_AB_X_500_ACCESS_CONTROL_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X500\_ACCESS\_CONTROL\_LIST

### EMS_AB_X_500_NC {#EMS-AB-X-500-NC}
```
public static final PidTagPropertyDescriptor EMS_AB_X_500_NC
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X500\_NC

### EMS_AB_X_500_RDN {#EMS-AB-X-500-RDN}
```
public static final PidTagPropertyDescriptor EMS_AB_X_500_RDN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EMS\_AB\_X500\_RDN

### END_DATE {#END-DATE}
```
public static final PidTagPropertyDescriptor END_DATE
```


Contains the value of the PidLidAppointmentEndWhole property (section 2.14). Area: MapiEnvelope Property set Canonical name: PidTagEndDate Alternate names: PR\_END\_DATE, http://schemas.microsoft.com/mapi/end\_date

### END_RECURRENCE_DATE {#END-RECURRENCE-DATE}
```
public static final PidLidPropertyDescriptor END_RECURRENCE_DATE
```


Identifies the end date of the recurrence range. Area: Meetings Canonical name: PidLidEndRecurrenceDate Alternate names: LID\_END\_RECUR\_DATE

### END_RECURRENCE_TIME {#END-RECURRENCE-TIME}
```
public static final PidLidPropertyDescriptor END_RECURRENCE_TIME
```


Identifies the end time of the recurrence range. Area: Meetings Canonical name: PidLidEndRecurrenceTime Alternate names: LID\_END\_RECUR\_TIME

### ENTRY_ID {#ENTRY-ID}
```
public static final PidTagPropertyDescriptor ENTRY_ID
```


Contains the information to identify many different types of messaging objects. Area: ID Properties Canonical name: PidTagEntryId Alternate names: PR\_ENTRYID, ptagEntryId

### EVENTS_ROOT_FOLDER_ENTRYID {#EVENTS-ROOT-FOLDER-ENTRYID}
```
public static final PidTagPropertyDescriptor EVENTS_ROOT_FOLDER_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EVENTS\_ROOT\_FOLDER\_ENTRYID

### EXCEPTION_END_TIME {#EXCEPTION-END-TIME}
```
public static final PidTagPropertyDescriptor EXCEPTION_END_TIME
```


Contains the end date and time of the exception in the local time zone of the computer when the exception is created. Area: MessageClassDefinedNonTransmittable Canonical name: PidTagExceptionEndTime Alternate names: PR\_EXCEPTION\_ENDTIME, ptagExceptionEndTime

### EXCEPTION_REPLACE_TIME {#EXCEPTION-REPLACE-TIME}
```
public static final PidLidPropertyDescriptor EXCEPTION_REPLACE_TIME
```


Specifies the date and time, in UTC, within a recurrence pattern that an exception will replace. Area: Calendar Canonical name: PidLidExceptionReplaceTime Alternate names: dispidExceptionReplaceTime

### EXCEPTION_START_TIME {#EXCEPTION-START-TIME}
```
public static final PidTagPropertyDescriptor EXCEPTION_START_TIME
```


Contains the start date and time of the exception in the local time zone of the computer when the exception is created. Area: MessageClassDefinedNonTransmittable Canonical name: PidTagExceptionStartTime Alternate names: PR\_EXCEPTION\_STARTTIME, ptagExceptionStartTime

### EXCESS_STORAGE_USED {#EXCESS-STORAGE-USED}
```
public static final PidTagPropertyDescriptor EXCESS_STORAGE_USED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EXCESS\_STORAGE\_USED

### EXCHANGE_INTENDED_BUSY_STATUS {#EXCHANGE-INTENDED-BUSY-STATUS}
```
public static final PidNamePropertyDescriptor EXCHANGE_INTENDED_BUSY_STATUS
```


Specifies the intended free/busy status of a meeting in a Meeting request. Area: Common Canonical name: PidNameExchangeIntendedBusyStatus Alternate names: http://schemas.microsoft.com/exchange/intendedbusystatus

### EXCHANGE_JUNK_EMAIL_MOVE_STAMP {#EXCHANGE-JUNK-EMAIL-MOVE-STAMP}
```
public static final PidNamePropertyDescriptor EXCHANGE_JUNK_EMAIL_MOVE_STAMP
```


Indicates that the message is not to be processed by a spam filter. Area: Secure Messaging Properties Canonical name: PidNameExchangeJunkEmailMoveStamp Alternate names: http://schemas.microsoft.com/exchange/junkemailmovestamp

### EXCHANGE_MODIFY_EXCEPTION_STRUCTURE {#EXCHANGE-MODIFY-EXCEPTION-STRUCTURE}
```
public static final PidNamePropertyDescriptor EXCHANGE_MODIFY_EXCEPTION_STRUCTURE
```


Specifies a structure that modifies an exception to the recurrence. Area: Common Canonical name: PidNameExchangeModifyExceptionStructure Alternate names: http://schemas.microsoft.com/exchange/modifyexceptionstruct

### EXCHANGE_NO_MODIFY_EXCEPTIONS {#EXCHANGE-NO-MODIFY-EXCEPTIONS}
```
public static final PidNamePropertyDescriptor EXCHANGE_NO_MODIFY_EXCEPTIONS
```


Indicates whether exceptions to a recurring appointment can be modified. Area: Common Canonical name: PidNameExchangeNoModifyExceptions Alternate names: http://schemas.microsoft.com/exchange/nomodifyexceptions

### EXCHANGE_NT_SECURITY_DESCRIPTOR {#EXCHANGE-NT-SECURITY-DESCRIPTOR}
```
public static final PidTagPropertyDescriptor EXCHANGE_NT_SECURITY_DESCRIPTOR
```


Contains the calculated security descriptor for the item. Area: Calendar Document Canonical name: PidTagExchangeNTSecurityDescriptor Alternate names: http://schemas.microsoft.com/exchange/ntsecuritydescriptor,

### EXCHANGE_PATTERN_END {#EXCHANGE-PATTERN-END}
```
public static final PidNamePropertyDescriptor EXCHANGE_PATTERN_END
```


Identifies the maximum time when an instance of a recurring appointment ends. Area: Common Canonical name: PidNameExchangePatternEnd Alternate names: http://schemas.microsoft.com/exchange/patternend

### EXCHANGE_PATTERN_START {#EXCHANGE-PATTERN-START}
```
public static final PidNamePropertyDescriptor EXCHANGE_PATTERN_START
```


Identifies the absolute minimum time when an instance of a recurring appointment starts. Area: Common Canonical name: PidNameExchangePatternStart Alternate names: http://schemas.microsoft.com/exchange/patternstart

### EXCHANGE_REMINDER_INTERVAL {#EXCHANGE-REMINDER-INTERVAL}
```
public static final PidNamePropertyDescriptor EXCHANGE_REMINDER_INTERVAL
```


Identifies the time, in seconds, between reminders. Area: Common Canonical name: PidNameExchangeReminderInterval Alternate names: http://schemas.microsoft.com/exchange/reminderinterval

### EXCH_DATABASE_SCHEMA {#EXCH-DATABASE-SCHEMA}
```
public static final PidNamePropertyDescriptor EXCH_DATABASE_SCHEMA
```


Specifies an array of URLs that identifies other folders within the same message store that contain schema definition items. Area: Common Canonical name: PidNameExchDatabaseSchema Alternate names: urn:schemas-microsoft-com:exch-data:baseschema

### EXCH_DATA_EXPECTED_CONTENT_CLASS {#EXCH-DATA-EXPECTED-CONTENT-CLASS}
```
public static final PidNamePropertyDescriptor EXCH_DATA_EXPECTED_CONTENT_CLASS
```


Specifies an array of names that indicates the expected content classes of items within a folder. Area: Common Canonical name: PidNameExchDataExpectedContentClass Alternate names: urn:schemas-microsoft-com:exch-data:expected-content-class

### EXCH_DATA_SCHEMA_COLLECTION_REFERENCE {#EXCH-DATA-SCHEMA-COLLECTION-REFERENCE}
```
public static final PidNamePropertyDescriptor EXCH_DATA_SCHEMA_COLLECTION_REFERENCE
```


Specifies an array of names that indicates the expected content classes of items within a folder. Area: Common Canonical name: PidNameExchDataSchemaCollectionReference Alternate names: urn:schemas-microsoft-com:exch-data:schema-collection-ref

### EXPIRY_NUMBER {#EXPIRY-NUMBER}
```
public static final PidTagPropertyDescriptor EXPIRY_NUMBER
```


Contains an integer value that is used along with the PidTagExpiryUnits property (section 2.681) to define the expiry send time. Area: MapiStatus Canonical name: PidTagExpiryNumber Alternate names: PR\_EXPIRY\_NUMBER

### EXPIRY_TIME {#EXPIRY-TIME}
```
public static final PidTagPropertyDescriptor EXPIRY_TIME
```


Contains the time, in UTC, after which a client wants to receive an expiry event if the message arrives late. Area: MapiEnvelope Canonical name: PidTagExpiryTime Alternate names: PR\_EXPIRY\_TIME, ptagExpiryTime, urn:schemas:httpmail:expiry-date,

### EXPIRY_UNITS {#EXPIRY-UNITS}
```
public static final PidTagPropertyDescriptor EXPIRY_UNITS
```


Contains the unit of time that the value of the PidTagExpiryNumber property (section 2.679) multiplies. Area: MapiStatus Canonical name: PidTagExpiryUnits Alternate names: PR\_EXPIRY\_UNITS

### EXPLICIT_CONVERSION {#EXPLICIT-CONVERSION}
```
public static final PidTagPropertyDescriptor EXPLICIT_CONVERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EXPLICIT\_CONVERSION

### EXTENDED_ACL_DATA {#EXTENDED-ACL-DATA}
```
public static final PidTagPropertyDescriptor EXTENDED_ACL_DATA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_EXTENDED\_ACL\_DATA

### EXTENDED_FOLDER_FLAGS {#EXTENDED-FOLDER-FLAGS}
```
public static final PidTagPropertyDescriptor EXTENDED_FOLDER_FLAGS
```


Contains encoded sub-properties for a folder. Area: MapiContainer Canonical name: PidTagExtendedFolderFlags Alternate names: PR\_EXTENDED\_FOLDER\_FLAGS, ptagExtendedFolderFlags

### EXTENDED_RULE_MESSAGE_ACTIONS {#EXTENDED-RULE-MESSAGE-ACTIONS}
```
public static final PidTagPropertyDescriptor EXTENDED_RULE_MESSAGE_ACTIONS
```


Contains action information about named properties used in the rule. Area: Rules Canonical name: PidTagExtendedRuleMessageActions Alternate names: PR\_EXTENDED\_RULE\_MSG\_ACTIONS

### EXTENDED_RULE_MESSAGE_CONDITION {#EXTENDED-RULE-MESSAGE-CONDITION}
```
public static final PidTagPropertyDescriptor EXTENDED_RULE_MESSAGE_CONDITION
```


Contains condition information about named properties used in the rule. Area: Rules Canonical name: PidTagExtendedRuleMessageCondition Alternate names: PR\_EXTENDED\_RULE\_MSG\_CONDITION

### EXTENDED_RULE_SIZE_LIMIT {#EXTENDED-RULE-SIZE-LIMIT}
```
public static final PidTagPropertyDescriptor EXTENDED_RULE_SIZE_LIMIT
```


Contains the maximum size, in bytes, that the user is allowed to accumulate for a single extended rule. Area: Rules Canonical name: PidTagExtendedRuleSizeLimit Alternate names: PR\_EXTENDED\_RULE\_SIZE\_LIMIT

### EXTRACTED_ADDRESSES {#EXTRACTED-ADDRESSES}
```
public static final PidNamePropertyDescriptor EXTRACTED_ADDRESSES
```


Contains an XML document with a single AddressSet element. Area: Extracted Entities Canonical name: PidNameExtractedAddresses Alternate names: dispidXmlExtractedAddresses

### EXTRACTED_CONTACTS {#EXTRACTED-CONTACTS}
```
public static final PidNamePropertyDescriptor EXTRACTED_CONTACTS
```


Contains an XML document with a single ContactSet element. Area: Extracted Entities Canonical name: PidNameExtractedContacts Alternate names: dispidXmlExtractedContacts

### EXTRACTED_EMAILS {#EXTRACTED-EMAILS}
```
public static final PidNamePropertyDescriptor EXTRACTED_EMAILS
```


Contains an XML document with a single EmailSet element. Area: Extracted Entities Canonical name: PidNameExtractedEmails Alternate names: dispidXmlExtractedEmails

### EXTRACTED_MEETINGS {#EXTRACTED-MEETINGS}
```
public static final PidNamePropertyDescriptor EXTRACTED_MEETINGS
```


Contains an XML document with a single MeetingSet element. Area: Extracted Entities Canonical name: PidNameExtractedMeetings Alternate names: dispidXmlExtractedMeetings

### EXTRACTED_PHONES {#EXTRACTED-PHONES}
```
public static final PidNamePropertyDescriptor EXTRACTED_PHONES
```


Contains an XML document with a single PhoneSet element. Area: Extracted Entities Canonical name: PidNameExtractedPhones Alternate names: dispidXmlExtractedPhones

### EXTRACTED_TASKS {#EXTRACTED-TASKS}
```
public static final PidNamePropertyDescriptor EXTRACTED_TASKS
```


Contains an XML document with a single TaskSet element. Area: Extracted Entities Canonical name: PidNameExtractedTasks Alternate names: dispidXmlExtractedTasks

### EXTRACTED_URLS {#EXTRACTED-URLS}
```
public static final PidNamePropertyDescriptor EXTRACTED_URLS
```


Contains an XML document with a single UrlSet element. Area: Extracted Entities Canonical name: PidNameExtractedUrls Alternate names: dispidXmlExtractedUrls

### EX_CURRENT_VERSION {#EX-CURRENT-VERSION}
```
public static final PidTagPropertyDescriptor EX_CURRENT_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_CURRENT\_VERSION

### EX_SECURITY {#EX-SECURITY}
```
public static final PidTagPropertyDescriptor EX_SECURITY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SECURITY

### FAST_TRANSFER {#FAST-TRANSFER}
```
public static final PidTagPropertyDescriptor FAST_TRANSFER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FAST\_TRANSFER

### FAVORITES_DEFAULT_NAME {#FAVORITES-DEFAULT-NAME}
```
public static final PidTagPropertyDescriptor FAVORITES_DEFAULT_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FAVORITES\_DEFAULT\_NAME

### FAX_1_ADDRESS_TYPE {#FAX-1-ADDRESS-TYPE}
```
public static final PidLidPropertyDescriptor FAX_1_ADDRESS_TYPE
```


Contains the string value "FAX". Area: Contact Properties Canonical name: PidLidFax1AddressType Alternate names: dispidFax1AddrType

### FAX_1_EMAIL_ADDRESS {#FAX-1-EMAIL-ADDRESS}
```
public static final PidLidPropertyDescriptor FAX_1_EMAIL_ADDRESS
```


Contains a user-readable display name, followed by the "@" character, followed by a fax number. Area: Contact Properties Canonical name: PidLidFax1EmailAddress Alternate names: dispidFax1EmailAddress

### FAX_1_ORIGINAL_DISPLAY_NAME {#FAX-1-ORIGINAL-DISPLAY-NAME}
```
public static final PidLidPropertyDescriptor FAX_1_ORIGINAL_DISPLAY_NAME
```


Contains the same value as the PidTagNormalizedSubject property (section 2.803). Area: Contact Properties Canonical name: PidLidFax1OriginalDisplayName Alternate names: dispidFax1OriginalDisplayName

### FAX_1_ORIGINAL_ENTRY_ID {#FAX-1-ORIGINAL-ENTRY-ID}
```
public static final PidLidPropertyDescriptor FAX_1_ORIGINAL_ENTRY_ID
```


Specifies a one-off EntryID that corresponds to this fax address. Area: Contact Properties Canonical name: PidLidFax1OriginalEntryId Alternate names: dispidFax1OriginalEntryID

### FAX_2_ADDRESS_TYPE {#FAX-2-ADDRESS-TYPE}
```
public static final PidLidPropertyDescriptor FAX_2_ADDRESS_TYPE
```


Contains the string value "FAX". Area: Contact Properties Canonical name: PidLidFax2AddressType Alternate names: dispidFax2AddrType

### FAX_2_EMAIL_ADDRESS {#FAX-2-EMAIL-ADDRESS}
```
public static final PidLidPropertyDescriptor FAX_2_EMAIL_ADDRESS
```


Contains a user-readable display name, followed by the "@" character, followed by a fax number. Area: Contact Properties Canonical name: PidLidFax2EmailAddress Alternate names: dispidFax2EmailAddress

### FAX_2_ORIGINAL_DISPLAY_NAME {#FAX-2-ORIGINAL-DISPLAY-NAME}
```
public static final PidLidPropertyDescriptor FAX_2_ORIGINAL_DISPLAY_NAME
```


Contains the same value as the PidTagNormalizedSubject property (section 2.803). Area: Contact Properties Canonical name: PidLidFax2OriginalDisplayName Alternate names: dispidFax2OriginalDisplayName

### FAX_2_ORIGINAL_ENTRY_ID {#FAX-2-ORIGINAL-ENTRY-ID}
```
public static final PidLidPropertyDescriptor FAX_2_ORIGINAL_ENTRY_ID
```


Specifies a one-off EntryID corresponding to this fax address. Area: Contact Properties Canonical name: PidLidFax2OriginalEntryId Alternate names: dispidFax2OriginalEntryID

### FAX_3_ADDRESS_TYPE {#FAX-3-ADDRESS-TYPE}
```
public static final PidLidPropertyDescriptor FAX_3_ADDRESS_TYPE
```


Contains the string value "FAX". Area: Contact Properties Canonical name: PidLidFax3AddressType Alternate names: dispidFax3AddrType

### FAX_3_EMAIL_ADDRESS {#FAX-3-EMAIL-ADDRESS}
```
public static final PidLidPropertyDescriptor FAX_3_EMAIL_ADDRESS
```


Contains a user-readable display name, followed by the "@" character, followed by a fax number. Area: Contact Properties Canonical name: PidLidFax3EmailAddress Alternate names: dispidFax3EmailAddress

### FAX_3_ORIGINAL_DISPLAY_NAME {#FAX-3-ORIGINAL-DISPLAY-NAME}
```
public static final PidLidPropertyDescriptor FAX_3_ORIGINAL_DISPLAY_NAME
```


Contains the same value as the PidTagNormalizedSubject property (section 2.803). Area: Contact Properties Canonical name: PidLidFax3OriginalDisplayName Alternate names: dispidFax3OriginalDisplayName

### FAX_3_ORIGINAL_ENTRY_ID {#FAX-3-ORIGINAL-ENTRY-ID}
```
public static final PidLidPropertyDescriptor FAX_3_ORIGINAL_ENTRY_ID
```


Specifies a one-off EntryID that corresponds to this fax address. Area: Contact Properties Canonical name: PidLidFax3OriginalEntryId Alternate names: dispidFax3OriginalEntryID

### FAX_NUMBER_OF_PAGES {#FAX-NUMBER-OF-PAGES}
```
public static final PidTagPropertyDescriptor FAX_NUMBER_OF_PAGES
```


Contains the number of pages in a Fax object. Area: Unified Messaging Canonical name: PidTagFaxNumberOfPages Alternate names: InternalSchemaFaxNumberOfPages

### FILE_UNDER {#FILE-UNDER}
```
public static final PidLidPropertyDescriptor FILE_UNDER
```


Specifies the name under which to file a contact when displaying a list of contacts. Area: Contact Properties Canonical name: PidLidFileUnder Alternate names: dispidFileUnder

### FILE_UNDER_ID {#FILE-UNDER-ID}
```
public static final PidLidPropertyDescriptor FILE_UNDER_ID
```


Specifies how to generate and recompute the value of the PidLidFileUnder property (section 2.132) when other contact name properties change. Area: Contact Properties Canonical name: PidLidFileUnderId Alternate names: dispidFileUnderId

### FILE_UNDER_LIST {#FILE-UNDER-LIST}
```
public static final PidLidPropertyDescriptor FILE_UNDER_LIST
```


Specifies a list of possible values for the PidLidFileUnderId property (section 2.133). Area: Contact Properties Canonical name: PidLidFileUnderList Alternate names: dispidFileUnderList

### FILTERING_HOOKS {#FILTERING-HOOKS}
```
public static final PidTagPropertyDescriptor FILTERING_HOOKS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FILTERING\_HOOKS

### FINDER_ENTRYID {#FINDER-ENTRYID}
```
public static final PidTagPropertyDescriptor FINDER_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FINDER\_ENTRYID

### FLAG_COMPLETE_TIME {#FLAG-COMPLETE-TIME}
```
public static final PidTagPropertyDescriptor FLAG_COMPLETE_TIME
```


Specifies the date and time, in UTC, that the Message object was flagged as complete. Area: Miscellaneous Properties Canonical name: PidTagFlagCompleteTime Alternate names: PR\_FLAG\_COMPLETE\_TIME, ptagFlagCompleteTime,

### FLAG_REQUEST {#FLAG-REQUEST}
```
public static final PidLidPropertyDescriptor FLAG_REQUEST
```


Contains user-specifiable text to be associated with the flag. Area: Flagging Canonical name: PidLidFlagRequest Alternate names: dispidRequest

### FLAG_STATUS {#FLAG-STATUS}
```
public static final PidTagPropertyDescriptor FLAG_STATUS
```


Specifies the flag state of the Message object. Area: Miscellaneous Properties Canonical name: PidTagFlagStatus Alternate names: PR\_FLAG\_STATUS, ptagFlagStatus

### FLAG_STRING {#FLAG-STRING}
```
public static final PidLidPropertyDescriptor FLAG_STRING
```


Contains an index identifying one of a set of pre-defined text strings to be associated with the flag. Area: Tasks Canonical name: PidLidFlagString Alternate names: dispidFlagStringEnum

### FLAT_URL_NAME {#FLAT-URL-NAME}
```
public static final PidTagPropertyDescriptor FLAT_URL_NAME
```


Contains a unique identifier for an item across the message store. Area: ExchangeAdministrative Canonical name: PidTagFlatUrlName Alternate names: PR\_FLAT\_URL\_NAME, PR\_FLAT\_URL\_NAME\_A, PR\_FLAT\_URL\_NAME\_W,

### FOLDER_ASSOCIATED_CONTENTS {#FOLDER-ASSOCIATED-CONTENTS}
```
public static final PidTagPropertyDescriptor FOLDER_ASSOCIATED_CONTENTS
```


Identifies all FAI messages in the current folder. Area: MapiContainer Canonical name: PidTagFolderAssociatedContents Alternate names: PR\_FOLDER\_ASSOCIATED\_CONTENTS

### FOLDER_CHILD_COUNT {#FOLDER-CHILD-COUNT}
```
public static final PidTagPropertyDescriptor FOLDER_CHILD_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FOLDER\_CHILD\_COUNT

### FOLDER_DESIGN_FLAGS {#FOLDER-DESIGN-FLAGS}
```
public static final PidTagPropertyDescriptor FOLDER_DESIGN_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FOLDER\_DESIGN\_FLAGS

### FOLDER_FLAGS {#FOLDER-FLAGS}
```
public static final PidTagPropertyDescriptor FOLDER_FLAGS
```


Contains a computed value to specify the type or state of a folder. Area: ExchangeAdministrative Canonical name: PidTagFolderFlags Alternate names: PR\_FOLDER\_FLAGS

### FOLDER_ID {#FOLDER-ID}
```
public static final PidTagPropertyDescriptor FOLDER_ID
```


Contains the Folder ID (FID) ([MS-OXCDATA] section 2.2.1.1) of the folder. Area: ID Properties Canonical name: PidTagFolderId Alternate names: ptagFID

### FOLDER_PATHNAME {#FOLDER-PATHNAME}
```
public static final PidTagPropertyDescriptor FOLDER_PATHNAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FOLDER\_PATHNAME

### FOLDER_TYPE {#FOLDER-TYPE}
```
public static final PidTagPropertyDescriptor FOLDER_TYPE
```


Specifies the type of a folder that includes the Root folder, Generic folder, and Search folder. Area: MapiContainer Canonical name: PidTagFolderType Alternate names: PR\_FOLDER\_TYPE, ptagFolderType

### FOLLOWUP_ICON {#FOLLOWUP-ICON}
```
public static final PidTagPropertyDescriptor FOLLOWUP_ICON
```


Specifies the flag color of the Message object. Area: RenMessageFolder Canonical name: PidTagFollowupIcon Alternate names: PR\_FOLLOWUP\_ICON, ptagFollowupIcon

### FOREIGN_ID {#FOREIGN-ID}
```
public static final PidTagPropertyDescriptor FOREIGN_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FOREIGN\_ID

### FOREIGN_REPORT_ID {#FOREIGN-REPORT-ID}
```
public static final PidTagPropertyDescriptor FOREIGN_REPORT_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FOREIGN\_REPORT\_ID

### FOREIGN_SUBJECT_ID {#FOREIGN-SUBJECT-ID}
```
public static final PidTagPropertyDescriptor FOREIGN_SUBJECT_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FOREIGN\_SUBJECT\_ID

### FORM_CATEGORY {#FORM-CATEGORY}
```
public static final PidTagPropertyDescriptor FORM_CATEGORY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FORM\_CATEGORY

### FORM_CATEGORY_SUB {#FORM-CATEGORY-SUB}
```
public static final PidTagPropertyDescriptor FORM_CATEGORY_SUB
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FORM\_CATEGORY\_SUB

### FORM_CLSID {#FORM-CLSID}
```
public static final PidTagPropertyDescriptor FORM_CLSID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FORM\_CLSID

### FORM_CONTACT_NAME {#FORM-CONTACT-NAME}
```
public static final PidTagPropertyDescriptor FORM_CONTACT_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FORM\_CONTACT\_NAME

### FORM_DESIGNER_GUID {#FORM-DESIGNER-GUID}
```
public static final PidTagPropertyDescriptor FORM_DESIGNER_GUID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FORM\_DESIGNER\_GUID

### FORM_DESIGNER_NAME {#FORM-DESIGNER-NAME}
```
public static final PidTagPropertyDescriptor FORM_DESIGNER_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FORM\_DESIGNER\_NAME

### FORM_HIDDEN {#FORM-HIDDEN}
```
public static final PidTagPropertyDescriptor FORM_HIDDEN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FORM\_HIDDEN

### FORM_HOST_MAP {#FORM-HOST-MAP}
```
public static final PidTagPropertyDescriptor FORM_HOST_MAP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FORM\_HOST\_MAP

### FORM_MESSAGE_BEHAVIOR {#FORM-MESSAGE-BEHAVIOR}
```
public static final PidTagPropertyDescriptor FORM_MESSAGE_BEHAVIOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FORM\_MESSAGE\_BEHAVIOR

### FORM_VERSION {#FORM-VERSION}
```
public static final PidTagPropertyDescriptor FORM_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FORM\_VERSION

### FORWARD_INSTANCE {#FORWARD-INSTANCE}
```
public static final PidLidPropertyDescriptor FORWARD_INSTANCE
```


Indicates whether the Meeting Request object represents an exception to a recurring invitation sent by the organizer. Area: Meetings Canonical name: PidLidForwardInstance Alternate names: dispidFwrdInstance

### FORWARD_NOTIFICATION_RECIPIENTS {#FORWARD-NOTIFICATION-RECIPIENTS}
```
public static final PidLidPropertyDescriptor FORWARD_NOTIFICATION_RECIPIENTS
```


Contains a list of RecipientRow structures, as described in [MS-OXCDATA] section 2.8.3, that indicate the recipients of a meeting forward. Area: Meetings Canonical name: PidLidForwardNotificationRecipients Alternate names: dispidForwardNotificationRecipients

### FREE_BUSY_COUNT_MONTHS {#FREE-BUSY-COUNT-MONTHS}
```
public static final PidTagPropertyDescriptor FREE_BUSY_COUNT_MONTHS
```


Contains an integer value used to calculate the start and end dates of the range of free/busy data to be published to the public folders. Area: MessageClassDefinedTransmittable Canonical name: PidTagFreeBusyCountMonths Alternate names: PR\_FREEBUSY\_COUNT\_MONTHS

### FREE_BUSY_ENTRY_IDS {#FREE-BUSY-ENTRY-IDS}
```
public static final PidTagPropertyDescriptor FREE_BUSY_ENTRY_IDS
```


Contains EntryIDs of the Delegate Information object, the free/busy message of the "Freebusy Data". Area: MapiContainer Canonical name: PidTagFreeBusyEntryIds Alternate names: PR\_FREEBUSY\_ENTRYIDS, ptagFreeBusyEntryIds

### FREE_BUSY_FOR_LOCAL_SITE_ENTRYID {#FREE-BUSY-FOR-LOCAL-SITE-ENTRYID}
```
public static final PidTagPropertyDescriptor FREE_BUSY_FOR_LOCAL_SITE_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_FREE\_BUSY\_FOR\_LOCAL\_SITE\_ENTRYID

### FREE_BUSY_LOCATION {#FREE-BUSY-LOCATION}
```
public static final PidLidPropertyDescriptor FREE_BUSY_LOCATION
```


Specifies a URL path from which a client can retrieve free/busy status information for the contact. Area: Contact Properties Canonical name: PidLidFreeBusyLocation Alternate names: dispidFreeBusyLocation

### FREE_BUSY_MESSAGE_EMAIL_ADDRESS {#FREE-BUSY-MESSAGE-EMAIL-ADDRESS}
```
public static final PidTagPropertyDescriptor FREE_BUSY_MESSAGE_EMAIL_ADDRESS
```


Specifies the email address of the user or resource to whom this free/busy message applies. Area: MessageClassDefinedTransmittable Canonical name: PidTagFreeBusyMessageEmailAddress Alternate names: PR\_FREEBUSY\_EMA

### FREE_BUSY_PUBLISH_END {#FREE-BUSY-PUBLISH-END}
```
public static final PidTagPropertyDescriptor FREE_BUSY_PUBLISH_END
```


Specifies the end time, in UTC, of the publishing range. Area: Free/Busy Properties Canonical name: PidTagFreeBusyPublishEnd Alternate names: PR\_FREEBUSY\_PUBLISH\_END

### FREE_BUSY_PUBLISH_START {#FREE-BUSY-PUBLISH-START}
```
public static final PidTagPropertyDescriptor FREE_BUSY_PUBLISH_START
```


Specifies the start time, in UTC, of the publishing range. Area: Free/Busy Properties Canonical name: PidTagFreeBusyPublishStart Alternate names: PR\_FREEBUSY\_PUBLISH\_START

### FREE_BUSY_RANGE_TIMESTAMP {#FREE-BUSY-RANGE-TIMESTAMP}
```
public static final PidTagPropertyDescriptor FREE_BUSY_RANGE_TIMESTAMP
```


Specifies the time, in UTC, that the data was published. Area: Free/Busy Properties Canonical name: PidTagFreeBusyRangeTimestamp Alternate names: PR\_FREEBUSY\_RANGE\_TIMESTAMP

### FROM {#FROM}
```
public static final PidNamePropertyDescriptor FROM
```


Specifies the SMTP email alias of the organizer of an appointment or meeting. Area: Email Canonical name: PidNameFrom Alternate names: urn:schemas:calendar:organizer

### FTP_SITE {#FTP-SITE}
```
public static final PidTagPropertyDescriptor FTP_SITE
```


Contains the File Transfer Protocol (FTP) site address of the mail user. Area: MapiMailUser Canonical name: PidTagFtpSite Alternate names: PR\_FTP\_SITE, PR\_FTP\_SITE\_A, PR\_FTP\_SITE\_W, urn:schemas:contacts:ftpsite

### F_EXCEPTIONAL_ATTENDEES {#F-EXCEPTIONAL-ATTENDEES}
```
public static final PidLidPropertyDescriptor F_EXCEPTIONAL_ATTENDEES
```


Indicates that the object is a Recurring Calendar object with one or more exceptions, structure, as described in [MS-OXCDATA] section 2.8.3. Area: Meetings Canonical name: PidLidFExceptionalAttendees Alternate names: dispidFExceptionalAttendees

### F_EXCEPTIONAL_BODY {#F-EXCEPTIONAL-BODY}
```
public static final PidLidPropertyDescriptor F_EXCEPTIONAL_BODY
```


Indicates that the Exception Embedded Message object has a body that differs from the Recurring Calendar object. Area: Meetings Canonical name: PidLidFExceptionalBody Alternate names: dispidFExceptionalBody

### F_INVITED {#F-INVITED}
```
public static final PidLidPropertyDescriptor F_INVITED
```


Indicates whether invitations have been sent for the meeting that this Meeting object represents. Area: Meetings Canonical name: PidLidFInvited Alternate names: dispidFInvited

### F_OTHERS_APPOINTMENT {#F-OTHERS-APPOINTMENT}
```
public static final PidLidPropertyDescriptor F_OTHERS_APPOINTMENT
```


Indicates whether the Calendar folder from which the meeting was opened is another user's calendar. Area: Meetings Canonical name: PidLidFOthersAppointment Alternate names: dispidFOthersAppt, http://schemas.microsoft.com/mapi/fothersappt

### GATEWAY_NEEDS_TO_REFRESH {#GATEWAY-NEEDS-TO-REFRESH}
```
public static final PidTagPropertyDescriptor GATEWAY_NEEDS_TO_REFRESH
```


This property is deprecated and SHOULD NOT be used. Area: MessageClassDefinedTransmittable Canonical name: PidTagGatewayNeedsToRefresh Alternate names: PR\_GATEWAY\_NEEDS\_TO\_REFRESH

### GDATA_CONTACT_VERSION {#GDATA-CONTACT-VERSION}
```
public static final PidTagPropertyDescriptor GDATA_CONTACT_VERSION
```


Contains GData contact version (ETag). https://developers.google.com/contacts/v3/ https://developers.google.com/gdata/docs/2.0/reference?csw=1\#ResourceVersioning This property does not transmit via transport protocols. Area: User-defined Aspose specified properties

### GDATA_PHOTO_VERSION {#GDATA-PHOTO-VERSION}
```
public static final PidTagPropertyDescriptor GDATA_PHOTO_VERSION
```


Contains GData photo version (ETag). https://developers.google.com/contacts/v3/ https://developers.google.com/gdata/docs/2.0/reference?csw=1\#ResourceVersioning This property does not transmit via transport protocols. Area: User-defined Aspose specified properties

### GENDER {#GENDER}
```
public static final PidTagPropertyDescriptor GENDER
```


Contains a value that represents the mail user's gender. Area: MapiMailUser Canonical name: PidTagGender Alternate names: PR\_GENDER, urn:schemas:contacts:gender

### GENERATION {#GENERATION}
```
public static final PidTagPropertyDescriptor GENERATION
```


Contains a generational abbreviation that follows the full name of the mail user. Area: MapiMailUser Canonical name: PidTagGeneration Alternate names: PR\_GENERATION, PR\_GENERATION\_A, PR\_GENERATION\_W,

### GIVEN_NAME {#GIVEN-NAME}
```
public static final PidTagPropertyDescriptor GIVEN_NAME
```


Contains the mail user's given name. Area: MapiMailUser Canonical name: PidTagGivenName Alternate names: PR\_GIVEN\_NAME, PR\_GIVEN\_NAME\_A, PR\_GIVEN\_NAME\_W,

### GLOBAL_OBJECT_ID {#GLOBAL-OBJECT-ID}
```
public static final PidLidPropertyDescriptor GLOBAL_OBJECT_ID
```


Contains an ID for an object that represents an exception to a recurring series. Area: Meetings Canonical name: PidLidGlobalObjectId Alternate names: LID\_GLOBAL\_OBJID

### GOVERNMENT_ID_NUMBER {#GOVERNMENT-ID-NUMBER}
```
public static final PidTagPropertyDescriptor GOVERNMENT_ID_NUMBER
```


Contains a government identifier for the mail user. Area: MapiMailUser Canonical name: PidTagGovernmentIdNumber Alternate names: PR\_GOVERNMENT\_ID\_NUMBER, PR\_GOVERNMENT\_ID\_NUMBER\_A,

### GW_ADMIN_OPERATIONS {#GW-ADMIN-OPERATIONS}
```
public static final PidTagPropertyDescriptor GW_ADMIN_OPERATIONS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_GW\_ADMIN\_OPERATIONS

### GW_MTSIN_ENTRYID {#GW-MTSIN-ENTRYID}
```
public static final PidTagPropertyDescriptor GW_MTSIN_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_GW\_MTSIN\_ENTRYID

### GW_MTSOUT_ENTRYID {#GW-MTSOUT-ENTRYID}
```
public static final PidTagPropertyDescriptor GW_MTSOUT_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_GW\_MTSOUT\_ENTRYID

### HAS_ATTACHMENTS {#HAS-ATTACHMENTS}
```
public static final PidTagPropertyDescriptor HAS_ATTACHMENTS
```


Indicates whether the Message object contains at least one attachment. Area: Message Attachment Properties Property set Canonical name: PidTagHasAttachments Alternate names: PR\_HASATTACH, ptagHasAttach, urn:schemas:httpmail:hasattachment

### HAS_DEFERRED_ACTION_MESSAGES {#HAS-DEFERRED-ACTION-MESSAGES}
```
public static final PidTagPropertyDescriptor HAS_DEFERRED_ACTION_MESSAGES
```


Indicates whether a Message object has a deferred action message associated with it. Area: Rules Canonical name: PidTagHasDeferredActionMessages Alternate names: PR\_HAS\_DAMS, ptagHasDAMs

### HAS_MODERATOR_RULES {#HAS-MODERATOR-RULES}
```
public static final PidTagPropertyDescriptor HAS_MODERATOR_RULES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_HAS\_MODERATOR\_RULES

### HAS_NAMED_PROPERTIES {#HAS-NAMED-PROPERTIES}
```
public static final PidTagPropertyDescriptor HAS_NAMED_PROPERTIES
```


Indicates whether the Message object has a named property. Area: ExchangeMessageReadOnly Canonical name: PidTagHasNamedProperties Alternate names: PR\_HAS\_NAMED\_PROPERTIES, ptagHasNamedProperties

### HAS_PICTURE {#HAS-PICTURE}
```
public static final PidLidPropertyDescriptor HAS_PICTURE
```


Specifies whether the attachment has a picture. Area: Contact Properties Canonical name: PidLidHasPicture Alternate names: dispidHasPicture

### HAS_RULES {#HAS-RULES}
```
public static final PidTagPropertyDescriptor HAS_RULES
```


Indicates whether a Folder object has rules. Area: ExchangeFolder Canonical name: PidTagHasRules Alternate names: PR\_HAS\_RULES, ptagHasRules

### HEADER_FOLDER_ENTRYID {#HEADER-FOLDER-ENTRYID}
```
public static final PidTagPropertyDescriptor HEADER_FOLDER_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_HEADER\_FOLDER\_ENTRYID

### HEADING_PAIRS {#HEADING-PAIRS}
```
public static final PidNamePropertyDescriptor HEADING_PAIRS
```


Specifies which group of headings are indented in the document. Area: Common Canonical name: PidNameHeadingPairs Alternate names: urn:schemas-microsoft-com:office:office\#HeadingPairs

### HIDDEN_COUNT {#HIDDEN-COUNT}
```
public static final PidNamePropertyDescriptor HIDDEN_COUNT
```


Specifies the hidden value of the file attached to the Document object. Area: Common Canonical name: PidNameHiddenCount Alternate names: urn:schemas-microsoft-com:office:office\#HiddenSlides

### HIERARCHY_CHANGE_NUMBER {#HIERARCHY-CHANGE-NUMBER}
```
public static final PidTagPropertyDescriptor HIERARCHY_CHANGE_NUMBER
```


Contains a number that monotonically increases every time a subfolder is added to, or deleted from, this folder. Area: ExchangeFolder Canonical name: PidTagHierarchyChangeNumber Alternate names: PR\_HIERARCHY\_CHANGE\_NUM

### HIERARCHY_SERVER {#HIERARCHY-SERVER}
```
public static final PidTagPropertyDescriptor HIERARCHY_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_HIERARCHY\_SERVER

### HIERARCHY_SYNCHRONIZER {#HIERARCHY-SYNCHRONIZER}
```
public static final PidTagPropertyDescriptor HIERARCHY_SYNCHRONIZER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_HIERARCHY\_SYNCHRONIZER

### HIER_REV {#HIER-REV}
```
public static final PidTagPropertyDescriptor HIER_REV
```


Specifies the time, in UTC, to trigger the client in cached mode to synchronize the folder hierarchy. Area: TransportEnvelope Canonical name: PidTagHierRev Alternate names: PR\_HIER\_REV, ptagHierRev

### HOBBIES {#HOBBIES}
```
public static final PidTagPropertyDescriptor HOBBIES
```


Contains the names of the mail user's hobbies. Area: MapiMailUser Canonical name: PidTagHobbies Alternate names: PR\_HOBBIES, PR\_HOBBIES\_A, PR\_HOBBIES\_W, urn:schemas:contacts:hobbies

### HOME_2_TELEPHONE_NUMBER {#HOME-2-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor HOME_2_TELEPHONE_NUMBER
```


Contains a secondary telephone number at the mail user's home. Area: MapiMailUser Canonical name: PidTagHome2TelephoneNumber Alternate names: PR\_HOME2\_TELEPHONE\_NUMBER, PR\_HOME2\_TELEPHONE\_NUMBER\_A,

### HOME_2_TELEPHONE_NUMBERS {#HOME-2-TELEPHONE-NUMBERS}
```
public static final PidTagPropertyDescriptor HOME_2_TELEPHONE_NUMBERS
```


Contains secondary telephone numbers at the mail user's home. Area: MapiMailUser Canonical name: PidTagHome2TelephoneNumbers Alternate names: PR\_HOME2\_TELEPHONE\_NUMBER\_A\_MV

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final PidLidPropertyDescriptor HOME_ADDRESS
```


Specifies the complete address of the home address of the contact. Area: Contact Properties Canonical name: PidLidHomeAddress Alternate names: dispidHomeAddress

### HOME_ADDRESS_CITY {#HOME-ADDRESS-CITY}
```
public static final PidTagPropertyDescriptor HOME_ADDRESS_CITY
```


Contains the name of the mail user's home locality, such as the town or city. Area: MapiMailUser Canonical name: PidTagHomeAddressCity Alternate names: PR\_HOME\_ADDRESS\_CITY, PR\_HOME\_ADDRESS\_CITY\_A,

### HOME_ADDRESS_COUNTRY {#HOME-ADDRESS-COUNTRY}
```
public static final PidTagPropertyDescriptor HOME_ADDRESS_COUNTRY
```


Contains the name of the mail user's home country/region. Area: MapiMailUser Canonical name: PidTagHomeAddressCountry Alternate names: PR\_HOME\_ADDRESS\_COUNTRY, PR\_HOME\_ADDRESS\_COUNTRY\_A,

### HOME_ADDRESS_COUNTRY_CODE {#HOME-ADDRESS-COUNTRY-CODE}
```
public static final PidLidPropertyDescriptor HOME_ADDRESS_COUNTRY_CODE
```


Specifies the country code portion of the home address of the contact. Area: Contact Properties Canonical name: PidLidHomeAddressCountryCode Alternate names: dispidHomeAddressCountryCode

### HOME_ADDRESS_POSTAL_CODE {#HOME-ADDRESS-POSTAL-CODE}
```
public static final PidTagPropertyDescriptor HOME_ADDRESS_POSTAL_CODE
```


Contains the postal code for the mail user's home postal address. Area: MapiMailUser Canonical name: PidTagHomeAddressPostalCode Alternate names: PR\_HOME\_ADDRESS\_POSTAL\_CODE, PR\_HOME\_ADDRESS\_POSTAL\_CODE\_A,

### HOME_ADDRESS_POST_OFFICE_BOX {#HOME-ADDRESS-POST-OFFICE-BOX}
```
public static final PidTagPropertyDescriptor HOME_ADDRESS_POST_OFFICE_BOX
```


Contains the number or identifier of the mail user's home post office box. Area: MapiMailUser Canonical name: PidTagHomeAddressPostOfficeBox Alternate names: PR\_HOME\_ADDRESS\_POST\_OFFICE\_BOX, PR\_HOME\_ADDRESS\_POST\_OFFICE\_BOX\_A, PR\_HOME\_ADDRESS\_POST\_OFFICE\_BOX\_W,

### HOME_ADDRESS_STATE_OR_PROVINCE {#HOME-ADDRESS-STATE-OR-PROVINCE}
```
public static final PidTagPropertyDescriptor HOME_ADDRESS_STATE_OR_PROVINCE
```


Contains the name of the mail user's home state or province. Area: MapiMailUser Canonical name: PidTagHomeAddressStateOrProvince Alternate names: PR\_HOME\_ADDRESS\_STATE\_OR\_PROVINCE, PR\_HOME\_ADDRESS\_STATE\_OR\_PROVINCE\_A, PR\_HOME\_ADDRESS\_STATE\_OR\_PROVINCE\_W,

### HOME_ADDRESS_STREET {#HOME-ADDRESS-STREET}
```
public static final PidTagPropertyDescriptor HOME_ADDRESS_STREET
```


Contains the mail user's home street address. Area: MapiMailUser Canonical name: PidTagHomeAddressStreet Alternate names: PR\_HOME\_ADDRESS\_STREET, PR\_HOME\_ADDRESS\_STREET\_A,

### HOME_FAX_NUMBER {#HOME-FAX-NUMBER}
```
public static final PidTagPropertyDescriptor HOME_FAX_NUMBER
```


Contains the telephone number of the mail user's home fax machine. Area: MapiMailUser Canonical name: PidTagHomeFaxNumber Alternate names: PR\_HOME\_FAX\_NUMBER, PR\_HOME\_FAX\_NUMBER\_A,

### HOME_TELEPHONE_NUMBER {#HOME-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor HOME_TELEPHONE_NUMBER
```


Contains the primary telephone number of the mail user's home. Area: MapiMailUser Canonical name: PidTagHomeTelephoneNumber Alternate names: PR\_HOME\_TELEPHONE\_NUMBER, PR\_HOME\_TELEPHONE\_NUMBER\_A,

### HTML {#HTML}
```
public static final PidLidPropertyDescriptor HTML
```


Specifies the business webpage URL of the contact. Area: Contact Properties Canonical name: PidLidHtml Alternate names: dispidHTML

### HTTPMAIL_CALENDAR {#HTTPMAIL-CALENDAR}
```
public static final PidNamePropertyDescriptor HTTPMAIL_CALENDAR
```


Specifies the URL for the Calendar folder for a particular user. Area: Common Canonical name: PidNameHttpmailCalendar Alternate names: urn:schemas:httpmail:calendar

### HTTPMAIL_HTML_DESCRIPTION {#HTTPMAIL-HTML-DESCRIPTION}
```
public static final PidNamePropertyDescriptor HTTPMAIL_HTML_DESCRIPTION
```


Specifies the HTML content of the message. Area: Common Canonical name: PidNameHttpmailHtmlDescription Alternate names: urn:schemas:httpmail:htmldescription

### HTTPMAIL_SEND_MESSAGE {#HTTPMAIL-SEND-MESSAGE}
```
public static final PidNamePropertyDescriptor HTTPMAIL_SEND_MESSAGE
```


Specifies the email submission URI to which outgoing email is submitted. Area: Common Canonical name: PidNameHttpmailSendMessage Alternate names: urn:schemas:httpmail:sendmsg

### ICON {#ICON}
```
public static final PidTagPropertyDescriptor ICON
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ICON

### ICON_INDEX {#ICON-INDEX}
```
public static final PidTagPropertyDescriptor ICON_INDEX
```


Specifies which icon is to be used by a user interface when displaying a group of Message objects. Area: General Message Properties Canonical name: PidTagIconIndex Alternate names: PR\_ICON\_INDEX, ptagIconIndex

### IDENTITY_DISPLAY {#IDENTITY-DISPLAY}
```
public static final PidTagPropertyDescriptor IDENTITY_DISPLAY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IDENTITY\_DISPLAY

### IDENTITY_ENTRYID {#IDENTITY-ENTRYID}
```
public static final PidTagPropertyDescriptor IDENTITY_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IDENTITY\_ENTRYID

### IDENTITY_SEARCH_KEY {#IDENTITY-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor IDENTITY_SEARCH_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IDENTITY\_SEARCH\_KEY

### IMAP_INTERNAL_DATE {#IMAP-INTERNAL-DATE}
```
public static final PidTagPropertyDescriptor IMAP_INTERNAL_DATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IMAP\_INTERNAL\_DATE

### IMPLICIT_CONVERSION_PROHIBITED {#IMPLICIT-CONVERSION-PROHIBITED}
```
public static final PidTagPropertyDescriptor IMPLICIT_CONVERSION_PROHIBITED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IMPLICIT\_CONVERSION\_PROHIBITED

### IMPORTANCE {#IMPORTANCE}
```
public static final PidTagPropertyDescriptor IMPORTANCE
```


Indicates the level of importance assigned by the end user to the Message object. Area: General Message Properties Canonical name: PidTagImportance Alternate names: PR\_IMPORTANCE, ptagImportance, urn:schemas:httpmail:importance,

### INBOUND_I_CAL_STREAM {#INBOUND-I-CAL-STREAM}
```
public static final PidLidPropertyDescriptor INBOUND_I_CAL_STREAM
```


Contains the contents of the iCalendar MIME part of the original MIME message. Area: Calendar Canonical name: PidLidInboundICalStream Alternate names: InboundICalStream, dispidInboundICalStream

### INBOUND_NEWSFEED_DN {#INBOUND-NEWSFEED-DN}
```
public static final PidTagPropertyDescriptor INBOUND_NEWSFEED_DN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INBOUND\_NEWSFEED\_DN

### INCOMPLETE_COPY {#INCOMPLETE-COPY}
```
public static final PidTagPropertyDescriptor INCOMPLETE_COPY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INCOMPLETE\_COPY

### INFO_PATH_FORM_NAME {#INFO-PATH-FORM-NAME}
```
public static final PidLidPropertyDescriptor INFO_PATH_FORM_NAME
```


Contains the name of the form associated with this message. Area: Common Canonical name: PidLidInfoPathFormName Alternate names:

### INITIALS {#INITIALS}
```
public static final PidTagPropertyDescriptor INITIALS
```


Contains the initials for parts of the full name of the mail user. Area: Address Properties Canonical name: PidTagInitials Alternate names: PR\_INITIALS, PR\_INITIALS\_A, PR\_INITIALS\_W, urn:schemas:contacts:initials

### INITIAL_DETAILS_PANE {#INITIAL-DETAILS-PANE}
```
public static final PidTagPropertyDescriptor INITIAL_DETAILS_PANE
```


Indicates which page of a display template to display first. Area: MAPI Display Tables Canonical name: PidTagInitialDetailsPane Alternate names: PR\_INITIAL\_DETAILS\_PANE

### INSTANCE_KEY {#INSTANCE-KEY}
```
public static final PidTagPropertyDescriptor INSTANCE_KEY
```


Contains an object on an NSPI server. Area: Table Properties Canonical name: PidTagInstanceKey Alternate names: PR\_INSTANCE\_KEY, ptagInstanceKey

### INSTANCE_NUM {#INSTANCE-NUM}
```
public static final PidTagPropertyDescriptor INSTANCE_NUM
```


Contains an identifier for a single instance of a row in the table. Area: ProviderDefinedNonTransmittable Canonical name: PidTagInstanceNum Alternate names: ptagInstanceNum

### INSTANT_MESSAGING_ADDRESS {#INSTANT-MESSAGING-ADDRESS}
```
public static final PidLidPropertyDescriptor INSTANT_MESSAGING_ADDRESS
```


Specifies the instant messaging address of the contact. Area: Contact Properties Canonical name: PidLidInstantMessagingAddress Alternate names: dispidInstMsg

### INST_ID {#INST-ID}
```
public static final PidTagPropertyDescriptor INST_ID
```


Contains an identifier for all instances of a row in the table. Area: ProviderDefinedNonTransmittable Canonical name: PidTagInstID Alternate names: ptagInstID

### INTENDED_BUSY_STATUS {#INTENDED-BUSY-STATUS}
```
public static final PidLidPropertyDescriptor INTENDED_BUSY_STATUS
```


Contains the value of the PidLidBusyStatus property (section 2.47) on the Meeting object was sent. Area: Meetings Canonical name: PidLidIntendedBusyStatus Alternate names: dispidIntendedBusyStatus

### INTERNET_ACCOUNT_NAME {#INTERNET-ACCOUNT-NAME}
```
public static final PidLidPropertyDescriptor INTERNET_ACCOUNT_NAME
```


Specifies the user-visible email account name through which the email message is sent. Area: General Message Properties Canonical name: PidLidInternetAccountName Alternate names: dispidInetAcctName

### INTERNET_ACCOUNT_STAMP {#INTERNET-ACCOUNT-STAMP}
```
public static final PidLidPropertyDescriptor INTERNET_ACCOUNT_STAMP
```


Specifies the email account ID through which the email message is sent. Area: General Message Properties Canonical name: PidLidInternetAccountStamp Alternate names: dispidInetAcctStamp

### INTERNET_APPROVED {#INTERNET-APPROVED}
```
public static final PidTagPropertyDescriptor INTERNET_APPROVED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_APPROVED

### INTERNET_ARTICLE_NUMBER {#INTERNET-ARTICLE-NUMBER}
```
public static final PidTagPropertyDescriptor INTERNET_ARTICLE_NUMBER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_ARTICLE\_NUMBER

### INTERNET_CHARSET {#INTERNET-CHARSET}
```
public static final PidTagPropertyDescriptor INTERNET_CHARSET
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_CHARSET

### INTERNET_CODEPAGE {#INTERNET-CODEPAGE}
```
public static final PidTagPropertyDescriptor INTERNET_CODEPAGE
```


Indicates the code page used for the PidTagBody property (section 2.609) or the PidTagBodyHtml property (section 2.612). Area: Miscellaneous Properties Canonical name: PidTagInternetCodepage Alternate names: PR\_INTERNET\_CPID, ptagInternetCpid

### INTERNET_CONTROL {#INTERNET-CONTROL}
```
public static final PidTagPropertyDescriptor INTERNET_CONTROL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_CONTROL

### INTERNET_DISTRIBUTION {#INTERNET-DISTRIBUTION}
```
public static final PidTagPropertyDescriptor INTERNET_DISTRIBUTION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_DISTRIBUTION

### INTERNET_FOLLOWUP_TO {#INTERNET-FOLLOWUP-TO}
```
public static final PidTagPropertyDescriptor INTERNET_FOLLOWUP_TO
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_FOLLOWUP\_TO

### INTERNET_LINES {#INTERNET-LINES}
```
public static final PidTagPropertyDescriptor INTERNET_LINES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_LINES

### INTERNET_MAIL_OVERRIDE_FORMAT {#INTERNET-MAIL-OVERRIDE-FORMAT}
```
public static final PidTagPropertyDescriptor INTERNET_MAIL_OVERRIDE_FORMAT
```


Indicates the encoding method and HTML inclusion for attachments. Area: MIME Properties Canonical name: PidTagInternetMailOverrideFormat Alternate names: PR\_INETMAIL\_OVERRIDE\_FORMAT, ptagInetMailOverrideFormat

### INTERNET_MESSAGE_ID {#INTERNET-MESSAGE-ID}
```
public static final PidTagPropertyDescriptor INTERNET_MESSAGE_ID
```


Corresponds to the message-id field. Area: MIME Properties Canonical name: PidTagInternetMessageId Alternate names: PR\_INTERNET\_MESSAGE\_ID, PR\_INTERNET\_MESSAGE\_ID\_A, PR\_INTERNET\_MESSAGE\_ID\_W

### INTERNET_NEWSGROUPS {#INTERNET-NEWSGROUPS}
```
public static final PidTagPropertyDescriptor INTERNET_NEWSGROUPS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_NEWSGROUPS

### INTERNET_NEWSGROUP_NAME {#INTERNET-NEWSGROUP-NAME}
```
public static final PidTagPropertyDescriptor INTERNET_NEWSGROUP_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_NEWSGROUP\_NAME

### INTERNET_NNTP_PATH {#INTERNET-NNTP-PATH}
```
public static final PidTagPropertyDescriptor INTERNET_NNTP_PATH
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_NNTP\_PATH

### INTERNET_ORGANIZATION {#INTERNET-ORGANIZATION}
```
public static final PidTagPropertyDescriptor INTERNET_ORGANIZATION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_ORGANIZATION

### INTERNET_PRECEDENCE {#INTERNET-PRECEDENCE}
```
public static final PidTagPropertyDescriptor INTERNET_PRECEDENCE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_INTERNET\_PRECEDENCE

### INTERNET_REFERENCES {#INTERNET-REFERENCES}
```
public static final PidTagPropertyDescriptor INTERNET_REFERENCES
```


Contains a list of message IDs that specify the messages to which this reply is related. Area: MIME Properties Canonical name: PidTagInternetReferences Alternate names: PR\_INTERNET\_REFERENCES, PR\_INTERNET\_REFERENCES\_A, PR\_INTERNET\_REFERENCES\_W

### INTERNET_SUBJECT {#INTERNET-SUBJECT}
```
public static final PidNamePropertyDescriptor INTERNET_SUBJECT
```


Specifies the subject of the message. Area: Email Canonical name: PidNameInternetSubject Alternate names: urn:schemas:mailheader:subject

### IN_CONFLICT {#IN-CONFLICT}
```
public static final PidTagPropertyDescriptor IN_CONFLICT
```


Specifies whether the attachment represents an alternate replica. Area: Conflict Note Canonical name: PidTagInConflict Alternate names: PR\_IN\_CONFLICT, ptagInConflict

### IN_REPLY_TO_ID {#IN-REPLY-TO-ID}
```
public static final PidTagPropertyDescriptor IN_REPLY_TO_ID
```


Contains the value of the original message's PidTagInternetMessageId property (section 2.739) value. Area: General Message Properties Canonical name: PidTagInReplyToId Alternate names: PR\_IN\_REPLY\_TO\_ID, PR\_IN\_REPLY\_TO\_ID\_A, PR\_IN\_REPLY\_TO\_ID\_W

### IN_TRANSIT {#IN-TRANSIT}
```
public static final PidTagPropertyDescriptor IN_TRANSIT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IN\_TRANSIT

### IPM_APPOINTMENT_ENTRY_ID {#IPM-APPOINTMENT-ENTRY-ID}
```
public static final PidTagPropertyDescriptor IPM_APPOINTMENT_ENTRY_ID
```


Contains the EntryID of the Calendar folder. Area: Folder Properties Canonical name: PidTagIpmAppointmentEntryId Alternate names: PR\_IPM\_APPOINTMENT\_ENTRYID

### IPM_CONTACT_ENTRY_ID {#IPM-CONTACT-ENTRY-ID}
```
public static final PidTagPropertyDescriptor IPM_CONTACT_ENTRY_ID
```


Contains the EntryID of the Contacts folder. Area: Folder Properties Canonical name: PidTagIpmContactEntryId Alternate names: PR\_IPM\_CONTACT\_ENTRYID

### IPM_DAF_ENTRYID {#IPM-DAF-ENTRYID}
```
public static final PidTagPropertyDescriptor IPM_DAF_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_DAF\_ENTRYID

### IPM_DRAFTS_ENTRY_ID {#IPM-DRAFTS-ENTRY-ID}
```
public static final PidTagPropertyDescriptor IPM_DRAFTS_ENTRY_ID
```


Contains the EntryID of the Drafts folder. Area: Folder Properties Canonical name: PidTagIpmDraftsEntryId Alternate names: PR\_IPM\_DRAFTS\_ENTRYID

### IPM_FAVORITES_ENTRYID {#IPM-FAVORITES-ENTRYID}
```
public static final PidTagPropertyDescriptor IPM_FAVORITES_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_FAVORITES\_ENTRYID

### IPM_ID {#IPM-ID}
```
public static final PidTagPropertyDescriptor IPM_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_ID

### IPM_JOURNAL_ENTRY_ID {#IPM-JOURNAL-ENTRY-ID}
```
public static final PidTagPropertyDescriptor IPM_JOURNAL_ENTRY_ID
```


Contains the EntryID of the Journal folder. Area: Folder Properties Canonical name: PidTagIpmJournalEntryId Alternate names: PR\_IPM\_JOURNAL\_ENTRYID

### IPM_NOTE_ENTRY_ID {#IPM-NOTE-ENTRY-ID}
```
public static final PidTagPropertyDescriptor IPM_NOTE_ENTRY_ID
```


Contains the EntryID of the Notes folder. Area: Folder Properties Canonical name: PidTagIpmNoteEntryId Alternate names: PR\_IPM\_NOTE\_ENTRYID

### IPM_OUTBOX_ENTRYID {#IPM-OUTBOX-ENTRYID}
```
public static final PidTagPropertyDescriptor IPM_OUTBOX_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_OUTBOX\_ENTRYID

### IPM_OUTBOX_SEARCH_KEY {#IPM-OUTBOX-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor IPM_OUTBOX_SEARCH_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_OUTBOX\_SEARCH\_KEY

### IPM_PUBLIC_FOLDERS_ENTRYID {#IPM-PUBLIC-FOLDERS-ENTRYID}
```
public static final PidTagPropertyDescriptor IPM_PUBLIC_FOLDERS_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_PUBLIC\_FOLDERS\_ENTRYID

### IPM_RETURN_REQUESTED {#IPM-RETURN-REQUESTED}
```
public static final PidTagPropertyDescriptor IPM_RETURN_REQUESTED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_RETURN\_REQUESTED

### IPM_SENTMAIL_ENTRYID {#IPM-SENTMAIL-ENTRYID}
```
public static final PidTagPropertyDescriptor IPM_SENTMAIL_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_SENTMAIL\_ENTRYID

### IPM_SENTMAIL_SEARCH_KEY {#IPM-SENTMAIL-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor IPM_SENTMAIL_SEARCH_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_SENTMAIL\_SEARCH\_KEY

### IPM_SUBTREE_ENTRYID {#IPM-SUBTREE-ENTRYID}
```
public static final PidTagPropertyDescriptor IPM_SUBTREE_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_SUBTREE\_ENTRYID

### IPM_SUBTREE_SEARCH_KEY {#IPM-SUBTREE-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor IPM_SUBTREE_SEARCH_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_SUBTREE\_SEARCH\_KEY

### IPM_TASK_ENTRY_ID {#IPM-TASK-ENTRY-ID}
```
public static final PidTagPropertyDescriptor IPM_TASK_ENTRY_ID
```


Contains the EntryID of the Tasks folder. Area: Folder Properties Canonical name: PidTagIpmTaskEntryId Alternate names: PR\_IPM\_TASK\_ENTRYID

### IPM_WASTEBASKET_ENTRYID {#IPM-WASTEBASKET-ENTRYID}
```
public static final PidTagPropertyDescriptor IPM_WASTEBASKET_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_WASTEBASKET\_ENTRYID

### IPM_WASTEBASKET_SEARCH_KEY {#IPM-WASTEBASKET-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor IPM_WASTEBASKET_SEARCH_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IPM\_WASTEBASKET\_SEARCH\_KEY

### ISDN_NUMBER {#ISDN-NUMBER}
```
public static final PidTagPropertyDescriptor ISDN_NUMBER
```


Contains the Integrated Services Digital Network (ISDN) telephone number of the mail user. Area: Address Properties Canonical name: PidTagIsdnNumber Alternate names: PR\_ISDN\_NUMBER, PR\_ISDN\_NUMBER\_A, PR\_ISDN\_NUMBER\_W,

### IS_CONTACT_LINKED {#IS-CONTACT-LINKED}
```
public static final PidLidPropertyDescriptor IS_CONTACT_LINKED
```


Specifies whether the contact is linked to other contacts. Area: Contact Properties Canonical name: PidLidIsContactLinked Alternate names: dispidIsContactLinked

### IS_EXCEPTION {#IS-EXCEPTION}
```
public static final PidLidPropertyDescriptor IS_EXCEPTION
```


Indicates whether the object represents an exception (including an orphan instance). Area: Meetings Canonical name: PidLidIsException Alternate names: LID\_IS\_EXCEPTION

### IS_NEWSGROUP {#IS-NEWSGROUP}
```
public static final PidTagPropertyDescriptor IS_NEWSGROUP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IS\_NEWSGROUP

### IS_NEWSGROUP_ANCHOR {#IS-NEWSGROUP-ANCHOR}
```
public static final PidTagPropertyDescriptor IS_NEWSGROUP_ANCHOR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_IS\_NEWSGROUP\_ANCHOR

### IS_RECURRING {#IS-RECURRING}
```
public static final PidLidPropertyDescriptor IS_RECURRING
```


Specifies whether the object is associated with a recurring series. Area: Meetings Canonical name: PidLidIsRecurring Alternate names: LID\_IS\_RECURRING

### IS_SILENT {#IS-SILENT}
```
public static final PidLidPropertyDescriptor IS_SILENT
```


Indicates whether the user did not include any text in the body of the Meeting Response object. Area: Meetings Canonical name: PidLidIsSilent Alternate names: LID\_IS\_SILENT

### I_CALENDAR_DAY_OF_WEEK_MASK {#I-CALENDAR-DAY-OF-WEEK-MASK}
```
public static final PidLidPropertyDescriptor I_CALENDAR_DAY_OF_WEEK_MASK
```


Identifies the day of the week for the appointment or meeting. Area: Calendar Canonical name: PidLidICalendarDayOfWeekMask Alternate names: http://schemas.microsoft.com/mapi/dayofweekmask

### I_CALENDAR_END_TIME {#I-CALENDAR-END-TIME}
```
public static final PidTagPropertyDescriptor I_CALENDAR_END_TIME
```


Contains the date and time, in UTC, when an appointment or meeting ends. Area: Calendar Canonical name: PidTagICalendarEndTime Alternate names: urn:schemas:calendar:dtend

### I_CALENDAR_RECURRENCE_DATE {#I-CALENDAR-RECURRENCE-DATE}
```
public static final PidNamePropertyDescriptor I_CALENDAR_RECURRENCE_DATE
```


Identifies an array of instances of a recurring appointment. Area: Common Canonical name: PidNameICalendarRecurrenceDate Alternate names: urn:schemas:calendar:rdate

### I_CALENDAR_RECURRENCE_RULE {#I-CALENDAR-RECURRENCE-RULE}
```
public static final PidNamePropertyDescriptor I_CALENDAR_RECURRENCE_RULE
```


Specifies the rule for the pattern that defines a recurring appointment. Area: Common Canonical name: PidNameICalendarRecurrenceRule Alternate names: urn:schemas:calendar:rrule

### I_CALENDAR_REMINDER_NEXT_TIME {#I-CALENDAR-REMINDER-NEXT-TIME}
```
public static final PidTagPropertyDescriptor I_CALENDAR_REMINDER_NEXT_TIME
```


Contains the date and time, in UTC, for the activation of the next reminder. Area: Calendar Canonical name: PidTagICalendarReminderNextTime Alternate names: urn:schemas:calendar:remindernexttime

### I_CALENDAR_START_TIME {#I-CALENDAR-START-TIME}
```
public static final PidTagPropertyDescriptor I_CALENDAR_START_TIME
```


Contains the date and time, in UTC, when the appointment or meeting starts. Area: Calendar Property set Canonical name: PidTagICalendarStartTime Alternate names: urn:schemas:calendar:dtstart

### JUNK_ADD_RECIPIENTS_TO_SAFE_SENDERS_LIST {#JUNK-ADD-RECIPIENTS-TO-SAFE-SENDERS-LIST}
```
public static final PidTagPropertyDescriptor JUNK_ADD_RECIPIENTS_TO_SAFE_SENDERS_LIST
```


Indicates whether email recipients are to be added to the safe senders list. Area: Spam Canonical name: PidTagJunkAddRecipientsToSafeSendersList Alternate names: PR\_JUNK\_ADD\_RECIPS\_TO\_SSL

### JUNK_INCLUDE_CONTACTS {#JUNK-INCLUDE-CONTACTS}
```
public static final PidTagPropertyDescriptor JUNK_INCLUDE_CONTACTS
```


Indicates whether email addresses of the contacts in the Contacts folder are treated in a special way with respect to the spam filter. Area: Spam Canonical name: PidTagJunkIncludeContacts Alternate names: PR\_JUNK\_INCLUDE\_CONTACTS

### JUNK_PERMANENTLY_DELETE {#JUNK-PERMANENTLY-DELETE}
```
public static final PidTagPropertyDescriptor JUNK_PERMANENTLY_DELETE
```


Indicates whether messages identified as spam can be permanently deleted. Area: Spam Canonical name: PidTagJunkPermanentlyDelete Alternate names: PR\_JUNK\_PERMANENTLY\_DELETE

### JUNK_PHISHING_ENABLE_LINKS {#JUNK-PHISHING-ENABLE-LINKS}
```
public static final PidTagPropertyDescriptor JUNK_PHISHING_ENABLE_LINKS
```


Indicated whether the phishing stamp on a message is to be ignored. Area: Spam Canonical name: PidTagJunkPhishingEnableLinks Alternate names: PR\_JUNK\_PHISHING\_ENABLE\_LINKS

### JUNK_THRESHOLD {#JUNK-THRESHOLD}
```
public static final PidTagPropertyDescriptor JUNK_THRESHOLD
```


Indicates how aggressively incoming email is to be sent to the Junk Email folder. Area: Spam Canonical name: PidTagJunkThreshold Alternate names: PR\_JUNK\_THRESHOLD

### KEYWORD {#KEYWORD}
```
public static final PidTagPropertyDescriptor KEYWORD
```


Contains a keyword that identifies the mail user to the mail user's system administrator. Area: Address Properties Canonical name: PidTagKeyword Alternate names: PR\_KEYWORD, PR\_KEYWORD\_A, PR\_KEYWORD\_W

### KEYWORDS {#KEYWORDS}
```
public static final PidNamePropertyDescriptor KEYWORDS
```


Contains keywords or categories for the Message object. Area: General Message Properties Canonical name: PidNameKeywords Alternate names: urn:schemas-microsoft-com:office:office\#Keywords,

### LANGUAGE {#LANGUAGE}
```
public static final PidTagPropertyDescriptor LANGUAGE
```


Contains a value that indicates the language in which the messaging user is writing messages. Area: Address Properties Canonical name: PidTagLanguage Alternate names: PR\_LANGUAGE, PR\_LANGUAGE\_A, PR\_LANGUAGE\_W,

### LANGUAGES {#LANGUAGES}
```
public static final PidTagPropertyDescriptor LANGUAGES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_LANGUAGES

### LAST_ACCESS_TIME {#LAST-ACCESS-TIME}
```
public static final PidTagPropertyDescriptor LAST_ACCESS_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_LAST\_ACCESS\_TIME

### LAST_AUTHOR {#LAST-AUTHOR}
```
public static final PidNamePropertyDescriptor LAST_AUTHOR
```


Specifies the most recent author of the file attached to the Document object. Area: Common Canonical name: PidNameLastAuthor Alternate names: urn:schemas-microsoft-com:office:office\#LastAuthor

### LAST_FULL_BACKUP {#LAST-FULL-BACKUP}
```
public static final PidTagPropertyDescriptor LAST_FULL_BACKUP
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_LAST\_FULL\_BACKUP

### LAST_LOGOFF_TIME {#LAST-LOGOFF-TIME}
```
public static final PidTagPropertyDescriptor LAST_LOGOFF_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_LAST\_LOGOFF\_TIME

### LAST_LOGON_TIME {#LAST-LOGON-TIME}
```
public static final PidTagPropertyDescriptor LAST_LOGON_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_LAST\_LOGON\_TIME

### LAST_MODIFICATION_TIME {#LAST-MODIFICATION-TIME}
```
public static final PidTagPropertyDescriptor LAST_MODIFICATION_TIME
```


Contains the time, in UTC, of the last modification to the object. Area: Message Time Properties Canonical name: PidTagLastModificationTime Alternate names: PR\_LAST\_MODIFICATION\_TIME, ptagLastModificationTime,

### LAST_MODIFIER_ENTRY_ID {#LAST-MODIFIER-ENTRY-ID}
```
public static final PidTagPropertyDescriptor LAST_MODIFIER_ENTRY_ID
```


Specifies the Address Book EntryID of the last user to modify the contents of the message. Area: History Properties Canonical name: PidTagLastModifierEntryId Alternate names: PR\_LAST\_MODIFIER\_ENTRYID, ptagLastModifierEntryId

### LAST_MODIFIER_NAME {#LAST-MODIFIER-NAME}
```
public static final PidTagPropertyDescriptor LAST_MODIFIER_NAME
```


Contains the name of the last mail user to change the Message object. Area: History Properties Canonical name: PidTagLastModifierName Alternate names: PR\_LAST\_MODIFIER\_NAME, PR\_LAST\_MODIFIER\_NAME\_A, ptagLastModifierName, PR\_LAST\_MODIFIER\_NAME\_W

### LAST_PRINTED {#LAST-PRINTED}
```
public static final PidNamePropertyDescriptor LAST_PRINTED
```


Specifies the time, in UTC, that the file was last printed. Area: Common Canonical name: PidNameLastPrinted Alternate names: urn:schemas-microsoft-com:office:office\#LastPrinted

### LAST_SAVE_DATE_TIME {#LAST-SAVE-DATE-TIME}
```
public static final PidNamePropertyDescriptor LAST_SAVE_DATE_TIME
```


Specifies the time, in UTC, that the file was last saved. Area: Common Canonical name: PidNameLastSaveDateTime Alternate names: urn:schemas-microsoft-com:office:office\#LastSaved

### LAST_VERB_EXECUTED {#LAST-VERB-EXECUTED}
```
public static final PidTagPropertyDescriptor LAST_VERB_EXECUTED
```


Specifies the last verb executed for the message item to which it is related. Area: History Properties Canonical name: PidTagLastVerbExecuted Alternate names: PR\_LAST\_VERB\_EXECUTED, ptagLastVerbExecuted

### LAST_VERB_EXECUTION_TIME {#LAST-VERB-EXECUTION-TIME}
```
public static final PidTagPropertyDescriptor LAST_VERB_EXECUTION_TIME
```


Contains the date and time, in UTC, during which the operation represented in the PidTagLastVerbExecuted property (section 2.758) took place. Area: History Properties Canonical name: PidTagLastVerbExecutionTime Alternate names: PR\_LAST\_VERB\_EXECUTION\_TIME, ptagLastVerbExecutionTime

### LATEST_DELIVERY_TIME {#LATEST-DELIVERY-TIME}
```
public static final PidTagPropertyDescriptor LATEST_DELIVERY_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_LATEST\_DELIVERY\_TIME

### LINE_COUNT {#LINE-COUNT}
```
public static final PidNamePropertyDescriptor LINE_COUNT
```


Specifies the number of lines in the file attached to the Document object. Area: Common Canonical name: PidNameLineCount Alternate names: urn:schemas-microsoft-com:office:office\#Lines

### LINKED_TASK_ITEMS {#LINKED-TASK-ITEMS}
```
public static final PidLidPropertyDescriptor LINKED_TASK_ITEMS
```


Indicates whether the user did not include any text in the body of the Meeting Response object. Area: Tasks Canonical name: PidLidLinkedTaskItems Alternate names: dispidLinkedTaskItems

### LINKS_DIRTY {#LINKS-DIRTY}
```
public static final PidNamePropertyDescriptor LINKS_DIRTY
```


Indicates whether the links in the document are up-to-date. Area: Common Canonical name: PidNameLinksDirty Alternate names: urn:schemas-microsoft-com:office:office\#LinksUpToDate

### LIST_HELP {#LIST-HELP}
```
public static final PidTagPropertyDescriptor LIST_HELP
```


Contains a URI that provides detailed help information for the mailing list from which an email message was sent. Area: Miscellaneous Properties Canonical name: PidTagListHelp Alternate names: PR\_LIST\_HELP, PR\_LIST\_HELP\_A, PR\_LIST\_HELP\_W

### LIST_SUBSCRIBE {#LIST-SUBSCRIBE}
```
public static final PidTagPropertyDescriptor LIST_SUBSCRIBE
```


Contains the URI that subscribes a recipient to a message\\ufffds associated mailing list. Area: Miscellaneous Properties Canonical name: PidTagListSubscribe Alternate names: PR\_LIST\_SUBSCRIBE, PR\_LIST\_SUBSCRIBE\_A, PR\_LIST\_SUBSCRIBE\_W

### LIST_UNSUBSCRIBE {#LIST-UNSUBSCRIBE}
```
public static final PidTagPropertyDescriptor LIST_UNSUBSCRIBE
```


Contains the URI that unsubscribes a recipient from a message\\ufffds associated mailing list. Area: Miscellaneous Properties Canonical name: PidTagListUnsubscribe Alternate names: PR\_LIST\_UNSUBSCRIBE, PR\_LIST\_UNSUBSCRIBE\_A, PR\_LIST\_UNSUBSCRIBE\_W

### LOCALE_ID {#LOCALE-ID}
```
public static final PidTagPropertyDescriptor LOCALE_ID
```


Contains the Logon object LocaleID. Area: Miscellaneous Properties Canonical name: PidTagLocaleId Alternate names: PR\_LOCALE\_ID, ptagLocaleId

### LOCALITY {#LOCALITY}
```
public static final PidTagPropertyDescriptor LOCALITY
```


Contains the name of the mail user's locality, such as the town or city. Area: Address Properties Canonical name: PidTagLocality Alternate names: PR\_LOCALITY, PR\_LOCALITY\_A, PR\_LOCALITY\_W, PR\_BUSINESS\_ADDRESS\_LOCALITY, PR\_BUSINESS\_ADDRESS\_LOCALITY\_A,

### LOCAL_COMMIT_TIME {#LOCAL-COMMIT-TIME}
```
public static final PidTagPropertyDescriptor LOCAL_COMMIT_TIME
```


Specifies the time, in UTC, that a Message object or Folder object was last changed. Area: Server Canonical name: PidTagLocalCommitTime Alternate names: PR\_LOCAL\_COMMIT\_TIME, ptagLocalCommitTime

### LOCAL_COMMIT_TIME_MAX {#LOCAL-COMMIT-TIME-MAX}
```
public static final PidTagPropertyDescriptor LOCAL_COMMIT_TIME_MAX
```


Contains the time of the most recent message change within the folder container, excluding messages changed within subfolders. Area: Server Canonical name: PidTagLocalCommitTimeMax Alternate names: PR\_LOCAL\_COMMIT\_TIME\_MAX, ptagLocalCommitTimeMax

### LOCATION {#LOCATION}
```
public static final PidLidPropertyDescriptor LOCATION
```


Specifies the location of the event. Area: Calendar Canonical name: PidLidLocation Alternate names: dispidLocation

### LOCATION_URL {#LOCATION-URL}
```
public static final PidNamePropertyDescriptor LOCATION_URL
```


Area: Calendar Canonical name: PidNameLocationUrl Alternate names: urn:schemas:calendar:locationurl, LocationUrl

### LOG_DOCUMENT_POSTED {#LOG-DOCUMENT-POSTED}
```
public static final PidLidPropertyDescriptor LOG_DOCUMENT_POSTED
```


Indicates whether the document was sent by email or posted to a server folder during journaling. Area: Journal Canonical name: PidLidLogDocumentPosted Alternate names: dispidLogDocPosted

### LOG_DOCUMENT_PRINTED {#LOG-DOCUMENT-PRINTED}
```
public static final PidLidPropertyDescriptor LOG_DOCUMENT_PRINTED
```


Indicates whether the document was printed during journaling. Area: Journal Canonical name: PidLidLogDocumentPrinted Alternate names: dispidLogDocPrinted

### LOG_DOCUMENT_ROUTED {#LOG-DOCUMENT-ROUTED}
```
public static final PidLidPropertyDescriptor LOG_DOCUMENT_ROUTED
```


Indicates whether the document was sent to a routing recipient during journaling. Area: Journal Canonical name: PidLidLogDocumentRouted Alternate names: dispidLogDocRouted

### LOG_DOCUMENT_SAVED {#LOG-DOCUMENT-SAVED}
```
public static final PidLidPropertyDescriptor LOG_DOCUMENT_SAVED
```


Indicates whether the document was saved during journaling. Area: Journal Canonical name: PidLidLogDocumentSaved Alternate names: dispidLogDocSaved

### LOG_DURATION {#LOG-DURATION}
```
public static final PidLidPropertyDescriptor LOG_DURATION
```


Contains the duration, in minutes, of the activity. Area: Journal Canonical name: PidLidLogDuration Alternate names: dispidLogDuration

### LOG_END {#LOG-END}
```
public static final PidLidPropertyDescriptor LOG_END
```


Contains the time, in UTC, at which the activity ended. Area: Journal Canonical name: PidLidLogEnd Alternate names: dispidLogEnd

### LOG_FLAGS {#LOG-FLAGS}
```
public static final PidLidPropertyDescriptor LOG_FLAGS
```


Contains metadata about the Journal object. Area: Journal Canonical name: PidLidLogFlags Alternate names: dispidLogFlags

### LOG_START {#LOG-START}
```
public static final PidLidPropertyDescriptor LOG_START
```


Contains the time, in UTC, at which the activity began. Area: Journal Canonical name: PidLidLogStart Alternate names: dispidLogStart

### LOG_TYPE {#LOG-TYPE}
```
public static final PidLidPropertyDescriptor LOG_TYPE
```


Briefly describes the journal activity that is being recorded. Area: Journal Canonical name: PidLidLogType Alternate names: dispidLogType

### LOG_TYPE_DESC {#LOG-TYPE-DESC}
```
public static final PidLidPropertyDescriptor LOG_TYPE_DESC
```


Contains an expanded description of the journal activity that is being recorded. Area: Journal Canonical name: PidLidLogTypeDesc Alternate names: dispidLogTypeDesc

### LONGTERM_ENTRYID_FROM_TABLE {#LONGTERM-ENTRYID-FROM-TABLE}
```
public static final PidTagPropertyDescriptor LONGTERM_ENTRYID_FROM_TABLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_LONGTERM\_ENTRYID\_FROM\_TABLE

### MAILBOX_OWNER_ENTRY_ID {#MAILBOX-OWNER-ENTRY-ID}
```
public static final PidTagPropertyDescriptor MAILBOX_OWNER_ENTRY_ID
```


Contains the EntryID in the Global Address List (GAL) of the owner of the mailbox. Area: Message Store Properties Canonical name: PidTagMailboxOwnerEntryId Alternate names: PR\_MAILBOX\_OWNER\_ENTRYID, ptagMailboxOwnerEntryId

### MAILBOX_OWNER_NAME {#MAILBOX-OWNER-NAME}
```
public static final PidTagPropertyDescriptor MAILBOX_OWNER_NAME
```


Contains the display name of the owner of the mailbox. Area: Message Store Properties Canonical name: PidTagMailboxOwnerName Alternate names: PR\_MAILBOX\_OWNER\_NAME, PR\_MAILBOX\_OWNER\_NAME\_A, ptagMailboxOwnerName, PR\_MAILBOX\_OWNER\_NAME\_W

### MAIL_PERMISSION {#MAIL-PERMISSION}
```
public static final PidTagPropertyDescriptor MAIL_PERMISSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MAIL\_PERMISSION

### MANAGER {#MANAGER}
```
public static final PidNamePropertyDescriptor MANAGER
```


Specifies the manager of the file attached to the Document object. Area: Common Canonical name: PidNameManager Alternate names: urn:schemas-microsoft-com:office:office\#Manager

### MANAGER_NAME {#MANAGER-NAME}
```
public static final PidTagPropertyDescriptor MANAGER_NAME
```


Contains the name of the mail user's manager. Area: Address Properties Canonical name: PidTagManagerName Alternate names: PR\_MANAGER\_NAME, PR\_MANAGER\_NAME\_A, PR\_MANAGER\_NAME\_W,

### MAPPING_SIGNATURE {#MAPPING-SIGNATURE}
```
public static final PidTagPropertyDescriptor MAPPING_SIGNATURE
```


A 16-byte constant that is present on all Address Book objects, but is not present on objects in an offline address book. Area: Miscellaneous Properties Canonical name: PidTagMappingSignature Alternate names: PR\_MAPPING\_SIGNATURE, ptagMappingSignature

### MAXIMUM_SUBMIT_MESSAGE_SIZE {#MAXIMUM-SUBMIT-MESSAGE-SIZE}
```
public static final PidTagPropertyDescriptor MAXIMUM_SUBMIT_MESSAGE_SIZE
```


Maximum size, in kilobytes, of a message that a user is allowed to submit for transmission to another user. Area: Message Store Properties Canonical name: PidTagMaximumSubmitMessageSize Alternate names: PR\_MAX\_SUBMIT\_MESSAGE\_SIZE

### MDB_PROVIDER {#MDB-PROVIDER}
```
public static final PidTagPropertyDescriptor MDB_PROVIDER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MDB\_PROVIDER

### MEETING_TYPE {#MEETING-TYPE}
```
public static final PidLidPropertyDescriptor MEETING_TYPE
```


Indicates the type of Meeting Request object or Meeting Update object. Area: Meetings Canonical name: PidLidMeetingType Alternate names: dispidMeetingType

### MEETING_WORKSPACE_URL {#MEETING-WORKSPACE-URL}
```
public static final PidLidPropertyDescriptor MEETING_WORKSPACE_URL
```


Specifies the URL of the Meeting Workspace that is associated with a Calendar object. Area: Meetings Canonical name: PidLidMeetingWorkspaceUrl Alternate names: dispidMWSURL

### MEMBER_ID {#MEMBER-ID}
```
public static final PidTagPropertyDescriptor MEMBER_ID
```


Contains a unique identifier that the messaging server generates for each user. Area: Access Control Properties Canonical name: PidTagMemberId Alternate names: PR\_MEMBER\_ID, ptagMemberId

### MEMBER_NAME {#MEMBER-NAME}
```
public static final PidTagPropertyDescriptor MEMBER_NAME
```


Contains the user-readable name of the user. Area: Access Control Properties Canonical name: PidTagMemberName Alternate names: PR\_MEMBER\_NAME, PR\_MEMBER\_NAME\_A, ptagMemberName, PR\_MEMBER\_NAME\_W

### MEMBER_RIGHTS {#MEMBER-RIGHTS}
```
public static final PidTagPropertyDescriptor MEMBER_RIGHTS
```


Contains the permissions for the specified user. Area: Access Control Properties Canonical name: PidTagMemberRights Alternate names: PR\_MEMBER\_RIGHTS, ptagMemberRights

### MESSAGE_ATTACHMENTS {#MESSAGE-ATTACHMENTS}
```
public static final PidTagPropertyDescriptor MESSAGE_ATTACHMENTS
```


Identifies all attachments to the current message. Area: Message Attachment Properties Canonical name: PidTagMessageAttachments Alternate names: PR\_MESSAGE\_ATTACHMENTS, ptagMessageAttachments

### MESSAGE_CC_ME {#MESSAGE-CC-ME}
```
public static final PidTagPropertyDescriptor MESSAGE_CC_ME
```


Area: General Message Properties Canonical name: PidTagMessageCcMe Alternate names: PR\_MESSAGE\_CC\_ME, ptagMessageCcMe

### MESSAGE_CLASS {#MESSAGE-CLASS}
```
public static final PidTagPropertyDescriptor MESSAGE_CLASS
```


Denotes the specific type of the Message object. Area: Common Property set Canonical name: PidTagMessageClass Alternate names: PR\_MESSAGE\_CLASS, PR\_MESSAGE\_CLASS\_A, ptagMessageClass, PR\_MESSAGE\_CLASS\_W,

### MESSAGE_CODEPAGE {#MESSAGE-CODEPAGE}
```
public static final PidTagPropertyDescriptor MESSAGE_CODEPAGE
```


Specifies the code page used to encode the non-Unicode string properties on this Message object. Area: Common Canonical name: PidTagMessageCodepage Alternate names: PR\_MESSAGE\_CODEPAGE

### MESSAGE_DELIVERY_ID {#MESSAGE-DELIVERY-ID}
```
public static final PidTagPropertyDescriptor MESSAGE_DELIVERY_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MESSAGE\_DELIVERY\_ID

### MESSAGE_DELIVERY_TIME {#MESSAGE-DELIVERY-TIME}
```
public static final PidTagPropertyDescriptor MESSAGE_DELIVERY_TIME
```


Specifies the time (in UTC) when the server received the message. Area: Message Time Properties Canonical name: PidTagMessageDeliveryTime Alternate names: PR\_MESSAGE\_DELIVERY\_TIME, urn:schemas:httpmail:datereceived

### MESSAGE_DOWNLOAD_TIME {#MESSAGE-DOWNLOAD-TIME}
```
public static final PidTagPropertyDescriptor MESSAGE_DOWNLOAD_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MESSAGE\_DOWNLOAD\_TIME

### MESSAGE_EDITOR_FORMAT {#MESSAGE-EDITOR-FORMAT}
```
public static final PidTagPropertyDescriptor MESSAGE_EDITOR_FORMAT
```


Specifies the format that an email editor can use for editing the message body. Area: Miscellaneous Properties Canonical name: PidTagMessageEditorFormat Alternate names: PR\_MSG\_EDITOR\_FORMAT, ptagMsgEditorFormat

### MESSAGE_FLAGS {#MESSAGE-FLAGS}
```
public static final PidTagPropertyDescriptor MESSAGE_FLAGS
```


Specifies the status of the Message object. Area: General Message Properties Canonical name: PidTagMessageFlags Alternate names: PR\_MESSAGE\_FLAGS, ptagMessageFlags

### MESSAGE_HANDLING_SYSTEM_COMMON_NAME {#MESSAGE-HANDLING-SYSTEM-COMMON-NAME}
```
public static final PidTagPropertyDescriptor MESSAGE_HANDLING_SYSTEM_COMMON_NAME
```


Contains the common name of a messaging user for use in a message header. Area: Address Properties Canonical name: PidTagMessageHandlingSystemCommonName Alternate names: PR\_MHS\_COMMON\_NAME, PR\_MHS\_COMMON\_NAME\_A,

### MESSAGE_LOCALE_ID {#MESSAGE-LOCALE-ID}
```
public static final PidTagPropertyDescriptor MESSAGE_LOCALE_ID
```


Contains the Windows Locale ID of the end-user who created this message. Area: Miscellaneous Properties Canonical name: PidTagMessageLocaleId Alternate names: PR\_MESSAGE\_LOCALE\_ID

### MESSAGE_PROCESSED {#MESSAGE-PROCESSED}
```
public static final PidTagPropertyDescriptor MESSAGE_PROCESSED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MESSAGE\_PROCESSED

### MESSAGE_RECIPIENTS {#MESSAGE-RECIPIENTS}
```
public static final PidTagPropertyDescriptor MESSAGE_RECIPIENTS
```


Identifies all of the recipients of the current message. Area: Address Properties Canonical name: PidTagMessageRecipients Alternate names: PR\_MESSAGE\_RECIPIENTS, ptagMessageRecipients

### MESSAGE_RECIPIENT_ME {#MESSAGE-RECIPIENT-ME}
```
public static final PidTagPropertyDescriptor MESSAGE_RECIPIENT_ME
```


Indicates that the receiving mailbox owner is a primary or a carbon copy (Cc) recipient of this email message. Area: General Message Properties Canonical name: PidTagMessageRecipientMe Alternate names: PR\_MESSAGE\_RECIP\_ME, ptagMessageRecipMe

### MESSAGE_SECURITY_LABEL {#MESSAGE-SECURITY-LABEL}
```
public static final PidTagPropertyDescriptor MESSAGE_SECURITY_LABEL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MESSAGE\_SECURITY\_LABEL

### MESSAGE_SITE_NAME {#MESSAGE-SITE-NAME}
```
public static final PidTagPropertyDescriptor MESSAGE_SITE_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MESSAGE\_SITE\_NAME

### MESSAGE_SIZE {#MESSAGE-SIZE}
```
public static final PidTagPropertyDescriptor MESSAGE_SIZE
```


Contains the size, in bytes, consumed by the Message object on the server. Area: General Message Properties Canonical name: PidTagMessageSize Alternate names: PR\_MESSAGE\_SIZE, ptagMessageSize

### MESSAGE_SIZE_EXTENDED {#MESSAGE-SIZE-EXTENDED}
```
public static final PidTagPropertyDescriptor MESSAGE_SIZE_EXTENDED
```


Specifies the 64-bit version of the PidTagMessageSize property (section 2.787). Area: General Message Properties Canonical name: PidTagMessageSizeExtended Alternate names: PR\_MESSAGE\_SIZE\_EXTENDED, ptagMessageSizeExtended

### MESSAGE_STATUS {#MESSAGE-STATUS}
```
public static final PidTagPropertyDescriptor MESSAGE_STATUS
```


Specifies the status of a message in a contents table. Area: General Message Properties Canonical name: PidTagMessageStatus Alternate names: PR\_MSG\_STATUS, ptagMsgStatus

### MESSAGE_SUBMISSION_ID {#MESSAGE-SUBMISSION-ID}
```
public static final PidTagPropertyDescriptor MESSAGE_SUBMISSION_ID
```


Contains a message identifier assigned by a message transfer agent. Area: Email Canonical name: PidTagMessageSubmissionId Alternate names: PR\_MESSAGE\_SUBMISSION\_ID, ptagMessageSubmissionId

### MESSAGE_TOKEN {#MESSAGE-TOKEN}
```
public static final PidTagPropertyDescriptor MESSAGE_TOKEN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MESSAGE\_TOKEN

### MESSAGE_TO_ME {#MESSAGE-TO-ME}
```
public static final PidTagPropertyDescriptor MESSAGE_TO_ME
```


Indicates that the receiving mailbox owner is one of the primary recipients of this email message. Area: General Message Properties Canonical name: PidTagMessageToMe Alternate names: PR\_MESSAGE\_TO\_ME, ptagMessageToMe

### MID {#MID}
```
public static final PidTagPropertyDescriptor MID
```


Contains a value that contains the MID of the message currently being synchronized. Area: ID Properties Canonical name: PidTagMid Alternate names: ptagMID, http://schemas.microsoft.com/exchange/mid

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final PidTagPropertyDescriptor MIDDLE_NAME
```


Specifies the middle name(s) of the contact. Area: Address Properties Canonical name: PidTagMiddleName Alternate names: PR\_MIDDLE\_NAME, PR\_MIDDLE\_NAME\_A, PR\_MIDDLE\_NAME\_W,

### MILEAGE {#MILEAGE}
```
public static final PidLidPropertyDescriptor MILEAGE
```


Contains the mileage information that is associated with an item. Area: General Message Properties Canonical name: PidLidMileage Alternate names: dispidMileage

### MIME_SKELETON {#MIME-SKELETON}
```
public static final PidTagPropertyDescriptor MIME_SKELETON
```


Contains the top-level MIME message headers, all MIME message body part headers, attachments. Area: MIME properties Canonical name: PidTagMimeSkeleton Alternate names: ptagMimeSkeleton

### MINI_ICON {#MINI-ICON}
```
public static final PidTagPropertyDescriptor MINI_ICON
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MINI\_ICON

### MOBILE_TELEPHONE_NUMBER {#MOBILE-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor MOBILE_TELEPHONE_NUMBER
```


Contains the mail user's cellular telephone number. Area: Address Properties Canonical name: PidTagMobileTelephoneNumber Alternate names: PR\_MOBILE\_TELEPHONE\_NUMBER, PR\_MOBILE\_TELEPHONE\_NUMBER\_A,

### MODIFY_VERSION {#MODIFY-VERSION}
```
public static final PidTagPropertyDescriptor MODIFY_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MODIFY\_VERSION

### MONTH_INTERVAL {#MONTH-INTERVAL}
```
public static final PidLidPropertyDescriptor MONTH_INTERVAL
```


Indicates the monthly interval of the appointment or meeting. Area: Meetings Canonical name: PidLidMonthInterval Alternate names: LID\_MONTH\_INTERVAL

### MONTH_OF_YEAR {#MONTH-OF-YEAR}
```
public static final PidLidPropertyDescriptor MONTH_OF_YEAR
```


Indicates the month of the year in which the appointment or meeting occurs. Area: Calendar Canonical name: PidLidMonthOfYear Alternate names:

### MONTH_OF_YEAR_MASK {#MONTH-OF-YEAR-MASK}
```
public static final PidLidPropertyDescriptor MONTH_OF_YEAR_MASK
```


Indicates the calculated month of the year in which the appointment or meeting occurs. Area: Meetings Canonical name: PidLidMonthOfYearMask Alternate names: LID\_MOY\_MASK

### MOVE_TO_FOLDER_ENTRYID {#MOVE-TO-FOLDER-ENTRYID}
```
public static final PidTagPropertyDescriptor MOVE_TO_FOLDER_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MOVE\_TO\_FOLDER\_ENTRYID

### MOVE_TO_STORE_ENTRYID {#MOVE-TO-STORE-ENTRYID}
```
public static final PidTagPropertyDescriptor MOVE_TO_STORE_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MOVE\_TO\_STORE\_ENTRYID

### MSG_BODY_ID {#MSG-BODY-ID}
```
public static final PidTagPropertyDescriptor MSG_BODY_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MSG\_BODY\_ID

### MTS_SUBJECT_ID {#MTS-SUBJECT-ID}
```
public static final PidTagPropertyDescriptor MTS_SUBJECT_ID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_MTS\_SUBJECT\_ID

### MULTIMEDIA_CLIP_COUNT {#MULTIMEDIA-CLIP-COUNT}
```
public static final PidNamePropertyDescriptor MULTIMEDIA_CLIP_COUNT
```


Specifies the number of multimedia clips in the file attached to the Document object. Area: Common Canonical name: PidNameMultimediaClipCount Alternate names: urn:schemas-microsoft-com:office:office\#MultimediaClips

### NATIVE_BODY {#NATIVE-BODY}
```
public static final PidTagPropertyDescriptor NATIVE_BODY
```


Indicates the best available format for storing the message body. Area: BestBody Canonical name: PidTagNativeBody Alternate names: PR\_NATIVE\_BODY\_INFO, ptagNativeBodyInfo

### NET_SHOW_URL {#NET-SHOW-URL}
```
public static final PidLidPropertyDescriptor NET_SHOW_URL
```


Specifies the URL to be launched when the user joins the meeting. Area: Conferencing Canonical name: PidLidNetShowUrl Alternate names: dispidNetShowURL

### NEWSFEED_INFO {#NEWSFEED-INFO}
```
public static final PidTagPropertyDescriptor NEWSFEED_INFO
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NEWSFEED\_INFO

### NEWSGROUP_COMPONENT {#NEWSGROUP-COMPONENT}
```
public static final PidTagPropertyDescriptor NEWSGROUP_COMPONENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NEWSGROUP\_COMPONENT

### NEWSGROUP_NAME {#NEWSGROUP-NAME}
```
public static final PidTagPropertyDescriptor NEWSGROUP_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NEWSGROUP\_NAME

### NEWSGROUP_ROOT_FOLDER_ENTRYID {#NEWSGROUP-ROOT-FOLDER-ENTRYID}
```
public static final PidTagPropertyDescriptor NEWSGROUP_ROOT_FOLDER_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NEWSGROUP\_ROOT\_FOLDER\_ENTRYID

### NEW_SUBS_GET_AUTO_ADD {#NEW-SUBS-GET-AUTO-ADD}
```
public static final PidTagPropertyDescriptor NEW_SUBS_GET_AUTO_ADD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NEW\_SUBS\_GET\_AUTO\_ADD

### NEXT_SEND_ACCT {#NEXT-SEND-ACCT}
```
public static final PidTagPropertyDescriptor NEXT_SEND_ACCT
```


Specifies the server that a client is currently attempting to use to send email. Area: Outlook Application Canonical name: PidTagNextSendAcct Alternate names: PR\_NEXT\_SEND\_ACCT

### NICKNAME {#NICKNAME}
```
public static final PidTagPropertyDescriptor NICKNAME
```


Contains the mail user's nickname. Area: Address Properties Canonical name: PidTagNickname Alternate names: PR\_NICKNAME, PR\_NICKNAME\_A, PR\_NICKNAME\_W,

### NNTP_ARTICLE_FOLDER_ENTRYID {#NNTP-ARTICLE-FOLDER-ENTRYID}
```
public static final PidTagPropertyDescriptor NNTP_ARTICLE_FOLDER_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NNTP\_ARTICLE\_FOLDER\_ENTRYID

### NNTP_CONTROL_FOLDER_ENTRYID {#NNTP-CONTROL-FOLDER-ENTRYID}
```
public static final PidTagPropertyDescriptor NNTP_CONTROL_FOLDER_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NNTP\_CONTROL\_FOLDER\_ENTRYID

### NNTP_XREF {#NNTP-XREF}
```
public static final PidTagPropertyDescriptor NNTP_XREF
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NNTP\_XREF

### NON_DELIVERY_REPORT_DIAG_CODE {#NON-DELIVERY-REPORT-DIAG-CODE}
```
public static final PidTagPropertyDescriptor NON_DELIVERY_REPORT_DIAG_CODE
```


Contains the diagnostic code for a delivery status notification, as specified in [RFC3464]. Area: Email Canonical name: PidTagNonDeliveryReportDiagCode Alternate names: PR\_NDR\_DIAG\_CODE, ptagNonDeliveryDiagCode

### NON_DELIVERY_REPORT_REASON_CODE {#NON-DELIVERY-REPORT-REASON-CODE}
```
public static final PidTagPropertyDescriptor NON_DELIVERY_REPORT_REASON_CODE
```


Contains an integer value that indicates a reason for delivery failure. Area: Email Canonical name: PidTagNonDeliveryReportReasonCode Alternate names: PR\_NDR\_REASON\_CODE, ptagNDRReasonCode

### NON_DELIVERY_REPORT_STATUS_CODE {#NON-DELIVERY-REPORT-STATUS-CODE}
```
public static final PidTagPropertyDescriptor NON_DELIVERY_REPORT_STATUS_CODE
```


Contains the value of the Status field for a delivery status notification, as specified in [RFC3464]. Area: Email Canonical name: PidTagNonDeliveryReportStatusCode Alternate names: PR\_NDR\_STATUS\_CODE, ptagNDRStatusCode

### NON_IPM_SUBTREE_ENTRYID {#NON-IPM-SUBTREE-ENTRYID}
```
public static final PidTagPropertyDescriptor NON_IPM_SUBTREE_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NON\_IPM\_SUBTREE\_ENTRYID

### NON_RECEIPT_NOTIFICATION_REQUESTED {#NON-RECEIPT-NOTIFICATION-REQUESTED}
```
public static final PidTagPropertyDescriptor NON_RECEIPT_NOTIFICATION_REQUESTED
```


Specifies whether the client sends a non-read receipt. Area: Email Canonical name: PidTagNonReceiptNotificationRequested Alternate names: PR\_NON\_RECEIPT\_NOTIFICATION\_REQUESTED

### NON_RECEIPT_REASON {#NON-RECEIPT-REASON}
```
public static final PidTagPropertyDescriptor NON_RECEIPT_REASON
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NON\_RECEIPT\_REASON

### NON_SENDABLE_BCC {#NON-SENDABLE-BCC}
```
public static final PidLidPropertyDescriptor NON_SENDABLE_BCC
```


Contains a list of all of the unsendable attendees who are also resources. Area: Meetings Canonical name: PidLidNonSendableBcc Alternate names: dispidNonSendableBCC

### NON_SENDABLE_CC {#NON-SENDABLE-CC}
```
public static final PidLidPropertyDescriptor NON_SENDABLE_CC
```


Contains a list of all of the unsendable attendees who are also optional attendees. Area: Meetings Canonical name: PidLidNonSendableCc Alternate names: dispidNonSendableCC

### NON_SENDABLE_TO {#NON-SENDABLE-TO}
```
public static final PidLidPropertyDescriptor NON_SENDABLE_TO
```


Contains a list of all of the unsendable attendees who are also required attendees. Area: Meetings Canonical name: PidLidNonSendableTo Alternate names: dispidNonSendableTo

### NON_SEND_BCC_TRACK_STATUS {#NON-SEND-BCC-TRACK-STATUS}
```
public static final PidLidPropertyDescriptor NON_SEND_BCC_TRACK_STATUS
```


Contains the value from the response table. Area: General Message Properties Canonical name: PidLidNonSendBccTrackStatus Alternate names: dispidNonSendBccTrackStatus

### NON_SEND_CC_TRACK_STATUS {#NON-SEND-CC-TRACK-STATUS}
```
public static final PidLidPropertyDescriptor NON_SEND_CC_TRACK_STATUS
```


Contains the value from the response table. Area: General Message Properties Canonical name: PidLidNonSendCcTrackStatus Alternate names: dispidNonSendCcTrackStatus

### NON_SEND_TO_TRACK_STATUS {#NON-SEND-TO-TRACK-STATUS}
```
public static final PidLidPropertyDescriptor NON_SEND_TO_TRACK_STATUS
```


Contains the value from the response table. Area: General Message Properties Canonical name: PidLidNonSendToTrackStatus Alternate names: dispidNonSendToTrackStatus

### NORMALIZED_SUBJECT {#NORMALIZED-SUBJECT}
```
public static final PidTagPropertyDescriptor NORMALIZED_SUBJECT
```


Contains the normalized subject of the message. Area: Email Canonical name: PidTagNormalizedSubject Alternate names: PR\_NORMALIZED\_SUBJECT, PR\_NORMALIZED\_SUBJECT\_A,

### NORMAL_MESSAGE_SIZE {#NORMAL-MESSAGE-SIZE}
```
public static final PidTagPropertyDescriptor NORMAL_MESSAGE_SIZE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NORMAL\_MESSAGE\_SIZE

### NORMAL_MESSAGE_SIZE_EXTENDED {#NORMAL-MESSAGE-SIZE-EXTENDED}
```
public static final PidTagPropertyDescriptor NORMAL_MESSAGE_SIZE_EXTENDED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NORMAL\_MESSAGE\_SIZE\_EXTENDED

### NORMAL_MSG_W_ATTACH_COUNT {#NORMAL-MSG-W-ATTACH-COUNT}
```
public static final PidTagPropertyDescriptor NORMAL_MSG_W_ATTACH_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NORMAL\_MSG\_W\_ATTACH\_COUNT

### NOTE_COLOR {#NOTE-COLOR}
```
public static final PidLidPropertyDescriptor NOTE_COLOR
```


Specifies the suggested background color of the Note object. Area: Sticky Notes Canonical name: PidLidNoteColor Alternate names: dispidNoteColor

### NOTE_COUNT {#NOTE-COUNT}
```
public static final PidNamePropertyDescriptor NOTE_COUNT
```


Specifies the number of notes in the file attached to the Document object. Area: Common Canonical name: PidNameNoteCount Alternate names: urn:schemas-microsoft-com:office:office\#Notes

### NOTE_HEIGHT {#NOTE-HEIGHT}
```
public static final PidLidPropertyDescriptor NOTE_HEIGHT
```


Specifies the height of the visible message window in pixels. Area: Sticky Notes Canonical name: PidLidNoteHeight Alternate names: dispidNoteHeight

### NOTE_WIDTH {#NOTE-WIDTH}
```
public static final PidLidPropertyDescriptor NOTE_WIDTH
```


Specifies the width of the visible message window in pixels. Area: Sticky Notes Canonical name: PidLidNoteWidth Alternate names: dispidNoteWidth

### NOTE_X {#NOTE-X}
```
public static final PidLidPropertyDescriptor NOTE_X
```


Specifies the distance, in pixels, from the left edge of the screen that a user interface displays a Note object. Area: Sticky Notes Canonical name: PidLidNoteX Alternate names: dispidNoteX

### NOTE_Y {#NOTE-Y}
```
public static final PidLidPropertyDescriptor NOTE_Y
```


Specifies the distance, in pixels, from the top edge of the screen that a user interface displays a Note object. Area: Sticky Notes Canonical name: PidLidNoteY Alternate names: dispidNoteY

### NO_END_DATE_FLAG {#NO-END-DATE-FLAG}
```
public static final PidLidPropertyDescriptor NO_END_DATE_FLAG
```


Indicates whether the recurrence pattern has an end date. Area: Calendar Canonical name: PidLidNoEndDateFlag Alternate names: http://schemas.microsoft.com/mapi/fnoenddate

### NT_USER_NAME {#NT-USER-NAME}
```
public static final PidTagPropertyDescriptor NT_USER_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_NT\_USER\_NAME

### OBJECT_TYPE {#OBJECT-TYPE}
```
public static final PidTagPropertyDescriptor OBJECT_TYPE
```


Indicates the type of Server object. Area: Common Canonical name: PidTagObjectType Alternate names: PR\_OBJECT\_TYPE, ptagObjectType

### OBJECT_URI {#OBJECT-URI}
```
public static final PidTagPropertyDescriptor OBJECT_URI
```


Contains exchange task uri. This property does not transmit via transport protocols. Area: User-defined Aspose specified properties Alternate names: ObjectUri

### OBSOLETED_IPMS {#OBSOLETED-IPMS}
```
public static final PidTagPropertyDescriptor OBSOLETED_IPMS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OBSOLETED\_IPMS

### OCCURRENCES {#OCCURRENCES}
```
public static final PidLidPropertyDescriptor OCCURRENCES
```


Indicates the number of occurrences in the recurring appointment or meeting. Area: Calendar Canonical name: PidLidOccurrences Alternate names:

### OFFICE_LOCATION {#OFFICE-LOCATION}
```
public static final PidTagPropertyDescriptor OFFICE_LOCATION
```


Contains the mail user's office location. Area: Address Properties Canonical name: PidTagOfficeLocation Alternate names: PR\_OFFICE\_LOCATION, PR\_OFFICE\_LOCATION\_A, PR\_OFFICE\_LOCATION\_W,

### OFFLINE_ADDRBOOK_ENTRYID {#OFFLINE-ADDRBOOK-ENTRYID}
```
public static final PidTagPropertyDescriptor OFFLINE_ADDRBOOK_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OFFLINE\_ADDRBOOK\_ENTRYID

### OFFLINE_ADDRESS_BOOK_CONTAINER_GUID {#OFFLINE-ADDRESS-BOOK-CONTAINER-GUID}
```
public static final PidTagPropertyDescriptor OFFLINE_ADDRESS_BOOK_CONTAINER_GUID
```


A string-formatted GUID that represents the address list container object. Area: Offline Address Book Properties Canonical name: PidTagOfflineAddressBookContainerGuid Alternate names: PR\_OAB\_CONTAINER\_GUID, PR\_OAB\_CONTAINER\_GUID\_W

### OFFLINE_ADDRESS_BOOK_DISTINGUISHED_NAME {#OFFLINE-ADDRESS-BOOK-DISTINGUISHED-NAME}
```
public static final PidTagPropertyDescriptor OFFLINE_ADDRESS_BOOK_DISTINGUISHED_NAME
```


Contains the DN of the address list that is contained in the OAB message. Area: Offline Address Book Properties Canonical name: PidTagOfflineAddressBookDistinguishedName Alternate names: PR\_OAB\_DN, PR\_OAB\_DN\_W

### OFFLINE_ADDRESS_BOOK_MESSAGE_CLASS {#OFFLINE-ADDRESS-BOOK-MESSAGE-CLASS}
```
public static final PidTagPropertyDescriptor OFFLINE_ADDRESS_BOOK_MESSAGE_CLASS
```


Contains the message class for full OAB messages. Area: Offline Address Book Properties Canonical name: PidTagOfflineAddressBookMessageClass Alternate names: PR\_OAB\_MESSAGE\_CLASS

### OFFLINE_ADDRESS_BOOK_NAME {#OFFLINE-ADDRESS-BOOK-NAME}
```
public static final PidTagPropertyDescriptor OFFLINE_ADDRESS_BOOK_NAME
```


Contains the display name of the address list. Area: Offline Address Book Properties Canonical name: PidTagOfflineAddressBookName Alternate names: PR\_OAB\_NAME, PR\_OAB\_NAME\_W

### OFFLINE_ADDRESS_BOOK_SEQUENCE {#OFFLINE-ADDRESS-BOOK-SEQUENCE}
```
public static final PidTagPropertyDescriptor OFFLINE_ADDRESS_BOOK_SEQUENCE
```


Contains the sequence number of the OAB. Area: Offline Address Book Properties Canonical name: PidTagOfflineAddressBookSequence Alternate names: PR\_OAB\_SEQUENCE

### OFFLINE_ADDRESS_BOOK_TRUNCATED_PROPERTIES {#OFFLINE-ADDRESS-BOOK-TRUNCATED-PROPERTIES}
```
public static final PidTagPropertyDescriptor OFFLINE_ADDRESS_BOOK_TRUNCATED_PROPERTIES
```


Contains a list of the property tags that have been truncated or limited by the server. Area: Offline Address Book Properties Canonical name: PidTagOfflineAddressBookTruncatedProperties Alternate names: PR\_OAB\_TRUNCATED\_PROPS

### OFFLINE_FLAGS {#OFFLINE-FLAGS}
```
public static final PidTagPropertyDescriptor OFFLINE_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OFFLINE\_FLAGS

### OFFLINE_MESSAGE_ENTRYID {#OFFLINE-MESSAGE-ENTRYID}
```
public static final PidTagPropertyDescriptor OFFLINE_MESSAGE_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OFFLINE\_MESSAGE\_ENTRYID

### OLDEST_DELETED_ON {#OLDEST-DELETED-ON}
```
public static final PidTagPropertyDescriptor OLDEST_DELETED_ON
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OLDEST\_DELETED\_ON

### OLD_LOCATION {#OLD-LOCATION}
```
public static final PidLidPropertyDescriptor OLD_LOCATION
```


Indicates the original value of the PidLidLocation property (section 2.159) before a meeting update. Area: Meetings Canonical name: PidLidOldLocation Alternate names: dispidOldLocation

### OLD_RECURRENCE_TYPE {#OLD-RECURRENCE-TYPE}
```
public static final PidLidPropertyDescriptor OLD_RECURRENCE_TYPE
```


Indicates the recurrence pattern for the appointment or meeting. Area: Meetings Canonical name: PidLidOldRecurrenceType Alternate names: LID\_RECUR\_TYPE

### OLD_WHEN_END_WHOLE {#OLD-WHEN-END-WHOLE}
```
public static final PidLidPropertyDescriptor OLD_WHEN_END_WHOLE
```


Indicates the original value of the PidLidAppointmentEndWhole property (section 2.14) before a meeting update. Area: Meetings Canonical name: PidLidOldWhenEndWhole Alternate names: dispidOldWhenEndWhole

### OLD_WHEN_START_WHOLE {#OLD-WHEN-START-WHOLE}
```
public static final PidLidPropertyDescriptor OLD_WHEN_START_WHOLE
```


Indicates the original value of the PidLidAppointmentStartWhole property (section 2.29) before a meeting update. Area: Meetings Canonical name: PidLidOldWhenStartWhole Alternate names: dispidOldWhenStartWhole

### OMS_ACCOUNT_GUID {#OMS-ACCOUNT-GUID}
```
public static final PidNamePropertyDescriptor OMS_ACCOUNT_GUID
```


Contains the GUID of the SMS account used to deliver the message. Area: SMS Canonical name: PidNameOMSAccountGuid Alternate names:

### OMS_MOBILE_MODEL {#OMS-MOBILE-MODEL}
```
public static final PidNamePropertyDescriptor OMS_MOBILE_MODEL
```


Indicates the model of the mobile device used to send the SMS or MMS message. Area: SMS Canonical name: PidNameOMSMobileModel Alternate names:

### OMS_SCHEDULE_TIME {#OMS-SCHEDULE-TIME}
```
public static final PidNamePropertyDescriptor OMS_SCHEDULE_TIME
```


Contains the time, in UTC, at which the client requested that the service provider send the SMS or MMS message. Area: SMS Canonical name: PidNameOMSScheduleTime Alternate names:

### OMS_SERVICE_TYPE {#OMS-SERVICE-TYPE}
```
public static final PidNamePropertyDescriptor OMS_SERVICE_TYPE
```


Contains the type of service used to send an SMS or MMS message. Area: SMS Canonical name: PidNameOMSServiceType Alternate names:

### OMS_SOURCE_TYPE {#OMS-SOURCE-TYPE}
```
public static final PidNamePropertyDescriptor OMS_SOURCE_TYPE
```


Contains the source of an SMS or MMS message. Area: SMS Canonical name: PidNameOMSSourceType Alternate names:

### ONLINE_PASSWORD {#ONLINE-PASSWORD}
```
public static final PidLidPropertyDescriptor ONLINE_PASSWORD
```


Specifies the password for a meeting on which the PidLidConferencingType property (section 2.66) has the value 0x00000002. Area: Conferencing Canonical name: PidLidOnlinePassword Alternate names: dispidOnlinePassword

### OPTIONAL_ATTENDEES {#OPTIONAL-ATTENDEES}
```
public static final PidLidPropertyDescriptor OPTIONAL_ATTENDEES
```


Specifies optional attendees. Area: Meetings Canonical name: PidLidOptionalAttendees Alternate names: LID\_OPTIONAL\_ATTENDEES

### ORDINAL_MOST {#ORDINAL-MOST}
```
public static final PidTagPropertyDescriptor ORDINAL_MOST
```


Contains a positive number whose negative is less than or equal to the value of the PidLidTaskOrdinal property (section 2.327) of all of the Task objects in the folder. Area: Tasks Canonical name: PidTagOrdinalMost Alternate names: PR\_ORDINAL\_MOST

### ORGANIZATIONAL_ID_NUMBER {#ORGANIZATIONAL-ID-NUMBER}
```
public static final PidTagPropertyDescriptor ORGANIZATIONAL_ID_NUMBER
```


Contains an identifier for the mail user used within the mail user's organization. Area: Address Properties Canonical name: PidTagOrganizationalIdNumber Alternate names: PR\_ORGANIZATIONAL\_ID\_NUMBER, PR\_ORGANIZATIONAL\_ID\_NUMBER\_A,

### ORGANIZER_ALIAS {#ORGANIZER-ALIAS}
```
public static final PidLidPropertyDescriptor ORGANIZER_ALIAS
```


Specifies the email address of the organizer. Area: Conferencing Canonical name: PidLidOrganizerAlias Alternate names: dispidOrgAlias

### ORIGINALLY_INTENDED_RECIPIENT_NAME {#ORIGINALLY-INTENDED-RECIPIENT-NAME}
```
public static final PidTagPropertyDescriptor ORIGINALLY_INTENDED_RECIPIENT_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINALLY\_INTENDED\_RECIPIENT\_NAME

### ORIGINALLY_INTENDED_RECIP_ADDRTYPE {#ORIGINALLY-INTENDED-RECIP-ADDRTYPE}
```
public static final PidTagPropertyDescriptor ORIGINALLY_INTENDED_RECIP_ADDRTYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINALLY\_INTENDED\_RECIP\_ADDRTYPE

### ORIGINALLY_INTENDED_RECIP_EMAIL_ADDRESS {#ORIGINALLY-INTENDED-RECIP-EMAIL-ADDRESS}
```
public static final PidTagPropertyDescriptor ORIGINALLY_INTENDED_RECIP_EMAIL_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINALLY\_INTENDED\_RECIP\_EMAIL\_ADDRESS

### ORIGINALLY_INTENDED_RECIP_ENTRYID {#ORIGINALLY-INTENDED-RECIP-ENTRYID}
```
public static final PidTagPropertyDescriptor ORIGINALLY_INTENDED_RECIP_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINALLY\_INTENDED\_RECIP\_ENTRYID

### ORIGINAL_AUTHOR_ADDRTYPE {#ORIGINAL-AUTHOR-ADDRTYPE}
```
public static final PidTagPropertyDescriptor ORIGINAL_AUTHOR_ADDRTYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINAL\_AUTHOR\_ADDRTYPE

### ORIGINAL_AUTHOR_EMAIL_ADDRESS {#ORIGINAL-AUTHOR-EMAIL-ADDRESS}
```
public static final PidTagPropertyDescriptor ORIGINAL_AUTHOR_EMAIL_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINAL\_AUTHOR\_EMAIL\_ADDRESS

### ORIGINAL_AUTHOR_ENTRY_ID {#ORIGINAL-AUTHOR-ENTRY-ID}
```
public static final PidTagPropertyDescriptor ORIGINAL_AUTHOR_ENTRY_ID
```


Contains an address book EntryID structure ([MS-OXCDATA] section 2.2.5.2) and is defined in report messages to identify the user who sent the original message. Area: Email Canonical name: PidTagOriginalAuthorEntryId Alternate names: PR\_ORIGINAL\_AUTHOR\_ENTRYID

### ORIGINAL_AUTHOR_NAME {#ORIGINAL-AUTHOR-NAME}
```
public static final PidTagPropertyDescriptor ORIGINAL_AUTHOR_NAME
```


Contains the display name of the sender of the original message referenced by a report message. Area: Email Canonical name: PidTagOriginalAuthorName Alternate names: PR\_ORIGINAL\_AUTHOR\_NAME\_W

### ORIGINAL_AUTHOR_SEARCH_KEY {#ORIGINAL-AUTHOR-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor ORIGINAL_AUTHOR_SEARCH_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINAL\_AUTHOR\_SEARCH\_KEY

### ORIGINAL_DELIVERY_TIME {#ORIGINAL-DELIVERY-TIME}
```
public static final PidTagPropertyDescriptor ORIGINAL_DELIVERY_TIME
```


Contains the delivery time, in UTC, from the original message. Area: General Message Properties Canonical name: PidTagOriginalDeliveryTime Alternate names: PR\_ORIGINAL\_DELIVERY\_TIME, ptagOriginalDeliveryTime

### ORIGINAL_DISPLAY_BCC {#ORIGINAL-DISPLAY-BCC}
```
public static final PidTagPropertyDescriptor ORIGINAL_DISPLAY_BCC
```


Contains the value of the PidTagDisplayBcc property (section 2.665) from the original message. Area: General Message Properties Canonical name: PidTagOriginalDisplayBcc Alternate names: PR\_ORIGINAL\_DISPLAY\_BCC, PR\_ORIGINAL\_DISPLAY\_BCC\_A, ptagOriginalDisplayBcc, PR\_ORIGINAL\_DISPLAY\_BCC\_W,

### ORIGINAL_DISPLAY_CC {#ORIGINAL-DISPLAY-CC}
```
public static final PidTagPropertyDescriptor ORIGINAL_DISPLAY_CC
```


Contains the value of the PidTagDisplayCc property(section 2.666) from the original message. Area: General Message Properties Canonical name: PidTagOriginalDisplayCc Alternate names: PR\_ORIGINAL\_DISPLAY\_CC, PR\_ORIGINAL\_DISPLAY\_CC\_A, ptagOriginalDisplayCc, PR\_ORIGINAL\_DISPLAY\_CC\_W,

### ORIGINAL_DISPLAY_NAME {#ORIGINAL-DISPLAY-NAME}
```
public static final PidTagPropertyDescriptor ORIGINAL_DISPLAY_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINAL\_DISPLAY\_NAME

### ORIGINAL_DISPLAY_TO {#ORIGINAL-DISPLAY-TO}
```
public static final PidTagPropertyDescriptor ORIGINAL_DISPLAY_TO
```


Contains the value of the PidTagDisplayTo property (section 2.669) from the original message. Area: General Message Properties Canonical name: PidTagOriginalDisplayTo Alternate names: PR\_ORIGINAL\_DISPLAY\_TO, PR\_ORIGINAL\_DISPLAY\_TO\_A, ptagOriginalDisplayTo, PR\_ORIGINAL\_DISPLAY\_TO\_W,

### ORIGINAL_EITS {#ORIGINAL-EITS}
```
public static final PidTagPropertyDescriptor ORIGINAL_EITS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINAL\_EITS

### ORIGINAL_ENTRY_ID {#ORIGINAL-ENTRY-ID}
```
public static final PidTagPropertyDescriptor ORIGINAL_ENTRY_ID
```


Contains the original EntryID of an object. Area: General Message Properties Canonical name: PidTagOriginalEntryId Alternate names: PR\_ORIGINAL\_ENTRYID, ptagOriginalEntryId

### ORIGINAL_MESSAGE_CLASS {#ORIGINAL-MESSAGE-CLASS}
```
public static final PidTagPropertyDescriptor ORIGINAL_MESSAGE_CLASS
```


Designates the PidTagMessageClass property ([MS-OXCMSG] section 2.2.1.3) from the original message. Area: Secure Messaging Properties Canonical name: PidTagOriginalMessageClass Alternate names: PR\_ORIG\_MESSAGE\_CLASS, PR\_ORIG\_MESSAGE\_CLASS\_A, PR\_ORIG\_MESSAGE\_CLASS\_W

### ORIGINAL_MESSAGE_ID {#ORIGINAL-MESSAGE-ID}
```
public static final PidTagPropertyDescriptor ORIGINAL_MESSAGE_ID
```


Contains the message ID of the original message included in replies or resent messages. Area: Mail Canonical name: PidTagOriginalMessageId Alternate names: ptagOriginalInternetMessageID, OriginalMessageId

### ORIGINAL_SEARCH_KEY {#ORIGINAL-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor ORIGINAL_SEARCH_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINAL\_SEARCH\_KEY

### ORIGINAL_SENDER_ADDRESS_TYPE {#ORIGINAL-SENDER-ADDRESS-TYPE}
```
public static final PidTagPropertyDescriptor ORIGINAL_SENDER_ADDRESS_TYPE
```


Contains the value of the original message sender's PidTagSenderAddressType property (section 2.991). Area: General Message Properties Canonical name: PidTagOriginalSenderAddressType Alternate names: PR\_ORIGINAL\_SENDER\_ADDRTYPE, PR\_ORIGINAL\_SENDER\_ADDRTYPE\_A, ptagOriginalSenderAddrType, PR\_ORIGINAL\_SENDER\_ADDRTYPE\_W

### ORIGINAL_SENDER_EMAIL_ADDRESS {#ORIGINAL-SENDER-EMAIL-ADDRESS}
```
public static final PidTagPropertyDescriptor ORIGINAL_SENDER_EMAIL_ADDRESS
```


Contains the value of the original message sender's PidTagSenderEmailAddress property (section 2.992). Area: General Message Properties Canonical name: PidTagOriginalSenderEmailAddress Alternate names: PR\_ORIGINAL\_SENDER\_EMAIL\_ADDRESS, PR\_ORIGINAL\_SENDER\_EMAIL\_ADDRESS\_A, PR\_ORIGINAL\_SENDER\_EMAIL\_ADDRESS\_W

### ORIGINAL_SENDER_ENTRY_ID {#ORIGINAL-SENDER-ENTRY-ID}
```
public static final PidTagPropertyDescriptor ORIGINAL_SENDER_ENTRY_ID
```


Contains an address book EntryID that is set on delivery report messages. Area: General Message Properties Canonical name: PidTagOriginalSenderEntryId Alternate names: PR\_ORIGINAL\_SENDER\_ENTRYID, ptagOriginalSenderEntryId

### ORIGINAL_SENDER_NAME {#ORIGINAL-SENDER-NAME}
```
public static final PidTagPropertyDescriptor ORIGINAL_SENDER_NAME
```


Contains the value of the original message sender's PidTagSenderName property (section 2.995), and is set on delivery report messages. Area: General Message Properties Canonical name: PidTagOriginalSenderName Alternate names: PR\_ORIGINAL\_SENDER\_NAME, PR\_ORIGINAL\_SENDER\_NAME\_A, ptagOriginalSenderName, PR\_ORIGINAL\_SENDER\_NAME\_W,

### ORIGINAL_SENDER_SEARCH_KEY {#ORIGINAL-SENDER-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor ORIGINAL_SENDER_SEARCH_KEY
```


Contains an address book search key set on the original email message. Area: General Message Properties Canonical name: PidTagOriginalSenderSearchKey Alternate names: PR\_ORIGINAL\_SENDER\_SEARCH\_KEY, ptagOriginalSenderSearchKey

### ORIGINAL_SENSITIVITY {#ORIGINAL-SENSITIVITY}
```
public static final PidTagPropertyDescriptor ORIGINAL_SENSITIVITY
```


Contains the sensitivity value of the original email message. Area: General Message Properties Canonical name: PidTagOriginalSensitivity Alternate names: PR\_ORIGINAL\_SENSITIVITY, ptagOriginalSensitivity

### ORIGINAL_SENT_REPRESENTING_ADDRESS_TYPE {#ORIGINAL-SENT-REPRESENTING-ADDRESS-TYPE}
```
public static final PidTagPropertyDescriptor ORIGINAL_SENT_REPRESENTING_ADDRESS_TYPE
```


Contains the address type of the end user who is represented by the original email message sender. Area: General Message Properties Canonical name: PidTagOriginalSentRepresentingAddressType Alternate names: PR\_ORIGINAL\_SENT\_REPRESENTING\_ADDRTYPE, PR\_ORIGINAL\_SENT\_REPRESENTING\_ADDRTYPE\_W

### ORIGINAL_SENT_REPRESENTING_EMAIL_ADDRESS {#ORIGINAL-SENT-REPRESENTING-EMAIL-ADDRESS}
```
public static final PidTagPropertyDescriptor ORIGINAL_SENT_REPRESENTING_EMAIL_ADDRESS
```


Contains the email address of the end user who is represented by the original email message sender. Area: General Message Properties Canonical name: PidTagOriginalSentRepresentingEmailAddress Alternate names: PR\_ORIGINAL\_SENT\_REPRESENTING\_EMAIL\_ADDRESS, PR\_ORIGINAL\_SENT\_REPRESENTING\_EMAIL\_ADDRESS\_W

### ORIGINAL_SENT_REPRESENTING_ENTRY_ID {#ORIGINAL-SENT-REPRESENTING-ENTRY-ID}
```
public static final PidTagPropertyDescriptor ORIGINAL_SENT_REPRESENTING_ENTRY_ID
```


Identifies an address book EntryID that contains the entry identifier of the end user who is represented by the original message sender. Area: General Message Properties Canonical name: PidTagOriginalSentRepresentingEntryId Alternate names: PR\_ORIGINAL\_SENT\_REPRESENTING\_ENTRYID, ptagOriginalSentRepresentingEntryId

### ORIGINAL_SENT_REPRESENTING_NAME {#ORIGINAL-SENT-REPRESENTING-NAME}
```
public static final PidTagPropertyDescriptor ORIGINAL_SENT_REPRESENTING_NAME
```


Contains the display name of the end user who is represented by the original email message sender. Area: General Message Properties Canonical name: PidTagOriginalSentRepresentingName Alternate names: PR\_ORIGINAL\_SENT\_REPRESENTING\_NAME, PR\_ORIGINAL\_SENT\_REPRESENTING\_NAME\_W

### ORIGINAL_SENT_REPRESENTING_SEARCH_KEY {#ORIGINAL-SENT-REPRESENTING-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor ORIGINAL_SENT_REPRESENTING_SEARCH_KEY
```


Identifies an address book search key that contains the SearchKey of the end user who is represented by the original message sender. Area: General Message Properties Canonical name: PidTagOriginalSentRepresentingSearchKey Alternate names: PR\_ORIGINAL\_SENT\_REPRESENTING\_SEARCH\_KEY, ptagOriginalSentRepresentingSearchKey

### ORIGINAL_STORE_ENTRY_ID {#ORIGINAL-STORE-ENTRY-ID}
```
public static final PidLidPropertyDescriptor ORIGINAL_STORE_ENTRY_ID
```


Specifies the EntryID of the delegator\\ufffds message store. Area: Meetings Canonical name: PidLidOriginalStoreEntryId Alternate names: dispidOrigStoreEid, http://schemas.microsoft.com/mapi/origstoreeid

### ORIGINAL_SUBJECT {#ORIGINAL-SUBJECT}
```
public static final PidTagPropertyDescriptor ORIGINAL_SUBJECT
```


Specifies the subject of the original message. Area: General Message Properties Canonical name: PidTagOriginalSubject Alternate names: PR\_ORIGINAL\_SUBJECT, PR\_ORIGINAL\_SUBJECT\_A, ptagOriginalSubject,

### ORIGINAL_SUBMIT_TIME {#ORIGINAL-SUBMIT-TIME}
```
public static final PidTagPropertyDescriptor ORIGINAL_SUBMIT_TIME
```


Specifies the original email message's submission date and time, in UTC. Area: General Message Properties Canonical name: PidTagOriginalSubmitTime Alternate names: PR\_ORIGINAL\_SUBMIT\_TIME, ptagOriginalSubmitTime,

### ORIGINATING_MTA_CERTIFICATE {#ORIGINATING-MTA-CERTIFICATE}
```
public static final PidTagPropertyDescriptor ORIGINATING_MTA_CERTIFICATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINATING\_MTA\_CERTIFICATE

### ORIGINATOR_ADDR {#ORIGINATOR-ADDR}
```
public static final PidTagPropertyDescriptor ORIGINATOR_ADDR
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINATOR\_ADDR

### ORIGINATOR_ADDRTYPE {#ORIGINATOR-ADDRTYPE}
```
public static final PidTagPropertyDescriptor ORIGINATOR_ADDRTYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINATOR\_ADDRTYPE

### ORIGINATOR_AND_DL_EXPANSION_HISTORY {#ORIGINATOR-AND-DL-EXPANSION-HISTORY}
```
public static final PidTagPropertyDescriptor ORIGINATOR_AND_DL_EXPANSION_HISTORY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINATOR\_AND\_DL\_EXPANSION\_HISTORY

### ORIGINATOR_CERTIFICATE {#ORIGINATOR-CERTIFICATE}
```
public static final PidTagPropertyDescriptor ORIGINATOR_CERTIFICATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINATOR\_CERTIFICATE

### ORIGINATOR_DELIVERY_REPORT_REQUESTED {#ORIGINATOR-DELIVERY-REPORT-REQUESTED}
```
public static final PidTagPropertyDescriptor ORIGINATOR_DELIVERY_REPORT_REQUESTED
```


Indicates whether an email sender requests an email delivery receipt from the messaging system. Area: MIME Properties Canonical name: PidTagOriginatorDeliveryReportRequested Alternate names: PR\_ORIGINATOR\_DELIVERY\_REPORT\_REQUESTED,

### ORIGINATOR_ENTRYID {#ORIGINATOR-ENTRYID}
```
public static final PidTagPropertyDescriptor ORIGINATOR_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINATOR\_ENTRYID

### ORIGINATOR_NAME {#ORIGINATOR-NAME}
```
public static final PidTagPropertyDescriptor ORIGINATOR_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINATOR\_NAME

### ORIGINATOR_NON_DELIVERY_REPORT_REQUESTED {#ORIGINATOR-NON-DELIVERY-REPORT-REQUESTED}
```
public static final PidTagPropertyDescriptor ORIGINATOR_NON_DELIVERY_REPORT_REQUESTED
```


Specifies whether an email sender requests suppression of nondelivery receipts. Area: MIME Properties Canonical name: PidTagOriginatorNonDeliveryReportRequested Alternate names: PR\_ORIGINATOR\_NON\_DELIVERY\_REPORT\_REQUESTED

### ORIGINATOR_REQUESTED_ALTERNATE_RECIPIENT {#ORIGINATOR-REQUESTED-ALTERNATE-RECIPIENT}
```
public static final PidTagPropertyDescriptor ORIGINATOR_REQUESTED_ALTERNATE_RECIPIENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINATOR\_REQUESTED\_ALTERNATE\_RECIPIENT

### ORIGINATOR_RETURN_ADDRESS {#ORIGINATOR-RETURN-ADDRESS}
```
public static final PidTagPropertyDescriptor ORIGINATOR_RETURN_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGINATOR\_RETURN\_ADDRESS

### ORIGIN_CHECK {#ORIGIN-CHECK}
```
public static final PidTagPropertyDescriptor ORIGIN_CHECK
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_ORIGIN\_CHECK

### OSC_SYNC_ENABLED {#OSC-SYNC-ENABLED}
```
public static final PidTagPropertyDescriptor OSC_SYNC_ENABLED
```


Specifies whether contact synchronization with an external source is handled by the server. Area: Contact Properties Canonical name: PidTagOscSyncEnabled Alternate names: PR\_OSC\_SYNC\_ENABLEDONSERVER

### OST_ENCRYPTION {#OST-ENCRYPTION}
```
public static final PidTagPropertyDescriptor OST_ENCRYPTION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OST\_ENCRYPTION

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final PidLidPropertyDescriptor OTHER_ADDRESS
```


Specifies the complete address of the other address of the contact. Area: Contact Properties Canonical name: PidLidOtherAddress Alternate names: dispidOtherAddress

### OTHER_ADDRESS_CITY {#OTHER-ADDRESS-CITY}
```
public static final PidTagPropertyDescriptor OTHER_ADDRESS_CITY
```


Contains the name of the mail user's other locality, such as the town or city. Area: Address Properties Canonical name: PidTagOtherAddressCity Alternate names: PR\_OTHER\_ADDRESS\_CITY, PR\_OTHER\_ADDRESS\_CITY\_A,

### OTHER_ADDRESS_COUNTRY {#OTHER-ADDRESS-COUNTRY}
```
public static final PidTagPropertyDescriptor OTHER_ADDRESS_COUNTRY
```


Contains the name of the mail user's other country/region. Area: Address Properties Canonical name: PidTagOtherAddressCountry Alternate names: PR\_OTHER\_ADDRESS\_COUNTRY, PR\_OTHER\_ADDRESS\_COUNTRY\_A,

### OTHER_ADDRESS_COUNTRY_CODE {#OTHER-ADDRESS-COUNTRY-CODE}
```
public static final PidLidPropertyDescriptor OTHER_ADDRESS_COUNTRY_CODE
```


Specifies the country code portion of the other address of the contact. Area: Contact Properties Canonical name: PidLidOtherAddressCountryCode Alternate names: dispidOtherAddressCountryCode

### OTHER_ADDRESS_POSTAL_CODE {#OTHER-ADDRESS-POSTAL-CODE}
```
public static final PidTagPropertyDescriptor OTHER_ADDRESS_POSTAL_CODE
```


Contains the postal code for the mail user's other postal address. Area: Address Properties Canonical name: PidTagOtherAddressPostalCode Alternate names: PR\_OTHER\_ADDRESS\_POSTAL\_CODE, PR\_OTHER\_ADDRESS\_POSTAL\_CODE\_A,

### OTHER_ADDRESS_POST_OFFICE_BOX {#OTHER-ADDRESS-POST-OFFICE-BOX}
```
public static final PidTagPropertyDescriptor OTHER_ADDRESS_POST_OFFICE_BOX
```


Contains the number or identifier of the mail user's other post office box. Area: Address Properties Canonical name: PidTagOtherAddressPostOfficeBox Alternate names: PR\_OTHER\_ADDRESS\_POST\_OFFICE\_BOX, PR\_OTHER\_ADDRESS\_POST\_OFFICE\_BOX\_A, PR\_OTHER\_ADDRESS\_POST\_OFFICE\_BOX\_W,

### OTHER_ADDRESS_STATE_OR_PROVINCE {#OTHER-ADDRESS-STATE-OR-PROVINCE}
```
public static final PidTagPropertyDescriptor OTHER_ADDRESS_STATE_OR_PROVINCE
```


Contains the name of the mail user's other state or province. Area: Address Properties Canonical name: PidTagOtherAddressStateOrProvince Alternate names: PR\_OTHER\_ADDRESS\_STATE\_OR\_PROVINCE, PR\_OTHER\_ADDRESS\_STATE\_OR\_PROVINCE\_A, PR\_OTHER\_ADDRESS\_STATE\_OR\_PROVINCE\_W,

### OTHER_ADDRESS_STREET {#OTHER-ADDRESS-STREET}
```
public static final PidTagPropertyDescriptor OTHER_ADDRESS_STREET
```


Contains the mail user's other street address. Area: Address Properties Canonical name: PidTagOtherAddressStreet Alternate names: PR\_OTHER\_ADDRESS\_STREET, PR\_OTHER\_ADDRESS\_STREET\_A,

### OTHER_TELEPHONE_NUMBER {#OTHER-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor OTHER_TELEPHONE_NUMBER
```


Contains an alternate telephone number for the mail user. Area: Address Properties Canonical name: PidTagOtherTelephoneNumber Alternate names: PR\_OTHER\_TELEPHONE\_NUMBER, PR\_OTHER\_TELEPHONE\_NUMBER\_A,

### OUTBOUND_NEWSFEED_DN {#OUTBOUND-NEWSFEED-DN}
```
public static final PidTagPropertyDescriptor OUTBOUND_NEWSFEED_DN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OUTBOUND\_NEWSFEED\_DN

### OUT_OF_OFFICE_STATE {#OUT-OF-OFFICE-STATE}
```
public static final PidTagPropertyDescriptor OUT_OF_OFFICE_STATE
```


Indicates whether the user is OOF. Area: Message Store Properties Canonical name: PidTagOutOfOfficeState Alternate names: PR\_OOF\_STATE, ptagOOFState

### OVERALL_AGE_LIMIT {#OVERALL-AGE-LIMIT}
```
public static final PidTagPropertyDescriptor OVERALL_AGE_LIMIT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OVERALL\_AGE\_LIMIT

### OVERALL_MSG_AGE_LIMIT {#OVERALL-MSG-AGE-LIMIT}
```
public static final PidTagPropertyDescriptor OVERALL_MSG_AGE_LIMIT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OVERALL\_MSG\_AGE\_LIMIT

### OWA_URL {#OWA-URL}
```
public static final PidTagPropertyDescriptor OWA_URL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OWA\_URL

### OWNER_APPOINTMENT_ID {#OWNER-APPOINTMENT-ID}
```
public static final PidTagPropertyDescriptor OWNER_APPOINTMENT_ID
```


Specifies a quasi-unique value among all of the Calendar objects in a user's mailbox. Area: Appointment Canonical name: PidTagOwnerAppointmentId Alternate names: PR\_OWNER\_APPT\_ID, http://schemas.microsoft.com/mapi/owner\_appt\_id

### OWNER_COUNT {#OWNER-COUNT}
```
public static final PidTagPropertyDescriptor OWNER_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OWNER\_COUNT

### OWNER_CRITICAL_CHANGE {#OWNER-CRITICAL-CHANGE}
```
public static final PidLidPropertyDescriptor OWNER_CRITICAL_CHANGE
```


Specifies the date and time at which a Meeting Request object was sent by the organizer. Area: Meetings Canonical name: PidLidOwnerCriticalChange Alternate names: LID\_OWNER\_CRITICAL\_CHANGE

### OWNER_NAME {#OWNER-NAME}
```
public static final PidLidPropertyDescriptor OWNER_NAME
```


Indicates the name of the owner of the mailbox. Area: Meetings Canonical name: PidLidOwnerName Alternate names: dispidOwnerName

### OWN_STORE_ENTRYID {#OWN-STORE-ENTRYID}
```
public static final PidTagPropertyDescriptor OWN_STORE_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_OWN\_STORE\_ENTRYID

### P1_CONTENT {#P1-CONTENT}
```
public static final PidTagPropertyDescriptor P1_CONTENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_P1\_CONTENT

### P1_CONTENT_TYPE {#P1-CONTENT-TYPE}
```
public static final PidTagPropertyDescriptor P1_CONTENT_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_P1\_CONTENT\_TYPE

### PAGER_TELEPHONE_NUMBER {#PAGER-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor PAGER_TELEPHONE_NUMBER
```


Contains the mail user's pager telephone number. Area: Address Properties Canonical name: PidTagPagerTelephoneNumber Alternate names: PR\_PAGER\_TELEPHONE\_NUMBER, PR\_PAGER\_TELEPHONE\_NUMBER\_A,

### PAGE_COUNT {#PAGE-COUNT}
```
public static final PidNamePropertyDescriptor PAGE_COUNT
```


Specifies the page count of the file attached to the Document object. Area: Common Canonical name: PidNamePageCount Alternate names: urn:schemas-microsoft-com:office:office\#Pages

### PARAGRAPH_COUNT {#PARAGRAPH-COUNT}
```
public static final PidNamePropertyDescriptor PARAGRAPH_COUNT
```


Specifies the number of paragraphs in the file attached to the Document object. Area: Common Canonical name: PidNameParagraphCount Alternate names: urn:schemas-microsoft-com:office:office\#Paragraphs

### PARENT_DISPLAY {#PARENT-DISPLAY}
```
public static final PidTagPropertyDescriptor PARENT_DISPLAY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PARENT\_DISPLAY

### PARENT_ENTRY_ID {#PARENT-ENTRY-ID}
```
public static final PidTagPropertyDescriptor PARENT_ENTRY_ID
```


Contains the EntryID of the folder where messages or subfolders reside. Area: ID Properties Canonical name: PidTagParentEntryId Alternate names: PR\_PARENT\_ENTRYID, ptagParentEntryId

### PARENT_FOLDER_ID {#PARENT-FOLDER-ID}
```
public static final PidTagPropertyDescriptor PARENT_FOLDER_ID
```


Contains a value that contains the Folder ID (FID), as specified in [MS-OXCDATA] section 2.2.1.1, that identifies the parent folder of the messaging object being synchronized. Area: ID Properties Canonical name: PidTagParentFolderId Alternate names: ptagParentFID

### PARENT_KEY {#PARENT-KEY}
```
public static final PidTagPropertyDescriptor PARENT_KEY
```


Contains the search key that is used to correlate the original message and the reports about the original message. Area: MapiEnvelope Canonical name: PidTagParentKey Alternate names: PR\_PARENT\_KEY, ptagParentKey

### PARENT_SOURCE_KEY {#PARENT-SOURCE-KEY}
```
public static final PidTagPropertyDescriptor PARENT_SOURCE_KEY
```


Contains a value on a folder that contains the PidTagSourceKey property (section 2.1012) of the parent folder. Area: ExchangeNonTransmittableReserved Canonical name: PidTagParentSourceKey Alternate names: PR\_PARENT\_SOURCE\_KEY

### PENDING_STATE_FOR_SITE_MAILBOX_DOCUMENT {#PENDING-STATE-FOR-SITE-MAILBOX-DOCUMENT}
```
public static final PidLidPropertyDescriptor PENDING_STATE_FOR_SITE_MAILBOX_DOCUMENT
```


Specifies the synchronization state of the Document object that is in the Document Libraries folder of the site mailbox. Area: Site Mailbox Canonical name: PidLidPendingStateForSiteMailboxDocument Alternate names: dispidPendingStateforTMDocument

### PERCENT_COMPLETE {#PERCENT-COMPLETE}
```
public static final PidLidPropertyDescriptor PERCENT_COMPLETE
```


Indicates whether a time-flagged Message object is complete. Area: Tasks Canonical name: PidLidPercentComplete Alternate names: dispidPercentComplete

### PERSONAL_HOME_PAGE {#PERSONAL-HOME-PAGE}
```
public static final PidTagPropertyDescriptor PERSONAL_HOME_PAGE
```


Contains the URL of the mail user's personal home page. Area: MapiMailUser Canonical name: PidTagPersonalHomePage Alternate names: PR\_PERSONAL\_HOME\_PAGE, PR\_PERSONAL\_HOME\_PAGE\_A,

### PHISHING_STAMP {#PHISHING-STAMP}
```
public static final PidNamePropertyDescriptor PHISHING_STAMP
```


Indicates whether a message is likely to be phishing. Area: Secure Messaging Properties Canonical name: PidNamePhishingStamp Alternate names:

### PHYSICAL_DELIVERY_BUREAU_FAX_DELIVERY {#PHYSICAL-DELIVERY-BUREAU-FAX-DELIVERY}
```
public static final PidTagPropertyDescriptor PHYSICAL_DELIVERY_BUREAU_FAX_DELIVERY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PHYSICAL\_DELIVERY\_BUREAU\_FAX\_DELIVERY

### PHYSICAL_DELIVERY_MODE {#PHYSICAL-DELIVERY-MODE}
```
public static final PidTagPropertyDescriptor PHYSICAL_DELIVERY_MODE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PHYSICAL\_DELIVERY\_MODE

### PHYSICAL_DELIVERY_REPORT_REQUEST {#PHYSICAL-DELIVERY-REPORT-REQUEST}
```
public static final PidTagPropertyDescriptor PHYSICAL_DELIVERY_REPORT_REQUEST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PHYSICAL\_DELIVERY\_REPORT\_REQUEST

### PHYSICAL_FORWARDING_ADDRESS {#PHYSICAL-FORWARDING-ADDRESS}
```
public static final PidTagPropertyDescriptor PHYSICAL_FORWARDING_ADDRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PHYSICAL\_FORWARDING\_ADDRESS

### PHYSICAL_FORWARDING_ADDRESS_REQUESTED {#PHYSICAL-FORWARDING-ADDRESS-REQUESTED}
```
public static final PidTagPropertyDescriptor PHYSICAL_FORWARDING_ADDRESS_REQUESTED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PHYSICAL\_FORWARDING\_ADDRESS\_REQUESTED

### PHYSICAL_FORWARDING_PROHIBITED {#PHYSICAL-FORWARDING-PROHIBITED}
```
public static final PidTagPropertyDescriptor PHYSICAL_FORWARDING_PROHIBITED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PHYSICAL\_FORWARDING\_PROHIBITED

### PHYSICAL_RENDITION_ATTRIBUTES {#PHYSICAL-RENDITION-ATTRIBUTES}
```
public static final PidTagPropertyDescriptor PHYSICAL_RENDITION_ATTRIBUTES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PHYSICAL\_RENDITION\_ATTRIBUTES

### POLICY_TAG {#POLICY-TAG}
```
public static final PidTagPropertyDescriptor POLICY_TAG
```


Specifies the GUID of a retention tag. Area: Archive Canonical name: PidTagPolicyTag Alternate names: PR\_POLICY\_TAG, ptagPolicyTag

### POSTAL_ADDRESS {#POSTAL-ADDRESS}
```
public static final PidTagPropertyDescriptor POSTAL_ADDRESS
```


Contains the mail user's postal address. Area: MapiMailUser Canonical name: PidTagPostalAddress Alternate names: PR\_POSTAL\_ADDRESS, PR\_POSTAL\_ADDRESS\_A, PR\_POSTAL\_ADDRESS\_W,

### POSTAL_ADDRESS_ID {#POSTAL-ADDRESS-ID}
```
public static final PidLidPropertyDescriptor POSTAL_ADDRESS_ID
```


Specifies which physical address is the mailing address for this contact. Area: Contact Properties Canonical name: PidLidPostalAddressId Alternate names: dispidPostalAddressId

### POSTAL_CODE {#POSTAL-CODE}
```
public static final PidTagPropertyDescriptor POSTAL_CODE
```


Contains the postal code for the mail user's postal address. Area: MapiMailUser Canonical name: PidTagPostalCode Alternate names: PR\_POSTAL\_CODE, PR\_POSTAL\_CODE\_A, PR\_POSTAL\_CODE\_W, PR\_BUSINESS\_ADDRESS\_POSTAL\_CODE, PR\_BUSINESS\_ADDRESS\_POSTAL\_CODE\_A,

### POST_FOLDER_ENTRIES {#POST-FOLDER-ENTRIES}
```
public static final PidTagPropertyDescriptor POST_FOLDER_ENTRIES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_POST\_FOLDER\_ENTRIES

### POST_FOLDER_NAMES {#POST-FOLDER-NAMES}
```
public static final PidTagPropertyDescriptor POST_FOLDER_NAMES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_POST\_FOLDER\_NAMES

### POST_OFFICE_BOX {#POST-OFFICE-BOX}
```
public static final PidTagPropertyDescriptor POST_OFFICE_BOX
```


Contains the number or identifier of the mail user's post office box. Area: MapiMailUser Canonical name: PidTagPostOfficeBox Alternate names: PR\_POST\_OFFICE\_BOX, PR\_POST\_OFFICE\_BOX\_A, PR\_POST\_OFFICE\_BOX\_W, PR\_BUSINESS\_ADDRESS\_POST\_OFFICE\_BOX, PR\_BUSINESS\_ADDRESS\_POST\_OFFICE\_BOX\_A,

### POST_REPLY_DENIED {#POST-REPLY-DENIED}
```
public static final PidTagPropertyDescriptor POST_REPLY_DENIED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_POST\_REPLY\_DENIED

### POST_REPLY_FOLDER_ENTRIES {#POST-REPLY-FOLDER-ENTRIES}
```
public static final PidTagPropertyDescriptor POST_REPLY_FOLDER_ENTRIES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_POST\_REPLY\_FOLDER\_ENTRIES

### POST_REPLY_FOLDER_NAMES {#POST-REPLY-FOLDER-NAMES}
```
public static final PidTagPropertyDescriptor POST_REPLY_FOLDER_NAMES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_POST\_REPLY\_FOLDER\_NAMES

### POST_RSS_CHANNEL {#POST-RSS-CHANNEL}
```
public static final PidLidPropertyDescriptor POST_RSS_CHANNEL
```


Contains the contents of the title field from the XML of the Atom feed or RSS channel. Area: RSS Canonical name: PidLidPostRssChannel Alternate names: dispidPostRssChannel

### POST_RSS_CHANNEL_LINK {#POST-RSS-CHANNEL-LINK}
```
public static final PidLidPropertyDescriptor POST_RSS_CHANNEL_LINK
```


Contains the URL of the RSS or Atom feed from which the XML file came. Area: RSS Canonical name: PidLidPostRssChannelLink Alternate names: dispidPostRssChannelLink

### POST_RSS_ITEM_GUID {#POST-RSS-ITEM-GUID}
```
public static final PidLidPropertyDescriptor POST_RSS_ITEM_GUID
```


Contains a unique identifier for the RSS object. Area: RSS Canonical name: PidLidPostRssItemGuid Alternate names: dispidPostRssItemGuid

### POST_RSS_ITEM_HASH {#POST-RSS-ITEM-HASH}
```
public static final PidLidPropertyDescriptor POST_RSS_ITEM_HASH
```


Contains a hash of the feed XML computed by using an implementation-dependent algorithm. Area: RSS Canonical name: PidLidPostRssItemHash Alternate names: dispidPostRssItemHash

### POST_RSS_ITEM_LINK {#POST-RSS-ITEM-LINK}
```
public static final PidLidPropertyDescriptor POST_RSS_ITEM_LINK
```


Contains the URL of the link from an RSS or Atom item. Area: RSS Canonical name: PidLidPostRssItemLink Alternate names: dispidPostRssItemLink

### POST_RSS_ITEM_XML {#POST-RSS-ITEM-XML}
```
public static final PidLidPropertyDescriptor POST_RSS_ITEM_XML
```


Contains the item element and all of its sub-elements from an RSS feed, or the entry element and all of its sub-elements from an Atom feed. Area: RSS Canonical name: PidLidPostRssItemXml Alternate names: dispidPostRssItemXml

### POST_RSS_SUBSCRIPTION {#POST-RSS-SUBSCRIPTION}
```
public static final PidLidPropertyDescriptor POST_RSS_SUBSCRIPTION
```


Contains the user's preferred name for the RSS or Atom subscription. Area: RSS Canonical name: PidLidPostRssSubscription Alternate names: dispidPostRssSubscription

### PREDECESSOR_CHANGE_LIST {#PREDECESSOR-CHANGE-LIST}
```
public static final PidTagPropertyDescriptor PREDECESSOR_CHANGE_LIST
```


Contains a value that contains a serialized representation of a PredecessorChangeList structure. Area: Sync Canonical name: PidTagPredecessorChangeList Alternate names: PR\_PREDECESSOR\_CHANGE\_LIST

### PREPROCESS {#PREPROCESS}
```
public static final PidTagPropertyDescriptor PREPROCESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PREPROCESS

### PRESENTATION_FORMAT {#PRESENTATION-FORMAT}
```
public static final PidNamePropertyDescriptor PRESENTATION_FORMAT
```


Specifies the presentation format of the file attached to the Document object. Area: Common Canonical name: PidNamePresentationFormat Alternate names: urn:schemas-microsoft-com:office:office\#PresentationFormat

### PREVENT_MSG_CREATE {#PREVENT-MSG-CREATE}
```
public static final PidTagPropertyDescriptor PREVENT_MSG_CREATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PREVENT\_MSG\_CREATE

### PREVIEW {#PREVIEW}
```
public static final PidTagPropertyDescriptor PREVIEW
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PREVIEW

### PREVIEW_UNREAD {#PREVIEW-UNREAD}
```
public static final PidTagPropertyDescriptor PREVIEW_UNREAD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PREVIEW\_UNREAD

### PRIMARY_CAPABILITY {#PRIMARY-CAPABILITY}
```
public static final PidTagPropertyDescriptor PRIMARY_CAPABILITY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PRIMARY\_CAPABILITY

### PRIMARY_FAX_NUMBER {#PRIMARY-FAX-NUMBER}
```
public static final PidTagPropertyDescriptor PRIMARY_FAX_NUMBER
```


Contains the telephone number of the mail user's primary fax machine. Area: MapiMailUser Canonical name: PidTagPrimaryFaxNumber Alternate names: PR\_PRIMARY\_FAX\_NUMBER, PR\_PRIMARY\_FAX\_NUMBER\_A,

### PRIMARY_SEND_ACCOUNT {#PRIMARY-SEND-ACCOUNT}
```
public static final PidTagPropertyDescriptor PRIMARY_SEND_ACCOUNT
```


Specifies the first server that a client is to use to send the email with. Area: MapiNonTransmittable Canonical name: PidTagPrimarySendAccount Alternate names: PR\_PRIMARY\_SEND\_ACCT

### PRIMARY_TELEPHONE_NUMBER {#PRIMARY-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor PRIMARY_TELEPHONE_NUMBER
```


Contains the mail user's primary telephone number. Area: MapiMailUser Canonical name: PidTagPrimaryTelephoneNumber Alternate names: PR\_PRIMARY\_TELEPHONE\_NUMBER, PR\_PRIMARY\_TELEPHONE\_NUMBER\_A, PR\_PRIMARY\_TELEPHONE\_NUMBER\_W

### PRIORITY {#PRIORITY}
```
public static final PidTagPropertyDescriptor PRIORITY
```


Indicates the client's request for the priority with which the message is to be sent by the messaging system. Area: Email Canonical name: PidTagPriority Alternate names: PR\_PRIORITY, ptagPriority, urn:schemas:httpmail:priority,

### PRIVATE {#PRIVATE}
```
public static final PidLidPropertyDescriptor PRIVATE
```


Indicates whether the end user wishes for this Message object to be hidden from other users who have access to the Message object. Area: General Message Properties Canonical name: PidLidPrivate Alternate names: dispidPrivate

### PROCESSED {#PROCESSED}
```
public static final PidTagPropertyDescriptor PROCESSED
```


Indicates whether a client has already processed a received task communication. Area: Calendar Canonical name: PidTagProcessed Alternate names: PR\_PROCESSED

### PROFESSION {#PROFESSION}
```
public static final PidTagPropertyDescriptor PROFESSION
```


Contains the name of the mail user's line of business. Area: MapiMailUser Canonical name: PidTagProfession Alternate names: PR\_PROFESSION, PR\_PROFESSION\_A, PR\_PROFESSION\_W,

### PROFILE_AB_FILES_PATH {#PROFILE-AB-FILES-PATH}
```
public static final PidTagPropertyDescriptor PROFILE_AB_FILES_PATH
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_AB\_FILES\_PATH

### PROFILE_ADDR_INFO {#PROFILE-ADDR-INFO}
```
public static final PidTagPropertyDescriptor PROFILE_ADDR_INFO
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_ADDR\_INFO

### PROFILE_ALLPUB_COMMENT {#PROFILE-ALLPUB-COMMENT}
```
public static final PidTagPropertyDescriptor PROFILE_ALLPUB_COMMENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_ALLPUB\_COMMENT

### PROFILE_ALLPUB_DISPLAY_NAME {#PROFILE-ALLPUB-DISPLAY-NAME}
```
public static final PidTagPropertyDescriptor PROFILE_ALLPUB_DISPLAY_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_ALLPUB\_DISPLAY\_NAME

### PROFILE_BINDING_ORDER {#PROFILE-BINDING-ORDER}
```
public static final PidTagPropertyDescriptor PROFILE_BINDING_ORDER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_BINDING\_ORDER

### PROFILE_CONFIG_FLAGS {#PROFILE-CONFIG-FLAGS}
```
public static final PidTagPropertyDescriptor PROFILE_CONFIG_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_CONFIG\_FLAGS

### PROFILE_CONNECT_FLAGS {#PROFILE-CONNECT-FLAGS}
```
public static final PidTagPropertyDescriptor PROFILE_CONNECT_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_CONNECT\_FLAGS

### PROFILE_FAVFLD_COMMENT {#PROFILE-FAVFLD-COMMENT}
```
public static final PidTagPropertyDescriptor PROFILE_FAVFLD_COMMENT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_FAVFLD\_COMMENT

### PROFILE_FAVFLD_DISPLAY_NAME {#PROFILE-FAVFLD-DISPLAY-NAME}
```
public static final PidTagPropertyDescriptor PROFILE_FAVFLD_DISPLAY_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_FAVFLD\_DISPLAY\_NAME

### PROFILE_HOME_SERVER {#PROFILE-HOME-SERVER}
```
public static final PidTagPropertyDescriptor PROFILE_HOME_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_HOME\_SERVER

### PROFILE_HOME_SERVER_ADDRS {#PROFILE-HOME-SERVER-ADDRS}
```
public static final PidTagPropertyDescriptor PROFILE_HOME_SERVER_ADDRS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_HOME\_SERVER\_ADDRS

### PROFILE_HOME_SERVER_DN {#PROFILE-HOME-SERVER-DN}
```
public static final PidTagPropertyDescriptor PROFILE_HOME_SERVER_DN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_HOME\_SERVER\_DN

### PROFILE_MAILBOX {#PROFILE-MAILBOX}
```
public static final PidTagPropertyDescriptor PROFILE_MAILBOX
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_MAILBOX

### PROFILE_MAX_RESTRICT {#PROFILE-MAX-RESTRICT}
```
public static final PidTagPropertyDescriptor PROFILE_MAX_RESTRICT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_MAX\_RESTRICT

### PROFILE_MOAB {#PROFILE-MOAB}
```
public static final PidTagPropertyDescriptor PROFILE_MOAB
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_MOAB

### PROFILE_MOAB_GUID {#PROFILE-MOAB-GUID}
```
public static final PidTagPropertyDescriptor PROFILE_MOAB_GUID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_MOAB\_GUID

### PROFILE_MOAB_SEQ {#PROFILE-MOAB-SEQ}
```
public static final PidTagPropertyDescriptor PROFILE_MOAB_SEQ
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_MOAB\_SEQ

### PROFILE_NAME {#PROFILE-NAME}
```
public static final PidTagPropertyDescriptor PROFILE_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_NAME

### PROFILE_OFFLINE_INFO {#PROFILE-OFFLINE-INFO}
```
public static final PidTagPropertyDescriptor PROFILE_OFFLINE_INFO
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_OFFLINE\_INFO

### PROFILE_OFFLINE_STORE_PATH {#PROFILE-OFFLINE-STORE-PATH}
```
public static final PidTagPropertyDescriptor PROFILE_OFFLINE_STORE_PATH
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_OFFLINE\_STORE\_PATH

### PROFILE_OPEN_FLAGS {#PROFILE-OPEN-FLAGS}
```
public static final PidTagPropertyDescriptor PROFILE_OPEN_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_OPEN\_FLAGS

### PROFILE_OPTIONS_DATA {#PROFILE-OPTIONS-DATA}
```
public static final PidTagPropertyDescriptor PROFILE_OPTIONS_DATA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_OPTIONS\_DATA

### PROFILE_SECURE_MAILBOX {#PROFILE-SECURE-MAILBOX}
```
public static final PidTagPropertyDescriptor PROFILE_SECURE_MAILBOX
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_SECURE\_MAILBOX

### PROFILE_SERVER {#PROFILE-SERVER}
```
public static final PidTagPropertyDescriptor PROFILE_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_SERVER

### PROFILE_SERVER_DN {#PROFILE-SERVER-DN}
```
public static final PidTagPropertyDescriptor PROFILE_SERVER_DN
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_SERVER\_DN

### PROFILE_TRANSPORT_FLAGS {#PROFILE-TRANSPORT-FLAGS}
```
public static final PidTagPropertyDescriptor PROFILE_TRANSPORT_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_TRANSPORT\_FLAGS

### PROFILE_TYPE {#PROFILE-TYPE}
```
public static final PidTagPropertyDescriptor PROFILE_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_TYPE

### PROFILE_UI_STATE {#PROFILE-UI-STATE}
```
public static final PidTagPropertyDescriptor PROFILE_UI_STATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_UI\_STATE

### PROFILE_UNRESOLVED_NAME {#PROFILE-UNRESOLVED-NAME}
```
public static final PidTagPropertyDescriptor PROFILE_UNRESOLVED_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_UNRESOLVED\_NAME

### PROFILE_UNRESOLVED_SERVER {#PROFILE-UNRESOLVED-SERVER}
```
public static final PidTagPropertyDescriptor PROFILE_UNRESOLVED_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_UNRESOLVED\_SERVER

### PROFILE_USER {#PROFILE-USER}
```
public static final PidTagPropertyDescriptor PROFILE_USER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_USER

### PROFILE_VERSION {#PROFILE-VERSION}
```
public static final PidTagPropertyDescriptor PROFILE_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROFILE\_VERSION

### PROHIBIT_RECEIVE_QUOTA {#PROHIBIT-RECEIVE-QUOTA}
```
public static final PidTagPropertyDescriptor PROHIBIT_RECEIVE_QUOTA
```


Maximum size, in kilobytes, that a user is allowed to accumulate in their mailbox before no further email will be delivered to their mailbox. Area: Exchange Administrative Canonical name: PidTagProhibitReceiveQuota Alternate names: PR\_PROHIBIT\_RECEIVE\_QUOTA, ptagProhibitReceiveQuota

### PROHIBIT_SEND_QUOTA {#PROHIBIT-SEND-QUOTA}
```
public static final PidTagPropertyDescriptor PROHIBIT_SEND_QUOTA
```


Maximum size, in kilobytes, that a user is allowed to accumulate in their mailbox before the user can no longer send any more email. Area: ExchangeAdministrative Canonical name: PidTagProhibitSendQuota Alternate names: PR\_PROHIBIT\_SEND\_QUOTA, ptagProhibitSendQuota

### PROMPT_SEND_UPDATE {#PROMPT-SEND-UPDATE}
```
public static final PidLidPropertyDescriptor PROMPT_SEND_UPDATE
```


Indicates that the Meeting Response object was out-of-date when it was received. Area: Meeting Response Canonical name: PidLidPromptSendUpdate Alternate names: dispidPromptSendUpdate

### PROOF_OF_DELIVERY {#PROOF-OF-DELIVERY}
```
public static final PidTagPropertyDescriptor PROOF_OF_DELIVERY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROOF\_OF\_DELIVERY

### PROOF_OF_DELIVERY_REQUESTED {#PROOF-OF-DELIVERY-REQUESTED}
```
public static final PidTagPropertyDescriptor PROOF_OF_DELIVERY_REQUESTED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROOF\_OF\_DELIVERY\_REQUESTED

### PROOF_OF_SUBMISSION {#PROOF-OF-SUBMISSION}
```
public static final PidTagPropertyDescriptor PROOF_OF_SUBMISSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROOF\_OF\_SUBMISSION

### PROOF_OF_SUBMISSION_REQUESTED {#PROOF-OF-SUBMISSION-REQUESTED}
```
public static final PidTagPropertyDescriptor PROOF_OF_SUBMISSION_REQUESTED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROOF\_OF\_SUBMISSION\_REQUESTED

### PROVIDER_DISPLAY {#PROVIDER-DISPLAY}
```
public static final PidTagPropertyDescriptor PROVIDER_DISPLAY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROVIDER\_DISPLAY

### PROVIDER_DLL_NAME {#PROVIDER-DLL-NAME}
```
public static final PidTagPropertyDescriptor PROVIDER_DLL_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROVIDER\_DLL\_NAME

### PROVIDER_ORDINAL {#PROVIDER-ORDINAL}
```
public static final PidTagPropertyDescriptor PROVIDER_ORDINAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROVIDER\_ORDINAL

### PROVIDER_SUBMIT_TIME {#PROVIDER-SUBMIT-TIME}
```
public static final PidTagPropertyDescriptor PROVIDER_SUBMIT_TIME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROVIDER\_SUBMIT\_TIME

### PROVIDER_UID {#PROVIDER-UID}
```
public static final PidTagPropertyDescriptor PROVIDER_UID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PROVIDER\_UID

### PST_ENCRYPTION {#PST-ENCRYPTION}
```
public static final PidTagPropertyDescriptor PST_ENCRYPTION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PST\_ENCRYPTION

### PST_PATH {#PST-PATH}
```
public static final PidTagPropertyDescriptor PST_PATH
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PST\_PATH

### PST_PW_SZ_OLD {#PST-PW-SZ-OLD}
```
public static final PidTagPropertyDescriptor PST_PW_SZ_OLD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PST\_PW\_SZ\_OLD

### PST_REMEMBER_PW {#PST-REMEMBER-PW}
```
public static final PidTagPropertyDescriptor PST_REMEMBER_PW
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PST\_REMEMBER\_PW

### PUBLIC_FOLDER_ENTRYID {#PUBLIC-FOLDER-ENTRYID}
```
public static final PidTagPropertyDescriptor PUBLIC_FOLDER_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PUBLIC\_FOLDER\_ENTRYID

### PUBLISH_IN_ADDRESS_BOOK {#PUBLISH-IN-ADDRESS-BOOK}
```
public static final PidTagPropertyDescriptor PUBLISH_IN_ADDRESS_BOOK
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_PUBLISH\_IN\_ADDRESS\_BOOK

### PURPORTED_SENDER_DOMAIN {#PURPORTED-SENDER-DOMAIN}
```
public static final PidTagPropertyDescriptor PURPORTED_SENDER_DOMAIN
```


Contains the domain responsible for transmitting the current message. Area: TransportEnvelope Canonical name: PidTagPurportedSenderDomain Alternate names: PR\_PURPORTED\_SENDER\_DOMAIN

### QUARANTINE_ORIGINAL_SENDER {#QUARANTINE-ORIGINAL-SENDER}
```
public static final PidNamePropertyDescriptor QUARANTINE_ORIGINAL_SENDER
```


Specifies the original sender of a message. Area: Common Canonical name: PidNameQuarantineOriginalSender Alternate names:

### RADIO_TELEPHONE_NUMBER {#RADIO-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor RADIO_TELEPHONE_NUMBER
```


Contains the mail user's radio telephone number. Area: MapiMailUser Canonical name: PidTagRadioTelephoneNumber Alternate names: PR\_RADIO\_TELEPHONE\_NUMBER, PR\_RADIO\_TELEPHONE\_NUMBER\_A, PR\_RADIO\_TELEPHONE\_NUMBER\_W

### READ {#READ}
```
public static final PidTagPropertyDescriptor READ
```


Indicates whether a message has been read. Area: MapiNonTransmittable Property set Canonical name: PidTagRead Alternate names: PR\_READ, ptagRead, urn:schemas:httpmail:read

### READ_RECEIPT_ADDRESS_TYPE {#READ-RECEIPT-ADDRESS-TYPE}
```
public static final PidTagPropertyDescriptor READ_RECEIPT_ADDRESS_TYPE
```


Contains the address type of the end user to whom a read receipt is directed. Area: Transport Envelope Canonical name: PidTagReadReceiptAddressType Alternate names: ptagReadReceiptAddrType, ReadReceiptAddrType

### READ_RECEIPT_EMAIL_ADDRESS {#READ-RECEIPT-EMAIL-ADDRESS}
```
public static final PidTagPropertyDescriptor READ_RECEIPT_EMAIL_ADDRESS
```


Contains the email address of the end user to whom a read receipt is directed. Area: Transport Envelope Canonical name: PidTagReadReceiptEmailAddress Alternate names: ptagReadReceiptEmailAddr, ReadReceiptEmailAddress

### READ_RECEIPT_ENTRY_ID {#READ-RECEIPT-ENTRY-ID}
```
public static final PidTagPropertyDescriptor READ_RECEIPT_ENTRY_ID
```


Contains an address book EntryID. Area: MapiEnvelope Canonical name: PidTagReadReceiptEntryId Alternate names: PR\_READ\_RECEIPT\_ENTRYID, ptagReadReceiptEntryId

### READ_RECEIPT_NAME {#READ-RECEIPT-NAME}
```
public static final PidTagPropertyDescriptor READ_RECEIPT_NAME
```


Contains the display name for the end user to whom a read receipt is directed. Area: Transport Envelope Canonical name: PidTagReadReceiptName Alternate names: ptagReadReceiptDisplayName, ReadReceiptDisplayName

### READ_RECEIPT_REQUESTED {#READ-RECEIPT-REQUESTED}
```
public static final PidTagPropertyDescriptor READ_RECEIPT_REQUESTED
```


Specifies whether the email sender requests a read receipt from all recipients when this email message is read or opened. Area: Email Canonical name: PidTagReadReceiptRequested Alternate names: PR\_READ\_RECEIPT\_REQUESTED, ptagReadReceiptRequested,

### READ_RECEIPT_SEARCH_KEY {#READ-RECEIPT-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor READ_RECEIPT_SEARCH_KEY
```


Contains an address book search key. Area: MapiEnvelope Canonical name: PidTagReadReceiptSearchKey Alternate names: PR\_READ\_RECEIPT\_SEARCH\_KEY, ptagReadReceiptSearchKey

### READ_RECEIPT_SMTP_ADDRESS {#READ-RECEIPT-SMTP-ADDRESS}
```
public static final PidTagPropertyDescriptor READ_RECEIPT_SMTP_ADDRESS
```


Contains the SMTP email address of the user to whom a read receipt is directed. Area: Mail Canonical name: PidTagReadReceiptSmtpAddress Alternate names: ptagRecipientReadReceiptSmtpAddress

### RECEIPT_TIME {#RECEIPT-TIME}
```
public static final PidTagPropertyDescriptor RECEIPT_TIME
```


Contains the sent time for a message disposition notification, as specified in [RFC3798]. Area: Email Canonical name: PidTagReceiptTime Alternate names: PR\_RECEIPT\_TIME, ptagReceiptTime

### RECEIVED_BY_ADDRESS_TYPE {#RECEIVED-BY-ADDRESS-TYPE}
```
public static final PidTagPropertyDescriptor RECEIVED_BY_ADDRESS_TYPE
```


Contains the email message receiver's email address type. Area: MapiEnvelope Canonical name: PidTagReceivedByAddressType Alternate names: PR\_RECEIVED\_BY\_ADDRTYPE, PR\_RECEIVED\_BY\_ADDRTYPE\_A, ptagReceivedByAddrType, PR\_RECEIVED\_BY\_ADDRTYPE\_W

### RECEIVED_BY_EMAIL_ADDRESS {#RECEIVED-BY-EMAIL-ADDRESS}
```
public static final PidTagPropertyDescriptor RECEIVED_BY_EMAIL_ADDRESS
```


Contains the email message receiver's email address. Area: Address Properties Canonical name: PidTagReceivedByEmailAddress Alternate names: PR\_RECEIVED\_BY\_EMAIL\_ADDRESS, PR\_RECEIVED\_BY\_EMAIL\_ADDRESS\_A, PR\_RECEIVED\_BY\_EMAIL\_ADDRESS\_W

### RECEIVED_BY_ENTRY_ID {#RECEIVED-BY-ENTRY-ID}
```
public static final PidTagPropertyDescriptor RECEIVED_BY_ENTRY_ID
```


Contains the address book EntryID of the mailbox receiving the Email object. Area: Address Properties Canonical name: PidTagReceivedByEntryId Alternate names: PR\_RECEIVED\_BY\_ENTRYID

### RECEIVED_BY_NAME {#RECEIVED-BY-NAME}
```
public static final PidTagPropertyDescriptor RECEIVED_BY_NAME
```


Contains the email message receiver's display name. Area: Address Properties Canonical name: PidTagReceivedByName Alternate names: PR\_RECEIVED\_BY\_NAME, PR\_RECEIVED\_BY\_NAME\_A, PR\_RECEIVED\_BY\_NAME\_W

### RECEIVED_BY_SEARCH_KEY {#RECEIVED-BY-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor RECEIVED_BY_SEARCH_KEY
```


Identifies an address book search key that contains a binary-comparable key that is used to identify correlated objects for a search. Area: Address Properties Canonical name: PidTagReceivedBySearchKey Alternate names: PR\_RECEIVED\_BY\_SEARCH\_KEY

### RECEIVED_BY_SMTP_ADDRESS {#RECEIVED-BY-SMTP-ADDRESS}
```
public static final PidTagPropertyDescriptor RECEIVED_BY_SMTP_ADDRESS
```


Contains the email message receiver's SMTP email address. Area: Mail Canonical name: PidTagReceivedBySmtpAddress Alternate names: ptagRecipientRcvdBySmtpAddress

### RECEIVED_REPRESENTING_ADDRESS_TYPE {#RECEIVED-REPRESENTING-ADDRESS-TYPE}
```
public static final PidTagPropertyDescriptor RECEIVED_REPRESENTING_ADDRESS_TYPE
```


Contains the email address type for the end user represented by the receiving mailbox owner. Area: Address Properties Canonical name: PidTagReceivedRepresentingAddressType Alternate names: PR\_RCVD\_REPRESENTING\_ADDRTYPE, PR\_RCVD\_REPRESENTING\_ADDRTYPE\_A, ptagRcvdRepresentingAddrType, PR\_RCVD\_REPRESENTING\_ADDRTYPE\_W

### RECEIVED_REPRESENTING_EMAIL_ADDRESS {#RECEIVED-REPRESENTING-EMAIL-ADDRESS}
```
public static final PidTagPropertyDescriptor RECEIVED_REPRESENTING_EMAIL_ADDRESS
```


Contains the email address for the end user represented by the receiving mailbox owner. Area: Address Properties Canonical name: PidTagReceivedRepresentingEmailAddress Alternate names: PR\_RCVD\_REPRESENTING\_EMAIL\_ADDRESS, PR\_RCVD\_REPRESENTING\_EMAIL\_ADDRESS\_A, PR\_RCVD\_REPRESENTING\_EMAIL\_ADDRESS\_W

### RECEIVED_REPRESENTING_ENTRY_ID {#RECEIVED-REPRESENTING-ENTRY-ID}
```
public static final PidTagPropertyDescriptor RECEIVED_REPRESENTING_ENTRY_ID
```


Contains an address book EntryID that identifies the end user represented by the receiving mailbox owner. Area: Address Properties Canonical name: PidTagReceivedRepresentingEntryId Alternate names: PR\_RCVD\_REPRESENTING\_ENTRYID, ptagRcvdRepresentingEntryId

### RECEIVED_REPRESENTING_NAME {#RECEIVED-REPRESENTING-NAME}
```
public static final PidTagPropertyDescriptor RECEIVED_REPRESENTING_NAME
```


Contains the display name for the end user represented by the receiving mailbox owner. Area: Address Properties Canonical name: PidTagReceivedRepresentingName Alternate names: PR\_RCVD\_REPRESENTING\_NAME, PR\_RCVD\_REPRESENTING\_NAME\_A, ptagRcvdRepresentingName, PR\_RCVD\_REPRESENTING\_NAME\_W

### RECEIVED_REPRESENTING_SEARCH_KEY {#RECEIVED-REPRESENTING-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor RECEIVED_REPRESENTING_SEARCH_KEY
```


Identifies an address book search key that contains a binary-comparable key of the end user represented by the receiving mailbox owner. Area: Address Properties Canonical name: PidTagReceivedRepresentingSearchKey Alternate names: PR\_RCVD\_REPRESENTING\_SEARCH\_KEY, ptagRcvdRepresentingSearchKey

### RECEIVED_REPRESENTING_SMTP_ADDRESS {#RECEIVED-REPRESENTING-SMTP-ADDRESS}
```
public static final PidTagPropertyDescriptor RECEIVED_REPRESENTING_SMTP_ADDRESS
```


Contains the SMTP email address of the user represented by the receiving mailbox owner. Area: Mail Canonical name: PidTagReceivedRepresentingSmtpAddress Alternate names: ptagRecipientRcvdRepresentingSmtpAddress

### RECEIVE_FOLDER_SETTINGS {#RECEIVE-FOLDER-SETTINGS}
```
public static final PidTagPropertyDescriptor RECEIVE_FOLDER_SETTINGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RECEIVE\_FOLDER\_SETTINGS

### RECIPIENT_CERTIFICATE {#RECIPIENT-CERTIFICATE}
```
public static final PidTagPropertyDescriptor RECIPIENT_CERTIFICATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RECIPIENT\_CERTIFICATE

### RECIPIENT_DISPLAY_NAME {#RECIPIENT-DISPLAY-NAME}
```
public static final PidTagPropertyDescriptor RECIPIENT_DISPLAY_NAME
```


Specifies the display name of the recipient. Area: TransportRecipient Canonical name: PidTagRecipientDisplayName Alternate names: PR\_RECIPIENT\_DISPLAY\_NAME, PR\_RECIPIENT\_DISPLAY\_NAME\_W

### RECIPIENT_ENTRY_ID {#RECIPIENT-ENTRY-ID}
```
public static final PidTagPropertyDescriptor RECIPIENT_ENTRY_ID
```


Identifies an Address Book object that specifies the recipient. Area: ID Properties Canonical name: PidTagRecipientEntryId Alternate names: PR\_RECIPIENT\_ENTRYID, ptagRecipientEntryId

### RECIPIENT_FLAGS {#RECIPIENT-FLAGS}
```
public static final PidTagPropertyDescriptor RECIPIENT_FLAGS
```


Specifies a bit field that describes the recipient status. Area: TransportRecipient Canonical name: PidTagRecipientFlags Alternate names: PR\_RECIPIENT\_FLAGS

### RECIPIENT_NUMBER {#RECIPIENT-NUMBER}
```
public static final PidTagPropertyDescriptor RECIPIENT_NUMBER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RECIPIENT\_NUMBER

### RECIPIENT_NUMBER_FOR_ADVICE {#RECIPIENT-NUMBER-FOR-ADVICE}
```
public static final PidTagPropertyDescriptor RECIPIENT_NUMBER_FOR_ADVICE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RECIPIENT\_NUMBER\_FOR\_ADVICE

### RECIPIENT_ON_ASSOC_MSG_COUNT {#RECIPIENT-ON-ASSOC-MSG-COUNT}
```
public static final PidTagPropertyDescriptor RECIPIENT_ON_ASSOC_MSG_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RECIPIENT\_ON\_ASSOC\_MSG\_COUNT

### RECIPIENT_ON_NORMAL_MSG_COUNT {#RECIPIENT-ON-NORMAL-MSG-COUNT}
```
public static final PidTagPropertyDescriptor RECIPIENT_ON_NORMAL_MSG_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RECIPIENT\_ON\_NORMAL\_MSG\_COUNT

### RECIPIENT_ORDER {#RECIPIENT-ORDER}
```
public static final PidTagPropertyDescriptor RECIPIENT_ORDER
```


Specifies the location of the current recipient in the recipient table. Area: TransportRecipient Canonical name: PidTagRecipientOrder Alternate names: PR\_RECIPIENT\_ORDER, ptagRecipientOrder

### RECIPIENT_PROPOSED {#RECIPIENT-PROPOSED}
```
public static final PidTagPropertyDescriptor RECIPIENT_PROPOSED
```


Indicates that the attendee proposed a new date and/or time. Area: TransportRecipient Canonical name: PidTagRecipientProposed Alternate names: PR\_RECIPIENT\_PROPOSED, ptagRecipientProposed

### RECIPIENT_PROPOSED_END_TIME {#RECIPIENT-PROPOSED-END-TIME}
```
public static final PidTagPropertyDescriptor RECIPIENT_PROPOSED_END_TIME
```


Indicates the meeting end time requested by the attendee in a counter proposal. Area: TransportRecipient Canonical name: PidTagRecipientProposedEndTime Alternate names: PR\_RECIPIENT\_PROPOSEDENDTIME, ptagRecipientProposedEndTime

### RECIPIENT_PROPOSED_START_TIME {#RECIPIENT-PROPOSED-START-TIME}
```
public static final PidTagPropertyDescriptor RECIPIENT_PROPOSED_START_TIME
```


Indicates the meeting start time requested by the attendee in a counter proposal. Area: TransportRecipient Canonical name: PidTagRecipientProposedStartTime Alternate names: PR\_RECIPIENT\_PROPOSEDSTARTTIME, ptagRecipientProposedStartTime

### RECIPIENT_REASSIGNMENT_PROHIBITED {#RECIPIENT-REASSIGNMENT-PROHIBITED}
```
public static final PidTagPropertyDescriptor RECIPIENT_REASSIGNMENT_PROHIBITED
```


Specifies whether adding additional or different recipients is prohibited for the email message when forwarding the email message. Area: MapiEnvelope Canonical name: PidTagRecipientReassignmentProhibited Alternate names: PR\_RECIPIENT\_REASSIGNMENT\_PROHIBITED, ptagRecipientReassignmentProhibited

### RECIPIENT_STATUS {#RECIPIENT-STATUS}
```
public static final PidTagPropertyDescriptor RECIPIENT_STATUS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RECIPIENT\_STATUS

### RECIPIENT_TRACK_STATUS {#RECIPIENT-TRACK-STATUS}
```
public static final PidTagPropertyDescriptor RECIPIENT_TRACK_STATUS
```


Indicates the response status that is returned by the attendee. Area: TransportRecipient Canonical name: PidTagRecipientTrackStatus Alternate names: PR\_RECIPIENT\_TRACKSTATUS, ptagRecipientTrackStatus

### RECIPIENT_TRACK_STATUS_TIME {#RECIPIENT-TRACK-STATUS-TIME}
```
public static final PidTagPropertyDescriptor RECIPIENT_TRACK_STATUS_TIME
```


Indicates the date and time at which the attendee responded. Area: TransportRecipient Canonical name: PidTagRecipientTrackStatusTime Alternate names: PR\_RECIPIENT\_TRACKSTATUS\_TIME, ptagRecipientTrackStatusTime

### RECIPIENT_TYPE {#RECIPIENT-TYPE}
```
public static final PidTagPropertyDescriptor RECIPIENT_TYPE
```


Represents the recipient type of a recipient on the message. Area: MapiRecipient Canonical name: PidTagRecipientType Alternate names: PR\_RECIPIENT\_TYPE, ptagRecipientType

### RECORD_KEY {#RECORD-KEY}
```
public static final PidTagPropertyDescriptor RECORD_KEY
```


Contains a unique binary-comparable identifier for a specific object. Area: ID Properties Canonical name: PidTagRecordKey Alternate names: PR\_RECORD\_KEY, ptagRecordKey

### RECURRENCE_DURATION {#RECURRENCE-DURATION}
```
public static final PidLidPropertyDescriptor RECURRENCE_DURATION
```


Identifies the length, in minutes, of the appointment or meeting. Area: Calendar Canonical name: PidLidRecurrenceDuration Alternate names:

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final PidLidPropertyDescriptor RECURRENCE_PATTERN
```


Specifies a description of the recurrence pattern of the Calendar object. Area: Calendar Canonical name: PidLidRecurrencePattern Alternate names: dispidRecurPattern

### RECURRENCE_TYPE {#RECURRENCE-TYPE}
```
public static final PidLidPropertyDescriptor RECURRENCE_TYPE
```


Specifies the recurrence type of the recurring series. Area: Calendar Canonical name: PidLidRecurrenceType Alternate names: dispidRecurType

### RECURRING {#RECURRING}
```
public static final PidLidPropertyDescriptor RECURRING
```


Specifies whether the object represents a recurring series. Area: Calendar Canonical name: PidLidRecurring Alternate names: dispidRecurring

### REDIRECTION_HISTORY {#REDIRECTION-HISTORY}
```
public static final PidTagPropertyDescriptor REDIRECTION_HISTORY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REDIRECTION\_HISTORY

### REFERENCE_ENTRY_ID {#REFERENCE-ENTRY-ID}
```
public static final PidLidPropertyDescriptor REFERENCE_ENTRY_ID
```


Specifies the value of the EntryID of the Contact object unless the Contact object is a copy of an earlier original. Area: Contact Properties Canonical name: PidLidReferenceEntryId Alternate names: dispidReferenceEID

### REFERRED_BY_NAME {#REFERRED-BY-NAME}
```
public static final PidTagPropertyDescriptor REFERRED_BY_NAME
```


Contains the name of the mail user's referral. Area: MapiMailUser Canonical name: PidTagReferredByName Alternate names: PR\_REFERRED\_BY\_NAME, PR\_REFERRED\_BY\_NAME\_A, PR\_REFERRED\_BY\_NAME\_W

### REGISTERED_MAIL_TYPE {#REGISTERED-MAIL-TYPE}
```
public static final PidTagPropertyDescriptor REGISTERED_MAIL_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REGISTERED\_MAIL\_TYPE

### RELATED_IPMS {#RELATED-IPMS}
```
public static final PidTagPropertyDescriptor RELATED_IPMS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RELATED\_IPMS

### REMINDERS_ONLINE_ENTRY_ID {#REMINDERS-ONLINE-ENTRY-ID}
```
public static final PidTagPropertyDescriptor REMINDERS_ONLINE_ENTRY_ID
```


Contains an EntryID for the Reminders folder. Area: MapiContainer Canonical name: PidTagRemindersOnlineEntryId Alternate names: PR\_REM\_ONLINE\_ENTRYID, ptagRemOnlineEntryId

### REMINDER_DELTA {#REMINDER-DELTA}
```
public static final PidLidPropertyDescriptor REMINDER_DELTA
```


Specifies the interval, in minutes, between the time at which the reminder first becomes overdue and the start time of the Calendar object. Area: Reminders Canonical name: PidLidReminderDelta Alternate names: dispidReminderDelta, http://schemas.microsoft.com/mapi/reminderdelta

### REMINDER_FILE_PARAMETER {#REMINDER-FILE-PARAMETER}
```
public static final PidLidPropertyDescriptor REMINDER_FILE_PARAMETER
```


Specifies the filename of the sound that a client is to play when the reminder for that object becomes overdue. Area: Reminders Canonical name: PidLidReminderFileParameter Alternate names: dispidReminderFileParam

### REMINDER_OVERRIDE {#REMINDER-OVERRIDE}
```
public static final PidLidPropertyDescriptor REMINDER_OVERRIDE
```


Specifies whether the client is to respect the current values of the property (section 2.219), or use the default values for those properties. Area: Reminders Canonical name: PidLidReminderOverride Alternate names: dispidReminderOverride

### REMINDER_PLAY_SOUND {#REMINDER-PLAY-SOUND}
```
public static final PidLidPropertyDescriptor REMINDER_PLAY_SOUND
```


Specifies whether the client is to play a sound when the reminder becomes overdue. Area: Reminders Canonical name: PidLidReminderPlaySound Alternate names: dispidReminderPlaySound

### REMINDER_SET {#REMINDER-SET}
```
public static final PidLidPropertyDescriptor REMINDER_SET
```


Specifies whether a reminder is set on the object. Area: Reminders Canonical name: PidLidReminderSet Alternate names: dispidReminderSet

### REMINDER_SIGNAL_TIME {#REMINDER-SIGNAL-TIME}
```
public static final PidLidPropertyDescriptor REMINDER_SIGNAL_TIME
```


Specifies the point in time when a reminder transitions from pending to overdue. Area: Reminders Canonical name: PidLidReminderSignalTime Alternate names: dispidReminderNextTime

### REMINDER_TIME {#REMINDER-TIME}
```
public static final PidLidPropertyDescriptor REMINDER_TIME
```


Specifies the initial signal time for objects that are not Calendar objects. Area: Reminders Canonical name: PidLidReminderTime Alternate names: dispidReminderTime

### REMINDER_TIME_DATE {#REMINDER-TIME-DATE}
```
public static final PidLidPropertyDescriptor REMINDER_TIME_DATE
```


Indicates the time and date of the reminder for the appointment or meeting. Area: Reminders Canonical name: PidLidReminderTimeDate Alternate names: dispidReminderTimeDate

### REMINDER_TIME_TIME {#REMINDER-TIME-TIME}
```
public static final PidLidPropertyDescriptor REMINDER_TIME_TIME
```


Indicates the time of the reminder for the appointment or meeting. Area: Reminders Canonical name: PidLidReminderTimeTime Alternate names: dispidReminderTimeTime

### REMINDER_TYPE {#REMINDER-TYPE}
```
public static final PidLidPropertyDescriptor REMINDER_TYPE
```


This property is not set and, if set, is ignored. Area: Reminders Canonical name: PidLidReminderType Alternate names: dispidReminderType, http://schemas.microsoft.com/mapi/remindertype

### REMOTE_MESSAGE_TRANSFER_AGENT {#REMOTE-MESSAGE-TRANSFER-AGENT}
```
public static final PidTagPropertyDescriptor REMOTE_MESSAGE_TRANSFER_AGENT
```


Contains the value of the Remote-MTA field for a delivery status notification, as specified in [RFC3464]. Area: Email Canonical name: PidTagRemoteMessageTransferAgent Alternate names: PR\_DSN\_REMOTE\_MTA, ptagDsnRemoteMta

### REMOTE_PROGRESS {#REMOTE-PROGRESS}
```
public static final PidTagPropertyDescriptor REMOTE_PROGRESS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REMOTE\_PROGRESS

### REMOTE_PROGRESS_TEXT {#REMOTE-PROGRESS-TEXT}
```
public static final PidTagPropertyDescriptor REMOTE_PROGRESS_TEXT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REMOTE\_PROGRESS\_TEXT

### REMOTE_STATUS {#REMOTE-STATUS}
```
public static final PidLidPropertyDescriptor REMOTE_STATUS
```


Indicates the remote status of the calendar item. Area: Run-time configuration Canonical name: PidLidRemoteStatus Alternate names: dispidRemoteStatus

### REMOTE_VALIDATE_OK {#REMOTE-VALIDATE-OK}
```
public static final PidTagPropertyDescriptor REMOTE_VALIDATE_OK
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REMOTE\_VALIDATE\_OK

### RENDERING_POSITION {#RENDERING-POSITION}
```
public static final PidTagPropertyDescriptor RENDERING_POSITION
```


Represents an offset, in rendered characters, to use when rendering an attachment within the main message text. Area: MapiAttachment Canonical name: PidTagRenderingPosition Alternate names: PR\_RENDERING\_POSITION, ptagRenderingPosition

### REPLICATION_ALWAYS_INTERVAL {#REPLICATION-ALWAYS-INTERVAL}
```
public static final PidTagPropertyDescriptor REPLICATION_ALWAYS_INTERVAL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPLICATION\_ALWAYS\_INTERVAL

### REPLICATION_MESSAGE_PRIORITY {#REPLICATION-MESSAGE-PRIORITY}
```
public static final PidTagPropertyDescriptor REPLICATION_MESSAGE_PRIORITY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPLICATION\_MESSAGE\_PRIORITY

### REPLICATION_MSG_SIZE {#REPLICATION-MSG-SIZE}
```
public static final PidTagPropertyDescriptor REPLICATION_MSG_SIZE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPLICATION\_MSG\_SIZE

### REPLICATION_SCHEDULE {#REPLICATION-SCHEDULE}
```
public static final PidTagPropertyDescriptor REPLICATION_SCHEDULE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPLICATION\_SCHEDULE

### REPLICATION_STYLE {#REPLICATION-STYLE}
```
public static final PidTagPropertyDescriptor REPLICATION_STYLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPLICATION\_STYLE

### REPLICA_LIST {#REPLICA-LIST}
```
public static final PidTagPropertyDescriptor REPLICA_LIST
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPLICA\_LIST

### REPLICA_SERVER {#REPLICA-SERVER}
```
public static final PidTagPropertyDescriptor REPLICA_SERVER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPLICA\_SERVER

### REPLICA_VERSION {#REPLICA-VERSION}
```
public static final PidTagPropertyDescriptor REPLICA_VERSION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPLICA\_VERSION

### REPLY_RECIPIENT_ENTRIES {#REPLY-RECIPIENT-ENTRIES}
```
public static final PidTagPropertyDescriptor REPLY_RECIPIENT_ENTRIES
```


Identifies a FlatEntryList structure ([MS-OXCDATA] section 2.3.3) of address book EntryIDs for recipients that are to receive a reply. Area: MapiEnvelope Canonical name: PidTagReplyRecipientEntries Alternate names: PR\_REPLY\_RECIPIENT\_ENTRIES, ptagReplyRecipientEntries,

### REPLY_RECIPIENT_NAMES {#REPLY-RECIPIENT-NAMES}
```
public static final PidTagPropertyDescriptor REPLY_RECIPIENT_NAMES
```


Contains a list of display names for recipients that are to receive a reply. Area: MapiEnvelope Canonical name: PidTagReplyRecipientNames Alternate names: PR\_REPLY\_RECIPIENT\_NAMES, PR\_REPLY\_RECIPIENT\_NAMES\_A, ptagReplyRecipientNames, PR\_REPLY\_RECIPIENT\_NAMES\_W

### REPLY_RECIPIENT_SMTP_PROXIES {#REPLY-RECIPIENT-SMTP-PROXIES}
```
public static final PidTagPropertyDescriptor REPLY_RECIPIENT_SMTP_PROXIES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPLY\_RECIPIENT\_SMTP\_PROXIES

### REPLY_REQUESTED {#REPLY-REQUESTED}
```
public static final PidTagPropertyDescriptor REPLY_REQUESTED
```


Indicates whether a reply is requested to a Message object. Area: MapiRecipient Canonical name: PidTagReplyRequested Alternate names: PR\_REPLY\_REQUESTED, ptagReplyRequested

### REPLY_TEMPLATE_ID {#REPLY-TEMPLATE-ID}
```
public static final PidTagPropertyDescriptor REPLY_TEMPLATE_ID
```


Contains the value of the GUID that points to a Reply template. Area: Rules Canonical name: PidTagReplyTemplateId Alternate names: PR\_REPLY\_TEMPLATE\_ID, ptagReplyTemplateId

### REPLY_TIME {#REPLY-TIME}
```
public static final PidTagPropertyDescriptor REPLY_TIME
```


Specifies the time, in UTC, that the sender has designated for an associated work item to be due. Area: MapiEnvelope Canonical name: PidTagReplyTime Alternate names: PR\_REPLY\_TIME, urn:schemas:httpmail:reply-by,

### REPORTING_DL_NAME {#REPORTING-DL-NAME}
```
public static final PidTagPropertyDescriptor REPORTING_DL_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPORTING\_DL\_NAME

### REPORTING_MESSAGE_TRANSFER_AGENT {#REPORTING-MESSAGE-TRANSFER-AGENT}
```
public static final PidTagPropertyDescriptor REPORTING_MESSAGE_TRANSFER_AGENT
```


Contains the value of the Reporting-MTA field for a delivery status notification, as specified in [RFC3464]. Area: Email Canonical name: PidTagReportingMessageTransferAgent Alternate names: ptagDsnReportingMta

### REPORTING_MTA_CERTIFICATE {#REPORTING-MTA-CERTIFICATE}
```
public static final PidTagPropertyDescriptor REPORTING_MTA_CERTIFICATE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPORTING\_MTA\_CERTIFICATE

### REPORT_DESTINATION_ENTRYID {#REPORT-DESTINATION-ENTRYID}
```
public static final PidTagPropertyDescriptor REPORT_DESTINATION_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPORT\_DESTINATION\_ENTRYID

### REPORT_DESTINATION_NAME {#REPORT-DESTINATION-NAME}
```
public static final PidTagPropertyDescriptor REPORT_DESTINATION_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REPORT\_DESTINATION\_NAME

### REPORT_DISPOSITION {#REPORT-DISPOSITION}
```
public static final PidTagPropertyDescriptor REPORT_DISPOSITION
```


Contains a string indicating whether the original message was displayed to the user or deleted (report messages only). Area: Email Canonical name: PidTagReportDisposition Alternate names: PR\_REPORT\_DISPOSITION\_W

### REPORT_DISPOSITION_MODE {#REPORT-DISPOSITION-MODE}
```
public static final PidTagPropertyDescriptor REPORT_DISPOSITION_MODE
```


Contains a description of the action that a client has performed on behalf of a user (report messages only). Area: Email Canonical name: PidTagReportDispositionMode Alternate names: PR\_REPORT\_DISPOSITION\_MODE\_W

### REPORT_ENTRY_ID {#REPORT-ENTRY-ID}
```
public static final PidTagPropertyDescriptor REPORT_ENTRY_ID
```


Specifies an entry ID that identifies the application that generated a report message. Area: MapiEnvelope Canonical name: PidTagReportEntryId Alternate names: PR\_REPORT\_ENTRYID, ptagReportEntryId

### REPORT_NAME {#REPORT-NAME}
```
public static final PidTagPropertyDescriptor REPORT_NAME
```


Contains the display name for the entity (usually a server agent) that generated the report message. Area: MapiEnvelope Canonical name: PidTagReportName Alternate names: PR\_REPORT\_NAME, PR\_REPORT\_NAME\_A, PR\_REPORT\_NAME\_W

### REPORT_SEARCH_KEY {#REPORT-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor REPORT_SEARCH_KEY
```


Contains an address book search key representing the entity (usually a server agent) that generated the report message. Area: MapiEnvelope Canonical name: PidTagReportSearchKey Alternate names: PR\_REPORT\_SEARCH\_KEY, ptagReportSearchKey

### REPORT_TAG {#REPORT-TAG}
```
public static final PidTagPropertyDescriptor REPORT_TAG
```


Contains the data that is used to correlate the report and the original message. Area: MapiEnvelope Canonical name: PidTagReportTag Alternate names: PR\_REPORT\_TAG, ptagReportTag

### REPORT_TEXT {#REPORT-TEXT}
```
public static final PidTagPropertyDescriptor REPORT_TEXT
```


Contains the optional text for a report message. Area: MapiMessage Canonical name: PidTagReportText Alternate names: PR\_REPORT\_TEXT, PR\_REPORT\_TEXT\_A, ptagReportText, PR\_REPORT\_TEXT\_W

### REPORT_TIME {#REPORT-TIME}
```
public static final PidTagPropertyDescriptor REPORT_TIME
```


Indicates the last time that the contact list that is controlled by the PidTagJunkIncludeContacts property (section 2.749) was updated. Area: MapiEnvelope Property set Canonical name: PidTagReportTime Alternate names: PR\_REPORT\_TIME, ptagReportTime,

### REQUESTED_DELIVERY_METHOD {#REQUESTED-DELIVERY-METHOD}
```
public static final PidTagPropertyDescriptor REQUESTED_DELIVERY_METHOD
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_REQUESTED\_DELIVERY\_METHOD

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final PidLidPropertyDescriptor REQUIRED_ATTENDEES
```


Identifies required attendees for the appointment or meeting. Area: Meetings Canonical name: PidLidRequiredAttendees Alternate names: LID\_REQUIRED\_ATTENDEES

### RESOLVE_METHOD {#RESOLVE-METHOD}
```
public static final PidTagPropertyDescriptor RESOLVE_METHOD
```


Specifies how to resolve any conflicts with the message. Area: MapiStatus Canonical name: PidTagResolveMethod Alternate names: PR\_RESOLVE\_METHOD, ptagResolveMethod

### RESOURCE_ATTENDEES {#RESOURCE-ATTENDEES}
```
public static final PidLidPropertyDescriptor RESOURCE_ATTENDEES
```


Identifies resource attendees for the appointment or meeting. Area: Meetings Canonical name: PidLidResourceAttendees Alternate names: LID\_RESOURCE\_ATTENDEES

### RESOURCE_FLAGS {#RESOURCE-FLAGS}
```
public static final PidTagPropertyDescriptor RESOURCE_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RESOURCE\_FLAGS

### RESOURCE_METHODS {#RESOURCE-METHODS}
```
public static final PidTagPropertyDescriptor RESOURCE_METHODS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RESOURCE\_METHODS

### RESOURCE_PATH {#RESOURCE-PATH}
```
public static final PidTagPropertyDescriptor RESOURCE_PATH
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RESOURCE\_PATH

### RESOURCE_TYPE {#RESOURCE-TYPE}
```
public static final PidTagPropertyDescriptor RESOURCE_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RESOURCE\_TYPE

### RESPONSE_REQUESTED {#RESPONSE-REQUESTED}
```
public static final PidTagPropertyDescriptor RESPONSE_REQUESTED
```


Indicates whether a response is requested to a Message object. Area: MapiEnvelope Property set Canonical name: PidTagResponseRequested Alternate names: PR\_RESPONSE\_REQUESTED, urn:schemas:calendar:responserequested,

### RESPONSE_STATUS {#RESPONSE-STATUS}
```
public static final PidLidPropertyDescriptor RESPONSE_STATUS
```


Specifies the response status of an attendee. Area: Meetings Canonical name: PidLidResponseStatus Alternate names: dispidResponseStatus

### RESPONSIBILITY {#RESPONSIBILITY}
```
public static final PidTagPropertyDescriptor RESPONSIBILITY
```


Specifies whether another mail agent has ensured that the message will be delivered. Area: MapiNonTransmittable Canonical name: PidTagResponsibility Alternate names: PR\_RESPONSIBILITY, ptagResponsibility

### RESTRICTION_COUNT {#RESTRICTION-COUNT}
```
public static final PidTagPropertyDescriptor RESTRICTION_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RESTRICTION\_COUNT

### RETENTION_AGE_LIMIT {#RETENTION-AGE-LIMIT}
```
public static final PidTagPropertyDescriptor RETENTION_AGE_LIMIT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RETENTION\_AGE\_LIMIT

### RETENTION_DATE {#RETENTION-DATE}
```
public static final PidTagPropertyDescriptor RETENTION_DATE
```


Specifies the date, in UTC, after which a Message object is expired by the server. Area: Archive Canonical name: PidTagRetentionDate Alternate names: PR\_RETENTION\_DATE, ptagRetentionDate

### RETENTION_FLAGS {#RETENTION-FLAGS}
```
public static final PidTagPropertyDescriptor RETENTION_FLAGS
```


Contains flags that specify the status or nature of an item's retention tag or archive tag. Area: Archive Canonical name: PidTagRetentionFlags Alternate names: PR\_RETENTION\_FLAGS, ptagRetentionFlags

### RETENTION_PERIOD {#RETENTION-PERIOD}
```
public static final PidTagPropertyDescriptor RETENTION_PERIOD
```


Specifies the number of days that a Message object can remain unarchived. Area: Archive Canonical name: PidTagRetentionPeriod Alternate names: PR\_RETENTION\_PERIOD, ptagRetentionPeriod

### RETURNED_IPM {#RETURNED-IPM}
```
public static final PidTagPropertyDescriptor RETURNED_IPM
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RETURNED\_IPM

### REVISION_NUMBER {#REVISION-NUMBER}
```
public static final PidNamePropertyDescriptor REVISION_NUMBER
```


Specifies the revision number of the file attached to the Document object. Area: Common Canonical name: PidNameRevisionNumber Alternate names: urn:schemas-microsoft-com:office:office\#Revision

### RIGHTS {#RIGHTS}
```
public static final PidTagPropertyDescriptor RIGHTS
```


Specifies a user's folder permissions. Area: ExchangeFolder Canonical name: PidTagRights Alternate names: PR\_RIGHTS, ptagRights

### RIGHTS_MANAGEMENT_LICENSE {#RIGHTS-MANAGEMENT-LICENSE}
```
public static final PidNamePropertyDescriptor RIGHTS_MANAGEMENT_LICENSE
```


Specifies the value used to cache the Use License for the rights-managed email message. Area: Secure Messaging Properties Canonical name: PidNameRightsManagementLicense Alternate names:

### ROAMING_DATATYPES {#ROAMING-DATATYPES}
```
public static final PidTagPropertyDescriptor ROAMING_DATATYPES
```


Contains a bitmask that indicates which stream properties exist on the message. Area: Configuration Canonical name: PidTagRoamingDatatypes Alternate names: PR\_ROAMING\_DATATYPES

### ROAMING_DICTIONARY {#ROAMING-DICTIONARY}
```
public static final PidTagPropertyDescriptor ROAMING_DICTIONARY
```


Contains a dictionary stream, as specified in [MS-OXOCFG] section 2.2.5.1. Area: Configuration Canonical name: PidTagRoamingDictionary Alternate names: PR\_ROAMING\_DICTIONARY

### ROAMING_XML_STREAM {#ROAMING-XML-STREAM}
```
public static final PidTagPropertyDescriptor ROAMING_XML_STREAM
```


Contains an XML stream, as specified in [MS-OXOCFG] section 2.2.5.2. Area: Configuration Canonical name: PidTagRoamingXmlStream Alternate names: PR\_ROAMING\_XMLSTREAM

### ROWID {#ROWID}
```
public static final PidTagPropertyDescriptor ROWID
```


Contains a unique identifier for a recipient in a message's recipient table. Area: MapiCommon Canonical name: PidTagRowid Alternate names: PR\_ROWID, ptagRowId

### ROW_TYPE {#ROW-TYPE}
```
public static final PidTagPropertyDescriptor ROW_TYPE
```


Identifies the type of the row. Area: MapiNonTransmittable Canonical name: PidTagRowType Alternate names: PR\_ROW\_TYPE, ptagRowType

### RTF_COMPRESSED {#RTF-COMPRESSED}
```
public static final PidTagPropertyDescriptor RTF_COMPRESSED
```


Contains message body text in compressed RTF format. Area: Email Canonical name: PidTagRtfCompressed Alternate names: PR\_RTF\_COMPRESSED, ptagRTFCompressed

### RTF_IN_SYNC {#RTF-IN-SYNC}
```
public static final PidTagPropertyDescriptor RTF_IN_SYNC
```


Indicates whether the PidTagBody property (section 2.609) and the PidTagRtfCompressed property (section 2.932) contain the same text (ignoring formatting). Area: Email Canonical name: PidTagRtfInSync Alternate names: PR\_RTF\_IN\_SYNC, ptagRTFInSync

### RTF_SYNC_BODY_COUNT {#RTF-SYNC-BODY-COUNT}
```
public static final PidTagPropertyDescriptor RTF_SYNC_BODY_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RTF\_SYNC\_BODY\_COUNT

### RTF_SYNC_BODY_CRC {#RTF-SYNC-BODY-CRC}
```
public static final PidTagPropertyDescriptor RTF_SYNC_BODY_CRC
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RTF\_SYNC\_BODY\_CRC

### RTF_SYNC_BODY_TAG {#RTF-SYNC-BODY-TAG}
```
public static final PidTagPropertyDescriptor RTF_SYNC_BODY_TAG
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RTF\_SYNC\_BODY\_TAG

### RTF_SYNC_PREFIX_COUNT {#RTF-SYNC-PREFIX-COUNT}
```
public static final PidTagPropertyDescriptor RTF_SYNC_PREFIX_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RTF\_SYNC\_PREFIX\_COUNT

### RTF_SYNC_TRAILING_COUNT {#RTF-SYNC-TRAILING-COUNT}
```
public static final PidTagPropertyDescriptor RTF_SYNC_TRAILING_COUNT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RTF\_SYNC\_TRAILING\_COUNT

### RULES_DATA {#RULES-DATA}
```
public static final PidTagPropertyDescriptor RULES_DATA
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RULES\_DATA

### RULES_TABLE {#RULES-TABLE}
```
public static final PidTagPropertyDescriptor RULES_TABLE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RULES\_TABLE

### RULE_ACTIONS {#RULE-ACTIONS}
```
public static final PidTagPropertyDescriptor RULE_ACTIONS
```


Contains the set of actions associated with the rule. Area: Server-Side Rules Properties Canonical name: PidTagRuleActions Alternate names: PR\_RULE\_ACTIONS, ptagRuleActions

### RULE_ACTION_NUMBER {#RULE-ACTION-NUMBER}
```
public static final PidTagPropertyDescriptor RULE_ACTION_NUMBER
```


Contains the index of a rule action that failed. Area: ExchangeMessageReadOnly Canonical name: PidTagRuleActionNumber Alternate names: PR\_RULE\_ACTION\_NUMBER, ptagRuleActionNumber

### RULE_ACTION_TYPE {#RULE-ACTION-TYPE}
```
public static final PidTagPropertyDescriptor RULE_ACTION_TYPE
```


Contains the ActionType field ([MS-OXORULE] section 2.2.5.1) of a rule that failed. Area: ExchangeMessageReadOnly Canonical name: PidTagRuleActionType Alternate names: PR\_RULE\_ACTION\_TYPE, ptagRuleActionType

### RULE_CONDITION {#RULE-CONDITION}
```
public static final PidTagPropertyDescriptor RULE_CONDITION
```


Defines the conditions under which a rule action is to be executed. Area: Server-Side Rules Properties Canonical name: PidTagRuleCondition Alternate names: PR\_RULE\_CONDITION, ptagRuleCondition

### RULE_ERROR {#RULE-ERROR}
```
public static final PidTagPropertyDescriptor RULE_ERROR
```


Contains the error code that indicates the cause of an error encountered during the execution of the rule. Area: ExchangeMessageReadOnly Canonical name: PidTagRuleError Alternate names: PR\_RULE\_ERROR, ptagRuleError

### RULE_FOLDER_ENTRY_ID {#RULE-FOLDER-ENTRY-ID}
```
public static final PidTagPropertyDescriptor RULE_FOLDER_ENTRY_ID
```


Contains the EntryID of the folder where the rule that triggered the generation of a DAM is stored. Area: ExchangeMessageReadOnly Canonical name: PidTagRuleFolderEntryId Alternate names: PR\_RULE\_FOLDER\_ENTRYID, ptagRuleFolderEntryId

### RULE_ID {#RULE-ID}
```
public static final PidTagPropertyDescriptor RULE_ID
```


Specifies a unique identifier that is generated by the messaging server for each rule when the rule is first created. Area: Server-Side Rules Properties Canonical name: PidTagRuleId Alternate names: PR\_RULE\_ID, ptagRuleId

### RULE_IDS {#RULE-IDS}
```
public static final PidTagPropertyDescriptor RULE_IDS
```


Contains a buffer that is obtained by concatenating the PidTagRuleId property (section property (section 2.625). Area: Server-Side Rules Properties Canonical name: PidTagRuleIds Alternate names: PR\_RULE\_IDS, ptagRuleIds

### RULE_LEVEL {#RULE-LEVEL}
```
public static final PidTagPropertyDescriptor RULE_LEVEL
```


Contains 0x00000000. This property is not used. Area: Server-Side Rules Properties Canonical name: PidTagRuleLevel Alternate names: PR\_RULE\_LEVEL, ptagRuleLevel

### RULE_MESSAGE_LEVEL {#RULE-MESSAGE-LEVEL}
```
public static final PidTagPropertyDescriptor RULE_MESSAGE_LEVEL
```


Contains 0x00000000. Set on the FAI message. Area: ExchangeNonTransmittableReserved Canonical name: PidTagRuleMessageLevel Alternate names: PR\_RULE\_MSG\_LEVEL, ptagRuleMsgLevel

### RULE_MESSAGE_NAME {#RULE-MESSAGE-NAME}
```
public static final PidTagPropertyDescriptor RULE_MESSAGE_NAME
```


Specifies the name of the rule. Set on the FAI message. Area: ExchangeNonTransmittableReserved Canonical name: PidTagRuleMessageName Alternate names: ptagRuleMsgName

### RULE_MESSAGE_PROVIDER {#RULE-MESSAGE-PROVIDER}
```
public static final PidTagPropertyDescriptor RULE_MESSAGE_PROVIDER
```


Identifies the client application that owns the rule. Set on the FAI message. Area: ExchangeNonTransmittableReserved Canonical name: PidTagRuleMessageProvider Alternate names: ptagRuleMsgProvider

### RULE_MESSAGE_PROVIDER_DATA {#RULE-MESSAGE-PROVIDER-DATA}
```
public static final PidTagPropertyDescriptor RULE_MESSAGE_PROVIDER_DATA
```


Contains opaque data set by the client for the exclusive use of the client. Set on the FAI message. Area: ExchangeNonTransmittableReserved Canonical name: PidTagRuleMessageProviderData Alternate names: PR\_RULE\_MSG\_PROVIDER\_DATA, ptagRuleMsgProviderData

### RULE_MESSAGE_SEQUENCE {#RULE-MESSAGE-SEQUENCE}
```
public static final PidTagPropertyDescriptor RULE_MESSAGE_SEQUENCE
```


Contains a value used to determine the order in which rules are evaluated and executed. Set on the FAI message. Area: ExchangeNonTransmittableReserved Canonical name: PidTagRuleMessageSequence Alternate names: PR\_RULE\_MSG\_SEQUENCE, ptagRuleMsgSequence

### RULE_MESSAGE_STATE {#RULE-MESSAGE-STATE}
```
public static final PidTagPropertyDescriptor RULE_MESSAGE_STATE
```


Contains flags that specify the state of the rule. Set on the FAI message. Area: ExchangeNonTransmittableReserved Canonical name: PidTagRuleMessageState Alternate names: PR\_RULE\_MSG\_STATE, ptagRuleMsgState

### RULE_MESSAGE_USER_FLAGS {#RULE-MESSAGE-USER-FLAGS}
```
public static final PidTagPropertyDescriptor RULE_MESSAGE_USER_FLAGS
```


Contains an opaque property that the client sets for the exclusive use of the client. Set on the FAI message. Area: ExchangeNonTransmittableReserved Canonical name: PidTagRuleMessageUserFlags Alternate names: PR\_RULE\_MSG\_USER\_FLAGS, ptagRuleMsgUserFlags

### RULE_NAME {#RULE-NAME}
```
public static final PidTagPropertyDescriptor RULE_NAME
```


Specifies the name of the rule. Area: Server-Side Rules Properties Canonical name: PidTagRuleName Alternate names: PR\_RULE\_NAME, PR\_RULE\_NAME\_A, ptagRuleName, PR\_RULE\_NAME\_W

### RULE_PROVIDER {#RULE-PROVIDER}
```
public static final PidTagPropertyDescriptor RULE_PROVIDER
```


A string identifying the client application that owns a rule. Area: Server-Side Rules Properties Canonical name: PidTagRuleProvider Alternate names: PR\_RULE\_PROVIDER, ptagRuleProvider, PR\_RULE\_PROVIDER\_W

### RULE_PROVIDER_DATA {#RULE-PROVIDER-DATA}
```
public static final PidTagPropertyDescriptor RULE_PROVIDER_DATA
```


Contains opaque data set by the client for the exclusive use of the client. Area: Server-Side Rules Properties Canonical name: PidTagRuleProviderData Alternate names: PR\_RULE\_PROVIDER\_DATA, ptagRuleProviderData

### RULE_SEQUENCE {#RULE-SEQUENCE}
```
public static final PidTagPropertyDescriptor RULE_SEQUENCE
```


Contains a value used to determine the order in which rules are evaluated and executed. Area: Server-Side Rules Properties Canonical name: PidTagRuleSequence Alternate names: PR\_RULE\_SEQUENCE, ptagRuleSequence

### RULE_STATE {#RULE-STATE}
```
public static final PidTagPropertyDescriptor RULE_STATE
```


Contains flags that specify the state of the rule. Area: Server-Side Rules Properties Canonical name: PidTagRuleState Alternate names: PR\_RULE\_STATE, ptagRuleState

### RULE_TRIGGER_HISTORY {#RULE-TRIGGER-HISTORY}
```
public static final PidTagPropertyDescriptor RULE_TRIGGER_HISTORY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_RULE\_TRIGGER\_HISTORY

### RULE_USER_FLAGS {#RULE-USER-FLAGS}
```
public static final PidTagPropertyDescriptor RULE_USER_FLAGS
```


Contains an opaque property that the client sets for the exclusive use of the client. Area: Server-Side Rules Properties Canonical name: PidTagRuleUserFlags Alternate names: PR\_RULE\_USER\_FLAGS, ptagRuleUserFlags

### RW_RULES_STREAM {#RW-RULES-STREAM}
```
public static final PidTagPropertyDescriptor RW_RULES_STREAM
```


Contains additional rule data about the Rule FAI message. Area: Message Class Defined Transmittable Canonical name: PidTagRwRulesStream Alternate names: PR\_RW\_RULES\_STREAM

### SCALE {#SCALE}
```
public static final PidNamePropertyDescriptor SCALE
```


Indicates whether the image is to be scaled or cropped. Area: Common Canonical name: PidNameScale Alternate names: urn:schemas-microsoft-com:office:office\#ScaleCrop

### SCHEDULE_FOLDER_ENTRYID {#SCHEDULE-FOLDER-ENTRYID}
```
public static final PidTagPropertyDescriptor SCHEDULE_FOLDER_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SCHEDULE\_FOLDER\_ENTRYID

### SCHEDULE_INFO_APPOINTMENT_TOMBSTONE {#SCHEDULE-INFO-APPOINTMENT-TOMBSTONE}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_APPOINTMENT_TOMBSTONE
```


Contains a list of tombstones, where each tombstone represents a Meeting object that has been declined. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoAppointmentTombstone Alternate names: PR\_SCHDINFO\_APPT\_TOMBSTONE

### SCHEDULE_INFO_AUTO_ACCEPT_APPOINTMENTS {#SCHEDULE-INFO-AUTO-ACCEPT-APPOINTMENTS}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_AUTO_ACCEPT_APPOINTMENTS
```


Indicates whether a client or server is to automatically respond to all meeting requests for the attendee or resource. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoAutoAcceptAppointments Alternate names: PR\_SCHDINFO\_AUTO\_ACCEPT\_APPTS

### SCHEDULE_INFO_DELEGATE_ENTRY_IDS {#SCHEDULE-INFO-DELEGATE-ENTRY-IDS}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_DELEGATE_ENTRY_IDS
```


Specifies the EntryIDs of the delegates. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoDelegateEntryIds Alternate names: PR\_SCHDINFO\_DELEGATE\_ENTRYIDS

### SCHEDULE_INFO_DELEGATE_NAMES {#SCHEDULE-INFO-DELEGATE-NAMES}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_DELEGATE_NAMES
```


Specifies the names of the delegates. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoDelegateNames Alternate names: PR\_SCHDINFO\_DELEGATE\_NAMES

### SCHEDULE_INFO_DELEGATE_NAMES_W {#SCHEDULE-INFO-DELEGATE-NAMES-W}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_DELEGATE_NAMES_W
```


Specifies the names of the delegates in Unicode. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoDelegateNamesW Alternate names: PR\_SCHDINFO\_DELEGATE\_NAMES\_W, ptagDelegateNames

### SCHEDULE_INFO_DELEGATOR_WANTS_COPY {#SCHEDULE-INFO-DELEGATOR-WANTS-COPY}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_DELEGATOR_WANTS_COPY
```


Indicates whether the delegator wants to receive copies of the meeting-related objects that are sent to the delegate. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoDelegatorWantsCopy Alternate names: PR\_SCHDINFO\_BOSS\_WANTS\_COPY

### SCHEDULE_INFO_DELEGATOR_WANTS_INFO {#SCHEDULE-INFO-DELEGATOR-WANTS-INFO}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_DELEGATOR_WANTS_INFO
```


Indicates whether the delegator wants to receive informational updates. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoDelegatorWantsInfo Alternate names: PR\_SCHDINFO\_BOSS\_WANTS\_INFO

### SCHEDULE_INFO_DISALLOW_OVERLAPPING_APPTS {#SCHEDULE-INFO-DISALLOW-OVERLAPPING-APPTS}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_DISALLOW_OVERLAPPING_APPTS
```


Indicates whether a client or server, when automatically responding to meeting requests, is to decline Meeting Request objects that overlap with previously scheduled events. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoDisallowOverlappingAppts Alternate names: PR\_SCHDINFO\_DISALLOW\_OVERLAPPING\_APPTS

### SCHEDULE_INFO_DISALLOW_RECURRING_APPTS {#SCHEDULE-INFO-DISALLOW-RECURRING-APPTS}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_DISALLOW_RECURRING_APPTS
```


Indicates whether a client or server, when automatically responding to meeting requests, is to decline Meeting Request objects that represent a recurring series. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoDisallowRecurringAppts Alternate names: PR\_SCHDINFO\_DISALLOW\_RECURRING\_APPTS

### SCHEDULE_INFO_DONT_MAIL_DELEGATES {#SCHEDULE-INFO-DONT-MAIL-DELEGATES}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_DONT_MAIL_DELEGATES
```


Contains a value set to TRUE by the client, regardless of user input. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoDontMailDelegates Alternate names: PR\_SCHDINFO\_DONT\_MAIL\_DELEGATES

### SCHEDULE_INFO_FREE_BUSY {#SCHEDULE-INFO-FREE-BUSY}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_FREE_BUSY
```


This property is deprecated and is not to be used. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoFreeBusy Alternate names: PR\_SCHDINFO\_FREEBUSY

### SCHEDULE_INFO_FREE_BUSY_AWAY {#SCHEDULE-INFO-FREE-BUSY-AWAY}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_FREE_BUSY_AWAY
```


Specifies the times for which the free/busy status is set a value of OOF. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoFreeBusyAway Alternate names: PR\_SCHDINFO\_FREEBUSY\_OOF

### SCHEDULE_INFO_FREE_BUSY_BUSY {#SCHEDULE-INFO-FREE-BUSY-BUSY}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_FREE_BUSY_BUSY
```


Specifies the blocks of time for which the free/busy status is set to a value of busy. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoFreeBusyBusy Alternate names: PR\_SCHDINFO\_FREEBUSY\_BUSY

### SCHEDULE_INFO_FREE_BUSY_MERGED {#SCHEDULE-INFO-FREE-BUSY-MERGED}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_FREE_BUSY_MERGED
```


Specifies the blocks for which free/busy data of type busy or OOF is present in the free/busy message. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoFreeBusyMerged Alternate names: PR\_SCHDINFO\_FREEBUSY\_MERGED

### SCHEDULE_INFO_FREE_BUSY_TENTATIVE {#SCHEDULE-INFO-FREE-BUSY-TENTATIVE}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_FREE_BUSY_TENTATIVE
```


Specifies the blocks of times for which the free/busy status is set to a value of tentative. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoFreeBusyTentative Alternate names: PR\_SCHDINFO\_FREEBUSY\_TENTATIVE

### SCHEDULE_INFO_MONTHS_AWAY {#SCHEDULE-INFO-MONTHS-AWAY}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_MONTHS_AWAY
```


Specifies the months for which free/busy data of type OOF is present in the free/busy message. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoMonthsAway Alternate names: PR\_SCHDINFO\_MONTHS\_OOF

### SCHEDULE_INFO_MONTHS_BUSY {#SCHEDULE-INFO-MONTHS-BUSY}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_MONTHS_BUSY
```


Specifies the months for which free/busy data of type busy is present in the free/busy message. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoMonthsBusy Alternate names: PR\_SCHDINFO\_MONTHS\_BUSY

### SCHEDULE_INFO_MONTHS_MERGED {#SCHEDULE-INFO-MONTHS-MERGED}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_MONTHS_MERGED
```


Specifies the months for which free/busy data of type busy or OOF is present in the free/busy message. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoMonthsMerged Alternate names: PR\_SCHDINFO\_MONTHS\_MERGED

### SCHEDULE_INFO_MONTHS_TENTATIVE {#SCHEDULE-INFO-MONTHS-TENTATIVE}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_MONTHS_TENTATIVE
```


Specifies the months for which free/busy data of type tentative is present in the free/busy message. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoMonthsTentative Alternate names: PR\_SCHDINFO\_MONTHS\_TENTATIVE

### SCHEDULE_INFO_RESOURCE_TYPE {#SCHEDULE-INFO-RESOURCE-TYPE}
```
public static final PidTagPropertyDescriptor SCHEDULE_INFO_RESOURCE_TYPE
```


Set to 0x00000000 when sending and is ignored on receipt. Area: Free/Busy Properties Canonical name: PidTagScheduleInfoResourceType Alternate names: PR\_SCHDINFO\_RESOURCE\_TYPE

### SCHEDULE_PLUS_FREE_BUSY_ENTRY_ID {#SCHEDULE-PLUS-FREE-BUSY-ENTRY-ID}
```
public static final PidTagPropertyDescriptor SCHEDULE_PLUS_FREE_BUSY_ENTRY_ID
```


Contains the EntryID of the folder named "SCHEDULE+ FREE BUSY" under the non-IPM subtree of the public folder message store. Area: ExchangeMessageStore Canonical name: PidTagSchedulePlusFreeBusyEntryId Alternate names: PR\_SPLUS\_FREE\_BUSY\_ENTRYID

### SCRIPT_DATA {#SCRIPT-DATA}
```
public static final PidTagPropertyDescriptor SCRIPT_DATA
```


Contains a series of instructions that can be executed to format an address and the data that is needed to execute those instructions. Area: Address Book Canonical name: PidTagScriptData Alternate names: PR\_EMS\_SCRIPT\_BLOB

### SEARCH {#SEARCH}
```
public static final PidTagPropertyDescriptor SEARCH
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SEARCH

### SEARCH_FOLDER_DEFINITION {#SEARCH-FOLDER-DEFINITION}
```
public static final PidTagPropertyDescriptor SEARCH_FOLDER_DEFINITION
```


Specifies the search criteria and search options. Area: Search Canonical name: PidTagSearchFolderDefinition Alternate names: PR\_WB\_SF\_DEFINITION

### SEARCH_FOLDER_EFP_FLAGS {#SEARCH-FOLDER-EFP-FLAGS}
```
public static final PidTagPropertyDescriptor SEARCH_FOLDER_EFP_FLAGS
```


Specifies flags that control how a folder is displayed. Area: Search Canonical name: PidTagSearchFolderEfpFlags Alternate names: PR\_WB\_SF\_EFP\_FLAGS

### SEARCH_FOLDER_EXPIRATION {#SEARCH-FOLDER-EXPIRATION}
```
public static final PidTagPropertyDescriptor SEARCH_FOLDER_EXPIRATION
```


Contains the time, in UTC, at which the search folder container will be stale and has to be updated or recreated. Area: Search Canonical name: PidTagSearchFolderExpiration Alternate names: PR\_WB\_SF\_EXPIRATION

### SEARCH_FOLDER_ID {#SEARCH-FOLDER-ID}
```
public static final PidTagPropertyDescriptor SEARCH_FOLDER_ID
```


Contains a GUID that identifies the search folder. Area: Search Canonical name: PidTagSearchFolderId Alternate names: PR\_WB\_SF\_ID

### SEARCH_FOLDER_LAST_USED {#SEARCH-FOLDER-LAST-USED}
```
public static final PidTagPropertyDescriptor SEARCH_FOLDER_LAST_USED
```


Contains the last time, in UTC, that the folder was accessed. Area: Search Canonical name: PidTagSearchFolderLastUsed Alternate names: PR\_WB\_SF\_LAST\_USED

### SEARCH_FOLDER_RECREATE_INFO {#SEARCH-FOLDER-RECREATE-INFO}
```
public static final PidTagPropertyDescriptor SEARCH_FOLDER_RECREATE_INFO
```


This property is not to be used. Area: Search Canonical name: PidTagSearchFolderRecreateInfo Alternate names: PR\_WB\_SF\_RECREATE\_INFO

### SEARCH_FOLDER_STORAGE_TYPE {#SEARCH-FOLDER-STORAGE-TYPE}
```
public static final PidTagPropertyDescriptor SEARCH_FOLDER_STORAGE_TYPE
```


Contains flags that specify the binary large object (BLOB) data that appears in the PidTagSearchFolderDefinition (section 2.979) property. Area: Search Canonical name: PidTagSearchFolderStorageType Alternate names: PR\_WB\_SF\_STORAGE\_TYPE

### SEARCH_FOLDER_TAG {#SEARCH-FOLDER-TAG}
```
public static final PidTagPropertyDescriptor SEARCH_FOLDER_TAG
```


Contains the value of the SearchFolderTag sub-property of the PidTagExtendedFolderFlags (section 2.682) property of the search folder container. Area: Search Canonical name: PidTagSearchFolderTag Alternate names: PR\_WB\_SF\_TAG

### SEARCH_FOLDER_TEMPLATE_ID {#SEARCH-FOLDER-TEMPLATE-ID}
```
public static final PidTagPropertyDescriptor SEARCH_FOLDER_TEMPLATE_ID
```


Contains the ID of the template that is being used for the search. Area: Search Canonical name: PidTagSearchFolderTemplateId Alternate names: PR\_WB\_SF\_TEMPLATE\_ID

### SEARCH_KEY {#SEARCH-KEY}
```
public static final PidTagPropertyDescriptor SEARCH_KEY
```


Contains a unique binary-comparable key that identifies an object for a search. Area: ID Properties Canonical name: PidTagSearchKey Alternate names: PR\_SEARCH\_KEY, ptagSearchKey

### SECURE_IN_SITE {#SECURE-IN-SITE}
```
public static final PidTagPropertyDescriptor SECURE_IN_SITE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SECURE\_IN\_SITE

### SECURE_ORIGINATION {#SECURE-ORIGINATION}
```
public static final PidTagPropertyDescriptor SECURE_ORIGINATION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SECURE\_ORIGINATION

### SECURITY {#SECURITY}
```
public static final PidNamePropertyDescriptor SECURITY
```


Specifies the security level of the file attached to the Document object. Area: Common Canonical name: PidNameSecurity Alternate names: urn:schemas-microsoft-com:office:office\#Security

### SECURITY_DESCRIPTOR_AS_XML {#SECURITY-DESCRIPTOR-AS-XML}
```
public static final PidTagPropertyDescriptor SECURITY_DESCRIPTOR_AS_XML
```


Contains security attributes in XML. Area: Access Control Properties Canonical name: PidTagSecurityDescriptorAsXml Alternate names: PR\_NT\_SECURITY\_DESCRIPTOR\_AS\_XML, PR\_NT\_SECURITY\_DESCRIPTOR\_AS\_XML\_A, PR\_NT\_SECURITY\_DESCRIPTOR\_AS\_XML\_W,

### SELECTABLE {#SELECTABLE}
```
public static final PidTagPropertyDescriptor SELECTABLE
```


This property is not set and, if set, is ignored. Area: AB Container Canonical name: PidTagSelectable Alternate names: PR\_SELECTABLE

### SENDER_ADDRESS_TYPE {#SENDER-ADDRESS-TYPE}
```
public static final PidTagPropertyDescriptor SENDER_ADDRESS_TYPE
```


Contains the email address type of the sending mailbox owner. Area: Address Properties Canonical name: PidTagSenderAddressType Alternate names: PR\_SENDER\_ADDRTYPE, PR\_SENDER\_ADDRTYPE\_A, ptagSenderAddrType, PR\_SENDER\_ADDRTYPE\_W

### SENDER_EMAIL_ADDRESS {#SENDER-EMAIL-ADDRESS}
```
public static final PidTagPropertyDescriptor SENDER_EMAIL_ADDRESS
```


Contains the email address of the sending mailbox owner. Area: Address Properties Canonical name: PidTagSenderEmailAddress Alternate names: PR\_SENDER\_EMAIL\_ADDRESS, PR\_SENDER\_EMAIL\_ADDRESS\_A, PR\_SENDER\_EMAIL\_ADDRESS\_W

### SENDER_ENTRY_ID {#SENDER-ENTRY-ID}
```
public static final PidTagPropertyDescriptor SENDER_ENTRY_ID
```


Identifies an address book EntryID that contains the address book EntryID of the sending mailbox owner. Area: Address Properties Canonical name: PidTagSenderEntryId Alternate names: PR\_SENDER\_ENTRYID, ptagSenderEntryId

### SENDER_ID_STATUS {#SENDER-ID-STATUS}
```
public static final PidTagPropertyDescriptor SENDER_ID_STATUS
```


Reports the results of a Sender-ID check. Area: Secure Messaging Properties Canonical name: PidTagSenderIdStatus Alternate names: PR\_SENDER\_ID\_STATUS

### SENDER_NAME {#SENDER-NAME}
```
public static final PidTagPropertyDescriptor SENDER_NAME
```


Contains the display name of the sending mailbox owner. Area: Address Properties Canonical name: PidTagSenderName Alternate names: PR\_SENDER\_NAME, PR\_SENDER\_NAME\_A, ptagSenderName,

### SENDER_SEARCH_KEY {#SENDER-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor SENDER_SEARCH_KEY
```


Identifies an address book search key. Area: Address Properties Canonical name: PidTagSenderSearchKey Alternate names: PR\_SENDER\_SEARCH\_KEY, ptagSenderSearchKey

### SENDER_SMTP_ADDRESS {#SENDER-SMTP-ADDRESS}
```
public static final PidTagPropertyDescriptor SENDER_SMTP_ADDRESS
```


Contains the SMTP email address format of the e\\ufffdmail address of the sending mailbox owner. Area: Mail Canonical name: PidTagSenderSmtpAddress Alternate names: SenderSmtpAddress, ptagSenderSmtpAddress

### SENDER_TELEPHONE_NUMBER {#SENDER-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor SENDER_TELEPHONE_NUMBER
```


Contains the telephone number of the caller associated with a voice mail message. Area: Unified Messaging Canonical name: PidTagSenderTelephoneNumber Alternate names: InternalSchemaSenderTelephoneNumber

### SEND_INTERNET_ENCODING {#SEND-INTERNET-ENCODING}
```
public static final PidTagPropertyDescriptor SEND_INTERNET_ENCODING
```


Contains a bitmask of message encoding preferences for email sent to an email-enabled entity that is represented by this Address Book object. Area: Address Properties Canonical name: PidTagSendInternetEncoding Alternate names: PR\_SEND\_INTERNET\_ENCODING, ptagSendInternetEncoding

### SEND_RICH_INFO {#SEND-RICH-INFO}
```
public static final PidTagPropertyDescriptor SEND_RICH_INFO
```


Indicates whether the email-enabled entity represented by the Address Book object can receive all message content, including Rich Text Format (RTF) and other embedded objects. Area: Address Properties Canonical name: PidTagSendRichInfo Alternate names: PR\_SEND\_RICH\_INFO, ptagSendRichInfo

### SENSITIVITY {#SENSITIVITY}
```
public static final PidTagPropertyDescriptor SENSITIVITY
```


Indicates the sender's assessment of the sensitivity of the Message object. Area: General Message Properties Canonical name: PidTagSensitivity Alternate names: PR\_SENSITIVITY, ptagSensitivity,

### SENTMAIL_ENTRYID {#SENTMAIL-ENTRYID}
```
public static final PidTagPropertyDescriptor SENTMAIL_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SENTMAIL\_ENTRYID

### SENT_MAIL_SVR_EID {#SENT-MAIL-SVR-EID}
```
public static final PidTagPropertyDescriptor SENT_MAIL_SVR_EID
```


Contains an EntryID that represents the Sent Items folder for the message. Area: ProviderDefinedNonTransmittable Canonical name: PidTagSentMailSvrEID Alternate names: ptagSentMailSvrEID

### SENT_REPRESENTING_ADDRESS_TYPE {#SENT-REPRESENTING-ADDRESS-TYPE}
```
public static final PidTagPropertyDescriptor SENT_REPRESENTING_ADDRESS_TYPE
```


Contains an email address type. Area: Address Properties Canonical name: PidTagSentRepresentingAddressType Alternate names: PR\_SENT\_REPRESENTING\_ADDRTYPE, PR\_SENT\_REPRESENTING\_ADDRTYPE\_A, ptagSentRepresentingAddrType, PR\_SENT\_REPRESENTING\_ADDRTYPE\_W

### SENT_REPRESENTING_EMAIL_ADDRESS {#SENT-REPRESENTING-EMAIL-ADDRESS}
```
public static final PidTagPropertyDescriptor SENT_REPRESENTING_EMAIL_ADDRESS
```


Contains an email address for the end user who is represented by the sending mailbox owner. Area: Address Properties Canonical name: PidTagSentRepresentingEmailAddress Alternate names: PR\_SENT\_REPRESENTING\_EMAIL\_ADDRESS, PR\_SENT\_REPRESENTING\_EMAIL\_ADDRESS\_A, PR\_SENT\_REPRESENTING\_EMAIL\_ADDRESS\_W

### SENT_REPRESENTING_ENTRY_ID {#SENT-REPRESENTING-ENTRY-ID}
```
public static final PidTagPropertyDescriptor SENT_REPRESENTING_ENTRY_ID
```


Contains the identifier of the end user who is represented by the sending mailbox owner. Area: Address Properties Canonical name: PidTagSentRepresentingEntryId Alternate names: PR\_SENT\_REPRESENTING\_ENTRYID, ptagSentRepresentingEntryId

### SENT_REPRESENTING_FLAGS {#SENT-REPRESENTING-FLAGS}
```
public static final PidTagPropertyDescriptor SENT_REPRESENTING_FLAGS
```


Area: Miscellaneous Properties Canonical name: PidTagSentRepresentingFlags Alternate names: ptagSentRepresentingFlags

### SENT_REPRESENTING_NAME {#SENT-REPRESENTING-NAME}
```
public static final PidTagPropertyDescriptor SENT_REPRESENTING_NAME
```


Contains the display name for the end user who is represented by the sending mailbox owner. Area: Address Properties Canonical name: PidTagSentRepresentingName Alternate names: PR\_SENT\_REPRESENTING\_NAME, PR\_SENT\_REPRESENTING\_NAME\_A,

### SENT_REPRESENTING_SEARCH_KEY {#SENT-REPRESENTING-SEARCH-KEY}
```
public static final PidTagPropertyDescriptor SENT_REPRESENTING_SEARCH_KEY
```


Contains a binary-comparable key that represents the end user who is represented by the sending mailbox owner. Area: Address Properties Canonical name: PidTagSentRepresentingSearchKey Alternate names: PR\_SENT\_REPRESENTING\_SEARCH\_KEY, ptagSentRepresentingSearchKey

### SENT_REPRESENTING_SMTP_ADDRESS {#SENT-REPRESENTING-SMTP-ADDRESS}
```
public static final PidTagPropertyDescriptor SENT_REPRESENTING_SMTP_ADDRESS
```


Contains the SMTP email address of the end user who is represented by the sending mailbox owner. Area: Mail Canonical name: PidTagSentRepresentingSmtpAddress Alternate names: ptagRecipientSentRepresentingSMTPAddress, SentRepresentingSMTPAddressXSO, PR\_SENT\_REPRESENTING\_SMTP\_ADDRESS

### SERVER_PROCESSED {#SERVER-PROCESSED}
```
public static final PidLidPropertyDescriptor SERVER_PROCESSED
```


Indicates whether the Meeting Request object or Meeting Update object has been processed. Area: Calendar Canonical name: PidLidServerProcessed Alternate names: dispidExchangeProcessed

### SERVER_PROCESSING_ACTIONS {#SERVER-PROCESSING-ACTIONS}
```
public static final PidLidPropertyDescriptor SERVER_PROCESSING_ACTIONS
```


Indicates what processing actions have been taken on this Meeting Request object or Meeting Update object. Area: Calendar Canonical name: PidLidServerProcessingActions Alternate names: dispidExchangeProcessingAction

### SERVICES {#SERVICES}
```
public static final PidTagPropertyDescriptor SERVICES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SERVICES

### SERVICE_DELETE_FILES {#SERVICE-DELETE-FILES}
```
public static final PidTagPropertyDescriptor SERVICE_DELETE_FILES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SERVICE\_DELETE\_FILES

### SERVICE_DLL_NAME {#SERVICE-DLL-NAME}
```
public static final PidTagPropertyDescriptor SERVICE_DLL_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SERVICE\_DLL\_NAME

### SERVICE_ENTRY_NAME {#SERVICE-ENTRY-NAME}
```
public static final PidTagPropertyDescriptor SERVICE_ENTRY_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SERVICE\_ENTRY\_NAME

### SERVICE_EXTRA_UIDS {#SERVICE-EXTRA-UIDS}
```
public static final PidTagPropertyDescriptor SERVICE_EXTRA_UIDS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SERVICE\_EXTRA\_UIDS

### SERVICE_NAME {#SERVICE-NAME}
```
public static final PidTagPropertyDescriptor SERVICE_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SERVICE\_NAME

### SERVICE_SUPPORT_FILES {#SERVICE-SUPPORT-FILES}
```
public static final PidTagPropertyDescriptor SERVICE_SUPPORT_FILES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SERVICE\_SUPPORT\_FILES

### SERVICE_UID {#SERVICE-UID}
```
public static final PidTagPropertyDescriptor SERVICE_UID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SERVICE\_UID

### SHARING_ANONYMITY {#SHARING-ANONYMITY}
```
public static final PidLidPropertyDescriptor SHARING_ANONYMITY
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingAnonymity Alternate names: dispidSharingAnonymity

### SHARING_BINDING_ENTRY_ID {#SHARING-BINDING-ENTRY-ID}
```
public static final PidLidPropertyDescriptor SHARING_BINDING_ENTRY_ID
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingBindingEntryId Alternate names: dispidSharingBindingEid

### SHARING_BROWSE_URL {#SHARING-BROWSE-URL}
```
public static final PidLidPropertyDescriptor SHARING_BROWSE_URL
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingBrowseUrl Alternate names: dispidSharingBrowseUrl

### SHARING_CAPABILITIES {#SHARING-CAPABILITIES}
```
public static final PidLidPropertyDescriptor SHARING_CAPABILITIES
```


Indicates that the Message object relates to a special folder. Area: Sharing Canonical name: PidLidSharingCapabilities Alternate names: dispidSharingCaps

### SHARING_CONFIGURATION_URL {#SHARING-CONFIGURATION-URL}
```
public static final PidLidPropertyDescriptor SHARING_CONFIGURATION_URL
```


Contains a zero-length string. Area: Sharing Canonical name: PidLidSharingConfigurationUrl Alternate names: dispidSharingConfigUrl

### SHARING_DATA_RANGE_END {#SHARING-DATA-RANGE-END}
```
public static final PidLidPropertyDescriptor SHARING_DATA_RANGE_END
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingDataRangeEnd Alternate names: dispidSharingDataRangeEnd

### SHARING_DATA_RANGE_START {#SHARING-DATA-RANGE-START}
```
public static final PidLidPropertyDescriptor SHARING_DATA_RANGE_START
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingDataRangeStart Alternate names: dispidSharingDataRangeStart

### SHARING_DETAIL {#SHARING-DETAIL}
```
public static final PidLidPropertyDescriptor SHARING_DETAIL
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingDetail Alternate names: dispidSharingDetail

### SHARING_EXTENSION_XML {#SHARING-EXTENSION-XML}
```
public static final PidLidPropertyDescriptor SHARING_EXTENSION_XML
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingExtensionXml Alternate names: dispidSharingExtXml

### SHARING_FILTER {#SHARING-FILTER}
```
public static final PidLidPropertyDescriptor SHARING_FILTER
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingFilter Alternate names: dispidSharingFilter

### SHARING_FLAGS {#SHARING-FLAGS}
```
public static final PidLidPropertyDescriptor SHARING_FLAGS
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingFlags Alternate names: dispidSharingFlags

### SHARING_FLAVOR {#SHARING-FLAVOR}
```
public static final PidLidPropertyDescriptor SHARING_FLAVOR
```


Indicates the type of Sharing Message object. Area: Sharing Canonical name: PidLidSharingFlavor Alternate names: dispidSharingFlavor

### SHARING_FOLDER_ENTRY_ID {#SHARING-FOLDER-ENTRY-ID}
```
public static final PidLidPropertyDescriptor SHARING_FOLDER_ENTRY_ID
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingFolderEntryId Alternate names: dispidSharingFolderEid

### SHARING_INDEX_ENTRY_ID {#SHARING-INDEX-ENTRY-ID}
```
public static final PidLidPropertyDescriptor SHARING_INDEX_ENTRY_ID
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingIndexEntryId Alternate names: dispidSharingIndexEid

### SHARING_INITIATOR_ENTRY_ID {#SHARING-INITIATOR-ENTRY-ID}
```
public static final PidLidPropertyDescriptor SHARING_INITIATOR_ENTRY_ID
```


Contains the value of the PidTagEntryId property (section 2.674) for the Address Book object of the currently logged-on user. Area: Sharing Canonical name: PidLidSharingInitiatorEntryId Alternate names: dispidSharingInitiatorEid

### SHARING_INITIATOR_NAME {#SHARING-INITIATOR-NAME}
```
public static final PidLidPropertyDescriptor SHARING_INITIATOR_NAME
```


Contains the value of the PidTagDisplayName property (section 2.667) from the Address Book object identified by the PidLidSharingInitiatorEntryId property (section 2.248). Area: Sharing Canonical name: PidLidSharingInitiatorName Alternate names: dispidSharingInitiatorName

### SHARING_INITIATOR_SMTP {#SHARING-INITIATOR-SMTP}
```
public static final PidLidPropertyDescriptor SHARING_INITIATOR_SMTP
```


Contains the value of the PidTagSmtpAddress property (section 2.1010) from the Address Book object identified by the PidLidSharingInitiatorEntryId property (section 2.248). Area: Sharing Canonical name: PidLidSharingInitiatorSmtp Alternate names: dispidSharingInitiatorSmtp

### SHARING_INSTANCE_GUID {#SHARING-INSTANCE-GUID}
```
public static final PidLidPropertyDescriptor SHARING_INSTANCE_GUID
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingInstanceGuid Alternate names: dispidSharingInstanceGuid

### SHARING_LAST_AUTO_SYNC_TIME {#SHARING-LAST-AUTO-SYNC-TIME}
```
public static final PidLidPropertyDescriptor SHARING_LAST_AUTO_SYNC_TIME
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingLastAutoSyncTime Alternate names: dispidSharingLastAutoSync

### SHARING_LAST_SYNC_TIME {#SHARING-LAST-SYNC-TIME}
```
public static final PidLidPropertyDescriptor SHARING_LAST_SYNC_TIME
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingLastSyncTime Alternate names: dispidSharingLastSync

### SHARING_LOCAL_COMMENT {#SHARING-LOCAL-COMMENT}
```
public static final PidLidPropertyDescriptor SHARING_LOCAL_COMMENT
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingLocalComment Alternate names: dispidSharingLocalComment

### SHARING_LOCAL_LAST_MODIFICATION_TIME {#SHARING-LOCAL-LAST-MODIFICATION-TIME}
```
public static final PidLidPropertyDescriptor SHARING_LOCAL_LAST_MODIFICATION_TIME
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingLocalLastModificationTime Alternate names: dispidSharingLocalLastMod

### SHARING_LOCAL_NAME {#SHARING-LOCAL-NAME}
```
public static final PidLidPropertyDescriptor SHARING_LOCAL_NAME
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingLocalName Alternate names: dispidSharingLocalName

### SHARING_LOCAL_PATH {#SHARING-LOCAL-PATH}
```
public static final PidLidPropertyDescriptor SHARING_LOCAL_PATH
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingLocalPath Alternate names: dispidSharingLocalPath

### SHARING_LOCAL_STORE_UID {#SHARING-LOCAL-STORE-UID}
```
public static final PidLidPropertyDescriptor SHARING_LOCAL_STORE_UID
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingLocalStoreUid Alternate names: dispidSharingLocalStoreUid

### SHARING_LOCAL_TYPE {#SHARING-LOCAL-TYPE}
```
public static final PidLidPropertyDescriptor SHARING_LOCAL_TYPE
```


Contains the value of the PidTagContainerClass property (section 2.633) of the folder being shared. Area: Sharing Canonical name: PidLidSharingLocalType Alternate names: dispidSharingLocalType

### SHARING_LOCAL_UID {#SHARING-LOCAL-UID}
```
public static final PidLidPropertyDescriptor SHARING_LOCAL_UID
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingLocalUid Alternate names: dispidSharingLocalUid

### SHARING_ORIGINAL_MESSAGE_ENTRY_ID {#SHARING-ORIGINAL-MESSAGE-ENTRY-ID}
```
public static final PidLidPropertyDescriptor SHARING_ORIGINAL_MESSAGE_ENTRY_ID
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingOriginalMessageEntryId Alternate names: dispidSharingOriginalMessageEid

### SHARING_PARENT_BINDING_ENTRY_ID {#SHARING-PARENT-BINDING-ENTRY-ID}
```
public static final PidLidPropertyDescriptor SHARING_PARENT_BINDING_ENTRY_ID
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingParentBindingEntryId Alternate names: dispidSharingParentBindingEid

### SHARING_PARTICIPANTS {#SHARING-PARTICIPANTS}
```
public static final PidLidPropertyDescriptor SHARING_PARTICIPANTS
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingParticipants Alternate names: dispidSharingParticipants

### SHARING_PERMISSIONS {#SHARING-PERMISSIONS}
```
public static final PidLidPropertyDescriptor SHARING_PERMISSIONS
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingPermissions Alternate names: dispidSharingPermissions

### SHARING_PROVIDER_EXTENSION {#SHARING-PROVIDER-EXTENSION}
```
public static final PidLidPropertyDescriptor SHARING_PROVIDER_EXTENSION
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingProviderExtension Alternate names: dispidSharingProviderExtension

### SHARING_PROVIDER_GUID {#SHARING-PROVIDER-GUID}
```
public static final PidLidPropertyDescriptor SHARING_PROVIDER_GUID
```


Contains the value "%xAE.F0.06.00.00.00.00.00.C0.00.00.00.00.00.00.46". Area: Sharing Canonical name: PidLidSharingProviderGuid Alternate names: dispidSharingProviderGuid

### SHARING_PROVIDER_NAME {#SHARING-PROVIDER-NAME}
```
public static final PidLidPropertyDescriptor SHARING_PROVIDER_NAME
```


Contains a user-displayable name of the sharing provider identified by the PidLidSharingProviderGuid property (section 2.266). Area: Sharing Canonical name: PidLidSharingProviderName Alternate names: dispidSharingProviderName

### SHARING_PROVIDER_URL {#SHARING-PROVIDER-URL}
```
public static final PidLidPropertyDescriptor SHARING_PROVIDER_URL
```


Contains a URL related to the sharing provider identified by the PidLidSharingProviderGuid property (section 2.266). Area: Sharing Canonical name: PidLidSharingProviderUrl Alternate names: dispidSharingProviderUrl

### SHARING_RANGE_END {#SHARING-RANGE-END}
```
public static final PidLidPropertyDescriptor SHARING_RANGE_END
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRangeEnd Alternate names: dispidSharingRangeEnd

### SHARING_RANGE_START {#SHARING-RANGE-START}
```
public static final PidLidPropertyDescriptor SHARING_RANGE_START
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRangeStart Alternate names: dispidSharingRangeStart

### SHARING_RECIPROCATION {#SHARING-RECIPROCATION}
```
public static final PidLidPropertyDescriptor SHARING_RECIPROCATION
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingReciprocation Alternate names: dispidSharingReciprocation

### SHARING_REMOTE_BYTE_SIZE {#SHARING-REMOTE-BYTE-SIZE}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_BYTE_SIZE
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRemoteByteSize Alternate names: dispidSharingRemoteByteSize

### SHARING_REMOTE_COMMENT {#SHARING-REMOTE-COMMENT}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_COMMENT
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRemoteComment Alternate names: dispidSharingRemoteComment

### SHARING_REMOTE_CRC {#SHARING-REMOTE-CRC}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_CRC
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRemoteCrc Alternate names: dispidSharingRemoteCrc

### SHARING_REMOTE_LAST_MODIFICATION_TIME {#SHARING-REMOTE-LAST-MODIFICATION-TIME}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_LAST_MODIFICATION_TIME
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRemoteLastModificationTime Alternate names: dispidSharingRemoteLastMod

### SHARING_REMOTE_MESSAGE_COUNT {#SHARING-REMOTE-MESSAGE-COUNT}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_MESSAGE_COUNT
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRemoteMessageCount Alternate names: dispidSharingRemoteMsgCount

### SHARING_REMOTE_NAME {#SHARING-REMOTE-NAME}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_NAME
```


Contains the value of the PidTagDisplayName property (section 2.667) on the folder being shared. Area: Sharing Canonical name: PidLidSharingRemoteName Alternate names: dispidSharingRemoteName

### SHARING_REMOTE_PASS {#SHARING-REMOTE-PASS}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_PASS
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRemotePass Alternate names: dispidSharingRemotePass

### SHARING_REMOTE_PATH {#SHARING-REMOTE-PATH}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_PATH
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRemotePath Alternate names: dispidSharingRemotePath

### SHARING_REMOTE_STORE_UID {#SHARING-REMOTE-STORE-UID}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_STORE_UID
```


Contains a hexadecimal string representation of the value of the PidTagStoreEntryId property (section 2.1018) on the folder being shared. Area: Sharing Canonical name: PidLidSharingRemoteStoreUid Alternate names: dispidSharingRemoteStoreUid

### SHARING_REMOTE_TYPE {#SHARING-REMOTE-TYPE}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_TYPE
```


Contains the same value as the PidLidSharingLocalType property (section 2.259). Area: Sharing Canonical name: PidLidSharingRemoteType Alternate names: dispidSharingRemoteType

### SHARING_REMOTE_UID {#SHARING-REMOTE-UID}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_UID
```


Contains the EntryID of the folder being shared. Area: Sharing Canonical name: PidLidSharingRemoteUid Alternate names: dispidSharingRemoteUid

### SHARING_REMOTE_USER {#SHARING-REMOTE-USER}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_USER
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRemoteUser Alternate names: dispidSharingRemoteUser

### SHARING_REMOTE_VERSION {#SHARING-REMOTE-VERSION}
```
public static final PidLidPropertyDescriptor SHARING_REMOTE_VERSION
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRemoteVersion Alternate names: dispidSharingRemoteVersion

### SHARING_RESPONSE_TIME {#SHARING-RESPONSE-TIME}
```
public static final PidLidPropertyDescriptor SHARING_RESPONSE_TIME
```


Contains the time at which the recipient of the sharing request sent a sharing response. Area: Sharing Canonical name: PidLidSharingResponseTime Alternate names: dispidSharingResponseTime

### SHARING_RESPONSE_TYPE {#SHARING-RESPONSE-TYPE}
```
public static final PidLidPropertyDescriptor SHARING_RESPONSE_TYPE
```


Contains the type of response with which the recipient of the sharing request responded. Area: Sharing Canonical name: PidLidSharingResponseType Alternate names: dispidSharingResponseType

### SHARING_ROAM_LOG {#SHARING-ROAM-LOG}
```
public static final PidLidPropertyDescriptor SHARING_ROAM_LOG
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingRoamLog Alternate names: dispidSharingRoamLog

### SHARING_START {#SHARING-START}
```
public static final PidLidPropertyDescriptor SHARING_START
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingStart Alternate names: dispidSharingStart

### SHARING_STATUS {#SHARING-STATUS}
```
public static final PidLidPropertyDescriptor SHARING_STATUS
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingStatus Alternate names: dispidSharingStatus

### SHARING_STOP {#SHARING-STOP}
```
public static final PidLidPropertyDescriptor SHARING_STOP
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingStop Alternate names: dispidSharingStop

### SHARING_SYNC_FLAGS {#SHARING-SYNC-FLAGS}
```
public static final PidLidPropertyDescriptor SHARING_SYNC_FLAGS
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingSyncFlags Alternate names: dispidSharingSyncFlags

### SHARING_SYNC_INTERVAL {#SHARING-SYNC-INTERVAL}
```
public static final PidLidPropertyDescriptor SHARING_SYNC_INTERVAL
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingSyncInterval Alternate names: dispidSharingSyncInterval

### SHARING_TIME_TO_LIVE {#SHARING-TIME-TO-LIVE}
```
public static final PidLidPropertyDescriptor SHARING_TIME_TO_LIVE
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingTimeToLive Alternate names: dispidSharingTimeToLive

### SHARING_TIME_TO_LIVE_AUTO {#SHARING-TIME-TO-LIVE-AUTO}
```
public static final PidLidPropertyDescriptor SHARING_TIME_TO_LIVE_AUTO
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingTimeToLiveAuto Alternate names: dispidSharingTimeToLiveAuto

### SHARING_WORKING_HOURS_DAYS {#SHARING-WORKING-HOURS-DAYS}
```
public static final PidLidPropertyDescriptor SHARING_WORKING_HOURS_DAYS
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingWorkingHoursDays Alternate names: dispidSharingWorkingHoursDays

### SHARING_WORKING_HOURS_END {#SHARING-WORKING-HOURS-END}
```
public static final PidLidPropertyDescriptor SHARING_WORKING_HOURS_END
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingWorkingHoursEnd Alternate names: dispidSharingWorkingHoursEnd

### SHARING_WORKING_HOURS_START {#SHARING-WORKING-HOURS-START}
```
public static final PidLidPropertyDescriptor SHARING_WORKING_HOURS_START
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingWorkingHoursStart Alternate names: dispidSharingWorkingHoursStart

### SHARING_WORKING_HOURS_TIME_ZONE {#SHARING-WORKING-HOURS-TIME-ZONE}
```
public static final PidLidPropertyDescriptor SHARING_WORKING_HOURS_TIME_ZONE
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidLidSharingWorkingHoursTimeZone Alternate names: dispidSharingWorkingHoursTZ

### SIDE_EFFECTS {#SIDE-EFFECTS}
```
public static final PidLidPropertyDescriptor SIDE_EFFECTS
```


Specifies how a Message object is handled by the client in relation to certain user interface actions by the user, such as deleting a message. Area: Run-time configuration Canonical name: PidLidSideEffects Alternate names: dispidSideEffects

### SINGLE_BODY_I_CAL {#SINGLE-BODY-I-CAL}
```
public static final PidLidPropertyDescriptor SINGLE_BODY_I_CAL
```


Indicates that the original MIME message contained a single MIME part. Area: Calendar Canonical name: PidLidSingleBodyICal Alternate names: IsSingleBodyICal, dispidIsSingleBodyICal

### SLIDE_COUNT {#SLIDE-COUNT}
```
public static final PidNamePropertyDescriptor SLIDE_COUNT
```


Specifies the number of slides in the file attached to the Document object. Area: Common Canonical name: PidNameSlideCount Alternate names: urn:schemas-microsoft-com:office:office\#Slides

### SMART_NO_ATTACH {#SMART-NO-ATTACH}
```
public static final PidLidPropertyDescriptor SMART_NO_ATTACH
```


Indicates whether the Message object has no end-user visible attachments. Area: Run-time configuration Canonical name: PidLidSmartNoAttach Alternate names: dispidSmartNoAttach

### SMTP_ADDRESS {#SMTP-ADDRESS}
```
public static final PidTagPropertyDescriptor SMTP_ADDRESS
```


Contains the SMTP address of the Message object. Area: Address Properties Canonical name: PidTagSmtpAddress Alternate names: PR\_SMTP\_ADDRESS, PR\_SMTP\_ADDRESS\_A, PR\_SMTP\_ADDRESS\_W

### SORT_LOCALE_ID {#SORT-LOCALE-ID}
```
public static final PidTagPropertyDescriptor SORT_LOCALE_ID
```


Contains the locale identifier. Area: ExchangeAdministrative Canonical name: PidTagSortLocaleId Alternate names: PR\_SORT\_LOCALE\_ID, ptagSortLocaleId

### SOURCE_KEY {#SOURCE-KEY}
```
public static final PidTagPropertyDescriptor SOURCE_KEY
```


Contains a value that contains an internal global identifier (GID) for this folder or message. Area: Sync Canonical name: PidTagSourceKey Alternate names: PR\_SOURCE\_KEY

### SPAM_ORIGINAL_FOLDER {#SPAM-ORIGINAL-FOLDER}
```
public static final PidLidPropertyDescriptor SPAM_ORIGINAL_FOLDER
```


Specifies which folder a message was in before it was filtered into the Junk Email folder. Area: Spam Canonical name: PidLidSpamOriginalFolder Alternate names: dispidSpamOriginalFolder

### SPOKEN_NAME {#SPOKEN-NAME}
```
public static final PidTagPropertyDescriptor SPOKEN_NAME
```


Contains a recording of the mail user's name pronunciation. Area: Address Book Canonical name: PidTagSpokenName Alternate names: PR\_EMS\_AB\_UM\_SPOKEN\_NAME

### SPOOLER_STATUS {#SPOOLER-STATUS}
```
public static final PidTagPropertyDescriptor SPOOLER_STATUS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SPOOLER\_STATUS

### SPOUSE_NAME {#SPOUSE-NAME}
```
public static final PidTagPropertyDescriptor SPOUSE_NAME
```


Contains the name of the mail user's spouse/partner. Area: MapiMailUser Canonical name: PidTagSpouseName Alternate names: PR\_SPOUSE\_NAME, PR\_SPOUSE\_NAME\_A, PR\_SPOUSE\_NAME\_W,

### START_DATE {#START-DATE}
```
public static final PidTagPropertyDescriptor START_DATE
```


Contains the value of the PidLidAppointmentStartWhole property (section 2.29). Area: MapiEnvelope Canonical name: PidTagStartDate Alternate names: PR\_START\_DATE, http://schemas.microsoft.com/mapi/start\_date

### START_DATE_ETC {#START-DATE-ETC}
```
public static final PidTagPropertyDescriptor START_DATE_ETC
```


Contains the default retention period, and the start date from which the age of a Message object is calculated. Area: Archive Canonical name: PidTagStartDateEtc Alternate names: PR\_START\_DATE\_ETC, ptagStartDateEtc

### START_RECURRENCE_DATE {#START-RECURRENCE-DATE}
```
public static final PidLidPropertyDescriptor START_RECURRENCE_DATE
```


Identifies the start date of the recurrence pattern. Area: Meetings Canonical name: PidLidStartRecurrenceDate Alternate names: LID\_START\_RECUR\_DATE

### START_RECURRENCE_TIME {#START-RECURRENCE-TIME}
```
public static final PidLidPropertyDescriptor START_RECURRENCE_TIME
```


Identifies the start time of the recurrence pattern. Area: Meetings Canonical name: PidLidStartRecurrenceTime Alternate names: LID\_START\_RECUR\_TIME

### STATE_OR_PROVINCE {#STATE-OR-PROVINCE}
```
public static final PidTagPropertyDescriptor STATE_OR_PROVINCE
```


Contains the name of the mail user's state or province. Area: MapiMailUser Canonical name: PidTagStateOrProvince Alternate names: PR\_STATE\_OR\_PROVINCE, PR\_STATE\_OR\_PROVINCE\_A, PR\_BUSINESS\_ADDRESS\_STATE\_OR\_PROVINCE\_A,

### STATUS {#STATUS}
```
public static final PidTagPropertyDescriptor STATUS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_STATUS

### STATUS_CODE {#STATUS-CODE}
```
public static final PidTagPropertyDescriptor STATUS_CODE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_STATUS\_CODE

### STATUS_STRING {#STATUS-STRING}
```
public static final PidTagPropertyDescriptor STATUS_STRING
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_STATUS\_STRING

### STORAGE_LIMIT_INFORMATION {#STORAGE-LIMIT-INFORMATION}
```
public static final PidTagPropertyDescriptor STORAGE_LIMIT_INFORMATION
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_STORAGE\_LIMIT\_INFORMATION

### STORAGE_QUOTA_LIMIT {#STORAGE-QUOTA-LIMIT}
```
public static final PidTagPropertyDescriptor STORAGE_QUOTA_LIMIT
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_STORAGE\_QUOTA\_LIMIT

### STORE_ENTRY_ID {#STORE-ENTRY-ID}
```
public static final PidTagPropertyDescriptor STORE_ENTRY_ID
```


Contains the unique EntryID of the message store where an object resides. Area: ID Properties Canonical name: PidTagStoreEntryId Alternate names: PR\_STORE\_ENTRYID, ptagStoreEntryId

### STORE_OFFLINE {#STORE-OFFLINE}
```
public static final PidTagPropertyDescriptor STORE_OFFLINE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_STORE\_OFFLINE

### STORE_PROVIDERS {#STORE-PROVIDERS}
```
public static final PidTagPropertyDescriptor STORE_PROVIDERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_STORE\_PROVIDERS

### STORE_RECORD_KEY {#STORE-RECORD-KEY}
```
public static final PidTagPropertyDescriptor STORE_RECORD_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_STORE\_RECORD\_KEY

### STORE_SLOWLINK {#STORE-SLOWLINK}
```
public static final PidTagPropertyDescriptor STORE_SLOWLINK
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_STORE\_SLOWLINK

### STORE_STATE {#STORE-STATE}
```
public static final PidTagPropertyDescriptor STORE_STATE
```


Indicates whether a mailbox has any active Search folders. Area: MapiMessageStore Canonical name: PidTagStoreState Alternate names: PR\_STORE\_STATE

### STORE_SUPPORT_MASK {#STORE-SUPPORT-MASK}
```
public static final PidTagPropertyDescriptor STORE_SUPPORT_MASK
```


Indicates whether string properties within the .msg file are Unicode-encoded. Area: Miscellaneous Properties Canonical name: PidTagStoreSupportMask Alternate names: PR\_STORE\_SUPPORT\_MASK, ptagStoreSupportMask

### STREET_ADDRESS {#STREET-ADDRESS}
```
public static final PidTagPropertyDescriptor STREET_ADDRESS
```


Contains the mail user's street address. Area: MapiMailUser Canonical name: PidTagStreetAddress Alternate names: PR\_STREET\_ADDRESS, PR\_STREET\_ADDRESS\_A, PR\_STREET\_ADDRESS\_W, PR\_BUSINESS\_ADDRESS\_STREET, PR\_BUSINESS\_ADDRESS\_STREET\_A,

### SUBFOLDERS {#SUBFOLDERS}
```
public static final PidTagPropertyDescriptor SUBFOLDERS
```


Specifies whether a folder has subfolders. Area: MapiContainer Canonical name: PidTagSubfolders Alternate names: PR\_SUBFOLDERS, ptagSubFolders, DAV:hassubs

### SUBJECT {#SUBJECT}
```
public static final PidNamePropertyDescriptor SUBJECT
```


Specifies the subject of the file attached to the Document object. Area: Common Canonical name: PidNameSubject Alternate names: urn:schemas-microsoft-com:office:office\#Subject

### SUBJECT_IPM {#SUBJECT-IPM}
```
public static final PidTagPropertyDescriptor SUBJECT_IPM
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SUBJECT\_IPM

### SUBJECT_PREFIX {#SUBJECT-PREFIX}
```
public static final PidTagPropertyDescriptor SUBJECT_PREFIX
```


Contains the prefix for the subject of the message. Area: General Message Properties Canonical name: PidTagSubjectPrefix Alternate names: PR\_SUBJECT\_PREFIX, PR\_SUBJECT\_PREFIX\_A, ptagSubjectPrefix, PR\_SUBJECT\_PREFIX\_W

### SUBJECT_TRACE_INFO {#SUBJECT-TRACE-INFO}
```
public static final PidTagPropertyDescriptor SUBJECT_TRACE_INFO
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SUBJECT\_TRACE\_INFO

### SUBMIT_FLAGS {#SUBMIT-FLAGS}
```
public static final PidTagPropertyDescriptor SUBMIT_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SUBMIT\_FLAGS

### SUPERSEDES {#SUPERSEDES}
```
public static final PidTagPropertyDescriptor SUPERSEDES
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SUPERSEDES

### SUPPLEMENTARY_INFO {#SUPPLEMENTARY-INFO}
```
public static final PidTagPropertyDescriptor SUPPLEMENTARY_INFO
```


Contains supplementary information about a delivery status notification, as specified in [RFC3464]. Area: Email Canonical name: PidTagSupplementaryInfo Alternate names: PR\_SUPPLEMENTARY\_INFO, ptagSupplementaryInfo

### SURNAME {#SURNAME}
```
public static final PidTagPropertyDescriptor SURNAME
```


Contains the mail user's family name. Area: MapiMailUser Canonical name: PidTagSurname Alternate names: PR\_SURNAME, PR\_SURNAME\_A, PR\_SURNAME\_W, urn:schemas:contacts:sn

### SVR_GENERATING_QUOTA_MSG {#SVR-GENERATING-QUOTA-MSG}
```
public static final PidTagPropertyDescriptor SVR_GENERATING_QUOTA_MSG
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SVR\_GENERATING\_QUOTA\_MSG

### SWAPPED_TO_DO_DATA {#SWAPPED-TO-DO-DATA}
```
public static final PidTagPropertyDescriptor SWAPPED_TO_DO_DATA
```


Contains a secondary storage location for flags when sender flags or sender reminders are supported. Area: MapiNonTransmittable Canonical name: PidTagSwappedToDoData Alternate names: PR\_SWAPPED\_TODO\_DATA, ptagSwappedTodoData

### SWAPPED_TO_DO_STORE {#SWAPPED-TO-DO-STORE}
```
public static final PidTagPropertyDescriptor SWAPPED_TO_DO_STORE
```


Contains the value of the PidTagStoreEntryId property (section 2.1018) of the message when the value of the PidTagSwappedToDoData property (section 2.1027) is set. Area: MapiNonTransmittable Canonical name: PidTagSwappedToDoStore Alternate names: PR\_SWAPPED\_TODO\_STORE, ptagSwappedTodoStore

### SYNCHRONIZE_FLAGS {#SYNCHRONIZE-FLAGS}
```
public static final PidTagPropertyDescriptor SYNCHRONIZE_FLAGS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SYNCHRONIZE\_FLAGS

### SYS_CONFIG_FOLDER_ENTRYID {#SYS-CONFIG-FOLDER-ENTRYID}
```
public static final PidTagPropertyDescriptor SYS_CONFIG_FOLDER_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_SYS\_CONFIG\_FOLDER\_ENTRYID

### TAG_EXCEPTION_REPLACE_TIME {#TAG-EXCEPTION-REPLACE-TIME}
```
public static final PidTagPropertyDescriptor TAG_EXCEPTION_REPLACE_TIME
```


Indicates the original date and time, in UTC, at which the instance in the recurrence pattern would have occurred if it were not an exception. Area: MessageClassDefinedNonTransmittable Canonical name: PidTagExceptionReplaceTime Alternate names: PR\_EXCEPTION\_REPLACETIME

### TAG_HTML {#TAG-HTML}
```
public static final PidTagPropertyDescriptor TAG_HTML
```


Contains message body text in HTML format. Area: General Message Properties Canonical name: PidTagHtml Alternate names: PR\_HTML, ptagHtml

### TAG_LOCATION {#TAG-LOCATION}
```
public static final PidTagPropertyDescriptor TAG_LOCATION
```


Contains the location of the mail user. Area: Address Properties Canonical name: PidTagLocation Alternate names: PR\_LOCATION, PR\_LOCATION\_A, PR\_LOCATION\_W,

### TAG_SUBJECT {#TAG-SUBJECT}
```
public static final PidTagPropertyDescriptor TAG_SUBJECT
```


Contains the subject of the email message. Area: General Message Properties Canonical name: PidTagSubject Alternate names: PR\_SUBJECT, PR\_SUBJECT\_A, ptagSubject, PR\_SUBJECT\_W,

### TAG_TITLE {#TAG-TITLE}
```
public static final PidTagPropertyDescriptor TAG_TITLE
```


Contains the mail user's job title. Area: MapiMailUser Canonical name: PidTagTitle Alternate names: PR\_TITLE, PR\_TITLE\_A, PR\_TITLE\_W, urn:schemas:contacts:title

### TARGET_ENTRY_ID {#TARGET-ENTRY-ID}
```
public static final PidTagPropertyDescriptor TARGET_ENTRY_ID
```


Contains the message ID of a Message object being submitted for optimization ([MS- OXOMSG] section 3.2.4.4). Area: ID Properties Canonical name: PidTagTargetEntryId Alternate names: PR\_TARGET\_ENTRYID, ptagTargetEntryId

### TASK_ACCEPTANCE_STATE {#TASK-ACCEPTANCE-STATE}
```
public static final PidLidPropertyDescriptor TASK_ACCEPTANCE_STATE
```


Indicates the acceptance state of the task. Area: Tasks Canonical name: PidLidTaskAcceptanceState Alternate names: dispidTaskDelegValue

### TASK_ACCEPTED {#TASK-ACCEPTED}
```
public static final PidLidPropertyDescriptor TASK_ACCEPTED
```


Indicates whether a task assignee has replied to a task request for this Task object. Area: Tasks Canonical name: PidLidTaskAccepted Alternate names: dispidTaskAccepted

### TASK_ACTUAL_EFFORT {#TASK-ACTUAL-EFFORT}
```
public static final PidLidPropertyDescriptor TASK_ACTUAL_EFFORT
```


Indicates the number of minutes that the user actually spent working on a task. Area: Tasks Canonical name: PidLidTaskActualEffort Alternate names: dispidTaskActualEffort

### TASK_ASSIGNER {#TASK-ASSIGNER}
```
public static final PidLidPropertyDescriptor TASK_ASSIGNER
```


Specifies the name of the user that last assigned the task. Area: Tasks Canonical name: PidLidTaskAssigner Alternate names: dispidTaskDelegator

### TASK_ASSIGNERS {#TASK-ASSIGNERS}
```
public static final PidLidPropertyDescriptor TASK_ASSIGNERS
```


Contains a stack of entries, each of which represents a task assigner. Area: Tasks Canonical name: PidLidTaskAssigners Alternate names: dispidTaskMyDelegators

### TASK_COMPLETE {#TASK-COMPLETE}
```
public static final PidLidPropertyDescriptor TASK_COMPLETE
```


Indicates that the task is complete. Area: Tasks Canonical name: PidLidTaskComplete Alternate names: dispidTaskComplete

### TASK_CUSTOM_FLAGS {#TASK-CUSTOM-FLAGS}
```
public static final PidLidPropertyDescriptor TASK_CUSTOM_FLAGS
```


The client can set this property, but it has no impact on the Task-Related Objects Protocol and is ignored by the server. Area: Tasks Canonical name: PidLidTaskCustomFlags Alternate names: dispidTaskCustomFlags

### TASK_DATE_COMPLETED {#TASK-DATE-COMPLETED}
```
public static final PidLidPropertyDescriptor TASK_DATE_COMPLETED
```


Specifies the date when the user completed work on the task. Area: Tasks Canonical name: PidLidTaskDateCompleted Alternate names: dispidTaskDateCompleted

### TASK_DEAD_OCCURRENCE {#TASK-DEAD-OCCURRENCE}
```
public static final PidLidPropertyDescriptor TASK_DEAD_OCCURRENCE
```


Indicates whether new occurrences remain to be generated. Area: Tasks Canonical name: PidLidTaskDeadOccurrence Alternate names: dispidTaskDeadOccur

### TASK_DUE_DATE {#TASK-DUE-DATE}
```
public static final PidLidPropertyDescriptor TASK_DUE_DATE
```


Specifies the date by which the user expects work on the task to be complete. Area: Tasks Canonical name: PidLidTaskDueDate Alternate names: dispidTaskDueDate

### TASK_ESTIMATED_EFFORT {#TASK-ESTIMATED-EFFORT}
```
public static final PidLidPropertyDescriptor TASK_ESTIMATED_EFFORT
```


Indicates the number of minutes that the user expects to work on a task. Area: Tasks Canonical name: PidLidTaskEstimatedEffort Alternate names: dispidTaskEstimatedEffort

### TASK_F_CREATOR {#TASK-F-CREATOR}
```
public static final PidLidPropertyDescriptor TASK_F_CREATOR
```


Indicates that the Task object was originally created by the action of the current user or user agent instead of by the processing of a task request. Area: Tasks Canonical name: PidLidTaskFCreator Alternate names: dispidTaskFCreator

### TASK_F_FIX_OFFLINE {#TASK-F-FIX-OFFLINE}
```
public static final PidLidPropertyDescriptor TASK_F_FIX_OFFLINE
```


Indicates the accuracy of the PidLidTaskOwner property (section 2.328). Area: Tasks Canonical name: PidLidTaskFFixOffline Alternate names: dispidTaskFFixOffline

### TASK_F_RECURRING {#TASK-F-RECURRING}
```
public static final PidLidPropertyDescriptor TASK_F_RECURRING
```


Indicates whether the task includes a recurrence pattern. Area: Tasks Canonical name: PidLidTaskFRecurring Alternate names: dispidTaskFRecur

### TASK_GLOBAL_ID {#TASK-GLOBAL-ID}
```
public static final PidLidPropertyDescriptor TASK_GLOBAL_ID
```


Contains a unique GUID for this task, which is used to locate an existing task upon receipt of a task response or task update. Area: Tasks Canonical name: PidLidTaskGlobalId Alternate names: dispidTaskGlobalObjId

### TASK_HISTORY {#TASK-HISTORY}
```
public static final PidLidPropertyDescriptor TASK_HISTORY
```


Indicates the type of change that was last made to the Task object. Area: Tasks Canonical name: PidLidTaskHistory Alternate names: dispidTaskHistory

### TASK_LAST_DELEGATE {#TASK-LAST-DELEGATE}
```
public static final PidLidPropertyDescriptor TASK_LAST_DELEGATE
```


Contains the name of the user who most recently assigned the task, or the user to whom it was most recently assigned. Area: Tasks Canonical name: PidLidTaskLastDelegate Alternate names: dispidTaskLastDelegate

### TASK_LAST_UPDATE {#TASK-LAST-UPDATE}
```
public static final PidLidPropertyDescriptor TASK_LAST_UPDATE
```


Contains the date and time of the most recent change made to the Task object. Area: Tasks Canonical name: PidLidTaskLastUpdate Alternate names: dispidTaskLastUpdate

### TASK_LAST_USER {#TASK-LAST-USER}
```
public static final PidLidPropertyDescriptor TASK_LAST_USER
```


Contains the name of the most recent user to have been the owner of the task. Area: Tasks Canonical name: PidLidTaskLastUser Alternate names: dispidTaskLastUser

### TASK_MODE {#TASK-MODE}
```
public static final PidLidPropertyDescriptor TASK_MODE
```


Specifies the assignment status of the embedded Task object. Area: Tasks Canonical name: PidLidTaskMode Alternate names: dispidTaskMode

### TASK_MULTIPLE_RECIPIENTS {#TASK-MULTIPLE-RECIPIENTS}
```
public static final PidLidPropertyDescriptor TASK_MULTIPLE_RECIPIENTS
```


Provides optimization hints about the recipients of a Task object. Area: Tasks Canonical name: PidLidTaskMultipleRecipients Alternate names: dispidTaskMultRecips

### TASK_NO_COMPUTE {#TASK-NO-COMPUTE}
```
public static final PidLidPropertyDescriptor TASK_NO_COMPUTE
```


Not used. The client can set this property, but it has no impact on the Task-Related Objects Protocol and is ignored by the server. Area: Tasks Canonical name: PidLidTaskNoCompute Alternate names: dispidTaskNoCompute

### TASK_ORDINAL {#TASK-ORDINAL}
```
public static final PidLidPropertyDescriptor TASK_ORDINAL
```


Provides an aid to custom sorting of Task objects. Area: Tasks Canonical name: PidLidTaskOrdinal Alternate names: dispidTaskOrdinal

### TASK_OWNER {#TASK-OWNER}
```
public static final PidLidPropertyDescriptor TASK_OWNER
```


Contains the name of the owner of the task. Area: Tasks Canonical name: PidLidTaskOwner Alternate names: dispidTaskOwner

### TASK_OWNERSHIP {#TASK-OWNERSHIP}
```
public static final PidLidPropertyDescriptor TASK_OWNERSHIP
```


Indicates the role of the current user relative to the Task object. Area: Tasks Canonical name: PidLidTaskOwnership Alternate names: dispidTaskOwnership

### TASK_RECURRENCE {#TASK-RECURRENCE}
```
public static final PidLidPropertyDescriptor TASK_RECURRENCE
```


Contains a RecurrencePattern structure that provides information about recurring tasks. Area: Tasks Canonical name: PidLidTaskRecurrence Alternate names: dispidTaskRecur

### TASK_RESET_REMINDER {#TASK-RESET-REMINDER}
```
public static final PidLidPropertyDescriptor TASK_RESET_REMINDER
```


Indicates whether future instances of recurring tasks need reminders, even though the value of the PidLidReminderSet property (section 2.222) is 0x00. Area: Tasks Canonical name: PidLidTaskResetReminder Alternate names: dispidTaskResetReminder

### TASK_ROLE {#TASK-ROLE}
```
public static final PidLidPropertyDescriptor TASK_ROLE
```


Not used. The client can set this property, but it has no impact on the Task-Related Objects Protocol and is ignored by the server. Area: Tasks Canonical name: PidLidTaskRole Alternate names: dispidTaskRole

### TASK_START_DATE {#TASK-START-DATE}
```
public static final PidLidPropertyDescriptor TASK_START_DATE
```


Specifies the date on which the user expects work on the task to begin. Area: Tasks Canonical name: PidLidTaskStartDate Alternate names: dispidTaskStartDate

### TASK_STATE {#TASK-STATE}
```
public static final PidLidPropertyDescriptor TASK_STATE
```


Indicates the current assignment state of the Task object. Area: Tasks Canonical name: PidLidTaskState Alternate names: dispidTaskState

### TASK_STATUS {#TASK-STATUS}
```
public static final PidLidPropertyDescriptor TASK_STATUS
```


Specifies the status of a task. Area: Tasks Canonical name: PidLidTaskStatus Alternate names: dispidTaskStatus

### TASK_STATUS_ON_COMPLETE {#TASK-STATUS-ON-COMPLETE}
```
public static final PidLidPropertyDescriptor TASK_STATUS_ON_COMPLETE
```


Indicates whether the task assignee has been requested to send an email message update upon completion of the assigned task. Area: Tasks Canonical name: PidLidTaskStatusOnComplete Alternate names: dispidTaskSOC

### TASK_UPDATES {#TASK-UPDATES}
```
public static final PidLidPropertyDescriptor TASK_UPDATES
```


Indicates whether the task assignee has been requested to send a task update when the assigned Task object changes. Area: Tasks Canonical name: PidLidTaskUpdates Alternate names: dispidTaskUpdates

### TASK_VERSION {#TASK-VERSION}
```
public static final PidLidPropertyDescriptor TASK_VERSION
```


Indicates which copy is the latest update of a Task object. Area: Tasks Canonical name: PidLidTaskVersion Alternate names: dispidTaskVersion

### TEAM_TASK {#TEAM-TASK}
```
public static final PidLidPropertyDescriptor TEAM_TASK
```


This property is set by the client but is ignored by the server. Area: Tasks Canonical name: PidLidTeamTask Alternate names: dispidTeamTask

### TELECOMMUNICATIONS_DEVICE_FOR_DEAF_TELEPHONE_NUMBER {#TELECOMMUNICATIONS-DEVICE-FOR-DEAF-TELEPHONE-NUMBER}
```
public static final PidTagPropertyDescriptor TELECOMMUNICATIONS_DEVICE_FOR_DEAF_TELEPHONE_NUMBER
```


Contains the mail user's telecommunication device for the deaf (TTY/TDD) telephone number. Area: MapiMailUser Canonical name: PidTagTelecommunicationsDeviceForDeafTelephoneNumber Alternate names: PR\_TTYTDD\_PHONE\_NUMBER, PR\_TTYTDD\_PHONE\_NUMBER\_A,

### TELEX_NUMBER {#TELEX-NUMBER}
```
public static final PidTagPropertyDescriptor TELEX_NUMBER
```


Contains the mail user's telex number. This property is returned from an NSPI server as a PtypMultipleBinary. Otherwise, the data type is PtypString. Area: MapiMailUser Canonical name: PidTagTelexNumber Alternate names: PR\_TELEX\_NUMBER, PR\_TELEX\_NUMBER\_A, PR\_TELEX\_NUMBER\_W,

### TEMPLATE {#TEMPLATE}
```
public static final PidNamePropertyDescriptor TEMPLATE
```


Specifies the template of the file attached to the Document object. Area: Common Canonical name: PidNameTemplate Alternate names: urn:schemas-microsoft-com:office:office\#Template

### TEMPLATEID {#TEMPLATEID}
```
public static final PidTagPropertyDescriptor TEMPLATEID
```


Contains the value of the PidTagEntryId property (section 2.674), expressed as a Permanent Entry ID format. Area: MapiAddressBook Canonical name: PidTagTemplateid Alternate names: PR\_TEMPLATEID

### TEMPLATE_DATA {#TEMPLATE-DATA}
```
public static final PidTagPropertyDescriptor TEMPLATE_DATA
```


Describes the controls used in the template that is used to retrieve address book information. Area: Address Book Canonical name: PidTagTemplateData Alternate names: PR\_EMS\_TEMPLATE\_BLOB

### TEST_LINE_SPEED {#TEST-LINE-SPEED}
```
public static final PidTagPropertyDescriptor TEST_LINE_SPEED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_TEST\_LINE\_SPEED

### TEXT_ATTACHMENT_CHARSET {#TEXT-ATTACHMENT-CHARSET}
```
public static final PidTagPropertyDescriptor TEXT_ATTACHMENT_CHARSET
```


Specifies the character set of an attachment received via MIME with the content-type of text. Area: Message Attachment Properties Canonical name: PidTagTextAttachmentCharset Alternate names: ptagTextAttachmentCharset

### THUMBNAIL {#THUMBNAIL}
```
public static final PidNamePropertyDescriptor THUMBNAIL
```


Specifies the data representing the thumbnail image of the document. Area: Common Canonical name: PidNameThumbnail Alternate names: urn:schemas-microsoft-com:office:office\#ThumbNail

### THUMBNAIL_PHOTO {#THUMBNAIL-PHOTO}
```
public static final PidTagPropertyDescriptor THUMBNAIL_PHOTO
```


Contains the mail user's photo in .jpg format. Area: Address Book Canonical name: PidTagThumbnailPhoto Alternate names: PR\_EMS\_AB\_THUMBNAIL\_PHOTO

### TIME_ZONE {#TIME-ZONE}
```
public static final PidLidPropertyDescriptor TIME_ZONE
```


Specifies information about the time zone of a recurring meeting. Area: Meetings Canonical name: PidLidTimeZone Alternate names: LID\_TIME\_ZONE

### TIME_ZONE_DESCRIPTION {#TIME-ZONE-DESCRIPTION}
```
public static final PidLidPropertyDescriptor TIME_ZONE_DESCRIPTION
```


Specifies a human-readable description of the time zone that is represented by the data in the PidLidTimeZoneStruct property (section 2.342). Area: Calendar Canonical name: PidLidTimeZoneDescription Alternate names: dispidTimeZoneDesc

### TIME_ZONE_STRUCT {#TIME-ZONE-STRUCT}
```
public static final PidLidPropertyDescriptor TIME_ZONE_STRUCT
```


Specifies time zone information for a recurring meeting. Area: Calendar Canonical name: PidLidTimeZoneStruct Alternate names: dispidTimeZoneStruct

### TITLE {#TITLE}
```
public static final PidNamePropertyDescriptor TITLE
```


Specifies the title of the file attached to the Document object. Area: Common Canonical name: PidNameTitle Alternate names: urn:schemas-microsoft-com:office:office\#Title

### TNEF_CORRELATION_KEY {#TNEF-CORRELATION-KEY}
```
public static final PidTagPropertyDescriptor TNEF_CORRELATION_KEY
```


Contains a value that correlates a Transport Neutral Encapsulation Format (TNEF) attachment with a message. Area: MapiEnvelope Canonical name: PidTagTnefCorrelationKey Alternate names: PR\_TNEF\_CORRELATION\_KEY

### TO_ATTENDEES_STRING {#TO-ATTENDEES-STRING}
```
public static final PidLidPropertyDescriptor TO_ATTENDEES_STRING
```


Contains a list of all of the sendable attendees who are also required attendees. Area: Meetings Canonical name: PidLidToAttendeesString Alternate names: dispidToAttendeesString

### TO_DO_ITEM_FLAGS {#TO-DO-ITEM-FLAGS}
```
public static final PidTagPropertyDescriptor TO_DO_ITEM_FLAGS
```


Contains flags associated with objects. Area: MapiNonTransmittable Canonical name: PidTagToDoItemFlags Alternate names: PR\_TODO\_ITEM\_FLAGS, ptagToDoItemFlags

### TO_DO_ORDINAL_DATE {#TO-DO-ORDINAL-DATE}
```
public static final PidLidPropertyDescriptor TO_DO_ORDINAL_DATE
```


Contains the current time, in UTC, which is used to determine the sort order of objects in a consolidated to-do list. Area: Tasks Canonical name: PidLidToDoOrdinalDate Alternate names: dispidToDoOrdinalDate

### TO_DO_SUB_ORDINAL {#TO-DO-SUB-ORDINAL}
```
public static final PidLidPropertyDescriptor TO_DO_SUB_ORDINAL
```


Contains the numerals 0 through 9 that are used to break a tie when the PidLidToDoOrdinalDate property (section 2.344) is used to perform a sort of objects. Area: Tasks Canonical name: PidLidToDoSubOrdinal Alternate names: dispidToDoSubOrdinal

### TO_DO_TITLE {#TO-DO-TITLE}
```
public static final PidLidPropertyDescriptor TO_DO_TITLE
```


Contains user-specifiable text to identify this Message object in a consolidated to-do list. Area: Tasks Canonical name: PidLidToDoTitle Alternate names: dispidToDoTitle

### TRACE_INFO {#TRACE-INFO}
```
public static final PidTagPropertyDescriptor TRACE_INFO
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_TRACE\_INFO

### TRANSFER_ENABLED {#TRANSFER-ENABLED}
```
public static final PidTagPropertyDescriptor TRANSFER_ENABLED
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_TRANSFER\_ENABLED

### TRANSMITTABLE_DISPLAY_NAME {#TRANSMITTABLE-DISPLAY-NAME}
```
public static final PidTagPropertyDescriptor TRANSMITTABLE_DISPLAY_NAME
```


Contains an Address Book object's display name that is transmitted with the message. Area: Address Properties Canonical name: PidTagTransmittableDisplayName Alternate names: PR\_TRANSMITABLE\_DISPLAY\_NAME, PR\_TRANSMITABLE\_DISPLAY\_NAME\_A, ptagTransmitableDisplayName, PR\_TRANSMITABLE\_DISPLAY\_NAME\_W

### TRANSPORT_KEY {#TRANSPORT-KEY}
```
public static final PidTagPropertyDescriptor TRANSPORT_KEY
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_TRANSPORT\_KEY

### TRANSPORT_MESSAGE_HEADERS {#TRANSPORT-MESSAGE-HEADERS}
```
public static final PidTagPropertyDescriptor TRANSPORT_MESSAGE_HEADERS
```


Contains transport-specific message envelope information for email. Area: Email Canonical name: PidTagTransportMessageHeaders Alternate names: PR\_TRANSPORT\_MESSAGE\_HEADERS, PR\_TRANSPORT\_MESSAGE\_HEADERS\_A, PR\_TRANSPORT\_MESSAGE\_HEADERS\_W

### TRANSPORT_PROVIDERS {#TRANSPORT-PROVIDERS}
```
public static final PidTagPropertyDescriptor TRANSPORT_PROVIDERS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_TRANSPORT\_PROVIDERS

### TRANSPORT_STATUS {#TRANSPORT-STATUS}
```
public static final PidTagPropertyDescriptor TRANSPORT_STATUS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_TRANSPORT\_STATUS

### TRUST_SENDER {#TRUST-SENDER}
```
public static final PidTagPropertyDescriptor TRUST_SENDER
```


Specifies whether the associated message was delivered through a trusted transport channel. Area: MapiNonTransmittable Canonical name: PidTagTrustSender Alternate names: PR\_TRUST\_SENDER, ptagTrustSender

### TYPE_OF_MTS_USER {#TYPE-OF-MTS-USER}
```
public static final PidTagPropertyDescriptor TYPE_OF_MTS_USER
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_TYPE\_OF\_MTS\_USER

### USER_CERTIFICATE {#USER-CERTIFICATE}
```
public static final PidTagPropertyDescriptor USER_CERTIFICATE
```


Contains an ASN.1 authentication certificate for a messaging user. Area: MapiMailUser Canonical name: PidTagUserCertificate Alternate names: PR\_USER\_CERTIFICATE, ptagUserCertificate, urn:schemas:contacts:usercertificate

### USER_ENTRY_ID {#USER-ENTRY-ID}
```
public static final PidTagPropertyDescriptor USER_ENTRY_ID
```


Address book EntryID of the user logged on to the public folders. Area: ExchangeMessageStore Canonical name: PidTagUserEntryId Alternate names: PR\_USER\_ENTRYID, ptagUserEntryId

### USER_NAME {#USER-NAME}
```
public static final PidTagPropertyDescriptor USER_NAME
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_USER\_NAME

### USER_X_509_CERTIFICATE {#USER-X-509-CERTIFICATE}
```
public static final PidTagPropertyDescriptor USER_X_509_CERTIFICATE
```


Contains a list of certificates for the mail user. Area: MapiMailUser Canonical name: PidTagUserX509Certificate Alternate names: PR\_USER\_X509\_CERTIFICATE

### USE_TNEF {#USE-TNEF}
```
public static final PidLidPropertyDescriptor USE_TNEF
```


Specifies whether Transport Neutral Encapsulation Format (TNEF) is to be included on a message when the message is converted from TNEF to MIME or SMTP format. Area: Run-time configuration Canonical name: PidLidUseTnef Alternate names: dispidUseTNEF

### VALID_FLAG_STRING_PROOF {#VALID-FLAG-STRING-PROOF}
```
public static final PidLidPropertyDescriptor VALID_FLAG_STRING_PROOF
```


Contains the value of the PidTagMessageDeliveryTime property (section 2.780) when modifying the PidLidFlagRequest property (section 2.136). Area: Tasks Canonical name: PidLidValidFlagStringProof Alternate names: dispidValidFlagStringProof

### VALID_FOLDER_MASK {#VALID-FOLDER-MASK}
```
public static final PidTagPropertyDescriptor VALID_FOLDER_MASK
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_VALID\_FOLDER\_MASK

### VERB_RESPONSE {#VERB-RESPONSE}
```
public static final PidLidPropertyDescriptor VERB_RESPONSE
```


Specifies the voting option that a respondent has selected. Area: General Message Properties Canonical name: PidLidVerbResponse Alternate names: dispidVerbResponse

### VERB_STREAM {#VERB-STREAM}
```
public static final PidLidPropertyDescriptor VERB_STREAM
```


Specifies what voting responses the user can make in response to the message. Area: Run-time configuration Canonical name: PidLidVerbStream Alternate names: dispidVerbStream

### VIEWS_ENTRYID {#VIEWS-ENTRYID}
```
public static final PidTagPropertyDescriptor VIEWS_ENTRYID
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_VIEWS\_ENTRYID

### VIEW_DESCRIPTOR_BINARY {#VIEW-DESCRIPTOR-BINARY}
```
public static final PidTagPropertyDescriptor VIEW_DESCRIPTOR_BINARY
```


Contains view definitions. Area: MessageClassDefinedTransmittable Canonical name: PidTagViewDescriptorBinary Alternate names: PR\_VD\_BINARY

### VIEW_DESCRIPTOR_NAME {#VIEW-DESCRIPTOR-NAME}
```
public static final PidTagPropertyDescriptor VIEW_DESCRIPTOR_NAME
```


Area: MessageClassDefinedTransmittable Canonical name: PidTagViewDescriptorName Alternate names: PR\_VD\_NAME, PR\_VD\_NAME\_W

### VIEW_DESCRIPTOR_STRINGS {#VIEW-DESCRIPTOR-STRINGS}
```
public static final PidTagPropertyDescriptor VIEW_DESCRIPTOR_STRINGS
```


Contains view definitions in string format. Area: MessageClassDefinedTransmittable Canonical name: PidTagViewDescriptorStrings Alternate names: PR\_VD\_STRINGS, PR\_VD\_STRINGS\_W

### VIEW_DESCRIPTOR_VERSION {#VIEW-DESCRIPTOR-VERSION}
```
public static final PidTagPropertyDescriptor VIEW_DESCRIPTOR_VERSION
```


Contains the View Descriptor version. Area: Miscellaneous Properties Canonical name: PidTagViewDescriptorVersion Alternate names: PR\_VD\_VERSION

### VOICE_MESSAGE_ATTACHMENT_ORDER {#VOICE-MESSAGE-ATTACHMENT-ORDER}
```
public static final PidTagPropertyDescriptor VOICE_MESSAGE_ATTACHMENT_ORDER
```


Contains a list of file names for the audio file attachments that are to be played as part of a message. Area: Unified Messaging Canonical name: PidTagVoiceMessageAttachmentOrder Alternate names: InternalSchemaVoiceMessageAttachmentOrder

### VOICE_MESSAGE_DURATION {#VOICE-MESSAGE-DURATION}
```
public static final PidTagPropertyDescriptor VOICE_MESSAGE_DURATION
```


Specifies the length of the attached audio message, in seconds. Area: Unified Messaging Canonical name: PidTagVoiceMessageDuration Alternate names: InternalSchemaVoiceMessageDuration

### VOICE_MESSAGE_SENDER_NAME {#VOICE-MESSAGE-SENDER-NAME}
```
public static final PidTagPropertyDescriptor VOICE_MESSAGE_SENDER_NAME
```


Specifies the name of the caller who left the attached voice message, as provided by the voice network's caller ID system. Area: Unified Messaging Canonical name: PidTagVoiceMessageSenderName Alternate names: InternalSchemaVoiceMessageSenderName

### WEDDING_ANNIVERSARY {#WEDDING-ANNIVERSARY}
```
public static final PidTagPropertyDescriptor WEDDING_ANNIVERSARY
```


Contains the date of the mail user's wedding anniversary. Area: MapiMailUser Canonical name: PidTagWeddingAnniversary Alternate names: PR\_WEDDING\_ANNIVERSARY, urn:schemas:contacts:weddinganniversary

### WEDDING_ANNIVERSARY_LOCAL {#WEDDING-ANNIVERSARY-LOCAL}
```
public static final PidLidPropertyDescriptor WEDDING_ANNIVERSARY_LOCAL
```


Specifies the wedding anniversary of the contact, at midnight in the client's local time zone, and is saved without any time zone conversions. Area: Contact Properties Canonical name: PidLidWeddingAnniversaryLocal Alternate names: dispidApptAnniversaryLocal

### WEEK_INTERVAL {#WEEK-INTERVAL}
```
public static final PidLidPropertyDescriptor WEEK_INTERVAL
```


Identifies the number of weeks that occur between each meeting. Area: Meetings Canonical name: PidLidWeekInterval Alternate names: LID\_WEEK\_INTERVAL

### WHERE {#WHERE}
```
public static final PidLidPropertyDescriptor WHERE
```


Contains the value of the PidLidLocation property (section 2.159) from the associated Meeting object. Area: Meetings Canonical name: PidLidWhere Alternate names: LID\_WHERE

### WLINK_ADDRESS_BOOK_EID {#WLINK-ADDRESS-BOOK-EID}
```
public static final PidTagPropertyDescriptor WLINK_ADDRESS_BOOK_EID
```


Specifies the value of the PidTagEntryId property (section 2.674) of the user to whom the folder belongs. Area: Configuration Canonical name: PidTagWlinkAddressBookEID Alternate names: PR\_WLINK\_ABEID

### WLINK_ADDRESS_BOOK_STORE_EID {#WLINK-ADDRESS-BOOK-STORE-EID}
```
public static final PidTagPropertyDescriptor WLINK_ADDRESS_BOOK_STORE_EID
```


Specifies the value of the PidTagStoreEntryId property (section 2.1018) of the current user (not the owner of the folder). Area: Configuration Canonical name: PidTagWlinkAddressBookStoreEID Alternate names: PR\_WLINK\_AB\_EXSTOREEID

### WLINK_CALENDAR_COLOR {#WLINK-CALENDAR-COLOR}
```
public static final PidTagPropertyDescriptor WLINK_CALENDAR_COLOR
```


Specifies the background color of the calendar. Area: Configuration Canonical name: PidTagWlinkCalendarColor Alternate names: PR\_WLINK\_CALENDAR\_COLOR

### WLINK_CLIENT_ID {#WLINK-CLIENT-ID}
```
public static final PidTagPropertyDescriptor WLINK_CLIENT_ID
```


Specifies the Client ID that allows the client to determine whether the shortcut was created on the current machine/user via an equality test. Area: Configuration Canonical name: PidTagWlinkClientID Alternate names: PR\_WLINK\_CLIENTID

### WLINK_ENTRY_ID {#WLINK-ENTRY-ID}
```
public static final PidTagPropertyDescriptor WLINK_ENTRY_ID
```


Specifies the EntryID of the folder pointed to by the shortcut. Area: Configuration Canonical name: PidTagWlinkEntryId Alternate names: PR\_WLINK\_ENTRYID

### WLINK_FLAGS {#WLINK-FLAGS}
```
public static final PidTagPropertyDescriptor WLINK_FLAGS
```


Specifies conditions associated with the shortcut. Area: Configuration Canonical name: PidTagWlinkFlags Alternate names: PR\_WLINK\_FLAGS

### WLINK_FOLDER_TYPE {#WLINK-FOLDER-TYPE}
```
public static final PidTagPropertyDescriptor WLINK_FOLDER_TYPE
```


Specifies the type of folder pointed to by the shortcut. Area: Configuration Canonical name: PidTagWlinkFolderType Alternate names: PR\_WLINK\_FOLDER\_TYPE

### WLINK_GROUP_CLSID {#WLINK-GROUP-CLSID}
```
public static final PidTagPropertyDescriptor WLINK_GROUP_CLSID
```


Specifies the value of the PidTagWlinkGroupHeaderID property (section 2.1060) of the group header associated with the shortcut. Area: Configuration Canonical name: PidTagWlinkGroupClsid Alternate names: PR\_WLINK\_GROUP\_CLSID

### WLINK_GROUP_HEADER_ID {#WLINK-GROUP-HEADER-ID}
```
public static final PidTagPropertyDescriptor WLINK_GROUP_HEADER_ID
```


Specifies the ID of the navigation shortcut that groups other navigation shortcuts. Area: Configuration Canonical name: PidTagWlinkGroupHeaderID Alternate names:

### WLINK_GROUP_NAME {#WLINK-GROUP-NAME}
```
public static final PidTagPropertyDescriptor WLINK_GROUP_NAME
```


Specifies the value of the PidTagNormalizedSubject (section 2.803) of the group header associated with the shortcut. Area: Configuration Canonical name: PidTagWlinkGroupName Alternate names: PR\_WLINK\_GROUP\_NAME

### WLINK_ORDINAL {#WLINK-ORDINAL}
```
public static final PidTagPropertyDescriptor WLINK_ORDINAL
```


Specifies a variable-length binary property to be used to sort shortcuts lexicographically. Area: Configuration Canonical name: PidTagWlinkOrdinal Alternate names: PR\_WLINK\_ORDINAL

### WLINK_RECORD_KEY {#WLINK-RECORD-KEY}
```
public static final PidTagPropertyDescriptor WLINK_RECORD_KEY
```


Specifies the value of PidTagRecordKey property (section 2.901) of the folder pointed to by the shortcut. Area: Configuration Canonical name: PidTagWlinkRecordKey Alternate names: PR\_WLINK\_RECKEY

### WLINK_RO_GROUP_TYPE {#WLINK-RO-GROUP-TYPE}
```
public static final PidTagPropertyDescriptor WLINK_RO_GROUP_TYPE
```


Specifies the type of group header. Area: Configuration Canonical name: PidTagWlinkROGroupType Alternate names: PR\_WLINK\_RO\_GROUP\_TYPE

### WLINK_SAVE_STAMP {#WLINK-SAVE-STAMP}
```
public static final PidTagPropertyDescriptor WLINK_SAVE_STAMP
```


Specifies an integer that allows a client to identify with a high probability whether the navigation shortcut was saved by the current client session. Area: Configuration Canonical name: PidTagWlinkSaveStamp Alternate names:

### WLINK_SECTION {#WLINK-SECTION}
```
public static final PidTagPropertyDescriptor WLINK_SECTION
```


Specifies the section where the shortcut should be grouped. Area: Configuration Canonical name: PidTagWlinkSection Alternate names: PR\_WLINK\_SECTION

### WLINK_STORE_ENTRY_ID {#WLINK-STORE-ENTRY-ID}
```
public static final PidTagPropertyDescriptor WLINK_STORE_ENTRY_ID
```


Specifies the value of the PidTagStoreEntryId property (section 2.1018) of the folder pointed to by the shortcut. Area: Configuration Canonical name: PidTagWlinkStoreEntryId Alternate names: PR\_WLINK\_STORE\_ENTRYID

### WLINK_TYPE {#WLINK-TYPE}
```
public static final PidTagPropertyDescriptor WLINK_TYPE
```


Specifies the type of navigation shortcut. Area: Configuration Canonical name: PidTagWlinkType Alternate names: PR\_WLINK\_TYPE

### WORD_COUNT {#WORD-COUNT}
```
public static final PidNamePropertyDescriptor WORD_COUNT
```


Specifies the word count of the file attached to the Document object. Area: Common Canonical name: PidNameWordCount Alternate names: urn:schemas-microsoft-com:office:office\#Words

### WORK_ADDRESS {#WORK-ADDRESS}
```
public static final PidLidPropertyDescriptor WORK_ADDRESS
```


Specifies the complete address of the work address of the contact. Area: Contact Properties Canonical name: PidLidWorkAddress Alternate names: dispidWorkAddress

### WORK_ADDRESS_CITY {#WORK-ADDRESS-CITY}
```
public static final PidLidPropertyDescriptor WORK_ADDRESS_CITY
```


Specifies the city or locality portion of the work address of the contact. Area: Contact Properties Canonical name: PidLidWorkAddressCity Alternate names: dispidWorkAddressCity

### WORK_ADDRESS_COUNTRY {#WORK-ADDRESS-COUNTRY}
```
public static final PidLidPropertyDescriptor WORK_ADDRESS_COUNTRY
```


Specifies the country or region portion of the work address of the contact. Area: Contact Properties Canonical name: PidLidWorkAddressCountry Alternate names: dispidWorkAddressCountry

### WORK_ADDRESS_COUNTRY_CODE {#WORK-ADDRESS-COUNTRY-CODE}
```
public static final PidLidPropertyDescriptor WORK_ADDRESS_COUNTRY_CODE
```


Specifies the country code portion of the work address of the contact. Area: Contact Properties Canonical name: PidLidWorkAddressCountryCode Alternate names: dispidWorkAddressCountryCode

### WORK_ADDRESS_POSTAL_CODE {#WORK-ADDRESS-POSTAL-CODE}
```
public static final PidLidPropertyDescriptor WORK_ADDRESS_POSTAL_CODE
```


Specifies the postal code (ZIP code) portion of the work address of the contact. Area: Contact Properties Canonical name: PidLidWorkAddressPostalCode Alternate names: dispidWorkAddressPostalCode

### WORK_ADDRESS_POST_OFFICE_BOX {#WORK-ADDRESS-POST-OFFICE-BOX}
```
public static final PidLidPropertyDescriptor WORK_ADDRESS_POST_OFFICE_BOX
```


Specifies the post office box portion of the work address of the contact. Area: Contact Properties Canonical name: PidLidWorkAddressPostOfficeBox Alternate names: dispidWorkAddressPostOfficeBox

### WORK_ADDRESS_STATE {#WORK-ADDRESS-STATE}
```
public static final PidLidPropertyDescriptor WORK_ADDRESS_STATE
```


Specifies the state or province portion of the work address of the contact. Area: Contact Properties Canonical name: PidLidWorkAddressState Alternate names: dispidWorkAddressState

### WORK_ADDRESS_STREET {#WORK-ADDRESS-STREET}
```
public static final PidLidPropertyDescriptor WORK_ADDRESS_STREET
```


Specifies the street portion of the work address of the contact. Area: Contact Properties Canonical name: PidLidWorkAddressStreet Alternate names: dispidWorkAddressStreet

### X4_00_CONTENT_TYPE {#X4-00-CONTENT-TYPE}
```
public static final PidTagPropertyDescriptor X4_00_CONTENT_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_X400\_CONTENT\_TYPE

### X4_00_DEFERRED_DELIVERY_CANCEL {#X4-00-DEFERRED-DELIVERY-CANCEL}
```
public static final PidTagPropertyDescriptor X4_00_DEFERRED_DELIVERY_CANCEL
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_X400\_DEFERRED\_DELIVERY\_CANCEL

### X4_00_ENVELOPE_TYPE {#X4-00-ENVELOPE-TYPE}
```
public static final PidTagPropertyDescriptor X4_00_ENVELOPE_TYPE
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_X400\_ENVELOPE\_TYPE

### XPOS {#XPOS}
```
public static final PidTagPropertyDescriptor XPOS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_XPOS

### X_CALL_ID {#X-CALL-ID}
```
public static final PidNamePropertyDescriptor X_CALL_ID
```


Contains a unique identifier associated with the phone call. Area: Unified Messaging Canonical name: PidNameXCallId Alternate names:

### X_FAX_NUMBER_OF_PAGES {#X-FAX-NUMBER-OF-PAGES}
```
public static final PidNamePropertyDescriptor X_FAX_NUMBER_OF_PAGES
```


Specifies how many discrete pages are contained within an attachment representing a facsimile message. Area: Unified Messaging Canonical name: PidNameXFaxNumberOfPages Alternate names:

### X_REQUIRE_PROTECTED_PLAY_ON_PHONE {#X-REQUIRE-PROTECTED-PLAY-ON-PHONE}
```
public static final PidNamePropertyDescriptor X_REQUIRE_PROTECTED_PLAY_ON_PHONE
```


Indicates that the client only renders the message on a phone. Area: Unified Messaging Canonical name: PidNameXRequireProtectedPlayOnPhone Alternate names:

### X_SENDER_TELEPHONE_NUMBER {#X-SENDER-TELEPHONE-NUMBER}
```
public static final PidNamePropertyDescriptor X_SENDER_TELEPHONE_NUMBER
```


Contains the telephone number of the caller associated with a voice mail message. Area: Unified Messaging Canonical name: PidNameXSenderTelephoneNumber Alternate names:

### X_SHARING_BROWSE_URL {#X-SHARING-BROWSE-URL}
```
public static final PidNamePropertyDescriptor X_SHARING_BROWSE_URL
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidNameXSharingBrowseUrl Alternate names:

### X_SHARING_CAPABILITIES {#X-SHARING-CAPABILITIES}
```
public static final PidNamePropertyDescriptor X_SHARING_CAPABILITIES
```


Contains a string representation of the value of the PidLidSharingCapabilities property (section 2.237). Area: Sharing Canonical name: PidNameXSharingCapabilities Alternate names:

### X_SHARING_CONFIG_URL {#X-SHARING-CONFIG-URL}
```
public static final PidNamePropertyDescriptor X_SHARING_CONFIG_URL
```


Contains the same value as the PidLidSharingConfigurationUrl property (section 2.238). Area: Sharing Canonical name: PidNameXSharingConfigUrl Alternate names:

### X_SHARING_EXENDED_CAPS {#X-SHARING-EXENDED-CAPS}
```
public static final PidNamePropertyDescriptor X_SHARING_EXENDED_CAPS
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidNameXSharingExendedCaps Alternate names:

### X_SHARING_FLAVOR {#X-SHARING-FLAVOR}
```
public static final PidNamePropertyDescriptor X_SHARING_FLAVOR
```


Contains a hexadecimal string representation of the value of the PidLidSharingFlavor property (section 2.245). Area: Sharing Canonical name: PidNameXSharingFlavor Alternate names:

### X_SHARING_INSTANCE_GUID {#X-SHARING-INSTANCE-GUID}
```
public static final PidNamePropertyDescriptor X_SHARING_INSTANCE_GUID
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidNameXSharingInstanceGuid Alternate names:

### X_SHARING_LOCAL_TYPE {#X-SHARING-LOCAL-TYPE}
```
public static final PidNamePropertyDescriptor X_SHARING_LOCAL_TYPE
```


Contains the same value as the PidLidSharingLocalType property (section 2.259). Area: Sharing Canonical name: PidNameXSharingLocalType Alternate names:

### X_SHARING_PROVIDER_GUID {#X-SHARING-PROVIDER-GUID}
```
public static final PidNamePropertyDescriptor X_SHARING_PROVIDER_GUID
```


Contains the hexadecimal string representation of the value of the PidLidSharingProviderGuid property (section 2.266). Area: Sharing Canonical name: PidNameXSharingProviderGuid Alternate names:

### X_SHARING_PROVIDER_NAME {#X-SHARING-PROVIDER-NAME}
```
public static final PidNamePropertyDescriptor X_SHARING_PROVIDER_NAME
```


Contains the same value as the PidLidSharingProviderName property (section 2.267). Area: Sharing Canonical name: PidNameXSharingProviderName Alternate names:

### X_SHARING_PROVIDER_URL {#X-SHARING-PROVIDER-URL}
```
public static final PidNamePropertyDescriptor X_SHARING_PROVIDER_URL
```


Contains the same value as the PidLidSharingProviderUrl property (section 2.268). Area: Sharing Canonical name: PidNameXSharingProviderUrl Alternate names:

### X_SHARING_REMOTE_NAME {#X-SHARING-REMOTE-NAME}
```
public static final PidNamePropertyDescriptor X_SHARING_REMOTE_NAME
```


Contains the same value as the PidLidSharingRemoteName property (section 2.277). Area: Sharing Canonical name: PidNameXSharingRemoteName Alternate names:

### X_SHARING_REMOTE_PATH {#X-SHARING-REMOTE-PATH}
```
public static final PidNamePropertyDescriptor X_SHARING_REMOTE_PATH
```


Contains a value that is ignored by the server no matter what value is generated by the client. Area: Sharing Canonical name: PidNameXSharingRemotePath Alternate names:

### X_SHARING_REMOTE_STORE_UID {#X-SHARING-REMOTE-STORE-UID}
```
public static final PidNamePropertyDescriptor X_SHARING_REMOTE_STORE_UID
```


Contains the same value as the PidLidSharingRemoteStoreUid property (section 2.282). Area: Sharing Canonical name: PidNameXSharingRemoteStoreUid Alternate names:

### X_SHARING_REMOTE_TYPE {#X-SHARING-REMOTE-TYPE}
```
public static final PidNamePropertyDescriptor X_SHARING_REMOTE_TYPE
```


Contains the same value as the PidLidSharingRemoteType property (section 2.281). Area: Sharing Canonical name: PidNameXSharingRemoteType Alternate names:

### X_SHARING_REMOTE_UID {#X-SHARING-REMOTE-UID}
```
public static final PidNamePropertyDescriptor X_SHARING_REMOTE_UID
```


Contains the same value as the PidLidSharingRemoteUid property (section 2.282). Area: Sharing Canonical name: PidNameXSharingRemoteUid Alternate names:

### X_VOICE_MESSAGE_ATTACHMENT_ORDER {#X-VOICE-MESSAGE-ATTACHMENT-ORDER}
```
public static final PidNamePropertyDescriptor X_VOICE_MESSAGE_ATTACHMENT_ORDER
```


Contains the list of names for the audio file attachments that are to be played as part of a message, in reverse order. Area: Unified Messaging Canonical name: PidNameXVoiceMessageAttachmentOrder Alternate names:

### X_VOICE_MESSAGE_DURATION {#X-VOICE-MESSAGE-DURATION}
```
public static final PidNamePropertyDescriptor X_VOICE_MESSAGE_DURATION
```


Specifies the length of the attached audio message, in seconds. Area: Unified Messaging Canonical name: PidNameXVoiceMessageDuration Alternate names:

### X_VOICE_MESSAGE_SENDER_NAME {#X-VOICE-MESSAGE-SENDER-NAME}
```
public static final PidNamePropertyDescriptor X_VOICE_MESSAGE_SENDER_NAME
```


Contains the name of the caller who left the attached voice message, as provided by the voice network's caller ID system. Area: Unified Messaging Canonical name: PidNameXVoiceMessageSenderName Alternate names:

### YEAR_INTERVAL {#YEAR-INTERVAL}
```
public static final PidLidPropertyDescriptor YEAR_INTERVAL
```


Indicates the yearly interval of the appointment or meeting. Area: Meetings Canonical name: PidLidYearInterval Alternate names: LID\_YEAR\_INTERVAL

### YOMI_COMPANY_NAME {#YOMI-COMPANY-NAME}
```
public static final PidLidPropertyDescriptor YOMI_COMPANY_NAME
```


Specifies the phonetic pronunciation of the company name of the contact. Area: Contact Properties Canonical name: PidLidYomiCompanyName Alternate names: dispidYomiCompanyName

### YOMI_FIRST_NAME {#YOMI-FIRST-NAME}
```
public static final PidLidPropertyDescriptor YOMI_FIRST_NAME
```


Specifies the phonetic pronunciation of the given name of the contact. Area: Contact Properties Canonical name: PidLidYomiFirstName Alternate names: dispidYomiFirstName

### YOMI_LAST_NAME {#YOMI-LAST-NAME}
```
public static final PidLidPropertyDescriptor YOMI_LAST_NAME
```


Specifies the phonetic pronunciation of the surname of the contact. Area: Contact Properties Canonical name: PidLidYomiLastName Alternate names: dispidYomiLastName

### YPOS {#YPOS}
```
public static final PidTagPropertyDescriptor YPOS
```


Microsoft® Exchange defines this property that is used by the Microsoft Exchange Server and the Microsoft Exchange Client. Canonical name: Alternate names: PR\_YPOS

### add(PropertyDescriptor item) {#add-com.aspose.email.PropertyDescriptor-}
```
public final void add(PropertyDescriptor item)
```


List is read-only. Operation is not supported.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The object to add to the System.Collections.Generic.ICollection. |

### clear() {#clear--}
```
public final void clear()
```


List is read-only. Operation is not supported.

### contains(PropertyDescriptor item) {#contains-com.aspose.email.PropertyDescriptor-}
```
public final boolean contains(PropertyDescriptor item)
```


Determines whether the System.Collections.Generic.ICollection contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The object to locate in the System.Collections.Generic.ICollection. |

**Returns:**
boolean - true if item is found in the System.Collections.Generic.ICollection; otherwise, false.
### copyTo(PropertyDescriptor[] array, int arrayIndex) {#copyTo-com.aspose.email.PropertyDescriptor---int-}
```
public final void copyTo(PropertyDescriptor[] array, int arrayIndex)
```


List is read-only. Operation is not supported.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [PropertyDescriptor\[\]](../../com.aspose.email/propertydescriptor) | The one-dimensional System.Array that is the destination of the elements copied from System.Collections.Generic.ICollection. The System.Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

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
### find(System.Guid[] propertySets) {#find-com.aspose.ms.System.Guid...-}
```
public PropertyDescriptor[] find(System.Guid[] propertySets)
```


Finds properties in list according to its PropertySet

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertySets | com.aspose.ms.System.Guid[] | PropertySet to find |

**Returns:**
com.aspose.email.PropertyDescriptor[] - Array of [PropertyDescriptor](../../com.aspose.email/propertydescriptor) objects with required PropertySet if found in the list; otherwise empty array.
### find(int id) {#find-int-}
```
public final PidTagPropertyDescriptor[] find(int id)
```


Finds [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) properties in list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | id to find |

**Returns:**
com.aspose.email.PidTagPropertyDescriptor[] - [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) Array of objects with defined tag if found in the list; otherwise empty array.
### find(int id, int type) {#find-int-int-}
```
public final PidTagPropertyDescriptor find(int id, int type)
```


Finds [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) property in list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | id to find |
| type | int | Data type of a property |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) - [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object with defined tag if found in the list; otherwise null.
### find(String name) {#find-java.lang.String-}
```
public final PropertyDescriptor find(String name)
```


Finds property in list with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name used to refer to the property. |

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor) - [PropertyDescriptor](../../com.aspose.email/propertydescriptor) object if found in the list; otherwise null.
### find(String name, int type, UUID propertySet) {#find-java.lang.String-int-java.util.UUID-}
```
public final PidNamePropertyDescriptor find(String name, int type, UUID propertySet)
```


Finds [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) property in list according to required parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of a property |
| type | int | Data type of a property |
| propertySet | java.util.UUID | PropertySet of a property |

**Returns:**
[PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) - [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) object if found in the list; otherwise null.
### find(String name, UUID propertySet) {#find-java.lang.String-java.util.UUID-}
```
public final PidNamePropertyDescriptor find(String name, UUID propertySet)
```


Finds [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) property in list according to required parameters This is simplified search operation without data type comparison.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of a property |
| propertySet | java.util.UUID | PropertySet of a property |

**Returns:**
[PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) - [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) object if found in the list; otherwise null.
### find(long tag) {#find-long-}
```
public final PidTagPropertyDescriptor find(long tag)
```


Finds [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) property in list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | Tag to find |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) - [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object with defined tag if found in the list; otherwise null.
### find(long lid, int type, UUID propertySet) {#find-long-int-java.util.UUID-}
```
public final PidLidPropertyDescriptor find(long lid, int type, UUID propertySet)
```


Finds [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) property in list according to required parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lid | long | Long id of a property |
| type | int | Data type of a property |
| propertySet | java.util.UUID | PropertySet of a property |

**Returns:**
[PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) - [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) object if found in the list; otherwise null.
### find(long lid, UUID propertySet) {#find-long-java.util.UUID-}
```
public final PidLidPropertyDescriptor find(long lid, UUID propertySet)
```


Finds [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) property in list according to required parameters This is simplified search operation without data type comparison.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lid | long | Long id of a property |
| propertySet | java.util.UUID | PropertySet of a property |

**Returns:**
[PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) - [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) object if found in the list; otherwise null.
### findOrGetCurrent(PropertyDescriptor item) {#findOrGetCurrent-com.aspose.email.PropertyDescriptor-}
```
public final PropertyDescriptor findOrGetCurrent(PropertyDescriptor item)
```


Finds property in list with canonical name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Property descriptor to search |

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor) - [PropertyDescriptor](../../com.aspose.email/propertydescriptor) object if found in the list; otherwise [PropertyDescriptor](../../com.aspose.email/propertydescriptor) object from parameter.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultValues() {#getDefaultValues--}
```
public static KnownPropertyList getDefaultValues()
```


Gets PropertyList with all properties.

**Returns:**
[KnownPropertyList](../../com.aspose.email/knownpropertylist) - Returns instance of PropertyList.
### getValues() {#getValues--}
```
public static KnownPropertyList getValues()
```


Gets PropertyList with all properties.

**Returns:**
[KnownPropertyList](../../com.aspose.email/knownpropertylist) - Returns instance of PropertyList.
### get_Item(int index) {#get-Item-int-}
```
public final PropertyDescriptor get_Item(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to get or set. |

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor) - The property is set and the System.Collections.Generic.IList is read-only.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(PropertyDescriptor item) {#indexOf-com.aspose.email.PropertyDescriptor-}
```
public final int indexOf(PropertyDescriptor item)
```


Determines the index of a specific item in the System.Collections.Generic.IList.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The object to locate in the System.Collections.Generic.IList. |

**Returns:**
int - The index of item if found in the list; otherwise, -1.
### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Determines the index of a specific item in the System.Collections.Generic.IList.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name used to refer to the property. |

**Returns:**
int - The index of item if found in the list; otherwise, -1.
### insert(int index, PropertyDescriptor item) {#insert-int-com.aspose.email.PropertyDescriptor-}
```
public final void insert(int index, PropertyDescriptor item)
```


List is read-only. Operation is not supported.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which item should be inserted. |
| item | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The object to insert into the System.Collections.Generic.IList. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


true if the System.Collections.Generic.ICollection is read-only; otherwise, false.

**Returns:**
boolean
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<PropertyDescriptor> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.email.PropertyDescriptor> - A System.Collections.Generic.IEnumerator that can be used to iterate through the collection.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(PropertyDescriptor item) {#remove-com.aspose.email.PropertyDescriptor-}
```
public final boolean remove(PropertyDescriptor item)
```


List is read-only. Operation is not supported.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The object to remove from the System.Collections.Generic.ICollection. |

**Returns:**
boolean - true if item was successfully removed from the System.Collections.Generic.ICollection; otherwise, false. This method also returns false if item is not found in the original System.Collections.Generic.ICollection.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


List is read-only. Operation is not supported.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the item to remove. |

### set_Item(int index, PropertyDescriptor value) {#set-Item-int-com.aspose.email.PropertyDescriptor-}
```
public final void set_Item(int index, PropertyDescriptor value)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to get or set. |
| value | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) |  |

### size() {#size--}
```
public final int size()
```


Gets the number of elements contained in the System.Collections.Generic.ICollection.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

