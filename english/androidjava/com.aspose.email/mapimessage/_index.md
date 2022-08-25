---
title: MapiMessage
second_title: Aspose.Email for Android via Java API Reference
description:   Represents an Outlook Message format document that can be parsed.
type: docs
weight: 256
url: /java/com.aspose.email/mapimessage/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiMessage extends MapiMessageItemBase
```

Represents an Outlook Message format document that can be parsed.

--------------------

> The following exmaple demonstrates how to read Outlook Message files.
> 
> [Java]
> 
> ```
> //Open Outlook Message files
>   MapiMessage msg = MapiMessage.fromFile("outlookmessage.msg");
> 
>   //read subject
>   System.out.print("Subject:" + msg.getSubject());
> 
>   //sender name
>   System.out.print("From:" + msg.getSenderName());
> 
>   //message body
>   System.out.print("Body:" + msg.getBody());
> 
>   //Attachments
>   for(MapiAttachment att : msg.getAttachments())
>   {
>       System.out.print("Attachment Name:"+att.getFileName());
>       att.save(att.getFileName());
>   }
> ```

--------------------

Instances of the MapiMessage class are used to represent Microsoft Outlook Message document files that are parsed by MapiMessageReader class. To access the sender, recipient, and contents of an e-mail message, use the associated properties of the MapiMessage class.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiMessage()](#MapiMessage--) | Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class. |
| [MapiMessage(int format)](#MapiMessage-int-) | Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class. |
| [MapiMessage(String from, String to, String subject, String body, int format)](#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-int-) | Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class. |
| [MapiMessage(String from, String to, String subject, String body)](#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class. |
## Methods

| Method | Description |
| --- | --- |
| [getBody()](#getBody--) | Gets the message text. |
| [setBody(String value)](#setBody-java.lang.String-) | Gets the message text. |
| [getReplyTo()](#getReplyTo--) | Gets or sets the reply to names. |
| [setReplyTo(String value)](#setReplyTo-java.lang.String-) | Gets or sets the reply to names. |
| [getNormalizedSubject()](#getNormalizedSubject--) | Gets normalized subject of the message. |
| [getDisplayTo()](#getDisplayTo--) | Gets a list of the display names of the primary (To) message recipients, separated by semicolons (;). |
| [getDisplayNamePrefix()](#getDisplayNamePrefix--) | Gets a prefix of the display name. |
| [getDisplayName()](#getDisplayName--) | Gets the display name for the message. |
| [getDisplayCc()](#getDisplayCc--) | Gets a list of the display names of any carbon copy (CC) message recipients, separated by semicolons (;). |
| [getDisplayBcc()](#getDisplayBcc--) | Gets a list of the display names of any blind carbon copy (BCC) message recipients, separated by semicolons (;). |
| [getSenderEmailAddress()](#getSenderEmailAddress--) | Gets or sets the message sender's e-mail address. |
| [setSenderEmailAddress(String value)](#setSenderEmailAddress-java.lang.String-) | Gets or sets the message sender's e-mail address. |
| [getSenderSmtpAddress()](#getSenderSmtpAddress--) | Gets or sets the message sender's e-mail address. |
| [setSenderSmtpAddress(String value)](#setSenderSmtpAddress-java.lang.String-) | Gets or sets the message sender's e-mail address. |
| [getSenderAddressType()](#getSenderAddressType--) | Gets the message sender's e-mail address type. |
| [getSenderName()](#getSenderName--) | Gets or sets the message sender's display name. |
| [setSenderName(String value)](#setSenderName-java.lang.String-) | Gets or sets the message sender's display name. |
| [getTransportMessageHeaders()](#getTransportMessageHeaders--) | Gets the transport-specific message envelope information. |
| [getInternetMessageId()](#getInternetMessageId--) | Gets the message id of the message. |
| [getConversationTopic()](#getConversationTopic--) | Gets the topic of the first message in a conversation thread. |
| [getSentRepresentingEmailAddress()](#getSentRepresentingEmailAddress--) | Gets or sets the e-mail address for the messaging user represented by the sender. |
| [setSentRepresentingEmailAddress(String value)](#setSentRepresentingEmailAddress-java.lang.String-) | Gets or sets the e-mail address for the messaging user represented by the sender. |
| [getSentRepresentingSmtpAddress()](#getSentRepresentingSmtpAddress--) | Gets or sets the e-mail address for the messaging user represented by the sender. |
| [getSentRepresentingAddressType()](#getSentRepresentingAddressType--) | Gets the address type for the messaging user represented by the sender. |
| [getSentRepresentingName()](#getSentRepresentingName--) | Gets or sets the display name for the messaging user represented by the sender. |
| [setSentRepresentingName(String value)](#setSentRepresentingName-java.lang.String-) | Gets or sets the display name for the messaging user represented by the sender. |
| [getClientSubmitTime()](#getClientSubmitTime--) | Gets or sets the date and time the message sender submitted a message. |
| [setClientSubmitTime(Date value)](#setClientSubmitTime-java.util.Date-) | Gets or sets the date and time the message sender submitted a message. |
| [getDeliveryTime()](#getDeliveryTime--) | Gets or sets the date and time a message was delivered. |
| [setDeliveryTime(Date value)](#setDeliveryTime-java.util.Date-) | Gets or sets the date and time a message was delivered. |
| [getHeaders()](#getHeaders--) | Gets the transport message headers |
| [setHeaders(HeaderCollection value)](#setHeaders-com.aspose.email.HeaderCollection-) | Gets the transport message headers |
| [getFlags()](#getFlags--) | Gets the message flags. |
| [getReadReceiptRequested()](#getReadReceiptRequested--) | Gets or sets a value indicating whether the read receipt is requested. |
| [setReadReceiptRequested(boolean value)](#setReadReceiptRequested-boolean-) | Gets or sets a value indicating whether the read receipt is requested. |
| [getMessageFormat()](#getMessageFormat--) | Gets the outlook message format. |
| [load(String fileName)](#load-java.lang.String-) | Loads message from file. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads message from stream. |
| [load(InputStream stream, LoadOptions options)](#load-java.io.InputStream-com.aspose.email.LoadOptions-) | Loads message from stream with additional options. |
| [load(String fileName, LoadOptions options)](#load-java.lang.String-com.aspose.email.LoadOptions-) | Loads message from file with additional options. |
| [fromFile(String path)](#fromFile-java.lang.String-) | Create an instance of MapiMessage from the specified file. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Create an instance of MapiMessage from the specified stream. |
| [fromProperties(MapiPropertyCollection properties)](#fromProperties-com.aspose.email.MapiPropertyCollection-) | Creates an instance of MapiMessage from a collection of Mapi properties. |
| [fromMailMessage(String fileName)](#fromMailMessage-java.lang.String-) | Creates an instance of MapiMessage from the MailMessage. |
| [fromMailMessage(MailMessage message)](#fromMailMessage-com.aspose.email.MailMessage-) | Creates an instance of MapiMessage from the MailMessage. |
| [fromMailMessage(MailMessage message, MapiConversionOptions options)](#fromMailMessage-com.aspose.email.MailMessage-com.aspose.email.MapiConversionOptions-) | Creates an instance of MapiMessage from the MailMessage. |
| [removeAttachments(String path)](#removeAttachments-java.lang.String-) | Removes all of the attachments from the specified Outlook Message files. |
| [destroyAttachments(String path)](#destroyAttachments-java.lang.String-) | Destroies the attachments in the specified Outlook Message files. |
| [loadFromTnef(InputStream stream)](#loadFromTnef-java.io.InputStream-) | Loads message from Transport Neutral Encapsulation Format (TNEF) data structure |
| [loadFromTnef(String fileName)](#loadFromTnef-java.lang.String-) | Loads message from Transport Neutral Encapsulation Format (TNEF) data structure |
| [isMsgFormat(String fileName)](#isMsgFormat-java.lang.String-) | Determines whether the specified file has a MSG format. |
| [isMsgFormat(InputStream stream)](#isMsgFormat-java.io.InputStream-) | Determines whether the specified stream has a MSG format. |
| [setStringPropertyValue(long tag, String value)](#setStringPropertyValue-long-java.lang.String-) | Sets the string property value. |
| [addCustomProperty(MapiProperty property, String stringNameId)](#addCustomProperty-com.aspose.email.MapiProperty-java.lang.String-) | Adds the custom property. |
| [addCustomProperty(int type, byte[] data, String stringNameId)](#addCustomProperty-int-byte---java.lang.String-) | Adds the custom property. |
| [getCustomProperties()](#getCustomProperties--) | Gets collection of custom MapiProperties. |
| [toMapiMessageItem()](#toMapiMessageItem--) | Convert MapiMessage to IMapiMessageItem object in dependence with MessageClass. |
| [toMailMessage(MailConversionOptions options)](#toMailMessage-com.aspose.email.MailConversionOptions-) | Creates an instance of MailMessage from this MapiMessage. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.email.SaveOptions-) | Saves message as a file with additional options. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.email.SaveOptions-) | Saves message as a stream with additional options. |
| [saveAsTnef(OutputStream stream)](#saveAsTnef-java.io.OutputStream-) | Save message in TNEF format. |
| [saveAsTnef(String fileName)](#saveAsTnef-java.lang.String-) | Save message in TNEF format. |
| [save(String fileName)](#save-java.lang.String-) | Saves to the specified file as Msg. |
| [saveAsTemplate(String fileName)](#saveAsTemplate-java.lang.String-) | Saves to the specified file as Outlook File Template(OFT format). |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves to the specified stream as Msg. |
| [saveAsTemplate(OutputStream stream)](#saveAsTemplate-java.io.OutputStream-) | Saves to the specified stream as Outlook File Template(OFT format). |
| [checkBounced()](#checkBounced--) | Checks whether this message can be treated as a bounce message. |
| [deepClone()](#deepClone--) | Creates a new object that is a copy of the current instance. |
| [setProperty(MapiAttachment value, long signed, long key)](#setProperty-com.aspose.email.MapiAttachment-long-long-) | Sets the attachment. |
| [setProperty(MapiRecipient value, long signed, long key)](#setProperty-com.aspose.email.MapiRecipient-long-long-) | Sets the recipient. |
### MapiMessage() {#MapiMessage--}
```
public MapiMessage()
```


Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class.

### MapiMessage(int format) {#MapiMessage-int-}
```
public MapiMessage(int format)
```


Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | Defines whether to use Unicode or ASCII encoding for this message. |

### MapiMessage(String from, String to, String subject, String body, int format) {#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-int-}
```
public MapiMessage(String from, String to, String subject, String body, int format)
```


Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | The From address. |
| to | java.lang.String | The addresses of recipients. Note, that addresses are separated by semicolon. |
| subject | java.lang.String | The message subject. |
| body | java.lang.String | The message body. |
| format | int | Defines whether to use Unicode or ASCII encoding for this message. |

### MapiMessage(String from, String to, String subject, String body) {#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public MapiMessage(String from, String to, String subject, String body)
```


Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | The From address. |
| to | java.lang.String | The addresses of recipients. Note, that addresses are separated by semicolon. |
| subject | java.lang.String | The message subject. |
| body | java.lang.String | The message body. |

