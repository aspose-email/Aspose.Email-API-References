---
title: GenerateOccurrences
second_title: Aspose.Email for .NET API 参考
description: 生成事件
type: docs
weight: 110
url: /zh/net/aspose.email.calendar.recurrences/calendarrecurrence/generateoccurrences/
---
## GenerateOccurrences() {#generateoccurrences}

生成事件。

```csharp
public DateCollection GenerateOccurrences()
```

### 返回值

日期集合[`DateCollection`](../../datecollection).

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| Exception | 如果未设置 StartDate，则抛出。 |

### 也可以看看

* class [DateCollection](../../datecollection)
* class [CalendarRecurrence](../../calendarrecurrence)
* 命名空间 [Aspose.Email.Calendar.Recurrences](../../calendarrecurrence)
* 部件 [Aspose.Email](../../../)

---

## GenerateOccurrences(int) {#generateoccurrences_1}

生成 n 次下一个事件。

```csharp
public DateCollection GenerateOccurrences(int nNextOccurrences)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| nNextOccurrences | Int32 | 需要发生的次数。 |

### 返回值

日期集合[`DateCollection`](../../datecollection).

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| Exception | 如果未设置 StartDate，则抛出。 |
| ArgumentOutOfRangeException | 如果所需事件的数量小于或等于零，则抛出。 |

### 也可以看看

* class [DateCollection](../../datecollection)
* class [CalendarRecurrence](../../calendarrecurrence)
* 命名空间 [Aspose.Email.Calendar.Recurrences](../../calendarrecurrence)
* 部件 [Aspose.Email](../../../)

---

## GenerateOccurrences(DateTime, DateTime) {#generateoccurrences_2}

生成事件。

```csharp
public DateCollection GenerateOccurrences(DateTime rangeStart, DateTime rangeEnd)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rangeStart | DateTime | 范围开始。 |
| rangeEnd | DateTime | 范围结束。 |

### 返回值

日期集合[`DateCollection`](../../datecollection).

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| Exception | 如果未设置 StartDate 则抛出 |

### 也可以看看

* class [DateCollection](../../datecollection)
* class [CalendarRecurrence](../../calendarrecurrence)
* 命名空间 [Aspose.Email.Calendar.Recurrences](../../calendarrecurrence)
* 部件 [Aspose.Email](../../../)

---

## GenerateOccurrences(DateTime, DateTime, int) {#generateoccurrences_3}

生成 n 次下一个事件。

```csharp
public DateCollection GenerateOccurrences(DateTime rangeStart, DateTime rangeEnd, 
    int nNextOccurrences)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rangeStart | DateTime | 范围开始。 |
| rangeEnd | DateTime | 范围结束。 |
| nNextOccurrences | Int32 | 需要发生的次数。 |

### 返回值

日期集合[`DateCollection`](../../datecollection).

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| Exception | 如果未设置 StartDate，则抛出。 |
| ArgumentOutOfRangeException | 如果所需事件的数量小于或等于零，则抛出。 |

### 也可以看看

* class [DateCollection](../../datecollection)
* class [CalendarRecurrence](../../calendarrecurrence)
* 命名空间 [Aspose.Email.Calendar.Recurrences](../../calendarrecurrence)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
