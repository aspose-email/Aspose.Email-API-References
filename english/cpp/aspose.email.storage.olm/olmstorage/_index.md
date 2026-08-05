---
title: "Aspose::Email::Storage::Olm::OlmStorage class"
linktitle: "OlmStorage"
articleTitle: "OlmStorage"
second_title: "Aspose.Email for C++"
description: "Represents an Outlook for Mac (.OLM) storage file and provides functionality to access and manipulate the data within the file such as emails, contacts, calenda"
type: docs
weight: 10
url: /cpp/aspose.email.storage.olm/olmstorage/
---

## OlmStorage class

Represents an Outlook for Mac (.OLM) storage file and provides functionality to access and manipulate the data within the file such as emails, contacts, calendars, tasks, and notes.

The OlmStorage class allows users to read from and interact with the contents of .OLM files typically used by Microsoft Outlook for Mac. This class handles the various data types stored within an .OLM file by providing methods to enumerate and extract information.

The following code shows how to access and retrieve information from an Outlook for Mac data file (.olm file).

```csharp
using (var olm = OlmStorage.FromFile("storage.olm"))
{
 // Retrieve the total number of items in the OLM storage.
    var totalItemsCount = olm.GetTotalItemsCount();
    Console.WriteLine($"Total items count: {totalItemsCount}");
 
 // Iterate through each folder in the OLM storage.
 foreach (var olmFolder in olm.GetFolders())
    {
 // Print the name of the currently iterated folder and the count of messages it contains.
        Console.WriteLine($"Folder: {olmFolder.Name}");
        Console.WriteLine($"Total items: {olmFolder.MessageCount}");
 
 // Iterate through each message in the current folder.
 foreach (var messageInfo in olmFolder.EnumerateMessages())
        {
 // Print the subject of the current message to the console.
            Console.WriteLine($"Subject: {messageInfo.Subject}");
 
 // Extract the full message object from the OLM storage.
            var msg = olm.ExtractMapiMessage(messageInfo);
 
 // Save the extracted message as a .msg file.
            msg.Save($"{msg.Subject}.msg");
        }
    }
}
```

```vb
Using olm As var = OlmStorage.FromFile("storage.olm")
 ' Retrieve the total number of items in the OLM storage and store the count in totalItemsCount.
    Dim totalItemsCount As Integer = olm.GetTotalItemsCount()
 
    ' Print the total number of items in the OLM storage to the console.
    Console.WriteLine($"Total items count: {totalItemsCount}")
 
 ' Iterate through each folder in the OLM storage.
    For Each olmFolder In olm.GetFolders()
        ' Print the name of the currently iterated folder and the count of messages it contains.
        Console.WriteLine($"Folder: {olmFolder.Name}")
        Console.WriteLine($"Total items: {olmFolder.MessageCount}")
 
 ' Iterate through each message in the current folder.
        For Each messageInfo In olmFolder.EnumerateMessages()
            ' Print the subject of the current message to the console.
            Console.WriteLine($"Subject: {messageInfo.Subject}")
 
 ' Extract the full message object from the OLM storage using the information from messageInfo.
            Dim msg As var = olm.ExtractMapiMessage(messageInfo)
 
            ' Save the extracted message as a .msg file on disk using its subject as the filename.
 ' Note: Message subject may need sanitization to be used as a valid filename.
            msg.Save($"{msg.Subject}.msg")
        Next
    Next
End Using
```

## Constructors

| Name | Description |
| --- | --- |
| [OlmStorage (3 overloads)](./olmstorage/) | Initializes a new instance of the OlmStorage class. Allows setting a callback method for handling exceptions that occur during OLM storage traversal. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose (2 overloads)](./dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [EnumerateMessages](./enumeratemessages/) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [ExtractMapiMessage (2 overloads)](./extractmapimessage/) | Get the message from OLM storage. |
| [FromFile](./fromfile/) | Load OLM storage from file. |
| [FromStream](./fromstream/) | Load OLM from stream. |
| [get_FolderHierarchy](./get_folderhierarchy/) | Gets the folder hierarchy. |
| [GetCategories](./getcategories/) | Gets the supported item categories. |
| [GetFolder](./getfolder/) | Gets the folder by name. |
| [GetFolders](./getfolders/) | Gets collection of folders. |
| [GetTotalItemsCount](./gettotalitemscount/) | Gets the total items count. Returns the total number of message items contained in the OLM. |
| [Load (2 overloads)](./load/) | Load OLM storage from stream. This method is used when a OlmStorage object is created using constructor with the TraversalExceptionsCallback parameter. |
| [SetVentureLicense](./setventurelicense/) |  |

