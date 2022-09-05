---
title: ListMessagesAsync
second_title: Aspose.Email for .NET API 参考
description: 获取当前文件夹中的邮件列表
type: docs
weight: 880
url: /zh/net/aspose.email.clients.imap/imapclient/listmessagesasync/
---
## ListMessagesAsync(int, CancellationToken) {#listmessagesasync_28}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | 最大消息数。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages*是负数。 |

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_17}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 用于检索消息的文件夹。 |
| modificationSequence | Int64 | 修改顺序 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection) {#listmessagesasync_1}

获取当前文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string) {#listmessagesasync_12}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 用于检索消息的文件夹。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_6}

获取当前文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long) {#listmessagesasync_10}

获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| modificationSequence | Int64 | 修改顺序 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool) {#listmessagesasync_15}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 用于检索消息的文件夹。 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

获取当前文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync()
```

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;) {#listmessagesasync_31}

获取当前文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_25}

获取当前文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(string) {#listmessagesasync_33}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool) {#listmessagesasync_36}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_37}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(long) {#listmessagesasync_29}

获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| modificationSequence | Int64 | 修改顺序 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int) {#listmessagesasync_13}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 消息位置 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_2}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int) {#listmessagesasync_3}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_21}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int) {#listmessagesasync_34}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 消息位置 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int) {#listmessagesasync_22}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int) {#listmessagesasync_8}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| maxNumberOfMessages | Int32 | 最大消息数。 |

### 返回值

任务对象，具有此操作的委托

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages*是负数。 |

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(int) {#listmessagesasync_27}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | 最大消息数。 |

### 返回值

任务对象，具有此操作的委托

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages*是负数。 |

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_18}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 用于检索消息的文件夹。 |
| modificationSequence | Int64 | 修改顺序 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_20}

获取当前文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, CancellationToken) {#listmessagesasync_19}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 用于检索消息的文件夹。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_7}

获取当前文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long, CancellationToken) {#listmessagesasync_11}

获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| modificationSequence | Int64 | 修改顺序 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool, CancellationToken) {#listmessagesasync_16}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 用于检索消息的文件夹。 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_41}

获取当前文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_32}

获取当前文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_26}

获取当前文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(string, CancellationToken) {#listmessagesasync_40}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, CancellationToken) {#listmessagesasync_39}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_38}

获取指定文件夹中的邮件列表

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(long, CancellationToken) {#listmessagesasync_30}

获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| modificationSequence | Int64 | 修改顺序 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int, CancellationToken) {#listmessagesasync_14}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 消息位置 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_5}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int, CancellationToken) {#listmessagesasync_4}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_24}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int, CancellationToken) {#listmessagesasync_35}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 消息位置 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int, CancellationToken) {#listmessagesasync_23}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索查询。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

ImapMessageInfo 对象的集合。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int, CancellationToken) {#listmessagesasync_9}

获取当前文件夹中的邮件列表。

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| maxNumberOfMessages | Int32 | 最大消息数。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages*是负数。 |

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
