---
title: TgzReader
second_title: Aspose.Email for Java API Reference
description: The mailbox items reader of Zimbra tgz storage.
type: docs
weight: 665
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
| [close()](#close--) |  |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportTo(String path)](#exportTo-java.lang.String-) | Save messages and directory structure using given path. |
| [getClass()](#getClass--) |  |
| [getCurrentDirectory()](#getCurrentDirectory--) | Gets the current directory name. |
| [getCurrentMessage()](#getCurrentMessage--) | Gets the current message. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readNextMessage()](#readNextMessage--) | Reads the next message. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TgzReader(String fileName) {#TgzReader-java.lang.String-}
```
public TgzReader(String fileName)
```


Initializes a new instance of the [TgzReader](../../com.aspose.email/tgzreader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The filename. |

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportTo(String path) {#exportTo-java.lang.String-}
```
public final void exportTo(String path)
```


Save messages and directory structure using given path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The main directory path to save storage structure. |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
public final boolean readNextMessage()
```


Reads the next message.

**Returns:**
boolean - 
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

