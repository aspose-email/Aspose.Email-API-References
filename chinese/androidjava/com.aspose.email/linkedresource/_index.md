---
title: LinkedResource
second_title: Aspose.Email for Android via Java API 参考
description: 表示消息中的嵌入资源。
type: docs
weight: 177
url: /zh/androidjava/com.aspose.email/linkedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase)
```
public class LinkedResource extends AttachmentBase
```

表示消息中的嵌入资源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LinkedResource(String fileName)](#LinkedResource-java.lang.String-) | 初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。 |
| [LinkedResource(String fileName, String mediaType)](#LinkedResource-java.lang.String-java.lang.String-) | 初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。 |
| [LinkedResource(String fileName, ContentType contentType)](#LinkedResource-java.lang.String-com.aspose.email.ContentType-) | 初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。 |
| [LinkedResource(InputStream contentStream)](#LinkedResource-java.io.InputStream-) | 初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。 |
| [LinkedResource(InputStream contentStream, String mediaType)](#LinkedResource-java.io.InputStream-java.lang.String-) | 初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。 |
| [LinkedResource(InputStream contentStream, ContentType contentType)](#LinkedResource-java.io.InputStream-com.aspose.email.ContentType-) | 初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [createLinkedResourceFromString(String content)](#createLinkedResourceFromString-java.lang.String-) | 从字符串创建链接资源。 |
| [createLinkedResourceFromString(String content, ContentType contentType)](#createLinkedResourceFromString-java.lang.String-com.aspose.email.ContentType-) | 从字符串创建链接资源。 |
| [createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType)](#createLinkedResourceFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-) | 从字符串创建链接资源。 |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | 获取 Content-Disposition 标头 |
| [getContentId()](#getContentId--) | 获取或设置内容 ID。 |
| [getContentLink()](#getContentLink--) | 获取或设置资源必须匹配的 URI。 |
| [getContentStream()](#getContentStream--) | 获取或设置内容流。 |
| [getContentType()](#getContentType--) | 获取或设置内容的类型。 |
| [getHeaders()](#getHeaders--) | 获取附件的标头集合。 |
| [getTransferEncoding()](#getTransferEncoding--) | 获取或设置传输编码。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 保存指定的流。 |
| [save(String fileName)](#save-java.lang.String-) | 保存指定的文件名。 |
| [setContentId(String value)](#setContentId-java.lang.String-) | 获取或设置内容 ID。 |
| [setContentLink(URI value)](#setContentLink-java.net.URI-) | 获取或设置资源必须匹配的 URI。 |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | 获取或设置内容流。 |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | 获取或设置内容的类型。 |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | 获取或设置传输编码。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinkedResource(String fileName) {#LinkedResource-java.lang.String-}
```
public LinkedResource(String fileName)
```


初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 保存此资源内容的文件名。 |

### LinkedResource(String fileName, String mediaType) {#LinkedResource-java.lang.String-java.lang.String-}
```
public LinkedResource(String fileName, String mediaType)
```


初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 保存此资源内容的文件名。 |
| mediaType | java.lang.String | Internet 媒体类型。 |

### LinkedResource(String fileName, ContentType contentType) {#LinkedResource-java.lang.String-com.aspose.email.ContentType-}
```
public LinkedResource(String fileName, ContentType contentType)
```


初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 保存此资源内容的文件名。 |
| contentType | [ContentType](../../com.aspose.email/contenttype) | 内容的类型。 |

### LinkedResource(InputStream contentStream) {#LinkedResource-java.io.InputStream-}
```
public LinkedResource(InputStream contentStream)
```


初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentStream | java.io.InputStream | 一个包含此资源内容的流。 |

### LinkedResource(InputStream contentStream, String mediaType) {#LinkedResource-java.io.InputStream-java.lang.String-}
```
public LinkedResource(InputStream contentStream, String mediaType)
```


初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentStream | java.io.InputStream | 一个包含此资源内容的流。 |
| mediaType | java.lang.String | Internet 媒体类型。 |

### LinkedResource(InputStream contentStream, ContentType contentType) {#LinkedResource-java.io.InputStream-com.aspose.email.ContentType-}
```
public LinkedResource(InputStream contentStream, ContentType contentType)
```


初始化 [LinkedResource](../../com.aspose.email/linkedresource) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentStream | java.io.InputStream | 一个包含此资源内容的流。 |
| contentType | [ContentType](../../com.aspose.email/contenttype) | 内容的类型。 |

### close() {#close--}
```
public void close()
```




### createLinkedResourceFromString(String content) {#createLinkedResourceFromString-java.lang.String-}
```
public static LinkedResource createLinkedResourceFromString(String content)
```


从字符串创建链接资源。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 一个包含要在电子邮件附件中加入的资源的字符串。 |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - A LinkedResource object that contains the embedded resource.
### createLinkedResourceFromString(String content, ContentType contentType) {#createLinkedResourceFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static LinkedResource createLinkedResourceFromString(String content, ContentType contentType)
```


从字符串创建链接资源。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 一个包含要在电子邮件附件中加入的资源的字符串。 |
| contentType | [ContentType](../../com.aspose.email/contenttype) | 内容的类型。 |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - A LinkedResource object that contains the embedded resource.
### createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType) {#createLinkedResourceFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-}
```
public static LinkedResource createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType)
```


从字符串创建链接资源。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 一个包含要在电子邮件附件中加入的资源的字符串。 |
| contentEncoding | java.nio.charset.Charset | 内容的编码。 |
| mediaType | java.lang.String | 内容的 MIME 媒体类型。 |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - A LinkedResource object that contains the embedded resource.
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
### getContentLink() {#getContentLink--}
```
public final URI getContentLink()
```


获取或设置资源必须匹配的 URI。

**Returns:**
java.net.URI
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

### setContentLink(URI value) {#setContentLink-java.net.URI-}
```
public final void setContentLink(URI value)
```


获取或设置资源必须匹配的 URI。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.net.URI |  |

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

