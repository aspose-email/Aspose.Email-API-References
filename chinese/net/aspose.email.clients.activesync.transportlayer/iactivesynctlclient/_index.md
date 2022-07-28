---
title: IActiveSyncTLClient
second_title: Aspose.Email for .NET API 参考
description: ActiveSync 客户端接口
type: docs
weight: 1310
url: /zh/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/
---
## IActiveSyncTLClient interface

ActiveSync 客户端接口

```csharp
public interface IActiveSyncTLClient : IBaseActiveSyncTLClient
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AirSyncKeys](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/airsynckeys) { get; } | 包含服务器用来标记每个同步集合的同步状态的值。 其中字典键是服务器 ID，字典值是 SyncKey。 用于 GetItemEstimate 和 Sync 命令。 |
| [FoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderssynckey) { get; } | 由服务器用来跟踪客户端的当前状态。 仅用于文件夹操作 |
| [HeartbeatInterval](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/heartbeatinterval) { get; set; } | HeartbeatInterval 元素是 Ping 命令请求和响应中 Ping 元素的子元素。 在 Ping 命令请求中，它指定时间长度，以秒为单位，如果没有新项目添加到指定的文件夹集，服务器应该在发送响应之前等待 ，如第 3.1.5.6 节所述。 HeartbeatInterval 元素也由服务器返回，状态代码为 5 ，并指定客户端请求的心跳间隔超出可接受范围时允许的最小或最大间隔 。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [FolderCreate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldercreate)(string, string, UserCreatedFolderTypes) | FolderCreate 创建一个新文件夹作为指定父文件夹的子文件夹。 |
| [FolderDelete](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderdelete)(string) | 删除具有匹配标识符的集合。 |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync)() | FolderSync 同步集合层次结构，但不同步集合中的项目本身。 |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync_1)(bool) | FolderSync 同步集合层次结构，但不同步集合中的项目本身。 |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate)(FolderInfo) | FolderUpdate 命令将文件夹从服务器上的一个位置移动到另一个位置。 该命令也用于重命名文件夹。 |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate_1)(string, string, string) | FolderUpdate 命令将文件夹从服务器上的一个位置移动到另一个位置。 该命令也用于重命名文件夹。 |
| [GetAttachment](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getattachment)(string) | GetAttachment 从服务器检索电子邮件附件。 当协议版本为 14.0 或 14.1 时，不支持 GetAttachment。 改用 ItemOperations 命令的 Fetch 元素。 |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_2)(IEnumerable&lt;ItemEstimateRequest&gt;) | GetItemEstimate 命令获取服务器上集合或文件夹中必须同步的项目数的估计值。 |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate)(ItemEstimateRequest) | GetItemEstimate 命令获取服务器上集合或文件夹中必须同步的项目数的估计值。 |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_1)(params ItemEstimateRequest[]) | GetItemEstimate 命令获取服务器上集合或文件夹中必须同步的项目数的估计值。 |
| [ItemOperations](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/itemoperations)(ItemOperationsRequest) | ItemOperations 提供对 Fetch、EmptyFolderContents 和 Move 操作的批量在线处理。 |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_3)(IEnumerable&lt;MeetingResponseRequest&gt;) | 接受、暂时接受或拒绝用户收件箱文件夹或日历文件夹中的会议请求。 |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_2)(params MeetingResponseRequest[]) | 接受、暂时接受或拒绝用户收件箱文件夹或日历文件夹中的会议请求。 |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse)(UserResponse, string, string) | 接受、暂时接受或拒绝用户收件箱文件夹或日历文件夹中的会议请求。 |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_1)(UserResponse, string, string, string, string) | 接受、暂时接受或拒绝用户收件箱文件夹或日历文件夹中的会议请求。 |
| [MoveItem](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitem)(string, string, string) | MoveItems 命令将一个或多个项目从服务器上的一个文件夹移动到另一个文件夹。 |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems_1)(IEnumerable&lt;MoveItemData&gt;) | MoveItems 命令将一个或多个项目从服务器上的一个文件夹移动到另一个文件夹。 |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems)(params MoveItemData[]) | MoveItems 命令将一个或多个项目从服务器上的一个文件夹移动到另一个文件夹。 |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_4)(IEnumerable&lt;PingParameter&gt;) | Ping 命令用于请求服务器监视指定文件夹以查找需要客户端重新同步的更改。 |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping)(params PingParameter[]) | Ping 命令用于请求服务器监视指定文件夹以查找需要客户端重新同步的更改。 |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_2)(int, IEnumerable&lt;PingParameter&gt;) | Ping 命令用于请求服务器监视指定文件夹以查找需要客户端重新同步的更改。 |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_1)(int, params PingParameter[]) | Ping 命令用于请求服务器监视指定文件夹以查找需要客户端重新同步的更改。 |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_5)(string, FolderClass) | Ping 命令用于请求服务器监视指定文件夹以查找需要客户端重新同步的更改。 |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_3)(int, string, FolderClass) | Ping 命令用于请求服务器监视指定文件夹以查找需要客户端重新同步的更改。 |
| [Provision](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/provision)(ProvisionRequest) | Provision 命令使客户端设备能够从服务器请求管理员设置的安全策略设置， 例如最小个人识别码 (PIN) 密码长度要求。 |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey)() | 重置所有集合的 GetItemEstimate 和同步操作的 SyncKeys。 |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey_1)(string) | 重置 GetItemEstimate 的 SyncKey 和定义集合的同步操作。 |
| [ResetFoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetfolderssynckey)() | 为文件夹操作重置 SyncKey |
| [ResolveRecipients](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resolverecipients)(ResolveRecipientsRequest) | ResolveRecipients 用于解析提供的收件人列表，检索他们的忙/闲信息，并可选择检索他们的 S/MIME 证书，以便客户端可以发送加密的 S/MIME 电子邮件。 检索忙/闲信息当协议版本为 12.1. 时，不支持在 ResolveRecipients 命令中使用可用性元素 |
| [Search](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/search)(SearchRequest) | 搜索用于在地址簿、邮箱或文档库（UNC 或 Windows SharePoint Services）中查找条目。 |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail)(string) | 客户端使用 SendMail 将 MIME 格式的电子邮件消息发送到服务器。 |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_1)(string, bool) | 客户端使用 SendMail 将 MIME 格式的电子邮件消息发送到服务器。 |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_2)(string, bool, string) | 客户端使用 SendMail 将 MIME 格式的电子邮件消息发送到服务器。 |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_3)(string, bool, string, string) | 客户端使用 SendMail 将 MIME 格式的电子邮件消息发送到服务器。 |
| [Settings](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/settings)(SettingsRequest) | 设置支持对全局属性和用户外出 (OOF) 设置的获取和设置操作。 设置还将设备信息发送到服务器，实现设备密码/个人识别码 (PIN) 恢复，并检索用户的电子邮件地址列表。 |
| [SmartForward](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartforward)(SmartRequest) | 客户端使用 SmartForward 命令转发消息，而无需从服务器检索完整的原始消息。 |
| [SmartReply](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartreply)(SmartRequest) | 客户端使用 SmartReply 命令回复消息，而无需从服务器检索完整的原始消息。 |
| [Sync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sync)(SyncRequest) | Sync 在客户端和服务器之间同步集合中的更改。 |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert)(IEnumerable&lt;X509Certificate&gt;) | ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。 |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_4)(X509Certificate) | ValidateCert 命令被客户端用来验证通过 S/MIME 邮件收到的证书。 |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_1)(IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。 |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_2)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) | ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。 |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_5)(X509Certificate, bool) | ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。 |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_6)(X509Certificate, IEnumerable&lt;X509Certificate&gt;) | ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。 |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_3)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。 |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_7)(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。 |

### 也可以看看

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
