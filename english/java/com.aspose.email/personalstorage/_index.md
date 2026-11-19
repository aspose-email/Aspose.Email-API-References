---
title: PersonalStorage
second_title: Aspose.Email for Java API Reference
description: Provides functionality to access and manipulate the PST Personal Storage Table files used by Microsoft Outlook.
type: docs
weight: 589
url: /java/com.aspose.email/personalstorage/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class PersonalStorage implements System.IDisposable, Closeable
```

Provides functionality to access and manipulate the PST (Personal Storage Table) files used by Microsoft Outlook.

The PersonalStorage class encapsulates methods for creating, opening, and working with the contents of PST files including emails, appointments, contacts, tasks, and other personal information.

This code serves as a way to browse and extract messages from a PST file, printing metadata about each folder and message, extract and saving the actual messages as .msg files.

```

 // Open the PST file by creating an instance of PersonalStorage
 try (PersonalStorage pst = PersonalStorage.fromFile("storage.pst")) {
     // Retrieve the total number of items in the PST file
     int totalItemsCount = pst.getStore().getTotalItemsCount();

     // Write the total items count to the console
     System.out.println("Total items count: " + totalItemsCount);

     // Iterate through each subfolder within the root folder of the PST
     for (FolderInfo folderInfo : pst.getRootFolder().getSubFolders()) {
         // Write the display name of the folder to the console
         System.out.println("Folder: " + folderInfo.getDisplayName());
         // Write the total number of items in the folder to the console
         System.out.println("Total items: " + folderInfo.getContentCount());
         // Write the count of unread items in the folder to the console
         System.out.println("Total unread items: " + folderInfo.getContentUnreadCount());

         // Enumerate through each message in the current folder
         for (MessageInfo messageInfo : folderInfo.enumerateMessages()) {
             // Write the subject of the message to the console
             System.out.println("Subject: " + messageInfo.getSubject());

             // Extract the full message object from the messageInfo
             MapiMessage msg = pst.extractMessage(messageInfo);

             // Save the message as a .msg file, using its subject as the filename
             msg.save(msg.getSubject() + ".msg");
         }
     }
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [PersonalStorage(TraversalExceptionsCallback callback)](#PersonalStorage-com.aspose.email.TraversalExceptionsCallback-) | Initializes a new instance of the [PersonalStorage](../../com.aspose.email/personalstorage) class that reports problems found while reading a damaged PST to a callback instead of throwing. |
## Fields

| Field | Description |
| --- | --- |
| [ItemMoved](#ItemMoved) | Occurs when an item is moved to the another folder. |
| [StorageProcessed](#StorageProcessed) | Occurs in splitting and merging operations when a new chunk of pst is created or the next file is processed and is to be merged. |
| [StorageProcessing](#StorageProcessing) | Occurs before the srorage is processed. |
## Methods

| Method | Description |
| --- | --- |
| [addAttachmentToMessage(MessageInfo messageInfo, String filePath)](#addAttachmentToMessage-com.aspose.email.MessageInfo-java.lang.String-) | Adds an attachment to the specified message using the file located at the provided path. |
| [addAttachmentToMessage(MessageInfo messageInfo, String name, InputStream stream)](#addAttachmentToMessage-com.aspose.email.MessageInfo-java.lang.String-java.io.InputStream-) | Adds an attachment to the specified message using the provided stream as attachment content. |
| [addAttachmentToMessage(String entryId, String filePath)](#addAttachmentToMessage-java.lang.String-java.lang.String-) | Adds an attachment to the message identified by the specified entry ID using the file located at the provided path. |
| [addAttachmentToMessage(String entryId, String name, InputStream stream)](#addAttachmentToMessage-java.lang.String-java.lang.String-java.io.InputStream-) | Adds an attachment to the message identified by the specified entry ID using the provided stream. |
| [canWrite()](#canWrite--) | Gets a value indicating whether the PST is open for writing. |
| [changeMessage(String entryId, MapiPropertyCollection updatedProperties)](#changeMessage-java.lang.String-com.aspose.email.MapiPropertyCollection-) | Changes properties of a message. |
| [close()](#close--) | Closes the PST and releases the resources it uses. |
| [convertTo(int format)](#convertTo-int-) | Converts the open file to the specified format. |
| [create(System.IO.Stream stream, int version)](#create-com.aspose.ms.System.IO.Stream-int-) | Creates a new PST in a stream. |
| [create(System.IO.Stream stream, int version, boolean leaveStreamOpen)](#create-com.aspose.ms.System.IO.Stream-int-boolean-) | Creates a new PST in a stream. |
| [create(OutputStream stream, int version)](#create-java.io.OutputStream-int-) | Creates the PST in a stream. |
| [create(OutputStream stream, int version, boolean leaveStreamOpen)](#create-java.io.OutputStream-int-boolean-) | Creates the PST in a stream. |
| [create(OutputStream stream, int blockSize, int version)](#create-java.io.OutputStream-int-int-) | Creates the PST in a stream. |
| [create(String fileName, int version)](#create-java.lang.String-int-) | Creates a new PST file. |
| [create(SeekableByteChannel channel, int version)](#create-java.nio.channels.SeekableByteChannel-int-) | Creates the PST in a java.nio.channels. |
| [createPredefinedFolder(String name, int defaultFolder)](#createPredefinedFolder-java.lang.String-int-) | Creates a standard Outlook folder, such as Inbox or Calendar, with the specified name. |
| [createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy)](#createPredefinedFolder-java.lang.String-int-boolean-) | Creates a standard Outlook folder, such as Inbox or Calendar, with the specified name. |
| [deleteItem(String entryId)](#deleteItem-java.lang.String-) | Deletes a message or folder by its entry ID. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [enumerateMessages(String entryId)](#enumerateMessages-java.lang.String-) | Enumerates the messages of the folder with the specified entry ID. |
| [enumerateMessages(String entryId, int startIndex, int count)](#enumerateMessages-java.lang.String-int-int-) | Enumerates a range of the messages of the folder with the specified entry ID. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractAttachments(MessageInfo messageInfo)](#extractAttachments-com.aspose.email.MessageInfo-) | Reads the attachments of a message without loading the whole message. |
| [extractAttachments(String entryId)](#extractAttachments-java.lang.String-) | Reads the attachments of a message without loading the whole message. |
| [extractMessage(byte[] entryId)](#extractMessage-byte---) | Loads the full message with the specified entry ID. |
| [extractMessage(MessageInfo messageInfo)](#extractMessage-com.aspose.email.MessageInfo-) | Loads the full message that a [MessageInfo](../../com.aspose.email/messageinfo) describes. |
| [extractMessage(String entryId)](#extractMessage-java.lang.String-) | Loads the full message with the specified entry ID. |
| [extractProperty(byte[] entryId, long tag)](#extractProperty-byte---long-) | Reads one property of an item without loading the whole item. |
| [extractRecipients(MessageInfo messageInfo)](#extractRecipients-com.aspose.email.MessageInfo-) | Reads the recipients of a message without loading the whole message. |
| [extractRecipients(String entryId)](#extractRecipients-java.lang.String-) | Reads the recipients of a message without loading the whole message. |
| [findAndEnumerateSoftDeletedItems()](#findAndEnumerateSoftDeletedItems--) | Finds soft-deleted messages and returns them one at a time. |
| [findAndExtractSoftDeletedItems()](#findAndExtractSoftDeletedItems--) | Finds and extracts all soft-deleted messages of the PST. |
| [findMessages(String parentEntryId)](#findMessages-java.lang.String-) | Finds the entry IDs of the messages of a folder. |
| [findSubfolders(String parentEntryId)](#findSubfolders-java.lang.String-) | Finds the entry IDs of the subfolders of a folder. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Opens a PST or OST file for reading and writing. |
| [fromFile(String fileName, boolean writable)](#fromFile-java.lang.String-boolean-) | Opens a PST or OST file. |
| [fromFile(String fileName, PersonalStorageLoadOptions loadOptions)](#fromFile-java.lang.String-com.aspose.email.PersonalStorageLoadOptions-) | Opens a PST or OST file with the specified options. |
| [fromStream(System.IO.Stream stream)](#fromStream-com.aspose.ms.System.IO.Stream-) | Load PST from stream. |
| [fromStream(System.IO.Stream stream, boolean writable)](#fromStream-com.aspose.ms.System.IO.Stream-boolean-) | Load PST from stream. |
| [fromStream(System.IO.Stream stream, PersonalStorageLoadOptions loadOptions)](#fromStream-com.aspose.ms.System.IO.Stream-com.aspose.email.PersonalStorageLoadOptions-) | Load PST from stream. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Opens a PST or OST from a stream for reading and writing. |
| [fromStream(InputStream stream, boolean writable)](#fromStream-java.io.InputStream-boolean-) | Opens a PST or OST from a stream. |
| [fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions)](#fromStream-java.io.InputStream-com.aspose.email.PersonalStorageLoadOptions-) | Opens a PST or OST from a stream with the specified options. |
| [getCategories()](#getCategories--) | Gets the categories used in the PST, each with its name and color. |
| [getClass()](#getClass--) |  |
| [getFolderById(byte[] entryId)](#getFolderById-byte---) | Gets the folder with the specified entry ID. |
| [getFolderById(String entryIdString)](#getFolderById-java.lang.String-) | Gets the folder with the specified entry ID. |
| [getFormat()](#getFormat--) | Gets the file format. |
| [getParentFolder(byte[] entryId)](#getParentFolder-byte---) | Gets the folder that contains a message or folder. |
| [getParentFolder(String entryIdString)](#getParentFolder-java.lang.String-) | Gets the folder that contains a message or folder. |
| [getPredefinedFolder(int defaultFolder)](#getPredefinedFolder-int-) | Gets a standard Outlook folder of the PST, such as Inbox, Sent Items or Deleted Items. |
| [getRootFolder()](#getRootFolder--) | Gets the root folder of the PST, which contains all other folders. |
| [getStore()](#getStore--) | Gets the PST message store. |
| [hashCode()](#hashCode--) |  |
| [isUnicode()](#isUnicode--) | Gets a value indicating whether the PST is in the Unicode format. |
| [load(System.IO.Stream stream)](#load-com.aspose.ms.System.IO.Stream-) | Load PST from stream. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Opens a PST from a stream for reading, for a storage created with the constructor that takes a  TraversalExceptionsCallback . |
| [load(String fileName)](#load-java.lang.String-) | Opens a PST file for reading, for a storage created with the constructor that takes a  TraversalExceptionsCallback . |
| [mergeWith(InputStream[] sourceStreams)](#mergeWith-java.io.InputStream---) | Merges one or more other PST streams into this PST. |
| [mergeWith(String[] sourceFileNames)](#mergeWith-java.lang.String---) | Merges one or more other PST files into this PST. |
| [moveItem(FolderInfo folder, FolderInfo newFolder)](#moveItem-com.aspose.email.FolderInfo-com.aspose.email.FolderInfo-) | Moves a folder to another parent folder of the same PST. |
| [moveItem(MessageInfo message, FolderInfo newFolder)](#moveItem-com.aspose.email.MessageInfo-com.aspose.email.FolderInfo-) | Moves a message to another folder of the same PST. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveAs(OutputStream stream, int format)](#saveAs-java.io.OutputStream-int-) | Saves the storage to a stream in the specified format. |
| [saveAs(String fileName, int format)](#saveAs-java.lang.String-int-) | Saves the storage to another file in the specified format. |
| [saveMessageToFile(String entryId, String fileName)](#saveMessageToFile-java.lang.String-java.lang.String-) | saveMessageToFile. |
| [saveMessageToStream(String entryId, OutputStream stream)](#saveMessageToStream-java.lang.String-java.io.OutputStream-) | Saves a message to a stream in Outlook MSG format, without loading it into a  MapiMessage . |
| [splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path)](#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-) | Splits the PST into several files by search criteria. |
| [splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String partFileNamePrefix, String path)](#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-java.lang.String-) | Splits the PST into several files by search criteria, named with a prefix. |
| [splitInto(long chunkSize, String path)](#splitInto-long-java.lang.String-) | Splits the PST into files of about the specified size. |
| [splitInto(long chunkSize, String partFileNamePrefix, String path)](#splitInto-long-java.lang.String-java.lang.String-) | Splits the PST into files of about the specified size, named with a prefix. |
| [toString()](#toString--) |  |
| [tryToGetFolderById(String entryIdString, FolderInfo[] folder)](#tryToGetFolderById-java.lang.String-com.aspose.email.FolderInfo---) | Tries to get the folder with the specified entry ID. |
| [tryToSaveMessage(String entryId, OutputStream stream)](#tryToSaveMessage-java.lang.String-java.io.OutputStream-) | Saves a message to a stream in Outlook MSG format, keeping as much of a damaged message as can be read instead of failing. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PersonalStorage(TraversalExceptionsCallback callback) {#PersonalStorage-com.aspose.email.TraversalExceptionsCallback-}
```
public PersonalStorage(TraversalExceptionsCallback callback)
```


Initializes a new instance of the [PersonalStorage](../../com.aspose.email/personalstorage) class that reports problems found while reading a damaged PST to a callback instead of throwing. Call  load  to open the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [TraversalExceptionsCallback](../../com.aspose.email/traversalexceptionscallback) | The method to call for each problem found while reading. |

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

### addAttachmentToMessage(MessageInfo messageInfo, String filePath) {#addAttachmentToMessage-com.aspose.email.MessageInfo-java.lang.String-}
```
public final void addAttachmentToMessage(MessageInfo messageInfo, String filePath)
```


Adds an attachment to the specified message using the file located at the provided path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | [MessageInfo](../../com.aspose.email/messageinfo) | The [MessageInfo](../../com.aspose.email/messageinfo) object representing the target message. |
| filePath | java.lang.String | The full path to the file to be added as an attachment. |

### addAttachmentToMessage(MessageInfo messageInfo, String name, InputStream stream) {#addAttachmentToMessage-com.aspose.email.MessageInfo-java.lang.String-java.io.InputStream-}
```
public final void addAttachmentToMessage(MessageInfo messageInfo, String name, InputStream stream)
```


Adds an attachment to the specified message using the provided stream as attachment content.

The provided  stream  is not closed or disposed by this method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | [MessageInfo](../../com.aspose.email/messageinfo) | The [MessageInfo](../../com.aspose.email/messageinfo) object representing the target message. |
| name | java.lang.String | The name of the attachment to add. |
| stream | java.io.InputStream | The stream containing the attachment data. |

### addAttachmentToMessage(String entryId, String filePath) {#addAttachmentToMessage-java.lang.String-java.lang.String-}
```
public final void addAttachmentToMessage(String entryId, String filePath)
```


Adds an attachment to the message identified by the specified entry ID using the file located at the provided path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the target message. |
| filePath | java.lang.String | The full path to the file to be added as an attachment. |

### addAttachmentToMessage(String entryId, String name, InputStream stream) {#addAttachmentToMessage-java.lang.String-java.lang.String-java.io.InputStream-}
```
public final void addAttachmentToMessage(String entryId, String name, InputStream stream)
```


Adds an attachment to the message identified by the specified entry ID using the provided stream.

The provided  stream  is not closed or disposed by this method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the target message. |
| name | java.lang.String | The name of the attachment to add. |
| stream | java.io.InputStream | The stream containing the attachment data. |

### canWrite() {#canWrite--}
```
public final boolean canWrite()
```


Gets a value indicating whether the PST is open for writing.

**Returns:**
boolean
### changeMessage(String entryId, MapiPropertyCollection updatedProperties) {#changeMessage-java.lang.String-com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessage(String entryId, MapiPropertyCollection updatedProperties)
```


Changes properties of a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the message. |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | The properties to set. |

### close() {#close--}
```
public void close()
```


Closes the PST and releases the resources it uses. The underlying stream is closed too, unless the storage was opened or created with the option to leave it open.

### convertTo(int format) {#convertTo-int-}
```
public final void convertTo(int format)
```


Converts the open file to the specified format.

Use it for a fast OST to PST conversion. It does not support OST files of Outlook 2013 and later; to convert such a file, create a new PST and call its \#mergeWith(InputStream[]).mergeWith(InputStream[]) method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | The format to convert to. |

### create(System.IO.Stream stream, int version) {#create-com.aspose.ms.System.IO.Stream-int-}
```
public static PersonalStorage create(System.IO.Stream stream, int version)
```


Creates a new PST in a stream.

Only Unicode PST files can be created. The stream is closed when the storage is disposed. Use the overload with leaveStreamOpen to keep it open.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream to write the PST to. |
| version | int | The version of the PST. Only  FileFormatVersion.Unicode  is supported. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - The new PST, open for writing.
### create(System.IO.Stream stream, int version, boolean leaveStreamOpen) {#create-com.aspose.ms.System.IO.Stream-int-boolean-}
```
public static PersonalStorage create(System.IO.Stream stream, int version, boolean leaveStreamOpen)
```


Creates a new PST in a stream.

Only Unicode PST files can be created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream to write the PST to. |
| version | int | The version of the PST. Only  FileFormatVersion.Unicode  is supported. |
| leaveStreamOpen | boolean |  true  to leave  stream  open when the storage is disposed. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - The new PST, open for writing.
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


Creates a new PST file.

Only Unicode PST files can be created.

This example creates a PST, adds the standard Inbox folder and puts a message into it.

```

 // Create a new PST; the file must not exist yet
 try (PersonalStorage pst = PersonalStorage.create("archive.pst", FileFormatVersion.Unicode)) {
     // Create the standard Inbox folder
     FolderInfo inbox = pst.createPredefinedFolder("Inbox", StandardIpmFolder.Inbox);

     // Add a message loaded from an .msg file
     MapiMessage message = MapiMessage.load("message.msg");
     String entryId = inbox.addMessage(message);

     System.out.println("Added message " + entryId);
 }
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to create. The file must not exist. |
| version | int | The version of the PST. Only  FileFormatVersion.Unicode  is supported. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - The new PST, open for writing.
### create(SeekableByteChannel channel, int version) {#create-java.nio.channels.SeekableByteChannel-int-}
```
public static PersonalStorage create(SeekableByteChannel channel, int version)
```


Creates the PST in a java.nio.channels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channel | java.nio.channels.SeekableByteChannel | The java.nio.channel in which PST is created. |
| version | int | The PST file version.

--------------------

Note, only Unicode file version creation is supported now. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### createPredefinedFolder(String name, int defaultFolder) {#createPredefinedFolder-java.lang.String-int-}
```
public final FolderInfo createPredefinedFolder(String name, int defaultFolder)
```


Creates a standard Outlook folder, such as Inbox or Calendar, with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the folder. |
| defaultFolder | int | Which standard folder to create. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new folder.
### createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy) {#createPredefinedFolder-java.lang.String-int-boolean-}
```
public final FolderInfo createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy)
```


Creates a standard Outlook folder, such as Inbox or Calendar, with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the folder. |
| defaultFolder | int | Which standard folder to create. |
| createHierarchy | boolean |  true  to treat  name  as a path separated by backslashes and create the folders that do not exist yet. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new folder.
### deleteItem(String entryId) {#deleteItem-java.lang.String-}
```
public final void deleteItem(String entryId)
```


Deletes a message or folder by its entry ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the item to delete. |

### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### enumerateMessages(String entryId) {#enumerateMessages-java.lang.String-}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages(String entryId)
```


Enumerates the messages of the folder with the specified entry ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the folder. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> - Information about the messages. They are read from the file as the sequence is enumerated.
### enumerateMessages(String entryId, int startIndex, int count) {#enumerateMessages-java.lang.String-int-int-}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages(String entryId, int startIndex, int count)
```


Enumerates a range of the messages of the folder with the specified entry ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the folder. |
| startIndex | int | The zero-based index of the first message to return. |
| count | int | The maximum number of messages to return. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> - Information about the messages. They are read from the file as the sequence is enumerated.
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


Reads the attachments of a message without loading the whole message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | [MessageInfo](../../com.aspose.email/messageinfo) | The message. |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) that represents the collection of attachments.
### extractAttachments(String entryId) {#extractAttachments-java.lang.String-}
```
public final MapiAttachmentCollection extractAttachments(String entryId)
```


Reads the attachments of a message without loading the whole message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the message. |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) that represents the collection of attachments.
### extractMessage(byte[] entryId) {#extractMessage-byte---}
```
public final MapiMessage extractMessage(byte[] entryId)
```


Loads the full message with the specified entry ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | byte[] | The entry ID of the message. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The message with its body, recipients and attachments.
### extractMessage(MessageInfo messageInfo) {#extractMessage-com.aspose.email.MessageInfo-}
```
public final MapiMessage extractMessage(MessageInfo messageInfo)
```


Loads the full message that a [MessageInfo](../../com.aspose.email/messageinfo) describes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | [MessageInfo](../../com.aspose.email/messageinfo) | Information about the message, from  FolderInfo.getContents  or  FolderInfo.enumerateMessages . |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The message with its body, recipients and attachments.
### extractMessage(String entryId) {#extractMessage-java.lang.String-}
```
public final MapiMessage extractMessage(String entryId)
```


Loads the full message with the specified entry ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the message, as a string. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The message with its body, recipients and attachments.
### extractProperty(byte[] entryId, long tag) {#extractProperty-byte---long-}
```
public final MapiProperty extractProperty(byte[] entryId, long tag)
```


Reads one property of an item without loading the whole item.

If a property is not found,  null  is returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | byte[] | The entry ID of the item. |
| tag | long | The tag of the property. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The property, or  null  if the item does not have it.
### extractRecipients(MessageInfo messageInfo) {#extractRecipients-com.aspose.email.MessageInfo-}
```
public final MapiRecipientCollection extractRecipients(MessageInfo messageInfo)
```


Reads the recipients of a message without loading the whole message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | [MessageInfo](../../com.aspose.email/messageinfo) | The message. |

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) - The [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) that represents the collection of recipients.
### extractRecipients(String entryId) {#extractRecipients-java.lang.String-}
```
public final MapiRecipientCollection extractRecipients(String entryId)
```


Reads the recipients of a message without loading the whole message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the message. |

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) - The [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) that represents the collection of recipients.
### findAndEnumerateSoftDeletedItems() {#findAndEnumerateSoftDeletedItems--}
```
public final System.Collections.Generic.IGenericEnumerable<RestoredItemEntry> findAndEnumerateSoftDeletedItems()
```


Finds soft-deleted messages and returns them one at a time.

Soft-deleted messages are messages that have been deleted but whose data is still present in the PST.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.RestoredItemEntry> - The soft-deleted messages, each with the entry ID of the folder it was in. They are read from the file as the sequence is enumerated.
### findAndExtractSoftDeletedItems() {#findAndExtractSoftDeletedItems--}
```
public final System.Collections.Generic.IGenericList<RestoredItemEntry> findAndExtractSoftDeletedItems()
```


Finds and extracts all soft-deleted messages of the PST.

Soft-deleted messages are messages that have been deleted but whose data is still present in the PST. For a large PST,  findAndEnumerateSoftDeletedItems  reads them one at a time.

This example recovers soft-deleted messages and saves them as .msg files.

```

 try (PersonalStorage pst = PersonalStorage.fromFile("archive.pst")) {
     int count = 0;
     for (RestoredItemEntry entry : pst.findAndExtractSoftDeletedItems()) {
         // The folder the message was deleted from, if it still exists
         FolderInfo[] folder = { null };
         String folderName = pst.tryToGetFolderById(entry.getFolderId(), folder)
                 ? folder[0].getDisplayName()
                 : "(unknown folder)";

         System.out.println(entry.getItem().getSubject() + " from " + folderName);
         entry.getItem().save("recovered_" + (++count) + ".msg");
     }
 }
 
```

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.RestoredItemEntry> - The soft-deleted messages, each with the entry ID of the folder it was in.
### findMessages(String parentEntryId) {#findMessages-java.lang.String-}
```
public final System.Collections.Generic.IGenericList<String> findMessages(String parentEntryId)
```


Finds the entry IDs of the messages of a folder. Use it to read a damaged PST when  FolderInfo.getContents  and  FolderInfo.enumerateMessages  throw.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentEntryId | java.lang.String | The entry ID of the folder. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.String> - The entry IDs of the messages.
### findSubfolders(String parentEntryId) {#findSubfolders-java.lang.String-}
```
public final System.Collections.Generic.IGenericList<String> findSubfolders(String parentEntryId)
```


Finds the entry IDs of the subfolders of a folder. Use it to read a damaged PST when  FolderInfo.getSubFolders  and  FolderInfo.enumerateFolders  throw.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentEntryId | java.lang.String | The entry ID of the folder. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.String> - The entry IDs of the subfolders.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static PersonalStorage fromFile(String fileName)
```


Opens a PST or OST file for reading and writing.

Opening for writing needs write access to the file. To read a file that is read-only or in use, use the overload with writable and pass  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - The opened storage.
### fromFile(String fileName, boolean writable) {#fromFile-java.lang.String-boolean-}
```
public static PersonalStorage fromFile(String fileName, boolean writable)
```


Opens a PST or OST file.

Opening for writing needs write access to the file. To read a file that is read-only or in use, open it with  writable  set to  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file. |
| writable | boolean |  true  to open the file for reading and writing;  false  to open it for reading only. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - The opened storage.
### fromFile(String fileName, PersonalStorageLoadOptions loadOptions) {#fromFile-java.lang.String-com.aspose.email.PersonalStorageLoadOptions-}
```
public static PersonalStorage fromFile(String fileName, PersonalStorageLoadOptions loadOptions)
```


Opens a PST or OST file with the specified options.

The file is opened for writing only if [PersonalStorageLoadOptions.getWritable()](../../com.aspose.email/personalstorageloadoptions\#getWritable--) is  true , which is not the default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file. |
| loadOptions | [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) | The options for opening the file. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - The opened storage.
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


Opens a PST or OST from a stream for reading and writing.

The stream is closed when the storage is disposed. To keep it open, use the overload with [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) and set its [PersonalStorageLoadOptions.getLeaveStreamOpen()](../../com.aspose.email/personalstorageloadoptions\#getLeaveStreamOpen--) property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream with the PST or OST data. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - The opened storage.
### fromStream(InputStream stream, boolean writable) {#fromStream-java.io.InputStream-boolean-}
```
public static PersonalStorage fromStream(InputStream stream, boolean writable)
```


Opens a PST or OST from a stream.

The stream is closed when the storage is disposed. To keep it open, use the overload with [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) and set its [PersonalStorageLoadOptions.getLeaveStreamOpen()](../../com.aspose.email/personalstorageloadoptions\#getLeaveStreamOpen--) property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream with the PST or OST data. |
| writable | boolean |  true  to open the PST for reading and writing;  false  for reading only. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - The opened storage.
### fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions) {#fromStream-java.io.InputStream-com.aspose.email.PersonalStorageLoadOptions-}
```
public static PersonalStorage fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions)
```


Opens a PST or OST from a stream with the specified options.

The PST is opened for writing only if [PersonalStorageLoadOptions.getWritable()](../../com.aspose.email/personalstorageloadoptions\#getWritable--) is  true , which is not the default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream with the PST or OST data. |
| loadOptions | [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) | The options for opening the stream. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - The opened storage.
### getCategories() {#getCategories--}
```
public final List<PstItemCategory> getCategories()
```


Gets the categories used in the PST, each with its name and color.

This example lists the categories of a PST with their colors.

```

 try (PersonalStorage pst = PersonalStorage.fromFile("archive.pst")) {
     for (PstItemCategory category : pst.getCategories()) {
         System.out.println(category.getName() + ": " + category.getColor());
     }
 }
 
```

**Returns:**
java.util.List<com.aspose.email.PstItemCategory> - The categories. The list is empty if no categories are found.
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


Gets the folder with the specified entry ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | byte[] | The entry ID of the folder. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The folder.
### getFolderById(String entryIdString) {#getFolderById-java.lang.String-}
```
public final FolderInfo getFolderById(String entryIdString)
```


Gets the folder with the specified entry ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryIdString | java.lang.String | The entry ID of the folder, as a string. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The folder.
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Gets the file format.

The .pst and .ost file formats are supported now.

**Returns:**
int - [FileFormat](../../com.aspose.email/fileformat) that specifies file format.
### getParentFolder(byte[] entryId) {#getParentFolder-byte---}
```
public final FolderInfo getParentFolder(byte[] entryId)
```


Gets the folder that contains a message or folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | byte[] | The entry ID of the message or folder. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The parent folder.
### getParentFolder(String entryIdString) {#getParentFolder-java.lang.String-}
```
public final FolderInfo getParentFolder(String entryIdString)
```


Gets the folder that contains a message or folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryIdString | java.lang.String | The entry ID of the message or folder, as a string. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The parent folder.
### getPredefinedFolder(int defaultFolder) {#getPredefinedFolder-int-}
```
public final FolderInfo getPredefinedFolder(int defaultFolder)
```


Gets a standard Outlook folder of the PST, such as Inbox, Sent Items or Deleted Items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| defaultFolder | int | Which standard folder to get. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The folder.
### getRootFolder() {#getRootFolder--}
```
public final FolderInfo getRootFolder()
```


Gets the root folder of the PST, which contains all other folders.

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - [FolderInfo](../../com.aspose.email/folderinfo) that represents a root folder.
### getStore() {#getStore--}
```
public final MessageStore getStore()
```


Gets the PST message store.

**Returns:**
[MessageStore](../../com.aspose.email/messagestore) - The [MessageStore](../../com.aspose.email/messagestore), the top-level object of the PST.
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


Gets a value indicating whether the PST is in the Unicode format. Only Unicode PST files can be edited; the older ANSI format is read-only.

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


Opens a PST from a stream for reading, for a storage created with the constructor that takes a  TraversalExceptionsCallback .

Problems found while reading are reported to the callback passed to the constructor instead of being thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream with the PST data. |

**Returns:**
boolean -  true  if the stream has been loaded and can be traversed; otherwise,  false .
### load(String fileName) {#load-java.lang.String-}
```
public final boolean load(String fileName)
```


Opens a PST file for reading, for a storage created with the constructor that takes a  TraversalExceptionsCallback .

The file is opened for reading only. Problems found while reading are reported to the callback passed to the constructor instead of being thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file. |

**Returns:**
boolean -  true  if the file has been loaded and can be traversed; otherwise,  false .
### mergeWith(InputStream[] sourceStreams) {#mergeWith-java.io.InputStream---}
```
public final void mergeWith(InputStream[] sourceStreams)
```


Merges one or more other PST streams into this PST.

 StorageProcessing  is raised before each source is merged, and  StorageProcessed  after it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceStreams | java.io.InputStream[] | The streams with the PST data to merge. |

### mergeWith(String[] sourceFileNames) {#mergeWith-java.lang.String---}
```
public final void mergeWith(String[] sourceFileNames)
```


Merges one or more other PST files into this PST.

 StorageProcessing  is raised before each source is merged, and  StorageProcessed  after it.

This example merges two PST files into a third one and reports each file as it is merged.

```

 try (PersonalStorage pst = PersonalStorage.fromFile("merged.pst")) {
     pst.StorageProcessing.add(new StorageProcessingEventHandler() {
         public void invoke(Object sender, StorageProcessingEventArgs e) {
             System.out.println("Merging " + e.getFileName());
         }
     });

     // Add the contents of the other files to merged.pst
     pst.mergeWith(new String[] { "2024.pst", "2025.pst" });
 }
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFileNames | java.lang.String[] | The paths of the PST files to merge. |

### moveItem(FolderInfo folder, FolderInfo newFolder) {#moveItem-com.aspose.email.FolderInfo-com.aspose.email.FolderInfo-}
```
public final void moveItem(FolderInfo folder, FolderInfo newFolder)
```


Moves a folder to another parent folder of the same PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | [FolderInfo](../../com.aspose.email/folderinfo) | The folder to move. |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | The new parent folder. |

### moveItem(MessageInfo message, FolderInfo newFolder) {#moveItem-com.aspose.email.MessageInfo-com.aspose.email.FolderInfo-}
```
public final void moveItem(MessageInfo message, FolderInfo newFolder)
```


Moves a message to another folder of the same PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MessageInfo](../../com.aspose.email/messageinfo) | The message to move. |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | The folder to move the message to. |

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


Saves the storage to a stream in the specified format.

Use it for a fast OST to PST conversion. It does not support OST files of Outlook 2013 and later; to convert such a file, create a new PST and call its \#mergeWith(InputStream[]).mergeWith(InputStream[]) method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |
| format | int | The format to save in. |

### saveAs(String fileName, int format) {#saveAs-java.lang.String-int-}
```
public final void saveAs(String fileName, int format)
```


Saves the storage to another file in the specified format.

Use it for a fast OST to PST conversion. It does not support OST files of Outlook 2013 and later; to convert such a file, create a new PST and call its \#mergeWith(String[]).mergeWith(String[]) method.

This example converts an OST file to PST.

```

 try (PersonalStorage ost = PersonalStorage.fromFile("mailbox.ost")) {
     ost.saveAs("mailbox.pst", FileFormat.Pst);
 }
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to create. |
| format | int | The format to save in. |

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


Saves a message to a stream in Outlook MSG format, without loading it into a  MapiMessage .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the message. |
| stream | java.io.OutputStream | The stream to write to. |

### splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path) {#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-}
```
public final void splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path)
```


Splits the PST into several files by search criteria.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| criteria | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MailQuery> | The search criteria. A separate PST is created for the messages that match each [MailQuery](../../com.aspose.email/mailquery). |
| path | java.lang.String | The folder to create the PST files in. |

### splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String partFileNamePrefix, String path) {#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-java.lang.String-}
```
public final void splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String partFileNamePrefix, String path)
```


Splits the PST into several files by search criteria, named with a prefix.

The files are named after the template  \{prefix\}\_part\{number\}.pst ; without a prefix, the  \{prefix\}  part is left out.  StorageProcessed  is raised after each file is created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| criteria | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MailQuery> | The search criteria. A separate PST is created for the messages that match each [MailQuery](../../com.aspose.email/mailquery). |
| partFileNamePrefix | java.lang.String | The prefix of the file names. If it is  null  or empty, the files are named without a prefix. |
| path | java.lang.String | The folder to create the PST files in. |

### splitInto(long chunkSize, String path) {#splitInto-long-java.lang.String-}
```
public final void splitInto(long chunkSize, String path)
```


Splits the PST into files of about the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | long | The approximate size of each PST file, in bytes. It must be greater than 271,360 bytes. |
| path | java.lang.String | The folder to create the PST files in. |

### splitInto(long chunkSize, String partFileNamePrefix, String path) {#splitInto-long-java.lang.String-java.lang.String-}
```
public final void splitInto(long chunkSize, String partFileNamePrefix, String path)
```


Splits the PST into files of about the specified size, named with a prefix.

The files are named after the template  \{prefix\}\_part\{number\}.pst ; without a prefix, the  \{prefix\}  part is left out.  StorageProcessed  is raised after each file is created.

This example splits a PST into files of about 50 MB and reports each new file.

```

 try (PersonalStorage pst = PersonalStorage.fromFile("archive.pst")) {
     pst.StorageProcessed.add(new StorageProcessedEventHandler() {
         public void invoke(Object sender, StorageProcessedEventArgs e) {
             System.out.println("Created " + e.getFileName());
         }
     });

     // Files of about 50 MB, named archive_part{number}.pst
     pst.splitInto(50 * 1024 * 1024, "archive", "C:\\Split");
 }
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | long | The approximate size of each PST file, in bytes. It must be greater than 271,360 bytes. |
| partFileNamePrefix | java.lang.String | The prefix of the file names. If it is  null  or empty, the files are named without a prefix. |
| path | java.lang.String | The folder to create the PST files in. |

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


Tries to get the folder with the specified entry ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryIdString | java.lang.String | The entry ID of the folder, as a string. |
| folder | [FolderInfo\[\]](../../com.aspose.email/folderinfo) | When the method returns  true , the folder; otherwise,  null . |

**Returns:**
boolean -  true  if the folder is found; otherwise,  false .
### tryToSaveMessage(String entryId, OutputStream stream) {#tryToSaveMessage-java.lang.String-java.io.OutputStream-}
```
public final SaveResult tryToSaveMessage(String entryId, OutputStream stream)
```


Saves a message to a stream in Outlook MSG format, keeping as much of a damaged message as can be read instead of failing.

This example salvages the messages of a damaged Inbox and reports the ones that were saved only in part.

```

 try (PersonalStorage pst = PersonalStorage.fromFile("damaged.pst", false)) {
     FolderInfo inbox = pst.getPredefinedFolder(StandardIpmFolder.Inbox);
     int count = 0;

     // findMessages works even when the message list of the folder is damaged
     for (String entryId : pst.findMessages(inbox.getEntryIdString())) {
         try (FileOutputStream stream = new FileOutputStream("message_" + (++count) + ".msg")) {
             SaveResult result = pst.tryToSaveMessage(entryId, stream);
             if (result.getStatus() != SaveStatus.Success) {
                 System.out.println("message_" + count + ".msg: " + result.getStatus() + ", "
                         + result.getMissedProperties().size() + " properties lost");
             }
         } catch (IOException e) {
             e.printStackTrace();
         }
     }
 }
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the message. |
| stream | java.io.OutputStream | The stream to write to. |

**Returns:**
[SaveResult](../../com.aspose.email/saveresult) - A [SaveResult](../../com.aspose.email/saveresult) that tells whether the message was saved completely or partially, and which properties could not be read.
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

