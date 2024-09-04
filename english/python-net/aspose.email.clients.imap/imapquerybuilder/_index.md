---
title: ImapQueryBuilder
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 260
url: /python-net/aspose.email.clients.imap/imapquerybuilder/
---

## ImapQueryBuilder class

Represents the builder of search expression<br/>            that used by IMAP protocol.

The ImapQueryBuilder type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|ImapQueryBuilder(default_encoding)|Initializes a new instance of the ImapQueryBuilder class|
|ImapQueryBuilder()|Initializes a new instance of the [ImapQueryBuilder](/email/python-net/aspose.email.clients.imap/imapquerybuilder/) class.|
## Properties
| Name | Description |
| :- | :- |
|to|Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field.|
|text|Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message.|
|bcc|Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field.|
|body|Gets the field that allows to find messages that contain the specified string in the body of the message.|
|cc|Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field.|
|from_address|Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field.|
|subject|Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field.|
|default_encoding|Gets default encoding (charset) for query builder|
|internal_date|Gets the field that allows to find messages by internal date.|
|sent_date|Gets the field that allows to find messages by sent date.|
|message_size|Gets messages with an specified size.|
|unique_id|Unique identifier|
|e_search_parameters|Gets or sets ESEARCH Parameters<br/>            This method works only if server supports ESEARCH extension. <br/>            Please, read more https://tools.ietf.org/html/rfc4315|
|mod_seq|Modification sequence|
## Methods
| Name | Description |
| :- | :- |
|either(query1, query2)|  |
|get_query()|  |
|has_flags(flags)|  |
|has_no_flags(flags)|  |
|has_header(field_name, field_value)|  |
|custom_search(field_value)|  |

### See Also

* namespace [aspose.email.clients.imap](/email/python-net/aspose.email.clients.imap/)
* assembly [Aspose.Email](/email/python-net/)

