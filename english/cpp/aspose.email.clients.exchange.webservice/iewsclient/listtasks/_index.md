---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::ListTasks method"
linktitle: "ListTasks"
articleTitle: "ListTasks"
second_title: "Aspose.Email for C++"
description: "Retrieves lists of exchange tasks for default folder."
type: docs
weight: 1070
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/listtasks/
---

## ListTasks (1 of 6) {#listtasks_1}

Retrieves lists of exchange tasks for default folder.

**Returns:** Tasks collection

```cpp
ListTasks()
```

---

## ListTasks (2 of 6) {#listtasks_2}

Retrieves lists of exchange tasks.

**Returns:** Tasks collection

```cpp
ListTasks(System::String folder)
```

| Parameter | Description |
| --- | --- |
| folder | Tasks folder |

---

## ListTasks (3 of 6) {#listtasks_3}

Retrieves lists of exchange tasks.

**Returns:** Tasks collection

```cpp
ListTasks(System::String folder, int32_t maxNumberOfItems)
```

| Parameter | Description |
| --- | --- |
| folder | Tasks folder |
| maxNumberOfItems | Maximum number of items |

---

## ListTasks (4 of 6) {#listtasks_4}

Retrieves lists of exchange tasks.

**Returns:** Tasks collection

```cpp
ListTasks(System::String folder, int32_t maxNumberOfItems, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| folder | Tasks folder |
| maxNumberOfItems | Maximum number of items |
| query | Mail query |

---

## ListTasks (5 of 6) {#listtasks_5}

Retrieves lists of exchange tasks.

**Returns:** Tasks collection

```cpp
ListTasks(System::String folder, int32_t maxNumberOfItems, System::SharedPtr < Tools::Search::MailQuery > query, bool recursive)
```

| Parameter | Description |
| --- | --- |
| folder | Tasks folder |
| maxNumberOfItems | Maximum number of items |
| query | Mail query |
| recursive | Retrieve tasks recursivly |

---

## ListTasks (6 of 6) {#listtasks_6}

Retrieves lists of exchange tasks.

**Returns:** Tasks collection

```cpp
ListTasks(System::String folder, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| folder | Tasks folder |
| query | Mail query |

