---
title: "Aspose::Email::Clients::TokenProvider::GetAccessToken method"
linktitle: "GetAccessToken"
articleTitle: "GetAccessToken"
second_title: "Aspose.Email for C++"
description: "Gets oAuth access token."
type: docs
weight: 110
url: /cpp/aspose.email.clients/tokenprovider/getaccesstoken/
---

## GetAccessToken (1 of 2) {#getaccesstoken_1}

Gets oAuth access token. If token exists and its expiration date is not expired returns current token, otherwise requests new token from a server.

**Returns:** Returns oAuth access token

```cpp
GetAccessToken()
```

---

## GetAccessToken (2 of 2) {#getaccesstoken_2}

Gets oAuth access token.

**Returns:** Returns oAuth access token

```cpp
GetAccessToken(bool ignoreExistingToken)
```

| Parameter | Description |
| --- | --- |
| ignoreExistingToken | If ignoreExistingToken is true, requests new token from a server. Otherwise behaviour is depended on whether token exists or not. If token exists and its expiration date is not expired returns current token, otherwise requests new token from a server. |

