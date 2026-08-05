---
title: "Aspose::Email::MailMessage::LoadMessageStructure method"
linktitle: "LoadMessageStructure"
articleTitle: "LoadMessageStructure"
second_title: "Aspose.Email for C++"
description: "Loads the message structure and search text body and html body parts' indexes"
type: docs
weight: 710
url: /cpp/aspose.email/mailmessage/loadmessagestructure/
---

## LoadMessageStructure {#loadmessagestructure}

Loads the message structure and search text body and html body parts' indexes

**Returns:** void Aspose::Email::

```cpp
LoadMessageStructure(System::SharedPtr < Clients::Imap::Commands::BodyStructureMultiPart > bodyStructure, System::SharedPtr < Clients::Imap::Commands::BodyStructurePart > & textBodyPart, System::SharedPtr < Clients::Imap::Commands::BodyStructurePart > & htmlBodyPart)
```

| Parameter | Description |
| --- | --- |
| bodyStructure | A BodyStructureMultiPart containing the message structure |
| textBodyPart | An index of found text body |
| htmlBodyPart | An index of found html body |

