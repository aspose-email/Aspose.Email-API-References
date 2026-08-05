---
title: "Aspose::Email::Clients::Graph::IGraphClient::ListOverrides method"
linktitle: "ListOverrides"
articleTitle: "ListOverrides"
second_title: "Aspose.Email for C++"
description: "Get the overrides that a user has set up to always classify messages from certain senders in specific ways."
type: docs
weight: 470
url: /cpp/aspose.email.clients.graph/igraphclient/listoverrides/
---

## ListOverrides {#listoverrides}

Get the overrides that a user has set up to always classify messages from certain senders in specific ways. Each override corresponds to an SMTP address of a sender.Initially, a user does not have any overrides. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) Mail.Read Delegated (personal Microsoft account) Mail.Read Application Mail.Read

**Returns:** virtual System::SharedPtr <System::Collections::Generic::ListExt< System::SharedPtr < ClassificationOverride > > > Aspose::Email::Clients::Graph::

```cpp
ListOverrides(System::SharedPtr < ODataQueryBuilder > queryBuilder)
```

| Parameter | Description |
| --- | --- |
| queryBuilder | Optional OData query builder for filtering overrides. |

