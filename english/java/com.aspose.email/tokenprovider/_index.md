---
title: TokenProvider
second_title: Aspose.Email for Java API Reference
description: Class TokenProvider allows to retrieve access token for mail services.
type: docs
weight: 677
url: /java/com.aspose.email/tokenprovider/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.ITokenProvider](../../com.aspose.email/itokenprovider)
```
public class TokenProvider implements ITokenProvider
```

Class TokenProvider allows to retrieve access token for mail services.
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Performs releasing resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccessToken()](#getAccessToken--) | Gets oAuth access token. |
| [getAccessToken(boolean ignoreExistingToken)](#getAccessToken-boolean-) | Gets oAuth access token. |
| [getClass()](#getClass--) |  |
| [getClientId()](#getClientId--) | The client ID obtained during application registration. |
| [getClientSecret()](#getClientSecret--) | The client secret obtained during application registration. |
| [getExtraParameters()](#getExtraParameters--) | Gets extra parameters for request |
| [getInstance(String requestUrl, String clientId, String clientSecret, String refreshToken)](#getInstance-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Gets an instance of the OutlookTokenProvider for defined parameters. |
| [getLogin()](#getLogin--) | Gets or sets login for basic authorization |
| [getPassword()](#getPassword--) | Gets or sets password for basic authorization |
| [getRefreshToken()](#getRefreshToken--) | OAuth 2.0 refresh token |
| [getRequestUrl()](#getRequestUrl--) | The url to obtain access token. |
| [getUseBasicAuthorization()](#getUseBasicAuthorization--) | Gets or sets value which indicates whether basic authorization is used |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLogin(String value)](#setLogin-java.lang.String-) | Gets or sets login for basic authorization |
| [setPassword(String value)](#setPassword-java.lang.String-) | Gets or sets password for basic authorization |
| [setUseBasicAuthorization(boolean value)](#setUseBasicAuthorization-boolean-) | Gets or sets value which indicates whether basic authorization is used |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### dispose() {#dispose--}
```
public void dispose()
```


Performs releasing resources.

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
public OAuthToken getAccessToken()
```


Gets oAuth access token. If token exists and its expiration date is not expired returns current token, otherwise requests new token from a server.

**Returns:**
[OAuthToken](../../com.aspose.email/oauthtoken) - Returns oAuth access token
### getAccessToken(boolean ignoreExistingToken) {#getAccessToken-boolean-}
```
public OAuthToken getAccessToken(boolean ignoreExistingToken)
```


Gets oAuth access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ignoreExistingToken | boolean | If ignoreExistingToken is true, requests new token from a server. Otherwise behaviour is depended on whether token exists or not. If token exists and its expiration date is not expired returns current token, otherwise requests new token from a server. |

**Returns:**
[OAuthToken](../../com.aspose.email/oauthtoken) - Returns oAuth access token
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClientId() {#getClientId--}
```
public String getClientId()
```


The client ID obtained during application registration.

**Returns:**
java.lang.String
### getClientSecret() {#getClientSecret--}
```
public String getClientSecret()
```


The client secret obtained during application registration.

**Returns:**
java.lang.String
### getExtraParameters() {#getExtraParameters--}
```
public System.Collections.Generic.KeyValuePair<String,String>[] getExtraParameters()
```


Gets extra parameters for request

**Returns:**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>[]
### getInstance(String requestUrl, String clientId, String clientSecret, String refreshToken) {#getInstance-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public static TokenProvider getInstance(String requestUrl, String clientId, String clientSecret, String refreshToken)
```


Gets an instance of the OutlookTokenProvider for defined parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| requestUrl | java.lang.String | The url to obtain access token. |
| clientId | java.lang.String | The client ID obtained from the Microsoft account Developer Center during application registration. |
| clientSecret | java.lang.String | The client secret obtained during application registration. |
| refreshToken | java.lang.String | OAuth 2.0 refresh token |

**Returns:**
[TokenProvider](../../com.aspose.email/tokenprovider) - Returns an instance of the OutlookTokenProvider for defined parameters.
### getLogin() {#getLogin--}
```
public String getLogin()
```


Gets or sets login for basic authorization

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public String getPassword()
```


Gets or sets password for basic authorization

**Returns:**
java.lang.String
### getRefreshToken() {#getRefreshToken--}
```
public String getRefreshToken()
```


OAuth 2.0 refresh token

**Returns:**
java.lang.String
### getRequestUrl() {#getRequestUrl--}
```
public String getRequestUrl()
```


The url to obtain access token.

**Returns:**
java.lang.String
### getUseBasicAuthorization() {#getUseBasicAuthorization--}
```
public boolean getUseBasicAuthorization()
```


Gets or sets value which indicates whether basic authorization is used

**Returns:**
boolean
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




### setLogin(String value) {#setLogin-java.lang.String-}
```
public void setLogin(String value)
```


Gets or sets login for basic authorization

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


Gets or sets password for basic authorization

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUseBasicAuthorization(boolean value) {#setUseBasicAuthorization-boolean-}
```
public void setUseBasicAuthorization(boolean value)
```


Gets or sets value which indicates whether basic authorization is used

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