### getBody() {#getBody--}
```
public final String getBody()
```


Gets the message text.

Value: The string that represents message body.

**Returns:**
java.lang.String
### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Gets the message text.

Value: The string that represents message body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getReplyTo() {#getReplyTo--}
```
public final String getReplyTo()
```


Gets or sets the reply to names.

**Returns:**
java.lang.String
### setReplyTo(String value) {#setReplyTo-java.lang.String-}
```
public final void setReplyTo(String value)
```


Gets or sets the reply to names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNormalizedSubject() {#getNormalizedSubject--}
```
public final String getNormalizedSubject()
```


Gets normalized subject of the message.

Value: The string that represents normalized subject.

**Returns:**
java.lang.String
### getDisplayTo() {#getDisplayTo--}
```
public final String getDisplayTo()
```


Gets a list of the display names of the primary (To) message recipients, separated by semicolons (;).

Value: The string that represents display to.

**Returns:**
java.lang.String
### getDisplayNamePrefix() {#getDisplayNamePrefix--}
```
public final String getDisplayNamePrefix()
```


Gets a prefix of the display name.

Value: The string that represents display name prefix.

**Returns:**
java.lang.String
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the display name for the message.

Value: The string that represents display name.

**Returns:**
java.lang.String
### getDisplayCc() {#getDisplayCc--}
```
public final String getDisplayCc()
```


Gets a list of the display names of any carbon copy (CC) message recipients, separated by semicolons (;).

Value: The string that represents display cc.

**Returns:**
java.lang.String
### getDisplayBcc() {#getDisplayBcc--}
```
public final String getDisplayBcc()
```


Gets a list of the display names of any blind carbon copy (BCC) message recipients, separated by semicolons (;).

Value: The string that represents display bcc.

**Returns:**
java.lang.String
### getSenderEmailAddress() {#getSenderEmailAddress--}
```
public final String getSenderEmailAddress()
```


Gets or sets the message sender's e-mail address.

**Returns:**
java.lang.String
### setSenderEmailAddress(String value) {#setSenderEmailAddress-java.lang.String-}
```
public final void setSenderEmailAddress(String value)
```


Gets or sets the message sender's e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSenderSmtpAddress() {#getSenderSmtpAddress--}
```
public final String getSenderSmtpAddress()
```


Gets or sets the message sender's e-mail address.

**Returns:**
java.lang.String
### setSenderSmtpAddress(String value) {#setSenderSmtpAddress-java.lang.String-}
```
public final void setSenderSmtpAddress(String value)
```


Gets or sets the message sender's e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSenderAddressType() {#getSenderAddressType--}
```
public final String getSenderAddressType()
```


Gets the message sender's e-mail address type.

Value: The string that represents sender address type.

**Returns:**
java.lang.String
### getSenderName() {#getSenderName--}
```
public final String getSenderName()
```


Gets or sets the message sender's display name.

Value: The the string that represents sender name.

--------------------

When setting a null value or empty string, the values of the property get the value equal to SenderEmailAddress.

**Returns:**
java.lang.String
### setSenderName(String value) {#setSenderName-java.lang.String-}
```
public final void setSenderName(String value)
```


Gets or sets the message sender's display name.

Value: The the string that represents sender name.

--------------------

When setting a null value or empty string, the values of the property get the value equal to SenderEmailAddress.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTransportMessageHeaders() {#getTransportMessageHeaders--}
```
public final String getTransportMessageHeaders()
```


Gets the transport-specific message envelope information.

Value: The string that represents transport message headers.

**Returns:**
java.lang.String
### getInternetMessageId() {#getInternetMessageId--}
```
public final String getInternetMessageId()
```


Gets the message id of the message.

Value: The string that represents internet message id.

**Returns:**
java.lang.String
### getConversationTopic() {#getConversationTopic--}
```
public final String getConversationTopic()
```


Gets the topic of the first message in a conversation thread.

Value: The string that represens conversation topic.

**Returns:**
java.lang.String
### getSentRepresentingEmailAddress() {#getSentRepresentingEmailAddress--}
```
public final String getSentRepresentingEmailAddress()
```


Gets or sets the e-mail address for the messaging user represented by the sender.

**Returns:**
java.lang.String
### setSentRepresentingEmailAddress(String value) {#setSentRepresentingEmailAddress-java.lang.String-}
```
public final void setSentRepresentingEmailAddress(String value)
```


Gets or sets the e-mail address for the messaging user represented by the sender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSentRepresentingSmtpAddress() {#getSentRepresentingSmtpAddress--}
```
public final String getSentRepresentingSmtpAddress()
```


Gets or sets the e-mail address for the messaging user represented by the sender.

Value: The string that represents sent representing email address.

**Returns:**
java.lang.String
### getSentRepresentingAddressType() {#getSentRepresentingAddressType--}
```
public final String getSentRepresentingAddressType()
```


Gets the address type for the messaging user represented by the sender.

Value: The string that represents sent representing address type.

**Returns:**
java.lang.String
### getSentRepresentingName() {#getSentRepresentingName--}
```
public final String getSentRepresentingName()
```


Gets or sets the display name for the messaging user represented by the sender.

Value: The string that represents sent representing name.

--------------------

When setting a null value or empty string, the values of the property are set in SentRepresentingEmailAddress.

**Returns:**
java.lang.String
### setSentRepresentingName(String value) {#setSentRepresentingName-java.lang.String-}
```
public final void setSentRepresentingName(String value)
```


Gets or sets the display name for the messaging user represented by the sender.

Value: The string that represents sent representing name.

--------------------

When setting a null value or empty string, the values of the property are set in SentRepresentingEmailAddress.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getClientSubmitTime() {#getClientSubmitTime--}
```
public final Date getClientSubmitTime()
```


Gets or sets the date and time the message sender submitted a message.

Value: The DateTime that represents client submit time.

--------------------

If the property was not available, DateTime.MinValue is returned.

**Returns:**
java.util.Date
### setClientSubmitTime(Date value) {#setClientSubmitTime-java.util.Date-}
```
public final void setClientSubmitTime(Date value)
```


Gets or sets the date and time the message sender submitted a message.

Value: The DateTime that represents client submit time.

--------------------

If the property was not available, DateTime.MinValue is returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getDeliveryTime() {#getDeliveryTime--}
```
public final Date getDeliveryTime()
```


Gets or sets the date and time a message was delivered.

Value: The DateTime that represents delivery time.

--------------------

If the property was not available, DateTime.MinValue is returned.

**Returns:**
java.util.Date
### setDeliveryTime(Date value) {#setDeliveryTime-java.util.Date-}
```
public final void setDeliveryTime(Date value)
```


Gets or sets the date and time a message was delivered.

Value: The DateTime that represents delivery time.

--------------------

If the property was not available, DateTime.MinValue is returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaders() {#getHeaders--}
```
public final HeaderCollection getHeaders()
```


Gets the transport message headers

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### setHeaders(HeaderCollection value) {#setHeaders-com.aspose.email.HeaderCollection-}
```
public final void setHeaders(HeaderCollection value)
```


Gets the transport message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HeaderCollection](../../com.aspose.email/headercollection) |  |

### getFlags() {#getFlags--}
```
public final long getFlags()
```


Gets the message flags.

Value: The message flags.

**Returns:**
long
### getReadReceiptRequested() {#getReadReceiptRequested--}
```
public final boolean getReadReceiptRequested()
```


Gets or sets a value indicating whether the read receipt is requested.

Value: \`\`\` true \`\`\` if the read receipt is requested; otherwise, \`\`\` false \`\`\`.

**Returns:**
boolean
### setReadReceiptRequested(boolean value) {#setReadReceiptRequested-boolean-}
```
public final void setReadReceiptRequested(boolean value)
```


Gets or sets a value indicating whether the read receipt is requested.

Value: \`\`\` true \`\`\` if the read receipt is requested; otherwise, \`\`\` false \`\`\`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMessageFormat() {#getMessageFormat--}
```
public final int getMessageFormat()
```


Gets the outlook message format.

Value: The outlook message format.

**Returns:**
int
### load(String fileName) {#load-java.lang.String-}
```
public static MapiMessage load(String fileName)
```


Loads message from file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Source file pathString. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static MapiMessage load(InputStream stream)
```


Loads message from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source streamjava.io.InputStream. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### load(InputStream stream, LoadOptions options) {#load-java.io.InputStream-com.aspose.email.LoadOptions-}
```
public static MapiMessage load(InputStream stream, LoadOptions options)
```


Loads message from stream with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source streamjava.io.InputStream. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | Additional options [LoadOptions](../../com.aspose.email/loadoptions). |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### load(String fileName, LoadOptions options) {#load-java.lang.String-com.aspose.email.LoadOptions-}
```
public static MapiMessage load(String fileName, LoadOptions options)
```


Loads message from file with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Source file pathString. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | Additional options [LoadOptions](../../com.aspose.email/loadoptions). |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### fromFile(String path) {#fromFile-java.lang.String-}
```
public static MapiMessage fromFile(String path)
```


Create an instance of MapiMessage from the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The name of the file to be loaded. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the specified file.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static MapiMessage fromStream(InputStream stream)
```


Create an instance of MapiMessage from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to be loaded. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the specified stream.
### fromProperties(MapiPropertyCollection properties) {#fromProperties-com.aspose.email.MapiPropertyCollection-}
```
public static MapiMessage fromProperties(MapiPropertyCollection properties)
```


Creates an instance of MapiMessage from a collection of Mapi properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| properties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | A collection of MapiProperty. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the specified properties.
### fromMailMessage(String fileName) {#fromMailMessage-java.lang.String-}
```
public static MapiMessage fromMailMessage(String fileName)
```


Creates an instance of MapiMessage from the MailMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name of MailMessage. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the MailMessage.
### fromMailMessage(MailMessage message) {#fromMailMessage-com.aspose.email.MailMessage-}
```
public static MapiMessage fromMailMessage(MailMessage message)
```


Creates an instance of MapiMessage from the MailMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The MailMessage. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the MailMessage.
### fromMailMessage(MailMessage message, MapiConversionOptions options) {#fromMailMessage-com.aspose.email.MailMessage-com.aspose.email.MapiConversionOptions-}
```
public static MapiMessage fromMailMessage(MailMessage message, MapiConversionOptions options)
```


Creates an instance of MapiMessage from the MailMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The MailMessage. |
| options | [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) | MapiFromMailMessageOptions [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - [MapiMessage](../../com.aspose.email/mapimessage) that represents Outlook message.
### removeAttachments(String path) {#removeAttachments-java.lang.String-}
```
public static MapiAttachmentCollection removeAttachments(String path)
```


Removes all of the attachments from the specified Outlook Message files.

--------------------

> The following exmaple demonstrates how to destroy attachments in Outlook Message files.
> 
> [Java]
> 
> ```
> //Remove attachments from Outlook Message files
>      MapiAttachmentCollection attachments = MapiMessage.removeAttachments("outlookmessage.msg");
> 
>      //Attachments
>      for(MapiAttachment att : attachments)
>      {
>         System.out.print("Attachment Name:"+att.getFileName());
>         att.save(att.getFileName());
>      }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The name of the Outlook Message file. |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The attachments collection.
### destroyAttachments(String path) {#destroyAttachments-java.lang.String-}
```
public static void destroyAttachments(String path)
```


Destroies the attachments in the specified Outlook Message files. DestroyAttachments will ignore the attachment parsing.

--------------------

> The following exmaple demonstrates how to destroy attachments in Outlook Message files.
> 
> [Java]
> 
> ```
> //Destroy attachments from Outlook Message files
>      MapiMessage.destroyAttachment("outlookmessage.msg");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The name of the Outlook Message file. |

### loadFromTnef(InputStream stream) {#loadFromTnef-java.io.InputStream-}
```
public static MapiMessage loadFromTnef(InputStream stream)
```


Loads message from Transport Neutral Encapsulation Format (TNEF) data structure

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream representing message data in TNEF format |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A read [MapiMessage](../../com.aspose.email/mapimessage)
### loadFromTnef(String fileName) {#loadFromTnef-java.lang.String-}
```
public static MapiMessage loadFromTnef(String fileName)
```


Loads message from Transport Neutral Encapsulation Format (TNEF) data structure

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of file containing message data in TNEF format |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A read [MapiMessage](../../com.aspose.email/mapimessage)
### isMsgFormat(String fileName) {#isMsgFormat-java.lang.String-}
```
public static boolean isMsgFormat(String fileName)
```


Determines whether the specified file has a MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

**Returns:**
boolean - \`\`\` true \`\`\` if the file is represented in MSG format; otherwise, \`\`\` false \`\`\`.
### isMsgFormat(InputStream stream) {#isMsgFormat-java.io.InputStream-}
```
public static boolean isMsgFormat(InputStream stream)
```


Determines whether the specified stream has a MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The message stream. |

**Returns:**
boolean - \`\`\` true \`\`\` if the stream is represented in MSG format]; otherwise, \`\`\` false \`\`\`.
### setStringPropertyValue(long tag, String value) {#setStringPropertyValue-long-java.lang.String-}
```
public final void setStringPropertyValue(long tag, String value)
```


Sets the string property value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The property tag. |
| value | java.lang.String | The property value. |

### addCustomProperty(MapiProperty property, String stringNameId) {#addCustomProperty-com.aspose.email.MapiProperty-java.lang.String-}
```
public final void addCustomProperty(MapiProperty property, String stringNameId)
```


Adds the custom property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | The property[MapiProperty](../../com.aspose.email/mapiproperty). |
| stringNameId | java.lang.String | The name of propertyString. |

### addCustomProperty(int type, byte[] data, String stringNameId) {#addCustomProperty-int-byte---java.lang.String-}
```
public final void addCustomProperty(int type, byte[] data, String stringNameId)
```


Adds the custom property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type of MapiProperty[MapiPropertyType](../../com.aspose.email/mapipropertytype) |
| data | byte[] | MapiProperty data.byte |
| stringNameId | java.lang.String | The name of propertyString. |

### getCustomProperties() {#getCustomProperties--}
```
public final MapiPropertyCollection getCustomProperties()
```


Gets collection of custom MapiProperties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - Collection of custom MapiProperties[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection).
### toMapiMessageItem() {#toMapiMessageItem--}
```
public final IMapiMessageItem toMapiMessageItem()
```


Convert MapiMessage to IMapiMessageItem object in dependence with MessageClass.

**Returns:**
[IMapiMessageItem](../../com.aspose.email/imapimessageitem) - The IMapiMessageItem interface.
### toMailMessage(MailConversionOptions options) {#toMailMessage-com.aspose.email.MailConversionOptions-}
```
public final MailMessage toMailMessage(MailConversionOptions options)
```


Creates an instance of MailMessage from this MapiMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [MailConversionOptions](../../com.aspose.email/mailconversionoptions) | Allows to specify additional options when converting from MapiMessage to MailMessage. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Returns a MailMessage instance which is loaded from this MapiMessage.
### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.email.SaveOptions-}
```
public final void save(String fileName, SaveOptions options)
```


Saves message as a file with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Stream into which message is saved. |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | Additional options for saving[SaveOptions](../../com.aspose.email/saveoptions). |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.email.SaveOptions-}
```
public final void save(OutputStream stream, SaveOptions options)
```


Saves message as a stream with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream into which message is saved. |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | Additional options for saving[SaveOptions](../../com.aspose.email/saveoptions). |

### saveAsTnef(OutputStream stream) {#saveAsTnef-java.io.OutputStream-}
```
public final void saveAsTnef(OutputStream stream)
```


Save message in TNEF format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream where a message will be saved to. |

### saveAsTnef(String fileName) {#saveAsTnef-java.lang.String-}
```
public final void saveAsTnef(String fileName)
```


Save message in TNEF format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file where a message will be saved to. |

### save(String fileName) {#save-java.lang.String-}
```
public final void save(String fileName)
```


Saves to the specified file as Msg.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

### saveAsTemplate(String fileName) {#saveAsTemplate-java.lang.String-}
```
public final void saveAsTemplate(String fileName)
```


Saves to the specified file as Outlook File Template(OFT format).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves to the specified stream as Msg.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream. |

### saveAsTemplate(OutputStream stream) {#saveAsTemplate-java.io.OutputStream-}
```
public final void saveAsTemplate(OutputStream stream)
```


Saves to the specified stream as Outlook File Template(OFT format).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream. |

### checkBounced() {#checkBounced--}
```
public final BounceResult checkBounced()
```


Checks whether this message can be treated as a bounce message.

**Returns:**
[BounceResult](../../com.aspose.email/bounceresult) - Result of checking[BounceResult](../../com.aspose.email/bounceresult).
### deepClone() {#deepClone--}
```
public final MapiMessage deepClone()
```


Creates a new object that is a copy of the current instance.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A new object that is a copy of this instance.
### setProperty(MapiAttachment value, long signed, long key) {#setProperty-com.aspose.email.MapiAttachment-long-long-}
```
public void setProperty(MapiAttachment value, long signed, long key)
```


Sets the attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiAttachment](../../com.aspose.email/mapiattachment) | The property value. |
| signed | long | The value, that indicates that the property is signed. |
| key | long | The property tag. |

### setProperty(MapiRecipient value, long signed, long key) {#setProperty-com.aspose.email.MapiRecipient-long-long-}
```
public void setProperty(MapiRecipient value, long signed, long key)
```


Sets the recipient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiRecipient](../../com.aspose.email/mapirecipient) | The property value. |
| signed | long | The value, that indicates that the property is signed. |
| key | long | The property tag. |

