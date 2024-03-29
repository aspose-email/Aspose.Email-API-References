---
title: ExchangeQueryBuilder
second_title: Aspose.Email for .NET API 参考
description: 表示基于 Exchange 协议使用的搜索过滤器的搜索表达式 的构建器
type: docs
weight: 3440
url: /zh/net/aspose.email.clients.exchange/exchangequerybuilder/
---
## ExchangeQueryBuilder class

表示基于 Exchange 协议使用的搜索过滤器的搜索表达式 的构建器。

```csharp
public sealed class ExchangeQueryBuilder : MailQueryBuilder
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ExchangeQueryBuilder](exchangequerybuilder)() | 初始化[`ExchangeQueryBuilder`](../exchangequerybuilder)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Appointment](../../aspose.email.clients.exchange/exchangequerybuilder/appointment) { get; } | 获取具有约会属性的对象以创建查询 |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | 获取允许在信封结构的密件抄送字段中查找包含指定字符串的消息的字段。 |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | 获取允许在消息正文中查找包含指定字符串的消息的字段。 |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | 获取允许在信封结构的 CC 字段中查找包含指定字符串的消息的字段。 |
| [Contact](../../aspose.email.clients.exchange/exchangequerybuilder/contact) { get; } | 获取具有联系人属性的对象以创建查询 |
| [ContentClass](../../aspose.email.clients.exchange/exchangequerybuilder/contentclass) { get; } | 获取具有指定内容类的项目。 |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | 获取查询 builder 的默认编码（字符集） |
| [ExtendedProperties](../../aspose.email.clients.exchange/exchangequerybuilder/extendedproperties) { get; } | 获取带有属性描述符对和比较字段的字典，以按扩展属性进行搜索。 |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | 获取允许在信封结构的 FROM 字段中查找包含指定字符串的消息的字段。 |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | 获取允许按内部日期查找消息的字段。 |
| [ItemSize](../../aspose.email.clients.exchange/exchangequerybuilder/itemsize) { get; } | 获取允许查找具有指定大小的项目的字段。 |
| [MessageId](../../aspose.email.clients.exchange/exchangequerybuilder/messageid) { get; } | 获取允许在信封结构的 MessageId 字段中查找包含指定字符串的消息的字段。 |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | 获取允许按发送日期查找消息的字段。 |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | 获取允许在信封结构的 SUBJECT 字段中查找包含指定字符串的消息的字段。 |
| [TaskStatus](../../aspose.email.clients.exchange/exchangequerybuilder/taskstatus) { get; } | 获取允许查找包含指定状态的任务的字段。 服务器兼容性：Exchange 2010 和更高版本 |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | 获取允许在邮件的标题（主题、发件人、收件人、抄送）和正文中查找包含指定字符串的邮件的字段。 |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | 获取允许在信封结构的 TO 字段中查找包含指定字符串的消息的字段。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | 获取查询。 |
| [HasFlags](../../aspose.email.clients.exchange/exchangequerybuilder/hasflags)(ExchangeMessageFlag) | 搜索带有指定标志的消息。 |
| [HasNoFlags](../../aspose.email.clients.exchange/exchangequerybuilder/hasnoflags)(ExchangeMessageFlag) | 搜索带有未指定标志的邮件。 |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | 搜索与任一搜索键匹配的消息。提供两个表达式之间的析取 (OR). |

### 也可以看看

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* 命名空间 [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
