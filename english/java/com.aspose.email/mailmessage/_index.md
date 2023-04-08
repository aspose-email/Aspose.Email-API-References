---
title: MailMessage
second_title: Aspose.Email for Java API Reference
description: Represents an e-mail message.
type: docs
weight: 368
url: /java/com.aspose.email/mailmessage/
---

**Inheritance:**
java.lang.Object, com.aspose.email.IPreferredTextEncodingProviderInternal

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable, [com.aspose.email.IPreferredTextEncodingProvider](../../com.aspose.email/ipreferredtextencodingprovider), [com.aspose.email.IMessage](../../com.aspose.email/imessage), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class MailMessage extends IPreferredTextEncodingProviderInternal implements System.IDisposable, Closeable, IPreferredTextEncodingProvider, IMessage, System.Collections.Generic.IGenericEnumerable<MailMessage>
```

Represents an e-mail message. It allows to access message properties, ex. subject, body, sender and recipients addreses, etc. Also it can be sent and delivered by means of supported mail protocols.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailMessage(String from, String to)](#MailMessage-java.lang.String-java.lang.String-) | Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class |
| [MailMessage()](#MailMessage--) | Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class |
| [MailMessage(String from, String to, String subject, String body)](#MailMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class |
| [MailMessage(MailAddress from, MailAddress to)](#MailMessage-com.aspose.email.MailAddress-com.aspose.email.MailAddress-) | Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class |
## Methods

| Method | Description |
| --- | --- |
| [addAlternateView(AlternateView view)](#addAlternateView-com.aspose.email.AlternateView-) | Add an alternate view to message |
| [addAttachment(Attachment attachment)](#addAttachment-com.aspose.email.Attachment-) | Add an attachment to message |
| [attachSignature(byte[] certificateRawData, String certificatePassword)](#attachSignature-byte---java.lang.String-) | Creates a signed message. |
| [attachSignature(byte[] certificateRawData, String certificatePassword, boolean detached)](#attachSignature-byte---java.lang.String-boolean-) | Creates a signed message. |
| [attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) |  |
| [attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, boolean detached)](#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | Creates a signed message. |
| [checkBounced()](#checkBounced--) | Checks whether this message can be treated as a bounce message. |
| [checkSignature()](#checkSignature--) | Checking signature exsisting MailMessage. |
| [checkSignature(InputStream stream)](#checkSignature-java.io.InputStream-) | Checks the signature of the specified eml message. |
| [checkSignature(String fileName)](#checkSignature-java.lang.String-) | Checks the signature of the specified eml file. |
| [checkSignatureCert()](#checkSignatureCert--) | Checking signature exsisting MailMessage. |
| [close()](#close--) |  |
| [createReadReceipt(String from, String bodyText)](#createReadReceipt-java.lang.String-java.lang.String-) | Creates the read receipt. |
| [dKIMSign(System.Security.Cryptography.RSACryptoServiceProvider rsa, DKIMSignatureInfo signatureInfo)](#dKIMSign-com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider-com.aspose.email.DKIMSignatureInfo-) | Signs this message using DKIM (DomainKeys Identified Mail) signature. |
| [decrypt()](#decrypt--) | Decrypts this message |
| [decrypt(byte[] certificateRawData, String certificatePassword)](#decrypt-byte---java.lang.String-) | Decrypts this message |
| [decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#decrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) |  |
| [deepClone()](#deepClone--) | Clones this instance |
| [dispose()](#dispose--) | Releases all resources used by the MailMessage |
| [encrypt(byte[] certificateRawData, String certificatePassword)](#encrypt-byte---java.lang.String-) | Encrypts this message |
| [encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) |  |
| [encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2[] certificates)](#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2---) | Encrypts this message |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [getAlternateViews()](#getAlternateViews--) | Gets the collection of alternate views of message |
| [getAttachments()](#getAttachments--) | Gets the collection of attachments of message |
| [getBcc()](#getBcc--) | Gets or sets the address collection that contains the BCC recipients of message |
| [getBody()](#getBody--) | Gets or sets the plain text representation of message's body. |
| [getBodyEncoding()](#getBodyEncoding--) | Gets or sets encoding of body |
| [getBodyType()](#getBodyType--) | Gets the type of the body. |
| [getCC()](#getCC--) | Gets or sets the address collection that contains the CC recipients |
| [getCc()](#getCc--) | Gets CC recipients |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | Gets or sets the date of message Specifies the date and time at which the creator of the message indicated that the message was complete and ready to enter the mail delivery system. |
| [getDeliveryNotificationOptions()](#getDeliveryNotificationOptions--) | Gets or sets the delivery notifications |
| [getEpilogue()](#getEpilogue--) | Gets or sets an epilogue text. |
| [getFrom()](#getFrom--) | Gets or sets the from address |
| [getHeaders()](#getHeaders--) | Gets headers collection of message |
| [getHtmlBody()](#getHtmlBody--) | Gets or sets html body |
| [getHtmlBodyText()](#getHtmlBodyText--) | Gets the message htmlbody as plain text. |
| [getHtmlBodyText(boolean showUrl)](#getHtmlBodyText-boolean-) | Gets the message html body as plain text. |
| [getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback)](#getHtmlBodyText-com.aspose.email.HyperlinkRenderingCallback-) | Gets the message htmlbody as plain text. |
| [getItemId()](#getItemId--) | Represents identification information about message in a mailbox. |
| [getLinkedResources()](#getLinkedResources--) | Gets the collection of linked resources of message |
| [getLocalDate()](#getLocalDate--) | Gets the local date of message |
| [getMessageId()](#getMessageId--) | Gets or sets the message id |
| [getOriginalIsTnef()](#getOriginalIsTnef--) | Gets a value indicating whether original EML message is in TNEF format. |
| [getPreamble()](#getPreamble--) | Gets or sets a preamble text. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets or sets preferred encoding for all text properties |
| [getPriority()](#getPriority--) | Gets or sets the priority of message |
| [getReadReceiptTo()](#getReadReceiptTo--) | Gets or sets the read receipt address. |
| [getReplyToList()](#getReplyToList--) | Gets or sets the list of addresses to reply to for the mail message |
| [getReversePath()](#getReversePath--) | Gets or sets ReversePath address |
| [getSender()](#getSender--) | Gets or sets sender address |
| [getSensitivity()](#getSensitivity--) | Gets or sets the sensitivity of message |
| [getSubject()](#getSubject--) | Gets or sets the subject line |
| [getSubjectEncoding()](#getSubjectEncoding--) | Gets or sets the encoding of subject |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. |
| [getTo()](#getTo--) | Gets or sets the address collection that contains the recipients of message |
| [getXMailer()](#getXMailer--) | Gets or sets the X-Mailer the software that created the e-mail message |
| [hashCode()](#hashCode--) | Returns a hash code for object |
| [importMessage(InputStream stream)](#importMessage-java.io.InputStream-) | Imports message from stream |
| [isBodyHtml()](#isBodyHtml--) | Gets or sets a value indicating whether the message body is in Html |
| [isBodyHtml(boolean value)](#isBodyHtml-boolean-) | Gets or sets a value indicating whether the message body is in Html |
| [isDraft()](#isDraft--) | Gets or sets value that indicates whether or not a message has been sent. |
| [isDraft(boolean value)](#isDraft-boolean-) | Gets or sets value that indicates whether or not a message has been sent. |
| [isEncrypted()](#isEncrypted--) | Gets a value indicating whether the message is encrypted. |
| [isLocalDate()](#isLocalDate--) | Defines if date is local date |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the message is read only |
| [isSigned()](#isSigned--) | Gets a value indicating whether the message is signed. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through a collection. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Load message from stream |
| [load(InputStream stream, LoadOptions options)](#load-java.io.InputStream-com.aspose.email.LoadOptions-) | Load message from stream with additional options. |
| [load(String fileName)](#load-java.lang.String-) | Load message from file |
| [load(String fileName, LoadOptions options)](#load-java.lang.String-com.aspose.email.LoadOptions-) | Load message from file with additional options. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [recomposeTnefContent()](#recomposeTnefContent--) | Composes the TNEF content. |
| [removeSignature()](#removeSignature--) | Remove signature |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Save message as a stream |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.email.SaveOptions-) | Save message as a stream with additional options. |
| [save(String fileName)](#save-java.lang.String-) | Save message as a file |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.email.SaveOptions-) | Save message as a file with additional options. |
| [setBcc(MailAddressCollection value)](#setBcc-com.aspose.email.MailAddressCollection-) | Gets or sets the address collection that contains the BCC recipients of message |
| [setBody(String value)](#setBody-java.lang.String-) | Gets or sets the plain text representation of message's body. |
| [setBodyEncoding(Charset value)](#setBodyEncoding-java.nio.charset.Charset-) | Gets or sets encoding of body |
| [setCC(MailAddressCollection value)](#setCC-com.aspose.email.MailAddressCollection-) | Gets or sets the address collection that contains the CC recipients |
| [setDate(Date value)](#setDate-java.util.Date-) | Gets or sets the date of message |
| [setDeliveryNotificationOptions(int value)](#setDeliveryNotificationOptions-int-) | Gets or sets the delivery notifications |
| [setEpilogue(String value)](#setEpilogue-java.lang.String-) | Gets or sets an epilogue text. |
| [setFrom(IMailAddress value)](#setFrom-com.aspose.email.IMailAddress-) | Sets from address |
| [setFrom(MailAddress value)](#setFrom-com.aspose.email.MailAddress-) | Gets or sets the from address |
| [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Gets or sets html body |
| [setHtmlBody(String value, boolean detectEncoding)](#setHtmlBody-java.lang.String-boolean-) | Sets html body. |
| [setMessageId(String value)](#setMessageId-java.lang.String-) | Gets or sets the message id |
| [setPreamble(String value)](#setPreamble-java.lang.String-) | Gets or sets a preamble text. |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Gets or sets preferred encoding for all text properties |
| [setPriority(MailPriority value)](#setPriority-com.aspose.email.MailPriority-) | Gets or sets the priority of message |
| [setReadReceiptTo(MailAddressCollection value)](#setReadReceiptTo-com.aspose.email.MailAddressCollection-) | Gets or sets the read receipt address. |
| [setReplyToList(MailAddressCollection value)](#setReplyToList-com.aspose.email.MailAddressCollection-) | Gets or sets the list of addresses to reply to for the mail message |
| [setReversePath(MailAddress value)](#setReversePath-com.aspose.email.MailAddress-) | Gets or sets ReversePath address |
| [setSender(MailAddress value)](#setSender-com.aspose.email.MailAddress-) | Gets or sets sender address |
| [setSensitivity(MailSensitivity value)](#setSensitivity-com.aspose.email.MailSensitivity-) | Gets or sets the sensitivity of message |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets the subject line |
| [setSubjectEncoding(Charset value)](#setSubjectEncoding-java.nio.charset.Charset-) | Gets or sets the encoding of subject |
| [setTimeZoneOffset(double value)](#setTimeZoneOffset-double-) | Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. |
| [setTo(MailAddressCollection value)](#setTo-com.aspose.email.MailAddressCollection-) | Gets or sets the address collection that contains the recipients of message |
| [setXMailer(String value)](#setXMailer-java.lang.String-) | Gets or sets the X-Mailer the software that created the e-mail message |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [validateMessage(InputStream stream)](#validateMessage-java.io.InputStream-) | Validate eml message for corresponding to mime specification. |
| [validateMessage(String fileName)](#validateMessage-java.lang.String-) | Validate eml message for corresponding to mime specification. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailMessage(String from, String to) {#MailMessage-java.lang.String-java.lang.String-}
```
public MailMessage(String from, String to)
```


Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | Sender address |
| to | java.lang.String | Recipient address |

### MailMessage() {#MailMessage--}
```
public MailMessage()
```


Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class

### MailMessage(String from, String to, String subject, String body) {#MailMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public MailMessage(String from, String to, String subject, String body)
```


Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | Sender address |
| to | java.lang.String | Recipient address |
| subject | java.lang.String | Message subject |
| body | java.lang.String | Message body |

