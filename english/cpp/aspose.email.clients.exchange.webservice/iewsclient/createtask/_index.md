---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::CreateTask method"
linktitle: "CreateTask"
articleTitle: "CreateTask"
second_title: "Aspose.Email for C++"
description: "Creates the given task in the default task folder."
type: docs
weight: 210
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/createtask/
---

## CreateTask (1 of 2) {#createtask_1}

Creates the given task in the default task folder.

**Returns:** A task uri

```cpp
CreateTask(System::SharedPtr < ExchangeTask > task)
```

| Parameter | Description |
| --- | --- |
| task | A task to create. |

---

## CreateTask (2 of 2) {#createtask_2}

Creates the given task in the specified folder.

**Returns:** A task uri

```cpp
CreateTask(System::String folder, System::SharedPtr < ExchangeTask > task)
```

| Parameter | Description |
| --- | --- |
| folder | A folder where task should be created. |
| task | A task to create. |

