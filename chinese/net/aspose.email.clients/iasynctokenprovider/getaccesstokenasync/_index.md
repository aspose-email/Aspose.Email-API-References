---
title: GetAccessTokenAsync
second_title: Aspose.Email for .NET API 参考
description: 获取 oAuth 访问令牌
type: docs
weight: 10
url: /zh/net/aspose.email.clients/iasynctokenprovider/getaccesstokenasync/
---
## IAsyncTokenProvider.GetAccessTokenAsync method

获取 oAuth 访问令牌。

```csharp
public Task<OAuthToken> GetAccessTokenAsync(bool ignoreExistingToken = false, 
    CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ignoreExistingToken | Boolean | 如果 ignoreExistingToken 为真，则从服务器请求新令牌。否则行为取决于令牌是否存在。 如果令牌存在且其过期日期未过期，则返回当前令牌，否则从服务器请求新令牌。 |
| cancellationToken | CancellationToken | 取消令牌 |

### 返回值

返回 oAuth 访问令牌

### 也可以看看

* class [OAuthToken](../../oauthtoken)
* interface [IAsyncTokenProvider](../../iasynctokenprovider)
* 命名空间 [Aspose.Email.Clients](../../iasynctokenprovider)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
