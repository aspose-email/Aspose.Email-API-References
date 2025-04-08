---
title: Criteria
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 100
url: /python-net/aspose.email.clients.google/criteria/
---

## Criteria class

Message matching criteria.

The Criteria type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Criteria()|Initializes a new instance of the Criteria class|
## Properties
| Name | Description |
| :- | :- |
|from_address|The sender's display name or email address.|
|to|The recipient's display name or email address. Includes recipients in the "to", "cc", and "bcc" header fields. <br/>            You can use simply the local part of the email address.<br/>            For example, "example" and "example@" both match "example@gmail.com". This field is case-insensitive.|
|subject|Case-insensitive phrase found in the message's subject. Trailing and leading whitespace are be trimmed and adjacent spaces are collapsed.|
|query|Only return messages matching the specified query.Supports the same query format as the Gmail search box.<br/>            For example, "from:someuser@example.com rfc822msgid:somemsgid@example.com is:unread".|
|negated_query|Only return messages not matching the specified query. Supports the same query format as the Gmail search box. <br/>            For example, "from:someuser@example.com rfc822msgid:somemsgid@example.com is:unread".|
|has_attachment|Whether the message has any attachment.|
|exclude_chats|Whether the response should exclude chats.|
|size|The size of the entire RFC822 message in bytes, including all headers and attachments.|
|size_comparison|How the message size in bytes should be in relation to the size field.|

### See Also

* namespace [aspose.email.clients.google](/email/python-net/aspose.email.clients.google/)
* assembly [Aspose.Email](/email/python-net/)

