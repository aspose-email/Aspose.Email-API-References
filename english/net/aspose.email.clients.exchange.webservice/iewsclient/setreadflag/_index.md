---
title: IEWSClient.SetReadFlag
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Sets the read flag
type: docs
weight: 1420
url: /net/aspose.email.clients.exchange.webservice/iewsclient/setreadflag/
---
## SetReadFlag(string) {#setreadflag}

Sets the read flag.

```csharp
public void SetReadFlag(string messageUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | String | The message URI. |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## SetReadFlag(string, bool) {#setreadflag_1}

Marks the specifeid message as read.

```csharp
public void SetReadFlag(string messageUri, bool isRead)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | String | A message uri. |
| isRead | Boolean | A value indicating whether the message was read |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *messageUri* is `null` or `empty`. |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


