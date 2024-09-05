---
title: IExchangeClientBase
second_title: Aspose.Email for Java API Reference
description: Represents the interface for base Exchange clients.
type: docs
weight: 764
url: /java/com.aspose.email/iexchangeclientbase/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public interface IExchangeClientBase extends System.IDisposable, Closeable
```

Represents the interface for base Exchange clients.
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [getCredentials()](#getCredentials--) | Gets or sets the credentials. |
| [getProxy()](#getProxy--) | Gets or sets the proxy. |
| [getTimeout()](#getTimeout--) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [setCredentials(System.Net.ICredentials value)](#setCredentials-com.aspose.ms.System.Net.ICredentials-) | Gets or sets the credentials. |
| [setProxy(System.Net.WebProxy value)](#setProxy-com.aspose.ms.System.Net.WebProxy-) | Gets or sets the proxy. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the number of milliseconds to wait before the operation times out. |
### close() {#close--}
```
public abstract void close()
```




### getCredentials() {#getCredentials--}
```
public abstract System.Net.ICredentials getCredentials()
```


Gets or sets the credentials.

**Returns:**
com.aspose.ms.System.Net.ICredentials
### getProxy() {#getProxy--}
```
public abstract System.Net.WebProxy getProxy()
```


Gets or sets the proxy.

**Returns:**
com.aspose.ms.System.Net.WebProxy
### getTimeout() {#getTimeout--}
```
public abstract int getTimeout()
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

**Returns:**
int
### setCredentials(System.Net.ICredentials value) {#setCredentials-com.aspose.ms.System.Net.ICredentials-}
```
public abstract void setCredentials(System.Net.ICredentials value)
```


Gets or sets the credentials.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.ICredentials |  |

### setProxy(System.Net.WebProxy value) {#setProxy-com.aspose.ms.System.Net.WebProxy-}
```
public abstract void setProxy(System.Net.WebProxy value)
```


Gets or sets the proxy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.WebProxy |  |

### setTimeout(int value) {#setTimeout-int-}
```
public abstract void setTimeout(int value)
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

