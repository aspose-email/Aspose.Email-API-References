---
title: MapiMessage
second_title: Aspose.Email for Java API Reference
description: Represents an Outlook message the content of an MSG file.
type: docs
weight: 469
url: /java/com.aspose.email/mapimessage/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiMessage extends MapiMessageItemBase
```

Represents an Outlook message: the content of an MSG file.

Load a message with \#load(String).load(String), create one with a constructor or from a [MailMessage](../../com.aspose.email/mailmessage) with \#fromMailMessage(String).fromMailMessage(String), and save it with \#save(String, SaveOptions).save(String, SaveOptions). Other Outlook items stored in MSG files \\u2014 contacts, appointments, tasks and so on \\u2014 load as a [MapiMessage](../../com.aspose.email/mapimessage) too; \#toMapiMessageItem().toMapiMessageItem() converts them to the matching class.

The following example demonstrates how to read Outlook Message files.

```

 //Open Outlook Message files
 MapiMessage msg = MapiMessage.load("c:\\outlookmessage.msg");

 //read subject
 System.out.println("Subject:" + msg.getSubject());

 //sender name
 System.out.println("From:" + msg.getSenderName());

 //message body
 System.out.println("Body:" + msg.getBody());

 //Attachments
 for (MapiAttachment att : msg.getAttachments()) {
     System.out.println("Attachment Name:" + att.getFileName());
     att.save(att.getFileName());
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiMessage()](#MapiMessage--) | Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class: an empty message. |
| [MapiMessage(int format)](#MapiMessage-int-) | Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class: an empty message in the specified format. |
| [MapiMessage(String from, String to, String subject, String body, int format)](#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-int-) | Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class with a sender, recipients, a subject and a body, in the specified format. |
| [MapiMessage(String from, String to, String subject, String body)](#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class with a sender, recipients, a subject and a body, in Unicode format. |
## Methods

| Method | Description |
| --- | --- |
| [addCustomProperty(MapiProperty property, String stringNameId)](#addCustomProperty-com.aspose.email.MapiProperty-java.lang.String-) | Adds a custom named property with a string name. |
| [addCustomProperty(int type, byte[] data, String stringNameId)](#addCustomProperty-int-byte---java.lang.String-) | Adds a custom named property with a string name. |
| [checkBounced()](#checkBounced--) | Checks whether the message is a bounce (a non-delivery report) and, if so, why it bounced. |
| [checkSignature()](#checkSignature--) | Verifies the digital signature of the message. |
| [close()](#close--) | Releases the resources used by the item. |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [decrypt(byte[] certificateRawData, String certificatePassword)](#decrypt-byte---java.lang.String-) | Decrypts this message |
| [decrypt(SmimeKey key)](#decrypt-com.aspose.email.SmimeKey-) | Decrypts this message |
| [deepClone()](#deepClone--) | Creates a copy of the message. |
| [destroyAttachments(String path)](#destroyAttachments-java.lang.String-) | Removes all attachments from an MSG file and overwrites the file. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromMailMessage(MailMessage message)](#fromMailMessage-com.aspose.email.MailMessage-) | Creates a message from a [MailMessage](../../com.aspose.email/mailmessage). |
| [fromMailMessage(MailMessage message, MapiConversionOptions options)](#fromMailMessage-com.aspose.email.MailMessage-com.aspose.email.MapiConversionOptions-) | Creates a message from a [MailMessage](../../com.aspose.email/mailmessage) with the specified options. |
| [fromMailMessage(InputStream stream)](#fromMailMessage-java.io.InputStream-) | Creates a message from a stream in EML format. |
| [fromMailMessage(String fileName)](#fromMailMessage-java.lang.String-) | Creates a message from an EML file. |
| [fromProperties(MapiPropertyCollection properties)](#fromProperties-com.aspose.email.MapiPropertyCollection-) | Creates a message from a collection of MAPI properties. |
| [getAttachments()](#getAttachments--) | Gets the attachments of the item. |
| [getBilling()](#getBilling--) | Gets the billing information of the item. |
| [getBody()](#getBody--) | Gets the plain-text body of the item. |
| [getBodyHtml()](#getBodyHtml--) | Gets the body of the item as HTML, converted from \#getBodyRtf().getBodyRtf(); an empty string when there is no RTF body. |
| [getBodyRtf()](#getBodyRtf--) | Gets the body of the item in RTF format. |
| [getBodyType()](#getBodyType--) | Gets the format of the body: plain text, HTML or RTF. |
| [getCategories()](#getCategories--) | Gets the categories of the item. |
| [getClass()](#getClass--) |  |
| [getClientSubmitTime()](#getClientSubmitTime--) | Gets the date and time the sender sent the message. |
| [getCodePage()](#getCodePage--) | Gets the code page of the ANSI strings of the object. |
| [getCompanies()](#getCompanies--) | Gets the names of the companies associated with the item. |
| [getConversationTopic()](#getConversationTopic--) | Gets the topic of the conversation the message belongs to: the subject of its first message, without prefixes. |
| [getCustomProperties()](#getCustomProperties--) | Gets the custom named properties of the message. |
| [getDeliveryTime()](#getDeliveryTime--) | Gets the date and time the message was delivered. |
| [getDisplayBcc()](#getDisplayBcc--) | Gets the display names of the BCC recipients, separated by semicolons ( ; ). |
| [getDisplayCc()](#getDisplayCc--) | Gets the display names of the CC recipients, separated by semicolons ( ; ). |
| [getDisplayName()](#getDisplayName--) | Gets the display name of the message. |
| [getDisplayNamePrefix()](#getDisplayNamePrefix--) | Gets the prefix of the display name, such as a title. |
| [getDisplayTo()](#getDisplayTo--) | Gets the display names of the To recipients, separated by semicolons ( ; ). |
| [getFlags()](#getFlags--) | Gets the flags of the message, such as read, unsent or has attachments. |
| [getHeaders()](#getHeaders--) | Gets the Internet headers of the message. |
| [getInternetMessageId()](#getInternetMessageId--) | Gets the  Message-ID  of the message. |
| [getItemId()](#getItemId--) | Gets the identifier of the item on the mail server, for items obtained from a server;  null  otherwise. |
| [getMessageClass()](#getMessageClass--) | Gets the message class of the item, such as  IPM.Note  for an e-mail message. |
| [getMessageFormat()](#getMessageFormat--) | Gets the format of the message: Unicode or ANSI. |
| [getMileage()](#getMileage--) | Gets the mileage information of the item. |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of the item. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Gets the mapping between the named properties and the tags they are stored under. |
| [getNormalizedSubject()](#getNormalizedSubject--) | Gets the subject without its prefix, such as  RE: . |
| [getProperties()](#getProperties--) | Gets all properties of the object. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets a MAPI property of the item by its descriptor. |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | Gets the value of a property as a Boolean. |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | Gets the value of a property as bytes. |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | Gets the value of a property as a date and time. |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | Gets the value of a property as a 32-bit integer. |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | Gets the value of a property as a 64-bit integer. |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | Gets the value of a property as a 16-bit integer. |
| [getPropertyStream()](#getPropertyStream--) | Gets the property stream of the item. |
| [getPropertyString(long tag)](#getPropertyString-long-) | Gets the value of a property as a string. |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [getReadReceiptRequested()](#getReadReceiptRequested--) | Gets a value indicating whether a read receipt is requested. |
| [getRecipients()](#getRecipients--) | Gets the recipients of the item. |
| [getReplyTo()](#getReplyTo--) | Gets the addresses that replies go to, separated by semicolons ( ; ). |
| [getSenderAddressType()](#getSenderAddressType--) | Gets the type of the address of the sender, such as  SMTP  or  EX . |
| [getSenderEmailAddress()](#getSenderEmailAddress--) | Gets the message sender's e-mail address. |
| [getSenderName()](#getSenderName--) | Gets the message sender's display name. |
| [getSenderSmtpAddress()](#getSenderSmtpAddress--) | Gets the SMTP address of the sender. |
| [getSensitivity()](#getSensitivity--) | Gets the sensitivity of the item: normal, personal, private or confidential. |
| [getSentRepresentingAddressType()](#getSentRepresentingAddressType--) | Gets the address type of the user on whose behalf the message was sent. |
| [getSentRepresentingEmailAddress()](#getSentRepresentingEmailAddress--) | Gets the e-mail address of the user on whose behalf the message was sent. |
| [getSentRepresentingName()](#getSentRepresentingName--) | Gets the display name of the user on whose behalf the message was sent. |
| [getSentRepresentingSmtpAddress()](#getSentRepresentingSmtpAddress--) | Gets the SMTP address of the user on whose behalf the message was sent. |
| [getSubStorages()](#getSubStorages--) | Gets the sub-storages of the item. |
| [getSubject()](#getSubject--) | Gets the subject of the message. |
| [getSubjectPrefix()](#getSubjectPrefix--) | Gets the prefix of the subject, such as  RE:  or  FW: . |
| [getSupportedType()](#getSupportedType--) | Gets the type of the item, as determined by its message class. |
| [getTransportMessageHeaders()](#getTransportMessageHeaders--) | Gets the Internet headers of the message as one string. |
| [hashCode()](#hashCode--) |  |
| [isEncrypted()](#isEncrypted--) | Gets a value indicating whether the message is encrypted (S/MIME). |
| [isMsgFormat(InputStream stream)](#isMsgFormat-java.io.InputStream-) | Determines whether a stream contains a message in MSG format. |
| [isMsgFormat(String fileName)](#isMsgFormat-java.lang.String-) | Determines whether a file is in MSG format. |
| [isSigned()](#isSigned--) | Gets a value indicating whether the message is digitally signed. |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Determines whether the string properties of the object are stored in Unicode. |
| [isTemplate()](#isTemplate--) | Gets a value indicating whether the message is an Outlook template (.oft). |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads a message from a stream. |
| [load(InputStream stream, LoadOptions options)](#load-java.io.InputStream-com.aspose.email.LoadOptions-) | Loads a message from a stream with the specified options. |
| [load(String fileName)](#load-java.lang.String-) | Loads a message from a file. |
| [load(String fileName, LoadOptions options)](#load-java.lang.String-com.aspose.email.LoadOptions-) | Loads a message from a file with the specified options. |
| [loadFromTnef(InputStream stream)](#loadFromTnef-java.io.InputStream-) | Loads a message from a stream in TNEF format (the content of a winmail.dat attachment). |
| [loadFromTnef(String fileName)](#loadFromTnef-java.lang.String-) | Loads a message from a file in TNEF format, such as winmail.dat. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAttachments(String path)](#removeAttachments-java.lang.String-) | Removes all attachments from an MSG file, overwrites the file, and returns the removed attachments. |
| [removeProperty(long tag)](#removeProperty-long-) | Removes a property from the item, including its named-property mapping. |
| [removeSignature()](#removeSignature--) | Returns a copy of a signed message without the signature. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the message to a stream in MSG format. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.email.SaveOptions-) | Saves the message to a stream in the format selected by the options, such as MSG, OFT, EML, EMLX, HTML or MHTML. |
| [save(String fileName)](#save-java.lang.String-) | Saves the message to a file in MSG format. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.email.SaveOptions-) | Saves the message to a file in the format selected by the options, such as MSG, OFT, EML, EMLX, HTML or MHTML. |
| [saveAsTemplate(OutputStream stream)](#saveAsTemplate-java.io.OutputStream-) | Saves the message to a stream as an Outlook template (.oft). |
| [saveAsTemplate(String fileName)](#saveAsTemplate-java.lang.String-) | Saves the message to a file as an Outlook template (.oft). |
| [saveAsTnef(OutputStream stream)](#saveAsTnef-java.io.OutputStream-) | Saves the message to a stream in TNEF format (the format of winmail.dat). |
| [saveAsTnef(String fileName)](#saveAsTnef-java.lang.String-) | Saves the message to a file in TNEF format (the format of winmail.dat). |
| [setBilling(String value)](#setBilling-java.lang.String-) | Sets the billing information of the item. |
| [setBody(String value)](#setBody-java.lang.String-) | Sets the plain-text body of the item. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Sets the body of the item in the specified format. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Sets the body of the item in the specified format, optionally compressing it. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Sets the body of the item in RTF format. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Sets the body of the item in RTF format, optionally compressing it. |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Sets the categories of the item. |
| [setClientSubmitTime(Date value)](#setClientSubmitTime-java.util.Date-) | Sets the date and time the sender sent the message. |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Sets the names of the companies associated with the item. |
| [setDeliveryTime(Date value)](#setDeliveryTime-java.util.Date-) | Sets the date and time the message was delivered. |
| [setHeaders(HeaderCollection value)](#setHeaders-com.aspose.email.HeaderCollection-) | Sets the Internet headers of the message. |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Sets the message class of the item, such as  IPM.Note  for an e-mail message. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Sets the flags of the message, such as read or unsent. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Sets the mileage information of the item. |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Sets the named property mapping. |
| [setProperty(MapiAttachment value, long signed, long key)](#setProperty-com.aspose.email.MapiAttachment-long-long-) | Sets the attachment. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Adds the property, or replaces the property with the same tag. |
| [setProperty(MapiRecipient value, long signed, long key)](#setProperty-com.aspose.email.MapiRecipient-long-long-) | Sets the recipient. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets the value of a MAPI property of the item. |
| [setReadReceiptRequested(boolean value)](#setReadReceiptRequested-boolean-) | Sets a value indicating whether a read receipt is requested. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Sets the recipients of the item. |
| [setReplyTo(String value)](#setReplyTo-java.lang.String-) | Sets the addresses that replies go to, separated by semicolons ( ; ). |
| [setSenderEmailAddress(String value)](#setSenderEmailAddress-java.lang.String-) | Sets the message sender's e-mail address. |
| [setSenderName(String value)](#setSenderName-java.lang.String-) | Sets the message sender's display name. |
| [setSenderSmtpAddress(String value)](#setSenderSmtpAddress-java.lang.String-) | Sets the SMTP address of the sender. |
| [setSensitivity(int value)](#setSensitivity-int-) | Sets the sensitivity of the item: normal, personal, private or confidential. |
| [setSentRepresentingEmailAddress(String value)](#setSentRepresentingEmailAddress-java.lang.String-) | Sets the e-mail address of the user on whose behalf the message was sent. |
| [setSentRepresentingName(String value)](#setSentRepresentingName-java.lang.String-) | Sets the display name of the user on whose behalf the message was sent. |
| [setStringPropertyValue(long tag, String value)](#setStringPropertyValue-long-java.lang.String-) | Sets the value of a string property, in the string format of the message (Unicode or ANSI). |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the message. |
| [toMailMessage(MailConversionOptions options)](#toMailMessage-com.aspose.email.MailConversionOptions-) | Converts the message to a [MailMessage](../../com.aspose.email/mailmessage) with the specified options. |
| [toMapiMessageItem()](#toMapiMessageItem--) | Converts the message to the item class that matches its message class, such as [MapiContact](../../com.aspose.email/mapicontact) for  IPM.Contact . |
| [toMvPropertyList(Object obj)](#toMvPropertyList-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | Gets the value of a property as bytes. |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | Gets the value of a property as a date and time, if the property exists. |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | Gets the value of a property as a string. |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | Gets the value of a property as a string, if the property exists. |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiMessage() {#MapiMessage--}
```
public MapiMessage()
```


Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class: an empty message.

### MapiMessage(int format) {#MapiMessage-int-}
```
public MapiMessage(int format)
```


Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class: an empty message in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | The format of the message: Unicode or ANSI. |

### MapiMessage(String from, String to, String subject, String body, int format) {#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-int-}
```
public MapiMessage(String from, String to, String subject, String body, int format)
```


Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class with a sender, recipients, a subject and a body, in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | The address of the sender. |
| to | java.lang.String | The addresses of the To recipients, separated by semicolons ( ; ). |
| subject | java.lang.String | The subject. |
| body | java.lang.String | The plain-text body. |
| format | int | The format of the message: Unicode or ANSI. |

### MapiMessage(String from, String to, String subject, String body) {#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public MapiMessage(String from, String to, String subject, String body)
```


Initializes a new instance of the [MapiMessage](../../com.aspose.email/mapimessage) class with a sender, recipients, a subject and a body, in Unicode format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | The address of the sender. |
| to | java.lang.String | The addresses of the To recipients, separated by semicolons ( ; ). |
| subject | java.lang.String | The subject. |
| body | java.lang.String | The plain-text body. |

### addCustomProperty(MapiProperty property, String stringNameId) {#addCustomProperty-com.aspose.email.MapiProperty-java.lang.String-}
```
public final void addCustomProperty(MapiProperty property, String stringNameId)
```


Adds a custom named property with a string name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | The property, with its type and value. |
| stringNameId | java.lang.String | The name of the property. |

### addCustomProperty(int type, byte[] data, String stringNameId) {#addCustomProperty-int-byte---java.lang.String-}
```
public final void addCustomProperty(int type, byte[] data, String stringNameId)
```


Adds a custom named property with a string name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The data type of the property. |
| data | byte[] | The value of the property, as bytes. |
| stringNameId | java.lang.String | The name of the property. |

### checkBounced() {#checkBounced--}
```
public final BounceResult checkBounced()
```


Checks whether the message is a bounce (a non-delivery report) and, if so, why it bounced.

**Returns:**
[BounceResult](../../com.aspose.email/bounceresult) - The result of the check.
### checkSignature() {#checkSignature--}
```
public List<X509Certificate> checkSignature()
```


Verifies the digital signature of the message.

**Returns:**
java.util.List<java.security.cert.X509Certificate> - The certificates of the signers.
### close() {#close--}
```
public void close()
```


Releases the resources used by the item.

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
### decrypt(byte[] certificateRawData, String certificatePassword) {#decrypt-byte---java.lang.String-}
```
public final MapiMessage decrypt(byte[] certificateRawData, String certificatePassword)
```


Decrypts this message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateRawData | byte[] |  |
| certificatePassword | java.lang.String |  |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - E-mail message
### decrypt(SmimeKey key) {#decrypt-com.aspose.email.SmimeKey-}
```
public final MapiMessage decrypt(SmimeKey key)
```


Decrypts this message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | [SmimeKey](../../com.aspose.email/smimekey) |  |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - E-mail message
### deepClone() {#deepClone--}
```
public final MapiMessage deepClone()
```


Creates a copy of the message.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The copy.
### destroyAttachments(String path) {#destroyAttachments-java.lang.String-}
```
public static void destroyAttachments(String path)
```


Removes all attachments from an MSG file and overwrites the file. The attachments are not read, which is faster than \#removeAttachments(String).removeAttachments(String).

This example removes the attachments of an MSG file without reading them.

```

 MapiMessage.destroyAttachments("c:\\messages\\message.msg");
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path of the MSG file. |

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
### fromMailMessage(MailMessage message) {#fromMailMessage-com.aspose.email.MailMessage-}
```
public static MapiMessage fromMailMessage(MailMessage message)
```


Creates a message from a [MailMessage](../../com.aspose.email/mailmessage).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message to convert. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The new message.
### fromMailMessage(MailMessage message, MapiConversionOptions options) {#fromMailMessage-com.aspose.email.MailMessage-com.aspose.email.MapiConversionOptions-}
```
public static MapiMessage fromMailMessage(MailMessage message, MapiConversionOptions options)
```


Creates a message from a [MailMessage](../../com.aspose.email/mailmessage) with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message to convert. |
| options | [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) | The options of the conversion. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The new message.
### fromMailMessage(InputStream stream) {#fromMailMessage-java.io.InputStream-}
```
public static MapiMessage fromMailMessage(InputStream stream)
```


Creates a message from a stream in EML format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The new message.
### fromMailMessage(String fileName) {#fromMailMessage-java.lang.String-}
```
public static MapiMessage fromMailMessage(String fileName)
```


Creates a message from an EML file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the EML file. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The new message.
### fromProperties(MapiPropertyCollection properties) {#fromProperties-com.aspose.email.MapiPropertyCollection-}
```
public static MapiMessage fromProperties(MapiPropertyCollection properties)
```


Creates a message from a collection of MAPI properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| properties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | The properties of the message. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The new message.
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


Gets the attachments of the item.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The attachments.
### getBilling() {#getBilling--}
```
public final String getBilling()
```


Gets the billing information of the item.

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public String getBody()
```


Gets the plain-text body of the item.

**Returns:**
java.lang.String - The body.
### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


Gets the body of the item as HTML, converted from \#getBodyRtf().getBodyRtf(); an empty string when there is no RTF body.

**Returns:**
java.lang.String
### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


Gets the body of the item in RTF format.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int), which encapsulates HTML in RTF as Outlook does. Setting  null  or an empty string clears both bodies.

**Returns:**
java.lang.String - The RTF body.
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Gets the format of the body: plain text, HTML or RTF.

**Returns:**
int - The format of the body.
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Gets the categories of the item.

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


Gets the date and time the sender sent the message.

 DateTime.MinValue  is returned when the message has no such date.

**Returns:**
java.util.Date - The date and time the message was sent.
### getCodePage() {#getCodePage--}
```
public int getCodePage()
```


Gets the code page of the ANSI strings of the object.

**Returns:**
int - The code page.
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Gets the names of the companies associated with the item.

**Returns:**
java.lang.String[]
### getConversationTopic() {#getConversationTopic--}
```
public final String getConversationTopic()
```


Gets the topic of the conversation the message belongs to: the subject of its first message, without prefixes.

**Returns:**
java.lang.String - The conversation topic.
### getCustomProperties() {#getCustomProperties--}
```
public final MapiPropertyCollection getCustomProperties()
```


Gets the custom named properties of the message.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The custom properties.
### getDeliveryTime() {#getDeliveryTime--}
```
public final Date getDeliveryTime()
```


Gets the date and time the message was delivered.

 DateTime.MinValue  is returned when the message has no such date.

**Returns:**
java.util.Date - The date and time of delivery.
### getDisplayBcc() {#getDisplayBcc--}
```
public final String getDisplayBcc()
```


Gets the display names of the BCC recipients, separated by semicolons ( ; ).

**Returns:**
java.lang.String - The display names.
### getDisplayCc() {#getDisplayCc--}
```
public final String getDisplayCc()
```


Gets the display names of the CC recipients, separated by semicolons ( ; ).

**Returns:**
java.lang.String - The display names.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the display name of the message.

**Returns:**
java.lang.String - The display name.
### getDisplayNamePrefix() {#getDisplayNamePrefix--}
```
public final String getDisplayNamePrefix()
```


Gets the prefix of the display name, such as a title.

**Returns:**
java.lang.String - The prefix.
### getDisplayTo() {#getDisplayTo--}
```
public final String getDisplayTo()
```


Gets the display names of the To recipients, separated by semicolons ( ; ).

**Returns:**
java.lang.String - The display names.
### getFlags() {#getFlags--}
```
public final long getFlags()
```


Gets the flags of the message, such as read, unsent or has attachments.

**Returns:**
long - The flags.
### getHeaders() {#getHeaders--}
```
public final HeaderCollection getHeaders()
```


Gets the Internet headers of the message.

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getInternetMessageId() {#getInternetMessageId--}
```
public final String getInternetMessageId()
```


Gets the  Message-ID  of the message.

**Returns:**
java.lang.String - The message ID.
### getItemId() {#getItemId--}
```
public String getItemId()
```


Gets the identifier of the item on the mail server, for items obtained from a server;  null  otherwise.

**Returns:**
java.lang.String
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets the message class of the item, such as  IPM.Note  for an e-mail message. The class determines the type of the item.

**Returns:**
java.lang.String - The message class. It is case-sensitive.
### getMessageFormat() {#getMessageFormat--}
```
public final int getMessageFormat()
```


Gets the format of the message: Unicode or ANSI.

**Returns:**
int - The format.
### getMileage() {#getMileage--}
```
public final String getMileage()
```


Gets the mileage information of the item.

**Returns:**
java.lang.String
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of the item.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The named properties.
### getNamedPropertyMapping() {#getNamedPropertyMapping--}
```
public final MapiNamedPropertyMappingStorage getNamedPropertyMapping()
```


Gets the mapping between the named properties and the tags they are stored under.

**Returns:**
[MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) - The named property mapping.
### getNormalizedSubject() {#getNormalizedSubject--}
```
public final String getNormalizedSubject()
```


Gets the subject without its prefix, such as  RE: .

**Returns:**
java.lang.String - The subject without a prefix.
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Gets all properties of the object.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The properties.
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Gets a MAPI property of the item by its descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The property, or  null  if the item does not have it.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


Gets the value of a property as a Boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Boolean - The value, or  null  if the property does not exist.
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


Gets the value of a property as bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
byte[] - The value, or  null  if the property does not exist.
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


Gets the value of a property as a date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The tag of the property. |

**Returns:**
java.util.Date - The value, or  null  if the property does not exist.
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


Gets the value of a property as a 32-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Integer - The value, or  null  if the property does not exist.
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


Gets the value of a property as a 64-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Long - The value, or  null  if the property does not exist.
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


Gets the value of a property as a 16-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Short - The value, or  null  if the property does not exist.
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Gets the property stream of the item.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream) - The property stream.
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


Gets the value of a property as a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


Gets the value of a property as a string, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### getReadReceiptRequested() {#getReadReceiptRequested--}
```
public final boolean getReadReceiptRequested()
```


Gets a value indicating whether a read receipt is requested.

**Returns:**
boolean -  true  if a read receipt is requested; otherwise,  false .
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


Gets the recipients of the item.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) - The recipients.
### getReplyTo() {#getReplyTo--}
```
public final String getReplyTo()
```


Gets the addresses that replies go to, separated by semicolons ( ; ).

Gets or sets the list of ReplyTo addresses separated by semicolon.

**Returns:**
java.lang.String - The reply addresses.
### getSenderAddressType() {#getSenderAddressType--}
```
public final String getSenderAddressType()
```


Gets the type of the address of the sender, such as  SMTP  or  EX .

**Returns:**
java.lang.String - The address type.
### getSenderEmailAddress() {#getSenderEmailAddress--}
```
public final String getSenderEmailAddress()
```


Gets the message sender's e-mail address.

Setting the address also updates the search key and the EntryID of the sender. Setting  null  or an empty string clears them.

**Returns:**
java.lang.String - The e-mail address of the sender.
### getSenderName() {#getSenderName--}
```
public final String getSenderName()
```


Gets the message sender's display name.

Setting  null  or an empty string sets the name to \#getSenderEmailAddress().getSenderEmailAddress().

**Returns:**
java.lang.String - The display name of the sender.
### getSenderSmtpAddress() {#getSenderSmtpAddress--}
```
public final String getSenderSmtpAddress()
```


Gets the SMTP address of the sender.

Use this property when the sender address is of another type, such as an Exchange ( EX ) address. Setting the address also updates the search key and the EntryID of the sender; setting  null  or an empty string clears them.

**Returns:**
java.lang.String - The SMTP address of the sender.
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the sensitivity of the item: normal, personal, private or confidential.

**Returns:**
int - The sensitivity.
### getSentRepresentingAddressType() {#getSentRepresentingAddressType--}
```
public final String getSentRepresentingAddressType()
```


Gets the address type of the user on whose behalf the message was sent.

**Returns:**
java.lang.String - The address type.
### getSentRepresentingEmailAddress() {#getSentRepresentingEmailAddress--}
```
public final String getSentRepresentingEmailAddress()
```


Gets the e-mail address of the user on whose behalf the message was sent.

Setting the address also updates the search key and the EntryID of that user. Setting  null  or an empty string clears them.

**Returns:**
java.lang.String - The e-mail address.
### getSentRepresentingName() {#getSentRepresentingName--}
```
public final String getSentRepresentingName()
```


Gets the display name of the user on whose behalf the message was sent.

Setting  null  or an empty string sets the name to \#getSentRepresentingEmailAddress().getSentRepresentingEmailAddress().

**Returns:**
java.lang.String - The display name.
### getSentRepresentingSmtpAddress() {#getSentRepresentingSmtpAddress--}
```
public final String getSentRepresentingSmtpAddress()
```


Gets the SMTP address of the user on whose behalf the message was sent.

**Returns:**
java.lang.String - The SMTP address.
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Gets the sub-storages of the item.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The sub-storages.
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject of the message.

Setting the subject also sets the subject prefix (such as  RE: ) and the normalized subject (the subject without the prefix). Setting  null  or an empty string clears all three.

**Returns:**
java.lang.String - The subject.
### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


Gets the prefix of the subject, such as  RE:  or  FW: .

**Returns:**
java.lang.String - The subject prefix.
### getSupportedType() {#getSupportedType--}
```
public final int getSupportedType()
```


Gets the type of the item, as determined by its message class.

**Returns:**
int - The item type.
### getTransportMessageHeaders() {#getTransportMessageHeaders--}
```
public final String getTransportMessageHeaders()
```


Gets the Internet headers of the message as one string.

**Returns:**
java.lang.String - The headers.
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


Gets a value indicating whether the message is encrypted (S/MIME).

**Returns:**
boolean
### isMsgFormat(InputStream stream) {#isMsgFormat-java.io.InputStream-}
```
public static boolean isMsgFormat(InputStream stream)
```


Determines whether a stream contains a message in MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to check. |

**Returns:**
boolean -  true  if the stream is in MSG format; otherwise,  false .
### isMsgFormat(String fileName) {#isMsgFormat-java.lang.String-}
```
public static boolean isMsgFormat(String fileName)
```


Determines whether a file is in MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file. |

**Returns:**
boolean -  true  if the file is in MSG format; otherwise,  false .
### isSigned() {#isSigned--}
```
public final boolean isSigned()
```


Gets a value indicating whether the message is digitally signed.

**Returns:**
boolean
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


Determines whether the string properties of the object are stored in Unicode.

**Returns:**
boolean -  true  if the strings are Unicode;  false  if they are ANSI.
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Gets a value indicating whether the message is an Outlook template (.oft).

**Returns:**
boolean -  true  if the message is a template; otherwise,  false .
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static MapiMessage load(InputStream stream)
```


Loads a message from a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The loaded message.
### load(InputStream stream, LoadOptions options) {#load-java.io.InputStream-com.aspose.email.LoadOptions-}
```
public static MapiMessage load(InputStream stream, LoadOptions options)
```


Loads a message from a stream with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | The options of loading. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The loaded message.
### load(String fileName) {#load-java.lang.String-}
```
public static MapiMessage load(String fileName)
```


Loads a message from a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The loaded message.
### load(String fileName, LoadOptions options) {#load-java.lang.String-com.aspose.email.LoadOptions-}
```
public static MapiMessage load(String fileName, LoadOptions options)
```


Loads a message from a file with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | The options of loading. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The loaded message.
### loadFromTnef(InputStream stream) {#loadFromTnef-java.io.InputStream-}
```
public static MapiMessage loadFromTnef(InputStream stream)
```


Loads a message from a stream in TNEF format (the content of a winmail.dat attachment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The loaded message.
### loadFromTnef(String fileName) {#loadFromTnef-java.lang.String-}
```
public static MapiMessage loadFromTnef(String fileName)
```


Loads a message from a file in TNEF format, such as winmail.dat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The loaded message.
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


Removes all attachments from an MSG file, overwrites the file, and returns the removed attachments.

This example removes the attachments from an MSG file and saves them to disk.

```

 MapiAttachmentCollection attachments = MapiMessage.removeAttachments("c:\\messages\\message.msg");

 for (MapiAttachment attachment : attachments) {
     System.out.println("Attachment: " + attachment.getLongFileName());
     attachment.save(Paths.get("c:\\attachments", attachment.getLongFileName()).toString());
 }
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path of the MSG file. |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The removed attachments.
### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Removes a property from the item, including its named-property mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property to remove. |

### removeSignature() {#removeSignature--}
```
public final MapiMessage removeSignature()
```


Returns a copy of a signed message without the signature.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The message without the signature.
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves the message to a stream in MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.email.SaveOptions-}
```
public final void save(OutputStream stream, SaveOptions options)
```


Saves the message to a stream in the format selected by the options, such as MSG, OFT, EML, EMLX, HTML or MHTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | The options; their class selects the format. |

### save(String fileName) {#save-java.lang.String-}
```
public final void save(String fileName)
```


Saves the message to a file in MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to write. |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.email.SaveOptions-}
```
public final void save(String fileName, SaveOptions options)
```


Saves the message to a file in the format selected by the options, such as MSG, OFT, EML, EMLX, HTML or MHTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to write. |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | The options; their class selects the format. |

### saveAsTemplate(OutputStream stream) {#saveAsTemplate-java.io.OutputStream-}
```
public final void saveAsTemplate(OutputStream stream)
```


Saves the message to a stream as an Outlook template (.oft).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### saveAsTemplate(String fileName) {#saveAsTemplate-java.lang.String-}
```
public final void saveAsTemplate(String fileName)
```


Saves the message to a file as an Outlook template (.oft).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to write. |

### saveAsTnef(OutputStream stream) {#saveAsTnef-java.io.OutputStream-}
```
public final void saveAsTnef(OutputStream stream)
```


Saves the message to a stream in TNEF format (the format of winmail.dat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### saveAsTnef(String fileName) {#saveAsTnef-java.lang.String-}
```
public final void saveAsTnef(String fileName)
```


Saves the message to a file in TNEF format (the format of winmail.dat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to write. |

### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


Sets the billing information of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


Sets the plain-text body of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The body. |

### setBodyContent(String content, int contentType) {#setBodyContent-java.lang.String-int-}
```
public void setBodyContent(String content, int contentType)
```


Sets the body of the item in the specified format.

The plain-text body, the RTF body and the compressed RTF property are all updated. After HTML content is set, \#getBodyRtf().getBodyRtf() returns that HTML encapsulated in RTF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The text of the body. |
| contentType | int | The format of  content . |

### setBodyContent(String content, int contentType, boolean compression) {#setBodyContent-java.lang.String-int-boolean-}
```
public void setBodyContent(String content, int contentType, boolean compression)
```


Sets the body of the item in the specified format, optionally compressing it.

The plain-text body, the RTF body and the compressed RTF property are all updated. After HTML content is set, \#getBodyRtf().getBodyRtf() returns that HTML encapsulated in RTF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The text of the body. |
| contentType | int | The format of  content . |
| compression | boolean |  true  to store the RTF body compressed. |

### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


Sets the body of the item in RTF format.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int), which encapsulates HTML in RTF as Outlook does. Setting  null  or an empty string clears both bodies.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The RTF body. |

### setBodyRtf(String value, boolean compression) {#setBodyRtf-java.lang.String-boolean-}
```
public final void setBodyRtf(String value, boolean compression)
```


Sets the body of the item in RTF format, optionally compressing it.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int). Setting  null  or an empty string clears both bodies.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The body in RTF. |
| compression | boolean |  true  to store the RTF body compressed. |

### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


Sets the categories of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setClientSubmitTime(Date value) {#setClientSubmitTime-java.util.Date-}
```
public final void setClientSubmitTime(Date value)
```


Sets the date and time the sender sent the message.

 DateTime.MinValue  is returned when the message has no such date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The date and time the message was sent. |

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Sets the names of the companies associated with the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setDeliveryTime(Date value) {#setDeliveryTime-java.util.Date-}
```
public final void setDeliveryTime(Date value)
```


Sets the date and time the message was delivered.

 DateTime.MinValue  is returned when the message has no such date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The date and time of delivery. |

### setHeaders(HeaderCollection value) {#setHeaders-com.aspose.email.HeaderCollection-}
```
public final void setHeaders(HeaderCollection value)
```


Sets the Internet headers of the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HeaderCollection](../../com.aspose.email/headercollection) |  |

### setMessageClass(String value) {#setMessageClass-java.lang.String-}
```
public final void setMessageClass(String value)
```


Sets the message class of the item, such as  IPM.Note  for an e-mail message. The class determines the type of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The message class. It is case-sensitive. |

### setMessageFlags(long flags) {#setMessageFlags-long-}
```
public final void setMessageFlags(long flags)
```


Sets the flags of the message, such as read or unsent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The flags to set. |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Sets the mileage information of the item.

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


Adds the property, or replaces the property with the same tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | The property to set. |

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


Sets the value of a MAPI property of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |
| value | java.lang.Object | The value, of a Java type that matches the data type of the property. |

### setReadReceiptRequested(boolean value) {#setReadReceiptRequested-boolean-}
```
public final void setReadReceiptRequested(boolean value)
```


Sets a value indicating whether a read receipt is requested.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if a read receipt is requested; otherwise,  false . |

### setRecipients(MapiRecipientCollection value) {#setRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setRecipients(MapiRecipientCollection value)
```


Sets the recipients of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) | The recipients. |

### setReplyTo(String value) {#setReplyTo-java.lang.String-}
```
public final void setReplyTo(String value)
```


Sets the addresses that replies go to, separated by semicolons ( ; ).

Gets or sets the list of ReplyTo addresses separated by semicolon.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The reply addresses. |

### setSenderEmailAddress(String value) {#setSenderEmailAddress-java.lang.String-}
```
public final void setSenderEmailAddress(String value)
```


Sets the message sender's e-mail address.

Setting the address also updates the search key and the EntryID of the sender. Setting  null  or an empty string clears them.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The e-mail address of the sender. |

### setSenderName(String value) {#setSenderName-java.lang.String-}
```
public final void setSenderName(String value)
```


Sets the message sender's display name.

Setting  null  or an empty string sets the name to \#getSenderEmailAddress().getSenderEmailAddress().

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The display name of the sender. |

### setSenderSmtpAddress(String value) {#setSenderSmtpAddress-java.lang.String-}
```
public final void setSenderSmtpAddress(String value)
```


Sets the SMTP address of the sender.

Use this property when the sender address is of another type, such as an Exchange ( EX ) address. Setting the address also updates the search key and the EntryID of the sender; setting  null  or an empty string clears them.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The SMTP address of the sender. |

### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


Sets the sensitivity of the item: normal, personal, private or confidential.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The sensitivity. |

### setSentRepresentingEmailAddress(String value) {#setSentRepresentingEmailAddress-java.lang.String-}
```
public final void setSentRepresentingEmailAddress(String value)
```


Sets the e-mail address of the user on whose behalf the message was sent.

Setting the address also updates the search key and the EntryID of that user. Setting  null  or an empty string clears them.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The e-mail address. |

### setSentRepresentingName(String value) {#setSentRepresentingName-java.lang.String-}
```
public final void setSentRepresentingName(String value)
```


Sets the display name of the user on whose behalf the message was sent.

Setting  null  or an empty string sets the name to \#getSentRepresentingEmailAddress().getSentRepresentingEmailAddress().

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The display name. |

### setStringPropertyValue(long tag, String value) {#setStringPropertyValue-long-java.lang.String-}
```
public final void setStringPropertyValue(long tag, String value)
```


Sets the value of a string property, in the string format of the message (Unicode or ANSI).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.lang.String | The value. |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets the subject of the message.

Setting the subject also sets the subject prefix (such as  RE: ) and the normalized subject (the subject without the prefix). Setting  null  or an empty string clears all three.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The subject. |

### toMailMessage(MailConversionOptions options) {#toMailMessage-com.aspose.email.MailConversionOptions-}
```
public final MailMessage toMailMessage(MailConversionOptions options)
```


Converts the message to a [MailMessage](../../com.aspose.email/mailmessage) with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [MailConversionOptions](../../com.aspose.email/mailconversionoptions) | The options of the conversion. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The new [MailMessage](../../com.aspose.email/mailmessage).
### toMapiMessageItem() {#toMapiMessageItem--}
```
public final IMapiMessageItem toMapiMessageItem()
```


Converts the message to the item class that matches its message class, such as [MapiContact](../../com.aspose.email/mapicontact) for  IPM.Contact .

The supported message classes are  IPM.Note ,  IPM.Contact ,  IPM.DistList ,  IPM.Appointment ,  IPM.Schedule.Meeting ,  IPM.Task ,  IPM.StickyNote  and  IPM.Activity . Check [MapiMessageItemBase.getSupportedType()](../../com.aspose.email/mapimessageitembase\#getSupportedType--) before the call to avoid the exception.

**Returns:**
[IMapiMessageItem](../../com.aspose.email/imapimessageitem) - The item: a [MapiContact](../../com.aspose.email/mapicontact), [MapiCalendar](../../com.aspose.email/mapicalendar), [MapiTask](../../com.aspose.email/mapitask), [MapiNote](../../com.aspose.email/mapinote), [MapiJournal](../../com.aspose.email/mapijournal) or [MapiDistributionList](../../com.aspose.email/mapidistributionlist); a copy of the message for  IPM.Note .
### toMvPropertyList(Object obj) {#toMvPropertyList-java.lang.Object-}
```
public static System.Collections.Generic.IGenericList<Object> toMvPropertyList(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Object>
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


Gets the value of a property as bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
byte[] - The value, or  null  if the property does not exist.
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


Gets the value of a property as a date and time, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.util.Date[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


Gets the value of a property as a 32-bit integer, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | int[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


Gets the value of a property as a 64-bit integer, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | long[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


Gets the value of a property as a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


Gets the value of a property as a string, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


Gets the value of a property as a string, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.lang.String[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.lang.String[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
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

