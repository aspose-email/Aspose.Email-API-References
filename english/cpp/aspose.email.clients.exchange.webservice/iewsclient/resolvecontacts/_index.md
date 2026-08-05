---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::ResolveContacts method"
linktitle: "ResolveContacts"
articleTitle: "ResolveContacts"
second_title: "Aspose.Email for C++"
description: "Resolves ambiguous mailbox display names."
type: docs
weight: 1240
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts/
---

## ResolveContacts (1 of 2) {#resolvecontacts_1}

Resolves ambiguous mailbox display names. Note: the maximum count of returned contacts is 100. This is a restriction of used exchange command.

**Returns:** An array of Contact objects.

```cpp
ResolveContacts(System::String unresolvedEntry)
```

| Parameter | Description |
| --- | --- |
| unresolvedEntry | A name of contact to resolve. |

---

## ResolveContacts (2 of 2) {#resolvecontacts_2}

Resolves ambiguous e-mail addresses and display names Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation.

**Returns:** Contacts that represents contacts information

```cpp
ResolveContacts(System::String unresolvedEntry, ExchangeListContactsOptions options)
```

| Parameter | Description |
| --- | --- |
| unresolvedEntry | A name of contact to resolve |
| options | Enumerates the list contacts options |

