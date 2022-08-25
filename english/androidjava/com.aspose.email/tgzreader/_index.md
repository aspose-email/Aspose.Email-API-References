---
title: TgzReader
second_title: Aspose.Email for Android via Java API Reference
description:  The mailbox items reader of Zimbra tgz storage.
type: docs
weight: 398
url: /java/com.aspose.email/tgzreader/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class TgzReader implements System.IDisposable, Closeable
```

The mailbox items reader of Zimbra tgz storage.
## Constructors

| Constructor | Description |
| --- | --- |
| [TgzReader(String fileName)](#TgzReader-java.lang.String-) | Initializes a new instance of the [TgzReader](../../com.aspose.email/tgzreader) class. |
## Methods

| Method | Description |
| --- | --- |
| [getCurrentDirectory()](#getCurrentDirectory--) | Gets the current directory name. |
| [getCurrentMessage()](#getCurrentMessage--) | Gets the current message. |
| [exportTo(String path)](#exportTo-java.lang.String-) | Save messages and directory structure using given path. |
| [readNextMessage()](#readNextMessage--) | Reads the next message. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [close()](#close--) |  |
### TgzReader(String fileName) {#TgzReader-java.lang.String-}
```
public TgzReader(String fileName)
```


Initializes a new instance of the [TgzReader](../../com.aspose.email/tgzreader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The filename. |

### getCurrentDirectory() {#getCurrentDirectory--}
```
public final String getCurrentDirectory()
```


Gets the current directory name.

Value: The name of directory.

**Returns:**
java.lang.String
### getCurrentMessage() {#getCurrentMessage--}
```
public final MailMessage getCurrentMessage()
```


Gets the current message.

Value: The [MailMessage](../../com.aspose.email/mailmessage).

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### exportTo(String path) {#exportTo-java.lang.String-}
```
public final void exportTo(String path)
```


Save messages and directory structure using given path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The main directory path to save storage structure. |

### readNextMessage() {#readNextMessage--}
```
public final boolean readNextMessage()
```


Reads the next message.

**Returns:**
boolean - 
### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### close() {#close--}
```
public void close()
```




