---
title: FetchMessageAsync
second_title: Aspose.Email för .NET API-referens
description: Hämtar meddelandet
type: docs
weight: 660
url: /sv/net/aspose.email.clients.imap/imapclient/fetchmessageasync/
---
## FetchMessageAsync(IConnection, int) {#fetchmessageasync}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, bool) {#fetchmessageasync_1}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| ignoreAttachment | Boolean | Ett värde som definierar om bilagorna inte ska laddas. Om den är inställd på`Sann` , då hämtas bara meddelanderubriker, meddelandetext och bilagainformation. Bilagans innehåll laddas inte |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## FetchMessageAsync(int) {#fetchmessageasync_6}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool) {#fetchmessageasync_7}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| ignoreAttachment | Boolean | Ett värde som definierar om bilagorna inte ska laddas. Om den är inställd på`Sann` , då hämtas bara meddelanderubriker, meddelandetext och bilagainformation. Bilagans innehåll laddas inte |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string) {#fetchmessageasync_4}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Meddelandets unika ID |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## FetchMessageAsync(string) {#fetchmessageasync_10}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Meddelandets unika ID |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, CancellationToken) {#fetchmessageasync_3}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, bool, CancellationToken) {#fetchmessageasync_2}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| ignoreAttachment | Boolean | Ett värde som definierar om bilagorna inte ska laddas. Om den är inställd på`Sann` , då hämtas bara meddelanderubriker, meddelandetext och bilagainformation. Bilagans innehåll laddas inte |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## FetchMessageAsync(int, CancellationToken) {#fetchmessageasync_9}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool, CancellationToken) {#fetchmessageasync_8}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| ignoreAttachment | Boolean | Ett värde som definierar om bilagorna inte ska laddas. Om den är inställd på`Sann` , då hämtas bara meddelanderubriker, meddelandetext och bilagainformation. Bilagans innehåll laddas inte |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string, CancellationToken) {#fetchmessageasync_5}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Meddelandets unika ID |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## FetchMessageAsync(string, CancellationToken) {#fetchmessageasync_11}

Hämtar meddelandet

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Meddelandets unika ID |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
