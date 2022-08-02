---
title: DeleteMessageAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Marca un mensaje con el número de secuencia especificado como eliminado
type: docs
weight: 570
url: /es/net/aspose.email.clients.imap/imapclient/deletemessageasync/
---
## DeleteMessageAsync(IConnection, int) {#deletemessageasync}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string) {#deletemessageasync_4}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(int) {#deletemessageasync_12}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string) {#deletemessageasync_16}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long) {#deletemessageasync_1}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long) {#deletemessageasync_7}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long) {#deletemessageasync_13}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long) {#deletemessageasync_19}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool) {#deletemessageasync_17}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool) {#deletemessageasync_5}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool) {#deletemessageasync_20}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool) {#deletemessageasync_8}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, CancellationToken) {#deletemessageasync_3}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, CancellationToken) {#deletemessageasync_11}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, CancellationToken) {#deletemessageasync_15}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_23}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long, CancellationToken) {#deletemessageasync_2}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, CancellationToken) {#deletemessageasync_10}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long, CancellationToken) {#deletemessageasync_14}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, CancellationToken) {#deletemessageasync_22}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool, CancellationToken) {#deletemessageasync_18}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool, CancellationToken) {#deletemessageasync_6}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool, CancellationToken) {#deletemessageasync_21}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool, CancellationToken) {#deletemessageasync_9}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
