---
title: ListMessages
second_title: Referencia de la API de Aspose.Email para .NET
description: Lista los mensajes.
type: docs
weight: 280
url: /es/net/aspose.email.clients.exchange.dav/exchangeclient/listmessages/
---
## ListMessages(string) {#listmessages}

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
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_4}

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
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_7}

Lista los mensajes.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string messageClass, 
    bool recursive)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | La carpeta. |
| messageClass | String | La clase de mensaje. |
| recursive | Boolean | si se establece en`verdadero` [recursivo]. |

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_3}

Lista los mensajes en la carpeta especificada

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | La carpeta uri |
| recursive | Boolean | Indica si el listado es recursivo o no. |

### Valor_devuelto

Una colección de información de mensajes.

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, string) {#listmessages_6}

Lista los mensajes.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string query)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | La carpeta. |
| query | String | La consulta. |

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_2}

Lista los mensajes.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | El Uri de la carpeta que contiene mensajes. |
| query | MailQuery | los[`MailQuery`](../../../aspose.email.tools.search/mailquery) que representa los criterios de búsqueda. |
| recursive | Boolean | Indica si el listado es recursivo o no. |

### Valor_devuelto

La recopilación de información del mensaje.

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_1}

Muestra el mensaje de correo en la carpeta especificada.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | URL de la carpeta |
| options | ExchangeListMessagesOptions | Especifica la configuración de la lista |

### Valor_devuelto

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) recopilación.

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_5}

Lista los mensajes en la carpeta especificada

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folder | String | La carpeta uri |
| maxNumberOfMessages | Int32 | Número máximo de mensajes |
| options | ExchangeListMessagesOptions | Especifica la configuración de la lista |

### Valor_devuelto

Una colección de información de mensajes.

### Ver también

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
