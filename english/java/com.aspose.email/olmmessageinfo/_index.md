---
title: OlmMessageInfo
second_title: Aspose.Email for Java API Reference
description:  Represents an information
 about message in the OLM storage.
type: docs
weight: 539
url: /java/com.aspose.email/olmmessageinfo/
---
**Inheritance:**
java.lang.Object
```
public class OlmMessageInfo
```

Represents an information about message in the OLM storage.
## Methods

| Method | Description |
| --- | --- |
| [getSubject()](#getSubject--) | Gets the message subject. |
| [getDate()](#getDate--) | Gets the date of message. |
| [getModifiedDate()](#getModifiedDate--) | Gets the date of message. |
| [getFrom()](#getFrom--) | Gets the from address. |
| [getTo()](#getTo--) | Gets the address collection that contains the recipients of message. |
| [getMessageClass()](#getMessageClass--) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. |
| [hasAttachments()](#hasAttachments--) | Gets or sets a value indicating whether the message has attachments. |
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the message subject.

**Returns:**
java.lang.String
### getDate() {#getDate--}
```
public final Date getDate()
```


Gets the date of message.

**Returns:**
java.util.Date
### getModifiedDate() {#getModifiedDate--}
```
public final Date getModifiedDate()
```


Gets the date of message.

**Returns:**
java.util.Date
### getFrom() {#getFrom--}
```
public final MapiElectronicAddress getFrom()
```


Gets the from address.

**Returns:**
[MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress)
### getTo() {#getTo--}
```
public final List<MapiElectronicAddress> getTo()
```


Gets the address collection that contains the recipients of message.

**Returns:**
java.util.List<com.aspose.email.MapiElectronicAddress>
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message.

**Returns:**
java.lang.String
### hasAttachments() {#hasAttachments--}
```
public final boolean hasAttachments()
```


Gets or sets a value indicating whether the message has attachments.

Value: \`\`\` true \`\`\` if this instance has attachments; otherwise, \`\`\` false \`\`\`.

**Returns:**
boolean
