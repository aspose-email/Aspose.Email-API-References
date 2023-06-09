---
title: IEWSClient.ListDelegates
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Lists the users who are granted access on the specified mailbox
type: docs
weight: 1100
url: /net/aspose.email.clients.exchange.webservice/iewsclient/listdelegates/
---
## IEWSClient.ListDelegates method

Lists the users who are granted access on the specified mailbox.

```csharp
public ExchangeDelegateUserCollection ListDelegates(string mailbox)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | String | A mailbox. |

### Return Value

A [`ExchangeDelegateUserCollection`](../../exchangedelegateusercollection/) representing the delegate users.

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *mailbox* is `null` or `empty`. |

### See Also

* class [ExchangeDelegateUserCollection](../../exchangedelegateusercollection/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


