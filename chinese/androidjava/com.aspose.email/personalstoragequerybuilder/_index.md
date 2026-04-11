---
title: PersonalStorageQueryBuilder
second_title: Aspose.Email for Android via Java API 参考
description: 表示由 PST 使用的搜索表达式构建器。
type: docs
weight: 346
url: /zh/androidjava/com.aspose.email/personalstoragequerybuilder/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailQueryBuilder](../../com.aspose.email/mailquerybuilder)
```
public final class PersonalStorageQueryBuilder extends MailQueryBuilder
```

表示由 PST 使用的搜索表达式构建器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PersonalStorageQueryBuilder()](#PersonalStorageQueryBuilder--) | 初始化一个新的 [PersonalStorageQueryBuilder](../../com.aspose.email/personalstoragequerybuilder) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findConversationThread(MessageInfo relatedMessage)](#findConversationThread-com.aspose.email.MessageInfo-) | 查找会话线程。 |
| [getBcc()](#getBcc--) | 获取允许在信封结构的 BCC 字段中查找包含指定字符串的邮件的字段。 |
| [getBody()](#getBody--) | 获取允许在邮件正文中查找包含指定字符串的邮件的字段。 |
| [getCc()](#getCc--) | 获取允许在信封结构的 CC 字段中查找包含指定字符串的邮件的字段。 |
| [getClass()](#getClass--) |  |
| [getContainerClass()](#getContainerClass--) | 获取具有指定消息类的文件夹。 |
| [getContentsCount()](#getContentsCount--) | 搜索具有指定内容计数的文件夹。 |
| [getDefaultEncoding()](#getDefaultEncoding--) | 获取查询构建器的默认编码（字符集）。 |
| [getFolderName()](#getFolderName--) | 搜索具有指定显示名称的文件夹。 |
| [getFrom()](#getFrom--) | 获取允许在信封结构的 FROM 字段中查找包含指定字符串的邮件的字段。 |
| [getImportance()](#getImportance--) | 搜索具有指定重要性的邮件。 |
| [getInternalDate()](#getInternalDate--) | 获取允许按内部日期查找邮件的字段。 |
| [getMessageClass()](#getMessageClass--) | 获取具有指定消息类的邮件。 |
| [getMessageId()](#getMessageId--) | 获取允许在信封结构的 MessageId 字段中查找包含指定字符串的邮件的字段。 |
| [getMessageSize()](#getMessageSize--) | 搜索具有指定大小的邮件。 |
| [getOnlyFoldersCreatedByUser()](#getOnlyFoldersCreatedByUser--) | 获取用户创建的文件夹，例如。 |
| [getQuery()](#getQuery--) | 获取查询。 |
| [getSentDate()](#getSentDate--) | 获取允许按发送日期查找邮件的字段。 |
| [getSubject()](#getSubject--) | 获取允许在信封结构的 SUBJECT 字段中包含指定字符串的邮件的字段。 |
| [getText()](#getText--) | 获取允许在邮件的标题（subject、from、to、cc）和正文中包含指定字符串的邮件的字段。 |
| [getTo()](#getTo--) | 获取允许在信封结构的 TO 字段中包含指定字符串的邮件的字段。 |
| [getUnreadContentsCount()](#getUnreadContentsCount--) | 搜索具有指定未读内容计数的文件夹。 |
| [hasFlags(long flags)](#hasFlags-long-) | 搜索具有指定标志的邮件。 |
| [hasNoFlags(long flags)](#hasNoFlags-long-) | 搜索具有未指定标志的邮件。 |
| [hasNoSubfolders()](#hasNoSubfolders--) | 搜索不包含子文件夹的文件夹。 |
| [hasSubfolders()](#hasSubfolders--) | 搜索包含子文件夹的文件夹。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [or(MailQuery query1, MailQuery query2)](#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-) | 搜索匹配任一搜索键的邮件。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PersonalStorageQueryBuilder() {#PersonalStorageQueryBuilder--}
```
public PersonalStorageQueryBuilder()
```


初始化一个新的 [PersonalStorageQueryBuilder](../../com.aspose.email/personalstoragequerybuilder) 类实例。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findConversationThread(MessageInfo relatedMessage) {#findConversationThread-com.aspose.email.MessageInfo-}
```
public final MailQuery findConversationThread(MessageInfo relatedMessage)
```


查找会话线程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| relatedMessage | [MessageInfo](../../com.aspose.email/messageinfo) | 相关的消息。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - 
### getBcc() {#getBcc--}
```
public final StringComparisonField getBcc()
```


获取允许在信封结构的 BCC 字段中查找包含指定字符串的邮件的字段。

值：表示 BCC 搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getBody() {#getBody--}
```
public final StringComparisonField getBody()
```


获取允许在邮件正文中查找包含指定字符串的邮件的字段。

值：表示正文搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getCc() {#getCc--}
```
public final StringComparisonField getCc()
```


获取允许在信封结构的 CC 字段中查找包含指定字符串的邮件的字段。

值：表示 cc 搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

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


获取具有指定消息类的文件夹。

值：表示容器类的 [StringComparisonField](../../com.aspose.email/stringcomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getContentsCount() {#getContentsCount--}
```
public final IntComparisonField getContentsCount()
```


搜索具有指定内容计数的文件夹。

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getDefaultEncoding() {#getDefaultEncoding--}
```
public final Charset getDefaultEncoding()
```


获取查询构建器的默认编码（字符集）。

**Returns:**
java.nio.charset.Charset
### getFolderName() {#getFolderName--}
```
public final StringComparisonField getFolderName()
```


搜索具有指定显示名称的文件夹。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getFrom() {#getFrom--}
```
public final StringComparisonField getFrom()
```


获取允许在信封结构的 FROM 字段中查找包含指定字符串的邮件的字段。

值：表示 from 搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getImportance() {#getImportance--}
```
public final IntComparisonField getImportance()
```


搜索具有指定重要性的邮件。

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getInternalDate() {#getInternalDate--}
```
public final DateComparisonField getInternalDate()
```


获取允许按内部日期查找邮件的字段。

值：表示内部日期搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getMessageClass() {#getMessageClass--}
```
public final StringComparisonField getMessageClass()
```


获取具有指定消息类的邮件。

值：表示消息类的 [StringComparisonField](../../com.aspose.email/stringcomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getMessageId() {#getMessageId--}
```
public final StringComparisonField getMessageId()
```


获取允许在信封结构的 MessageId 字段中查找包含指定字符串的邮件的字段。

值：表示 MessageId 搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getMessageSize() {#getMessageSize--}
```
public final IntComparisonField getMessageSize()
```


搜索具有指定大小的邮件。

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getOnlyFoldersCreatedByUser() {#getOnlyFoldersCreatedByUser--}
```
public final BoolComparisonField getOnlyFoldersCreatedByUser()
```


获取用户创建的文件夹，即排除所有标准 IPM 文件夹。

值：表示搜索字段的 The[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)。

**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### getQuery() {#getQuery--}
```
public MailQuery getQuery()
```


获取查询。

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query.
### getSentDate() {#getSentDate--}
```
public final DateComparisonField getSentDate()
```


获取允许按发送日期查找邮件的字段。

值：表示发送日期搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getSubject() {#getSubject--}
```
public final StringComparisonField getSubject()
```


获取允许在信封结构的 SUBJECT 字段中包含指定字符串的邮件的字段。

值：表示主题搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getText() {#getText--}
```
public final StringComparisonField getText()
```


获取允许在邮件的标题（subject、from、to、cc）和正文中包含指定字符串的邮件的字段。

值：表示文本标题或正文搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getTo() {#getTo--}
```
public final StringComparisonField getTo()
```


获取允许在信封结构的 TO 字段中包含指定字符串的邮件的字段。

值：表示 TO 搜索字段的 [DateComparisonField](../../com.aspose.email/datecomparisonfield)。

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getUnreadContentsCount() {#getUnreadContentsCount--}
```
public final IntComparisonField getUnreadContentsCount()
```


搜索具有指定未读内容计数的文件夹。

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### hasFlags(long flags) {#hasFlags-long-}
```
public final MailQuery hasFlags(long flags)
```


搜索具有指定标志的邮件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flags | long | 标志。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasNoFlags(long flags) {#hasNoFlags-long-}
```
public final MailQuery hasNoFlags(long flags)
```


搜索具有未指定标志的邮件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flags | long | 标志。 |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasNoSubfolders() {#hasNoSubfolders--}
```
public final MailQuery hasNoSubfolders()
```


搜索不包含子文件夹的文件夹。

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasSubfolders() {#hasSubfolders--}
```
public final MailQuery hasSubfolders()
```


搜索包含子文件夹的文件夹。

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


搜索匹配任一搜索键的邮件。提供两个表达式之间的析取（OR）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| query1 | [MailQuery](../../com.aspose.email/mailquery) | 查询1。 |
| query2 | [MailQuery](../../com.aspose.email/mailquery) | 查询2。 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

