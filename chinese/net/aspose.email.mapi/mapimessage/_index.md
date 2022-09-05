---
title: MapiMessage
second_title: Aspose.Email for .NET API 参考
description: 表示可以解析的 Outlook Message 格式文档
type: docs
weight: 18450
url: /zh/net/aspose.email.mapi/mapimessage/
---
## MapiMessage class

表示可以解析的 Outlook Message 格式文档。

```csharp
public sealed class MapiMessage : MapiMessageItemBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MapiMessage](mapimessage#constructor)() | 初始化[`MapiMessage`](../mapimessage)类. |
| [MapiMessage](mapimessage#constructor_1)(OutlookMessageFormat) | 初始化[`MapiMessage`](../mapimessage)类. |
| [MapiMessage](mapimessage#constructor_2)(string, string, string, string) | 初始化[`MapiMessage`](../mapimessage)类. |
| [MapiMessage](mapimessage#constructor_3)(string, string, string, string, OutlookMessageFormat) | 初始化[`MapiMessage`](../mapimessage)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | 获取邮件中的附件。 |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | 包含与项目关联的帐单信息。 |
| [Body](../../aspose.email.mapi/mapimessage/body) { get; set; } | 获取消息文本。 |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | 获取[`BodyRtf`](../mapimessageitembase/bodyrtf)将消息转换为 HTML（如果存在），否则为空字符串。 |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | 获取或设置 RTF 格式的消息文本。 |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | 获取 body 的类型。 |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | 包含消息对象的关键字或类别。 |
| [ClientSubmitTime](../../aspose.email.mapi/mapimessage/clientsubmittime) { get; set; } | 获取或设置日期和时间 消息发送者提交消息 |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | 获取代码页。 |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | 包含与项目关联的公司名称。 |
| [ConversationTopic](../../aspose.email.mapi/mapimessage/conversationtopic) { get; } | 获取对话线程中第一条消息的主题。 |
| [DeliveryTime](../../aspose.email.mapi/mapimessage/deliverytime) { get; set; } | 获取或设置日期和时间 消息已送达。 |
| [DisplayBcc](../../aspose.email.mapi/mapimessage/displaybcc) { get; } | 获取所有密件抄送 (BCC) 消息收件人的显示名称列表，以分号 (;) 分隔。 |
| [DisplayCc](../../aspose.email.mapi/mapimessage/displaycc) { get; } | 获取所有抄送 (CC) 消息收件人的显示名称列表，以分号 (;) 分隔。 |
| [DisplayName](../../aspose.email.mapi/mapimessage/displayname) { get; } | 获取消息的显示名称。 |
| [DisplayNamePrefix](../../aspose.email.mapi/mapimessage/displaynameprefix) { get; } | 获取显示名称的前缀。 |
| [DisplayTo](../../aspose.email.mapi/mapimessage/displayto) { get; } | 获取主要 (To) 邮件收件人的显示名称列表，以分号 (;) 分隔。 |
| [Flags](../../aspose.email.mapi/mapimessage/flags) { get; } | 获取消息标志。 |
| [Headers](../../aspose.email.mapi/mapimessage/headers) { get; set; } | 获取传输消息头 |
| [InternetMessageId](../../aspose.email.mapi/mapimessage/internetmessageid) { get; } | 获取消息的消息id。 |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | 项目 ID，与服务器一起使用 |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | 获取区分大小写的字符串，标识发送方定义的消息类，例如 IPM。注意。 消息类指定消息的类型、用途或内容。 |
| [MessageFormat](../../aspose.email.mapi/mapimessage/messageformat) { get; } | 获取 Outlook 消息格式。 |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | 包含与项目关联的里程信息。 |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | 获取消息的命名属性。 |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | 获取命名属性映射。 |
| [NormalizedSubject](../../aspose.email.mapi/mapimessage/normalizedsubject) { get; } | 获取消息的规范化主题。 |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | 获取属性的集合。 |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | 获取属性流。 |
| [ReadReceiptRequested](../../aspose.email.mapi/mapimessage/readreceiptrequested) { get; set; } | 获取或设置是否请求已读回执的值。 |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | 获取消息的收件人。 |
| [ReplyTo](../../aspose.email.mapi/mapimessage/replyto) { get; set; } | 获取或设置对名称的回复。 |
| [SenderAddressType](../../aspose.email.mapi/mapimessage/senderaddresstype) { get; } | 获取消息发送者的电子邮件地址类型。 |
| [SenderEmailAddress](../../aspose.email.mapi/mapimessage/senderemailaddress) { get; set; } | 获取或设置邮件发送者的电子邮件地址。 |
| [SenderName](../../aspose.email.mapi/mapimessage/sendername) { get; set; } | 获取或设置消息发送者的显示名称。 |
| [SenderSmtpAddress](../../aspose.email.mapi/mapimessage/sendersmtpaddress) { get; set; } | 获取或设置邮件发送者的电子邮件地址。 |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | 获取灵敏度。 |
| [SentRepresentingAddressType](../../aspose.email.mapi/mapimessage/sentrepresentingaddresstype) { get; } | 获取发件人所代表的消息传递用户的地址类型。 |
| [SentRepresentingEmailAddress](../../aspose.email.mapi/mapimessage/sentrepresentingemailaddress) { get; set; } | 获取或设置发件人代表的消息传递用户的电子邮件地址。 |
| [SentRepresentingName](../../aspose.email.mapi/mapimessage/sentrepresentingname) { get; set; } | 获取或设置发件人所代表的消息传递用户的显示名称。 |
| [SentRepresentingSmtpAddress](../../aspose.email.mapi/mapimessage/sentrepresentingsmtpaddress) { get; } | 获取或设置发件人代表的消息传递用户的电子邮件地址。 |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | 获取或设置消息的主题。 |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | 获取主题前缀，该前缀通常指示对消息的某些操作，例如用于转发的“FW:”。 |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | 获取子存储。 |
| [TransportMessageHeaders](../../aspose.email.mapi/mapimessage/transportmessageheaders) { get; } | 获取特定于传输的消息信封信息。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage)(MailMessage) | 从 MailMessage 创建 MapiMessage 实例。 |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_2)(string) | 从 MailMessage 创建 MapiMessage 实例。 |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_1)(MailMessage, MapiConversionOptions) | 从 MailMessage 创建 MapiMessage 实例。 |
| static [FromProperties](../../aspose.email.mapi/mapimessage/fromproperties)(MapiPropertyCollection) | 从 Mapi 属性的集合创建 MapiMessage 的实例。 |
| static [Load](../../aspose.email.mapi/mapimessage/load#load)(Stream) | 从流中加载消息。 |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_2)(string) | 从文件加载消息。 |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_1)(Stream, LoadOptions) | 使用附加选项从流中加载消息。 |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_3)(string, LoadOptions) | 使用附加选项从文件加载消息。 |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef)(Stream) | 从传输中性封装格式 (TNEF) 数据结构加载消息 |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef_1)(string) | 从传输中性封装格式 (TNEF) 数据结构加载消息 |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty)(MapiProperty, string) | 添加自定义属性。 |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty_1)(MapiPropertyType, byte[], string) | 添加自定义属性。 |
| [CheckBounced](../../aspose.email.mapi/mapimessage/checkbounced)() | 检查是否可以将此邮件视为退回邮件。 |
| [Clone](../../aspose.email.mapi/mapimessage/clone)() | 创建一个作为当前实例副本的新对象。 |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| [GetCustomProperties](../../aspose.email.mapi/mapimessage/getcustomproperties)() | 获取自定义 MapiProperties 的集合。 |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | 通过属性描述符获取 MAPI 属性。 |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | 获取tag指定的属性值为布尔类型。 |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | 获取tag指定的属性的字符串值。 |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | 获取 tag 指定的属性值为 DateTime 类型。 |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | 获取tag指定的属性的int32值。 |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | 获取tag指定的属性值为Long(int64)类型。 |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | 获取 tag 指定的属性值为 Short 类型。 |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | 获取tag指定的属性的字符串值。 |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | 获取tag指定的属性的字符串值。 |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | 确定字符串属性是否为 Unicode 编码。 |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | 提供从所有集合中正确删除的属性。 |
| [Save](../../aspose.email.mapi/mapimessage/save#save)(Stream) | 作为 Msg. 保存到指定的流 |
| [Save](../../aspose.email.mapi/mapimessage/save#save_2)(string) | 保存到指定文件作为 Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_1)(Stream, SaveOptions) | 将消息保存为带有附加选项的流。 |
| [Save](../../aspose.email.mapi/mapimessage/save#save_3)(string, SaveOptions) | 将消息另存为带有附加选项的文件。 |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate)(Stream) | 以 Outlook 文件模板（OFT 格式）保存到指定流。 |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate_1)(string) | 以 Outlook 文件模板（OFT 格式）保存到指定文件。 |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef)(Stream) | 以 TNEF 格式保存消息。 |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef_1)(string) | 以 TNEF 格式保存消息。 |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | 设置正文的内容。 |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | 设置正文的内容。 |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | 获取或设置 RTF 格式的消息文本。 |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | 设置消息标志。 |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | 设置属性。 |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | 设置 MAPI 属性。 |
| [SetStringPropertyValue](../../aspose.email.mapi/mapimessage/setstringpropertyvalue)(long, string) | 设置字符串属性值。 |
| [ToMailMessage](../../aspose.email.mapi/mapimessage/tomailmessage)(MailConversionOptions) | 从此 MapiMessage 创建 MailMessage 的实例。 |
| [ToMapiMessageItem](../../aspose.email.mapi/mapimessage/tomapimessageitem)() | 将 MapiMessage 转换为 IMapiMessageItem object 依赖于 MessageClass. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | 尝试获取指定标签键的属性数据。 |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | 获取指定属性的值作为 DateTime 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | 获取指定属性的值作为 Int32 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | 获取指定属性的值作为 Long 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | 尝试获取属性数据作为带有指定标签的字符串。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | 尝试将属性数据作为具有指定标签和代码页的字符串获取。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | 以字符串类型获取指定属性的值。 返回值表示操作是否成功。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | 以字符串类型获取指定属性的值。 返回值表示操作是否成功。 |
| static [DestroyAttachments](../../aspose.email.mapi/mapimessage/destroyattachments)(string) | 销毁指定 Outlook 邮件文件中的附件。 DestroyAttachments 将忽略附件解析。 |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat)(Stream) | 判断指定流是否有MSG格式 |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat_1)(string) | 判断指定文件是否为MSG格式 |
| static [RemoveAttachments](../../aspose.email.mapi/mapimessage/removeattachments)(string) | 从指定的 Outlook 邮件文件中删除所有附件。 |

### 评论

MapiMessage 类的实例用于表示由 MapiMessageReader 类 解析的 Microsoft Outlook 消息文档文件。 要访问电子邮件的发件人、收件人和内容，请使用 MapiMessage 类的相关属性。

### 例子

以下示例演示了如何读取 Outlook 邮件文件。

[C＃]

[视觉基础]

```csharp
//打开 Outlook 邮件文件
MapiMessage msg = MapiMessage.FromFile(@"c:\outlookmessage.msg");

/读取主题
onsole.WriteLine("Subject:" + msg.Subject);

/发件者姓名
onsole.WriteLine("From:" + msg.SenderName);

/邮件正文
onsole.WriteLine("Body:" + msg.Body);

/附件
oreach(MapiAttachment att in msg.Attachments)

   Console.WriteLine("Attachment Name:"+att.FileName);
   att.Save(att.FileName);
    
```

```csharp
'打开 Outlook 邮件文件 
Dim msg As MapiMessage = MapiMessage.FromFile("c:\outlookmessage.msg") 

'阅读主题 
Console.WriteLine("Subject:" + msg.Subject) 

'发件者姓名 
Console.WriteLine("From:" + msg.SenderName) 

'邮件正文 
Console.WriteLine("Body:" + msg.Body) 

'附件 
For Each att As MapiAttachment In msg.Attachments 
    Console.WriteLine("Attachment Name:" + att.FileName) 
    att.Save(att.FileName) 
Next
```

### 也可以看看

* class [MapiMessageItemBase](../mapimessageitembase)
* 命名空间 [Aspose.Email.Mapi](../../aspose.email.mapi)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
