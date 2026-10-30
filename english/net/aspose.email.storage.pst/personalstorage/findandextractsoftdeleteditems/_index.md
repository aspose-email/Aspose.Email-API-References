---
title: PersonalStorage.FindAndExtractSoftDeletedItems
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Finds and extracts all softdeleted messages of the PST
type: docs
weight: 250
url: /net/aspose.email.storage.pst/personalstorage/findandextractsoftdeleteditems/
---
## PersonalStorage.FindAndExtractSoftDeletedItems method

Finds and extracts all soft-deleted messages of the PST.

```csharp
public IList<RestoredItemEntry> FindAndExtractSoftDeletedItems()
```

### Return Value

The soft-deleted messages, each with the entry ID of the folder it was in.

## Remarks

Soft-deleted messages are messages that have been deleted but whose data is still present in the PST. For a large PST, `FindAndEnumerateSoftDeletedItems` reads them one at a time.

## Examples

This example recovers soft-deleted messages and saves them as .msg files.

[C#]

```csharp
using (var pst = PersonalStorage.FromFile("archive.pst"))
{
    int count = 0;
    foreach (var entry in pst.FindAndExtractSoftDeletedItems())
    {
        // The folder the message was deleted from, if it still exists
        string folderName = pst.TryToGetFolderById(entry.FolderId, out FolderInfo folder)
            ? folder.DisplayName
            : "(unknown folder)";

        Console.WriteLine($"{entry.Item.Subject} from {folderName}");
        entry.Item.Save($"recovered_{++count}.msg");
    }
}
```

[Visual Basic]

```csharp
Using pst As PersonalStorage = PersonalStorage.FromFile("archive.pst")
    Dim count As Integer = 0
    For Each entry As RestoredItemEntry In pst.FindAndExtractSoftDeletedItems()
        ' The folder the message was deleted from, if it still exists
        Dim folder As FolderInfo = Nothing
        Dim folderName As String = If(pst.TryToGetFolderById(entry.FolderId, folder),
            folder.DisplayName, "(unknown folder)")

        Console.WriteLine($"{entry.Item.Subject} from {folderName}")
        count += 1
        entry.Item.Save($"recovered_{count}.msg")
    Next
End Using
```

### See Also

* class [RestoredItemEntry](../../restoreditementry/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


