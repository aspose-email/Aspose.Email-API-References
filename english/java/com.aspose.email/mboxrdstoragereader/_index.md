---
title: MboxrdStorageReader
second_title: Aspose.Email for Java API Reference
description: Represents mboxrd format storage reader this format is being used by Thunderbird and other mail clients.
type: docs
weight: 482
url: /java/com.aspose.email/mboxrdstoragereader/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MboxStorageReader](../../com.aspose.email/mboxstoragereader)
```
public final class MboxrdStorageReader extends MboxStorageReader
```

Represents mboxrd format storage reader, this format is being used by Thunderbird and other mail clients.
## Constructors

| Constructor | Description |
| --- | --- |
| [MboxrdStorageReader(InputStream stream, boolean leaveOpen)](#MboxrdStorageReader-java.io.InputStream-boolean-) | Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class. |
| [MboxrdStorageReader(System.IO.Stream stream, boolean leaveOpen)](#MboxrdStorageReader-com.aspose.ms.System.IO.Stream-boolean-) | Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class. |
| [MboxrdStorageReader(String fileName, boolean leaveOpen)](#MboxrdStorageReader-java.lang.String-boolean-) | Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class. |
| [MboxrdStorageReader(InputStream stream, MboxLoadOptions options)](#MboxrdStorageReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-) | Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class. |
| [MboxrdStorageReader(System.IO.Stream stream, MboxLoadOptions options)](#MboxrdStorageReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-) | Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class. |
| [MboxrdStorageReader(String fileName, MboxLoadOptions options)](#MboxrdStorageReader-java.lang.String-com.aspose.email.MboxLoadOptions-) | Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class. |
## Methods

| Method | Description |
| --- | --- |
| [readNextMessage(String[] fromMarker)](#readNextMessage-java.lang.String---) | Reads the next message from underlying storage stream. |
| [readNextMessage(EmlLoadOptions options)](#readNextMessage-com.aspose.email.EmlLoadOptions-) | Reads the next message from underlying storage stream. |
| [readNextMessage(String[] fromMarker, EmlLoadOptions options)](#readNextMessage-java.lang.String---com.aspose.email.EmlLoadOptions-) | Reads the next message from underlying storage stream. |
| [readNextMessage()](#readNextMessage--) | Reads the next message from underlying storage stream. |
| [getTotalItemsCount()](#getTotalItemsCount--) | Returns the number of messages in a storage. |
### MboxrdStorageReader(InputStream stream, boolean leaveOpen) {#MboxrdStorageReader-java.io.InputStream-boolean-}
```
public MboxrdStorageReader(InputStream stream, boolean leaveOpen)
```


Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| leaveOpen | boolean | if set to  true  leaves the underlying stream open after disposing. |

### MboxrdStorageReader(System.IO.Stream stream, boolean leaveOpen) {#MboxrdStorageReader-com.aspose.ms.System.IO.Stream-boolean-}
```
public MboxrdStorageReader(System.IO.Stream stream, boolean leaveOpen)
```


Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream. |
| leaveOpen | boolean | if set to  true  leaves the underlying stream open after disposing. |

### MboxrdStorageReader(String fileName, boolean leaveOpen) {#MboxrdStorageReader-java.lang.String-boolean-}
```
public MboxrdStorageReader(String fileName, boolean leaveOpen)
```


Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| leaveOpen | boolean | if set to  true  leaves the underlying stream open after disposing. |

### MboxrdStorageReader(InputStream stream, MboxLoadOptions options) {#MboxrdStorageReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-}
```
public MboxrdStorageReader(InputStream stream, MboxLoadOptions options)
```


Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | additional options when loading a Mbox storage[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

### MboxrdStorageReader(System.IO.Stream stream, MboxLoadOptions options) {#MboxrdStorageReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-}
```
public MboxrdStorageReader(System.IO.Stream stream, MboxLoadOptions options)
```


Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | additional options when loading a Mbox storage[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

### MboxrdStorageReader(String fileName, MboxLoadOptions options) {#MboxrdStorageReader-java.lang.String-com.aspose.email.MboxLoadOptions-}
```
public MboxrdStorageReader(String fileName, MboxLoadOptions options)
```


Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | additional options when loading a Mbox storage[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

### readNextMessage(String[] fromMarker) {#readNextMessage-java.lang.String---}
```
public MailMessage readNextMessage(String[] fromMarker)
```


Reads the next message from underlying storage stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fromMarker | java.lang.String[] | Gets the From Marker while parsing the MBox Storage file. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
### readNextMessage(EmlLoadOptions options) {#readNextMessage-com.aspose.email.EmlLoadOptions-}
```
public MailMessage readNextMessage(EmlLoadOptions options)
```


Reads the next message from underlying storage stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | Specifies [EmlLoadOptions](../../com.aspose.email/emlloadoptions) when reading message from Mbox storage. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
### readNextMessage(String[] fromMarker, EmlLoadOptions options) {#readNextMessage-java.lang.String---com.aspose.email.EmlLoadOptions-}
```
public MailMessage readNextMessage(String[] fromMarker, EmlLoadOptions options)
```


Reads the next message from underlying storage stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fromMarker | java.lang.String[] | Gets the From Marker while parsing the MBox Storage file. |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | Specifies [EmlLoadOptions](../../com.aspose.email/emlloadoptions) when reading message from Mbox storage. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
### readNextMessage() {#readNextMessage--}
```
public MailMessage readNextMessage()
```


Reads the next message from underlying storage stream.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
### getTotalItemsCount() {#getTotalItemsCount--}
```
public int getTotalItemsCount()
```


Returns the number of messages in a storage.

**Returns:**
int - Returns the number of messages in a storage.
