---
title: "Aspose::Email::Mapi::MapiMessage::FromMailMessage method"
linktitle: "FromMailMessage"
articleTitle: "FromMailMessage"
second_title: "Aspose.Email for C++"
description: "Creates an instance of MapiMessage from the MailMessage ."
type: docs
weight: 100
url: /cpp/aspose.email.mapi/mapimessage/frommailmessage/
---

## FromMailMessage (1 of 4) {#frommailmessage_1}

Creates an instance of MapiMessage from the MailMessage .

**Returns:** Returns a MapiMessage instance which is loaded from the MailMessage .

```cpp
FromMailMessage(System::SharedPtr < MailMessage > message)
```

| Parameter | Description |
| --- | --- |
| message | The MailMessage . |

---

## FromMailMessage (2 of 4) {#frommailmessage_2}

Creates an instance of MapiMessage from the MailMessage .

**Returns:** MapiMessage that represents Outlook message.

```cpp
FromMailMessage(System::SharedPtr < MailMessage > message, System::SharedPtr < MapiConversionOptions > options)
```

| Parameter | Description |
| --- | --- |
| message | The MailMessage . |
| options | MapiFromMailMessageOptions MapiConversionOptions |

---

## FromMailMessage (3 of 4) {#frommailmessage_3}

Creates an instance of MapiMessage from the EML format data stream.

**Returns:** Returns a MapiMessage instance which is loaded from the EML format data stream.

```cpp
FromMailMessage(System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| stream | The stream of data that represents an EML file. |

---

## FromMailMessage (4 of 4) {#frommailmessage_4}

Creates an instance of MapiMessage from the MailMessage .

**Returns:** Returns a MapiMessage instance which is loaded from the MailMessage .

```cpp
FromMailMessage(System::String fileName)
```

| Parameter | Description |
| --- | --- |
| fileName | The file name of MailMessage . |

