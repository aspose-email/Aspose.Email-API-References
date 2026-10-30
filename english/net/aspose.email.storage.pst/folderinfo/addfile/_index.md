---
title: FolderInfo.AddFile
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Adds a file to the folder as a new item with the specified message class
type: docs
weight: 130
url: /net/aspose.email.storage.pst/folderinfo/addfile/
---
## FolderInfo.AddFile method

Adds a file to the folder as a new item with the specified message class.

```csharp
public string AddFile(string fileName, string messageClass)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file to add. |
| messageClass | String | The message class of the new item. |

### Return Value

The entry ID of the new item.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| ArgumentNullException | *fileName* is `null` or empty. |
| InvalidOperationException | The PST is open for reading only. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


