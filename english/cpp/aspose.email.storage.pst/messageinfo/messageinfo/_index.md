---
title: "Aspose::Email::Storage::Pst::MessageInfo::MessageInfo constructor"
linktitle: "MessageInfo"
articleTitle: "MessageInfo"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the MessageInfo class."
type: docs
weight: 10
url: /cpp/aspose.email.storage.pst/messageinfo/messageinfo/
---

## MessageInfo (1 of 3) {#messageinfo_1}

Initializes a new instance of the MessageInfo class.

**Returns:** Aspose::Email::Storage::Pst::

```cpp
MessageInfo()
```

---

## MessageInfo (2 of 3) {#messageinfo_2}

Initializes a new instance of the MessageInfo class.

**Returns:** Aspose::Email::Storage::Pst::

```cpp
MessageInfo(System::SharedPtr < Ltp::Item > item, System::SharedPtr < Ndb::NodeId > parentNodeId, System::ArrayPtr< uint8_t > pstRecordKey, FileFormat format)
```

| Parameter | Description |
| --- | --- |
| item | The item. |
| parentNodeId | The parent node identifier. |
| pstRecordKey | The PST record key. |
| xmlQuery | The XML query. |

---

## MessageInfo (3 of 3) {#messageinfo_3}

Initializes a new instance of the MessageInfo class.

**Returns:** Aspose::Email::Storage::Pst::

```cpp
MessageInfo(System::SharedPtr < System::Collections::Generic::IEnumerator< System::SharedPtr < Ltp::PropertyInfo >>> enumerator, System::SharedPtr < Ndb::NodeId > msgNodeId, System::SharedPtr < Ndb::NodeId > parentNodeId, System::ArrayPtr< uint8_t > pstRecordKey, FileFormat format)
```

| Parameter | Description |
| --- | --- |
| enumerator | The enumerator. |
| msgNodeId | The MSG node identifier. |
| parentNodeId | The parent node identifier. |
| pstRecordKey | The PST record key. |

