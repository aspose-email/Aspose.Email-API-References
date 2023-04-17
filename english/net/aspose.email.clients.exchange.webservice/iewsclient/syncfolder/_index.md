---
title: IEWSClient.SyncFolder
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Retrieves changes of the items and subfolders in a specified folder
type: docs
weight: 1430
url: /net/aspose.email.clients.exchange.webservice/iewsclient/syncfolder/
---
## SyncFolder(string) {#syncfolder_1}

Retrieves changes of the items and subfolders in a specified folder.

```csharp
public SyncFolderResult SyncFolder(string folderUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | String | The folder uri |

### Return Value

Returns result of SyncFolder operation.

### See Also

* class [SyncFolderResult](../../syncfolderresult/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## SyncFolder(string, SyncFolderType) {#syncfolder_2}

Retrieves changes of the items and subfolders in a specified folder.

```csharp
public SyncFolderResult SyncFolder(string folderUri, SyncFolderType syncType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | String | The folder uri |
| syncType | SyncFolderType | Folder synchronization type |

### Return Value

Returns result of SyncFolder operation.

### See Also

* class [SyncFolderResult](../../syncfolderresult/)
* enum [SyncFolderType](../../syncfoldertype/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## SyncFolder(SyncState) {#syncfolder}

Retrieves changes of the items in a specified folder.

```csharp
public SyncFolderResult SyncFolder(SyncState syncState)
```

| Parameter | Type | Description |
| --- | --- | --- |
| syncState | SyncState | The synchronization state. |

### Return Value

Returns result of SyncFolder operation.

### See Also

* class [SyncFolderResult](../../syncfolderresult/)
* class [SyncState](../../syncstate/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## SyncFolder(string, string) {#syncfolder_3}

Retrieves changes of the items in a specified folder.

```csharp
public SyncFolderResult SyncFolder(string folderUri, string syncState)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | String | The folder uri |
| syncState | String | The optional synchronization state. Must be null for first synchronization. |

### Return Value

Returns result of SyncFolder operation.

### See Also

* class [SyncFolderResult](../../syncfolderresult/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## SyncFolder(string, string, IEnumerable&lt;string&gt;) {#syncfolder_4}

Retrieves changes of the items in a specified folder.

```csharp
public SyncFolderResult SyncFolder(string folderUri, string syncState, 
    IEnumerable<string> ignoreList)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | String | The folder uri |
| syncState | String | The optional synchronization state. Must be null for first synchronization. |
| ignoreList | IEnumerable`1 | The optional list of item uris that should be ignored. |

### Return Value

Returns result of SyncFolder operation.

### See Also

* class [SyncFolderResult](../../syncfolderresult/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


