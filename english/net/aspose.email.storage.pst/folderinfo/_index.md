---
title: Class FolderInfo
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Pst.FolderInfo class. Represents a folder of a PST or OST file and gives access to its messages and subfolders
type: docs
weight: 19120
url: /net/aspose.email.storage.pst/folderinfo/
---
## FolderInfo class

Represents a folder of a PST or OST file and gives access to its messages and subfolders.

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
| [ContainerClass](../../aspose.email.storage.pst/folderinfo/containerclass/) { get; } | Gets the container class of the folder, which defines the kind of items it holds, for example `IPF.Note` for mail. |
| [ContentCount](../../aspose.email.storage.pst/folderinfo/contentcount/) { get; } | Gets the total number of items in the folder. |
| [ContentUnreadCount](../../aspose.email.storage.pst/folderinfo/contentunreadcount/) { get; } | Gets the number of unread items in the folder. |
| [DisplayName](../../aspose.email.storage.pst/folderinfo/displayname/) { get; } | Gets the display name of folder. |
| [EntryId](../../aspose.email.storage.pst/folderinfo/entryid/) { get; } | Gets the entry ID of the folder, which identifies it in the PST. |
| [EntryIdString](../../aspose.email.storage.pst/folderinfo/entryidstring/) { get; } | Gets the entry ID of the folder as a string. |
| [HasSubFolders](../../aspose.email.storage.pst/folderinfo/hassubfolders/) { get; } | Gets a value indicating whether the Folder object has any subfolders. |
| [LastModificationTime](../../aspose.email.storage.pst/folderinfo/lastmodificationtime/) { get; } | Gets the last modification time. |
| [Properties](../../aspose.email.storage.pst/folderinfo/properties/) { get; } | Gets the MAPI properties of the folder. |

## Methods

