---
title: Class ImapQueryBuilder
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Imap.ImapQueryBuilder class. Represents the builder of search expression that used by IMAP protocol
type: docs
weight: 16560
url: /net/aspose.email.clients.imap/imapquerybuilder/
---
## ImapQueryBuilder class

Represents the builder of search expression that used by IMAP protocol.

```csharp
public sealed class ImapQueryBuilder : MailQueryBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [ImapQueryBuilder](imapquerybuilder/#constructor)() | Initializes a new instance of the `ImapQueryBuilder` class. |
| [ImapQueryBuilder](imapquerybuilder/#constructor_1)(Encoding) | Initializes a new instance of the `ImapQueryBuilder` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body/) { get; } | Gets the field that allows to find messages that contain the specified string in the body of the message. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding/) { get; } | Gets default encoding (charset) for query builder |
| [ESearchParameters](../../aspose.email.clients.imap/imapquerybuilder/esearchparameters/) { get; set; } | Gets or sets ESEARCH Parameters This method works only if server supports ESEARCH extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [From](../../aspose.email.tools.search/mailquerybuilder/from/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate/) { get; } | Gets the field that allows to find messages by internal date. |
| [MessageSize](../../aspose.email.clients.imap/imapquerybuilder/messagesize/) { get; } | Gets messages with an specified size. |
| [ModSeq](../../aspose.email.clients.imap/imapquerybuilder/modseq/) { get; } | Modification sequence |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate/) { get; } | Gets the field that allows to find messages by sent date. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text/) { get; } | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |
| [UniqueId](../../aspose.email.clients.imap/imapquerybuilder/uniqueid/) { get; } | Unique identifier |

## Methods

| Name | Description |
| --- | --- |
| [CustomSearch](../../aspose.email.clients.imap/imapquerybuilder/customsearch/)(string) | Search messages according to extended server search syntax. |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery/)() | Gets the query. |
| [HasFlags](../../aspose.email.clients.imap/imapquerybuilder/hasflags/)(ImapMessageFlags) | Search messages with the specified flags. |
| [HasHeader](../../aspose.email.clients.imap/imapquerybuilder/hasheader/)(string, string) | Search messages that have a header with the specified field-name and that contains the specified string in the text of the header (what comes after the colon). If the string to search is zero-length, this matches all messages that have a header line with the specified field-name regardless of the contents. |
| [HasNoFlags](../../aspose.email.clients.imap/imapquerybuilder/hasnoflags/)(ImapMessageFlags) | Search messages with the unspecified flags. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or/)(MailQuery, MailQuery) | Search messages that match either search key. Provides disjunction between two expressions (OR). |

### See Also

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder/)
* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap/)
* assembly [Aspose.Email](../../)


