---
title: MailQuery
second_title: Aspose.Email for Android via Java API 参考
description: 表示用于匹配邮箱中多个邮件属性的搜索条件。
type: docs
weight: 196
url: /zh/androidjava/com.aspose.email/mailquery/
---

**Inheritance:**
java.lang.Object
```
public class MailQuery
```

表示用于匹配邮箱中多个邮件属性的搜索条件。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MailQuery(String queryString)](#MailQuery-java.lang.String-) | 初始化 [MailQuery](../../com.aspose.email/mailquery) 类的新实例。 |
| [MailQuery(String queryString, String orderByString)](#MailQuery-java.lang.String-java.lang.String-) | 初始化 [MailQuery](../../com.aspose.email/mailquery) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(MailQuery other)](#equals-com.aspose.email.MailQuery-) | 指示当前对象是否等于同类型的另一个对象。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的对象是否等于此实例。 |
| [getClass()](#getClass--) |  |
| [getOrderByString()](#getOrderByString--) | 排序查询字符串。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回表示此实例的 String。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailQuery(String queryString) {#MailQuery-java.lang.String-}
```
public MailQuery(String queryString)
```


初始化 [MailQuery](../../com.aspose.email/mailquery) 类的新实例。

--------------------

> ```
> MailQuery mailQuery = new MailQuery("(('From' Contains 'test@test.com' | 'Seen' = 'True') & 'SentDate' >= '12-May-2010')");
> ```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | queryString | java.lang.String | 查询字符串。 |

--------------------

查询字符串应具有以下视图。

简单表达式的示例：

'<Field name>' <Comparison operator> '<Field value>',

其中 <Field Name> - 用于过滤的邮件字段名称，<Comparison operator> - 比较运算符，顾名思义，用于比较邮件字段和指定的值，<Field value> - 与邮件字段进行比较的值。

多个简单表达式可以组合成复合表达式，例如：(<Simple expression 1> & <Simple expression 2>) | <Simple expression 3>，

其中 '&' - 逻辑与（AND）运算符，'|' - 逻辑或（OR）运算符

目前允许以下值作为字段名称（<Field name>）：

'To' - 表示消息的收件人（TO）字段，'Text' - 表示消息头部或正文中的字符串，'Bcc' - 表示消息的密送（BCC）字段，'Body' - 表示消息正文中的字符串，'Cc' - 表示消息的抄送（CC）字段，'From' - 表示消息的发件人字段，'Subject' - 表示消息主题中的字符串，'InternalDate' - 表示消息的内部日期，'SentDate' - 表示消息的发送日期

此外，IMAP 协议允许以下字段名称：

'Answered' - 表示消息的 /Answered 标志，'Seen' - 表示消息的 /Seen 标志，'Flagged' - 表示消息的 /Flagged 标志，'Draft' - 表示消息的 /Draft 标志，'Deleted' - 表示消息的 Deleted/ 标志，'Recent' - 表示消息的 Deleted/ 标志，'MessageSize' - 表示消息的大小（字节）

此外，Exchange 允许以下字段名称：

'IsRead' - 表示消息是否已被读取，'HasAttachment' - 表示消息是否有附件，'IsSubmitted' - 表示消息是否已提交到发件箱，'ContentClass' - 表示项目的内容类

此外，pst/ost 文件允许以下字段名称：

'MessageClass' - 表示消息类，'ContainerClass' - 表示文件夹容器类，'Importance' - 表示消息的重要性，'MessageSize' - 表示消息的大小（字节），'FolderName' - 表示文件夹名称，'ContentsCount' - 表示文件夹中项目的总数，'UnreadContentsCount' - 表示文件夹中未读项目的数量。'Subfolders' - 表示文件夹是否有子文件夹，'Read' - 表示消息已标记为已读，'HasAttachment' - 表示消息至少有一个附件，'Unsent' - 表示消息仍在撰写中，'Unmodified' - 表示自首次保存（如果未发送）或已发送后（如果已发送）以来消息未被修改，'FromMe' - 接收消息的用户也是发送该消息的用户，'Resend' - 消息包含请求重新发送的操作及未送达报告，'NotifyRead' - 发送者请求在收件人首次阅读时收到通知，'NotifyUnread' - 发送者请求在收件人在阅读前删除或消息对象过期时收到通知，'EverRead' - 消息至少被读取过一次

字段值（<Field value>）可以取以下值：文本字段 - 任意字符串，日期类型字段 - 'd-MMM-yyy' 格式的字符串，例如 '10-Feb-2009'，布尔标志字段 - 'True' 或 'False' |

### MailQuery(String queryString, String orderByString) {#MailQuery-java.lang.String-java.lang.String-}
```
public MailQuery(String queryString, String orderByString)
```


初始化 [MailQuery](../../com.aspose.email/mailquery) 类的新实例。

--------------------

> ```
> MailQuery mailQuery = new MailQuery("", "(('From' OrderBy 'ASC') & ('SentDate' OrderBy 'DESC'))");
> ```

--------------------

排序查询字符串应具有以下视图。

简单表达式的示例：

'<Field name>' OrderBy ['ASC'|'DESC'],

where <Field Name> - 用于排序的消息字段名称, ['ASC'|'DESC'] - 排序运算符, 允许升序或降序,

多个简单表达式可以组合成一个复合表达式，例如: (<Simple expression 1> & <Simple expression 2>),

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| queryString | java.lang.String |  |
| orderByString | java.lang.String |  |

### equals(MailQuery other) {#equals-com.aspose.email.MailQuery-}
```
public final boolean equals(MailQuery other)
```


指示当前对象是否等于同类型的另一个对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [MailQuery](../../com.aspose.email/mailquery) | 用于与此对象比较的对象。 |

**Returns:**
boolean - 如果当前对象等于 other 参数则为 true；否则为 false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的对象是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 Object。 |

**Returns:**
boolean - 如果指定的 Object 等于此实例则为 true；否则为 false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOrderByString() {#getOrderByString--}
```
public final String getOrderByString()
```


排序查询字符串。

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


返回表示此实例的 String。

**Returns:**
java.lang.String - 表示此实例的查询字符串。
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

