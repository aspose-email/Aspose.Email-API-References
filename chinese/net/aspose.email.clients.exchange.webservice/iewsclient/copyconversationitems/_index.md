---
title: CopyConversationItems
second_title: Aspose.Email for .NET API 参考
description: 将对话项复制到指定的目标文件夹
type: docs
weight: 440
url: /zh/net/aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems/
---
## CopyConversationItems(string, string) {#copyconversationitems}

将对话项复制到指定的目标文件夹

```csharp
public void CopyConversationItems(string conversationId, string destinationFolderId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| conversationId | String | Id要复制的对话 |
| destinationFolderId | String | 复制项目的文件夹 ID |

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

## CopyConversationItems(string, string, string) {#copyconversationitems_1}

将位于指定文件夹中的会话项复制到指定目标文件夹

```csharp
public void CopyConversationItems(string conversationId, string contextFolderId, 
    string destinationFolderId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| conversationId | String | 要复制的对话 ID |
| contextFolderId | String | 对话项目所在文件夹的 ID。注意:如果设置为 null（或为空），将复制所有对话项目 |
| destinationFolderId | String | 复制项目所在文件夹的 ID |

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