---
title: ITokenProvider
second_title: Aspose.Email for Android via Java API 参考
description: 定义允许检索访问令牌的接口。
type: docs
weight: 464
url: /zh/androidjava/com.aspose.email/itokenprovider/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface ITokenProvider extends System.IDisposable
```

定义允许检索访问令牌的接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAccessToken()](#getAccessToken--) | 获取 oAuth 访问令牌。 |
| [getAccessToken(boolean ignoreExistingToken)](#getAccessToken-boolean-) | 获取 oAuth 访问令牌。 |
### getAccessToken() {#getAccessToken--}
```
public abstract OAuthToken getAccessToken()
```


获取 oAuth 访问令牌。如果令牌存在且其过期日期未过期，则返回当前令牌；否则向服务器请求新令牌。

**Returns:**
[OAuthToken](../../com.aspose.email/oauthtoken) - Returns oAuth access token
### getAccessToken(boolean ignoreExistingToken) {#getAccessToken-boolean-}
```
public abstract OAuthToken getAccessToken(boolean ignoreExistingToken)
```


获取 oAuth 访问令牌。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ignoreExistingToken | boolean | 如果 ignoreExistingToken 为 true，则向服务器请求新令牌。否则行为取决于令牌是否存在。如果令牌存在且其过期日期未过期，则返回当前令牌；否则向服务器请求新令牌。 |

**Returns:**
[OAuthToken](../../com.aspose.email/oauthtoken) - Returns oAuth access token
