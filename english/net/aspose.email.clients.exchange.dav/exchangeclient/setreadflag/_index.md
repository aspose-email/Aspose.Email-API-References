---
title: ExchangeClient.SetReadFlag
second_title: Aspose.Email for .NET API Reference
description: ExchangeClient method. Marks the specifeid message as read
type: docs
weight: 380
url: /net/aspose.email.clients.exchange.dav/exchangeclient/setreadflag/
---
## SetReadFlag(string) {#setreadflag}

Marks the specifeid message as read.

```csharp
public void SetReadFlag(string messageUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | String | A message uri. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *messageUri* is `null` or `empty`. |

### See Also

* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)

---

## SetReadFlag(string, bool) {#setreadflag_1}

Marks the specifeid message as read.

```csharp
public void SetReadFlag(string messageUri, bool suppressReceipt)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | String | A message uri. |
| suppressReceipt | Boolean | A value indicating whether the sending a read receipt should be suppressed. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *messageUri* is `null` or `empty`. |

### See Also

* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)


