---
title: MessageTrackingReportInfo
second_title: Aspose.Email for Java API Reference
description:  Represents an information about the message that was found by using the FindMessageTrackingReport
type: docs
weight: 506
url: /java/com.aspose.email/messagetrackingreportinfo/
---
**Inheritance:**
java.lang.Object
```
public final class MessageTrackingReportInfo
```

Represents an information about the message that was found by using the FindMessageTrackingReport
## Methods

| Method | Description |
| --- | --- |
| [getSubject()](#getSubject--) | Gets the subject of the message that was found. |
| [getSender()](#getSender--) | Gets the e-mail address of the sender for the message that was found. |
| [getRecipients()](#getRecipients--) | Gets the e-mail addresses of the recipients for the message that was found. |
| [getSubmittedTime()](#getSubmittedTime--) | Gets the time that the message entered the server. |
| [getMessageTrackingReportId()](#getMessageTrackingReportId--) | Gets the value specifying message by its message-id, the organization where the message was found, the server on which the message was submitted, and an internal ID that uniquely identifies the message. |
| [getPreviousHopServer()](#getPreviousHopServer--) | Gets the previous server name, when available, that submitted the message. |
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject of the message that was found.

**Returns:**
java.lang.String
### getSender() {#getSender--}
```
public final MailAddress getSender()
```


Gets the e-mail address of the sender for the message that was found.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getRecipients() {#getRecipients--}
```
public final MailAddressCollection getRecipients()
```


Gets the e-mail addresses of the recipients for the message that was found.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getSubmittedTime() {#getSubmittedTime--}
```
public final Date getSubmittedTime()
```


Gets the time that the message entered the server.

**Returns:**
java.util.Date
### getMessageTrackingReportId() {#getMessageTrackingReportId--}
```
public final String getMessageTrackingReportId()
```


Gets the value specifying message by its message-id, the organization where the message was found, the server on which the message was submitted, and an internal ID that uniquely identifies the message.

**Returns:**
java.lang.String
### getPreviousHopServer() {#getPreviousHopServer--}
```
public final String getPreviousHopServer()
```


Gets the previous server name, when available, that submitted the message.

**Returns:**
java.lang.String
