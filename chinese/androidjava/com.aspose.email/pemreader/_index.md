---
title: PemReader
second_title: Aspose.Email for Android via Java API 参考
description: PEM 格式读取器。
type: docs
weight: 343
url: /zh/androidjava/com.aspose.email/pemreader/
---

**Inheritance:**
java.lang.Object
```
public class PemReader
```

PEM 格式读取器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PemReader()](#PemReader--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPrivateKey(InputStream pem)](#getPrivateKey-java.io.InputStream-) | 从 stream 读取私钥。 |
| [getPrivateKey(String path)](#getPrivateKey-java.lang.String-) | 从 PEM 文件读取私钥。 |
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
| 参数 | 类型 | 描述 |
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


从 stream 读取私钥。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pem | java.io.InputStream | 用于读取的 stream。 |

**Returns:**
com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider - 已读取的证书。
### getPrivateKey(String path) {#getPrivateKey-java.lang.String-}
```
public static System.Security.Cryptography.RSACryptoServiceProvider getPrivateKey(String path)
```


从 PEM 文件读取私钥。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 要读取的文件路径。 |

**Returns:**
com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider - 已读取的证书。
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

