---
title: OAuthNetworkCredential
second_title: Aspose.Email for Java API Reference
description: Represents the NetworkCredential for OAuth authentication.
type: docs
weight: 533
url: /java/com.aspose.email/oauthnetworkcredential/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Net.NetworkCredential

**All Implemented Interfaces:**
com.aspose.ms.System.Net.ICredentialsByHost
```
public class OAuthNetworkCredential extends System.Net.NetworkCredential implements System.Net.ICredentialsByHost
```

Represents the NetworkCredential for OAuth authentication.
## Constructors

| Constructor | Description |
| --- | --- |
| [OAuthNetworkCredential(String accessToken)](#OAuthNetworkCredential-java.lang.String-) | Initializes a new instance of the [OAuthNetworkCredential](../../com.aspose.email/oauthnetworkcredential) class |
| [OAuthNetworkCredential(ITokenProvider tokenProvider)](#OAuthNetworkCredential-com.aspose.email.ITokenProvider-) | Initializes a new instance of the [OAuthNetworkCredential](../../com.aspose.email/oauthnetworkcredential) class |
| [OAuthNetworkCredential(String userName, String accessToken)](#OAuthNetworkCredential-java.lang.String-java.lang.String-) | Initializes a new instance of the [OAuthNetworkCredential](../../com.aspose.email/oauthnetworkcredential) class |
| [OAuthNetworkCredential(String userName, ITokenProvider tokenProvider)](#OAuthNetworkCredential-java.lang.String-com.aspose.email.ITokenProvider-) | Initializes a new instance of the [OAuthNetworkCredential](../../com.aspose.email/oauthnetworkcredential) class |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccessToken()](#getAccessToken--) | Gets OAuth 2.0 access token. |
| [getClass()](#getClass--) |  |
| [getCredential(System.Uri arg0, String arg1)](#getCredential-com.aspose.ms.System.Uri-java.lang.String-) |  |
| [getCredential(String host, int port, String authenticationType)](#getCredential-java.lang.String-int-java.lang.String-) | \{@inheritDoc\} |
| [getDomain()](#getDomain--) |  |
| [getPassword()](#getPassword--) |  |
| [getTokenProvider()](#getTokenProvider--) | Gets the token provider. |
| [getUserName()](#getUserName--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDomain(String arg0)](#setDomain-java.lang.String-) |  |
| [setPassword(String arg0)](#setPassword-java.lang.String-) |  |
| [setUserName(String arg0)](#setUserName-java.lang.String-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OAuthNetworkCredential(String accessToken) {#OAuthNetworkCredential-java.lang.String-}
```
public OAuthNetworkCredential(String accessToken)
```


Initializes a new instance of the [OAuthNetworkCredential](../../com.aspose.email/oauthnetworkcredential) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| accessToken | java.lang.String | Access token |

### OAuthNetworkCredential(ITokenProvider tokenProvider) {#OAuthNetworkCredential-com.aspose.email.ITokenProvider-}
```
public OAuthNetworkCredential(ITokenProvider tokenProvider)
```


Initializes a new instance of the [OAuthNetworkCredential](../../com.aspose.email/oauthnetworkcredential) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tokenProvider | [ITokenProvider](../../com.aspose.email/itokenprovider) | Token provider |

### OAuthNetworkCredential(String userName, String accessToken) {#OAuthNetworkCredential-java.lang.String-java.lang.String-}
```
public OAuthNetworkCredential(String userName, String accessToken)
```


Initializes a new instance of the [OAuthNetworkCredential](../../com.aspose.email/oauthnetworkcredential) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userName | java.lang.String | User name |
| accessToken | java.lang.String | Access token |

### OAuthNetworkCredential(String userName, ITokenProvider tokenProvider) {#OAuthNetworkCredential-java.lang.String-com.aspose.email.ITokenProvider-}
```
public OAuthNetworkCredential(String userName, ITokenProvider tokenProvider)
```


Initializes a new instance of the [OAuthNetworkCredential](../../com.aspose.email/oauthnetworkcredential) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userName | java.lang.String | User name |
| tokenProvider | [ITokenProvider](../../com.aspose.email/itokenprovider) | Token provider |

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
### getAccessToken() {#getAccessToken--}
```
public final String getAccessToken()
```


Gets OAuth 2.0 access token.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCredential(System.Uri arg0, String arg1) {#getCredential-com.aspose.ms.System.Uri-java.lang.String-}
```
public System.Net.NetworkCredential getCredential(System.Uri arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Uri |  |
| arg1 | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Net.NetworkCredential
### getCredential(String host, int port, String authenticationType) {#getCredential-java.lang.String-int-java.lang.String-}
```
public final System.Net.NetworkCredential getCredential(String host, int port, String authenticationType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String |  |
| port | int |  |
| authenticationType | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Net.NetworkCredential
### getDomain() {#getDomain--}
```
public String getDomain()
```




**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public String getPassword()
```




**Returns:**
java.lang.String
### getTokenProvider() {#getTokenProvider--}
```
public final ITokenProvider getTokenProvider()
```


Gets the token provider.

**Returns:**
[ITokenProvider](../../com.aspose.email/itokenprovider)
### getUserName() {#getUserName--}
```
public String getUserName()
```




**Returns:**
java.lang.String
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




### setDomain(String arg0) {#setDomain-java.lang.String-}
```
public void setDomain(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

### setPassword(String arg0) {#setPassword-java.lang.String-}
```
public void setPassword(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

### setUserName(String arg0) {#setUserName-java.lang.String-}
```
public void setUserName(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

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