### MailMessage(MailAddress from, MailAddress to) {#MailMessage-com.aspose.email.MailAddress-com.aspose.email.MailAddress-}
```
public MailMessage(MailAddress from, MailAddress to)
```


Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | [MailAddress](../../com.aspose.email/mailaddress) | Sender address |
| to | [MailAddress](../../com.aspose.email/mailaddress) | Recipient address |

### addAlternateView(AlternateView view) {#addAlternateView-com.aspose.email.AlternateView-}
```
public void addAlternateView(AlternateView view)
```


Add an alternate view to message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| view | [AlternateView](../../com.aspose.email/alternateview) | Alternate view for adding |

### addAttachment(Attachment attachment) {#addAttachment-com.aspose.email.Attachment-}
```
public void addAttachment(Attachment attachment)
```


Add an attachment to message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attachment | [Attachment](../../com.aspose.email/attachment) | Attachment for adding |

### attachSignature(byte[] certificateRawData, String certificatePassword) {#attachSignature-byte---java.lang.String-}
```
public MailMessage attachSignature(byte[] certificateRawData, String certificatePassword)
```


Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateRawData | byte[] | X.509 certificate. |
| certificatePassword | java.lang.String | The password required to access the X.509 certificate data |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The signed MailMessage.
### attachSignature(byte[] certificateRawData, String certificatePassword, boolean detached) {#attachSignature-byte---java.lang.String-boolean-}
```
public MailMessage attachSignature(byte[] certificateRawData, String certificatePassword, boolean detached)
```


Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateRawData | byte[] | X.509 certificate. |
| certificatePassword | java.lang.String | The password required to access the X.509 certificate data |
| detached | boolean | .If detached is true, the signature is detached.If detached is false(the default), the signature is not detached. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The signed MailMessage.
### attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public MailMessage attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, boolean detached) {#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
```
public MailMessage attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, boolean detached)
```


Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | X.509 certificate. |
| detached | boolean | .If detached is true, the signature is detached.If detached is false(the default), the signature is not detached. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - 
### checkBounced() {#checkBounced--}
```
public BounceResult checkBounced()
```


