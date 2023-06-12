---
title: IBaseGmailClient
second_title: Aspose.Email for Java API Reference
description: Interface for base class of Gmail client
type: docs
weight: 737
url: /java/com.aspose.email/ibasegmailclient/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public interface IBaseGmailClient extends System.IDisposable, Closeable
```

Interface for base class of Gmail client
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [getAccessToken()](#getAccessToken--) | Gets or sets OAuth 2.0 bearer token |
| [getDefaultEmail()](#getDefaultEmail--) | Gets default email address |
| [getProxy()](#getProxy--) | Gets or sets the proxy. |
| [getTimeout()](#getTimeout--) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [refreshToken()](#refreshToken--) | Refresh access token |
| [setAccessToken(String value)](#setAccessToken-java.lang.String-) | Gets or sets OAuth 2.0 bearer token |
| [setProxy(System.Net.IWebProxy value)](#setProxy-com.aspose.ms.System.Net.IWebProxy-) | Gets or sets the proxy. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the number of milliseconds to wait before the operation times out. |
### close() {#close--}
```
public abstract void close()
```




### getAccessToken() {#getAccessToken--}
```
public abstract String getAccessToken()
```


Gets or sets OAuth 2.0 bearer token

**Returns:**
java.lang.String
### getDefaultEmail() {#getDefaultEmail--}
```
public abstract String getDefaultEmail()
```


Gets default email address

**Returns:**
java.lang.String
### getProxy() {#getProxy--}
```
public abstract System.Net.IWebProxy getProxy()
```


Gets or sets the proxy.

**Returns:**
com.aspose.ms.System.Net.IWebProxy
### getTimeout() {#getTimeout--}
```
public abstract int getTimeout()
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

**Returns:**
int
### refreshToken() {#refreshToken--}
```
public abstract void refreshToken()
```


Refresh access token

### setAccessToken(String value) {#setAccessToken-java.lang.String-}
```
public abstract void setAccessToken(String value)
```


Gets or sets OAuth 2.0 bearer token

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setProxy(System.Net.IWebProxy value) {#setProxy-com.aspose.ms.System.Net.IWebProxy-}
```
public abstract void setProxy(System.Net.IWebProxy value)
```


Gets or sets the proxy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.IWebProxy |  |

### setTimeout(int value) {#setTimeout-int-}
```
public abstract void setTimeout(int value)
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

