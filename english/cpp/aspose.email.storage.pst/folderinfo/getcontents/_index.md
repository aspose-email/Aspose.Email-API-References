---
title: "Aspose::Email::Storage::Pst::FolderInfo::GetContents method"
linktitle: "GetContents"
articleTitle: "GetContents"
second_title: "Aspose.Email for C++"
description: "Get collection of messages."
type: docs
weight: 290
url: /cpp/aspose.email.storage.pst/folderinfo/getcontents/
---

## GetContents (1 of 6) {#getcontents_1}

Get collection of messages.

**Returns:** Collection of MessageInfo .

```cpp
GetContents()
```

---

## GetContents (2 of 6) {#getcontents_2}

Get collection of messages.

**Returns:** Collection of MessageInfo .

```cpp
GetContents(bool tryToReadCorruptedContents)
```

| Parameter | Description |
| --- | --- |
| tryToReadCorruptedContents | If the value of this parameter is true, the method will try to read the content even if the file is corrupted. This value can be used if the GetContents() method throws an exception about the file corruption. If the value of this parameter is false, the method works in the same way as GetContents() method without parameters. |

---

## GetContents (3 of 6) {#getcontents_3}

Gets the collection of messages.

**Returns:** Collection of MessageInfo .

```cpp
GetContents(int32_t startIndex, int32_t count)
```

| Parameter | Description |
| --- | --- |
| startIndex | The start message index. |
| count | The number of messages that will be retrieved. |

---

## GetContents (4 of 6) {#getcontents_4}

Get collection of messages.

**Returns:** Collection of MessageInfo .

```cpp
GetContents(MessageKind kind)
```

| Parameter | Description |
| --- | --- |
| kind | The message kind. |

---

## GetContents (5 of 6) {#getcontents_5}

Get collection of messages.

**Returns:** Collection of MessageInfo .

```cpp
GetContents(System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents search query. |

---

## GetContents (6 of 6) {#getcontents_6}

Gets the collection of messages.

**Returns:** Collection of MessageInfo .

```cpp
GetContents(System::SharedPtr < Tools::Search::MailQuery > query, int32_t startIndex, int32_t count)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents search query. |
| startIndex | The start message index. |
| count | The number of messages that will be retrieved. |

