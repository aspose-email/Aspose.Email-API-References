---
title: ExtendedCalendar
second_title: Aspose.Email for .NET API 参考
description: 初始化 ExtendedCalendar 类的新实例
type: docs
weight: 10
url: /zh/net/aspose.email.clients.google/extendedcalendar/extendedcalendar/
---
## ExtendedCalendar() {#constructor}

初始化 ExtendedCalendar 类的新实例。

```csharp
public ExtendedCalendar()
```

### 也可以看看

* class [ExtendedCalendar](../../extendedcalendar)
* 命名空间 [Aspose.Email.Clients.Google](../../extendedcalendar)
* 部件 [Aspose.Email](../../../)

---

## ExtendedCalendar(string) {#constructor_1}

初始化 ExtendedCalendar 类的新实例。

```csharp
public ExtendedCalendar(string summary)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| summary | String | 日历的标题。 |

### 也可以看看

* class [ExtendedCalendar](../../extendedcalendar)
* 命名空间 [Aspose.Email.Clients.Google](../../extendedcalendar)
* 部件 [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string) {#constructor_2}

初始化 ExtendedCalendar 类的新实例。

```csharp
public ExtendedCalendar(string id, string summary)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| id | String | 资源的标识符。 |
| summary | String | 日历的标题。 |

### 也可以看看

* class [ExtendedCalendar](../../extendedcalendar)
* 命名空间 [Aspose.Email.Clients.Google](../../extendedcalendar)
* 部件 [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string) {#constructor_3}

初始化 ExtendedCalendar 类的新实例。

```csharp
public ExtendedCalendar(string summary, string description, string location, string timeZone)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| summary | String | 日历的标题。 |
| description | String | 日历的说明。 |
| location | String | 日历的地理位置为自由格式文本。 |
| timeZone | String | 日历的时区。 |

### 也可以看看

* class [ExtendedCalendar](../../extendedcalendar)
* 命名空间 [Aspose.Email.Clients.Google](../../extendedcalendar)
* 部件 [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string) {#constructor_4}

初始化 ExtendedCalendar 类的新实例。

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| id | String | 资源的标识符。 |
| summary | String | 日历的标题。 |
| description | String | 日历的说明。 |
| location | String | 日历的地理位置为自由格式文本。 |
| timeZone | String | 日历的时区。 |

### 也可以看看

* class [ExtendedCalendar](../../extendedcalendar)
* 命名空间 [Aspose.Email.Clients.Google](../../extendedcalendar)
* 部件 [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_5}

初始化 ExtendedCalendar 类的新实例。

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone, string summaryOverride, string colorId, string backgroundColor, 
    string foregroundColor, bool hidden, bool selected, AccessRole accessRole, 
    KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| id | String | 资源的标识符。 |
| summary | String | 日历的标题。 |
| description | String | 日历的说明。 |
| location | String | 日历的地理位置为自由格式文本。 |
| timeZone | String | 日历的时区。 |
| summaryOverride | String | 经过身份验证的用户为此日历设置的摘要。 |
| colorId | String | 日历的颜色。这是一个 ID，指的是颜色定义的“日历”部分中的条目（请参阅“颜色”端点）。 |
| backgroundColor | String | 日历的主颜色，格式为“#0088aa”。此属性取代了基于索引的 colorId 属性。 |
| foregroundColor | String | 日历的前景色，格式为“#ffffff”。此属性取代了基于索引的 colorId 属性。 |
| hidden | Boolean | 日历是否已从列表中隐藏。默认值为假。 |
| selected | Boolean | 日历内容是否显示在日历 UI 中。默认值为假。 |
| accessRole | AccessRole | 经过身份验证的用户在日历上的有效访问角色。只读。可能的值为： |
| defaultReminders | KeyValuePair`2[] | 经过身份验证的用户对此日历的默认提醒。 |
| primary | Boolean | 日历是否是经过身份验证的用户的主日历。只读。默认值为假。 |

### 也可以看看

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* 命名空间 [Aspose.Email.Clients.Google](../../extendedcalendar)
* 部件 [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_6}

初始化 ExtendedCalendar 类的新实例。

```csharp
public ExtendedCalendar(string id, string eTag, string summary, string description, 
    string location, string timeZone, string summaryOverride, string colorId, 
    string backgroundColor, string foregroundColor, bool hidden, bool selected, 
    AccessRole accessRole, KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| id | String | 资源的标识符。 |
| eTag | String | 实体标签 |
| summary | String | 日历的标题。 |
| description | String | 日历的说明。 |
| location | String | 日历的地理位置为自由格式文本。 |
| timeZone | String | 日历的时区。 |
| summaryOverride | String | 经过身份验证的用户为此日历设置的摘要。 |
| colorId | String | 日历的颜色。这是一个 ID，指的是颜色定义的“日历”部分中的条目（请参阅“颜色”端点）。 |
| backgroundColor | String | 日历的主颜色，格式为“#0088aa”。此属性取代了基于索引的 colorId 属性。 |
| foregroundColor | String | 日历的前景色，格式为“#ffffff”。此属性取代了基于索引的 colorId 属性。 |
| hidden | Boolean | 日历是否已从列表中隐藏。默认值为假。 |
| selected | Boolean | 日历内容是否显示在日历 UI 中。默认值为假。 |
| accessRole | AccessRole | 经过身份验证的用户在日历上的有效访问角色。只读。可能的值为： |
| defaultReminders | KeyValuePair`2[] | 经过身份验证的用户对此日历的默认提醒。 |
| primary | Boolean | 日历是否是经过身份验证的用户的主日历。只读。默认值为假。 |

### 也可以看看

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* 命名空间 [Aspose.Email.Clients.Google](../../extendedcalendar)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
