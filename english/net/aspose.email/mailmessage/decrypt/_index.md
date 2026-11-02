---
title: MailMessage.Decrypt
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Decrypts the message with a certificate found in the certificate store
type: docs
weight: 440
url: /net/aspose.email/mailmessage/decrypt/
---
## Decrypt() {#decrypt}

Decrypts the message with a certificate found in the certificate store.

```csharp
public virtual MailMessage Decrypt()
```

### Return Value

The decrypted message.

## Remarks

The certificate and its private key are searched for in the personal (My) stores of the current user and of the computer.

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Decrypt(X509Certificate2) {#decrypt_1}

Decrypts the message with the specified certificate.

```csharp
public virtual MailMessage Decrypt(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | The certificate, with its private key, to decrypt with. |

### Return Value

The decrypted message.

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


