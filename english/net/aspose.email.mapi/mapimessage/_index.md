---
title: Class MapiMessage
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiMessage class. Represents an Outlook message the content of an MSG file
type: docs
weight: 17290
url: /net/aspose.email.mapi/mapimessage/
---
## MapiMessage class

Represents an Outlook message: the content of an MSG file.

```csharp
public sealed class MapiMessage : MapiMessageItemBase
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiMessage](mapimessage/#constructor)() | Initializes a new instance of the `MapiMessage` class: an empty message. |
| [MapiMessage](mapimessage/#constructor_1)(OutlookMessageFormat) | Initializes a new instance of the `MapiMessage` class: an empty message in the specified format. |
| [MapiMessage](mapimessage/#constructor_2)(string, string, string, string) | Initializes a new instance of the `MapiMessage` class with a sender, recipients, a subject and a body, in Unicode format. |
| [MapiMessage](mapimessage/#constructor_3)(string, string, string, string, OutlookMessageFormat) | Initializes a new instance of the `MapiMessage` class with a sender, recipients, a subject and a body, in the specified format. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments/) { get; } | Gets the attachments of the item. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing/) { get; set; } | Gets or sets the billing information of the item. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body/) { get; set; } | Gets or sets the plain-text body of the item. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml/) { get; } | Gets the body of the item as HTML, converted from [`BodyRtf`](../mapimessageitembase/bodyrtf/); an empty string when there is no RTF body. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf/) { get; set; } | Gets or sets the body of the item in RTF format. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype/) { get; } | Gets the format of the body: plain text, HTML or RTF. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories/) { get; set; } | Gets or sets the categories of the item. |
| [ClientSubmitTime](../../aspose.email.mapi/mapimessage/clientsubmittime/) { get; set; } | Gets or sets the date and time the sender sent the message. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page of the ANSI strings of the object. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies/) { get; set; } | Gets or sets the names of the companies associated with the item. |
| [ConversationTopic](../../aspose.email.mapi/mapimessage/conversationtopic/) { get; } | Gets the topic of the conversation the message belongs to: the subject of its first message, without prefixes. |
| [DeliveryTime](../../aspose.email.mapi/mapimessage/deliverytime/) { get; set; } | Gets or sets the date and time the message was delivered. |
| [DisplayBcc](../../aspose.email.mapi/mapimessage/displaybcc/) { get; } | Gets the display names of the BCC recipients, separated by semicolons (`;`). |
| [DisplayCc](../../aspose.email.mapi/mapimessage/displaycc/) { get; } | Gets the display names of the CC recipients, separated by semicolons (`;`). |
| [DisplayName](../../aspose.email.mapi/mapimessage/displayname/) { get; } | Gets the display name of the message. |
| [DisplayNamePrefix](../../aspose.email.mapi/mapimessage/displaynameprefix/) { get; } | Gets the prefix of the display name, such as a title. |
| [DisplayTo](../../aspose.email.mapi/mapimessage/displayto/) { get; } | Gets the display names of the To recipients, separated by semicolons (`;`). |
| [Flags](../../aspose.email.mapi/mapimessage/flags/) { get; } | Gets the flags of the message, such as read, unsent or has attachments. |
| [Headers](../../aspose.email.mapi/mapimessage/headers/) { get; set; } | Gets or sets the Internet headers of the message. |
| [InternetMessageId](../../aspose.email.mapi/mapimessage/internetmessageid/) { get; } | Gets the `Message-ID` of the message. |
| [IsEncrypted](../../aspose.email.mapi/mapimessage/isencrypted/) { get; } | Gets a value indicating whether the message is encrypted (S/MIME). |
| [IsSigned](../../aspose.email.mapi/mapimessage/issigned/) { get; } | Gets a value indicating whether the message is digitally signed. |
| [IsTemplate](../../aspose.email.mapi/mapimessage/istemplate/) { get; } | Gets a value indicating whether the message is an Outlook template (.oft). |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid/) { get; } | Gets the identifier of the item on the mail server, for items obtained from a server; `null` otherwise. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass/) { get; set; } | Gets or sets the message class of the item, such as `IPM.Note` for an e-mail message. The class determines the type of the item. |
| [MessageFormat](../../aspose.email.mapi/mapimessage/messageformat/) { get; } | Gets the format of the message: Unicode or ANSI. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage/) { get; set; } | Gets or sets the mileage information of the item. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties/) { get; } | Gets the named properties of the item. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping/) { get; } | Gets the mapping between the named properties and the tags they are stored under. |
| [NormalizedSubject](../../aspose.email.mapi/mapimessage/normalizedsubject/) { get; } | Gets the subject without its prefix, such as `RE:`. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets all properties of the object. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream/) { get; } | Gets the property stream of the item. |
| [ReadReceiptRequested](../../aspose.email.mapi/mapimessage/readreceiptrequested/) { get; set; } | Gets or sets a value indicating whether a read receipt is requested. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients/) { get; set; } | Gets or sets the recipients of the item. |
| [ReplyTo](../../aspose.email.mapi/mapimessage/replyto/) { get; set; } | Gets or sets the addresses that replies go to, separated by semicolons (`;`). |
| [SenderAddressType](../../aspose.email.mapi/mapimessage/senderaddresstype/) { get; } | Gets the type of the address of the sender, such as `SMTP` or `EX`. |
| [SenderEmailAddress](../../aspose.email.mapi/mapimessage/senderemailaddress/) { get; set; } | Gets or sets the message sender's e-mail address. |
| [SenderName](../../aspose.email.mapi/mapimessage/sendername/) { get; set; } | Gets or sets the message sender's display name. |
| [SenderSmtpAddress](../../aspose.email.mapi/mapimessage/sendersmtpaddress/) { get; set; } | Gets or sets the SMTP address of the sender. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity/) { get; set; } | Gets or sets the sensitivity of the item: normal, personal, private or confidential. |
| [SentRepresentingAddressType](../../aspose.email.mapi/mapimessage/sentrepresentingaddresstype/) { get; } | Gets the address type of the user on whose behalf the message was sent. |
| [SentRepresentingEmailAddress](../../aspose.email.mapi/mapimessage/sentrepresentingemailaddress/) { get; set; } | Gets or sets the e-mail address of the user on whose behalf the message was sent. |
| [SentRepresentingName](../../aspose.email.mapi/mapimessage/sentrepresentingname/) { get; set; } | Gets or sets the display name of the user on whose behalf the message was sent. |
| [SentRepresentingSmtpAddress](../../aspose.email.mapi/mapimessage/sentrepresentingsmtpaddress/) { get; } | Gets the SMTP address of the user on whose behalf the message was sent. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject/) { get; set; } | Gets or sets the subject of the message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix/) { get; } | Gets the prefix of the subject, such as `RE: ` or `FW: `. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages/) { get; } | Gets the sub-storages of the item. |
| [SupportedType](../../aspose.email.mapi/mapimessageitembase/supportedtype/) { get; } | Gets the type of the item, as determined by its message class. |
| [TransportMessageHeaders](../../aspose.email.mapi/mapimessage/transportmessageheaders/) { get; } | Gets the Internet headers of the message as one string. |

## Methods

| Name | Description |
| --- | --- |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage/#frommailmessage)(MailMessage) | Creates a message from a [`MailMessage`](../../aspose.email/mailmessage/). |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage/#frommailmessage_2)(Stream) | Creates a message from a stream in EML format. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage/#frommailmessage_3)(string) | Creates a message from an EML file. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage/#frommailmessage_1)(MailMessage, MapiConversionOptions) | Creates a message from a [`MailMessage`](../../aspose.email/mailmessage/) with the specified options. |
| static [FromProperties](../../aspose.email.mapi/mapimessage/fromproperties/)(MapiPropertyCollection) | Creates a message from a collection of MAPI properties. |
| static [Load](../../aspose.email.mapi/mapimessage/load/#load)(Stream) | Loads a message from a stream. |
| static [Load](../../aspose.email.mapi/mapimessage/load/#load_2)(string) | Loads a message from a file. |
| static [Load](../../aspose.email.mapi/mapimessage/load/#load_1)(Stream, LoadOptions) | Loads a message from a stream with the specified options. |
| static [Load](../../aspose.email.mapi/mapimessage/load/#load_3)(string, LoadOptions) | Loads a message from a file with the specified options. |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef/#loadfromtnef)(Stream) | Loads a message from a stream in TNEF format (the content of a winmail.dat attachment). |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef/#loadfromtnef_1)(string) | Loads a message from a file in TNEF format, such as winmail.dat. |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty/#addcustomproperty)(MapiProperty, string) | Adds a custom named property with a string name. |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty/#addcustomproperty_1)(MapiPropertyType, byte[], string) | Adds a custom named property with a string name. |
| [CheckBounced](../../aspose.email.mapi/mapimessage/checkbounced/)() | Checks whether the message is a bounce (a non-delivery report) and, if so, why it bounced. |
| [CheckSignature](../../aspose.email.mapi/mapimessage/checksignature/)() | Verifies the digital signature of the message. |
| [Clone](../../aspose.email.mapi/mapimessage/clone/)() | Creates a copy of the message. |
| [Decrypt](../../aspose.email.mapi/mapimessage/decrypt/#decrypt)() | Decrypts the message with a certificate found in the certificate store. |
| [Decrypt](../../aspose.email.mapi/mapimessage/decrypt/#decrypt_1)(X509Certificate2) | Decrypts the message with the specified certificate. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose/)() | Releases the resources used by the item. |
| [GetCustomProperties](../../aspose.email.mapi/mapimessage/getcustomproperties/)() | Gets the custom named properties of the message. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty/)(PropertyDescriptor) | Gets a MAPI property of the item by its descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of a property as a Boolean. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the value of a property as bytes. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of a property as a date and time. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the value of a property as a 32-bit integer. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of a property as a 64-bit integer. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of a property as a 16-bit integer. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long) | Gets the value of a property as a string. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines whether the string properties of the object are stored in Unicode. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty/)(long) | Removes a property from the item, including its named-property mapping. |
| [RemoveSignature](../../aspose.email.mapi/mapimessage/removesignature/)() | Returns a copy of a signed message without the signature. |
| [Save](../../aspose.email.mapi/mapimessage/save/#save)(Stream) | Saves the message to a stream in MSG format. |
| [Save](../../aspose.email.mapi/mapimessage/save/#save_2)(string) | Saves the message to a file in MSG format. |
| [Save](../../aspose.email.mapi/mapimessage/save/#save_1)(Stream, SaveOptions) | Saves the message to a stream in the format selected by the options, such as MSG, OFT, EML, EMLX, HTML or MHTML. |
| [Save](../../aspose.email.mapi/mapimessage/save/#save_3)(string, SaveOptions) | Saves the message to a file in the format selected by the options, such as MSG, OFT, EML, EMLX, HTML or MHTML. |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef/#saveastnef)(Stream) | Saves the message to a stream in TNEF format (the format of winmail.dat). |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef/#saveastnef_1)(string) | Saves the message to a file in TNEF format (the format of winmail.dat). |
| [SaveAsync](../../aspose.email.mapi/mapimessage/saveasync/#saveasync_1)(Stream, CancellationToken) | Saves this `MapiMessage` to the specified stream asynchronously. |
| [SaveAsync](../../aspose.email.mapi/mapimessage/saveasync/#saveasync_3)(string, CancellationToken) | Saves this `MapiMessage` to the specified file asynchronously. |
| [SaveAsync](../../aspose.email.mapi/mapimessage/saveasync/#saveasync)(Stream, SaveOptions, CancellationToken) | Saves this `MapiMessage` to the specified stream with specified options asynchronously. |
| [SaveAsync](../../aspose.email.mapi/mapimessage/saveasync/#saveasync_2)(string, SaveOptions, CancellationToken) | Saves this `MapiMessage` to the specified file with specified options asynchronously. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType) | Sets the body of the item in the specified format. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType, bool) | Sets the body of the item in the specified format, optionally compressing it. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf/)(string, bool) | Sets the body of the item in RTF format, optionally compressing it. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags/)(MapiMessageFlags) | Sets the flags of the message, such as read or unsent. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(MapiProperty) | Adds the property, or replaces the property with the same tag. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty/)(PropertyDescriptor, object) | Sets the value of a MAPI property of the item. |
| [SetStringPropertyValue](../../aspose.email.mapi/mapimessage/setstringpropertyvalue/)(long, string) | Sets the value of a string property, in the string format of the message (Unicode or ANSI). |
| [ToMailMessage](../../aspose.email.mapi/mapimessage/tomailmessage/)(MailConversionOptions) | Converts the message to a [`MailMessage`](../../aspose.email/mailmessage/) with the specified options. |
| [ToMapiMessageItem](../../aspose.email.mapi/mapimessage/tomapimessageitem/)() | Converts the message to the item class that matches its message class, such as [`MapiContact`](../mapicontact/) for `IPM.Contact`. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Gets the value of a property as bytes. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of a property as a date and time, if the property exists. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long) | Gets the value of a property as a string. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string) | Gets the value of a property as a string, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string, int) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |
| static [DestroyAttachments](../../aspose.email.mapi/mapimessage/destroyattachments/)(string) | Removes all attachments from an MSG file and overwrites the file. The attachments are not read, which is faster than [`RemoveAttachments`](./removeattachments/). |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat/#ismsgformat)(Stream) | Determines whether a stream contains a message in MSG format. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat/#ismsgformat_1)(string) | Determines whether a file is in MSG format. |
| static [LoadAsync](../../aspose.email.mapi/mapimessage/loadasync/#loadasync_1)(Stream, CancellationToken) | Loads a `MapiMessage` from the specified stream asynchronously. |
| static [LoadAsync](../../aspose.email.mapi/mapimessage/loadasync/#loadasync_3)(string, CancellationToken) | Loads a `MapiMessage` from the specified file asynchronously. |
| static [LoadAsync](../../aspose.email.mapi/mapimessage/loadasync/#loadasync)(Stream, LoadOptions, CancellationToken) | Loads a `MapiMessage` from the specified stream with specified options asynchronously. |
| static [LoadAsync](../../aspose.email.mapi/mapimessage/loadasync/#loadasync_2)(string, LoadOptions, CancellationToken) | Loads a `MapiMessage` from the specified file with specified options asynchronously. |
| static [RemoveAttachments](../../aspose.email.mapi/mapimessage/removeattachments/)(string) | Removes all attachments from an MSG file, overwrites the file, and returns the removed attachments. |

## Remarks

Load a message with [`Load`](./load/), create one with a constructor or from a [`MailMessage`](../../aspose.email/mailmessage/) with [`FromMailMessage`](./frommailmessage/), and save it with [`Save`](./save/). Other Outlook items stored in MSG files — contacts, appointments, tasks and so on — load as a `MapiMessage` too; [`ToMapiMessageItem`](./tomapimessageitem/) converts them to the matching class.

## Examples

The following exmaple demonstrates how to read Outlook Message files.

[C#]

```csharp
//Open Outlook Message files
MapiMessage msg = MapiMessage.Load(@"c:\outlookmessage.msg");

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

### See Also

* class [MapiMessageItemBase](../mapimessageitembase/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


