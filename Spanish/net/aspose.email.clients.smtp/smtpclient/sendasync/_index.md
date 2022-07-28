---
title: SendAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Crea y envía el mensaje especificado.
type: docs
weight: 180
url: /es/net/aspose.email.clients.smtp/smtpclient/sendasync/
---
## SendAsync(string, string, string, string) {#sendasync_18}

Crea y envía el mensaje especificado.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| from | String | Una cadena que contiene la dirección del remitente del mensaje. |
| recipients | String | Una cadena que contiene la dirección de los destinatarios. |
| subject | String | Un asunto de mensaje. |
| body | String | Un cuerpo de mensaje. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(MailMessage) {#sendasync_11}

Enviar el mensaje especificado.

```csharp
public Task SendAsync(MailMessage message)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| message | MailMessage | El MailMessage que representa un mensaje de correo electrónico. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(params MailMessage[]) {#sendasync_15}

Enviar el mensaje especificado.

```csharp
public Task SendAsync(params MailMessage[] messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messages | MailMessage[] | La matriz de MailMessage que representa un mensaje de correo electrónico para enviar. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection) {#sendasync_13}

Enviar la colección de mensajes especificada.

```csharp
public Task SendAsync(MailMessageCollection messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messages | MailMessageCollection | La colección de mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;) {#sendasync_16}

Envía los mensajes especificados.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messages | IEnumerable`1 | El IEnumerator que admite una iteración de mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string) {#sendasync_7}

Crea y envía el mensaje especificado.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| from | String | Una cadena que contiene la dirección del remitente del mensaje. |
| recipients | String | Una cadena que contiene la dirección de los destinatarios. |
| subject | String | Un asunto de mensaje. |
| body | String | Un cuerpo de mensaje. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage) {#sendasync}

Enviar el mensaje especificado.

```csharp
public Task SendAsync(IConnection connection, MailMessage message)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| message | MailMessage | El MailMessage que representa un mensaje de correo electrónico. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, params MailMessage[]) {#sendasync_4}

Enviar el mensaje especificado.

```csharp
public Task SendAsync(IConnection connection, params MailMessage[] messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messages | MailMessage[] | La matriz de MailMessage que representa un mensaje de correo electrónico para enviar. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection) {#sendasync_2}

Enviar la colección de mensajes especificada.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messages | MailMessageCollection | La colección de mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#sendasync_5}

Envía los mensajes especificados.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messages | IEnumerable`1 | El IEnumerator que admite una iteración de mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(string, string, string, string, CancellationToken) {#sendasync_19}

Crea y envía el mensaje especificado.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| from | String | Una cadena que contiene la dirección del remitente del mensaje. |
| recipients | String | Una cadena que contiene la dirección de los destinatarios. |
| subject | String | Un asunto de mensaje. |
| body | String | Un cuerpo de mensaje. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(MailMessage, CancellationToken) {#sendasync_12}

Enviar el mensaje especificado.

```csharp
public Task SendAsync(MailMessage message, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| message | MailMessage | El MailMessage que representa un mensaje de correo electrónico. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(CancellationToken, params MailMessage[]) {#sendasync_20}

Enviar el mensaje especificado.

```csharp
public Task SendAsync(CancellationToken token, params MailMessage[] messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |
| messages | MailMessage[] | La matriz de MailMessage que representa un mensaje de correo electrónico para enviar. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection, CancellationToken) {#sendasync_14}

Enviar la colección de mensajes especificada.

```csharp
public Task SendAsync(MailMessageCollection messages, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messages | MailMessageCollection | La colección de mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_17}

Envía los mensajes especificados.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messages | IEnumerable`1 | El IEnumerator que admite una iteración de mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string, CancellationToken) {#sendasync_8}

Crea y envía el mensaje especificado.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| from | String | Una cadena que contiene la dirección del remitente del mensaje. |
| recipients | String | Una cadena que contiene la dirección de los destinatarios. |
| subject | String | Un asunto de mensaje. |
| body | String | Un cuerpo de mensaje. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage, CancellationToken) {#sendasync_1}

Enviar el mensaje especificado.

```csharp
public Task SendAsync(IConnection connection, MailMessage message, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| message | MailMessage | El MailMessage que representa un mensaje de correo electrónico. |
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

## SendAsync(IConnection, CancellationToken, params MailMessage[]) {#sendasync_9}

Enviar el mensaje especificado.

```csharp
public Task SendAsync(IConnection connection, CancellationToken token, 
    params MailMessage[] messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |
| messages | MailMessage[] | La matriz de MailMessage que representa un mensaje de correo electrónico para enviar. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection, CancellationToken) {#sendasync_3}

Enviar la colección de mensajes especificada.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messages | MailMessageCollection | La colección de mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_6}

Envía los mensajes especificados.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messages | IEnumerable`1 | El IEnumerator que admite una iteración de mensajes. |
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

## SendAsync(SmtpSend) {#sendasync_10}

```csharp
public Task SendAsync(SmtpSend parameters)
```

### Ver también

* class [SmtpSend](../../../aspose.email.clients.smtp.models/smtpsend)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
