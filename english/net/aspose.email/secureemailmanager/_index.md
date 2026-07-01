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
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature)(MailMessage, CmsSigner) | Creates a copy of the specified MailMessage and adds a digital signature to it. |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_2)(MailMessage, X509Certificate2) | Creates a copy of the specified MailMessage and adds a digital signature to it. |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_4)(MapiMessage, CmsSigner) | Creates a copy of the specified MapiMessage and adds a digital signature to it. |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_6)(MapiMessage, X509Certificate2) | Creates a copy of the specified MapiMessage and adds a digital signature to it. |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_1)(MailMessage, CmsSigner, SignatureOptions) | Creates a copy of the specified MailMessage and adds a digital signature to it. |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_3)(MailMessage, X509Certificate2, SignatureOptions) | Creates a copy of the specified MailMessage and adds a digital signature to it. |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_5)(MapiMessage, CmsSigner, SignatureOptions) | Creates a copy of the specified MapiMessage and adds a digital signature to it. |
| virtual [AttachSignature](../../aspose.email/secureemailmanager/attachsignature/#attachsignature_7)(MapiMessage, X509Certificate2, SignatureOptions) | Creates a copy of the specified MapiMessage and adds a digital signature to it. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature)(MailMessage) | Checking signature MailMessage. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature_3)(MapiMessage) | Checking signature MapiMessage. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature_1)(MailMessage, X509Certificate2) | Checking signature MailMessage. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature_4)(MapiMessage, X509Certificate2) | Checking signature MapiMessage. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature_2)(MailMessage, X509Certificate2, X509Store) | Checking signature MailMessage. |
| [CheckSignature](../../aspose.email/secureemailmanager/checksignature/#checksignature_5)(MapiMessage, X509Certificate2, X509Store) | Checking signature MapiMessage. |

## Remarks

Use [`CheckSignature`](./checksignature/) to verify digital signatures on [`MailMessage`](../mailmessage/) or [`MapiMessage`](../../aspose.email.mapi/mapimessage/) objects and retrieve signing/encryption certificates. Use [`AttachSignature`](./attachsignature/) methods to digitally sign messages using X.509 certificates or CmsSigner objects. Supports both attached (enveloped) and detached signature formats, as well as message encryption and decryption.

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


