---
title: PersonalStorageQueryBuilder
second_title: Aspose.Email for Java API Reference
description: Represents the builder of search expression that used by pst.
type: docs
weight: 587
url: /java/com.aspose.email/personalstoragequerybuilder/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailQueryBuilder](../../com.aspose.email/mailquerybuilder)
```
public final class PersonalStorageQueryBuilder extends MailQueryBuilder
```

Represents the builder of search expression that used by pst.
## Constructors

| Constructor | Description |
| --- | --- |
| [PersonalStorageQueryBuilder()](#PersonalStorageQueryBuilder--) | Initializes a new instance of the [PersonalStorageQueryBuilder](../../com.aspose.email/personalstoragequerybuilder) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findConversationThread(MessageInfo relatedMessage)](#findConversationThread-com.aspose.email.MessageInfo-) | Finds the conversation thread. |
| [getBcc()](#getBcc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field. |
| [getBody()](#getBody--) | Gets the field that allows to find messages that contain the specified string in the body of the message. |
| [getCc()](#getCc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field. |
| [getClass()](#getClass--) |  |
| [getContainerClass()](#getContainerClass--) | Gets folders with an specified message class. |
| [getContentsCount()](#getContentsCount--) | Search folders with an specified contents count. |
| [getDefaultEncoding()](#getDefaultEncoding--) | Gets default encoding (charset) for query builder |
| [getFolderName()](#getFolderName--) | Search folders with an specified display name. |
| [getFrom()](#getFrom--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [getImportance()](#getImportance--) | Search messages with an specified importance. |
| [getInternalDate()](#getInternalDate--) | Gets the field that allows to find messages by internal date. |
| [getMessageClass()](#getMessageClass--) | Gets messages with an specified message class. |
| [getMessageId()](#getMessageId--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's MessageId field. |
| [getMessageSize()](#getMessageSize--) | Search messages with an specified size. |
| [getOnlyFoldersCreatedByUser()](#getOnlyFoldersCreatedByUser--) | Gets folders that created by user, i.e. |
| [getQuery()](#getQuery--) | Gets the query. |
| [getSentDate()](#getSentDate--) | Gets the field that allows to find messages by sent date. |
| [getSubject()](#getSubject--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [getText()](#getText--) | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [getTo()](#getTo--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |
| [getUnreadContentsCount()](#getUnreadContentsCount--) | Search folders with an specified unread contents count. |
| [hasFlags(long flags)](#hasFlags-long-) | Search messages with the specified flags. |
| [hasNoFlags(long flags)](#hasNoFlags-long-) | Search messages with the unspecified flags. |
| [hasNoSubfolders()](#hasNoSubfolders--) | Search folders which does not contains subfolders. |
| [hasSubfolders()](#hasSubfolders--) | Search folders which contains subfolders. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [or(MailQuery query1, MailQuery query2)](#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-) | Search messages that match either search key. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PersonalStorageQueryBuilder() {#PersonalStorageQueryBuilder--}
```
public PersonalStorageQueryBuilder()
```


Initializes a new instance of the [PersonalStorageQueryBuilder](../../com.aspose.email/personalstoragequerybuilder) class.

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
### findConversationThread(MessageInfo relatedMessage) {#findConversationThread-com.aspose.email.MessageInfo-}
```
public final MailQuery findConversationThread(MessageInfo relatedMessage)
```


Finds the conversation thread.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relatedMessage | [MessageInfo](../../com.aspose.email/messageinfo) | The related message. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - 
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
### getContainerClass() {#getContainerClass--}
```
public final StringComparisonField getContainerClass()
```


Gets folders with an specified message class.

Value: The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents a container class.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getContentsCount() {#getContentsCount--}
```
public final IntComparisonField getContentsCount()
```


Search folders with an specified contents count.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getDefaultEncoding() {#getDefaultEncoding--}
```
public final Charset getDefaultEncoding()
```


Gets default encoding (charset) for query builder

**Returns:**
java.nio.charset.Charset
### getFolderName() {#getFolderName--}
```
public final StringComparisonField getFolderName()
```


Search folders with an specified display name.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
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
public final IntComparisonField getImportance()
```


Search messages with an specified importance.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getInternalDate() {#getInternalDate--}
```
public final DateComparisonField getInternalDate()
```


Gets the field that allows to find messages by internal date.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents internal date search field.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getMessageClass() {#getMessageClass--}
```
public final StringComparisonField getMessageClass()
```


Gets messages with an specified message class.

Value: The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents a message class.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getMessageId() {#getMessageId--}
```
public final StringComparisonField getMessageId()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's MessageId field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents MessageId search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getMessageSize() {#getMessageSize--}
```
public final IntComparisonField getMessageSize()
```


Search messages with an specified size.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getOnlyFoldersCreatedByUser() {#getOnlyFoldersCreatedByUser--}
```
public final BoolComparisonField getOnlyFoldersCreatedByUser()
```


Gets folders that created by user, i.e. excludes all standard IPM folders.

Value: The[BoolComparisonField](../../com.aspose.email/boolcomparisonfield) that represents search field.

**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
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
### getUnreadContentsCount() {#getUnreadContentsCount--}
```
public final IntComparisonField getUnreadContentsCount()
```


Search folders with an specified unread contents count.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### hasFlags(long flags) {#hasFlags-long-}
```
public final MailQuery hasFlags(long flags)
```


Search messages with the specified flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The flags. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasNoFlags(long flags) {#hasNoFlags-long-}
```
public final MailQuery hasNoFlags(long flags)
```


Search messages with the unspecified flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The flags. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasNoSubfolders() {#hasNoSubfolders--}
```
public final MailQuery hasNoSubfolders()
```


Search folders which does not contains subfolders.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasSubfolders() {#hasSubfolders--}
```
public final MailQuery hasSubfolders()
```


Search folders which contains subfolders.

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

