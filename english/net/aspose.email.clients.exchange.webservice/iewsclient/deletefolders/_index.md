---
title: IEWSClient.DeleteFolders
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Deletes the specified folders
type: docs
weight: 610
url: /net/aspose.email.clients.exchange.webservice/iewsclient/deletefolders/
---
## DeleteFolders(ExchangeFolderInfoCollection) {#deletefolders}

Deletes the specified folders

```csharp
public void DeleteFolders(ExchangeFolderInfoCollection folders)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folders | ExchangeFolderInfoCollection | A [`ExchangeFolderInfoCollection`](../../../aspose.email.clients.exchange/exchangefolderinfocollection/) containing information about folders to delete |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *folders* is `null` |

### See Also

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteFolders(StringCollection) {#deletefolders_2}

Deletes the specified folders

```csharp
public void DeleteFolders(StringCollection folderUris)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUris | StringCollection | The folder uris |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *folderUris* is `null` |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteFolders(ExchangeFolderInfoCollection, bool) {#deletefolders_1}

Deletes the specified folders

```csharp
public void DeleteFolders(ExchangeFolderInfoCollection folders, bool deletePermanently)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folders | ExchangeFolderInfoCollection | A [`ExchangeFolderInfoCollection`](../../../aspose.email.clients.exchange/exchangefolderinfocollection/) containing information about folders to delete |
| deletePermanently | Boolean | Indicates whether the folder should be deleted permanently or should be moved into DeletedItems folder |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *folders* is `null` |

### See Also

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteFolders(StringCollection, bool) {#deletefolders_3}

Deletes the folder

```csharp
public void DeleteFolders(StringCollection folderUris, bool deletePermanently)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUris | StringCollection | The folder Uri |
| deletePermanently | Boolean | Indicates whether the folder should be deleted permanently or should be moved into DeletedItems folder |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *folderUris* is `null` |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


