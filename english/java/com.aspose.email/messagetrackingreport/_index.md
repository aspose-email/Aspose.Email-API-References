---
title: MessageTrackingReport
second_title: Aspose.Email for Java API Reference
description:  Represents the information to be included in the report.
type: docs
weight: 505
url: /java/com.aspose.email/messagetrackingreport/
---
**Inheritance:**
java.lang.Object
```
public final class MessageTrackingReport
```

Represents the information to be included in the report.
## Methods

| Method | Description |
| --- | --- |
| [getSender()](#getSender--) | Gets the e-mail address for the sender of the message. |
| [getSubject()](#getSubject--) | Gets the subject of the message. |
| [getSubmitTime()](#getSubmitTime--) | Gets the time at which the message was sent to the server. |
| [getOriginalRecipients()](#getOriginalRecipients--) | Gets the e-mail addresses of the message recipients. |
| [getRecipientTrackingEvents()](#getRecipientTrackingEvents--) | Gets the type of events to report. |
### getSender() {#getSender--}
```
public final MailAddress getSender()
```


Gets the e-mail address for the sender of the message.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject of the message.

**Returns:**
java.lang.String
### getSubmitTime() {#getSubmitTime--}
```
public final Date getSubmitTime()
```


Gets the time at which the message was sent to the server.

**Returns:**
java.util.Date
### getOriginalRecipients() {#getOriginalRecipients--}
```
public final MailAddressCollection getOriginalRecipients()
```


Gets the e-mail addresses of the message recipients.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getRecipientTrackingEvents() {#getRecipientTrackingEvents--}
```
public final RecipientTrackingEvent[] getRecipientTrackingEvents()
```


Gets the type of events to report.

**Returns:**
com.aspose.email.RecipientTrackingEvent[]
