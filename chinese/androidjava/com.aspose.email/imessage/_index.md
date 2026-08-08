---
title: IMessage
second_title: Aspose.Email for Android via Java API 参考
description: 表示通用消息接口
type: docs
weight: 459
url: /zh/androidjava/com.aspose.email/imessage/
---
```
public interface IMessage
```

表示通用消息接口
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAttachments()](#getAttachments--) | 获取邮件附件 |
| [getBcc()](#getBcc--) | 获取密送收件人 |
| [getBody()](#getBody--) | 获取或设置邮件正文 |
| [getBodyType()](#getBodyType--) | 获取正文的类型。 |
| [getCC()](#getCC--) | 获取抄送收件人 |
| [getDate()](#getDate--) | 获取邮件投递的日期和时间 |
| [getFrom()](#getFrom--) | 获取或设置发件人地址 |
| [getHtmlBody()](#getHtmlBody--) | 获取或设置 HTML 格式的邮件正文 |
| [getSubject()](#getSubject--) | 获取或设置邮件主题 |
| [getTo()](#getTo--) | 获取收件人 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将邮件保存到指定的流 |
| [save(String fileName)](#save-java.lang.String-) | 将邮件保存到指定的文件 |
| [setBody(String value)](#setBody-java.lang.String-) | 获取或设置邮件正文 |
| [setFrom(IMailAddress value)](#setFrom-com.aspose.email.IMailAddress-) | 获取或设置发件人地址 |
| [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | 获取或设置 HTML 格式的邮件正文 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 获取或设置邮件主题 |
### getAttachments() {#getAttachments--}
```
public abstract System.Collections.Generic.IGenericCollection<Attachment> getAttachments()
```


获取邮件附件

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.Attachment>
### getBcc() {#getBcc--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getBcc()
```


获取密送收件人

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### getBody() {#getBody--}
```
public abstract String getBody()
```


获取或设置邮件正文

**Returns:**
java.lang.String
### getBodyType() {#getBodyType--}
```
public abstract int getBodyType()
```


获取正文的类型。

**Returns:**
int
### getCC() {#getCC--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getCC()
```


获取抄送收件人

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### getDate() {#getDate--}
```
public abstract Date getDate()
```


获取邮件投递的日期和时间

**Returns:**
java.util.Date
### getFrom() {#getFrom--}
```
public abstract IMailAddress getFrom()
```


获取或设置发件人地址

**Returns:**
[IMailAddress](../../com.aspose.email/imailaddress)
### getHtmlBody() {#getHtmlBody--}
```
public abstract String getHtmlBody()
```


获取或设置 HTML 格式的邮件正文

**Returns:**
java.lang.String
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


获取或设置邮件主题

**Returns:**
java.lang.String
### getTo() {#getTo--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getTo()
```


获取收件人

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream stream)
```


将邮件保存到指定的流

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存的流 |

### save(String fileName) {#save-java.lang.String-}
```
public abstract void save(String fileName)
```


将邮件保存到指定的文件

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名 |

### setBody(String value) {#setBody-java.lang.String-}
```
public abstract void setBody(String value)
```


获取或设置邮件正文

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFrom(IMailAddress value) {#setFrom-com.aspose.email.IMailAddress-}
```
public abstract void setFrom(IMailAddress value)
```


获取或设置发件人地址

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMailAddress](../../com.aspose.email/imailaddress) |  |

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public abstract void setHtmlBody(String value)
```


获取或设置 HTML 格式的邮件正文

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```


获取或设置邮件主题

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

