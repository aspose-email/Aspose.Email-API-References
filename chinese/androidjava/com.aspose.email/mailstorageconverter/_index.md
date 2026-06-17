---
title: MailStorageConverter
second_title: Aspose.Email for Android via Java API 参考
description: 邮件存储转换器提供存储转换操作的服务。
type: docs
weight: 200
url: /zh/androidjava/com.aspose.email/mailstorageconverter/
---

**Inheritance:**
java.lang.Object
```
public class MailStorageConverter
```

邮件存储转换器提供存储转换操作的服务。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MailStorageConverter()](#MailStorageConverter--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMboxMessageOptions()](#getMboxMessageOptions--) | 在解析 Mbox 存储时获取或设置电子邮件加载选项。 |
| [hashCode()](#hashCode--) |  |
| [mboxToPst(MboxStorageReader mboxStorageReader, PersonalStorage pst, String pstFolderName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-com.aspose.email.MboxStorageReader-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | 将 Mbox 存储转换为 PST。 |
| [mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream)](#mboxToPst-java.io.InputStream-java.io.OutputStream-) | 将 Mbox 存储转换为 PST。 |
| [mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.io.InputStream-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-) | 将 Mbox 存储转换为 PST。 |
| [mboxToPst(InputStream mboxrdDataStream, String pstFileName)](#mboxToPst-java.io.InputStream-java.lang.String-) | 将 Mbox 存储转换为 PST。 |
| [mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.io.InputStream-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | 将 Mbox 存储转换为 PST。 |
| [mboxToPst(String mboxFileName, System.IO.Stream pstDataStream)](#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-) | 将 Mbox 存储转换为 PST。 |
| [mboxToPst(String mboxFileName, System.IO.Stream pstDataStream, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-com.aspose.email.MailStorageConverter.MailHandler-) | 将 Mbox 存储转换为 PST。 |
| [mboxToPst(String mboxFileName, OutputStream pstDataStream)](#mboxToPst-java.lang.String-java.io.OutputStream-) | 将 Mbox 存储转换为 PST。 |
| [mboxToPst(String mboxFileName, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.lang.String-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-) | 将 Mbox 存储转换为 PST。 |
| [mboxToPst(String mboxFileName, String pstFileName)](#mboxToPst-java.lang.String-java.lang.String-) | 将 Mbox 存储转换为 PST。 |
| [mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.lang.String-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | 将 Mbox 存储转换为 PST。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMboxMessageOptions(EmlLoadOptions value)](#setMboxMessageOptions-com.aspose.email.EmlLoadOptions-) | 在解析 Mbox 存储时获取或设置电子邮件加载选项。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailStorageConverter() {#MailStorageConverter--}
```
public MailStorageConverter()
```


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
### getMboxMessageOptions() {#getMboxMessageOptions--}
```
public static EmlLoadOptions getMboxMessageOptions()
```


在解析 Mbox 存储时获取或设置电子邮件加载选项。

值：指定加载选项的 [EmlLoadOptions](../../com.aspose.email/emlloadoptions)。

**Returns:**
[EmlLoadOptions](../../com.aspose.email/emlloadoptions)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mboxToPst(MboxStorageReader mboxStorageReader, PersonalStorage pst, String pstFolderName, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-com.aspose.email.MboxStorageReader-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static void mboxToPst(MboxStorageReader mboxStorageReader, PersonalStorage pst, String pstFolderName, MailStorageConverter.MailHandler mailHandler)
```


将 Mbox 存储转换为 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mboxStorageReader | [MboxStorageReader](../../com.aspose.email/mboxstoragereader) | 一个表示基于 mbox 的邮件存储读取器的 [MboxStorageReader](../../com.aspose.email/mboxstoragereader)。 |
| pst | [PersonalStorage](../../com.aspose.email/personalstorage) | 一个表示 pst 存储的 [PersonalStorage](../../com.aspose.email/personalstorage)。 |
| pstFolderName | java.lang.String | 文件夹名称，位于 pst 根目录，用于添加 Mbox 消息。如果此文件夹不存在，将会创建。如果文件夹已存在且不为空，新消息将添加到已有的消息中。 |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | 每读取一条来自 Mbox 的消息，都会调用 [MailHandler](../../com.aspose.email/mailhandler) 委托。 |

### mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream) {#mboxToPst-java.io.InputStream-java.io.OutputStream-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream)
```


将 Mbox 存储转换为 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | 一个表示 Mbox 格式数据的 java.io.InputStream。 |
| pstDataStream | java.io.OutputStream | 一个表示 Pst 格式数据的 java.io.InputStream。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.io.InputStream-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)
```


将 Mbox 存储转换为 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | 一个表示 Mbox 格式数据的 java.io.InputStream。 |
| pstDataStream | java.io.OutputStream | 一个表示 Pst 格式数据的 java.io.InputStream。 |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | 每读取一条来自 Mbox 的消息，都会调用 [MailHandler](../../com.aspose.email/mailhandler) 委托。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(InputStream mboxrdDataStream, String pstFileName) {#mboxToPst-java.io.InputStream-java.lang.String-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, String pstFileName)
```


将 Mbox 存储转换为 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | 一个表示 Mbox 格式数据的 java.io.InputStream。 |
|  | pstFileName | java.lang.String | PST 文件名。 |

--------------------

此外，使用打开/读取、创建/写入模式创建 FileStream 时可能抛出的相同异常集合也会被抛出。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.io.InputStream-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler)
```


将 Mbox 存储转换为 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | 一个表示 Mbox 格式数据的 java.io.InputStream。 |
| pstFileName | java.lang.String | PST 文件名。 |
|  | mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | 每读取一条来自 Mbox 的消息，都会调用 [MailHandler](../../com.aspose.email/mailhandler) 委托。 |

--------------------

此外，使用打开/读取、创建/写入模式创建 FileStream 时可能抛出的相同异常集合也会被抛出。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, System.IO.Stream pstDataStream) {#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public static PersonalStorage mboxToPst(String mboxFileName, System.IO.Stream pstDataStream)
```


将 Mbox 存储转换为 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox 文件名。 |
|  | pstDataStream | com.aspose.ms.System.IO.Stream | 一个表示 Pst 格式数据的 Stream。 |

--------------------

此外，使用打开/读取、创建/写入模式创建 FileStream 时可能抛出的相同异常集合也会被抛出。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, System.IO.Stream pstDataStream, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(String mboxFileName, System.IO.Stream pstDataStream, MailStorageConverter.MailHandler mailHandler)
```


将 Mbox 存储转换为 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox 文件名。 |
| pstDataStream | com.aspose.ms.System.IO.Stream | 一个表示 Pst 格式数据的 Stream。 |
|  | mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | 每读取一条来自 Mbox 的消息，都会调用 [MailHandler](../../com.aspose.email/mailhandler) 委托。 |

--------------------

此外，使用打开/读取、创建/写入模式创建 FileStream 时可能抛出的相同异常集合也会被抛出。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, OutputStream pstDataStream) {#mboxToPst-java.lang.String-java.io.OutputStream-}
```
public static PersonalStorage mboxToPst(String mboxFileName, OutputStream pstDataStream)
```


将 Mbox 存储转换为 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox 文件名。 |
|  | pstDataStream | java.io.OutputStream | 一个表示 Pst 格式数据的 java.io.InputStream。 |

--------------------

此外，使用打开/读取、创建/写入模式创建 FileStream 时可能抛出的相同异常集合也会被抛出。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.lang.String-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(String mboxFileName, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)
```


将 Mbox 存储转换为 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox 文件名。 |
| pstDataStream | java.io.OutputStream | 一个表示 Pst 格式数据的 java.io.InputStream。 |
|  | mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | 每读取一条来自 Mbox 的消息，都会调用 [MailHandler](../../com.aspose.email/mailhandler) 委托。 |

--------------------

此外，使用打开/读取、创建/写入模式创建 FileStream 时可能抛出的相同异常集合也会被抛出。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, String pstFileName) {#mboxToPst-java.lang.String-java.lang.String-}
```
public static PersonalStorage mboxToPst(String mboxFileName, String pstFileName)
```


将 Mbox 存储转换为 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox 文件名。 |
|  | pstFileName | java.lang.String | PST 文件名。 |

--------------------

此外，使用打开/读取、创建/写入模式创建 FileStream 时可能抛出的相同异常集合也会被抛出。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.lang.String-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler)
```


将 Mbox 存储转换为 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox 文件名。 |
| pstFileName | java.lang.String | PST 文件名。 |
|  | mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | 每读取一条来自 Mbox 的消息，都会调用 [MailHandler](../../com.aspose.email/mailhandler) 委托。 |

--------------------

此外，使用打开/读取、创建/写入模式创建 FileStream 时可能抛出的相同异常集合也会被抛出。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMboxMessageOptions(EmlLoadOptions value) {#setMboxMessageOptions-com.aspose.email.EmlLoadOptions-}
```
public static void setMboxMessageOptions(EmlLoadOptions value)
```


在解析 Mbox 存储时获取或设置电子邮件加载选项。

值：指定加载选项的 [EmlLoadOptions](../../com.aspose.email/emlloadoptions)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) |  |

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

