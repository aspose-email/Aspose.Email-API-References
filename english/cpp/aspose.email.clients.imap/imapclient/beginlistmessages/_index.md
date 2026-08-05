---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginListMessages method"
linktitle: "BeginListMessages"
articleTitle: "BeginListMessages"
second_title: "Aspose.Email for C++"
description: "Begins getting the list of messages asynchronously in the current folder"
type: docs
weight: 310
url: /cpp/aspose.email.clients.imap/imapclient/beginlistmessages/
---

## BeginListMessages (1 of 44) {#beginlistmessages_1}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages()
```

---

## BeginListMessages (2 of 44) {#beginlistmessages_2}

Begins getting the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| modificationSequence | Modification sequence |

---

## BeginListMessages (3 of 44) {#beginlistmessages_3}

Begins getting the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| modificationSequence | Modification sequence |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (4 of 44) {#beginlistmessages_4}

Begins getting the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| modificationSequence | Modification sequence |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (5 of 44) {#beginlistmessages_5}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (6 of 44) {#beginlistmessages_6}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (7 of 44) {#beginlistmessages_7}

Begins getting the list of messages in the current folder Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| maxNumberOfMessages | Maximum number of messages. |

---

## BeginListMessages (8 of 44) {#beginlistmessages_8}

Begins getting the list of messages in the current folder Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, int32_t maxNumberOfMessages, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| maxNumberOfMessages | Maximum number of messages. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (9 of 44) {#beginlistmessages_9}

Begins getting the list of messages in the current folder Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, int32_t maxNumberOfMessages, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| maxNumberOfMessages | Maximum number of messages. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (10 of 44) {#beginlistmessages_10}

Begins getting the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| modificationSequence | Modification sequence |

---

## BeginListMessages (11 of 44) {#beginlistmessages_11}

Begins getting the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, int64_t modificationSequence, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| modificationSequence | Modification sequence |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (12 of 44) {#beginlistmessages_12}

Begins getting the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, int64_t modificationSequence, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| modificationSequence | Modification sequence |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (13 of 44) {#beginlistmessages_13}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::String folderName, ImapListFields fieldsList, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| fieldsList | Fields that may be retrieved from the server. |
| maxNumberOfMessages | Maximum number of messages. |

---

## BeginListMessages (14 of 44) {#beginlistmessages_14}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::String folderName, ImapListFields fieldsList, int32_t maxNumberOfMessages, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| fieldsList | Fields that may be retrieved from the server. |
| maxNumberOfMessages | Maximum number of messages. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (15 of 44) {#beginlistmessages_15}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::String folderName, ImapListFields fieldsList, int32_t maxNumberOfMessages, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| fieldsList | Fields that may be retrieved from the server. |
| maxNumberOfMessages | Maximum number of messages. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (16 of 44) {#beginlistmessages_16}

Begins getting the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::String folderName, int64_t modificationSequence, bool retrieveRecursively, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageExtraFields, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| modificationSequence | Modification sequence |
| retrieveRecursively | Indicates, if messages have to be retrieved recursively. |
| messageExtraFields | List of extra parameters for a message wich will be requested. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (17 of 44) {#beginlistmessages_17}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| sequenceNumberLst | sequenceNumber list for ImapMessageInfo to retrieve from a server. |

---

## BeginListMessages (18 of 44) {#beginlistmessages_18}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| sequenceNumberLst | sequenceNumber list for ImapMessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (19 of 44) {#beginlistmessages_19}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| sequenceNumberLst | sequenceNumber list for ImapMessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (20 of 44) {#beginlistmessages_20}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| uniqueIdLst | UniqueId list for ImapMessageInfo to retrieve from a server. |

---

## BeginListMessages (21 of 44) {#beginlistmessages_21}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| uniqueIdLst | UniqueId list for ImapMessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (22 of 44) {#beginlistmessages_22}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| uniqueIdLst | UniqueId list for ImapMessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (23 of 44) {#beginlistmessages_23}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < Tools::Search::MailQuery > query, int32_t maxNumberOfMessages, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageExtraFields, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Messages location |
| query | MailQuery that represents search query. |
| maxNumberOfMessages | Maximum number of messages. |
| messageExtraFields | List of extra parameters for a message wich will be requested. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (24 of 44) {#beginlistmessages_24}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents search query. |

---

## BeginListMessages (25 of 44) {#beginlistmessages_25}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < Tools::Search::MailQuery > query, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents search query. |
| maxNumberOfMessages | Maximum number of messages. |

---

## BeginListMessages (26 of 44) {#beginlistmessages_26}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < Tools::Search::MailQuery > query, int32_t maxNumberOfMessages, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents search query. |
| maxNumberOfMessages | Maximum number of messages. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (27 of 44) {#beginlistmessages_27}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::SharedPtr < Tools::Search::MailQuery > query, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents search query. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (28 of 44) {#beginlistmessages_28}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName)
```

