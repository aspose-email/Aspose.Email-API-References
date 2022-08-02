---
title: AddMessageFlagsAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Agrega las banderas del mensaje
type: docs
weight: 350
url: /es/net/aspose.email.clients.imap/imapclient/addmessageflagsasync/
---
## AddMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_35}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_27}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| flags | ImapMessageFlags | Las banderas a cambiar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_7}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_54}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_34}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_26}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_6}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_47}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| flags | ImapMessageFlags | Las banderas a cambiar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_43}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_19}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| flags | ImapMessageFlags | Las banderas a cambiar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_15}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_46}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_42}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_18}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_14}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_39}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| flags | ImapMessageFlags | Las banderas a cambiar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_11}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| flags | ImapMessageFlags | Las banderas a cambiar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_38}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_10}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#addmessageflagsasync}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| flags | ImapMessageFlags | Las banderas que se añadirán |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#addmessageflagsasync_20}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | Identificador único de un mensaje |
| flags | ImapMessageFlags | Las banderas que se añadirán |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags) {#addmessageflagsasync_28}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| flags | ImapMessageFlags | Las banderas que se añadirán |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags) {#addmessageflagsasync_48}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | Identificador único de un mensaje |
| flags | ImapMessageFlags | Las banderas que se añadirán |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#addmessageflagsasync_1}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#addmessageflagsasync_21}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | Identificador único de un mensaje |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, long) {#addmessageflagsasync_29}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, long) {#addmessageflagsasync_49}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | Identificador único de un mensaje |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags) {#addmessageflagsasync_52}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| flags | ImapMessageFlags | Las banderas a cambiar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags) {#addmessageflagsasync_32}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#addmessageflagsasync_24}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| flags | ImapMessageFlags | Las banderas a cambiar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#addmessageflagsasync_4}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, long) {#addmessageflagsasync_53}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags, long) {#addmessageflagsasync_33}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#addmessageflagsasync_25}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#addmessageflagsasync_5}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#addmessageflagsasync_44}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| flags | ImapMessageFlags | Las banderas a cambiar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#addmessageflagsasync_40}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#addmessageflagsasync_16}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| flags | ImapMessageFlags | Las banderas a cambiar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#addmessageflagsasync_12}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#addmessageflagsasync_45}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#addmessageflagsasync_41}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#addmessageflagsasync_17}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#addmessageflagsasync_13}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| flags | ImapMessageFlags | Las banderas a quitar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#addmessageflagsasync_36}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| flags | ImapMessageFlags | Las banderas a cambiar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#addmessageflagsasync_8}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| flags | ImapMessageFlags | Las banderas a cambiar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#addmessageflagsasync_37}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#addmessageflagsasync_9}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| flags | ImapMessageFlags | Las banderas a cambiar |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_3}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_23}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | Identificador único de un mensaje |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_31}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_51}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | Identificador único de un mensaje |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_2}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_22}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | Identificador único de un mensaje |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_30}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_50}

Agrega las banderas al mensaje

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | Identificador único de un mensaje |
| flags | ImapMessageFlags | Las banderas que se añadirán |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_55}

Agrega las banderas del mensaje

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| flags | ImapMessageFlags | Las banderas a cambiar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
