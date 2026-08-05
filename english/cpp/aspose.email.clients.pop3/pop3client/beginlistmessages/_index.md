---
title: "Aspose::Email::Clients::Pop3::Pop3Client::BeginListMessages method"
linktitle: "BeginListMessages"
articleTitle: "BeginListMessages"
second_title: "Aspose.Email for C++"
description: "Begins ListMessages operation asynchronously"
type: docs
weight: 130
url: /cpp/aspose.email.clients.pop3/pop3client/beginlistmessages/
---

## BeginListMessages (1 of 25) {#beginlistmessages_1}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages()
```

---

## BeginListMessages (2 of 25) {#beginlistmessages_2}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (3 of 25) {#beginlistmessages_3}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (4 of 25) {#beginlistmessages_4}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |

---

## BeginListMessages (5 of 25) {#beginlistmessages_5}

Begins ListMessage operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, Pop3ListFields fields, bool closeTransaction, System::SharedPtr < Tools::Search::MailQuery > query, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| fields | The fields that we want get |
| closeTransaction | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | The MailQuery object. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (6 of 25) {#beginlistmessages_6}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (7 of 25) {#beginlistmessages_7}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (8 of 25) {#beginlistmessages_8}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumberLst | sequenceNumber list for Pop3MessageInfo to retrieve from a server. |

---

## BeginListMessages (9 of 25) {#beginlistmessages_9}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumberLst | sequenceNumber list for Pop3MessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (10 of 25) {#beginlistmessages_10}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumberLst | sequenceNumber list for Pop3MessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (11 of 25) {#beginlistmessages_11}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueIdLst | UniqueId list for Pop3MessageInfo to retrieve from a server. |

---

## BeginListMessages (12 of 25) {#beginlistmessages_12}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueIdLst | UniqueId list for Pop3MessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (13 of 25) {#beginlistmessages_13}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueIdLst | UniqueId list for Pop3MessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (14 of 25) {#beginlistmessages_14}

Begins ListMessage operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| query | MailQuery that represents search query. |

---

## BeginListMessages (15 of 25) {#beginlistmessages_15}

Begins ListMessage operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < Tools::Search::MailQuery > query, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| query | The MailQuery object. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (16 of 25) {#beginlistmessages_16}

Begins ListMessage operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < Tools::Search::MailQuery > query, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| query | The MailQuery object. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (17 of 25) {#beginlistmessages_17}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst)
```

| Parameter | Description |
| --- | --- |
| sequenceNumberLst | sequenceNumber list for Pop3MessageInfo to retrieve from a server. |

---

## BeginListMessages (18 of 25) {#beginlistmessages_18}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| sequenceNumberLst | sequenceNumber list for Pop3MessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (19 of 25) {#beginlistmessages_19}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sequenceNumberLst | sequenceNumber list for Pop3MessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (20 of 25) {#beginlistmessages_20}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst)
```

| Parameter | Description |
| --- | --- |
| uniqueIdLst | UniqueId list for Pop3MessageInfo to retrieve from a server. |

---

## BeginListMessages (21 of 25) {#beginlistmessages_21}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uniqueIdLst | UniqueId list for Pop3MessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (22 of 25) {#beginlistmessages_22}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uniqueIdLst | UniqueId list for Pop3MessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (23 of 25) {#beginlistmessages_23}

Begins ListMessage operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents search query. |

---

## BeginListMessages (24 of 25) {#beginlistmessages_24}

Begins ListMessage operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < Tools::Search::MailQuery > query, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| query | The MailQuery object. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (25 of 25) {#beginlistmessages_25}

Begins ListMessage operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < Tools::Search::MailQuery > query, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| query | The MailQuery object. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

