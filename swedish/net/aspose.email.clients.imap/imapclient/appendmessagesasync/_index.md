---
title: AppendMessagesAsync
second_title: Aspose.Email för .NET API-referens
description: Laddar upp e-postmeddelanden till den aktuella mappen
type: docs
weight: 390
url: /sv/net/aspose.email.clients.imap/imapclient/appendmessagesasync/
---
## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_2}

Laddar upp e-postmeddelanden till den aktuella mappen

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp som kommer att ta emot e-postmeddelandet |
| messages | IEnumerable`1 | Uppräkning av e-postmeddelanden som ska laddas upp |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_4}

Laddar upp e-postmeddelandet till den aktuella mappen Om den aktuella mappen inte har specificerats används standardmappen.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | IEnumerable`1 | Uppräkning av e-postmeddelanden som ska laddas upp |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_6}

Laddar upp e-postmeddelanden till den aktuella mappen

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp som kommer att ta emot e-postmeddelandet |
| messages | IEnumerable`1 | Uppräkning av e-postmeddelanden som ska laddas upp |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_1}

Laddar upp e-postmeddelanden till den aktuella mappen Om den aktuella mappen inte har specificerats används standardmappen.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messages | IEnumerable`1 | Uppräkning av e-postmeddelanden som ska laddas upp |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_3}

Laddar upp e-postmeddelanden till den aktuella mappen

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp som kommer att ta emot e-postmeddelandet |
| messages | IEnumerable`1 | Uppräkning av e-postmeddelanden som ska laddas upp |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_5}

Laddar upp e-postmeddelandet till den aktuella mappen Om den aktuella mappen inte har specificerats används standardmappen.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | IEnumerable`1 | Uppräkning av e-postmeddelanden som ska laddas upp |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_7}

Laddar upp e-postmeddelanden till den aktuella mappen

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp som kommer att ta emot e-postmeddelandet |
| messages | IEnumerable`1 | Uppräkning av e-postmeddelanden som ska laddas upp |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync}

Laddar upp e-postmeddelanden till den aktuella mappen Om den aktuella mappen inte har specificerats används standardmappen.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messages | IEnumerable`1 | Uppräkning av e-postmeddelanden som ska laddas upp |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
