---
title: ListMessages
second_title: Aspose.Email für .NET-API-Referenz
description: Listet die Nachrichten auf.
type: docs
weight: 1140
url: /de/net/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---
## ListMessages(string) {#listmessages_2}

Listet die Nachrichten auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Die Mappe. |

### Rückgabewert

EIN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_3}

Listet die Nachrichten auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Die Mappe. |
| options | ExchangeListMessagesOptions | Gibt die Listeneinstellungen an |

### Rückgabewert

EIN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_8}

Listet die Nachrichten auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Die Mappe. |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten |

### Rückgabewert

EIN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_9}

Listet die Nachrichten auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Die Mappe. |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten |
| options | ExchangeListMessagesOptions | Gibt die Listeneinstellungen an |

### Rückgabewert

EIN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_13}

Listet die Nachrichten im angegebenen Ordner auf

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, bool recursive)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mailbox | String | Das Postfach, das zum Initialisieren der Ordner-ID-Klasse verwendet wird. |
| folder | String | Ein Ordner zum Suchen von Nachrichten |
| recursive | Boolean | Gibt an, ob rekursive Auflistung oder nicht |

### Rückgabewert

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) die Nachrichten aus dem angegebenen Ordner enthält

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, string, MailQuery) {#listmessages_12}

Listet die Nachrichten im angegebenen Ordner auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, MailQuery query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mailbox | String | Das Postfach, das zum Initialisieren der Ordner-ID-Klasse verwendet wird. |
| folder | String | Ein Ordner zum Suchen von Nachrichten. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die Suchkriterien für Nachrichten darstellt. |

### Rückgabewert

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)die Nachrichten aus dem angegebenen Ordner enthält.

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_7}

Listet die Nachrichten im angegebenen Ordner auf

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Ein Ordner zum Suchen von Nachrichten |
| recursive | Boolean | Gibt an, ob rekursive Auflistung oder nicht |

### Rückgabewert

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) die Nachrichten aus dem angegebenen Ordner enthält

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) {#listmessages_4}

Listet die Nachrichten im angegebenen Ordner auf

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options, IEnumerable<PropertyDescriptor> extendedProperties)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Ein Ordner zum Suchen von Nachrichten |
| options | ExchangeListMessagesOptions | Gibt die Listeneinstellungen an |
| extendedProperties | IEnumerable`1 | Erweiterte Eigenschaften von abgerufenen Nachrichten |

### Rückgabewert

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) die Nachrichten aus dem angegebenen Ordner enthält

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery) {#listmessages_5}

Listet die Nachrichten im angegebenen Ordner auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Ein Ordner zum Suchen von Nachrichten. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die Suchkriterien für Nachrichten darstellt. |

### Rückgabewert

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) die Nachrichten aus dem angegebenen Ordner enthält.

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_6}

Listet die Nachrichten im angegebenen Ordner auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Ein Ordner zum Suchen von Nachrichten. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die Suchkriterien für Nachrichten darstellt. |
| recursive | Boolean | Gibt an, ob rekursive Auflistung oder nicht. |

### Rückgabewert

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) die Nachrichten aus dem angegebenen Ordner enthält.

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery, bool) {#listmessages_11}

Listet die Nachrichten im angegebenen Ordner auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query, bool recursive)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Ein Ordner zum Suchen von Nachrichten. |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die Suchkriterien für Nachrichten darstellt. |
| recursive | Boolean | Gibt an, ob rekursive Auflistung oder nicht. |

### Rückgabewert

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)die Nachrichten aus dem angegebenen Ordner enthält.

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_1}

Listet die Nachrichten im angegebenen Ordner auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(IEnumerable<string> iDs)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| iDs | IEnumerable`1 | Aufzählung von Nachrichten-IDs |

### Rückgabewert

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) das enthält Nachrichten mit.

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Listen Sie die Nachrichten im Posteingangsordner auf.

```csharp
public ExchangeMessageInfoCollection ListMessages()
```

### Rückgabewert

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) aus Posteingangsordner.

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery) {#listmessages_10}

Listet die Nachrichten im angegebenen Ordner auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Ein Ordner zum Suchen von Nachrichten. |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die Suchkriterien für Nachrichten darstellt. |

### Rückgabewert

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)die Nachrichten aus dem angegebenen Ordner enthält.

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
