---
title: EASProvisionDoc
second_title: Aspose.Email for .NET API 参考
description: 指定设备配置的安全设置集合
type: docs
weight: 1190
url: /zh/net/aspose.email.clients.activesync.transportlayer/easprovisiondoc/
---
## EASProvisionDoc class

指定设备配置的安全设置集合。

```csharp
public class EASProvisionDoc
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EASProvisionDoc](easprovisiondoc)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AllowBluetooth](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowbluetooth) { get; set; } | 指定设备上蓝牙的使用。 如果客户端不支持蓝牙，这个属性应该被忽略。 |
| [AllowBrowser](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowbrowser) { get; set; } | 指定设备是否允许使用网络浏览器。 |
| [AllowCamera](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowcamera) { get; set; } | 指定设备是否允许使用内置摄像头。 如果客户端没有相机并且没有相机可以连接到设备，则应该忽略此属性。 |
| [AllowConsumerEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowconsumeremail) { get; set; } | 指定设备是否允许用户配置个人电子邮件帐户。 |
| [AllowDesktopSync](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowdesktopsync) { get; set; } | 指定设备是否允许与 Desktop ActiveSync 同步。 如果客户端不支持连接到个人计算机，则应忽略此属性。 |
| [AllowHTMLEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowhtmlemail) { get; set; } | 指定客户端是否使用 HTML 格式的电子邮件。 |
| [AllowInternetSharing](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowinternetsharing) { get; set; } | 指定设备是否允许使用 Internet 共享。 如果客户端不支持与其他设备共享其互联网连接，则应忽略此属性。 |
| [AllowIrDA](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowirda) { get; set; } | 指定设备是否允许使用 IrDA（红外线）连接。 如果客户端不具备发送或接收红外信号的能力，则应忽略此属性。 |
| [AllowPOPIMAPEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowpopimapemail) { get; set; } | 指定设备是否允许访问 POP 或 IMAP 电子邮件。 |
| [AllowRemoteDesktop](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowremotedesktop) { get; set; } | 指定设备是否允许使用远程桌面。 如果客户端不支持远程连接到个人计算机，则应忽略此属性。 |
| [AllowSimpleDevicePassword](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsimpledevicepassword) { get; set; } | 指定客户端是否允许使用简单密码。 简单密码是仅由重复（“2222”）或连续（“abcd”）字符组成的密码。 如果 AllowSimpleDevicePassword 为空，客户端应该将此值视为 TRUE。 如果 DevicePasswordEnabled 的值设置为 FALSE，客户端应该忽略这个属性。 |
| [AllowSMIMEEncryptionAlgorithmNegotiation](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsmimeencryptionalgorithmnegotiation) { get; set; } | 控制加密算法的协商。 |
| [AllowSMIMESoftCerts](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsmimesoftcerts) { get; set; } | 指定客户端是否可以使用软证书来签署传出消息。 |
| [AllowStorageCard](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowstoragecard) { get; set; } | 指定设备是否允许使用存储卡。 如果客户端不支持在可移动存储上存储数据，则应忽略此属性。 |
| [AllowTextMessaging](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowtextmessaging) { get; set; } | 指定设备是否允许使用 SMS 或文本消息。 如果客户端不支持 SMS 或文本消息，则应忽略此属性。 |
| [AllowUnsignedApplications](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowunsignedapplications) { get; set; } | 指定设备是否允许执行未签名的应用程序。 |
| [AllowUnsignedInstallationPackages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowunsignedinstallationpackages) { get; set; } | 指定设备是否允许安装未签名的cabinet (.cab) 文件。 |
| [AllowWiFi](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowwifi) { get; set; } | 指定设备是否允许使用 Wi-Fi 连接。 如果客户端没有 Wi-Fi 功能，则应忽略此属性。 |
| [AlphanumericDevicePasswordRequired](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/alphanumericdevicepasswordrequired) { get; set; } | 指定客户端是否需要字母数字密码。 如果 AlphanumericDevicePasswordRequired 为空，客户端应该将此值视为 FALSE。 如果 DevicePasswordEnabled 的值为 FALSE，客户端应该忽略这个属性。 |
| [ApprovedApplicationList](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/approvedapplicationlist) { get; } | 指定被批准执行的内存应用程序列表。 只有内存中的应用程序受此属性影响。 此属性不适用于 in-ROM 应用程序。 如果非空，客户端必须只允许此属性指定的内存应用程序执行。 |
| [AttachmentsEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/attachmentsenabled) { get; set; } | 指定是否启用电子邮件附件。 |
| [DevicePasswordEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordenabled) { get; set; } | 指定客户端是否需要密码。 |
| [DevicePasswordExpiration](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordexpiration) { get; set; } | 指定密码过期前的最大天数。 DevicePasswordExpiration 可以为空，表示没有设置密码过期策略。 有效值如下所列: = 0 - 密码不会过期。 &gt; 0 - 密码在指定的最大天数内过期。 如果 DevicePasswordExpiration 为空，客户端应将此值视为 0。 如果 DevicePasswordEnabled 的值设置为 FALSE，则客户端应忽略此属性。 |
| [DevicePasswordHistory](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordhistory) { get; set; } | 指定存储的以前使用的密码的最小数量，以防止客户端重复使用。 有效值如下所示: = 0 - 不需要存储以前使用的密码。 &gt; 0 - 要存储的先前使用的密码的最小数量。 如果 DevicePasswordHistory 为空，则客户端应将此值视为 0。 如果 DevicePasswordEnabled 的值设置为 TRUE，则客户端不允许用户使用存储的先验密码过期后的密码。 如果 DevicePasswordEnabled 的值设置为 FALSE，客户端应该忽略这个属性。 |
| [MaxAttachmentSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxattachmentsize) { get; set; } | 指定由安全策略确定的最大附件大小（以字节为单位）。 如果该属性为空，则客户端将此解释为意味着安全策略未设置最大附件大小。 |
| [MaxCalendarAgeFilter](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxcalendaragefilter) { get; set; } | 指定可以同步的最大日历天数。 有效值如下所列: 所有天 2 周 1 个月 3 个月 6 个月 |
| [MaxDevicePasswordFailedAttempts](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxdevicepasswordfailedattempts) { get; set; } | 指定允许的最大失败密码登录尝试次数。 如果达到最大失败密码登录尝试次数，客户端应该执行本地擦除或进入超时锁定模式。 MaxDevicePasswordFailedAttempts 可以为 null 或具有 4 到 16 范围内的值。 如果该属性为 null，则客户端将其解释为没有最大失败密码次数登录尝试已由安全策略设置。 如果 DevicePasswordEnabled 的值设置为 FALSE，则客户端忽略此属性。 |
| [MaxEmailAgeFilter](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailagefilter) { get; set; } | 指定同步的电子邮件期限。 有效值如下所列: 同步所有 1 天 3 天 1 周 2 周 1 个月 |
| [MaxEmailBodyTruncationSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailbodytruncationsize) { get; set; } | 指定纯文本格式电子邮件的截断大小。 有效值如下所列: -1 无截断。 =0 仅截断标题。 &gt;0 将电子邮件正文截断为指定大小。 |
| [MaxEmailHTMLBodyTruncationSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailhtmlbodytruncationsize) { get; set; } | 指定 HTML 格式电子邮件的截断大小。 有效值如下所列: -1 无截断。 =0 仅截断标题。 &gt;0 将电子邮件正文截断为指定大小。 |
| [MaxInactivityTimeDeviceLock](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxinactivitytimedevicelock) { get; set; } | 指定设备锁定自身之前不活动的最大秒数。 如果这个值大于等于9999，客户端将其解释为无限制。 如果 MaxInactivityTimeDeviceLock 为空，则客户端将此解释为意味着安全策略没有设置时间设备锁定。 |
| [MinDevicePasswordComplexCharacters](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/mindevicepasswordcomplexcharacters) { get; set; } | 指定客户端密码所需的复杂程度。 该值指定密码中需要出现的字符组数。 字符组定义为: 小写字母字符 = 1 小写和大写字母字符 = 2 小写、大写字母字符和数字 = 3 小写和大写字母字符、数字和非字母数字字符 = 4 例如 如果 MinDevicePasswordComplexCharacters 的值为 2，则同时包含大写和小写字母字符的密码就足够了， 与包含小写字母字符和数字的密码一样。 |
| [MinDevicePasswordLength](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/mindevicepasswordlength) { get; set; } | 指定最小客户端密码长度。 MinDevicePasswordLength 可以为空，也可以是不小于 1 且不大于 16 的值。 如果该属性为 null 或该属性的值为 1，则没有设备密码的最小长度。 如果 DevicePasswordEnabled 的值为 FALSE，客户端应该忽略这个属性。 |
| [PasswordRecoveryEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/passwordrecoveryenabled) { get; set; } | 指定服务器是否支持存储由客户端使用设置命令发送的恢复密码。 恢复密码是由客户端创建的特殊密码，它赋予管理员或用户一次登录设备的能力， 之后用户需要创建新密码。然后客户端创建一个新的恢复密码。 如果 PasswordRecoveryEnabled 设置为 TRUE，则服务器支持存储设备发送的恢复密码。 如果该属性设置为 FALSE，则设备不应发送恢复密码，因为服务器不支持存储密码。 如果 PasswordRecoveryEnabled 为空，客户端应该将此值视为 FALSE。 如果 DevicePasswordEnabled 的值为 FALSE，客户端应该忽略这个属性。 如果客户端不支持恢复密码，则应忽略此属性。 |
| [RequireDeviceEncryption](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiredeviceencryption) { get; set; } | 指定客户端是否使用加密。 |
| [RequireEncryptedSMIMEMessages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requireencryptedsmimemessages) { get; set; } | 指定客户端是否发送加密电子邮件。 |
| [RequireEncryptionSMIMEAlgorithm](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requireencryptionsmimealgorithm) { get; set; } | 指定加密 S/MIME 消息时使用的算法。 |
| [RequireManualSyncWhenRoaming](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiremanualsyncwhenroaming) { get; set; } | 指定设备漫游时是否需要手动同步。 |
| [RequireSignedSMIMEAlgorithm](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiresignedsmimealgorithm) { get; set; } | 指定签署 S/MIME 消息时使用的算法。 |
| [RequireSignedSMIMEMessages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiresignedsmimemessages) { get; set; } | 指定客户端是否发送签名的 S/MIME 消息。 |
| [RequireStorageCardEncryption](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requirestoragecardencryption) { get; set; } | 指定设备是否加密存储在设备上的内容。 如果客户端不支持在可移动存储上存储数据，则应忽略此属性。 |
| [UnapprovedInROMApplicationList](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/unapprovedinromapplicationlist) { get; } | 指定未被批准执行的 in-ROM 应用程序列表。 只有预装在 ROM 中的应用程序才受此属性中的条目影响。 此属性不适用于安装在内存中的应用程序。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
