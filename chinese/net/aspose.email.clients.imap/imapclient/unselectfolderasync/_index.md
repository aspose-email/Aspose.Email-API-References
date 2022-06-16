---
title: UnselectFolderAsync
second_title: Aspose.Email for .NET API 参考
description: 永久删除当前选定文件夹的所有标记为已删除的邮件并删除此文件夹的选定状态
type: docs
weight: 1260
url: /zh/net/aspose.email.clients.imap/imapclient/unselectfolderasync/
---
## UnselectFolderAsync(IConnection) {#unselectfolderasync_1}

永久删除当前选定文件夹的所有标记为已删除的邮件，并删除此文件夹的选定状态。

```csharp
public Task UnselectFolderAsync(IConnection connection)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |

### 返回值

任务对象，带委托对于这个操作

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## UnselectFolderAsync() {#unselectfolderasync}

永久删除当前选定文件夹的所有标记为已删除的邮件，并删除此文件夹的选定状态。

```csharp
public Task UnselectFolderAsync()
```

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, bool) {#unselectfolderasync_2}

取消选择当前选择的文件夹。 如果 doNotExpunge 属性为 true，则删除所有标记为已删除的消息，否则取消删除。 请注意，此操作仅适用于服务器支持 RFC3691 查看更多 https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(IConnection connection, bool doNotExpunge)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| doNotExpunge | Boolean | 指定是否应删除标记为已删除的消息。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## UnselectFolderAsync(bool) {#unselectfolderasync_5}

取消选择当前选择的文件夹。 如果 doNotExpunge 属性为 true，则删除所有标记为已删除的消息，否则取消删除。 请注意，此操作仅适用于服务器支持 RFC3691 查看更多 https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doNotExpunge | Boolean | 指定是否应删除标记为已删除的消息。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, CancellationToken) {#unselectfolderasync_4}

永久删除当前选定文件夹的所有标记为已删除的邮件，并删除此文件夹的选定状态。

```csharp
public Task UnselectFolderAsync(IConnection connection, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| token | CancellationToken | 传播通知应取消操作。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## UnselectFolderAsync(CancellationToken) {#unselectfolderasync_7}

永久删除当前选定文件夹的所有标记为已删除的邮件，并删除此文件夹的选定状态。

```csharp
public Task UnselectFolderAsync(CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, bool, CancellationToken) {#unselectfolderasync_3}

取消选择当前选择的文件夹。 如果 doNotExpunge 属性为 true，则删除所有标记为已删除的消息，否则取消删除。 请注意，此操作仅适用于服务器支持 RFC3691 查看更多 https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(IConnection connection, bool doNotExpunge, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| doNotExpunge | Boolean | 指定是否应删除标记为已删除的消息。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## UnselectFolderAsync(bool, CancellationToken) {#unselectfolderasync_6}

取消选择当前选择的文件夹。 如果 doNotExpunge 属性为 true，则删除所有标记为已删除的消息，否则取消删除。 请注意，此操作仅适用于服务器支持 RFC3691 查看更多 https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doNotExpunge | Boolean | 指定是否应删除标记为已删除的消息。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->