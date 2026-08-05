---
title: "Aspose::Email::MailMessage::LoadInternal method"
linktitle: "LoadInternal"
articleTitle: "LoadInternal"
second_title: "Aspose.Email for C++"
description: "Load message from stream."
type: docs
weight: 700
url: /cpp/aspose.email/mailmessage/loadinternal/
---

## LoadInternal (1 of 2) {#loadinternal_1}

Load message from stream. NOTE!!! Call this method if you don't need to increase customer consumption credit for Dynabic.Metered.

**Returns:** E-mail message

```cpp
LoadInternal(System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| stream | Stream that represents message in eml or msg format |

---

## LoadInternal (2 of 2) {#loadinternal_2}

Load message from stream with additional options. NOTE!!! Call this method if you don't need to increase customer consumption credit for Dynabic.Metered.

**Returns:** Mail message MailMessage .

```cpp
LoadInternal(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < LoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| stream | Source stream System::IO::Stream . |
| options | Additional options LoadOptions . |

