---
title: SmimeResult
second_title: Aspose.Email for Java API Reference
description: The result of verifying the signature of a message.
type: docs
weight: 678
url: /java/com.aspose.email/smimeresult/
---

**Inheritance:**
java.lang.Object
```
public class SmimeResult
```

The result of verifying the signature of a message.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncryptionCertificates()](#getEncryptionCertificates--) | Gets the certificates the message was encrypted with. |
| [getError()](#getError--) | Gets the error that occurred during the check, if any. |
| [getSigningCertificates()](#getSigningCertificates--) | Gets the certificates the message was signed with. |
| [hashCode()](#hashCode--) |  |
| [isSuccess()](#isSuccess--) | Gets a value indicating whether the signature is valid. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getEncryptionCertificates() {#getEncryptionCertificates--}
```
public final List<X509Certificate> getEncryptionCertificates()
```


Gets the certificates the message was encrypted with.

**Returns:**
java.util.List<java.security.cert.X509Certificate>
### getError() {#getError--}
```
public final RuntimeException getError()
```


Gets the error that occurred during the check, if any.

**Returns:**
java.lang.RuntimeException
### getSigningCertificates() {#getSigningCertificates--}
```
public final List<X509Certificate> getSigningCertificates()
```


Gets the certificates the message was signed with.

**Returns:**
java.util.List<java.security.cert.X509Certificate>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isSuccess() {#isSuccess--}
```
public final boolean isSuccess()
```


Gets a value indicating whether the signature is valid.

**Returns:**
boolean
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

