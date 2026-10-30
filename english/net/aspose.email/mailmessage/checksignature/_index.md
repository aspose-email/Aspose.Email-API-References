---
title: MailMessage.CheckSignature
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Verifies the signature of a message in an EML file
type: docs
weight: 580
url: /net/aspose.email/mailmessage/checksignature/
---
## CheckSignature(string) {#checksignature_1}

Verifies the signature of a message in an EML file.

```csharp
public static bool CheckSignature(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the EML file. |

### Return Value

`true` if the signature is valid; otherwise, `false`.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *fileName* is `null` or `empty`. |
| FileNotFoundException | The file does not exist. |
| NotSupportedException | The type of the signature is not supported. |
| InvalidOperationException | The message is not signed, or the type of the signature is not specified. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature(Stream) {#checksignature}

Verifies the signature of a message read from a stream in EML format.

```csharp
public static bool CheckSignature(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read. |

### Return Value

`true` if the signature is valid; otherwise, `false`.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | The type of the signature is not supported. |
| InvalidOperationException | The message is not signed, or the type of the signature is not specified. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## CheckSignature()

Verifies the signature of the message.

```csharp
public virtual X509Certificate2[] CheckSignature()
```

### Return Value

The certificates of the signers.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | The message is not signed, or the signature is not valid. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


