---
title: DKIMSignatureInfo
second_title: Aspose.Email for Android via Java API 参考
description: 表示 DKIM 签名信息。
type: docs
weight: 91
url: /zh/androidjava/com.aspose.email/dkimsignatureinfo/
---

**Inheritance:**
java.lang.Object
```
public class DKIMSignatureInfo
```

表示 DKIM 签名信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain)](#DKIMSignatureInfo-java.lang.String-java.lang.String-) | 创建 DKIMSignatureInfo 的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBodyCanonicalization()](#getBodyCanonicalization--) | 获取或设置正文规范化 (c=)。 |
| [getClass()](#getClass--) |  |
| [getDomain()](#getDomain--) | 获取或设置公钥 DNS 域 (d=)。 |
| [getHashAlgorithm()](#getHashAlgorithm--) | 获取或设置哈希算法 (a=)。 |
| [getHeaderCanonicalization()](#getHeaderCanonicalization--) | 获取或设置标头规范化 (c=)。 |
| [getHeaders()](#getHeaders--) | 签名中包含的标头 (h=)。 |
| [getSelector()](#getSelector--) | 获取或设置公钥 DNS 选择器 (s=)。 |
| [getTime()](#getTime--) | 获取或设置签名时间戳 - 此签名创建的时间 (t=)。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBodyCanonicalization(int value)](#setBodyCanonicalization-int-) | 获取或设置正文规范化 (c=)。 |
| [setDomain(String value)](#setDomain-java.lang.String-) | 获取或设置公钥 DNS 域 (d=)。 |
| [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | 获取或设置哈希算法 (a=)。 |
| [setHeaderCanonicalization(int value)](#setHeaderCanonicalization-int-) | 获取或设置标头规范化 (c=)。 |
| [setSelector(String value)](#setSelector-java.lang.String-) | 获取或设置公钥 DNS 选择器 (s=)。 |
| [setTime(System.DateTime value)](#setTime-com.aspose.ms.System.DateTime-) | 获取或设置签名时间戳 - 此签名创建的时间 (t=)。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain) {#DKIMSignatureInfo-java.lang.String-java.lang.String-}
```
public DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain)
```


创建 DKIMSignatureInfo 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicKeyDnsSelector | java.lang.String | DNS 公钥域选择器。 |
| publicKeyDnsDomain | java.lang.String | DNS 公钥域。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBodyCanonicalization() {#getBodyCanonicalization--}
```
public final int getBodyCanonicalization()
```


获取或设置正文规范化 (c=)。

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


获取或设置公钥 DNS 域 (d=)。

**Returns:**
java.lang.String
### getHashAlgorithm() {#getHashAlgorithm--}
```
public int getHashAlgorithm()
```


获取或设置哈希算法 (a=)。

**Returns:**
int
### getHeaderCanonicalization() {#getHeaderCanonicalization--}
```
public final int getHeaderCanonicalization()
```


获取或设置标头规范化 (c=)。

**Returns:**
int
### getHeaders() {#getHeaders--}
```
public final HeaderList getHeaders()
```


签名中包含的标头 (h=)。

**Returns:**
[HeaderList](../../com.aspose.email/headerlist)
### getSelector() {#getSelector--}
```
public final String getSelector()
```


获取或设置公钥 DNS 选择器 (s=)。

**Returns:**
java.lang.String
### getTime() {#getTime--}
```
public final System.DateTime getTime()
```


获取或设置签名时间戳 - 此签名创建的时间 (t=)。默认 (null) 为未知的创建时间。

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


获取或设置正文规范化 (c=)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setDomain(String value) {#setDomain-java.lang.String-}
```
public final void setDomain(String value)
```


获取或设置公钥 DNS 域 (d=)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


获取或设置哈希算法 (a=)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setHeaderCanonicalization(int value) {#setHeaderCanonicalization-int-}
```
public final void setHeaderCanonicalization(int value)
```


获取或设置标头规范化 (c=)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setSelector(String value) {#setSelector-java.lang.String-}
```
public final void setSelector(String value)
```


获取或设置公钥 DNS 选择器 (s=)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setTime(System.DateTime value) {#setTime-com.aspose.ms.System.DateTime-}
```
public final void setTime(System.DateTime value)
```


获取或设置签名时间戳 - 此签名创建的时间 (t=)。默认 (null) 为未知的创建时间。

**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

