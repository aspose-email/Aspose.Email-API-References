---
title: MboxoStorageReader
second_title: Aspose.Email for Android via Java API Reference
description:  Represents mboxo format storage reader this format is being used by Eudora.
type: docs
weight: 294
url: /java/com.aspose.email/mboxostoragereader/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MboxStorageReader](../../com.aspose.email/mboxstoragereader)
```
public final class MboxoStorageReader extends MboxStorageReader
```

Represents mboxo format storage reader, this format is being used by Eudora.
## Constructors

| Constructor | Description |
| --- | --- |
| [MboxoStorageReader(InputStream stream, boolean leaveOpen)](#MboxoStorageReader-java.io.InputStream-boolean-) | Initializes a new instance of the [MboxoStorageReader](../../com.aspose.email/mboxostoragereader) class. |
| [MboxoStorageReader(System.IO.Stream stream, boolean leaveOpen)](#MboxoStorageReader-com.aspose.ms.System.IO.Stream-boolean-) | Initializes a new instance of the [MboxoStorageReader](../../com.aspose.email/mboxostoragereader) class. |
| [MboxoStorageReader(String fileName, boolean leaveOpen)](#MboxoStorageReader-java.lang.String-boolean-) | Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class. |
| [MboxoStorageReader(InputStream stream, MboxLoadOptions options)](#MboxoStorageReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-) | Initializes a new instance of the [MboxoStorageReader](../../com.aspose.email/mboxostoragereader) class. |
| [MboxoStorageReader(System.IO.Stream stream, MboxLoadOptions options)](#MboxoStorageReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-) | Initializes a new instance of the [MboxoStorageReader](../../com.aspose.email/mboxostoragereader) class. |
| [MboxoStorageReader(String fileName, MboxLoadOptions options)](#MboxoStorageReader-java.lang.String-com.aspose.email.MboxLoadOptions-) | Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class. |
## Methods

| Method | Description |
| --- | --- |
| [getTotalItemsCount()](#getTotalItemsCount--) | Returns the number of messages in a storage. |
| [readNextMessage()](#readNextMessage--) | Reads the next message from underlying storage stream. |
| [readNextMessage(String[] fromMarker)](#readNextMessage-java.lang.String---) | Reads the next message from underlying storage stream. |
### MboxoStorageReader(InputStream stream, boolean leaveOpen) {#MboxoStorageReader-java.io.InputStream-boolean-}
```
public MboxoStorageReader(InputStream stream, boolean leaveOpen)
```


Initializes a new instance of the [MboxoStorageReader](../../com.aspose.email/mboxostoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| leaveOpen | boolean | if set to \`\`\` true \`\`\` leaves the underlying stream open after disposing. |

### MboxoStorageReader(System.IO.Stream stream, boolean leaveOpen) {#MboxoStorageReader-com.aspose.ms.System.IO.Stream-boolean-}
```
public MboxoStorageReader(System.IO.Stream stream, boolean leaveOpen)
```


Initializes a new instance of the [MboxoStorageReader](../../com.aspose.email/mboxostoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream. |
| leaveOpen | boolean | if set to \`\`\` true \`\`\` leaves the underlying stream open after disposing. |

### MboxoStorageReader(String fileName, boolean leaveOpen) {#MboxoStorageReader-java.lang.String-boolean-}
```
public MboxoStorageReader(String fileName, boolean leaveOpen)
```


Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| leaveOpen | boolean | if set to \`\`\` true \`\`\` leaves the underlying stream open after disposing. |

### MboxoStorageReader(InputStream stream, MboxLoadOptions options) {#MboxoStorageReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-}
```
public MboxoStorageReader(InputStream stream, MboxLoadOptions options)
```


Initializes a new instance of the [MboxoStorageReader](../../com.aspose.email/mboxostoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | additional options when loading a Mbox storage[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

### MboxoStorageReader(System.IO.Stream stream, MboxLoadOptions options) {#MboxoStorageReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-}
```
public MboxoStorageReader(System.IO.Stream stream, MboxLoadOptions options)
```


Initializes a new instance of the [MboxoStorageReader](../../com.aspose.email/mboxostoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | additional options when loading a Mbox storage[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

### MboxoStorageReader(String fileName, MboxLoadOptions options) {#MboxoStorageReader-java.lang.String-com.aspose.email.MboxLoadOptions-}
```
public MboxoStorageReader(String fileName, MboxLoadOptions options)
```


Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | additional options when loading a Mbox storage[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

### getTotalItemsCount() {#getTotalItemsCount--}
```
public int getTotalItemsCount()
```


Returns the number of messages in a storage.

**Returns:**
int - Returns the number of messages in a storage.
### readNextMessage() {#readNextMessage--}
```
public MailMessage readNextMessage()
```


Reads the next message from underlying storage stream.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or \`\`\` **null** \`\`\` if no more messages are available.
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
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or \`\`\` **null** \`\`\` if no more messages are available.
