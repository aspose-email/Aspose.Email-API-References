---
title: Send
second_title: Aspose.Email for .NET API 参考
description: 在草稿文件夹中发送消息 草稿消息可以是新消息草稿回复草稿全部回复草稿或转发草稿 然后将消息保存在已发送邮件文件夹中
type: docs
weight: 360
url: /zh/net/aspose.email.clients.graph/igraphclient/send/
---
## Send(string) {#send_2}

在草稿文件夹中发送消息。 草稿消息可以是新消息草稿、回复草稿、全部回复草稿或转发草稿。 然后将消息保存在已发送邮件文件夹中。

```csharp
public void Send(string itemId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| itemId | String | 草稿消息的项目 ID |

### 也可以看看

* interface [IGraphClient](../../igraphclient)
* 命名空间 [Aspose.Email.Clients.Graph](../../igraphclient)
* 部件 [Aspose.Email](../../../)

---

## Send(MapiMessage) {#send}

发送电子邮件消息

```csharp
public void Send(MapiMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | MapiMessage | 要发送的 Mapi 消息 |

### 也可以看看

* class [MapiMessage](../../../aspose.email.mapi/mapimessage)
* interface [IGraphClient](../../igraphclient)
* 命名空间 [Aspose.Email.Clients.Graph](../../igraphclient)
* 部件 [Aspose.Email](../../../)

---

## Send(MapiMessage, bool) {#send_1}

发送电子邮件消息

```csharp
public void Send(MapiMessage message, bool saveToSentItems)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | MapiMessage | 要发送的 Mapi 消息 |
| saveToSentItems | Boolean | 指示是否将消息保存在已发送项目中。 |

### 也可以看看

* class [MapiMessage](../../../aspose.email.mapi/mapimessage)
* interface [IGraphClient](../../igraphclient)
* 命名空间 [Aspose.Email.Clients.Graph](../../igraphclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
