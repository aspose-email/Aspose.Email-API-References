---
title: FolderInfo.AddMessages
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Adds messages to the folder in bulk which is faster than adding them one by one
type: docs
weight: 160
url: /net/aspose.email.storage.pst/folderinfo/addmessages/
---
## FolderInfo.AddMessages method

Adds messages to the folder in bulk, which is faster than adding them one by one.

```csharp
public void AddMessages(IEnumerable<MapiMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | IEnumerable`1 | The messages to add. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |

## Remarks

The `MessageAdded` event is raised for each added message and gives its entry ID.

## Examples

This example adds all .msg files of a directory to the Inbox and prints the entry ID of each added message.

[C#]

```csharp
using (var pst = PersonalStorage.FromFile("archive.pst"))
{
    var inbox = pst.GetPredefinedFolder(StandardIpmFolder.Inbox);

    // Called once for every message added in bulk
    inbox.MessageAdded += (sender, e) => Console.WriteLine($"Added {e.EntryId}");

    // Messages are loaded one at a time while the folder consumes them
    var messages = Directory.EnumerateFiles(@"C:\Messages", "*.msg")
        .Select(path => MapiMessage.Load(path));

    inbox.AddMessages(messages);
}
```

[Visual Basic]

```csharp
Using pst As PersonalStorage = PersonalStorage.FromFile("archive.pst")
    Dim inbox As FolderInfo = pst.GetPredefinedFolder(StandardIpmFolder.Inbox)

    ' Called once for every message added in bulk
    AddHandler inbox.MessageAdded, Sub(sender, e) Console.WriteLine($"Added {e.EntryId}")

    ' Messages are loaded one at a time while the folder consumes them
    Dim messages = Directory.EnumerateFiles("C:\Messages", "*.msg") _
        .Select(Function(path) MapiMessage.Load(path))

    inbox.AddMessages(messages)
End Using
```

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


