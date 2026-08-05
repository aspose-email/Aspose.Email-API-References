---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::MarkAllItems method"
linktitle: "MarkAllItems"
articleTitle: "MarkAllItems"
second_title: "Aspose.Email for C++"
description: "Marks all items in specified folders."
type: docs
weight: 1110
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/markallitems/
---

## MarkAllItems (1 of 3) {#markallitems_1}

Marks all items in specified folders.

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
MarkAllItems(bool read, bool suppressReadReceipts, const System::ArrayPtr< System::String > & folderIds)
```

| Parameter | Description |
| --- | --- |
| read | Sets the read/unread state to messages in specified folder. True to mark messages in the folder as read. False to mark messages as unread. |
| suppressReadReceipts | True to suppress sending read receipts for messages; otherwise, false. |
| folderIds | List of folder uri for processing. |

---

## MarkAllItems (2 of 3) {#markallitems_2}

Marks all items in specified folders.

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
MarkAllItems(bool read, bool suppressReadReceipts, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> folderIds)
```

| Parameter | Description |
| --- | --- |
| read | Sets the read/unread state to messages in specified folder. True to mark messages in the folder as read. False to mark messages as unread. |
| suppressReadReceipts | True to suppress sending read receipts for messages; otherwise, false. |
| folderIds | List of folder uri for processing. |

---

## MarkAllItems (3 of 3) {#markallitems_3}

Marks all items in specified folders.

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
MarkAllItems(bool read, const System::ArrayPtr< System::String > & folderIds)
```

| Parameter | Description |
| --- | --- |
| read | Sets the read/unread state to messages in specified folder. True to mark messages in the folder as read. False to mark messages as unread. |
| folderIds | List of folder uri for processing. |

