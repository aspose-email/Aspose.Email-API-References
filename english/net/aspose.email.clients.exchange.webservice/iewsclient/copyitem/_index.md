---
title: IEWSClient.CopyItem
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Copies the item to specified folder
type: docs
weight: 450
url: /net/aspose.email.clients.exchange.webservice/iewsclient/copyitem/
---
## IEWSClient.CopyItem method

Copies the item to specified folder

```csharp
public string CopyItem(string itemUri, string destinationFolderUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| itemUri | String | The item URI |
| destinationFolderUri | String | The destination folder URI |

### Return Value

An uri of the copied message

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *itemUri* is `null` or `empty` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *destinationFolderUri* is `null` or `empty` |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


