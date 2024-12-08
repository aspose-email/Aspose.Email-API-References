---
title: IMultipleServicesTokenProvider
second_title: Aspose.Email for Java API Reference
description: Defines interface allowing to retrieve access token.
type: docs
weight: 781
url: /java/com.aspose.email/imultipleservicestokenprovider/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IMultipleServicesTokenProvider extends System.IDisposable
```

Defines interface allowing to retrieve access token.
## Methods

| Method | Description |
| --- | --- |
| [getAccessToken(boolean ignoreExistingToken, String service)](#getAccessToken-boolean-java.lang.String-) | Gets oAuth access token. |
| [getAccessToken(String service)](#getAccessToken-java.lang.String-) | Gets oAuth access token. |
### getAccessToken(boolean ignoreExistingToken, String service) {#getAccessToken-boolean-java.lang.String-}
```
public abstract OAuthToken getAccessToken(boolean ignoreExistingToken, String service)
```


Gets oAuth access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ignoreExistingToken | boolean | If ignoreExistingToken is true, requests new token from a server. Otherwise behaviour is depended on whether token exists or not. If token exists and its expiration date is not expired returns current token, otherwise requests new token from a server. |
| service | java.lang.String | Services that this access token applies to. |

**Returns:**
[OAuthToken](../../com.aspose.email/oauthtoken) - Returns oAuth access token
### getAccessToken(String service) {#getAccessToken-java.lang.String-}
```
public abstract OAuthToken getAccessToken(String service)
```


Gets oAuth access token. If token exists and its expiration date is not expired returns current token, otherwise requests new token from a server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| service | java.lang.String | Services that this access token applies to. |

**Returns:**
[OAuthToken](../../com.aspose.email/oauthtoken) - Returns oAuth access token
