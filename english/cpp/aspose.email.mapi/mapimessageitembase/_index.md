---
title: "Aspose::Email::Mapi::MapiMessageItemBase class"
linktitle: "MapiMessageItemBase"
articleTitle: "MapiMessageItemBase"
second_title: "Aspose.Email for C++"
description: "Represents the base class for all MapiMessageItem classes and keeps common collections of mapi properties, attachments, recipients."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapimessageitembase/
---

## MapiMessageItemBase class

**Inherits:** Aspose::Email::Mapi::MapiPropertyContainer, Aspose::Email::Mapi::IMapiMessageItem

Represents the base class for all MapiMessageItem classes and keeps common collections of mapi properties, attachments, recipients.

## Constructors

| Name | Description |
| --- | --- |
| [MapiMessageItemBase (2 overloads)](./mapimessageitembase/) | Initializes a new instance of the MapiMessageItemBase class. |

## Methods

| Name | Description |
| --- | --- |
| [AddNamedProperty (15 overloads)](./addnamedproperty/) | Adds the named bool property. |
| [AddNamedPropertyLong (2 overloads)](./addnamedpropertylong/) | Adds the named long property. |
| [AddNamedPropertyToEmbeddedMsg](./addnamedpropertytoembeddedmsg/) | Adds the named property to embedded message. |
| [CheckIsDisposed](./checkisdisposed/) | Checks if the object is disposed and raised exception in this case. |
| [ConvertToMapiMessage](./converttomapimessage/) | Convert item to MapiMessage . Set MessageClass, Subject, Mileage and Billing. |
| [CreateNamedProperty](./createnamedproperty/) |  |
| [Dispose](./dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [get_Attachments](./get_attachments/) | Gets the attachments in the message. |
| [get_Billing](./get_billing/) | Contains the billing information associated with an item. |
| [get_Body](./get_body/) | Gets the message text. |
| [get_BodyHtml](./get_bodyhtml/) | Gets the BodyRtf of the message converted to HTML, if present, otherwise an empty string. |
| [get_BodyRtf](./get_bodyrtf/) | Gets the RTF formatted message text. |
| [get_BodyType](./get_bodytype/) | Gets the type of the body. |
| [get_Categories](./get_categories/) | Contains keywords or categories for the message object. |
| [get_Companies](./get_companies/) | Contains the names of the companies that are associated with an item. |
| [get_ItemId](./get_itemid/) | The item id, uses with a server |
| [get_MessageClass](./get_messageclass/) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message. |
| [get_Mileage](./get_mileage/) | Contains the mileage information that is associated with an item. |
| [get_NamedProperties](./get_namedproperties/) | Gets the named properties of message. |
| [get_NamedPropertyMapping](./get_namedpropertymapping/) | Gets the named property mapping. |
| [get_PropertyStream](./get_propertystream/) | Gets the property stream. |
| [get_Recipients](./get_recipients/) | Gets the recipients of the message. |
| [get_Sensitivity](./get_sensitivity/) | Gets the Sensitivity. |
| [get_Subject](./get_subject/) | Gets the subject of the message. |
| [get_SubjectPrefix](./get_subjectprefix/) | Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding. |
| [get_SubStorages](./get_substorages/) | Gets the sub storages. |
| [get_SupportedType](./get_supportedtype/) | Gets the supported item type. |
| [get_VentureLicenseObj](./get_venturelicenseobj/) | This stores the venture licensing state instead of 2 obvious fields such as string value for watermark and some value indicating license is set or not. |
| [GetFlags](./getflags/) |  |
| [GetProperty](./getproperty/) | Gets MAPI property by property descriptor. |
| [GetTagFromNamedProperty (4 overloads)](./gettagfromnamedproperty/) | Gets the tag from named property. |
| [InitNamedPropertyMappingStorage](./initnamedpropertymappingstorage/) | Inits the named property mapping storage. |
| [RemoveProperty](./removeproperty/) | Provides correctly removing property from all collections. |
| [set_Attachments](./set_attachments/) | Gets the attachments in the message. |
| [set_Billing](./set_billing/) | Contains the billing information associated with an item. |
| [set_Body](./set_body/) | Gets the message text. |
| [set_BodyRtf](./set_bodyrtf/) | Sets the RTF formatted message text. |
| [set_Categories](./set_categories/) | Contains keywords or categories for the message object. |
| [set_Companies](./set_companies/) | Contains the names of the companies that are associated with an item. |
| [set_ItemId](./set_itemid/) | The item id, uses with a server |
| [set_MessageClass](./set_messageclass/) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message. |
| [set_Mileage](./set_mileage/) | Contains the mileage information that is associated with an item. |
| [set_Recipients](./set_recipients/) | Gets the recipients of the message. |
| [set_Sensitivity](./set_sensitivity/) | Gets the Sensitivity. |
| [set_Subject](./set_subject/) | Sets the subject of the message. |
| [SetBodyContent (2 overloads)](./setbodycontent/) | Sets the content of the body. |
| [SetBodyRtf](./setbodyrtf/) | Gets or sets the RTF formatted message text. |
| [SetMessageFlags](./setmessageflags/) | Sets the message flags. |
| [SetNamedPropertyMapping](./setnamedpropertymapping/) | Sets the named property mapping. |
| [SetPriority](./setpriority/) | Sets MailPriority value for MapiMessageItemBase See more PidTagPriority mapi property: https://msdn.microsoft.com/en-us/library/ee159473(v=exchg.80).aspx See more PidTagImportance mapi property: https://msdn.microsoft.com/en-us/library/ee237166(v=exchg.80).aspx |
| [SetProperty](./setproperty/) | Sets MAPI property. |
| [SetsIMapiMessageItemMembers](./setsimapimessageitemmembers/) | Sets MessageClass,Body and Subject. |
| [SetStringNamedProperty](./setstringnamedproperty/) |  |
| [SetVentureLicense](./setventurelicense/) | All Aspose products should implement this method. It is called by a GroupDocs product to indicate whether GroupDocs itself is licensed or not and specify a custom watermark. When GroupDocs is licensed, this document instance should behave as licensed too even if the Aspose product is not licensed. |
| [TryGetNamedProperty](./trygetnamedproperty/) | If MapiNamedPropertyMappingStorage is available, initializes and returns MapiNamedProperty , otherwise null. |
| [UpdateDisplayNames](./updatedisplaynames/) | Updates the display names. |
| [UpdateHasAttach](./updatehasattach/) | Updates the PR_HASATTACH property value. |
| [Aspose::Email::Clients::Exchange::WebService::ContactEwsConverter](./asposeemailclientsexchangewebservicecontactewsconverter/) |  |
| [Aspose::Email::Clients::Exchange::WebService::EwsConverterUtils](./asposeemailclientsexchangewebserviceewsconverterutils/) |  |
| [Aspose::Email::Clients::Exchange::WebService::Implementation::Contacts::Create::EwsClientContactCreate](./asposeemailclientsexchangewebserviceimplementationcontactscreateewsclientcontactcreate/) |  |
| [Aspose::Email::Clients::Exchange::WebService::Implementation::Contacts::Update::EwsClientContactUpdate](./asposeemailclientsexchangewebserviceimplementationcontactsupdateewsclientcontactupdate/) |  |
| [Aspose::Email::Clients::Exchange::WebService::Implementation::Notes::Create::EwsClientNoteCreate](./asposeemailclientsexchangewebserviceimplementationnotescreateewsclientnotecreate/) |  |
| [Aspose::Email::Clients::Exchange::WebService::NoteEwsConverter](./asposeemailclientsexchangewebservicenoteewsconverter/) |  |
| [Aspose::Email::Clients::Graph::GraphClientV1](./asposeemailclientsgraphgraphclientv1/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::SendMessageCommand](./asposeemailclientsgraphv1commandssendmessagecommand/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::UpdateContactCommand](./asposeemailclientsgraphv1commandsupdatecontactcommand/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::UpdateMessageCommand](./asposeemailclientsgraphv1commandsupdatemessagecommand/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::UpdateTodoTaskCommand](./asposeemailclientsgraphv1commandsupdatetodotaskcommand/) |  |
| [Aspose::Email::Storage::Olm::MapiMessageIterator](./asposeemailstorageolmmapimessageiterator/) |  |
| [Aspose::Email::Storage::Olm::OlmStorage](./asposeemailstorageolmolmstorage/) |  |
| [Aspose::Email::Storage::Pst::FolderInfo](./asposeemailstoragepstfolderinfo/) |  |
| [Aspose::Email::Storage::Pst::Ltp::LtpDoer](./asposeemailstoragepstltpltpdoer/) |  |
| [Aspose::Email::Storage::Pst::PersonalStorage](./asposeemailstoragepstpersonalstorage/) |  |
| [Aspose::Email::Storage::Pst::PstDoer](./asposeemailstoragepstpstdoer/) |  |
| [Aspose::Email::Tnef::TnefAttachment](./asposeemailtneftnefattachment/) |  |
| [Aspose::Email::Tools::ContactConverter](./asposeemailtoolscontactconverter/) |  |
| [Aspose::Email::Tools::ForwardMessageBuilder](./asposeemailtoolsforwardmessagebuilder/) |  |
| [Aspose::Email::Tools::MessageConverter](./asposeemailtoolsmessageconverter/) |  |
| [Aspose::Email::Tools::ResponseMessageBuilder](./asposeemailtoolsresponsemessagebuilder/) |  |
| [ClearSignedMailMessageInterpretor](./clearsignedmailmessageinterpretor/) |  |
| [MailMessageInterpretor](./mailmessageinterpretor/) |  |
| [MapiCalendar](./mapicalendar/) |  |
| [MapiCalendarEventRecurrence](./mapicalendareventrecurrence/) |  |
| [MapiCalendarExceptionInfo](./mapicalendarexceptioninfo/) |  |
| [MapiContact](./mapicontact/) |  |
| [MapiContactPhoto](./mapicontactphoto/) |  |
| [MapiDistributionList](./mapidistributionlist/) |  |
| [MapiJournal](./mapijournal/) |  |
| [MapiMessage](./mapimessage/) |  |
| [MapiMessagePropertyStream](./mapimessagepropertystream/) |  |
| [MapiMessageReader](./mapimessagereader/) |  |
| [MapiNote](./mapinote/) |  |
| [MapiTask](./mapitask/) |  |
| [OpaqueSignedMailMessageInterpretor](./opaquesignedmailmessageinterpretor/) |  |
| [OutlookUtil](./outlookutil/) |  |
| [TaskMailMessageInterpretor](./taskmailmessageinterpretor/) |  |
| [attachments](./attachments/) | The collection of attachments. |
| [namedPropertyMappingStorage](./namedpropertymappingstorage/) | The named property mapping storage. |
| [recipients](./recipients/) | The collection of recipients. |

