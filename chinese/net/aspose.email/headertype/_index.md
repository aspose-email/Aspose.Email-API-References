---
title: HeaderType
second_title: Aspose.Email for .NET API 参考
description: 代表 Internet 标准RFC 定义了 Internet 邮件消息中可能出现的标头字段
type: docs
weight: 17510
url: /zh/net/aspose.email/headertype/
---
## HeaderType class

代表 Internet 标准，RFC 定义了 Internet 邮件消息中可能出现的标头字段。

```csharp
public sealed class HeaderType
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [ApparentlyTo](../../aspose.email/headertype/apparentlyto) { get; } | 当原始消息中没有“To:”收件人时，通过发送电子邮件插入。这会导致从信封派生的收件人列在邮件标题中。 这种行为不太恰当，MTA 不应该修改标题（插入 Received 行除外），并且在某些情况下会导致密件抄送收件人被错误地泄露给非密件抄送收件人。 示例: 显然-To:someone@somedomain.com 不鼓励使用的非标准标头，提到在 RFC1211 中。 |
| static [ApprovedBy](../../aspose.email/headertype/approvedby) { get; } | 邮件发送到的邮件列表的版主名称；必须在发送到主持邮件列表的帖子中才能将其分发给列表成员。 示例: 批准人:someone@somedomain.com 非标准用于电子邮件。在 RFC1036 中定义。 |
| static [Bcc](../../aspose.email/headertype/bcc) { get; } | 在主要收件人不知情的情况下发送给一个或多个收件人的电子邮件副本。 主要收件人列在 To:和 Cc:行中。如果您想将消息复制给许多人，而每个人都看不到其他收件人是谁，这很有用。 如果您在收到的邮件中看到此标头，则说明有问题，因为它没有出现在标头中。 |
| static [CC](../../aspose.email/headertype/cc) { get; } | 该标头可以被认为是“To:”字段的扩展，因为它用于指定其他收件人。 在这种情况下，发送给收件人的电子邮件消息的副本会在消息中显示收件人的地址。 如果您想将一条消息复制给许多人，每个人都可以看到其他收件人是谁，这很有用；与上面的密件抄送形成对比。 这个标题确实出现在收到的电子邮件中。 示例: 抄送:gboyd@netcom.com |
| static [Comments](../../aspose.email/headertype/comments) { get; } | 这是 RFC2822 中定义的自由格式头字段。 标头用于将说明性文本放入电子邮件的标头部分。 该字段可能包含任意文本。 示例: 评论:经过身份验证的发件人是某人@somedonmain.com。 |
| static [ContentTransferEncoding](../../aspose.email/headertype/contenttransferencoding) { get; } | MIME 相关标头的第三个。指示 MIME 消息正文中使用的编码方法。 它与电子邮件的传递没有直接关系，但它会影响符合 MIME 的邮件程序如何解释邮件内容。 在 RFC2045 中定义。 内容传输编码:8bit 内容传输编码:7BIT 内容传输编码:7bit 内容传输编码:base64 内容传输编码:引用打印 |
| static [ContentType](../../aspose.email/headertype/contenttype) { get; } | “Content-Type”定义了内容的格式（字符集等）。请注意，此标头的值在 RFC1049 和 MIME 中以不同的方式定义（ RFC2045）。查找 MIME-version:标头以了解 Content-Type 是根据 RFC1049 还是根据 MIME (RFC2045) 进行解释。 MIME 定义应用于生成邮件。 历史上，内容类型字段是在 RFC1049 中提出的。其中，Content-Type 没有像 RFC2045 那样区分类型和子类型。 示例: Content-Type:text/plain; charset="us-ascii" 内容类型:文本/纯文本； charset=US-ASCII Content-Type:text/plain; charset="iso-8859-1" Content-Type:text/plain; charset=koi8-r Content-Type:text/plain; charset=unknown-8bit |
| static [Date](../../aspose.email/headertype/date) { get; } | 此标头指定日期（和时间），通常是撰写和发送消息的日期。在 X.400 邮件系统中，提交邮件的时间。一些 Internet 邮件系统也使用提交邮件的日期。如果发件人的计算机省略了此标头，则可以想象它可能是由邮件服务器添加的，甚至可能是由沿途的其他机器添加的。 您可能不知道的是，“日期:”行中的信息是由发件人计算机上的时间提供的，可能设置正确，也可能设置不正确。此外，“日期:”标头通常不会指示消息的发送时间，而只会指示消息的撰写时间。 日期格式为 3 个字符的星期几（Sun - Sat）、日期编号 (1-31) dd、3 个字符的月份名称、4 个字符的年份 yyyy，后跟时间（24 小时制）hh:mm:ss 和 zone zzz 格式。时区 (zzz) 可以是 3 个字符的时区，也可以是与 UTC（协调世界时 - 旧格林威治标准时间）的当地时差和分时差。 “-”表示西，“+”表示UTC以东。 似乎不存在标准时区定义。许多 UNIX 版本可以理解很多缩写，但我找到的最详尽的列表是 GNU tar 手册 Timezone 项和 Perl 日期操作模块 TIMEZONES 的文档。 示例: 日期:2001 年 1 月 9 日星期二 23:40:00 -0800 日期:4 月 1 日星期日2001 22:52:04 EDT 日期:2001 年 4 月 2 日星期一 16:02:19 +0200 日期:2001 年 3 月 30 日星期五 10:47:15 -0800 |
| static [DispositionNotificationTo](../../aspose.email/headertype/dispositionnotificationto) { get; } | 当设置了 DispositionNotificationTo 字段时，将请求 MDN（消息传递通知）。 收件人的电子邮件软件（Outlook、Eudora 等）可能会默默地忽略该请求，也可能会提示用户允许发送 MDN。 不保证“退货收据”。 DispositionNotificationTo 字段是请求回执（即 MDN，或消息传递通知）的事实标准。 |
| static [FollowupTo](../../aspose.email/headertype/followupto) { get; } | 在 Usenet 新闻中使用，表示未来对一篇文章的讨论（=后续）应该转到与回复文章不同的一组新闻组。 最常见的用法是将一篇文章发布到多个新闻组，而进一步的讨论只在其中一个新闻组中进行。 在 RFC 1036:2.2.3 中定义，未标准化用于电子邮件。 |
| static [From](../../aspose.email/headertype/from) { get; } | 此字段包含希望发送此消息的人的身份。 消息创建过程应默认此字段为单个经过身份验证的机器地址，指示组成消息的代理（人、系统或进程）。 如果不这样做，“发件人:”字段必须存在。如果“发件人:”字段默认采用这种方式，则“发件人:”字段是可选的，并且与“发件人:”字段是多余的。 示例: 来自:“某人先生”someone@somedomain.com |
| static [Importance](../../aspose.email/headertype/importance) { get; } | 获取重要性。 |
| static [InReplyTo](../../aspose.email/headertype/inreplyto) { get; } | 引用此消息作为回复的消息。 |
| static [MessageID](../../aspose.email/headertype/messageid) { get; } | 此消息的唯一 ID。 在 RFC 822:4.6.1 ,RFC 1036:2.1.5 中定义。 |
| static [MIMEVersion](../../aspose.email/headertype/mimeversion) { get; } | 此消息根据 MIME 标准格式化的指示符，以及使用哪个 MIME 版本的指示符。 在 RFC 2045 中定义 |
| static [Newsgroups](../../aspose.email/headertype/newsgroups) { get; } | 在 Usenet 新闻中:本文发布到的组。 一些系统也在电子邮件中提供这个头域，尽管它在那里没有标准化。 不幸的是，标题字段可以在电子邮件中出现，具有三种不同且相互矛盾的含义: (a) 指示发送到这两个电子邮件的文章/消息的新闻组收件人和 Usenet 新闻收件人。 (b) 在发往新闻网关的某些邮件的消息中，指明该消息要发布到的新闻组。 (c) 在对新闻组中一篇文章的个人回复中，指出该讨论起源于哪个新闻组。 在 RFC 1036:2.1.3 中定义，在电子邮件中的使用未标准化且存在争议。 |
| static [Received](../../aspose.email/headertype/received) { get; } | 消息已通过的 MTA 跟踪。 定义在 RFC 822 |
| static [References](../../aspose.email/headertype/references) { get; } | 引用其他相关消息。 |
| static [ReplyTo](../../aspose.email/headertype/replyto) { get; } | 这个标头字段用于指示发件人想要回复的位置。 不幸的是，这是模棱两可的，因为有不同类型的回复，发件人可能希望发送到不同的地址。 特别是，个人回复仅针对一个人，而群组回复针对阅读回复消息的整个群体（通常是邮件列表，新闻组名称不能出现在此处，因为不同的语法，请参阅“FollowupTo”。）。 |
| static [ReturnPath](../../aspose.email/headertype/returnpath) { get; } | 当邮件离开使用“MAIL FROM”的 SMTP 环境时，用于在最终传递中传送来自 MAIL FROM 信封属性的信息。 /// |
| static [ReturnReceiptTo](../../aspose.email/headertype/returnreceiptto) { get; } | 发送者可以通过包含这个头域来请求回执。 回执被发送到电子邮件的 Return-Path 地址，而不是 Return-Receipt-To 标头字段中指定的地址。 此标头是非标准的，并且大多不受支持。 使用 Disposition-Notification-To 代替。 即使支持，也不能保证发送收据。 |
| static [Sender](../../aspose.email/headertype/sender) { get; } | 将消息提交到网络的个人或代理，如果 From:标头字段未显示。应该是认证的，根据RFC 822，但是什么样的认证还不清楚。 |
| static [Sensitivity](../../aspose.email/headertype/sensitivity) { get; } | 获取灵敏度。 |
| static [Subject](../../aspose.email/headertype/subject) { get; } | 标题、标题、主题。通常用作回复或评论其他消息的消息的线程指示器。 |
| static [To](../../aspose.email/headertype/to) { get; } | 主要收件人。 示例: 收件人:someone@somedomain.com |
| static [XConfirmReadingTo](../../aspose.email/headertype/xconfirmreadingto) { get; } | 此标头在收到或阅读消息时请求自动确认通知。它通常被忽略；大概是某些软件对其起作用。 |
| static [XMailer](../../aspose.email/headertype/xmailer) { get; } | 关于发起者客户端软件的信息。 示例: X-Mailer:Aspose.Email |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Equals](../../aspose.email/headertype/equals)(object) | 返回一个布尔值，指示传入的对象 obj 是否等于 this。 |
| override [GetHashCode](../../aspose.email/headertype/gethashcode)() | 用作特定类型的哈希函数。 |
| override [ToString](../../aspose.email/headertype/tostring)() | 返回代表当前Object的String。 |
| [implicit operator](../../aspose.email/headertype/op_implicit) | 执行从[`HeaderType`](../headertype)到String的隐式转换。 |

### 也可以看看

* 命名空间 [Aspose.Email](../../aspose.email)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