Checks whether this message can be treated as a bounce message.

**Returns:**
[BounceResult](../../com.aspose.email/bounceresult) - Result of checking[BounceResult](../../com.aspose.email/bounceresult).
### checkSignature() {#checkSignature--}
```
public String[] checkSignature()
```


Checking signature exsisting MailMessage.

**Returns:**
java.lang.String[] - X.509 signers certificates
### checkSignature(InputStream stream) {#checkSignature-java.io.InputStream-}
```
public static boolean checkSignature(InputStream stream)
```


Checks the signature of the specified eml message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream containing the message in eml format. |

**Returns:**
boolean -  True  if signature is valid; otherwise,  false .
### checkSignature(String fileName) {#checkSignature-java.lang.String-}
```
public static boolean checkSignature(String fileName)
```


Checks the signature of the specified eml file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | A file name (eml). |

**Returns:**
boolean -  True  if signature is valid; otherwise,  false .
### checkSignatureCert() {#checkSignatureCert--}
```
public System.Security.Cryptography.X509Certificates.X509Certificate2[] checkSignatureCert()
```


Checking signature exsisting MailMessage.

**Returns:**
com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2[] - X.509 signers certificates
### close() {#close--}
```
public void close()
```




### createReadReceipt(String from, String bodyText) {#createReadReceipt-java.lang.String-java.lang.String-}
```
public final MailMessage createReadReceipt(String from, String bodyText)
```


