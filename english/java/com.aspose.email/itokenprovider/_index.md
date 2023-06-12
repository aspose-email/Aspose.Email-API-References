---
title: ITokenProvider
second_title: Aspose.Email for Java API Reference
description: Defines interface allowing to retrieve access token.
type: docs
weight: 755
url: /java/com.aspose.email/itokenprovider/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface ITokenProvider extends System.IDisposable
```

Defines interface allowing to retrieve access token.
## Methods

| Method | Description |
| --- | --- |
| [getAccessToken()](#getAccessToken--) | Gets oAuth access token. |
| [getAccessToken(boolean ignoreExistingToken)](#getAccessToken-boolean-) | Gets oAuth access token. |
### getAccessToken() {#getAccessToken--}
```
public abstract OAuthToken getAccessToken()
```


Gets oAuth access token. If token exists and its expiration date is not expired returns current token, otherwise requests new token from a server.

**Returns:**
[OAuthToken](../../com.aspose.email/oauthtoken) - Returns oAuth access token
### getAccessToken(boolean ignoreExistingToken) {#getAccessToken-boolean-}
```
public abstract OAuthToken getAccessToken(boolean ignoreExistingToken)
```


Gets oAuth access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ignoreExistingToken | boolean | If ignoreExistingToken is true, requests new token from a server. Otherwise behavior is depended on whether token exists or not. If token exists and its expiration date is not expired returns current token, otherwise requests new token from a server. |

**Returns:**
[OAuthToken](../../com.aspose.email/oauthtoken) - Returns oAuth access token
