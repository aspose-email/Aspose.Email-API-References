---
title: ExchangeAdvancedSyntaxQueryBuilder
second_title: Aspose.Email for Java API Reference
description: Represents the builder of search expression based on the Advanced Query Syntax AQS that used by Exchange protocol.
type: docs
weight: 186
url: /java/com.aspose.email/exchangeadvancedsyntaxquerybuilder/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailQueryBuilder](../../com.aspose.email/mailquerybuilder)
```
public final class ExchangeAdvancedSyntaxQueryBuilder extends MailQueryBuilder
```

Represents the builder of search expression based on the Advanced Query Syntax (AQS) that used by Exchange protocol. AQS is an alternative to search filters for expressing search criteria.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExchangeAdvancedSyntaxQueryBuilder()](#ExchangeAdvancedSyntaxQueryBuilder--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachment()](#getAttachment--) | Gets the field that allows to find items with a specified attachment name. |
| [getBcc()](#getBcc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field. |
| [getBody()](#getBody--) | Gets the field that allows to find messages that contain the specified string in the body of the message. |
| [getCategory()](#getCategory--) |  |
| [getCc()](#getCc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field. |
| [getClass()](#getClass--) |  |
| [getDefaultEncoding()](#getDefaultEncoding--) | Gets default encoding (charset) for query builder |
| [getFrom()](#getFrom--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [getImportance()](#getImportance--) |  |
| [getInternalDate()](#getInternalDate--) | Gets the field that allows to find messages by internal date. |
| [getIsflagged()](#getIsflagged--) |  |
| [getKind()](#getKind--) |  |
| [getParticipants()](#getParticipants--) |  |
| [getQuery()](#getQuery--) | Gets the query. |
| [getSentDate()](#getSentDate--) | Gets the field that allows to find messages by sent date. |
| [getSize()](#getSize--) |  |
| [getSubject()](#getSubject--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [getText()](#getText--) | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [getTo()](#getTo--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |
| [hasAttachment()](#hasAttachment--) |  |
| [hashCode()](#hashCode--) |  |
| [isRead()](#isRead--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [or(MailQuery query1, MailQuery query2)](#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-) | Search messages that match either search key. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExchangeAdvancedSyntaxQueryBuilder() {#ExchangeAdvancedSyntaxQueryBuilder--}
```
public ExchangeAdvancedSyntaxQueryBuilder()
```




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
### getAttachment() {#getAttachment--}
```
public final StringComparisonField getAttachment()
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
### getCategory() {#getCategory--}
```
public final StringComparisonField getCategory()
```




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
### getDefaultEncoding() {#getDefaultEncoding--}
```
public final Charset getDefaultEncoding()
```


Gets default encoding (charset) for query builder

**Returns:**
java.nio.charset.Charset
### getFrom() {#getFrom--}
```
public final StringComparisonField getFrom()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents from search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getImportance() {#getImportance--}
```
public final StringComparisonField getImportance()
```




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
### getIsflagged() {#getIsflagged--}
```
public final BoolComparisonField getIsflagged()
```




**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### getKind() {#getKind--}
```
public final EnumComparisonField getKind()
```




**Returns:**
[EnumComparisonField](../../com.aspose.email/enumcomparisonfield)
### getParticipants() {#getParticipants--}
```
public final StringComparisonField getParticipants()
```




**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getQuery() {#getQuery--}
```
public final MailQuery getQuery()
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
### getSize() {#getSize--}
```
public final IntComparisonField getSize()
```




**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getSubject() {#getSubject--}
```
public final StringComparisonField getSubject()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents subject search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
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
### hasAttachment() {#hasAttachment--}
```
public final BoolComparisonField hasAttachment()
```




**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isRead() {#isRead--}
```
public final BoolComparisonField isRead()
```




**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
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
public final MailQuery or(MailQuery query1, MailQuery query2)
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

