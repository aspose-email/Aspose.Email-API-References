---
title: "Aspose::Email::HeaderType::get_From method"
linktitle: "get_From"
articleTitle: "get_From"
second_title: "Aspose.Email for C++"
description: "This field contains the identity of the person(s) who wished this message to be sent."
type: docs
weight: 120
url: /cpp/aspose.email/headertype/get_from/
---

## get_From {#get_from}

This field contains the identity of the person(s) who wished this message to be sent. The message-creation process should default this field to be a single, authenticated machine address, indicating the AGENT (person, system or process) composing the message. If this is not done, the "Sender:" field MUST be present. If the "From:" field IS defaulted this way, the "Sender:" field is optional and is redundant with the "From:" field.

**Returns:** static System::SharedPtr < HeaderType > Aspose::Email::

```cpp
get_From()
```

