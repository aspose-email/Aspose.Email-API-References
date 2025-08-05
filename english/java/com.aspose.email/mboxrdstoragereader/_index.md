---
title: MboxrdStorageReader
second_title: Aspose.Email for Java API Reference
description: Represents mboxrd format storage reader this format is being used by Thunderbird and other mail clients.
type: docs
weight: 509
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
| [MboxrdStorageReader(InputStream stream, MboxLoadOptions options)](#MboxrdStorageReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-) | Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class. |
| [MboxrdStorageReader(System.IO.Stream stream, MboxLoadOptions options)](#MboxrdStorageReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-) | Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class. |
| [MboxrdStorageReader(String fileName, MboxLoadOptions options)](#MboxrdStorageReader-java.lang.String-com.aspose.email.MboxLoadOptions-) | Initializes a new instance of the [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader) class. |
## Methods

| Method | Description |
| --- | --- |
| [cancel()](#cancel--) | This method is used to interrupt a split operation if splitInto is running asynchronously. |
| [close()](#close--) |  |
| [createReader(System.IO.Stream stream, MboxLoadOptions options)](#createReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-) | Creates the instance of reader. |
| [createReader(InputStream stream, MboxLoadOptions options)](#createReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-) | Creates the instance of reader. |
| [createReader(String fileName, MboxLoadOptions options)](#createReader-java.lang.String-com.aspose.email.MboxLoadOptions-) | Creates the instance of reader. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [enumerateMessageInfo()](#enumerateMessageInfo--) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [enumerateMessageInfo(MailQuery query)](#enumerateMessageInfo-com.aspose.email.MailQuery-) | Enumerates the message information that matches the specified query. |
| [enumerateMessageInfo(int startIndex, int count)](#enumerateMessageInfo-int-int-) | Enumerates a specified number of message information entries, starting from the given index. |
| [enumerateMessages()](#enumerateMessages--) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [enumerateMessages(EmlLoadOptions options)](#enumerateMessages-com.aspose.email.EmlLoadOptions-) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [enumerateMessages(EmlLoadOptions options, MailQuery query)](#enumerateMessages-com.aspose.email.EmlLoadOptions-com.aspose.email.MailQuery-) | Enumerates the mail messages that match the specified query, using the provided load options. |
| [enumerateMessages(EmlLoadOptions options, int startIndex, int count)](#enumerateMessages-com.aspose.email.EmlLoadOptions-int-int-) | Enumerates a specified number of mail messages, starting from the given index, using the provided load options. |
| [enumerateMessages(MailQuery query)](#enumerateMessages-com.aspose.email.MailQuery-) | Enumerates the mail messages that match the specified query. |
| [enumerateMessages(int startIndex, int count)](#enumerateMessages-int-int-) | Enumerates a specified number of mail messages, starting from the given index. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractMessage(String id, EmlLoadOptions options)](#extractMessage-java.lang.String-com.aspose.email.EmlLoadOptions-) | Get the message from MBOX. |
| [getClass()](#getClass--) |  |
| [getCurrentDataSize()](#getCurrentDataSize--) | Gets the number of bytes that is read by ReadNextMessage method. |
| [getEmlCopiedEventHandler()](#getEmlCopiedEventHandler--) | Event that occurs after successful copy of a [MailMessage](../../com.aspose.email/mailmessage) object within the \#splitInto(long,String).splitInto(long,String) method. |
| [getEmlCopyingEventHandler()](#getEmlCopyingEventHandler--) | Event that occurs before the [MailMessage](../../com.aspose.email/mailmessage) object copy process, within the \#splitInto(long,String).splitInto(long,String) method. |
| [getMboxFileCreatedEventHandler()](#getMboxFileCreatedEventHandler--) | Event that occurs when a new MBOX file is created during the \#splitInto(long,String).splitInto(long,String) method. |
| [getMboxFileFilledEventHandler()](#getMboxFileFilledEventHandler--) | Event that occurs after filling an MBOX file with data within the \#splitInto(long,String).splitInto(long,String) method. |
| [getTotalItemsCount()](#getTotalItemsCount--) | Returns the number of messages in a storage. |
| [hashCode()](#hashCode--) |  |
| [nextMessage()](#nextMessage--) | Gets the next message info. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readNextMessage()](#readNextMessage--) | Reads the next message from underlying storage stream. |
| [readNextMessage(EmlLoadOptions options)](#readNextMessage-com.aspose.email.EmlLoadOptions-) | Reads the next message from underlying storage stream. |
| [readNextMessage(String[] fromMarker)](#readNextMessage-java.lang.String---) | Reads the next message from underlying storage stream. |
| [readNextMessage(String[] fromMarker, EmlLoadOptions options)](#readNextMessage-java.lang.String---com.aspose.email.EmlLoadOptions-) | Reads the next message from underlying storage stream. |
| [setEmlCopiedEventHandler(MimeItemCopyEventHandler value)](#setEmlCopiedEventHandler-com.aspose.email.MimeItemCopyEventHandler-) | Event that occurs after successful copy of a [MailMessage](../../com.aspose.email/mailmessage) object within the \#splitInto(long,String).splitInto(long,String) method. |
| [setEmlCopyingEventHandler(MimeItemCopyEventHandler value)](#setEmlCopyingEventHandler-com.aspose.email.MimeItemCopyEventHandler-) | Event that occurs before the [MailMessage](../../com.aspose.email/mailmessage) object copy process, within the \#splitInto(long,String).splitInto(long,String) method. |
| [setMboxFileCreatedEventHandler(NewStorageEventHandler value)](#setMboxFileCreatedEventHandler-com.aspose.email.NewStorageEventHandler-) | Event that occurs when a new MBOX file is created during the \#splitInto(long,String).splitInto(long,String) method. |
| [setMboxFileFilledEventHandler(NewStorageEventHandler value)](#setMboxFileFilledEventHandler-com.aspose.email.NewStorageEventHandler-) | Event that occurs after filling an MBOX file with data within the \#splitInto(long,String).splitInto(long,String) method. |
| [splitInto(long chunkSize, String outputPath)](#splitInto-long-java.lang.String-) | Splits the mbox storage into less sized parts. |
| [splitInto(long chunkSize, String outputPath, String partFileNamePrefix)](#splitInto-long-java.lang.String-java.lang.String-) | Splits the mbox storage into less sized parts. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### cancel() {#cancel--}
```
public final void cancel()
```


This method is used to interrupt a split operation if splitInto is running asynchronously.

### close() {#close--}
```
public void close()
```




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
### enumerateMessageInfo(MailQuery query) {#enumerateMessageInfo-com.aspose.email.MailQuery-}
```
public final System.Collections.Generic.IGenericEnumerable<MboxMessageInfo> enumerateMessageInfo(MailQuery query)
```


Enumerates the message information that matches the specified query.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) used to filter messages. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MboxMessageInfo> - An enumerable collection of [MboxMessageInfo](../../com.aspose.email/mboxmessageinfo) instances that match the specified query. The collection may be empty if no messages match.
### enumerateMessageInfo(int startIndex, int count) {#enumerateMessageInfo-int-int-}
```
public final System.Collections.Generic.IGenericEnumerable<MboxMessageInfo> enumerateMessageInfo(int startIndex, int count)
```


Enumerates a specified number of message information entries, starting from the given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | The zero-based index of the first message to retrieve. If  startIndex  is greater than or equal to the total number of items, an ArgumentOutOfRangeException is thrown. |
| count | int | The maximum number of message information entries to retrieve. If set to -1, all messages from the start index will be read. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MboxMessageInfo> - An enumerable collection of [MboxMessageInfo](../../com.aspose.email/mboxmessageinfo) instances starting from the specified index. The collection may be empty if there are no messages in the specified range.
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
### enumerateMessages(EmlLoadOptions options, MailQuery query) {#enumerateMessages-com.aspose.email.EmlLoadOptions-com.aspose.email.MailQuery-}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages(EmlLoadOptions options, MailQuery query)
```


Enumerates the mail messages that match the specified query, using the provided load options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | The [EmlLoadOptions](../../com.aspose.email/emlloadoptions) specifying how EML should be read. |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) used to filter messages. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MailMessage> - An enumerable collection of [MailMessage](../../com.aspose.email/mailmessage) instances that match the specified query. The collection may be empty if no messages match.
### enumerateMessages(EmlLoadOptions options, int startIndex, int count) {#enumerateMessages-com.aspose.email.EmlLoadOptions-int-int-}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages(EmlLoadOptions options, int startIndex, int count)
```


Enumerates a specified number of mail messages, starting from the given index, using the provided load options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | The [EmlLoadOptions](../../com.aspose.email/emlloadoptions) specifying how EML files should be loaded. |
| startIndex | int | The zero-based index of the first message to retrieve. If  startIndex  is greater than or equal to the total number of items, an ArgumentOutOfRangeException is thrown. |
| count | int | The maximum number of messages to retrieve. If set to -1, all messages from the start index will be read. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MailMessage> - An enumerable collection of [MailMessage](../../com.aspose.email/mailmessage) instances starting from the specified index. The collection may be empty if there are no messages in the specified range.
### enumerateMessages(MailQuery query) {#enumerateMessages-com.aspose.email.MailQuery-}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages(MailQuery query)
```


Enumerates the mail messages that match the specified query.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) used to filter messages. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MailMessage> - An enumerable collection of [MailMessage](../../com.aspose.email/mailmessage) instances that match the specified query. The collection may be empty if no messages match.
### enumerateMessages(int startIndex, int count) {#enumerateMessages-int-int-}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages(int startIndex, int count)
```


Enumerates a specified number of mail messages, starting from the given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | The zero-based index of the first message to retrieve. If  startIndex  is greater than or equal to the total number of items, an ArgumentOutOfRangeException is thrown. |
| count | int | The maximum number of messages to retrieve. If set to -1, all messages from the start index will be read. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MailMessage> - An enumerable collection of [MailMessage](../../com.aspose.email/mailmessage) instances starting from the specified index. The collection may be empty if there are no messages in the specified range.
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
### getEmlCopiedEventHandler() {#getEmlCopiedEventHandler--}
```
public final MimeItemCopyEventHandler getEmlCopiedEventHandler()
```


Event that occurs after successful copy of a [MailMessage](../../com.aspose.email/mailmessage) object within the \#splitInto(long,String).splitInto(long,String) method.

**Returns:**
[MimeItemCopyEventHandler](../../com.aspose.email/mimeitemcopyeventhandler)
### getEmlCopyingEventHandler() {#getEmlCopyingEventHandler--}
```
public final MimeItemCopyEventHandler getEmlCopyingEventHandler()
```


Event that occurs before the [MailMessage](../../com.aspose.email/mailmessage) object copy process, within the \#splitInto(long,String).splitInto(long,String) method.

**Returns:**
[MimeItemCopyEventHandler](../../com.aspose.email/mimeitemcopyeventhandler)
### getMboxFileCreatedEventHandler() {#getMboxFileCreatedEventHandler--}
```
public final NewStorageEventHandler getMboxFileCreatedEventHandler()
```


Event that occurs when a new MBOX file is created during the \#splitInto(long,String).splitInto(long,String) method.

**Returns:**
[NewStorageEventHandler](../../com.aspose.email/newstorageeventhandler)
### getMboxFileFilledEventHandler() {#getMboxFileFilledEventHandler--}
```
public final NewStorageEventHandler getMboxFileFilledEventHandler()
```


Event that occurs after filling an MBOX file with data within the \#splitInto(long,String).splitInto(long,String) method.

**Returns:**
[NewStorageEventHandler](../../com.aspose.email/newstorageeventhandler)
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
### setEmlCopiedEventHandler(MimeItemCopyEventHandler value) {#setEmlCopiedEventHandler-com.aspose.email.MimeItemCopyEventHandler-}
```
public final void setEmlCopiedEventHandler(MimeItemCopyEventHandler value)
```


Event that occurs after successful copy of a [MailMessage](../../com.aspose.email/mailmessage) object within the \#splitInto(long,String).splitInto(long,String) method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MimeItemCopyEventHandler](../../com.aspose.email/mimeitemcopyeventhandler) |  |

### setEmlCopyingEventHandler(MimeItemCopyEventHandler value) {#setEmlCopyingEventHandler-com.aspose.email.MimeItemCopyEventHandler-}
```
public final void setEmlCopyingEventHandler(MimeItemCopyEventHandler value)
```


Event that occurs before the [MailMessage](../../com.aspose.email/mailmessage) object copy process, within the \#splitInto(long,String).splitInto(long,String) method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MimeItemCopyEventHandler](../../com.aspose.email/mimeitemcopyeventhandler) |  |

### setMboxFileCreatedEventHandler(NewStorageEventHandler value) {#setMboxFileCreatedEventHandler-com.aspose.email.NewStorageEventHandler-}
```
public final void setMboxFileCreatedEventHandler(NewStorageEventHandler value)
```


Event that occurs when a new MBOX file is created during the \#splitInto(long,String).splitInto(long,String) method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NewStorageEventHandler](../../com.aspose.email/newstorageeventhandler) |  |

### setMboxFileFilledEventHandler(NewStorageEventHandler value) {#setMboxFileFilledEventHandler-com.aspose.email.NewStorageEventHandler-}
```
public final void setMboxFileFilledEventHandler(NewStorageEventHandler value)
```


Event that occurs after filling an MBOX file with data within the \#splitInto(long,String).splitInto(long,String) method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NewStorageEventHandler](../../com.aspose.email/newstorageeventhandler) |  |

### splitInto(long chunkSize, String outputPath) {#splitInto-long-java.lang.String-}
```
public final void splitInto(long chunkSize, String outputPath)
```


Splits the mbox storage into less sized parts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | long | The approximate size of a chunk in bytes. |
| outputPath | java.lang.String | The folder path where chunks will be created. |

### splitInto(long chunkSize, String outputPath, String partFileNamePrefix) {#splitInto-long-java.lang.String-java.lang.String-}
```
public final void splitInto(long chunkSize, String outputPath, String partFileNamePrefix)
```


Splits the mbox storage into less sized parts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | long | The approximate size of a chunk in bytes. |
| outputPath | java.lang.String | The folder path where chunks will be created. |
| partFileNamePrefix | java.lang.String |  |

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

