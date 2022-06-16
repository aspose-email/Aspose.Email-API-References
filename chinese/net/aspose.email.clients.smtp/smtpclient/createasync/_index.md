---
title: CreateAsync
second_title: Aspose.Email for .NET API 参考
description: 创建SmtpClientaspose.email.clients.smtp/smtpclient类的新实例
type: docs
weight: 220
url: /zh/net/aspose.email.clients.smtp/smtpclient/createasync/
---
## SmtpClient.CreateAsync method

创建[`SmtpClient`](../../smtpclient)类的新实例

```csharp
public static Task<IAsyncSmtpClient> CreateAsync(string host, string username, 
    IAsyncTokenProvider asyncTokenProvider, int port = 25, 
    SecurityOptions securityOptions = SecurityOptions.Auto, 
    CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| host | String | 主机名 |
| port | String | 端口号 |
| username | IAsyncTokenProvider | 用户名 |
| asyncTokenProvider | Int32 | 访问令牌提供程序。 |
| securityOptions | SecurityOptions | 邮件客户端的安全模式 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 也可以看看

* interface [IAsyncSmtpClient](../../iasyncsmtpclient)
* interface [IAsyncTokenProvider](../../../aspose.email.clients/iasynctokenprovider)
* enum [SecurityOptions](../../../aspose.email.clients/securityoptions)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->