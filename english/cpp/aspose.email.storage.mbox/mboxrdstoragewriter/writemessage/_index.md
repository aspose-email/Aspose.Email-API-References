---
title: "Aspose::Email::Storage::Mbox::MboxrdStorageWriter::WriteMessage method"
linktitle: "WriteMessage"
articleTitle: "WriteMessage"
second_title: "Aspose.Email for C++"
description: "Writes the message to underlying storage stream."
type: docs
weight: 10
url: /cpp/aspose.email.storage.mbox/mboxrdstoragewriter/writemessage/
---

## WriteMessage (1 of 2) {#writemessage_1}

Writes the message to underlying storage stream.

**Returns:** The string identifier of added message.

```cpp
WriteMessage(System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| message | The message to write to. |

---

## WriteMessage (2 of 2) {#writemessage_2}

Writes the message to underlying storage stream.

**Returns:** The string identifier of added message.

```cpp
WriteMessage(System::SharedPtr < MailMessage > message, System::String & fromMarker)
```

| Parameter | Description |
| --- | --- |
| message | The message to write to. |
| fromMarker | Gets the From Marker while writing the MBox Storage file. |

