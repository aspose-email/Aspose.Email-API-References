---
title: ExchangeClient
second_title: Aspose.Email for .NET API 参考
description: ExchangeClient 类允许应用程序使用 WebDav Exchange 存储协议管理 Microsoft Exchange Server 中的电子邮件箱
type: docs
weight: 3150
url: /zh/net/aspose.email.clients.exchange.dav/exchangeclient/
---
## ExchangeClient class

ExchangeClient 类允许应用程序使用 WebDav Exchange 存储协议管理 Microsoft Exchange Server 中的电子邮件箱。

```csharp
public sealed class ExchangeClient : ExchangeClientBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ExchangeClient](exchangeclient#constructor)(string, ICredentials) | 初始化类的新实例[`ExchageClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_1)(string, string, string) | 初始化类的新实例[`ExchageClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_2)(string, string, string, string) | 初始化类的新实例[`ExchageClient`](../exchangeclient) |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ClientCertificate](../../aspose.email.clients.exchange.dav/exchangeclient/clientcertificate) { get; set; } | 获取或设置客户端证书。 |
| [CookieContainer](../../aspose.email.clients.exchange.dav/exchangeclient/cookiecontainer) { get; set; } | 获取或设置 cookie 容器。 |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | 获取或设置凭证 |
| [Encoding](../../aspose.email.clients.exchange.dav/exchangeclient/encoding) { get; set; } | 获取或设置编码。 |
| [KeepAlive](../../aspose.email.clients.exchange.dav/exchangeclient/keepalive) { get; set; } | 表示是否存活。 |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | 获取或设置日志文件名 |
| [MailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/mailboxinfo) { get; } | 获取邮箱信息。 |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | 获取或设置邮箱的uri |
| [PreAuthenticate](../../aspose.email.clients.exchange.dav/exchangeclient/preauthenticate) { get; set; } | 表示是否做预认证。 |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | 获取或设置代理。 |
| [SendChunked](../../aspose.email.clients.exchange.dav/exchangeclient/sendchunked) { get; set; } | 获取或设置一个值，指示是否[send chunked]。 |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | 获取或设置操作超时前等待的毫秒数。 默认值为 100,000 毫秒（100 秒）。 |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | 获取或设置指示是否必须在日志文件名中使用日期的值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage)(string, MailMessage) | 将邮件信息上传到指定文件夹 |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage_1)(string, MailMessage, bool) | 将邮件信息上传到指定文件夹 |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | 备份指定文件夹的内容 |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | 备份指定文件夹的内容 |
| [CreateContact](../../aspose.email.clients.exchange.dav/exchangeclient/createcontact)(Contact) | 在 Exchange 存储中创建联系人项目。 |
| [CreateFolder](../../aspose.email.clients.exchange.dav/exchangeclient/createfolder)(string, string) | 在指定的父文件夹中创建具有指定名称的新文件夹。 |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_1)(Contact) | 删除联系人。 |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact)(MapiContact) | 删除联系人。 |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_2)(string) | 删除联系人。 |
| [DeleteFolder](../../aspose.email.clients.exchange.dav/exchangeclient/deletefolder)(string) | 删除文件夹 |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage)(string) | 删除邮件信息。 |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage_1)(string, bool) | 删除邮件信息。 |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| [FetchAttachment](../../aspose.email.clients.exchange.dav/exchangeclient/fetchattachment)(string) | 获取附件 |
| [FetchMapiMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmapimessage)(string) | 获取具有指定 uri 的 mapi 消息。 |
| [FetchMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmessage)(string) | 获取具有指定 uri 的邮件消息。 |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists)(string, string) | 检查指定文件夹是否存在。 |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | 检查指定文件夹是否存在。 |
| [GetContacts](../../aspose.email.clients.exchange.dav/exchangeclient/getcontacts)(string) | 列出服务器上指定文件夹中的联系人 |
| [GetFolderInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getfolderinfo)(string) | 获取文件夹信息。 |
| [GetMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxes)() | 列出全局地址列表中的邮箱。 |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo)() | 获取邮箱信息 |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo_1)(string) | 获取邮箱信息 |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize)() | 获取邮箱大小 |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize_1)(string) | 获取邮箱大小 |
| [GetVersionInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getversioninfo)() | 返回交换服务器版本信息 |
| [ListContacts](../../aspose.email.clients.exchange.dav/exchangeclient/listcontacts)(string) | 列出服务器上指定文件夹中的联系人 |
| [ListMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/listmailboxes)() | 列出全局地址列表中的邮箱。 |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages)(string) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_3)(string, bool) | 列出指定文件夹中的消息 |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_1)(string, ExchangeListMessagesOptions) | 列出指定文件夹中的邮件消息。 |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_4)(string, int) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_6)(string, string) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_5)(string, int, ExchangeListMessagesOptions) | 列出指定文件夹中的消息 |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_2)(string, MailQuery, bool) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_7)(string, string, bool) | 列出消息。 |
| [ListMessagesById](../../aspose.email.clients.exchange.dav/exchangeclient/listmessagesbyid)(string, string) | 按 id 列出消息。 |
| [ListPublicFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listpublicfolders)() | 从根公用文件夹获取公用文件夹集合 |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | 从父级 |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders_1)(string) | 从父级获取子文件夹的集合 |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems_1)(string, params string[]) | 移动项目。 |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems)(string, bool, params string[]) | 移动项目。 |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage)(ExchangeMessageInfo, string) | 移动消息。 |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_3)(string, string) | 移动消息。 |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_1)(ExchangeMessageInfo, string, bool) | 移动消息。 |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_2)(string, bool, string) | 移动消息。 |
| [ResolveContacts](../../aspose.email.clients.exchange.dav/exchangeclient/resolvecontacts)(string) | 解决不明确的邮箱显示名称。 注意:返回联系人的最大数量为 100。这是使用交换命令的限制。 |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_1)(PersonalStorage, RestoreOptions) | 从给定的个人存储中恢复交换文件夹。 |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_3)(Stream, RestoreOptions) | 从给定的个人存储中恢复交换文件夹。 |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_5)(string, RestoreOptions) | 从指定的个人存储文件恢复交换文件夹。 |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | 从给定的个人存储中恢复指定的交换文件夹。 |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_2)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | 从给定的个人存储中恢复指定的交换文件夹。 |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_4)(string, ExchangeFolderInfoCollection, RestoreOptions) | 从指定的个人存储文件中恢复指定的交换文件夹。 |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage)(string, Stream) | 保存消息。 |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage_1)(string, string) | 将 uri 指定的邮件信息保存到本地文件系统。邮件消息文件是符合 RFC 822 的格式 (EML)。  如果要解析邮件消息文件，请使用[`MailMessage`](../../aspose.email/mailmessage)。 |
| [Send](../../aspose.email.clients.exchange.dav/exchangeclient/send)(MailMessage) | 发送邮件消息。 |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag)(string) | 将特定消息标记为已读。 |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag_1)(string, bool) | 将特定消息标记为已读。 |

### 也可以看看

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
