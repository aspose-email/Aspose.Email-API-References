---
title: MapiMessage
second_title: Aspose.Email for .NET API Reference
description: Represents an Outlook Message format document that can be parsed.
type: docs
weight: 18470
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
| [MapiMessage](mapimessage#constructor)() | Initializes a new instance of the [`MapiMessage`](../mapimessage) class. |
| [MapiMessage](mapimessage#constructor_1)(OutlookMessageFormat) | Initializes a new instance of the [`MapiMessage`](../mapimessage) class. |
| [MapiMessage](mapimessage#constructor_2)(string, string, string, string) | Initializes a new instance of the [`MapiMessage`](../mapimessage) class. |
| [MapiMessage](mapimessage#constructor_3)(string, string, string, string, OutlookMessageFormat) | Initializes a new instance of the [`MapiMessage`](../mapimessage) class. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Gets the attachments in the message. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contains the billing information associated with an item. |
| [Body](../../aspose.email.mapi/mapimessage/body) { get; set; } | Gets the message text. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Gets the [`BodyRtf`](../mapimessageitembase/bodyrtf) of the message converted to HTML, if present, otherwise an empty string. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Gets or sets the RTF formatted message text. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Gets the type of the body. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contains keywords or categories for the message object. |
| [ClientSubmitTime](../../aspose.email.mapi/mapimessage/clientsubmittime) { get; set; } | Gets or sets the date and time the message sender submitted a message. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Gets the code page. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contains the names of the companies that are associated with an item. |
| [ConversationTopic](../../aspose.email.mapi/mapimessage/conversationtopic) { get; } | Gets the topic of the first message in a conversation thread. |
| [DeliveryTime](../../aspose.email.mapi/mapimessage/deliverytime) { get; set; } | Gets or sets the date and time a message was delivered. |
| [DisplayBcc](../../aspose.email.mapi/mapimessage/displaybcc) { get; } | Gets a list of the display names of any blind carbon copy (BCC) message recipients, separated by semicolons (;). |
| [DisplayCc](../../aspose.email.mapi/mapimessage/displaycc) { get; } | Gets a list of the display names of any carbon copy (CC) message recipients, separated by semicolons (;). |
| [DisplayName](../../aspose.email.mapi/mapimessage/displayname) { get; } | Gets the display name for the message. |
| [DisplayNamePrefix](../../aspose.email.mapi/mapimessage/displaynameprefix) { get; } | Gets a prefix of the display name. |
| [DisplayTo](../../aspose.email.mapi/mapimessage/displayto) { get; } | Gets a list of the display names of the primary (To) message recipients, separated by semicolons (;). |
| [Flags](../../aspose.email.mapi/mapimessage/flags) { get; } | Gets the message flags. |
| [Headers](../../aspose.email.mapi/mapimessage/headers) { get; set; } | Gets the transport message headers |
| [InternetMessageId](../../aspose.email.mapi/mapimessage/internetmessageid) { get; } | Gets the message id of the message. |
| [IsSigned](../../aspose.email.mapi/mapimessage/issigned) { get; } | Gets a value indicating whether the message is signed. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | The item id, uses with a server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message. |
| [MessageFormat](../../aspose.email.mapi/mapimessage/messageformat) { get; } | Gets the outlook message format. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contains the mileage information that is associated with an item. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Gets the named properties of message. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Gets the named property mapping. |
| [NormalizedSubject](../../aspose.email.mapi/mapimessage/normalizedsubject) { get; } | Gets normalized subject of the message. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Gets the collection of properties. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Gets the property stream. |
| [ReadReceiptRequested](../../aspose.email.mapi/mapimessage/readreceiptrequested) { get; set; } | Gets or sets a value indicating whether the read receipt is requested. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Gets the recipients of the message. |
| [ReplyTo](../../aspose.email.mapi/mapimessage/replyto) { get; set; } | Gets or sets the reply to names. |
| [SenderAddressType](../../aspose.email.mapi/mapimessage/senderaddresstype) { get; } | Gets the message sender's e-mail address type. |
| [SenderEmailAddress](../../aspose.email.mapi/mapimessage/senderemailaddress) { get; set; } | Gets or sets the message sender's e-mail address. |
| [SenderName](../../aspose.email.mapi/mapimessage/sendername) { get; set; } | Gets or sets the message sender's display name. |
| [SenderSmtpAddress](../../aspose.email.mapi/mapimessage/sendersmtpaddress) { get; set; } | Gets or sets the message sender's e-mail address. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Gets the Sensitivity. |
| [SentRepresentingAddressType](../../aspose.email.mapi/mapimessage/sentrepresentingaddresstype) { get; } | Gets the address type for the messaging user represented by the sender. |
| [SentRepresentingEmailAddress](../../aspose.email.mapi/mapimessage/sentrepresentingemailaddress) { get; set; } | Gets or sets the e-mail address for the messaging user represented by the sender. |
| [SentRepresentingName](../../aspose.email.mapi/mapimessage/sentrepresentingname) { get; set; } | Gets or sets the display name for the messaging user represented by the sender. |
| [SentRepresentingSmtpAddress](../../aspose.email.mapi/mapimessage/sentrepresentingsmtpaddress) { get; } | Gets or sets the e-mail address for the messaging user represented by the sender. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Gets or sets the subject of the message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Gets the sub storages. |
| [SupportedType](../../aspose.email.mapi/mapimessageitembase/supportedtype) { get; } | Gets the supported item type. |
| [TransportMessageHeaders](../../aspose.email.mapi/mapimessage/transportmessageheaders) { get; } | Gets the transport-specific message envelope information. |

## Methods

| Name | Description |
| --- | --- |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage)(MailMessage) | Creates an instance of MapiMessage from the MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_2)(string) | Creates an instance of MapiMessage from the MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_1)(MailMessage, MapiConversionOptions) | Creates an instance of MapiMessage from the MailMessage. |
| static [FromProperties](../../aspose.email.mapi/mapimessage/fromproperties)(MapiPropertyCollection) | Creates an instance of MapiMessage from a collection of Mapi properties. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load)(Stream) | Loads message from stream. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_2)(string) | Loads message from file. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_1)(Stream, LoadOptions) | Loads message from stream with additional options. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_3)(string, LoadOptions) | Loads message from file with additional options. |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef)(Stream) | Loads message from Transport Neutral Encapsulation Format (TNEF) data structure |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef_1)(string) | Loads message from Transport Neutral Encapsulation Format (TNEF) data structure |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty)(MapiProperty, string) | Adds the custom property. |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty_1)(MapiPropertyType, byte[], string) | Adds the custom property. |
| [CheckBounced](../../aspose.email.mapi/mapimessage/checkbounced)() | Checks whether this message can be treated as a bounce message. |
| [Clone](../../aspose.email.mapi/mapimessage/clone)() | Creates a new object that is a copy of the current instance. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [GetCustomProperties](../../aspose.email.mapi/mapimessage/getcustomproperties)() | Gets collection of custom MapiProperties. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Gets MAPI property by property descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Gets the value of the property specified by tag as Boolean type. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Gets the value of the property specified by tag as DateTime type. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Gets the int32 value of the property specified by tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Gets the value of the property specified by tag as Long (int64) type. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Gets the value of the property specified by tag as Short type. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Gets the string value of the property specified by tag. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determines if string properties are Unicode encoded or not. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Provides correctly removing property from all collections. |
| [RemoveSignature](../../aspose.email.mapi/mapimessage/removesignature)() | Remove signature. |
| [Save](../../aspose.email.mapi/mapimessage/save#save)(Stream) | Saves to the specified stream as Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_2)(string) | Saves to the specified file as Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_1)(Stream, SaveOptions) | Saves message as a stream with additional options. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_3)(string, SaveOptions) | Saves message as a file with additional options. |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate)(Stream) | Saves to the specified stream as Outlook File Template(OFT format). |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate_1)(string) | Saves to the specified file as Outlook File Template(OFT format). |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef)(Stream) | Save message in TNEF format. |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef_1)(string) | Save message in TNEF format. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Sets the content of the body. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Sets the content of the body. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Gets or sets the RTF formatted message text. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Sets the message flags. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Sets the property. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Sets MAPI property. |
| [SetStringPropertyValue](../../aspose.email.mapi/mapimessage/setstringpropertyvalue)(long, string) | Sets the string property value. |
| [ToMailMessage](../../aspose.email.mapi/mapimessage/tomailmessage)(MailConversionOptions) | Creates an instance of MailMessage from this MapiMessage. |
| [ToMapiMessageItem](../../aspose.email.mapi/mapimessage/tomapimessageitem)() | Convert MapiMessage to IMapiMessageItem object in dependence with MessageClass. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Try to get the property data with specified tag key. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Gets the value of the specified property as DateTime type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Gets the value of the specified property as Int32 type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Gets the value of the specified property as Long type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Try to get a property data as string with specified tag. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Try to get a property data as string with specified tag and code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |
| static [DestroyAttachments](../../aspose.email.mapi/mapimessage/destroyattachments)(string) | Destroies the attachments in the specified Outlook Message files. DestroyAttachments will ignore the attachment parsing. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat)(Stream) | Determines whether the specified stream has a MSG format. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat_1)(string) | Determines whether the specified file has a MSG format. |
| static [RemoveAttachments](../../aspose.email.mapi/mapimessage/removeattachments)(string) | Removes all of the attachments from the specified Outlook Message files. |

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
