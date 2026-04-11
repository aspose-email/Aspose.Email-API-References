---
title: MboxStorageReader
second_title: Aspose.Email for Android via Java API 参考
description: 任何基于 mbox 的邮件存储读取器的基类。
type: docs
weight: 296
url: /zh/androidjava/com.aspose.email/mboxstoragereader/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public abstract class MboxStorageReader implements System.IDisposable, Closeable
```

任何基于 mbox 的邮件存储读取器的基类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [createReader(System.IO.Stream stream, boolean leaveOpen)](#createReader-com.aspose.ms.System.IO.Stream-boolean-) | 创建读取器的实例。 |
| [createReader(System.IO.Stream stream, MboxLoadOptions options)](#createReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-) | 创建读取器的实例。 |
| [createReader(InputStream stream, boolean leaveOpen)](#createReader-java.io.InputStream-boolean-) | 创建读取器的实例。 |
| [createReader(InputStream stream, MboxLoadOptions options)](#createReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-) | 创建读取器的实例。 |
| [createReader(String fileName, boolean leaveOpen)](#createReader-java.lang.String-boolean-) | 创建读取器的实例。 |
| [createReader(String fileName, MboxLoadOptions options)](#createReader-java.lang.String-com.aspose.email.MboxLoadOptions-) | 创建读取器的实例。 |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [enumerateMessages()](#enumerateMessages--) | 公开枚举器，支持对存储中消息的迭代。 |
| [enumerateMessages(EmlLoadOptions options)](#enumerateMessages-com.aspose.email.EmlLoadOptions-) | 公开枚举器，支持对存储中消息的迭代。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCurrentDataSize()](#getCurrentDataSize--) | 获取由 ReadNextMessage 方法读取的字节数。 |
| [getTotalItemsCount()](#getTotalItemsCount--) | 返回存储中的消息数量。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readNextMessage()](#readNextMessage--) | 从底层存储流读取下一条消息。 |
| [readNextMessage(EmlLoadOptions options)](#readNextMessage-com.aspose.email.EmlLoadOptions-) | 从底层存储流读取下一条消息。 |
| [readNextMessage(String[] fromMarker)](#readNextMessage-java.lang.String---) | 从底层存储流读取下一条消息。 |
| [readNextMessage(String[] fromMarker, EmlLoadOptions options)](#readNextMessage-java.lang.String---com.aspose.email.EmlLoadOptions-) | 从底层存储流读取下一条消息。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### close() {#close--}
```
public void close()
```




### createReader(System.IO.Stream stream, boolean leaveOpen) {#createReader-com.aspose.ms.System.IO.Stream-boolean-}
```
public static MboxStorageReader createReader(System.IO.Stream stream, boolean leaveOpen)
```


创建读取器的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 流。 |
| leaveOpen | boolean | 如果设置为 true，则在释放后保持底层流打开。 |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(System.IO.Stream stream, MboxLoadOptions options) {#createReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-}
```
public static MboxStorageReader createReader(System.IO.Stream stream, MboxLoadOptions options)
```


创建读取器的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 流。 |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | 加载 Mbox 存储时的附加选项[MboxLoadOptions](../../com.aspose.email/mboxloadoptions)。 |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(InputStream stream, boolean leaveOpen) {#createReader-java.io.InputStream-boolean-}
```
public static MboxStorageReader createReader(InputStream stream, boolean leaveOpen)
```


创建读取器的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 流。 |
| leaveOpen | boolean | 如果设置为 true，则在释放后保持底层流打开。 |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(InputStream stream, MboxLoadOptions options) {#createReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-}
```
public static MboxStorageReader createReader(InputStream stream, MboxLoadOptions options)
```


创建读取器的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 流。 |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | 加载 Mbox 存储时的附加选项[MboxLoadOptions](../../com.aspose.email/mboxloadoptions)。 |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(String fileName, boolean leaveOpen) {#createReader-java.lang.String-boolean-}
```
public static MboxStorageReader createReader(String fileName, boolean leaveOpen)
```


创建读取器的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String |  |
| leaveOpen | boolean |  |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(String fileName, MboxLoadOptions options) {#createReader-java.lang.String-com.aspose.email.MboxLoadOptions-}
```
public static MboxStorageReader createReader(String fileName, MboxLoadOptions options)
```


创建读取器的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | 加载 Mbox 存储时的附加选项[MboxLoadOptions](../../com.aspose.email/mboxloadoptions)。 |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### dispose() {#dispose--}
```
public final void dispose()
```


执行应用程序定义的任务，以释放、释放或重置非托管资源。

### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages()
```


公开枚举器，支持对存储中消息的迭代。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MailMessage> -  System.Collections.Generic.IEnumerableltTgt，表示遍历存储中消息的枚举器。
### enumerateMessages(EmlLoadOptions options) {#enumerateMessages-com.aspose.email.EmlLoadOptions-}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages(EmlLoadOptions options)
```


公开枚举器，支持对存储中消息的迭代。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | 在从 Mbox 存储读取消息时指定[EmlLoadOptions](../../com.aspose.email/emlloadoptions)。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MailMessage> -  System.Collections.Generic.IEnumerableltTgt，表示遍历存储中消息的枚举器。
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
### getCurrentDataSize() {#getCurrentDataSize--}
```
public final long getCurrentDataSize()
```


获取由 ReadNextMessage 方法读取的字节数。

**Returns:**
long
### getTotalItemsCount() {#getTotalItemsCount--}
```
public abstract int getTotalItemsCount()
```


返回存储中的消息数量。

**Returns:**
int - 返回存储中的消息数量。
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




### readNextMessage() {#readNextMessage--}
```
public abstract MailMessage readNextMessage()
```


从底层存储流读取下一条消息。

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
### readNextMessage(EmlLoadOptions options) {#readNextMessage-com.aspose.email.EmlLoadOptions-}
```
public abstract MailMessage readNextMessage(EmlLoadOptions options)
```


从底层存储流读取下一条消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | 在从 Mbox 存储读取消息时指定[EmlLoadOptions](../../com.aspose.email/emlloadoptions)。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
### readNextMessage(String[] fromMarker) {#readNextMessage-java.lang.String---}
```
public abstract MailMessage readNextMessage(String[] fromMarker)
```


从底层存储流读取下一条消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fromMarker | java.lang.String[] | 在解析 MBox 存储文件时获取 From 标记。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
### readNextMessage(String[] fromMarker, EmlLoadOptions options) {#readNextMessage-java.lang.String---com.aspose.email.EmlLoadOptions-}
```
public abstract MailMessage readNextMessage(String[] fromMarker, EmlLoadOptions options)
```


从底层存储流读取下一条消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fromMarker | java.lang.String[] | 在解析 MBox 存储文件时获取 From 标记。 |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | 在从 Mbox 存储读取消息时指定[EmlLoadOptions](../../com.aspose.email/emlloadoptions)。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
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

