---
title: Send
second_title: Referencia de la API de Aspose.Email para .NET
description: Crea y envía el mensaje especificado.
type: docs
weight: 170
url: /es/net/aspose.email.clients.smtp/smtpclient/send/
---
## Send(string, string, string, string) {#send_9}

Crea y envía el mensaje especificado.

```csharp
public void Send(string from, string recipients, string subject, string body)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| from | String | Una cadena que contiene la dirección del remitente del mensaje. |
| recipients | String | Una cadena que contiene la dirección de los destinatarios. |
| subject | String | Un asunto de mensaje. |
| body | String | Un cuerpo de mensaje. |

### Ver también

* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## Send(MailMessage) {#send_5}

Enviar el mensaje especificado.

```csharp
public void Send(MailMessage message)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| message | MailMessage | El MailMessage que representa un mensaje de correo electrónico. |

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## Send(params MailMessage[]) {#send_7}

Enviar el mensaje especificado.

```csharp
public void Send(params MailMessage[] messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messages | MailMessage[] | La matriz de MailMessage que representa un mensaje de correo electrónico para enviar. |

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## Send(MailMessageCollection) {#send_6}

Enviar la colección de mensajes especificada.

```csharp
public void Send(MailMessageCollection messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messages | MailMessageCollection | La colección de mensajes. |

### Ver también

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## Send(IEnumerable&lt;MailMessage&gt;) {#send_8}

Envía los mensajes especificados.

```csharp
public void Send(IEnumerable<MailMessage> messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messages | IEnumerable`1 | El IEnumerator que admite una iteración de mensajes. |

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## Send(IConnection, string, string, string, string) {#send_4}

Crea y envía el mensaje especificado.

```csharp
public void Send(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| from | String | Una cadena que contiene la dirección del remitente del mensaje. |
| recipients | String | Una cadena que contiene la dirección de los destinatarios. |
| subject | String | Un asunto de mensaje. |
| body | String | Un cuerpo de mensaje. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## Send(IConnection, MailMessage) {#send}

Enviar el mensaje especificado.

```csharp
public void Send(IConnection connection, MailMessage message)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| message | MailMessage | El MailMessage que representa un mensaje de correo electrónico. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## Send(IConnection, params MailMessage[]) {#send_2}

Enviar el mensaje especificado.

```csharp
public void Send(IConnection connection, params MailMessage[] messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messages | MailMessage[] | La matriz de MailMessage que representa un mensaje de correo electrónico para enviar. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## Send(IConnection, MailMessageCollection) {#send_1}

Enviar la colección de mensajes especificada.

```csharp
public void Send(IConnection connection, MailMessageCollection messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messages | MailMessageCollection | La colección de mensajes. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

---

## Send(IConnection, IEnumerable&lt;MailMessage&gt;) {#send_3}

Envía los mensajes especificados.

```csharp
public void Send(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messages | IEnumerable`1 | El IEnumerator que admite una iteración de mensajes. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../smtpclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
