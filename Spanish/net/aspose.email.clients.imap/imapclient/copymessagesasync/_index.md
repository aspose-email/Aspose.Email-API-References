---
title: CopyMessagesAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Copie el mensaje
type: docs
weight: 510
url: /es/net/aspose.email.clients.imap/imapclient/copymessagesasync/
---
## CopyMessagesAsync(IConnection, int, int, string) {#copymessagesasync}

Copie el mensaje

```csharp
public Task CopyMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(int, int, string) {#copymessagesasync_10}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(int startSequence, int endSequence, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, string, string, string) {#copymessagesasync_8}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(string, string, string) {#copymessagesasync_19}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(string startUid, string endUid, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string) {#copymessagesasync_4}

Copie el mensaje

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;int&gt;, string) {#copymessagesasync_14}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IEnumerable<int> sequenceSet, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string) {#copymessagesasync_6}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;string&gt;, string) {#copymessagesasync_17}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IEnumerable<string> uidSet, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessagesasync_2}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessagesasync_12}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, int, int, string, CancellationToken) {#copymessagesasync_1}

Copie el mensaje

```csharp
public Task CopyMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(int, int, string, CancellationToken) {#copymessagesasync_11}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(int startSequence, int endSequence, string folderName, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, string, string, string, CancellationToken) {#copymessagesasync_9}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(string, string, string, CancellationToken) {#copymessagesasync_20}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(string startUid, string endUid, string folderName, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) {#copymessagesasync_5}

Copie el mensaje

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;int&gt;, string, CancellationToken) {#copymessagesasync_16}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) {#copymessagesasync_7}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;string&gt;, string, CancellationToken) {#copymessagesasync_18}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IEnumerable<string> uidSet, string folderName, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#copymessagesasync_3}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
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

## CopyMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#copymessagesasync_13}

Copiar mensajes

```csharp
public Task CopyMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
