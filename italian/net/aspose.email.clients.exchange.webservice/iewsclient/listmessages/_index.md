---
title: ListMessages
second_title: Aspose.Email per riferimento all'API .NET
description: Elenca i messaggi.
type: docs
weight: 1140
url: /it/net/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---
## ListMessages(string) {#listmessages_2}

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
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_3}

Elenca i messaggi.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | La cartella. |
| options | ExchangeListMessagesOptions | Specifica le impostazioni dell'elenco |

### Valore di ritorno

UN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_8}

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
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_9}

Elenca i messaggi.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | La cartella. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi |
| options | ExchangeListMessagesOptions | Specifica le impostazioni dell'elenco |

### Valore di ritorno

UN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_13}

Elenca i messaggi nella cartella specificata

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, bool recursive)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mailbox | String | La cassetta postale utilizzata per inizializzare la classe ID cartella. |
| folder | String | Una cartella in cui cercare i messaggi |
| recursive | Boolean | Indica se l'elenco ricorsivo o meno |

### Valore di ritorno

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) che contiene i messaggi dalla cartella specificata

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, string, MailQuery) {#listmessages_12}

Elenca i messaggi nella cartella specificata.

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mailbox | String | La cassetta postale utilizzata per inizializzare la classe ID cartella. |
| folder | String | Una cartella in cui cercare i messaggi. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta i criteri di ricerca dei messaggi. |

### Valore di ritorno

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)che contiene i messaggi dalla cartella specificata.

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_7}

Elenca i messaggi nella cartella specificata

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | Una cartella in cui cercare i messaggi |
| recursive | Boolean | Indica se l'elenco ricorsivo o meno |

### Valore di ritorno

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) che contiene i messaggi dalla cartella specificata

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) {#listmessages_4}

Elenca i messaggi nella cartella specificata

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options, IEnumerable<PropertyDescriptor> extendedProperties)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | Una cartella in cui cercare i messaggi |
| options | ExchangeListMessagesOptions | Specifica le impostazioni dell'elenco |
| extendedProperties | IEnumerable`1 | Proprietà estese dei messaggi recuperati |

### Valore di ritorno

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) che contiene i messaggi dalla cartella specificata

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery) {#listmessages_5}

Elenca i messaggi nella cartella specificata.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | Una cartella in cui cercare i messaggi. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta i criteri di ricerca dei messaggi. |

### Valore di ritorno

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) che contiene i messaggi dalla cartella specificata.

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_6}

Elenca i messaggi nella cartella specificata.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | Una cartella in cui cercare i messaggi. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta i criteri di ricerca dei messaggi. |
| recursive | Boolean | Indica se l'elenco ricorsivo o meno. |

### Valore di ritorno

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) che contiene i messaggi dalla cartella specificata.

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery, bool) {#listmessages_11}

Elenca i messaggi nella cartella specificata.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query, bool recursive)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | Una cartella in cui cercare i messaggi. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta i criteri di ricerca dei messaggi. |
| recursive | Boolean | Indica se l'elenco ricorsivo o meno. |

### Valore di ritorno

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)che contiene i messaggi dalla cartella specificata.

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_1}

Elenca i messaggi nella cartella specificata.

```csharp
public ExchangeMessageInfoCollection ListMessages(IEnumerable<string> iDs)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| iDs | IEnumerable`1 | Enumerazione degli ID dei messaggi |

### Valore di ritorno

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) che contiene messaggi con.

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Elenca i messaggi nella cartella della posta in arrivo.

```csharp
public ExchangeMessageInfoCollection ListMessages()
```

### Valore di ritorno

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) dalla cartella Posta in arrivo.

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery) {#listmessages_10}

Elenca i messaggi nella cartella specificata.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | String | Una cartella in cui cercare i messaggi. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta i criteri di ricerca dei messaggi. |

### Valore di ritorno

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)che contiene i messaggi dalla cartella specificata.

### Guarda anche

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
