---
title: PemReader
second_title: Aspose.Email for Android via Java API Reference
description: Читатель формата PEM.
type: docs
weight: 343
url: /ru/androidjava/com.aspose.email/pemreader/
---

**Inheritance:**
java.lang.Object
```
public class PemReader
```

Читатель формата PEM.
## Constructors

| Constructor | Описание |
| --- | --- |
| [PemReader()](#PemReader--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPrivateKey(InputStream pem)](#getPrivateKey-java.io.InputStream-) | Читает закрытый ключ из потока. |
| [getPrivateKey(String path)](#getPrivateKey-java.lang.String-) | Читает закрытый ключ из PEM‑файла. |
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
| Parameter | Type | Описание |
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
public static System.Security.Cryptography.RSACryptoServiceProvider getPrivateKey(InputStream pem)
```


Читает закрытый ключ из потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pem | java.io.InputStream | Поток для чтения. |

**Returns:**
com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider — сертификат, который был прочитан.
### getPrivateKey(String path) {#getPrivateKey-java.lang.String-}
```
public static System.Security.Cryptography.RSACryptoServiceProvider getPrivateKey(String path)
```


Читает закрытый ключ из PEM‑файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| путь | java.lang.String | Путь к файлу для чтения. |

**Returns:**
com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider — сертификат, который был прочитан.
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

