---
title: SupportedEncryption
second_title: Aspose.Email for .NET API 参考
description: 定义要使用的 SSL/TLS 加密协议的版本 请注意您只能设置 .net 框架支持的协议版本 如果您当前版本不支持某些协议版本对于 .NET 框架它们将被忽略和跳过 这可能会导致 TLS 安全级别降级在这种情况下不会生成异常 请参阅EncryptionProtocolsaspose.email.clients.base/encryptionprotocols有关更多详细信息的文档 请使用SetSupportedEncryptionUnsafeaspose.email.clients/emailclient/setsupportedencryptionunsafe如果要设置加密协议而不进行任何兼容性检查的方法 默认值为Tls x7C tls11 x7C tls12 x7C tls13如果您当前版本的 .net 框架支持这些版本的 TLS
type: docs
weight: 170
url: /zh/net/aspose.email.clients/emailclient/supportedencryption/
---
## EmailClient.SupportedEncryption property

定义要使用的 SSL/TLS 加密协议的版本。 请注意，您只能设置 .net 框架支持的协议版本。 如果您当前版本不支持某些协议版本对于 .NET 框架，它们将被忽略和跳过。 这可能会导致 TLS 安全级别降级。在这种情况下，不会生成异常！！！ 请参阅[`EncryptionProtocols`](../../../aspose.email.clients.base/encryptionprotocols)有关更多详细信息的文档。 请使用[`SetSupportedEncryptionUnsafe`](../setsupportedencryptionunsafe)如果要设置加密协议而不进行任何兼容性检查的方法。 默认值为：Tls &#x7C; tls11 &#x7C; tls12 &#x7C; tls13（如果您当前版本的 .net 框架支持这些版本的 TLS）

```csharp
public virtual EncryptionProtocols SupportedEncryption { get; set; }
```

### 也可以看看

* enum [EncryptionProtocols](../../../aspose.email.clients.base/encryptionprotocols)
* class [EmailClient](../../emailclient)
* 命名空间 [Aspose.Email.Clients](../../emailclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
