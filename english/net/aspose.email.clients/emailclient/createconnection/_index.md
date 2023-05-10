---
title: EmailClient.CreateConnection
second_title: Aspose.Email for .NET API Reference
description: EmailClient method. Creates new independent connection for operations not linked to threads not default connection. Invocation of this method is similar to invocation of CreateConnectioncreateAsDefaultConnection  false Please see more in documentation for EmailClient.ConnectionAsgmtMode property
type: docs
weight: 280
url: /net/aspose.email.clients/emailclient/createconnection/
---
## CreateConnection() {#createconnection}

Creates new independent connection for operations not linked to threads (not default connection). Invocation of this method is similar to invocation of CreateConnection(createAsDefaultConnection = false) Please see more in documentation for EmailClient.ConnectionAsgmtMode property.

```csharp
public virtual IConnection CreateConnection()
```

### Return Value

Returns connection object

### See Also

* interface [IConnection](../../iconnection/)
* class [EmailClient](../)
* namespace [Aspose.Email.Clients](../../emailclient/)
* assembly [Aspose.Email](../../../)

---

## CreateConnection(bool) {#createconnection_1}

Creates new (default or independent) connection for operations. Please see more in documentation for EmailClient.ConnectionAsgmtMode property.

```csharp
public virtual IConnection CreateConnection(bool createAsDefaultConnection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createAsDefaultConnection | Boolean | Indicates if connection has to be created as default for current thread |

### Return Value

Returns connection object

### See Also

* interface [IConnection](../../iconnection/)
* class [EmailClient](../)
* namespace [Aspose.Email.Clients](../../emailclient/)
* assembly [Aspose.Email](../../../)


