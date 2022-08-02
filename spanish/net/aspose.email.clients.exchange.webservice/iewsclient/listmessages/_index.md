---
title: ListMessages
second_title: Referencia de la API de Aspose.Email para .NET
description: Lista los mensajes.
type: docs
weight: 1140
url: /es/net/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---
## ListMessages(string) {#listmessages_2}

Lista los mensajes.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | La carpeta. |

### Valor_devuelto

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_3}

Lista los mensajes.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | La carpeta. |
| options | ExchangeListMessagesOptions | Especifica la configuración de la lista |

### Valor_devuelto

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_8}

Lista los mensajes.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | La carpeta. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes |

### Valor_devuelto

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_9}

Lista los mensajes.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | La carpeta. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes |
| options | ExchangeListMessagesOptions | Especifica la configuración de la lista |

### Valor_devuelto

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_13}

Lista los mensajes en la carpeta especificada

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, bool recursive)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mailbox | String | El buzón que se utiliza para inicializar la clase de ID de carpeta. |
| folder | String | Una carpeta para buscar mensajes en |
| recursive | Boolean | Indica si el listado recursivo o no |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) que contiene mensajes de la carpeta especificada

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, string, MailQuery) {#listmessages_12}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, MailQuery query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mailbox | String | El buzón que se utiliza para inicializar la clase de ID de carpeta. |
| folder | String | Una carpeta para buscar mensajes. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa los criterios de búsqueda de mensajes. |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_7}

Lista los mensajes en la carpeta especificada

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes en |
| recursive | Boolean | Indica si el listado recursivo o no |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) que contiene mensajes de la carpeta especificada

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) {#listmessages_4}

Lista los mensajes en la carpeta especificada

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options, IEnumerable<PropertyDescriptor> extendedProperties)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes en |
| options | ExchangeListMessagesOptions | Especifica la configuración de la lista |
| extendedProperties | IEnumerable`1 | Propiedades extendidas de mensajes recuperados |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) que contiene mensajes de la carpeta especificada

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery) {#listmessages_5}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa los criterios de búsqueda de mensajes. |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_6}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa los criterios de búsqueda de mensajes. |
| recursive | Boolean | Indica si el listado es recursivo o no. |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery, bool) {#listmessages_11}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query, bool recursive)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa los criterios de búsqueda de mensajes. |
| recursive | Boolean | Indica si el listado es recursivo o no. |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_1}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessageInfoCollection ListMessages(IEnumerable<string> iDs)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| iDs | IEnumerable`1 | Enumeración de ID de mensajes |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) que contiene mensajes con.

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Lista los mensajes en la carpeta de la bandeja de entrada.

```csharp
public ExchangeMessageInfoCollection ListMessages()
```

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) de la carpeta de la bandeja de entrada.

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery) {#listmessages_10}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes. |
| maxNumberOfMessages | Int32 | Número máximo de mensajes. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa los criterios de búsqueda de mensajes. |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
