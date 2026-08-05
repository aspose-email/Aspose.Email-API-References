---
title: "Aspose::Email::Storage::Pst::PersonalStorage class"
linktitle: "PersonalStorage"
articleTitle: "PersonalStorage"
second_title: "Aspose.Email for C++"
description: "Provides functionality to access and manipulate the PST (Personal Storage Table) files used by Microsoft Outlook."
type: docs
weight: 10
url: /cpp/aspose.email.storage.pst/personalstorage/
---

## PersonalStorage class

Provides functionality to access and manipulate the PST (Personal Storage Table) files used by Microsoft Outlook.

The PersonalStorage class encapsulates methods for creating, opening, and working with the contents of PST files including emails, appointments, contacts, tasks, and other personal information.

This code serves as a way to browse and extract messages from a PST file, printing metadata about each folder and message, extract and saving the actual messages as .msg files.

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

```vb
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

## Constructors

| Name | Description |
| --- | --- |
| [PersonalStorage](./personalstorage/) | Initializes a new instance of the PersonalStorage class. Allows setting a callback method for handling exceptions that occur during PST traversal. |

## Methods

| Name | Description |
| --- | --- |
| [AddAttachmentToMessage (4 overloads)](./addattachmenttomessage/) | Adds an attachment to the specified message using the file located at the provided path. |
| [Cancel](./cancel/) | This method used to interrupt a split operation. |
| [ChangeMessage](./changemessage/) | Changes the message properties. |
| [CloneFolderStructure](./clonefolderstructure/) | Clones the folder structure. |
| [ConvertTo](./convertto/) | Converts the current object to the specified format. |
| [Create (3 overloads)](./create/) | Creates the PST in a stream. |
| [CreateFolderMapping](./createfoldermapping/) | Clones the folder structure. |
| [CreatePredefinedFolder (2 overloads)](./createpredefinedfolder/) | Creates the standard interpersonal message (IPM) folder. |
| [DeleteItem](./deleteitem/) | Deletes the item (folder or message) by it's entryId |
| [Dispose (2 overloads)](./dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [EnumerateMessages (2 overloads)](./enumeratemessages/) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [ExtractAttachments (2 overloads)](./extractattachments/) | Extracts the attachments. |
| [ExtractMessage (3 overloads)](./extractmessage/) | Get the message from PST. |
| [ExtractProperty](./extractproperty/) | Gets the specified property of item, without extract the item fully. |
| [ExtractRecipients (2 overloads)](./extractrecipients/) | Extracts the recipients. |
| [FindAndExtractSoftDeletedItems](./findandextractsoftdeleteditems/) | Finds and extracts soft-deleted messages from the PST. |
| [FindMessages](./findmessages/) | Finds the identifiers of messages for for the current folder. It might be useful in case of reading corrupted pst when the GetContents and EnumerateMessages methods could throw an exception. |
| [FindSubfolders](./findsubfolders/) | Finds the identifiers of subfolders for for the current folder. It might be useful in case of reading corrupted pst when the GetSubfolders and EnumerateFolders methods could throw an exception. |
| [FromFile (3 overloads)](./fromfile/) | Load PST from file. |
| [FromStream (3 overloads)](./fromstream/) | Load PST from stream. |
| [get_CanWrite](./get_canwrite/) | Gets a value indicating whether the current pst supports writing. |
| [get_Format](./get_format/) | Gets the file format. |
| [get_IsUnicode](./get_isunicode/) | Gets a value indicating whether the PST file format is Unicode. There are two versions of the PST file format: Unicode and ANSI. |
| [get_RootFolder](./get_rootfolder/) | Gets the root folder of PST. |
| [get_Store](./get_store/) | Gets the PST message store. |
| [GetCategories](./getcategories/) | Retrieves a list of PST item categories, each containing a name and associated color. |
| [GetFolderById (2 overloads)](./getfolderbyid/) | Gets the personal folder from PST. |
| [GetParentFolder (2 overloads)](./getparentfolder/) | Gets the parent folder of message. |
| [GetPredefinedFolder](./getpredefinedfolder/) | Gets the standard interpersonal message (IPM) folder from PST. Outlook can create a number of default folders, such as Outbox, Deleted Items, Sent Items etc. |
| [GetVentureLicenseState](./getventurelicensestate/) |  |
| [Load (2 overloads)](./load/) | Load PST from stream. This method is used when a PersonalStorage object is created using the constructor. |
| [MergeWith (2 overloads)](./mergewith/) | Merges the pst storage with one or more other pst streams. Thus, the combined stream are sources. |
| [MoveItem (2 overloads)](./moveitem/) | Moves a specified folder to a new parent folder within the current pst. |
| [OnStorageProcessed](./onstorageprocessed/) | Raises the E:ChunkCreated event. |
| [SaveAs (2 overloads)](./saveas/) | Saves the current object to a specified file format in a stream. |
| [SaveMessageToStream](./savemessagetostream/) | Saves the message, with specified entryID, to a stream. |
| [SplitInto (4 overloads)](./splitinto/) | Splits the pst storage into less sized parts. |
| [TryToGetFolderById](./trytogetfolderbyid/) | Gets the folder associated with the specified entry ID. |
| [TryToSaveMessage](./trytosavemessage/) | Saves the message, with specified entryID, to a stream. |
| [ItemMoved](./itemmoved/) | Occurs when an item is moved to the another folder. |
| [pstDoer](./pstdoer/) | The pst reader. |
| [StorageProcessed](./storageprocessed/) | Occurs in splitting and merging operations when a new chunk of pst is created or the next file is processed and is to be merged. |
| [StorageProcessing](./storageprocessing/) | Occurs before the srorage is processed. The event is raised before processing the next storage in merging or splitting operations. |