Creates the read receipt.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | String that represents the sender address. |
| bodyText | java.lang.String | The message body text. The default message body text will be applied if this parameter is null or empty. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A newly created [MailMessage](../../com.aspose.email/mailmessage) that represents the read receipt.
### dKIMSign(System.Security.Cryptography.RSACryptoServiceProvider rsa, DKIMSignatureInfo signatureInfo) {#dKIMSign-com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider-com.aspose.email.DKIMSignatureInfo-}
```
public MailMessage dKIMSign(System.Security.Cryptography.RSACryptoServiceProvider rsa, DKIMSignatureInfo signatureInfo)
```


Signs this message using DKIM (DomainKeys Identified Mail) signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rsa | com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider | RSA class containing private key used for signing. |
| signatureInfo | [DKIMSignatureInfo](../../com.aspose.email/dkimsignatureinfo) | DKIM signature information. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - 
### decrypt() {#decrypt--}
```
public MailMessage decrypt()
```


Decrypts this message

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Decrypted E-mail message

--------------------

Method searches the current user and computer My stores for the appropriate certificate and private key.
### decrypt(byte[] certificateRawData, String certificatePassword) {#decrypt-byte---java.lang.String-}
```
public MailMessage decrypt(byte[] certificateRawData, String certificatePassword)
```


