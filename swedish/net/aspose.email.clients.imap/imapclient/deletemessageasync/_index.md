---
title: DeleteMessageAsync
second_title: Aspose.Email för .NET API-referens
description: Markerar ett meddelande med det angivna sekvensnumret som borttaget
type: docs
weight: 570
url: /sv/net/aspose.email.clients.imap/imapclient/deletemessageasync/
---
## DeleteMessageAsync(IConnection, int) {#deletemessageasync}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string) {#deletemessageasync_4}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(int) {#deletemessageasync_12}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(string) {#deletemessageasync_16}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long) {#deletemessageasync_1}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long) {#deletemessageasync_7}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long) {#deletemessageasync_13}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long) {#deletemessageasync_19}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool) {#deletemessageasync_17}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool) {#deletemessageasync_5}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool) {#deletemessageasync_20}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool) {#deletemessageasync_8}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, CancellationToken) {#deletemessageasync_3}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, CancellationToken) {#deletemessageasync_11}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, CancellationToken) {#deletemessageasync_15}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_23}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long, CancellationToken) {#deletemessageasync_2}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, CancellationToken) {#deletemessageasync_10}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long, CancellationToken) {#deletemessageasync_14}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, CancellationToken) {#deletemessageasync_22}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool, CancellationToken) {#deletemessageasync_18}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool, CancellationToken) {#deletemessageasync_6}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool, CancellationToken) {#deletemessageasync_21}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool, CancellationToken) {#deletemessageasync_9}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
