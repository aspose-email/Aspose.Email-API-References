---
title: ForwardAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Reenvía el mensaje especificado al destinatario
type: docs
weight: 140
url: /es/net/aspose.email.clients.smtp/smtpclient/forwardasync/
---
## ForwardAsync(IConnection, string, string, MailMessage) {#forwardasync_4}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sender | String | Remitente del mensaje reenviado. |
| recipient | String | Destinatario del mensaje reenviado. |
| message | MailMessage | El mensaje para un reenvío. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage) {#forwardasync}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sender | String | Remitente del mensaje reenviado. |
| recipients | MailAddressCollection | Destinatarios del mensaje reenviado. |
| message | MailMessage | El mensaje para un reenvío. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage) {#forwardasync_10}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sender | String | Remitente del mensaje reenviado. |
| recipient | String | Destinatario del mensaje reenviado. |
| message | MailMessage | El mensaje para un reenvío. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage) {#forwardasync_6}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sender | String | Remitente del mensaje reenviado. |
| recipients | MailAddressCollection | Destinatarios del mensaje reenviado. |
| message | MailMessage | El mensaje para un reenvío. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream) {#forwardasync_2}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sender | String | Remitente del mensaje reenviado. |
| recipients | MailAddressCollection | Destinatarios del mensaje reenviado. |
| messageStream | Stream | El flujo que representa el mensaje en formato eml. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream) {#forwardasync_8}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sender | String | Remitente del mensaje reenviado. |
| recipients | MailAddressCollection | Destinatarios del mensaje reenviado. |
| messageStream | Stream | El flujo que representa el mensaje en formato eml. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, string, MailMessage, CancellationToken) {#forwardasync_5}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sender | String | Remitente del mensaje reenviado. |
| recipient | String | Destinatario del mensaje reenviado. |
| message | MailMessage | El mensaje para un reenvío. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_1}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sender | String | Remitente del mensaje reenviado. |
| recipients | MailAddressCollection | Destinatarios del mensaje reenviado. |
| message | MailMessage | El mensaje para un reenvío. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage, CancellationToken) {#forwardasync_11}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sender | String | Remitente del mensaje reenviado. |
| recipient | String | Destinatario del mensaje reenviado. |
| message | MailMessage | El mensaje para un reenvío. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_7}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sender | String | Remitente del mensaje reenviado. |
| recipients | MailAddressCollection | Destinatarios del mensaje reenviado. |
| message | MailMessage | El mensaje para un reenvío. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_3}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sender | String | Remitente del mensaje reenviado. |
| recipients | MailAddressCollection | Destinatarios del mensaje reenviado. |
| messageStream | Stream | El flujo que representa el mensaje en formato eml. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_9}

Reenvía el mensaje especificado al destinatario

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sender | String | Remitente del mensaje reenviado. |
| recipients | MailAddressCollection | Destinatarios del mensaje reenviado. |
| messageStream | Stream | El flujo que representa el mensaje en formato eml. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
