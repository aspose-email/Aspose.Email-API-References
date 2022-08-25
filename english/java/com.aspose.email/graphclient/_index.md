---
title: GraphClient
second_title: Aspose.Email for Java API Reference
description:  Provides access to MS Exchange Server Office365 by using REST API.
type: docs
weight: 280
url: /java/com.aspose.email/graphclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public abstract class GraphClient implements System.IDisposable, Closeable
```

Provides access to MS Exchange Server (Office365) by using REST API.
## Methods

| Method | Description |
| --- | --- |
| [getClient(IMultipleServicesTokenProvider tokenProvider, String tenantId)](#getClient-com.aspose.email.IMultipleServicesTokenProvider-java.lang.String-) | Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class |
| [getClient(IMultipleServicesTokenProvider tokenProvider)](#getClient-com.aspose.email.IMultipleServicesTokenProvider-) | Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class |
| [getClient(ITokenProvider tokenProvider, String tenantId)](#getClient-com.aspose.email.ITokenProvider-java.lang.String-) | Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class |
| [getClient(ITokenProvider tokenProvider)](#getClient-com.aspose.email.ITokenProvider-) | Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class |
| [getProxy()](#getProxy--) | Gets or sets data to proxy access to Exchange server. |
| [setProxy(System.Net.IWebProxy value)](#setProxy-com.aspose.ms.System.Net.IWebProxy-) | Gets or sets data to proxy access to Exchange server. |
| [getTimeout()](#getTimeout--) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [getMultipleServicesTokenProvider()](#getMultipleServicesTokenProvider--) | Gets or sets an object allows to retrieve OAuth access token. |
| [setMultipleServicesTokenProvider(IMultipleServicesTokenProvider value)](#setMultipleServicesTokenProvider-com.aspose.email.IMultipleServicesTokenProvider-) | Gets or sets an object allows to retrieve OAuth access token. |
| [getTokenProvider()](#getTokenProvider--) | Gets or sets an object allows to retrieve OAuth access token. |
| [setTokenProvider(ITokenProvider value)](#setTokenProvider-com.aspose.email.ITokenProvider-) | Gets or sets an object allows to retrieve OAuth access token. |
| [getTenantId()](#getTenantId--) | Gets or sets tenant identifier |
| [setTenantId(String value)](#setTenantId-java.lang.String-) | Gets or sets tenant identifier |
| [getResourceId()](#getResourceId--) | Gets or sets resource id. |
| [setResourceId(String value)](#setResourceId-java.lang.String-) | Gets or sets resource id. |
| [getResource()](#getResource--) | Gets or sets resource type. |
| [setResource(int value)](#setResource-int-) | Gets or sets resource type. |
| [getEndpoint()](#getEndpoint--) | Gets or sets Endpoint URL. |
| [setEndpoint(String value)](#setEndpoint-java.lang.String-) | Gets or sets Endpoint URL. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [close()](#close--) |  |
### getClient(IMultipleServicesTokenProvider tokenProvider, String tenantId) {#getClient-com.aspose.email.IMultipleServicesTokenProvider-java.lang.String-}
```
public static IGraphClient getClient(IMultipleServicesTokenProvider tokenProvider, String tenantId)
```


Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tokenProvider | [IMultipleServicesTokenProvider](../../com.aspose.email/imultipleservicestokenprovider) | Token provider allows to retrieve OAuth access token |
| tenantId | java.lang.String | A tenant is representation of an organization. It's a dedicated instance of Azure AD that an organization or app developer receives when the organization or app developer, creates a relationship with Microsoft like signing up for Azure, Microsoft Intune, or Microsoft 365. |

**Returns:**
[IGraphClient](../../com.aspose.email/igraphclient) - Returns IGraphClient object
### getClient(IMultipleServicesTokenProvider tokenProvider) {#getClient-com.aspose.email.IMultipleServicesTokenProvider-}
```
public static IGraphClient getClient(IMultipleServicesTokenProvider tokenProvider)
```


Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tokenProvider | [IMultipleServicesTokenProvider](../../com.aspose.email/imultipleservicestokenprovider) | Token provider allows to retrieve OAuth access token |

**Returns:**
[IGraphClient](../../com.aspose.email/igraphclient) - Returns IGraphClient object
### getClient(ITokenProvider tokenProvider, String tenantId) {#getClient-com.aspose.email.ITokenProvider-java.lang.String-}
```
public static IGraphClient getClient(ITokenProvider tokenProvider, String tenantId)
```


Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tokenProvider | [ITokenProvider](../../com.aspose.email/itokenprovider) | Token provider allows to retrieve OAuth access token |
| tenantId | java.lang.String | A tenant is representation of an organization. It's a dedicated instance of Azure AD that an organization or app developer receives when the organization or app developer, creates a relationship with Microsoft like signing up for Azure, Microsoft Intune, or Microsoft 365. |

**Returns:**
[IGraphClient](../../com.aspose.email/igraphclient) - Returns IGraphClient object
### getClient(ITokenProvider tokenProvider) {#getClient-com.aspose.email.ITokenProvider-}
```
public static IGraphClient getClient(ITokenProvider tokenProvider)
```


Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tokenProvider | [ITokenProvider](../../com.aspose.email/itokenprovider) | Token provider allows to retrieve OAuth access token |

**Returns:**
[IGraphClient](../../com.aspose.email/igraphclient) - Returns IGraphClient object
### getProxy() {#getProxy--}
```
public System.Net.IWebProxy getProxy()
```


Gets or sets data to proxy access to Exchange server.

**Returns:**
com.aspose.ms.System.Net.IWebProxy
### setProxy(System.Net.IWebProxy value) {#setProxy-com.aspose.ms.System.Net.IWebProxy-}
```
public void setProxy(System.Net.IWebProxy value)
```


Gets or sets data to proxy access to Exchange server.

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

### getMultipleServicesTokenProvider() {#getMultipleServicesTokenProvider--}
```
public IMultipleServicesTokenProvider getMultipleServicesTokenProvider()
```


Gets or sets an object allows to retrieve OAuth access token.

**Returns:**
[IMultipleServicesTokenProvider](../../com.aspose.email/imultipleservicestokenprovider)
### setMultipleServicesTokenProvider(IMultipleServicesTokenProvider value) {#setMultipleServicesTokenProvider-com.aspose.email.IMultipleServicesTokenProvider-}
```
public void setMultipleServicesTokenProvider(IMultipleServicesTokenProvider value)
```


Gets or sets an object allows to retrieve OAuth access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMultipleServicesTokenProvider](../../com.aspose.email/imultipleservicestokenprovider) |  |

### getTokenProvider() {#getTokenProvider--}
```
public ITokenProvider getTokenProvider()
```


Gets or sets an object allows to retrieve OAuth access token.

**Returns:**
[ITokenProvider](../../com.aspose.email/itokenprovider)
### setTokenProvider(ITokenProvider value) {#setTokenProvider-com.aspose.email.ITokenProvider-}
```
public void setTokenProvider(ITokenProvider value)
```


Gets or sets an object allows to retrieve OAuth access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITokenProvider](../../com.aspose.email/itokenprovider) |  |

### getTenantId() {#getTenantId--}
```
public String getTenantId()
```


Gets or sets tenant identifier

**Returns:**
java.lang.String
### setTenantId(String value) {#setTenantId-java.lang.String-}
```
public void setTenantId(String value)
```


Gets or sets tenant identifier

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getResourceId() {#getResourceId--}
```
public String getResourceId()
```


Gets or sets resource id. For instance for users it may be user principal name (UPN) or user id

**Returns:**
java.lang.String
### setResourceId(String value) {#setResourceId-java.lang.String-}
```
public void setResourceId(String value)
```


Gets or sets resource id. For instance for users it may be user principal name (UPN) or user id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getResource() {#getResource--}
```
public int getResource()
```


Gets or sets resource type.

**Returns:**
int
### setResource(int value) {#setResource-int-}
```
public void setResource(int value)
```


Gets or sets resource type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEndpoint() {#getEndpoint--}
```
public String getEndpoint()
```


Gets or sets Endpoint URL.

**Returns:**
java.lang.String
### setEndpoint(String value) {#setEndpoint-java.lang.String-}
```
public void setEndpoint(String value)
```


Gets or sets Endpoint URL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### close() {#close--}
```
public void close()
```




