---
title: MoveConversationItems
second_title: Aspose.Email for .NET API 参考
description: 将对话项目移动到指定的目标文件夹
type: docs
weight: 1280
url: /zh/net/aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems/
---
## MoveConversationItems(string, string) {#moveconversationitems}

将对话项目移动到指定的目标文件夹

```csharp
public void MoveConversationItems(string conversationId, string destinationFolderId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| conversationId | String | Id要删除的对话 |
| destinationFolderId | String | 将项目移动到其中的文件夹 ID |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId*是` null` 或` 空` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderId*is` null` 或` 空` |

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## MoveConversationItems(string, string, string) {#moveconversationitems_1}

将位于指定文件夹中的对话项移动到指定目标文件夹

```csharp
public void MoveConversationItems(string conversationId, string contextFolderId, 
    string destinationFolderId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| conversationId | String | 要移动的对话 ID |
| contextFolderId | String | 从中移动对话项目的文件夹 ID。注意:如果设置为 null（或为空），所有对话项目将被移动 |
| destinationFolderId | String | 移动项目的文件夹 ID |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId*是` null` 或` 空` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderId*is` null` 或` 空` |

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->