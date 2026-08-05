---
title: "Aspose::Email::Clients::Imap::ImapPageInfo::ImapPageInfo constructor"
linktitle: "ImapPageInfo"
articleTitle: "ImapPageInfo"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the ImapPageInfo class"
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/imappageinfo/imappageinfo/
---

## ImapPageInfo (1 of 2) {#imappageinfo_1}

Initializes a new instance of the ImapPageInfo class

**Returns:** Aspose::Email::Clients::Imap::

```cpp
ImapPageInfo(int32_t totalCount, int32_t itemsPerPage, int32_t offset, bool lastPage, System::SharedPtr < System::Collections::Generic::ListExt< int64_t >> searchedSeqNums)
```

| Parameter | Description |
| --- | --- |
| totalCount | Total count of items in view |
| itemsPerPage | A number of items in page |
| offset | offset in view of a page |
| lastPage | Indicates whether current page is last page in view |
| searchedSeqNums | A searched items collection |

---

## ImapPageInfo (2 of 2) {#imappageinfo_2}

Initializes a new instance of the ImapPageInfo class

**Returns:** Aspose::Email::Clients::Imap::

```cpp
ImapPageInfo(int32_t totalCount, int32_t itemsPerPage, int32_t offset, bool lastPage, System::SharedPtr < ImapMessageInfoCollection > items)
```

| Parameter | Description |
| --- | --- |
| totalCount | Total count of items in view |
| offset | offset in view of a page |
| lastPage | Indicates whether current page is last page in view |
| itemsPerPage | A number of items in page |
| items | A collection of ImapMessageInfo objects |

