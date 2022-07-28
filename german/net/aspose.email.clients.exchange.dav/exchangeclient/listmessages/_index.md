---
title: ListMessages
second_title: Aspose.Email für .NET-API-Referenz
description: Listet die Nachrichten auf.
type: docs
weight: 280
url: /de/net/aspose.email.clients.exchange.dav/exchangeclient/listmessages/
---
## ListMessages(string) {#listmessages}

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
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_4}

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
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_7}

Listet die Nachrichten auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string messageClass, 
    bool recursive)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Die Mappe. |
| messageClass | String | Die Nachrichtenklasse. |
| recursive | Boolean | wenn eingestellt`Stimmt` [rekursiv]. |

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_3}

Listet die Nachrichten im angegebenen Ordner auf

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Der Ordner Uri |
| recursive | Boolean | Gibt an, ob rekursive Auflistung oder nicht. |

### Rückgabewert

Eine Sammlung von Nachrichteninformationen

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, string) {#listmessages_6}

Listet die Nachrichten auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Die Mappe. |
| query | String | Die Abfrage. |

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_2}

Listet die Nachrichten auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Der Uri des Ordners, der Nachrichten enthält. |
| query | MailQuery | Das[`MailQuery`](../../../aspose.email.tools.search/mailquery) das Suchkriterien darstellt. |
| recursive | Boolean | Gibt an, ob rekursive Auflistung oder nicht. |

### Rückgabewert

Die Sammlung von Nachrichteninformationen.

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_1}

Listet die E-Mail-Nachricht im angegebenen Ordner auf.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Die Ordner-URL |
| options | ExchangeListMessagesOptions | Gibt die Listeneinstellungen an |

### Rückgabewert

EIN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) Sammlung.

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_5}

Listet die Nachrichten im angegebenen Ordner auf

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | String | Der Ordner Uri |
| maxNumberOfMessages | Int32 | Maximale Anzahl von Nachrichten |
| options | ExchangeListMessagesOptions | Gibt die Listeneinstellungen an |

### Rückgabewert

Eine Sammlung von Nachrichteninformationen

### Siehe auch

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
