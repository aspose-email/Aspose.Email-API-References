---
title: "Aspose::Email::HeaderType::get_ApparentlyTo method"
linktitle: "get_ApparentlyTo"
articleTitle: "get_ApparentlyTo"
second_title: "Aspose.Email for C++"
description: "Inserted by sending e-mail when there is no \"To:\" recipient in the original message."
type: docs
weight: 20
url: /cpp/aspose.email/headertype/get_apparentlyto/
---

## get_ApparentlyTo {#get_apparentlyto}

Inserted by sending e-mail when there is no "To:" recipient in the original message. This causes the recipients derived from the envelope to be listed in the message heading. This behavior is not quite proper, MTAs should not modify headers (except inserting Received lines), and it can in some cases cause Bcc recipients to be wrongly divulged to non-Bcc recipients. Example: Apparently-To: someo .nosp@m. ne@s .nosp@m. omedo .nosp@m. main .nosp@m. .com

**Returns:** static System::SharedPtr < HeaderType > Aspose::Email::

```cpp
get_ApparentlyTo()
```

