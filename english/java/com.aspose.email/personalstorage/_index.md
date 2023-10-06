---
title: PersonalStorage
second_title: Aspose.Email for Java API Reference
description: Represents Personal Storage Table .pst file.
type: docs
weight: 559
url: /java/com.aspose.email/personalstorage/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class PersonalStorage implements System.IDisposable, Closeable
```

Represents Personal Storage Table (.pst) file.
## Constructors

| Constructor | Description |
| --- | --- |
| [PersonalStorage(TraversalExceptionsCallback callback)](#PersonalStorage-com.aspose.email.TraversalExceptionsCallback-) | Initializes a new instance of the [PersonalStorage](../../com.aspose.email/personalstorage) class. |
## Fields

| Field | Description |
| --- | --- |
| [ItemMoved](#ItemMoved) | Occurs when an item is moved to the another folder. |
| [StorageProcessed](#StorageProcessed) | Occurs in splitting and merging operations when a new chunk of pst is created or the next file is processed and is to be merged. |
| [StorageProcessing](#StorageProcessing) | Occurs before the srorage is processed. |
## Methods

| Method | Description |
| --- | --- |
| [canWrite()](#canWrite--) | Gets a value indicating whether the current pst supports writing. |
| [changeMessage(String entryId, MapiPropertyCollection updatedProperties)](#changeMessage-java.lang.String-com.aspose.email.MapiPropertyCollection-) | Changes the message properties. |
| [close()](#close--) |  |
| [convertTo(int format)](#convertTo-int-) | Converts the current object to the specified format. |
| [create(System.IO.Stream stream, int version)](#create-com.aspose.ms.System.IO.Stream-int-) | Creates the PST in a stream. |
| [create(System.IO.Stream stream, int version, boolean leaveStreamOpen)](#create-com.aspose.ms.System.IO.Stream-int-boolean-) | Creates the PST in a stream. |
| [create(OutputStream stream, int version)](#create-java.io.OutputStream-int-) | Creates the PST in a stream. |
| [create(OutputStream stream, int version, boolean leaveStreamOpen)](#create-java.io.OutputStream-int-boolean-) | Creates the PST in a stream. |
| [create(OutputStream stream, int blockSize, int version)](#create-java.io.OutputStream-int-int-) | Creates the PST in a stream. |
| [create(String fileName, int version)](#create-java.lang.String-int-) | Creates the new PST file with the specified file name. |
| [createPredefinedFolder(String name, int defaultFolder)](#createPredefinedFolder-java.lang.String-int-) | Creates the standard interpersonal message (IPM) folder. |
| [createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy)](#createPredefinedFolder-java.lang.String-int-boolean-) | Creates the standard interpersonal message (IPM) folder. |
| [deleteItem(String entryId)](#deleteItem-java.lang.String-) | Deletes the item (folder or message) by it's entryId |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [enumerateMessages(String entryId)](#enumerateMessages-java.lang.String-) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [enumerateMessages(String entryId, int startIndex, int count)](#enumerateMessages-java.lang.String-int-int-) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractAttachments(MessageInfo messageInfo)](#extractAttachments-com.aspose.email.MessageInfo-) | Extracts the attachments. |
| [extractAttachments(String entryId)](#extractAttachments-java.lang.String-) | Extracts the attachments. |
| [extractMessage(byte[] entryId)](#extractMessage-byte---) | Get the message from PST. |
| [extractMessage(MessageInfo messageInfo)](#extractMessage-com.aspose.email.MessageInfo-) | Get the message from PST. |
| [extractMessage(String entryId)](#extractMessage-java.lang.String-) | Get the message from PST. |
| [extractProperty(byte[] entryId, long tag)](#extractProperty-byte---long-) | Gets the specified property of item, without extract the item fully. |
| [findMessages(String parentEntryId)](#findMessages-java.lang.String-) | Finds the identifiers of messages for for the current folder. |
| [findSubfolders(String parentEntryId)](#findSubfolders-java.lang.String-) | Finds the identifiers of subfolders for for the current folder. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Load PST from file. |
| [fromFile(String fileName, boolean writable)](#fromFile-java.lang.String-boolean-) | Load PST from file. |
| [fromFile(String fileName, PersonalStorageLoadOptions loadOptions)](#fromFile-java.lang.String-com.aspose.email.PersonalStorageLoadOptions-) | Load PST from file. |
| [fromStream(System.IO.Stream stream)](#fromStream-com.aspose.ms.System.IO.Stream-) | Load PST from stream. |
| [fromStream(System.IO.Stream stream, boolean writable)](#fromStream-com.aspose.ms.System.IO.Stream-boolean-) | Load PST from stream. |
| [fromStream(System.IO.Stream stream, PersonalStorageLoadOptions loadOptions)](#fromStream-com.aspose.ms.System.IO.Stream-com.aspose.email.PersonalStorageLoadOptions-) | Load PST from stream. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Load PST from stream. |
| [fromStream(InputStream stream, boolean writable)](#fromStream-java.io.InputStream-boolean-) | Load PST from stream. |
| [fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions)](#fromStream-java.io.InputStream-com.aspose.email.PersonalStorageLoadOptions-) | Load PST from stream. |
| [getClass()](#getClass--) |  |
| [getFolderById(byte[] entryId)](#getFolderById-byte---) | Gets the personal folder from PST. |
| [getFolderById(String entryIdString)](#getFolderById-java.lang.String-) | Gets the personal folder from PST. |
| [getFormat()](#getFormat--) | Gets the file format. |
| [getParentFolder(byte[] entryId)](#getParentFolder-byte---) | Gets the parent folder of message. |
| [getParentFolder(String entryIdString)](#getParentFolder-java.lang.String-) | Gets the parent folder of message. |
| [getPredefinedFolder(int defaultFolder)](#getPredefinedFolder-int-) | Gets the standard interpersonal message (IPM) folder from PST. |
| [getRootFolder()](#getRootFolder--) | Gets the root folder of PST. |
| [getStore()](#getStore--) | Gets the PST message store. |
| [hashCode()](#hashCode--) |  |
| [isUnicode()](#isUnicode--) | Gets a value indicating whether the PST file format is Unicode. |
| [load(System.IO.Stream stream)](#load-com.aspose.ms.System.IO.Stream-) | Load PST from stream. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Load PST from stream. |
| [load(String fileName)](#load-java.lang.String-) | Load PST from file. |
| [mergeWith(InputStream[] sourceStreams)](#mergeWith-java.io.InputStream---) | Merges the pst storage with one or more other pst streams. |
| [mergeWith(String[] sourceFileNames)](#mergeWith-java.lang.String---) | Merges the pst storage with one or more other pst files. |
| [moveItem(FolderInfo folder, FolderInfo newFolder)](#moveItem-com.aspose.email.FolderInfo-com.aspose.email.FolderInfo-) | Moves a specified folder to a new parent folder within the current pst. |
| [moveItem(MessageInfo message, FolderInfo newFolder)](#moveItem-com.aspose.email.MessageInfo-com.aspose.email.FolderInfo-) | Moves a specified message to a new folder within the current pst. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveAs(OutputStream stream, int format)](#saveAs-java.io.OutputStream-int-) | Saves the current object to a specified file format in a stream. |
| [saveAs(String fileName, int format)](#saveAs-java.lang.String-int-) | Saves the current object to a specified file format in a different file. |
| [saveMessageToFile(String entryId, String fileName)](#saveMessageToFile-java.lang.String-java.lang.String-) | saveMessageToFile. |
| [saveMessageToStream(String entryId, OutputStream stream)](#saveMessageToStream-java.lang.String-java.io.OutputStream-) | Saves the message, with specified entryID, to a stream. |
| [splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path)](#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-) | Splits the pst storage based on criteria. |
| [splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String partFileNamePrefix, String path)](#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-java.lang.String-) | Splits the pst storage based on criteria. |
| [splitInto(long chunkSize, String path)](#splitInto-long-java.lang.String-) | Splits the pst storage into less sized parts. |
| [splitInto(long chunkSize, String partFileNamePrefix, String path)](#splitInto-long-java.lang.String-java.lang.String-) | Splits the pst storage into less sized parts. |
| [toString()](#toString--) |  |
| [tryToGetFolderById(String entryIdString, FolderInfo[] folder)](#tryToGetFolderById-java.lang.String-com.aspose.email.FolderInfo---) | Gets the folder associated with the specified entry ID. |
| [tryToSaveMessage(String entryId, OutputStream stream)](#tryToSaveMessage-java.lang.String-java.io.OutputStream-) | Saves the message, with specified entryID, to a stream. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PersonalStorage(TraversalExceptionsCallback callback) {#PersonalStorage-com.aspose.email.TraversalExceptionsCallback-}
```
public PersonalStorage(TraversalExceptionsCallback callback)
```


Initializes a new instance of the [PersonalStorage](../../com.aspose.email/personalstorage) class. Allows setting a callback method for handling exceptions that occur during PST traversal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [TraversalExceptionsCallback](../../com.aspose.email/traversalexceptionscallback) | The exception callback. |

### ItemMoved {#ItemMoved}
```
public final Event<ItemMovedEventHandler> ItemMoved
```


Occurs when an item is moved to the another folder.

### StorageProcessed {#StorageProcessed}
```
public final Event<StorageProcessedEventHandler> StorageProcessed
```


Occurs in splitting and merging operations when a new chunk of pst is created or the next file is processed and is to be merged.

### StorageProcessing {#StorageProcessing}
```
public final Event<StorageProcessingEventHandler> StorageProcessing
```


Occurs before the srorage is processed. The event is raised before processing the next storage in merging or splitting operations.

### canWrite() {#canWrite--}
```
public final boolean canWrite()
```


Gets a value indicating whether the current pst supports writing.

**Returns:**
boolean
### changeMessage(String entryId, MapiPropertyCollection updatedProperties) {#changeMessage-java.lang.String-com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessage(String entryId, MapiPropertyCollection updatedProperties)
```


