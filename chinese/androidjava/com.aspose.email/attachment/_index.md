---
title: Attachment
second_title: Aspose.Email for Android via Java API 参考
description: 表示电子邮件附件。
type: docs
weight: 52
url: /zh/androidjava/com.aspose.email/attachment/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase)

**All Implemented Interfaces:**
[com.aspose.email.IPreferredTextEncodingProvider](../../com.aspose.email/ipreferredtextencodingprovider), [com.aspose.email.IAttachment](../../com.aspose.email/iattachment)
```
public class Attachment extends AttachmentBase implements IPreferredTextEncodingProvider, IAttachment
```

表示电子邮件附件。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Attachment(String fileName)](#Attachment-java.lang.String-) | 初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。 |
| [Attachment(String fileName, String mediaType)](#Attachment-java.lang.String-java.lang.String-) | 初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。 |
| [Attachment(String fileName, ContentType contentType)](#Attachment-java.lang.String-com.aspose.email.ContentType-) | 初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。 |
| [Attachment(InputStream contentStream, String name)](#Attachment-java.io.InputStream-java.lang.String-) | 初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。 |
| [Attachment(InputStream contentStream, String name, String mediaType)](#Attachment-java.io.InputStream-java.lang.String-java.lang.String-) | 初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。 |
| [Attachment(InputStream contentStream, ContentType contentType)](#Attachment-java.io.InputStream-com.aspose.email.ContentType-) | 初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [createAttachmentFromString(String content, ContentType contentType)](#createAttachmentFromString-java.lang.String-com.aspose.email.ContentType-) | 从字符串创建附件。 |
| [createAttachmentFromString(String content, String name)](#createAttachmentFromString-java.lang.String-java.lang.String-) | 从字符串创建附件。 |
| [createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType)](#createAttachmentFromString-java.lang.String-java.lang.String-java.nio.charset.Charset-java.lang.String-) | 从字符串创建附件。 |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | 获取 Content-Disposition 标头 |
| [getContentId()](#getContentId--) | 获取或设置内容 ID。 |
| [getContentStream()](#getContentStream--) | 获取或设置内容流。 |
| [getContentType()](#getContentType--) | 获取或设置内容的类型。 |
| [getHeaders()](#getHeaders--) | 获取附件的标头集合。 |
| [getName()](#getName--) | 获取或设置附件名称 |
| [getNameEncoding()](#getNameEncoding--) | 获取或设置附件名称的编码 |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | 获取或设置首选文本编码 |
| [getTransferEncoding()](#getTransferEncoding--) | 获取或设置传输编码。 |
| [hashCode()](#hashCode--) |  |
| [isEmbeddedMessage()](#isEmbeddedMessage--) | 获取一个值，指示附件是否为嵌入的消息。 |
| [isUri()](#isUri--) | 获取一个值，指示附件是否为 URI 附件。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 保存指定的流。 |
| [save(String fileName)](#save-java.lang.String-) | 保存指定的文件名。 |
| [setContentId(String value)](#setContentId-java.lang.String-) | 获取或设置内容 ID。 |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | 获取或设置内容流。 |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | 获取或设置内容的类型。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置附件名称 |
| [setNameEncoding(Charset value)](#setNameEncoding-java.nio.charset.Charset-) | 获取或设置附件名称的编码 |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | 获取或设置首选文本编码 |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | 获取或设置传输编码。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Attachment(String fileName) {#Attachment-java.lang.String-}
```
public Attachment(String fileName)
```


初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |

### Attachment(String fileName, String mediaType) {#Attachment-java.lang.String-java.lang.String-}
```
public Attachment(String fileName, String mediaType)
```


初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
| mediaType | java.lang.String | 类型的媒体类型名称。 |

### Attachment(String fileName, ContentType contentType) {#Attachment-java.lang.String-com.aspose.email.ContentType-}
```
public Attachment(String fileName, ContentType contentType)
```


初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
| contentType | [ContentType](../../com.aspose.email/contenttype) | ContentType（[AttachmentBase.getContentType](../../com.aspose.email/attachmentbase\#getContentType)/[AttachmentBase.setContentType(ContentType)](../../com.aspose.email/attachmentbase\#setContentType-ContentType-))。 |

### Attachment(InputStream contentStream, String name) {#Attachment-java.io.InputStream-java.lang.String-}
```
public Attachment(InputStream contentStream, String name)
```


初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentStream | java.io.InputStream | 附件的内容流。 |
| name | java.lang.String | 附件名称。 |

### Attachment(InputStream contentStream, String name, String mediaType) {#Attachment-java.io.InputStream-java.lang.String-java.lang.String-}
```
public Attachment(InputStream contentStream, String name, String mediaType)
```


初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentStream | java.io.InputStream | 附件的内容流。 |
| name | java.lang.String | 附件名称。 |
| mediaType | java.lang.String | 媒体类型名称。 |

### Attachment(InputStream contentStream, ContentType contentType) {#Attachment-java.io.InputStream-com.aspose.email.ContentType-}
```
public Attachment(InputStream contentStream, ContentType contentType)
```


初始化一个新的 [Attachment](../../com.aspose.email/attachment) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentStream | java.io.InputStream | 附件的内容流。 |
| contentType | [ContentType](../../com.aspose.email/contenttype) | ContentType（[AttachmentBase.getContentType](../../com.aspose.email/attachmentbase\#getContentType)/[AttachmentBase.setContentType(ContentType)](../../com.aspose.email/attachmentbase\#setContentType-ContentType-))。 |

### close() {#close--}
```
public void close()
```




### createAttachmentFromString(String content, ContentType contentType) {#createAttachmentFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static Attachment createAttachmentFromString(String content, ContentType contentType)
```


从字符串创建附件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 表示附件内容的字符串。 |
| contentType | [ContentType](../../com.aspose.email/contenttype) | ContentType（[AttachmentBase.getContentType](../../com.aspose.email/attachmentbase\#getContentType)/[AttachmentBase.setContentType(ContentType)](../../com.aspose.email/attachmentbase\#setContentType-ContentType-))。 |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - Returns created attachment
### createAttachmentFromString(String content, String name) {#createAttachmentFromString-java.lang.String-java.lang.String-}
```
public static Attachment createAttachmentFromString(String content, String name)
```


从字符串创建附件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 表示附件内容的字符串。 |
| name | java.lang.String | 附件名称。 |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - Returns created attachment
### createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType) {#createAttachmentFromString-java.lang.String-java.lang.String-java.nio.charset.Charset-java.lang.String-}
```
public static Attachment createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType)
```


从字符串创建附件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 表示附件内容的字符串。 |
| name | java.lang.String | 附件名称。 |
| contentEncoding | java.nio.charset.Charset | 内容的编码。 |
| mediaType | java.lang.String | 媒体类型名称 |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - Returns created attachment
### dispose() {#dispose--}
```
public final void dispose()
```


执行应用程序定义的任务，以释放、释放或重置非托管资源。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentDisposition() {#getContentDisposition--}
```
public final ContentDisposition getContentDisposition()
```


获取 Content-Disposition 标头

**Returns:**
[ContentDisposition](../../com.aspose.email/contentdisposition)
### getContentId() {#getContentId--}
```
public final String getContentId()
```


获取或设置内容 ID。

值：内容 ID。

**Returns:**
java.lang.String
### getContentStream() {#getContentStream--}
```
public final InputStream getContentStream()
```


获取或设置内容流。

值：内容流。

**Returns:**
java.io.InputStream
### getContentType() {#getContentType--}
```
public final ContentType getContentType()
```


获取或设置内容的类型。

值：内容的类型。

**Returns:**
[ContentType](../../com.aspose.email/contenttype)
### getHeaders() {#getHeaders--}
```
public HeaderCollection getHeaders()
```


获取附件的标头集合。

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getName() {#getName--}
```
public final String getName()
```


获取或设置附件名称

**Returns:**
java.lang.String
### getNameEncoding() {#getNameEncoding--}
```
public final Charset getNameEncoding()
```


获取或设置附件名称的编码

**Returns:**
java.nio.charset.Charset
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


获取或设置首选文本编码

**Returns:**
java.nio.charset.Charset
### getTransferEncoding() {#getTransferEncoding--}
```
public final int getTransferEncoding()
```


获取或设置传输编码。

值：传输编码。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmbeddedMessage() {#isEmbeddedMessage--}
```
public final boolean isEmbeddedMessage()
```


获取一个值，指示附件是否为嵌入的消息。

**Returns:**
boolean
### isUri() {#isUri--}
```
public final boolean isUri()
```


获取一个值，指示附件是否为 URI 附件。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


保存指定的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 流。 |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


保存指定的文件名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |

### setContentId(String value) {#setContentId-java.lang.String-}
```
public final void setContentId(String value)
```


获取或设置内容 ID。

值：内容 ID。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setContentStream(InputStream value) {#setContentStream-java.io.InputStream-}
```
public final void setContentStream(InputStream value)
```


获取或设置内容流。

值：内容流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream |  |

### setContentType(ContentType value) {#setContentType-com.aspose.email.ContentType-}
```
public final void setContentType(ContentType value)
```


获取或设置内容的类型。

值：内容的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ContentType](../../com.aspose.email/contenttype) |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


获取或设置附件名称

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameEncoding(Charset value) {#setNameEncoding-java.nio.charset.Charset-}
```
public final void setNameEncoding(Charset value)
```


获取或设置附件名称的编码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


获取或设置首选文本编码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setTransferEncoding(int value) {#setTransferEncoding-int-}
```
public final void setTransferEncoding(int value)
```


获取或设置传输编码。

值：传输编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

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

