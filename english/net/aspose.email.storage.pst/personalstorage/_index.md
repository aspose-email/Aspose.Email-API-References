---
title: PersonalStorage
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 20070
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
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite) { get; } | Gets a value indicating whether the current pst supports writing. |
| [Format](../../aspose.email.storage.pst/personalstorage/format) { get; } | Gets the file format. |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode) { get; } | Gets a value indicating whether the PST file format is Unicode. There are two versions of the PST file format: Unicode and ANSI. |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder) { get; } | Gets the root folder of PST. |
| [Store](../../aspose.email.storage.pst/personalstorage/store) { get; } | Gets the PST message store. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create)(Stream, FileFormatVersion) | Creates the PST in a stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create)(string, FileFormatVersion) | Creates the new PST file with the specified file name. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create)(Stream, FileFormatVersion, bool) | Creates the PST in a stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create)(Stream, FileFormatVersion, CancellationToken) | Creates the PST in a stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create)(string, FileFormatVersion, CancellationToken) | Creates the new PST file with the specified file name. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create)(Stream, FileFormatVersion, bool, CancellationToken) | Creates the PST in a stream. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile)(string) | Load PST from file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile)(string, bool) | Load PST from file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile)(string, CancellationToken) | Load PST from file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile)(string, PersonalStorageLoadOptions) | Load PST from file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile)(string, bool, CancellationToken) |  |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile)(string, PersonalStorageLoadOptions, CancellationToken) | Load PST from file. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream)(Stream) | Load PST from stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream)(Stream, bool) | Load PST from stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream)(Stream, CancellationToken) | Load PST from file. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream)(Stream, PersonalStorageLoadOptions) | Load PST from stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream)(Stream, bool, CancellationToken) |  |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream)(Stream, PersonalStorageLoadOptions, CancellationToken) | Load PST from file. |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage)(string, MapiPropertyCollection) | Changes the message properties. |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto)(FileFormat) | Converts the current object to the specified format. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder)(string, StandardIpmFolder) | Creates the standard interpersonal message (IPM) folder. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder)(string, StandardIpmFolder, bool) | Creates the standard interpersonal message (IPM) folder. |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages)(string) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages)(string, int, int) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments)(MessageInfo) | Extracts the attachments. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments)(string) | Extracts the attachments. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage)(byte[]) | Get the message from PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage)(MessageInfo) | Get the message from PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage)(string) | Get the message from PST. |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty)(byte[], long) | Gets the specified property of item, without extract the item fully. |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages)(string) | Finds the identifiers of messages for for the current folder. It might be useful in case of reading corrupted pst when the GetContents and EnumerateMessages methods could throw an exception. |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders)(string) | Finds the identifiers of subfolders for for the current folder. It might be useful in case of reading corrupted pst when the GetSubfolders and EnumerateFolders methods could throw an exception. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid)(byte[]) | Gets the personal folder from PST. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid)(string) | Gets the personal folder from PST. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder)(byte[]) | Gets the parent folder of message. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder)(string) | Gets the parent folder of message. |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder)(StandardIpmFolder) | Gets the standard interpersonal message (IPM) folder from PST. Outlook can create a number of default folders, such as Outbox, Deleted Items, Sent Items etc. |
| [Load](../../aspose.email.storage.pst/personalstorage/load)(Stream) | Load PST from stream. This method is used when a PersonalStorage object is created using the constructor. |
| [Load](../../aspose.email.storage.pst/personalstorage/load)(string) | Load PST from file. This method is used when a PersonalStorage object is created using the constructor. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith)(Stream[]) | Merges the pst storage with one or more other pst streams. Thus, the combined stream are sources. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith)(string[]) | Merges the pst storage with one or more other pst files. Thus, the combined files are sources. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem)(FolderInfo, FolderInfo) | Moves a specified folder to a new parent folder within the current pst. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem)(MessageInfo, FolderInfo) | Moves a specified message to a new folder within the current pst. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas)(Stream, FileFormat) | Saves the current object to a specified file format in a stream. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas)(string, FileFormat) | Saves the current object to a specified file format in a different file. |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream)(string, Stream) | Saves the message, with specified entryID, to a stream. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto)(IList&lt;MailQuery&gt;, string) | Splits the pst storage based on criteria. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto)(long, string) | Splits the pst storage into less sized parts. |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid)(string, out FolderInfo) | Gets the folder associated with the specified entry ID. |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage)(string, Stream) | Saves the message, with specified entryID, to a stream. |

## Other Members

| Name | Description |
| --- | --- |
| event [ItemMoved](itemmoved) | Occurs when an item is moved to the another folder. |
| event [StorageProcessed](storageprocessed) | Occurs in splitting and merging operations when a new chunk of pst is created or the next file is processed and is to be merged. |

### See Also

* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
