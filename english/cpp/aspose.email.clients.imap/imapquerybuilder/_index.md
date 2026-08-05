---
title: "Aspose::Email::Clients::Imap::ImapQueryBuilder class"
linktitle: "ImapQueryBuilder"
articleTitle: "ImapQueryBuilder"
second_title: "Aspose.Email for C++"
description: "Represents the builder of search expression that used by IMAP protocol."
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/imapquerybuilder/
---

## ImapQueryBuilder class

**Inherits:** Aspose::Email::Tools::Search::MailQueryBuilder

Represents the builder of search expression that used by IMAP protocol.

## Constructors

| Name | Description |
| --- | --- |
| [ImapQueryBuilder (2 overloads)](./imapquerybuilder/) | Initializes a new instance of the ImapQueryBuilder class. |

## Methods

| Name | Description |
| --- | --- |
| [CustomSearch](./customsearch/) | Search messages according to extended server search syntax. |
| [get_ESearchParameters](./get_esearchparameters/) | Gets ESEARCH Parameters This method works only if server supports ESEARCH extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [get_MessageSize](./get_messagesize/) | Gets messages with an specified size. |
| [get_ModSeq](./get_modseq/) | Modification sequence |
| [get_UniqueId](./get_uniqueid/) | Unique identifier |
| [HasFlags](./hasflags/) | Search messages with the specified flags. |
| [HasHeader](./hasheader/) | Search messages that have a header with the specified field-name and that contains the specified string in the text of the header (what comes after the colon). If the string to search is zero-length, this matches all messages that have a header line with the specified field-name regardless of the contents. |
| [HasNoFlags](./hasnoflags/) | Search messages with the unspecified flags. |
| [set_ESearchParameters](./set_esearchparameters/) | Sets ESEARCH Parameters This method works only if server supports ESEARCH extension. Please, read more https://tools.ietf.org/html/rfc4315 |

