---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginSetQuota method"
linktitle: "BeginSetQuota"
articleTitle: "BeginSetQuota"
second_title: "Aspose.Email for C++"
description: "Begins setting quota information"
type: docs
weight: 450
url: /cpp/aspose.email.clients.imap/imapclient/beginsetquota/
---

## BeginSetQuota (1 of 6) {#beginsetquota_1}

Begins setting quota information

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSetQuota(System::SharedPtr < IConnection > connection, System::String quotaRootName, System::String resourceName, int32_t resourceLimit)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| quotaRootName | quota root name |
| resourceName | resource name |
| resourceLimit | resource limit |

---

## BeginSetQuota (2 of 6) {#beginsetquota_2}

Begins setting quota information

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSetQuota(System::SharedPtr < IConnection > connection, System::String quotaRootName, System::String resourceName, int32_t resourceLimit, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| quotaRootName | quota root name |
| resourceName | resource name |
| resourceLimit | resource limit |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginSetQuota (3 of 6) {#beginsetquota_3}

Begins setting quota information

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSetQuota(System::SharedPtr < IConnection > connection, System::String quotaRootName, System::String resourceName, int32_t resourceLimit, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| quotaRootName | quota root name |
| resourceName | resource name |
| resourceLimit | resource limit |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginSetQuota (4 of 6) {#beginsetquota_4}

Begins setting quota information

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSetQuota(System::String quotaRootName, System::String resourceName, int32_t resourceLimit)
```

| Parameter | Description |
| --- | --- |
| quotaRootName | quota root name |
| resourceName | resource name |
| resourceLimit | resource limit |

---

## BeginSetQuota (5 of 6) {#beginsetquota_5}

Begins setting quota information

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSetQuota(System::String quotaRootName, System::String resourceName, int32_t resourceLimit, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| quotaRootName | quota root name |
| resourceName | resource name |
| resourceLimit | resource limit |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginSetQuota (6 of 6) {#beginsetquota_6}

Begins setting quota information

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginSetQuota(System::String quotaRootName, System::String resourceName, int32_t resourceLimit, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| quotaRootName | quota root name |
| resourceLimit | Resource limit. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |
| resourceName | Resource name. |

