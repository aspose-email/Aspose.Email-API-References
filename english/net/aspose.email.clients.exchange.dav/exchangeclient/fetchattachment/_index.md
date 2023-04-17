---
title: ExchangeClient.FetchAttachment
second_title: Aspose.Email for .NET API Reference
description: ExchangeClient method. Fetches the attachment
type: docs
weight: 160
url: /net/aspose.email.clients.exchange.dav/exchangeclient/fetchattachment/
---
## ExchangeClient.FetchAttachment method

Fetches the attachment

```csharp
public Attachment FetchAttachment(string attachmentUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| attachmentUri | String | The attachment uri. (Attachment uri can be retrieved using ListMessages(folder, ExchangeListMessagesOptions.FetchAttachmentInformation) method) |

### Return Value

[`Attachment`](../../../aspose.email/attachment/) that represents fetched attachment

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *attachmentUri* is null or empty |

### See Also

* class [Attachment](../../../aspose.email/attachment/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)


