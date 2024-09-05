---
title: Class PersonalStorage
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Pst.PersonalStorage class. Provides functionality to access and manipulate the PST Personal Storage Table files used by Microsoft Outlook
type: docs
weight: 20580
url: /net/aspose.email.storage.pst/personalstorage/
---
## PersonalStorage class

Provides functionality to access and manipulate the PST (Personal Storage Table) files used by Microsoft Outlook.

```csharp
public class PersonalStorage : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [PersonalStorage](personalstorage/)(TraversalExceptionsCallback) | Initializes a new instance of the `PersonalStorage` class. Allows setting a callback method for handling exceptions that occur during PST traversal. |

## Properties

| Name | Description |
| --- | --- |
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite/) { get; } | Gets a value indicating whether the current pst supports writing. |
| [Format](../../aspose.email.storage.pst/personalstorage/format/) { get; } | Gets the file format. |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode/) { get; } | Gets a value indicating whether the PST file format is Unicode. There are two versions of the PST file format: Unicode and ANSI. |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder/) { get; } | Gets the root folder of PST. |
| [Store](../../aspose.email.storage.pst/personalstorage/store/) { get; } | Gets the PST message store. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create/#create)(Stream, FileFormatVersion) | Creates the PST in a stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create/#create_4)(string, FileFormatVersion) | Creates the new PST file with the specified file name. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create/#create_1)(Stream, FileFormatVersion, bool) | Creates the PST in a stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create/#create_3)(Stream, FileFormatVersion, CancellationToken) | Creates the PST in a stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create/#create_5)(string, FileFormatVersion, CancellationToken) | Creates the new PST file with the specified file name. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create/#create_2)(Stream, FileFormatVersion, bool, CancellationToken) | Creates the PST in a stream. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile/#fromfile)(string) | Load PST from file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile/#fromfile_3)(string, bool) | Load PST from file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile/#fromfile_5)(string, CancellationToken) | Load PST from file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile/#fromfile_1)(string, PersonalStorageLoadOptions) | Load PST from file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile/#fromfile_4)(string, bool, CancellationToken) |  |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile/#fromfile_2)(string, PersonalStorageLoadOptions, CancellationToken) | Load PST from file. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream/#fromstream)(Stream) | Load PST from stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream/#fromstream_3)(Stream, bool) | Load PST from stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream/#fromstream_5)(Stream, CancellationToken) | Load PST from file. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream/#fromstream_1)(Stream, PersonalStorageLoadOptions) | Load PST from stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream/#fromstream_4)(Stream, bool, CancellationToken) |  |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream/#fromstream_2)(Stream, PersonalStorageLoadOptions, CancellationToken) | Load PST from file. |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage/)(string, MapiPropertyCollection) | Changes the message properties. |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto/)(FileFormat) | Converts the current object to the specified format. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder/#createpredefinedfolder)(string, StandardIpmFolder) | Creates the standard interpersonal message (IPM) folder. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder/#createpredefinedfolder_1)(string, StandardIpmFolder, bool) | Creates the standard interpersonal message (IPM) folder. |
| [DeleteItem](../../aspose.email.storage.pst/personalstorage/deleteitem/)(string) | Deletes the item (folder or message) by it's entryId |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages/#enumeratemessages)(string) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages/#enumeratemessages_1)(string, int, int) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments/#extractattachments)(MessageInfo) | Extracts the attachments. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments/#extractattachments_1)(string) | Extracts the attachments. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage/#extractmessage_1)(byte[]) | Get the message from PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage/#extractmessage)(MessageInfo) | Get the message from PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage/#extractmessage_2)(string) | Get the message from PST. |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty/)(byte[], long) | Gets the specified property of item, without extract the item fully. |
| [ExtractRecipients](../../aspose.email.storage.pst/personalstorage/extractrecipients/#extractrecipients)(MessageInfo) | Extracts the recipients. |
| [ExtractRecipients](../../aspose.email.storage.pst/personalstorage/extractrecipients/#extractrecipients_1)(string) | Extracts the recipients. |
| [FindAndExtractSoftDeletedItems](../../aspose.email.storage.pst/personalstorage/findandextractsoftdeleteditems/)() | Finds and extracts soft-deleted messages from the PST. |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages/)(string) | Finds the identifiers of messages for for the current folder. It might be useful in case of reading corrupted pst when the GetContents and EnumerateMessages methods could throw an exception. |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders/)(string) | Finds the identifiers of subfolders for for the current folder. It might be useful in case of reading corrupted pst when the GetSubfolders and EnumerateFolders methods could throw an exception. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid/#getfolderbyid)(byte[]) | Gets the personal folder from PST. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid/#getfolderbyid_1)(string) | Gets the personal folder from PST. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder/#getparentfolder)(byte[]) | Gets the parent folder of message. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder/#getparentfolder_1)(string) | Gets the parent folder of message. |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder/)(StandardIpmFolder) | Gets the standard interpersonal message (IPM) folder from PST. Outlook can create a number of default folders, such as Outbox, Deleted Items, Sent Items etc. |
| [Load](../../aspose.email.storage.pst/personalstorage/load/#load)(Stream) | Load PST from stream. This method is used when a PersonalStorage object is created using the constructor. |
| [Load](../../aspose.email.storage.pst/personalstorage/load/#load_1)(string) | Load PST from file. This method is used when a PersonalStorage object is created using the constructor. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith/#mergewith)(Stream[]) | Merges the pst storage with one or more other pst streams. Thus, the combined stream are sources. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith/#mergewith_1)(string[]) | Merges the pst storage with one or more other pst files. Thus, the combined files are sources. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem/#moveitem)(FolderInfo, FolderInfo) | Moves a specified folder to a new parent folder within the current pst. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem/#moveitem_1)(MessageInfo, FolderInfo) | Moves a specified message to a new folder within the current pst. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas/#saveas)(Stream, FileFormat) | Saves the current object to a specified file format in a stream. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas/#saveas_1)(string, FileFormat) | Saves the current object to a specified file format in a different file. |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream/)(string, Stream) | Saves the message, with specified entryID, to a stream. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto/#splitinto_2)(IList&lt;MailQuery&gt;, string) | Splits the pst storage based on criteria. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto/#splitinto)(long, string) | Splits the pst storage into less sized parts. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto/#splitinto_3)(IList&lt;MailQuery&gt;, string, string) | Splits the pst storage based on criteria. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto/#splitinto_1)(long, string, string) | Splits the pst storage into less sized parts. |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid/)(string, out FolderInfo) | Gets the folder associated with the specified entry ID. |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage/)(string, Stream) | Saves the message, with specified entryID, to a stream. |

## Events

| Name | Description |
| --- | --- |
| event [ItemMoved](../../aspose.email.storage.pst/personalstorage/itemmoved/) | Occurs when an item is moved to the another folder. |
| event [StorageProcessed](../../aspose.email.storage.pst/personalstorage/storageprocessed/) | Occurs in splitting and merging operations when a new chunk of pst is created or the next file is processed and is to be merged. |
| event [StorageProcessing](../../aspose.email.storage.pst/personalstorage/storageprocessing/) | Occurs before the srorage is processed. The event is raised before processing the next storage in merging or splitting operations. |

## Remarks

The PersonalStorage class encapsulates methods for creating, opening, and working with the contents of PST files including emails, appointments, contacts, tasks, and other personal information.

## Examples

This code serves as a way to browse and extract messages from a PST file, printing metadata about each folder and message, extract and saving the actual messages as .msg files.

[C#]

```csharp
// Open the PST file by creating an instance of PersonalStorage
using (var pst = PersonalStorage.FromFile("storage.pst"))
{
    // Retrieve the total number of items in the PST file
    var totalItemsCount = pst.Store.GetTotalItemsCount();
    
    // Write the total items count to the console
    Console.WriteLine($"Total items count: {totalItemsCount}");

    // Iterate through each subfolder within the root folder of the PST
    foreach (var folderInfo in pst.RootFolder.GetSubFolders())
    {
        // Write the display name of the folder to the console
        Console.WriteLine($"Folder: {folderInfo.DisplayName}");
        // Write the total number of items in the folder to the console
        Console.WriteLine($"Total items: {folderInfo.ContentCount}");
        // Write the count of unread items in the folder to the console
        Console.WriteLine($"Total unread items: {folderInfo.ContentUnreadCount}");

        // Enumerate through each message in the current folder
        foreach (var messageInfo in folderInfo.EnumerateMessages())
        {
            // Write the subject of the message to the console
            Console.WriteLine($"Subject: {messageInfo.Subject}");
            
            // Extract the full message object from the messageInfo
            var msg = pst.ExtractMessage(messageInfo);
            
            // Save the message as a .msg file, using its subject as the filename
            msg.Save($"{msg.Subject}.msg");
        }
    }
}
```

[Visual Basic]

```csharp
' Open the PST file by creating an instance of PersonalStorage
Using pst As PersonalStorage = PersonalStorage.FromFile("storage.pst")
    ' Retrieve the total number of items in the PST file
    Dim totalItemsCount As Integer = pst.Store.GetTotalItemsCount()
    
    ' Write the total items count to the console
    Console.WriteLine($"Total items count: {totalItemsCount}")

    ' Iterate through each subfolder within the root folder of the PST
    For Each folderInfo In pst.RootFolder.GetSubFolders()
        ' Write the display name of the folder to the console
        Console.WriteLine($"Folder: {folderInfo.DisplayName}")
        ' Write the total number of items in the folder to the console
        Console.WriteLine($"Total items: {folderInfo.ContentCount}")
        ' Write the count of unread items in the folder to the console
        Console.WriteLine($"Total unread items: {folderInfo.ContentUnreadCount}")

        ' Enumerate through each message in the current folder
        For Each messageInfo In folderInfo.EnumerateMessages()
            ' Write the subject of the message to the console
            Console.WriteLine($"Subject: {messageInfo.Subject}")
            
            ' Extract the full message object from the messageInfo
            Dim msg As MailItem = pst.ExtractMessage(messageInfo)
            
            ' Save the message as a .msg file, using its subject as the filename
            msg.Save($"{msg.Subject}.msg")
        Next
    Next
End Using
```

### See Also

* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst/)
* assembly [Aspose.Email](../../)


