---
title: "Aspose::Email::Clients::EmailClient::SetSupportedEncryptionUnsafe method"
linktitle: "SetSupportedEncryptionUnsafe"
articleTitle: "SetSupportedEncryptionUnsafe"
second_title: "Aspose.Email for C++"
description: "Defines the versions of SSL/TLS encryption protocols to be used."
type: docs
weight: 660
url: /cpp/aspose.email.clients/emailclient/setsupportedencryptionunsafe/
---

## SetSupportedEncryptionUnsafe {#setsupportedencryptionunsafe}

Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use SupportedEncryption property to safely set only protocols that definitely supported by .net framework. Please note, if your current .net framework does not support this level of security, an exception will be thrown when trying to establish a connection to the server.

**Returns:** void Aspose::Email::Clients::

```cpp
SetSupportedEncryptionUnsafe(Base::EncryptionProtocols value)
```

| Parameter | Description |
| --- | --- |
| value |  |

