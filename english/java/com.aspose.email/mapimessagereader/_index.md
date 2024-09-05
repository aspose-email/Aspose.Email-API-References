---
title: MapiMessageReader
second_title: Aspose.Email for Java API Reference
description: Represents a reader that can read a Microsoft Outlook Message format document.
type: docs
weight: 456
url: /java/com.aspose.email/mapimessagereader/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class MapiMessageReader implements System.IDisposable, Closeable
```

Represents a reader that can read a Microsoft Outlook Message format document.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiMessageReader(String path)](#MapiMessageReader-java.lang.String-) | Initializes a new instance of the MapiMessageReader class for the specified file name. |
| [MapiMessageReader(InputStream stream)](#MapiMessageReader-java.io.InputStream-) | Initializes a new instance of the MapiMessageReader class for the specified stream. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Releases the unmanaged resources used by the MapiMessageReader. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readAttachments()](#readAttachments--) | Extracts the attachment from the Outlook Message files. |
| [readMessage()](#readMessage--) | Parse the current stream and returns the data as a MapiMessage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiMessageReader(String path) {#MapiMessageReader-java.lang.String-}
```
public MapiMessageReader(String path)
```


Initializes a new instance of the MapiMessageReader class for the specified file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The complete file path to be read. |

### MapiMessageReader(InputStream stream) {#MapiMessageReader-java.io.InputStream-}
```
public MapiMessageReader(InputStream stream)
```


Initializes a new instance of the MapiMessageReader class for the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to be read. |

### close() {#close--}
```
public void close()
```




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


Extracts the attachment from the Outlook Message files.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The Attachment collection.
### readMessage() {#readMessage--}
```
public final MapiMessage readMessage()
```


Parse the current stream and returns the data as a MapiMessage.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The MapiMessage from the input stream.
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

