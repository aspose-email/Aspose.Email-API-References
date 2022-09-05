---
title: UserSettingName
second_title: Aspose.Email for .NET API 参考
description: 可以使用 GetUserSettings 请求的用户设置
type: docs
weight: 3600
url: /zh/net/aspose.email.clients.exchange/usersettingname/
---
## UserSettingName enumeration

可以使用 GetUserSettings 请求的用户设置。

```csharp
public enum UserSettingName
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| UserDisplayName | `0` | 用户的显示名称。 |
| UserDN | `1` | 用户的旧专有名称。 |
| UserDeploymentId | `2` | 用户的部署ID。 |
| InternalMailboxServer | `3` | 邮箱服务器的完全限定域名。 |
| InternalRpcClientServer | `4` | RPC 客户端服务器的完全限定域名。 |
| InternalMailboxServerDN | `5` | 邮箱服务器的旧专有名称。 |
| InternalEcpUrl | `6` | Exchange 控制面板的内部 URL。 |
| InternalEcpVoicemailUrl | `7` | 用于语音邮件自定义的 Exchange 控制面板的内部 URL。 |
| InternalEcpEmailSubscriptionsUrl | `8` | 电子邮件订阅的 Exchange 控制面板的内部 URL。 |
| InternalEcpTextMessagingUrl | `9` | 用于文本消息的 Exchange 控制面板的内部 URL。 |
| InternalEcpDeliveryReportUrl | `10` | 传递报告的 Exchange 控制面板的内部 URL。 |
| InternalEcpRetentionPolicyTagsUrl | `11` | RetentionPolicy 标记的 Exchange 控制面板的内部 URL。 |
| InternalEcpPublishingUrl | `12` | 用于发布的 Exchange 控制面板的内部 URL。 |
| InternalEcpPhotoUrl | `13` | 照片的 Exchange 控制面板的内部 URL。 |
| InternalEcpConnectUrl | `14` | 用于 People Connect 订阅的 Exchange 控制面板的内部 URL。 |
| InternalEcpTeamMailboxUrl | `15` | 团队邮箱的 Exchange 控制面板的内部 URL。 |
| InternalEcpTeamMailboxCreatingUrl | `16` | 用于创建团队邮箱的 Exchange 控制面板的内部 URL。 |
| InternalEcpTeamMailboxEditingUrl | `17` | 用于编辑团队邮箱的 Exchange 控制面板的内部 URL。 |
| InternalEcpTeamMailboxHidingUrl | `18` | 用于隐藏团队邮箱的 Exchange 控制面板的内部 URL。 |
| InternalEcpExtensionInstallationUrl | `19` | 用于扩展安装的 Exchange 控制面板的内部 URL。 |
| InternalEwsUrl | `20` | Exchange Web 服务的内部 URL。 |
| InternalEmwsUrl | `21` | Exchange 管理 Web 服务的内部 URL。 |
| InternalOABUrl | `22` | 脱机通讯簿的内部 URL。 |
| InternalPhotosUrl | `23` | 照片服务的内部 URL。 |
| InternalUMUrl | `24` | 统一消息服务的内部 URL。 |
| InternalWebClientUrls | `25` | Exchange Web 客户端的内部 URL。 |
| MailboxDN | `26` | 用户邮箱的邮箱数据库的可分辨名称。 |
| PublicFolderServer | `27` | 公用文件夹服务器的名称。 |
| ActiveDirectoryServer | `28` | Active Directory 服务器的名称。 |
| ExternalMailboxServer | `29` | RPC over HTTP 服务器的名称。 |
| ExternalMailboxServerRequiresSSL | `30` | 指示 RPC over HTTP 服务器是否需要 SSL。 |
| ExternalMailboxServerAuthenticationMethods | `31` | RPC over HTTP 服务器支持的身份验证方法。 |
| EcpVoicemailUrlFragment | `32` | 用于语音邮件自定义的 Exchange 控制面板的 URL 片段。 |
| EcpEmailSubscriptionsUrlFragment | `33` | 电子邮件订阅的 Exchange 控制面板的 URL 片段。 |
| EcpTextMessagingUrlFragment | `34` | 用于文本消息的 Exchange 控制面板的 URL 片段。 |
| EcpDeliveryReportUrlFragment | `35` | 用于传递报告的 Exchange 控制面板的 URL 片段。 |
| EcpRetentionPolicyTagsUrlFragment | `36` | RetentionPolicy 标记的 Exchange 控制面板的 URL 片段。 |
| EcpPublishingUrlFragment | `37` | 用于发布的 Exchange 控制面板的 URL 片段。 |
| EcpPhotoUrlFragment | `38` | 照片的 Exchange 控制面板的 URL 片段。 |
| EcpConnectUrlFragment | `39` | People Connect 的 Exchange 控制面板的 URL 片段。 |
| EcpTeamMailboxUrlFragment | `40` | 团队邮箱的 Exchange 控制面板的 URL 片段。 |
| EcpTeamMailboxCreatingUrlFragment | `41` | 用于创建团队邮箱的 Exchange 控制面板的 URL 片段。 |
| EcpTeamMailboxEditingUrlFragment | `42` | 用于编辑团队邮箱的 Exchange 控制面板的 URL 片段。 |
| EcpExtensionInstallationUrlFragment | `43` | 用于安装扩展的 Exchange 控制面板的 URL 片段。 |
| ExternalEcpUrl | `44` | Exchange 控制面板的外部 URL。 |
| ExternalEcpVoicemailUrl | `45` | 用于语音邮件自定义的 Exchange 控制面板的外部 URL。 |
| ExternalEcpEmailSubscriptionsUrl | `46` | 电子邮件订阅的 Exchange 控制面板的外部 URL。 |
| ExternalEcpTextMessagingUrl | `47` | 用于文本消息的 Exchange 控制面板的外部 URL。 |
| ExternalEcpDeliveryReportUrl | `48` | 用于传递报告的 Exchange 控制面板的外部 URL。 |
| ExternalEcpRetentionPolicyTagsUrl | `49` | RetentionPolicy 标记的 Exchange 控制面板的外部 URL。 |
| ExternalEcpPublishingUrl | `50` | 用于发布的 Exchange 控制面板的外部 URL。 |
| ExternalEcpPhotoUrl | `51` | 照片的 Exchange 控制面板的外部 URL。 |
| ExternalEcpConnectUrl | `52` | 用于 People Connect 订阅的 Exchange 控制面板的外部 URL。 |
| ExternalEcpTeamMailboxUrl | `53` | 团队邮箱的 Exchange 控制面板的外部 URL。 |
| ExternalEcpTeamMailboxCreatingUrl | `54` | 用于创建团队邮箱的 Exchange 控制面板的外部 URL。 |
| ExternalEcpTeamMailboxEditingUrl | `55` | 用于编辑团队邮箱的 Exchange 控制面板的外部 URL。 |
| ExternalEcpTeamMailboxHidingUrl | `56` | 用于隐藏团队邮箱的 Exchange 控制面板的外部 URL。 |
| ExternalEcpExtensionInstallationUrl | `57` | 扩展安装的 Exchange 控制面板的外部 URL。 |
| ExternalEwsUrl | `58` | Exchange Web 服务的外部 URL。 |
| ExternalEmwsUrl | `59` | Exchange 管理 Web 服务的外部 URL。 |
| ExternalOABUrl | `60` | 脱机通讯簿的外部 URL。 |
| ExternalPhotosUrl | `61` | 照片服务的外部 URL。 |
| ExternalUMUrl | `62` | 统一消息服务的外部 URL。 |
| ExternalWebClientUrls | `63` | Exchange Web 客户端的外部 URL。 |
| CrossOrganizationSharingEnabled | `64` | 表示已启用跨组织共享。 |
| AlternateMailboxes | `65` | 备用邮箱的集合。 |
| CasVersion | `66` | 为请求提供服务的客户端访问服务器的版本（例如 14.XX.YYY.ZZZ） |
| EwsSupportedSchemas | `67` | Exchange Web 服务支持的架构版本的逗号分隔列表。架构版本 values 将与 ExchangeServerVersion 枚举的值相同。 |
| InternalPop3Connections | `68` | pop 协议的内部连接设置列表 |
| ExternalPop3Connections | `69` | pop 协议的外部连接设置列表 |
| InternalImap4Connections | `70` | imap4协议的内部连接设置列表 |
| ExternalImap4Connections | `71` | imap4协议的外部连接设置列表 |
| InternalSmtpConnections | `72` | smtp 协议的内部连接设置列表 |
| ExternalSmtpConnections | `73` | smtp 协议的外部连接设置列表 |
| InternalServerExclusiveConnect | `74` | 如果设置为“关闭”，则客户端不应通过此协议进行连接。 协议内容仅供参考。 |
| ExternalEwsVersion | `75` | Exchange Web 服务服务器 ExternalEwsUrl 指向的版本。 |
| MobileMailboxPolicy | `76` | 移动邮箱策略设置。 |
| DocumentSharingLocations | `77` | 文档共享位置及其设置。 |
| UserMSOnline | `78` | 用户帐号是否为 MSOnline 帐号。 |
| InternalMailboxServerAuthenticationMethods | `79` | RPC 客户端服务器支持的认证方式。 |
| MailboxVersion | `80` | 托管用户邮箱的服务器版本。 |
| SPMySiteHostURL | `81` | Sharepoint MySite 主机 URL。 |
| SiteMailboxCreationURL | `82` | SharePoint 中的网站邮箱创建 URL。 Outlook 使用它直接从 SharePoint 创建网站邮箱。 |
| InternalRpcHttpServer | `83` | 用于内部 RPC/HTTP 连接的服务器的 FQDN。 |
| InternalRpcHttpConnectivityRequiresSsl | `84` | 指示内部 RPC/HTTP 连接是否需要 SSL。 |
| InternalRpcHttpAuthenticationMethod | `85` | 用于内部 RPC/HTTP 连接的身份验证方法。 |
| ExternalServerExclusiveConnect | `86` | 如果设置为“开”，则客户端只能通过此协议进行连接。 |
| ExchangeRpcUrl | `87` | 如果设置，则客户端可以通过 XTC 调用服务器 |
| ShowGalAsDefaultView | `88` | 如果设置为 false，则默认情况下客户端不应显示 GAL，而是显示联系人列表。 |
| AutoDiscoverSMTPAddress | `89` | 自动发现用户的主 SMTP 地址。 |
| InteropExternalEwsUrl | `90` | Exchange Web 服务的“互操作”外部 URL。 互操作是指 E14（或更高版本）服务器的 URL，它可以为托管在下级服务器（E2K3 和更早版本）中的邮箱 提供服务。 |
| InteropExternalEwsVersion | `91` | 服务器 InteropExternalEwsUrl 指向的版本。 |
| PublicFolderInformation | `92` | 公用文件夹（层次结构）信息 |
| RedirectUrl | `93` | 应回答此查询的 AutoDiscover 服务的相应版本 URL。 |
| EwsPartnerUrl | `94` | Office365 合作伙伴的 Exchange Web 服务的 URL。 |
| CertPrincipalName | `95` | SSL 证书名称 |
| GroupingInformation | `96` | 特定客户端的分组提示。 |
| InternalOutlookServiceUrl | `98` | 内部 Outlook 服务 URL |
| ExternalOutlookServiceUrl | `99` | 外部 Outlook 服务 URL |

### 评论

在末尾添加新值并与 Microsoft.Exchange.Autodiscover.ConfigurationSettings.UserConfigurationSettingName. 保持同步

### 也可以看看

* 命名空间 [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
