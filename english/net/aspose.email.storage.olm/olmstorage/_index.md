---
title: Class OlmStorage
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Olm.OlmStorage class. Represents an Outlook for Mac .OLM storage file and provides functionality to access and manipulate the data within the file such as emails contacts calendars tasks and notes
type: docs
weight: 20490
url: /net/aspose.email.storage.olm/olmstorage/
---
## OlmStorage class

Represents an Outlook for Mac (.OLM) storage file and provides functionality to access and manipulate the data within the file such as emails, contacts, calendars, tasks, and notes.

```csharp
public class OlmStorage : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [OlmStorage](olmstorage/#constructor_1)(Stream) | Initializes a new instance of the `OlmStorage` class. |
| [OlmStorage](olmstorage/#constructor_2)(string) | Initializes a new instance of the `OlmStorage` class. |
| [OlmStorage](olmstorage/#constructor)(TraversalExceptionsCallback) | Initializes a new instance of the `OlmStorage` class. Allows setting a callback method for handling exceptions that occur during OLM storage traversal. |

## Properties

| Name | Description |
| --- | --- |
| [FolderHierarchy](../../aspose.email.storage.olm/olmstorage/folderhierarchy/) { get; } | Gets the folder hierarchy. |

## Methods

| Name | Description |
| --- | --- |
| static [FromFile](../../aspose.email.storage.olm/olmstorage/fromfile/)(string) | Load OLM storage from file. |
| static [FromStream](../../aspose.email.storage.olm/olmstorage/fromstream/)(Stream) | Load OLM from stream. |
| [Dispose](../../aspose.email.storage.olm/olmstorage/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [EnumerateMessages](../../aspose.email.storage.olm/olmstorage/enumeratemessages/)(OlmFolder) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [ExtractMapiMessage](../../aspose.email.storage.olm/olmstorage/extractmapimessage/#extractmapimessage)(OlmMessageInfo) | Get the message from OLM storage. |
| [ExtractMapiMessage](../../aspose.email.storage.olm/olmstorage/extractmapimessage/#extractmapimessage_1)(string) | Get the message from OLM. |
| [GetCategories](../../aspose.email.storage.olm/olmstorage/getcategories/)() | Gets the supported item categories. |
| [GetFolder](../../aspose.email.storage.olm/olmstorage/getfolder/)(string, bool) | Gets the folder by name. |
| [GetFolders](../../aspose.email.storage.olm/olmstorage/getfolders/)() | Gets collection of folders. |
| [GetTotalItemsCount](../../aspose.email.storage.olm/olmstorage/gettotalitemscount/)() | Gets the total items count. Returns the total number of message items contained in the OLM. |
| [Load](../../aspose.email.storage.olm/olmstorage/load/#load)(Stream) | Load OLM storage from stream. This method is used when a OlmStorage object is created using constructor with the TraversalExceptionsCallback parameter. |
| [Load](../../aspose.email.storage.olm/olmstorage/load/#load_1)(string) | Load OLM storage from file. This method is used when a OlmStorage object is created using constructor with the TraversalExceptionsCallback parameter. |

## Remarks

The OlmStorage class allows users to read from and interact with the contents of .OLM files typically used by Microsoft Outlook for Mac. This class handles the various data types stored within an .OLM file by providing methods to enumerate and extract information.

## Examples

The following code shows how to access and retrieve information from an Outlook for Mac data file (.olm file).

[C#]

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

[Visual Basic]

```csharp
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

### See Also

* namespace [Aspose.Email.Storage.Olm](../../aspose.email.storage.olm/)
* assembly [Aspose.Email](../../)


