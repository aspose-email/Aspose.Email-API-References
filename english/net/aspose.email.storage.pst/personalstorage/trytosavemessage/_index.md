---
title: PersonalStorage.TryToSaveMessage
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Saves a message to a stream in Outlook MSG format keeping as much of a damaged message as can be read instead of failing
type: docs
weight: 410
url: /net/aspose.email.storage.pst/personalstorage/trytosavemessage/
---
## PersonalStorage.TryToSaveMessage method

Saves a message to a stream in Outlook MSG format, keeping as much of a damaged message as can be read instead of failing.

```csharp
public SaveResult TryToSaveMessage(string entryId, Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the message. |
| stream | Stream | The stream to write to. |

### Return Value

A [`SaveResult`](../../saveresult/) that tells whether the message was saved completely or partially, and which properties could not be read.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *entryId* is `null` or empty. |
| ArgumentNullException | *stream* is `null`. |

## Examples

This example salvages the messages of a damaged Inbox and reports the ones that were saved only in part.

[C#]

```csharp
using (var pst = PersonalStorage.FromFile("damaged.pst", false))
{
    var inbox = pst.GetPredefinedFolder(StandardIpmFolder.Inbox);
    int count = 0;

    // FindMessages works even when the message list of the folder is damaged
    foreach (string entryId in pst.FindMessages(inbox.EntryIdString))
    {
        using (var stream = File.Create($"message_{++count}.msg"))
        {
            SaveResult result = pst.TryToSaveMessage(entryId, stream);
            if (result.Status != SaveStatus.Success)
            {
                Console.WriteLine($"message_{count}.msg: {result.Status}, " +
                                  $"{result.MissedProperties.Count} properties lost");
            }
        }
    }
}
```

[Visual Basic]

```csharp
Using pst As PersonalStorage = PersonalStorage.FromFile("damaged.pst", False)
    Dim inbox As FolderInfo = pst.GetPredefinedFolder(StandardIpmFolder.Inbox)
    Dim count As Integer = 0

    ' FindMessages works even when the message list of the folder is damaged
    For Each entryId As String In pst.FindMessages(inbox.EntryIdString)
        count += 1
        Using stream As FileStream = File.Create($"message_{count}.msg")
            Dim result As SaveResult = pst.TryToSaveMessage(entryId, stream)
            If result.Status <> SaveStatus.Success Then
                Console.WriteLine($"message_{count}.msg: {result.Status}, " &
                                  $"{result.MissedProperties.Count} properties lost")
            End If
        End Using
    Next
End Using
```

### See Also

* class [SaveResult](../../saveresult/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


