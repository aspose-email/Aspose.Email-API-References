---
title: "Aspose::Email::Storage::Mbox::MboxoStorageReader::ReadNextMessage method"
linktitle: "ReadNextMessage"
articleTitle: "ReadNextMessage"
second_title: "Aspose.Email for C++"
description: "Reads the next message from underlying storage stream."
type: docs
weight: 30
url: /cpp/aspose.email.storage.mbox/mboxostoragereader/readnextmessage/
---

## ReadNextMessage (1 of 5) {#readnextmessage_1}

Reads the next message from underlying storage stream.

**Returns:** A MailMessage object if it can be read or null if no more messages are available.

```cpp
ReadNextMessage()
```

---

## ReadNextMessage (2 of 5) {#readnextmessage_2}

Reads the next message from underlying storage stream.

**Returns:** A MailMessage object if it can be read or null if no more messages are available.

```cpp
ReadNextMessage(System::SharedPtr < EmlLoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| options | Specifies EmlLoadOptions when reading message from Mbox storage. |

---

## ReadNextMessage (3 of 5) {#readnextmessage_3}

Implements Aspose::Email::Storage::Mbox::MboxStorageReader .

**Returns:** System::SharedPtr < MailMessage > Aspose::Email::Storage::Mbox::

```cpp
ReadNextMessage(System::SharedPtr < EmlLoadOptions > options, int32_t count)
```

| Parameter | Description |
| --- | --- |
| options |  |
| count |  |

---

## ReadNextMessage (4 of 5) {#readnextmessage_4}

Reads the next message from underlying storage stream.

**Returns:** A MailMessage object if it can be read or null if no more messages are available.

```cpp
ReadNextMessage(System::String & fromMarker)
```

| Parameter | Description |
| --- | --- |
| fromMarker | Gets the From Marker while parsing the MBox Storage file. |

---

## ReadNextMessage (5 of 5) {#readnextmessage_5}

Reads the next message from underlying storage stream.

**Returns:** A MailMessage object if it can be read or null if no more messages are available.

```cpp
ReadNextMessage(System::String & fromMarker, System::SharedPtr < EmlLoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| fromMarker | Gets the From Marker while parsing the MBox Storage file. |
| options | Specifies EmlLoadOptions when reading message from Mbox storage. |

