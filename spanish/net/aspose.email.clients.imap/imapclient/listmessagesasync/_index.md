---
title: ListMessagesAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Obtiene la lista de mensajes en la carpeta actual.
type: docs
weight: 880
url: /es/net/aspose.email.clients.imap/imapclient/listmessagesasync/
---
## ListMessagesAsync(int, CancellationToken) {#listmessagesasync_28}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* es negativo |

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_17}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta para recuperar mensajes. |
| modificationSequence | Int64 | Secuencia de modificación |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |
| messageExtraFields | IEnumerable`1 | Lista de parámetros extra para un mensaje que será solicitado. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string) {#listmessagesasync_12}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta para recuperar mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_6}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long) {#listmessagesasync_10}

Obtiene la lista de mensajes en la carpeta actual que tienen una secuencia de modificación mayor que el valor especificado. Consulte más https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| modificationSequence | Int64 | Secuencia de modificación |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool) {#listmessagesasync_15}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta para recuperar mensajes. |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync()
```

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;) {#listmessagesasync_31}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Lista de parámetros extra para un mensaje que será solicitado. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_25}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string) {#listmessagesasync_33}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool) {#listmessagesasync_36}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_37}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |
| messageExtraFields | IEnumerable`1 | Lista de parámetros extra para un mensaje que será solicitado. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(long) {#listmessagesasync_29}

Obtiene la lista de mensajes en la carpeta actual que tienen una secuencia de modificación mayor que el valor especificado. Consulte más https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| modificationSequence | Int64 | Secuencia de modificación |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int) {#listmessagesasync_13}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Ubicación de los mensajes |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_2}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int) {#listmessagesasync_3}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_21}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int) {#listmessagesasync_34}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Ubicación de los mensajes |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int) {#listmessagesasync_22}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int) {#listmessagesasync_8}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* es negativo |

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(int) {#listmessagesasync_27}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* es negativo |

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_18}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta para recuperar mensajes. |
| modificationSequence | Int64 | Secuencia de modificación |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |
| messageExtraFields | IEnumerable`1 | Lista de parámetros extra para un mensaje que será solicitado. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_20}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, CancellationToken) {#listmessagesasync_19}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta para recuperar mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_7}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long, CancellationToken) {#listmessagesasync_11}

Obtiene la lista de mensajes en la carpeta actual que tienen una secuencia de modificación mayor que el valor especificado. Consulte más https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| modificationSequence | Int64 | Secuencia de modificación |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool, CancellationToken) {#listmessagesasync_16}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta para recuperar mensajes. |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_41}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_32}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Lista de parámetros extra para un mensaje que será solicitado. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_26}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, CancellationToken) {#listmessagesasync_40}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, CancellationToken) {#listmessagesasync_39}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_38}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |
| messageExtraFields | IEnumerable`1 | Lista de parámetros extra para un mensaje que será solicitado. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(long, CancellationToken) {#listmessagesasync_30}

Obtiene la lista de mensajes en la carpeta actual que tienen una secuencia de modificación mayor que el valor especificado. Consulte más https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| modificationSequence | Int64 | Secuencia de modificación |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int, CancellationToken) {#listmessagesasync_14}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Ubicación de los mensajes |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_5}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int, CancellationToken) {#listmessagesasync_4}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_24}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int, CancellationToken) {#listmessagesasync_35}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Ubicación de los mensajes |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int, CancellationToken) {#listmessagesasync_23}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa la consulta de búsqueda. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Colección de objetos ImapMessageInfo.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int, CancellationToken) {#listmessagesasync_9}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* es negativo |

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
