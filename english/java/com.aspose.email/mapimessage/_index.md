---
title: MapiMessage
second_title: Aspose.Email for Java API Reference
description: Represents an Outlook Message format document that can be parsed.
type: docs
weight: 447
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
| [addCustomProperty(MapiProperty property, String stringNameId)](#addCustomProperty-com.aspose.email.MapiProperty-java.lang.String-) | Adds the custom property. |
| [addCustomProperty(int type, byte[] data, String stringNameId)](#addCustomProperty-int-byte---java.lang.String-) | Adds the custom property. |
| [checkBounced()](#checkBounced--) | Checks whether this message can be treated as a bounce message. |
| [close()](#close--) |  |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [decrypt()](#decrypt--) | Decrypts this message |
| [decrypt(byte[] certificateRawData, String certificatePassword)](#decrypt-byte---java.lang.String-) | Decrypts this message |
| [decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#decrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Decrypts this message |
| [deepClone()](#deepClone--) | Creates a new object that is a copy of the current instance. |
| [destroyAttachments(String path)](#destroyAttachments-java.lang.String-) | Destroies the attachments in the specified Outlook Message files. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromFile(String path)](#fromFile-java.lang.String-) | Create an instance of MapiMessage from the specified file. |
| [fromMailMessage(MailMessage message)](#fromMailMessage-com.aspose.email.MailMessage-) | Creates an instance of MapiMessage from the MailMessage. |
| [fromMailMessage(MailMessage message, MapiConversionOptions options)](#fromMailMessage-com.aspose.email.MailMessage-com.aspose.email.MapiConversionOptions-) | Creates an instance of MapiMessage from the MailMessage. |
| [fromMailMessage(String fileName)](#fromMailMessage-java.lang.String-) | Creates an instance of MapiMessage from the MailMessage. |
| [fromProperties(MapiPropertyCollection properties)](#fromProperties-com.aspose.email.MapiPropertyCollection-) | Creates an instance of MapiMessage from a collection of Mapi properties. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Create an instance of MapiMessage from the specified stream. |
| [getAttachments()](#getAttachments--) | Gets the attachments in the message. |
| [getBilling()](#getBilling--) | Contains the billing information associated with an item. |
| [getBody()](#getBody--) | Gets the message text. |
| [getBodyHtml()](#getBodyHtml--) | Gets the  BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) of the message converted to HTML, if present, otherwise an empty string. |
| [getBodyRtf()](#getBodyRtf--) | Gets or sets the RTF formatted message text. |
| [getBodyType()](#getBodyType--) | Gets the type of the body. |
| [getCategories()](#getCategories--) | Contains keywords or categories for the message object. |
| [getClass()](#getClass--) |  |
| [getClientSubmitTime()](#getClientSubmitTime--) | Gets or sets the date and time the message sender submitted a message. |
| [getCodePage()](#getCodePage--) | Gets the code page. |
| [getCompanies()](#getCompanies--) | Contains the names of the companies that are associated with an item. |
| [getConversationTopic()](#getConversationTopic--) | Gets the topic of the first message in a conversation thread. |
| [getCustomProperties()](#getCustomProperties--) | Gets collection of custom MapiProperties. |
| [getDeliveryTime()](#getDeliveryTime--) | Gets or sets the date and time a message was delivered. |
| [getDisplayBcc()](#getDisplayBcc--) | Gets a list of the display names of any blind carbon copy (BCC) message recipients, separated by semicolons (;). |
| [getDisplayCc()](#getDisplayCc--) | Gets a list of the display names of any carbon copy (CC) message recipients, separated by semicolons (;). |
| [getDisplayName()](#getDisplayName--) | Gets the display name for the message. |
| [getDisplayNamePrefix()](#getDisplayNamePrefix--) | Gets a prefix of the display name. |
| [getDisplayTo()](#getDisplayTo--) | Gets a list of the display names of the primary (To) message recipients, separated by semicolons (;). |
| [getFlags()](#getFlags--) | Gets the message flags. |
| [getHeaders()](#getHeaders--) | Gets the transport message headers |
| [getInternetMessageId()](#getInternetMessageId--) | Gets the message id of the message. |
| [getItemId()](#getItemId--) | The item id, uses with a server |
| [getMessageClass()](#getMessageClass--) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. |
| [getMessageFormat()](#getMessageFormat--) | Gets the outlook message format. |
| [getMileage()](#getMileage--) | Contains the mileage information that is associated with an item. |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of message. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Gets the named property mapping. |
| [getNormalizedSubject()](#getNormalizedSubject--) | Gets normalized subject of the message. |
| [getProperties()](#getProperties--) | Gets the collection of properties. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets MAPI property by property descriptor. |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | Gets the value of the property specified by tag as Boolean type. |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | Gets the string value of the property specified by tag. |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | Gets the value of the property specified by tag as DateTime type. |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | Gets the int32 value of the property specified by tag. |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | Gets the value of the property specified by tag as Long (int64) type. |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | Gets the value of the property specified by tag as Short type. |
| [getPropertyStream()](#getPropertyStream--) | Gets the property stream. |
| [getPropertyString(long tag)](#getPropertyString-long-) | Gets the string value of the property specified by tag. |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | Gets the string value of the property specified by tag. |
| [getReadReceiptRequested()](#getReadReceiptRequested--) | Gets or sets a value indicating whether the read receipt is requested. |
| [getRecipients()](#getRecipients--) | Gets the recipients of the message. |
| [getReplyTo()](#getReplyTo--) | Gets or sets the reply to names. |
| [getSenderAddressType()](#getSenderAddressType--) | Gets the message sender's e-mail address type. |
| [getSenderEmailAddress()](#getSenderEmailAddress--) | Gets or sets the message sender's e-mail address. |
| [getSenderName()](#getSenderName--) | Gets or sets the message sender's display name. |
| [getSenderSmtpAddress()](#getSenderSmtpAddress--) | Gets or sets the message sender's e-mail address. |
| [getSensitivity()](#getSensitivity--) | Gets the Sensitivity. |
| [getSentRepresentingAddressType()](#getSentRepresentingAddressType--) | Gets the address type for the messaging user represented by the sender. |
| [getSentRepresentingEmailAddress()](#getSentRepresentingEmailAddress--) | Gets or sets the e-mail address for the messaging user represented by the sender. |
| [getSentRepresentingName()](#getSentRepresentingName--) | Gets or sets the display name for the messaging user represented by the sender. |
| [getSentRepresentingSmtpAddress()](#getSentRepresentingSmtpAddress--) | Gets or sets the e-mail address for the messaging user represented by the sender. |
| [getSubStorages()](#getSubStorages--) | Gets the sub storages. |
| [getSubject()](#getSubject--) | Gets or sets the subject of the message. |
| [getSubjectPrefix()](#getSubjectPrefix--) | Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding. |
| [getSupportedType()](#getSupportedType--) | Gets the supported item type. |
| [getTransportMessageHeaders()](#getTransportMessageHeaders--) | Gets the transport-specific message envelope information. |
| [hashCode()](#hashCode--) |  |
| [isEncrypted()](#isEncrypted--) | Gets a value indicating whether the message is encrypted. |
| [isMsgFormat(InputStream stream)](#isMsgFormat-java.io.InputStream-) | Determines whether the specified stream has a MSG format. |
| [isMsgFormat(String fileName)](#isMsgFormat-java.lang.String-) | Determines whether the specified file has a MSG format. |
| [isSigned()](#isSigned--) | Gets a value indicating whether the message is signed. |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Determines if string properties are Unicode encoded or not. |
| [isTemplate()](#isTemplate--) | Determines whether the message is Outlook template (.oft). |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads message from stream. |
| [load(InputStream stream, LoadOptions options)](#load-java.io.InputStream-com.aspose.email.LoadOptions-) | Loads message from stream with additional options. |
| [load(String fileName)](#load-java.lang.String-) | Loads message from file. |
| [load(String fileName, LoadOptions options)](#load-java.lang.String-com.aspose.email.LoadOptions-) | Loads message from file with additional options. |
| [loadFromTnef(InputStream stream)](#loadFromTnef-java.io.InputStream-) | Loads message from Transport Neutral Encapsulation Format (TNEF) data structure |
| [loadFromTnef(String fileName)](#loadFromTnef-java.lang.String-) | Loads message from Transport Neutral Encapsulation Format (TNEF) data structure |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAttachments(String path)](#removeAttachments-java.lang.String-) | Removes all of the attachments from the specified Outlook Message files. |
| [removeProperty(long tag)](#removeProperty-long-) | Provides correctly removing property from all collections. |
| [removeSignature()](#removeSignature--) | Remove signature. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves to the specified stream as Msg. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.email.SaveOptions-) | Saves message as a stream with additional options. |
| [save(String fileName)](#save-java.lang.String-) | Saves to the specified file as Msg. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.email.SaveOptions-) | Saves message as a file with additional options. |
| [saveAsTemplate(OutputStream stream)](#saveAsTemplate-java.io.OutputStream-) | Saves to the specified stream as Outlook File Template(OFT format). |
| [saveAsTemplate(String fileName)](#saveAsTemplate-java.lang.String-) | Saves to the specified file as Outlook File Template(OFT format). |
| [saveAsTnef(OutputStream stream)](#saveAsTnef-java.io.OutputStream-) | Save message in TNEF format. |
| [saveAsTnef(String fileName)](#saveAsTnef-java.lang.String-) | Save message in TNEF format. |
| [setBilling(String value)](#setBilling-java.lang.String-) | Contains the billing information associated with an item. |
| [setBody(String value)](#setBody-java.lang.String-) | Gets the message text. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Sets the content of the body. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Sets the content of the body. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Gets or sets the RTF formatted message text. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Gets or sets the RTF formatted message text. |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Contains keywords or categories for the message object. |
| [setClientSubmitTime(Date value)](#setClientSubmitTime-java.util.Date-) | Gets or sets the date and time the message sender submitted a message. |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Contains the names of the companies that are associated with an item. |
| [setDeliveryTime(Date value)](#setDeliveryTime-java.util.Date-) | Gets or sets the date and time a message was delivered. |
| [setHeaders(HeaderCollection value)](#setHeaders-com.aspose.email.HeaderCollection-) | Gets the transport message headers |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Sets the message flags. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Contains the mileage information that is associated with an item. |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Sets the named property mapping. |
| [setProperty(MapiAttachment value, long signed, long key)](#setProperty-com.aspose.email.MapiAttachment-long-long-) | Sets the attachment. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Sets the property. |
| [setProperty(MapiRecipient value, long signed, long key)](#setProperty-com.aspose.email.MapiRecipient-long-long-) | Sets the recipient. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets MAPI property. |
| [setReadReceiptRequested(boolean value)](#setReadReceiptRequested-boolean-) | Gets or sets a value indicating whether the read receipt is requested. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Gets the recipients of the message. |
| [setReplyTo(String value)](#setReplyTo-java.lang.String-) | Gets or sets the reply to names. |
| [setSenderEmailAddress(String value)](#setSenderEmailAddress-java.lang.String-) | Gets or sets the message sender's e-mail address. |
| [setSenderName(String value)](#setSenderName-java.lang.String-) | Gets or sets the message sender's display name. |
| [setSenderSmtpAddress(String value)](#setSenderSmtpAddress-java.lang.String-) | Gets or sets the message sender's e-mail address. |
| [setSensitivity(int value)](#setSensitivity-int-) | Gets the Sensitivity. |
| [setSentRepresentingEmailAddress(String value)](#setSentRepresentingEmailAddress-java.lang.String-) | Gets or sets the e-mail address for the messaging user represented by the sender. |
| [setSentRepresentingName(String value)](#setSentRepresentingName-java.lang.String-) | Gets or sets the display name for the messaging user represented by the sender. |
| [setStringPropertyValue(long tag, String value)](#setStringPropertyValue-long-java.lang.String-) | Sets the string property value. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets the subject of the message. |
| [toMailMessage(MailConversionOptions options)](#toMailMessage-com.aspose.email.MailConversionOptions-) | Creates an instance of MailMessage from this MapiMessage. |
| [toMapiMessageItem()](#toMapiMessageItem--) | Convert MapiMessage to IMapiMessageItem object in dependence with MessageClass. |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | Try to get the property data with specified tag key. |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | Gets the value of the specified property as DateTime type. |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | Gets the value of the specified property as Int32 type. |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | Gets the value of the specified property as Long type. |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | Try to get a property data as string with specified tag. |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | Try to get a property data as string with specified tag and code page. |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | Gets the value of the specified property as String type. |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | Gets the value of the specified property as String type. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### checkBounced() {#checkBounced--}
```
public final BounceResult checkBounced()
```


Checks whether this message can be treated as a bounce message.

**Returns:**
[BounceResult](../../com.aspose.email/bounceresult) - Result of checking[BounceResult](../../com.aspose.email/bounceresult).
### close() {#close--}
```
public void close()
```




### createMapiNode(String key) {#createMapiNode-java.lang.String-}
```
public IMapiNode createMapiNode(String key)
```


Creates the mapi node.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The node key. |

**Returns:**
com.aspose.email.IMapiNode - The IMapiNode interface.
### decrypt() {#decrypt--}
```
public final MapiMessage decrypt()
```


Decrypts this message

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Decrypted MapiMessage

--------------------

Method searches the current user and computer My stores for the appropriate certificate and private key.
### decrypt(byte[] certificateRawData, String certificatePassword) {#decrypt-byte---java.lang.String-}
```
public final MapiMessage decrypt(byte[] certificateRawData, String certificatePassword)
```


Decrypts this message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateRawData | byte[] | X509Certificate2 |
| certificatePassword | java.lang.String |  |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - E-mail message
### decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#decrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public final MapiMessage decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```


Decrypts this message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | System.Security.Cryptography.X509Certificates.X509Certificate2 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - E-mail message
### deepClone() {#deepClone--}
```
public final MapiMessage deepClone()
```


Creates a new object that is a copy of the current instance.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A new object that is a copy of this instance.
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

### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

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
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


Gets the attachments in the message.

Value: The attachment collection.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection)
### getBilling() {#getBilling--}
```
public final String getBilling()
```


Contains the billing information associated with an item.

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public final String getBody()
```


Gets the message text.

Value: The string that represents message body.

**Returns:**
java.lang.String
### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


Gets the  BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) of the message converted to HTML, if present, otherwise an empty string.

**Returns:**
java.lang.String
### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Returns:**
java.lang.String
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Gets the type of the body.

Value: The type of the body.

**Returns:**
int
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Contains keywords or categories for the message object.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getCodePage() {#getCodePage--}
```
public int getCodePage()
```


Gets the code page.

Value: The code page.

**Returns:**
int
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Contains the names of the companies that are associated with an item.

**Returns:**
java.lang.String[]
### getConversationTopic() {#getConversationTopic--}
```
public final String getConversationTopic()
```


Gets the topic of the first message in a conversation thread.

Value: The string that represens conversation topic.

**Returns:**
java.lang.String
### getCustomProperties() {#getCustomProperties--}
```
public final MapiPropertyCollection getCustomProperties()
```


Gets collection of custom MapiProperties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - Collection of custom MapiProperties[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection).
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
### getDisplayBcc() {#getDisplayBcc--}
```
public final String getDisplayBcc()
```


Gets a list of the display names of any blind carbon copy (BCC) message recipients, separated by semicolons (;).

Value: The string that represents display bcc.

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
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the display name for the message.

Value: The string that represents display name.

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
### getDisplayTo() {#getDisplayTo--}
```
public final String getDisplayTo()
```


Gets a list of the display names of the primary (To) message recipients, separated by semicolons (;).

Value: The string that represents display to.

**Returns:**
java.lang.String
### getFlags() {#getFlags--}
```
public final long getFlags()
```


Gets the message flags.

Value: The message flags.

**Returns:**
long
### getHeaders() {#getHeaders--}
```
public final HeaderCollection getHeaders()
```


Gets the transport message headers

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getInternetMessageId() {#getInternetMessageId--}
```
public final String getInternetMessageId()
```


Gets the message id of the message.

Value: The string that represents internet message id.

**Returns:**
java.lang.String
### getItemId() {#getItemId--}
```
public String getItemId()
```


The item id, uses with a server

**Returns:**
java.lang.String
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message.

Value: The string that represents message class.

**Returns:**
java.lang.String
### getMessageFormat() {#getMessageFormat--}
```
public final int getMessageFormat()
```


Gets the outlook message format.

Value: The outlook message format.

**Returns:**
int
### getMileage() {#getMileage--}
```
public final String getMileage()
```


Contains the mileage information that is associated with an item.

**Returns:**
java.lang.String
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of message.

Value: The collection of named properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getNamedPropertyMapping() {#getNamedPropertyMapping--}
```
public final MapiNamedPropertyMappingStorage getNamedPropertyMapping()
```


Gets the named property mapping.

Value: The named property mapping.

**Returns:**
[MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage)
### getNormalizedSubject() {#getNormalizedSubject--}
```
public final String getNormalizedSubject()
```


Gets normalized subject of the message.

Value: The string that represents normalized subject.

**Returns:**
java.lang.String
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Gets the collection of properties.

Value: The properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Gets MAPI property by property descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Property descriptor for looked property |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - Mapi property if it is found, otherwise null.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


Gets the value of the property specified by tag as Boolean type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Boolean - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


Gets the string value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
byte[] - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


Gets the value of the property specified by tag as DateTime type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The MAPI property tag. |

**Returns:**
java.util.Date - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


Gets the int32 value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Integer - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


Gets the value of the property specified by tag as Long (int64) type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Long - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


Gets the value of the property specified by tag as Short type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Short - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Gets the property stream.

Value: The property stream.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream)
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


Gets the string value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.String - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


Gets the string value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| codepage | int | The specified codepage used to get string value. |

**Returns:**
java.lang.String - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getReadReceiptRequested() {#getReadReceiptRequested--}
```
public final boolean getReadReceiptRequested()
```


Gets or sets a value indicating whether the read receipt is requested.

Value:  true  if the read receipt is requested; otherwise,  false .

**Returns:**
boolean
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


Gets the recipients of the message.

Value: The collection of recipients.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection)
### getReplyTo() {#getReplyTo--}
```
public final String getReplyTo()
```


Gets or sets the reply to names.

**Returns:**
java.lang.String
### getSenderAddressType() {#getSenderAddressType--}
```
public final String getSenderAddressType()
```


Gets the message sender's e-mail address type.

Value: The string that represents sender address type.

**Returns:**
java.lang.String
### getSenderEmailAddress() {#getSenderEmailAddress--}
```
public final String getSenderEmailAddress()
```


Gets or sets the message sender's e-mail address.

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
### getSenderSmtpAddress() {#getSenderSmtpAddress--}
```
public final String getSenderSmtpAddress()
```


Gets or sets the message sender's e-mail address.

**Returns:**
java.lang.String
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the Sensitivity.

Value: The sensitivity.

**Returns:**
int
### getSentRepresentingAddressType() {#getSentRepresentingAddressType--}
```
public final String getSentRepresentingAddressType()
```


Gets the address type for the messaging user represented by the sender.

Value: The string that represents sent representing address type.

**Returns:**
java.lang.String
### getSentRepresentingEmailAddress() {#getSentRepresentingEmailAddress--}
```
public final String getSentRepresentingEmailAddress()
```


Gets or sets the e-mail address for the messaging user represented by the sender.

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
### getSentRepresentingSmtpAddress() {#getSentRepresentingSmtpAddress--}
```
public final String getSentRepresentingSmtpAddress()
```


Gets or sets the e-mail address for the messaging user represented by the sender.

Value: The string that represents sent representing email address.

**Returns:**
java.lang.String
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Gets the sub storages.

Value: The sub storages.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets or sets the subject of the message.

Value: The string that represents message subject.

--------------------

When setting a value, the values of SubjectPrefix(PR\_SUBJECT\_PREFIX) and NormalizedSubject(PR\_NORMALIZED\_SUBJECT) properties are updated as well. If Subject has no prefix, the value of SubjectPrefix property is set null. When setting a null value or empty string, the values of Subject, SubjectPrefix, NormalizedSubject properties are set null.

**Returns:**
java.lang.String
### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding.

Value: The string that represents subject prefix.

**Returns:**
java.lang.String
### getSupportedType() {#getSupportedType--}
```
public final int getSupportedType()
```


Gets the supported item type.

Value: The [MapiItemType](../../com.aspose.email/mapiitemtype).

**Returns:**
int
### getTransportMessageHeaders() {#getTransportMessageHeaders--}
```
public final String getTransportMessageHeaders()
```


Gets the transport-specific message envelope information.

Value: The string that represents transport message headers.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Gets a value indicating whether the message is encrypted.

**Returns:**
boolean
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
boolean -  true  if the stream is represented in MSG format]; otherwise,  false .
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
boolean -  true  if the file is represented in MSG format; otherwise,  false .
### isSigned() {#isSigned--}
```
public final boolean isSigned()
```


Gets a value indicating whether the message is signed.

**Returns:**
boolean
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


Determines if string properties are Unicode encoded or not.

**Returns:**
boolean - True, if string properties are Unicode encoded.
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Determines whether the message is Outlook template (.oft).

**Returns:**
boolean -  true  if the message is OFT template; otherwise,  false .
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Provides correctly removing property from all collections.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of MapiProperty. |

### removeSignature() {#removeSignature--}
```
public final MapiMessage removeSignature()
```


Remove signature.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Unsigned MapiMessage message
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves to the specified stream as Msg.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream. |

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

### save(String fileName) {#save-java.lang.String-}
```
public final void save(String fileName)
```


Saves to the specified file as Msg.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

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

### saveAsTemplate(OutputStream stream) {#saveAsTemplate-java.io.OutputStream-}
```
public final void saveAsTemplate(OutputStream stream)
```


Saves to the specified stream as Outlook File Template(OFT format).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream. |

### saveAsTemplate(String fileName) {#saveAsTemplate-java.lang.String-}
```
public final void saveAsTemplate(String fileName)
```


Saves to the specified file as Outlook File Template(OFT format).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

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

### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


Contains the billing information associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setBodyContent(String content, int contentType) {#setBodyContent-java.lang.String-int-}
```
public void setBodyContent(String content, int contentType)
```


Sets the content of the body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content. |
| contentType | int | Type of the content.

--------------------

It is provided for setting of the content of the body message in RTF, HTML or Plain Text formats. When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated as well. Note, after the value in HTML format is set, BodyRtf property returns the value which is encoded within RTF. |

### setBodyContent(String content, int contentType, boolean compression) {#setBodyContent-java.lang.String-int-boolean-}
```
public void setBodyContent(String content, int contentType, boolean compression)
```


Sets the content of the body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content. |
| contentType | int | Type of the content. |
| compression | boolean | Specify that the content should be compressed.

--------------------

It is provided for setting of the content of the body message in RTF, HTML or Plain Text formats. When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated as well. Note, after the value in HTML format is set, BodyRtf property returns the value which is encoded within RTF. |

### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyRtf(String value, boolean compression) {#setBodyRtf-java.lang.String-boolean-}
```
public final void setBodyRtf(String value, boolean compression)
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
| compression | boolean | Specify that the content should be compressed. |

### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


Contains keywords or categories for the message object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

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

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Contains the names of the companies that are associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

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

### setHeaders(HeaderCollection value) {#setHeaders-com.aspose.email.HeaderCollection-}
```
public final void setHeaders(HeaderCollection value)
```


Gets the transport message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HeaderCollection](../../com.aspose.email/headercollection) |  |

### setMessageClass(String value) {#setMessageClass-java.lang.String-}
```
public final void setMessageClass(String value)
```


Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message.

Value: The string that represents message class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessageFlags(long flags) {#setMessageFlags-long-}
```
public final void setMessageFlags(long flags)
```


Sets the message flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The message flags. |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Contains the mileage information that is associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNamedPropertyMapping(MapiNamedPropertyMappingStorage value) {#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-}
```
public final void setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)
```


Sets the named property mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) | The MapiNamedPropertyMappingStorage. |

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

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


Sets the property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | The property. |

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

### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


Sets MAPI property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The property descriptor. |
| value | java.lang.Object | The property data. |

### setReadReceiptRequested(boolean value) {#setReadReceiptRequested-boolean-}
```
public final void setReadReceiptRequested(boolean value)
```


Gets or sets a value indicating whether the read receipt is requested.

Value:  true  if the read receipt is requested; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRecipients(MapiRecipientCollection value) {#setRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setRecipients(MapiRecipientCollection value)
```


Gets the recipients of the message.

Value: The collection of recipients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) |  |

### setReplyTo(String value) {#setReplyTo-java.lang.String-}
```
public final void setReplyTo(String value)
```


Gets or sets the reply to names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSenderEmailAddress(String value) {#setSenderEmailAddress-java.lang.String-}
```
public final void setSenderEmailAddress(String value)
```


Gets or sets the message sender's e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setSenderSmtpAddress(String value) {#setSenderSmtpAddress-java.lang.String-}
```
public final void setSenderSmtpAddress(String value)
```


Gets or sets the message sender's e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


Gets the Sensitivity.

Value: The sensitivity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSentRepresentingEmailAddress(String value) {#setSentRepresentingEmailAddress-java.lang.String-}
```
public final void setSentRepresentingEmailAddress(String value)
```


Gets or sets the e-mail address for the messaging user represented by the sender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gets or sets the subject of the message.

Value: The string that represents message subject.

--------------------

When setting a value, the values of SubjectPrefix(PR\_SUBJECT\_PREFIX) and NormalizedSubject(PR\_NORMALIZED\_SUBJECT) properties are updated as well. If Subject has no prefix, the value of SubjectPrefix property is set null. When setting a null value or empty string, the values of Subject, SubjectPrefix, NormalizedSubject properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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
### toMapiMessageItem() {#toMapiMessageItem--}
```
public final IMapiMessageItem toMapiMessageItem()
```


Convert MapiMessage to IMapiMessageItem object in dependence with MessageClass.

**Returns:**
[IMapiMessageItem](../../com.aspose.email/imapimessageitem) - The IMapiMessageItem interface.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetPropertyData(long tag) {#tryGetPropertyData-long-}
```
public final byte[] tryGetPropertyData(long tag)
```


Try to get the property data with specified tag key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag key. |

**Returns:**
byte[] - The property data.
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


Gets the value of the specified property as DateTime type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | java.util.Date[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


Gets the value of the specified property as Int32 type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | int[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


Gets the value of the specified property as Long type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | long[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


Try to get a property data as string with specified tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The property tag key. |

**Returns:**
java.lang.String - String that contains the contents of property data.
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


Try to get a property data as string with specified tag and code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The property tag key. |
| codepage | int | The code page. |

**Returns:**
java.lang.String - String that contains the contents of property data.
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


Gets the value of the specified property as String type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | java.lang.String[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


Gets the value of the specified property as String type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | java.lang.String[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |
| codepage | int | The specified codepage used to get string value. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
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

