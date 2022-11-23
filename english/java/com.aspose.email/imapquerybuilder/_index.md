---
title: ImapQueryBuilder
second_title: Aspose.Email for Java API Reference
description: Represents the builder of search expression that used by IMAP protocol.
type: docs
weight: 325
url: /java/com.aspose.email/imapquerybuilder/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailQueryBuilder](../../com.aspose.email/mailquerybuilder)
```
public final class ImapQueryBuilder extends MailQueryBuilder
```

Represents the builder of search expression that used by IMAP protocol.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImapQueryBuilder(Charset defaultEncoding)](#ImapQueryBuilder-java.nio.charset.Charset-) | Initializes a new instance of the [ImapQueryBuilder](../../com.aspose.email/imapquerybuilder) class. |
| [ImapQueryBuilder()](#ImapQueryBuilder--) | Initializes a new instance of the [ImapQueryBuilder](../../com.aspose.email/imapquerybuilder) class. |
## Methods

| Method | Description |
| --- | --- |
| [customSearch(String fieldValue)](#customSearch-java.lang.String-) | Search messages according to extended server search syntax. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBcc()](#getBcc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field. |
| [getBody()](#getBody--) | Gets the field that allows to find messages that contain the specified string in the body of the message. |
| [getCc()](#getCc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field. |
| [getClass()](#getClass--) |  |
| [getDefaultEncoding()](#getDefaultEncoding--) | Gets default encoding (charset) for query builder |
| [getESearchParameters()](#getESearchParameters--) | Gets or sets ESEARCH Parameters This method works only if server supports ESEARCH extension. |
| [getFrom()](#getFrom--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [getInternalDate()](#getInternalDate--) | Gets the field that allows to find messages by internal date. |
| [getMessageSize()](#getMessageSize--) | Gets messages with an specified size. |
| [getModSeq()](#getModSeq--) | Modification sequence |
| [getQuery()](#getQuery--) | Gets the query. |
| [getSentDate()](#getSentDate--) | Gets the field that allows to find messages by sent date. |
| [getSubject()](#getSubject--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [getText()](#getText--) | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [getTo()](#getTo--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |
| [getUniqueId()](#getUniqueId--) | Unique identifier |
| [hasFlags(ImapMessageFlags flags)](#hasFlags-com.aspose.email.ImapMessageFlags-) | Search messages with the specified flags. |
| [hasHeader(String fieldName, String fieldValue)](#hasHeader-java.lang.String-java.lang.String-) | Search messages that have a header with the specified field-name and that contains the specified string in the text of the header (what comes after the colon). |
| [hasNoFlags(ImapMessageFlags flags)](#hasNoFlags-com.aspose.email.ImapMessageFlags-) | Search messages with the unspecified flags. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [or(MailQuery query1, MailQuery query2)](#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-) | Search messages that match either search key. |
| [setESearchParameters(ESearchOptions value)](#setESearchParameters-com.aspose.email.ESearchOptions-) | Gets or sets ESEARCH Parameters This method works only if server supports ESEARCH extension. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImapQueryBuilder(Charset defaultEncoding) {#ImapQueryBuilder-java.nio.charset.Charset-}
```
public ImapQueryBuilder(Charset defaultEncoding)
```


Initializes a new instance of the [ImapQueryBuilder](../../com.aspose.email/imapquerybuilder) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| defaultEncoding | java.nio.charset.Charset | Contains default encoding (charset) for query builder. |

### ImapQueryBuilder() {#ImapQueryBuilder--}
```
public ImapQueryBuilder()
```


Initializes a new instance of the [ImapQueryBuilder](../../com.aspose.email/imapquerybuilder) class.

### customSearch(String fieldValue) {#customSearch-java.lang.String-}
```
public final MailQuery customSearch(String fieldValue)
```


Search messages according to extended server search syntax.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldValue | java.lang.String | The field value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
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
### getDefaultEncoding() {#getDefaultEncoding--}
```
public final Charset getDefaultEncoding()
```


Gets default encoding (charset) for query builder

**Returns:**
java.nio.charset.Charset
### getESearchParameters() {#getESearchParameters--}
```
public final ESearchOptions getESearchParameters()
```


Gets or sets ESEARCH Parameters This method works only if server supports ESEARCH extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:**
[ESearchOptions](../../com.aspose.email/esearchoptions)
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
### getMessageSize() {#getMessageSize--}
```
public final IntComparisonField getMessageSize()
```


Gets messages with an specified size.

Value: The [IntComparisonField](../../com.aspose.email/intcomparisonfield) that represents a message size.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getModSeq() {#getModSeq--}
```
public final ModificationSequenceField getModSeq()
```


Modification sequence

**Returns:**
[ModificationSequenceField](../../com.aspose.email/modificationsequencefield)
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
### getUniqueId() {#getUniqueId--}
```
public final SequenceSetField getUniqueId()
```


Unique identifier

**Returns:**
[SequenceSetField](../../com.aspose.email/sequencesetfield)
### hasFlags(ImapMessageFlags flags) {#hasFlags-com.aspose.email.ImapMessageFlags-}
```
public final MailQuery hasFlags(ImapMessageFlags flags)
```


Search messages with the specified flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | The flags. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasHeader(String fieldName, String fieldValue) {#hasHeader-java.lang.String-java.lang.String-}
```
public final MailQuery hasHeader(String fieldName, String fieldValue)
```


Search messages that have a header with the specified field-name and that contains the specified string in the text of the header (what comes after the colon). If the string to search is zero-length, this matches all messages that have a header line with the specified field-name regardless of the contents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the field. |
| fieldValue | java.lang.String | The field value. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasNoFlags(ImapMessageFlags flags) {#hasNoFlags-com.aspose.email.ImapMessageFlags-}
```
public final MailQuery hasNoFlags(ImapMessageFlags flags)
```


Search messages with the unspecified flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | The flags. |

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
### setESearchParameters(ESearchOptions value) {#setESearchParameters-com.aspose.email.ESearchOptions-}
```
public final void setESearchParameters(ESearchOptions value)
```


Gets or sets ESEARCH Parameters This method works only if server supports ESEARCH extension. Please, read more https://tools.ietf.org/html/rfc4315

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ESearchOptions](../../com.aspose.email/esearchoptions) |  |

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

