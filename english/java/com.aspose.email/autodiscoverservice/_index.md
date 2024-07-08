---
title: AutodiscoverService
second_title: Aspose.Email for Java API Reference
description: Represents a binding to the Exchange Autodiscover Service.
type: docs
weight: 75
url: /java/com.aspose.email/autodiscoverservice/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AutodiscoverServiceBase](../../com.aspose.email/autodiscoverservicebase)
```
public final class AutodiscoverService extends AutodiscoverServiceBase
```

Represents a binding to the Exchange Autodiscover Service.
## Constructors

| Constructor | Description |
| --- | --- |
| [AutodiscoverService()](#AutodiscoverService--) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
| [AutodiscoverService(Integer requestedServerVersion)](#AutodiscoverService-java.lang.Integer-) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
| [AutodiscoverService(String domain)](#AutodiscoverService-java.lang.String-) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
| [AutodiscoverService(String domain, Integer requestedServerVersion)](#AutodiscoverService-java.lang.String-java.lang.Integer-) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
| [AutodiscoverService(URI url)](#AutodiscoverService-java.net.URI-) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
| [AutodiscoverService(URI url, Integer requestedServerVersion)](#AutodiscoverService-java.net.URI-java.lang.Integer-) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
## Fields

| Field | Description |
| --- | --- |
| [OnSerializeCustomSoapHeaders](#OnSerializeCustomSoapHeaders) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAcceptGzipEncoding()](#getAcceptGzipEncoding--) | Gets or sets a value indicating whether GZip compression encoding should be accepted. |
| [getClass()](#getClass--) |  |
| [getClientRequestId()](#getClientRequestId--) | Gets or sets the request id for the request. |
| [getConnectionGroupName()](#getConnectionGroupName--) | Gets or sets the name of the connection group for the request. |
| [getCookieContainer()](#getCookieContainer--) | Gets or sets the cookie container. |
| [getCredentials()](#getCredentials--) | Gets or sets the credentials used to authenticate with the Exchange Web Services. |
| [getDomain()](#getDomain--) | Gets or sets the domain this service is bound to. |
| [getEnableScpLookup()](#getEnableScpLookup--) | Gets or sets a value indicating whether the AutodiscoverService should perform SCP (ServiceConnectionPoint) record lookup when determining the Autodiscover service URL. |
| [getHttpHeaders()](#getHttpHeaders--) | Gets a collection of HTTP headers that will be sent with each request to EWS. |
| [getHttpResponseHeaders()](#getHttpResponseHeaders--) | Gets a collection of HTTP headers from the last response. |
| [getKeepAlive()](#getKeepAlive--) | Gets or sets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive |
| [getLogFileName()](#getLogFileName--) | Gets or sets log file name |
| [getPreAuthenticate()](#getPreAuthenticate--) | Gets or sets a value that indicates whether HTTP pre-authentication should be performed. |
| [getRedirectionUrlValidationCallback()](#getRedirectionUrlValidationCallback--) | Gets or sets the redirection URL validation callback. |
| [getRequestedServerVersion()](#getRequestedServerVersion--) | Gets the requested server version. |
| [getReturnClientRequestId()](#getReturnClientRequestId--) | Gets or sets a flag to indicate whether the client requires the server side to return the request id. |
| [getSendClientLatencies()](#getSendClientLatencies--) | Gets or sets a value indicating whether client latency info is push to server. |
| [getServerInfo()](#getServerInfo--) | Gets information associated with the server that processed the last request. |
| [getTimeout()](#getTimeout--) | Gets or sets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. |
| [getUrl()](#getUrl--) | Gets or sets the URL this service is bound to. |
| [getUseDateInLogFileName()](#getUseDateInLogFileName--) | Gets or sets value which indicates if date has to be used in log file name. |
| [getUseDefaultCredentials()](#getUseDefaultCredentials--) | Gets or sets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. |
| [getUserAgent()](#getUserAgent--) | Gets or sets the user agent. |
| [getUserSettings(String userSmtpAddress, Integer[] userSettingNames)](#getUserSettings-java.lang.String-java.lang.Integer...-) | Retrieves the specified settings for single SMTP address. |
| [getUsersSettings(System.Collections.Generic.IGenericEnumerable<String> userSmtpAddresses, Integer[] userSettingNames)](#getUsersSettings-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-java.lang.String--java.lang.Integer...-) | Retrieves the specified settings for a set of users. |
| [getWebProxy()](#getWebProxy--) | Gets or sets the web proxy that should be used when sending requests to EWS. |
| [hashCode()](#hashCode--) |  |
| [isExternal()](#isExternal--) | Gets a value indicating whether the Autodiscover service that URL points to is internal (inside the corporate network) or external (outside the corporate network). |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAcceptGzipEncoding(boolean value)](#setAcceptGzipEncoding-boolean-) | Gets or sets a value indicating whether GZip compression encoding should be accepted. |
| [setClientRequestId(String value)](#setClientRequestId-java.lang.String-) | Gets or sets the request id for the request. |
| [setConnectionGroupName(String value)](#setConnectionGroupName-java.lang.String-) | Gets or sets the name of the connection group for the request. |
| [setCookieContainer(System.Net.CookieContainer value)](#setCookieContainer-com.aspose.ms.System.Net.CookieContainer-) | Gets or sets the cookie container. |
| [setCredentials(System.Net.ICredentials value)](#setCredentials-com.aspose.ms.System.Net.ICredentials-) | Gets or sets the credentials used to authenticate with the Exchange Web Services. |
| [setDomain(String value)](#setDomain-java.lang.String-) | Gets or sets the domain this service is bound to. |
| [setEnableScpLookup(boolean value)](#setEnableScpLookup-boolean-) | Gets or sets a value indicating whether the AutodiscoverService should perform SCP (ServiceConnectionPoint) record lookup when determining the Autodiscover service URL. |
| [setKeepAlive(boolean value)](#setKeepAlive-boolean-) | Gets or sets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Gets or sets log file name |
| [setPreAuthenticate(boolean value)](#setPreAuthenticate-boolean-) | Gets or sets a value that indicates whether HTTP pre-authentication should be performed. |
| [setRedirectionUrlValidationCallback(AutodiscoverRedirectionUrlValidationCallback value)](#setRedirectionUrlValidationCallback-com.aspose.email.AutodiscoverRedirectionUrlValidationCallback-) | Gets or sets the redirection URL validation callback. |
| [setReturnClientRequestId(boolean value)](#setReturnClientRequestId-boolean-) | Gets or sets a flag to indicate whether the client requires the server side to return the request id. |
| [setSendClientLatencies(boolean value)](#setSendClientLatencies-boolean-) | Gets or sets a value indicating whether client latency info is push to server. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. |
| [setUrl(URI value)](#setUrl-java.net.URI-) | Gets or sets the URL this service is bound to. |
| [setUseDateInLogFileName(boolean value)](#setUseDateInLogFileName-boolean-) | Gets or sets value which indicates if date has to be used in log file name. |
| [setUseDefaultCredentials(boolean value)](#setUseDefaultCredentials-boolean-) | Gets or sets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. |
| [setUserAgent(String value)](#setUserAgent-java.lang.String-) | Gets or sets the user agent. |
| [setWebProxy(System.Net.IWebProxy value)](#setWebProxy-com.aspose.ms.System.Net.IWebProxy-) | Gets or sets the web proxy that should be used when sending requests to EWS. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutodiscoverService() {#AutodiscoverService--}
```
public AutodiscoverService()
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

### AutodiscoverService(Integer requestedServerVersion) {#AutodiscoverService-java.lang.Integer-}
```
public AutodiscoverService(Integer requestedServerVersion)
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| requestedServerVersion | java.lang.Integer | The requested server version. |

### AutodiscoverService(String domain) {#AutodiscoverService-java.lang.String-}
```
public AutodiscoverService(String domain)
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| domain | java.lang.String | The domain that will be used to determine the URL of the service. |

### AutodiscoverService(String domain, Integer requestedServerVersion) {#AutodiscoverService-java.lang.String-java.lang.Integer-}
```
public AutodiscoverService(String domain, Integer requestedServerVersion)
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| domain | java.lang.String | The domain that will be used to determine the URL of the service. |
| requestedServerVersion | java.lang.Integer | The requested server version. |

### AutodiscoverService(URI url) {#AutodiscoverService-java.net.URI-}
```
public AutodiscoverService(URI url)
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.net.URI | The URL of the service. |

### AutodiscoverService(URI url, Integer requestedServerVersion) {#AutodiscoverService-java.net.URI-java.lang.Integer-}
```
public AutodiscoverService(URI url, Integer requestedServerVersion)
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.net.URI | The URL of the service. |
| requestedServerVersion | java.lang.Integer | The requested server version. |

### OnSerializeCustomSoapHeaders {#OnSerializeCustomSoapHeaders}
```
public final Event<AutodiscoverServiceBase.CustomXmlSerializationDelegate> OnSerializeCustomSoapHeaders
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
### getAcceptGzipEncoding() {#getAcceptGzipEncoding--}
```
public final boolean getAcceptGzipEncoding()
```


Gets or sets a value indicating whether GZip compression encoding should be accepted.

--------------------

This value will tell the server that the client is able to handle GZip compression encoding. The server will only send Gzip compressed content if it has been configured to do so.

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClientRequestId() {#getClientRequestId--}
```
public final String getClientRequestId()
```


Gets or sets the request id for the request.

**Returns:**
java.lang.String
### getConnectionGroupName() {#getConnectionGroupName--}
```
public final String getConnectionGroupName()
```


Gets or sets the name of the connection group for the request.

**Returns:**
java.lang.String
### getCookieContainer() {#getCookieContainer--}
```
public final System.Net.CookieContainer getCookieContainer()
```


Gets or sets the cookie container.

Value: The cookie container.

**Returns:**
com.aspose.ms.System.Net.CookieContainer
### getCredentials() {#getCredentials--}
```
public final System.Net.ICredentials getCredentials()
```


Gets or sets the credentials used to authenticate with the Exchange Web Services. Setting the Credentials property automatically sets the UseDefaultCredentials to false.

**Returns:**
com.aspose.ms.System.Net.ICredentials
### getDomain() {#getDomain--}
```
public final String getDomain()
```


Gets or sets the domain this service is bound to. When this property is set, the domain name is used to automatically determine the Autodiscover service URL.

**Returns:**
java.lang.String
### getEnableScpLookup() {#getEnableScpLookup--}
```
public final boolean getEnableScpLookup()
```


Gets or sets a value indicating whether the AutodiscoverService should perform SCP (ServiceConnectionPoint) record lookup when determining the Autodiscover service URL.

**Returns:**
boolean
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
### getKeepAlive() {#getKeepAlive--}
```
public final boolean getKeepAlive()
```


Gets or sets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive

**Returns:**
boolean
### getLogFileName() {#getLogFileName--}
```
public final String getLogFileName()
```


Gets or sets log file name

**Returns:**
java.lang.String
### getPreAuthenticate() {#getPreAuthenticate--}
```
public final boolean getPreAuthenticate()
```


Gets or sets a value that indicates whether HTTP pre-authentication should be performed.

**Returns:**
boolean
### getRedirectionUrlValidationCallback() {#getRedirectionUrlValidationCallback--}
```
public final AutodiscoverRedirectionUrlValidationCallback getRedirectionUrlValidationCallback()
```


Gets or sets the redirection URL validation callback.

Value: The redirection URL validation callback.

**Returns:**
[AutodiscoverRedirectionUrlValidationCallback](../../com.aspose.email/autodiscoverredirectionurlvalidationcallback)
### getRequestedServerVersion() {#getRequestedServerVersion--}
```
public final int getRequestedServerVersion()
```


Gets the requested server version.

Value: The requested server version.

**Returns:**
int
### getReturnClientRequestId() {#getReturnClientRequestId--}
```
public final boolean getReturnClientRequestId()
```


Gets or sets a flag to indicate whether the client requires the server side to return the request id.

**Returns:**
boolean
### getSendClientLatencies() {#getSendClientLatencies--}
```
public final boolean getSendClientLatencies()
```


Gets or sets a value indicating whether client latency info is push to server.

**Returns:**
boolean
### getServerInfo() {#getServerInfo--}
```
public final ServerVersionInfo getServerInfo()
```


Gets information associated with the server that processed the last request. Will be null if no requests have been processed.

**Returns:**
com.microsoft.schemas.exchange.services._2006.types.ServerVersionInfo
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Gets or sets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. Defaults to 100000.

**Returns:**
int
### getUrl() {#getUrl--}
```
public final URI getUrl()
```


Gets or sets the URL this service is bound to.

**Returns:**
java.net.URI
### getUseDateInLogFileName() {#getUseDateInLogFileName--}
```
public final boolean getUseDateInLogFileName()
```


Gets or sets value which indicates if date has to be used in log file name.

**Returns:**
boolean
### getUseDefaultCredentials() {#getUseDefaultCredentials--}
```
public final boolean getUseDefaultCredentials()
```


Gets or sets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. Setting UseDefaultCredentials to true automatically sets the Credentials property to null.

**Returns:**
boolean
### getUserAgent() {#getUserAgent--}
```
public final String getUserAgent()
```


Gets or sets the user agent.

Value: The user agent.

**Returns:**
java.lang.String
### getUserSettings(String userSmtpAddress, Integer[] userSettingNames) {#getUserSettings-java.lang.String-java.lang.Integer...-}
```
public final GetUserSettingsResponse getUserSettings(String userSmtpAddress, Integer[] userSettingNames)
```


Retrieves the specified settings for single SMTP address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userSmtpAddress | java.lang.String | The SMTP addresses of the user. |
| userSettingNames | java.lang.Integer[] | The user setting names.

--------------------

This method handles will run the entire Autodiscover "discovery" algorithm and will follow address and URL redirections. |

**Returns:**
[GetUserSettingsResponse](../../com.aspose.email/getusersettingsresponse) - A UserResponse object containing the requested settings for the specified user.
### getUsersSettings(System.Collections.Generic.IGenericEnumerable<String> userSmtpAddresses, Integer[] userSettingNames) {#getUsersSettings-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-java.lang.String--java.lang.Integer...-}
```
public final GetUserSettingsResponseCollection getUsersSettings(System.Collections.Generic.IGenericEnumerable<String> userSmtpAddresses, Integer[] userSettingNames)
```


Retrieves the specified settings for a set of users.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userSmtpAddresses | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<java.lang.String> | The SMTP addresses of the users. |
| userSettingNames | java.lang.Integer[] | The user setting names. |

**Returns:**
[GetUserSettingsResponseCollection](../../com.aspose.email/getusersettingsresponsecollection) - A GetUserSettingsResponseCollection object containing the responses for each individual user.
### getWebProxy() {#getWebProxy--}
```
public final System.Net.IWebProxy getWebProxy()
```


Gets or sets the web proxy that should be used when sending requests to EWS. Set this property to null to use the default web proxy.

**Returns:**
com.aspose.ms.System.Net.IWebProxy
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExternal() {#isExternal--}
```
public final Boolean isExternal()
```


Gets a value indicating whether the Autodiscover service that URL points to is internal (inside the corporate network) or external (outside the corporate network).

--------------------

IsExternal is null in the following cases: - This instance has been created with a domain name and no method has been called, - This instance has been created with a URL.

**Returns:**
java.lang.Boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### setClientRequestId(String value) {#setClientRequestId-java.lang.String-}
```
public final void setClientRequestId(String value)
```


Gets or sets the request id for the request.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setConnectionGroupName(String value) {#setConnectionGroupName-java.lang.String-}
```
public final void setConnectionGroupName(String value)
```


Gets or sets the name of the connection group for the request.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setCredentials(System.Net.ICredentials value) {#setCredentials-com.aspose.ms.System.Net.ICredentials-}
```
public final void setCredentials(System.Net.ICredentials value)
```


Gets or sets the credentials used to authenticate with the Exchange Web Services. Setting the Credentials property automatically sets the UseDefaultCredentials to false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.ICredentials |  |

### setDomain(String value) {#setDomain-java.lang.String-}
```
public final void setDomain(String value)
```


Gets or sets the domain this service is bound to. When this property is set, the domain name is used to automatically determine the Autodiscover service URL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setEnableScpLookup(boolean value) {#setEnableScpLookup-boolean-}
```
public final void setEnableScpLookup(boolean value)
```


Gets or sets a value indicating whether the AutodiscoverService should perform SCP (ServiceConnectionPoint) record lookup when determining the Autodiscover service URL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setKeepAlive(boolean value) {#setKeepAlive-boolean-}
```
public final void setKeepAlive(boolean value)
```


Gets or sets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public final void setLogFileName(String value)
```


Gets or sets log file name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreAuthenticate(boolean value) {#setPreAuthenticate-boolean-}
```
public final void setPreAuthenticate(boolean value)
```


Gets or sets a value that indicates whether HTTP pre-authentication should be performed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRedirectionUrlValidationCallback(AutodiscoverRedirectionUrlValidationCallback value) {#setRedirectionUrlValidationCallback-com.aspose.email.AutodiscoverRedirectionUrlValidationCallback-}
```
public final void setRedirectionUrlValidationCallback(AutodiscoverRedirectionUrlValidationCallback value)
```


Gets or sets the redirection URL validation callback.

Value: The redirection URL validation callback.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AutodiscoverRedirectionUrlValidationCallback](../../com.aspose.email/autodiscoverredirectionurlvalidationcallback) |  |

### setReturnClientRequestId(boolean value) {#setReturnClientRequestId-boolean-}
```
public final void setReturnClientRequestId(boolean value)
```


Gets or sets a flag to indicate whether the client requires the server side to return the request id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSendClientLatencies(boolean value) {#setSendClientLatencies-boolean-}
```
public final void setSendClientLatencies(boolean value)
```


Gets or sets a value indicating whether client latency info is push to server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Gets or sets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. Defaults to 100000.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUrl(URI value) {#setUrl-java.net.URI-}
```
public final void setUrl(URI value)
```


Gets or sets the URL this service is bound to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.net.URI |  |

### setUseDateInLogFileName(boolean value) {#setUseDateInLogFileName-boolean-}
```
public final void setUseDateInLogFileName(boolean value)
```


Gets or sets value which indicates if date has to be used in log file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseDefaultCredentials(boolean value) {#setUseDefaultCredentials-boolean-}
```
public final void setUseDefaultCredentials(boolean value)
```


Gets or sets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. Setting UseDefaultCredentials to true automatically sets the Credentials property to null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### setWebProxy(System.Net.IWebProxy value) {#setWebProxy-com.aspose.ms.System.Net.IWebProxy-}
```
public final void setWebProxy(System.Net.IWebProxy value)
```


Gets or sets the web proxy that should be used when sending requests to EWS. Set this property to null to use the default web proxy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.IWebProxy |  |

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

