---
title: IEWSClient.ListSubFoldersByPage
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Searches the specified folder in the given parent folder with paging Method supports paging
type: docs
weight: 1190
url: /net/aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage/
---
## ListSubFoldersByPage(string, PageInfo) {#listsubfoldersbypage}

Searches the specified folder in the given parent folder with paging Method supports paging.

```csharp
public ExchangeFolderPageInfo ListSubFoldersByPage(string parentFolderUri, PageInfo page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | String | A parent folder URI |
| page | PageInfo | A page info |

### Return Value

A [`ExchangeFolderPageInfo`](../../../aspose.email.clients.exchange/exchangefolderpageinfo/) containing the found folder if folder name is specified; otherwise, returns all subfolders

### See Also

* class [ExchangeFolderPageInfo](../../../aspose.email.clients.exchange/exchangefolderpageinfo/)
* class [PageInfo](../../../aspose.email.clients/pageinfo/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListSubFoldersByPage(string, int) {#listsubfoldersbypage_1}

Searches the specified folder in the given parent folder with paging Method supports paging. Invokes for the first time in paging cycle.

```csharp
public ExchangeFolderPageInfo ListSubFoldersByPage(string parentFolderUri, int itemsPerPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | String | A parent folder URI |
| itemsPerPage | Int32 | A number of folders in page |

### Return Value

A [`ExchangeFolderPageInfo`](../../../aspose.email.clients.exchange/exchangefolderpageinfo/) containing the found folder if folder name is specified; otherwise, returns all subfolders

### See Also

* class [ExchangeFolderPageInfo](../../../aspose.email.clients.exchange/exchangefolderpageinfo/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListSubFoldersByPage(string, int, int) {#listsubfoldersbypage_2}

Searches the specified folder in the given parent folder with paging Method supports paging.

```csharp
public ExchangeFolderPageInfo ListSubFoldersByPage(string parentFolderUri, int itemsPerPage, 
    int pageOffset)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | String | A parent folder URI |
| itemsPerPage | Int32 | A number of folders in page |
| pageOffset | Int32 | An offset of next item in view |

### Return Value

A [`ExchangeFolderPageInfo`](../../../aspose.email.clients.exchange/exchangefolderpageinfo/) containing the found folder if folder name is specified; otherwise, returns all subfolders

### See Also

* class [ExchangeFolderPageInfo](../../../aspose.email.clients.exchange/exchangefolderpageinfo/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


