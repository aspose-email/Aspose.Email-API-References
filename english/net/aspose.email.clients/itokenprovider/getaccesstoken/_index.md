---
title: GetAccessToken
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.email.clients/itokenprovider/getaccesstoken/
---
## ITokenProvider.GetAccessToken method (1 of 2)

Gets oAuth access token. If token exists and its expiration date is not expired returns current token, otherwise requests new token from a server.

```csharp
public OAuthToken GetAccessToken()
```

## Return Value

Returns oAuth access token

### See Also

* class [OAuthToken](../../oauthtoken)
* interface [ITokenProvider](../../itokenprovider)
* namespace [Aspose.Email.Clients](../../itokenprovider)
* assembly [Aspose.Email](../../../)

---

## ITokenProvider.GetAccessToken method (2 of 2)

Gets oAuth access token.

```csharp
public OAuthToken GetAccessToken(bool ignoreExistingToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ignoreExistingToken | Boolean | If ignoreExistingToken is true, requests new token from a server. Otherwise behaviour is depended on whether token exists or not. If token exists and its expiration date is not expired returns current token, otherwise requests new token from a server. |

## Return Value

Returns oAuth access token

### See Also

* class [OAuthToken](../../oauthtoken)
* interface [ITokenProvider](../../itokenprovider)
* namespace [Aspose.Email.Clients](../../itokenprovider)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->