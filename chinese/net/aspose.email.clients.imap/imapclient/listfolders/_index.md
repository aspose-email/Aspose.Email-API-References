---
title: ListFolders
second_title: Aspose.Email for .NET API 参考
description: 获取邮箱中的文件夹列表
type: docs
weight: 830
url: /zh/net/aspose.email.clients.imap/imapclient/listfolders/
---
## ListFolders(IConnection) {#listfolders_1}

获取邮箱中的文件夹列表

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | Connection to服务器 |

### 返回值

ImapFolderInfo 对象集合

### 也可以看看

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListFolders(IConnection, string) {#listfolders_3}

获取指定文件夹中的子文件夹列表

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, string parentFolder)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | Connection到服务器 |
| parentFolder | String | 文件夹名称 |

### 返回值

ImapFolderInfo 对象集合

### 也可以看看

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListFolders(IConnection, bool) {#listfolders_2}

获取邮箱中的文件夹列表

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, bool loadFullInfo)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | Connection to服务器 |
| loadFullInfo | Boolean | 如果为 true 则表示应从服务器完整检索文件夹信息，否则仅检索文件夹名称。 |

### 返回值

ImapFolderInfo 对象集合

### 也可以看看

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListFolders() {#listfolders}

获取邮箱中的文件夹列表

```csharp
public ImapFolderInfoCollection ListFolders()
```

### 返回值

ImapFolderInfo 对象的集合

### 也可以看看

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListFolders(string) {#listfolders_7}

获取指定文件夹中的子文件夹列表

```csharp
public ImapFolderInfoCollection ListFolders(string parentFolder)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolder | String | Name文件夹 |

### 返回值

ImapFolderInfo 对象集合

### 也可以看看

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListFolders(bool) {#listfolders_6}

获取邮箱中的文件夹列表

```csharp
public ImapFolderInfoCollection ListFolders(bool loadFullInfo)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| loadFullInfo | Boolean | 如果为 true，则表示应从服务器完全检索文件夹信息，否则仅检索文件夹名称。 |

### 返回值

ImapFolderInfo 对象集合

### 也可以看看

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListFolders(string, bool) {#listfolders_8}

获取指定文件夹中的子文件夹列表

```csharp
public ImapFolderInfoCollection ListFolders(string parentFolder, bool loadFullInfo)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolder | String | Name文件夹的 |
| loadFullInfo | Boolean | 如果为 true，则应从服务器完全检索文件夹信息，否则仅检索文件夹名称。 |

### 返回值

ImapFolderInfo 对象集合

### 也可以看看

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListFolders(IConnection, string, bool) {#listfolders_4}

获取指定文件夹中的子文件夹列表

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, string parentFolder, 
    bool loadFullInfo)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | Connection到服务器 |
| parentFolder | String | 文件夹名称 |
| loadFullInfo | Boolean | 如果为 true，则表示应从服务器完全检索文件夹信息，否则仅检索文件夹名称。 |

### 返回值

ImapFolderInfo 对象集合

### 也可以看看

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListFolders(string, bool, ListFoldersOptions, ListFoldersReturnOptions) {#listfolders_9}

获取指定文件夹中的子文件夹列表

```csharp
public ImapFolderInfoCollection ListFolders(string parentFolder, bool loadFullInfo, 
    ListFoldersOptions options, ListFoldersReturnOptions returnOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolder | String | Name文件夹的 |
| loadFullInfo | Boolean | 如果为 true，则应从服务器完全检索文件夹信息，否则仅检索文件夹名称。 |
| options | ListFoldersOptions | 操作选项 |
| returnOptions | ListFoldersReturnOptions | 返回操作选项 |

### 返回值

ImapFolderInfo 对象集合

### 也可以看看

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListFolders(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) {#listfolders_5}

获取指定文件夹中的子文件夹列表

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, string parentFolder, 
    bool loadFullInfo, ListFoldersOptions options, ListFoldersReturnOptions returnOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | Connection到服务器 |
| parentFolder | String | 文件夹名称 |
| loadFullInfo | Boolean | 如果为 true 表示文件夹信息应该完全从服务器检索，否则只检索文件夹名称。 |
| options | ListFoldersOptions | 操作选项 |
| returnOptions | ListFoldersReturnOptions | 返回操作选项 |

### 返回值

ImapFolderInfo 对象集合

### 也可以看看

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
