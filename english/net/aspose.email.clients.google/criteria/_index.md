---
title: Class Criteria
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Google.Criteria class. Message matching criteria
type: docs
weight: 15710
url: /net/aspose.email.clients.google/criteria/
---
## Criteria class

Message matching criteria.

```csharp
public class Criteria
```

## Constructors

| Name | Description |
| --- | --- |
| [Criteria](criteria/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ExcludeChats](../../aspose.email.clients.google/criteria/excludechats/) { get; set; } | Whether the response should exclude chats. |
| [From](../../aspose.email.clients.google/criteria/from/) { get; set; } | The sender's display name or email address. |
| [HasAttachment](../../aspose.email.clients.google/criteria/hasattachment/) { get; set; } | Whether the message has any attachment. |
| [NegatedQuery](../../aspose.email.clients.google/criteria/negatedquery/) { get; set; } | Only return messages not matching the specified query. Supports the same query format as the Gmail search box. For example, "from:someuser@example.com rfc822msgid:somemsgid@example.com is:unread". |
| [Query](../../aspose.email.clients.google/criteria/query/) { get; set; } | Only return messages matching the specified query.Supports the same query format as the Gmail search box. For example, "from:someuser@example.com rfc822msgid:somemsgid@example.com is:unread". |
| [Size](../../aspose.email.clients.google/criteria/size/) { get; set; } | The size of the entire RFC822 message in bytes, including all headers and attachments. |
| [SizeComparison](../../aspose.email.clients.google/criteria/sizecomparison/) { get; set; } | How the message size in bytes should be in relation to the size field. |
| [Subject](../../aspose.email.clients.google/criteria/subject/) { get; set; } | Case-insensitive phrase found in the message's subject. Trailing and leading whitespace are be trimmed and adjacent spaces are collapsed. |
| [To](../../aspose.email.clients.google/criteria/to/) { get; set; } | The recipient's display name or email address. Includes recipients in the "to", "cc", and "bcc" header fields. You can use simply the local part of the email address. For example, "example" and "example@" both match "example@gmail.com". This field is case-insensitive. |

### See Also

* namespace [Aspose.Email.Clients.Google](../../aspose.email.clients.google/)
* assembly [Aspose.Email](../../)


