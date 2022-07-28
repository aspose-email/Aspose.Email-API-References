---
title: Restore
second_title: Aspose.Email for .NET API 参考
description: 从指定的个人存储文件恢复交换文件夹
type: docs
weight: 350
url: /zh/net/aspose.email.clients.exchange.dav/exchangeclient/restore/
---
## Restore(string, RestoreOptions) {#restore_5}

从指定的个人存储文件恢复交换文件夹。

```csharp
public void Restore(string fileName, RestoreOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 个人存储文件的路径。 |
| options | RestoreOptions | 恢复选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName*未指定。 |

### 也可以看看

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## Restore(Stream, RestoreOptions) {#restore_3}

从给定的个人存储中恢复交换文件夹。

```csharp
public void Restore(Stream stream, RestoreOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 包含个人存储的流。 |
| options | RestoreOptions | 恢复选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| NotSupportedException | 这*stream*不支持阅读。 |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream*是`无效的`. |

### 也可以看看

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## Restore(PersonalStorage, RestoreOptions) {#restore_1}

从给定的个人存储中恢复交换文件夹。

```csharp
public void Restore(PersonalStorage pst, RestoreOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pst | PersonalStorage | 包含备份 imap 文件夹的个人存储。 |
| options | RestoreOptions | 恢复选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst*是`无效的`. |

### 也可以看看

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## Restore(string, ExchangeFolderInfoCollection, RestoreOptions) {#restore_4}

从指定的个人存储文件恢复指定的交换文件夹。

```csharp
public void Restore(string fileName, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 个人存储文件的路径。 |
| folders | ExchangeFolderInfoCollection | 要恢复的文件夹。 |
| options | RestoreOptions | 恢复选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName*未指定。 |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders*是`无效的`. |

### 也可以看看

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## Restore(Stream, ExchangeFolderInfoCollection, RestoreOptions) {#restore_2}

从给定的个人存储中恢复指定的交换文件夹。

```csharp
public void Restore(Stream stream, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 包含个人存储的流。 |
| folders | ExchangeFolderInfoCollection | 要恢复的文件夹。 |
| options | RestoreOptions | 恢复选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| NotSupportedException | 这*stream*不支持阅读。 |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream*或者*folders*是`无效的`. |

### 也可以看看

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## Restore(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) {#restore}

从给定的个人存储中恢复指定的交换文件夹。

```csharp
public void Restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, 
    RestoreOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pst | PersonalStorage | 包含备份交换文件夹的个人存储。 |
| folders | ExchangeFolderInfoCollection | 要恢复的文件夹。 |
| options | RestoreOptions | 恢复选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst*或者*folders*是`无效的`. |

### 也可以看看

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
