---
title: ListMessagesAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Lista los mensajes. Obtiene información para buscar el mensaje
type: docs
weight: 300
url: /es/net/aspose.email.clients.pop3/pop3client/listmessagesasync/
---
## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_8}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_6}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
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

## ListMessagesAsync(IConnection, Pop3ListFields) {#listmessagesasync_2}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| fields | Pop3ListFields | Los campos que queremos obtener |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

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

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery) {#listmessagesasync_3}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| fields | Pop3ListFields | Los campos que queremos obtener |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |
| query | MailQuery | los[`MailQuery`](../../../aspose.email.tools.search/mailquery) objeto. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync()
```

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_17}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_15}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query)
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

## ListMessagesAsync(Pop3ListFields) {#listmessagesasync_11}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fields | Pop3ListFields | Los campos que queremos obtener |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery) {#listmessagesasync_12}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fields | Pop3ListFields | Los campos que queremos obtener |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |
| query | MailQuery | los[`MailQuery`](../../../aspose.email.tools.search/mailquery) objeto. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_10}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_9}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_7}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| query | MailQuery | los[`MailQuery`](../../../aspose.email.tools.search/mailquery) objeto. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

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

## ListMessagesAsync(IConnection, Pop3ListFields, CancellationToken) {#listmessagesasync_5}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| fields | Pop3ListFields | Los campos que queremos obtener |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

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

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_4}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| fields | Pop3ListFields | Los campos que queremos obtener |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |
| query | MailQuery | los[`MailQuery`](../../../aspose.email.tools.search/mailquery) objeto. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_19}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_18}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_16}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| query | MailQuery | los[`MailQuery`](../../../aspose.email.tools.search/mailquery) objeto. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Colección de objetos Pop3MessageInfo.

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, CancellationToken) {#listmessagesasync_14}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fields | Pop3ListFields | Los campos que queremos obtener |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_13}

Lista los mensajes.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fields | Pop3ListFields | Los campos que queremos obtener |
| closeTransaction | Boolean | Indica si se debe cerrar la transacción actual antes de recuperar la lista. |
| query | MailQuery | los[`MailQuery`](../../../aspose.email.tools.search/mailquery) objeto. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
