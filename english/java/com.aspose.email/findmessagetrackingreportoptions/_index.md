---
title: FindMessageTrackingReportOptions
second_title: Aspose.Email for Java API Reference
description: Represents options for FindMessageTrackingReport operation
type: docs
weight: 254
url: /java/com.aspose.email/findmessagetrackingreportoptions/
---

**Inheritance:**
java.lang.Object
```
public final class FindMessageTrackingReportOptions
```

Represents options for FindMessageTrackingReport operation
## Constructors

| Constructor | Description |
| --- | --- |
| [FindMessageTrackingReportOptions(String scope, String domain)](#FindMessageTrackingReportOptions-java.lang.String-java.lang.String-) | Initializes a new instance of the [FindMessageTrackingReportOptions](../../com.aspose.email/findmessagetrackingreportoptions) class |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDiagnosticsLevel()](#getDiagnosticsLevel--) | Gets or sets diagnostics level specifying how detailed the tracing report should be. |
| [getDomain()](#getDomain--) | Gets or sets the domain to search for. |
| [getEndDateTime()](#getEndDateTime--) | Gets or sets the search time period, indicating that the message was sent before this value. |
| [getFederatedDeliveryMailbox()](#getFederatedDeliveryMailbox--) | Gets or sets the mailbox to which a cross-premise message was sent. |
| [getMessageId()](#getMessageId--) | Gets or sets the message identification to search for. |
| [getRecipient()](#getRecipient--) | Gets or sets the e-mail addresses of the people who are receiving the message. |
| [getScope()](#getScope--) | Gets or sets the search scope (non-empty string) |
| [getSender()](#getSender--) | Gets or sets the e-mail address of the person who is sending the message. |
| [getStartDateTime()](#getStartDateTime--) | Gets or sets the search time period, indicating that the message was sent after this value. |
| [getSubject()](#getSubject--) | Gets or sets the subject filter to search for. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDiagnosticsLevel(String value)](#setDiagnosticsLevel-java.lang.String-) | Gets or sets diagnostics level specifying how detailed the tracing report should be. |
| [setDomain(String value)](#setDomain-java.lang.String-) | Gets or sets the domain to search for. |
| [setEndDateTime(Date value)](#setEndDateTime-java.util.Date-) | Gets or sets the search time period, indicating that the message was sent before this value. |
| [setFederatedDeliveryMailbox(MailAddress value)](#setFederatedDeliveryMailbox-com.aspose.email.MailAddress-) | Gets or sets the mailbox to which a cross-premise message was sent. |
| [setMessageId(String value)](#setMessageId-java.lang.String-) | Gets or sets the message identification to search for. |
| [setRecipient(MailAddress value)](#setRecipient-com.aspose.email.MailAddress-) | Gets or sets the e-mail addresses of the people who are receiving the message. |
| [setScope(String value)](#setScope-java.lang.String-) | Gets or sets the search scope (non-empty string) |
| [setSender(MailAddress value)](#setSender-com.aspose.email.MailAddress-) | Gets or sets the e-mail address of the person who is sending the message. |
| [setStartDateTime(Date value)](#setStartDateTime-java.util.Date-) | Gets or sets the search time period, indicating that the message was sent after this value. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets the subject filter to search for. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FindMessageTrackingReportOptions(String scope, String domain) {#FindMessageTrackingReportOptions-java.lang.String-java.lang.String-}
```
public FindMessageTrackingReportOptions(String scope, String domain)
```


Initializes a new instance of the [FindMessageTrackingReportOptions](../../com.aspose.email/findmessagetrackingreportoptions) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scope | java.lang.String | Specifies where to perform the search. |
| domain | java.lang.String | Specified the domain to search for. |

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
### getDiagnosticsLevel() {#getDiagnosticsLevel--}
```
public final String getDiagnosticsLevel()
```


Gets or sets diagnostics level specifying how detailed the tracing report should be.

**Returns:**
java.lang.String
### getDomain() {#getDomain--}
```
public final String getDomain()
```


Gets or sets the domain to search for.

**Returns:**
java.lang.String
### getEndDateTime() {#getEndDateTime--}
```
public final Date getEndDateTime()
```


Gets or sets the search time period, indicating that the message was sent before this value.

**Returns:**
java.util.Date
### getFederatedDeliveryMailbox() {#getFederatedDeliveryMailbox--}
```
public final MailAddress getFederatedDeliveryMailbox()
```


Gets or sets the mailbox to which a cross-premise message was sent.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getMessageId() {#getMessageId--}
```
public final String getMessageId()
```


Gets or sets the message identification to search for.

**Returns:**
java.lang.String
### getRecipient() {#getRecipient--}
```
public final MailAddress getRecipient()
```


Gets or sets the e-mail addresses of the people who are receiving the message.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getScope() {#getScope--}
```
public final String getScope()
```


Gets or sets the search scope (non-empty string)

**Returns:**
java.lang.String
### getSender() {#getSender--}
```
public final MailAddress getSender()
```


Gets or sets the e-mail address of the person who is sending the message.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getStartDateTime() {#getStartDateTime--}
```
public final Date getStartDateTime()
```


Gets or sets the search time period, indicating that the message was sent after this value.

**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets or sets the subject filter to search for.

**Returns:**
java.lang.String
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




### setDiagnosticsLevel(String value) {#setDiagnosticsLevel-java.lang.String-}
```
public final void setDiagnosticsLevel(String value)
```


Gets or sets diagnostics level specifying how detailed the tracing report should be.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDomain(String value) {#setDomain-java.lang.String-}
```
public final void setDomain(String value)
```


Gets or sets the domain to search for.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setEndDateTime(Date value) {#setEndDateTime-java.util.Date-}
```
public final void setEndDateTime(Date value)
```


Gets or sets the search time period, indicating that the message was sent before this value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setFederatedDeliveryMailbox(MailAddress value) {#setFederatedDeliveryMailbox-com.aspose.email.MailAddress-}
```
public final void setFederatedDeliveryMailbox(MailAddress value)
```


Gets or sets the mailbox to which a cross-premise message was sent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setMessageId(String value) {#setMessageId-java.lang.String-}
```
public final void setMessageId(String value)
```


Gets or sets the message identification to search for.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setRecipient(MailAddress value) {#setRecipient-com.aspose.email.MailAddress-}
```
public final void setRecipient(MailAddress value)
```


Gets or sets the e-mail addresses of the people who are receiving the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setScope(String value) {#setScope-java.lang.String-}
```
public final void setScope(String value)
```


Gets or sets the search scope (non-empty string)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSender(MailAddress value) {#setSender-com.aspose.email.MailAddress-}
```
public final void setSender(MailAddress value)
```


Gets or sets the e-mail address of the person who is sending the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setStartDateTime(Date value) {#setStartDateTime-java.util.Date-}
```
public final void setStartDateTime(Date value)
```


Gets or sets the search time period, indicating that the message was sent after this value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gets or sets the subject filter to search for.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

