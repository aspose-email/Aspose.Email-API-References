---
title: MapiMessageReader
second_title: Aspose.Email for Java API Reference
description: Reads Outlook messages MSG files from a file or a stream.
type: docs
weight: 474
url: /java/com.aspose.email/mapimessagereader/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class MapiMessageReader implements System.IDisposable, Closeable
```

Reads Outlook messages (MSG files) from a file or a stream.

In most cases [MapiMessage.load(String)](../../com.aspose.email/mapimessage\#load-String-) is simpler.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiMessageReader(String path)](#MapiMessageReader-java.lang.String-) | Initializes a new instance of the [MapiMessageReader](../../com.aspose.email/mapimessagereader) class that reads a file. |
| [MapiMessageReader(InputStream stream)](#MapiMessageReader-java.io.InputStream-) | Initializes a new instance of the [MapiMessageReader](../../com.aspose.email/mapimessagereader) class that reads a stream. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Releases the resources used by the reader. |
| [dispose()](#dispose--) | Releases the unmanaged resources used by the MapiMessageReader. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readAttachments()](#readAttachments--) | Reads the attachments of the message. |
| [readMessage()](#readMessage--) | Reads the message. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiMessageReader(String path) {#MapiMessageReader-java.lang.String-}
```
public MapiMessageReader(String path)
```


Initializes a new instance of the [MapiMessageReader](../../com.aspose.email/mapimessagereader) class that reads a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path of the file. |

### MapiMessageReader(InputStream stream) {#MapiMessageReader-java.io.InputStream-}
```
public MapiMessageReader(InputStream stream)
```


Initializes a new instance of the [MapiMessageReader](../../com.aspose.email/mapimessagereader) class that reads a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |

### close() {#close--}
```
public void close()
```


Releases the resources used by the reader.

### dispose() {#dispose--}
```
public final void dispose()
```


Releases the unmanaged resources used by the MapiMessageReader.

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




### readAttachments() {#readAttachments--}
```
public final MapiAttachmentCollection readAttachments()
```


Reads the attachments of the message.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The attachments.
### readMessage() {#readMessage--}
```
public final MapiMessage readMessage()
```


Reads the message.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The message.
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

