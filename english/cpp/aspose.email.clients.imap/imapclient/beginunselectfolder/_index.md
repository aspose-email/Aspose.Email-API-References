---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginUnselectFolder method"
linktitle: "BeginUnselectFolder"
articleTitle: "BeginUnselectFolder"
second_title: "Aspose.Email for C++"
description: "Begins permanently removes all messages marked as deleted for currently selected folder and removes selected-state for current folder asyncronously."
type: docs
weight: 490
url: /cpp/aspose.email.clients.imap/imapclient/beginunselectfolder/
---

## BeginUnselectFolder (1 of 12) {#beginunselectfolder_1}

Begins permanently removes all messages marked as deleted for currently selected folder and removes selected-state for current folder asyncronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder()
```

---

## BeginUnselectFolder (2 of 12) {#beginunselectfolder_2}

Unselects folder which are currently selected asyncronously. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder(bool doNotExpunge)
```

| Parameter | Description |
| --- | --- |
| doNotExpunge | Specifies whether messages marked as deleted should be removed. |

---

## BeginUnselectFolder (3 of 12) {#beginunselectfolder_3}

Unselects folder which are currently selected asyncronously. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder(bool doNotExpunge, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| doNotExpunge | Specifies whether messages marked as deleted should be removed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginUnselectFolder (4 of 12) {#beginunselectfolder_4}

Unselects folder which are currently selected asyncronously. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder(bool doNotExpunge, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| doNotExpunge | Specifies whether messages marked as deleted should be removed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginUnselectFolder (5 of 12) {#beginunselectfolder_5}

Begins permanently removes all messages marked as deleted for currently selected folder and removes selected-state for current folder asyncronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder(System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginUnselectFolder (6 of 12) {#beginunselectfolder_6}

Begins permanently removes all messages marked as deleted for currently selected folder and removes selected-state for current folder asyncronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder(System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginUnselectFolder (7 of 12) {#beginunselectfolder_7}

Begins permanently removes all messages marked as deleted for currently selected folder and removes selected-state for current folder asyncronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder(System::SharedPtr < IConnection > connection)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |

---

## BeginUnselectFolder (8 of 12) {#beginunselectfolder_8}

Unselects folder which are currently selected asyncronously. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder(System::SharedPtr < IConnection > connection, bool doNotExpunge)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| doNotExpunge | Specifies whether messages marked as deleted should be removed. |

---

## BeginUnselectFolder (9 of 12) {#beginunselectfolder_9}

Unselects folder which are currently selected asyncronously. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder(System::SharedPtr < IConnection > connection, bool doNotExpunge, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| doNotExpunge | Specifies whether messages marked as deleted should be removed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginUnselectFolder (10 of 12) {#beginunselectfolder_10}

Unselects folder which are currently selected asyncronously. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder(System::SharedPtr < IConnection > connection, bool doNotExpunge, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| doNotExpunge | Specifies whether messages marked as deleted should be removed. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginUnselectFolder (11 of 12) {#beginunselectfolder_11}

Begins permanently removes all messages marked as deleted for currently selected folder and removes selected-state for current folder asyncronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder(System::SharedPtr < IConnection > connection, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginUnselectFolder (12 of 12) {#beginunselectfolder_12}

Begins permanently removes all messages marked as deleted for currently selected folder and removes selected-state for current folder asyncronously.

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginUnselectFolder(System::SharedPtr < IConnection > connection, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

