---
title: "Aspose::Email::Metered::SetMeteredKey method"
linktitle: "SetMeteredKey"
articleTitle: "SetMeteredKey"
second_title: "Aspose.Email for C++"
description: "Sets metered public and private key."
type: docs
weight: 90
url: /cpp/aspose.email/metered/setmeteredkey/
---

## SetMeteredKey {#setmeteredkey}

Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again.

**Returns:** void Aspose::Email::

```cpp
SetMeteredKey(System::String publicKey, System::String privateKey)
```

| Parameter | Description |
| --- | --- |
| publicKey | public key |
| privateKey | private key |

