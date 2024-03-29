---
title: CreateConnection
second_title: Aspose.Email for .NET API 参考
description: 为未链接到线程的操作非默认连接创建新的独立连接 调用此方法类似于调用 CreateConnectioncreateAsDefaultConnection  false 请参阅 EmailClient.ConnectionAsgmtMode 属性的文档中的更多信息
type: docs
weight: 280
url: /zh/net/aspose.email.clients/emailclient/createconnection/
---
## CreateConnection() {#createconnection}

为未链接到线程的操作（非默认连接）创建新的独立连接。 调用此方法类似于调用 CreateConnection(createAsDefaultConnection = false) 请参阅 EmailClient.ConnectionAsgmtMode 属性的文档中的更多信息。

```csharp
public virtual IConnection CreateConnection()
```

### 返回值

返回连接对象

### 也可以看看

* interface [IConnection](../../iconnection)
* class [EmailClient](../../emailclient)
* 命名空间 [Aspose.Email.Clients](../../emailclient)
* 部件 [Aspose.Email](../../../)

---

## CreateConnection(bool) {#createconnection_1}

为操作创建新的（默认或独立的）连接。 请参阅 EmailClient.ConnectionAsgmtMode 属性的文档中的更多信息。

```csharp
public virtual IConnection CreateConnection(bool createAsDefaultConnection)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createAsDefaultConnection | Boolean | 指示是否必须为当前线程默认创建连接 |

### 返回值

返回连接对象

### 也可以看看

* interface [IConnection](../../iconnection)
* class [EmailClient](../../emailclient)
* 命名空间 [Aspose.Email.Clients](../../emailclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
