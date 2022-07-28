---
title: ListMessages
second_title: Aspose.Email for .NET API 参考
description: 列出消息 获取搜索消息的信息
type: docs
weight: 870
url: /zh/net/aspose.email.clients.imap/imapclient/listmessages/
---
## ListMessages(string, ImapListFields, int) {#listmessages_21}

列出消息。 获取搜索消息的信息

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, ImapListFields fieldsList, 
    int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |
| fieldsList | ImapListFields | 可以从服务器检索的字段。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |

### 返回值

ImapMessageInfoCollection

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, ImapListFields, int) {#listmessages_8}

列出消息。 获取搜索消息的信息

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    ImapListFields fieldsList, int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 用于检索消息的文件夹。 |
| fieldsList | ImapListFields | 可以从服务器检索的字段。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |

### 返回值

ImapMessageInfoCollection

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;string&gt;) {#listmessages_26}

列出消息。 获取搜索消息的信息

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<string> uniqueIdLst)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |
| uniqueIdLst | IEnumerable`1 | UniqueId 列表[`ImapMessageInfo`](../../imapmessageinfo)从服务器检索。 |

### 返回值

ImapMessageInfoCollection

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;int&gt;) {#listmessages_25}

列出消息。 获取搜索消息的信息

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<int> sequenceNumberLst)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |
| sequenceNumberLst | IEnumerable`1 | 序列号列表[`ImapMessageInfo`](../../imapmessageinfo)从服务器检索。 |

### 返回值

ImapMessageInfoCollection

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;string&gt;) {#listmessages_13}

列出消息。 获取搜索消息的信息

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<string> uniqueIdLst)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 用于检索消息的文件夹。 |
| uniqueIdLst | IEnumerable`1 | UniqueId 列表[`ImapMessageInfo`](../../imapmessageinfo)从服务器检索。 |

### 返回值

ImapMessageInfoCollection

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;int&gt;) {#listmessages_12}

列出消息。 获取搜索消息的信息

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<int> sequenceNumberLst)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 用于检索消息的文件夹。 |
| sequenceNumberLst | IEnumerable`1 | 序列号列表[`ImapMessageInfo`](../../imapmessageinfo)从服务器检索。 |

### 返回值

ImapMessageInfoCollection

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessages_11}

获取指定文件夹中的邮件列表

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
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

ImapMessageInfo 对象的集合

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

获取当前文件夹中的邮件列表

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |

### 返回值

ImapMessageInfo 对象的集合

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, string) {#listmessages_7}

获取指定文件夹中的邮件列表

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 用于检索消息的文件夹。 |

### 返回值

ImapMessageInfo 对象的集合

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_4}

获取当前文件夹中的邮件列表

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, bool retrieveRecursively)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |

### 返回值

ImapMessageInfo 对象的集合

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, long) {#listmessages_6}

获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| modificationSequence | Int64 | 修改顺序 |

### 返回值

收集[`ImapMessageInfo`](../../imapmessageinfo)表示消息信息。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, bool) {#listmessages_10}

获取指定文件夹中的邮件列表

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 用于检索消息的文件夹。 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |

### 返回值

ImapMessageInfo 对象的集合

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

获取当前文件夹中的邮件列表

```csharp
public ImapMessageInfoCollection ListMessages()
```

### 返回值

ImapMessageInfo 对象的集合

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_19}

获取当前文件夹中的邮件列表

```csharp
public ImapMessageInfoCollection ListMessages(IEnumerable<string> messageExtraFields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |

### 返回值

ImapMessageInfo 对象的集合

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_16}

获取当前文件夹中的邮件列表

```csharp
public ImapMessageInfoCollection ListMessages(bool retrieveRecursively)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |

### 返回值

ImapMessageInfo 对象的集合

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string) {#listmessages_20}

获取指定文件夹中的邮件列表

```csharp
public ImapMessageInfoCollection ListMessages(string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |

### 返回值

ImapMessageInfo 对象的集合

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_23}

获取指定文件夹中的邮件列表

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |

### 返回值

ImapMessageInfo 对象的集合

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, bool, IEnumerable&lt;string&gt;) {#listmessages_24}

获取指定文件夹中的邮件列表

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively, 
    IEnumerable<string> messageExtraFields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 用于检索消息的文件夹。 |
| retrieveRecursively | Boolean | 指示是否必须递归检索消息。 |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |

### 返回值

ImapMessageInfo 对象的集合

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(long) {#listmessages_18}

获取当前文件夹中修改序列大于指定值的邮件列表。 请查看更多 https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| modificationSequence | Int64 | 修改顺序 |

### 返回值

收集[`ImapMessageInfo`](../../imapmessageinfo)表示消息信息。

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, MailQuery, int) {#listmessages_9}

获取当前文件夹中的邮件列表。

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
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

## ListMessages(IConnection, MailQuery) {#listmessages_2}

获取当前文件夹中的邮件列表。

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query)
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

## ListMessages(IConnection, MailQuery, int) {#listmessages_3}

获取当前文件夹中的邮件列表。

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query, 
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

## ListMessages(MailQuery) {#listmessages_14}

获取当前文件夹中的邮件列表。

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query)
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

## ListMessages(string, MailQuery, int) {#listmessages_22}

获取当前文件夹中的邮件列表。

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, MailQuery query, 
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

## ListMessages(MailQuery, int) {#listmessages_15}

获取当前文件夹中的邮件列表。

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query, int maxNumberOfMessages)
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

## ListMessages(IConnection, int) {#listmessages_5}

获取当前文件夹中的邮件列表。

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| maxNumberOfMessages | Int32 | 最大消息数。 |

### 返回值

收集[`ImapMessageInfo`](../../imapmessageinfo)表示消息信息。

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

## ListMessages(int) {#listmessages_17}

获取当前文件夹中的邮件列表。

```csharp
public ImapMessageInfoCollection ListMessages(int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | 最大消息数。 |

### 返回值

收集[`ImapMessageInfo`](../../imapmessageinfo)表示消息信息。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages*是负数。 |

### 也可以看看

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
