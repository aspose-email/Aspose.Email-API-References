---
title: "Aspose::Email::Clients::Imap::ImapClient::ListMessages method"
linktitle: "ListMessages"
articleTitle: "ListMessages"
second_title: "Aspose.Email for C++"
description: "Gets the list of messages in the current folder"
type: docs
weight: 1590
url: /cpp/aspose.email.clients.imap/imapclient/listmessages/
---

## ListMessages (1 of 27) {#listmessages_1}

Gets the list of messages in the current folder

**Returns:** Collection of ImapMessageInfo objects

```cpp
ListMessages()
```

---

## ListMessages (2 of 27) {#listmessages_2}

Gets the list of messages in the current folder

**Returns:** Collection of ImapMessageInfo objects

```cpp
ListMessages(bool retrieveRecursively)
```

| Parameter | Description |
| --- | --- |
| retrieveRecursively | Indicates, if messages have to be retrieved recursively. |

---

## ListMessages (3 of 27) {#listmessages_3}

Gets the list of messages in the current folder.

**Returns:** Collection of ImapMessageInfo representing the messages information.

```cpp
ListMessages(int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| maxNumberOfMessages | Maximum number of messages. |

---

## ListMessages (4 of 27) {#listmessages_4}

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** Collection of ImapMessageInfo representing the messages information.

```cpp
ListMessages(int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| modificationSequence | Modification sequence |

---

## ListMessages (5 of 27) {#listmessages_5}

Gets the list of messages in the current folder

**Returns:** Collection of ImapMessageInfo objects

```cpp
ListMessages(System::SharedPtr < IConnection > connection)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |

---

## ListMessages (6 of 27) {#listmessages_6}

Gets the list of messages in the current folder

**Returns:** Collection of ImapMessageInfo objects

```cpp
ListMessages(System::SharedPtr < IConnection > connection, bool retrieveRecursively)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| retrieveRecursively | Indicates, if messages have to be retrieved recursively. |

---

## ListMessages (7 of 27) {#listmessages_7}

Gets the list of messages in the current folder.

**Returns:** Collection of ImapMessageInfo representing the messages information.

```cpp
ListMessages(System::SharedPtr < IConnection > connection, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| maxNumberOfMessages | Maximum number of messages. |

---

## ListMessages (8 of 27) {#listmessages_8}

Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162

**Returns:** Collection of ImapMessageInfo representing the messages information.

```cpp
ListMessages(System::SharedPtr < IConnection > connection, int64_t modificationSequence)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| modificationSequence | Modification sequence |

---

## ListMessages (9 of 27) {#listmessages_9}

Gets the list of messages in the current folder.

**Returns:** Collection of ImapMessageInfo objects.

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| query | MailQuery that represents search query. |

---

## ListMessages (10 of 27) {#listmessages_10}

Gets the list of messages in the current folder.

**Returns:** Collection of ImapMessageInfo objects.

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < Tools::Search::MailQuery > query, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| query | MailQuery that represents search query. |
| maxNumberOfMessages | Maximum number of messages. |

---

## ListMessages (11 of 27) {#listmessages_11}

Gets the list of messages in the specified folder

**Returns:** Collection of ImapMessageInfo objects

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |

---

## ListMessages (12 of 27) {#listmessages_12}

Gets the list of messages in the specified folder

**Returns:** Collection of ImapMessageInfo objects

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::String folderName, bool retrieveRecursively)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| retrieveRecursively | Indicates, if messages have to be retrieved recursively. |

---

## ListMessages (13 of 27) {#listmessages_13}

Lists the messages. Gets an information for earch message

**Returns:** ImapMessageInfoCollection

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::String folderName, ImapListFields fieldsList, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| fieldsList | Fields that may be retrieved from the server. |
| maxNumberOfMessages | Maximum number of messages. |

---

## ListMessages (14 of 27) {#listmessages_14}

Gets the list of messages in the specified folder

**Returns:** Collection of ImapMessageInfo objects

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::String folderName, int64_t modificationSequence, bool retrieveRecursively, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageExtraFields)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| modificationSequence | Modification sequence |
| retrieveRecursively | Indicates, if messages have to be retrieved recursively. |
| messageExtraFields | List of extra parameters for a message wich will be requested. |

