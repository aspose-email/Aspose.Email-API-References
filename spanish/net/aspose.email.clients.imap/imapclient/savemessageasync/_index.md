---
title: SaveMessageAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un flujo proporcionado
type: docs
weight: 1100
url: /es/net/aspose.email.clients.imap/imapclient/savemessageasync/
---
## SaveMessageAsync(IConnection, int, Stream) {#savemessageasync}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un flujo proporcionado

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| resultStream | Stream | Stream que recibirá el mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream) {#savemessageasync_4}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un flujo proporcionado

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | La identificación única del mensaje |
| resultStream | Stream | Stream que recibirá el mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string) {#savemessageasync_6}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un archivo local

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | La identificación única del mensaje |
| fileName | String | La ruta del archivo local. Esto no puede ser un directorio. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string) {#savemessageasync_2}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un archivo local

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| fileName | String | La ruta del archivo local. Esto no puede ser un directorio. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream) {#savemessageasync_8}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un flujo proporcionado

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| resultStream | Stream | Stream que recibirá el mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream) {#savemessageasync_12}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un flujo proporcionado

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | La identificación única del mensaje |
| resultStream | Stream | Stream que recibirá el mensaje |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string) {#savemessageasync_14}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un archivo local

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | La identificación única del mensaje |
| fileName | String | La ruta del archivo local. Esto no puede ser un directorio. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string) {#savemessageasync_10}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un archivo local

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| fileName | String | La ruta del archivo local. Esto no puede ser un directorio. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream, CancellationToken) {#savemessageasync_1}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un flujo proporcionado

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| resultStream | Stream | Stream que recibirá el mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream, CancellationToken) {#savemessageasync_5}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un flujo proporcionado

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | La identificación única del mensaje |
| resultStream | Stream | Stream que recibirá el mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string, CancellationToken) {#savemessageasync_7}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un archivo local

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | La identificación única del mensaje |
| fileName | String | La ruta del archivo local. Esto no puede ser un directorio. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string, CancellationToken) {#savemessageasync_3}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un archivo local

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| fileName | String | La ruta del archivo local. Esto no puede ser un directorio. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream, CancellationToken) {#savemessageasync_9}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un flujo proporcionado

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| resultStream | Stream | Stream que recibirá el mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream, CancellationToken) {#savemessageasync_13}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un flujo proporcionado

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | La identificación única del mensaje |
| resultStream | Stream | Stream que recibirá el mensaje |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string, CancellationToken) {#savemessageasync_15}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un archivo local

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | La identificación única del mensaje |
| fileName | String | La ruta del archivo local. Esto no puede ser un directorio. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string, CancellationToken) {#savemessageasync_11}

Descarga el mensaje con el número de secuencia especificado y escribe sus datos en un archivo local

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| fileName | String | La ruta del archivo local. Esto no puede ser un directorio. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
