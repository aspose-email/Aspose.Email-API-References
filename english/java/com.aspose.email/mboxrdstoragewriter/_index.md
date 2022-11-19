---
title: MboxrdStorageWriter
second_title: Aspose.Email for Java API Reference
description: Represents mboxrd format storage writer this format is being used by Thunderbird and other mail clients.
type: docs
weight: 483
url: /java/com.aspose.email/mboxrdstoragewriter/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MboxStorageWriter](../../com.aspose.email/mboxstoragewriter)
```
public final class MboxrdStorageWriter extends MboxStorageWriter
```

Represents mboxrd format storage writer, this format is being used by Thunderbird and other mail clients.
## Constructors

| Constructor | Description |
| --- | --- |
| [MboxrdStorageWriter(OutputStream stream, boolean leaveOpen)](#MboxrdStorageWriter-java.io.OutputStream-boolean-) | Initializes a new instance of the [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) class. |
| [MboxrdStorageWriter(System.IO.Stream stream, boolean leaveOpen)](#MboxrdStorageWriter-com.aspose.ms.System.IO.Stream-boolean-) | Initializes a new instance of the [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) class. |
| [MboxrdStorageWriter(String fileName, boolean leaveOpen)](#MboxrdStorageWriter-java.lang.String-boolean-) | Initializes a new instance of the [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) class. |
| [MboxrdStorageWriter(String fileName)](#MboxrdStorageWriter-java.lang.String-) | Constructor for MboxrdStorageWriter. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | flush. |
| [getBaseStream()](#getBaseStream--) | Gets the base stream. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeMessage(MailMessage message)](#writeMessage-com.aspose.email.MailMessage-) | Writes the message to underlying storage stream. |
| [writeMessage(MailMessage message, String[] fromMarker)](#writeMessage-com.aspose.email.MailMessage-java.lang.String---) | Writes the message to underlying storage stream. |
### MboxrdStorageWriter(OutputStream stream, boolean leaveOpen) {#MboxrdStorageWriter-java.io.OutputStream-boolean-}
```
public MboxrdStorageWriter(OutputStream stream, boolean leaveOpen)
```


Initializes a new instance of the [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream. |
| leaveOpen | boolean | if set to  true  leaves the underlying stream open after disposing. |

### MboxrdStorageWriter(System.IO.Stream stream, boolean leaveOpen) {#MboxrdStorageWriter-com.aspose.ms.System.IO.Stream-boolean-}
```
public MboxrdStorageWriter(System.IO.Stream stream, boolean leaveOpen)
```


Initializes a new instance of the [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream. |
| leaveOpen | boolean | if set to  true  leaves the underlying stream open after disposing. |

### MboxrdStorageWriter(String fileName, boolean leaveOpen) {#MboxrdStorageWriter-java.lang.String-boolean-}
```
public MboxrdStorageWriter(String fileName, boolean leaveOpen)
```


Initializes a new instance of the [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| leaveOpen | boolean | if set to  true  leaves the underlying stream open after disposing. |

### MboxrdStorageWriter(String fileName) {#MboxrdStorageWriter-java.lang.String-}
```
public MboxrdStorageWriter(String fileName)
```


Constructor for MboxrdStorageWriter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | a java.lang.String object. |

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
### flush() {#flush--}
```
public void flush()
```


flush.

### getBaseStream() {#getBaseStream--}
```
public InputStream getBaseStream()
```


Gets the base stream.

Value: The base stream.

**Returns:**
java.io.InputStream
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

### writeMessage(MailMessage message) {#writeMessage-com.aspose.email.MailMessage-}
```
public void writeMessage(MailMessage message)
```


Writes the message to underlying storage stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message to write to. |

### writeMessage(MailMessage message, String[] fromMarker) {#writeMessage-com.aspose.email.MailMessage-java.lang.String---}
```
public void writeMessage(MailMessage message, String[] fromMarker)
```


Writes the message to underlying storage stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message to write to. |
| fromMarker | java.lang.String[] | Gets the From Marker while writing the MBox Storage file. |

