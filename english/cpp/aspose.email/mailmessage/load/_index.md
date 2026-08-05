---
title: "Aspose::Email::MailMessage::Load method"
linktitle: "Load"
articleTitle: "Load"
second_title: "Aspose.Email for C++"
description: "Load message from stream"
type: docs
weight: 690
url: /cpp/aspose.email/mailmessage/load/
---

## Load (1 of 4) {#load_1}

Load message from stream

**Returns:** E-mail message

```cpp
Load(System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| stream | Stream that represents message in eml or msg format |

---

## Load (2 of 4) {#load_2}

Load message from stream with additional options.

**Returns:** Mail message MailMessage .

```cpp
Load(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < LoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| stream | Source stream System::IO::Stream . |
| options | Additional options LoadOptions . |

---

## Load (3 of 4) {#load_3}

Load message from file

**Returns:** E-mail message

```cpp
Load(System::String fileName)
```

| Parameter | Description |
| --- | --- |
| fileName | Message file name. The message file must be in eml or msg format. |

---

## Load (4 of 4) {#load_4}

Load message from file with additional options.

**Returns:** Mail message MailMessage .

```cpp
Load(System::String fileName, System::SharedPtr < LoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| fileName | Source file path System::String . |
| options | Additional options LoadOptions . |

