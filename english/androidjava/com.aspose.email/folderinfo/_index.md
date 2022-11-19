---
title: FolderInfo
second_title: Aspose.Email for Android via Java API Reference
description: Represents information about personal folder in PST.
type: docs
weight: 141
url: /androidjava/com.aspose.email/folderinfo/
---

**Inheritance:**
java.lang.Object
```
public final class FolderInfo
```

Represents information about personal folder in PST.
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
| [addFile(String fileName, String messageClass)](#addFile-java.lang.String-java.lang.String-) | Adds a file into pst folder. |
| [addMapiMessageItem(IMapiMessageItem item)](#addMapiMessageItem-com.aspose.email.IMapiMessageItem-) | Adds the IMapiMessageItem object into folder. |
| [addMessage(MapiMessage message)](#addMessage-com.aspose.email.MapiMessage-) | Adds a new message into folder. |
| [addMessages(Iterable<MapiMessage> messages)](#addMessages-java.lang.Iterable-com.aspose.email.MapiMessage--) | Provides message adding in a bulk mode. |
| [addSubFolder(String name)](#addSubFolder-java.lang.String-) | Adds the new sub-folder. |
| [addSubFolder(String name, boolean createHierarchy)](#addSubFolder-java.lang.String-boolean-) | Adds the new sub-folder. |
| [addSubFolder(String name, String containerClass)](#addSubFolder-java.lang.String-java.lang.String-) | Adds the new subfolder. |
| [changeContainerClass(String containerClass)](#changeContainerClass-java.lang.String-) | Changes the container class. |
| [changeDisplayName(String newName)](#changeDisplayName-java.lang.String-) | Changes the display name. |
| [changeMessages(MapiPropertyCollection updatedProperties)](#changeMessages-com.aspose.email.MapiPropertyCollection-) | Changes all messages in folder. |
| [changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties)](#changeMessages-java.lang.Iterable-java.lang.String--com.aspose.email.MapiPropertyCollection-) | Changes the messages in folder. |
| [deleteChildItem(byte[] entryId)](#deleteChildItem-byte---) | Deletes the item (folder or message) by it's entryId. |
| [deleteChildItems(Iterable<String> entryIdCollection)](#deleteChildItems-java.lang.Iterable-java.lang.String--) | Deletes the child messages. |
| [enumerateFolders()](#enumerateFolders--) | Exposes the enumerator, which supports an iteration of subfolders in folder. |
| [enumerateFolders(int kind)](#enumerateFolders-int-) | Exposes the enumerator, which supports an iteration of subfolders in folder. |
| [enumerateMapiMessages()](#enumerateMapiMessages--) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [enumerateMessageObjects()](#enumerateMessageObjects--) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [enumerateMessages()](#enumerateMessages--) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [enumerateMessagesEntryId()](#enumerateMessagesEntryId--) | Enumerates the entryID of messages. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainerClass()](#getContainerClass--) | Gets container class of the folder object. |
| [getContentCount()](#getContentCount--) | Gets the total number of items in the folder. |
| [getContentUnreadCount()](#getContentUnreadCount--) | Gets the number of unread items in the folder. |
| [getContents()](#getContents--) | Get collection of messages.
Method is used to display brief message information [MessageInfo](../../com.aspose.email/messageinfo) like subject, sender, recipients. |
| [getContents(boolean tryToReadCorruptedContents)](#getContents-boolean-) | Get collection of messages.
Method is used to display brief message information [MessageInfo](../../com.aspose.email/messageinfo) like subject, sender, recipients. |
| [getContents(MailQuery query)](#getContents-com.aspose.email.MailQuery-) | Get collection of messages.
Method is used to display brief message information [MessageInfo](../../com.aspose.email/messageinfo) like subject, sender, recipients. |
| [getContents(int kind)](#getContents-int-) | Get collection of messages.
Method is used to display brief message information [MessageInfo](../../com.aspose.email/messageinfo) like subject, sender, recipients. |
| [getContents(int startIndex, int count)](#getContents-int-int-) | Gets the collection of messages.
Method is used to display brief message information [MessageInfo](../../com.aspose.email/messageinfo) like subject, sender, recipients. |
| [getDisplayName()](#getDisplayName--) | Gets the display name of folder. |
| [getEntryId()](#getEntryId--) | Gets the entry ID. |
| [getEntryIdString()](#getEntryIdString--) | Gets string representation of entry ID. |
| [getLastModificationTime()](#getLastModificationTime--) | Gets the last modification time. |
| [getProperties()](#getProperties--) | Gets the folder properties. |
| [getSubFolder(String name)](#getSubFolder-java.lang.String-) | Get subfolder. |
| [getSubFolder(String name, boolean ignoreCase)](#getSubFolder-java.lang.String-boolean-) | Gets the subfolder. |
| [getSubFolders()](#getSubFolders--) | Gets collection of subfolders. |
| [getSubFolders(MailQuery query)](#getSubFolders-com.aspose.email.MailQuery-) | Gets collection of subfolders. |
| [getSubFolders(int kind)](#getSubFolders-int-) | Gets collection of subfolders. |
| [hasSubFolders()](#hasSubFolders--) | Gets a value indicating whether the Folder object has any subfolders. |
| [hashCode()](#hashCode--) |  |
| [mergeWith(FolderInfo sourceFolder)](#mergeWith-com.aspose.email.FolderInfo-) | Merges the folder with the folder from another pst. |
| [mergeWith(FolderInfo sourceFolder, boolean recursiveHandler)](#mergeWith-com.aspose.email.FolderInfo-boolean-) | Merges the folder with the folder from another pst. |
| [moveContents(FolderInfo newFolder)](#moveContents-com.aspose.email.FolderInfo-) | Moves the contents to a new folder. |
| [moveSubfolders(FolderInfo newFolder)](#moveSubfolders-com.aspose.email.FolderInfo-) | Moves the subfolders to a new parent folder. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [retrieveFullPath()](#retrieveFullPath--) | Retrieves the full path of folder within the PST file. |
| [toString()](#toString--) |  |
| [updateMessage(String entryId, MapiMessageItemBase updatedMessage)](#updateMessage-java.lang.String-com.aspose.email.MapiMessageItemBase-) | Updates the message in folder. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FolderInfo() {#FolderInfo--}
```
public FolderInfo()
```


Initializes a new instance of the [FolderInfo](../../com.aspose.email/folderinfo) class.

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


Adds a file into pst folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The name of file necessary to add. |
| messageClass | java.lang.String | The message class. |

**Returns:**
java.lang.String - The string that represents the EntryId of the added message.
### addMapiMessageItem(IMapiMessageItem item) {#addMapiMessageItem-com.aspose.email.IMapiMessageItem-}
```
public final String addMapiMessageItem(IMapiMessageItem item)
```


Adds the IMapiMessageItem object into folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMapiMessageItem](../../com.aspose.email/imapimessageitem) | The item necessary to add. |

**Returns:**
java.lang.String - The string that represents the EntryId of the added item.
### addMessage(MapiMessage message) {#addMessage-com.aspose.email.MapiMessage-}
```
public final String addMessage(MapiMessage message)
```


Adds a new message into folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The message necessary to add. |

**Returns:**
java.lang.String - The string that represents the EntryId of the added message.
### addMessages(Iterable<MapiMessage> messages) {#addMessages-java.lang.Iterable-com.aspose.email.MapiMessage--}
```
public final void addMessages(Iterable<MapiMessage> messages)
```


Provides message adding in a bulk mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MapiMessage> | An IEnumerator representing the enumerator, which supports iteration over a collection of [MapiMessage](../../com.aspose.email/mapimessage). |

### addSubFolder(String name) {#addSubFolder-java.lang.String-}
```
public final FolderInfo addSubFolder(String name)
```


Adds the new sub-folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of sub-folder. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new sub-folder.
### addSubFolder(String name, boolean createHierarchy) {#addSubFolder-java.lang.String-boolean-}
```
public final FolderInfo addSubFolder(String name, boolean createHierarchy)
```


Adds the new sub-folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of sub-folder. |
| createHierarchy | boolean | if set to  true , it is possible to create a folder hierarchy using string notation. Backslash ('\\') is used as path separator. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new sub-folder.
### addSubFolder(String name, String containerClass) {#addSubFolder-java.lang.String-java.lang.String-}
```
public final FolderInfo addSubFolder(String name, String containerClass)
```


Adds the new subfolder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of subfolder. |
| containerClass | java.lang.String | Container class of the sub-Folder object. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new subfolder.
### changeContainerClass(String containerClass) {#changeContainerClass-java.lang.String-}
```
public final void changeContainerClass(String containerClass)
```


Changes the container class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| containerClass | java.lang.String | Container class of the of the folder object. |

### changeDisplayName(String newName) {#changeDisplayName-java.lang.String-}
```
public final void changeDisplayName(String newName)
```


Changes the display name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newName | java.lang.String | A new name. |

### changeMessages(MapiPropertyCollection updatedProperties) {#changeMessages-com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessages(MapiPropertyCollection updatedProperties)
```


Changes all messages in folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | The updated properties. |

### changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties) {#changeMessages-java.lang.Iterable-java.lang.String--com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties)
```


Changes the messages in folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryIdCollection | java.lang.Iterable<java.lang.String> | The entry identifier collection. |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | The updated properties. |

### deleteChildItem(byte[] entryId) {#deleteChildItem-byte---}
```
public final void deleteChildItem(byte[] entryId)
```


Deletes the item (folder or message) by it's entryId.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | byte[] | The entry id.

--------------------

The item must be contained in a folder. |

### deleteChildItems(Iterable<String> entryIdCollection) {#deleteChildItems-java.lang.Iterable-java.lang.String--}
```
public final void deleteChildItems(Iterable<String> entryIdCollection)
```


Deletes the child messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryIdCollection | java.lang.Iterable<java.lang.String> | The entry id collection. |

### enumerateFolders() {#enumerateFolders--}
```
public final System.Collections.Generic.IGenericEnumerable<FolderInfo> enumerateFolders()
```


Exposes the enumerator, which supports an iteration of subfolders in folder.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.FolderInfo> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a subfolders in folder.
### enumerateFolders(int kind) {#enumerateFolders-int-}
```
public final System.Collections.Generic.IGenericEnumerable<FolderInfo> enumerateFolders(int kind)
```


Exposes the enumerator, which supports an iteration of subfolders in folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kind | int | The [FolderKind](../../com.aspose.email/folderkind) that represents kind of folder. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.FolderInfo> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a subfolders in folder.
### enumerateMapiMessages() {#enumerateMapiMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MapiMessage> enumerateMapiMessages()
```


Exposes the enumerator, which supports an iteration of messages in folder.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MapiMessage> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in folder.
### enumerateMessageObjects() {#enumerateMessageObjects--}
```
public final System.Collections.Generic.IGenericEnumerable<MessageObject> enumerateMessageObjects()
```


Exposes the enumerator, which supports an iteration of messages in folder.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageObject> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in folder.
### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages()
```


Exposes the enumerator, which supports an iteration of messages in folder.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in folder.
### enumerateMessagesEntryId() {#enumerateMessagesEntryId--}
```
public final System.Collections.Generic.IGenericEnumerable<String> enumerateMessagesEntryId()
```


Enumerates the entryID of messages.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<java.lang.String> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through entryID of messages in folder.
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


Gets container class of the folder object.

Value: The container class.

**Returns:**
java.lang.String
### getContentCount() {#getContentCount--}
```
public final int getContentCount()
```


Gets the total number of items in the folder.

Value: The content count.

**Returns:**
int
### getContentUnreadCount() {#getContentUnreadCount--}
```
public final int getContentUnreadCount()
```


Gets the number of unread items in the folder.

Value: The content unread count.

**Returns:**
int
### getContents() {#getContents--}
```
public final MessageInfoCollection getContents()
```


Get collection of messages.
Method is used to display brief message information [MessageInfo](../../com.aspose.email/messageinfo) like subject, sender, recipients. In terms of performance, this is the most suitable option for obtaining primary information about messages. To extract complete message data, the [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-) method is provided.

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(boolean tryToReadCorruptedContents) {#getContents-boolean-}
```
public final MessageInfoCollection getContents(boolean tryToReadCorruptedContents)
```


Get collection of messages.
Method is used to display brief message information [MessageInfo](../../com.aspose.email/messageinfo) like subject, sender, recipients. In terms of performance, this is the most suitable option for obtaining primary information about messages. To extract complete message data, the [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-) method is provided.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tryToReadCorruptedContents | boolean | If the value of this parameter is true, the method will try to read the content even if the file is corrupted. This value can be used if the GetContents() method throws an exception about the file corruption. If the value of this parameter is false, the method works in the same way as GetContents() method without parameters. |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(MailQuery query) {#getContents-com.aspose.email.MailQuery-}
```
public final MessageInfoCollection getContents(MailQuery query)
```


Get collection of messages.
Method is used to display brief message information [MessageInfo](../../com.aspose.email/messageinfo) like subject, sender, recipients. In terms of performance, this is the most suitable option for obtaining primary information about messages. To extract complete message data, the [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-) method is provided.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents search query. |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(int kind) {#getContents-int-}
```
public final MessageInfoCollection getContents(int kind)
```


Get collection of messages.
Method is used to display brief message information [MessageInfo](../../com.aspose.email/messageinfo) like subject, sender, recipients. In terms of performance, this is the most suitable option for obtaining primary information about messages. To extract complete message data, the [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-) method is provided.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kind | int | The message kind. |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(int startIndex, int count) {#getContents-int-int-}
```
public final MessageInfoCollection getContents(int startIndex, int count)
```


Gets the collection of messages.
Method is used to display brief message information [MessageInfo](../../com.aspose.email/messageinfo) like subject, sender, recipients. In terms of performance, this is the most suitable option for obtaining primary information about messages. To extract complete message data, the [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-) method is provided.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | The start message index. |
| count | int | The number of messages that will be retrieved.

--------------------

If "count" param is less than 0 or more than remained message count then remained message count will be returned. |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the display name of folder.

Value: The display name.

**Returns:**
java.lang.String
### getEntryId() {#getEntryId--}
```
public final byte[] getEntryId()
```


Gets the entry ID.

Value: The entry id.

**Returns:**
byte[]
### getEntryIdString() {#getEntryIdString--}
```
public final String getEntryIdString()
```


Gets string representation of entry ID.

Value: The entry id string.

**Returns:**
java.lang.String
### getLastModificationTime() {#getLastModificationTime--}
```
public final Date getLastModificationTime()
```


Gets the last modification time.

Value: The last modification time. If the folder doesn't have PR\_LAST\_MODIFICATION\_TIME property, DateTime.MinValue is returned.

**Returns:**
java.util.Date
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


Gets the folder properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getSubFolder(String name) {#getSubFolder-java.lang.String-}
```
public final FolderInfo getSubFolder(String name)
```


Get subfolder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of subfolder. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getSubFolder(String name, boolean ignoreCase) {#getSubFolder-java.lang.String-boolean-}
```
public final FolderInfo getSubFolder(String name, boolean ignoreCase)
```


Gets the subfolder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of subfolder. |
| ignoreCase | boolean | Indicates that a search should ignore case sensitivity when matching the folder name. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getSubFolders() {#getSubFolders--}
```
public final FolderInfoCollection getSubFolders()
```


Gets collection of subfolders.

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The FolderInfo collection.
### getSubFolders(MailQuery query) {#getSubFolders-com.aspose.email.MailQuery-}
```
public final FolderInfoCollection getSubFolders(MailQuery query)
```


Gets collection of subfolders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents search query. |

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The FolderInfo collection.
### getSubFolders(int kind) {#getSubFolders-int-}
```
public final FolderInfoCollection getSubFolders(int kind)
```


Gets collection of subfolders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kind | int | The [FolderKind](../../com.aspose.email/folderkind) that represents kind of folder. |

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The FolderInfo collection.
### hasSubFolders() {#hasSubFolders--}
```
public final boolean hasSubFolders()
```


Gets a value indicating whether the Folder object has any subfolders.

Value: The has sub folders.

**Returns:**
boolean
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


Merges the folder with the folder from another pst.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | [FolderInfo](../../com.aspose.email/folderinfo) | The source folder. |

### mergeWith(FolderInfo sourceFolder, boolean recursiveHandler) {#mergeWith-com.aspose.email.FolderInfo-boolean-}
```
public final void mergeWith(FolderInfo sourceFolder, boolean recursiveHandler)
```


Merges the folder with the folder from another pst. OnItemMoved event is called on both messages and directories.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | [FolderInfo](../../com.aspose.email/folderinfo) | The source folder. |
| recursiveHandler | boolean | If true, OnItemMoved will be called on all messages, including messages in sub-directories, otherwise OnItemMoved will be called only for messages in the current directory. |

### moveContents(FolderInfo newFolder) {#moveContents-com.aspose.email.FolderInfo-}
```
public final void moveContents(FolderInfo newFolder)
```


Moves the contents to a new folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | The new folder. |

### moveSubfolders(FolderInfo newFolder) {#moveSubfolders-com.aspose.email.FolderInfo-}
```
public final void moveSubfolders(FolderInfo newFolder)
```


Moves the subfolders to a new parent folder.

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


Retrieves the full path of folder within the PST file.

**Returns:**
java.lang.String - The string that represents the full path.
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


Updates the message in folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The message entry identifier. |
| updatedMessage | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The updated message. |

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

