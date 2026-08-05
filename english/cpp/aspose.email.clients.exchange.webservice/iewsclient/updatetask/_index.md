---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::UpdateTask method"
linktitle: "UpdateTask"
articleTitle: "UpdateTask"
second_title: "Aspose.Email for C++"
description: "Updates the specified task."
type: docs
weight: 1580
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/updatetask/
---

## UpdateTask (1 of 5) {#updatetask_1}

Updates the specified task.

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
UpdateTask(System::SharedPtr < ExchangeTask > task)
```

| Parameter | Description |
| --- | --- |
| task | An ExchangeTask containing the task information. |

---

## UpdateTask (2 of 5) {#updatetask_2}

Updates the specified task.

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
UpdateTask(System::SharedPtr < ExchangeTask > task, UpdateTaskOptions options)
```

| Parameter | Description |
| --- | --- |
| task | An ExchangeTask containing the task information. |
| options | An updation options. |

---

## UpdateTask (3 of 5) {#updatetask_3}

Updates the specified task.

**Returns:** Task uri.

```cpp
UpdateTask(System::SharedPtr < Mapi::MapiTask > task)
```

| Parameter | Description |
| --- | --- |
| task | An MapiTask containing the task information. |

---

## UpdateTask (4 of 5) {#updatetask_4}

Updates the specified task.

**Returns:** Task uri.

```cpp
UpdateTask(System::String uri, System::SharedPtr < Mapi::MapiTask > task)
```

| Parameter | Description |
| --- | --- |
| uri | Task identifier |
| task | An ExchangeTask containing the task information. |

---

## UpdateTask (5 of 5) {#updatetask_5}

Updates the specified task.

**Returns:** Task uri.

```cpp
UpdateTask(System::String uri, System::SharedPtr < Mapi::MapiTask > task, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < Mapi::PropertyDescriptor >>> additionalProperties)
```

| Parameter | Description |
| --- | --- |
| uri | Task identifier |
| task | An ExchangeTask containing the task information. |
| additionalProperties | An additional MAPI properties which can be used in MAPI object. |

