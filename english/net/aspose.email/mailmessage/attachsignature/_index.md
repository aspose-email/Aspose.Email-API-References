---
title: MailMessage.AttachSignature
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Creates a signed copy of the message S/MIME. The copy is readonly
type: docs
weight: 400
url: /net/aspose.email/mailmessage/attachsignature/
---
## AttachSignature(X509Certificate2, bool) {#attachsignature_3}

Creates a signed copy of the message (S/MIME). The copy is read-only.

```csharp
public virtual MailMessage AttachSignature(X509Certificate2 certificate, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | The certificate, with its private key, to sign with. |
| detached | Boolean | `true` to create a detached signature (`multipart/signed`), which clients that do not support S/MIME can still read; `false` (the default) to embed the message in the signature. |

### Return Value

A signed, read-only copy of the message.

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## AttachSignature(CmsSigner, bool) {#attachsignature_1}

Creates a signed copy of the message (S/MIME). The copy is read-only.

```csharp
public virtual MailMessage AttachSignature(CmsSigner signer, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signer | CmsSigner | The signer, with its certificate and options. |
| detached | Boolean | `true` to create a detached signature (`multipart/signed`), which clients that do not support S/MIME can still read; `false` (the default) to embed the message in the signature. |

### Return Value

A signed, read-only copy of the message.

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## AttachSignature(X509Certificate2) {#attachsignature_2}

Creates a signed copy of the message (S/MIME). The copy is read-only.

```csharp
public virtual MailMessage AttachSignature(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | The certificate, with its private key, to sign with. |

### Return Value

A signed, read-only copy of the message.

## Examples

The following example shows how to attach a Certificate with AttachSignature Method.

[C#]

```csharp
var privateCertFile = "MartinCertificate.pfx";
var privateCert = new X509Certificate2(privateCertFile, "anothertestaccount");
var msg = new MailMessage("user@domain.com", "receiver@domain.com", "subject:Signed message only by AE", "body:Test Body of signed message by AE");
var signed = msg.AttachSignature(privateCert, true);
```

[Visual Basic]

```csharp
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

Creates a signed copy of the message (S/MIME). The copy is read-only.

```csharp
public virtual MailMessage AttachSignature(CmsSigner signer)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signer | CmsSigner | The signer, with its certificate and options. |

### Return Value

A signed, read-only copy of the message.

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


