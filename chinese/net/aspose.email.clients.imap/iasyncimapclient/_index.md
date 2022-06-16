---
title: IAsyncImapClient
second_title: Aspose.Email for .NET API 参考
description: 允许应用程序使用 Internet 消息访问协议 IMAP 访问和操作 消息
type: docs
weight: 16240
url: /zh/net/aspose.email.clients.imap/iasyncimapclient/
---
## IAsyncImapClient interface

允许应用程序使用 Internet 消息访问协议 (IMAP) 访问和操作 消息。

```csharp
public interface IAsyncImapClient
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/addmessageflagsasync)(ImapChangeMessageFlags) | 将标志添加到消息 |
| [AppendMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessageasync)(MailMessage, string, IConnection, CancellationToken) | 将邮件信息上传到指定文件夹 |
| [AppendMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, string, IConnection, CancellationToken) | 将邮件信息上传到当前文件夹 |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) | 备份指定文件夹的内容 |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync_1)(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) | 备份指定文件夹的内容 |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/changemessageflagsasync)(ImapChangeMessageFlags) | 更改消息的标志 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | 通知服务器客户端支持哪些扩展。 请注意，此操作仅适用于服务器支持 RFC5161 查看更多 https://tools.ietf.org/html/rfc5161 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/iasyncimapclient/commitdeletesasync)(ImapUniqueIdParameterSet) | 提交删除 |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync)(int, string, IConnection, CancellationToken) | 复制消息 |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync_1)(string, string, IConnection, CancellationToken) | 复制消息。 |
| [CopyMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessagesasync)(ImapCopyMessages) | 复制消息。 |
| [CreateFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/createfolderasync)(string, IConnection, CancellationToken) | 创建具有指定名称的文件夹。 |
| [DeleteFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/deletefolderasync)(string, IConnection, CancellationToken) | 删除指定文件夹。此方法代表 IMAP DELETE 命令。 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/deletemessagesasync)(ImapDeleteMessages) | 将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| [ExistFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/existfolderasync)(string, IConnection, CancellationToken) | 检查此文件夹是否存在 |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync)(int, string, IConnection, CancellationToken) | 获取指定的附件。 |
| [FetchMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchmessagesasync)(ImapFetchMessages) | 异步获取消息 |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/iasyncimapclient/getfolderinfoasync)(string, IConnection, CancellationToken) | 返回有关指定文件夹的信息而不选择它 |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/getmessagethreadsasync)(BaseSearchConditions, IConnection, CancellationToken) | 获取消息线程。 |
| [GetNamespacesAsync](../../aspose.email.clients.imap/iasyncimapclient/getnamespacesasync)(IConnection, CancellationToken) | 获取服务器上可用的命名空间。 |
| [GetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotaasync)(string, IConnection, CancellationToken) | 获取配额信息 |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotarootasync)(string, IConnection, CancellationToken) | 获取邮箱的配额根信息 |
| [IntroduceClientAsync](../../aspose.email.clients.imap/iasyncimapclient/introduceclientasync)(ImapIdentificationInfo, IConnection, CancellationToken) | 将客户端信息引入服务器。 |
| [ListFoldersAsync](../../aspose.email.clients.imap/iasyncimapclient/listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, IConnection, CancellationToken) | 获取指定文件夹中的子文件夹列表 |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync)(int, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | 获取有关消息的信息。 |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync_1)(string, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | 获取有关消息的信息。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync)(MailQuery, string, int, IConnection, CancellationToken) | 获取当前文件夹中的邮件列表。 |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync_1)(string, long, bool, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | 获取指定文件夹中的消息列表 |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync_1)(int, int, PageSettings, CancellationToken) | 获取消息列表 |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) | 获取消息列表 |
| [MoveFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/movefolderasync)(string, string, IConnection, CancellationToken) | 将指定文件夹及其子文件夹移动到新位置。 |
| [MoveMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/movemessagesasync)(ImapMoveMessages) | 移动消息。 |
| [NoopAsync](../../aspose.email.clients.imap/iasyncimapclient/noopasync)(IConnection, CancellationToken) | 'No operation' 命令 |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/removemessageflagsasync)(ImapChangeMessageFlags) | 删除消息的标志 |
| [RenameFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/renamefolderasync)(string, string, IConnection, CancellationToken) | 将指定文件夹重命名为新名称 |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/iasyncimapclient/requestcheckpointasync)(IConnection, CancellationToken) | 请求当前选定邮箱的检查点。 |
| [RestoreAsync](../../aspose.email.clients.imap/iasyncimapclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | 开始从给定的个人存储中恢复 imap 文件夹。 |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | 恢复监视指定文件夹的消息更改。 与 StartMonitoring 方法不同，它会找到所有丢失的邮箱更改并为它们调用 回调。 |
| [SelectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/selectfolderasync)(string, bool?, IConnection, CancellationToken) | 选择指定文件夹 |
| [SetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/setquotaasync)(string, string, int, IConnection, CancellationToken) | 设置配额信息 |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/sortmessagethreadsasync)(SortConditions, IConnection, CancellationToken) | 对消息线程进行排序。 |
| [StartMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | 开始监视指定文件夹的消息更改。 |
| [StopMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/stopmonitoringasync)(string, CancellationToken) | 停止监视指定文件夹的消息更改。如果 folderName 为空，则停止监视所有文件夹。 |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/subscribefolderasync)(string, IConnection, CancellationToken) | 发送 SUBSCRIBE 命令，将指定的邮箱名称添加到服务器的“活动”邮箱集。 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync)(int, long, IConnection, CancellationToken) | 将具有指定序列号的消息标记为未删除 |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync_1)(string, long, IConnection, CancellationToken) | 将具有指定序列号的消息标记为未删除。 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unselectfolderasync)(bool, IConnection, CancellationToken) | 取消选择当前选择的文件夹。 如果 doNotExpunge 属性为 true，则删除所有标记为已删除的消息，否则取消删除。 请注意，此操作仅适用于服务器支持 RFC3691 查看更多 https://tools.ietf.org/html/rfc3691 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unsubscribefolderasync)(string, IConnection, CancellationToken) | 发送了 UNSUBSCRIBE 命令，从服务器的“活动”邮箱集中删除指定的邮箱名称 |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/iasyncimapclient/validatecredentialsasync)(IConnection, CancellationToken) | 执行凭据验证 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
