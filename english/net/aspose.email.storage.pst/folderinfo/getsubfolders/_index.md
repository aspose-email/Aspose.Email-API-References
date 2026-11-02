---
title: FolderInfo.GetSubFolders
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Gets the subfolders of the folder
type: docs
weight: 310
url: /net/aspose.email.storage.pst/folderinfo/getsubfolders/
---
## GetSubFolders() {#getsubfolders}

Gets the subfolders of the folder.

```csharp
public FolderInfoCollection GetSubFolders()
```

### Return Value

The subfolders.

## Remarks

For a folder with many subfolders, `EnumerateFolders` reads them one at a time.

### See Also

* class [FolderInfoCollection](../../folderinfocollection/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## GetSubFolders(FolderKind) {#getsubfolders_1}

Gets the subfolders of the specified kind.

```csharp
public FolderInfoCollection GetSubFolders(FolderKind kind)
```

| Parameter | Type | Description |
| --- | --- | --- |
| kind | FolderKind | Which kinds of folders to return: normal folders, search folders or both. |

### Return Value

The subfolders.

### See Also

* class [FolderInfoCollection](../../folderinfocollection/)
* enum [FolderKind](../../folderkind/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## GetSubFolders(MailQuery) {#getsubfolders_2}

Gets the subfolders that match a query.

```csharp
public FolderInfoCollection GetSubFolders(MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | The search query, built with [`PersonalStorageQueryBuilder`](../../personalstoragequerybuilder/), for example with its `FolderName` or `ContentsCount` field. |

### Return Value

The matching subfolders.

### See Also

* class [FolderInfoCollection](../../folderinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


