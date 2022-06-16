---
title: IGraphClient
second_title: Aspose.Email for .NET API 参考
description: 表示 Exchange REST 客户端的接口
type: docs
weight: 15950
url: /zh/net/aspose.email.clients.graph/igraphclient/
---
## IGraphClient interface

表示 Exchange REST 客户端的接口。

```csharp
public interface IGraphClient : IDisposable
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [MultipleServicesTokenProvider](../../aspose.email.clients.graph/igraphclient/multipleservicestokenprovider) { get; set; } | 获取或设置允许检索 OAuth 访问令牌的对象。 |
| [Proxy](../../aspose.email.clients.graph/igraphclient/proxy) { get; set; } | 获取或设置数据以代理访问 Exchange 服务器。 |
| [Resource](../../aspose.email.clients.graph/igraphclient/resource) { get; set; } | 获取或设置资源类型。 |
| [ResourceId](../../aspose.email.clients.graph/igraphclient/resourceid) { get; set; } | 获取或设置资源ID。 例如对于用户，它可能是用户主体名称 (UPN) 或用户 ID |
| [TenantId](../../aspose.email.clients.graph/igraphclient/tenantid) { get; set; } | 获取或设置租户标识符 |
| [Timeout](../../aspose.email.clients.graph/igraphclient/timeout) { get; set; } | 获取或设置操作超时前等待的毫秒数。 默认值为 100,000 毫秒（100 秒）。 |
| [TokenProvider](../../aspose.email.clients.graph/igraphclient/tokenprovider) { get; set; } | 获取或设置允许检索 OAuth 访问令牌的对象。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CopyFolder](../../aspose.email.clients.graph/igraphclient/copyfolder)(string, string) | 将一个邮件文件夹及其内容复制到另一个邮件文件夹。 |
| [CopyMessage](../../aspose.email.clients.graph/igraphclient/copymessage)(string, string) | 将邮件复制到另一个邮件文件夹。 |
| [CopyNotebook](../../aspose.email.clients.graph/igraphclient/copynotebook)(string, string, string) | 将笔记本复制到目标文档库中的笔记本文件夹。如果文件夹不存在，则会创建该文件夹。 对于复制操作，您遵循异步调用模式:首先调用复制操作，然后轮询操作端点以获取结果。 权限 调用此 API 需要以下权限之一。 Delegated（工作或学校帐户）Notes.Create、Notes.ReadWrite、Notes.ReadWrite.All Delegated（个人 Microsoft 帐户）Notes.Create、Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateAttachment](../../aspose.email.clients.graph/igraphclient/createattachment)(string, MapiAttachment) | 为指定项目创建新附件 |
| [CreateCategory](../../aspose.email.clients.graph/igraphclient/createcategory)(string, CategoryPreset) | 在用户的主类别列表中创建[`OutlookCategory`](../outlookcategory)对象。 |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder)(string) | 创建新文件夹。 |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder_1)(string, string) | 创建新文件夹。 |
| [CreateMessage](../../aspose.email.clients.graph/igraphclient/createmessage)(string, MapiMessage) | 在指定文件夹中创建消息 |
| [CreateNotebook](../../aspose.email.clients.graph/igraphclient/createnotebook)(Notebook) | 创建一个新的 OneNote 笔记本。 权限 调用此 API 需要以下权限之一。 委托（工作或学校帐户）Notes.Create、Notes.ReadWrite、Notes.ReadWrite.All 委托（个人 Microsoft 帐户）Notes.Create、Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride)(ClassificationOverride) | 为由 SMTP 地址标识的发件人创建覆盖。 来自该 SMTP 地址的未来邮件将始终按照覆盖中指定的方式分类。 注意 - 如果已存在具有相同 SMTP 地址的覆盖，则使用提供的值更新该覆盖的分类和名称字段。 - 邮箱支持的最大覆盖数为 1000，基于唯一的发件人 SMTP 地址。 权限: Delegated（工作或学校帐户） Mail.ReadWrite Delegated（个人 Microsoft 帐户） Mail.ReadWrite Application Mail.ReadWrite |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride_1)(MailAddress, ClassificationType) | 为由 SMTP 地址标识的发件人创建覆盖。 来自该 SMTP 地址的未来邮件将始终按照覆盖中指定的方式分类。 注意 - 如果已存在具有相同 SMTP 地址的覆盖，则使用提供的值更新该覆盖的分类和名称字段。 - 邮箱支持的最大覆盖数为 1000，基于唯一的发件人 SMTP 地址。 权限: Delegated（工作或学校帐户） Mail.ReadWrite Delegated（个人 Microsoft 帐户） Mail.ReadWrite Application Mail.ReadWrite |
| [CreateRule](../../aspose.email.clients.graph/igraphclient/createrule)(InboxRule) | 通过指定一组条件和操作来创建消息规则。 如果用户收件箱中的传入邮件满足指定条件，Outlook 将执行这些操作。 权限： 调用此 API 需要以下权限之一。要了解更多信息，包括如何选择权限，请参阅权限。 委托（工作或学校帐户）MailboxSettings.ReadWrite 委派（个人 Microsoft 帐户）MailboxSettings.ReadWrite 应用程序邮箱设置.ReadWrite |
| [Delete](../../aspose.email.clients.graph/igraphclient/delete)(string) | 删除对象。 |
| [DeleteAttachment](../../aspose.email.clients.graph/igraphclient/deleteattachment)(string) | 删除附件 |
| [FetchAttachment](../../aspose.email.clients.graph/igraphclient/fetchattachment)(string) | 获取指定 id 的附件 |
| [FetchCategory](../../aspose.email.clients.graph/igraphclient/fetchcategory)(string) | 获取指定outlookCategory对象的属性和关系。 |
| [FetchMessage](../../aspose.email.clients.graph/igraphclient/fetchmessage)(string) | 获取指定 id 中的消息 |
| [FetchNotebook](../../aspose.email.clients.graph/igraphclient/fetchnotebook)(string) | 检索笔记本对象的属性和关系。 权限 调用此 API 需要以下权限之一。 Delegated（工作或学校帐户） Notes.Create、Notes.Read、Notes.ReadWrite、Notes.Read.All、Notes.ReadWrite.All Delegated（个人 Microsoft 帐户） Notes.Create、Notes.Read、Notes.ReadWrite 应用程序 Notes.Read.All、Notes.ReadWrite.All |
| [FetchRule](../../aspose.email.clients.graph/igraphclient/fetchrule)(string) | 获取消息规则对象的属性和关系。 权限 调用此 API 需要以下权限之一。要了解更多信息，包括如何选择权限，请参阅权限。 委派（工作或学校帐户）MailboxSettings.Read 委派（个人 Microsoft 帐户）MailboxSettings.Read 应用程序邮箱设置.读取 |
| [GetFolder](../../aspose.email.clients.graph/igraphclient/getfolder)(string) | 通过 id 获取文件夹。 |
| [GetOneNoteOperationStatus](../../aspose.email.clients.graph/igraphclient/getonenoteoperationstatus)(string) | 获取长时间运行的 OneNote 操作的状态。 这适用于在响应中返回 Operation-Location 标头的操作，例如 CopyNotebook、CopyToNotebook、CopyToSectionGroup 和 CopyToSection。 您可以轮询 Operation-Location 端点，直到状态属性返回完成或失败。 如果状态为已完成，则 resourceLocation 属性包含资源端点 URI。 如果状态为失败，则错误和@api.diagnostics 属性提供错误信息。 |
| [ListAttachments](../../aspose.email.clients.graph/igraphclient/listattachments)(string) | 列出来自父消息的附件。 |
| [ListCategories](../../aspose.email.clients.graph/igraphclient/listcategories)() | 获取已为用户定义的所有类别。 |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders)() | 列出在普通邮件客户端（例如收件箱）中显示的文件夹的父文件夹中的文件夹。 |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders_1)(string) | 列出在普通邮件客户端（例如收件箱）中显示的文件夹的父文件夹中的文件夹。 |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages_1)(string) | 列出父文件夹中的 MessageInfo。 |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages)(string, PageInfo, MailQuery) | 列出父文件夹中的 MessageInfo。 |
| [ListNotebooks](../../aspose.email.clients.graph/igraphclient/listnotebooks)() | 检索笔记本对象列表。 权限 调用此 API 需要以下权限之一。 Delegated（工作或学校帐户） Notes.Create、Notes.Read、Notes.ReadWrite、Notes.Read.All、Notes.ReadWrite.All Delegated（个人 Microsoft 帐户） Notes.Create、Notes.Read、Notes.ReadWrite 应用程序 Notes.Read.All、Notes.ReadWrite.All |
| [ListOverrides](../../aspose.email.clients.graph/igraphclient/listoverrides)() | 获取用户设置的覆盖，以始终以特定方式对来自某些发件人的邮件进行分类。 每个覆盖对应于发件人的一个 SMTP 地址。最初，用户没有任何覆盖。 权限： 调用此 API 需要以下权限之一。要了解更多信息，包括如何选择权限，请参阅权限。 委派（工作或学校帐户）Mail.Read 委托（个人 Microsoft 帐户）Mail.Read 申请邮件.阅读 |
| [ListRules](../../aspose.email.clients.graph/igraphclient/listrules)() | 获取为用户收件箱定义的所有 messageRule 对象。 权限 调用此 API 需要以下权限之一。要了解更多信息，包括如何选择权限，请参阅权限。 委派（工作或学校帐户）MailboxSettings.Read 委派（个人 Microsoft 帐户）MailboxSettings.Read 应用程序邮箱设置.读取 |
| [MoveFolder](../../aspose.email.clients.graph/igraphclient/movefolder)(string, string) | 将一个邮件文件夹及其内容移动到另一个邮件文件夹。 |
| [MoveMessage](../../aspose.email.clients.graph/igraphclient/movemessage)(string, string) | 将邮件移动到另一个邮件文件夹。 |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send)(MapiMessage) | 发送电子邮件 |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_2)(string) | 在草稿文件夹中发送消息。 草稿消息可以是新消息草稿、回复草稿、全部回复草稿或转发草稿。 邮件然后保存在已发送邮件文件夹中。 |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_1)(MapiMessage, bool) | 发送电子邮件 |
| [SetRead](../../aspose.email.clients.graph/igraphclient/setread)(string) | 将消息标记为已读 |
| [UpdateCategory](../../aspose.email.clients.graph/igraphclient/updatecategory)(OutlookCategory) | 更新指定类别的预设颜色常数 |
| [UpdateFolder](../../aspose.email.clients.graph/igraphclient/updatefolder)(FolderInfo) | 更新文件夹。 |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage)(MapiMessage) | 更新消息 |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage_1)(MapiMessage, UpdateSettings) | 更新消息 |
| [UpdateOverride](../../aspose.email.clients.graph/igraphclient/updateoverride)(ClassificationOverride) | 按指定更改覆盖的分类作为字段。 您不能使用此方法更改 ClassificationOverride 实例中的任何其他字段。 如果发件人存在覆盖并且发件人更改了他/她的显示名称，您可以使用 CreateOrUpdateOverride 强制更新现有覆盖中的名称字段。 如果发件人存在覆盖并且发件人更改了他/她的 SMTP 地址， 删除现有覆盖并使用新的 SMTP 地址创建一个新覆盖是“更新”此发件人覆盖的唯一方法。 权限： 调用此 API 需要以下权限之一。要了解更多信息，包括如何选择权限，请参阅权限。 委托（工作或学校帐户）Mail.ReadWrite 委托（个人 Microsoft 帐户）Mail.ReadWrite 应用程序 Mail.ReadWrite |
| [UpdateRule](../../aspose.email.clients.graph/igraphclient/updaterule)(InboxRule) | 更改 messageRule 对象的可写属性并保存更改。 权限 调用此 API 需要以下权限之一。要了解更多信息，包括如何选择权限，请参阅权限。 委托（工作或学校帐户）MailboxSettings.ReadWrite 委派（个人 Microsoft 帐户）MailboxSettings.ReadWrite 应用程序邮箱设置.ReadWrite |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
