---
title: "Aspose::Email::Storage::Pst::FolderInfo::EnumerateMessages method"
linktitle: "EnumerateMessages"
articleTitle: "EnumerateMessages"
second_title: "Aspose.Email for C++"
description: "Retrieves MessageInfo objects from the folder."
type: docs
weight: 160
url: /cpp/aspose.email.storage.pst/folderinfo/enumeratemessages/
---

## EnumerateMessages (1 of 4) {#enumeratemessages_1}

Retrieves MessageInfo objects from the folder.

**Returns:** An enumerable collection of all MessageInfo objects in the folder, excluding folder associated information (FAI) items.

```cpp
EnumerateMessages()
```

---

## EnumerateMessages (2 of 4) {#enumeratemessages_2}

Retrieves a collection of MessageInfo objects starting from a specific index and limited to a specified count.

**Returns:** An enumerable collection of MessageInfo objects starting at the specified index.

```cpp
EnumerateMessages(int32_t startIndex, int32_t count)
```

| Parameter | Description |
| --- | --- |
| startIndex | The zero-based index of the first message to retrieve. |
| count | The maximum number of messages to retrieve. If set to -1 , retrieves all messages starting from the specified startIndex . |

---

## EnumerateMessages (3 of 4) {#enumeratemessages_3}

Retrieves a collection of MessageInfo objects of the specified kind.

**Returns:** An enumerable collection of MessageInfo objects of the specified kind.

```cpp
EnumerateMessages(MessageKind kind)
```

| Parameter | Description |
| --- | --- |
| kind | The type of items to retrieve, such as normal messages or folder associated information items. |

---

## EnumerateMessages (4 of 4) {#enumeratemessages_4}

Retrieves a collection of MessageInfo objects that match the specified query.

**Returns:** An enumerable collection of MessageInfo objects matching the query.

```cpp
EnumerateMessages(System::SharedPtr < Tools::Search::MailQuery > mailQuery)
```

| Parameter | Description |
| --- | --- |
| mailQuery | The query criteria used to filter messages. |

