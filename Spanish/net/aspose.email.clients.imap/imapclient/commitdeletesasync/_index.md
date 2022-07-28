---
title: CommitDeletesAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Confirmar las eliminaciones
type: docs
weight: 470
url: /es/net/aspose.email.clients.imap/imapclient/commitdeletesasync/
---
## CommitDeletesAsync(IConnection) {#commitdeletesasync_1}

Confirmar las eliminaciones

```csharp
public Task CommitDeletesAsync(IConnection connection)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int) {#commitdeletesasync_2}

Confirmar las eliminaciones

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sleep | Int32 | Tiempo de espera para completar la operación en milisegundos |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync() {#commitdeletesasync}

Confirmar las eliminaciones

```csharp
public Task CommitDeletesAsync()
```

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(int) {#commitdeletesasync_11}

Confirmar las eliminaciones

```csharp
public Task CommitDeletesAsync(int sleep)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sleep | Int32 | Tiempo de espera para completar la operación en milisegundos |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;) {#commitdeletesasync_13}

Confirmar las eliminaciones Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Conjunto de identificadores únicos para mensajes |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(string) {#commitdeletesasync_15}

Confirmar las eliminaciones Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid de un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, string) {#commitdeletesasync_16}

Confirmar las eliminaciones Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;) {#commitdeletesasync_4}

Confirmar las eliminaciones Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | Conjunto de identificadores únicos para mensajes |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string) {#commitdeletesasync_6}

Confirmar las eliminaciones

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid de un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, string) {#commitdeletesasync_7}

Confirmar las eliminaciones Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, CancellationToken) {#commitdeletesasync_10}

Confirmar las eliminaciones

```csharp
public Task CommitDeletesAsync(IConnection connection, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int, CancellationToken) {#commitdeletesasync_3}

Confirmar las eliminaciones

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sleep | Int32 | Tiempo de espera para completar la operación en milisegundos |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(CancellationToken) {#commitdeletesasync_19}

Confirmar las eliminaciones

```csharp
public Task CommitDeletesAsync(CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(int, CancellationToken) {#commitdeletesasync_12}

Confirmar las eliminaciones

```csharp
public Task CommitDeletesAsync(int sleep, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sleep | Int32 | Tiempo de espera para completar la operación en milisegundos |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_14}

Confirmar las eliminaciones Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Conjunto de identificadores únicos para mensajes |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, CancellationToken) {#commitdeletesasync_18}

Confirmar las eliminaciones Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid de un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, string, CancellationToken) {#commitdeletesasync_17}

Confirmar las eliminaciones Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_5}

Confirmar las eliminaciones Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | Conjunto de identificadores únicos para mensajes |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, CancellationToken) {#commitdeletesasync_9}

Confirmar las eliminaciones

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid de un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, string, CancellationToken) {#commitdeletesasync_8}

Confirmar las eliminaciones Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
