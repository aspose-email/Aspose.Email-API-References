---
title: ListMessages
second_title: Referencia de la API de Aspose.Email para .NET
description: Lista los mensajes. Obtiene información para buscar el mensaje
type: docs
weight: 870
url: /es/net/aspose.email.clients.imap/imapclient/listmessages/
---
## ListMessages(string, ImapListFields, int) {#listmessages_21}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, ImapListFields fieldsList, 
    int maxNumberOfMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |
| fieldsList | ImapListFields | Campos que se pueden recuperar del servidor. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |

### Valor_devuelto

ImapMessageInfoCollectionImapMessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, ImapListFields, int) {#listmessages_8}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    ImapListFields fieldsList, int maxNumberOfMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta para recuperar mensajes. |
| fieldsList | ImapListFields | Campos que se pueden recuperar del servidor. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |

### Valor_devuelto

ImapMessageInfoCollectionImapMessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;string&gt;) {#listmessages_26}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<string> uniqueIdLst)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |
| uniqueIdLst | IEnumerable`1 | Lista de identificadores únicos para[`ImapMessageInfo`](../../imapmessageinfo) para recuperar de un servidor. |

### Valor_devuelto

ImapMessageInfoCollectionImapMessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;int&gt;) {#listmessages_25}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<int> sequenceNumberLst)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |
| sequenceNumberLst | IEnumerable`1 | lista de números de secuencia para[`ImapMessageInfo`](../../imapmessageinfo) para recuperar de un servidor. |

### Valor_devuelto

ImapMessageInfoCollectionImapMessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;string&gt;) {#listmessages_13}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<string> uniqueIdLst)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta para recuperar mensajes. |
| uniqueIdLst | IEnumerable`1 | Lista de identificadores únicos para[`ImapMessageInfo`](../../imapmessageinfo) para recuperar de un servidor. |

### Valor_devuelto

ImapMessageInfoCollectionImapMessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;int&gt;) {#listmessages_12}

Lista los mensajes. Obtiene información para buscar el mensaje

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<int> sequenceNumberLst)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta para recuperar mensajes. |
| sequenceNumberLst | IEnumerable`1 | lista de números de secuencia para[`ImapMessageInfo`](../../imapmessageinfo) para recuperar de un servidor. |

### Valor_devuelto

ImapMessageInfoCollectionImapMessageInfoCollection

### Observaciones

Tenga en cuenta que los mensajes marcados como eliminados no aparecen en la lista

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessages_11}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
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

Colección de objetos ImapMessageInfo

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |

### Valor_devuelto

Colección de objetos ImapMessageInfo

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string) {#listmessages_7}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta para recuperar mensajes. |

### Valor_devuelto

Colección de objetos ImapMessageInfo

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_4}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, bool retrieveRecursively)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |

### Valor_devuelto

Colección de objetos ImapMessageInfo

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, long) {#listmessages_6}

Obtiene la lista de mensajes en la carpeta actual que tienen una secuencia de modificación mayor que el valor especificado. Consulte más https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| modificationSequence | Int64 | Secuencia de modificación |

### Valor_devuelto

Colección de[`ImapMessageInfo`](../../imapmessageinfo) que representa la información de los mensajes.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, bool) {#listmessages_10}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| folderName | String | Carpeta para recuperar mensajes. |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |

### Valor_devuelto

Colección de objetos ImapMessageInfo

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public ImapMessageInfoCollection ListMessages()
```

### Valor_devuelto

Colección de objetos ImapMessageInfo

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_19}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public ImapMessageInfoCollection ListMessages(IEnumerable<string> messageExtraFields)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Lista de parámetros extra para un mensaje que será solicitado. |

### Valor_devuelto

Colección de objetos ImapMessageInfo

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_16}

Obtiene la lista de mensajes en la carpeta actual

```csharp
public ImapMessageInfoCollection ListMessages(bool retrieveRecursively)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |

### Valor_devuelto

Colección de objetos ImapMessageInfo

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string) {#listmessages_20}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public ImapMessageInfoCollection ListMessages(string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |

### Valor_devuelto

Colección de objetos ImapMessageInfo

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_23}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |

### Valor_devuelto

Colección de objetos ImapMessageInfo

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, bool, IEnumerable&lt;string&gt;) {#listmessages_24}

Obtiene la lista de mensajes en la carpeta especificada

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively, 
    IEnumerable<string> messageExtraFields)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderName | String | Carpeta para recuperar mensajes. |
| retrieveRecursively | Boolean | Indica si los mensajes deben recuperarse recursivamente. |
| messageExtraFields | IEnumerable`1 | Lista de parámetros extra para un mensaje que será solicitado. |

### Valor_devuelto

Colección de objetos ImapMessageInfo

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(long) {#listmessages_18}

Obtiene la lista de mensajes en la carpeta actual que tienen una secuencia de modificación mayor que el valor especificado. Consulte más https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| modificationSequence | Int64 | Secuencia de modificación |

### Valor_devuelto

Colección de[`ImapMessageInfo`](../../imapmessageinfo) que representa la información de los mensajes.

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, MailQuery, int) {#listmessages_9}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
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

## ListMessages(IConnection, MailQuery) {#listmessages_2}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query)
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

## ListMessages(IConnection, MailQuery, int) {#listmessages_3}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query, 
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

## ListMessages(MailQuery) {#listmessages_14}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query)
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

## ListMessages(string, MailQuery, int) {#listmessages_22}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, MailQuery query, 
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

## ListMessages(MailQuery, int) {#listmessages_15}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query, int maxNumberOfMessages)
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

## ListMessages(IConnection, int) {#listmessages_5}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, int maxNumberOfMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |

### Valor_devuelto

Colección de[`ImapMessageInfo`](../../imapmessageinfo) que representa la información de los mensajes.

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

## ListMessages(int) {#listmessages_17}

Obtiene la lista de mensajes en la carpeta actual.

```csharp
public ImapMessageInfoCollection ListMessages(int maxNumberOfMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |

### Valor_devuelto

Colección de[`ImapMessageInfo`](../../imapmessageinfo) que representa la información de los mensajes.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* es negativo |

### Ver también

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
