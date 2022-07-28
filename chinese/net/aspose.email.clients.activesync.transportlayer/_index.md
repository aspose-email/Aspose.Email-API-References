---
title: Aspose.Email.Clients.ActiveSync.TransportLayer
second_title: Aspose.Email for .NET API 参考
description: 
type: docs
weight: 80
url: /zh/net/aspose.email.clients.activesync.transportlayer/
---


## 课程

| 班级 | 描述 |
| --- | --- |
| [AccountInformation](./accountinformation) | 包含用户的帐户信息。 |
| [ActiveSyncTLClient](./activesynctlclient) | ActiveSync 客户端实现的基本类 |
| [AutodiscoverResult](./autodiscoverresult) | 自动发现操作的结果 |
| [Body](./body) | 指定与服务器上存储的项目关联的自由格式、可变长度的数据字段。 |
| [BodyPart](./bodypart) | 指定有关回复中电子邮件消息部分的详细信息。 当在请求中指定 BodyPartPreference 时，必须在命令响应中包含 BodyPart 元素。 |
| [BodyPreference](./bodypreference) | 包含与从搜索、同步或获取返回的信息的类型和大小相关的首选项信息。 |
| [CertificateStatuses](./certificatestatuses) | 表示证书是否已成功验证。 |
| [DataContainer](./datacontainer) | 包含特定对象的数据，例如联系人、电子邮件、日历约会或任务项。 DataContainer 可用于在客户端设备或服务器上更改项目、添加项目或获取项目。 |
| [DeviceInformation](./deviceinformation) | 用于将客户端设备的属性发送到服务器的请求。 |
| [DevicePasswordRequest](./devicepasswordrequest) | 指定服务器设置客户端设备恢复密码的请求。 要清除现有的恢复密码，客户端必须发送一个空密码。 |
| [EASProvisionDoc](./easprovisiondoc) | 指定设备配置的安全设置集合。 |
| [EmptyFolderContentsRequest](./emptyfoldercontentsrequest) | 包含有关删除文件夹内容的请求。 EmptyFolderContents 支持 Options 元素的单个子元素 DeleteSubFolders，它决定是否删除文件夹中包含的子文件夹。 如果请求中不包含 DeleteSubFolders 选项，则不删除指定 CollectionId 的子文件夹。 |
| [FolderInfo](./folderinfo) | FolderInfo 类包含文件夹信息 |
| [FolderSyncResult](./foldersyncresult) | 包含对文件夹层次结构的更改。 |
| [ItemEstimate](./itemestimate) | 包含对请求文件夹的评估 |
| [ItemEstimateOptions](./itemestimateoptions) | 包含过滤 GetItemEstimate 操作结果的元素。 |
| [ItemEstimateRequest](./itemestimaterequest) | 包含 ItemEstimate 请求参数 |
| [ItemOperationsEmptFldrCntntsResponce](./itemoperationsemptfldrcntntsresponce) | 将响应的主体标识为包含删除文件夹内容的操作。 |
| [ItemOperationsFetchProperties](./itemoperationsfetchproperties) | 包含为响应中的项目返回的属性。 |
| [ItemOperationsFetchRequest](./itemoperationsfetchrequest) | 包含有关从服务器检索项目的请求。 |
| [ItemOperationsFetchResponce](./itemoperationsfetchresponce) | 包含有关从服务器检索项目的响应。 |
| [ItemOperationsMoveRequest](./itemoperationsmoverequest) | 包含有关将对话移动到特定文件夹的请求。 |
| [ItemOperationsMoveResponce](./itemoperationsmoveresponce) | 将响应的主体标识为包含移动给定对话的操作。 |
| [ItemOperationsRequest](./itemoperationsrequest) | 包含 ItemOperations 请求。 |
| [ItemOperationsResponse](./itemoperationsresponse) | 包含 ItemOperations 响应。 |
| [ItOpEmpFldCntOptions](./itopempfldcntoptions) | 包含 ItemOperations.EmptyFolderContents 操作的选项 |
| [ItOpFetchOptions](./itopfetchoptions) | 包含 ItemOperations.Fetch 操作的选项。 |
| [ItOpMoveOptions](./itopmoveoptions) | 包含 ItemOperations.Move 操作的选项。 |
| [MeetingResponseRequest](./meetingresponserequest) | 指定正在响应的会议请求、对该会议请求的响应以及会议请求所在的服务器上的文件夹。 |
| [MeetingResponseResult](./meetingresponseresult) | 会议响应结果对象 |
| [MoveItemData](./moveitemdata) | 包含有关移动项目的信息 |
| [MoveItemResponse](./moveitemresponse) | 包含描述移动项目的信息。 |
| [OOFMessage](./oofmessage) | 为特定受众指定 OOF 消息。 Exchange 2007、Exchange 2010 和 Exchange 2013 要求未知外部受众和已知外部受众的回复消息相同。 该属性支持 OOF 消息的以下三种受众： 内部 - 与发送用户在同一组织中的用户。 已知外部 - 在发送用户的组织之外但在发送用户的联系人中表示的用户。 未知外部 - 在发送用户的组织之外的用户组织并且不在发送用户的联系人中表示。 |
| [OOFReqParametrs](./oofreqparametrs) | 从服务器获取 OOF 信息设置。 |
| [OOFRequest](./oofrequest) | 指定用于检索和设置外出 (OOF) 信息的类。 |
| [OOFResponse](./oofresponse) | 指定用于检索和设置外出 (OOF) 信息的类。 |
| [OOFSettings](./oofsettings) | OOF信息设置。 |
| [PictureRequest](./picturerequest) | 表示客户端请求在服务器响应中返回照片。 协议版本为12.1或14.0时不支持图片。 包含与照片请求相关的数据。 |
| [PictureRespose](./picturerespose) | 包含与联系人照片相关的数据。 协议版本为 12.1 或 14.0 时不支持图片。 |
| [PingParameter](./pingparameter) | 包含 ping 命令参数 |
| [ProvisionPolicy](./provisionpolicy) | 指定安全策略。 |
| [ProvisionPolicyData](./provisionpolicydata) | 指定策略的设置。 |
| [ProvisionRequest](./provisionrequest) | 包含提供命令的请求信息 |
| [ProvisionResponse](./provisionresponse) | 包含提供命令的响应信息 |
| [QueryType](./querytype) | 指定用于匹配正在搜索的商店中的条目的关键字。 查询的值用作前缀字符串匹配模式，并返回匹配字符串开头的条目。 例如，搜索“John”将匹配“John Frum”或“Barry Johnson”，但不会匹配“James Littlejohn”。 GAL 中使用 ANR 索引的所有非空文本属性都与 Query 元素进行比较价值。 使用不区分大小写的匹配来执行搜索比较。 对于 Windows SharePoint Services 文档库搜索，此协议支持以下形式的查询： LinkId == value，其中 value 指定项目或文件夹的 URL，LinkId 表示该值将与链接 ID 属性进行比较。 对于邮箱搜索，查询语法如下： - 可以通过以下方式指定文件夹： 指定 ID 指定文件夹和子文件夹 所有电子邮件文件夹，包括草稿，收件箱和子文件夹、发件箱和已发送邮件 - 基本关键字查询可由以下内容组成： 基本运算符：And（第 2.2.3.10 节） 使用 GreaterThan（第 2.2.3.78 节）和 LessThan 指定的日期时间过滤器包含关键字的元素（第 2.2.3.87 节） 自由文本元素（第 2.2.3.73 节） 对所有索引属性执行基本关键字查询。 |
| [Recipient](./recipient) | 表示已解析的单个收件人。 |
| [ResolveRecipientsAvailabilityRequest](./resolverecipientsavailabilityrequest) | 向服务器指示客户端正在请求空闲/忙碌数据，并标识要检索的空闲/忙碌数据的开始时间和结束时间。 协议版本为 12.1 时不支持可用性。 |
| [ResolveRecipientsAvailabilityResponse](./resolverecipientsavailabilityresponse) | 标识请求中标识的用户或分发列表在 StartTime 和 EndTime 标识的时间的状态和忙/闲数据。 当可用性包含在 ResolveRecipients 请求中时，服务器检索标识的用户的忙/闲信息在请求中包含的 To 元素中，并在响应中的 MergedFreeBusy 中返回忙/闲信息。 服务器解析请求时，首先解析To元素标识的接收者，然后判断指定时间段内的用户忙/闲信息，然后在MergedFreeBusy中返回忙/闲数据。 |
| [ResolveRecipientsCertificates](./resolverecipientscertificates) | 包含有关收件人证书的信息。 |
| [ResolveRecipientsOptions](./resolverecipientsoptions) | 包含用于解析收件人列表的选项。 |
| [ResolveRecipientsRequest](./resolverecipientsrequest) | 包含解析收件人的信息。 |
| [ResolveRecipientsResponse](./resolverecipientsresponse) | 包含有关收件人是否已解析的信息。 如果收件人已解析，它还包含收件人类型、收件人解析到的电子邮件地址，以及收件人的 S/MIME 证书（可选）。 |
| [RightsManagementInformationResponce](./rightsmanagementinformationresponce) | 包含从服务器检索的权限管理信息设置。 |
| [RightsManagementLicense](./rightsmanagementlicense) | 包含应用于正在同步的电子邮件的模板的权限策略模板设置。 |
| [RightsManagementTemplate](./rightsmanagementtemplate) | 包含客户端上可用的权限策略模板的模板标识符、名称和描述。 |
| [SearchCondition](./searchcondition) | 指定搜索请求的条件 |
| [SearchOptions](./searchoptions) | 包含搜索选项。 只有在收到状态值为 14 后，才能在请求中发送用户名和密码。 服务器需要这些凭据才能访问请求的资源。 客户端必须仅通过安全或受信任的连接发送这些，并且仅响应状态值 14。 支持的选项因正在搜索的商店而异。 下表列出了每个商店的有效选项。 GAL：范围、用户名、密码、图片 邮箱：范围、DeepTraversal、RebuildResults、BodyPreference、BodyPartPreference、RightsManagementSupport DocumentLibrary：范围、用户名、密码 BodyPartPreference 仅在搜索中有效包含 ConversationId. 的命令请求 |
| [SearchQuery](./searchquery) | 指定用于匹配正在搜索的商店中的条目的关键字。 查询的值用作前缀字符串匹配模式，并返回匹配字符串开头的条目。 例如，搜索“John”将匹配“John Frum”或“Barry Johnson”，但不会匹配“James Littlejohn”。 GAL 中使用 ANR 索引的所有非空文本属性都与 Query 元素进行比较价值。 使用不区分大小写的匹配来执行搜索比较。 对于 Windows SharePoint Services 文档库搜索，此协议支持以下形式的查询：LinkId == value， 其中 value 指定项目或文件夹的 URL，LinkId 表示该值将与链接 ID 属性进行比较。 对于邮箱搜索，查询语法如下： - 可以通过以下方式指定文件夹： 指定 ID 指定文件夹和子文件夹 所有电子邮件文件夹，包括草稿，收件箱和子文件夹、发件箱和已发送邮件 - 基本关键字查询可由以下内容组成： 基本运算符：And（第 2.2.3.10 节） 使用 GreaterThan（第 2.2.3.78 节）和 LessThan 指定的日期时间过滤器包含关键字的元素（第 2.2.3.87 节） 自由文本元素（第 2.2.3.73 节） 对所有索引属性执行基本关键字查询。 |
| [SearchRequest](./searchrequest) | 包含搜索请求信息 |
| [SearchRequestStore](./searchrequeststore) | 指定搜索的名称、查询和选项。 |
| [SearchResponse](./searchresponse) | 包含搜索响应信息 |
| [SearchResponseStore](./searchresponsestore) | 包含返回邮箱条目的状态、结果、范围和总计元素。 |
| [SearchResult](./searchresult) | 单个匹配邮箱项目的容器。 当正在搜索的商店是邮箱时： - 邮箱中找到的每个匹配项都有一个 Result 元素。 如果未找到匹配项，则响应 XML 的 Store 容器元素中存在一个空的 Result 元素。 - 在 Result 元素中，Properties 元素包含邮箱项目的请求属性列表。 当存储正在搜索的是文档库： - 搜索响应中返回的第一个结果是 LinkId 值指向的根文件夹或项目的元数据。 如果不需要，客户端可以选择忽略此条目。 - 如果请求中的 documentlibrary:LinkId 元素值指向一个文件夹，则该文件夹的元数据属性作为第一项返回，其内容为该文件夹作为后续结果返回。 Range 适用于这些结果，没有区别；例如，索引 0 将始终用于链接指向的根项目。 - 如果请求中的 documentlibrary:LinkId 元素值指向一个项目，则只返回一个结果：该项目的元数据。 - 在 Result 元素中，Properties 元素包含邮箱项目的请求属性列表。 |
| [SearchResultProperties](./searchresultproperties) | 搜索命令响应属性是属性的容器，适用于与查询元素搜索字符串匹配的单个条目。 例如，Properties 元素包含每个附加到匹配 GAL 条目的非空文本值 GAL 属性的元素。 仅返回那些附加到特定 GAL 条目的属性；因此，对于不同的匹配 GAL 条目，可以在响应 XML 中返回不同的属性集。 属性容器中的每个元素的范围都限定在顶级搜索元素中指定的适当命名空间。 |
| [ServerInfo](./serverinfo) | 自动发现操作中的服务器设置 |
| [SettingsRequest](./settingsrequest) | 设置命令支持对全局属性和用户外出 (OOF) 设置的获取和设置操作。 Settings 命令还将设备信息发送到服务器，实现设备密码/个人识别码 (PIN) 恢复，并检索用户的电子邮件地址列表。 |
| [SettingsResponse](./settingsresponse) | 指定带有外出 (OOF) 设置和用户帐户列表的响应。 |
| [SmartRequest](./smartrequest) | 包含智能请求信息 |
| [SmartRequestSource](./smartrequestsource) | 包含有关源消息的信息。 |
| [Status](./status) | 表示操作的结果。 |
| [SyncAddClientOperation](./syncaddclientoperation) | 在客户端的集合中创建一个新对象。 |
| [SyncAddResponse](./syncaddresponse) | 表示必须在集合中创建一个新对象。 |
| [SyncAddServerOperation](./syncaddserveroperation) | 在服务器上的集合中创建一个新对象。 |
| [SyncChangeClientOperation](./syncchangeclientoperation) | 包含客户端设备上已修改的现有对象的属性。 更改的对象由其 ServerId 元素标识。 |
| [SyncChangeResponse](./syncchangeresponse) | 表示对象已被修改。 |
| [SyncChangeServerOperation](./syncchangeserveroperation) | 包含服务器上已修改的现有对象的属性。 更改的对象由其 ServerId 元素标识。 |
| [SyncCollectionRequest](./synccollectionrequest) | 类包含适用于特定集合的命令和选项。 |
| [SyncCollectionResponse](./synccollectionresponse) | 类包含适用于同步响应的命令和选项。 |
| [SyncCommandsRequest](./synccommandsrequest) | 包含适用于集合的操作。可用的操作包括添加、删除、更改、获取和 SoftDelete。 |
| [SyncCommandsResponse](./synccommandsresponse) | 包含适用于集合的操作。可用的操作包括添加、删除、更改、获取和 SoftDelete。 |
| [SyncDeleteClientOperation](./syncdeleteclientoperation) | 删除客户端设备或服务器上的对象。该对象由其 ServerId. 标识 |
| [SyncFetchResponse](./syncfetchresponse) | 请求在来自服务器的同步响应中被截断的项目的应用程序数据。 |
| [SyncOperationResponse](./syncoperationresponse) | 同步操作响应的基本抽象类 |
| [SyncOperationsResponse](./syncoperationsresponse) | 包含对服务器处理的 Add、Fetch、Change 等操作的响应。 响应包含状态代码和其他信息，具体取决于操作。 |
| [SyncOptions](./syncoptions) | 指定控制同步执行方式的某些方面的选项。 |
| [SyncRequest](./syncrequest) | 包含同步请求参数 |
| [UserInformationResponse](./userinformationresponse) | 包含请求状态和用户帐户信息（电子邮件地址）列表。 |
| [ValueConverter](./valueconverter) | 类将 ActiveSync 协议版本从字符串表示形式转换为枚举并返回。 |
## 接口

