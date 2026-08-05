---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::MarkAsJunk method"
linktitle: "MarkAsJunk"
articleTitle: "MarkAsJunk"
second_title: "Aspose.Email for C++"
description: "The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender."
type: docs
weight: 1140
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/markasjunk/
---

## MarkAsJunk (1 of 5) {#markasjunk_1}

The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

**Returns:** Returns the array of message ID which are moved to the junk mail folder.

```cpp
MarkAsJunk(bool isJunk, bool moveItem, const System::ArrayPtr< System::String > & messageUriEn)
```

| Parameter | Description |
| --- | --- |
| isJunk | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| moveItem | Indicates, whether messages is moved to the junk mail folder. |
| messageUriEn | Array of message uri |

---

## MarkAsJunk (2 of 5) {#markasjunk_2}

The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

**Returns:** Returns the array of message ID which are moved to the junk mail folder.

```cpp
MarkAsJunk(bool isJunk, bool moveItem, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageUriEn)
```

| Parameter | Description |
| --- | --- |
| isJunk | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| moveItem | Indicates, whether messages is moved to the junk mail folder. |
| messageUriEn | Enumeration of message uri |

---

## MarkAsJunk (3 of 5) {#markasjunk_3}

The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
MarkAsJunk(bool isJunk, bool moveItem, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageUriEn, System::ArrayPtr< System::String > & movedMessageIds, System::ArrayPtr< System::String > & failedMessageIds, System::ArrayPtr< System::String > & errorMessages)
```

| Parameter | Description |
| --- | --- |
| isJunk | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| moveItem | Indicates, whether messages is moved to the junk mail folder. |
| messageUriEn | Enumeration of message uri |
| movedMessageIds | Returns the array of message ID which are moved to the junk mail folder. |
| failedMessageIds | Returns the array of message ID which haven't been moved to the junk mail folder. |
| errorMessages | Error messages for failed operations |

---

## MarkAsJunk (4 of 5) {#markasjunk_4}

The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

**Returns:** Returns the array of message ID which are moved to the junk mail folder.

```cpp
MarkAsJunk(bool isJunk, const System::ArrayPtr< System::String > & messageUriEn)
```

| Parameter | Description |
| --- | --- |
| isJunk | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| messageUriEn | Array of message uri |

---

## MarkAsJunk (5 of 5) {#markasjunk_5}

The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

**Returns:** Returns the item ID of the message marked as junk mail.

```cpp
MarkAsJunk(bool isJunk, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> messageUriEn)
```

| Parameter | Description |
| --- | --- |
| isJunk | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| messageUriEn | Enumeration of message uri |

