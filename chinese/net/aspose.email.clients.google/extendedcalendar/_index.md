---
title: ExtendedCalendar
second_title: Aspose.Email for .NET API 参考
description: 单个日历的一组扩展元数据例如颜色
type: docs
weight: 15700
url: /zh/net/aspose.email.clients.google/extendedcalendar/
---
## ExtendedCalendar class

单个日历的一组扩展元数据，例如颜色。

```csharp
public class ExtendedCalendar : Calendar
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ExtendedCalendar](extendedcalendar#constructor)() | 初始化 ExtendedCalendar 类的新实例。 |
| [ExtendedCalendar](extendedcalendar#constructor_1)(string) | 初始化 ExtendedCalendar 类的新实例。 |
| [ExtendedCalendar](extendedcalendar#constructor_2)(string, string) | 初始化 ExtendedCalendar 类的新实例。 |
| [ExtendedCalendar](extendedcalendar#constructor_3)(string, string, string, string) | 初始化 ExtendedCalendar 类的新实例。 |
| [ExtendedCalendar](extendedcalendar#constructor_4)(string, string, string, string, string) | 初始化 ExtendedCalendar 类的新实例。 |
| [ExtendedCalendar](extendedcalendar#constructor_5)(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | 初始化 ExtendedCalendar 类的新实例。 |
| [ExtendedCalendar](extendedcalendar#constructor_6)(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | 初始化 ExtendedCalendar 类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [AccessRole](../../aspose.email.clients.google/extendedcalendar/accessrole) { get; } | 认证用户在日历上的有效访问角色。只读。可能的值为： |
| virtual [BackgroundColor](../../aspose.email.clients.google/extendedcalendar/backgroundcolor) { get; set; } | 格式为“#0088aa”的日历的主要颜色。 此属性取代基于索引的 colorId 属性。 |
| virtual [ColorId](../../aspose.email.clients.google/extendedcalendar/colorid) { get; set; } | 日历的颜色。 这是一个 ID，指的是颜色定义的“日历”部分中的条目（请参阅“颜色”端点）。 |
| virtual [ConferenceProperties](../../aspose.email.clients.google/calendar/conferenceproperties) { get; } | 获取此日历的会议属性。 |
| virtual [DefaultReminders](../../aspose.email.clients.google/extendedcalendar/defaultreminders) { get; set; } | 经过身份验证的用户对此日历的默认提醒。 |
| virtual [Description](../../aspose.email.clients.google/calendar/description) { get; set; } | 日历的描述。 |
| virtual [ETag](../../aspose.email.clients.google/basedataobject/etag) { get; set; } | ETag 或实体标记是 HTTP 为 Web 缓存验证提供的几种机制之一，它允许客户端发出条件请求。 这允许缓存更有效，并节省带宽，因为如果内容没有更改，Web 服务器不需要发送完整的响应。 ETag 也可用于乐观并发控制，以帮助防止资源的同时更新相互覆盖。 |
| virtual [ForegroundColor](../../aspose.email.clients.google/extendedcalendar/foregroundcolor) { get; set; } | 日历的前景色，格式为“#ffffff”。 此属性取代基于索引的 colorId 属性。 |
| virtual [Hidden](../../aspose.email.clients.google/extendedcalendar/hidden) { get; set; } | 日历是否已从列表中隐藏。 默认为 False。 |
| virtual [Id](../../aspose.email.clients.google/basedataobject/id) { get; set; } | 资源标识符。 |
| virtual [Kind](../../aspose.email.clients.google/basedataobject/kind) { get; } | 资源类型 |
| virtual [Location](../../aspose.email.clients.google/calendar/location) { get; set; } | 日历的地理位置为自由格式文本。 |
| virtual [NotificationSettings](../../aspose.email.clients.google/extendedcalendar/notificationsettings) { get; set; } | 已通过身份验证的用户收到的此日历的通知。 |
| virtual [Primary](../../aspose.email.clients.google/extendedcalendar/primary) { get; set; } | 日历是否是认证用户的主日历。只读。 默认为 False。 |
| virtual [Selected](../../aspose.email.clients.google/extendedcalendar/selected) { get; set; } | 日历内容是否显示在日历 UI 中。 默认为 False。 |
| virtual [Summary](../../aspose.email.clients.google/calendar/summary) { get; set; } | 日历的标题。 |
| virtual [SummaryOverride](../../aspose.email.clients.google/extendedcalendar/summaryoverride) { get; set; } | 已验证用户为此日历设置的摘要。 |
| virtual [TimeZone](../../aspose.email.clients.google/calendar/timezone) { get; set; } | 日历的时区。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [ToString](../../aspose.email.clients.google/extendedcalendar/tostring)() | 返回代表对象实例的字符串。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [ExtendedCalendarKind](../../aspose.email.clients.google/extendedcalendar/extendedcalendarkind) | 资源类型“calendar#calendarListEntry”。 |
| const [ListKind](../../aspose.email.clients.google/extendedcalendar/listkind) | 资源列表类型“calendar#calendarList”. |

### 也可以看看

* class [Calendar](../calendar)
* 命名空间 [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
