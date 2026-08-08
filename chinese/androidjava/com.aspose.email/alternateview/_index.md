---
title: AlternateView
second_title: Aspose.Email for Android via Java API 参考
description: 表示查看消息的格式。
type: docs
weight: 11
url: /zh/androidjava/com.aspose.email/alternateview/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase)
```
public class AlternateView extends AttachmentBase
```

表示查看消息的格式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AlternateView(String fileName)](#AlternateView-java.lang.String-) | 初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。 |
| [AlternateView(String fileName, String mediaType)](#AlternateView-java.lang.String-java.lang.String-) | 初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。 |
| [AlternateView(String fileName, ContentType contentType)](#AlternateView-java.lang.String-com.aspose.email.ContentType-) | 初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。 |
| [AlternateView(InputStream contentStream)](#AlternateView-java.io.InputStream-) | 初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。 |
| [AlternateView(InputStream contentStream, String mediaType)](#AlternateView-java.io.InputStream-java.lang.String-) | 初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。 |
| [AlternateView(InputStream contentStream, ContentType contentType)](#AlternateView-java.io.InputStream-com.aspose.email.ContentType-) | 初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [createAlternateViewFromString(String content)](#createAlternateViewFromString-java.lang.String-) | 使用字符串中指定的内容创建一个 AlternateView。 |
| [createAlternateViewFromString(String content, ContentType contentType)](#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-) | 使用字符串中指定的内容创建一个 AlternateView。 |
| [createAlternateViewFromString(String content, ContentType contentType, int transferencoding)](#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-int-) | 使用字符串中指定的内容创建一个 AlternateView。 |
| [createAlternateViewFromString(String content, Charset contentEncoding, String mediaType)](#createAlternateViewFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-) | 使用字符串中指定的内容创建一个 AlternateView。 |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseUri()](#getBaseUri--) | 获取或设置基础 URI。 |
| [getClass()](#getClass--) |  |
| [getContentId()](#getContentId--) | 获取或设置内容 ID。 |
| [getContentStream()](#getContentStream--) | 获取或设置内容流。 |
| [getContentType()](#getContentType--) | 获取或设置内容的类型。 |
| [getHeaders()](#getHeaders--) | 获取附件的标头集合。 |
| [getLinkedResources()](#getLinkedResources--) | 获取此备用视图引用的嵌入资源集合。 |
| [getTransferEncoding()](#getTransferEncoding--) | 获取或设置传输编码。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 保存指定的流。 |
| [save(String fileName)](#save-java.lang.String-) | 保存指定的文件名。 |
| [setBaseUri(URI value)](#setBaseUri-java.net.URI-) | 获取或设置基础 URI。 |
| [setContentId(String value)](#setContentId-java.lang.String-) | 获取或设置内容 ID。 |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | 获取或设置内容流。 |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | 获取或设置内容的类型。 |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | 获取或设置传输编码。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AlternateView(String fileName) {#AlternateView-java.lang.String-}
```
public AlternateView(String fileName)
```


初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |

### AlternateView(String fileName, String mediaType) {#AlternateView-java.lang.String-java.lang.String-}
```
public AlternateView(String fileName, String mediaType)
```


初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
| mediaType | java.lang.String | Internet 媒体类型。 |

### AlternateView(String fileName, ContentType contentType) {#AlternateView-java.lang.String-com.aspose.email.ContentType-}
```
public AlternateView(String fileName, ContentType contentType)
```


初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
| contentType | [ContentType](../../com.aspose.email/contenttype) | 内容类型。 |

### AlternateView(InputStream contentStream) {#AlternateView-java.io.InputStream-}
```
public AlternateView(InputStream contentStream)
```


初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentStream | java.io.InputStream | 内容流。 |

### AlternateView(InputStream contentStream, String mediaType) {#AlternateView-java.io.InputStream-java.lang.String-}
```
public AlternateView(InputStream contentStream, String mediaType)
```


初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentStream | java.io.InputStream | 内容流。 |
| mediaType | java.lang.String | Internet 媒体类型。 |

### AlternateView(InputStream contentStream, ContentType contentType) {#AlternateView-java.io.InputStream-com.aspose.email.ContentType-}
```
public AlternateView(InputStream contentStream, ContentType contentType)
```


初始化 [AlternateView](../../com.aspose.email/alternateview) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentStream | java.io.InputStream | 内容流。 |
| contentType | [ContentType](../../com.aspose.email/contenttype) | 内容类型。 |

### close() {#close--}
```
public void close()
```




### createAlternateViewFromString(String content) {#createAlternateViewFromString-java.lang.String-}
```
public static AlternateView createAlternateViewFromString(String content)
```


使用字符串中指定的内容创建一个 AlternateView。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 包含内容的字符串。 |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
### createAlternateViewFromString(String content, ContentType contentType) {#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static AlternateView createAlternateViewFromString(String content, ContentType contentType)
```


使用字符串中指定的内容创建一个 AlternateView。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 包含内容的字符串。 |
| contentType | [ContentType](../../com.aspose.email/contenttype) | 内容类型。 |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
### createAlternateViewFromString(String content, ContentType contentType, int transferencoding) {#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-int-}
```
public static AlternateView createAlternateViewFromString(String content, ContentType contentType, int transferencoding)
```


使用字符串中指定的内容创建一个 AlternateView。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 包含内容的字符串。 |
| contentType | [ContentType](../../com.aspose.email/contenttype) | 内容类型。 |
| transferencoding | int | 传输编码。 |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
### createAlternateViewFromString(String content, Charset contentEncoding, String mediaType) {#createAlternateViewFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-}
```
public static AlternateView createAlternateViewFromString(String content, Charset contentEncoding, String mediaType)
```


使用字符串中指定的内容创建一个 AlternateView。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 包含内容的字符串。 |
| contentEncoding | java.nio.charset.Charset | 内容的编码。 |
| mediaType | java.lang.String | Internet 媒体类型。 |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
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
### getBaseUri() {#getBaseUri--}
```
public final URI getBaseUri()
```


获取或设置基础 URI。

值：基础 URI。

**Returns:**
java.net.URI
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getLinkedResources() {#getLinkedResources--}
```
public final LinkedResourceCollection getLinkedResources()
```


获取此备用视图引用的嵌入资源集合。

值：链接资源。

**Returns:**
[LinkedResourceCollection](../../com.aspose.email/linkedresourcecollection)
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

### setBaseUri(URI value) {#setBaseUri-java.net.URI-}
```
public final void setBaseUri(URI value)
```


获取或设置基础 URI。

值：基础 URI。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.net.URI |  |

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

