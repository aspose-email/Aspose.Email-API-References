---
title: AmpMessage
second_title: Aspose.Email for Android via Java API 参考
description: 允许发件人在电子邮件中嵌入 AMP 组件的消息。
type: docs
weight: 22
url: /zh/androidjava/com.aspose.email/ampmessage/
---

**Inheritance:**
java.lang.Object, com.aspose.email.IPreferredTextEncodingProviderInternal, [com.aspose.email.MailMessage](../../com.aspose.email/mailmessage)
```
public class AmpMessage extends MailMessage
```

允许发件人在电子邮件中嵌入 AMP 组件的消息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AmpMessage()](#AmpMessage--) | 初始化 [MailMessage](../../com.aspose.email/mailmessage) 类的新实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addAlternateView(AlternateView view)](#addAlternateView-com.aspose.email.AlternateView-) | 向消息添加备用视图 |
| [addAmpComponent(AmpComponent component)](#addAmpComponent-com.aspose.email.AmpComponent-) | 向此消息添加 Amp 组件。 |
| [addAttachment(Attachment attachment)](#addAttachment-com.aspose.email.Attachment-) | 向消息添加附件 |
| [attachSignature(byte[] certificateRawData, String certificatePassword)](#attachSignature-byte---java.lang.String-) | 创建已签名的消息。 |
| [attachSignature(byte[] certificateRawData, String certificatePassword, boolean detached)](#attachSignature-byte---java.lang.String-boolean-) | 创建已签名的消息。 |
| [attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) |  |
| [attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, boolean detached)](#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | 创建已签名的消息。 |
| [checkBounced()](#checkBounced--) | 检查此消息是否可以视为退回消息。 |
| [checkSignature()](#checkSignature--) | 检查已存在的 MailMessage 的签名。 |
| [checkSignature(InputStream stream)](#checkSignature-java.io.InputStream-) | 检查指定 eml 消息的签名。 |
| [checkSignature(String fileName)](#checkSignature-java.lang.String-) | 检查指定 eml 文件的签名。 |
| [checkSignatureCert()](#checkSignatureCert--) | 检查已存在的 MailMessage 的签名。 |
| [close()](#close--) |  |
| [createReadReceipt(String from, String bodyText)](#createReadReceipt-java.lang.String-java.lang.String-) | 创建已读回执。 |
| [dKIMSign(System.Security.Cryptography.RSACryptoServiceProvider rsa, DKIMSignatureInfo signatureInfo)](#dKIMSign-com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider-com.aspose.email.DKIMSignatureInfo-) | 使用 DKIM（DomainKeys Identified Mail）签名对该消息进行签名。 |
| [decrypt()](#decrypt--) | 解密此消息 |
| [decrypt(byte[] certificateRawData, String certificatePassword)](#decrypt-byte---java.lang.String-) | 解密此消息 |
| [decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#decrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) |  |
| [deepClone()](#deepClone--) | 克隆此实例 |
| [dispose()](#dispose--) | 释放 MailMessage 使用的所有资源 |
| [encrypt(byte[] certificateRawData, String certificatePassword)](#encrypt-byte---java.lang.String-) | 加密此消息 |
| [encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) |  |
| [encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2[] certificates)](#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2---) | 加密此消息 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于当前 Object。 |
| [getAlternateViews()](#getAlternateViews--) | 获取消息的备用视图集合 |
| [getAmpHtmlBody()](#getAmpHtmlBody--) | 获取消息正文的 AmpHtml 表示形式。 |
| [getAttachments()](#getAttachments--) | 获取消息的附件集合 |
| [getBcc()](#getBcc--) | 获取或设置包含消息 BCC 收件人的地址集合 |
| [getBody()](#getBody--) | 获取或设置消息正文的纯文本表示。 |
| [getBodyEncoding()](#getBodyEncoding--) | 获取或设置正文的编码 |
| [getBodyType()](#getBodyType--) | 获取正文的类型。 |
| [getCC()](#getCC--) | 获取或设置包含抄送收件人的地址集合 |
| [getCc()](#getCc--) | 获取抄送收件人 |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | 获取或设置消息的日期，指定消息创建者指示消息已完成并准备进入邮件投递系统的日期和时间。 |
| [getDeliveryNotificationOptions()](#getDeliveryNotificationOptions--) | 获取或设置投递通知 |
| [getEpilogue()](#getEpilogue--) | 获取或设置结尾文本。 |
| [getFrom()](#getFrom--) | 获取或设置发件人地址 |
| [getHeaders()](#getHeaders--) | 获取消息的标头集合 |
| [getHtmlBody()](#getHtmlBody--) | 获取或设置 HTML 正文 |
| [getHtmlBodyText()](#getHtmlBodyText--) | 获取消息的 HTML 正文为纯文本。 |
| [getHtmlBodyText(boolean showUrl)](#getHtmlBodyText-boolean-) | 获取消息的 HTML 正文为纯文本。 |
| [getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback)](#getHtmlBodyText-com.aspose.email.HyperlinkRenderingCallback-) | 获取消息的 HTML 正文为纯文本。 |
| [getItemId()](#getItemId--) | 表示邮箱中邮件的标识信息。 |
| [getLinkedResources()](#getLinkedResources--) | 获取消息的链接资源集合 |
| [getLocalDate()](#getLocalDate--) | 获取消息的本地日期 |
| [getMessageId()](#getMessageId--) | 获取或设置消息 ID |
| [getOriginalIsTnef()](#getOriginalIsTnef--) | 获取一个值，指示原始 EML 消息是否为 TNEF 格式。 |
| [getPreamble()](#getPreamble--) | 获取或设置前言文本。 |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | 获取或设置所有文本属性的首选编码 |
| [getPriority()](#getPriority--) | 获取或设置消息的优先级 |
| [getReadReceiptTo()](#getReadReceiptTo--) | 获取或设置已读回执地址。 |
| [getReplyToList()](#getReplyToList--) | 获取或设置邮件消息的回复地址列表 |
| [getReversePath()](#getReversePath--) | 获取或设置 ReversePath 地址 |
| [getSender()](#getSender--) | 获取或设置发件人地址 |
| [getSensitivity()](#getSensitivity--) | 获取或设置消息的敏感度 |
| [getSubject()](#getSubject--) | 获取或设置主题行 |
| [getSubjectEncoding()](#getSubjectEncoding--) | 获取或设置主题的编码 |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | 获取或设置消息日期的协调世界时 (UTC) 偏移量。 |
| [getTo()](#getTo--) | 获取或设置包含消息收件人的地址集合 |
| [getXMailer()](#getXMailer--) | 获取或设置创建电子邮件的 X-Mailer 软件 |
| [hashCode()](#hashCode--) | 返回对象的哈希码 |
| [importMessage(InputStream stream)](#importMessage-java.io.InputStream-) | 从流导入消息 |
| [isBodyHtml()](#isBodyHtml--) | 获取或设置指示消息正文是否为 Html 的值 |
| [isBodyHtml(boolean value)](#isBodyHtml-boolean-) | 获取或设置指示消息正文是否为 Html 的值 |
| [isDraft()](#isDraft--) | 获取或设置指示消息是否已发送的值。 |
| [isDraft(boolean value)](#isDraft-boolean-) | 获取或设置指示消息是否已发送的值。 |
| [isEncrypted()](#isEncrypted--) | 获取指示消息是否已加密的值。 |
| [isLocalDate()](#isLocalDate--) | 定义日期是否为本地日期 |
| [isReadOnly()](#isReadOnly--) | 获取指示消息是否为只读的值 |
| [isSigned()](#isSigned--) | 获取指示消息是否已签名的值。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [load(InputStream stream)](#load-java.io.InputStream-) | 从流加载消息 |
| [load(InputStream stream, LoadOptions options)](#load-java.io.InputStream-com.aspose.email.LoadOptions-) | 使用附加选项从流加载消息。 |
| [load(String fileName)](#load-java.lang.String-) | 从文件加载消息 |
| [load(String fileName, LoadOptions options)](#load-java.lang.String-com.aspose.email.LoadOptions-) | 使用附加选项从文件加载消息。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [recomposeTnefContent()](#recomposeTnefContent--) | 生成 TNEF 内容。 |
| [removeSignature()](#removeSignature--) | 移除签名 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将消息保存为流 |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.email.SaveOptions-) | 将消息保存为流 |
| [save(String fileName)](#save-java.lang.String-) | 将消息保存为文件 |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.email.SaveOptions-) | 使用附加选项将消息保存为文件。 |
| [setAmpHtmlBody(String value)](#setAmpHtmlBody-java.lang.String-) | 获取消息正文的 AmpHtml 表示形式。 |
| [setBcc(MailAddressCollection value)](#setBcc-com.aspose.email.MailAddressCollection-) | 获取或设置包含消息 BCC 收件人的地址集合 |
| [setBody(String value)](#setBody-java.lang.String-) | 获取或设置消息正文的纯文本表示。 |
| [setBodyEncoding(Charset value)](#setBodyEncoding-java.nio.charset.Charset-) | 获取或设置正文的编码 |
| [setCC(MailAddressCollection value)](#setCC-com.aspose.email.MailAddressCollection-) | 获取或设置包含抄送收件人的地址集合 |
| [setDate(Date value)](#setDate-java.util.Date-) | 获取或设置消息的日期 |
| [setDeliveryNotificationOptions(int value)](#setDeliveryNotificationOptions-int-) | 获取或设置投递通知 |
| [setEpilogue(String value)](#setEpilogue-java.lang.String-) | 获取或设置结尾文本。 |
| [setFrom(IMailAddress value)](#setFrom-com.aspose.email.IMailAddress-) | 设置发件人地址 |
| [setFrom(MailAddress value)](#setFrom-com.aspose.email.MailAddress-) | 获取或设置发件人地址 |
| [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | 获取或设置 HTML 正文 |
| [setHtmlBody(String value, boolean detectEncoding)](#setHtmlBody-java.lang.String-boolean-) | 设置 HTML 正文。 |
| [setMessageId(String value)](#setMessageId-java.lang.String-) | 获取或设置消息 ID |
| [setPreamble(String value)](#setPreamble-java.lang.String-) | 获取或设置前言文本。 |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | 获取或设置所有文本属性的首选编码 |
| [setPriority(MailPriority value)](#setPriority-com.aspose.email.MailPriority-) | 获取或设置消息的优先级 |
| [setReadReceiptTo(MailAddressCollection value)](#setReadReceiptTo-com.aspose.email.MailAddressCollection-) | 获取或设置已读回执地址。 |
| [setReplyToList(MailAddressCollection value)](#setReplyToList-com.aspose.email.MailAddressCollection-) | 获取或设置邮件消息的回复地址列表 |
| [setReversePath(MailAddress value)](#setReversePath-com.aspose.email.MailAddress-) | 获取或设置 ReversePath 地址 |
| [setSender(MailAddress value)](#setSender-com.aspose.email.MailAddress-) | 获取或设置发件人地址 |
| [setSensitivity(MailSensitivity value)](#setSensitivity-com.aspose.email.MailSensitivity-) | 获取或设置消息的敏感度 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 获取或设置主题行 |
| [setSubjectEncoding(Charset value)](#setSubjectEncoding-java.nio.charset.Charset-) | 获取或设置主题的编码 |
| [setTimeZoneOffset(double value)](#setTimeZoneOffset-double-) | 获取或设置消息日期的协调世界时 (UTC) 偏移量。 |
| [setTo(MailAddressCollection value)](#setTo-com.aspose.email.MailAddressCollection-) | 获取或设置包含消息收件人的地址集合 |
| [setXMailer(String value)](#setXMailer-java.lang.String-) | 获取或设置创建电子邮件的 X-Mailer 软件 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [validateMessage(InputStream stream)](#validateMessage-java.io.InputStream-) | 验证 eml 消息是否符合 mime 规范。 |
| [validateMessage(String fileName)](#validateMessage-java.lang.String-) | 验证 eml 消息是否符合 mime 规范。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpMessage() {#AmpMessage--}
```
public AmpMessage()
```


初始化 [MailMessage](../../com.aspose.email/mailmessage) 类的新实例

### addAlternateView(AlternateView view) {#addAlternateView-com.aspose.email.AlternateView-}
```
public void addAlternateView(AlternateView view)
```


向消息添加备用视图

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| view | [AlternateView](../../com.aspose.email/alternateview) | 用于添加的备用视图 |

### addAmpComponent(AmpComponent component) {#addAmpComponent-com.aspose.email.AmpComponent-}
```
public final void addAmpComponent(AmpComponent component)
```


向此消息添加 Amp 组件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| component | [AmpComponent](../../com.aspose.email/ampcomponent) |  |

### addAttachment(Attachment attachment) {#addAttachment-com.aspose.email.Attachment-}
```
public void addAttachment(Attachment attachment)
```


向消息添加附件

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attachment | [Attachment](../../com.aspose.email/attachment) | 用于添加的附件 |

### attachSignature(byte[] certificateRawData, String certificatePassword) {#attachSignature-byte---java.lang.String-}
```
public MailMessage attachSignature(byte[] certificateRawData, String certificatePassword)
```


创建已签名的消息。创建指定 MailMessage 的只读副本并向其添加数字签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificateRawData | byte[] | X.509 证书。 |
| certificatePassword | java.lang.String | 访问 X.509 证书数据所需的密码 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The signed MailMessage.
### attachSignature(byte[] certificateRawData, String certificatePassword, boolean detached) {#attachSignature-byte---java.lang.String-boolean-}
```
public MailMessage attachSignature(byte[] certificateRawData, String certificatePassword, boolean detached)
```


创建已签名的消息。创建指定 MailMessage 的只读副本并向其添加数字签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificateRawData | byte[] | X.509 证书。 |
| certificatePassword | java.lang.String | 访问 X.509 证书数据所需的密码 |
| detached | boolean | .如果 detached 为 true，则签名为分离式。如果 detached 为 false（默认），则签名不是分离式。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The signed MailMessage.
### attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public MailMessage attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, boolean detached) {#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
```
public MailMessage attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, boolean detached)
```


创建已签名的消息。创建指定 MailMessage 的只读副本并向其添加数字签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | X.509 证书。 |
| detached | boolean | .如果 detached 为 true，则签名为分离式。如果 detached 为 false（默认），则签名不是分离式。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - 
### checkBounced() {#checkBounced--}
```
public BounceResult checkBounced()
```


检查此消息是否可以视为退回消息。

**Returns:**
[BounceResult](../../com.aspose.email/bounceresult) - Result of checking[BounceResult](../../com.aspose.email/bounceresult).
### checkSignature() {#checkSignature--}
```
public String[] checkSignature()
```


检查已存在的 MailMessage 的签名。

**Returns:**
java.lang.String[] - X.509 签名者证书
### checkSignature(InputStream stream) {#checkSignature-java.io.InputStream-}
```
public static boolean checkSignature(InputStream stream)
```


检查指定 eml 消息的签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含 eml 格式消息的流。 |

**Returns:**
boolean - 如果签名有效则为 True；否则为 false。
### checkSignature(String fileName) {#checkSignature-java.lang.String-}
```
public static boolean checkSignature(String fileName)
```


检查指定 eml 文件的签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名 (eml)。 |

**Returns:**
boolean - 如果签名有效则为 True；否则为 false。
### checkSignatureCert() {#checkSignatureCert--}
```
public System.Security.Cryptography.X509Certificates.X509Certificate2[] checkSignatureCert()
```


检查已存在的 MailMessage 的签名。

**Returns:**
com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2[] - X.509 签名者证书
### close() {#close--}
```
public void close()
```




### createReadReceipt(String from, String bodyText) {#createReadReceipt-java.lang.String-java.lang.String-}
```
public final MailMessage createReadReceipt(String from, String bodyText)
```


创建已读回执。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| from | java.lang.String | 表示发件人地址的字符串。 |
| bodyText | java.lang.String | 消息正文文本。如果此参数为 null 或为空，将使用默认的消息正文文本。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A newly created [MailMessage](../../com.aspose.email/mailmessage) that represents the read receipt.
### dKIMSign(System.Security.Cryptography.RSACryptoServiceProvider rsa, DKIMSignatureInfo signatureInfo) {#dKIMSign-com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider-com.aspose.email.DKIMSignatureInfo-}
```
public MailMessage dKIMSign(System.Security.Cryptography.RSACryptoServiceProvider rsa, DKIMSignatureInfo signatureInfo)
```


使用 DKIM（DomainKeys Identified Mail）签名对该消息进行签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rsa | com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider | 包含用于签名的私钥的 RSA 类。 |
| signatureInfo | [DKIMSignatureInfo](../../com.aspose.email/dkimsignatureinfo) | DKIM 签名信息。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - 
### decrypt() {#decrypt--}
```
public MailMessage decrypt()
```


解密此消息

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### decrypt(byte[] certificateRawData, String certificatePassword) {#decrypt-byte---java.lang.String-}
```
public MailMessage decrypt(byte[] certificateRawData, String certificatePassword)
```


解密此消息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificateRawData | byte[] | System.Security.Cryptography.X509Certificates.X509Certificate2 |
| certificatePassword | java.lang.String | 访问 X.509 证书数据所需的密码 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#decrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public MailMessage decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### deepClone() {#deepClone--}
```
public MailMessage deepClone()
```


克隆此实例

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - MailMessage that is a copy of the current instance
### dispose() {#dispose--}
```
public final void dispose()
```


释放 MailMessage 使用的所有资源

### encrypt(byte[] certificateRawData, String certificatePassword) {#encrypt-byte---java.lang.String-}
```
public MailMessage encrypt(byte[] certificateRawData, String certificatePassword)
```


加密此消息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificateRawData | byte[] | 用于加密消息的 X509 证书 |
| certificatePassword | java.lang.String |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Encrypted email message
### encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public MailMessage encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2[] certificates) {#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2---}
```
public MailMessage encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2[] certificates)
```


加密此消息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 证书 | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2[] | 用于加密消息的 X509 证书数组 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Encrypted email message
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 Object 是否等于当前 Object。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与当前对象比较的对象。 |

**Returns:**
boolean - 返回一个布尔值，指示传入的对象 obj 是否等于此对象。
### getAlternateViews() {#getAlternateViews--}
```
public AlternateViewCollection getAlternateViews()
```


获取消息的备用视图集合

**Returns:**
[AlternateViewCollection](../../com.aspose.email/alternateviewcollection)
### getAmpHtmlBody() {#getAmpHtmlBody--}
```
public String getAmpHtmlBody()
```


获取消息正文的 AmpHtml 表示形式。

**Returns:**
java.lang.String
### getAttachments() {#getAttachments--}
```
public AttachmentCollection getAttachments()
```


获取消息的附件集合

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getBcc() {#getBcc--}
```
public MailAddressCollection getBcc()
```


获取或设置包含消息 BCC 收件人的地址集合

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getBody() {#getBody--}
```
public String getBody()
```


获取或设置消息正文的纯文本表示。如果消息中存在 text/plain 部分，属性返回其文本数据。否则，属性返回 HtmlBody 属性的文本内容，且不包含 HTML 标记。

**Returns:**
java.lang.String
### getBodyEncoding() {#getBodyEncoding--}
```
public Charset getBodyEncoding()
```


获取或设置正文的编码

**Returns:**
java.nio.charset.Charset
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


获取正文的类型。

**Returns:**
int
### getCC() {#getCC--}
```
public MailAddressCollection getCC()
```


获取或设置包含抄送收件人的地址集合

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getCc() {#getCc--}
```
public final System.Collections.Generic.IGenericCollection<MailAddress> getCc()
```


获取抄送收件人

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDate() {#getDate--}
```
public Date getDate()
```


获取或设置消息的日期，指定消息创建者指示消息已完成并准备进入邮件投递系统的日期和时间。

**Returns:**
java.util.Date
### getDeliveryNotificationOptions() {#getDeliveryNotificationOptions--}
```
public int getDeliveryNotificationOptions()
```


获取或设置投递通知

**Returns:**
int
### getEpilogue() {#getEpilogue--}
```
public final String getEpilogue()
```


获取或设置尾部文本。它位于最后一个边界之后。

值：表示尾部的字符串值。

**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public MailAddress getFrom()
```


获取或设置发件人地址

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getHeaders() {#getHeaders--}
```
public HeaderCollection getHeaders()
```


获取消息的标头集合

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getHtmlBody() {#getHtmlBody--}
```
public String getHtmlBody()
```


获取或设置 HTML 正文

**Returns:**
java.lang.String
### getHtmlBodyText() {#getHtmlBodyText--}
```
public final String getHtmlBodyText()
```


获取消息的 HTML 正文为纯文本。

**Returns:**
java.lang.String
### getHtmlBodyText(boolean showUrl) {#getHtmlBodyText-boolean-}
```
public String getHtmlBodyText(boolean showUrl)
```


获取消息的 HTML 正文的纯文本。此方法解析 HtmlBody 属性并返回忽略 HTML 标记的纯文本内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| showUrl | boolean | 定义是否需要在文本中显示 URL。 |

**Returns:**
java.lang.String
### getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback) {#getHtmlBodyText-com.aspose.email.HyperlinkRenderingCallback-}
```
public String getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback)
```


获取消息的 HTML 正文为纯文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hyperlinkRenderingCallback | [HyperlinkRenderingCallback](../../com.aspose.email/hyperlinkrenderingcallback) | 对自定义方法的引用，用于处理超链接的渲染。 |

**Returns:**
java.lang.String - 自定义处理超链接渲染的结果字符串。
### getItemId() {#getItemId--}
```
public MailboxInfo getItemId()
```


表示邮箱中邮件的标识信息。

**Returns:**
[MailboxInfo](../../com.aspose.email/mailboxinfo)
### getLinkedResources() {#getLinkedResources--}
```
public LinkedResourceCollection getLinkedResources()
```


获取消息的链接资源集合

**Returns:**
[LinkedResourceCollection](../../com.aspose.email/linkedresourcecollection)
### getLocalDate() {#getLocalDate--}
```
public Date getLocalDate()
```


获取消息的本地日期

**Returns:**
java.util.Date - 消息的本地日期
### getMessageId() {#getMessageId--}
```
public String getMessageId()
```


获取或设置消息 ID

**Returns:**
java.lang.String
### getOriginalIsTnef() {#getOriginalIsTnef--}
```
public boolean getOriginalIsTnef()
```


获取一个值，指示原始 EML 消息是否为 TNEF 格式。

**Returns:**
boolean
### getPreamble() {#getPreamble--}
```
public final String getPreamble()
```


获取或设置前言文本。它位于第一个边界之前，通常包含对非 MIME 合规阅读器的说明性注释。

值：表示前言的字符串值。

**Returns:**
java.lang.String
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


获取或设置所有文本属性的首选编码

**Returns:**
java.nio.charset.Charset
### getPriority() {#getPriority--}
```
public MailPriority getPriority()
```


获取或设置消息的优先级

**Returns:**
[MailPriority](../../com.aspose.email/mailpriority)
### getReadReceiptTo() {#getReadReceiptTo--}
```
public final MailAddressCollection getReadReceiptTo()
```


获取或设置已读回执地址。

值：表示 [MailAddressCollection](../../com.aspose.email/mailaddresscollection) 的

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getReplyToList() {#getReplyToList--}
```
public MailAddressCollection getReplyToList()
```


获取或设置邮件消息的回复地址列表

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getReversePath() {#getReversePath--}
```
public MailAddress getReversePath()
```


获取或设置 ReversePath 地址

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getSender() {#getSender--}
```
public MailAddress getSender()
```


获取或设置发件人地址

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getSensitivity() {#getSensitivity--}
```
public MailSensitivity getSensitivity()
```


获取或设置消息的敏感度

**Returns:**
[MailSensitivity](../../com.aspose.email/mailsensitivity)
### getSubject() {#getSubject--}
```
public String getSubject()
```


获取或设置主题行

**Returns:**
java.lang.String
### getSubjectEncoding() {#getSubjectEncoding--}
```
public Charset getSubjectEncoding()
```


获取或设置主题的编码

**Returns:**
java.nio.charset.Charset
### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final double getTimeZoneOffset()
```


获取或设置消息日期的协调世界时 (UTC) 偏移量。此属性定义本地时间与 UTC 之间的时区差异。

**Returns:**
double - 毫秒数。
### getTo() {#getTo--}
```
public MailAddressCollection getTo()
```


获取或设置包含消息收件人的地址集合

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getXMailer() {#getXMailer--}
```
public String getXMailer()
```


获取或设置创建电子邮件的 X-Mailer 软件

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回对象的哈希码

**Returns:**
int -
### importMessage(InputStream stream) {#importMessage-java.io.InputStream-}
```
public void importMessage(InputStream stream)
```


从流导入消息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | System.IO.Stream |

### isBodyHtml() {#isBodyHtml--}
```
public boolean isBodyHtml()
```


获取或设置指示消息正文是否为 Html 的值

**Returns:**
boolean
### isBodyHtml(boolean value) {#isBodyHtml-boolean-}
```
public void isBodyHtml(boolean value)
```


获取或设置指示消息正文是否为 Html 的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isDraft() {#isDraft--}
```
public boolean isDraft()
```


获取或设置指示消息是否已发送的值。

**Returns:**
boolean
### isDraft(boolean value) {#isDraft-boolean-}
```
public void isDraft(boolean value)
```


获取或设置指示消息是否已发送的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


获取指示消息是否已加密的值。

**Returns:**
boolean
### isLocalDate() {#isLocalDate--}
```
public boolean isLocalDate()
```


定义日期是否为本地日期

**Returns:**
boolean - 如果日期是本地日期则为 true
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取指示消息是否为只读的值

**Returns:**
boolean
### isSigned() {#isSigned--}
```
public boolean isSigned()
```


获取指示消息是否已签名的值。

**Returns:**
boolean
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<MailMessage> iterator()
```


返回一个遍历集合的枚举器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.email.MailMessage> - 可用于遍历集合的 IEnumerator 对象。
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static MailMessage load(InputStream stream)
```


从流加载消息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 表示 eml 或 msg 格式消息的流 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### load(InputStream stream, LoadOptions options) {#load-java.io.InputStream-com.aspose.email.LoadOptions-}
```
public static MailMessage load(InputStream stream, LoadOptions options)
```


使用附加选项从流加载消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 源流 java.io.InputStream。 |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | 附加选项 [LoadOptions](../../com.aspose.email/loadoptions)。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Mail message[MailMessage](../../com.aspose.email/mailmessage).
### load(String fileName) {#load-java.lang.String-}
```
public static MailMessage load(String fileName)
```


从文件加载消息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 消息文件名。消息文件必须是 eml 或 msg 格式。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### load(String fileName, LoadOptions options) {#load-java.lang.String-com.aspose.email.LoadOptions-}
```
public static MailMessage load(String fileName, LoadOptions options)
```


使用附加选项从文件加载消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 源文件路径字符串。 |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | 附加选项 [LoadOptions](../../com.aspose.email/loadoptions)。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Mail message[MailMessage](../../com.aspose.email/mailmessage).
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### recomposeTnefContent() {#recomposeTnefContent--}
```
public final void recomposeTnefContent()
```


组成 TNEF 内容。注意，如果消息最初包含 TNEF 并且在加载时未使用 FileCompatibilityMode.PreserveTnefAttachments 标志，则会生成 tnef 附件。也就是说，此方法不会将普通消息创建为 tnef 消息。

### removeSignature() {#removeSignature--}
```
public MailMessage removeSignature()
```


移除签名

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


将消息保存为流

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 保存消息的流 |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.email.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


将消息保存为流

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 保存消息的流 |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | 用于保存的附加选项[SaveOptions](../../com.aspose.email/saveoptions)。 |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


将消息保存为文件

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 用于保存消息的文件名。 |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.email.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


使用附加选项将消息保存为文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 保存消息的流。 |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | 用于保存的附加选项[SaveOptions](../../com.aspose.email/saveoptions)。 |

### setAmpHtmlBody(String value) {#setAmpHtmlBody-java.lang.String-}
```
public void setAmpHtmlBody(String value)
```


获取消息正文的 AmpHtml 表示形式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBcc(MailAddressCollection value) {#setBcc-com.aspose.email.MailAddressCollection-}
```
public void setBcc(MailAddressCollection value)
```


获取或设置包含消息 BCC 收件人的地址集合

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


获取或设置消息正文的纯文本表示。如果消息中存在 text/plain 部分，属性返回其文本数据。否则，属性返回 HtmlBody 属性的文本内容，且不包含 HTML 标记。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyEncoding(Charset value) {#setBodyEncoding-java.nio.charset.Charset-}
```
public void setBodyEncoding(Charset value)
```


获取或设置正文的编码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setCC(MailAddressCollection value) {#setCC-com.aspose.email.MailAddressCollection-}
```
public void setCC(MailAddressCollection value)
```


获取或设置包含抄送收件人的地址集合

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setDate(Date value) {#setDate-java.util.Date-}
```
public void setDate(Date value)
```


获取或设置消息的日期

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setDeliveryNotificationOptions(int value) {#setDeliveryNotificationOptions-int-}
```
public void setDeliveryNotificationOptions(int value)
```


获取或设置投递通知

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setEpilogue(String value) {#setEpilogue-java.lang.String-}
```
public final void setEpilogue(String value)
```


获取或设置尾部文本。它位于最后一个边界之后。

值：表示尾部的字符串值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFrom(IMailAddress value) {#setFrom-com.aspose.email.IMailAddress-}
```
public final void setFrom(IMailAddress value)
```


设置发件人地址

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMailAddress](../../com.aspose.email/imailaddress) | 发件人地址 |

### setFrom(MailAddress value) {#setFrom-com.aspose.email.MailAddress-}
```
public void setFrom(MailAddress value)
```


获取或设置发件人地址

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public void setHtmlBody(String value)
```


获取或设置 HTML 正文

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setHtmlBody(String value, boolean detectEncoding) {#setHtmlBody-java.lang.String-boolean-}
```
public void setHtmlBody(String value, boolean detectEncoding)
```


设置 HTML 正文。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | HtmlBody 内容文本。 |
| detectEncoding | boolean | 如果未为 MailMessage 指定编码，则检测正文编码。 |

### setMessageId(String value) {#setMessageId-java.lang.String-}
```
public void setMessageId(String value)
```


获取或设置消息 ID

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreamble(String value) {#setPreamble-java.lang.String-}
```
public final void setPreamble(String value)
```


获取或设置前言文本。它位于第一个边界之前，通常包含对非 MIME 合规阅读器的说明性注释。

值：表示前言的字符串值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


获取或设置所有文本属性的首选编码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPriority(MailPriority value) {#setPriority-com.aspose.email.MailPriority-}
```
public void setPriority(MailPriority value)
```


获取或设置消息的优先级

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailPriority](../../com.aspose.email/mailpriority) |  |

### setReadReceiptTo(MailAddressCollection value) {#setReadReceiptTo-com.aspose.email.MailAddressCollection-}
```
public final void setReadReceiptTo(MailAddressCollection value)
```


获取或设置已读回执地址。

值：表示 [MailAddressCollection](../../com.aspose.email/mailaddresscollection) 的

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setReplyToList(MailAddressCollection value) {#setReplyToList-com.aspose.email.MailAddressCollection-}
```
public void setReplyToList(MailAddressCollection value)
```


获取或设置邮件消息的回复地址列表

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setReversePath(MailAddress value) {#setReversePath-com.aspose.email.MailAddress-}
```
public void setReversePath(MailAddress value)
```


获取或设置 ReversePath 地址

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setSender(MailAddress value) {#setSender-com.aspose.email.MailAddress-}
```
public void setSender(MailAddress value)
```


获取或设置发件人地址

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setSensitivity(MailSensitivity value) {#setSensitivity-com.aspose.email.MailSensitivity-}
```
public void setSensitivity(MailSensitivity value)
```


获取或设置消息的敏感度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailSensitivity](../../com.aspose.email/mailsensitivity) |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


获取或设置主题行

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubjectEncoding(Charset value) {#setSubjectEncoding-java.nio.charset.Charset-}
```
public void setSubjectEncoding(Charset value)
```


获取或设置主题的编码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setTimeZoneOffset(double value) {#setTimeZoneOffset-double-}
```
public final void setTimeZoneOffset(double value)
```


获取或设置消息日期的协调世界时 (UTC) 偏移量。此属性定义本地时间与 UTC 之间的时区差异。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 毫秒数。 |

### setTo(MailAddressCollection value) {#setTo-com.aspose.email.MailAddressCollection-}
```
public void setTo(MailAddressCollection value)
```


获取或设置包含消息收件人的地址集合

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setXMailer(String value) {#setXMailer-java.lang.String-}
```
public void setXMailer(String value)
```


获取或设置创建电子邮件的 X-Mailer 软件

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。

**Returns:**
java.lang.String - 表示当前对象的字符串。
### validateMessage(InputStream stream) {#validateMessage-java.io.InputStream-}
```
public static EmlValidationErrorCollection validateMessage(InputStream stream)
```


验证 eml 消息是否符合 mime 规范。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含 eml 格式消息的流。 |

**Returns:**
[EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) - A [EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) containing the found validation error messages.
### validateMessage(String fileName) {#validateMessage-java.lang.String-}
```
public static EmlValidationErrorCollection validateMessage(String fileName)
```


验证 eml 消息是否符合 mime 规范。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名 (eml)。 |

**Returns:**
[EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) - A [EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) containing the found validation error messages.
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

