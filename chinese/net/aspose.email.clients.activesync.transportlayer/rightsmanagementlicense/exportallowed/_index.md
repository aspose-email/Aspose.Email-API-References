---
title: ExportAllowed
second_title: Aspose.Email for .NET API 参考
description: 指定用户是否可以取消对电子邮件的 IRM 保护 如果用户可以在用户转发回复或全部回复电子邮件时取消 IRM 保护则该值为 TRUE否则该值为 TRUE否则FALSE. 如果使用 SmartForward 或 SmartReply 命令转发或回复权限管理的电子邮件则评估以下条件 - 原始权限策略模板的 ExportAllowed 元素设置为 TRUE - 新的 TemplateID消息设置为无限制模板TemplateID 值00000000-0000-0000-0000-000000000000 如果两个条件都为真则从传出消息中删除 IRM 保护 原始邮件保留其 IRM 保护
type: docs
weight: 50
url: /zh/net/aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/exportallowed/
---
## RightsManagementLicense.ExportAllowed property

指定用户是否可以取消对电子邮件的 IRM 保护。 如果用户可以在用户转发、回复或全部回复电子邮件时取消 IRM 保护，则该值为 TRUE；否则，该值为 TRUE。否则，FALSE. 如果使用 SmartForward 或 SmartReply 命令转发或回复权限管理的电子邮件，则评估以下条件： - 原始权限策略模板的 ExportAllowed 元素设置为 TRUE - 新的 TemplateID消息设置为“无限制”模板（TemplateID 值“00000000-0000-0000-0000-000000000000”） 如果两个条件都为真，则从传出消息中删除 IRM 保护。 原始邮件保留其 IRM 保护。

```csharp
public bool ExportAllowed { get; set; }
```

### 也可以看看

* class [RightsManagementLicense](../../rightsmanagementlicense)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../rightsmanagementlicense)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
