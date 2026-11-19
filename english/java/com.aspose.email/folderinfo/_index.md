---
title: FolderInfo
second_title: Aspose.Email for Java API Reference
description: Represents a folder of a PST or OST file and gives access to its messages and subfolders.
type: docs
weight: 260
url: /java/com.aspose.email/folderinfo/
---

**Inheritance:**
java.lang.Object
```
public final class FolderInfo
```

Represents a folder of a PST or OST file and gives access to its messages and subfolders.

Get folders from a [PersonalStorage](../../com.aspose.email/personalstorage):  getRootFolder() ,  getPredefinedFolder ,  getFolderById , or the  getSubFolder  and  getSubFolders  methods of another folder. Methods that change a folder throw  UnsupportedOperationException  for an ANSI PST and  IllegalStateException  when the PST is open for reading only.
## Constructors

| Constructor | Description |
| --- | --- |
| [FolderInfo()](#FolderInfo--) | Initializes a new instance of the [FolderInfo](../../com.aspose.email/folderinfo) class. |
## Fields

| Field | Description |
| --- | --- |
| [ItemMoved](#ItemMoved) | Occurs when an item is moved to the another folder. |
| [MessageAdded](#MessageAdded) | Occurs when a message is added to the current folder. |
## Methods

| Method | Description |
| --- | --- |
| [addFile(String fileName, String messageClass)](#addFile-java.lang.String-java.lang.String-) | Adds a file to the folder as a new item with the specified message class. |
| [addMapiMessageItem(IMapiMessageItem item)](#addMapiMessageItem-com.aspose.email.IMapiMessageItem-) | Adds a message, contact, appointment, meeting, task, note or journal item to the folder. |
| [addMessage(MapiMessage message)](#addMessage-com.aspose.email.MapiMessage-) | Adds a message to the folder. |
| [addMessages(Iterable<MapiMessage> messages)](#addMessages-java.lang.Iterable-com.aspose.email.MapiMessage--) | Adds messages to the folder in bulk, which is faster than adding them one by one. |
| [addSubFolder(String name)](#addSubFolder-java.lang.String-) | Adds a subfolder with the specified name. |
| [addSubFolder(String name, boolean createHierarchy)](#addSubFolder-java.lang.String-boolean-) | Adds a subfolder. |
| [addSubFolder(String name, FolderCreationOptions creationOptions)](#addSubFolder-java.lang.String-com.aspose.email.FolderCreationOptions-) | Adds a subfolder with the specified name to the current folder using the provided creation options. |
| [addSubFolder(String name, String containerClass)](#addSubFolder-java.lang.String-java.lang.String-) | Adds a subfolder with the specified name and container class. |
| [changeContainerClass(String containerClass)](#changeContainerClass-java.lang.String-) | Changes the container class of the folder. |
| [changeDisplayName(String newName)](#changeDisplayName-java.lang.String-) | Renames the folder. |
| [changeMessages(MapiPropertyCollection updatedProperties)](#changeMessages-com.aspose.email.MapiPropertyCollection-) | Sets the specified properties on all messages of the folder. |
| [changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties)](#changeMessages-java.lang.Iterable-java.lang.String--com.aspose.email.MapiPropertyCollection-) | Sets the specified properties on the given messages of the folder. |
| [deleteChildItem(byte[] entryId)](#deleteChildItem-byte---) | Deletes a message or subfolder of this folder by its entry ID. |
| [deleteChildItems(Iterable<String> entryIdCollection)](#deleteChildItems-java.lang.Iterable-java.lang.String--) | Deletes the specified messages of the folder. |
| [enumerateFolders()](#enumerateFolders--) | Enumerates the subfolders of the folder. |
| [enumerateFolders(int kind)](#enumerateFolders-int-) | Enumerates the subfolders of the specified kind. |
| [enumerateMapiMessages()](#enumerateMapiMessages--) | Enumerates the messages of the folder as fully loaded [MapiMessage](../../com.aspose.email/mapimessage) objects. |
| [enumerateMessageObjects()](#enumerateMessageObjects--) | Enumerates the messages of the folder as [MessageObject](../../com.aspose.email/messageobject) objects. |
| [enumerateMessages()](#enumerateMessages--) | Retrieves [MessageInfo](../../com.aspose.email/messageinfo) objects from the folder. |
| [enumerateMessages(MailQuery mailQuery)](#enumerateMessages-com.aspose.email.MailQuery-) | Retrieves a collection of [MessageInfo](../../com.aspose.email/messageinfo) objects that match the specified query. |
| [enumerateMessages(int kind)](#enumerateMessages-int-) | Retrieves a collection of [MessageInfo](../../com.aspose.email/messageinfo) objects of the specified kind. |
| [enumerateMessages(int startIndex, int count)](#enumerateMessages-int-int-) | Retrieves a collection of [MessageInfo](../../com.aspose.email/messageinfo) objects starting from a specific index and limited to a specified count. |
| [enumerateMessagesEntryId()](#enumerateMessagesEntryId--) | Enumerates the entry IDs of the messages in the folder. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainerClass()](#getContainerClass--) | Gets the container class of the folder, which defines the kind of items it holds, for example  IPF.Note  for mail. |
| [getContentCount()](#getContentCount--) | Gets the total number of items in the folder. |
| [getContentUnreadCount()](#getContentUnreadCount--) | Gets the number of unread items in the folder. |
| [getContents()](#getContents--) | Gets information about all messages in the folder. |
| [getContents(boolean tryToReadCorruptedContents)](#getContents-boolean-) | Gets information about the messages in the folder, optionally reading a damaged message list. |
| [getContents(MailQuery query)](#getContents-com.aspose.email.MailQuery-) | Gets information about the messages that match a query. |
| [getContents(MailQuery query, int startIndex, int count)](#getContents-com.aspose.email.MailQuery-int-int-) | Gets information about a range of the messages that match a query. |
| [getContents(int kind)](#getContents-int-) | Gets information about the messages of the specified kind. |
| [getContents(int startIndex, int count)](#getContents-int-int-) | Gets information about a range of the messages in the folder. |
| [getDisplayName()](#getDisplayName--) | Gets the display name of folder. |
| [getEntryId()](#getEntryId--) | Gets the entry ID of the folder, which identifies it in the PST. |
| [getEntryIdString()](#getEntryIdString--) | Gets the entry ID of the folder as a string. |
| [getLastModificationTime()](#getLastModificationTime--) | Gets the last modification time. |
| [getPredefinedType(boolean getForTopLevelParent)](#getPredefinedType-boolean-) | Gets which standard Outlook folder, such as Inbox or Sent Items, this folder is. |
| [getProperties()](#getProperties--) | Gets the MAPI properties of the folder. |
| [getSubFolder(String name)](#getSubFolder-java.lang.String-) | Gets the subfolder with the specified name. |
| [getSubFolder(String name, boolean ignoreCase)](#getSubFolder-java.lang.String-boolean-) | Gets the subfolder with the specified name, optionally ignoring case. |
| [getSubFolder(String name, boolean ignoreCase, boolean handlePathSeparator)](#getSubFolder-java.lang.String-boolean-boolean-) | Retrieves a subfolder with the specified name from the current folder. |
| [getSubFolders()](#getSubFolders--) | Gets the subfolders of the folder. |
| [getSubFolders(MailQuery query)](#getSubFolders-com.aspose.email.MailQuery-) | Gets the subfolders that match a query. |
| [getSubFolders(int kind)](#getSubFolders-int-) | Gets the subfolders of the specified kind. |
| [hasSubFolders()](#hasSubFolders--) | Gets a value indicating whether the Folder object has any subfolders. |
| [hashCode()](#hashCode--) |  |
| [mergeWith(FolderInfo sourceFolder)](#mergeWith-com.aspose.email.FolderInfo-) | Merges a folder from another PST into this folder. |
| [mergeWith(FolderInfo sourceFolder, boolean recursiveHandler)](#mergeWith-com.aspose.email.FolderInfo-boolean-) | Merges a folder from another PST into this folder and raises  ItemMoved  for the merged messages and folders. |
| [moveContents(FolderInfo newFolder)](#moveContents-com.aspose.email.FolderInfo-) | Moves all messages of this folder to another folder. |
| [moveSubfolders(FolderInfo newFolder)](#moveSubfolders-com.aspose.email.FolderInfo-) | Moves all subfolders of this folder to another parent folder. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [retrieveFullPath()](#retrieveFullPath--) | Gets the path of the folder from the root of the PST. |
| [setReadStatus(Iterable<String> messageEntryIds, boolean isRead)](#setReadStatus-java.lang.Iterable-java.lang.String--boolean-) | Sets or clears the  Read  status for the specified messages in a PST file. |
| [toString()](#toString--) |  |
| [updateMessage(String entryId, MapiMessageItemBase updatedMessage)](#updateMessage-java.lang.String-com.aspose.email.MapiMessageItemBase-) | Updates the message with the specified entry ID. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FolderInfo() {#FolderInfo--}
```
public FolderInfo()
```


Initializes a new instance of the [FolderInfo](../../com.aspose.email/folderinfo) class.

A folder created this way is not connected to any PST. To work with a folder, get it from a [PersonalStorage](../../com.aspose.email/personalstorage) object.

### ItemMoved {#ItemMoved}
```
public Event<ItemMovedEventHandler> ItemMoved
```


Occurs when an item is moved to the another folder.

### MessageAdded {#MessageAdded}
```
public final Event<MessageAddedEventHandler> MessageAdded
```


Occurs when a message is added to the current folder.

### addFile(String fileName, String messageClass) {#addFile-java.lang.String-java.lang.String-}
```
public final String addFile(String fileName, String messageClass)
```


Adds a file to the folder as a new item with the specified message class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to add. |
| messageClass | java.lang.String | The message class of the new item. |

**Returns:**
java.lang.String - The entry ID of the new item.
### addMapiMessageItem(IMapiMessageItem item) {#addMapiMessageItem-com.aspose.email.IMapiMessageItem-}
```
public final String addMapiMessageItem(IMapiMessageItem item)
```


Adds a message, contact, appointment, meeting, task, note or journal item to the folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMapiMessageItem](../../com.aspose.email/imapimessageitem) | The item to add. |

**Returns:**
java.lang.String - The entry ID of the added item.
### addMessage(MapiMessage message) {#addMessage-com.aspose.email.MapiMessage-}
```
public final String addMessage(MapiMessage message)
```


Adds a message to the folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The message to add. |

**Returns:**
java.lang.String - The entry ID of the added message.
### addMessages(Iterable<MapiMessage> messages) {#addMessages-java.lang.Iterable-com.aspose.email.MapiMessage--}
```
public final void addMessages(Iterable<MapiMessage> messages)
```


Adds messages to the folder in bulk, which is faster than adding them one by one.

The  MessageAdded  event is raised for each added message and gives its entry ID.

This example adds all .msg files of a directory to the Inbox and prints the entry ID of each added message.

```

 try (PersonalStorage pst = PersonalStorage.fromFile("archive.pst")) {
     FolderInfo inbox = pst.getPredefinedFolder(StandardIpmFolder.Inbox);

     // Called once for every message added in bulk
     inbox.MessageAdded.add(new MessageAddedEventHandler() {
         public void invoke(Object sender, MessageAddedEventArgs e) {
             System.out.println("Added " + e.getEntryId());
         }
     });

     // Messages of the directory
     java.util.List messages = new java.util.ArrayList();
     for (java.io.File file : new java.io.File("C:\\Messages").listFiles((dir, name) -> name.endsWith(".msg"))) {
         messages.add(MapiMessage.load(file.getPath()));
     }

     inbox.addMessages(messages);
 }
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MapiMessage> | The messages to add. |

### addSubFolder(String name) {#addSubFolder-java.lang.String-}
```
public final FolderInfo addSubFolder(String name)
```


Adds a subfolder with the specified name.

The new folder gets the container class of this folder, or  IPF.Note  if this folder has none.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the subfolder. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new subfolder.
### addSubFolder(String name, boolean createHierarchy) {#addSubFolder-java.lang.String-boolean-}
```
public final FolderInfo addSubFolder(String name, boolean createHierarchy)
```


Adds a subfolder. With  createHierarchy , the name can be a path, and the missing folders are created.

The new folder gets the container class of this folder, or  IPF.Note  if this folder has none.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the subfolder, or a path such as  Parent\\Child  when  createHierarchy  is  true . |
| createHierarchy | boolean |  true  to treat  name  as a path separated by backslashes and create the folders that do not exist yet. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new subfolder.
### addSubFolder(String name, FolderCreationOptions creationOptions) {#addSubFolder-java.lang.String-com.aspose.email.FolderCreationOptions-}
```
public final FolderInfo addSubFolder(String name, FolderCreationOptions creationOptions)
```


Adds a subfolder with the specified name to the current folder using the provided creation options.

 name  can be a path with backslash separators, such as  Parent1\\Parent2\\Subfolder ; set [FolderCreationOptions.getCreateHierarchy()](../../com.aspose.email/foldercreationoptions\#getCreateHierarchy--) to create the parent folders that do not exist yet. Whether a folder with the same name already exists depends on [FolderCreationOptions.getAllowNameCaseDifference()](../../com.aspose.email/foldercreationoptions\#getAllowNameCaseDifference--): when it is  false  (the default), names are compared case-insensitively and an existing name throws  IllegalStateException ; when it is  true , a name that differs only in case creates a new folder.

This example creates a folder three levels deep, adding the parent folders that are missing.

```

 try (PersonalStorage pst = PersonalStorage.fromFile("archive.pst")) {
     // Treat the name as a path and create the folders that do not exist yet
     FolderCreationOptions options = new FolderCreationOptions();
     options.setCreateHierarchy(true);

     FolderInfo folder = pst.getRootFolder().addSubFolder("Projects\\2026\\Reports", options);
     System.out.println("Created " + folder.getDisplayName());
 }
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the subfolder to add. |
| creationOptions | [FolderCreationOptions](../../com.aspose.email/foldercreationoptions) | The options for creating the subfolder. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The [FolderInfo](../../com.aspose.email/folderinfo) representing the added subfolder.
### addSubFolder(String name, String containerClass) {#addSubFolder-java.lang.String-java.lang.String-}
```
public final FolderInfo addSubFolder(String name, String containerClass)
```


Adds a subfolder with the specified name and container class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the subfolder. |
| containerClass | java.lang.String | The container class of the new folder, for example  IPF.Note  for mail or  IPF.Appointment  for a calendar. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new subfolder.
### changeContainerClass(String containerClass) {#changeContainerClass-java.lang.String-}
```
public final void changeContainerClass(String containerClass)
```


Changes the container class of the folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| containerClass | java.lang.String | The new container class, for example  IPF.Note  for mail. |

### changeDisplayName(String newName) {#changeDisplayName-java.lang.String-}
```
public final void changeDisplayName(String newName)
```


Renames the folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newName | java.lang.String | The new name of the folder. |

### changeMessages(MapiPropertyCollection updatedProperties) {#changeMessages-com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessages(MapiPropertyCollection updatedProperties)
```


Sets the specified properties on all messages of the folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | The properties to set. |

### changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties) {#changeMessages-java.lang.Iterable-java.lang.String--com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties)
```


Sets the specified properties on the given messages of the folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryIdCollection | java.lang.Iterable<java.lang.String> | The entry IDs of the messages to change. |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | The properties to set. |

### deleteChildItem(byte[] entryId) {#deleteChildItem-byte---}
```
public final void deleteChildItem(byte[] entryId)
```


Deletes a message or subfolder of this folder by its entry ID.

The item must be a direct child of this folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | byte[] | The entry ID of the item to delete. |

### deleteChildItems(Iterable<String> entryIdCollection) {#deleteChildItems-java.lang.Iterable-java.lang.String--}
```
public final void deleteChildItems(Iterable<String> entryIdCollection)
```


Deletes the specified messages of the folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryIdCollection | java.lang.Iterable<java.lang.String> | The entry IDs of the messages to delete. |

### enumerateFolders() {#enumerateFolders--}
```
public final System.Collections.Generic.IGenericEnumerable<FolderInfo> enumerateFolders()
```


Enumerates the subfolders of the folder.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.FolderInfo> - The subfolders. They are read from the file as the sequence is enumerated.
### enumerateFolders(int kind) {#enumerateFolders-int-}
```
public final System.Collections.Generic.IGenericEnumerable<FolderInfo> enumerateFolders(int kind)
```


Enumerates the subfolders of the specified kind.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kind | int | Which kinds of folders to return: normal folders, search folders or both. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.FolderInfo> - The subfolders. They are read from the file as the sequence is enumerated.
### enumerateMapiMessages() {#enumerateMapiMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MapiMessage> enumerateMapiMessages()
```


Enumerates the messages of the folder as fully loaded [MapiMessage](../../com.aspose.email/mapimessage) objects.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MapiMessage> - The messages. They are read from the file as the sequence is enumerated.
### enumerateMessageObjects() {#enumerateMessageObjects--}
```
public final System.Collections.Generic.IGenericEnumerable<MessageObject> enumerateMessageObjects()
```


Enumerates the messages of the folder as [MessageObject](../../com.aspose.email/messageobject) objects.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageObject> - The messages. They are read from the file as the sequence is enumerated.
### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages()
```


Retrieves [MessageInfo](../../com.aspose.email/messageinfo) objects from the folder.

Use this method to iterate through all messages in the folder without applying any filters or limits. Folder associated information (FAI) items, such as hidden metadata or configuration items, are not included in the returned collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> - An enumerable collection of all [MessageInfo](../../com.aspose.email/messageinfo) objects in the folder, excluding folder associated information (FAI) items.
### enumerateMessages(MailQuery mailQuery) {#enumerateMessages-com.aspose.email.MailQuery-}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages(MailQuery mailQuery)
```


Retrieves a collection of [MessageInfo](../../com.aspose.email/messageinfo) objects that match the specified query.

Use this method to retrieve messages that satisfy specific conditions, such as sender, subject, or date range, as defined by the  mailQuery .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailQuery | [MailQuery](../../com.aspose.email/mailquery) | The query criteria used to filter messages. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> - An enumerable collection of [MessageInfo](../../com.aspose.email/messageinfo) objects matching the query.
### enumerateMessages(int kind) {#enumerateMessages-int-}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages(int kind)
```


Retrieves a collection of [MessageInfo](../../com.aspose.email/messageinfo) objects of the specified kind.

Use this method to filter items based on their type, such as distinguishing between messages or Folder Associated Information items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kind | int | The type of items to retrieve, such as normal messages or folder associated information items. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> - An enumerable collection of [MessageInfo](../../com.aspose.email/messageinfo) objects of the specified kind.
### enumerateMessages(int startIndex, int count) {#enumerateMessages-int-int-}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages(int startIndex, int count)
```


Retrieves a collection of [MessageInfo](../../com.aspose.email/messageinfo) objects starting from a specific index and limited to a specified count.

Use this method to fetch a subset of messages from the folder, which is useful for paginated retrieval or scenarios requiring controlled message processing. When  count  is set to  -1 , all messages from  startIndex  to the end of the folder are returned.

This example reads a large folder in pages of 100 messages.

```

 try (PersonalStorage pst = PersonalStorage.fromFile("archive.pst")) {
     FolderInfo inbox = pst.getPredefinedFolder(StandardIpmFolder.Inbox);
     final int pageSize = 100;

     for (int start = 0; start < inbox.getContentCount(); start += pageSize) {
         for (MessageInfo messageInfo : inbox.enumerateMessages(start, pageSize)) {
             System.out.println(messageInfo.getSubject());
         }
     }
 }
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | The zero-based index of the first message to retrieve. |
| count | int | The maximum number of messages to retrieve. If set to  -1 , retrieves all messages starting from the specified  startIndex . |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> - An enumerable collection of [MessageInfo](../../com.aspose.email/messageinfo) objects starting at the specified index.
### enumerateMessagesEntryId() {#enumerateMessagesEntryId--}
```
public final System.Collections.Generic.IGenericEnumerable<String> enumerateMessagesEntryId()
```


Enumerates the entry IDs of the messages in the folder.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<java.lang.String> - The entry IDs as strings. They are read from the file as the sequence is enumerated.
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
### getContainerClass() {#getContainerClass--}
```
public final String getContainerClass()
```


Gets the container class of the folder, which defines the kind of items it holds, for example  IPF.Note  for mail.

**Returns:**
java.lang.String - The container class.
### getContentCount() {#getContentCount--}
```
public final int getContentCount()
```


Gets the total number of items in the folder.

**Returns:**
int - The number of items in the folder.
### getContentUnreadCount() {#getContentUnreadCount--}
```
public final int getContentUnreadCount()
```


Gets the number of unread items in the folder.

**Returns:**
int - The number of unread items in the folder.
### getContents() {#getContents--}
```
public final MessageInfoCollection getContents()
```


Gets information about all messages in the folder.

The whole list is read into memory. For a large folder,  enumerateMessages  reads the messages one at a time.

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Information about the messages. Use  PersonalStorage.extractMessage  to load a full message.
### getContents(boolean tryToReadCorruptedContents) {#getContents-boolean-}
```
public final MessageInfoCollection getContents(boolean tryToReadCorruptedContents)
```


Gets information about the messages in the folder, optionally reading a damaged message list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tryToReadCorruptedContents | boolean |  true  to try to read the list of messages even if parts of it are damaged; use it when  getContents()  fails because the file is corrupted.  false  gives the same result as  getContents() . |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Information about the messages. Use  PersonalStorage.extractMessage  to load a full message.
### getContents(MailQuery query) {#getContents-com.aspose.email.MailQuery-}
```
public final MessageInfoCollection getContents(MailQuery query)
```


Gets information about the messages that match a query.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | The search query, built with [PersonalStorageQueryBuilder](../../com.aspose.email/personalstoragequerybuilder). |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Information about the messages. Use  PersonalStorage.extractMessage  to load a full message.
### getContents(MailQuery query, int startIndex, int count) {#getContents-com.aspose.email.MailQuery-int-int-}
```
public final MessageInfoCollection getContents(MailQuery query, int startIndex, int count)
```


Gets information about a range of the messages that match a query.

If  count  is negative or greater than the number of remaining messages, all remaining messages are returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | The search query, built with [PersonalStorageQueryBuilder](../../com.aspose.email/personalstoragequerybuilder). |
| startIndex | int | The zero-based index of the first message to return. |
| count | int | The maximum number of messages to return. |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Information about the messages. Use  PersonalStorage.extractMessage  to load a full message.
### getContents(int kind) {#getContents-int-}
```
public final MessageInfoCollection getContents(int kind)
```


Gets information about the messages of the specified kind.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kind | int | Normal messages, folder associated information (FAI) items, or both. |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Information about the messages. Use  PersonalStorage.extractMessage  to load a full message.
### getContents(int startIndex, int count) {#getContents-int-int-}
```
public final MessageInfoCollection getContents(int startIndex, int count)
```


Gets information about a range of the messages in the folder.

If  count  is negative or greater than the number of remaining messages, all remaining messages are returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | The zero-based index of the first message to return. |
| count | int | The maximum number of messages to return. |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Information about the messages. Use  PersonalStorage.extractMessage  to load a full message.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the display name of folder.

**Returns:**
java.lang.String - The name of the folder.
### getEntryId() {#getEntryId--}
```
public final byte[] getEntryId()
```


Gets the entry ID of the folder, which identifies it in the PST.

**Returns:**
byte[] - The entry ID as a byte array.
### getEntryIdString() {#getEntryIdString--}
```
public final String getEntryIdString()
```


Gets the entry ID of the folder as a string.

**Returns:**
java.lang.String - The entry ID in the string form accepted by  PersonalStorage.getFolderById .
### getLastModificationTime() {#getLastModificationTime--}
```
public final Date getLastModificationTime()
```


Gets the last modification time.

**Returns:**
java.util.Date - The time of the last change, or  DateTime.MinValue  if the folder does not have the PR\_LAST\_MODIFICATION\_TIME property.
### getPredefinedType(boolean getForTopLevelParent) {#getPredefinedType-boolean-}
```
public final int getPredefinedType(boolean getForTopLevelParent)
```


Gets which standard Outlook folder, such as Inbox or Sent Items, this folder is.

Use it to find out whether a folder is, or lies inside, one of the standard Outlook folders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| getForTopLevelParent | boolean |  true  to check the top-level folder this folder belongs to, which tells whether it is inside a standard folder;  false  to check this folder itself. |

**Returns:**
int - The [StandardIpmFolder](../../com.aspose.email/standardipmfolder) value, or  StandardIpmFolder.Unspecified  if the folder is not a standard one.
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


Gets the MAPI properties of the folder.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getSubFolder(String name) {#getSubFolder-java.lang.String-}
```
public final FolderInfo getSubFolder(String name)
```


Gets the subfolder with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the subfolder. The comparison is case-sensitive. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The subfolder, or  null  if there is no subfolder with this name.
### getSubFolder(String name, boolean ignoreCase) {#getSubFolder-java.lang.String-boolean-}
```
public final FolderInfo getSubFolder(String name, boolean ignoreCase)
```


Gets the subfolder with the specified name, optionally ignoring case.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the subfolder. |
| ignoreCase | boolean |  true  to compare names case-insensitively. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The subfolder, or  null  if there is no subfolder with this name.
### getSubFolder(String name, boolean ignoreCase, boolean handlePathSeparator) {#getSubFolder-java.lang.String-boolean-boolean-}
```
public final FolderInfo getSubFolder(String name, boolean ignoreCase, boolean handlePathSeparator)
```


Retrieves a subfolder with the specified name from the current folder.

The  name  parameter specifies the name of the subfolder to retrieve.

The  ignoreCase  parameter determines whether the search for the subfolder name should be case-sensitive or case-insensitive. If set to  true , the search will be case-insensitive, otherwise, it will be case-sensitive.

The  handlePathSeparator  parameter specifies whether the specified folder name should be treated as a path if it contains backslashes. If set to  true , the method will interpret the folder name as a path, attempting to navigate to the subfolder using the path. If set to  false , the method will treat the folder name as a simple name, searching for a subfolder with an exact name match.

If the subfolder is found, the method returns the [FolderInfo](../../com.aspose.email/folderinfo) object representing the retrieved subfolder. If the subfolder is not found, the method returns  null .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the subfolder to retrieve. |
| ignoreCase | boolean | Specifies whether to perform a case-insensitive search for folders with the given name. |
| handlePathSeparator | boolean | Specifies whether the specified folder name should be treated as a path if it contains backslashes. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The [FolderInfo](../../com.aspose.email/folderinfo) representing the retrieved subfolder, or  null  if the subfolder is not found.
### getSubFolders() {#getSubFolders--}
```
public final FolderInfoCollection getSubFolders()
```


Gets the subfolders of the folder.

For a folder with many subfolders,  enumerateFolders  reads them one at a time.

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The subfolders.
### getSubFolders(MailQuery query) {#getSubFolders-com.aspose.email.MailQuery-}
```
public final FolderInfoCollection getSubFolders(MailQuery query)
```


Gets the subfolders that match a query.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | The search query, built with [PersonalStorageQueryBuilder](../../com.aspose.email/personalstoragequerybuilder), for example with its  getFolderName()  or  getContentsCount()  field. |

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The matching subfolders.
### getSubFolders(int kind) {#getSubFolders-int-}
```
public final FolderInfoCollection getSubFolders(int kind)
```


Gets the subfolders of the specified kind.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kind | int | Which kinds of folders to return: normal folders, search folders or both. |

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The subfolders.
### hasSubFolders() {#hasSubFolders--}
```
public final boolean hasSubFolders()
```


Gets a value indicating whether the Folder object has any subfolders.

**Returns:**
boolean -  true  if the folder has subfolders; otherwise,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mergeWith(FolderInfo sourceFolder) {#mergeWith-com.aspose.email.FolderInfo-}
```
public final void mergeWith(FolderInfo sourceFolder)
```


Merges a folder from another PST into this folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | [FolderInfo](../../com.aspose.email/folderinfo) | The folder to merge. It must belong to another PST. |

### mergeWith(FolderInfo sourceFolder, boolean recursiveHandler) {#mergeWith-com.aspose.email.FolderInfo-boolean-}
```
public final void mergeWith(FolderInfo sourceFolder, boolean recursiveHandler)
```


Merges a folder from another PST into this folder and raises  ItemMoved  for the merged messages and folders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | [FolderInfo](../../com.aspose.email/folderinfo) | The folder to merge. It must belong to another PST. |
| recursiveHandler | boolean |  true  to raise  ItemMoved  for the messages in the subfolders of  sourceFolder  too;  false  to raise it only for the messages directly in  sourceFolder . |

### moveContents(FolderInfo newFolder) {#moveContents-com.aspose.email.FolderInfo-}
```
public final void moveContents(FolderInfo newFolder)
```


Moves all messages of this folder to another folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | The folder to move the messages to. |

### moveSubfolders(FolderInfo newFolder) {#moveSubfolders-com.aspose.email.FolderInfo-}
```
public final void moveSubfolders(FolderInfo newFolder)
```


Moves all subfolders of this folder to another parent folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | The new parent folder. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### retrieveFullPath() {#retrieveFullPath--}
```
public final String retrieveFullPath()
```


Gets the path of the folder from the root of the PST.

**Returns:**
java.lang.String - The full path of the folder.
### setReadStatus(Iterable<String> messageEntryIds, boolean isRead) {#setReadStatus-java.lang.Iterable-java.lang.String--boolean-}
```
public final void setReadStatus(Iterable<String> messageEntryIds, boolean isRead)
```


Sets or clears the  Read  status for the specified messages in a PST file.

This method updates the read/unread state of existing messages without modifying their content or other message properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageEntryIds | java.lang.Iterable<java.lang.String> | A list of message entry IDs that identify the messages whose read status should be updated. |
| isRead | boolean |  true  to mark the messages as read;  false  to mark them as unread. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateMessage(String entryId, MapiMessageItemBase updatedMessage) {#updateMessage-java.lang.String-com.aspose.email.MapiMessageItemBase-}
```
public final void updateMessage(String entryId, MapiMessageItemBase updatedMessage)
```


Updates the message with the specified entry ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the message to update. |
| updatedMessage | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message with the new content. |

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

