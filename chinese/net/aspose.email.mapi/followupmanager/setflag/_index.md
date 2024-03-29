---
title: SetFlag
second_title: Aspose.Email for .NET API 参考
description: 设置消息的后续标志
type: docs
weight: 120
url: /zh/net/aspose.email.mapi/followupmanager/setflag/
---
## SetFlag(MapiMessage, string) {#setflag}

设置消息的后续标志。

```csharp
public static void SetFlag(MapiMessage message, string flagRequest)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | MapiMessage | 这[`MapiMessage`](../../mapimessage)其中将设置一个标志。 |
| flagRequest | String | 一个字符串，指示请求的电子邮件消息的 操作。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果*flagRequest*为空或为空。 |
| ArgumentNullException | 如果*message*一片空白。 |

### 也可以看看

* class [MapiMessage](../../mapimessage)
* class [FollowUpManager](../../followupmanager)
* 命名空间 [Aspose.Email.Mapi](../../followupmanager)
* 部件 [Aspose.Email](../../../)

---

## SetFlag(MapiMessage, string, DateTime, DateTime) {#setflag_1}

设置消息的后续标志。

```csharp
public static void SetFlag(MapiMessage message, string flagRequest, DateTime startDate, 
    DateTime dueDate)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | MapiMessage | 这[`MapiMessage`](../../mapimessage)其中将设置一个标志。 |
| flagRequest | String | 一个字符串，指示请求的电子邮件消息的 操作。 |
| startDate | DateTime | 开始日期。 |
| dueDate | DateTime | 截止日期。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果*flagRequest*为空或为空。 |
| ArgumentNullException | 如果*message*一片空白。 |

### 也可以看看

* class [MapiMessage](../../mapimessage)
* class [FollowUpManager](../../followupmanager)
* 命名空间 [Aspose.Email.Mapi](../../followupmanager)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
