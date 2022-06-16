---
title: SharePointAuditOperation
second_title: Aspose.Email for .NET API 参考
description: SharePoint 审计操作
type: docs
weight: 2760
url: /zh/net/aspose.email.clients.activity/sharepointauditoperation/
---
## SharePointAuditOperation enumeration

SharePoint 审计操作

```csharp
public enum SharePointAuditOperation
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| AccessInvitationAccepted | `0` | 此操作在预览中。 查看或编辑共享文件（或文件夹）邀请的收件人已通过单击邀请中的链接访问了共享文件。 |
| AccessInvitationCreated | `1` | 此操作在预览中。 用户向其他人（其组织内部或外部）发送邀请以查看或编辑 SharePoint 或 OneDrive for Business 网站上的共享文件或文件夹。 事件条目的详细信息标识了共享文件的名称、发送邀请的用户、 以及共享权限的类型。发出了邀请。 |
| AccessInvitationExpired | `2` | 此操作在预览中。 发送给外部用户的邀请过期。默认情况下，如果不接受邀请，则发送给组织外部用户的邀请会在 7 天后过期。 |
| AccessInvitationRevoked | `3` | 此操作在预览中。 SharePoint 或 OneDrive for Business 中的网站或文档的网站管理员或所有者撤回发送给组织外部用户的邀请。 邀请只能在被接受之前撤回。 |
| AccessInvitationUpdated | `4` | 此操作在预览中。 创建邀请并向其他人发送邀请以查看或编辑 SharePoint 或 OneDrive for Business 网站上的共享文件（或文件夹）的用户重新发送邀请。 |
| AccessRequestApproved | `5` | SharePoint 或 OneDrive for Business 中网站或文档的网站管理员或所有者批准用户访问网站或文档的请求。 |
| AccessRequestCreated | `6` | 用户请求访问他们无权访问的 SharePoint 或 OneDrive for Business 中的网站或文档。 |
| AccessRequestRejected | `7` | 此操作在预览中。 SharePoint 中网站或文档的网站管理员或所有者拒绝用户访问该网站或文档的请求。 |
| ActivationEnabled | `8` | 此操作在预览中。 用户可以在浏览器中启用不包含表单代码、需要完全信任、启用在移动设备上呈现或使用由服务器管理员管理的数据连接的表单模板。 |
| AdministratorAddedToTermStore | `9` | 此操作在预览中。 术语库管理员已添加。 |
| AdministratorDeletedFromTermStore | `10` | 此操作在预览中。 术语库管理员已删除。 |
| AllowGroupCreationSet | `11` | 此操作在预览中。 站点管理员或所有者向 SharePoint 或 OneDrive for Business 站点添加权限级别，允许分配该权限的用户为该站点创建组。 |
| AppCatalogCreated | `12` | 此操作在预览中。 创建应用程序目录以使自定义业务应用程序可用于您的 SharePoint 环境。 |
| AuditPolicyRemoved | `13` | 此操作在预览中。 已删除网站集的文档生命周期策略。 |
| AuditPolicyUpdate | `14` | 此操作在预览中。 已为网站集更新了文档生命周期策略。 |
| AzureStreamingEnabledSet | `15` | 此操作在预览中。 视频门户所有者已允许从 Azure 流式传输视频。 |
| CollaborationTypeModified | `16` | 此操作在预览中。 站点上允许的协作类型（例如，Intranet、Extranet 或公共）已被修改。 |
| ConnectedSiteSettingModified | `17` | 用户创建、修改或删除了项目与项目站点之间的链接，或者用户修改了 Project Web App 中链接上的同步设置。 |
| CreateSSOApplication | `18` | 此操作在预览中。 在安全存储服务中创建的目标应用程序。 |
| CustomFieldOrLookupTableCreated | `19` | 用户在 Project Web App 中创建了自定义字段或查找表/项目。 |
| CustomFieldOrLookupTableDeleted | `20` | 用户删除了 Project Web App 中的自定义字段或查找表/项目。 |
| CustomFieldOrLookupTableModified | `21` | 用户修改了 Project Web App 中的自定义字段或查找表/项目。 |
| CustomizeExemptUsers | `22` | 此操作在预览中。 全局管理员在 SharePoint 管理中心自定义了豁免用户代理列表。 您可以指定哪些用户代理免于接收要索引的整个网页。 这意味着当您指定为豁免的用户代理遇到 InfoPath 表单时，该表单将作为 XML 文件而不是整个网页返回。 这使得索引 InfoPath 表单的速度更快。 |
| DefaultLanguageChangedInTermStore | `23` | 此操作在预览中。 术语库中的语言设置已更改。 |
| DelegateModified | `24` | 用户在 Project Web App 中创建或修改了安全委托。 |
| DelegateRemoved | `25` | 用户删除了 Project Web App 中的安全委托。 |
| DeleteSSOApplication | `26` | 此操作在预览中。 SSO 应用程序已删除。 |
| eDiscoveryHoldApplied | `27` | 此操作在预览中。 在内容源上放置了就地保留。就地保留通过使用 SharePoint 中的电子数据展示网站集（例如电子数据展示中心）进行管理。 |
| eDiscoveryHoldRemoved | `28` | 此操作在预览中。 从内容源中删除了就地保留。就地保留通过使用 SharePoint 中的电子数据展示网站集（例如电子数据展示中心）进行管理。 |
| eDiscoverySearchPerformed | `29` | 此操作在预览中。 使用 SharePoint 中的电子数据展示网站集执行了电子数据展示搜索。 |
| EngagementAccepted | `30` | 用户接受 Project Web App 中的资源参与。 |
| EngagementModified | `31` | 用户在 Project Web App 中修改资源参与。 |
| EngagementRejected | `32` | 用户拒绝 Project Web App 中的资源参与。 |
| EnterpriseCalendarModified | `33` | 用户在 Project Web App 中复制、修改或删除企业日历。 |
| EntityDeleted | `34` | 用户删除 Project Web App 中的时间表。 |
| EntityForceCheckedIn | `35` | 用户强制签入 Project Web App 中的日历、自定义字段或查找表。 |
| ExemptUserAgentSet | `36` | 此操作在预览中。 全局管理员将用户代理添加到 SharePoint 管理中心的豁免用户代理列表中。 |
| FileAccessed | `37` | 用户或系统帐户访问 SharePoint 或 OneDrive for Business 网站上的文件。系统帐户也可以生成 FileAccessed 事件。 |
| FileCheckOutDiscarded | `38` | 此操作在预览中。 用户丢弃（或撤消）签出的文件。 这意味着他们在签出文件时对文件所做的任何更改都将被丢弃，并且不会保存到文档库中的文档版本中。 |
| FileCheckedIn | `39` | 此操作在预览中。 用户签入他们从 SharePoint 或 OneDrive for Business 文档库中签出的文档。 |
| FileCheckedOut | `40` | 此操作在预览中。 用户签出位于 SharePoint 或 OneDrive for Business 文档库中的文档。用户可以签出并更改与他们共享的文档。 |
| FileCopied | `41` | 用户从 SharePoint 或 OneDrive for Business 网站复制文档。复制的文件可以保存到站点上的另一个文件夹中。 |
| FileDeleted | `42` | 用户从 SharePoint 或 OneDrive for Business 网站中删除文档。 |
| FileDeletedFirstStageRecycleBin | `43` | 用户从 SharePoint 或 OneDrive for Business 网站的回收站中删除文件。 |
| FileDeletedSecondStageRecycleBin | `44` | 用户从 SharePoint 或 OneDrive for Business 网站上的第二阶段回收站中删除文件。 |
| FileDownloaded | `45` | 用户从 SharePoint 或 OneDrive for Business 网站下载文档。 |
| FileFetched | `46` | 此事件已被 FileAccessed 事件替换，并且已被弃用。 |
| FileModified | `47` | 用户或系统帐户修改位于 SharePoint 或 OneDrive for Business 网站上的文档的内容或属性。 |
| FileMoved | `48` | 用户将文档从其在 SharePoint 或 OneDrive for Business 网站上的当前位置移动到新位置。 |
| FilePreviewed | `49` | 用户在 SharePoint 或 OneDrive for Business 网站上预览文档。 |
| FileRenamed | `50` | 用户重命名 SharePoint 或 OneDrive for Business 网站上的文档。 |
| FileRestored | `51` | 用户从 SharePoint 或 OneDrive for Business 网站的回收站恢复文档。 |
| FileSyncDownloadedFull | `52` | 用户建立同步关系并首次成功地将文件从 SharePoint 或 OneDrive for Business 文档库下载到他们的计算机。 |
| FileSyncDownloadedPartial | `53` | 用户成功从 SharePoint 或 OneDrive for Business 文档库下载对文件的任何更改。 此事件表示对文档库中的文件所做的任何更改都已下载到用户的计算机。 仅下载了更改，因为用户先前已下载文档库（如 FileSyncDownloadedFull 事件所示）。 |
| FileSyncUploadedFull | `54` | 此操作在预览中。 用户建立同步关系并首次将文件从其计算机成功上传到 SharePoint 或 OneDrive for Business 文档库。 |
| FileSyncUploadedPartial | `55` | 此操作在预览中。 用户成功上传对 SharePoint 或 OneDrive for Business 文档库上文件的更改。 此事件表示对文档库中文件的本地版本所做的任何更改都已成功上传到文档库。 仅卸载更改，因为这些文件先前已由用户上传（如 FileSyncUploadedFull 事件所示）。 |
| FileUploaded | `56` | 用户将文档上传到 SharePoint 或 OneDrive for Business 网站上的文件夹。 |
| FileViewed | `57` | 此事件已被 FileAccessed 事件替换，并且已被弃用。 |
| FolderCopied | `58` | 用户将文件夹从 SharePoint 或 OneDrive for Business 网站复制到 SharePoint 或 OneDrive for Business 中的另一个位置。 |
| FolderCreated | `59` | 用户在 SharePoint 或 OneDrive for Business 网站上创建一个文件夹。 |
| FolderDeleted | `60` | 用户从 SharePoint 或 OneDrive for Business 网站中删除文件夹。 |
| FolderDeletedFirstStageRecycleBin | `61` | 用户从 SharePoint 或 OneDrive for Business 网站的回收站中删除文件夹。 |
| FolderDeletedSecondStageRecycleBin | `62` | 用户从 SharePoint 或 OneDrive for Business 网站上的第二阶段回收站中删除文件夹。 |
| FolderModified | `63` | 用户修改 SharePoint 或 OneDrive for Business 网站上的文件夹。此事件包括文件夹元数据更改，例如标签和属性。 |
| FolderMoved | `64` | 用户从 SharePoint 或 OneDrive for Business 网站移动文件夹。 |
| FolderRenamed | `65` | 用户重命名 SharePoint 或 OneDrive for Business 网站上的文件夹。 |
| FolderRestored | `66` | 用户从 SharePoint 或 OneDrive for Business 网站上的回收站还原文件夹。 |
| GroupAdded | `67` | 此操作在预览中。 站点管理员或所有者为 SharePoint 或 OneDrive for Business 站点创建组，或执行导致创建组的任务。 例如，用户第一次创建链接以共享文件时，系统组将添加到用户的 OneDrive for Business 站点。 此事件也可能是用户创建对共享文件具有编辑权限的链接的结果。 |
| GroupRemoved | `68` | 此操作在预览中。 用户从 SharePoint 或 OneDrive for Business 网站中删除组。 |
| GroupUpdated | `69` | 此操作在预览中。 站点管理员或所有者更改 SharePoint 或 OneDrive for Business 站点的组设置。 这可以包括更改组的名称、谁可以查看或编辑组成员身份以及如何处理成员资格请求。 |
| LanguageAddedToTermStore | `70` | 此操作在预览中。 添加到术语库的语言。 |
| LanguageRemovedFromTermStore | `71` | 此操作在预览中。 从术语库中删除的语言。 |
| LegacyWorkflowEnabledSet | `72` | 此操作在预览中。 站点管理员或所有者将 SharePoint 工作流任务内容类型添加到站点。全局管理员还可以在 SharePoint 管理中心为整个组织启用工作流。 |
| LookAndFeelModified | `73` | 用户修改快速启动、甘特图格式或组格式。或者用户在 Project Web App 中创建、修改或删除视图。 |
| ManagedSyncClientAllowed | `74` | 用户成功建立与 SharePoint 或 OneDrive for Business 网站的同步关系。 同步关系成功，因为用户的计算机是域 的成员，该域已添加到可以访问文档库的域列表（称为安全收件人列表）中您的组织。 有关此功能的详细信息，请参阅使用 Windows PowerShell cmdlet 为安全收件人列表中的域启用 OneDrive 同步。 |
| MaxQuotaModified | `75` | 此操作在预览中。 修改了站点的最大配额。 |
| MaxResourceUsageModified | `76` | 此操作在预览中。 已修改站点的最大允许资源使用量。 |
| MySitePublicEnabledSet | `77` | 此操作在预览中。 SharePoint 管理员已设置允许用户拥有公共 MySites 的标志。 |
| NewsFeedEnabledSet | `78` | 此操作在预览中。 站点管理员或所有者为 SharePoint 或 OneDrive for Business 站点启用 RSS 源。 全局管理员可以在 SharePoint 管理中心为整个组织启用 RSS 源。 |
| ODBNextUXSettings | `79` | 此操作在预览中。 OneDrive for Business 的新 UI 已启用。 |
| OfficeOnDemandSet | `80` | 此操作在预览中。 站点管理员启用 Office on Demand，允许用户访问最新版本的 Office 桌面应用程序。 Office on Demand 在 SharePoint 管理中心启用，并且需要包含完整安装的 Office 应用程序的 Office 365 订阅。 |
| PageViewed | `81` | 用户查看 SharePoint 网站或 OneDrive for Business 网站上的页面。 这不包括在浏览器上从 SharePoint 网站或 One Drive for Business 网站查看文档库文件。 |
| PeopleResultsScopeSet | `82` | 此操作在预览中。 站点管理员为 SharePoint 站点的人员搜索创建或更改结果源。 |
| PermissionSyncSettingModified | `83` | 用户在 Project Web App 中修改项目权限同步设置。 |
| PermissionTemplateModified | `84` | 用户在 Project Web App 中创建、修改或删除权限模板。 |
| PortfolioDataAccessed | `85` | 用户在 Project Web App 中访问投资组合内容（驱动程序库、驱动程序优先级、投资组合分析）。 |
| PortfolioDataModified | `86` | 用户在 Project Web App 中创建、修改或删除项目组合数据（驱动程序库、驱动程序优先级、项目组合分析）。 |
| PreviewModeEnabledSet | `87` | 此操作在预览中。 站点管理员启用 SharePoint 站点的文档预览。 |
| ProjectAccessed | `88` | 用户访问 Project Web App 中的项目内容。 |
| ProjectCheckedIn | `89` | 用户签入他们从 Project Web App 签出的项目。 |
| ProjectCheckedOut | `90` | 用户签出位于 Project Web App 中的项目。用户可以签出并更改他们有权打开的项目。 |
| ProjectCreated | `91` | 用户在 Project Web App 中创建项目。 |
| ProjectDeleted | `92` | 用户删除 Project Web App 中的项目。 |
| ProjectForceCheckedIn | `93` | 用户强制签入 Project Web App 中的项目。 |
| ProjectModified | `94` | 用户在 Project Web App 中修改项目。 |
| ProjectPublished | `95` | 用户在 Project Web App 中发布项目。 |
| ProjectWorkflowRestarted | `96` | 用户在 Project Web App 中重新启动工作流。 |
| PWASettingsAccessed | `97` | 用户通过 CSOM 访问 Project Web App 设置。 |
| PWASettingsModified | `98` | 用户修改 Project Web App 配置。 |
| QueueJobStateModified | `99` | 用户取消或重新启动 Project Web App 中的队列作业。 |
| QuotaWarningEnabledModified | `100` | 此操作在预览中。 存储配额警告已修改。 |
| RenderingEnabled | `101` | 此操作在预览中。 InfoPath 表单服务将呈现启用浏览器的表单模板。 |
| ReportingAccessed | `102` | 用户访问了 Project Web App 中的报告终结点。 |
| ReportingSettingModified | `103` | 用户修改 Project Web App 中的报告配置。 |
| ResourceAccessed | `104` | 用户访问 Project Web App 中的企业资源内容。 |
| ResourceCheckedIn | `105` | 用户签入他们从 Project Web App 签出的企业资源。 |
| ResourceCheckedOut | `106` | 用户签出位于 Project Web App 中的企业资源。 |
| ResourceCreated | `107` | 用户在 Project Web App 中创建企业资源。 |
| ResourceDeleted | `108` | 用户删除 Project Web App 中的企业资源。 |
| ResourceForceCheckedIn | `109` | 用户强制签入 Project Web App 中的企业资源。 |
| ResourceModified | `110` | 用户在 Project Web App 中修改企业资源。 |
| ResourcePlanCheckedInOrOut | `111` | 用户在 Project Web App 中签入或签出资源计划。 |
| ResourcePlanModified | `112` | 用户在 Project Web App 中修改资源计划。 |
| ResourcePlanPublished | `113` | 用户在 Project Web App 中发布资源计划。 |
| ResourceRedacted | `114` | 用户编辑企业资源，删除 Project Web App 中的所有个人信息。 |
| ResourceWarningEnabledModified | `115` | 此操作在预览中。 资源配额警告已修改。 |
| SSOGroupCredentialsSet | `116` | 此操作在预览中。 安全存储服务中设置的组凭据。 |
| SSOUserCredentialsSet | `117` | 此操作在预览中。 安全存储服务中设置的用户凭据。 |
| SearchCenterUrlSet | `118` | 此操作在预览中。 搜索中心 URL 集。 |
| SecondaryMySiteOwnerSet | `119` | 此操作在预览中。 用户已将二级所有者添加到其 MySite。 |
| SecurityCategoryModified | `120` | 用户在 Project Web App 中创建、修改或删除安全类别。 |
| SecurityGroupModified | `121` | 用户在 Project Web App 中创建、修改或删除安全组。 |
| SendToConnectionAdded | `122` | 此操作在预览中。 全局管理员在 SharePoint 管理中心的记录管理页面上创建新的发送到连接。 发送到连接指定文档存储库或记录中心的设置。 当您创建发送到连接时，内容组织者可以将文档提交到指定位置。 |
| SendToConnectionRemoved | `123` | 此操作在预览中。 全局管理员在 SharePoint 管理中心的记录管理页面上删除了发送到连接。 |
| SharedLinkCreated | `124` | 用户创建指向 SharePoint 或 OneDrive for Business 中的共享文件的链接。 这个链接可以发送给其他人，让他们访问该文件。 用户可以创建两种类型的链接:允许用户查看和编辑共享文件的链接，或允许用户仅查看文件的链接。 |
| SharedLinkDisabled | `125` | 此操作在预览中。 用户禁用（永久）为共享文件而创建的链接。 |
| SharingInvitationAccepted | `126` | 此操作在预览中。 用户接受共享文件或文件夹的邀请。当用户与其他用户共享文件时，会记录此事件。 |
| SharingRevoked | `127` | 此操作在预览中。 用户取消共享之前与其他用户共享的文件或文件夹。当用户停止与其他用户共享文件时，将记录此事件。 |
| SharingSet | `128` | 用户与组织内的其他用户共享位于 SharePoint 或 OneDrive for Business 中的文件或文件夹。 |
| SiteAdminChangeRequest | `129` | 此操作在预览中。 用户请求添加为 SharePoint 网站集的网站集管理员。 网站集管理员对网站集和所有子网站具有完全控制权限。 |
| SiteCollectionAdminAdded | `130` | 此操作在预览中。 网站集管理员或所有者添加一个人作为 SharePoint 或 OneDrive for Business 网站的网站集管理员。 网站集管理员对网站集和所有子网站具有完全控制权限。 |
| SiteCollectionCreated | `131` | 此操作在预览中。 全局管理员在您的 SharePoint 组织中创建一个新网站集。 |
| SiteRenamed | `132` | 此操作在预览中。 网站管理员或所有者重命名 SharePoint 或 OneDrive for Business 网站 |
| StatusReportModified | `133` | 用户在 Project Web App 中创建、修改或删除状态报告。 |
| SyncGetChanges | `134` | 此操作在预览中。 用户在 SharePoint 或 OneDrive for Business 的操作托盘中单击同步，以将文档库中文件的任何更改同步到他们的计算机。 |
| TaskStatusAccessed | `135` | 用户访问 Project Web App 中一项或多项任务的状态。 |
| TaskStatusApproved | `136` | 用户批准 Project Web App 中一项或多项任务的状态更新。 |
| TaskStatusRejected | `137` | 用户拒绝 Project Web App 中一项或多项任务的状态更新。 |
| TaskStatusSaved | `138` | 用户在 Project Web App 中保存一个或多个任务的状态更新。 |
| TaskStatusSubmitted | `139` | 用户提交 Project Web App 中一项或多项任务的状态更新。 |
| TimesheetAccessed | `140` | 用户访问 Project Web App 中的时间表。 |
| TimesheetApproved | `141` | 用户在 Project Web App 中批准时间表。 |
| TimesheetRejected | `142` | 用户拒绝 Project Web App 中的时间表。 |
| TimesheetSaved | `143` | 用户在 Project Web App 中保存时间表。 |
| TimesheetSubmitted | `144` | 用户在 Project Web App 中提交状态时间表。 |
| UnmanagedSyncClientBlocked | `145` | 用户尝试从非组织域成员的计算机与 SharePoint 或 OneDrive for Business 网站 建立同步关系或者是尚未添加到可以访问组织中的文档库的域列表（称为安全收件人列表）的域 的成员。 不允许同步关系，阻止用户电脑同步、下载或上传文档库中的文件。 有关此功能的信息，请参阅使用 Windows PowerShell cmdlet 为安全收件人列表中的域启用 OneDrive 同步。 |
| UpdateSSOApplication | `146` | 此操作在预览中。 目标应用程序在安全存储服务中更新。 |
| UserAddedToGroup | `147` | 此操作在预览中。 站点管理员或所有者将人员添加到 SharePoint 或 OneDrive for Business 站点上的组。 将一个人添加到组会授予用户分配给组的权限。 |
| UserRemovedFromGroup | `148` | 此操作在预览中。 网站管理员或所有者从 SharePoint 或 OneDrive for Business 网站上的组中删除人员。 删除此人后，他们不再被授予分配给该组的权限。 |
| WorkflowModified | `149` | 用户在 Project Web App 中创建、修改或删除企业项目类型或工作流阶段或阶段。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
