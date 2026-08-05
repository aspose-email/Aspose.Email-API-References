---
title: "Aspose::Email::Storage::Pst::PersonalStorage::AddAttachmentToMessage method"
linktitle: "AddAttachmentToMessage"
articleTitle: "AddAttachmentToMessage"
second_title: "Aspose.Email for C++"
description: "Adds an attachment to the specified message using the file located at the provided path."
type: docs
weight: 10
url: /cpp/aspose.email.storage.pst/personalstorage/addattachmenttomessage/
---

## AddAttachmentToMessage (1 of 4) {#addattachmenttomessage_1}

Adds an attachment to the specified message using the file located at the provided path.

**Returns:** void Aspose::Email::Storage::Pst::

```cpp
AddAttachmentToMessage(System::SharedPtr < MessageInfo > messageInfo, System::String filePath)
```

| Parameter | Description |
| --- | --- |
| messageInfo | The MessageInfo object representing the target message. |
| filePath | The full path to the file to be added as an attachment. |

---

## AddAttachmentToMessage (2 of 4) {#addattachmenttomessage_2}

Adds an attachment to the specified message using the provided stream as attachment content.

**Returns:** void Aspose::Email::Storage::Pst::

```cpp
AddAttachmentToMessage(System::SharedPtr < MessageInfo > messageInfo, System::String name, System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| messageInfo | The MessageInfo object representing the target message. |
| name | The name of the attachment to add. |
| stream | The stream containing the attachment data. |

---

## AddAttachmentToMessage (3 of 4) {#addattachmenttomessage_3}

Adds an attachment to the message identified by the specified entry ID using the file located at the provided path.

**Returns:** void Aspose::Email::Storage::Pst::

```cpp
AddAttachmentToMessage(System::String entryId, System::String filePath)
```

| Parameter | Description |
| --- | --- |
| entryId | The entry ID of the target message. |
| filePath | The full path to the file to be added as an attachment. |

---

## AddAttachmentToMessage (4 of 4) {#addattachmenttomessage_4}

Adds an attachment to the message identified by the specified entry ID using the provided stream.

**Returns:** void Aspose::Email::Storage::Pst::

```cpp
AddAttachmentToMessage(System::String entryId, System::String name, System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| entryId | The entry ID of the target message. |
| name | The name of the attachment to add. |
| stream | The stream containing the attachment data. |

