---
title: ExchangeClient.DeleteMessage
second_title: Aspose.Email for .NET API Reference
description: ExchangeClient method. Deletes the mail message
type: docs
weight: 150
url: /net/aspose.email.clients.exchange.dav/exchangeclient/deletemessage/
---
## DeleteMessage(string) {#deletemessage}

Deletes the mail message.

```csharp
public void DeleteMessage(string messageUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | String | The message uri. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *messageUri* is `empty`. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *messageUri* is `null`. |

### See Also

* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteMessage(string, bool) {#deletemessage_1}

Deletes the mail message.

```csharp
public void DeleteMessage(string messageUri, bool suppressReceipt)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | String | The message uri. |
| suppressReceipt | Boolean | A value indicating whether the sending a non-read report should be suppressed. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *messageUri* is `empty`. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *messageUri* is `null`. |

### See Also

* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)


