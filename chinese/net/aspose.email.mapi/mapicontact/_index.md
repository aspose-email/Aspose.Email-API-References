---
title: MapiContact
second_title: Aspose.Email for .NET API 参考
description: 代表outlook联系信息
type: docs
weight: 18190
url: /zh/net/aspose.email.mapi/mapicontact/
---
## MapiContact class

代表outlook联系信息

```csharp
public sealed class MapiContact : MapiMessageItemBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MapiContact](mapicontact#constructor)() | 初始化[`MapiContact`](../mapicontact) class |
| [MapiContact](mapicontact#constructor_1)(string, string) | 初始化[`MapiContact`](../mapicontact)类. |
| [MapiContact](mapicontact#constructor_2)(string, string, string) | 初始化[`MapiContact`](../mapicontact)类. |
| [MapiContact](mapicontact#constructor_3)(string, string, string, string) | 初始化[`MapiContact`](../mapicontact)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapicontact/attachments) { get; } | 获取联系人中的附件。 |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | 包含与项目关联的帐单信息。 |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | 获取消息文本。 |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | 获取[`BodyRtf`](../mapimessageitembase/bodyrtf)将消息转换为 HTML（如果存在），否则为空字符串。 |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | 获取或设置 RTF 格式的消息文本。 |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | 获取 body 的类型。 |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | 包含消息对象的关键字或类别。 |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | 获取代码页。 |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | 包含与项目关联的公司名称。 |
| [ElectronicAddresses](../../aspose.email.mapi/mapicontact/electronicaddresses) { get; set; } | 为最多三个不同的 电子邮件地址 和三个不同的传真地址 指定属性 |
| [Events](../../aspose.email.mapi/mapicontact/events) { get; set; } | 指定与联系人关联的事件 |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | 项目 ID，与服务器一起使用 |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | 获取区分大小写的字符串，标识发送方定义的消息类，例如 IPM。注意。 消息类指定消息的类型、用途或内容。 |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | 包含与项目关联的里程信息。 |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | 获取消息的命名属性。 |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | 获取命名属性映射。 |
| [NameInfo](../../aspose.email.mapi/mapicontact/nameinfo) { get; set; } | 属性用于指定联系人所代表的人的姓名 |
| [OtherFields](../../aspose.email.mapi/mapicontact/otherfields) { get; set; } | 指定联系人的其他字段。 |
| [PersonalInfo](../../aspose.email.mapi/mapicontact/personalinfo) { get; set; } | 指定其他附加联系信息 |
| [Photo](../../aspose.email.mapi/mapicontact/photo) { get; set; } | 包含联系人照片[`MapiContactPhoto`](../mapicontactphoto). |
| [PhysicalAddresses](../../aspose.email.mapi/mapicontact/physicaladdresses) { get; set; } | 指定三个物理地址： 家庭地址、工作地址和其他地址。 其中一个地址可以标记为邮寄地址 |
| [ProfessionalInfo](../../aspose.email.mapi/mapicontact/professionalinfo) { get; set; } | 属性用于存储联系人代表的人的专业 详细信息 |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | 获取属性的集合。 |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | 获取属性流。 |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | 获取消息的收件人。 |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | 获取灵敏度。 |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | 获取或设置消息的主题。 |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | 获取主题前缀，该前缀通常指示对消息的某些操作，例如用于转发的“FW:”。 |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | 获取子存储。 |
| [Telephones](../../aspose.email.mapi/mapicontact/telephones) { get; set; } | 指定联系人的电话号码 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard)(Stream) | 读取[`MapiContact`](../mapicontact)来自包含 vCard 的指定流。 支持的 vCard 版本为 2.1 和 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_2)(string) | 读取[`MapiContact`](../mapicontact)从指定的 vCard 文件 支持的 vCard 版本为 2.1 和 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_1)(Stream, Encoding) | 读取[`MapiContact`](../mapicontact)来自包含 vCard 的指定流。 支持的 vCard 版本为 2.1 和 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_3)(string, Encoding) | 读取[`MapiContact`](../mapicontact)从指定的 vCard 文件 支持的 vCard 版本为 2.1 和 3.0 |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | 通过属性描述符获取 MAPI 属性。 |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | 获取tag指定的属性值为布尔类型。 |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | 获取tag指定的属性的字符串值。 |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | 获取 tag 指定的属性值为 DateTime 类型。 |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | 获取tag指定的属性的int32值。 |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | 获取tag指定的属性值为Long(int64)类型。 |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | 获取 tag 指定的属性值为 Short 类型。 |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | 获取tag指定的属性的字符串值。 |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | 获取tag指定的属性的字符串值。 |
| [GetUnderlyingMessage](../../aspose.email.mapi/mapicontact/getunderlyingmessage)() | 获取代表联系人的 MapiMessage。 |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | 确定字符串属性是否为 Unicode 编码。 |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | 提供从所有集合中正确删除的属性。 |
| [Save](../../aspose.email.mapi/mapicontact/save#save)(Stream) | 保存这个[`MapiContact`](../mapicontact)进入具有 vCard 格式的给定流。 支持的 vCard 版本是 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_3)(string) | 保存这个[`MapiContact`](../mapicontact)到带有默认选项的 vCard 文件。 支持的 vCard 版本是 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_1)(Stream, ContactSaveFormat) | 保存这个[`MapiContact`](../mapicontact)使用默认选项的格式保存到给定的流。 支持的保存格式是vCard |
| [Save](../../aspose.email.mapi/mapicontact/save#save_2)(Stream, ContactSaveOptions) | 保存这个[`MapiContact`](../mapicontact)使用指定的保存选项到给定的流。 支持的保存选项是[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| [Save](../../aspose.email.mapi/mapicontact/save#save_4)(string, ContactSaveFormat) | 保存这个[`MapiContact`](../mapicontact)以使用默认选项的格式保存到指定文件。 支持的保存格式为 vCard。 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_5)(string, ContactSaveOptions) | 保存这个[`MapiContact`](../mapicontact)使用指定的保存选项进入文件。 支持的保存选项是[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| override [SetBodyContent](../../aspose.email.mapi/mapicontact/setbodycontent#setbodycontent)(string, BodyContentType) | 设置正文的内容。 |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | 设置正文的内容。 |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | 获取或设置 RTF 格式的消息文本。 |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | 设置消息标志。 |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | 设置属性。 |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | 设置 MAPI 属性。 |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | 尝试获取指定标签键的属性数据。 |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | 获取指定属性的值作为 DateTime 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | 获取指定属性的值作为 Int32 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | 获取指定属性的值作为 Long 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | 尝试获取属性数据作为带有指定标签的字符串。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | 尝试将属性数据作为具有指定标签和代码页的字符串获取。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | 以字符串类型获取指定属性的值。 返回值表示操作是否成功。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | 以字符串类型获取指定属性的值。 返回值表示操作是否成功。 |

### 也可以看看

* class [MapiMessageItemBase](../mapimessageitembase)
* 命名空间 [Aspose.Email.Mapi](../../aspose.email.mapi)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
