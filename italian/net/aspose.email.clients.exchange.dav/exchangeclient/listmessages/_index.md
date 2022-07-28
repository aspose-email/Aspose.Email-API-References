---
title: ListMessages
second_title: Aspose.Email per riferimento all'API .NET
description: Elenca i messaggi.
type: docs
weight: 280
url: /it/net/aspose.email.clients.exchange.dav/exchangeclient/listmessages/
---
## ListMessages(string) {#listmessages}

Elenca i messaggi.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | La cartella. |

### Valore di ritorno

UN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_4}

Elenca i messaggi.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | La cartella. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi |

### Valore di ritorno

UN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_7}

Elenca i messaggi.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string messageClass, 
    bool recursive)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | La cartella. |
| messageClass | String | La classe dei messaggi |
| recursive | Boolean | se impostato su`VERO` [ricorsivo]. |

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_3}

Elenca i messaggi nella cartella specificata

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | La cartella Uri |
| recursive | Boolean | Indica se l'elenco ricorsivo o meno. |

### Valore di ritorno

Una raccolta di informazioni sui messaggi

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, string) {#listmessages_6}

Elenca i messaggi.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | La cartella. |
| query | String | La domanda. |

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_2}

Elenca i messaggi.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | L'Uri della cartella che contiene i messaggi. |
| query | MailQuery | Il[`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta i criteri di ricerca. |
| recursive | Boolean | Indica se l'elenco ricorsivo o meno. |

### Valore di ritorno

La raccolta di informazioni sui messaggi.

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_1}

Elenca il messaggio di posta nella cartella specificata.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | L'URL della cartella |
| options | ExchangeListMessagesOptions | Specifica le impostazioni dell'elenco |

### Valore di ritorno

UN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) collezione.

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_5}

Elenca i messaggi nella cartella specificata

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | La cartella Uri |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi |
| options | ExchangeListMessagesOptions | Specifica le impostazioni dell'elenco |

### Valore di ritorno

Una raccolta di informazioni sui messaggi

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
