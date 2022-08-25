---
title: GmailClient
second_title: Aspose.Email for Java API Reference
description:  Base class for Gmail client
type: docs
weight: 277
url: /java/com.aspose.email/gmailclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IBaseGmailClient](../../com.aspose.email/ibasegmailclient)
```
public abstract class GmailClient implements IBaseGmailClient
```

Base class for Gmail client
## Methods

| Method | Description |
| --- | --- |
| [useJDKHTTP(boolean value)](#useJDKHTTP-boolean-) | Sets value indicating whether JDK HTTP is used. |
| [getInstance(String accessToken, String defaultEmail)](#getInstance-java.lang.String-java.lang.String-) | Gets instance of Gmail client |
| [getInstance(String accessToken, System.Net.IWebProxy proxy, String defaultEmail)](#getInstance-java.lang.String-com.aspose.ms.System.Net.IWebProxy-java.lang.String-) | Gets instance of Gmail client |
| [getInstance(String clientId, String clientSecret, String refreshToken, String defaultEmail)](#getInstance-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Gets instance of Gmail client |
| [getInstance(String clientId, String clientSecret, String refreshToken, System.Net.IWebProxy proxy, String defaultEmail)](#getInstance-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.Net.IWebProxy-java.lang.String-) | Gets instance of Gmail client |
| [refreshToken()](#refreshToken--) | Refresh access token |
| [getDefaultEmail()](#getDefaultEmail--) | Gets or sets default email address |
| [getAccessToken()](#getAccessToken--) | Gets or sets OAuth 2.0 access token In case if refresh token is set, access token is generated automatically. |
| [setAccessToken(String value)](#setAccessToken-java.lang.String-) | Gets or sets OAuth 2.0 access token In case if refresh token is set, access token is generated automatically. |
| [getProxy()](#getProxy--) | Gets or sets the proxy. |
| [setProxy(System.Net.IWebProxy value)](#setProxy-com.aspose.ms.System.Net.IWebProxy-) | Gets or sets the proxy. |
| [getTimeout()](#getTimeout--) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [getDefaultTimeout()](#getDefaultTimeout--) | Gets or sets the default timeout value for ActiveSync client instances The default value is 100,000 milliseconds (100 seconds). |
| [setDefaultTimeout(int value)](#setDefaultTimeout-int-) | Gets or sets the default timeout value for ActiveSync client instances The default value is 100,000 milliseconds (100 seconds). |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [close()](#close--) |  |
### useJDKHTTP(boolean value) {#useJDKHTTP-boolean-}
```
public static void useJDKHTTP(boolean value)
```


Sets value indicating whether JDK HTTP is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | True if JDK HTTP should be used. |

### getInstance(String accessToken, String defaultEmail) {#getInstance-java.lang.String-java.lang.String-}
```
public static IGmailClient getInstance(String accessToken, String defaultEmail)
```


Gets instance of Gmail client

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| accessToken | java.lang.String | OAuth 2.0 access token |
| defaultEmail | java.lang.String | Default email address |

**Returns:**
[IGmailClient](../../com.aspose.email/igmailclient) - Returns instance of Gmail client
### getInstance(String accessToken, System.Net.IWebProxy proxy, String defaultEmail) {#getInstance-java.lang.String-com.aspose.ms.System.Net.IWebProxy-java.lang.String-}
```
public static IGmailClient getInstance(String accessToken, System.Net.IWebProxy proxy, String defaultEmail)
```


Gets instance of Gmail client

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| accessToken | java.lang.String | OAuth 2.0 access token |
| proxy | com.aspose.ms.System.Net.IWebProxy | IWebProxy for Gmail client |
| defaultEmail | java.lang.String | Default email address |

**Returns:**
[IGmailClient](../../com.aspose.email/igmailclient) - Returns instance of Gmail client
### getInstance(String clientId, String clientSecret, String refreshToken, String defaultEmail) {#getInstance-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public static IGmailClient getInstance(String clientId, String clientSecret, String refreshToken, String defaultEmail)
```


Gets instance of Gmail client

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| clientId | java.lang.String | The client ID obtained from the Google Cloud Console during application registration. |
| clientSecret | java.lang.String | The client secret obtained during application registration. |
| refreshToken | java.lang.String | OAuth 2.0 refresh token |
| defaultEmail | java.lang.String | Default email address |

**Returns:**
[IGmailClient](../../com.aspose.email/igmailclient) - Returns instance of Gmail client
### getInstance(String clientId, String clientSecret, String refreshToken, System.Net.IWebProxy proxy, String defaultEmail) {#getInstance-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.Net.IWebProxy-java.lang.String-}
```
public static IGmailClient getInstance(String clientId, String clientSecret, String refreshToken, System.Net.IWebProxy proxy, String defaultEmail)
```


Gets instance of Gmail client

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| clientId | java.lang.String | The client ID obtained from the Google Cloud Console during application registration. |
| clientSecret | java.lang.String | The client secret obtained during application registration. |
| refreshToken | java.lang.String | OAuth 2.0 refresh token |
| proxy | com.aspose.ms.System.Net.IWebProxy | IWebProxy for Gmail client |
| defaultEmail | java.lang.String | Default email address |

**Returns:**
[IGmailClient](../../com.aspose.email/igmailclient) - Returns instance of Gmail client
### refreshToken() {#refreshToken--}
```
public void refreshToken()
```


Refresh access token

### getDefaultEmail() {#getDefaultEmail--}
```
public String getDefaultEmail()
```


Gets or sets default email address

**Returns:**
java.lang.String
### getAccessToken() {#getAccessToken--}
```
public String getAccessToken()
```


Gets or sets OAuth 2.0 access token In case if refresh token is set, access token is generated automatically.

**Returns:**
java.lang.String
### setAccessToken(String value) {#setAccessToken-java.lang.String-}
```
public void setAccessToken(String value)
```


Gets or sets OAuth 2.0 access token In case if refresh token is set, access token is generated automatically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getProxy() {#getProxy--}
```
public System.Net.IWebProxy getProxy()
```


Gets or sets the proxy.

**Returns:**
com.aspose.ms.System.Net.IWebProxy
### setProxy(System.Net.IWebProxy value) {#setProxy-com.aspose.ms.System.Net.IWebProxy-}
```
public void setProxy(System.Net.IWebProxy value)
```


Gets or sets the proxy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.IWebProxy |  |

### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

**Returns:**
int
### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultTimeout() {#getDefaultTimeout--}
```
public static int getDefaultTimeout()
```


Gets or sets the default timeout value for ActiveSync client instances The default value is 100,000 milliseconds (100 seconds).

**Returns:**
int
### setDefaultTimeout(int value) {#setDefaultTimeout-int-}
```
public static void setDefaultTimeout(int value)
```


Gets or sets the default timeout value for ActiveSync client instances The default value is 100,000 milliseconds (100 seconds).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### close() {#close--}
```
public void close()
```




