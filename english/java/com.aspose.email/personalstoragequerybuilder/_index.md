---
title: PersonalStorageQueryBuilder
second_title: Aspose.Email for Java API Reference
description: Builds search queries for the messages and folders of a PST.
type: docs
weight: 591
url: /java/com.aspose.email/personalstoragequerybuilder/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailQueryBuilder](../../com.aspose.email/mailquerybuilder)
```
public final class PersonalStorageQueryBuilder extends MailQueryBuilder
```

Builds search queries for the messages and folders of a PST.

Add conditions through the fields of the builder: for messages, the fields inherited from [MailQueryBuilder](../../com.aspose.email/mailquerybuilder), such as  getFrom()  or  getSubject() , and fields such as  getMessageClass() ; for folders,  getFolderName() ,  getContentsCount()  and the like. All conditions are combined. Pass the result of  getQuery()  to  FolderInfo.getContents  or  FolderInfo.getSubFolders .

This example finds the unread messages of the Inbox from a given sender whose subject contains "invoice".

```

 try (PersonalStorage pst = PersonalStorage.fromFile("archive.pst")) {
     FolderInfo inbox = pst.getPredefinedFolder(StandardIpmFolder.Inbox);

     PersonalStorageQueryBuilder builder = new PersonalStorageQueryBuilder();
     builder.getFrom().contains("billing@example.com");
     builder.getSubject().contains("invoice", true);
     builder.hasNoFlags(MapiMessageFlags.MSGFLAG_READ);

     for (MessageInfo messageInfo : inbox.getContents(builder.getQuery())) {
         System.out.println(messageInfo.getSubject());
     }
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [PersonalStorageQueryBuilder()](#PersonalStorageQueryBuilder--) | Initializes a new instance of the [PersonalStorageQueryBuilder](../../com.aspose.email/personalstoragequerybuilder) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findConversationThread(MessageInfo relatedMessage)](#findConversationThread-com.aspose.email.MessageInfo-) | Adds a condition that finds the messages of the same conversation as the specified message. |
| [getBcc()](#getBcc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field. |
| [getBody()](#getBody--) | Gets the field that allows to find messages that contain the specified string in the body of the message. |
| [getCc()](#getCc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field. |
| [getClass()](#getClass--) |  |
| [getContainerClass()](#getContainerClass--) | Gets the field to search folders by container class. |
| [getContentsCount()](#getContentsCount--) | Gets the field to search folders by the number of items they contain. |
| [getDefaultEncoding()](#getDefaultEncoding--) | Gets default encoding (charset) for query builder. |
| [getFolderName()](#getFolderName--) | Gets the field to search folders by name. |
| [getFrom()](#getFrom--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [getImportance()](#getImportance--) | Gets the field to search messages by importance. |
| [getInternalDate()](#getInternalDate--) | Gets the field that allows to find messages by internal date. |
| [getMessageClass()](#getMessageClass--) | Gets the field to search messages by message class. |
| [getMessageId()](#getMessageId--) | Gets the field to search messages by the Message-ID header. |
| [getMessageSize()](#getMessageSize--) | Gets the field to search messages by size, in bytes. |
| [getOnlyFoldersCreatedByUser()](#getOnlyFoldersCreatedByUser--) | Gets the field to search only the folders created by the user, leaving out the standard Outlook folders. |
| [getQuery()](#getQuery--) | Gets the query. |
| [getSentDate()](#getSentDate--) | Gets the field that allows to find messages by sent date. |
| [getSubject()](#getSubject--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [getText()](#getText--) | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [getTo()](#getTo--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |
| [getUnreadContentsCount()](#getUnreadContentsCount--) | Gets the field to search folders by the number of unread items they contain. |
| [hasFlags(long flags)](#hasFlags-long-) | Adds a condition that finds messages with the specified flags set. |
| [hasNoFlags(long flags)](#hasNoFlags-long-) | Adds a condition that finds messages with the specified flags not set. |
| [hasNoSubfolders()](#hasNoSubfolders--) | Adds a condition that finds folders without subfolders. |
| [hasSubfolders()](#hasSubfolders--) | Adds a condition that finds folders with subfolders. |
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


Adds a condition that finds the messages of the same conversation as the specified message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relatedMessage | [MessageInfo](../../com.aspose.email/messageinfo) | A message of the conversation. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - The query for the conversation, or  null  if  relatedMessage  has no conversation index or topic.
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
### getContainerClass() {#getContainerClass--}
```
public final StringComparisonField getContainerClass()
```


Gets the field to search folders by container class.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents a container class.
### getContentsCount() {#getContentsCount--}
```
public final IntComparisonField getContentsCount()
```


Gets the field to search folders by the number of items they contain.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getDefaultEncoding() {#getDefaultEncoding--}
```
public final Charset getDefaultEncoding()
```


Gets default encoding (charset) for query builder.

**Returns:**
java.nio.charset.Charset
### getFolderName() {#getFolderName--}
```
public final StringComparisonField getFolderName()
```


Gets the field to search folders by name.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getFrom() {#getFrom--}
```
public final StringComparisonField getFrom()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents from search field.
### getImportance() {#getImportance--}
```
public final IntComparisonField getImportance()
```


Gets the field to search messages by importance.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getInternalDate() {#getInternalDate--}
```
public final DateComparisonField getInternalDate()
```


Gets the field that allows to find messages by internal date.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield) - The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents internal date search field.
### getMessageClass() {#getMessageClass--}
```
public final StringComparisonField getMessageClass()
```


Gets the field to search messages by message class.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents a message class.
### getMessageId() {#getMessageId--}
```
public final StringComparisonField getMessageId()
```


Gets the field to search messages by the Message-ID header.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield) - The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents the Message-ID search field.
### getMessageSize() {#getMessageSize--}
```
public final IntComparisonField getMessageSize()
```


Gets the field to search messages by size, in bytes.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getOnlyFoldersCreatedByUser() {#getOnlyFoldersCreatedByUser--}
```
public final BoolComparisonField getOnlyFoldersCreatedByUser()
```


Gets the field to search only the folders created by the user, leaving out the standard Outlook folders.

**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield) - The [BoolComparisonField](../../com.aspose.email/boolcomparisonfield) that represents the search field.
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
### getUnreadContentsCount() {#getUnreadContentsCount--}
```
public final IntComparisonField getUnreadContentsCount()
```


Gets the field to search folders by the number of unread items they contain.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### hasFlags(long flags) {#hasFlags-long-}
```
public final MailQuery hasFlags(long flags)
```


Adds a condition that finds messages with the specified flags set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The flags, for example  MapiMessageFlags.MSGFLAG\_READ . |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - The query for this condition.
### hasNoFlags(long flags) {#hasNoFlags-long-}
```
public final MailQuery hasNoFlags(long flags)
```


Adds a condition that finds messages with the specified flags not set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The flags, for example  MapiMessageFlags.MSGFLAG\_READ  to find unread messages. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - The query for this condition.
### hasNoSubfolders() {#hasNoSubfolders--}
```
public final MailQuery hasNoSubfolders()
```


Adds a condition that finds folders without subfolders.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - The query for this condition.
### hasSubfolders() {#hasSubfolders--}
```
public final MailQuery hasSubfolders()
```


Adds a condition that finds folders with subfolders.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - The query for this condition.
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

