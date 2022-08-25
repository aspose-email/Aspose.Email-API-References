---
title: PemReader
second_title: Aspose.Email for Java API Reference
description:  PEM format reader.
type: docs
weight: 551
url: /java/com.aspose.email/pemreader/
---
**Inheritance:**
java.lang.Object
```
public class PemReader
```

PEM format reader.
## Constructors

| Constructor | Description |
| --- | --- |
| [PemReader()](#PemReader--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPrivateKey(InputStream pem)](#getPrivateKey-java.io.InputStream-) | Reads private key from stream. |
| [getPrivateKey(String path)](#getPrivateKey-java.lang.String-) | Reads private key from PEM file. |
### PemReader() {#PemReader--}
```
public PemReader()
```


### getPrivateKey(InputStream pem) {#getPrivateKey-java.io.InputStream-}
```
public static System.Security.Cryptography.RSACryptoServiceProvider getPrivateKey(InputStream pem)
```


Reads private key from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pem | java.io.InputStream | Stream to read from. |

**Returns:**
com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider - Certificate that was read.
### getPrivateKey(String path) {#getPrivateKey-java.lang.String-}
```
public static System.Security.Cryptography.RSACryptoServiceProvider getPrivateKey(String path)
```


Reads private key from PEM file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Path to file to read from. |

**Returns:**
com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider - Certificate that was read.
