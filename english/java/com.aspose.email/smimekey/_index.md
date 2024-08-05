---
title: SmimeKey
second_title: Aspose.Email for Java API Reference
description: A wrapper around a PrivateKey and a chain of X509Certificate used to sign or decrypt a MIME message.
type: docs
weight: 657
url: /java/com.aspose.email/smimekey/
---

**Inheritance:**
java.lang.Object
```
public class SmimeKey
```

A wrapper around a PrivateKey and a chain of X509Certificate used to sign or decrypt a MIME message.
## Constructors

| Constructor | Description |
| --- | --- |
| [SmimeKey(PrivateKey privateKey, X509Certificate[] certificateChain)](#SmimeKey-java.security.PrivateKey-java.security.cert.X509Certificate...-) | Create a new  SmimeKey  with the given private key and certificate chain. |
| [SmimeKey(X509Certificate[] certificateChain)](#SmimeKey-java.security.cert.X509Certificate...-) | Create a new  SmimeKey  with the given private key and certificate chain. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedAddresses()](#getAssociatedAddresses--) | Compiles and returns the list of email address associated with the \#getCertificate().getCertificate() of this  SmimeKey  by inspecting the subjects distinguished name. |
| [getCertificate()](#getCertificate--) | Returns the certificate that holds the public key that corresponds to the private key of this  SmimeKey . |
| [getCertificateChain()](#getCertificateChain--) | Returns the chain of certificates of this  SmimeKey  starting with the certificate that holds the public key that corresponds to the private key of this  SmimeKey  and ending with the trust anchor. |
| [getClass()](#getClass--) |  |
| [getPrivateKey()](#getPrivateKey--) | Returns the private key of this  SmimeKey . |
| [hashCode()](#hashCode--) |  |
| [loadCertificate(InputStream stream)](#loadCertificate-java.io.InputStream-) | Load a new  SmimeKey  with the given certificate from string -----CERTIFICATE----- |
| [loadCertificate(String crtPath)](#loadCertificate-java.lang.String-) | Load a new  SmimeKey  with the given private key and certificate from string -----CERTIFICATE----- |
| [loadPFX(InputStream stream, char[] password)](#loadPFX-java.io.InputStream-char---) | Load a new  SmimeKey  with the given private key and certificate from PFX store |
| [loadPFX(InputStream stream, String alias, char[] password)](#loadPFX-java.io.InputStream-java.lang.String-char---) | Load a new  SmimeKey  with the given private key and certificate from PFX store |
| [loadPFX(String pfxPath, char[] password)](#loadPFX-java.lang.String-char---) | Load a new  SmimeKey  with the given private key and certificate from PFX store |
| [loadPFX(String pfxPath, String alias, char[] password)](#loadPFX-java.lang.String-java.lang.String-char---) | Load a new  SmimeKey  with the given private key and certificate from PFX store |
| [loadPrivateKey(InputStream stream)](#loadPrivateKey-java.io.InputStream-) | Load a new  SmimeKey  with the given private key from string ---RSA PRIVATE KEY---. |
| [loadPrivateKey(String keyPath)](#loadPrivateKey-java.lang.String-) | Load a new  SmimeKey  with the given private key from string -----RSA PRIVATE KEY----- |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmimeKey(PrivateKey privateKey, X509Certificate[] certificateChain) {#SmimeKey-java.security.PrivateKey-java.security.cert.X509Certificate...-}
```
public SmimeKey(PrivateKey privateKey, X509Certificate[] certificateChain)
```


Create a new  SmimeKey  with the given private key and certificate chain.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| privateKey | java.security.PrivateKey | The PrivateKey of this  SmimeKey  |
| certificateChain | java.security.cert.X509Certificate[] | The chain of X509Certificate of this  SmimeKey  starting with the certificate that holds the public key that corresponds to the given private key and ending with the trust anchor. |

### SmimeKey(X509Certificate[] certificateChain) {#SmimeKey-java.security.cert.X509Certificate...-}
```
public SmimeKey(X509Certificate[] certificateChain)
```


Create a new  SmimeKey  with the given private key and certificate chain.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateChain | java.security.cert.X509Certificate[] | The chain of X509Certificate of this  SmimeKey  starting with the certificate that holds the public key that corresponds to the given private key and ending with the trust anchor. |

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
### getAssociatedAddresses() {#getAssociatedAddresses--}
```
public List<String> getAssociatedAddresses()
```


Compiles and returns the list of email address associated with the \#getCertificate().getCertificate() of this  SmimeKey  by inspecting the subjects distinguished name.

**Returns:**
java.util.List<java.lang.String> - A Collections\#unmodifiableList(List).unmodifiableList(List) of email addresses.
### getCertificate() {#getCertificate--}
```
public X509Certificate getCertificate()
```


Returns the certificate that holds the public key that corresponds to the private key of this  SmimeKey .

**Returns:**
java.security.cert.X509Certificate - The X509Certificate.
### getCertificateChain() {#getCertificateChain--}
```
public X509Certificate[] getCertificateChain()
```


Returns the chain of certificates of this  SmimeKey  starting with the certificate that holds the public key that corresponds to the private key of this  SmimeKey  and ending with the trust anchor.

**Returns:**
java.security.cert.X509Certificate[] - The chain of X509Certificate.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPrivateKey() {#getPrivateKey--}
```
public PrivateKey getPrivateKey()
```


Returns the private key of this  SmimeKey .

**Returns:**
java.security.PrivateKey - The PrivateKey.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadCertificate(InputStream stream) {#loadCertificate-java.io.InputStream-}
```
public static SmimeKey loadCertificate(InputStream stream)
```


Load a new  SmimeKey  with the given certificate from string -----CERTIFICATE-----

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The InputStream to read the certificate from. |

**Returns:**
[SmimeKey](../../com.aspose.email/smimekey)
### loadCertificate(String crtPath) {#loadCertificate-java.lang.String-}
```
public static SmimeKey loadCertificate(String crtPath)
```


Load a new  SmimeKey  with the given private key and certificate from string -----CERTIFICATE-----

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| crtPath | java.lang.String | The path to the file containing certificate. |

**Returns:**
[SmimeKey](../../com.aspose.email/smimekey)
### loadPFX(InputStream stream, char[] password) {#loadPFX-java.io.InputStream-char---}
```
public static SmimeKey loadPFX(InputStream stream, char[] password)
```


Load a new  SmimeKey  with the given private key and certificate from PFX store

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The InputStream to read the PFX store from. |
| password | char[] | The password to unlock the PFX store with. |

**Returns:**
[SmimeKey](../../com.aspose.email/smimekey)
### loadPFX(InputStream stream, String alias, char[] password) {#loadPFX-java.io.InputStream-java.lang.String-char---}
```
public static SmimeKey loadPFX(InputStream stream, String alias, char[] password)
```


Load a new  SmimeKey  with the given private key and certificate from PFX store

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The InputStream to read the PFX store from. |
| alias | java.lang.String | The alias of the key entry in the PFX store. |
| password | char[] | The password to unlock the PFX store with. |

**Returns:**
[SmimeKey](../../com.aspose.email/smimekey)
### loadPFX(String pfxPath, char[] password) {#loadPFX-java.lang.String-char---}
```
public static SmimeKey loadPFX(String pfxPath, char[] password)
```


Load a new  SmimeKey  with the given private key and certificate from PFX store

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfxPath | java.lang.String | The path to the PFX file |
| password | char[] | The password to unlock the PFX store with. |

**Returns:**
[SmimeKey](../../com.aspose.email/smimekey)
### loadPFX(String pfxPath, String alias, char[] password) {#loadPFX-java.lang.String-java.lang.String-char---}
```
public static SmimeKey loadPFX(String pfxPath, String alias, char[] password)
```


Load a new  SmimeKey  with the given private key and certificate from PFX store

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfxPath | java.lang.String | The path to the PFX file |
| alias | java.lang.String | The alias of the key entry in the PFX store. |
| password | char[] | The password to unlock the PFX store with. |

**Returns:**
[SmimeKey](../../com.aspose.email/smimekey)
### loadPrivateKey(InputStream stream) {#loadPrivateKey-java.io.InputStream-}
```
public static SmimeKey loadPrivateKey(InputStream stream)
```


Load a new  SmimeKey  with the given private key from string ---RSA PRIVATE KEY---.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The InputStream to read the private key from. |

**Returns:**
[SmimeKey](../../com.aspose.email/smimekey)
### loadPrivateKey(String keyPath) {#loadPrivateKey-java.lang.String-}
```
public static SmimeKey loadPrivateKey(String keyPath)
```


Load a new  SmimeKey  with the given private key from string -----RSA PRIVATE KEY-----

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keyPath | java.lang.String | The path to the file containing the private key. |

**Returns:**
[SmimeKey](../../com.aspose.email/smimekey)
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