Decrypts this message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateRawData | byte[] | System.Security.Cryptography.X509Certificates.X509Certificate2 |
| certificatePassword | java.lang.String | The password required to access the X.509 certificate data |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#decrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public MailMessage decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### deepClone() {#deepClone--}
```
public MailMessage deepClone()
```


Clones this instance

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - MailMessage that is a copy of the current instance
### dispose() {#dispose--}
```
public final void dispose()
```


Releases all resources used by the MailMessage

### encrypt(byte[] certificateRawData, String certificatePassword) {#encrypt-byte---java.lang.String-}
```
public MailMessage encrypt(byte[] certificateRawData, String certificatePassword)
```


Encrypts this message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateRawData | byte[] | X509 certificate to encrypt message |
| certificatePassword | java.lang.String |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Encrypted email message
### encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public MailMessage encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2[] certificates) {#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2---}
```
public MailMessage encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2[] certificates)
```


Encrypts this message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificates | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2[] | Array with X509 certificates to encrypt message |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Encrypted email message
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object is equal to the current Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with the current Object. |

**Returns:**
boolean - Returns a boolean indicating if the passed in object obj is Equal to this.
### getAlternateViews() {#getAlternateViews--}
```
public AlternateViewCollection getAlternateViews()
```


Gets the collection of alternate views of message

**Returns:**
[AlternateViewCollection](../../com.aspose.email/alternateviewcollection)
### getAttachments() {#getAttachments--}
```
public AttachmentCollection getAttachments()
```


