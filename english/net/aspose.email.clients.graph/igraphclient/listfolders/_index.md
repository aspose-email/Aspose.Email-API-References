---
title: IGraphClient.ListFolders
second_title: Aspose.Email for .NET API Reference
description: IGraphClient method. List folders from the parent folder for folders that are displayed in normal mail clients such as the inbox
type: docs
weight: 450
url: /net/aspose.email.clients.graph/igraphclient/listfolders/
---
## ListFolders(ODataQueryBuilder) {#listfolders}

List folders from the parent folder for folders that are displayed in normal mail clients, such as the inbox.

```csharp
public FolderInfoCollection ListFolders(ODataQueryBuilder queryBuilder = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering folders. |

### Return Value

Returns list of subfolders of the root folder

### See Also

* class [FolderInfoCollection](../../folderinfocollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)

---

## ListFolders(string, ODataQueryBuilder) {#listfolders_1}

List folders from the parent folder for folders that are displayed in normal mail clients, such as the inbox.

```csharp
public FolderInfoCollection ListFolders(string id, ODataQueryBuilder queryBuilder = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Parent folder id |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering folders. |

### Return Value

Returns list of subfolders of the root folder

### See Also

* class [FolderInfoCollection](../../folderinfocollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)


