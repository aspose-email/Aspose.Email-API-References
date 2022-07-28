---
title: ListMessagesByPage
second_title: Referencia de la API de Aspose.Email para .NET
description: Lista los mensajes en la carpeta especificada.
type: docs
weight: 1150
url: /es/net/aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/
---
## ListMessagesByPage(string, int) {#listmessagesbypage_4}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes. |
| itemsPerPage | Int32 | Varios artículos en la página |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int) {#listmessagesbypage_2}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa los criterios de búsqueda. |
| itemsPerPage | Int32 | Varios artículos en la página |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int) {#listmessagesbypage_5}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int offset)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes. |
| itemsPerPage | Int32 | Varios artículos en la página |
| offset | Int32 | Un desplazamiento de la página siguiente a la vista |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int, int) {#listmessagesbypage_3}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage, 
    int offset)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa los criterios de búsqueda. |
| itemsPerPage | Int32 | Varios artículos en la página |
| offset | Int32 | Un desplazamiento de la página siguiente a la vista |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int, ExchangeListMessagesOptions) {#listmessagesbypage_6}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int pageOffset, 
    ExchangeListMessagesOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes. |
| itemsPerPage | Int32 | Varios artículos en la página |
| pageOffset | Int32 | Un desplazamiento del siguiente elemento a la vista |
| options | ExchangeListMessagesOptions | Especifica la configuración de la lista |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo) {#listmessagesbypage}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes. |
| pageInfo | PageInfo | información de una página |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo, ExchangeListMessagesOptions) {#listmessagesbypage_1}

Lista los mensajes en la carpeta especificada.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo, 
    ExchangeListMessagesOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | Una carpeta para buscar mensajes. |
| pageInfo | PageInfo | información de una página |
| options | ExchangeListMessagesOptions | Especifica la configuración de la lista |

### Valor_devuelto

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)que contiene mensajes de la carpeta especificada.

### Ver también

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
