---
title: ListMessages
second_title: Referencia de la API de Aspose.Email para .NET
description: Lista los mensajes. Obtiene información para buscar el mensaje
type: docs
weight: 290
url: /es/net/aspose.email.clients.pop3/pop3client/listmessages/
---
## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_13}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<string> uniqueIdLst)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueIdLst | IEnumerable`1 | Lista de identificadores únicos para[`Pop3MessageInfo`](../../pop3messageinfo) para recuperar de un servidor. |

### Valor_devuelto

Pop3MessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;int&gt;) {#listmessages_12}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<int> sequenceNumberLst)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumberLst | IEnumerable`1 | lista de números de secuencia para[`Pop3MessageInfo`](../../pop3messageinfo) para recuperar de un servidor. |

### Valor_devuelto

Pop3MessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;string&gt;) {#listmessages_7}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<string> uniqueIdLst)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueIdLst | IEnumerable`1 | Lista de identificadores únicos para[`Pop3MessageInfo`](../../pop3messageinfo) para recuperar de un servidor. |

### Valor_devuelto

Pop3MessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;int&gt;) {#listmessages_6}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<int> sequenceNumberLst)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumberLst | IEnumerable`1 | lista de números de secuencia para[`Pop3MessageInfo`](../../pop3messageinfo) para recuperar de un servidor. |

### Valor_devuelto

Pop3MessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |

### Valor_devuelto

Pop3MessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_5}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, bool closeTransaction)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |

### Valor_devuelto

Pop3MessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_4}

Lista los mensajes.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| query | MailQuery | los[`MailQuery`](../../../aspose.email.tools.search/mailquery) objeto. |

### Valor_devuelto

Colección de objetos Pop3MessageInfo.

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, Pop3ListFields) {#listmessages_2}

Lista los mensajes.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| fields | Pop3ListFields | Los campos que queremos obtener |

### Valor_devuelto

Pop3MessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, Pop3ListFields, bool, MailQuery) {#listmessages_3}

Lista los mensajes.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| fields | Pop3ListFields | Los campos que queremos obtener |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |
| query | MailQuery | los[`MailQuery`](../../../aspose.email.tools.search/mailquery) objeto. |

### Valor_devuelto

Pop3MessageInfoCollection

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Pop3MessageInfoCollection ListMessages()
```

### Valor_devuelto

Pop3MessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_11}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Pop3MessageInfoCollection ListMessages(bool closeTransaction)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |

### Valor_devuelto

Pop3MessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_10}

Lista los mensajes.

```csharp
public Pop3MessageInfoCollection ListMessages(MailQuery query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| query | MailQuery | los[`MailQuery`](../../../aspose.email.tools.search/mailquery) objeto. |

### Valor_devuelto

Colección de objetos Pop3MessageInfo.

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields) {#listmessages_8}

Lista los mensajes.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fields | Pop3ListFields | Los campos que queremos obtener |

### Valor_devuelto

Pop3MessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields, bool, MailQuery) {#listmessages_9}

Lista los mensajes.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields, bool closeTransaction, 
    MailQuery query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fields | Pop3ListFields | Los campos que queremos obtener |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |
| query | MailQuery | los[`MailQuery`](../../../aspose.email.tools.search/mailquery) objeto. |

### Valor_devuelto

Pop3MessageInfoCollection

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
