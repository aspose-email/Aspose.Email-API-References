---
title: DKIMSignatureInfo
second_title: Aspose.Email for Java API Reference
description: Represents DKIM signature information.
type: docs
weight: 132
url: /java/com.aspose.email/dkimsignatureinfo/
---

**Inheritance:**
java.lang.Object
```
public class DKIMSignatureInfo
```

Represents DKIM signature information.
## Constructors

| Constructor | Description |
| --- | --- |
| [DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain)](#DKIMSignatureInfo-java.lang.String-java.lang.String-) | Creates new instance of DKIMSignatureInfo. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBodyCanonicalization()](#getBodyCanonicalization--) | Gets or sets body canonicalization (c=). |
| [getClass()](#getClass--) |  |
| [getDomain()](#getDomain--) | Gets or sets public key DNS domain (d=). |
| [getHashAlgorithm()](#getHashAlgorithm--) | Gets or sets hash algorithm (a=). |
| [getHeaderCanonicalization()](#getHeaderCanonicalization--) | Gets or sets header canonicalization (c=). |
| [getHeaders()](#getHeaders--) | Headers that are included in the signature (h=). |
| [getSelector()](#getSelector--) | Gets or sets public key DNS selector (s=). |
| [getTime()](#getTime--) | Gets or sets the signature timestamp - the time that this signature was created (t=). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBodyCanonicalization(int value)](#setBodyCanonicalization-int-) | Gets or sets body canonicalization (c=). |
| [setDomain(String value)](#setDomain-java.lang.String-) | Gets or sets public key DNS domain (d=). |
| [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Gets or sets hash algorithm (a=). |
| [setHeaderCanonicalization(int value)](#setHeaderCanonicalization-int-) | Gets or sets header canonicalization (c=). |
| [setSelector(String value)](#setSelector-java.lang.String-) | Gets or sets public key DNS selector (s=). |
| [setTime(System.DateTime value)](#setTime-com.aspose.ms.System.DateTime-) | Gets or sets the signature timestamp - the time that this signature was created (t=). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain) {#DKIMSignatureInfo-java.lang.String-java.lang.String-}
```
public DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain)
```


Creates new instance of DKIMSignatureInfo.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKeyDnsSelector | java.lang.String | DNS public key domain selector. |
| publicKeyDnsDomain | java.lang.String | DNS public key domain. |

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


Gets or sets body canonicalization (c=).

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


Gets or sets public key DNS domain (d=).

**Returns:**
java.lang.String
### getHashAlgorithm() {#getHashAlgorithm--}
```
public int getHashAlgorithm()
```


Gets or sets hash algorithm (a=).

**Returns:**
int
### getHeaderCanonicalization() {#getHeaderCanonicalization--}
```
public final int getHeaderCanonicalization()
```


Gets or sets header canonicalization (c=).

**Returns:**
int
### getHeaders() {#getHeaders--}
```
public final HeaderList getHeaders()
```


Headers that are included in the signature (h=).

**Returns:**
[HeaderList](../../com.aspose.email/headerlist)
### getSelector() {#getSelector--}
```
public final String getSelector()
```


Gets or sets public key DNS selector (s=).

**Returns:**
java.lang.String
### getTime() {#getTime--}
```
public final System.DateTime getTime()
```


Gets or sets the signature timestamp - the time that this signature was created (t=). Default (null) is an unknown creation time.

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


Gets or sets body canonicalization (c=).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDomain(String value) {#setDomain-java.lang.String-}
```
public final void setDomain(String value)
```


Gets or sets public key DNS domain (d=).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Gets or sets hash algorithm (a=).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHeaderCanonicalization(int value) {#setHeaderCanonicalization-int-}
```
public final void setHeaderCanonicalization(int value)
```


Gets or sets header canonicalization (c=).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSelector(String value) {#setSelector-java.lang.String-}
```
public final void setSelector(String value)
```


Gets or sets public key DNS selector (s=).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTime(System.DateTime value) {#setTime-com.aspose.ms.System.DateTime-}
```
public final void setTime(System.DateTime value)
```


Gets or sets the signature timestamp - the time that this signature was created (t=). Default (null) is an unknown creation time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime |  |

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

