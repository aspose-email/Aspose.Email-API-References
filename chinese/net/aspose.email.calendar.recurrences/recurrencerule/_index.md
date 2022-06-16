---
title: RecurrenceRule
second_title: Aspose.Email for .NET API 参考
description: 表示重复模式中的一个重复或异常规则
type: docs
weight: 770
url: /zh/net/aspose.email.calendar.recurrences/recurrencerule/
---
## RecurrenceRule class

表示重复模式中的一个重复或异常规则。

```csharp
public class RecurrenceRule
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RecurrenceRule](recurrencerule)() | 初始化[`RecurrenceRule`](../recurrencerule)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ByDay](../../aspose.email.calendar.recurrences/recurrencerule/byday) { get; } | 获取白天。 |
| [ByHour](../../aspose.email.calendar.recurrences/recurrencerule/byhour) { get; } | 获取小时。 |
| [ByMinute](../../aspose.email.calendar.recurrences/recurrencerule/byminute) { get; } | 获取每分钟。 |
| [ByMonth](../../aspose.email.calendar.recurrences/recurrencerule/bymonth) { get; } | 获取按月。 |
| [ByMonthDay](../../aspose.email.calendar.recurrences/recurrencerule/bymonthday) { get; } | 获取按月日。 |
| [BySecond](../../aspose.email.calendar.recurrences/recurrencerule/bysecond) { get; } | 获取秒数。 |
| [BySetPos](../../aspose.email.calendar.recurrences/recurrencerule/bysetpos) { get; } | 获取by set pos。 |
| [ByWeekNo](../../aspose.email.calendar.recurrences/recurrencerule/byweekno) { get; } | 获取按周编号。 |
| [ByYearDay](../../aspose.email.calendar.recurrences/recurrencerule/byyearday) { get; } | 获取年份。 |
| [Count](../../aspose.email.calendar.recurrences/recurrencerule/count) { get; set; } | 获取或设置计数。 |
| [EndType](../../aspose.email.calendar.recurrences/recurrencerule/endtype) { get; set; } | 获取或设置结束类型。 |
| [Frequency](../../aspose.email.calendar.recurrences/recurrencerule/frequency) { get; set; } | 获取或设置循环规则的类型。 |
| [FriendlyText](../../aspose.email.calendar.recurrences/recurrencerule/friendlytext) { get; } | 获取用户友好的规则文本。 |
| [Interval](../../aspose.email.calendar.recurrences/recurrencerule/interval) { get; set; } | 获取或设置间隔。 |
| [Until](../../aspose.email.calendar.recurrences/recurrencerule/until) { get; set; } | 获取或设置直到。 |
| [WeekStart](../../aspose.email.calendar.recurrences/recurrencerule/weekstart) { get; set; } | 获取或设置一周的开始日期。 |

### 评论

对应 iCalendar 中的 RRULE 或 EXRULE 部分。

要构造重复规则，您通常需要:

1. 指定[`Frequency`](./frequency)中的规则。

2. 使用[`EndType`](./endtype),指定重复模式如何结束 Count或[`Until`](./until)。

3. 在一个或多个 ByXXX 集合中指定值。

注意，如果发现 ByXXX 规则部分值超出了可用 范围（即，二月的 BYMONTHDAY=30），它们被简单地忽略了。

信息，不包含在规则中，需要确定各种重复实例 开始时间和日期是派生自[`StartDate`](../calendarrecurrence/startdate)。例如， "FREQ=YEARLY;BYMONTH=1" 不指定月份或时间中的特定日期。此信息 将与为 DTSTART 指定的信息相同。

ByXXX 规则部分以某种方式修改重复。 ByXXX 规则部分在一段时间内与 相同或大于频率一般会减少或限制 重复生成的出现次数。例如，“FREQ=DAILY;BYMONTH=1”将重复实例数 从所有天数（如果不存在 BYMONTH 标签）减少到一月的所有天数。 ByXXX 规则部分为 时间小于频率一般增加或扩大重复出现的次数。 例如，“FREQ=YEARLY;BYMONTH=1,2”将年度重复集 中的天数从 1（如果 BYMONTH 标签不存在）增加到 2 .

如果指定了多个 ByXXX 规则部分，则在评估指定的频率和间隔 规则部分后， ByXXX 规则部分应用于以下 顺序中的当前评估事件集:[`ByMonth`](./bymonth),[`ByWeekNo`](./byweekno),[`ByYearDay`](./byyearday),ByMonthDay, [`ByDay`](./byday),[`ByHour`](./byhour),[`ByMinute`](./byminute),[`BySecond`](./bysecond)和 [`BySetPos`](./bysetpos)；然后Count和[`Until`](./until)被评估。

### 也可以看看

* 命名空间 [Aspose.Email.Calendar.Recurrences](../../aspose.email.calendar.recurrences)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->