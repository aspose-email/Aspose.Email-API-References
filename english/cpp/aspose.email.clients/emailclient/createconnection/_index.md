---
title: "Aspose::Email::Clients::EmailClient::CreateConnection method"
linktitle: "CreateConnection"
articleTitle: "CreateConnection"
second_title: "Aspose.Email for C++"
description: "Creates new independent connection for operations not linked to threads (not default connection)."
type: docs
weight: 30
url: /cpp/aspose.email.clients/emailclient/createconnection/
---

## CreateConnection (1 of 2) {#createconnection_1}

Creates new independent connection for operations not linked to threads (not default connection). Invocation of this method is similar to invocation of CreateConnection(createAsDefaultConnection = false) Please see more in documentation for EmailClient.ConnectionAsgmtMode property.

**Returns:** Returns connection object

```cpp
CreateConnection()
```

---

## CreateConnection (2 of 2) {#createconnection_2}

Creates new (default or independent) connection for operations. Please see more in documentation for EmailClient.ConnectionAsgmtMode property.

**Returns:** Returns connection object

```cpp
CreateConnection(bool createAsDefaultConnection)
```

| Parameter | Description |
| --- | --- |
| createAsDefaultConnection | Indicates if connection has to be created as default for current thread |

