---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::UpdateNote method"
linktitle: "UpdateNote"
articleTitle: "UpdateNote"
second_title: "Aspose.Email for C++"
description: "Updates the specified note."
type: docs
weight: 1560
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/updatenote/
---

## UpdateNote (1 of 3) {#updatenote_1}

Updates the specified note.

**Returns:** Note uri.

```cpp
UpdateNote(System::SharedPtr < Mapi::MapiNote > note)
```

| Parameter | Description |
| --- | --- |
| note | An MapiNote containing the note information. |

---

## UpdateNote (2 of 3) {#updatenote_2}

Updates the specified note.

**Returns:** Note uri.

```cpp
UpdateNote(System::String uri, System::SharedPtr < Mapi::MapiNote > note)
```

| Parameter | Description |
| --- | --- |
| uri | Note identifier |
| note | An MapiNote containing the note information. |

---

## UpdateNote (3 of 3) {#updatenote_3}

Updates the specified note.

**Returns:** Note uri.

```cpp
UpdateNote(System::String uri, System::SharedPtr < Mapi::MapiNote > note, System::SharedPtr < System::Collections::Generic::IEnumerable< System::SharedPtr < Mapi::PropertyDescriptor >>> additionalProperties)
```

| Parameter | Description |
| --- | --- |
| uri | Note identifier |
| note | An MapiNote containing the note information. |
| additionalProperties | An additional MAPI properties which can be used in MAPI object. |

