---
title: DKIMSignatureInfo
second_title: Aspose.Email for Java API Reference
description: Describes how a message is signed with DKIM and what goes into the DKIM-Signature header.
type: docs
weight: 135
url: /java/com.aspose.email/dkimsignatureinfo/
---

**Inheritance:**
java.lang.Object
```
public class DKIMSignatureInfo
```

Describes how a message is signed with DKIM and what goes into the DKIM-Signature header.

Set the DNS selector and domain of the published public key, list the headers to sign in \#getHeaders().getHeaders(), then pass the instance to  MailMessage.dKIMSign  together with the private key loaded by [PemReader](../../com.aspose.email/pemreader).
## Constructors

| Constructor | Description |
| --- | --- |
| [DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain)](#DKIMSignatureInfo-java.lang.String-java.lang.String-) | Initializes a new instance of the [DKIMSignatureInfo](../../com.aspose.email/dkimsignatureinfo) class with the DNS selector and domain of the public key. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBodyCanonicalization()](#getBodyCanonicalization--) | Gets how the message body is normalized before it is hashed (the body half of the c= tag). |
| [getClass()](#getClass--) |  |
| [getDomain()](#getDomain--) | Gets the domain whose DNS TXT records publish the public key (the d= tag). |
| [getHashAlgorithm()](#getHashAlgorithm--) | Gets the algorithm used to hash the signed headers and body (the a= tag). |
| [getHeaderCanonicalization()](#getHeaderCanonicalization--) | Gets how the signed headers are normalized before they are hashed (the header half of the c= tag). |
| [getHeaders()](#getHeaders--) | Gets the names of the headers to include in the signature (the h= tag). |
| [getSelector()](#getSelector--) | Gets the selector that tells verifiers which public key of the domain to use (the s= tag). |
| [getTime()](#getTime--) | Gets the signature timestamp - the time that this signature was created (t=). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBodyCanonicalization(int value)](#setBodyCanonicalization-int-) | Sets how the message body is normalized before it is hashed (the body half of the c= tag). |
| [setDomain(String value)](#setDomain-java.lang.String-) | Sets the domain whose DNS TXT records publish the public key (the d= tag). |
| [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Sets the algorithm used to hash the signed headers and body (the a= tag). |
| [setHeaderCanonicalization(int value)](#setHeaderCanonicalization-int-) | Sets how the signed headers are normalized before they are hashed (the header half of the c= tag). |
| [setSelector(String value)](#setSelector-java.lang.String-) | Sets the selector that tells verifiers which public key of the domain to use (the s= tag). |
| [setTime(System.DateTime value)](#setTime-com.aspose.ms.System.DateTime-) | Sets the signature timestamp - the time that this signature was created (t=). |
| [setTimeNew(Date value)](#setTimeNew-java.util.Date-) | Gets or sets the signature timestamp - the time that this signature was created (t=). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain) {#DKIMSignatureInfo-java.lang.String-java.lang.String-}
```
public DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain)
```


Initializes a new instance of the [DKIMSignatureInfo](../../com.aspose.email/dkimsignatureinfo) class with the DNS selector and domain of the public key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKeyDnsSelector | java.lang.String | Selector that tells verifiers which public key of the domain to use (the s= tag). |
| publicKeyDnsDomain | java.lang.String | Domain whose DNS TXT records publish the public key (the d= tag). |

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
### getBodyCanonicalization() {#getBodyCanonicalization--}
```
public final int getBodyCanonicalization()
```


Gets how the message body is normalized before it is hashed (the body half of the c= tag). Default is  Relaxed .

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDomain() {#getDomain--}
```
public final String getDomain()
```


Gets the domain whose DNS TXT records publish the public key (the d= tag).

**Returns:**
java.lang.String
### getHashAlgorithm() {#getHashAlgorithm--}
```
public int getHashAlgorithm()
```


Gets the algorithm used to hash the signed headers and body (the a= tag). Default is  RSASha1 .

**Returns:**
int
### getHeaderCanonicalization() {#getHeaderCanonicalization--}
```
public final int getHeaderCanonicalization()
```


Gets how the signed headers are normalized before they are hashed (the header half of the c= tag). Default is  Relaxed .

**Returns:**
int
### getHeaders() {#getHeaders--}
```
public final HeaderList getHeaders()
```


Gets the names of the headers to include in the signature (the h= tag). Add at least From, otherwise the signature is not valid.

**Returns:**
[HeaderList](../../com.aspose.email/headerlist)
### getSelector() {#getSelector--}
```
public final String getSelector()
```


Gets the selector that tells verifiers which public key of the domain to use (the s= tag).

**Returns:**
java.lang.String
### getTime() {#getTime--}
```
public final System.DateTime getTime()
```


Gets the signature timestamp - the time that this signature was created (t=). Default ( null ) is an unknown creation time.

**Returns:**
com.aspose.ms.System.DateTime
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




### setBodyCanonicalization(int value) {#setBodyCanonicalization-int-}
```
public final void setBodyCanonicalization(int value)
```


Sets how the message body is normalized before it is hashed (the body half of the c= tag). Default is  Relaxed .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDomain(String value) {#setDomain-java.lang.String-}
```
public final void setDomain(String value)
```


Sets the domain whose DNS TXT records publish the public key (the d= tag).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Sets the algorithm used to hash the signed headers and body (the a= tag). Default is  RSASha1 .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHeaderCanonicalization(int value) {#setHeaderCanonicalization-int-}
```
public final void setHeaderCanonicalization(int value)
```


Sets how the signed headers are normalized before they are hashed (the header half of the c= tag). Default is  Relaxed .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSelector(String value) {#setSelector-java.lang.String-}
```
public final void setSelector(String value)
```


Sets the selector that tells verifiers which public key of the domain to use (the s= tag).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTime(System.DateTime value) {#setTime-com.aspose.ms.System.DateTime-}
```
public final void setTime(System.DateTime value)
```


Sets the signature timestamp - the time that this signature was created (t=). Default ( null ) is an unknown creation time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime |  |

### setTimeNew(Date value) {#setTimeNew-java.util.Date-}
```
public final void setTimeNew(Date value)
```


Gets or sets the signature timestamp - the time that this signature was created (t=). Default (null) is an unknown creation time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

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

