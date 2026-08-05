---
title: "Aspose::Email::Clients::Graph::IGraphClient::CreateOrUpdateOverride method"
linktitle: "CreateOrUpdateOverride"
articleTitle: "CreateOrUpdateOverride"
second_title: "Aspose.Email for C++"
description: "Create an override for a sender identified by an SMTP address."
type: docs
weight: 110
url: /cpp/aspose.email.clients.graph/igraphclient/createorupdateoverride/
---

## CreateOrUpdateOverride (1 of 2) {#createorupdateoverride_1}

Create an override for a sender identified by an SMTP address. Future messages from that SMTP address will be consistently classified as specified in the override. Note:

**Returns:** virtual System::SharedPtr < ClassificationOverride > Aspose::Email::Clients::Graph::

```cpp
CreateOrUpdateOverride(System::SharedPtr < ClassificationOverride > classificationOverride)
```

| Parameter | Description |
| --- | --- |
| classificationOverride |  |

---

## CreateOrUpdateOverride (2 of 2) {#createorupdateoverride_2}

Create an override for a sender identified by an SMTP address. Future messages from that SMTP address will be consistently classified as specified in the override. Note:

**Returns:** virtual System::SharedPtr < ClassificationOverride > Aspose::Email::Clients::Graph::

```cpp
CreateOrUpdateOverride(System::SharedPtr < MailAddress > sender, ClassificationType classifyAs)
```

| Parameter | Description |
| --- | --- |
| sender | Email address information of the sender for whom the override is created. |
| classifyAs | Value which specifies how incoming messages from a specific sender should always be classified as. |

