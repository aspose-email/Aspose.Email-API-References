---
title: IEWSClient.CreateItems
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Creates the specified items in the speciifed folder
type: docs
weight: 530
url: /net/aspose.email.clients.exchange.webservice/iewsclient/createitems/
---
## IEWSClient.CreateItems method

Creates the specified items in the speciifed folder

```csharp
public ExchangeUploadItemResult[] CreateItems(ExchangeStreamedItem[] items, string parentFolderUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| items | ExchangeStreamedItem[] | An items to be uploaded |
| parentFolderUri | String | Specifies the folder in which to place the items |

### Return Value

An array of [`ExchangeUploadItemResult`](../../exchangeuploaditemresult/)

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *items* is `null` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *items* is `empty` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *parentFolderUri* is `null` or `empty` |

### See Also

* class [ExchangeUploadItemResult](../../exchangeuploaditemresult/)
* class [ExchangeStreamedItem](../../exchangestreameditem/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


