---
title: IEWSClient
second_title: Aspose.Email for .NET API 参考
description: 表示 Exchange 客户端的接口
type: docs
weight: 3960
url: /zh/net/aspose.email.clients.exchange.webservice/iewsclient/
---
## IEWSClient interface

表示 Exchange 客户端的接口。

```csharp
public interface IEWSClient : IExchangeClientBase
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CalendarFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/calendarfoldereventfilter) { get; set; } | 指定日历文件夹的事件类型 |
| [ContactsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/contactsfoldereventfilter) { get; set; } | 指定联系人文件夹的事件类型 |
| [CurrentCalendarFolderUri](../../aspose.email.clients.exchange.webservice/iewsclient/currentcalendarfolderuri) { get; set; } | 获取或设置当前日历文件夹 uri |
| [DeletedItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/deleteditemsfoldereventfilter) { get; set; } | 指定 DeletedItems 文件夹的事件类型 |
| [DraftsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/draftsfoldereventfilter) { get; set; } | 指定草稿文件夹的事件类型 |
| [EnableDecompression](../../aspose.email.clients.exchange.webservice/iewsclient/enabledecompression) { get; set; } | 获取或设置一个指示是否启用解压的值 |
| [Headers](../../aspose.email.clients.exchange.webservice/iewsclient/headers) { get; } | 获取名称值对的数组，它们被添加到 EWS 请求中的 WebHeaderCollection。 |
| [InboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/inboxfoldereventfilter) { get; set; } | 指定收件箱文件夹的事件类型 |
| [JournalFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/journalfoldereventfilter) { get; set; } | 指定日记文件夹的事件类型 |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/mailboxinfo) { get; } | 获取邮箱信息。 |
| [NotesFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/notesfoldereventfilter) { get; set; } | 指定 Notes 文件夹的事件类型 |
| [NotificationsCheckInterval](../../aspose.email.clients.exchange.webservice/iewsclient/notificationscheckinterval) { get; set; } | 定义通知检查的间隔 |
| [NotificationTimeout](../../aspose.email.clients.exchange.webservice/iewsclient/notificationtimeout) { get; set; } | 定义服务器通知的超时 |
| [OutboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/outboxfoldereventfilter) { get; set; } | 指定发件箱文件夹的事件类型 |
| [ReconnectCount](../../aspose.email.clients.exchange.webservice/iewsclient/reconnectcount) { get; set; } | 获取或设置连接中断时的重新连接尝试次数。 |
| [ReturnClientRequestId](../../aspose.email.clients.exchange.webservice/iewsclient/returnclientrequestid) { get; set; } | 获取或设置一个标志，表示客户端是否要求服务端返回请求id。 |
| [RootFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/rootfoldereventfilter) { get; set; } | 指定根文件夹的事件类型 |
| [SentItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/sentitemsfoldereventfilter) { get; set; } | 指定 SentItems 文件夹的事件类型 |
| [ServerVersion](../../aspose.email.clients.exchange.webservice/iewsclient/serverversion) { get; } | 获取有关 MS Exchange 的当前版本的信息。 |
| [TasksFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/tasksfoldereventfilter) { get; set; } | 指定任务文件夹的事件类型 |
| [TimezoneId](../../aspose.email.clients.exchange.webservice/iewsclient/timezoneid) { get; set; } | 获取或设置时区 id |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iewsclient/useslashasfolderseparator) { get; set; } | 获取或设置确定斜线“/”是否用作文件夹分隔符的值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddHeader](../../aspose.email.clients.exchange.webservice/iewsclient/addheader)(string, string) | 在 EWS 请求中向 WebHeaderCollection 添加名称和值。 |
| [AddToDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/addtodistributionlist)(ExchangeDistributionList, MailAddressCollection) | 将成员附加到分发列表。 |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage)(MailMessage) | 将邮件信息上传到收件箱文件夹 |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_1)(MapiMessage) | 将邮件信息上传到指定文件夹 |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_2)(MapiMessage, bool) | 将邮件信息上传到指定文件夹 |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_3)(string, MailMessage) | 将邮件信息上传到指定文件夹 |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_5)(string, MapiMessage, bool) | 将邮件信息上传到指定文件夹 |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_1)(IEnumerable&lt;MailMessage&gt;) | 将邮件信息上传到指定文件夹 |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages)(params MailMessage[]) | 将邮件信息上传到指定文件夹 |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_3)(string, IEnumerable&lt;MailMessage&gt;) | 将邮件信息上传到指定文件夹 |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_4)(string, IEnumerable&lt;MapiMessage&gt;) | 将 mapi 消息上传到指定文件夹 |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_2)(string, params MailMessage[]) | 将邮件信息上传到指定文件夹 |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem)(string, Appointment) | ArchiveItem 操作将项目移动到邮箱用户的存档邮箱中。 |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_1)(string, ExchangeTask) | ArchiveItem 操作将项目移动到邮箱用户的存档邮箱中。 |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_2)(string, MapiMessageItemBase) | ArchiveItem 操作将项目移动到邮箱用户的存档邮箱中。 |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_3)(string, string) | ArchiveItem 操作将项目移动到邮箱用户的存档邮箱中。 |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | 备份指定文件夹的内容 |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | 备份指定文件夹的内容 |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment)(Appointment) | 取消约会。 |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_2)(MapiCalendar) | 取消约会。 |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_4)(string) | 取消组织者日历上的退出会议 |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_1)(Appointment, string) | 取消约会。 |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_3)(MapiCalendar, string) | 取消约会。 |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_5)(string, string) | 取消组织者日历上的退出会议 |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability)(string, DateRange) | 在指定的时间范围内检查用户的可用性。 |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability_1)(StringCollection, DateRange) | 在指定的时间范围内检查用户的可用性。 |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_1)(ExchangeDelegateUser, string) | 关闭指定用户对指定邮箱的访问。 |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_2)(ExchangeDelegateUserCollection, string) | 关闭指定用户对指定邮箱的访问。 |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess)(ExchangeFolderUserInfo, string) | 关闭指定用户对指定邮箱的访问。 |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_3)(string, string) | 关闭指定用户对指定邮箱的访问。 |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems)(string, string) | 将对话项复制到指定的目标文件夹 |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems_1)(string, string, string) | 将位于指定文件夹中的对话项复制到指定的目标文件夹 |
| [CopyItem](../../aspose.email.clients.exchange.webservice/iewsclient/copyitem)(string, string) | 将项目复制到指定文件夹 |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment)(Appointment) | 创建约会。 |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_1)(Appointment, string) | 创建约会。 |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_4)(MapiCalendar, string, bool) | 创建约会。 |
| [CreateCalendarSharingInvitationMessage](../../aspose.email.clients.exchange.webservice/iewsclient/createcalendarsharinginvitationmessage)(string) | 创建日历共享邀请消息。 |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_1)(Contact) | 在 Exchange 存储中创建联系人项目。 |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_3)(string, Contact) | 在指定文件夹中创建联系人项目。 |
| [CreateDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/createdistributionlist)(ExchangeDistributionList, MailAddressCollection) | 创建私有分发列表。 |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder)(string) | 在根文件夹中创建新文件夹。 |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_1)(string, ExchangeFolderType) | 在根文件夹中创建新文件夹。 |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_2)(string, string) | 在指定的父文件夹中创建具有指定名称的新文件夹。 |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_3)(string, string, ExchangeFolderPermissionCollection) | 创建新文件夹 |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_5)(string, string, ExchangeFolderType) | 创建新文件夹 |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_4)(string, string, ExchangeFolderPermissionCollection, string) | 创建新文件夹 |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule)(InboxRule) | 创建指定的收件箱规则 |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule_1)(InboxRule, string) | 创建指定的收件箱规则 |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem)(MapiMessageItemBase) | 在默认项目文件夹中创建给定项目。 |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem_1)(string, MapiMessageItemBase) | 在指定文件夹中创建给定项目。 |
| [CreateItems](../../aspose.email.clients.exchange.webservice/iewsclient/createitems)(ExchangeStreamedItem[], string) | 在指定文件夹中创建指定项目 |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder)(string, ExchangeFolderPermissionCollection) | 在根公用文件夹中创建指定的公用文件夹 |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_1)(string, ExchangeFolderPermissionCollection, ExchangeFolderType) | 在根公用文件夹中创建指定的公用文件夹 |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_2)(string, string, ExchangeFolderPermissionCollection) | 在根公用文件夹中创建指定的公用文件夹 |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask)(ExchangeTask) | 在默认任务文件夹中创建给定任务。 |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask_2)(string, ExchangeTask) | 在指定文件夹中创建给定任务。 |
| [CreateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/createuserconfiguration)(UserConfiguration) | 创建指定的用户配置 |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess)(ExchangeDelegateUser, string) | 将指定邮箱的访问权限委托给指定用户。 |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_1)(ExchangeDelegateUserCollection, string) | 将邮箱的访问权限委托给指定的用户。 |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_2)(string, ExchangeDelegateFolderPermissionLevel, string) | 将主体邮箱的访问权限委托给指定用户。 |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems)(string) | 删除指定对话的所有项目 |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems_1)(string, string) | 删除指定文件夹中的对话项目 |
| [DeleteDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletedistributionlist)(ExchangeDistributionList, bool) | 删除分发列表。 |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder)(string) | 删除文件夹 |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder_1)(string, bool) | 删除文件夹 |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders)(ExchangeFolderInfoCollection) | 删除指定文件夹 |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_2)(StringCollection) | 删除指定文件夹 |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_1)(ExchangeFolderInfoCollection, bool) | 删除指定文件夹 |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_3)(StringCollection, bool) | 删除文件夹 |
| [DeleteFromDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletefromdistributionlist)(ExchangeDistributionList, MailAddressCollection) | 从分发列表中删除成员。 |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule)(string) | 删除指定的收件箱规则 |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule_1)(string, string) | 删除指定的收件箱规则 |
| [DeleteItem](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitem)(string, DeletionOptions) | 删除指定项目 |
| [DeleteItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitems)(IEnumerable&lt;string&gt;, DeletionOptions) | 删除指定项目 |
| [DeleteUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/deleteuserconfiguration)(UserConfigurationName) | 删除指定的用户配置 |
| [DisconnectPhoneCall](../../aspose.email.clients.exchange.webservice/iewsclient/disconnectphonecall)(string) | 断开 id 指定的电话呼叫。 |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder)(string) | 清空指定文件夹。子文件夹不会被删除；已删除的项目将被移动到 DeletedItems 文件夹 |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder_1)(string, EmptyFolderOptions) | 清空指定文件夹 |
| [ExpandDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/expanddistributionlist)(MailAddress) | 扩展公共分发列表成员。 |
| [ExportItems](../../aspose.email.clients.exchange.webservice/iewsclient/exportitems)(params string[]) | 从邮箱中导出指定的项目 |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment)(string) | 从服务器获取指定的约会。 |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment_1)(string, string) | 从服务器获取指定的约会。 |
| [FetchAttachment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchattachment)(string) | 获取附件 |
| [FetchConversationMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchconversationmessages)(string) | 获取指定的对话消息 |
| [FetchDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/fetchdistributionlist)(ExchangeDistributionList) | 获取私有分发列表成员。 |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem)(string) | 检索项目为[`MapiMessage`](../../aspose.email.mapi/mapimessage). |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | 检索项目为[`MapiMessage`](../../aspose.email.mapi/mapimessage). |
| [FetchItems](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitems)(EwsFetchItems) | 检索项目。 |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar)(IEnumerable&lt;string&gt;) | 获取数组[`MapiCalendar`](../../aspose.email.mapi/mapicalendar)对象. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | 获取数组[`MapiCalendar`](../../aspose.email.mapi/mapicalendar)对象. |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages)(IEnumerable&lt;string&gt;) | 获取指定的消息 |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | 获取指定的消息 |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes)(IEnumerable&lt;string&gt;) | 获取数组[`MapiNote`](../../aspose.email.mapi/mapinote)对象. |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | 获取数组[`MapiNote`](../../aspose.email.mapi/mapinote)对象. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks)(IEnumerable&lt;string&gt;) | 获取数组[`MapiTask`](../../aspose.email.mapi/mapitask)对象. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | 获取数组[`MapiTask`](../../aspose.email.mapi/mapitask)对象. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage)(string) | 获取消息。 |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | 从服务器获取消息 |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages)(IEnumerable&lt;ExchangeMessageInfo&gt;) | 获取指定的消息 |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_1)(IEnumerable&lt;string&gt;) | 获取指定的消息 |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_3)(StringCollection) | 获取指定的消息 |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_2)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | 获取指定的消息 |
| [FetchTask](../../aspose.email.clients.exchange.webservice/iewsclient/fetchtask)(string) | 获取指定的任务。 |
| [FindConversations](../../aspose.email.clients.exchange.webservice/iewsclient/findconversations)(string) | 在指定文件夹中查找对话 |
| [FindMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/findmessagetrackingreport)(FindMessageTrackingReportOptions) | 查找符合指定条件的消息。 |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople_1)(string, int) | 在服务器上的全局地址列表 (GAL) 中查找联系人。 |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople)(string, MailQuery, int) | 查找位于服务器上指定用户个人邮箱中的联系人。 |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists)(string, string) | 检查指定文件夹是否存在。 |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | 检查指定文件夹是否存在。 |
| [Forward](../../aspose.email.clients.exchange.webservice/iewsclient/forward)(MailMessage, ExchangeMessageInfo) | 转发消息。 |
| [GetCallInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getcallinfo)(string) | 通过呼叫 id 检索电话信息 |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact)(ObjectIdentifier) | 根据指定的标识符检索联系信息。 |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_2)(string) | 根据指定的标识符检索联系信息。 |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_1)(ObjectIdentifier, ExchangeListContactsOptions) | 根据指定的标识符检索联系信息。 |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_3)(string, ExchangeListContactsOptions) | 根据指定的标识符检索联系信息。 |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts)(string) | 列出服务器上指定文件夹中的联系人 |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts_1)(string, ExchangeListContactsOptions) | 列出服务器上指定文件夹中的联系人 |
| [GetExchangeType](../../aspose.email.clients.exchange.webservice/iewsclient/getexchangetype)() | 获取有关 MS Exchange 的当前版本的信息。 |
| [GetFolderInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderinfo)(string) | 获取文件夹信息 |
| [GetFolderPermissions](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderpermissions)(string) | 获取文件夹权限。 |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules)() | 获取收件箱规则 |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules_1)(string) | 获取收件箱规则 |
| [GetMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxes)() | 列出具有 smtp 地址的邮箱。 注意：返回的联系人的最大计数为 100。这是使用 EWS 操作的限制。 |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo)() | 获取邮箱信息。 |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo_1)(string) | 获取邮箱信息 |
| [GetMailboxSize](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsize)() | 获取邮箱的大小。 请注意，此操作对所有子文件夹递归执行，需要一些时间 |
| [GetMailboxSizeEx](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsizeex)(string) | 获取邮箱的大小 请注意，此操作对所有子文件夹递归执行，需要一些时间 |
| [GetMailTips](../../aspose.email.clients.exchange.webservice/iewsclient/getmailtips)(GetMailTipsOptions) | 获取邮件提示 |
| [GetMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/getmessagetrackingreport)(GetMessageTrackingReportOptions) | 获取邮件跟踪报告 |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids)() | GetServerTimeZoneIds 从 Exchange 服务器上可用的时区 ID 返回信息。 |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_1)(IEnumerable&lt;string&gt;) | GetServerTimeZoneIds 从 Exchange 服务器上可用的时区 ID 返回信息。 |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_2)(params string[]) | GetServerTimeZoneIds 从 Exchange 服务器上可用的时区 ID 返回信息。 |
| [GetUMConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getumconfiguration)() | 检索统一消息配置 |
| [GetUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getuserconfiguration)(UserConfigurationName) | 获取指定的用户配置 |
| [GetVersionInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getversioninfo)() | 返回交换服务器版本信息 |
| [ImpersonateUser](../../aspose.email.clients.exchange.webservice/iewsclient/impersonateuser)(ItemChoice, string) | 冒充用户。 |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments)() | 检索默认日历文件夹的约会列表 |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_3)(bool) | 检索默认日历文件夹的约会列表 |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_1)(MailQuery) | 检索默认日历文件夹的约会列表 |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_4)(string) | 检索指定日历文件夹的约会列表 |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_2)(MailQuery, bool) | 检索默认日历文件夹的约会列表 |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_7)(string, bool) | 检索指定日历文件夹的约会列表 |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_5)(string, MailQuery) | 检索指定日历文件夹的约会列表 |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_6)(string, MailQuery, bool) | 检索指定日历文件夹的约会列表 |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_2)(int) | 检索日历文件夹的约会页面 |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_3)(int, int) | 检索日历文件夹的约会页面 |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage)(MailQuery, int) | 检索日历文件夹的约会页面 |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_6)(string, int) | 检索指定日历文件夹的约会页面 |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_1)(MailQuery, int, int) | 检索日历文件夹的约会页面 |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_7)(string, int, int) | 检索指定日历文件夹的约会页面 |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_4)(string, MailQuery, int) | 检索指定日历文件夹的约会页面 |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_5)(string, MailQuery, int, int) | 检索指定日历文件夹的约会页面 |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts)(string) | 列出服务器上指定文件夹中的联系人 |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | 列出服务器上指定文件夹中的联系人 |
| [ListDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/listdelegates)(string) | 列出被授予访问指定邮箱的用户。 |
| [ListDistributionLists](../../aspose.email.clients.exchange.webservice/iewsclient/listdistributionlists)() | 列出私有分发列表。 |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems)(string) | 检索指定文件夹中的项目 uris 列表 |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_1)(string, MailQuery) | 检索指定文件夹中的项目 uris 列表 |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_3)(string, string) | 检索指定文件夹中的项目 uris 列表 |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_2)(string, MailQuery, bool) | 检索指定文件夹中的项目 uris 列表 |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_4)(string, string, MailQuery) | 检索指定文件夹中的项目 uris 列表 |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_5)(string, string, MailQuery, bool) | 检索指定文件夹中的项目 uris 列表 |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes)() | 列出邮箱。 |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes_1)(string) | 请注意，此覆盖方法适用于 Exchange Server 2013 及更高版本。 列出邮箱。 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages)() | 列出收件箱文件夹中的邮件。 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_1)(IEnumerable&lt;string&gt;) | 列出指定文件夹中的邮件。 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_2)(string) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_7)(string, bool) | 列出指定文件夹中的邮件 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_3)(string, ExchangeListMessagesOptions) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_8)(string, int) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_5)(string, MailQuery) | 列出指定文件夹中的邮件。 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_4)(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) | 列出指定文件夹中的邮件 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_9)(string, int, ExchangeListMessagesOptions) | 列出消息。 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_10)(string, int, MailQuery) | 列出指定文件夹中的邮件。 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_6)(string, MailQuery, bool) | 列出指定文件夹中的邮件。 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_13)(string, string, bool) | 列出指定文件夹中的邮件 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_12)(string, string, MailQuery) | 列出指定文件夹中的邮件。 |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_11)(string, int, MailQuery, bool) | 列出指定文件夹中的邮件。 |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_4)(string, int) | 列出指定文件夹中的邮件。 |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage)(string, PageInfo) | 列出指定文件夹中的邮件。 |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_5)(string, int, int) | 列出指定文件夹中的邮件。 |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_2)(string, MailQuery, int) | 列出指定文件夹中的邮件。 |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_1)(string, PageInfo, ExchangeListMessagesOptions) | 列出指定文件夹中的邮件。 |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_6)(string, int, int, ExchangeListMessagesOptions) | 列出指定文件夹中的邮件。 |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_3)(string, MailQuery, int, int) | 列出指定文件夹中的邮件。 |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder)(ExchangeFolderInfo) | 从公共文件夹中获取消息集合 |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder_1)(string) | 从公共文件夹中获取消息集合 |
| [ListPublicFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listpublicfolders)() | 从根公用文件夹获取公用文件夹集合 |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | 从 parent 获取子公用文件夹的集合 |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_1)(string) | 从 parent 获取子文件夹的集合 |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_2)(string, string) | 从 parent 获取子文件夹的集合 |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_1)(string, int) | 使用 paging 方法在给定父文件夹中搜索指定文件夹，支持分页。 在分页周期中第一次调用。 |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage)(string, PageInfo) | 使用分页搜索给定父文件夹中的指定文件夹 方法支持分页。 |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_2)(string, int, int) | 使用分页搜索给定父文件夹中的指定文件夹 方法支持分页。 |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks)() | 检索默认文件夹的交换任务列表。 |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_1)(string) | 检索交换任务列表。 |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_3)(string, int) | 检索交换任务列表。 |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_2)(string, MailQuery) | 检索交换任务列表。 |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_4)(string, int, MailQuery) | 检索交换任务列表。 |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_5)(string, int, MailQuery, bool) | 检索交换任务列表。 |
| [LoadContactPhoto](../../aspose.email.clients.exchange.webservice/iewsclient/loadcontactphoto)(ContactPhoto) | 加载联系人照片二进制数据 |
| [MailDisablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/maildisablepublicfolder)(string) | 邮件禁用公用文件夹 |
| [MailEnablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/mailenablepublicfolder)(string) | 为公用文件夹启用邮件 |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_2)(bool, params string[]) | 标记指定文件夹中的所有项目。 |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems)(bool, bool, IEnumerable&lt;string&gt;) | 标记指定文件夹中的所有项目。 |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_1)(bool, bool, params string[]) | 标记指定文件夹中的所有项目。 |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread)() | 将收件箱文件夹中的所有项目标记为已读且没有回执。 |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_1)(IEnumerable&lt;string&gt;) | 将指定文件夹中的所有项目标记为已读且没有回执。 |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_2)(params string[]) | 将指定文件夹中的所有项目标记为已读且没有回执。 |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread)() | 将收件箱文件夹中的所有项目标记为未读。 |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_1)(IEnumerable&lt;string&gt;) | 将指定文件夹中的所有项目标记为未读。 |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_2)(params string[]) | 将指定文件夹中的所有项目标记为未读。 |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_2)(bool, IEnumerable&lt;string&gt;) | MarkAsJunk 方法将邮件移动到垃圾邮件文件夹并阻止邮件发件人。 |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_3)(bool, params string[]) | MarkAsJunk 方法将邮件移动到垃圾邮件文件夹并阻止邮件发件人。 |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk)(bool, bool, IEnumerable&lt;string&gt;) | MarkAsJunk 方法将邮件移动到垃圾邮件文件夹并阻止邮件发件人。 |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_1)(bool, bool, params string[]) | MarkAsJunk 方法将邮件移动到垃圾邮件文件夹并阻止邮件发件人。 |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_4)(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) | MarkAsJunk 方法将邮件移动到垃圾邮件文件夹并阻止邮件发件人。 |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems)(string, string) | 将对话项目移动到指定的目标文件夹 |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems_1)(string, string, string) | 将位于指定文件夹中的对话项移动到指定的目标文件夹 |
| [MoveItem](../../aspose.email.clients.exchange.webservice/iewsclient/moveitem)(string, string) | 将项目移动到指定文件夹 |
| [PlayOnPhone](../../aspose.email.clients.exchange.webservice/iewsclient/playonphone)(string, string) | PlayOnPhone 操作发起一个外呼并通过电话播放一条消息。 |
| [RemoveHeader](../../aspose.email.clients.exchange.webservice/iewsclient/removeheader)(string) | 从 EWS 请求中的 WebHeaderCollection 中删除 WebHeader。 |
| [Reply](../../aspose.email.clients.exchange.webservice/iewsclient/reply)(MailMessage, ExchangeMessageInfo) | 回复发件人的消息。 |
| [ReplyAll](../../aspose.email.clients.exchange.webservice/iewsclient/replyall)(MailMessage, ExchangeMessageInfo) | 回复邮件的发件人和所有收件人。 |
| [ResetImpersonation](../../aspose.email.clients.exchange.webservice/iewsclient/resetimpersonation)() | 使模拟重置。 |
| [ResetSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/resetsubscription)() | 重置所有订阅 |
| [ResolveContact](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontact)(string) | 解决不明确的邮箱名称。 |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts)(string) | 解决不明确的邮箱显示名称。 注意：返回的联系人的最大计数为 100。这是使用交换命令的限制。 |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts_1)(string, ExchangeListContactsOptions) | 解决不明确的电子邮件地址和显示名称 注意：返回的联系人的最大计数为 100。这是使用 EWS 操作的限制。 |
| [Restore](../../aspose.email.clients.exchange.webservice/iewsclient/restore)(PersonalStorage, RestoreSettings) | 从给定的个人存储中恢复指定的交换文件夹。 |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage)(string, Stream) | 保存消息。 |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage_1)(string, string) | 保存消息。 |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send)(MailMessage) | 发送指定的消息。 |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_1)(MailMessage, FollowUpOptions) | 发送消息。 |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_2)(string, string, string, string) | 发送指定的消息 |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate)(string, bool) | 将会话项的读取状态设置为指定值 |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate_1)(string, string, bool) | 将位于指定文件夹中的对话项的读取状态设置为指定值 |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag)(string) | 设置读取标志。 |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag_1)(string, bool) | 将特定消息标记为已读。 |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_1)(string) | 检索指定文件夹中项目和子文件夹的更改。 |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder)(SyncState) | 检索指定文件夹中项目的更改。 |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_3)(string, string) | 检索指定文件夹中项目的更改。 |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_2)(string, SyncFolderType) | 检索指定文件夹中项目和子文件夹的更改。 |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_4)(string, string, IEnumerable&lt;string&gt;) | 检索指定文件夹中项目的更改。 |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment)(Appointment) | 更新约会。 |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_2)(MapiCalendar) | 更新约会。 |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_1)(Appointment, string) | 更新约会。 |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_3)(MapiCalendar, string) | 更新约会。 |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact_1)(Contact) | 更新 Exchange 存储中的联系人项目。 |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact)(MapiContact) | 更新 Exchange 存储中的联系人项目。 |
| [UpdateDelegate](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegate)(ExchangeDelegateUser, string) | 更新被授予访问指定邮箱的代理用户设置。 |
| [UpdateDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegates)(ExchangeDelegateUserCollection, string) | 更新被授予访问指定邮箱的代理用户设置。 |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule)(InboxRule) | 更新指定的收件箱规则 |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule_1)(InboxRule, string) | 更新指定的收件箱规则 |
| [UpdateItems](../../aspose.email.clients.exchange.webservice/iewsclient/updateitems)(ExchangeStreamedItem[], string) | 将指定项目更新到邮箱 |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote)(MapiNote) | 更新指定的注释。 |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_1)(string, MapiNote) | 更新指定的注释。 |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_2)(string, MapiNote, IEnumerable&lt;PropertyDescriptor&gt;) | 更新指定的注释。 |
| [UpdateSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/updatesubscription)() | 更新订阅 |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_3)(ExchangeTask) | 更新指定的任务。 |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask)(MapiTask) | 更新指定的任务。 |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_4)(ExchangeTask, UpdateTaskOptions) | 更新指定的任务。 |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_1)(string, MapiTask) | 更新指定的任务。 |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_2)(string, MapiTask, IEnumerable&lt;PropertyDescriptor&gt;) | 更新指定的任务。 |
| [UpdateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/updateuserconfiguration)(UserConfiguration) | 更新指定的用户配置 |

### 也可以看看

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
