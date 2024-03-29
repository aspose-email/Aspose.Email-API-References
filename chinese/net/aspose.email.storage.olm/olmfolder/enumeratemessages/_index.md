---
title: EnumerateMessages
second_title: Aspose.Email for .NET API 参考
description: 公开枚举器它支持文件夹中消息的迭代
type: docs
weight: 70
url: /zh/net/aspose.email.storage.olm/olmfolder/enumeratemessages/
---
## EnumerateMessages() {#enumeratemessages}

公开枚举器，它支持文件夹中消息的迭代。

```csharp
public IEnumerable<OlmMessageInfo> EnumerateMessages()
```

### 返回值

IEnumerable, 表示遍历文件夹中消息的枚举器。

### 也可以看看

* class [OlmMessageInfo](../../olmmessageinfo)
* class [OlmFolder](../../olmfolder)
* 命名空间 [Aspose.Email.Storage.Olm](../../olmfolder)
* 部件 [Aspose.Email](../../../)

---

## EnumerateMessages(int, int) {#enumeratemessages_2}

公开枚举器，它支持文件夹中消息的迭代。

```csharp
public IEnumerable<OlmMessageInfo> EnumerateMessages(int startIndex, int count)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | Int32 | 开始消息索引。 |
| count | Int32 | 将检索的消息数。 |

### 返回值

IEnumerable, 表示遍历文件夹中消息的枚举器。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | 如果 startIndex 小于 0，则抛出。 |
| ArgumentOutOfRangeException | 如果 startIndex 大于或等于该文件夹包含的总消息数，则抛出。 |

### 评论

如果“count”参数小于 0 或大于剩余消息计数，则将返回剩余消息计数。

### 也可以看看

* class [OlmMessageInfo](../../olmmessageinfo)
* class [OlmFolder](../../olmfolder)
* 命名空间 [Aspose.Email.Storage.Olm](../../olmfolder)
* 部件 [Aspose.Email](../../../)

---

## EnumerateMessages(MailQuery) {#enumeratemessages_1}

公开枚举器，它支持文件夹中消息的迭代。

```csharp
public IEnumerable<OlmMessageInfo> EnumerateMessages(MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |

### 返回值

IEnumerable, 表示遍历文件夹中消息的枚举器。

### 也可以看看

* class [OlmMessageInfo](../../olmmessageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [OlmFolder](../../olmfolder)
* 命名空间 [Aspose.Email.Storage.Olm](../../olmfolder)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
