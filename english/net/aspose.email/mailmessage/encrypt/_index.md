---
title: MailMessage.Encrypt
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Encrypts this message
type: docs
weight: 470
url: /net/aspose.email/mailmessage/encrypt/
---
## Encrypt(X509Certificate2) {#encrypt}

Encrypts this message

```csharp
public virtual MailMessage Encrypt(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | X509 certificate to encrypt message |

### Return Value

Encrypted email message

### Examples

The following example shows how to encrypt Messages.

```csharp
[C#]

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

```csharp
[VB.NET]

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

Encrypts this message

```csharp
public virtual MailMessage Encrypt(X509Certificate2[] certificates)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificates | X509Certificate2[] | Array with X509 certificates to encrypt message |

### Return Value

Encrypted email message

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


