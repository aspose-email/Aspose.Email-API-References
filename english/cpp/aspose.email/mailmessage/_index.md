---
title: "Aspose::Email::MailMessage class"
linktitle: "MailMessage"
articleTitle: "MailMessage"
second_title: "Aspose.Email for C++"
description: "Provides possibility to handle rendering of hyperlink in custom style."
type: docs
weight: 10
url: /cpp/aspose.email/mailmessage/
---

## MailMessage class

**Inherits:** Aspose::Email::IPreferredTextEncodingProvider, Aspose::Email::IMessage

Provides possibility to handle rendering of hyperlink in custom style.

Represents an e-mail message. It allows to access message properties, ex. subject, body, sender and recipients addreses, etc. Also it can be sent and delivered by means of supported mail protocols.

The following example shows how to create a new Email Message and save with SaveOptions .

```csharp
var message = new MailMessage
{
 // Set subject of the message, Html body and sender information
    Subject = "New message created by Aspose.Email for .NET",
    HtmlBody = "<b>This line is in bold.</b> <br/> <br/>" +
 "<font color=blue>This line is in blue color</font>",
    From = new MailAddress("from@domain.com", "Sender Name", false)
};
 
// Add TO recipients and Add CC recipients
message.To.Add(new MailAddress("to1@domain.com", "Recipient 1", false));
message.To.Add(new MailAddress("to2@domain.com", "Recipient 2", false));
message.CC.Add(new MailAddress("cc1@domain.com", "Recipient 3", false));
message.CC.Add(new MailAddress("cc2@domain.com", "Recipient 4", false));
 
// Save message to EML, EMLX, MSG and MHTML formats
message.Save("CreateNewMailMessage_out.eml", SaveOptions.DefaultEml);
message.Save("CreateNewMailMessage_out.emlx", SaveOptions.CreateSaveOptions(MailMessageSaveType.EmlxFormat));
message.Save("CreateNewMailMessage_out.msg", SaveOptions.DefaultMsgUnicode);
message.Save("CreateNewMailMessage_out.mhtml", SaveOptions.DefaultMhtml);
```

```vb
' Create a new instance of MailMessage class
Dim message As MailMessage = New MailMessage()
 
' Set subject of the message, Html body and sender information
message.Subject = "New message created by Aspose.Email for .NET"
message.HtmlBody = "<b>This line is in bold.</b> <br/> <br/>" & "<font color=blue>This line is in blue color</font>"
message.From = New MailAddress("from@domain.com", "Sender Name", False)
 
' Add TO recipients and Add CC recipients
message.[To].Add(New MailAddress("to1@domain.com", "Recipient 1", False))
message.[To].Add(New MailAddress("to2@domain.com", "Recipient 2", False))
message.CC.Add(New MailAddress("cc1@domain.com", "Recipient 3", False))
message.CC.Add(New MailAddress("cc2@domain.com", "Recipient 4", False))
 
' Save message in EML, EMLX, MSG and MHTML formats
message.Save("CreateNewMailMessage_out.eml", SaveOptions.DefaultEml)
message.Save("CreateNewMailMessage_out.emlx", SaveOptions.CreateSaveOptions(MailMessageSaveType.EmlxFormat))
message.Save("CreateNewMailMessage_out.msg", SaveOptions.DefaultMsgUnicode)
message.Save("CreateNewMailMessage_out.mhtml", SaveOptions.DefaultMhtml)
```

## Constructors

| Name | Description |
| --- | --- |
| [MailMessage (5 overloads)](./mailmessage/) | Initializes a new instance of the MailMessage class |

## Methods

