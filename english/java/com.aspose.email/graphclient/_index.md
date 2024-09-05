---
title: GraphClient
second_title: Aspose.Email for Java API Reference
description: Provides access to MS Exchange Server Office365 by using REST API.
type: docs
weight: 283
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
| [close()](#close--) |  |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClient(IMultipleServicesTokenProvider tokenProvider)](#getClient-com.aspose.email.IMultipleServicesTokenProvider-) | Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class |
| [getClient(IMultipleServicesTokenProvider tokenProvider, String tenantId)](#getClient-com.aspose.email.IMultipleServicesTokenProvider-java.lang.String-) | Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class |
| [getClient(ITokenProvider tokenProvider)](#getClient-com.aspose.email.ITokenProvider-) | Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class |
| [getClient(ITokenProvider tokenProvider, String tenantId)](#getClient-com.aspose.email.ITokenProvider-java.lang.String-) | Initializes a new instance of the [GraphClient](../../com.aspose.email/graphclient) based class |
| [getEndpoint()](#getEndpoint--) | Gets or sets Endpoint URL. |
| [getMultipleServicesTokenProvider()](#getMultipleServicesTokenProvider--) | Gets or sets an object allows to retrieve OAuth access token. |
| [getProxy()](#getProxy--) | Gets or sets data to proxy access to Exchange server. |
| [getResource()](#getResource--) | Gets or sets resource type. |
| [getResourceId()](#getResourceId--) | Gets or sets resource id. |
| [getTenantId()](#getTenantId--) | Gets or sets tenant identifier |
| [getTimeout()](#getTimeout--) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [getTokenProvider()](#getTokenProvider--) | Gets or sets an object allows to retrieve OAuth access token. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEndpoint(String value)](#setEndpoint-java.lang.String-) | Gets or sets Endpoint URL. |
| [setMultipleServicesTokenProvider(IMultipleServicesTokenProvider value)](#setMultipleServicesTokenProvider-com.aspose.email.IMultipleServicesTokenProvider-) | Gets or sets an object allows to retrieve OAuth access token. |
| [setProxy(System.Net.IWebProxy value)](#setProxy-com.aspose.ms.System.Net.IWebProxy-) | Gets or sets data to proxy access to Exchange server. |
| [setResource(int value)](#setResource-int-) | Gets or sets resource type. |
| [setResourceId(String value)](#setResourceId-java.lang.String-) | Gets or sets resource id. |
| [setTenantId(String value)](#setTenantId-java.lang.String-) | Gets or sets tenant identifier |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [setTokenProvider(ITokenProvider value)](#setTokenProvider-com.aspose.email.ITokenProvider-) | Gets or sets an object allows to retrieve OAuth access token. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

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
### getEndpoint() {#getEndpoint--}
```
public String getEndpoint()
```


Gets or sets Endpoint URL.

**Returns:**
java.lang.String
### getMultipleServicesTokenProvider() {#getMultipleServicesTokenProvider--}
```
public IMultipleServicesTokenProvider getMultipleServicesTokenProvider()
```


Gets or sets an object allows to retrieve OAuth access token.

**Returns:**
[IMultipleServicesTokenProvider](../../com.aspose.email/imultipleservicestokenprovider)
### getProxy() {#getProxy--}
```
public System.Net.IWebProxy getProxy()
```


Gets or sets data to proxy access to Exchange server.

**Returns:**
com.aspose.ms.System.Net.IWebProxy
### getResource() {#getResource--}
```
public int getResource()
```


Gets or sets resource type.

**Returns:**
int
### getResourceId() {#getResourceId--}
```
public String getResourceId()
```


Gets or sets resource id. For instance for users it may be user principal name (UPN) or user id

**Returns:**
java.lang.String
### getTenantId() {#getTenantId--}
```
public String getTenantId()
```


Gets or sets tenant identifier

**Returns:**
java.lang.String
### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

**Returns:**
int
### getTokenProvider() {#getTokenProvider--}
```
public ITokenProvider getTokenProvider()
```


Gets or sets an object allows to retrieve OAuth access token.

**Returns:**
[ITokenProvider](../../com.aspose.email/itokenprovider)
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




### setEndpoint(String value) {#setEndpoint-java.lang.String-}
```
public void setEndpoint(String value)
```


Gets or sets Endpoint URL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMultipleServicesTokenProvider(IMultipleServicesTokenProvider value) {#setMultipleServicesTokenProvider-com.aspose.email.IMultipleServicesTokenProvider-}
```
public void setMultipleServicesTokenProvider(IMultipleServicesTokenProvider value)
```


Gets or sets an object allows to retrieve OAuth access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMultipleServicesTokenProvider](../../com.aspose.email/imultipleservicestokenprovider) |  |

### setProxy(System.Net.IWebProxy value) {#setProxy-com.aspose.ms.System.Net.IWebProxy-}
```
public void setProxy(System.Net.IWebProxy value)
```


Gets or sets data to proxy access to Exchange server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.IWebProxy |  |

### setResource(int value) {#setResource-int-}
```
public void setResource(int value)
```


Gets or sets resource type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setResourceId(String value) {#setResourceId-java.lang.String-}
```
public void setResourceId(String value)
```


Gets or sets resource id. For instance for users it may be user principal name (UPN) or user id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTenantId(String value) {#setTenantId-java.lang.String-}
```
public void setTenantId(String value)
```


Gets or sets tenant identifier

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTokenProvider(ITokenProvider value) {#setTokenProvider-com.aspose.email.ITokenProvider-}
```
public void setTokenProvider(ITokenProvider value)
```


Gets or sets an object allows to retrieve OAuth access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITokenProvider](../../com.aspose.email/itokenprovider) |  |

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

