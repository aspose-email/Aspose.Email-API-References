---
title: "Aspose::Email::Clients::Exchange::Dav::ExchangeClient::SaveMessage method"
linktitle: "SaveMessage"
articleTitle: "SaveMessage"
second_title: "Aspose.Email for C++"
description: "Saves the message."
type: docs
weight: 410
url: /cpp/aspose.email.clients.exchange.dav/exchangeclient/savemessage/
---

## SaveMessage (1 of 2) {#savemessage_1}

Saves the message.

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
SaveMessage(System::String messageUri, System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| messageUri | The message URI. |
| stream | The stream. |

---

## SaveMessage (2 of 2) {#savemessage_2}

Saves mail message specified by the uri to local file system. The mail message file is RFC 822 compliant format (EML).

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
SaveMessage(System::String messageUri, System::String path)
```

| Parameter | Description |
| --- | --- |
| messageUri | The Uri of the mail message |
| path | The target path to save the message |

