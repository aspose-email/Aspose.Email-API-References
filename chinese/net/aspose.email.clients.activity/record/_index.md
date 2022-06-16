---
title: Record
second_title: Aspose.Email for .NET API 参考
description: 审核日志记录
type: docs
weight: 2720
url: /zh/net/aspose.email.clients.activity/record/
---
## Record class

审核日志记录

```csharp
public class Record
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Record](record)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AzureActiveDirectoryEventType](../../aspose.email.clients.activity/record/azureactivedirectoryeventtype) { get; set; } | 获取或设置 Azure AD 事件的类型。 强制:是 |
| [Client](../../aspose.email.clients.activity/record/client) { get; set; } | 获取或设置有关用于帐户登录事件的客户端设备、设备操作系统和设备浏览器的详细信息。 强制:否 |
| [ClientIP](../../aspose.email.clients.activity/record/clientip) { get; set; } | 获取或设置记录活动时使用的设备的 IP 地址。 IP 地址以 IPv4 或 IPv6 地址格式显示。 强制:是 |
| [CreationTime](../../aspose.email.clients.activity/record/creationtime) { get; set; } | 获取或设置用户执行活动时采用协调世界时 (UTC) 的日期和时间。 强制:是 |
| [ExtendedProperties](../../aspose.email.clients.activity/record/extendedproperties) { get; set; } | 获取或设置正在更改的设置的扩展属性列表。每个属性都有一个名称和值。 强制:否 |
| [Id](../../aspose.email.clients.activity/record/id) { get; set; } | 获取或设置审计记录的唯一标识符。 强制:是 |
| [LoginStatus](../../aspose.email.clients.activity/record/loginstatus) { get; set; } | 获取或设置登录状态 强制:是 |
| [ObjectId](../../aspose.email.clients.activity/record/objectid) { get; set; } | 获取或设置对象标识符。 对于 SharePoint 和 OneDrive for Business 活动，用户访问的文件或文件夹的完整路径名。 对于 Exchange 管理员审核日志记录，由 cmdlet 修改的对象的名称。 强制:否 |
| [Operation](../../aspose.email.clients.activity/record/operation) { get; set; } | 获取或设置用户或管理员活动的名称。 有关最常见操作/活动的描述，请参阅在 Office 365 保护中心搜索审核日志。 对于 Exchange 管理员活动，此属性标识已运行的 cmdlet 的名称。 对于 Dlp 事件，这可以是“DlpRuleMatch”、“DlpRuleUndo”或“DlpInfo”，它们在下面的“DLP 架构”下进行了描述。 强制:是 |
| [OrganizationId](../../aspose.email.clients.activity/record/organizationid) { get; set; } | 获取或设置组织的 Office 365 租户的 GUID。 对于您的组织，此值将始终相同，无论它发生在哪个 Office 365 服务中。 强制:是 |
| [RecordType](../../aspose.email.clients.activity/record/recordtype) { get; set; } | 获取或设置记录指示的操作类型。 强制:是 |
| [ResultStatus](../../aspose.email.clients.activity/record/resultstatus) { get; set; } | 获取或设置指示操作（在操作属性中指定）是否成功的值。 强制:否 |
| [UserDomain](../../aspose.email.clients.activity/record/userdomain) { get; set; } | 获取或设置租户身份信息 (TII)。 强制:是 |
| [UserId](../../aspose.email.clients.activity/record/userid) { get; set; } | 获取或设置执行导致记录被记录的操作（在 Operation 属性中指定）的用户的 UPN（用户主体名称）； 例如，my_name@my_domain_name。 请注意，系统帐户（例如 SHAREPOINT\system 或 NT AUTHORITY\SYSTEM）执行的活动记录也包括在内。 强制:是 |
| [UserKey](../../aspose.email.clients.activity/record/userkey) { get; set; } | 获取或设置在 UserId 属性中标识的用户的替代 ID。 例如，此属性填充了用户在 SharePoint、OneDrive for Business 和 Exchange 中执行的事件的护照唯一 ID (PUID)。 此属性还可以为其他服务中发生的事件和系统帐户执行的事件指定与 UserID 属性相同的值。 强制:是 |
| [UserType](../../aspose.email.clients.activity/record/usertype) { get; set; } | 获取或设置执行操作的用户类型。 强制:是 |
| [Workload](../../aspose.email.clients.activity/record/workload) { get; set; } | 获取或设置发生活动的 Office 365 服务。 强制:否 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->