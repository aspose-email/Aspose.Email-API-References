---
title: IEWSClient.ResolveContacts
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Resolves ambiguous mailbox display names. Note the maximum count of returned contacts is 100. This is a restriction of used exchange command
type: docs
weight: 1370
url: /net/aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts/
---
## ResolveContacts(string) {#resolvecontacts}

Resolves ambiguous mailbox display names. Note: the maximum count of returned contacts is 100. This is a restriction of used exchange command.

```csharp
public Contact[] ResolveContacts(string unresolvedEntry)
```

| Parameter | Type | Description |
| --- | --- | --- |
| unresolvedEntry | String | A name of contact to resolve. |

### Return Value

An array of [`Contact`](../../../aspose.email.personalinfo/contact/) objects.

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ResolveContacts(string, ExchangeListContactsOptions) {#resolvecontacts_1}

Resolves ambiguous e-mail addresses and display names Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation.

```csharp
public Contact[] ResolveContacts(string unresolvedEntry, ExchangeListContactsOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| unresolvedEntry | String | A name of contact to resolve |
| options | ExchangeListContactsOptions | Enumerates the list contacts options |

### Return Value

Contacts that represents contacts information

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *unresolvedEntry* is `null` or `empty` |

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* enum [ExchangeListContactsOptions](../../exchangelistcontactsoptions/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


