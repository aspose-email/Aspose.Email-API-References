---
title: MapiNote
second_title: Aspose.Email for .NET API 参考
description: 表示 Outlook Note 对象便笺
type: docs
weight: 18500
url: /zh/net/aspose.email.mapi/mapinote/
---
## MapiNote class

表示 Outlook Note 对象（“便笺”）

```csharp
public sealed class MapiNote : MapiMessageItemBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MapiNote](mapinote#constructor)() | 初始化[`MapiNote`](../mapinote)类的新实例。 |
| [MapiNote](mapinote#constructor_1)(string, string) | 初始化[`MapiNote`](../mapinote)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | 获取邮件中的附件。 |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | 包含与项目相关的账单信息。 |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | 获取消息文本。 |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | 获取转换为 HTML 的消息的[`BodyRtf`](../mapimessageitembase/bodyrtf)，如果存在，否则为空字符串. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | 获取或设置 RTF 格式的消息文本。 |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | 获取正文的类型。 |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | 包含消息对象的关键字或类别。 |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | 获取代码页。 |
| [Color](../../aspose.email.mapi/mapinote/color) { get; set; } | 获取或设置 Note 对象的建议背景颜色 |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | 包含与项目关联的公司名称。 |
| [CreationDate](../../aspose.email.mapi/mapinote/creationdate) { get; set; } | 获取或设置笔记的创建日期 |
| [Height](../../aspose.email.mapi/mapinote/height) { get; set; } | 获取或设置可见消息窗口的高度（以像素为单位） |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | 项目ID，与服务器一起使用 |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | 获取区分大小写的字符串，该字符串标识发件人定义的消息类，例如 IPM.Note。 消息类指定消息的类型、目的或内容。 |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | 包含与项目关联的里程信息。 |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | 获取消息的命名属性。 |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | 获取命名属性映射。 |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | 获取属性集合。 |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | 获取属性流。 |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | 获取消息的收件人。 |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | 获取灵敏度。 |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | 获取或设置消息的主题。 |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | 获取主题前缀，该前缀通常表示对消息的某些操作，例如用于转发的“FW:”。 |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | 获取子存储。 |
| [Width](../../aspose.email.mapi/mapinote/width) { get; set; } | 获取或设置可见消息窗口的宽度（以像素为单位） |
| [XPosition](../../aspose.email.mapi/mapinote/xposition) { get; set; } | 获取或设置用户界面显示的距离屏幕左边缘 的距离，以像素为单位注释对象 |
| [YPosition](../../aspose.email.mapi/mapinote/yposition) { get; set; } | 获取或设置距离，以像素为单位， 到用户界面显示的屏幕顶部边缘 注释对象 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | 通过属性描述符获取 MAPI 属性。 |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | 获取 tag 指定的属性值作为布尔类型。 |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | 获取tag指定的属性的字符串值。 |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | 获取 tag 指定为 DateTime 类型的属性值。 |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | 获取 tag 指定的属性的 int32 值。 |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | 获取 tag 指定的属性值，为 Long (int64) 类型。 |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | 获取 tag 指定的属性值为 Short 类型。 |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | 获取tag指定的属性的字符串值。 |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | 获取tag指定的属性的字符串值。 |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | 确定字符串属性是否为 Unicode 编码。 |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | 提供从所有集合中正确删除属性。 |
| [Save](../../aspose.email.mapi/mapinote/save#save)(Stream, NoteSaveFormat) | 将此[`MapiNote`](../mapinote)保存到使用指定格式的给定流中。 |
| [Save](../../aspose.email.mapi/mapinote/save#save_1)(string, NoteSaveFormat) | 使用指定格式将此[`MapiNote`](../mapinote)保存到文件中。 |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | 设置正文的内容。 |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | 设置正文的内容。 |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | 获取或设置 RTF 格式的消息文本。 |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | 设置消息标志。 |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | 设置属性。 |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | 设置 MAPI 属性。 |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | 尝试获取指定标签键的属性数据。 |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | 获取指定属性的值作为 DateTime 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | 获取指定属性的值作为 Int32 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | 获取指定属性的值为 Long 类型。 返回值表示操作是否成功。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | 尝试获取属性数据作为带有指定标签的字符串。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | 尝试获取属性数据作为具有指定标记和代码页的字符串。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | 获取字符串类型的指定属性的值。 返回值表示操作是否成功。 |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | 获取字符串类型的指定属性的值。 返回值表示操作是否成功。 |

### 也可以看看

* class [MapiMessageItemBase](../mapimessageitembase)
* 命名空间 [Aspose.Email.Mapi](../../aspose.email.mapi)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