| Name | Description |
| --- | --- |
| [AddAlternateView](./addalternateview/) | Add an alternate view to message |
| [AddAttachment](./addattachment/) | Add an attachment to message |
| [BuildDeliveryStatusNotificationString](./builddeliverystatusnotificationstring/) |  |
| [CheckBounced](./checkbounced/) | Checks whether this message can be treated as a bounce message. |
| [Clone](./clone/) | Clones this instance |
| [CreateContentData](./createcontentdata/) |  |
| [CreateDKIMContentData](./createdkimcontentdata/) |  |
| [CreateReadReceipt](./createreadreceipt/) | Creates the read receipt. |
| [Dispose (2 overloads)](./dispose/) | Releases all resources used by the MailMessage |
| [Equals](./equals/) | Determines whether the specified Object is equal to the current Object. |
| [ForceTextContentType](./forcetextcontenttype/) |  |
| [get_AlternateViews](./get_alternateviews/) | Gets the collection of alternate views of message |
| [get_Attachments](./get_attachments/) | Gets the collection of attachments of message |
| [get_Bcc](./get_bcc/) | Gets the address collection that contains the BCC recipients of message |
| [get_Body](./get_body/) | Gets the plain text representation of message's body. If the text/plain part is present in a message, the propery returns its text data. Otherwise, property returns the text content of the HtmlBody property without html markup. |
| [get_BodyEncoding](./get_bodyencoding/) | Gets encoding of body |
| [get_BodyType](./get_bodytype/) | Gets the type of the body. |
| [get_Categories](./get_categories/) | Gets exchange message categories |
| [get_CC](./get_cc/) | Gets the address collection that contains the CC recipients |
| [get_Date](./get_date/) | Gets the date of message |
| [get_DeliveryNotificationOptions](./get_deliverynotificationoptions/) | Gets the delivery notifications |
| [get_Epilogue](./get_epilogue/) | Gets an epilogue text. It is located after the last boundary. |
| [get_ExtendedProperties](./get_extendedproperties/) | Gets extended properties of a message. |
| [get_From](./get_from/) | Gets the from address |
| [get_Headers](./get_headers/) | Gets headers collection of message |
| [get_HtmlBody](./get_htmlbody/) | Gets html body |
| [get_IsBodyHtml](./get_isbodyhtml/) | Gets a value indicating whether the message body is in Html |
| [get_IsDraft](./get_isdraft/) | Gets value that indicates whether or not a message has been sent. |
| [get_IsEmpty](./get_isempty/) |  |
| [get_IsEncrypted](./get_isencrypted/) | Gets a value indicating whether the message is encrypted. |
| [get_IsRead](./get_isread/) |  |
| [get_IsReadOnly](./get_isreadonly/) | Gets a value indicating whether the message is read only |
| [get_IsSigned](./get_issigned/) | Gets a value indicating whether the message is signed. |
| [get_ItemId](./get_itemid/) | Represents identification information about message in a mailbox. |
| [get_LinkedResources](./get_linkedresources/) | Gets the collection of linked resources of message |
| [get_ListUnsubscribe](./get_listunsubscribe/) | The List-Unsubscribe field describes the command (preferably using mail) to directly unsubscribe the user(removing them from the list). For more details please see https://tools.ietf.org/html/rfc2369 |
| [get_Message](./get_message/) |  |
| [get_MessageId](./get_messageid/) | Gets the message id |
| [get_OriginalIsTnef](./get_originalistnef/) | Gets a value indicating whether original EML message is in TNEF format. |
| [get_Preamble](./get_preamble/) | Gets a preamble text. It is located before the first boundary and generally includes an explanatory note to non-MIME conformant readers. |
| [get_PreferredTextEncoding](./get_preferredtextencoding/) | Gets preferred encoding for all text properties |
| [get_PreserveTnefAttachment](./get_preservetnefattachment/) | Controls TNEF attachment load/save behaviour |
| [get_Priority](./get_priority/) | Gets the priority of message |
| [get_ReadReceiptRequested](./get_readreceiptrequested/) |  |
| [get_ReadReceiptTo](./get_readreceiptto/) | Gets the read receipt address. |
| [get_ReplyToList](./get_replytolist/) | Gets the list of addresses to reply to for the mail message |
| [get_ReversePath](./get_reversepath/) | Gets ReversePath address |
| [get_Sender](./get_sender/) | Gets sender address |
| [get_Sensitivity](./get_sensitivity/) | Gets the sensitivity of message |
| [get_Subject](./get_subject/) | Gets the subject line |
| [get_SubjectEncoding](./get_subjectencoding/) | Gets the encoding of subject |
| [get_SuppressBcc](./get_suppressbcc/) | Indicates whether Bcc header is suppressed in MIME. |
| [get_TimeZoneOffset](./get_timezoneoffset/) | Gets the Coordinated Universal Time (UTC) offset for the message dates. This property defines the time zone difference, between the local time and UTC. |
| [get_TnefAttachment](./get_tnefattachment/) | Gets the tnef attachment. |
| [get_To](./get_to/) | Gets the address collection that contains the recipients of message |
| [get_VentLicense](./get_ventlicense/) | This stores the venture licensing state instead of 2 obvious fields such as string value for watermark and some value indicating license is set or not. |
| [get_XMailer](./get_xmailer/) | Gets the X-Mailer the software that created the e-mail message |
| [GetAlternateViewContent](./getalternateviewcontent/) | Gets the content as a string from the specified AlternateView . |
| [GetEmlStream](./getemlstream/) |  |
| [GetHashCode](./gethashcode/) | Returns a hash code for object |
| [GetHeadersAsString](./getheadersasstring/) |  |
| [GetHtmlBodyText (2 overloads)](./gethtmlbodytext/) | Gets the message html body as plain text. This method parses the HtmlBody property and returns plain text content ignoring the html markup. |
| [GetHtmlView](./gethtmlview/) |  |
| [GetLinkedResourceCount](./getlinkedresourcecount/) | Gets the count of message linked resources and alternative view linked resourced. |
| [GetTextPlainView](./gettextplainview/) |  |
| [Import](./import/) | Populates a T:System::Runtime::Serialization::SerializationInfo with the data needed to serialize the target object. |
| [ImportHeaders (2 overloads)](./importheaders/) |  |
| [ListAttachmentBase](./listattachmentbase/) |  |
| [Load (4 overloads)](./load/) | Load message from stream |
| [LoadInternal (2 overloads)](./loadinternal/) | Load message from stream. NOTE!!! Call this method if you don't need to increase customer consumption credit for Dynabic.Metered. |
| [LoadMessageStructure](./loadmessagestructure/) | Loads the message structure and search text body and html body parts' indexes |
| [OnConversionProgress](./onconversionprogress/) |  |
| [RecomposeTnefContent](./recomposetnefcontent/) | Composes the TNEF content. Note, that tnef attachment is composed if a message initially contained TNEF and was loaded without FileCompatibilityMode.PreserveTnefAttachments flag, That is this method doesn't create tnef message out of the regular one. |
| [Replace](./replace/) |  |
| [Save (4 overloads)](./save/) | Save message as a stream |
| [Send](./send/) |  |
| [set_Bcc](./set_bcc/) | Sets the address collection that contains the BCC recipients of message |
| [set_Body](./set_body/) | Sets the plain text representation of message's body. If the text/plain part is present in a message, the propery returns its text data. Otherwise, property returns the text content of the HtmlBody property without html markup. |
| [set_BodyEncoding](./set_bodyencoding/) | Sets encoding of body |
| [set_Categories](./set_categories/) | Sets exchange message categories |
| [set_CC](./set_cc/) | Sets the address collection that contains the CC recipients |
| [set_Date](./set_date/) | Sets the date of message |
| [set_DeliveryNotificationOptions](./set_deliverynotificationoptions/) | Sets the delivery notifications |
| [set_Epilogue](./set_epilogue/) | Sets an epilogue text. It is located after the last boundary. |
| [set_From (2 overloads)](./set_from/) | Sets the from address |
| [set_HtmlBody](./set_htmlbody/) | Sets html body |
| [set_IsBodyHtml](./set_isbodyhtml/) | Sets a value indicating whether the message body is in Html |
| [set_IsDraft](./set_isdraft/) | Sets value that indicates whether or not a message has been sent. |
| [set_ItemId](./set_itemid/) | Represents identification information about message in a mailbox. |
| [set_ListUnsubscribe](./set_listunsubscribe/) | The List-Unsubscribe field describes the command (preferably using mail) to directly unsubscribe the user(removing them from the list). For more details please see https://tools.ietf.org/html/rfc2369 |
| [set_MessageId](./set_messageid/) | Sets the message id |
| [set_Preamble](./set_preamble/) | Sets a preamble text. It is located before the first boundary and generally includes an explanatory note to non-MIME conformant readers. |
| [set_PreferredTextEncoding](./set_preferredtextencoding/) | Sets preferred encoding for all text properties |
| [set_PreserveTnefAttachment](./set_preservetnefattachment/) | Controls TNEF attachment load/save behaviour |
| [set_Priority](./set_priority/) | Sets the priority of message |
| [set_ReadReceiptRequested](./set_readreceiptrequested/) |  |
| [set_ReadReceiptTo (2 overloads)](./set_readreceiptto/) | Sets the read receipt address. |
| [set_ReplyToList (3 overloads)](./set_replytolist/) |  |
| [set_ReversePath](./set_reversepath/) | Sets ReversePath address |
| [set_Sender (2 overloads)](./set_sender/) | Sets sender address |
| [set_Sensitivity](./set_sensitivity/) | Sets the sensitivity of message |
| [set_Subject](./set_subject/) | Sets the subject line |
| [set_SubjectEncoding](./set_subjectencoding/) | Sets the encoding of subject |
| [set_SuppressBcc](./set_suppressbcc/) | Indicates whether Bcc header is suppressed in MIME. |
| [set_TimeZoneOffset](./set_timezoneoffset/) | Sets the Coordinated Universal Time (UTC) offset for the message dates. This property defines the time zone difference, between the local time and UTC. |
| [set_TnefAttachment](./set_tnefattachment/) | Gets the tnef attachment. |
| [set_To (3 overloads)](./set_to/) |  |
| [set_XMailer](./set_xmailer/) | Sets the X-Mailer the software that created the e-mail message |
| [SetContent](./setcontent/) |  |
| [SetHtmlBody (2 overloads)](./sethtmlbody/) | Sets html body. |
| [SetMessageId](./setmessageid/) |  |
| [SetVentureLicense](./setventurelicense/) | All Aspose products should implement this method. It is called by a GroupDocs product to indicate whether GroupDocs itself is licensed or not and specify a custom watermark. When GroupDocs is licensed, this document instance should behave as licensed too even if the Aspose product is not licensed. |
| [ToString](./tostring/) | Returns a string that represents the current object. |
| [TryGetEncodingFromHtmlBody](./trygetencodingfromhtmlbody/) |  |
| [ValidateMessage (2 overloads)](./validatemessage/) | Validate eml message for corresponding to mime specification. |
| [Aspose::Email::Clients::Google::Commands::MessageAPI::V1::GetMessageCommand](./asposeemailclientsgooglecommandsmessageapiv1getmessagecommand/) |  |
| [Aspose::Email::Clients::Graph::GraphClientV1](./asposeemailclientsgraphgraphclientv1/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::CreateMailMessageCommand](./asposeemailclientsgraphv1commandscreatemailmessagecommand/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::SendMailMessageCommand](./asposeemailclientsgraphv1commandssendmailmessagecommand/) |  |
| [Aspose::Email::Clients::Graph::V1::Commands::UpdateMailMessageCommand](./asposeemailclientsgraphv1commandsupdatemailmessagecommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::FetchMessageGrCommand](./asposeemailclientsimapcommandsfetchmessagegrcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::FetchMessagesGrCommand](./asposeemailclientsimapcommandsfetchmessagesgrcommand/) |  |
| [Aspose::Email::Mapi::MailMessageInterpretor](./asposeemailmapimailmessageinterpretor/) |  |
| [Aspose::Email::Mapi::MapiMessage](./asposeemailmapimapimessage/) |  |
| [attachments](./attachments/) |  |
| [body](./body/) |  |
| [bodyEncoding](./bodyencoding/) |  |
| [bodyHtml](./bodyhtml/) |  |
| [boundaries](./boundaries/) |  |
| [ConversionProgressEvent](./conversionprogressevent/) | Event to notify user about progress of conversion/saving. |
| [deliveryStatusNotification](./deliverystatusnotification/) |  |
| [disposed](./disposed/) |  |
| [isBodyHtml](./isbodyhtml/) |  |
| [isProcessedByMboxrdStorageWriter](./isprocessedbymboxrdstoragewriter/) | The property is true, if the current message is processed by a MboxrdStorageWriter. See EMAILNET-38895 and EMAILNET-39005 |
| [linkedResources](./linkedresources/) |  |
| [message](./message/) |  |
| [views](./views/) |  |

