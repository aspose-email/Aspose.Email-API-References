---
title: "Aspose::Email::Mapi::MapiMessage class"
linktitle: "MapiMessage"
articleTitle: "MapiMessage"
second_title: "Aspose.Email for C++"
description: "Represents an Outlook Message format document that can be parsed."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapimessage/
---

## MapiMessage class

**Inherits:** Aspose::Email::Mapi::MapiMessageItemBase

Represents an Outlook Message format document that can be parsed.

Instances of the MapiMessage class are used to represent Microsoft Outlook Message document files that are parsed by MapiMessageReader class. To access the sender, recipient, and contents of an e-mail message, use the associated properties of the MapiMessage class.

The following exmaple demonstrates how to read Outlook Message files.

```csharp
 //Open Outlook Message files
 MapiMessage msg = MapiMessage.Load(@"c:\outlookmessage.msg");
 
//read subject
Console.WriteLine("Subject:" + msg.Subject);
 
//sender name
Console.WriteLine("From:" + msg.SenderName);
 
//message body
Console.WriteLine("Body:" + msg.Body);
 
//Attachments
foreach(MapiAttachment att in msg.Attachments)
{
    Console.WriteLine("Attachment Name:"+att.FileName);
    att.Save(att.FileName);
}
```

```vb
'Open Outlook Message files
Dim msg As MapiMessage = MapiMessage.Load("c:\outlookmessage.msg")
 
'read subject
Console.WriteLine("Subject:" + msg.Subject)
 
'sender name
Console.WriteLine("From:" + msg.SenderName)
 
'message body
Console.WriteLine("Body:" + msg.Body)
 
'Attachments
For Each att As MapiAttachment In msg.Attachments
    Console.WriteLine("Attachment Name:" + att.FileName)
    att.Save(att.FileName)
Next
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiMessage (7 overloads)](./mapimessage/) | Initializes a new instance of the MapiMessage class. |

## Methods

| Name | Description |
| --- | --- |
| [AddCustomProperty (2 overloads)](./addcustomproperty/) | Adds the custom property. |
| [AddEmbeddedImageToRtfBody](./addembeddedimagetortfbody/) | Adds string data that represents embedded image into rtf body. |
| [ChangeMessageClass](./changemessageclass/) | Changes the message type to the specified value. |
| [CheckBounced](./checkbounced/) | Checks whether this message can be treated as a bounce message. |
| [Clone](./clone/) | Creates a new object that is a copy of the current instance. |
| [ConvertToMapiMessage](./converttomapimessage/) | Convert item to MapiMessage . Set MessageClass, Subject, Mileage and Billing. |
| [ConvertToUnicode](./converttounicode/) | Converts ASCII message to unicode. |
| [CovertToUnicode](./coverttounicode/) |  |
| [DestroyAttachments](./destroyattachments/) | Destroies the attachments in the specified Outlook Message files. DestroyAttachments will ignore the attachment parsing. |
| [FromMailMessage (4 overloads)](./frommailmessage/) | Creates an instance of MapiMessage from the MailMessage . |
| [FromObjectData](./fromobjectdata/) | Creates the MapiMessage from the object data. |
| [FromProperties (2 overloads)](./fromproperties/) | Creates an instance of MapiMessage from a collection of Mapi properties. |
| [FromStreamInternal](./fromstreaminternal/) |  |
| [get_ClientSubmitTime](./get_clientsubmittime/) | Gets the date and time the message sender submitted a message. |
| [get_ConversationTopic](./get_conversationtopic/) | Gets the topic of the first message in a conversation thread. |
| [get_DeliveryTime](./get_deliverytime/) | Gets the date and time a message was delivered. |
| [get_DisplayBcc](./get_displaybcc/) | Gets a list of the display names of any blind carbon copy (BCC) message recipients, separated by semicolons (;). |
| [get_DisplayCc](./get_displaycc/) | Gets a list of the display names of any carbon copy (CC) message recipients, separated by semicolons (;). |
| [get_DisplayName](./get_displayname/) | Gets the display name for the message. |
| [get_DisplayNamePrefix](./get_displaynameprefix/) | Gets a prefix of the display name. |
| [get_DisplayTo](./get_displayto/) | Gets a list of the display names of the primary (To) message recipients, separated by semicolons (;). |
| [get_Flags](./get_flags/) | Gets the message flags. |
| [get_Headers](./get_headers/) | Gets the transport message headers |
| [get_InternetMessageId](./get_internetmessageid/) | Gets the message id of the message. |
| [get_IsEncrypted](./get_isencrypted/) | Gets a value indicating whether the message is encrypted. |
| [get_IsSigned](./get_issigned/) | Gets a value indicating whether the message is signed. |
| [get_IsTemplate](./get_istemplate/) | Determines whether the message is Outlook template (.oft). |
| [get_MessageFormat](./get_messageformat/) | Gets the outlook message format. |
| [get_NormalizedSubject](./get_normalizedsubject/) | Gets normalized subject of the message. |
| [get_ReadReceiptRequested](./get_readreceiptrequested/) | Gets a value indicating whether the read receipt is requested. |
| [get_ReplyTo](./get_replyto/) | Gets the reply to names. |
| [get_SenderAddressType](./get_senderaddresstype/) | Gets the message sender's e-mail address type. |
| [get_SenderEmailAddress](./get_senderemailaddress/) | Gets the message sender's e-mail address. |
| [get_SenderName](./get_sendername/) | Gets the message sender's display name. |
| [get_SenderSmtpAddress](./get_sendersmtpaddress/) | Gets the message sender's e-mail address. |
| [get_SentRepresentingAddressType](./get_sentrepresentingaddresstype/) | Gets the address type for the messaging user represented by the sender. |
| [get_SentRepresentingEmailAddress](./get_sentrepresentingemailaddress/) | Gets the e-mail address for the messaging user represented by the sender. |
| [get_SentRepresentingName](./get_sentrepresentingname/) | Gets the display name for the messaging user represented by the sender. |
| [get_SentRepresentingSmtpAddress](./get_sentrepresentingsmtpaddress/) | Gets the e-mail address for the messaging user represented by the sender. |
| [get_TransportMessageHeaders](./get_transportmessageheaders/) | Gets the transport-specific message envelope information. |
| [GetAddressType](./getaddresstype/) |  |
| [GetBlankMapiMessage](./getblankmapimessage/) |  |
| [GetCustomProperties](./getcustomproperties/) | Gets collection of custom MapiProperties. |
| [GetSize](./getsize/) | Gets the total size of message property values. |
| [ImportCalendarToMapiMessage (2 overloads)](./importcalendartomapimessage/) | Imports the iCalendar to MapiMessage . |
| [IsMsgFormat (2 overloads)](./ismsgformat/) | Determines whether the specified stream has a MSG format. |
| [Load (4 overloads)](./load/) | Loads message from stream. |
| [LoadFromTnef (2 overloads)](./loadfromtnef/) | Loads message from Transport Neutral Encapsulation Format (TNEF) data structure |
| [LoadInternal](./loadinternal/) | Loads message from stream with additional options. NOTE!!! Call this method if you don't need to increase customer consumption credit for Dynabic.Metered. |
| [MakeTemplate](./maketemplate/) |  |
| [OnConversionProgress](./onconversionprogress/) |  |
| [RemoveAttachments](./removeattachments/) | Removes all of the attachments from the specified Outlook Message files. |
| [Save (4 overloads)](./save/) | Saves to the specified stream as Msg . |
| [SaveAsTemplate (2 overloads)](./saveastemplate/) | Saves to the specified stream as Outlook File Template(OFT format). |
| [SaveAsTnef (2 overloads)](./saveastnef/) | Save message in TNEF format. |
| [set_ClientSubmitTime](./set_clientsubmittime/) | Sets the date and time the message sender submitted a message. |
| [set_DeliveryTime](./set_deliverytime/) | Sets the date and time a message was delivered. |
| [set_Headers](./set_headers/) | Gets the transport message headers |
| [set_ReadReceiptRequested](./set_readreceiptrequested/) | Sets a value indicating whether the read receipt is requested. |
| [set_ReplyTo](./set_replyto/) | Sets the reply to names. |
| [set_SenderEmailAddress](./set_senderemailaddress/) | Sets the message sender's e-mail address. |
| [set_SenderName](./set_sendername/) | Sets the message sender's display name. |
| [set_SenderSmtpAddress](./set_sendersmtpaddress/) | Sets the message sender's e-mail address. |
| [set_SentRepresentingEmailAddress](./set_sentrepresentingemailaddress/) | Sets the e-mail address for the messaging user represented by the sender. |
| [set_SentRepresentingName](./set_sentrepresentingname/) | Sets the display name for the messaging user represented by the sender. |
| [SetDateInHeaders](./setdateinheaders/) |  |
| [SetProperty (3 overloads)](./setproperty/) | Sets the attachment. |
| [SetStringPropertyValue](./setstringpropertyvalue/) | Sets the string property value. |
| [ToMailMessage](./tomailmessage/) | Creates an instance of MailMessage from this MapiMessage . |
| [ToMapiMessageItem](./tomapimessageitem/) | Convert MapiMessage to IMapiMessageItem object in dependence with MessageClass. |
| [TrySetCodePageFromRtfBody](./trysetcodepagefromrtfbody/) | Tries the set code page from RTF body. |
| [ConversionProgressEvent](./conversionprogressevent/) | Event to notify user about progress of conversion/saving. |
| [emlBoundaries](./emlboundaries/) |  |

