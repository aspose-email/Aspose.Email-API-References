---
title: Class GraphQueryBuilder
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Graph.GraphQueryBuilder class. Represents the builder of search expression based on search filters that used by MS Graph protocol
type: docs
weight: 16040
url: /net/aspose.email.clients.graph/graphquerybuilder/
---
## GraphQueryBuilder class

Represents the builder of search expression based on search filters that used by MS Graph protocol.

```csharp
public class GraphQueryBuilder : MailQueryBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [GraphQueryBuilder](graphquerybuilder/)() | Initializes a new instance of the `GraphQueryBuilder` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body/) { get; } | Gets the field that allows to find messages that contain the specified string in the body of the message. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding/) { get; } | Gets default encoding (charset) for query builder |
| [From](../../aspose.email.tools.search/mailquerybuilder/from/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate/) { get; } | Gets the field that allows to find messages by internal date. |
| [IsRead](../../aspose.email.clients.graph/graphquerybuilder/isread/) { get; } | Gets the field that allows to find unread items. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate/) { get; } | Gets the field that allows to find messages by sent date. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text/) { get; } | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |

## Methods

| Name | Description |
| --- | --- |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery/)() | Gets the query. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or/)(MailQuery, MailQuery) | Search messages that match either search key. Provides disjunction between two expressions (OR). |

### See Also

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder/)
* namespace [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph/)
* assembly [Aspose.Email](../../)


