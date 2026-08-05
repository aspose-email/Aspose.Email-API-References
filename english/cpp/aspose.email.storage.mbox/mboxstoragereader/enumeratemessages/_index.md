---
title: "Aspose::Email::Storage::Mbox::MboxStorageReader::EnumerateMessages method"
linktitle: "EnumerateMessages"
articleTitle: "EnumerateMessages"
second_title: "Aspose.Email for C++"
description: "Exposes the enumerator, which supports an iteration of messages in storage."
type: docs
weight: 70
url: /cpp/aspose.email.storage.mbox/mboxstoragereader/enumeratemessages/
---

## EnumerateMessages (1 of 6) {#enumeratemessages_1}

Exposes the enumerator, which supports an iteration of messages in storage.

**Returns:** System::Collections::Generic::IEnumerable<T> , that represents an enumerator that iterates through a messages in storage.

```cpp
EnumerateMessages()
```

---

## EnumerateMessages (2 of 6) {#enumeratemessages_2}

Enumerates a specified number of mail messages, starting from the given index.

**Returns:** An enumerable collection of MailMessage instances starting from the specified index. The collection may be empty if there are no messages in the specified range.

```cpp
EnumerateMessages(int32_t startIndex, int32_t count)
```

| Parameter | Description |
| --- | --- |
| startIndex | The zero-based index of the first message to retrieve. If startIndex is greater than or equal to the total number of items, an ArgumentOutOfRangeException is thrown. |
| count | The maximum number of messages to retrieve. If set to -1, all messages from the start index will be read. |

---

## EnumerateMessages (3 of 6) {#enumeratemessages_3}

Exposes the enumerator, which supports an iteration of messages in storage.

**Returns:** System::Collections::Generic::IEnumerable<T> , that represents an enumerator that iterates through a messages in storage.

```cpp
EnumerateMessages(System::SharedPtr < EmlLoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| options | Specifies EmlLoadOptions when reading message from Mbox storage. |

---

## EnumerateMessages (4 of 6) {#enumeratemessages_4}

Enumerates a specified number of mail messages, starting from the given index, using the provided load options.

**Returns:** An enumerable collection of MailMessage instances starting from the specified index. The collection may be empty if there are no messages in the specified range.

```cpp
EnumerateMessages(System::SharedPtr < EmlLoadOptions > options, int32_t startIndex, int32_t count)
```

| Parameter | Description |
| --- | --- |
| options | The EmlLoadOptions specifying how EML files should be loaded. |
| startIndex | The zero-based index of the first message to retrieve. If startIndex is greater than or equal to the total number of items, an ArgumentOutOfRangeException is thrown. |
| count | The maximum number of messages to retrieve. If set to -1, all messages from the start index will be read. |

---

## EnumerateMessages (5 of 6) {#enumeratemessages_5}

Enumerates the mail messages that match the specified query, using the provided load options.

**Returns:** An enumerable collection of MailMessage instances that match the specified query. The collection may be empty if no messages match.

```cpp
EnumerateMessages(System::SharedPtr < EmlLoadOptions > options, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| options | The EmlLoadOptions specifying how EML should be read. |
| query | The MailQuery used to filter messages. |

---

## EnumerateMessages (6 of 6) {#enumeratemessages_6}

Enumerates the mail messages that match the specified query.

**Returns:** An enumerable collection of MailMessage instances that match the specified query. The collection may be empty if no messages match.

```cpp
EnumerateMessages(System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| query | The MailQuery used to filter messages. |

