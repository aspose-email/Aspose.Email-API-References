---
title: DKIMSignatureInfo
second_title: Aspose.Email for Android via Java API Reference
description: Представляет информацию о подписи DKIM.
type: docs
weight: 91
url: /ru/androidjava/com.aspose.email/dkimsignatureinfo/
---

**Inheritance:**
java.lang.Object
```
public class DKIMSignatureInfo
```

Представляет информацию о подписи DKIM.
## Constructors

| Constructor | Описание |
| --- | --- |
| [DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain)](#DKIMSignatureInfo-java.lang.String-java.lang.String-) | Создает новый экземпляр DKIMSignatureInfo. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBodyCanonicalization()](#getBodyCanonicalization--) | Получает или задает канонизацию тела (c=). |
| [getClass()](#getClass--) |  |
| [getDomain()](#getDomain--) | Получает или задает домен DNS публичного ключа (d=). |
| [getHashAlgorithm()](#getHashAlgorithm--) | Получает или задает алгоритм хеширования (a=). |
| [getHeaderCanonicalization()](#getHeaderCanonicalization--) | Получает или задает канонизацию заголовка (c=). |
| [getHeaders()](#getHeaders--) | Заголовки, включенные в подпись (h=). |
| [getSelector()](#getSelector--) | Получает или задает селектор DNS публичного ключа (s=). |
| [getTime()](#getTime--) | Получает или задает метку времени подписи — время создания этой подписи (t=). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBodyCanonicalization(int value)](#setBodyCanonicalization-int-) | Получает или задает канонизацию тела (c=). |
| [setDomain(String value)](#setDomain-java.lang.String-) | Получает или задает домен DNS публичного ключа (d=). |
| [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Получает или задает алгоритм хеширования (a=). |
| [setHeaderCanonicalization(int value)](#setHeaderCanonicalization-int-) | Получает или задает канонизацию заголовка (c=). |
| [setSelector(String value)](#setSelector-java.lang.String-) | Получает или задает селектор DNS публичного ключа (s=). |
| [setTime(System.DateTime value)](#setTime-com.aspose.ms.System.DateTime-) | Получает или задает метку времени подписи — время создания этой подписи (t=). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain) {#DKIMSignatureInfo-java.lang.String-java.lang.String-}
```
public DKIMSignatureInfo(String publicKeyDnsSelector, String publicKeyDnsDomain)
```


Создает новый экземпляр DKIMSignatureInfo.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| publicKeyDnsSelector | java.lang.String | Селектор домена публичного ключа DNS. |
| publicKeyDnsDomain | java.lang.String | Домен публичного ключа DNS. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBodyCanonicalization() {#getBodyCanonicalization--}
```
public final int getBodyCanonicalization()
```


Получает или задает канонизацию тела (c=).

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


Получает или задает домен DNS публичного ключа (d=).

**Returns:**
java.lang.String
### getHashAlgorithm() {#getHashAlgorithm--}
```
public int getHashAlgorithm()
```


Получает или задает алгоритм хеширования (a=).

**Returns:**
int
### getHeaderCanonicalization() {#getHeaderCanonicalization--}
```
public final int getHeaderCanonicalization()
```


Получает или задает канонизацию заголовка (c=).

**Returns:**
int
### getHeaders() {#getHeaders--}
```
public final HeaderList getHeaders()
```


Заголовки, включенные в подпись (h=).

**Returns:**
[HeaderList](../../com.aspose.email/headerlist)
### getSelector() {#getSelector--}
```
public final String getSelector()
```


Получает или задает селектор DNS публичного ключа (s=).

**Returns:**
java.lang.String
### getTime() {#getTime--}
```
public final System.DateTime getTime()
```


Получает или задает метку времени подписи — время создания этой подписи (t=). По умолчанию (null) — неизвестное время создания.

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


Получает или задает канонизацию тела (c=).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setDomain(String value) {#setDomain-java.lang.String-}
```
public final void setDomain(String value)
```


Получает или задает домен DNS публичного ключа (d=).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Получает или задает алгоритм хеширования (a=).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setHeaderCanonicalization(int value) {#setHeaderCanonicalization-int-}
```
public final void setHeaderCanonicalization(int value)
```


Получает или задает канонизацию заголовка (c=).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setSelector(String value) {#setSelector-java.lang.String-}
```
public final void setSelector(String value)
```


Получает или задает селектор DNS публичного ключа (s=).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setTime(System.DateTime value) {#setTime-com.aspose.ms.System.DateTime-}
```
public final void setTime(System.DateTime value)
```


Получает или задает метку времени подписи — время создания этой подписи (t=). По умолчанию (null) — неизвестное время создания.

**Parameters:**
| Parameter | Type | Описание |
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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

