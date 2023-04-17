---
title: IAsyncEwsClient.FetchAttachmentAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Fetches the attachment
type: docs
weight: 230
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchattachmentasync/
---
## IAsyncEwsClient.FetchAttachmentAsync method

Fetches the attachment

```csharp
public Task<Attachment> FetchAttachmentAsync(string attachmentUri, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| attachmentUri | String | The attachment uri. (Attachment uri can be retrieved using ListMessages(folder, ExchangeListMessagesOptions.FetchAttachmentInformation) method) |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

[`Attachment`](../../../aspose.email/attachment/) that represents fetched attachment

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *attachmentUri* is null or empty |

### See Also

* class [Attachment](../../../aspose.email/attachment/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


