---
title: "Aspose::Email::Storage::Mbox::MboxStorageReader::EnumerateMessageInfo method"
linktitle: "EnumerateMessageInfo"
articleTitle: "EnumerateMessageInfo"
second_title: "Aspose.Email for C++"
description: "Exposes the enumerator, which supports an iteration of messages in storage."
type: docs
weight: 60
url: /cpp/aspose.email.storage.mbox/mboxstoragereader/enumeratemessageinfo/
---

## EnumerateMessageInfo (1 of 3) {#enumeratemessageinfo_1}

Exposes the enumerator, which supports an iteration of messages in storage.

**Returns:** System::Collections::Generic::IEnumerable<T> , that represents an enumerator that iterates through a messages in storage.

```cpp
EnumerateMessageInfo()
```

---

## EnumerateMessageInfo (2 of 3) {#enumeratemessageinfo_2}

Enumerates a specified number of message information entries, starting from the given index.

**Returns:** An enumerable collection of MboxMessageInfo instances starting from the specified index. The collection may be empty if there are no messages in the specified range.

```cpp
EnumerateMessageInfo(int32_t startIndex, int32_t count)
```

| Parameter | Description |
| --- | --- |
| startIndex | The zero-based index of the first message to retrieve. If startIndex is greater than or equal to the total number of items, an ArgumentOutOfRangeException is thrown. |
| count | The maximum number of message information entries to retrieve. If set to -1, all messages from the start index will be read. |

---

## EnumerateMessageInfo (3 of 3) {#enumeratemessageinfo_3}

Enumerates the message information that matches the specified query.

**Returns:** An enumerable collection of MboxMessageInfo instances that match the specified query. The collection may be empty if no messages match.

```cpp
EnumerateMessageInfo(System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| query | The MailQuery used to filter messages. |

