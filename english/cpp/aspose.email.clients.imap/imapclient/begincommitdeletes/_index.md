---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginCommitDeletes method"
linktitle: "BeginCommitDeletes"
articleTitle: "BeginCommitDeletes"
second_title: "Aspose.Email for C++"
description: "Begins to commit the deletions"
type: docs
weight: 110
url: /cpp/aspose.email.clients.imap/imapclient/begincommitdeletes/
---

## BeginCommitDeletes (1 of 28) {#begincommitdeletes_1}

Begins to commit the deletions

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes()
```

---

## BeginCommitDeletes (2 of 28) {#begincommitdeletes_2}

Begins to commit the deletions

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(int32_t sleep)
```

| Parameter | Description |
| --- | --- |
| sleep | Wait time complete the operation in milliseconds |

---

## BeginCommitDeletes (3 of 28) {#begincommitdeletes_3}

Begins to commit the deletions

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(int32_t sleep, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| sleep | Wait time complete the operation in milliseconds |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCommitDeletes (4 of 28) {#begincommitdeletes_4}

Begins to commit the deletions

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCommitDeletes (5 of 28) {#begincommitdeletes_5}

Begins to commit the deletions

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCommitDeletes (6 of 28) {#begincommitdeletes_6}

Begins to commit the deletions

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |

---

## BeginCommitDeletes (7 of 28) {#begincommitdeletes_7}

Begins to commit the deletions

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, int32_t sleep)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sleep | Wait time complete the operation in milliseconds |

---

## BeginCommitDeletes (8 of 28) {#begincommitdeletes_8}

Begins to commit the deletions

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, int32_t sleep, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sleep | Wait time complete the operation in milliseconds |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCommitDeletes (9 of 28) {#begincommitdeletes_9}

Begins to commit the deletions

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCommitDeletes (10 of 28) {#begincommitdeletes_10}

Begins to commit the deletions

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCommitDeletes (11 of 28) {#begincommitdeletes_11}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | Set of unique identifiers for messages |

---

## BeginCommitDeletes (12 of 28) {#begincommitdeletes_12}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | Set of unique identifiers for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCommitDeletes (13 of 28) {#begincommitdeletes_13}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | Set of unique identifiers for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCommitDeletes (14 of 28) {#begincommitdeletes_14}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |

---

## BeginCommitDeletes (15 of 28) {#begincommitdeletes_15}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCommitDeletes (16 of 28) {#begincommitdeletes_16}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCommitDeletes (17 of 28) {#begincommitdeletes_17}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of a message |

---

## BeginCommitDeletes (18 of 28) {#begincommitdeletes_18}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, System::String uniqueId, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of a message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCommitDeletes (19 of 28) {#begincommitdeletes_19}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < IConnection > connection, System::String uniqueId, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of a message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCommitDeletes (20 of 28) {#begincommitdeletes_20}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet)
```

| Parameter | Description |
| --- | --- |
| uidSet | Set of unique identifiers for messages |

---

## BeginCommitDeletes (21 of 28) {#begincommitdeletes_21}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uidSet | Set of unique identifiers for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCommitDeletes (22 of 28) {#begincommitdeletes_22}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uidSet | Set of unique identifiers for messages |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCommitDeletes (23 of 28) {#begincommitdeletes_23}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::String startUid, System::String endUid)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |

---

## BeginCommitDeletes (24 of 28) {#begincommitdeletes_24}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::String startUid, System::String endUid, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCommitDeletes (25 of 28) {#begincommitdeletes_25}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::String startUid, System::String endUid, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginCommitDeletes (26 of 28) {#begincommitdeletes_26}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of a message |

---

## BeginCommitDeletes (27 of 28) {#begincommitdeletes_27}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::String uniqueId, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of a message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginCommitDeletes (28 of 28) {#begincommitdeletes_28}

Begins to commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginCommitDeletes(System::String uniqueId, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of a message |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

