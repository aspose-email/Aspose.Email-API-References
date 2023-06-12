---
title: MboxoStorageReader
second_title: Aspose.Email for Java API Reference
description: Represents mboxo format storage reader this format is being used by Eudora.
type: docs
weight: 486
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
| [close()](#close--) |  |
| [createReader(System.IO.Stream stream, boolean leaveOpen)](#createReader-com.aspose.ms.System.IO.Stream-boolean-) | Creates the instance of reader. |
| [createReader(System.IO.Stream stream, MboxLoadOptions options)](#createReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-) | Creates the instance of reader. |
| [createReader(InputStream stream, boolean leaveOpen)](#createReader-java.io.InputStream-boolean-) | Creates the instance of reader. |
| [createReader(InputStream stream, MboxLoadOptions options)](#createReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-) | Creates the instance of reader. |
| [createReader(String fileName, boolean leaveOpen)](#createReader-java.lang.String-boolean-) | Creates the instance of reader. |
| [createReader(String fileName, MboxLoadOptions options)](#createReader-java.lang.String-com.aspose.email.MboxLoadOptions-) | Creates the instance of reader. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [enumerateMessageInfo()](#enumerateMessageInfo--) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [enumerateMessages()](#enumerateMessages--) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [enumerateMessages(EmlLoadOptions options)](#enumerateMessages-com.aspose.email.EmlLoadOptions-) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractMessage(String id, EmlLoadOptions options)](#extractMessage-java.lang.String-com.aspose.email.EmlLoadOptions-) | Get the message from MBOX. |
| [getClass()](#getClass--) |  |
| [getCurrentDataSize()](#getCurrentDataSize--) | Gets the number of bytes that is read by ReadNextMessage method. |
| [getTotalItemsCount()](#getTotalItemsCount--) | Returns the number of messages in a storage. |
| [hashCode()](#hashCode--) |  |
| [nextMessage()](#nextMessage--) | Gets the next message info. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readNextMessage()](#readNextMessage--) | Reads the next message from underlying storage stream. |
| [readNextMessage(EmlLoadOptions options)](#readNextMessage-com.aspose.email.EmlLoadOptions-) | Reads the next message from underlying storage stream. |
| [readNextMessage(String[] fromMarker)](#readNextMessage-java.lang.String---) | Reads the next message from underlying storage stream. |
| [readNextMessage(String[] fromMarker, EmlLoadOptions options)](#readNextMessage-java.lang.String---com.aspose.email.EmlLoadOptions-) | Reads the next message from underlying storage stream. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MboxoStorageReader(InputStream stream, boolean leaveOpen) {#MboxoStorageReader-java.io.InputStream-boolean-}
```
public MboxoStorageReader(InputStream stream, boolean leaveOpen)
```


Initializes a new instance of the [MboxoStorageReader](../../com.aspose.email/mboxostoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| leaveOpen | boolean | if set to  true  leaves the underlying stream open after disposing. |

### MboxoStorageReader(System.IO.Stream stream, boolean leaveOpen) {#MboxoStorageReader-com.aspose.ms.System.IO.Stream-boolean-}
```
public MboxoStorageReader(System.IO.Stream stream, boolean leaveOpen)
```


Initializes a new instance of the [MboxoStorageReader](../../com.aspose.email/mboxostoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream. |
| leaveOpen | boolean | if set to  true  leaves the underlying stream open after disposing. |

### MboxoStorageReader(String fileName, boolean leaveOpen) {#MboxoStorageReader-java.lang.String-boolean-}
```
public MboxoStorageReader(String fileName, boolean leaveOpen)
```


Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| leaveOpen | boolean | if set to  true  leaves the underlying stream open after disposing. |

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

### close() {#close--}
```
public void close()
```




### createReader(System.IO.Stream stream, boolean leaveOpen) {#createReader-com.aspose.ms.System.IO.Stream-boolean-}
```
public static MboxStorageReader createReader(System.IO.Stream stream, boolean leaveOpen)
```


Creates the instance of reader.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream. |
| leaveOpen | boolean | if set to  true  leaves the underlying stream open after disposing. |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(System.IO.Stream stream, MboxLoadOptions options) {#createReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-}
```
public static MboxStorageReader createReader(System.IO.Stream stream, MboxLoadOptions options)
```


Creates the instance of reader.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | additional options when loading a Mbox storage[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(InputStream stream, boolean leaveOpen) {#createReader-java.io.InputStream-boolean-}
```
public static MboxStorageReader createReader(InputStream stream, boolean leaveOpen)
```


Creates the instance of reader.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| leaveOpen | boolean | if set to  true  leaves the underlying stream open after disposing. |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(InputStream stream, MboxLoadOptions options) {#createReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-}
```
public static MboxStorageReader createReader(InputStream stream, MboxLoadOptions options)
```


Creates the instance of reader.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | additional options when loading a Mbox storage[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(String fileName, boolean leaveOpen) {#createReader-java.lang.String-boolean-}
```
public static MboxStorageReader createReader(String fileName, boolean leaveOpen)
```


Creates the instance of reader.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |
| leaveOpen | boolean |  |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(String fileName, MboxLoadOptions options) {#createReader-java.lang.String-com.aspose.email.MboxLoadOptions-}
```
public static MboxStorageReader createReader(String fileName, MboxLoadOptions options)
```


Creates the instance of reader.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | additional options when loading a Mbox storage[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### enumerateMessageInfo() {#enumerateMessageInfo--}
```
public final System.Collections.Generic.IGenericEnumerable<MboxMessageInfo> enumerateMessageInfo()
```


Exposes the enumerator, which supports an iteration of messages in storage.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MboxMessageInfo> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in storage.
### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages()
```


Exposes the enumerator, which supports an iteration of messages in storage.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MailMessage> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in storage.
### enumerateMessages(EmlLoadOptions options) {#enumerateMessages-com.aspose.email.EmlLoadOptions-}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages(EmlLoadOptions options)
```


Exposes the enumerator, which supports an iteration of messages in storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | Specifies [EmlLoadOptions](../../com.aspose.email/emlloadoptions) when reading message from Mbox storage. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MailMessage> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in storage.
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
### extractMessage(String id, EmlLoadOptions options) {#extractMessage-java.lang.String-com.aspose.email.EmlLoadOptions-}
```
public final MailMessage extractMessage(String id, EmlLoadOptions options)
```


Get the message from MBOX.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | String representation of EntryId. |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | Specifies [EmlLoadOptions](../../com.aspose.email/emlloadoptions) when reading message from Mbox storage. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object.
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


Gets the number of bytes that is read by ReadNextMessage method.

**Returns:**
long
### getTotalItemsCount() {#getTotalItemsCount--}
```
public int getTotalItemsCount()
```


Returns the number of messages in a storage.

**Returns:**
int - Returns the number of messages in a storage.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### nextMessage() {#nextMessage--}
```
public MboxMessageInfo nextMessage()
```


Gets the next message info.

**Returns:**
[MboxMessageInfo](../../com.aspose.email/mboxmessageinfo) - A [MboxMessageInfo](../../com.aspose.email/mboxmessageinfo) object if it can be read or  **null**  if no more messages are available.
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
public MailMessage readNextMessage()
```


Reads the next message from underlying storage stream.

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

