---
title: MailMessage.CheckSignature
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Checks the signature of the specified eml file
type: docs
weight: 600
url: /net/aspose.email/mailmessage/checksignature/
---
## CheckSignature(string) {#checksignature_1}

Checks the signature of the specified eml file.

```csharp
public static bool CheckSignature(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | A file name (eml). |

### Return Value

`True` if signature is valid; otherwise, `false`.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *fileName* is `null` or `empty`. |
| FileNotFoundException | The specified *fileName* doesn't exist. |
| NotSupportedException | Signature type is not supported. |
| InvalidOperationException | Mail message is not signed or signature type is not specified. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(Stream) {#checksignature}

Checks the signature of the specified eml message.

```csharp
public static bool CheckSignature(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream containing the message in eml format. |

### Return Value

`True` if signature is valid; otherwise, `false`.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | Signature type is not supported. |
| InvalidOperationException | Mail message is not signed or signature type is not specified. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature()

Checking signature exsisting MailMessage.

```csharp
public virtual X509Certificate2[] CheckSignature()
```

### Return Value

X.509 signers certificates

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Throws if Mail message is not signed or signature is not verified. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