Changes the message properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry identifier of message. |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | The updated properties. |

### close() {#close--}
```
public void close()
```




### convertTo(int format) {#convertTo-int-}
```
public final void convertTo(int format)
```


Converts the current object to the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | The FileFormat to convert the current object to.

--------------------

It is used for the fast OST to PST conversion. The method doesn't support conversion of OST created by MS Office 2013 and later versions. To convert an OST of later version, create a new PST and use the \#mergeWith(Stream[]).mergeWith(Stream[]) method. |

### create(System.IO.Stream stream, int version) {#create-com.aspose.ms.System.IO.Stream-int-}
```
public static PersonalStorage create(System.IO.Stream stream, int version)
```


Creates the PST in a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream in which PST is created. |
| version | int | The PST file version.

--------------------

Note, only Unicode file version creation is supported now. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(System.IO.Stream stream, int version, boolean leaveStreamOpen) {#create-com.aspose.ms.System.IO.Stream-int-boolean-}
```
public static PersonalStorage create(System.IO.Stream stream, int version, boolean leaveStreamOpen)
```


Creates the PST in a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream in which PST is created. |
| version | int | The PST file version. |
| leaveStreamOpen | boolean | Leave stream open when PersonalStorage is disposed.

--------------------

Note, only Unicode file version creation is supported now. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(OutputStream stream, int version) {#create-java.io.OutputStream-int-}
```
public static PersonalStorage create(OutputStream stream, int version)
```


Creates the PST in a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream in which PST is created. |
| version | int | The PST file version.

--------------------

Note, only Unicode file version creation is supported now. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(OutputStream stream, int version, boolean leaveStreamOpen) {#create-java.io.OutputStream-int-boolean-}
```
public static PersonalStorage create(OutputStream stream, int version, boolean leaveStreamOpen)
```


Creates the PST in a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream in which PST is created. |
| version | int | The PST file version. |
| leaveStreamOpen | boolean | Leave stream open when PersonalStorage is disposed.

--------------------

Note, only Unicode file version creation is supported now. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(OutputStream stream, int blockSize, int version) {#create-java.io.OutputStream-int-int-}
```
public static PersonalStorage create(OutputStream stream, int blockSize, int version)
```


Creates the PST in a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream in which PST is created. |
| blockSize | int | The optimal block size to expand cache buffer(in bytes). |
| version | int | The PST file version.

--------------------

Note, only Unicode file version creation is supported now. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(String fileName, int version) {#create-java.lang.String-int-}
```
public static PersonalStorage create(String fileName, int version)
```


Creates the new PST file with the specified file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The full name of the file. |
| version | int | The PST file version.

--------------------

Note, only Unicode file version creation is supported now. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### createPredefinedFolder(String name, int defaultFolder) {#createPredefinedFolder-java.lang.String-int-}
```
public final FolderInfo createPredefinedFolder(String name, int defaultFolder)
```


Creates the standard interpersonal message (IPM) folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of folder. |
| defaultFolder | int | The value of [StandardIpmFolder](../../com.aspose.email/standardipmfolder) enumeration. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A [FolderInfo](../../com.aspose.email/folderinfo) object that represents a standard IPM folder.
### createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy) {#createPredefinedFolder-java.lang.String-int-boolean-}
```
public final FolderInfo createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy)
```


Creates the standard interpersonal message (IPM) folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of folder. |
| defaultFolder | int | The value of [StandardIpmFolder](../../com.aspose.email/standardipmfolder) enumeration. |
| createHierarchy | boolean | if set to  true , it is possible to create a folder hierarchy using string notation. Backslash ('\\') is used as path separator. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A [FolderInfo](../../com.aspose.email/folderinfo) object that represents a standard IPM folder.
### deleteItem(String entryId) {#deleteItem-java.lang.String-}
```
public final void deleteItem(String entryId)
```


Deletes the item (folder or message) by it's entryId

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String |  |

### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### enumerateMessages(String entryId) {#enumerateMessages-java.lang.String-}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages(String entryId)
```


Exposes the enumerator, which supports an iteration of messages in folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The string that represents a parent folder entry ID. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in folder.
### enumerateMessages(String entryId, int startIndex, int count) {#enumerateMessages-java.lang.String-int-int-}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages(String entryId, int startIndex, int count)
```


Exposes the enumerator, which supports an iteration of messages in folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The string that represents a parent folder entry ID. |
| startIndex | int | The start message index. |
| count | int | The number of messages that will be retrieved. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in folder.
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
### extractAttachments(MessageInfo messageInfo) {#extractAttachments-com.aspose.email.MessageInfo-}
```
public final MapiAttachmentCollection extractAttachments(MessageInfo messageInfo)
```


Extracts the attachments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | [MessageInfo](../../com.aspose.email/messageinfo) | The message information. |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) that represents the collection of attachments.
### extractAttachments(String entryId) {#extractAttachments-java.lang.String-}
```
public final MapiAttachmentCollection extractAttachments(String entryId)
```


Extracts the attachments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The message entryId. |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) that represents the collection of attachments.
### extractMessage(byte[] entryId) {#extractMessage-byte---}
```
public final MapiMessage extractMessage(byte[] entryId)
```


Get the message from PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | byte[] | EntryId of message. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### extractMessage(MessageInfo messageInfo) {#extractMessage-com.aspose.email.MessageInfo-}
```
public final MapiMessage extractMessage(MessageInfo messageInfo)
```


Get the message from PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | [MessageInfo](../../com.aspose.email/messageinfo) | A MessageInfo object that represents information about message. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### extractMessage(String entryId) {#extractMessage-java.lang.String-}
```
public final MapiMessage extractMessage(String entryId)
```


Get the message from PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | String representation of EntryId. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### extractProperty(byte[] entryId, long tag) {#extractProperty-byte---long-}
```
public final MapiProperty extractProperty(byte[] entryId, long tag)
```


Gets the specified property of item, without extract the item fully.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | byte[] | The entry id of item. |
| tag | long | The property tag.

--------------------

If a property is not found, null is returned. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The MapiProperty.
### findMessages(String parentEntryId) {#findMessages-java.lang.String-}
```
public final System.Collections.Generic.IGenericList<String> findMessages(String parentEntryId)
```


Finds the identifiers of messages for for the current folder. It might be useful in case of reading corrupted pst when the GetContents and EnumerateMessages methods could throw an exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentEntryId | java.lang.String | Entry id of the parent folder. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.String> - Collection of entry Ids.
### findSubfolders(String parentEntryId) {#findSubfolders-java.lang.String-}
```
public final System.Collections.Generic.IGenericList<String> findSubfolders(String parentEntryId)
```


Finds the identifiers of subfolders for for the current folder. It might be useful in case of reading corrupted pst when the GetSubfolders and EnumerateFolders methods could throw an exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentEntryId | java.lang.String | Entry id of the parent folder. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.String> - Collection of entry Ids.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static PersonalStorage fromFile(String fileName)
```


Load PST from file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of .pst file.

--------------------

By default, the pst will support writing. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromFile(String fileName, boolean writable) {#fromFile-java.lang.String-boolean-}
```
public static PersonalStorage fromFile(String fileName, boolean writable)
```


Load PST from file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of .pst file. |
| writable | boolean | if set to  true  then the the pst file will support writing, otherwise it will be opened in read-only mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromFile(String fileName, PersonalStorageLoadOptions loadOptions) {#fromFile-java.lang.String-com.aspose.email.PersonalStorageLoadOptions-}
```
public static PersonalStorage fromFile(String fileName, PersonalStorageLoadOptions loadOptions)
```


Load PST from file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of .pst file. |
| loadOptions | [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) | The load options. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(System.IO.Stream stream) {#fromStream-com.aspose.ms.System.IO.Stream-}
```
public static PersonalStorage fromStream(System.IO.Stream stream)
```


Load PST from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The System.IO.Stream.

--------------------

By default, the pst will support writing. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(System.IO.Stream stream, boolean writable) {#fromStream-com.aspose.ms.System.IO.Stream-boolean-}
```
public static PersonalStorage fromStream(System.IO.Stream stream, boolean writable)
```


Load PST from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The System.IO.Stream. |
| writable | boolean | if set to  true  then the the pst will support writing, otherwise it will be opened in read-only mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(System.IO.Stream stream, PersonalStorageLoadOptions loadOptions) {#fromStream-com.aspose.ms.System.IO.Stream-com.aspose.email.PersonalStorageLoadOptions-}
```
public static PersonalStorage fromStream(System.IO.Stream stream, PersonalStorageLoadOptions loadOptions)
```


Load PST from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The System.IO.Stream. |
| loadOptions | [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) | The load options. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static PersonalStorage fromStream(InputStream stream)
```


Load PST from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The System.IO.Stream.

--------------------

By default, the pst will support writing. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(InputStream stream, boolean writable) {#fromStream-java.io.InputStream-boolean-}
```
public static PersonalStorage fromStream(InputStream stream, boolean writable)
```


Load PST from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The System.IO.Stream. |
| writable | boolean | if set to  true  then the the pst will support writing, otherwise it will be opened in read-only mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions) {#fromStream-java.io.InputStream-com.aspose.email.PersonalStorageLoadOptions-}
```
public static PersonalStorage fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions)
```


Load PST from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The System.IO.Stream. |
| loadOptions | [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) | The load options. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFolderById(byte[] entryId) {#getFolderById-byte---}
```
public final FolderInfo getFolderById(byte[] entryId)
```


Gets the personal folder from PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | byte[] | The Entry id. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getFolderById(String entryIdString) {#getFolderById-java.lang.String-}
```
public final FolderInfo getFolderById(String entryIdString)
```


Gets the personal folder from PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryIdString | java.lang.String | String representation of entry ID. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Gets the file format.

Value: [FileFormat](../../com.aspose.email/fileformat) that specifies file format.

--------------------

The .pst and .ost file formats are supported now.

**Returns:**
int
### getParentFolder(byte[] entryId) {#getParentFolder-byte---}
```
public final FolderInfo getParentFolder(byte[] entryId)
```


Gets the parent folder of message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | byte[] | Entry Id of message or folder. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The parent folder[FolderInfo](../../com.aspose.email/folderinfo) of message.
### getParentFolder(String entryIdString) {#getParentFolder-java.lang.String-}
```
public final FolderInfo getParentFolder(String entryIdString)
```


Gets the parent folder of message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryIdString | java.lang.String | String representation of Entry Id of message or folder. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The parent folder[FolderInfo](../../com.aspose.email/folderinfo) of message.
### getPredefinedFolder(int defaultFolder) {#getPredefinedFolder-int-}
```
public final FolderInfo getPredefinedFolder(int defaultFolder)
```


Gets the standard interpersonal message (IPM) folder from PST. Outlook can create a number of default folders, such as Outbox, Deleted Items, Sent Items etc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| defaultFolder | int | The value of [StandardIpmFolder](../../com.aspose.email/standardipmfolder) enumeration. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A [FolderInfo](../../com.aspose.email/folderinfo) object that represents a standard IPM folder.
### getRootFolder() {#getRootFolder--}
```
public final FolderInfo getRootFolder()
```


Gets the root folder of PST.

Value: [FolderInfo](../../com.aspose.email/folderinfo) that represents a root folder.

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo)
### getStore() {#getStore--}
```
public final MessageStore getStore()
```


Gets the PST message store.

Value: The [MessageStore](../../com.aspose.email/messagestore) which is the rough equivalent of the top of a Mailbox.

**Returns:**
[MessageStore](../../com.aspose.email/messagestore)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isUnicode() {#isUnicode--}
```
public final boolean isUnicode()
```


Gets a value indicating whether the PST file format is Unicode. There are two versions of the PST file format: Unicode and ANSI.

**Returns:**
boolean
### load(System.IO.Stream stream) {#load-com.aspose.ms.System.IO.Stream-}
```
public final boolean load(System.IO.Stream stream)
```


Load PST from stream. This method is used when a PersonalStorage object is created using the constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The System.IO.Stream. |

**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public final boolean load(InputStream stream)
```


Load PST from stream. This method is used when a PersonalStorage object is created using the constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The System.IO.Stream. |

**Returns:**
boolean - 'true' if the file has been loaded successfully and further traversal is possible; otherwise, false.
### load(String fileName) {#load-java.lang.String-}
```
public final boolean load(String fileName)
```


Load PST from file. This method is used when a PersonalStorage object is created using the constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The name of .pst file. |

**Returns:**
boolean - 'true' if the file has been loaded successfully and further traversal is possible; otherwise, false.
### mergeWith(InputStream[] sourceStreams) {#mergeWith-java.io.InputStream---}
```
public final void mergeWith(InputStream[] sourceStreams)
```


Merges the pst storage with one or more other pst streams. Thus, the combined stream are sources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceStreams | java.io.InputStream[] | The source streams. |

### mergeWith(String[] sourceFileNames) {#mergeWith-java.lang.String---}
```
public final void mergeWith(String[] sourceFileNames)
```


Merges the pst storage with one or more other pst files. Thus, the combined files are sources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFileNames | java.lang.String[] | The source file names. |

### moveItem(FolderInfo folder, FolderInfo newFolder) {#moveItem-com.aspose.email.FolderInfo-com.aspose.email.FolderInfo-}
```
public final void moveItem(FolderInfo folder, FolderInfo newFolder)
```


Moves a specified folder to a new parent folder within the current pst.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | [FolderInfo](../../com.aspose.email/folderinfo) | The folder to move. |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | The new parent folder. |

### moveItem(MessageInfo message, FolderInfo newFolder) {#moveItem-com.aspose.email.MessageInfo-com.aspose.email.FolderInfo-}
```
public final void moveItem(MessageInfo message, FolderInfo newFolder)
```


Moves a specified message to a new folder within the current pst.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MessageInfo](../../com.aspose.email/messageinfo) | The message to move. |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | The new folder for the message. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveAs(OutputStream stream, int format) {#saveAs-java.io.OutputStream-int-}
```
public final void saveAs(OutputStream stream, int format)
```


Saves the current object to a specified file format in a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to be saved. |
| format | int | The [FileFormat](../../com.aspose.email/fileformat) is to be used.

--------------------

It is used for the fast OST to PST conversion. The method doesn't support conversion of OST created by MS Office 2013 and later versions. To convert an OST of later version, create a new PST and use the \#mergeWith(Stream[]).mergeWith(Stream[]) method. |

### saveAs(String fileName, int format) {#saveAs-java.lang.String-int-}
```
public final void saveAs(String fileName, int format)
```


Saves the current object to a specified file format in a different file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The name of the file to be saved. |
| format | int | The [FileFormat](../../com.aspose.email/fileformat) is to be used when saving a file.

--------------------

It is used for the fast OST to PST conversion. The method doesn't support conversion of OST created by MS Office 2013 and later versions. To convert an OST of later version, create a new PST and use the \#mergeWith(String[]).mergeWith(String[]) method. |

### saveMessageToFile(String entryId, String fileName) {#saveMessageToFile-java.lang.String-java.lang.String-}
```
public void saveMessageToFile(String entryId, String fileName)
```


saveMessageToFile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | a java.lang.String object. |
| fileName | java.lang.String | a java.lang.String object. |

### saveMessageToStream(String entryId, OutputStream stream) {#saveMessageToStream-java.lang.String-java.io.OutputStream-}
```
public final void saveMessageToStream(String entryId, OutputStream stream)
```


Saves the message, with specified entryID, to a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry id. |
| stream | java.io.OutputStream | The stream for writing. |

### splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path) {#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-}
```
public final void splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path)
```


Splits the pst storage based on criteria.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| criteria | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MailQuery> | The collection of [MailQuery](../../com.aspose.email/mailquery) that represents criteria of pst splitting. |
| path | java.lang.String | The folder path where chunks will be created. |

### splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String partFileNamePrefix, String path) {#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-java.lang.String-}
```
public final void splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String partFileNamePrefix, String path)
```


Splits the pst storage based on criteria.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| criteria | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MailQuery> | The collection of [MailQuery](../../com.aspose.email/mailquery) that represents criteria of pst splitting. |
| partFileNamePrefix | java.lang.String | The prefix to be added to the filename of each part of pst. If provided, the prefix will be added to the beginning of each file name. If not provided (null or empty), the pst parts will be created without a prefix. The pst file names are produced using the following template: \{prefix\}\_part\{number\}.pst - \{prefix\}: The filename prefix provided by the partFileNamePrefix parameter. If not provided, this part will be omitted. - \{number\}: The number of the chunk file. |
| path | java.lang.String | The folder path where chunks will be created. |

### splitInto(long chunkSize, String path) {#splitInto-long-java.lang.String-}
```
public final void splitInto(long chunkSize, String path)
```


Splits the pst storage into less sized parts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | long | The approximate size of a chunk in bytes. |
| path | java.lang.String | The folder path where chunks will be created. |

### splitInto(long chunkSize, String partFileNamePrefix, String path) {#splitInto-long-java.lang.String-java.lang.String-}
```
public final void splitInto(long chunkSize, String partFileNamePrefix, String path)
```


Splits the pst storage into less sized parts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | long | The approximate size of a chunk in bytes. |
| partFileNamePrefix | java.lang.String | The prefix to be added to the filename of each part of pst. If provided, the prefix will be added to the beginning of each file name. If not provided (null or empty), the pst parts will be created without a prefix.

--------------------

The pst file names are produced using the following template: \{prefix\}\_part\{number\}.pst - \{prefix\}: The filename prefix provided by the partFileNamePrefix parameter. If not provided, this part will be omitted. - \{number\}: The number of the chunk file. |
| path | java.lang.String | The folder path where chunks will be created. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryToGetFolderById(String entryIdString, FolderInfo[] folder) {#tryToGetFolderById-java.lang.String-com.aspose.email.FolderInfo---}
```
public final boolean tryToGetFolderById(String entryIdString, FolderInfo[] folder)
```


Gets the folder associated with the specified entry ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryIdString | java.lang.String | The string that represented the entry ID. |
| folder | [FolderInfo\[\]](../../com.aspose.email/folderinfo) | When this method returns true, contains the [FolderInfo](../../com.aspose.email/folderinfo) object associated with the specified ID. |

**Returns:**
boolean - true if the folder is successfully found; otherwise, false.
### tryToSaveMessage(String entryId, OutputStream stream) {#tryToSaveMessage-java.lang.String-java.io.OutputStream-}
```
public final SaveResult tryToSaveMessage(String entryId, OutputStream stream)
```


Saves the message, with specified entryID, to a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry id. |
| stream | java.io.OutputStream | The stream for writing. |

**Returns:**
[SaveResult](../../com.aspose.email/saveresult) - The [SaveResult](../../com.aspose.email/saveresult) that represents the result of item saving.
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

