---
title: SmimeResult
second_title: Aspose.Email for Java API Reference
description: This class containing results of checking secure emails.
type: docs
weight: 641
url: /java/com.aspose.email/smimeresult/
---

**Inheritance:**
java.lang.Object
```
public class SmimeResult
```

This class containing results of checking secure emails.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncryptionCertificates()](#getEncryptionCertificates--) | Gets the collection of certificates with which the email was encrypted. |
| [getError()](#getError--) | Gets error which was thrown while checking. |
| [getSigningCertificates()](#getSigningCertificates--) | Gets the collection of certificates with which the email was signed. |
| [hashCode()](#hashCode--) |  |
| [isSuccess()](#isSuccess--) | Gets true if check was successful, otherwise false. |
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
public final System.Security.Cryptography.X509Certificates.X509Certificate2Collection getEncryptionCertificates()
```


Gets the collection of certificates with which the email was encrypted.

**Returns:**
com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2Collection
### getError() {#getError--}
```
public final RuntimeException getError()
```


Gets error which was thrown while checking.

**Returns:**
java.lang.RuntimeException
### getSigningCertificates() {#getSigningCertificates--}
```
public final System.Security.Cryptography.X509Certificates.X509Certificate2Collection getSigningCertificates()
```


Gets the collection of certificates with which the email was signed.

**Returns:**
com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2Collection
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


Gets true if check was successful, otherwise false.

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

