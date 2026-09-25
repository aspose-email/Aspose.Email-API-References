---
title: PemReader.GetPrivateKey
second_title: Aspose.Email for .NET API Reference
description: PemReader method. Reads an RSA private key from a PEMencoded stream
type: docs
weight: 10
url: /net/aspose.email.dkim/pemreader/getprivatekey/
---
## GetPrivateKey(Stream) {#getprivatekey}

Reads an RSA private key from a PEM-encoded stream.

```csharp
public static RSACryptoServiceProvider GetPrivateKey(Stream pem)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pem | Stream | Stream with the PEM-encoded private key, in PKCS#1 or PKCS#8 format. |

### Return Value

An RSA provider initialized with the private key.

### Exceptions

| exception | condition |
| --- | --- |
| FormatException | The stream does not contain a supported PEM private key. |

### See Also

* class [PemReader](../)
* namespace [Aspose.Email.DKIM](../../pemreader/)
* assembly [Aspose.Email](../../../)

---

## GetPrivateKey(string) {#getprivatekey_1}

Reads an RSA private key from a PEM file.

```csharp
public static RSACryptoServiceProvider GetPrivateKey(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Path to the PEM file with the private key. |

### Return Value

An RSA provider initialized with the private key.

### Exceptions

| exception | condition |
| --- | --- |
| FormatException | The file does not contain a supported PEM private key. |

### See Also

* class [PemReader](../)
* namespace [Aspose.Email.DKIM](../../pemreader/)
* assembly [Aspose.Email](../../../)


