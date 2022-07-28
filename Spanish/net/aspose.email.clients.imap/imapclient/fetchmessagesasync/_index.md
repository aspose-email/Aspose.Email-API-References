---
title: FetchMessagesAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Obtiene los mensajes de forma asíncrona
type: docs
weight: 680
url: /es/net/aspose.email.clients.imap/imapclient/fetchmessagesasync/
---
## FetchMessagesAsync(IEnumerable&lt;int&gt;) {#fetchmessagesasync_4}

Obtiene los mensajes de forma asíncrona

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<int> sequenceNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumbers | IEnumerable`1 | Los números de secuencia de los mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;string&gt;) {#fetchmessagesasync_6}

Obtiene los mensajes de forma asíncrona

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<string> uids)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uids | IEnumerable`1 | Los números de secuencia de los mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#fetchmessagesasync}

Obtiene los mensajes de forma asíncrona

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<int> sequenceNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumbers | IEnumerable`1 | Los números de secuencia de los mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#fetchmessagesasync_2}

Obtiene los mensajes de forma asíncrona

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, IEnumerable<string> uids)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uids | IEnumerable`1 | Los números de secuencia de los mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#fetchmessagesasync_5}

Obtiene los mensajes de forma asíncrona

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<int> sequenceNumbers, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumbers | IEnumerable`1 | Los números de secuencia de los mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#fetchmessagesasync_7}

Obtiene los mensajes de forma asíncrona

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<string> uids, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uids | IEnumerable`1 | Los números de secuencia de los mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#fetchmessagesasync_1}

Obtiene los mensajes de forma asíncrona

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<int> sequenceNumbers, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumbers | IEnumerable`1 | Los números de secuencia de los mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#fetchmessagesasync_3}

Obtiene los mensajes de forma asíncrona

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<string> uids, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uids | IEnumerable`1 | Los números de secuencia de los mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
