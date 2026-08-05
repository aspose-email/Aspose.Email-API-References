---
title: "Aspose::Email::Clients::Graph::IGraphClient::CreateRule method"
linktitle: "CreateRule"
articleTitle: "CreateRule"
second_title: "Aspose.Email for C++"
description: "Create a message rule by specifying a set of conditions and actions."
type: docs
weight: 120
url: /cpp/aspose.email.clients.graph/igraphclient/createrule/
---

## CreateRule {#createrule}

Create a message rule by specifying a set of conditions and actions. Outlook carries out those actions if an incoming message in the user's Inbox meets the specified conditions. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.ReadWrite Delegated (personal Microsoft account) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite

**Returns:** Created rule

```cpp
CreateRule(System::SharedPtr < Exchange::InboxRule > rule)
```

| Parameter | Description |
| --- | --- |
| rule | Rule to be created in inbox |

