---
title: MailQueryBuilder
second_title: Aspose.Email for Java API Reference
description: Represents the builder of search expression.
type: docs
weight: 394
url: /java/com.aspose.email/mailquerybuilder/
---

**Inheritance:**
java.lang.Object
```
public class MailQueryBuilder
```

Represents the builder of search expression.

Note: By default, the result is the intersection (AND function) of all the messages that match those keys. To join keys by OR function, please, use the \#or(MailQuery, MailQuery).or(MailQuery, MailQuery) method of this class
## Constructors

| Constructor | Description |
| --- | --- |
| [MailQueryBuilder()](#MailQueryBuilder--) | Initializes a new instance of the [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) class. |
| [MailQueryBuilder(Charset defaultEncoding)](#MailQueryBuilder-java.nio.charset.Charset-) | Initializes a new instance of the [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBcc()](#getBcc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field. |
| [getBody()](#getBody--) | Gets the field that allows to find messages that contain the specified string in the body of the message. |
| [getCc()](#getCc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field. |
| [getClass()](#getClass--) |  |
| [getDefaultEncoding()](#getDefaultEncoding--) | Gets default encoding (charset) for query builder. |
| [getFrom()](#getFrom--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [getInternalDate()](#getInternalDate--) | Gets the field that allows to find messages by internal date. |
| [getQuery()](#getQuery--) | Gets the query. |
| [getSentDate()](#getSentDate--) | Gets the field that allows to find messages by sent date. |
| [getSubject()](#getSubject--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [getText()](#getText--) | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [getTo()](#getTo--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [or(MailQuery query1, MailQuery query2)](#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-) | Search messages that match either search key. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailQueryBuilder() {#MailQueryBuilder--}
```
public MailQueryBuilder()
```


Initializes a new instance of the [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) class.

### MailQueryBuilder(Charset defaultEncoding) {#MailQueryBuilder-java.nio.charset.Charset-}
```
public MailQueryBuilder(Charset defaultEncoding)
```


Initializes a new instance of the [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| defaultEncoding | java.nio.charset.Charset | Contains default encoding (charset) for query builder. |

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

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents BCC search field.
### getBody() {#getBody--}
```
public final StringComparisonField getBody()
```


Gets the field that allows to find messages that contain the specified string in the body of the message.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents body search field.
### getCc() {#getCc--}
```
public final StringComparisonField getCc()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents cc search field.
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


Gets default encoding (charset) for query builder.

**Returns:**
java.nio.charset.Charset
### getFrom() {#getFrom--}
```
public final StringComparisonField getFrom()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents from search field.
### getInternalDate() {#getInternalDate--}
```
public final DateComparisonField getInternalDate()
```


Gets the field that allows to find messages by internal date.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield) - The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents internal date search field.
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

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield) - The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents sent date search field.
### getSubject() {#getSubject--}
```
public final StringComparisonField getSubject()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents subject search field.
### getText() {#getText--}
```
public final StringComparisonField getText()
```


Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents text header or body search fields.
### getTo() {#getTo--}
```
public final StringComparisonField getTo()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents TO search field.
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

