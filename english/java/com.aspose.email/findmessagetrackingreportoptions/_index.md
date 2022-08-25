---
title: FindMessageTrackingReportOptions
second_title: Aspose.Email for Java API Reference
description:  Represents options for FindMessageTrackingReport operation
type: docs
weight: 252
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
| [getScope()](#getScope--) | Gets or sets the search scope (non-empty string) |
| [setScope(String value)](#setScope-java.lang.String-) | Gets or sets the search scope (non-empty string) |
| [getDomain()](#getDomain--) | Gets or sets the domain to search for. |
| [setDomain(String value)](#setDomain-java.lang.String-) | Gets or sets the domain to search for. |
| [getSender()](#getSender--) | Gets or sets the e-mail address of the person who is sending the message. |
| [setSender(MailAddress value)](#setSender-com.aspose.email.MailAddress-) | Gets or sets the e-mail address of the person who is sending the message. |
| [getRecipient()](#getRecipient--) | Gets or sets the e-mail addresses of the people who are receiving the message. |
| [setRecipient(MailAddress value)](#setRecipient-com.aspose.email.MailAddress-) | Gets or sets the e-mail addresses of the people who are receiving the message. |
| [getSubject()](#getSubject--) | Gets or sets the subject filter to search for. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets the subject filter to search for. |
| [getStartDateTime()](#getStartDateTime--) | Gets or sets the search time period, indicating that the message was sent after this value. |
| [setStartDateTime(Date value)](#setStartDateTime-java.util.Date-) | Gets or sets the search time period, indicating that the message was sent after this value. |
| [getEndDateTime()](#getEndDateTime--) | Gets or sets the search time period, indicating that the message was sent before this value. |
| [setEndDateTime(Date value)](#setEndDateTime-java.util.Date-) | Gets or sets the search time period, indicating that the message was sent before this value. |
| [getMessageId()](#getMessageId--) | Gets or sets the message identification to search for. |
| [setMessageId(String value)](#setMessageId-java.lang.String-) | Gets or sets the message identification to search for. |
| [getFederatedDeliveryMailbox()](#getFederatedDeliveryMailbox--) | Gets or sets the mailbox to which a cross-premise message was sent. |
| [setFederatedDeliveryMailbox(MailAddress value)](#setFederatedDeliveryMailbox-com.aspose.email.MailAddress-) | Gets or sets the mailbox to which a cross-premise message was sent. |
| [getDiagnosticsLevel()](#getDiagnosticsLevel--) | Gets or sets diagnostics level specifying how detailed the tracing report should be. |
| [setDiagnosticsLevel(String value)](#setDiagnosticsLevel-java.lang.String-) | Gets or sets diagnostics level specifying how detailed the tracing report should be. |
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

### getScope() {#getScope--}
```
public final String getScope()
```


Gets or sets the search scope (non-empty string)

**Returns:**
java.lang.String
### setScope(String value) {#setScope-java.lang.String-}
```
public final void setScope(String value)
```


Gets or sets the search scope (non-empty string)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDomain() {#getDomain--}
```
public final String getDomain()
```


Gets or sets the domain to search for.

**Returns:**
java.lang.String
### setDomain(String value) {#setDomain-java.lang.String-}
```
public final void setDomain(String value)
```


Gets or sets the domain to search for.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSender() {#getSender--}
```
public final MailAddress getSender()
```


Gets or sets the e-mail address of the person who is sending the message.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### setSender(MailAddress value) {#setSender-com.aspose.email.MailAddress-}
```
public final void setSender(MailAddress value)
```


Gets or sets the e-mail address of the person who is sending the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### getRecipient() {#getRecipient--}
```
public final MailAddress getRecipient()
```


Gets or sets the e-mail addresses of the people who are receiving the message.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### setRecipient(MailAddress value) {#setRecipient-com.aspose.email.MailAddress-}
```
public final void setRecipient(MailAddress value)
```


Gets or sets the e-mail addresses of the people who are receiving the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets or sets the subject filter to search for.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gets or sets the subject filter to search for.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getStartDateTime() {#getStartDateTime--}
```
public final Date getStartDateTime()
```


Gets or sets the search time period, indicating that the message was sent after this value.

**Returns:**
java.util.Date
### setStartDateTime(Date value) {#setStartDateTime-java.util.Date-}
```
public final void setStartDateTime(Date value)
```


Gets or sets the search time period, indicating that the message was sent after this value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getEndDateTime() {#getEndDateTime--}
```
public final Date getEndDateTime()
```


Gets or sets the search time period, indicating that the message was sent before this value.

**Returns:**
java.util.Date
### setEndDateTime(Date value) {#setEndDateTime-java.util.Date-}
```
public final void setEndDateTime(Date value)
```


Gets or sets the search time period, indicating that the message was sent before this value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getMessageId() {#getMessageId--}
```
public final String getMessageId()
```


Gets or sets the message identification to search for.

**Returns:**
java.lang.String
### setMessageId(String value) {#setMessageId-java.lang.String-}
```
public final void setMessageId(String value)
```


Gets or sets the message identification to search for.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFederatedDeliveryMailbox() {#getFederatedDeliveryMailbox--}
```
public final MailAddress getFederatedDeliveryMailbox()
```


Gets or sets the mailbox to which a cross-premise message was sent.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### setFederatedDeliveryMailbox(MailAddress value) {#setFederatedDeliveryMailbox-com.aspose.email.MailAddress-}
```
public final void setFederatedDeliveryMailbox(MailAddress value)
```


Gets or sets the mailbox to which a cross-premise message was sent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### getDiagnosticsLevel() {#getDiagnosticsLevel--}
```
public final String getDiagnosticsLevel()
```


Gets or sets diagnostics level specifying how detailed the tracing report should be.

**Returns:**
java.lang.String
### setDiagnosticsLevel(String value) {#setDiagnosticsLevel-java.lang.String-}
```
public final void setDiagnosticsLevel(String value)
```


Gets or sets diagnostics level specifying how detailed the tracing report should be.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

