---
title: "Aspose::Email::Clients::Exchange::Dav::ExchangeClient::MoveMessage method"
linktitle: "MoveMessage"
articleTitle: "MoveMessage"
second_title: "Aspose.Email for C++"
description: "Moves the message."
type: docs
weight: 360
url: /cpp/aspose.email.clients.exchange.dav/exchangeclient/movemessage/
---

## MoveMessage (1 of 4) {#movemessage_1}

Moves the message.

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
MoveMessage(System::SharedPtr < ExchangeMessageInfo > msgInfo, System::String destinationFolderUri)
```

| Parameter | Description |
| --- | --- |
| msgInfo | Represents the E-Mail message info fetched from the Exchange Store. |
| destinationFolderUri | An URI of a destination folder. |

---

## MoveMessage (2 of 4) {#movemessage_2}

Moves the message.

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
MoveMessage(System::SharedPtr < ExchangeMessageInfo > msgInfo, System::String destinationFolderUri, bool overwrite)
```

| Parameter | Description |
| --- | --- |
| msgInfo | Represents the E-Mail message info fetched from the Exchange Store. |
| destinationFolderUri | An URI of a destination folder. |
| overwrite | Specifies whether the server should overwrite a existing message while processing a MOVE operation. |

---

## MoveMessage (3 of 4) {#movemessage_3}

Moves the message.

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
MoveMessage(System::String destinationFolderUri, bool overwrite, System::String messageUri)
```

| Parameter | Description |
| --- | --- |
| destinationFolderUri | An URI of a destination folder. |
| overwrite | Specifies whether the server should overwrite a existing message while processing a MOVE operation. |
| messageUri | Represents the uri of E-Mail message. |

---

## MoveMessage (4 of 4) {#movemessage_4}

Moves the message.

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
MoveMessage(System::String destinationFolderUri, System::String messageUri)
```

| Parameter | Description |
| --- | --- |
| destinationFolderUri | An URI of a destination folder. |
| messageUri | Represents the uri of E-Mail message. |

