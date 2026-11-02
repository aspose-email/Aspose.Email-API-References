---
title: Class PersonalStorage
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Pst.PersonalStorage class. Provides functionality to access and manipulate the PST Personal Storage Table files used by Microsoft Outlook
type: docs
weight: 19260
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
| [PersonalStorage](personalstorage/)(TraversalExceptionsCallback) | Initializes a new instance of the `PersonalStorage` class that reports problems found while reading a damaged PST to a callback instead of throwing. Call `Load` to open the file. |

## Properties

| Name | Description |
| --- | --- |
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite/) { get; } | Gets a value indicating whether the PST is open for writing. |
| [Format](../../aspose.email.storage.pst/personalstorage/format/) { get; } | Gets the file format. |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode/) { get; } | Gets a value indicating whether the PST is in the Unicode format. Only Unicode PST files can be edited; the older ANSI format is read-only. |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder/) { get; } | Gets the root folder of the PST, which contains all other folders. |
| [Store](../../aspose.email.storage.pst/personalstorage/store/) { get; } | Gets the PST message store. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create/#create)(Stream, FileFormatVersion) | Creates a new PST in a stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create/#create_2)(string, FileFormatVersion) | Creates a new PST file. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create/#create_1)(Stream, FileFormatVersion, bool) | Creates a new PST in a stream. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile/#fromfile)(string) | Opens a PST or OST file for reading and writing. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile/#fromfile_2)(string, bool) | Opens a PST or OST file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile/#fromfile_1)(string, PersonalStorageLoadOptions) | Opens a PST or OST file with the specified options. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream/#fromstream)(Stream) | Opens a PST or OST from a stream for reading and writing. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream/#fromstream_2)(Stream, bool) | Opens a PST or OST from a stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream/#fromstream_1)(Stream, PersonalStorageLoadOptions) | Opens a PST or OST from a stream with the specified options. |
| [AddAttachmentToMessage](../../aspose.email.storage.pst/personalstorage/addattachmenttomessage/#addattachmenttomessage)(MessageInfo, string) | Adds an attachment to the specified message using the file located at the provided path. |
| [AddAttachmentToMessage](../../aspose.email.storage.pst/personalstorage/addattachmenttomessage/#addattachmenttomessage_2)(string, string) | Adds an attachment to the message identified by the specified entry ID using the file located at the provided path. |
| [AddAttachmentToMessage](../../aspose.email.storage.pst/personalstorage/addattachmenttomessage/#addattachmenttomessage_1)(MessageInfo, string, Stream) | Adds an attachment to the specified message using the provided stream as attachment content. |
| [AddAttachmentToMessage](../../aspose.email.storage.pst/personalstorage/addattachmenttomessage/#addattachmenttomessage_3)(string, string, Stream) | Adds an attachment to the message identified by the specified entry ID using the provided stream. |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage/)(string, MapiPropertyCollection) | Changes properties of a message. |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto/)(FileFormat) | Converts the open file to the specified format. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder/#createpredefinedfolder)(string, StandardIpmFolder) | Creates a standard Outlook folder, such as Inbox or Calendar, with the specified name. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder/#createpredefinedfolder_1)(string, StandardIpmFolder, bool) | Creates a standard Outlook folder, such as Inbox or Calendar, with the specified name. |
| [DeleteItem](../../aspose.email.storage.pst/personalstorage/deleteitem/)(string) | Deletes a message or folder by its entry ID. |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose/)() | Closes the PST and releases the resources it uses. The underlying stream is closed too, unless the storage was opened or created with the option to leave it open. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages/#enumeratemessages)(string) | Enumerates the messages of the folder with the specified entry ID. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages/#enumeratemessages_1)(string, int, int) | Enumerates a range of the messages of the folder with the specified entry ID. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments/#extractattachments)(MessageInfo) | Reads the attachments of a message without loading the whole message. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments/#extractattachments_1)(string) | Reads the attachments of a message without loading the whole message. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage/#extractmessage_1)(byte[]) | Loads the full message with the specified entry ID. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage/#extractmessage)(MessageInfo) | Loads the full message that a [`MessageInfo`](../messageinfo/) describes. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage/#extractmessage_2)(string) | Loads the full message with the specified entry ID. |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty/)(byte[], long) | Reads one property of an item without loading the whole item. |
| [ExtractRecipients](../../aspose.email.storage.pst/personalstorage/extractrecipients/#extractrecipients)(MessageInfo) | Reads the recipients of a message without loading the whole message. |
| [ExtractRecipients](../../aspose.email.storage.pst/personalstorage/extractrecipients/#extractrecipients_1)(string) | Reads the recipients of a message without loading the whole message. |
| [FindAndEnumerateSoftDeletedItems](../../aspose.email.storage.pst/personalstorage/findandenumeratesoftdeleteditems/)() | Finds soft-deleted messages and returns them one at a time. |
| [FindAndExtractSoftDeletedItems](../../aspose.email.storage.pst/personalstorage/findandextractsoftdeleteditems/)() | Finds and extracts all soft-deleted messages of the PST. |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages/)(string) | Finds the entry IDs of the messages of a folder. Use it to read a damaged PST when `FolderInfo.GetContents` and `FolderInfo.EnumerateMessages` throw. |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders/)(string) | Finds the entry IDs of the subfolders of a folder. Use it to read a damaged PST when `FolderInfo.GetSubFolders` and `FolderInfo.EnumerateFolders` throw. |
| [GetCategories](../../aspose.email.storage.pst/personalstorage/getcategories/)() | Gets the categories used in the PST, each with its name and color. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid/#getfolderbyid)(byte[]) | Gets the folder with the specified entry ID. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid/#getfolderbyid_1)(string) | Gets the folder with the specified entry ID. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder/#getparentfolder)(byte[]) | Gets the folder that contains a message or folder. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder/#getparentfolder_1)(string) | Gets the folder that contains a message or folder. |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder/)(StandardIpmFolder) | Gets a standard Outlook folder of the PST, such as Inbox, Sent Items or Deleted Items. |
| [Load](../../aspose.email.storage.pst/personalstorage/load/#load)(Stream) | Opens a PST from a stream for reading, for a storage created with the constructor that takes a `TraversalExceptionsCallback`. |
| [Load](../../aspose.email.storage.pst/personalstorage/load/#load_1)(string) | Opens a PST file for reading, for a storage created with the constructor that takes a `TraversalExceptionsCallback`. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith/#mergewith)(Stream[]) | Merges one or more other PST streams into this PST. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith/#mergewith_1)(string[]) | Merges one or more other PST files into this PST. |
| [MergeWithAsync](../../aspose.email.storage.pst/personalstorage/mergewithasync/#mergewithasync)(Stream[], CancellationToken) | Asynchronously merges one or more other PST streams into this PST. |
| [MergeWithAsync](../../aspose.email.storage.pst/personalstorage/mergewithasync/#mergewithasync_1)(string[], CancellationToken) | Asynchronously merges one or more other PST files into this PST. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem/#moveitem)(FolderInfo, FolderInfo) | Moves a folder to another parent folder of the same PST. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem/#moveitem_1)(MessageInfo, FolderInfo) | Moves a message to another folder of the same PST. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas/#saveas)(Stream, FileFormat) | Saves the storage to a stream in the specified format. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas/#saveas_1)(string, FileFormat) | Saves the storage to another file in the specified format. |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream/)(string, Stream) | Saves a message to a stream in Outlook MSG format, without loading it into a `MapiMessage`. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto/#splitinto_2)(IList&lt;MailQuery&gt;, string) | Splits the PST into several files by search criteria. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto/#splitinto)(long, string) | Splits the PST into files of about the specified size. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto/#splitinto_3)(IList&lt;MailQuery&gt;, string, string) | Splits the PST into several files by search criteria, named with a prefix. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto/#splitinto_1)(long, string, string) | Splits the PST into files of about the specified size, named with a prefix. |
| [SplitIntoAsync](../../aspose.email.storage.pst/personalstorage/splitintoasync/#splitintoasync_3)(IList&lt;MailQuery&gt;, string, CancellationToken) | Asynchronously splits the PST into several files by search criteria. |
| [SplitIntoAsync](../../aspose.email.storage.pst/personalstorage/splitintoasync/#splitintoasync_1)(long, string, CancellationToken) | Asynchronously splits the PST into files of about the specified size. |
| [SplitIntoAsync](../../aspose.email.storage.pst/personalstorage/splitintoasync/#splitintoasync_2)(IList&lt;MailQuery&gt;, string, string, CancellationToken) | Asynchronously splits the PST into several files by search criteria, named with a prefix. |
| [SplitIntoAsync](../../aspose.email.storage.pst/personalstorage/splitintoasync/#splitintoasync)(long, string, string, CancellationToken) | Asynchronously splits the PST into files of about the specified size, named with a prefix. |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid/)(string, out FolderInfo) | Tries to get the folder with the specified entry ID. |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage/)(string, Stream) | Saves a message to a stream in Outlook MSG format, keeping as much of a damaged message as can be read instead of failing. |
| static [CreateAsync](../../aspose.email.storage.pst/personalstorage/createasync/#createasync_1)(Stream, FileFormatVersion, CancellationToken) | Asynchronously creates a new PST in a stream. |
| static [CreateAsync](../../aspose.email.storage.pst/personalstorage/createasync/#createasync_2)(string, FileFormatVersion, CancellationToken) | Asynchronously creates a new PST file. |
| static [CreateAsync](../../aspose.email.storage.pst/personalstorage/createasync/#createasync)(Stream, FileFormatVersion, bool, CancellationToken) | Asynchronously creates a new PST in a stream. |
| static [FromFileAsync](../../aspose.email.storage.pst/personalstorage/fromfileasync/#fromfileasync_2)(string, CancellationToken) | Asynchronously opens a PST or OST file for reading and writing. |
| static [FromFileAsync](../../aspose.email.storage.pst/personalstorage/fromfileasync/#fromfileasync_1)(string, bool, CancellationToken) | Asynchronously opens a PST or OST file. |
| static [FromFileAsync](../../aspose.email.storage.pst/personalstorage/fromfileasync/#fromfileasync)(string, PersonalStorageLoadOptions, CancellationToken) | Asynchronously opens a PST or OST file with the specified options. |
| static [FromStreamAsync](../../aspose.email.storage.pst/personalstorage/fromstreamasync/#fromstreamasync_2)(Stream, CancellationToken) | Asynchronously opens a PST or OST from a stream for reading and writing. |
| static [FromStreamAsync](../../aspose.email.storage.pst/personalstorage/fromstreamasync/#fromstreamasync_1)(Stream, bool, CancellationToken) | Asynchronously opens a PST or OST from a stream. |
| static [FromStreamAsync](../../aspose.email.storage.pst/personalstorage/fromstreamasync/#fromstreamasync)(Stream, PersonalStorageLoadOptions, CancellationToken) | Asynchronously opens a PST or OST from a stream with the specified options. |

## Events

| Name | Description |
| --- | --- |
| event [ItemMoved](../../aspose.email.storage.pst/personalstorage/itemmoved/) | Occurs when an item is moved to another folder. |
| event [StorageProcessed](../../aspose.email.storage.pst/personalstorage/storageprocessed/) | Occurs while splitting, after a new PST file has been created, and while merging, after the next source has been processed. |
| event [StorageProcessing](../../aspose.email.storage.pst/personalstorage/storageprocessing/) | Occurs before the next PST file is processed while merging or splitting. |

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


