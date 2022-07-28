---
title: DeleteMessage
second_title: Aspose.Email for .NET API 参考
description: 将具有指定序列号的消息标记为已删除
type: docs
weight: 560
url: /zh/net/aspose.email.clients.imap/imapclient/deletemessage/
---
## DeleteMessage(IConnection, int) {#deletemessage}

将具有指定序列号的消息标记为已删除

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string) {#deletemessage_2}

将具有指定序列号的消息标记为已删除

```csharp
public void DeleteMessage(IConnection connection, string uniqueId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessage(int) {#deletemessage_6}

将具有指定序列号的消息标记为已删除

```csharp
public void DeleteMessage(int sequenceNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessage(string) {#deletemessage_8}

将具有指定序列号的消息标记为已删除

```csharp
public void DeleteMessage(string uniqueId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, int, long) {#deletemessage_1}

将具有指定序列号的消息标记为已删除

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long) {#deletemessage_4}

将具有指定唯一标识符的消息标记为已删除

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessage(int, long) {#deletemessage_7}

将具有指定序列号的消息标记为已删除

```csharp
public void DeleteMessage(int sequenceNumber, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessage(string, long) {#deletemessage_10}

将具有指定唯一标识符的消息标记为已删除

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessage(string, bool) {#deletemessage_9}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, bool) {#deletemessage_3}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessage(string, long, bool) {#deletemessage_11}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long, bool) {#deletemessage_5}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
