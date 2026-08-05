---
title: "Aspose::Email::HeaderType::get_DispositionNotificationTo method"
linktitle: "get_DispositionNotificationTo"
articleTitle: "get_DispositionNotificationTo"
second_title: "Aspose.Email for C++"
description: "When the DispositionNotificationTo field is set, a request for a MDN (Message Delivery Notification) is made."
type: docs
weight: 100
url: /cpp/aspose.email/headertype/get_dispositionnotificationto/
---

## get_DispositionNotificationTo {#get_dispositionnotificationto}

When the DispositionNotificationTo field is set, a request for a MDN (Message Delivery Notification) is made. The recipient's email software (Outlook, Eudora, etc.) may silently ignore the request, or it may prompt the user for permission to send the MDN. There is no guarantee of the "return-receipt". The DispositionNotificationTo field is the de facto standard for requesting return-receipts (i.e. MDN, or message delivery notifications).

**Returns:** static System::SharedPtr < HeaderType > Aspose::Email::

```cpp
get_DispositionNotificationTo()
```

