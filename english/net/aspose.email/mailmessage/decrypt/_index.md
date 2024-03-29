---
title: MailMessage.Decrypt
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Decrypts this message
type: docs
weight: 440
url: /net/aspose.email/mailmessage/decrypt/
---
## Decrypt() {#decrypt}

Decrypts this message

```csharp
public virtual MailMessage Decrypt()
```

### Return Value

Decrypted E-mail message

## Remarks

Method searches the current user and computer My stores for the appropriate certificate and private key.

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Decrypt(X509Certificate2) {#decrypt_1}

Decrypts this message

```csharp
public virtual MailMessage Decrypt(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | System.Security.Cryptography.X509Certificates.X509Certificate2 |

### Return Value

E-mail message

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


