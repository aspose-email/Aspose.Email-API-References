---
title: "Aspose::Email::Storage::MailboxConverter::ConvertPersonalStorageToMbox method"
linktitle: "ConvertPersonalStorageToMbox"
articleTitle: "ConvertPersonalStorageToMbox"
second_title: "Aspose.Email for C++"
description: "Converts the PersonalStorage to mbox format using given MboxStorageWriter ."
type: docs
weight: 10
url: /cpp/aspose.email.storage/mailboxconverter/convertpersonalstoragetombox/
---

## ConvertPersonalStorageToMbox (1 of 2) {#convertpersonalstoragetombox_1}

Converts the PersonalStorage to mbox format using given MboxStorageWriter .

**Returns:** static void Aspose::Email::Storage::

```cpp
ConvertPersonalStorageToMbox(System::SharedPtr < Pst::PersonalStorage > personalStorage, System::SharedPtr < Mbox::MboxStorageWriter > mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback)
```

| Parameter | Description |
| --- | --- |
| personalStorage | The personal storage. |
| mboxStorageWriter | The mbox storage writer. |
| acceptanceCallback | The acceptance callback, can be null. |

---

## ConvertPersonalStorageToMbox (2 of 2) {#convertpersonalstoragetombox_2}

Converts the PersonalStorage to mbox format using given path.

**Returns:** static void Aspose::Email::Storage::

```cpp
ConvertPersonalStorageToMbox(System::SharedPtr < Pst::PersonalStorage > personalStorage, System::String storagePath, MessageAcceptanceCallback acceptanceCallback)
```

| Parameter | Description |
| --- | --- |
| personalStorage | The personal storage. |
| storagePath | The path to save personalStorage structure to. |
| acceptanceCallback | The acceptance callback, can be null. |

