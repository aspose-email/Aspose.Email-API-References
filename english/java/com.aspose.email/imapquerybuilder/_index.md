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
| [getMessageSize()](#getMessageSize--) | Gets messages with an specified size. |
| [getUniqueId()](#getUniqueId--) | Unique identifier |
| [getESearchParameters()](#getESearchParameters--) | Gets or sets ESEARCH Parameters This method works only if server supports ESEARCH extension. |
| [setESearchParameters(ESearchOptions value)](#setESearchParameters-com.aspose.email.ESearchOptions-) | Gets or sets ESEARCH Parameters This method works only if server supports ESEARCH extension. |
| [getModSeq()](#getModSeq--) | Modification sequence |
| [hasFlags(ImapMessageFlags flags)](#hasFlags-com.aspose.email.ImapMessageFlags-) | Search messages with the specified flags. |
| [hasNoFlags(ImapMessageFlags flags)](#hasNoFlags-com.aspose.email.ImapMessageFlags-) | Search messages with the unspecified flags. |
| [hasHeader(String fieldName, String fieldValue)](#hasHeader-java.lang.String-java.lang.String-) | Search messages that have a header with the specified field-name and that contains the specified string in the text of the header (what comes after the colon). |
| [customSearch(String fieldValue)](#customSearch-java.lang.String-) | Search messages according to extended server search syntax. |
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

### getMessageSize() {#getMessageSize--}
```
public final IntComparisonField getMessageSize()
```


Gets messages with an specified size.

Value: The [IntComparisonField](../../com.aspose.email/intcomparisonfield) that represents a message size.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getUniqueId() {#getUniqueId--}
```
public final SequenceSetField getUniqueId()
```


Unique identifier

**Returns:**
[SequenceSetField](../../com.aspose.email/sequencesetfield)
### getESearchParameters() {#getESearchParameters--}
```
public final ESearchOptions getESearchParameters()
```


Gets or sets ESEARCH Parameters This method works only if server supports ESEARCH extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:**
[ESearchOptions](../../com.aspose.email/esearchoptions)
### setESearchParameters(ESearchOptions value) {#setESearchParameters-com.aspose.email.ESearchOptions-}
```
public final void setESearchParameters(ESearchOptions value)
```


Gets or sets ESEARCH Parameters This method works only if server supports ESEARCH extension. Please, read more https://tools.ietf.org/html/rfc4315

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ESearchOptions](../../com.aspose.email/esearchoptions) |  |

### getModSeq() {#getModSeq--}
```
public final ModificationSequenceField getModSeq()
```


Modification sequence

**Returns:**
[ModificationSequenceField](../../com.aspose.email/modificationsequencefield)
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