| Name | Description |
| --- | --- |
| [AddFile](../../aspose.email.storage.pst/folderinfo/addfile/)(string, string) | Adds a file to the folder as a new item with the specified message class. |
| [AddMapiMessageItem](../../aspose.email.storage.pst/folderinfo/addmapimessageitem/)(IMapiMessageItem) | Adds a message, contact, appointment, meeting, task, note or journal item to the folder. |
| [AddMessage](../../aspose.email.storage.pst/folderinfo/addmessage/)(MapiMessage) | Adds a message to the folder. |
| [AddMessages](../../aspose.email.storage.pst/folderinfo/addmessages/)(IEnumerable&lt;MapiMessage&gt;) | Adds messages to the folder in bulk, which is faster than adding them one by one. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder/#addsubfolder)(string) | Adds a subfolder with the specified name. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder/#addsubfolder_2)(string, bool) | Adds a subfolder. With *createHierarchy*, the name can be a path, and the missing folders are created. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder/#addsubfolder_1)(string, FolderCreationOptions) | Adds a subfolder with the specified name to the current folder using the provided creation options. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder/#addsubfolder_3)(string, string) | Adds a subfolder with the specified name and container class. |
| [ChangeContainerClass](../../aspose.email.storage.pst/folderinfo/changecontainerclass/)(string) | Changes the container class of the folder. |
| [ChangeDisplayName](../../aspose.email.storage.pst/folderinfo/changedisplayname/)(string) | Renames the folder. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages/#changemessages)(MapiPropertyCollection) | Sets the specified properties on all messages of the folder. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages/#changemessages_1)(IEnumerable&lt;string&gt;, MapiPropertyCollection) | Sets the specified properties on the given messages of the folder. |
| [DeleteChildItem](../../aspose.email.storage.pst/folderinfo/deletechilditem/)(byte[]) | Deletes a message or subfolder of this folder by its entry ID. |
| [DeleteChildItems](../../aspose.email.storage.pst/folderinfo/deletechilditems/)(IEnumerable&lt;string&gt;) | Deletes the specified messages of the folder. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders/#enumeratefolders)() | Enumerates the subfolders of the folder. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders/#enumeratefolders_1)(FolderKind) | Enumerates the subfolders of the specified kind. |
| [EnumerateMapiMessages](../../aspose.email.storage.pst/folderinfo/enumeratemapimessages/)() | Enumerates the messages of the folder as fully loaded [`MapiMessage`](../../aspose.email.mapi/mapimessage/) objects. |
| [EnumerateMessageObjects](../../aspose.email.storage.pst/folderinfo/enumeratemessageobjects/)() | Enumerates the messages of the folder as [`MessageObject`](../../aspose.email.mapi.msg/messageobject/) objects. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages/#enumeratemessages)() | Retrieves [`MessageInfo`](../messageinfo/) objects from the folder. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages/#enumeratemessages_2)(MailQuery) | Retrieves a collection of [`MessageInfo`](../messageinfo/) objects that match the specified query. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages/#enumeratemessages_1)(MessageKind) | Retrieves a collection of [`MessageInfo`](../messageinfo/) objects of the specified kind. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages/#enumeratemessages_3)(int, int) | Retrieves a collection of [`MessageInfo`](../messageinfo/) objects starting from a specific index and limited to a specified count. |
| [EnumerateMessagesEntryId](../../aspose.email.storage.pst/folderinfo/enumeratemessagesentryid/)() | Enumerates the entry IDs of the messages in the folder. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents/#getcontents)() | Gets information about all messages in the folder. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents/#getcontents_4)(bool) | Gets information about the messages in the folder, optionally reading a damaged message list. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents/#getcontents_2)(MailQuery) | Gets information about the messages that match a query. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents/#getcontents_1)(MessageKind) | Gets information about the messages of the specified kind. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents/#getcontents_5)(int, int) | Gets information about a range of the messages in the folder. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents/#getcontents_3)(MailQuery, int, int) | Gets information about a range of the messages that match a query. |
| [GetPredefinedType](../../aspose.email.storage.pst/folderinfo/getpredefinedtype/)(bool) | Gets which standard Outlook folder, such as Inbox or Sent Items, this folder is. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder/#getsubfolder)(string) | Gets the subfolder with the specified name. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder/#getsubfolder_1)(string, bool) | Gets the subfolder with the specified name, optionally ignoring case. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder/#getsubfolder_2)(string, bool, bool) | Retrieves a subfolder with the specified name from the current folder. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders/#getsubfolders)() | Gets the subfolders of the folder. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders/#getsubfolders_1)(FolderKind) | Gets the subfolders of the specified kind. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders/#getsubfolders_2)(MailQuery) | Gets the subfolders that match a query. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith/#mergewith)(FolderInfo) | Merges a folder from another PST into this folder. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith/#mergewith_1)(FolderInfo, bool) | Merges a folder from another PST into this folder and raises `ItemMoved` for the merged messages and folders. |
| [MergeWithAsync](../../aspose.email.storage.pst/folderinfo/mergewithasync/#mergewithasync_1)(FolderInfo, CancellationToken) | Asynchronously merges a folder from another PST into this folder. |
| [MergeWithAsync](../../aspose.email.storage.pst/folderinfo/mergewithasync/#mergewithasync)(FolderInfo, bool, CancellationToken) | Asynchronously merges a folder from another PST into this folder and raises `ItemMoved` for the merged messages and folders. |
| [MoveContents](../../aspose.email.storage.pst/folderinfo/movecontents/)(FolderInfo) | Moves all messages of this folder to another folder. |
| [MoveSubfolders](../../aspose.email.storage.pst/folderinfo/movesubfolders/)(FolderInfo) | Moves all subfolders of this folder to another parent folder. |
| [RetrieveFullPath](../../aspose.email.storage.pst/folderinfo/retrievefullpath/)() | Gets the path of the folder from the root of the PST. |
| [SetReadStatus](../../aspose.email.storage.pst/folderinfo/setreadstatus/)(IList&lt;string&gt;, bool) | Sets or clears the `Read` status for the specified messages in a PST file. |
| [UpdateMessage](../../aspose.email.storage.pst/folderinfo/updatemessage/)(string, MapiMessageItemBase) | Updates the message with the specified entry ID. |

## Events

| Name | Description |
| --- | --- |
| event [ItemMoved](../../aspose.email.storage.pst/folderinfo/itemmoved/) | Occurs when an item is moved to another folder. |
| event [MessageAdded](../../aspose.email.storage.pst/folderinfo/messageadded/) | Occurs when a message is added to the folder. |

## Remarks

Get folders from a [`PersonalStorage`](../personalstorage/): `RootFolder`, `GetPredefinedFolder`, `GetFolderById`, or the `GetSubFolder` and `GetSubFolders` methods of another folder. Methods that change a folder throw `NotImplementedException` for an ANSI PST and `InvalidOperationException` when the PST is open for reading only.

### See Also

* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst/)
* assembly [Aspose.Email](../../)


