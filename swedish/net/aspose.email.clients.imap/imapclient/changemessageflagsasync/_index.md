---
title: ChangeMessageFlagsAsync
second_title: Aspose.Email för .NET API-referens
description: Ändrar flaggorna för meddelandet
type: docs
weight: 430
url: /sv/net/aspose.email.clients.imap/imapclient/changemessageflagsasync/
---
## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#changemessageflagsasync_41}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#changemessageflagsasync_17}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#changemessageflagsasync_13}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#changemessageflagsasync_36}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| flags | ImapMessageFlags | Flaggan ska ändras |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#changemessageflagsasync_8}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| flags | ImapMessageFlags | Flaggan ska ändras |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#changemessageflagsasync_37}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#changemessageflagsasync_9}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_51}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| flags | ImapMessageFlags | Flaggan ska ändras |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_31}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_23}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| flags | ImapMessageFlags | Flaggan ska ändras |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_3}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_50}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_30}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_22}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_2}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_55}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| flags | ImapMessageFlags | Flaggan ska ändras |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_35}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_27}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| flags | ImapMessageFlags | Flaggan ska ändras |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_7}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_54}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_34}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_26}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_6}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_47}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| flags | ImapMessageFlags | Flaggan ska ändras |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_43}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_19}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| flags | ImapMessageFlags | Flaggan ska ändras |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_15}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_46}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_42}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_18}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_14}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_39}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| flags | ImapMessageFlags | Flaggan ska ändras |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_11}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| flags | ImapMessageFlags | Flaggan ska ändras |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_38}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_10}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags) {#changemessageflagsasync_48}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| flags | ImapMessageFlags | Flaggan ska ändras |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags) {#changemessageflagsasync_28}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| flags | ImapMessageFlags | Flaggorna ska tas bort |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#changemessageflagsasync_20}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| flags | ImapMessageFlags | Flaggan ska ändras |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#changemessageflagsasync}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| flags | ImapMessageFlags | Flaggorna ska tas bort |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, long) {#changemessageflagsasync_49}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, long) {#changemessageflagsasync_29}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#changemessageflagsasync_21}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#changemessageflagsasync_1}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags) {#changemessageflagsasync_52}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| flags | ImapMessageFlags | Flaggan ska ändras |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags) {#changemessageflagsasync_32}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| flags | ImapMessageFlags | Flaggorna ska tas bort |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#changemessageflagsasync_24}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| flags | ImapMessageFlags | Flaggan ska ändras |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#changemessageflagsasync_4}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| flags | ImapMessageFlags | Flaggorna ska tas bort |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, long) {#changemessageflagsasync_53}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, long) {#changemessageflagsasync_33}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#changemessageflagsasync_25}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#changemessageflagsasync_5}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| flags | ImapMessageFlags | Flaggorna ska tas bort |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#changemessageflagsasync_44}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| flags | ImapMessageFlags | Flaggan ska ändras |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#changemessageflagsasync_40}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| flags | ImapMessageFlags | Flaggorna ska tas bort |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#changemessageflagsasync_16}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| flags | ImapMessageFlags | Flaggan ska ändras |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#changemessageflagsasync_12}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| flags | ImapMessageFlags | Flaggorna ska tas bort |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#changemessageflagsasync_45}

Ändrar flaggorna för meddelandet

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| flags | ImapMessageFlags | Flaggan ska ändras |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
