---
title: MapiMessageReader
second_title: Aspose.Email for Android via Java API Reference
description:  Represents a reader that can read a Microsoft Outlook Message format document.
type: docs
weight: 261
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
| [readMessage()](#readMessage--) | Parse the current stream and returns the data as a MapiMessage. |
| [readAttachments()](#readAttachments--) | Extracts the attachment from the Outlook Message files. |
| [dispose()](#dispose--) | Releases the unmanaged resources used by the MapiMessageReader. |
| [close()](#close--) |  |
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

### readMessage() {#readMessage--}
```
public final MapiMessage readMessage()
```


Parse the current stream and returns the data as a MapiMessage.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The MapiMessage from the input stream.
### readAttachments() {#readAttachments--}
```
public final MapiAttachmentCollection readAttachments()
```


Extracts the attachment from the Outlook Message files.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The Attachment collection.
### dispose() {#dispose--}
```
public final void dispose()
```


Releases the unmanaged resources used by the MapiMessageReader.

### close() {#close--}
```
public void close()
```




