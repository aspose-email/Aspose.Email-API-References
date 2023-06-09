---
title: IEWSClient.CreateFolder
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Creates the new folder with the specified name in the specified parent folder
type: docs
weight: 500
url: /net/aspose.email.clients.exchange.webservice/iewsclient/createfolder/
---
## CreateFolder(string, string) {#createfolder_2}

Creates the new folder with the specified name in the specified parent folder.

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | String | An uri of parent folder. |
| name | String | A name of folder to be created. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *parentFolderUri* or *name* is `null` or `empty`. |

### See Also

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection) {#createfolder_3}

Creates the new folder

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | String | The URI of parent folder |
| name | String | The name of new folder |
| permissions | ExchangeFolderPermissionCollection | A permission on new folder |

### Return Value

Returns folder information

### See Also

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo/)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection, string) {#createfolder_4}

Creates the new folder

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions, string folderClass)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | String | The URI of parent folder |
| name | String | The name of new folder |
| permissions | ExchangeFolderPermissionCollection | A permission on new folder |
| folderClass | String | The class of new folder |

### Return Value

Returns folder information

### See Also

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo/)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## CreateFolder(string, ExchangeFolderType) {#createfolder_1}

Creates new folder in the root folder.

```csharp
public ExchangeFolderInfo CreateFolder(string name, ExchangeFolderType folderType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of new folder |
| folderType | ExchangeFolderType | Type of folder |

### Return Value

Returns folder information

### See Also

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo/)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderType) {#createfolder_5}

Creates the new folder

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderType folderType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | String | The URI of parent folder |
| name | String | The name of new folder |
| folderType | ExchangeFolderType | Type of folder |

### Return Value

Returns folder information

### See Also

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo/)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## CreateFolder(string) {#createfolder}

Creates new folder in the root folder.

```csharp
public ExchangeFolderInfo CreateFolder(string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of new folder |

### Return Value

Returns folder information

### See Also

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


