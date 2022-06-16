---
title: CopyMessages
second_title: Aspose.Email for .NET API 参考
description: 复制消息
type: docs
weight: 500
url: /zh/net/aspose.email.clients.imap/imapclient/copymessages/
---
## CopyMessages(IConnection, int, int, string) {#copymessages}

复制消息

```csharp
public void CopyMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| folderName | String | 要移动消息的文件夹名称 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CopyMessages(int, int, string) {#copymessages_5}

复制消息

```csharp
public void CopyMessages(int startSequence, int endSequence, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序列号 |
| endSequence | Int32 | 消息列表的结束序列号 |
| folderName | String | 消息所在的文件夹名称待移动 |

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CopyMessages(IConnection, string, string, string) {#copymessages_4}

复制消息

```csharp
public void CopyMessages(IConnection connection, string startUid, string endUid, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| folderName | String | 要移动消息的文件夹名称 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CopyMessages(string, string, string) {#copymessages_10}

复制消息

```csharp
public void CopyMessages(string startUid, string endUid, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| folderName | String | 消息所在的文件夹名称移动 |

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;int&gt;, string, bool) {#copymessages_8}

复制消息

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除. |

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CopyMessages(IConnection, IEnumerable&lt;int&gt;, string) {#copymessages_2}

复制消息

```csharp
public void CopyMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集合 |
| folderName | String | 要移动消息的文件夹名称 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;int&gt;, string) {#copymessages_7}

复制消息

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| folderName | String | 要移动消息的文件夹名称 |

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CopyMessages(IConnection, IEnumerable&lt;string&gt;, string) {#copymessages_3}

复制消息

```csharp
public void CopyMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| folderName | String | 要移动消息的文件夹名称 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;string&gt;, string) {#copymessages_9}

复制消息

```csharp
public void CopyMessages(IEnumerable<string> uidSet, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| folderName | String | 要移动消息的文件夹名称 |

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CopyMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_1}

复制消息

```csharp
public void CopyMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 集合 |
| folderName | String | 要移动消息的文件夹名称 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CopyMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_6}

复制邮件

```csharp
public void CopyMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 集合 |
| folderName | String | 要移动消息的文件夹名称 |

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
