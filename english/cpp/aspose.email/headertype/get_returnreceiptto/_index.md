---
title: "Aspose::Email::HeaderType::get_ReturnReceiptTo method"
linktitle: "get_ReturnReceiptTo"
articleTitle: "get_ReturnReceiptTo"
second_title: "Aspose.Email for C++"
description: "A sender can request a return-receipt by including this header field."
type: docs
weight: 220
url: /cpp/aspose.email/headertype/get_returnreceiptto/
---

## get_ReturnReceiptTo {#get_returnreceiptto}

A sender can request a return-receipt by including this header field. The return-receipt is sent to the Return-Path address of the email and not to the address specified in the Return-Receipt-To header field. This header is non-standard and mostly not supported. Use Disposition-Notification-To instead. Even if supported, there is no guarantee of a receipt being sent.

**Returns:** static System::SharedPtr < HeaderType > Aspose::Email::

```cpp
get_ReturnReceiptTo()
```

