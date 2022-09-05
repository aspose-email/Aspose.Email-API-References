---
title: OAuthNetworkCredential
second_title: Aspose.Email for Java API Reference
description:  Represents the NetworkCredential for OAuth authentication.
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
| [getAccessToken()](#getAccessToken--) | Gets OAuth 2.0 access token. |
| [getTokenProvider()](#getTokenProvider--) | Gets the token provider. |
| [getCredential(String host, int port, String authenticationType)](#getCredential-java.lang.String-int-java.lang.String-) | \{@inheritDoc\} |
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

### getAccessToken() {#getAccessToken--}
```
public final String getAccessToken()
```


Gets OAuth 2.0 access token.

**Returns:**
java.lang.String
### getTokenProvider() {#getTokenProvider--}
```
public final ITokenProvider getTokenProvider()
```


Gets the token provider.

**Returns:**
[ITokenProvider](../../com.aspose.email/itokenprovider)
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
