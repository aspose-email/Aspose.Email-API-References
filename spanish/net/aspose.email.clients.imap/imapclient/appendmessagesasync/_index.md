---
title: AppendMessagesAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Sube los mensajes de correo a la carpeta actual
type: docs
weight: 390
url: /es/net/aspose.email.clients.imap/imapclient/appendmessagesasync/
---
## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_2}

Sube los mensajes de correo a la carpeta actual

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta que recibirá el mensaje de correo |
| messages | IEnumerable`1 | Enumeración de mensajes de correo electrónico para cargar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_4}

Carga el mensaje de correo en la carpeta actual Si no se ha especificado la carpeta actual, se utiliza la carpeta predeterminada.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messages | IEnumerable`1 | Enumeración de mensajes de correo electrónico para cargar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_6}

Sube los mensajes de correo a la carpeta actual

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta que recibirá el mensaje de correo |
| messages | IEnumerable`1 | Enumeración de mensajes de correo electrónico para cargar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_1}

Carga los mensajes de correo a la carpeta actual Si no se ha especificado la carpeta actual, se utiliza la carpeta predeterminada.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messages | IEnumerable`1 | Enumeración de mensajes de correo electrónico para cargar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_3}

Sube los mensajes de correo a la carpeta actual

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta que recibirá el mensaje de correo |
| messages | IEnumerable`1 | Enumeración de mensajes de correo electrónico para cargar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_5}

Carga el mensaje de correo en la carpeta actual Si no se ha especificado la carpeta actual, se utiliza la carpeta predeterminada.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messages | IEnumerable`1 | Enumeración de mensajes de correo electrónico para cargar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_7}

Sube los mensajes de correo a la carpeta actual

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta que recibirá el mensaje de correo |
| messages | IEnumerable`1 | Enumeración de mensajes de correo electrónico para cargar |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync}

Carga los mensajes de correo a la carpeta actual Si no se ha especificado la carpeta actual, se utiliza la carpeta predeterminada.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messages | IEnumerable`1 | Enumeración de mensajes de correo electrónico para cargar |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
