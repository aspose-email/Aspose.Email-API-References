---
title: ImapQueryBuilder.HasHeader
second_title: Aspose.Email for .NET API Reference
description: ImapQueryBuilder method. Search messages that have a header with the specified fieldname and that contains the specified string in the text of the header what comes after the colon. If the string to search is zerolength this matches all messages that have a header line with the specified fieldname regardless of the contents
type: docs
weight: 80
url: /net/aspose.email.clients.imap/imapquerybuilder/hasheader/
---
## ImapQueryBuilder.HasHeader method

Search messages that have a header with the specified field-name and that contains the specified string in the text of the header (what comes after the colon). If the string to search is zero-length, this matches all messages that have a header line with the specified field-name regardless of the contents.

```csharp
public MailQuery HasHeader(string fieldName, string fieldValue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of the field. |
| fieldValue | String | The field value. |

### Return Value

[`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query (one searching criteria).

### See Also

* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ImapQueryBuilder](../)
* namespace [Aspose.Email.Clients.Imap](../../imapquerybuilder/)
* assembly [Aspose.Email](../../../)


