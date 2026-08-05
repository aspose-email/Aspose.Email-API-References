---
title: "Aspose::Email::Clients::EmailClient::set_SupportedEncryption method"
linktitle: "set_SupportedEncryption"
articleTitle: "set_SupportedEncryption"
second_title: "Aspose.Email for C++"
description: "Defines the versions of SSL/TLS encryption protocols to be used."
type: docs
weight: 560
url: /cpp/aspose.email.clients/emailclient/set_supportedencryption/
---

## set_SupportedEncryption {#set_supportedencryption}

Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF .NET FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see EncryptionProtocols documentation for more details. Please use SetSupportedEncryptionUnsafe method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls | Tls11 | Tls12 | Tls13 (in case if your current version of .net framework supports these versions of TLS)

**Returns:** virtual void Aspose::Email::Clients::

```cpp
set_SupportedEncryption(Base::EncryptionProtocols value)
```

| Parameter | Description |
| --- | --- |
| value |  |

