---
title: PemReader
second_title: Aspose.Email for Java API Reference
description: Reads RSA private keys from PEM files and streams for use with DKIM signing.
type: docs
weight: 588
url: /java/com.aspose.email/pemreader/
---

**Inheritance:**
java.lang.Object
```
public class PemReader
```

Reads RSA private keys from PEM files and streams, for use with DKIM signing.
## Constructors

| Constructor | Description |
| --- | --- |
| [PemReader()](#PemReader--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPrivateKey(InputStream pem)](#getPrivateKey-java.io.InputStream-) | Reads an RSA private key from a PEM-encoded stream. |
| [getPrivateKey(String pemFile)](#getPrivateKey-java.lang.String-) | Reads an RSA private key from a PEM file. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PemReader() {#PemReader--}
```
public PemReader()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPrivateKey(InputStream pem) {#getPrivateKey-java.io.InputStream-}
```
public static PrivateKey getPrivateKey(InputStream pem)
```


Reads an RSA private key from a PEM-encoded stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pem | java.io.InputStream | Stream with the PEM-encoded private key, in PKCS\#1 or PKCS\#8 format. |

**Returns:**
java.security.PrivateKey - The private key.
### getPrivateKey(String pemFile) {#getPrivateKey-java.lang.String-}
```
public static PrivateKey getPrivateKey(String pemFile)
```


Reads an RSA private key from a PEM file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pemFile | java.lang.String | Path to the PEM file with the private key. |

**Returns:**
java.security.PrivateKey - The private key.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

