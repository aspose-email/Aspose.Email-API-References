---
title: AutodiscoverServiceBase
second_title: Aspose.Email for Java API Reference
description:  Represents an abstract binding to an Autodiscover Service.
type: docs
weight: 74
url: /java/com.aspose.email/autodiscoverservicebase/
---
**Inheritance:**
java.lang.Object
```
public abstract class AutodiscoverServiceBase
```

Represents an abstract binding to an Autodiscover Service.
## Fields

| Field | Description |
| --- | --- |
| [OnSerializeCustomSoapHeaders](#OnSerializeCustomSoapHeaders) |  |
## Methods

| Method | Description |
| --- | --- |
| [getLogFileName()](#getLogFileName--) | Gets or sets log file name |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Gets or sets log file name |
| [getUseDateInLogFileName()](#getUseDateInLogFileName--) | Gets or sets value which indicates if date has to be used in log file name. |
| [setUseDateInLogFileName(boolean value)](#setUseDateInLogFileName-boolean-) | Gets or sets value which indicates if date has to be used in log file name. |
| [getCookieContainer()](#getCookieContainer--) | Gets or sets the cookie container. |
| [setCookieContainer(System.Net.CookieContainer value)](#setCookieContainer-com.aspose.ms.System.Net.CookieContainer-) | Gets or sets the cookie container. |
| [getSendClientLatencies()](#getSendClientLatencies--) | Gets or sets a value indicating whether client latency info is push to server. |
| [setSendClientLatencies(boolean value)](#setSendClientLatencies-boolean-) | Gets or sets a value indicating whether client latency info is push to server. |
| [getCredentials()](#getCredentials--) | Gets or sets the credentials used to authenticate with the Exchange Web Services. |
| [setCredentials(System.Net.ICredentials value)](#setCredentials-com.aspose.ms.System.Net.ICredentials-) | Gets or sets the credentials used to authenticate with the Exchange Web Services. |
| [getUseDefaultCredentials()](#getUseDefaultCredentials--) | Gets or sets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. |
| [setUseDefaultCredentials(boolean value)](#setUseDefaultCredentials-boolean-) | Gets or sets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. |
| [getTimeout()](#getTimeout--) | Gets or sets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. |
| [getPreAuthenticate()](#getPreAuthenticate--) | Gets or sets a value that indicates whether HTTP pre-authentication should be performed. |
| [setPreAuthenticate(boolean value)](#setPreAuthenticate-boolean-) | Gets or sets a value that indicates whether HTTP pre-authentication should be performed. |
| [getAcceptGzipEncoding()](#getAcceptGzipEncoding--) | Gets or sets a value indicating whether GZip compression encoding should be accepted. |
| [setAcceptGzipEncoding(boolean value)](#setAcceptGzipEncoding-boolean-) | Gets or sets a value indicating whether GZip compression encoding should be accepted. |
| [getRequestedServerVersion()](#getRequestedServerVersion--) | Gets the requested server version. |
| [getUserAgent()](#getUserAgent--) | Gets or sets the user agent. |
| [setUserAgent(String value)](#setUserAgent-java.lang.String-) | Gets or sets the user agent. |
| [getServerInfo()](#getServerInfo--) | Gets information associated with the server that processed the last request. |
| [getWebProxy()](#getWebProxy--) | Gets or sets the web proxy that should be used when sending requests to EWS. |
| [setWebProxy(System.Net.IWebProxy value)](#setWebProxy-com.aspose.ms.System.Net.IWebProxy-) | Gets or sets the web proxy that should be used when sending requests to EWS. |
| [getKeepAlive()](#getKeepAlive--) | Gets or sets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive |
| [setKeepAlive(boolean value)](#setKeepAlive-boolean-) | Gets or sets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive |
| [getConnectionGroupName()](#getConnectionGroupName--) | Gets or sets the name of the connection group for the request. |
| [setConnectionGroupName(String value)](#setConnectionGroupName-java.lang.String-) | Gets or sets the name of the connection group for the request. |
| [getClientRequestId()](#getClientRequestId--) | Gets or sets the request id for the request. |
| [setClientRequestId(String value)](#setClientRequestId-java.lang.String-) | Gets or sets the request id for the request. |
| [getReturnClientRequestId()](#getReturnClientRequestId--) | Gets or sets a flag to indicate whether the client requires the server side to return the request id. |
| [setReturnClientRequestId(boolean value)](#setReturnClientRequestId-boolean-) | Gets or sets a flag to indicate whether the client requires the server side to return the request id. |
| [getHttpHeaders()](#getHttpHeaders--) | Gets a collection of HTTP headers that will be sent with each request to EWS. |
| [getHttpResponseHeaders()](#getHttpResponseHeaders--) | Gets a collection of HTTP headers from the last response. |
### OnSerializeCustomSoapHeaders {#OnSerializeCustomSoapHeaders}
```
public final Event<AutodiscoverServiceBase.CustomXmlSerializationDelegate> OnSerializeCustomSoapHeaders
```


### getLogFileName() {#getLogFileName--}
```
public final String getLogFileName()
```


Gets or sets log file name

**Returns:**
java.lang.String
### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public final void setLogFileName(String value)
```


Gets or sets log file name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getUseDateInLogFileName() {#getUseDateInLogFileName--}
```
public final boolean getUseDateInLogFileName()
```


Gets or sets value which indicates if date has to be used in log file name.

**Returns:**
boolean
### setUseDateInLogFileName(boolean value) {#setUseDateInLogFileName-boolean-}
```
public final void setUseDateInLogFileName(boolean value)
```


Gets or sets value which indicates if date has to be used in log file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCookieContainer() {#getCookieContainer--}
```
public final System.Net.CookieContainer getCookieContainer()
```


Gets or sets the cookie container.

Value: The cookie container.

**Returns:**
com.aspose.ms.System.Net.CookieContainer
### setCookieContainer(System.Net.CookieContainer value) {#setCookieContainer-com.aspose.ms.System.Net.CookieContainer-}
```
public final void setCookieContainer(System.Net.CookieContainer value)
```


Gets or sets the cookie container.

Value: The cookie container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.CookieContainer |  |

### getSendClientLatencies() {#getSendClientLatencies--}
```
public final boolean getSendClientLatencies()
```


Gets or sets a value indicating whether client latency info is push to server.

**Returns:**
boolean
### setSendClientLatencies(boolean value) {#setSendClientLatencies-boolean-}
```
public final void setSendClientLatencies(boolean value)
```


Gets or sets a value indicating whether client latency info is push to server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCredentials() {#getCredentials--}
```
public final System.Net.ICredentials getCredentials()
```


Gets or sets the credentials used to authenticate with the Exchange Web Services. Setting the Credentials property automatically sets the UseDefaultCredentials to false.

**Returns:**
com.aspose.ms.System.Net.ICredentials
### setCredentials(System.Net.ICredentials value) {#setCredentials-com.aspose.ms.System.Net.ICredentials-}
```
public final void setCredentials(System.Net.ICredentials value)
```


Gets or sets the credentials used to authenticate with the Exchange Web Services. Setting the Credentials property automatically sets the UseDefaultCredentials to false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.ICredentials |  |

### getUseDefaultCredentials() {#getUseDefaultCredentials--}
```
public final boolean getUseDefaultCredentials()
```


Gets or sets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. Setting UseDefaultCredentials to true automatically sets the Credentials property to null.

**Returns:**
boolean
### setUseDefaultCredentials(boolean value) {#setUseDefaultCredentials-boolean-}
```
public final void setUseDefaultCredentials(boolean value)
```


Gets or sets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. Setting UseDefaultCredentials to true automatically sets the Credentials property to null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Gets or sets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. Defaults to 100000.

**Returns:**
int
### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Gets or sets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. Defaults to 100000.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPreAuthenticate() {#getPreAuthenticate--}
```
public final boolean getPreAuthenticate()
```


Gets or sets a value that indicates whether HTTP pre-authentication should be performed.

**Returns:**
boolean
### setPreAuthenticate(boolean value) {#setPreAuthenticate-boolean-}
```
public final void setPreAuthenticate(boolean value)
```


Gets or sets a value that indicates whether HTTP pre-authentication should be performed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAcceptGzipEncoding() {#getAcceptGzipEncoding--}
```
public final boolean getAcceptGzipEncoding()
```


Gets or sets a value indicating whether GZip compression encoding should be accepted.

--------------------

This value will tell the server that the client is able to handle GZip compression encoding. The server will only send Gzip compressed content if it has been configured to do so.

**Returns:**
boolean
### setAcceptGzipEncoding(boolean value) {#setAcceptGzipEncoding-boolean-}
```
public final void setAcceptGzipEncoding(boolean value)
```


Gets or sets a value indicating whether GZip compression encoding should be accepted.

--------------------

This value will tell the server that the client is able to handle GZip compression encoding. The server will only send Gzip compressed content if it has been configured to do so.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRequestedServerVersion() {#getRequestedServerVersion--}
```
public final int getRequestedServerVersion()
```


Gets the requested server version.

Value: The requested server version.

**Returns:**
int
### getUserAgent() {#getUserAgent--}
```
public final String getUserAgent()
```


Gets or sets the user agent.

Value: The user agent.

**Returns:**
java.lang.String
### setUserAgent(String value) {#setUserAgent-java.lang.String-}
```
public final void setUserAgent(String value)
```


Gets or sets the user agent.

Value: The user agent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getServerInfo() {#getServerInfo--}
```
public final ServerVersionInfo getServerInfo()
```


Gets information associated with the server that processed the last request. Will be null if no requests have been processed.

**Returns:**
com.microsoft.schemas.exchange.services._2006.types.ServerVersionInfo
### getWebProxy() {#getWebProxy--}
```
public final System.Net.IWebProxy getWebProxy()
```


Gets or sets the web proxy that should be used when sending requests to EWS. Set this property to null to use the default web proxy.

**Returns:**
com.aspose.ms.System.Net.IWebProxy
### setWebProxy(System.Net.IWebProxy value) {#setWebProxy-com.aspose.ms.System.Net.IWebProxy-}
```
public final void setWebProxy(System.Net.IWebProxy value)
```


Gets or sets the web proxy that should be used when sending requests to EWS. Set this property to null to use the default web proxy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.IWebProxy |  |

### getKeepAlive() {#getKeepAlive--}
```
public final boolean getKeepAlive()
```


Gets or sets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive

**Returns:**
boolean
### setKeepAlive(boolean value) {#setKeepAlive-boolean-}
```
public final void setKeepAlive(boolean value)
```


Gets or sets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getConnectionGroupName() {#getConnectionGroupName--}
```
public final String getConnectionGroupName()
```


Gets or sets the name of the connection group for the request.

**Returns:**
java.lang.String
### setConnectionGroupName(String value) {#setConnectionGroupName-java.lang.String-}
```
public final void setConnectionGroupName(String value)
```


Gets or sets the name of the connection group for the request.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getClientRequestId() {#getClientRequestId--}
```
public final String getClientRequestId()
```


Gets or sets the request id for the request.

**Returns:**
java.lang.String
### setClientRequestId(String value) {#setClientRequestId-java.lang.String-}
```
public final void setClientRequestId(String value)
```


Gets or sets the request id for the request.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getReturnClientRequestId() {#getReturnClientRequestId--}
```
public final boolean getReturnClientRequestId()
```


Gets or sets a flag to indicate whether the client requires the server side to return the request id.

**Returns:**
boolean
### setReturnClientRequestId(boolean value) {#setReturnClientRequestId-boolean-}
```
public final void setReturnClientRequestId(boolean value)
```


Gets or sets a flag to indicate whether the client requires the server side to return the request id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHttpHeaders() {#getHttpHeaders--}
```
public final System.Collections.Generic.IGenericDictionary<String,String> getHttpHeaders()
```


Gets a collection of HTTP headers that will be sent with each request to EWS.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String>
### getHttpResponseHeaders() {#getHttpResponseHeaders--}
```
public final System.Collections.Generic.IGenericDictionary<String,String> getHttpResponseHeaders()
```


Gets a collection of HTTP headers from the last response.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String>
