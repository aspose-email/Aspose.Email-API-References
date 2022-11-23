---
title: ExchangeQueryBuilder
second_title: Aspose.Email for Java API Reference
description: Represents the builder of search expression based on search filters that used by Exchange protocol.
type: docs
weight: 225
url: /java/com.aspose.email/exchangequerybuilder/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailQueryBuilder](../../com.aspose.email/mailquerybuilder)
```
public final class ExchangeQueryBuilder extends MailQueryBuilder
```

Represents the builder of search expression based on search filters that used by Exchange protocol.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExchangeQueryBuilder()](#ExchangeQueryBuilder--) | Initializes a new instance of the [ExchangeQueryBuilder](../../com.aspose.email/exchangequerybuilder) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppointment()](#getAppointment--) | Gets object with appointment properties to create query |
| [getAttachmentName()](#getAttachmentName--) | Gets the field that allows to find items with a specified attachment name. |
| [getBcc()](#getBcc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field. |
| [getBody()](#getBody--) | Gets the field that allows to find messages that contain the specified string in the body of the message. |
| [getCc()](#getCc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field. |
| [getClass()](#getClass--) |  |
| [getContact()](#getContact--) | Gets object with contact properties to create query |
| [getContentClass()](#getContentClass--) | Gets items with an specified content class. |
| [getDefaultEncoding()](#getDefaultEncoding--) | Gets default encoding (charset) for query builder |
| [getExtendedProperties()](#getExtendedProperties--) |  |
| [getFrom()](#getFrom--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [getInternalDate()](#getInternalDate--) | Gets the field that allows to find messages by internal date. |
| [getItemSize()](#getItemSize--) | Gets the field that allows to find items with a specified size. |
| [getMessageId()](#getMessageId--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's MessageId field. |
| [getQuery()](#getQuery--) | Gets the query. |
| [getSentDate()](#getSentDate--) | Gets the field that allows to find messages by sent date. |
| [getSubject()](#getSubject--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [getTaskStatus()](#getTaskStatus--) | Gets the field that allows to find tasks that contains the specified status. |
| [getText()](#getText--) | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [getTo()](#getTo--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |
| [hasFlags(int flags)](#hasFlags-int-) | Search messages with the specified flags. |
| [hasNoFlags(int flags)](#hasNoFlags-int-) | Search messages with the unspecified flags. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [or(MailQuery query1, MailQuery query2)](#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-) | Search messages that match either search key. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExchangeQueryBuilder() {#ExchangeQueryBuilder--}
```
public ExchangeQueryBuilder()
```


Initializes a new instance of the [ExchangeQueryBuilder](../../com.aspose.email/exchangequerybuilder) class.

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
### getAppointment() {#getAppointment--}
```
public final AppointmentQueryBuilder getAppointment()
```


Gets object with appointment properties to create query

**Returns:**
[AppointmentQueryBuilder](../../com.aspose.email/appointmentquerybuilder)
### getAttachmentName() {#getAttachmentName--}
```
public final StringComparisonField getAttachmentName()
```


Gets the field that allows to find items with a specified attachment name.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getBcc() {#getBcc--}
```
public final StringComparisonField getBcc()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents BCC search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getBody() {#getBody--}
```
public final StringComparisonField getBody()
```


Gets the field that allows to find messages that contain the specified string in the body of the message.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents body search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getCc() {#getCc--}
```
public final StringComparisonField getCc()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents cc search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContact() {#getContact--}
```
public final ContactQueryBuilder getContact()
```


Gets object with contact properties to create query

**Returns:**
[ContactQueryBuilder](../../com.aspose.email/contactquerybuilder)
### getContentClass() {#getContentClass--}
```
public final StringComparisonField getContentClass()
```


Gets items with an specified content class.

Value: The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents a content class.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getDefaultEncoding() {#getDefaultEncoding--}
```
public final Charset getDefaultEncoding()
```


Gets default encoding (charset) for query builder

**Returns:**
java.nio.charset.Charset
### getExtendedProperties() {#getExtendedProperties--}
```
public final ExtendedPropertiesComparisonField getExtendedProperties()
```


Value: Gets dictionary with pairs of property descriptors and comparison field to search by extended properties.

**Returns:**
[ExtendedPropertiesComparisonField](../../com.aspose.email/extendedpropertiescomparisonfield)
### getFrom() {#getFrom--}
```
public final StringComparisonField getFrom()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents from search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getInternalDate() {#getInternalDate--}
```
public final DateComparisonField getInternalDate()
```


Gets the field that allows to find messages by internal date.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents internal date search field.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getItemSize() {#getItemSize--}
```
public final IntComparisonField getItemSize()
```


Gets the field that allows to find items with a specified size.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getMessageId() {#getMessageId--}
```
public final StringComparisonField getMessageId()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's MessageId field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents MessageId search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getQuery() {#getQuery--}
```
public MailQuery getQuery()
```


Gets the query.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query.
### getSentDate() {#getSentDate--}
```
public final DateComparisonField getSentDate()
```


Gets the field that allows to find messages by sent date.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents sent date search field.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getSubject() {#getSubject--}
```
public final StringComparisonField getSubject()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents subject search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getTaskStatus() {#getTaskStatus--}
```
public final EnumComparisonField getTaskStatus()
```


Gets the field that allows to find tasks that contains the specified status. Server compatibility: Exchange 2010 and higher

**Returns:**
[EnumComparisonField](../../com.aspose.email/enumcomparisonfield)
### getText() {#getText--}
```
public final StringComparisonField getText()
```


Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents text header or body search fields.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getTo() {#getTo--}
```
public final StringComparisonField getTo()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents TO search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### hasFlags(int flags) {#hasFlags-int-}
```
public final MailQuery hasFlags(int flags)
```


Search messages with the specified flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | int | The flags. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasNoFlags(int flags) {#hasNoFlags-int-}
```
public final MailQuery hasNoFlags(int flags)
```


Search messages with the unspecified flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | int | The flags. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
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




### or(MailQuery query1, MailQuery query2) {#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-}
```
public MailQuery or(MailQuery query1, MailQuery query2)
```


Search messages that match either search key. Provides disjunction between two expressions (OR).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query1 | [MailQuery](../../com.aspose.email/mailquery) | The query1. |
| query2 | [MailQuery](../../com.aspose.email/mailquery) | The query2. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
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

