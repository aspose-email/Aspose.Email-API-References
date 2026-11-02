---
title: MailMessage.Encrypt
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Creates a copy of the message encrypted for one recipient S/MIME
type: docs
weight: 460
url: /net/aspose.email/mailmessage/encrypt/
---
## Encrypt(X509Certificate2) {#encrypt}

Creates a copy of the message encrypted for one recipient (S/MIME).

```csharp
public virtual MailMessage Encrypt(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | The certificate of the recipient. |

### Return Value

The encrypted message.

## Examples

The following example shows how to encrypt Messages

[C#]

```csharp
var publicCertFile = "MartinCertificate.cer";
var publicCert = new X509Certificate2(publicCertFile);

// Create a message
var eml = new MailMessage
{
    From = "atneostthaecrcount@gmail.com",
    To = "atneostthaecrcount@gmail.com",
    Subject = "Test subject",
    Body = "Test Body"
};

// Encrypt the message
var encryptedEml = eml.Encrypt(publicCert);
Console.WriteLine(encryptedEml.IsEncrypted ? "Its encrypted" : "Its NOT encrypted");
```

[Visual Basic]

```csharp
Dim publicCertFile = "MartinCertificate.cer"
    Dim publicCert = New X509Certificate2(publicCertFile)

' Create a message
    Dim eml = New MailMessage With {
        .From = "atneostthaecrcount@gmail.com",
        .[To] = "atneostthaecrcount@gmail.com",
        .Subject = "Test subject",
        .Body = "Test Body"
    }

' Encrypt the message
    Dim encryptedEml = eml.Encrypt(publicCert)
    Console.WriteLine(If(encryptedEml.IsEncrypted, "Its encrypted", "Its NOT encrypted"))
```

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Encrypt(X509Certificate2[]) {#encrypt_1}

Creates a copy of the message encrypted for several recipients (S/MIME).

```csharp
public virtual MailMessage Encrypt(X509Certificate2[] certificates)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificates | X509Certificate2[] | The certificates of the recipients. |

### Return Value

The encrypted message.

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


