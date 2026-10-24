---
title: DkimVerifier
second_title: Aspose.Email for Java API Reference
description: Verifies DKIM signature of the MIME file or stream.
type: docs
weight: 163
url: /java/com.aspose.email/dkimverifier/
---

**Inheritance:**
java.lang.Object
```
public class DkimVerifier
```

Verifies DKIM signature of the MIME file or stream.
## Constructors

| Constructor | Description |
| --- | --- |
| [DkimVerifier()](#DkimVerifier--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [verify(InputStream mimeStream)](#verify-java.io.InputStream-) | Verifies DKIM signature of the MIME stream. |
| [verify(String mimeFilePath)](#verify-java.lang.String-) | Verifies DKIM signature of the MIME file. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DkimVerifier() {#DkimVerifier--}
```
public DkimVerifier()
```


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
### verify(InputStream mimeStream) {#verify-java.io.InputStream-}
```
public static DkimResult verify(InputStream mimeStream)
```


Verifies DKIM signature of the MIME stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mimeStream | java.io.InputStream | Source MIME stream. |

**Returns:**
[DkimResult](../../com.aspose.email/dkimresult) - Result of validation [DkimResult](../../com.aspose.email/dkimresult)
### verify(String mimeFilePath) {#verify-java.lang.String-}
```
public static DkimResult verify(String mimeFilePath)
```


Verifies DKIM signature of the MIME file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mimeFilePath | java.lang.String | Path to source MIME file. |

**Returns:**
[DkimResult](../../com.aspose.email/dkimresult) - Result of validation [DkimResult](../../com.aspose.email/dkimresult)
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

