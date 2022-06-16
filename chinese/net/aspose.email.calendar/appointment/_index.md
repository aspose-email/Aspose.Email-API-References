---
title: Appointment
second_title: Aspose.Email for .NET API 参考
description: 表示电子邮件的日历
type: docs
weight: 430
url: /zh/net/aspose.email.calendar/appointment/
---
## Appointment class

表示电子邮件的日历。

```csharp
public class Appointment
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Appointment](appointment#constructor)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | 初始化[`Appointment`](../appointment)类的新实例。 |
| [Appointment](appointment#constructor_1)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | 初始化[`Appointment`](../appointment)类的新实例。 |
| [Appointment](appointment#constructor_2)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | 初始化[`Appointment`](../appointment)类的新实例。 |
| [Appointment](appointment#constructor_3)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | 初始化[`Appointment`](../appointment)类的新实例。 |
| [Appointment](appointment#constructor_4)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | 初始化[`Appointment`](../appointment)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Attachments](../../aspose.email.calendar/appointment/attachments) { get; } | 获取约会附件集合。 |
| [Attendees](../../aspose.email.calendar/appointment/attendees) { get; set; } | 获取或设置参加者。 |
| [Class](../../aspose.email.calendar/appointment/class) { get; set; } | 指定约会的访问分类。 |
| [CreatedDate](../../aspose.email.calendar/appointment/createddate) { get; set; } | 获取或设置日历信息创建的日期和时间。 |
| [Description](../../aspose.email.calendar/appointment/description) { get; set; } | 获取或设置描述。 |
| [EndDate](../../aspose.email.calendar/appointment/enddate) { get; set; } | 获取或设置结束日期。 |
| [EndTimeZone](../../aspose.email.calendar/appointment/endtimezone) { get; set; } | 结束时区 |
| [Flags](../../aspose.email.calendar/appointment/flags) { get; set; } | 获取或设置约会标志。 |
| [HtmlDescription](../../aspose.email.calendar/appointment/htmldescription) { get; set; } | 获取或设置描述的 html 表示。 |
| [LastModifiedDate](../../aspose.email.calendar/appointment/lastmodifieddate) { get; set; } | 获取或设置上次修改日历信息的日期和时间。 |
| [Location](../../aspose.email.calendar/appointment/location) { get; set; } | 获取或设置位置。 |
| [MethodType](../../aspose.email.calendar/appointment/methodtype) { get; set; } | 获取或设置与日历对象关联 的 iCalendar 对象方法类型。 |
| [MicrosoftBusyStatus](../../aspose.email.calendar/appointment/microsoftbusystatus) { get; set; } | 指定约会的忙碌状态。 |
| [MicrosoftImportance](../../aspose.email.calendar/appointment/microsoftimportance) { get; set; } | 指定约会的重要性。 |
| [MicrosoftIntendedStatus](../../aspose.email.calendar/appointment/microsoftintendedstatus) { get; set; } | 指定约会的 INTENDED 状态。 |
| [OptionalAttendees](../../aspose.email.calendar/appointment/optionalattendees) { get; } | 获取可选的与会者。 |
| [Organizer](../../aspose.email.calendar/appointment/organizer) { get; set; } | 获取或设置组织者。 |
| [Recurrence](../../aspose.email.calendar/appointment/recurrence) { get; set; } | 获取或设置重复模式。 |
| [Reminders](../../aspose.email.calendar/appointment/reminders) { get; } | 包含 AppointmentReminder[`AppointmentReminder`](../appointmentreminder)对象的集合。 |
| [SequenceId](../../aspose.email.calendar/appointment/sequenceid) { get; } | 获取序列 ID。 |
| [StartDate](../../aspose.email.calendar/appointment/startdate) { get; set; } | 获取或设置开始日期。 |
| [StartTimeZone](../../aspose.email.calendar/appointment/starttimezone) { get; set; } | 开始时区 |
| [Status](../../aspose.email.calendar/appointment/status) { get; set; } | 获取或设置对象的整体状态或确认。 |
| [Summary](../../aspose.email.calendar/appointment/summary) { get; set; } | 获取或设置摘要。 |
| [Transparency](../../aspose.email.calendar/appointment/transparency) { get; set; } | 指定此约会是否打算在可用性搜索中可见。 |
| [UniqueId](../../aspose.email.calendar/appointment/uniqueid) { get; set; } | 获取或设置包含日历项的 GUID 的字符串值。 在 MS Exchange 中，这是 PidLidGlobalObjectId mapi 属性。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Load](../../aspose.email.calendar/appointment/load#load)(Stream) | 从流 |
| static [Load](../../aspose.email.calendar/appointment/load#load_3)(string) | 从文件中加载[`Appointment`](../appointment)。 支持的文件格式:iCalendar |
| static [Load](../../aspose.email.calendar/appointment/load#load_1)(Stream, AppointmentLoadOptions) | 从流 |
| static [Load](../../aspose.email.calendar/appointment/load#load_2)(Stream, bool) | 从流 |
| static [Load](../../aspose.email.calendar/appointment/load#load_4)(string, AppointmentLoadOptions) | 从文件中加载[`Appointment`](../appointment)。 支持的文件格式:iCalendar  文件路径。 表示约会加载选项[`AppointmentLoadOptions`](../appointmentloadoptions)。 读取[`Appointment`](../appointment)。 |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment)() | 取消约会。 |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment_1)(int) | 取消约会。 |
| [GetAppointmentHtml](../../aspose.email.calendar/appointment/getappointmenthtml)() | 获取日历 HTML。 |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext)() | 获取日历文本。 |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext_1)(AppointmentFormattingOptions) | 获取日历文本。 |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment)() | 请求指定。 |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment_1)(int) | 请求指定。 |
| [ResetTimeZone](../../aspose.email.calendar/appointment/resettimezone)() | 设置本地时区 |
| [Save](../../aspose.email.calendar/appointment/save#save)(Stream) | 使用默认保存选项以 iCalendar 格式将约会保存到文件 |
| [Save](../../aspose.email.calendar/appointment/save#save_3)(string) | 使用默认保存选项以 iCalendar 格式将约会保存到文件 |
| [Save](../../aspose.email.calendar/appointment/save#save_1)(Stream, AppointmentSaveFormat) | 使用默认保存选项以指定格式将约会保存到流 |
| [Save](../../aspose.email.calendar/appointment/save#save_2)(Stream, AppointmentSaveOptions) | 使用指定的保存选项将约会保存到流 |
| [Save](../../aspose.email.calendar/appointment/save#save_4)(string, AppointmentSaveFormat) | 使用默认保存选项将约会保存到指定格式的文件 |
| [Save](../../aspose.email.calendar/appointment/save#save_5)(string, AppointmentSaveOptions) | 使用指定的保存选项将约会保存到文件 |
| [SetTimeZone](../../aspose.email.calendar/appointment/settimezone)(string) | 设置时区 |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment)() | 更新约会。 |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment_1)(int) | 更新约会。 |

### 例子

此示例演示如何将日历添加到电子邮件中。

[C#]

```csharp
MailMessage msg = new MailMessage();

