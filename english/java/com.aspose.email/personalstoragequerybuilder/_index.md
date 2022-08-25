---
title: PersonalStorageQueryBuilder
second_title: Aspose.Email for Java API Reference
description:  Represents the builder of search expression
 that used by pst.
type: docs
weight: 554
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
| [getOnlyFoldersCreatedByUser()](#getOnlyFoldersCreatedByUser--) | Gets folders that created by user, i.e. |
| [getMessageId()](#getMessageId--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's MessageId field. |
| [getMessageClass()](#getMessageClass--) | Gets messages with an specified message class. |
| [getMessageSize()](#getMessageSize--) | Search messages with an specified size. |
| [getImportance()](#getImportance--) | Search messages with an specified importance. |
| [getContainerClass()](#getContainerClass--) | Gets folders with an specified message class. |
| [getFolderName()](#getFolderName--) | Search folders with an specified display name. |
| [getContentsCount()](#getContentsCount--) | Search folders with an specified contents count. |
| [getUnreadContentsCount()](#getUnreadContentsCount--) | Search folders with an specified unread contents count. |
| [findConversationThread(MessageInfo relatedMessage)](#findConversationThread-com.aspose.email.MessageInfo-) | Finds the conversation thread. |
| [hasFlags(long flags)](#hasFlags-long-) | Search messages with the specified flags. |
| [hasNoFlags(long flags)](#hasNoFlags-long-) | Search messages with the unspecified flags. |
| [hasSubfolders()](#hasSubfolders--) | Search folders which contains subfolders. |
| [hasNoSubfolders()](#hasNoSubfolders--) | Search folders which does not contains subfolders. |
### PersonalStorageQueryBuilder() {#PersonalStorageQueryBuilder--}
```
public PersonalStorageQueryBuilder()
```


Initializes a new instance of the [PersonalStorageQueryBuilder](../../com.aspose.email/personalstoragequerybuilder) class.

### getOnlyFoldersCreatedByUser() {#getOnlyFoldersCreatedByUser--}
```
public final BoolComparisonField getOnlyFoldersCreatedByUser()
```


Gets folders that created by user, i.e. excludes all standard IPM folders.

Value: The[BoolComparisonField](../../com.aspose.email/boolcomparisonfield) that represents search field.

**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### getMessageId() {#getMessageId--}
```
public final StringComparisonField getMessageId()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's MessageId field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents MessageId search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getMessageClass() {#getMessageClass--}
```
public final StringComparisonField getMessageClass()
```


Gets messages with an specified message class.

Value: The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents a message class.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getMessageSize() {#getMessageSize--}
```
public final IntComparisonField getMessageSize()
```


Search messages with an specified size.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getImportance() {#getImportance--}
```
public final IntComparisonField getImportance()
```


Search messages with an specified importance.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getContainerClass() {#getContainerClass--}
```
public final StringComparisonField getContainerClass()
```


Gets folders with an specified message class.

Value: The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents a container class.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getFolderName() {#getFolderName--}
```
public final StringComparisonField getFolderName()
```


Search folders with an specified display name.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getContentsCount() {#getContentsCount--}
```
public final IntComparisonField getContentsCount()
```


Search folders with an specified contents count.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getUnreadContentsCount() {#getUnreadContentsCount--}
```
public final IntComparisonField getUnreadContentsCount()
```


Search folders with an specified unread contents count.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
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
### hasSubfolders() {#hasSubfolders--}
```
public final MailQuery hasSubfolders()
```


Search folders which contains subfolders.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasNoSubfolders() {#hasNoSubfolders--}
```
public final MailQuery hasNoSubfolders()
```


Search folders which does not contains subfolders.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
