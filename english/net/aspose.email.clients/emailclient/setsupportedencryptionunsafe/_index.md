---
title: EmailClient.SetSupportedEncryptionUnsafe
second_title: Aspose.Email for .NET API Reference
description: EmailClient method. Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use SupportedEncryption property to safely set only protocols that definitely supported by .net framework. Please note if your current .net framework does not support this level of security an exception will be thrown when trying to establish a connection to the server
type: docs
weight: 330
url: /net/aspose.email.clients/emailclient/setsupportedencryptionunsafe/
---
## EmailClient.SetSupportedEncryptionUnsafe method

Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use [`SupportedEncryption`](../supportedencryption/) property to safely set only protocols that definitely supported by .net framework. Please note, if your current .net framework does not support this level of security, an exception will be thrown when trying to establish a connection to the server.

```csharp
public void SetSupportedEncryptionUnsafe(EncryptionProtocols value)
```

### See Also

* enum [EncryptionProtocols](../../../aspose.email.clients.base/encryptionprotocols/)
* class [EmailClient](../)
* namespace [Aspose.Email.Clients](../../emailclient/)
* assembly [Aspose.Email](../../../)


