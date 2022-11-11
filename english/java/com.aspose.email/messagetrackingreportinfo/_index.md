---
title: MessageTrackingReportInfo
second_title: Aspose.Email for Java API Reference
description: Represents an information about the message that was found by using the FindMessageTrackingReport
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessageTrackingReportId()](#getMessageTrackingReportId--) | Gets the value specifying message by its message-id, the organization where the message was found, the server on which the message was submitted, and an internal ID that uniquely identifies the message. |
| [getPreviousHopServer()](#getPreviousHopServer--) | Gets the previous server name, when available, that submitted the message. |
| [getRecipients()](#getRecipients--) | Gets the e-mail addresses of the recipients for the message that was found. |
| [getSender()](#getSender--) | Gets the e-mail address of the sender for the message that was found. |
| [getSubject()](#getSubject--) | Gets the subject of the message that was found. |
| [getSubmittedTime()](#getSubmittedTime--) | Gets the time that the message entered the server. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getRecipients() {#getRecipients--}
```
public final MailAddressCollection getRecipients()
```


Gets the e-mail addresses of the recipients for the message that was found.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getSender() {#getSender--}
```
public final MailAddress getSender()
```


Gets the e-mail address of the sender for the message that was found.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject of the message that was found.

**Returns:**
java.lang.String
### getSubmittedTime() {#getSubmittedTime--}
```
public final Date getSubmittedTime()
```


Gets the time that the message entered the server.

**Returns:**
java.util.Date
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

