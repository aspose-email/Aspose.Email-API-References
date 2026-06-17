---
title: AttachmentBase
second_title: Aspose.Email for Android via Java API 参考
description: 邮件附件的基类。
type: docs
weight: 53
url: /zh/androidjava/com.aspose.email/attachmentbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public abstract class AttachmentBase implements System.IDisposable, Closeable
```

邮件附件的基类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentId()](#getContentId--) | 获取或设置内容 ID。 |
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
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | 获取或设置内容流。 |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | 获取或设置内容的类型。 |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | 获取或设置传输编码。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### close() {#close--}
```
public void close()
```




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

