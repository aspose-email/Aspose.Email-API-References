---
title: MailMessage.AttachSignature
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Creates a signed message. Creates a readonly copy of the specified MailMessage and adds a digital signature to it
type: docs
weight: 400
url: /net/aspose.email/mailmessage/attachsignature/
---
## AttachSignature(X509Certificate2, bool) {#attachsignature_3}

Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

```csharp
public virtual MailMessage AttachSignature(X509Certificate2 certificate, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | X.509 certificate. |
| detached | Boolean | .If detached is true, the signature is detached.If detached is false(the default), the signature is not detached. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## AttachSignature(CmsSigner, bool) {#attachsignature_1}

Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

```csharp
public virtual MailMessage AttachSignature(CmsSigner signer, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signer | CmsSigner | System.Security.Cryptography.Pkcs.CmsSigner. |
| detached | Boolean | .If detached is true, the signature is detached.If detached is false(the default), the signature is not detached. |

### Return Value

The signed MailMessage.

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## AttachSignature(X509Certificate2) {#attachsignature_2}

Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

```csharp
public virtual MailMessage AttachSignature(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | X.509 certificate. |

### Return Value

The signed MailMessage.

### Examples

The following example shows how to attach a Certificate with AttachSignature Method.

```csharp
[C#]
       var privateCertFile = "MartinCertificate.pfx";
       var privateCert = new X509Certificate2(privateCertFile, "anothertestaccount");
       var msg = new MailMessage("user@domain.com", "receiver@domain.com", "subject:Signed message only by AE", "body:Test Body of signed message by AE");
       var signed = msg.AttachSignature(privateCert, true);
```

```csharp
[VB.NET]
       Dim privateCertFile = "MartinCertificate.pfx"
       Dim privateCert = New X509Certificate2(privateCertFile, "anothertestaccount")
       Dim msg = New MailMessage("user@domain.com", "receiver@domain.com", "subject:Signed message only by AE", "body:Test Body of signed message by AE")
       Dim signed = msg.AttachSignature(privateCert, True)
```

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## AttachSignature(CmsSigner) {#attachsignature}

Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

```csharp
public virtual MailMessage AttachSignature(CmsSigner signer)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signer | CmsSigner | System.Security.Cryptography.Pkcs.CmsSigner. |

### Return Value

The signed MailMessage.

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