//事件的参与者
MailAddressCollection attendees = new MailAddressCollection();
attendees.Add(new MailAddress("person1@domain.com"));
attendees.Add(new MailAddress("person2@domain.com"));
attendees.Add(new MailAddress("person3@domain.com"));

   //创建约会
Appointment app = new Appointment("Room 112",new DateTime(2006,7,17,13,0,0),new DateTime(2006,7,17,14,0,0),new MailAddress("somebody@domain.com"), attendees );
cal.Summary = "Release Meetting";
cal.Description = "Discuss for the next release";

   //将日历添加到message
msg.AddAlternateView(app.RequestApointment());

   //发送电子邮件消息
SmtpClient smtp= new SmtpClient("smtp.server.com", 25, "user", "password");
smtp.Send(msg);
```

[Visual Basic]

```csharp
Dim msg As MailMessage = New MailMessage()

'参加者为活动
Dim 参加者 As MailAddressCollection = New MailAddressCollection( )
Attendees.Add(New MailAddress("person1@domain.com"))
Attendees.Add(New MailAddress("person2@domain.com"))
Attendees.Add(New MailAddress("person3@domain.com"))

'创建日历
Dim cal As Appointment = New约会("112 房间",New DateTime(2006,7,17,13,0,0),New DateTime(2006,7,17,14,0,0),New MailAddress("somebody@domain.com") ,attendees)
cal.Summary = "发布会议"
cal.Description = "讨论下一个版本"

'在消息中添加日历
msg.AddAlternateView(app.RequestApointment())
```

### 也可以看看

* 命名空间 [Aspose.Email.Calendar](../../aspose.email.calendar)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