Gets the collection of attachments of message

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getBcc() {#getBcc--}
```
public MailAddressCollection getBcc()
```


Gets or sets the address collection that contains the BCC recipients of message

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getBody() {#getBody--}
```
public String getBody()
```


Gets or sets the plain text representation of message's body. If the text/plain part is present in a message, the propery returns its text data. Otherwise, property returns the text content of the HtmlBody property without html markup.

**Returns:**
java.lang.String
### getBodyEncoding() {#getBodyEncoding--}
```
public Charset getBodyEncoding()
```


Gets or sets encoding of body

**Returns:**
java.nio.charset.Charset
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Gets the type of the body.

**Returns:**
int
### getCC() {#getCC--}
```
public MailAddressCollection getCC()
```


Gets or sets the address collection that contains the CC recipients

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getCc() {#getCc--}
```
public final System.Collections.Generic.IGenericCollection<MailAddress> getCc()
```


Gets CC recipients

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDate() {#getDate--}
```
public Date getDate()
```


Gets or sets the date of message Specifies the date and time at which the creator of the message indicated that the message was complete and ready to enter the mail delivery system.

**Returns:**
java.util.Date
### getDeliveryNotificationOptions() {#getDeliveryNotificationOptions--}
```
public int getDeliveryNotificationOptions()
```


Gets or sets the delivery notifications

**Returns:**
int
### getEpilogue() {#getEpilogue--}
```
public final String getEpilogue()
```


Gets or sets an epilogue text. It is located after the last boundary.

Value: The string value that represents an epilogue.

**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public MailAddress getFrom()
```


Gets or sets the from address

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getHeaders() {#getHeaders--}
```
public HeaderCollection getHeaders()
```


Gets headers collection of message

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getHtmlBody() {#getHtmlBody--}
```
public String getHtmlBody()
```


Gets or sets html body

**Returns:**
java.lang.String
### getHtmlBodyText() {#getHtmlBodyText--}
```
public final String getHtmlBodyText()
```


Gets the message htmlbody as plain text.

**Returns:**
java.lang.String
### getHtmlBodyText(boolean showUrl) {#getHtmlBodyText-boolean-}
```
public String getHtmlBodyText(boolean showUrl)
```


Gets the message html body as plain text. This method parses the HtmlBody property and returns plain text content ignoring the html markup.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| showUrl | boolean | Defines need to show URL in text. |

**Returns:**
java.lang.String
### getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback) {#getHtmlBodyText-com.aspose.email.HyperlinkRenderingCallback-}
```
public String getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback)
```


Gets the message htmlbody as plain text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hyperlinkRenderingCallback | [HyperlinkRenderingCallback](../../com.aspose.email/hyperlinkrenderingcallback) | Reference to custom method for handling rendering of hyperlink. |

**Returns:**
java.lang.String - Result string of custom handling rendering of hyperlink.
### getItemId() {#getItemId--}
```
public MailboxInfo getItemId()
```


Represents identification information about message in a mailbox.

**Returns:**
[MailboxInfo](../../com.aspose.email/mailboxinfo)
### getLinkedResources() {#getLinkedResources--}
```
public LinkedResourceCollection getLinkedResources()
```


Gets the collection of linked resources of message

**Returns:**
[LinkedResourceCollection](../../com.aspose.email/linkedresourcecollection)
### getLocalDate() {#getLocalDate--}
```
public Date getLocalDate()
```


Gets the local date of message

**Returns:**
java.util.Date - A local date of message
### getMessageId() {#getMessageId--}
```
public String getMessageId()
```


Gets or sets the message id

**Returns:**
java.lang.String
### getOriginalIsTnef() {#getOriginalIsTnef--}
```
public boolean getOriginalIsTnef()
```


Gets a value indicating whether original EML message is in TNEF format.

**Returns:**
boolean
### getPreamble() {#getPreamble--}
```
public final String getPreamble()
```


Gets or sets a preamble text. It is located before the first boundary and generally includes an explanatory note to non-MIME conformant readers.

Value: The string value that represents a preamble.

**Returns:**
java.lang.String
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Gets or sets preferred encoding for all text properties

**Returns:**
java.nio.charset.Charset
### getPriority() {#getPriority--}
```
public MailPriority getPriority()
```


Gets or sets the priority of message

**Returns:**
[MailPriority](../../com.aspose.email/mailpriority)
### getReadReceiptTo() {#getReadReceiptTo--}
```
public final MailAddressCollection getReadReceiptTo()
```


Gets or sets the read receipt address.

Value: The [MailAddressCollection](../../com.aspose.email/mailaddresscollection) that represents

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getReplyToList() {#getReplyToList--}
```
public MailAddressCollection getReplyToList()
```


Gets or sets the list of addresses to reply to for the mail message

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getReversePath() {#getReversePath--}
```
public MailAddress getReversePath()
```


Gets or sets ReversePath address

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getSender() {#getSender--}
```
public MailAddress getSender()
```


Gets or sets sender address

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getSensitivity() {#getSensitivity--}
```
public MailSensitivity getSensitivity()
```


Gets or sets the sensitivity of message

**Returns:**
[MailSensitivity](../../com.aspose.email/mailsensitivity)
### getSubject() {#getSubject--}
```
public String getSubject()
```


Gets or sets the subject line

**Returns:**
java.lang.String
### getSubjectEncoding() {#getSubjectEncoding--}
```
public Charset getSubjectEncoding()
```


Gets or sets the encoding of subject

**Returns:**
java.nio.charset.Charset
### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final double getTimeZoneOffset()
```


Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. This property defines the time zone difference, between the local time and UTC.

**Returns:**
double - A number of milliseconds.
### getTo() {#getTo--}
```
public MailAddressCollection getTo()
```


Gets or sets the address collection that contains the recipients of message

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getXMailer() {#getXMailer--}
```
public String getXMailer()
```


Gets or sets the X-Mailer the software that created the e-mail message

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for object

**Returns:**
int - 
### importMessage(InputStream stream) {#importMessage-java.io.InputStream-}
```
public void importMessage(InputStream stream)
```


Imports message from stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | System.IO.Stream |

### isBodyHtml() {#isBodyHtml--}
```
public boolean isBodyHtml()
```


Gets or sets a value indicating whether the message body is in Html

**Returns:**
boolean
### isBodyHtml(boolean value) {#isBodyHtml-boolean-}
```
public void isBodyHtml(boolean value)
```


Gets or sets a value indicating whether the message body is in Html

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isDraft() {#isDraft--}
```
public boolean isDraft()
```


Gets or sets value that indicates whether or not a message has been sent.

**Returns:**
boolean
### isDraft(boolean value) {#isDraft-boolean-}
```
public void isDraft(boolean value)
```


Gets or sets value that indicates whether or not a message has been sent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Gets a value indicating whether the message is encrypted.

**Returns:**
boolean
### isLocalDate() {#isLocalDate--}
```
public boolean isLocalDate()
```


Defines if date is local date

**Returns:**
boolean - true if date is local date
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the message is read only

**Returns:**
boolean
### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Gets a value indicating whether the message is signed.

**Returns:**
boolean
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<MailMessage> iterator()
```


Returns an enumerator that iterates through a collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.email.MailMessage> - An IEnumerator object that can be used to iterate through the collection.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static MailMessage load(InputStream stream)
```


Load message from stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream that represents message in eml or msg format |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### load(InputStream stream, LoadOptions options) {#load-java.io.InputStream-com.aspose.email.LoadOptions-}
```
public static MailMessage load(InputStream stream, LoadOptions options)
```


Load message from stream with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source streamjava.io.InputStream. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | Additional options [LoadOptions](../../com.aspose.email/loadoptions). |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Mail message[MailMessage](../../com.aspose.email/mailmessage).
### load(String fileName) {#load-java.lang.String-}
```
public static MailMessage load(String fileName)
```


Load message from file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Message file name. The message file must be in eml or msg format. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### load(String fileName, LoadOptions options) {#load-java.lang.String-com.aspose.email.LoadOptions-}
```
public static MailMessage load(String fileName, LoadOptions options)
```


Load message from file with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Source file pathString. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | Additional options [LoadOptions](../../com.aspose.email/loadoptions). |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Mail message[MailMessage](../../com.aspose.email/mailmessage).
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### recomposeTnefContent() {#recomposeTnefContent--}
```
public final void recomposeTnefContent()
```


Composes the TNEF content. Note, that tnef attachment is composed if a message initially contained TNEF and was loaded without FileCompatibilityMode.PreserveTnefAttachments flag, That is this method doesn't create tnef message out of the regular one.

### removeSignature() {#removeSignature--}
```
public MailMessage removeSignature()
```


Remove signature

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Save message as a stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream into which message is saved |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.email.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


Save message as a stream with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream into which message is saved. |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | Additional options for saving[SaveOptions](../../com.aspose.email/saveoptions). |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Save message as a file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of a file to save message. |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.email.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Save message as a file with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Stream into which message is saved. |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | Additional options for saving[SaveOptions](../../com.aspose.email/saveoptions). |

### setBcc(MailAddressCollection value) {#setBcc-com.aspose.email.MailAddressCollection-}
```
public void setBcc(MailAddressCollection value)
```


Gets or sets the address collection that contains the BCC recipients of message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


Gets or sets the plain text representation of message's body. If the text/plain part is present in a message, the propery returns its text data. Otherwise, property returns the text content of the HtmlBody property without html markup.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyEncoding(Charset value) {#setBodyEncoding-java.nio.charset.Charset-}
```
public void setBodyEncoding(Charset value)
```


Gets or sets encoding of body

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setCC(MailAddressCollection value) {#setCC-com.aspose.email.MailAddressCollection-}
```
public void setCC(MailAddressCollection value)
```


Gets or sets the address collection that contains the CC recipients

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setDate(Date value) {#setDate-java.util.Date-}
```
public void setDate(Date value)
```


Gets or sets the date of message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setDeliveryNotificationOptions(int value) {#setDeliveryNotificationOptions-int-}
```
public void setDeliveryNotificationOptions(int value)
```


Gets or sets the delivery notifications

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEpilogue(String value) {#setEpilogue-java.lang.String-}
```
public final void setEpilogue(String value)
```


Gets or sets an epilogue text. It is located after the last boundary.

Value: The string value that represents an epilogue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFrom(IMailAddress value) {#setFrom-com.aspose.email.IMailAddress-}
```
public final void setFrom(IMailAddress value)
```


Sets from address

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMailAddress](../../com.aspose.email/imailaddress) | A from address |

### setFrom(MailAddress value) {#setFrom-com.aspose.email.MailAddress-}
```
public void setFrom(MailAddress value)
```


Gets or sets the from address

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public void setHtmlBody(String value)
```


Gets or sets html body

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setHtmlBody(String value, boolean detectEncoding) {#setHtmlBody-java.lang.String-boolean-}
```
public void setHtmlBody(String value, boolean detectEncoding)
```


Sets html body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The HtmlBody content text. |
| detectEncoding | boolean | Detect body encoding if no encoding is specified for the MailMessage. |

### setMessageId(String value) {#setMessageId-java.lang.String-}
```
public void setMessageId(String value)
```


Gets or sets the message id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreamble(String value) {#setPreamble-java.lang.String-}
```
public final void setPreamble(String value)
```


Gets or sets a preamble text. It is located before the first boundary and generally includes an explanatory note to non-MIME conformant readers.

Value: The string value that represents a preamble.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Gets or sets preferred encoding for all text properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPriority(MailPriority value) {#setPriority-com.aspose.email.MailPriority-}
```
public void setPriority(MailPriority value)
```


Gets or sets the priority of message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailPriority](../../com.aspose.email/mailpriority) |  |

### setReadReceiptTo(MailAddressCollection value) {#setReadReceiptTo-com.aspose.email.MailAddressCollection-}
```
public final void setReadReceiptTo(MailAddressCollection value)
```


Gets or sets the read receipt address.

Value: The [MailAddressCollection](../../com.aspose.email/mailaddresscollection) that represents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setReplyToList(MailAddressCollection value) {#setReplyToList-com.aspose.email.MailAddressCollection-}
```
public void setReplyToList(MailAddressCollection value)
```


Gets or sets the list of addresses to reply to for the mail message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setReversePath(MailAddress value) {#setReversePath-com.aspose.email.MailAddress-}
```
public void setReversePath(MailAddress value)
```


Gets or sets ReversePath address

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setSender(MailAddress value) {#setSender-com.aspose.email.MailAddress-}
```
public void setSender(MailAddress value)
```


Gets or sets sender address

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setSensitivity(MailSensitivity value) {#setSensitivity-com.aspose.email.MailSensitivity-}
```
public void setSensitivity(MailSensitivity value)
```


Gets or sets the sensitivity of message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailSensitivity](../../com.aspose.email/mailsensitivity) |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Gets or sets the subject line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubjectEncoding(Charset value) {#setSubjectEncoding-java.nio.charset.Charset-}
```
public void setSubjectEncoding(Charset value)
```


Gets or sets the encoding of subject

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setTimeZoneOffset(double value) {#setTimeZoneOffset-double-}
```
public final void setTimeZoneOffset(double value)
```


Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. This property defines the time zone difference, between the local time and UTC.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | A number of milliseconds. |

### setTo(MailAddressCollection value) {#setTo-com.aspose.email.MailAddressCollection-}
```
public void setTo(MailAddressCollection value)
```


Gets or sets the address collection that contains the recipients of message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setXMailer(String value) {#setXMailer-java.lang.String-}
```
public void setXMailer(String value)
```


Gets or sets the X-Mailer the software that created the e-mail message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
### validateMessage(InputStream stream) {#validateMessage-java.io.InputStream-}
```
public static EmlValidationErrorCollection validateMessage(InputStream stream)
```


Validate eml message for corresponding to mime specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream containing the message in eml format. |

**Returns:**
[EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) - A [EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) containing the found validation error messages.
### validateMessage(String fileName) {#validateMessage-java.lang.String-}
```
public static EmlValidationErrorCollection validateMessage(String fileName)
```


Validate eml message for corresponding to mime specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | A file name (eml). |

**Returns:**
[EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) - A [EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) containing the found validation error messages.
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

