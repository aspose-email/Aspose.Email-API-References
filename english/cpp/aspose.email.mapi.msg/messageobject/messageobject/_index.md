---
title: "Aspose::Email::Mapi::Msg::MessageObject::MessageObject constructor"
linktitle: "MessageObject"
articleTitle: "MessageObject"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the MessageObject class, used internally for embedded messages."
type: docs
weight: 10
url: /cpp/aspose.email.mapi.msg/messageobject/messageobject/
---

## MessageObject (1 of 3) {#messageobject_1}

Initializes a new instance of the MessageObject class, used internally for embedded messages.

**Returns:** Aspose::Email::Mapi::Msg::

```cpp
MessageObject(System::SharedPtr < MessageObjectPropertiesCollection > properties, System::SharedPtr < MessageObjectRecipientsCollection > recipients, System::SharedPtr < MessageObjectAttachmentsCollection > attachments)
```

| Parameter | Description |
| --- | --- |
| properties | The properties list. |
| recipients | The recipients list. |
| attachments | The attachments list. |

---

## MessageObject (2 of 3) {#messageobject_2}

Initializes a new instance of the MessageObject class.

**Returns:** Aspose::Email::Mapi::Msg::

```cpp
MessageObject(System::SharedPtr < System::IO::Stream > stream, MessageObjectLoadFormat loadFormat)
```

| Parameter | Description |
| --- | --- |
| stream | The stream to initialize this object from. |
| loadFormat | The source format message object is stored with. |

---

## MessageObject (3 of 3) {#messageobject_3}

Initializes a new instance of the MessageObject class.

**Returns:** Aspose::Email::Mapi::Msg::

```cpp
MessageObject(System::String fileName, MessageObjectLoadFormat loadFormat)
```

| Parameter | Description |
| --- | --- |
| fileName | Name of the file to read from. |
| loadFormat | The source format message object is stored with. |

