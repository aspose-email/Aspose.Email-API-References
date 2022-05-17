---
title: MapiMessage
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 18250
url: /net/aspose.email.mapi/mapimessage/
---
## MapiMessage class

Represents an Outlook Message format document that can be parsed.

```csharp
public sealed class MapiMessage : MapiMessageItemBase
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiMessage](mapimessage)() | Initializes a new instance of the [`MapiMessage`](../mapimessage) class. |
| [MapiMessage](mapimessage)(OutlookMessageFormat) | Initializes a new instance of the [`MapiMessage`](../mapimessage) class. |
| [MapiMessage](mapimessage)(string, string, string, string) | Initializes a new instance of the [`MapiMessage`](../mapimessage) class. |
| [MapiMessage](mapimessage)(string, string, string, string, OutlookMessageFormat) | Initializes a new instance of the [`MapiMessage`](../mapimessage) class. |

## Properties

| Name | Description |
| --- | --- |
| [Body](body) { get; set; } | Gets the message text. |
| [ClientSubmitTime](clientsubmittime) { get; set; } | Gets or sets the date and time the message sender submitted a message. |
| [ConversationTopic](conversationtopic) { get; } | Gets the topic of the first message in a conversation thread. |
| [DeliveryTime](deliverytime) { get; set; } | Gets or sets the date and time a message was delivered. |
| [DisplayBcc](displaybcc) { get; } | Gets a list of the display names of any blind carbon copy (BCC) message recipients, separated by semicolons (;). |
| [DisplayCc](displaycc) { get; } | Gets a list of the display names of any carbon copy (CC) message recipients, separated by semicolons (;). |
| [DisplayName](displayname) { get; } | Gets the display name for the message. |
| [DisplayNamePrefix](displaynameprefix) { get; } | Gets a prefix of the display name. |
| [DisplayTo](displayto) { get; } | Gets a list of the display names of the primary (To) message recipients, separated by semicolons (;). |
| [Flags](flags) { get; } | Gets the message flags. |
| [Headers](headers) { get; set; } | Gets the transport message headers |
| [InternetMessageId](internetmessageid) { get; } | Gets the message id of the message. |
| [MessageFormat](messageformat) { get; } | Gets the outlook message format. |
| [NormalizedSubject](normalizedsubject) { get; } | Gets normalized subject of the message. |
| [ReadReceiptRequested](readreceiptrequested) { get; set; } | Gets or sets a value indicating whether the read receipt is requested. |
| [ReplyTo](replyto) { get; set; } | Gets or sets the reply to names. |
| [SenderAddressType](senderaddresstype) { get; } | Gets the message sender's e-mail address type. |
| [SenderEmailAddress](senderemailaddress) { get; set; } | Gets or sets the message sender's e-mail address. |
| [SenderName](sendername) { get; set; } | Gets or sets the message sender's display name. |
| [SenderSmtpAddress](sendersmtpaddress) { get; set; } | Gets or sets the message sender's e-mail address. |
| [SentRepresentingAddressType](sentrepresentingaddresstype) { get; } | Gets the address type for the messaging user represented by the sender. |
| [SentRepresentingEmailAddress](sentrepresentingemailaddress) { get; set; } | Gets or sets the e-mail address for the messaging user represented by the sender. |
| [SentRepresentingName](sentrepresentingname) { get; set; } | Gets or sets the display name for the messaging user represented by the sender. |
| [SentRepresentingSmtpAddress](sentrepresentingsmtpaddress) { get; } | Gets or sets the e-mail address for the messaging user represented by the sender. |
| [TransportMessageHeaders](transportmessageheaders) { get; } | Gets the transport-specific message envelope information. |

## Methods

| Name | Description |
| --- | --- |
| static [FromMailMessage](frommailmessage)(MailMessage) | Creates an instance of MapiMessage from the MailMessage. |
| static [FromMailMessage](frommailmessage)(string) | Creates an instance of MapiMessage from the MailMessage. |
| static [FromMailMessage](frommailmessage)(MailMessage, MapiConversionOptions) | Creates an instance of MapiMessage from the MailMessage. |
| static [FromProperties](fromproperties)(MapiPropertyCollection) | Creates an instance of MapiMessage from a collection of Mapi properties. |
| static [Load](load)(Stream) | Loads message from stream. |
| static [Load](load)(string) | Loads message from file. |
| static [Load](load)(Stream, LoadOptions) | Loads message from stream with additional options. |
| static [Load](load)(string, LoadOptions) | Loads message from file with additional options. |
| static [LoadFromTnef](loadfromtnef)(Stream) | Loads message from Transport Neutral Encapsulation Format (TNEF) data structure |
| static [LoadFromTnef](loadfromtnef)(string) | Loads message from Transport Neutral Encapsulation Format (TNEF) data structure |
| [AddCustomProperty](addcustomproperty)(MapiProperty, string) | Adds the custom property. |
| [AddCustomProperty](addcustomproperty)(MapiPropertyType, byte[], string) | Adds the custom property. |
| [CheckBounced](checkbounced)() | Checks whether this message can be treated as a bounce message. |
| [Clone](clone)() | Creates a new object that is a copy of the current instance. |
| [GetCustomProperties](getcustomproperties)() | Gets collection of custom MapiProperties. |
| [Save](save)(Stream) | Saves to the specified stream as Msg. |
| [Save](save)(string) | Saves to the specified file as Msg. |
| [Save](save)(Stream, SaveOptions) | Saves message as a stream with additional options. |
| [Save](save)(string, SaveOptions) | Saves message as a file with additional options. |
| [SaveAsTemplate](saveastemplate)(Stream) | Saves to the specified stream as Outlook File Template(OFT format). |
| [SaveAsTemplate](saveastemplate)(string) | Saves to the specified file as Outlook File Template(OFT format). |
| [SaveAsTnef](saveastnef)(Stream) | Save message in TNEF format. |
| [SaveAsTnef](saveastnef)(string) | Save message in TNEF format. |
| [SetStringPropertyValue](setstringpropertyvalue)(long, string) | Sets the string property value. |
| [ToMailMessage](tomailmessage)(MailConversionOptions) | Creates an instance of MailMessage from this MapiMessage. |
| [ToMapiMessageItem](tomapimessageitem)() | Convert MapiMessage to IMapiMessageItem object in dependence with MessageClass. |
| static [DestroyAttachments](destroyattachments)(string) | Destroies the attachments in the specified Outlook Message files. DestroyAttachments will ignore the attachment parsing. |
| static [IsMsgFormat](ismsgformat)(Stream) | Determines whether the specified stream has a MSG format. |
| static [IsMsgFormat](ismsgformat)(string) | Determines whether the specified file has a MSG format. |
| static [RemoveAttachments](removeattachments)(string) | Removes all of the attachments from the specified Outlook Message files. |

### Remarks

Instances of the MapiMessage class are used to represent Microsoft Outlook Message document files that are parsed by MapiMessageReader class. To access the sender, recipient, and contents of an e-mail message, use the associated properties of the MapiMessage class.

### Examples

The following exmaple demonstrates how to read Outlook Message files.

[C#]

```csharp
//Open Outlook Message files
MapiMessage msg = MapiMessage.FromFile(@"c:\outlookmessage.msg");

/read subject
onsole.WriteLine("Subject:" + msg.Subject);

/sender name
onsole.WriteLine("From:" + msg.SenderName);

/message body
onsole.WriteLine("Body:" + msg.Body);

/Attachments
oreach(MapiAttachment att in msg.Attachments)

   Console.WriteLine("Attachment Name:"+att.FileName);
   att.Save(att.FileName);
    
```

[Visual Basic]

```csharp
'Open Outlook Message files 
Dim msg As MapiMessage = MapiMessage.FromFile("c:\outlookmessage.msg") 

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

### See Also

* class [MapiMessageItemBase](../mapimessageitembase)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
