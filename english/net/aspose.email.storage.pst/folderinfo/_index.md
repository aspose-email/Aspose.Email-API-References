---
title: Class FolderInfo
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Pst.FolderInfo class. Represents information about personal folder in PST
type: docs
weight: 20210
url: /net/aspose.email.storage.pst/folderinfo/
---
## FolderInfo class

Represents information about personal folder in PST.

```csharp
public sealed class FolderInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [FolderInfo](folderinfo/)() | Initializes a new instance of the `FolderInfo` class. |

## Properties

| Name | Description |
| --- | --- |
| [ContainerClass](../../aspose.email.storage.pst/folderinfo/containerclass/) { get; } | Gets container class of the folder object. |
| [ContentCount](../../aspose.email.storage.pst/folderinfo/contentcount/) { get; } | Gets the total number of items in the folder. |
| [ContentUnreadCount](../../aspose.email.storage.pst/folderinfo/contentunreadcount/) { get; } | Gets the number of unread items in the folder. |
| [DisplayName](../../aspose.email.storage.pst/folderinfo/displayname/) { get; } | Gets the display name of folder. |
| [EntryId](../../aspose.email.storage.pst/folderinfo/entryid/) { get; } | Gets the entry ID. |
| [EntryIdString](../../aspose.email.storage.pst/folderinfo/entryidstring/) { get; } | Gets string representation of entry ID. |
| [HasSubFolders](../../aspose.email.storage.pst/folderinfo/hassubfolders/) { get; } | Gets a value indicating whether the Folder object has any subfolders. |
| [LastModificationTime](../../aspose.email.storage.pst/folderinfo/lastmodificationtime/) { get; } | Gets the last modification time. |
| [Properties](../../aspose.email.storage.pst/folderinfo/properties/) { get; } | Gets the folder properties. |

## Methods

| Name | Description |
| --- | --- |
| [AddFile](../../aspose.email.storage.pst/folderinfo/addfile/)(string, string) | Adds a file into pst folder. |
| [AddMapiMessageItem](../../aspose.email.storage.pst/folderinfo/addmapimessageitem/)(IMapiMessageItem) | Adds the IMapiMessageItem object into folder. |
| [AddMessage](../../aspose.email.storage.pst/folderinfo/addmessage/)(MapiMessage) | Adds a new message into folder. |
| [AddMessages](../../aspose.email.storage.pst/folderinfo/addmessages/)(IEnumerable&lt;MapiMessage&gt;) | Provides message adding in a bulk mode. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder/#addsubfolder)(string) | Adds the new sub-folder. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder/#addsubfolder_1)(string, bool) | Adds the new sub-folder. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder/#addsubfolder_2)(string, string) | Adds the new subfolder. |
| [ChangeContainerClass](../../aspose.email.storage.pst/folderinfo/changecontainerclass/)(string) | Changes the container class. |
| [ChangeDisplayName](../../aspose.email.storage.pst/folderinfo/changedisplayname/)(string) | Changes the display name. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages/#changemessages)(MapiPropertyCollection) | Changes all messages in folder. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages/#changemessages_1)(IEnumerable&lt;string&gt;, MapiPropertyCollection) | Changes the messages in folder. |
| [DeleteChildItem](../../aspose.email.storage.pst/folderinfo/deletechilditem/)(byte[]) | Deletes the item (folder or message) by it's entryId. |
| [DeleteChildItems](../../aspose.email.storage.pst/folderinfo/deletechilditems/)(IEnumerable&lt;string&gt;) | Deletes the child messages. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders/#enumeratefolders)() | Exposes the enumerator, which supports an iteration of subfolders in folder. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders/#enumeratefolders_1)(FolderKind) | Exposes the enumerator, which supports an iteration of subfolders in folder. |
| [EnumerateMapiMessages](../../aspose.email.storage.pst/folderinfo/enumeratemapimessages/)() | Exposes the enumerator, which supports an iteration of messages in folder. |
| [EnumerateMessageObjects](../../aspose.email.storage.pst/folderinfo/enumeratemessageobjects/)() | Exposes the enumerator, which supports an iteration of messages in folder. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages/)() | Exposes the enumerator, which supports an iteration of messages in folder. |
| [EnumerateMessagesEntryId](../../aspose.email.storage.pst/folderinfo/enumeratemessagesentryid/)() | Enumerates the entryID of messages. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents/#getcontents)() | Get collection of messages. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents/#getcontents_3)(bool) | Get collection of messages. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents/#getcontents_2)(MailQuery) | Get collection of messages. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents/#getcontents_1)(MessageKind) | Get collection of messages. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents/#getcontents_4)(int, int) | Gets the collection of messages. |
| [GetPredefinedType](../../aspose.email.storage.pst/folderinfo/getpredefinedtype/)(bool) | Gets the type of predefined folder. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder/#getsubfolder)(string) | Get subfolder. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder/#getsubfolder_1)(string, bool) | Gets the subfolder. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders/#getsubfolders)() | Gets collection of subfolders. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders/#getsubfolders_1)(FolderKind) | Gets collection of subfolders. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders/#getsubfolders_2)(MailQuery) | Gets collection of subfolders. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith/#mergewith)(FolderInfo) | Merges the folder with the folder from another pst. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith/#mergewith_1)(FolderInfo, bool) | Merges the folder with the folder from another pst. OnItemMoved event is called on both messages and directories. |
| [MoveContents](../../aspose.email.storage.pst/folderinfo/movecontents/)(FolderInfo) | Moves the contents to a new folder. |
| [MoveSubfolders](../../aspose.email.storage.pst/folderinfo/movesubfolders/)(FolderInfo) | Moves the subfolders to a new parent folder. |
| [RetrieveFullPath](../../aspose.email.storage.pst/folderinfo/retrievefullpath/)() | Retrieves the full path of folder within the PST file. |
| [UpdateMessage](../../aspose.email.storage.pst/folderinfo/updatemessage/)(string, MapiMessageItemBase) | Updates the message in folder. |

## Events

| Name | Description |
| --- | --- |
| event [ItemMoved](../../aspose.email.storage.pst/folderinfo/itemmoved/) | Occurs when an item is moved to the another folder. |
| event [MessageAdded](../../aspose.email.storage.pst/folderinfo/messageadded/) | Occurs when a message is added to the current folder. |

### See Also

* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst/)
* assembly [Aspose.Email](../../)


