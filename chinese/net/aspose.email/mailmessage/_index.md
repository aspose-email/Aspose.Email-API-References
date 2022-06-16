---
title: MailMessage
second_title: Aspose.Email for .NET API 参考
description: 表示电子邮件它允许访问消息属性 ex主题正文发件人和收件人地址等 也可以通过支持的邮件协议发送和投递
type: docs
weight: 17710
url: /zh/net/aspose.email/mailmessage/
---
## MailMessage class

表示电子邮件。它允许访问消息属性， ex。主题、正文、发件人和收件人地址等 也可以通过支持的邮件协议发送和投递。

```csharp
public class MailMessage : IDisposable, IEnumerable<MailMessage>, IMessage, 
    IPreferredTextEncodingProvider, ISerializable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MailMessage](mailmessage#constructor)() | 初始化[`MailMessage`](../mailmessage)类的新实例 |
| [MailMessage](mailmessage#constructor_2)(bool) | 初始化[`MailMessage`](../mailmessage)类的新实例 |
| [MailMessage](mailmessage#constructor_1)(MailAddress, MailAddress) | 初始化[`MailMessage`](../mailmessage)类的新实例 |
| [MailMessage](mailmessage#constructor_3)(string, string) | 初始化[`MailMessage`](../mailmessage)类的新实例 |
| [MailMessage](mailmessage#constructor_4)(string, string, string, string) | 初始化[`MailMessage`](../mailmessage)类的新实例 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews) { get; } | 获取消息的备用视图集合 |
| virtual [Attachments](../../aspose.email/mailmessage/attachments) { get; } | 获取消息的附件集合 |
| virtual [Bcc](../../aspose.email/mailmessage/bcc) { get; set; } | 获取或设置地址集合 包含消息的密件抄送收件人 |
| virtual [Body](../../aspose.email/mailmessage/body) { get; set; } | 获取或设置消息正文的纯文本表示。 如果消息中存在 text/plain 部分，则属性返回其文本数据。 否则，属性返回不带 html 标记的 HtmlBody 属性的文本内容。 |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding) { get; set; } | 获取或设置正文的编码 |
| [BodyType](../../aspose.email/mailmessage/bodytype) { get; } | 获取正文的类型。 |
| virtual [CC](../../aspose.email/mailmessage/cc) { get; set; } | 获取或设置地址集合 包含抄送收件人 |
| virtual [Date](../../aspose.email/mailmessage/date) { get; set; } | 获取或设置消息日期 |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions) { get; set; } | 获取或设置发送通知 |
| [Epilogue](../../aspose.email/mailmessage/epilogue) { get; set; } | 获取或设置结尾文本。 它位于最后一个边界之后。 |
| virtual [From](../../aspose.email/mailmessage/from) { get; set; } | 获取或设置发件人地址 |
| virtual [Headers](../../aspose.email/mailmessage/headers) { get; } | 获取消息的标头集合 |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody) { get; set; } | 获取或设置 html 正文 |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml) { get; set; } | 获取或设置一个值，该值指示 消息体是否为 Html |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft) { get; set; } | 获取或设置指示是否已发送消息的值。 |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted) { get; } | 获取表示消息是否加密的值。 |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly) { get; } | 获取一个值，该值指示 消息是否为只读 |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned) { get; } | 获取一个值，该值指示消息是否已签名。 |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources) { get; } | 获取消息链接资源的集合 |
| virtual [MessageId](../../aspose.email/mailmessage/messageid) { get; set; } | 获取或设置消息ID |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef) { get; } | 获取表示 原始 EML 消息是否为 TNEF 格式的值。 |
| [Preamble](../../aspose.email/mailmessage/preamble) { get; set; } | 获取或设置前导文本。 它位于第一个边界 之前，通常包括对不符合 MIME 的读者的解释性说明。 |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding) { get; set; } | 获取或设置所有文本属性的首选编码 |
| virtual [Priority](../../aspose.email/mailmessage/priority) { get; set; } | 获取或设置消息的优先级 |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto) { get; set; } | 获取或设置已读回执地址。 |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist) { get; set; } | 获取或设置地址列表 回复邮件消息 |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath) { get; set; } | 获取或设置 ReversePath 地址 |
| virtual [Sender](../../aspose.email/mailmessage/sender) { get; set; } | 获取或设置发送者地址 |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity) { get; set; } | 获取或设置消息的敏感度 |
| virtual [Subject](../../aspose.email/mailmessage/subject) { get; set; } | 获取或设置主题行 |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding) { get; set; } | 获取或设置主题的编码 |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset) { get; set; } | 获取或设置协调世界时 (UTC) 消息日期的偏移量。 此属性定义本地时间和 UTC 之间的时区差异 。 |
| virtual [To](../../aspose.email/mailmessage/to) { get; set; } | 获取或设置包含 消息接收者的地址集合 |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer) { get; set; } | 获取或设置 X-Mailer 软件 创建电子邮件 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Load](../../aspose.email/mailmessage/load#load)(Stream) | 从流中加载消息 |
| static [Load](../../aspose.email/mailmessage/load#load_2)(string) | 从文件加载消息 |
| static [Load](../../aspose.email/mailmessage/load#load_1)(Stream, LoadOptions) | 使用附加选项从流中加载消息。 |
| static [Load](../../aspose.email/mailmessage/load#load_3)(string, LoadOptions) | 使用附加选项从文件加载消息。 |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview)(AlternateView) | 向消息添加替代视图 |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment)(Attachment) | 添加邮件附件 |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature)(CmsSigner) | 创建签名消息。 创建指定 MailMessage 的只读副本并为其添加数字签名。 |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_2)(X509Certificate2) | 创建签名消息。 创建指定 MailMessage 的只读副本并为其添加数字签名。 |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_1)(CmsSigner, bool) | 创建签名消息。 创建指定 MailMessage 的只读副本并为其添加数字签名。 |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_3)(X509Certificate2, bool) | 创建签名消息。 创建指定 MailMessage 的只读副本并为其添加数字签名。 |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced)() | 检查是否可以将此邮件视为退回邮件。 |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature)() | 检查签名存在的 MailMessage。 |
| virtual [Clone](../../aspose.email/mailmessage/clone)() | 克隆此实例 |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt)(string, string) | 创建已读回执。 |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt#decrypt)() | 解密此消息 |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt#decrypt_1)(X509Certificate2) | 解密此消息 |
| [Dispose](../../aspose.email/mailmessage/dispose)() | 释放 MailMessage 使用的所有资源 |
| virtual [DKIMSign](../../aspose.email/mailmessage/dkimsign)(RSACryptoServiceProvider, DKIMSignatureInfo) | 使用 DKIM（域密钥识别邮件）签名对此邮件进行签名。 |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt#encrypt)(X509Certificate2) | 加密此消息 |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt#encrypt_1)(X509Certificate2[]) | 加密此消息 |
| override [Equals](../../aspose.email/mailmessage/equals)(object) | 判断指定Object是否等于当前Object。 |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator)() | 返回遍历集合的枚举数。 |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode)() | 返回对象的哈希码 |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext#gethtmlbodytext_1)(bool) | 以纯文本形式获取消息 html 正文。此方法解析 HtmlBody 属性并返回忽略 html 标记的纯文本内容。 |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext#gethtmlbodytext)(HyperlinkRenderingCallback) | 以纯文本形式获取消息 htmlbody。 |
| virtual [GetObjectData](../../aspose.email/mailmessage/getobjectdata)(SerializationInfo, StreamingContext) | 使用序列化目标对象所需的数据填充SerializationInfo。 |
| virtual [Import](../../aspose.email/mailmessage/import)(Stream) | 从流中导入消息 |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent)() | 组成 TNEF 内容。 注意，如果消息最初包含 TNEF 并且在没有 FileCompatibilityMode.PreserveTnefAttachments 标志的情况下加载，则该 tnef 附件是组成的， 即此方法不从常规消息中创建 tnef 消息。 |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature)() | 删除签名 |
| virtual [Save](../../aspose.email/mailmessage/save#save)(Stream) | 将消息保存为流 |
| virtual [Save](../../aspose.email/mailmessage/save#save_2)(string) | 将消息保存为文件 |
| virtual [Save](../../aspose.email/mailmessage/save#save_1)(Stream, SaveOptions) | 将消息保存为带有附加选项的流。 |
| virtual [Save](../../aspose.email/mailmessage/save#save_3)(string, SaveOptions) | 将消息保存为带有附加选项的文件。 |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody)(string, bool) | 设置 html 正文。 |
| override [ToString](../../aspose.email/mailmessage/tostring)() | 返回代表当前对象的字符串。 |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature#checksignature)(Stream) | 检查指定 eml 消息的签名。 |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature#checksignature_1)(string) | 检查指定 eml 文件的签名。 |
| static [ValidateMessage](../../aspose.email/mailmessage/validatemessage#validatemessage)(Stream) | 验证 eml 消息是否符合 mime 规范。 |
| static [ValidateMessage](../../aspose.email/mailmessage/validatemessage#validatemessage_1)(string) | 验证 eml 消息是否符合 mime 规范。 |

### 也可以看看

* interface [IMessage](../imessage)
* interface [IPreferredTextEncodingProvider](../ipreferredtextencodingprovider)
* 命名空间 [Aspose.Email](../../aspose.email)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
