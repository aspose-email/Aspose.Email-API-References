---
title: MoveMessageAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Mueve el mensaje
type: docs
weight: 940
url: /es/net/aspose.email.clients.imap/imapclient/movemessageasync/
---
## MoveMessageAsync(int, string, bool) {#movemessageasync_9}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool) {#movemessageasync_13}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string) {#movemessageasync}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string) {#movemessageasync_4}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string) {#movemessageasync_8}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string) {#movemessageasync_12}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool, CancellationToken) {#movemessageasync_2}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool, CancellationToken) {#movemessageasync_6}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, bool, CancellationToken) {#movemessageasync_10}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool, CancellationToken) {#movemessageasync_14}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, CancellationToken) {#movemessageasync_3}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
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

## MoveMessageAsync(IConnection, string, string, CancellationToken) {#movemessageasync_7}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
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

## MoveMessageAsync(int, string, CancellationToken) {#movemessageasync_11}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, CancellationToken) {#movemessageasync_15}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool) {#movemessageasync_1}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool) {#movemessageasync_5}

Mueve el mensaje

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
