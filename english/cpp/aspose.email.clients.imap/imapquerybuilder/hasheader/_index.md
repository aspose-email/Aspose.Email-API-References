---
title: "Aspose::Email::Clients::Imap::ImapQueryBuilder::HasHeader method"
linktitle: "HasHeader"
articleTitle: "HasHeader"
second_title: "Aspose.Email for C++"
description: "Search messages that have a header with the specified field-name and that contains the specified string in the text of the header (what comes after the colon)."
type: docs
weight: 70
url: /cpp/aspose.email.clients.imap/imapquerybuilder/hasheader/
---

## HasHeader {#hasheader}

Search messages that have a header with the specified field-name and that contains the specified string in the text of the header (what comes after the colon). If the string to search is zero-length, this matches all messages that have a header line with the specified field-name regardless of the contents.

**Returns:** MailQuery that represents search query (one searching criteria).

```cpp
HasHeader(System::String fieldName, System::String fieldValue)
```

| Parameter | Description |
| --- | --- |
| fieldName | Name of the field. |
| fieldValue | The field value. |

