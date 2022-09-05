---
title: TokenProvider.Google
second_title: Aspose.Email for Java API Reference
description:  Provides an instance of the TokenProvider for Google mail server
type: docs
weight: 10
url: /java/com.aspose.email/tokenprovider.google/
---
**Inheritance:**
java.lang.Object
```
public static class TokenProvider.Google
```

Provides an instance of the TokenProvider for Google mail server
## Constructors

| Constructor | Description |
| --- | --- |
| [Google()](#Google--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getInstance(String clientId, String clientSecret, String refreshToken)](#getInstance-java.lang.String-java.lang.String-java.lang.String-) | Gets an instance of the TokenProvider for Google mail server |
### Google() {#Google--}
```
public Google()
```


### getInstance(String clientId, String clientSecret, String refreshToken) {#getInstance-java.lang.String-java.lang.String-java.lang.String-}
```
public static TokenProvider getInstance(String clientId, String clientSecret, String refreshToken)
```


Gets an instance of the TokenProvider for Google mail server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| clientId | java.lang.String | The client ID obtained from the Microsoft account Developer Center during application registration. |
| clientSecret | java.lang.String | The client secret obtained during application registration. |
| refreshToken | java.lang.String | OAuth 2.0 refresh token |

**Returns:**
[TokenProvider](../../com.aspose.email/tokenprovider) - Returns an instance of the OutlookTokenProvider for defined parameters.
