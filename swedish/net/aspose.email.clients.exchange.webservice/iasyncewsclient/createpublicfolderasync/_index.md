---
title: CreatePublicFolderAsync
second_title: Aspose.Email för .NET API-referens
description: Skapar den angivna offentliga mappen i den offentliga rotmappen
type: docs
weight: 130
url: /sv/net/aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync/
---
## CreatePublicFolderAsync(string, ExchangeFolderPermissionCollection, ExchangeFolderType, string, CancellationToken) {#createpublicfolderasync}

Skapar den angivna offentliga mappen i den offentliga rotmappen

```csharp
public Task<ExchangeFolderInfo> CreatePublicFolderAsync(string name, 
    ExchangeFolderPermissionCollection permissions, ExchangeFolderType folderType, 
    string parentFolderUri = null, CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | Ett namn på den nya mappen |
| permissions | ExchangeFolderPermissionCollection | En behörighet för ny mapp |
| folderType | ExchangeFolderType | Typ av mapp |
| parentFolderUri | String | URI:n för den överordnade mappen |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Returnerar mappinformation

### Se även

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* hopsättning [Aspose.Email](../../../)

---

## CreatePublicFolderAsync(string, ExchangeFolderPermissionCollection, string, CancellationToken) {#createpublicfolderasync_1}

Skapar den angivna offentliga mappen i den offentliga rotmappen

```csharp
public Task<ExchangeFolderInfo> CreatePublicFolderAsync(string name, 
    ExchangeFolderPermissionCollection permissions, string parentFolderUri = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | Ett namn på den nya mappen |
| permissions | ExchangeFolderPermissionCollection | En behörighet för ny mapp |
| parentFolderUri | String | URI:n för den överordnade mappen |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Returnerar mappinformation

### Se även

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->