| 界面 | 描述 |
| --- | --- |
| [IActiveSyncTLClient](./iactivesynctlclient) | ActiveSync 客户端接口 |
| [IBaseActiveSyncTLClient](./ibaseactivesynctlclient) | 基本 ActiveSync 客户端接口 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [ActiveSyncAuthenticationType](./activesyncauthenticationtype) | 枚举指定身份验证类型 |
| [AirSync](./airsync) | ActiveSync 协议的 AirSync 命名空间 |
| [AirSyncBase](./airsyncbase) | ActiveSync 协议的 AirSyncBase 命名空间 |
| [AirsyncClass](./airsyncclass) | 标识项目的类。 当协议版本为 12.1 时，邮箱搜索支持以下类： - Email - Calendar - Contacts - Tasks SMS 和 Notes 类仅在协议版本为 14.0 或 14.1 时可用。 |
| [AirsyncFilterType](./airsyncfiltertype) | 指定对象 的可选时间窗口 |
| [AllowBluetooth](./allowbluetooth) | 指定设备上蓝牙的使用。 |
| [ASProtocolVersions](./asprotocolversions) | ASProtocolVersions 表示 ActiveSync 协议的版本。 |
| [BehaviorReplacement](./behaviorreplacement) | 指定如何解决在客户端和服务器上都更改对象时发生的冲突。 该值指定在发生冲突时保留哪个对象（客户端对象或服务器对象）。 |
| [BodyType](./bodytype) | 指定项目正文内容的格式类型。 |
| [Calendar](./calendar) | ActiveSync 协议的日历命名空间 |
| [CertificateRetrieval](./certificateretrieval) | 指定服务器是否应为每个已解析的收件人返回 S/MIME 证书。 |
| [CommandCodes](./commandcodes) | 下表提供了对应于 ActiveSync 命令的数字代码。 base64 编码 URI 的命令代码字段中使用数字代码来指定命令。 |
| [CommandParameters](./commandparameters) | 命令参数. |
| [ComposeMail](./composemail) | ActiveSync 协议的 ComposeMail 命名空间 |
| [Contacts](./contacts) | ActiveSync 协议的联系人命名空间 |
| [Contacts2](./contacts2) | ActiveSync 协议的 Contacts2 命名空间 |
| [DocumentLibrary](./documentlibrary) | ActiveSync 协议的 DocumentLibrary 命名空间 |
| [Email](./email) | ActiveSync 协议的电子邮件命名空间 |
| [Email2](./email2) | ActiveSync 协议的 Email2 命名空间 |
| [EncryptionSMIMEAlgorithm](./encryptionsmimealgorithm) | 指定加密 S/MIME 消息时使用的算法。 |
| [FolderClass](./folderclass) | 指定要监控的文件夹的内容类别。 |
| [FolderHierarchy](./folderhierarchy) | ActiveSync 协议的 FolderHierarchy 命名空间 |
| [FolderTypes](./foldertypes) | 指定在服务器上更新（重命名或移动）或添加的文件夹的类型。 |
| [GAL](./gal) | ActiveSync 协议的 GAL 命名空间 |
| [GetItemEstimate](./getitemestimate) | ActiveSync 协议的 GetItemEstimate 命名空间 |
| [ItemOperations](./itemoperations) | ActiveSync 协议的 ItemOperations 命名空间 |
| [MaxAgeFilter](./maxagefilter) | 指定可以同步的最大日历天数。 |
| [MeetingResponse](./meetingresponse) | ActiveSync 协议的 MeetingResponse 命名空间 |
| [MergedFreeBusy](./mergedfreebusy) | 指定用户或分发列表的忙/闲信息。 |
| [MIMESupport](./mimesupport) | 为从服务器发送到客户端的电子邮件项目启用 MIME 支持。 |
| [MIMETruncation](./mimetruncation) | 指定电子邮件项的 MIME 数据在从服务器发送到客户端时是否应该被截断。 |
| [MinDevicePasswordComplexCharacters](./mindevicepasswordcomplexcharacters) | 指定客户端密码所需的复杂程度。 例如： 如果 MinDevicePasswordComplexCharacters 的值为 2，则包含大写和小写字母字符的密码就足够了， 与包含小写字母字符的密码一样和数字。 |
| [Move](./move) | 移动 ActiveSync 协议的命名空间 |
| [Namespace](./namespace) | ActiveSync 代码页 |
| [Notes](./notes) | ActiveSync 协议的 Notes 命名空间 |
| [OofState](./oofstate) | 指定 Oof 属性的可用性。 |
| [Ping](./ping) | ActiveSync 协议的 Ping 命名空间 |
| [Provision](./provision) | ActiveSync 协议的配置命名空间 |
| [ProvisionPolicyStatuses](./provisionpolicystatuses) | 该值指示客户端应用从服务器检索到的策略设置是成功还是失败。 |
| [ProvisionRemoteWipeStatuses](./provisionremotewipestatuses) | 该值表示客户端远程擦除操作的成功或失败。 |
| [RecipientType](./recipienttype) | 表示收件人的类型。 |
| [ResolveRecipients](./resolverecipients) | ActiveSync 协议的 ResolveRecipients 命名空间 |
| [RightsManagement](./rightsmanagement) | ActiveSync 协议的 RightsManagement 命名空间 |
| [Search](./search) | ActiveSync 协议的搜索命名空间 |
| [ServerType](./servertype) | 指定服务器类型 |
| [Settings](./settings) | ActiveSync 协议的设置命名空间 |
| [SignedSMIMEAlgorithm](./signedsmimealgorithm) | 指定签署 S/MIME 消息时使用的算法。 |
| [SMIMEEncryptionAlgorithmNegotiation](./smimeencryptionalgorithmnegotiation) | 控制加密算法的协商。 |
| [StoreType](./storetype) | 包含为操作指定位置的信息。 |
| [Tasks](./tasks) | ActiveSync 协议的任务命名空间 |
| [UserCreatedFolderTypes](./usercreatedfoldertypes) | 指定要创建的文件夹的类型。 |
| [UserResponse](./userresponse) | 指示会议是被接受、暂时接受还是被拒绝。 |
| [ValidateCert](./validatecert) | ActiveSync 协议的 ValidateCert 命名空间 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
