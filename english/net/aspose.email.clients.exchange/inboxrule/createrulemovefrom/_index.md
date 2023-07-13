---
title: InboxRule.CreateRuleMoveFrom
second_title: Aspose.Email for .NET API Reference
description: InboxRule method. Creates inbox rule that moves messages from specified senders into the specified folder
type: docs
weight: 50
url: /net/aspose.email.clients.exchange/inboxrule/createrulemovefrom/
---
## InboxRule.CreateRuleMoveFrom method

Creates inbox rule that moves messages from specified senders into the specified folder

```csharp
public static InboxRule CreateRuleMoveFrom(MailAddress from, string destinationFolderId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| from | MailAddress | A EmailAddress of sender |
| destinationFolderId | String | An id of folder in which messages will be moved |

### Return Value

A created [`InboxRule`](../)

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *from* is `null` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *destinationFolderId* is `null` or `empty` |

### See Also

* class [MailAddress](../../../aspose.email/mailaddress/)
* class [InboxRule](../)
* namespace [Aspose.Email.Clients.Exchange](../../inboxrule/)
* assembly [Aspose.Email](../../../)


