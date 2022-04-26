---
title: PersonalStorage
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 18420
url: /net/aspose.email.storage.pst/personalstorage/
---
## PersonalStorage class

Represents Personal Storage Table (.pst) file.

```csharp
public class PersonalStorage : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [PersonalStorage](personalstorage)(TraversalExceptionsCallback) | Initializes a new instance of the [`PersonalStorage`](../personalstorage) class. Allows setting a callback method for handling exceptions that occur during PST traversal. |

## Properties

| Name | Description |
| --- | --- |
| [CanWrite](canwrite) { get; } | Gets a value indicating whether the current pst supports writing. |
| [Format](format) { get; } | Gets the file format. |
| [IsUnicode](isunicode) { get; } | Gets a value indicating whether the PST file format is Unicode. There are two versions of the PST file format: Unicode and ANSI. |
| [RootFolder](rootfolder) { get; } | Gets the root folder of PST. |
| [Store](store) { get; } | Gets the PST message store. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](create)(Stream, FileFormatVersion) | Creates the PST in a stream. |
| static [Create](create)(string, FileFormatVersion) | Creates the new PST file with the specified file name. |
| static [Create](create)(Stream, FileFormatVersion, bool) | Creates the PST in a stream. |
| static [Create](create)(Stream, FileFormatVersion, CancellationToken) | Creates the PST in a stream. |
| static [Create](create)(string, FileFormatVersion, CancellationToken) | Creates the new PST file with the specified file name. |
| static [Create](create)(Stream, FileFormatVersion, bool, CancellationToken) | Creates the PST in a stream. |
| static [FromFile](fromfile)(string) | Load PST from file. |
| static [FromFile](fromfile)(string, bool) | Load PST from file. |
| static [FromFile](fromfile)(string, CancellationToken) | Load PST from file. |
| static [FromFile](fromfile)(string, PersonalStorageLoadOptions) | Load PST from file. |
| static [FromFile](fromfile)(string, bool, CancellationToken) |  |
| static [FromFile](fromfile)(string, PersonalStorageLoadOptions, CancellationToken) | Load PST from file. |
| static [FromStream](fromstream)(Stream) | Load PST from stream. |
| static [FromStream](fromstream)(Stream, bool) | Load PST from stream. |
| static [FromStream](fromstream)(Stream, CancellationToken) | Load PST from file. |
| static [FromStream](fromstream)(Stream, PersonalStorageLoadOptions) | Load PST from stream. |
| static [FromStream](fromstream)(Stream, bool, CancellationToken) |  |
| static [FromStream](fromstream)(Stream, PersonalStorageLoadOptions, CancellationToken) | Load PST from file. |
| [ChangeMessage](changemessage)(string, MapiPropertyCollection) | Changes the message properties. |
| [ConvertTo](convertto)(FileFormat) | Converts the current object to the specified format. |
| [CreatePredefinedFolder](createpredefinedfolder)(string, StandardIpmFolder) | Creates the standard interpersonal message (IPM) folder. |
| [CreatePredefinedFolder](createpredefinedfolder)(string, StandardIpmFolder, bool) | Creates the standard interpersonal message (IPM) folder. |
| [Dispose](dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [EnumerateMessages](enumeratemessages)(string) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [EnumerateMessages](enumeratemessages)(string, int, int) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [ExtractAttachments](extractattachments)(MessageInfo) | Extracts the attachments. |
| [ExtractAttachments](extractattachments)(string) | Extracts the attachments. |
| [ExtractMessage](extractmessage)(byte[]) | Get the message from PST. |
| [ExtractMessage](extractmessage)(MessageInfo) | Get the message from PST. |
| [ExtractMessage](extractmessage)(string) | Get the message from PST. |
| [ExtractProperty](extractproperty)(byte[], long) | Gets the specified property of item, without extract the item fully. |
| [FindMessages](findmessages)(string) | Finds the identifiers of messages for for the current folder. It might be useful in case of reading corrupted pst when the GetContents and EnumerateMessages methods could throw an exception. |
| [FindSubfolders](findsubfolders)(string) | Finds the identifiers of subfolders for for the current folder. It might be useful in case of reading corrupted pst when the GetSubfolders and EnumerateFolders methods could throw an exception. |
| [GetFolderById](getfolderbyid)(byte[]) | Gets the personal folder from PST. |
| [GetFolderById](getfolderbyid)(string) | Gets the personal folder from PST. |
| [GetParentFolder](getparentfolder)(byte[]) | Gets the parent folder of message. |
| [GetParentFolder](getparentfolder)(string) | Gets the parent folder of message. |
| [GetPredefinedFolder](getpredefinedfolder)(StandardIpmFolder) | Gets the standard interpersonal message (IPM) folder from PST. Outlook can create a number of default folders, such as Outbox, Deleted Items, Sent Items etc. |
| [Load](load)(Stream) | Load PST from stream. This method is used when a PersonalStorage object is created using the constructor. |
| [Load](load)(string) | Load PST from file. This method is used when a PersonalStorage object is created using the constructor. |
| [MergeWith](mergewith)(Stream[]) | Merges the pst storage with one or more other pst streams. Thus, the combined stream are sources. |
| [MergeWith](mergewith)(string[]) | Merges the pst storage with one or more other pst files. Thus, the combined files are sources. |
| [MoveItem](moveitem)(FolderInfo, FolderInfo) | Moves a specified folder to a new parent folder within the current pst. |
| [MoveItem](moveitem)(MessageInfo, FolderInfo) | Moves a specified message to a new folder within the current pst. |
| [SaveAs](saveas)(Stream, FileFormat) | Saves the current object to a specified file format in a stream. |
| [SaveAs](saveas)(string, FileFormat) | Saves the current object to a specified file format in a different file. |
| [SaveMessageToStream](savemessagetostream)(string, Stream) | Saves the message, with specified entryID, to a stream. |
| [SplitInto](splitinto)(IList&lt;MailQuery&gt;, string) | Splits the pst storage based on criteria. |
| [SplitInto](splitinto)(long, string) | Splits the pst storage into less sized parts. |
| [TryToGetFolderById](trytogetfolderbyid)(string, out FolderInfo) | Gets the folder associated with the specified entry ID. |
| [TryToSaveMessage](trytosavemessage)(string, Stream) | Saves the message, with specified entryID, to a stream. |

## Other Members

| Name | Description |
| --- | --- |
| event [ItemMoved](itemmoved) | Occurs when an item is moved to the another folder. |
| event [StorageProcessed](storageprocessed) | Occurs in splitting and merging operations when a new chunk of pst is created or the next file is processed and is to be merged. |

### See Also

* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
