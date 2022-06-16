---
title: MapiCalendar
second_title: Aspose.Email for .NET API 参考
description: 表示mapi日历对象
type: docs
weight: 17910
url: /zh/net/aspose.email.mapi/mapicalendar/
---
## MapiCalendar class

表示mapi日历对象

```csharp
public sealed class MapiCalendar : MapiMessageItemBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MapiCalendar](mapicalendar#constructor)() | 初始化 [`MapiCalendar`](../mapicalendar) 类的新实例 |
| [MapiCalendar](mapicalendar#constructor_1)(string, string, string, DateTime, DateTime) | 初始化[`MapiCalendar`](../mapicalendar)类的新实例。 |
| [MapiCalendar](mapicalendar#constructor_2)(string, string, string, DateTime, DateTime, MapiElectronicAddress, MapiRecipientCollection) | 初始化[`MapiCalendar`](../mapicalendar)类的新实例。 |
| [MapiCalendar](mapicalendar#constructor_3)(string, string, string, DateTime, DateTime, string, MapiRecipientCollection) | 初始化[`MapiCalendar`](../mapicalendar)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AppointmentCounterProposal](../../aspose.email.mapi/mapicalendar/appointmentcounterproposal) { get; set; } | 获取或设置一个值，该值指示会议响应对象是否为反提议。 |
| [Attachments](../../aspose.email.mapi/mapicalendar/attachments) { get; } | 获取附件集合。 |
| [Attendees](../../aspose.email.mapi/mapicalendar/attendees) { get; set; } | 获取或设置参加者 |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | 包含与项目相关的账单信息。 |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | 获取消息文本。 |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | 获取转换为 HTML 的消息的[`BodyRtf`](../mapimessageitembase/bodyrtf)，如果存在，否则为空字符串. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | 获取或设置 RTF 格式的消息文本。 |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | 获取正文的类型。 |
| [BusyStatus](../../aspose.email.mapi/mapicalendar/busystatus) { get; set; } | 获取或设置忙状态 |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | 包含消息对象的关键字或类别。 |
| [ClientIntent](../../aspose.email.mapi/mapicalendar/clientintent) { get; set; } | 获取或设置用户对此会议对象执行的操作。 |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | 获取代码页。 |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | 包含与项目关联的公司名称。 |
| [EndDate](../../aspose.email.mapi/mapicalendar/enddate) { get; set; } | 获取或设置事件的结束日期和时间。 如果未设置日期，则返回DateTime的默认值。 |
| [EndDateTimeZone](../../aspose.email.mapi/mapicalendar/enddatetimezone) { get; set; } | 获取或设置指示 EndDate 属性时区的时区信息 |
| [IsAllDay](../../aspose.email.mapi/mapicalendar/isallday) { get; set; } | 获取或设置事件是否为全天事件 |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | 项目ID，与服务器一起使用 |
| [KeyWords](../../aspose.email.mapi/mapicalendar/keywords) { get; set; } | 获取或设置日历对象的类别 |
| [Location](../../aspose.email.mapi/mapicalendar/location) { get; set; } | 获取或设置事件的位置 |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | 获取区分大小写的字符串，该字符串标识发件人定义的消息类，例如 IPM.Note。 消息类指定消息的类型、目的或内容。 |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | 包含与项目关联的里程信息。 |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | 获取消息的命名属性。 |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | 获取命名属性映射。 |
| [Organizer](../../aspose.email.mapi/mapicalendar/organizer) { get; set; } | 获取或设置组织者。 |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | 获取属性集合。 |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | 获取属性流。 |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | 获取消息的收件人。 |
| [Recurrence](../../aspose.email.mapi/mapicalendar/recurrence) { get; set; } | 获取或设置循环属性 |
| [ReminderDelta](../../aspose.email.mapi/mapicalendar/reminderdelta) { get; set; } | 获取或设置提醒第一次过期的时间和日历对象的开始时间之间的时间间隔，以分钟为单位 |
| [ReminderFileParameter](../../aspose.email.mapi/mapicalendar/reminderfileparameter) { get; set; } | 指定提醒过期时客户端应该播放的声音的完整路径。 |
| [ReminderSet](../../aspose.email.mapi/mapicalendar/reminderset) { get; set; } | 获取或设置一个值，该值指示是否在对象上设置了提醒 |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | 获取灵敏度。 |
| [Sequence](../../aspose.email.mapi/mapicalendar/sequence) { get; set; } | 获取或设置序列号 |
| [StartDate](../../aspose.email.mapi/mapicalendar/startdate) { get; set; } | 获取或设置事件的开始日期和时间。 如果未设置日期，则返回DateTime的默认值。 |
| [StartDateTimeZone](../../aspose.email.mapi/mapicalendar/startdatetimezone) { get; set; } | 获取或设置指示 StartDate 属性时区的时区信息 |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | 获取或设置消息的主题。 |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | 获取主题前缀，该前缀通常表示对消息的某些操作，例如用于转发的“FW:”。 |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | 获取子存储。 |
| [Uid](../../aspose.email.mapi/mapicalendar/uid) { get; set; } | 获取唯一标识符 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Dispose](../../aspose.email.mapi/mapicalendar/dispose)() | 释放所有资源。 |
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
| [Save](../../aspose.email.mapi/mapicalendar/save#save)(Stream) | 使用默认保存选项将日历对象保存到具有 iCalendar 格式的文件 |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_2)(string) | 使用默认保存选项将日历对象保存到具有 iCalendar 格式的文件 |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_1)(Stream, AppointmentSaveFormat) | 使用默认保存选项将日历对象以指定格式保存到流中 |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_3)(string, AppointmentSaveFormat) | 使用默认保存选项将日历对象保存到具有指定格式的文件 |
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
