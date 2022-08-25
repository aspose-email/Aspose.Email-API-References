---
title: TokenProvider.Outlook
second_title: Aspose.Email for Java API Reference
description:  Provides an instance of the TokenProvider for Outlook mail server
type: docs
weight: 11
url: /java/com.aspose.email/tokenprovider.outlook/
---
**Inheritance:**
java.lang.Object
```
public static class TokenProvider.Outlook
```

Provides an instance of the TokenProvider for Outlook mail server
## Constructors

| Constructor | Description |
| --- | --- |
| [Outlook()](#Outlook--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getInstance(String clientId, String clientSecret, String refreshToken)](#getInstance-java.lang.String-java.lang.String-java.lang.String-) | Gets an instance of the TokenProvider for Outlook mail server |
### Outlook() {#Outlook--}
```
public Outlook()
```


### getInstance(String clientId, String clientSecret, String refreshToken) {#getInstance-java.lang.String-java.lang.String-java.lang.String-}
```
public static TokenProvider getInstance(String clientId, String clientSecret, String refreshToken)
```


Gets an instance of the TokenProvider for Outlook mail server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| clientId | java.lang.String | The client ID obtained from the Microsoft account Developer Center during application registration. |
| clientSecret | java.lang.String | The client secret obtained during application registration. |
| refreshToken | java.lang.String | OAuth 2.0 refresh token |

**Returns:**
[TokenProvider](../../com.aspose.email/tokenprovider) - Returns an instance of the OutlookTokenProvider for defined parameters.
