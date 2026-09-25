---
title: Class DKIMSignatureInfo
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.DKIM.DKIMSignatureInfo class. Describes how a message is signed with DKIM and what goes into the DKIMSignature header
type: docs
weight: 17380
url: /net/aspose.email.dkim/dkimsignatureinfo/
---
## DKIMSignatureInfo class

Describes how a message is signed with DKIM and what goes into the DKIM-Signature header.

```csharp
public class DKIMSignatureInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [DKIMSignatureInfo](dkimsignatureinfo/)(string, string) | Initializes a new instance of the `DKIMSignatureInfo` class with the DNS selector and domain of the public key. |

## Properties

| Name | Description |
| --- | --- |
| [BodyCanonicalization](../../aspose.email.dkim/dkimsignatureinfo/bodycanonicalization/) { get; set; } | Gets or sets how the message body is normalized before it is hashed (the body half of the c= tag). Default is `Relaxed`. |
| [Domain](../../aspose.email.dkim/dkimsignatureinfo/domain/) { get; set; } | Gets or sets the domain whose DNS TXT records publish the public key (the d= tag). |
| [HashAlgorithm](../../aspose.email.dkim/dkimsignatureinfo/hashalgorithm/) { get; set; } | Gets or sets the algorithm used to hash the signed headers and body (the a= tag). Default is `RSASha1`. |
| [HeaderCanonicalization](../../aspose.email.dkim/dkimsignatureinfo/headercanonicalization/) { get; set; } | Gets or sets how the signed headers are normalized before they are hashed (the header half of the c= tag). Default is `Relaxed`. |
| [Headers](../../aspose.email.dkim/dkimsignatureinfo/headers/) { get; } | Gets the names of the headers to include in the signature (the h= tag). Add at least From, otherwise the signature is not valid. |
| [Selector](../../aspose.email.dkim/dkimsignatureinfo/selector/) { get; set; } | Gets or sets the selector that tells verifiers which public key of the domain to use (the s= tag). |
| [Time](../../aspose.email.dkim/dkimsignatureinfo/time/) { get; set; } | Gets or sets the signature timestamp - the time that this signature was created (t=). Default (null) is an unknown creation time. |

## Remarks

Set the DNS selector and domain of the published public key, list the headers to sign in `Headers`, then pass the instance to `MailMessage.DKIMSign` together with the private key loaded by `PemReader`.

### See Also

* namespace [Aspose.Email.DKIM](../../aspose.email.dkim/)
* assembly [Aspose.Email](../../)


