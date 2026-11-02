---
title: Class SecureEmailManager
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.SecureEmailManager class. Provides methods for working with secure emails including S/MIME signing and encryption operations. This class enables digital signature verification message decryption and signing of email messages using X.509 certificates and PKCS7/CMS standards
type: docs
weight: 18820
url: /net/aspose.email/secureemailmanager/
---
## SecureEmailManager class

Provides methods for working with secure emails, including S/MIME signing and encryption operations. This class enables digital signature verification, message decryption, and signing of email messages using X.509 certificates and PKCS#7/CMS standards.

```csharp
public class SecureEmailManager
```

## Constructors

| Name | Description |
| --- | --- |
| [SecureEmailManager](secureemailmanager/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature)(MailMessage, CmsSigner) | Creates a signed copy of the message (S/MIME). |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_2)(MailMessage, X509Certificate2) | Creates a signed copy of the message (S/MIME). |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_4)(MapiMessage, CmsSigner) | Creates a signed copy of the message (S/MIME). |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_6)(MapiMessage, X509Certificate2) | Creates a signed copy of the message (S/MIME). |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_1)(MailMessage, CmsSigner, SignatureOptions) | Creates a signed copy of the message (S/MIME) with the specified options. |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_3)(MailMessage, X509Certificate2, SignatureOptions) | Creates a signed copy of the message (S/MIME) with the specified options. |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_5)(MapiMessage, CmsSigner, SignatureOptions) | Creates a signed copy of the message (S/MIME) with the specified options. |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_7)(MapiMessage, X509Certificate2, SignatureOptions) | Creates a signed copy of the message (S/MIME) with the specified options. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature)(MailMessage) | Verifies the signature of the message. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature_3)(MapiMessage) | Verifies the signature of the message. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature_1)(MailMessage, X509Certificate2) | Verifies the signature of the message, decrypting it first if needed. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature_4)(MapiMessage, X509Certificate2) | Verifies the signature of the message, decrypting it first if needed. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature_2)(MailMessage, X509Certificate2, X509Store) | Verifies the signature of the message, decrypting it first if needed. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature_5)(MapiMessage, X509Certificate2, X509Store) | Verifies the signature of the message, decrypting it first if needed. |

## Remarks

Use [`CheckSignature`](./checksignature/) to verify digital signatures on [`MailMessage`](../mailmessage/) or [`MapiMessage`](../../aspose.email.mapi/mapimessage/) objects and retrieve signing/encryption certificates. Use [`AttachSignature`](./attachsignature/) methods to digitally sign messages using X.509 certificates or CmsSigner objects. Supports both attached (enveloped) and detached signature formats, as well as message encryption and decryption.

## Examples

This example signs a message and verifies the signature.

[C#]

```csharp
var certificate = new X509Certificate2("signer.pfx", "password");
var manager = new SecureEmailManager();

var msg = new MailMessage("from@example.com", "to@example.com", "Signed message", "Hello");
MailMessage signed = manager.AttachSignature(msg, certificate, new SignatureOptions { Detached = true });
signed.Save("signed.eml");

SmimeResult result = manager.CheckSignature(MailMessage.Load("signed.eml"));
Console.WriteLine(result.IsSuccess ? "The signature is valid." : "The signature is not valid: " + result.Error);
```

[Visual Basic]

```csharp
Dim certificate = New X509Certificate2("signer.pfx", "password")
Dim manager = New SecureEmailManager()

Dim msg = New MailMessage("from@example.com", "to@example.com", "Signed message", "Hello")
Dim signed As MailMessage = manager.AttachSignature(msg, certificate, New SignatureOptions With {.Detached = True})
signed.Save("signed.eml")

Dim result As SmimeResult = manager.CheckSignature(MailMessage.Load("signed.eml"))
Console.WriteLine(If(result.IsSuccess, "The signature is valid.", "The signature is not valid: " & result.Error.ToString()))
```

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


