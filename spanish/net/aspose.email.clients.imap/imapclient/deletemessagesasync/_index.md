---
title: DeleteMessagesAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Marca un mensaje con el identificador único especificado como eliminado
type: docs
weight: 590
url: /es/net/aspose.email.clients.imap/imapclient/deletemessagesasync/
---
## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessagesasync_19}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long) {#deletemessagesasync_45}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long) {#deletemessagesasync_51}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_49}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_17}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_52}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_20}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
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

## DeleteMessagesAsync(IConnection, int, int) {#deletemessagesasync}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string) {#deletemessagesasync_24}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid)
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

## DeleteMessagesAsync(int, int) {#deletemessagesasync_32}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string) {#deletemessagesasync_56}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid)
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

## DeleteMessagesAsync(IConnection, int, int, long) {#deletemessagesasync_1}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long) {#deletemessagesasync_27}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long) {#deletemessagesasync_33}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long) {#deletemessagesasync_59}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool) {#deletemessagesasync_57}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool) {#deletemessagesasync_25}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool) {#deletemessagesasync_60}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool) {#deletemessagesasync_28}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_4}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_36}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_7}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_39}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_37}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_5}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_40}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_8}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_15}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_23}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_47}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_55}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_14}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_22}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
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

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_46}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_54}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_50}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_18}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
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

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_53}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_21}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
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

---

## DeleteMessagesAsync(IConnection, int, int, CancellationToken) {#deletemessagesasync_3}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, CancellationToken) {#deletemessagesasync_31}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
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

---

## DeleteMessagesAsync(int, int, CancellationToken) {#deletemessagesasync_35}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, CancellationToken) {#deletemessagesasync_63}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, CancellationToken token)
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

## DeleteMessagesAsync(IConnection, int, int, long, CancellationToken) {#deletemessagesasync_2}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
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

## DeleteMessagesAsync(IConnection, string, string, long, CancellationToken) {#deletemessagesasync_30}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
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

## DeleteMessagesAsync(int, int, long, CancellationToken) {#deletemessagesasync_34}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, CancellationToken) {#deletemessagesasync_62}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool, CancellationToken) {#deletemessagesasync_58}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool, CancellationToken) {#deletemessagesasync_26}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
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

## DeleteMessagesAsync(string, string, long, bool, CancellationToken) {#deletemessagesasync_61}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
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

## DeleteMessagesAsync(IConnection, string, string, long, bool, CancellationToken) {#deletemessagesasync_29}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
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

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_11}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_43}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_10}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_42}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_38}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_6}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_41}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_9}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#deletemessagesasync_12}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#deletemessagesasync_16}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;) {#deletemessagesasync_44}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;) {#deletemessagesasync_48}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessagesasync_13}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
