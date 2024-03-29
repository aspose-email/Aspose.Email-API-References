---
title: MailMessage.DKIMSign
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Signs this message using DKIM DomainKeys Identified Mail signature
type: docs
weight: 460
url: /net/aspose.email/mailmessage/dkimsign/
---
## MailMessage.DKIMSign method

Signs this message using DKIM (DomainKeys Identified Mail) signature.

```csharp
public virtual MailMessage DKIMSign(RSACryptoServiceProvider rsa, DKIMSignatureInfo signatureInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rsa | RSACryptoServiceProvider | RSA class containing private key used for signing. |
| signatureInfo | DKIMSignatureInfo | DKIM signature information. |

## Examples

The following example shows how to sign Emails with DKIM.

[C#]

```csharp
string privateKeyFile = "key2.pem";

var rsa = PemReader.GetPrivateKey(privateKeyFile);
var signInfo = new DKIMSignatureInfo("test", "some_email.com");
signInfo.Headers.Add("From");
signInfo.Headers.Add("Subject");

var mailMessage = new MailMessage("useremail@gmail.com", "test@gmail.com")
{
    Subject = "Signed DKIM message text body",
    Body = "This is a text body signed DKIM message"
};

var signedMsg = mailMessage.DKIMSign(rsa, signInfo);
```

[Visual Basic]

```csharp
Dim privateKeyFile As String = "key2.pem"

Dim rsa = PemReader.GetPrivateKey(privateKeyFile)
Dim signInfo = New DKIMSignatureInfo("test", "some_email.com")
signInfo.Headers.Add("From")
signInfo.Headers.Add("Subject")

Dim mailMessage = New MailMessage("useremail@gmail.com", "test@gmail.com") With {
    .Subject = "Signed DKIM message text body",
    .Body = "This is a text body signed DKIM message"
}

Dim signedMsg = mailMessage.DKIMSign(rsa, signInfo)
```

### See Also

* class [DKIMSignatureInfo](../../../aspose.email.dkim/dkimsignatureinfo/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


