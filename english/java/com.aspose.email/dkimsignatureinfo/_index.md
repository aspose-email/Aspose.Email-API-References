---
title: DKIMSignatureInfo
second_title: Aspose.Email for Java API Reference
description:  Represents DKIM signature information.
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
| [getBodyCanonicalization()](#getBodyCanonicalization--) | Gets or sets body canonicalization (c=). |
| [setBodyCanonicalization(int value)](#setBodyCanonicalization-int-) | Gets or sets body canonicalization (c=). |
| [getHeaderCanonicalization()](#getHeaderCanonicalization--) | Gets or sets header canonicalization (c=). |
| [setHeaderCanonicalization(int value)](#setHeaderCanonicalization-int-) | Gets or sets header canonicalization (c=). |
| [getSelector()](#getSelector--) | Gets or sets public key DNS selector (s=). |
| [setSelector(String value)](#setSelector-java.lang.String-) | Gets or sets public key DNS selector (s=). |
| [getDomain()](#getDomain--) | Gets or sets public key DNS domain (d=). |
| [setDomain(String value)](#setDomain-java.lang.String-) | Gets or sets public key DNS domain (d=). |
| [getTime()](#getTime--) | Gets or sets the signature timestamp - the time that this signature was created (t=). |
| [setTime(System.DateTime value)](#setTime-com.aspose.ms.System.DateTime-) | Gets or sets the signature timestamp - the time that this signature was created (t=). |
| [getHashAlgorithm()](#getHashAlgorithm--) | Gets or sets hash algorithm (a=). |
| [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Gets or sets hash algorithm (a=). |
| [getHeaders()](#getHeaders--) | Headers that are included in the signature (h=). |
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

### getBodyCanonicalization() {#getBodyCanonicalization--}
```
public final int getBodyCanonicalization()
```


Gets or sets body canonicalization (c=).

**Returns:**
int
### setBodyCanonicalization(int value) {#setBodyCanonicalization-int-}
```
public final void setBodyCanonicalization(int value)
```


Gets or sets body canonicalization (c=).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeaderCanonicalization() {#getHeaderCanonicalization--}
```
public final int getHeaderCanonicalization()
```


Gets or sets header canonicalization (c=).

**Returns:**
int
### setHeaderCanonicalization(int value) {#setHeaderCanonicalization-int-}
```
public final void setHeaderCanonicalization(int value)
```


Gets or sets header canonicalization (c=).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSelector() {#getSelector--}
```
public final String getSelector()
```


Gets or sets public key DNS selector (s=).

**Returns:**
java.lang.String
### setSelector(String value) {#setSelector-java.lang.String-}
```
public final void setSelector(String value)
```


Gets or sets public key DNS selector (s=).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDomain() {#getDomain--}
```
public final String getDomain()
```


Gets or sets public key DNS domain (d=).

**Returns:**
java.lang.String
### setDomain(String value) {#setDomain-java.lang.String-}
```
public final void setDomain(String value)
```


Gets or sets public key DNS domain (d=).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTime() {#getTime--}
```
public final System.DateTime getTime()
```


Gets or sets the signature timestamp - the time that this signature was created (t=). Default (null) is an unknown creation time.

**Returns:**
com.aspose.ms.System.DateTime
### setTime(System.DateTime value) {#setTime-com.aspose.ms.System.DateTime-}
```
public final void setTime(System.DateTime value)
```


Gets or sets the signature timestamp - the time that this signature was created (t=). Default (null) is an unknown creation time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public int getHashAlgorithm()
```


Gets or sets hash algorithm (a=).

**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Gets or sets hash algorithm (a=).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeaders() {#getHeaders--}
```
public final HeaderList getHeaders()
```


Headers that are included in the signature (h=).

**Returns:**
[HeaderList](../../com.aspose.email/headerlist)