---

## ListMessages (15 of 27) {#listmessages_15}

Lists the messages. Gets an information for earch message

**Returns:** ImapMessageInfoCollection

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| sequenceNumberLst | sequenceNumber list for ImapMessageInfo to retrieve from a server. |

---

## ListMessages (16 of 27) {#listmessages_16}

Lists the messages. Gets an information for earch message

**Returns:** ImapMessageInfoCollection

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Folder to retrieve messages. |
| uniqueIdLst | UniqueId list for ImapMessageInfo to retrieve from a server. |

---

## ListMessages (17 of 27) {#listmessages_17}

Gets the list of messages in the current folder.

**Returns:** Collection of ImapMessageInfo objects.

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < Tools::Search::MailQuery > query, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Messages location |
| query | MailQuery that represents search query. |
| maxNumberOfMessages | Maximum number of messages. |

---

## ListMessages (18 of 27) {#listmessages_18}

Gets the list of messages in the current folder

**Returns:** Collection of ImapMessageInfo objects

```cpp
ListMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageExtraFields)
```

| Parameter | Description |
| --- | --- |
| messageExtraFields | List of extra parameters for a message wich will be requested. |

---

## ListMessages (19 of 27) {#listmessages_19}

Gets the list of messages in the current folder.

**Returns:** Collection of ImapMessageInfo objects.

```cpp
ListMessages(System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents search query. |

---

## ListMessages (20 of 27) {#listmessages_20}

Gets the list of messages in the current folder.

**Returns:** Collection of ImapMessageInfo objects.

```cpp
ListMessages(System::SharedPtr < Tools::Search::MailQuery > query, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents search query. |
| maxNumberOfMessages | Maximum number of messages. |

---

## ListMessages (21 of 27) {#listmessages_21}

Gets the list of messages in the specified folder

**Returns:** Collection of ImapMessageInfo objects

```cpp
ListMessages(System::String folderName)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |

---

## ListMessages (22 of 27) {#listmessages_22}

Gets the list of messages in the specified folder

**Returns:** Collection of ImapMessageInfo objects

```cpp
ListMessages(System::String folderName, bool retrieveRecursively)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| retrieveRecursively | Indicates, if messages have to be retrieved recursively. |

---

## ListMessages (23 of 27) {#listmessages_23}

Gets the list of messages in the specified folder

**Returns:** Collection of ImapMessageInfo objects

```cpp
ListMessages(System::String folderName, bool retrieveRecursively, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageExtraFields)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| retrieveRecursively | Indicates, if messages have to be retrieved recursively. |
| messageExtraFields | List of extra parameters for a message wich will be requested. |

---

## ListMessages (24 of 27) {#listmessages_24}

Lists the messages. Gets an information for earch message

**Returns:** ImapMessageInfoCollection

```cpp
ListMessages(System::String folderName, ImapListFields fieldsList, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| fieldsList | Fields that may be retrieved from the server. |
| maxNumberOfMessages | Maximum number of messages. |

---

## ListMessages (25 of 27) {#listmessages_25}

Lists the messages. Gets an information for earch message

**Returns:** ImapMessageInfoCollection

```cpp
ListMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| sequenceNumberLst | sequenceNumber list for ImapMessageInfo to retrieve from a server. |

---

## ListMessages (26 of 27) {#listmessages_26}

Lists the messages. Gets an information for earch message

**Returns:** ImapMessageInfoCollection

```cpp
ListMessages(System::String folderName, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst)
```

| Parameter | Description |
| --- | --- |
| folderName | Folder to retrieve messages. |
| uniqueIdLst | UniqueId list for ImapMessageInfo to retrieve from a server. |

---

## ListMessages (27 of 27) {#listmessages_27}

Gets the list of messages in the current folder.

**Returns:** Collection of ImapMessageInfo objects.

```cpp
ListMessages(System::String folderName, System::SharedPtr < Tools::Search::MailQuery > query, int32_t maxNumberOfMessages)
```

| Parameter | Description |
| --- | --- |
| folderName | Messages location |
| query | MailQuery that represents search query. |
| maxNumberOfMessages | Maximum number of messages. |

