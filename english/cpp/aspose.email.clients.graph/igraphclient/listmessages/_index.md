---
title: "Aspose::Email::Clients::Graph::IGraphClient::ListMessages method"
linktitle: "ListMessages"
articleTitle: "ListMessages"
second_title: "Aspose.Email for C++"
description: "List MessageInfo from the parent folder."
type: docs
weight: 450
url: /cpp/aspose.email.clients.graph/igraphclient/listmessages/
---

## ListMessages (1 of 2) {#listmessages_1}

List MessageInfo from the parent folder.

**Returns:** Returns list of MessageInfo of the folder

```cpp
ListMessages(System::String id, System::SharedPtr < ODataQueryBuilder > queryBuilder)
```

| Parameter | Description |
| --- | --- |
| id | Parent folder id |
| queryBuilder | Optional OData query builder for filtering messages. |

---

## ListMessages (2 of 2) {#listmessages_2}

List MessageInfo from the parent folder.

**Returns:** Returns list of MessageInfo of the folder

```cpp
ListMessages(System::String id, System::SharedPtr < PageInfo > page, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| id | Parent folder id |
| page | A page info |
| query | MailQuery that represents search query |

