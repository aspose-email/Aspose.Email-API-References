---
title: DeleteMessageAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Borra el mensaje
type: docs
weight: 80
url: /es/net/aspose.email.clients.pop3/pop3client/deletemessageasync/
---
## DeleteMessageAsync(IConnection, int) {#deletemessageasync}

Borra el mensaje

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

El servidor POP3 marca el mensaje como eliminado. El servidor POP3 en realidad no elimina el mensaje hasta que la sesión POP3 ingresa al estado ACTUALIZAR.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string) {#deletemessageasync_2}

Borra el mensaje

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | La identificación única del mensaje. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

El servidor POP3 marca el mensaje como eliminado. El servidor POP3 en realidad no elimina el mensaje hasta que la sesión POP3 ingresa al estado ACTUALIZAR.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(int) {#deletemessageasync_4}

Borra el mensaje

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

El servidor POP3 marca el mensaje como eliminado. El servidor POP3 en realidad no elimina el mensaje hasta que la sesión POP3 ingresa al estado ACTUALIZAR.

### Ver también

* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string) {#deletemessageasync_6}

Borra el mensaje

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | La identificación única del mensaje. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

El servidor POP3 marca el mensaje como eliminado. El servidor POP3 en realidad no elimina el mensaje hasta que la sesión POP3 ingresa al estado ACTUALIZAR.

### Ver también

* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, CancellationToken) {#deletemessageasync_1}

Borra el mensaje

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

El servidor POP3 marca el mensaje como eliminado. El servidor POP3 en realidad no elimina el mensaje hasta que la sesión POP3 ingresa al estado ACTUALIZAR.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, CancellationToken) {#deletemessageasync_3}

Borra el mensaje

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | La identificación única del mensaje. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

El servidor POP3 marca el mensaje como eliminado. El servidor POP3 en realidad no elimina el mensaje hasta que la sesión POP3 ingresa al estado ACTUALIZAR.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, CancellationToken) {#deletemessageasync_5}

Borra el mensaje

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | El número de secuencia del mensaje. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

El servidor POP3 marca el mensaje como eliminado. El servidor POP3 en realidad no elimina el mensaje hasta que la sesión POP3 ingresa al estado ACTUALIZAR.

### Ver también

* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_7}

Borra el mensaje

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | La identificación única del mensaje. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Observaciones

El servidor POP3 marca el mensaje como eliminado. El servidor POP3 en realidad no elimina el mensaje hasta que la sesión POP3 ingresa al estado ACTUALIZAR.

### Ver también

* class [Pop3Client](../../pop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../pop3client)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
