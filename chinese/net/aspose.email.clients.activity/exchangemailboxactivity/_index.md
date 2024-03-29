---
title: ExchangeMailboxActivity
second_title: Aspose.Email for .NET API 参考
description: 使用特定于所有 Exchange 邮箱审核数据的属性扩展通用架构
type: docs
weight: 2510
url: /zh/net/aspose.email.clients.activity/exchangemailboxactivity/
---
## ExchangeMailboxActivity class

使用特定于所有 Exchange 邮箱审核数据的属性扩展通用架构。

```csharp
public class ExchangeMailboxActivity : Content
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ExchangeMailboxActivity](exchangemailboxactivity)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ClientInfoString](../../aspose.email.clients.activity/exchangemailboxactivity/clientinfostring) { get; set; } | 用于执行操作的电子邮件客户端的信息，例如浏览器版本、Outlook 版本和移动设备信息。 |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | 记录活动时使用的设备的 IP 地址。 IP 地址以 IPv4 或 IPv6 地址格式显示。 强制：是 |
| [ClientIPAddress](../../aspose.email.clients.activity/exchangemailboxactivity/clientipaddress) { get; set; } | 记录操作时使用的设备的 IP 地址。 IP 地址以 IPv4 或 IPv6 地址格式显示。 |
| [ClientMachineName](../../aspose.email.clients.activity/exchangemailboxactivity/clientmachinename) { get; set; } | 托管 Outlook 客户端的计算机名称。 |
| [ClientProcessName](../../aspose.email.clients.activity/exchangemailboxactivity/clientprocessname) { get; set; } | 用于访问邮箱的电子邮件客户端。 |
| [ClientVersion](../../aspose.email.clients.activity/exchangemailboxactivity/clientversion) { get; set; } | 电子邮件客户端的版本。 |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | 用户执行活动时的协调世界时 (UTC) 日期和时间。 必填：是 |
| [ExternalAccess](../../aspose.email.clients.activity/exchangemailboxactivity/externalaccess) { get; set; } | 如果登录用户的域与邮箱所有者的域不同，则为真。 |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | 审计记录的唯一标识符。 强制：是 |
| [InternalLogonType](../../aspose.email.clients.activity/exchangemailboxactivity/internallogontype) { get; set; } | 保留供内部使用。 |
| [LogonType](../../aspose.email.clients.activity/exchangemailboxactivity/logontype) { get; set; } | 表示访问邮箱并执行已记录操作的用户类型。 |
| [LogonUserDisplayName](../../aspose.email.clients.activity/exchangemailboxactivity/logonuserdisplayname) { get; set; } | 执行操作的用户的用户友好名称。 |
| [LogonUserSid](../../aspose.email.clients.activity/exchangemailboxactivity/logonusersid) { get; set; } | 执行操作的用户的 SID。 |
| [MailboxGuid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxguid) { get; set; } | 已访问邮箱的 Exchange GUID。 |
| [MailboxOwnerMasterAccountSid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownermasteraccountsid) { get; set; } | 邮箱所有者帐户的主帐户 SID. |
| [MailboxOwnerSid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownersid) { get; set; } | 邮箱所有者的 SID。 |
| [MailboxOwnerUPN](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownerupn) { get; set; } | 拥有被访问邮箱的人的电子邮件地址。 |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | 对于 SharePoint 和 OneDrive for Business 活动，用户访问的文件或文件夹的完整路径名。 对于 Exchange 管理员审核日志记录，由 cmdlet 修改的对象的名称。 强制：否 |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | 用户或管理员活动的名称。 有关最常见操作/活动的描述，请参阅在 Office 365 保护中心搜索审核日志。 对于 Exchange 管理员活动，此属性标识已运行的 cmdlet 的名称。 对于 Dlp 事件，这可以是“DlpRuleMatch”、“DlpRuleUndo”或“DlpInfo”，在下面的“DLP 架构”下进行了描述。 强制：是 |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | 组织的 Office 365 租户的 GUID。 无论在哪个 Office 365 服务中出现，此值对于您的组织始终是相同的。 强制：是 |
| [OrganizationName](../../aspose.email.clients.activity/exchangemailboxactivity/organizationname) { get; set; } | 租户名称。 |
| [OriginatingServer](../../aspose.email.clients.activity/exchangemailboxactivity/originatingserver) { get; set; } | 这是操作起源的地方。 |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | 记录指示的操作类型。 强制：是 |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | 指示操作（在操作属性中指定）是否成功。 可能的值为 Succeeded、PartiallySucceded 或 Failed。 对于 Exchange 管理员活动，该值为 True 或 False。 强制：No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | 此事件是由托管的 O365 服务还是本地服务器创建的？ 可能的值是 online 和 onprem。请注意，SharePoint 是当前将事件从本地发送到 O365 的唯一工作负载。 强制：No |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | 执行导致记录被记录的操作（在操作属性中指定）的用户的 UPN（用户主体名称）； 例如，my_name@my_domain_name。 请注意，系统帐户（例如 SHAREPOINT\system 或 NT AUTHORITY\SYSTEM）执行的活动记录也包括在内。 强制：是 |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | UserId 属性中标识的用户的备用 ID。 例如，此属性由用户在 SharePoint、OneDrive for Business 和 Exchange 中执行的事件的护照唯一 ID (PUID) 填充。 此属性还可以为其他服务中发生的事件和系统帐户执行的事件指定与 UserID 属性相同的值。 强制：是 |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | 执行操作的用户类型。 强制：是 |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | 工作负载字符串中发生活动的 Office 365 服务。此属性的可能值为： Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence 强制：No |

### 也可以看看

* class [Content](../content)
* 命名空间 [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
