---
title: MailMessage
second_title: Aspose.Email for Java API Reference
description: Represents an e-mail message its headers body attachments and recipients.
type: docs
weight: 389
url: /java/com.aspose.email/mailmessage/
---

**Inheritance:**
java.lang.Object, com.aspose.email.IPreferredTextEncodingProviderInternal

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable, [com.aspose.email.IPreferredTextEncodingProvider](../../com.aspose.email/ipreferredtextencodingprovider), [com.aspose.email.IMessage](../../com.aspose.email/imessage), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class MailMessage extends IPreferredTextEncodingProviderInternal implements System.IDisposable, Closeable, IPreferredTextEncodingProvider, IMessage, System.Collections.Generic.IGenericEnumerable<MailMessage>
```

Represents an e-mail message: its headers, body, attachments and recipients. Load it from or save it to EML, MSG, MHTML, HTML and other formats, and send it with the mail clients.

Load a message with \#load(String).load(String), save it with \#save(String).save(String). Without options, \#load(String).load(String) recognizes MSG and otherwise reads EML, and \#save(String).save(String) writes EML; pass a [LoadOptions](../../com.aspose.email/loadoptions) or [SaveOptions](../../com.aspose.email/saveoptions) object for other formats. To work with Outlook-specific properties, convert the message to a [MapiMessage](../../com.aspose.email/mapimessage).

The following example shows how to create a new Email Message and save with SaveOptions.

```

 MailMessage message = new MailMessage();
 // Set subject of the message, Html body and sender information
 message.setSubject("New message created by Aspose.Email for .NET");
 message.setHtmlBody("This line is in bold. 
 
" +
         "This line is in blue color");
 message.setFrom(new MailAddress("from@domain.com", "Sender Name", false));

 // Add TO recipients and Add CC recipients
 message.getTo().addMailAddress(new MailAddress("to1@domain.com", "Recipient 1", false));
 message.getTo().addMailAddress(new MailAddress("to2@domain.com", "Recipient 2", false));
 message.getCC().addMailAddress(new MailAddress("cc1@domain.com", "Recipient 3", false));
 message.getCC().addMailAddress(new MailAddress("cc2@domain.com", "Recipient 4", false));

 // Save message to EML, EMLX, MSG and MHTML formats
 message.save("CreateNewMailMessage_out.eml", SaveOptions.getDefaultEml());
 message.save("CreateNewMailMessage_out.emlx", SaveOptions.createSaveOptions(MailMessageSaveType.getEmlxFormat()));
 message.save("CreateNewMailMessage_out.msg", SaveOptions.getDefaultMsgUnicode());
 message.save("CreateNewMailMessage_out.mhtml", SaveOptions.getDefaultMhtml());
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MailMessage(String from, String to)](#MailMessage-java.lang.String-java.lang.String-) | Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class with a sender and recipients. |
| [MailMessage()](#MailMessage--) | Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class: an empty message. |
| [MailMessage(String from, String to, String subject, String body)](#MailMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class with a sender, recipients, a subject and a plain-text body. |
| [MailMessage(MailAddress from, MailAddress to)](#MailMessage-com.aspose.email.MailAddress-com.aspose.email.MailAddress-) | Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class with a sender and a recipient. |
## Methods

| Method | Description |
| --- | --- |
| [addAlternateView(AlternateView view)](#addAlternateView-com.aspose.email.AlternateView-) | Adds an alternate view of the body to the message. |
| [addAttachment(Attachment attachment)](#addAttachment-com.aspose.email.Attachment-) | Adds an attachment to the message. |
| [attachDetachedSignature(SmimeKey key)](#attachDetachedSignature-com.aspose.email.SmimeKey-) | Creates a signed message. |
| [attachSignature(byte[] certificateRawData, String certificatePassword)](#attachSignature-byte---java.lang.String-) | Creates a signed message. |
| [attachSignature(byte[] certificateRawData, String certificatePassword, boolean detached)](#attachSignature-byte---java.lang.String-boolean-) | Creates a signed message. |
| [attachSignature(SmimeKey key)](#attachSignature-com.aspose.email.SmimeKey-) | Creates a signed message. |
| [attachSignature(SmimeKey key, boolean detached)](#attachSignature-com.aspose.email.SmimeKey-boolean-) | Creates a signed message. |
| [checkBounced()](#checkBounced--) | Checks whether the message is a bounce (a non-delivery report) and, if so, why it bounced. |
| [checkSignature()](#checkSignature--) | Verifies the signature of the message. |
| [checkSignature(InputStream stream)](#checkSignature-java.io.InputStream-) | Verifies the signature of a message read from a stream in EML format. |
| [checkSignature(String fileName)](#checkSignature-java.lang.String-) | Verifies the signature of a message in an EML file. |
| [checkSignatureCert()](#checkSignatureCert--) | Checking signature exsisting MailMessage. |
| [close()](#close--) | Releases the resources used by the message, including its attachments. |
| [createReadReceipt(String from, String bodyText)](#createReadReceipt-java.lang.String-java.lang.String-) | Creates a read receipt for the message. |
| [dKIMSign(PrivateKey rsa, DKIMSignatureInfo signatureInfo)](#dKIMSign-java.security.PrivateKey-com.aspose.email.DKIMSignatureInfo-) | Creates a copy of the message signed with DKIM (DomainKeys Identified Mail). |
| [decrypt()](#decrypt--) | Decrypts the message with a certificate found in the certificate store. |
| [decrypt(byte[] certificateRawData, String certificatePassword)](#decrypt-byte---java.lang.String-) | Decrypts this message |
| [decrypt(SmimeKey key)](#decrypt-com.aspose.email.SmimeKey-) | Decrypts the message with the specified certificate. |
| [deepClone()](#deepClone--) | Creates a copy of the message. |
| [dispose()](#dispose--) | Releases all resources used by the MailMessage |
| [encrypt(byte[] certificateRawData, String certificatePassword)](#encrypt-byte---java.lang.String-) | Encrypts this message. |
| [encrypt(SmimeKey[] key)](#encrypt-com.aspose.email.SmimeKey...-) | Encrypts this message. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is equal to this message. |
| [getAlternateViewContent(String mediaType)](#getAlternateViewContent-java.lang.String-) | Gets the content of the alternate view of the specified media type. |
| [getAlternateViews()](#getAlternateViews--) | Gets the alternate views of the body: the plain-text, HTML and other versions. |
| [getAttachments()](#getAttachments--) | Gets the attachments of the message. |
| [getBcc()](#getBcc--) | Gets the BCC recipients. |
| [getBody()](#getBody--) | Gets the plain-text body. |
| [getBodyEncoding()](#getBodyEncoding--) | Gets the character encoding of the body. |
| [getBodyType()](#getBodyType--) | Gets the format of the body: plain text, HTML or RTF. |
| [getCC()](#getCC--) | Gets the CC recipients. |
| [getCc()](#getCc--) | Gets CC recipients |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | Gets the date and time of the message (the  Date  header). |
| [getDeliveryNotificationOptions()](#getDeliveryNotificationOptions--) | Gets when the SMTP server sends a delivery status notification to the sender. |
| [getEpilogue()](#getEpilogue--) | Gets the text after the last MIME boundary of the message. |
| [getFrom()](#getFrom--) | Gets the author of the message (the  From  header). |
| [getHeaders()](#getHeaders--) | Gets the headers of the message. |
| [getHtmlBody()](#getHtmlBody--) | Gets the HTML body. |
| [getHtmlBodyText(boolean showUrl)](#getHtmlBodyText-boolean-) | Gets the text of the HTML body without the markup. |
| [getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback)](#getHtmlBodyText-com.aspose.email.HyperlinkRenderingCallback-) | Gets the text of the HTML body without the markup, rendering hyperlinks with a custom method. |
| [getHtmlWithResources(String html, MailMessage msg)](#getHtmlWithResources-java.lang.String-com.aspose.email.MailMessage-) |  |
| [getItemId()](#getItemId--) | Gets the identifiers of the message in the mailbox it was retrieved from. |
| [getLinkedResources()](#getLinkedResources--) | Gets the resources embedded in the HTML body, such as images. |
| [getLocalDate()](#getLocalDate--) | Gets the local date of message |
| [getMessageId()](#getMessageId--) | Gets the unique identifier of the message (the  Message-ID  header). |
| [getOriginalIsTnef()](#getOriginalIsTnef--) | Gets a value indicating whether the message was loaded from TNEF data (winmail.dat). |
| [getPreamble()](#getPreamble--) | Gets the text before the first MIME boundary, usually a note for mail clients that do not support MIME. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets the encoding used for all text of the message when no other encoding is specified. |
| [getPriority()](#getPriority--) | Gets the priority of the message: normal, low or high. |
| [getReadReceiptTo()](#getReadReceiptTo--) | Gets the addresses a read receipt is requested to (the  Disposition-Notification-To  header). |
| [getReplyToList()](#getReplyToList--) | Gets the addresses replies should go to (the  Reply-To  header). |
| [getReversePath()](#getReversePath--) | Gets the address bounces are returned to (the  Return-Path  header). |
| [getSender()](#getSender--) | Gets the agent that sent the message on behalf of the author (the  Sender  header). |
| [getSensitivity()](#getSensitivity--) | Gets the sensitivity of the message: personal, private or company confidential. |
| [getSubject()](#getSubject--) | Gets the subject of the message. |
| [getSubjectEncoding()](#getSubjectEncoding--) | Gets the character encoding of the subject. |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Gets the offset from UTC that the dates of the message are written with. |
| [getTo()](#getTo--) | Gets the To recipients. |
| [getXMailer()](#getXMailer--) | Gets the software that created the message (the  X-Mailer  header). |
| [hashCode()](#hashCode--) | Returns the hash code of the message. |
| [importMessage(InputStream stream)](#importMessage-java.io.InputStream-) | Replaces the content of this message with a message read from a stream in EML format. |
| [isBodyHtml()](#isBodyHtml--) | Gets a value indicating whether the body is HTML. |
| [isBodyHtml(boolean value)](#isBodyHtml-boolean-) | Sets a value indicating whether the body is HTML. |
| [isDraft()](#isDraft--) | Gets a value indicating whether the message is a draft that has not been sent (the  X-Unsent  header). |
| [isDraft(boolean value)](#isDraft-boolean-) | Sets a value indicating whether the message is a draft that has not been sent (the  X-Unsent  header). |
| [isEncrypted()](#isEncrypted--) | Gets a value indicating whether the message is encrypted (S/MIME). |
| [isLocalDate()](#isLocalDate--) | Defines if date is local date |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the message is read-only, as a signed copy is. |
| [isSigned()](#isSigned--) | Gets a value indicating whether the message is digitally signed. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through a collection. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads a message from a stream. |
| [load(InputStream stream, LoadOptions options)](#load-java.io.InputStream-com.aspose.email.LoadOptions-) | Loads a message from a stream in the format selected by the options. |
| [load(String fileName)](#load-java.lang.String-) | Loads a message from a file. |
| [load(String fileName, LoadOptions options)](#load-java.lang.String-com.aspose.email.LoadOptions-) | Loads a message from a file in the format selected by the options. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [recomposeTnefContent()](#recomposeTnefContent--) | Rebuilds the TNEF attachment (winmail.dat) of a message that was loaded from TNEF, so that it reflects the changes made to the message. |
| [removeSignature()](#removeSignature--) | Returns a copy of a signed message without the signature. |
| [resetBoundaryTemplate(String boundaryTemplate)](#resetBoundaryTemplate-java.lang.String-) | Sets the boundary template for the message.
Sets the boundary number to 0.
Default value is null. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the message to a stream in EML format. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.email.SaveOptions-) | Saves the message to a stream in the format selected by the options. |
| [save(String fileName)](#save-java.lang.String-) | Saves the message to a file in EML format, whatever the file extension. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.email.SaveOptions-) | Saves the message to a file in the format selected by the options. |
| [setBcc(MailAddressCollection value)](#setBcc-com.aspose.email.MailAddressCollection-) | Sets the BCC recipients. |
| [setBody(String value)](#setBody-java.lang.String-) | Sets the plain-text body. |
| [setBodyEncoding(Charset value)](#setBodyEncoding-java.nio.charset.Charset-) | Sets the character encoding of the body. |
| [setCC(MailAddressCollection value)](#setCC-com.aspose.email.MailAddressCollection-) | Sets the CC recipients. |
| [setDate(Date value)](#setDate-java.util.Date-) | Sets the date and time of the message (the  Date  header). |
| [setDeliveryNotificationOptions(int value)](#setDeliveryNotificationOptions-int-) | Sets when the SMTP server sends a delivery status notification to the sender. |
| [setEpilogue(String value)](#setEpilogue-java.lang.String-) | Sets the text after the last MIME boundary of the message. |
| [setFrom(IMailAddress value)](#setFrom-com.aspose.email.IMailAddress-) | Sets from address |
| [setFrom(MailAddress value)](#setFrom-com.aspose.email.MailAddress-) | Sets the author of the message (the  From  header). |
| [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Sets the HTML body. |
| [setHtmlBody(String value, boolean detectEncoding)](#setHtmlBody-java.lang.String-boolean-) | Sets the HTML body, optionally detecting its encoding. |
| [setMessageId(String value)](#setMessageId-java.lang.String-) | Sets the unique identifier of the message (the  Message-ID  header). |
| [setPreamble(String value)](#setPreamble-java.lang.String-) | Sets the text before the first MIME boundary, usually a note for mail clients that do not support MIME. |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Sets the encoding used for all text of the message when no other encoding is specified. |
| [setPriority(MailPriority value)](#setPriority-com.aspose.email.MailPriority-) | Sets the priority of the message: normal, low or high. |
| [setReadReceiptTo(MailAddressCollection value)](#setReadReceiptTo-com.aspose.email.MailAddressCollection-) | Sets the addresses a read receipt is requested to (the  Disposition-Notification-To  header). |
| [setReplyToList(MailAddressCollection value)](#setReplyToList-com.aspose.email.MailAddressCollection-) | Sets the addresses replies should go to (the  Reply-To  header). |
| [setReversePath(MailAddress value)](#setReversePath-com.aspose.email.MailAddress-) | Sets the address bounces are returned to (the  Return-Path  header). |
| [setSender(MailAddress value)](#setSender-com.aspose.email.MailAddress-) | Sets the agent that sent the message on behalf of the author (the  Sender  header). |
| [setSensitivity(MailSensitivity value)](#setSensitivity-com.aspose.email.MailSensitivity-) | Sets the sensitivity of the message: personal, private or company confidential. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the message. |
| [setSubjectEncoding(Charset value)](#setSubjectEncoding-java.nio.charset.Charset-) | Sets the character encoding of the subject. |
| [setTimeZoneOffset(double value)](#setTimeZoneOffset-double-) | Sets the offset from UTC that the dates of the message are written with. |
| [setTo(MailAddressCollection value)](#setTo-com.aspose.email.MailAddressCollection-) | Sets the To recipients. |
| [setXMailer(String value)](#setXMailer-java.lang.String-) | Sets the software that created the message (the  X-Mailer  header). |
| [toString()](#toString--) | Returns a string that represents the message. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailMessage(String from, String to) {#MailMessage-java.lang.String-java.lang.String-}
```
public MailMessage(String from, String to)
```


Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class with a sender and recipients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | The address of the sender. |
| to | java.lang.String | The addresses of the recipients, separated by commas. |

### MailMessage() {#MailMessage--}
```
public MailMessage()
```


Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class: an empty message.

### MailMessage(String from, String to, String subject, String body) {#MailMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public MailMessage(String from, String to, String subject, String body)
```


Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class with a sender, recipients, a subject and a plain-text body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | The address of the sender. |
| to | java.lang.String | The addresses of the recipients, separated by commas. |
| subject | java.lang.String | The subject. |
| body | java.lang.String | The plain-text body. |

### MailMessage(MailAddress from, MailAddress to) {#MailMessage-com.aspose.email.MailAddress-com.aspose.email.MailAddress-}
```
public MailMessage(MailAddress from, MailAddress to)
```


Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class with a sender and a recipient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | [MailAddress](../../com.aspose.email/mailaddress) | The sender. |
| to | [MailAddress](../../com.aspose.email/mailaddress) | The recipient. |

### addAlternateView(AlternateView view) {#addAlternateView-com.aspose.email.AlternateView-}
```
public void addAlternateView(AlternateView view)
```


Adds an alternate view of the body to the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| view | [AlternateView](../../com.aspose.email/alternateview) | The view to add. |

### addAttachment(Attachment attachment) {#addAttachment-com.aspose.email.Attachment-}
```
public void addAttachment(Attachment attachment)
```


Adds an attachment to the message.

The following example shows how to add Attachments to MailMessage.

```

 // Create an instance of MailMessage class
 MailMessage eml = new MailMessage();
 eml.setFrom(MailAddress.to_MailAddress("sender@from.com"));
 eml.setTo(MailAddressCollection.to_MailAddressCollection("receiver@to.com"));
 eml.setSubject("This is message");
 eml.setBody("This is body");

 // Load an attachment
 Attachment attachment = new Attachment("1.txt");

 // Add Multiple Attachment in instance of MailMessage class and Save message to disk
 eml.getAttachments().addItem(attachment);

 eml.addAttachment(new Attachment("1.jpg"));
 eml.addAttachment(new Attachment("1.doc"));
 eml.addAttachment(new Attachment("1.rar"));
 eml.addAttachment(new Attachment("1.pdf"));
 eml.save("AddAttachments.eml");
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attachment | [Attachment](../../com.aspose.email/attachment) | The attachment to add. |

### attachDetachedSignature(SmimeKey key) {#attachDetachedSignature-com.aspose.email.SmimeKey-}
```
public MailMessage attachDetachedSignature(SmimeKey key)
```


Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

--------------------

> The following example shows how to attach a Certificate with AttachSignature Method.
> 
> [Java]
> 
> ```
> ```
> 
>  MailMessage msg = new MailMessage("user@domain.com", "receiver@domain.com", "subject:Signed message only by AE",
>      "body:Test Body of signed message by AE");
>  MailMessage signed = msg.attachDetachedSignature(key);
>  // load PFX file
>  SmimeKey key = SmimeKey.loadPFX(pfxPath, "key".toCharArray());
>  // load SmimeKey from private key string
>  SmimeKey key = SmimeKey.loadPrivateKey(keyPath);
>  // create SmimeKey from private key and X509 certificates
>  SmimeKey key = new SmimeKey(privateKey, x509Certificate1, x509Certificate2);
>  
> ```
> ```

--------------------

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | [SmimeKey](../../com.aspose.email/smimekey) | SmimeKey with private key. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The signed MailMessage.
### attachSignature(byte[] certificateRawData, String certificatePassword) {#attachSignature-byte---java.lang.String-}
```
public MailMessage attachSignature(byte[] certificateRawData, String certificatePassword)
```


Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

--------------------

> The following example shows how to attach a Certificate with AttachSignature Method.
> 
> [Java]
> 
> ```
> MailMessage msg = new MailMessage("user@domain.com", "receiver@domain.com", "subject:Signed message only by AE",
>      "body:Test Body of signed message by AE");
>  MailMessage signed = msg.attachSignature(certData, true);
> ```

--------------------

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
### attachSignature(SmimeKey key) {#attachSignature-com.aspose.email.SmimeKey-}
```
public MailMessage attachSignature(SmimeKey key)
```


Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

--------------------

> The following example shows how to attach a Certificate with AttachSignature Method.
> 
> [Java]
> 
> ```
> ```
> 
>  MailMessage msg = new MailMessage("user@domain.com", "receiver@domain.com", "subject:Signed message only by AE",
>      "body:Test Body of signed message by AE");
>  MailMessage signed = msg.attachSignature(key);
>  // load PFX file
>  SmimeKey key = SmimeKey.loadPFX(pfxPath, "key".toCharArray());
>  // load SmimeKey from private key string
>  SmimeKey key = SmimeKey.loadPrivateKey(keyPath);
>  // create SmimeKey from private key and X509 certificates
>  SmimeKey key = new SmimeKey(privateKey, x509Certificate1, x509Certificate2);
>  
> ```
> ```

--------------------

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | [SmimeKey](../../com.aspose.email/smimekey) | SmimeKey with private key. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The signed MailMessage.
### attachSignature(SmimeKey key, boolean detached) {#attachSignature-com.aspose.email.SmimeKey-boolean-}
```
public MailMessage attachSignature(SmimeKey key, boolean detached)
```


Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

--------------------

> The following example shows how to attach a Certificate with AttachSignature Method.
> 
> [Java]
> 
> ```
> ```
> 
>  MailMessage msg = new MailMessage("user@domain.com", "receiver@domain.com", "subject:Signed message only by AE",
>      "body:Test Body of signed message by AE");
>  // create signed mail with detached signature
>  MailMessage signedDetached = msg.attachSignature(key, true);
>  // create signed mail with attached signature
>  MailMessage signedAttached = msg.attachSignature(key, false);
>  // load PFX file
>  SmimeKey key = SmimeKey.loadPFX(pfxPath, "key".toCharArray());
>  // load SmimeKey from private key string
>  SmimeKey key = SmimeKey.loadPrivateKey(keyPath);
>  // create SmimeKey from private key and X509 certificates
>  SmimeKey key = new SmimeKey(privateKey, x509Certificate1, x509Certificate2);
>  
> ```
> ```

--------------------

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | [SmimeKey](../../com.aspose.email/smimekey) | SmimeKey with private key. |
| detached | boolean | .If detached is true, the signature is detached. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The signed MailMessage.
### checkBounced() {#checkBounced--}
```
public BounceResult checkBounced()
```


Checks whether the message is a bounce (a non-delivery report) and, if so, why it bounced.

**Returns:**
[BounceResult](../../com.aspose.email/bounceresult) - The result of the check.
### checkSignature() {#checkSignature--}
```
public String[] checkSignature()
```


Verifies the signature of the message.

**Returns:**
java.lang.String[] - The certificates of the signers.
### checkSignature(InputStream stream) {#checkSignature-java.io.InputStream-}
```
public static boolean checkSignature(InputStream stream)
```


Verifies the signature of a message read from a stream in EML format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |

**Returns:**
boolean -  true  if the signature is valid; otherwise,  false .
### checkSignature(String fileName) {#checkSignature-java.lang.String-}
```
public static boolean checkSignature(String fileName)
```


Verifies the signature of a message in an EML file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the EML file. |

**Returns:**
boolean -  true  if the signature is valid; otherwise,  false .
### checkSignatureCert() {#checkSignatureCert--}
```
public List<X509Certificate> checkSignatureCert()
```


Checking signature exsisting MailMessage.

**Returns:**
java.util.List<java.security.cert.X509Certificate> - X.509 signers certificates
### close() {#close--}
```
public void close()
```


Releases the resources used by the message, including its attachments.

### createReadReceipt(String from, String bodyText) {#createReadReceipt-java.lang.String-java.lang.String-}
```
public final MailMessage createReadReceipt(String from, String bodyText)
```


Creates a read receipt for the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | The address of the sender of the receipt. |
| bodyText | java.lang.String | The text of the receipt;  null  or empty for the default text. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The read receipt, addressed to \#getReadReceiptTo().getReadReceiptTo().
### dKIMSign(PrivateKey rsa, DKIMSignatureInfo signatureInfo) {#dKIMSign-java.security.PrivateKey-com.aspose.email.DKIMSignatureInfo-}
```
public MailMessage dKIMSign(PrivateKey rsa, DKIMSignatureInfo signatureInfo)
```


Creates a copy of the message signed with DKIM (DomainKeys Identified Mail).

The following example shows how to sign Emails with DKIM.

```

 String privateKeyFile = "key2.pem";

 PrivateKey rsa = PemReader.getPrivateKey(privateKeyFile);
 DKIMSignatureInfo signInfo = new DKIMSignatureInfo("test", "some_email.com");
 signInfo.getHeaders().addItem("From");
 signInfo.getHeaders().addItem("Subject");

 MailMessage mailMessage = new MailMessage("useremail@gmail.com", "test@gmail.com");
 mailMessage.setSubject("Signed DKIM message text body");
 mailMessage.setBody("This is a text body signed DKIM message");

 MailMessage signedMsg = mailMessage.dKIMSign(rsa, signInfo);
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rsa | java.security.PrivateKey | The RSA provider with the private key of the domain. |
| signatureInfo | [DKIMSignatureInfo](../../com.aspose.email/dkimsignatureinfo) | The parameters of the signature: the domain, the selector and the headers to sign. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The signed message.
### decrypt() {#decrypt--}
```
public MailMessage decrypt()
```


Decrypts the message with a certificate found in the certificate store.

The certificate and its private key are searched for in the personal (My) stores of the current user and of the computer.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The decrypted message.
### decrypt(byte[] certificateRawData, String certificatePassword) {#decrypt-byte---java.lang.String-}
```
public MailMessage decrypt(byte[] certificateRawData, String certificatePassword)
```


Decrypts this message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateRawData | byte[] | X509 certificate to decrypt message |
| certificatePassword | java.lang.String | The password required to access the X.509 certificate data |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### decrypt(SmimeKey key) {#decrypt-com.aspose.email.SmimeKey-}
```
public MailMessage decrypt(SmimeKey key)
```


Decrypts the message with the specified certificate.

```

 // load the S/MIME key: from a PFX file, from a private key file or from a key and certificates
 SmimeKey key = SmimeKey.loadPFX(pfxPath, "key".toCharArray());

 // decrypt the message
 MailMessage decrypted = encryptedEml.decrypt(key);
 System.out.println(decrypted.isEncrypted() ? "It's encrypted" : "It's NOT encrypted");
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | [SmimeKey](../../com.aspose.email/smimekey) | The S/MIME key (the certificate with its private key) to decrypt with. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The decrypted message.
### deepClone() {#deepClone--}
```
public MailMessage deepClone()
```


Creates a copy of the message.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The copy.
### dispose() {#dispose--}
```
public final void dispose()
```


Releases all resources used by the MailMessage

### encrypt(byte[] certificateRawData, String certificatePassword) {#encrypt-byte---java.lang.String-}
```
public MailMessage encrypt(byte[] certificateRawData, String certificatePassword)
```


Encrypts this message.

--------------------

> The following example shows how to encrypt messages.
> 
> [Java]
> 
> ```
> ```
> 
>  // Create a message
>  MailMessage eml = new MailMessage();
>  eml.setFrom(MailAddress.to_MailAddress("atneostthaecrcount@gmail.com"));
>  eml.setTo(MailAddressCollection.to_MailAddressCollection("atneostthaecrcount@gmail.com"));
>  eml.setSubject("Test subject");
>  eml.setBody("Test Body");
> 
>  // Encrypt the message
>  MailMessage encryptedEml = eml.encrypt(certData, certPass);
>  System.out.println(encryptedEml.isEncrypted() ? "It's encrypted" : "It's NOT encrypted");
>  
> ```
> ```

--------------------

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateRawData | byte[] | X509 certificate to encrypt the message. |
| certificatePassword | java.lang.String | Password for the X509 certificate. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Encrypted email message.
### encrypt(SmimeKey[] key) {#encrypt-com.aspose.email.SmimeKey...-}
```
public MailMessage encrypt(SmimeKey[] key)
```


Encrypts this message.

--------------------

> The following example shows how to encrypt messages.
> 
> [Java]
> 
> ```
> ```
> 
>  // Create a message
>  MailMessage eml = new MailMessage();
>  eml.setFrom(MailAddress.to_MailAddress("atneostthaecrcount@gmail.com"));
>  eml.setTo(MailAddressCollection.to_MailAddressCollection("atneostthaecrcount@gmail.com"));
>  eml.setSubject("Test subject");
>  eml.setBody("Test Body");
> 
>  // load PFX file
>  SmimeKey key = SmimeKey.loadPFX(pfxPath, "key".toCharArray());
>  // load SmimeKey from certificate string
>  SmimeKey key = SmimeKey.loadCertificate(crtPath);
>  // create SmimeKey from private key and X509 certificates
>  SmimeKey key = new SmimeKey(privateKey, x509Certificate1, x509Certificate2);
> 
>  // Encrypt the message
>  MailMessage encryptedEml = eml.encrypt(key);
>  System.out.println(encryptedEml.isEncrypted() ? "It's encrypted" : "It's NOT encrypted");
>  
> ```
> ```

--------------------

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | [SmimeKey\[\]](../../com.aspose.email/smimekey) | SmimeKey with the public certificate. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Encrypted email message.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified object is equal to this message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with. |

**Returns:**
boolean -  true  if the objects are equal; otherwise,  false .
### getAlternateViewContent(String mediaType) {#getAlternateViewContent-java.lang.String-}
```
public final String getAlternateViewContent(String mediaType)
```


Gets the content of the alternate view of the specified media type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mediaType | java.lang.String | The media type of the view, such as  text/calendar . |

**Returns:**
java.lang.String - The content of the view, or  null  if the message has no such view.
### getAlternateViews() {#getAlternateViews--}
```
public AlternateViewCollection getAlternateViews()
```


Gets the alternate views of the body: the plain-text, HTML and other versions.

**Returns:**
[AlternateViewCollection](../../com.aspose.email/alternateviewcollection)
### getAttachments() {#getAttachments--}
```
public AttachmentCollection getAttachments()
```


Gets the attachments of the message.

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getBcc() {#getBcc--}
```
public MailAddressCollection getBcc()
```


Gets the BCC recipients.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getBody() {#getBody--}
```
public String getBody()
```


Gets the plain-text body. When the message has no plain-text part, the text of \#getHtmlBody().getHtmlBody() without the HTML markup is returned.

**Returns:**
java.lang.String
### getBodyEncoding() {#getBodyEncoding--}
```
public Charset getBodyEncoding()
```


Gets the character encoding of the body.

**Returns:**
java.nio.charset.Charset
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Gets the format of the body: plain text, HTML or RTF.

**Returns:**
int
### getCC() {#getCC--}
```
public MailAddressCollection getCC()
```


Gets the CC recipients.

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


Gets the date and time of the message (the  Date  header).

**Returns:**
java.util.Date
### getDeliveryNotificationOptions() {#getDeliveryNotificationOptions--}
```
public int getDeliveryNotificationOptions()
```


Gets when the SMTP server sends a delivery status notification to the sender.

**Returns:**
int
### getEpilogue() {#getEpilogue--}
```
public final String getEpilogue()
```


Gets the text after the last MIME boundary of the message.

**Returns:**
java.lang.String - The epilogue.
### getFrom() {#getFrom--}
```
public MailAddress getFrom()
```


Gets the author of the message (the  From  header).

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getHeaders() {#getHeaders--}
```
public HeaderCollection getHeaders()
```


Gets the headers of the message.

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getHtmlBody() {#getHtmlBody--}
```
public String getHtmlBody()
```


Gets the HTML body.

**Returns:**
java.lang.String
### getHtmlBodyText(boolean showUrl) {#getHtmlBodyText-boolean-}
```
public String getHtmlBodyText(boolean showUrl)
```


Gets the text of the HTML body without the markup.

The following example shows how to get an email message\\ufffds HTML body as plain text.

```

 MailMessage eml = MailMessage.load("HtmlWithUrlSample.eml");
 String bodyWithUrl = eml.getHtmlBodyText(true);// body will contain URL
 String bodyWithoutUrl = eml.getHtmlBodyText(false);// body will not contain URL

 System.out.println("Body with URL: " + bodyWithUrl);
 System.out.println("Body without URL: " + bodyWithoutUrl);
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| showUrl | boolean |  true  to write the URLs of hyperlinks after their text. |

**Returns:**
java.lang.String - The text of the HTML body.
### getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback) {#getHtmlBodyText-com.aspose.email.HyperlinkRenderingCallback-}
```
public String getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback)
```


Gets the text of the HTML body without the markup, rendering hyperlinks with a custom method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hyperlinkRenderingCallback | [HyperlinkRenderingCallback](../../com.aspose.email/hyperlinkrenderingcallback) | The method that renders each hyperlink as text. |

**Returns:**
java.lang.String - The text of the HTML body.
### getHtmlWithResources(String html, MailMessage msg) {#getHtmlWithResources-java.lang.String-com.aspose.email.MailMessage-}
```
public static String getHtmlWithResources(String html, MailMessage msg)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| html | java.lang.String |  |
| msg | [MailMessage](../../com.aspose.email/mailmessage) |  |

**Returns:**
java.lang.String
### getItemId() {#getItemId--}
```
public MailboxInfo getItemId()
```


Gets the identifiers of the message in the mailbox it was retrieved from.

**Returns:**
[MailboxInfo](../../com.aspose.email/mailboxinfo)
### getLinkedResources() {#getLinkedResources--}
```
public LinkedResourceCollection getLinkedResources()
```


Gets the resources embedded in the HTML body, such as images.

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


Gets the unique identifier of the message (the  Message-ID  header).

**Returns:**
java.lang.String
### getOriginalIsTnef() {#getOriginalIsTnef--}
```
public boolean getOriginalIsTnef()
```


Gets a value indicating whether the message was loaded from TNEF data (winmail.dat).

**Returns:**
boolean
### getPreamble() {#getPreamble--}
```
public final String getPreamble()
```


Gets the text before the first MIME boundary, usually a note for mail clients that do not support MIME.

**Returns:**
java.lang.String - The preamble.
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Gets the encoding used for all text of the message when no other encoding is specified.

**Returns:**
java.nio.charset.Charset
### getPriority() {#getPriority--}
```
public MailPriority getPriority()
```


Gets the priority of the message: normal, low or high.

**Returns:**
[MailPriority](../../com.aspose.email/mailpriority)
### getReadReceiptTo() {#getReadReceiptTo--}
```
public final MailAddressCollection getReadReceiptTo()
```


Gets the addresses a read receipt is requested to (the  Disposition-Notification-To  header).

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection) - The addresses for the read receipt.
### getReplyToList() {#getReplyToList--}
```
public MailAddressCollection getReplyToList()
```


Gets the addresses replies should go to (the  Reply-To  header).

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getReversePath() {#getReversePath--}
```
public MailAddress getReversePath()
```


Gets the address bounces are returned to (the  Return-Path  header). When the message is sent, it is used as the envelope sender in preference to \#getSender().getSender() and \#getFrom().getFrom().

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getSender() {#getSender--}
```
public MailAddress getSender()
```


Gets the agent that sent the message on behalf of the author (the  Sender  header).

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getSensitivity() {#getSensitivity--}
```
public MailSensitivity getSensitivity()
```


Gets the sensitivity of the message: personal, private or company confidential.

**Returns:**
[MailSensitivity](../../com.aspose.email/mailsensitivity)
### getSubject() {#getSubject--}
```
public String getSubject()
```


Gets the subject of the message.

**Returns:**
java.lang.String
### getSubjectEncoding() {#getSubjectEncoding--}
```
public Charset getSubjectEncoding()
```


Gets the character encoding of the subject.

**Returns:**
java.nio.charset.Charset
### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final double getTimeZoneOffset()
```


Gets the offset from UTC that the dates of the message are written with.

**Returns:**
double
### getTo() {#getTo--}
```
public MailAddressCollection getTo()
```


Gets the To recipients.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getXMailer() {#getXMailer--}
```
public String getXMailer()
```


Gets the software that created the message (the  X-Mailer  header).

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code of the message.

**Returns:**
int - The hash code.
### importMessage(InputStream stream) {#importMessage-java.io.InputStream-}
```
public void importMessage(InputStream stream)
```


Replaces the content of this message with a message read from a stream in EML format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |

### isBodyHtml() {#isBodyHtml--}
```
public boolean isBodyHtml()
```


Gets a value indicating whether the body is HTML.

**Returns:**
boolean
### isBodyHtml(boolean value) {#isBodyHtml-boolean-}
```
public void isBodyHtml(boolean value)
```


Sets a value indicating whether the body is HTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isDraft() {#isDraft--}
```
public boolean isDraft()
```


Gets a value indicating whether the message is a draft that has not been sent (the  X-Unsent  header).

**Returns:**
boolean
### isDraft(boolean value) {#isDraft-boolean-}
```
public void isDraft(boolean value)
```


Sets a value indicating whether the message is a draft that has not been sent (the  X-Unsent  header).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Gets a value indicating whether the message is encrypted (S/MIME).

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


Gets a value indicating whether the message is read-only, as a signed copy is.

**Returns:**
boolean
### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Gets a value indicating whether the message is digitally signed.

**Returns:**
boolean
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<MailMessage> iterator()
```


Returns an enumerator that iterates through a collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.email.MailMessage> - An iterator that can be used to iterate through the collection.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static MailMessage load(InputStream stream)
```


Loads a message from a stream. MSG is recognized automatically; any other data is read as EML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The loaded message.
### load(InputStream stream, LoadOptions options) {#load-java.io.InputStream-com.aspose.email.LoadOptions-}
```
public static MailMessage load(InputStream stream, LoadOptions options)
```


Loads a message from a stream in the format selected by the options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | The options; their class selects the format, such as [EmlLoadOptions](../../com.aspose.email/emlloadoptions) or [MsgLoadOptions](../../com.aspose.email/msgloadoptions). |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The loaded message.
### load(String fileName) {#load-java.lang.String-}
```
public static MailMessage load(String fileName)
```


Loads a message from a file. MSG is recognized automatically; any other file is read as EML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The loaded message.
### load(String fileName, LoadOptions options) {#load-java.lang.String-com.aspose.email.LoadOptions-}
```
public static MailMessage load(String fileName, LoadOptions options)
```


Loads a message from a file in the format selected by the options.

The following example shows how to load a Message with Load Options.

```

 // Load Eml, html, mhtml, msg and dat file
 MailMessage.load("Message.eml", new EmlLoadOptions());
 MailMessage.load("description.html", new HtmlLoadOptions());
 MailMessage.load("Message.mhtml", new MhtmlLoadOptions());
 MailMessage.load("Message.msg", new MsgLoadOptions());

 // loading with custom options
 EmlLoadOptions emlLoadOptions = new EmlLoadOptions();
 emlLoadOptions.setPreferredTextEncoding(Charset.forName("utf-8"));
 emlLoadOptions.setPreserveTnefAttachments(true);

 MailMessage.load("description.html", emlLoadOptions);

 HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
 htmlLoadOptions.setPreferredTextEncoding(Charset.forName("utf-8"));
 htmlLoadOptions.shouldAddPlainTextView(true);
 htmlLoadOptions.setPathToResources(htmlImagesFolder);

 MailMessage.load("description.html", htmlLoadOptions);
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | The options; their class selects the format, such as [EmlLoadOptions](../../com.aspose.email/emlloadoptions) or [MsgLoadOptions](../../com.aspose.email/msgloadoptions). |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The loaded message.
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


Rebuilds the TNEF attachment (winmail.dat) of a message that was loaded from TNEF, so that it reflects the changes made to the message.

It applies only to a message that originally contained TNEF and was loaded without [FileCompatibilityMode.PreserveTnefAttachments](../../com.aspose.email/filecompatibilitymode\#PreserveTnefAttachments); it does not turn an ordinary message into TNEF.

### removeSignature() {#removeSignature--}
```
public MailMessage removeSignature()
```


Returns a copy of a signed message without the signature.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The message without the signature.
### resetBoundaryTemplate(String boundaryTemplate) {#resetBoundaryTemplate-java.lang.String-}
```
public static void resetBoundaryTemplate(String boundaryTemplate)
```


Sets the boundary template for the message.
Sets the boundary number to 0.
Default value is null.

The '\{\#\}' wildcard is used for the boundary number placeholder.
The '\{guid\}' wildcard is used for the boundary GUID placeholder.

example: boundary--\{\#\}-\{guid\}

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| boundaryTemplate | java.lang.String |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves the message to a stream in EML format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.email.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


Saves the message to a stream in the format selected by the options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | The options; their class selects the format, such as [MsgSaveOptions](../../com.aspose.email/msgsaveoptions) or [MhtSaveOptions](../../com.aspose.email/mhtsaveoptions). |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Saves the message to a file in EML format, whatever the file extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to write. |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.email.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Saves the message to a file in the format selected by the options.

The following example shows how to save an email message as HTML with embedded images.

```

 String fileName = "EmailWithAttachEmbedded.eml";
 MailMessage eml = MailMessage.load(fileName);

 HtmlSaveOptions options = new HtmlSaveOptions();
 options.setResourceRenderingMode(ResourceRenderingMode.EmbedIntoHtml);
 eml.save(fileName + ".html", options);
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to write. |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | The options; their class selects the format, such as [MsgSaveOptions](../../com.aspose.email/msgsaveoptions) or [MhtSaveOptions](../../com.aspose.email/mhtsaveoptions). |

### setBcc(MailAddressCollection value) {#setBcc-com.aspose.email.MailAddressCollection-}
```
public void setBcc(MailAddressCollection value)
```


Sets the BCC recipients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


Sets the plain-text body. When the message has no plain-text part, the text of \#getHtmlBody().getHtmlBody() without the HTML markup is returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyEncoding(Charset value) {#setBodyEncoding-java.nio.charset.Charset-}
```
public void setBodyEncoding(Charset value)
```


Sets the character encoding of the body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setCC(MailAddressCollection value) {#setCC-com.aspose.email.MailAddressCollection-}
```
public void setCC(MailAddressCollection value)
```


Sets the CC recipients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setDate(Date value) {#setDate-java.util.Date-}
```
public void setDate(Date value)
```


Sets the date and time of the message (the  Date  header).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setDeliveryNotificationOptions(int value) {#setDeliveryNotificationOptions-int-}
```
public void setDeliveryNotificationOptions(int value)
```


Sets when the SMTP server sends a delivery status notification to the sender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEpilogue(String value) {#setEpilogue-java.lang.String-}
```
public final void setEpilogue(String value)
```


Sets the text after the last MIME boundary of the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The epilogue. |

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


Sets the author of the message (the  From  header).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public void setHtmlBody(String value)
```


Sets the HTML body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setHtmlBody(String value, boolean detectEncoding) {#setHtmlBody-java.lang.String-boolean-}
```
public void setHtmlBody(String value, boolean detectEncoding)
```


Sets the HTML body, optionally detecting its encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The HTML body. |
| detectEncoding | boolean |  true  to detect the encoding from the content when the message has none set. |

### setMessageId(String value) {#setMessageId-java.lang.String-}
```
public void setMessageId(String value)
```


Sets the unique identifier of the message (the  Message-ID  header).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreamble(String value) {#setPreamble-java.lang.String-}
```
public final void setPreamble(String value)
```


Sets the text before the first MIME boundary, usually a note for mail clients that do not support MIME.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The preamble. |

### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Sets the encoding used for all text of the message when no other encoding is specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPriority(MailPriority value) {#setPriority-com.aspose.email.MailPriority-}
```
public void setPriority(MailPriority value)
```


Sets the priority of the message: normal, low or high.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailPriority](../../com.aspose.email/mailpriority) |  |

### setReadReceiptTo(MailAddressCollection value) {#setReadReceiptTo-com.aspose.email.MailAddressCollection-}
```
public final void setReadReceiptTo(MailAddressCollection value)
```


Sets the addresses a read receipt is requested to (the  Disposition-Notification-To  header).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The addresses for the read receipt. |

### setReplyToList(MailAddressCollection value) {#setReplyToList-com.aspose.email.MailAddressCollection-}
```
public void setReplyToList(MailAddressCollection value)
```


Sets the addresses replies should go to (the  Reply-To  header).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setReversePath(MailAddress value) {#setReversePath-com.aspose.email.MailAddress-}
```
public void setReversePath(MailAddress value)
```


Sets the address bounces are returned to (the  Return-Path  header). When the message is sent, it is used as the envelope sender in preference to \#getSender().getSender() and \#getFrom().getFrom().

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setSender(MailAddress value) {#setSender-com.aspose.email.MailAddress-}
```
public void setSender(MailAddress value)
```


Sets the agent that sent the message on behalf of the author (the  Sender  header).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setSensitivity(MailSensitivity value) {#setSensitivity-com.aspose.email.MailSensitivity-}
```
public void setSensitivity(MailSensitivity value)
```


Sets the sensitivity of the message: personal, private or company confidential.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailSensitivity](../../com.aspose.email/mailsensitivity) |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Sets the subject of the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubjectEncoding(Charset value) {#setSubjectEncoding-java.nio.charset.Charset-}
```
public void setSubjectEncoding(Charset value)
```


Sets the character encoding of the subject.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setTimeZoneOffset(double value) {#setTimeZoneOffset-double-}
```
public final void setTimeZoneOffset(double value)
```


Sets the offset from UTC that the dates of the message are written with.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setTo(MailAddressCollection value) {#setTo-com.aspose.email.MailAddressCollection-}
```
public void setTo(MailAddressCollection value)
```


Sets the To recipients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setXMailer(String value) {#setXMailer-java.lang.String-}
```
public void setXMailer(String value)
```


Sets the software that created the message (the  X-Mailer  header).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the message.

**Returns:**
java.lang.String - A string that represents the message.
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