| Parameter | Description |
| --- | --- |
| folderName | Messages location |

---

## BeginListMessages (29 of 44) {#beginlistmessages_29}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, ImapListFields fieldsList, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| fieldsList | Fields that may be retrieved from the server. |
| maxNumberOfMessages | Maximum number of messages. |

---

## BeginListMessages (30 of 44) {#beginlistmessages_30}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, ImapListFields fieldsList, int32_t maxNumberOfMessages, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| fieldsList | Fields that may be retrieved from the server. |
| maxNumberOfMessages | Maximum number of messages. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (31 of 44) {#beginlistmessages_31}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, ImapListFields fieldsList, int32_t maxNumberOfMessages, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| fieldsList | Fields that may be retrieved from the server. |
| maxNumberOfMessages | Maximum number of messages. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (32 of 44) {#beginlistmessages_32}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (33 of 44) {#beginlistmessages_33}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (34 of 44) {#beginlistmessages_34}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| sequenceNumberLst | sequenceNumber list for ImapMessageInfo to retrieve from a server. |

---

## BeginListMessages (35 of 44) {#beginlistmessages_35}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| sequenceNumberLst | sequenceNumber list for ImapMessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (36 of 44) {#beginlistmessages_36}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| sequenceNumberLst | sequenceNumber list for ImapMessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (37 of 44) {#beginlistmessages_37}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| uniqueIdLst | UniqueId list for ImapMessageInfo to retrieve from a server. |

---

## BeginListMessages (38 of 44) {#beginlistmessages_38}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| uniqueIdLst | UniqueId list for ImapMessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (39 of 44) {#beginlistmessages_39}

Begins ListMessages operation asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| uniqueIdLst | UniqueId list for ImapMessageInfo to retrieve from a server. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (40 of 44) {#beginlistmessages_40}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| folderName | Messages location |
| query | MailQuery that represents search query. |

---

## BeginListMessages (41 of 44) {#beginlistmessages_41}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::SharedPtr < Tools::Search::MailQuery > query, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| folderName | Messages location |
| query | MailQuery that represents search query. |
| maxNumberOfMessages | Maximum number of messages. |

---

## BeginListMessages (42 of 44) {#beginlistmessages_42}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::SharedPtr < Tools::Search::MailQuery > query, int32_t maxNumberOfMessages, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| folderName | Messages location |
| query | MailQuery that represents search query. |
| maxNumberOfMessages | Maximum number of messages. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginListMessages (43 of 44) {#beginlistmessages_43}

Begins getting the list of messages asynchronously in the current folder

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::SharedPtr < Tools::Search::MailQuery > query, int32_t maxNumberOfMessages, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| folderName | Messages location |
| query | MailQuery that represents search query. |
| maxNumberOfMessages | Maximum number of messages. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginListMessages (44 of 44) {#beginlistmessages_44}

Begins getting the list of messages asynchronously

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginListMessages(System::String folderName, System::SharedPtr < Tools::Search::MailQuery > query, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| folderName | Messages location |
| query | MailQuery that represents search query. |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

