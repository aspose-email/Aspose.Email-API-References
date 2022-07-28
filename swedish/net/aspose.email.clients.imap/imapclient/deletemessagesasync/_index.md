---
title: DeleteMessagesAsync
second_title: Aspose.Email för .NET API-referens
description: Markerar ett meddelande med den angivna unika identifieraren som deleted
type: docs
weight: 590
url: /sv/net/aspose.email.clients.imap/imapclient/deletemessagesasync/
---
## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessagesasync_19}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long) {#deletemessagesasync_45}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long) {#deletemessagesasync_51}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_49}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_17}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_52}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_20}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
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

## DeleteMessagesAsync(IConnection, int, int) {#deletemessagesasync}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string) {#deletemessagesasync_24}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int) {#deletemessagesasync_32}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string) {#deletemessagesasync_56}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long) {#deletemessagesasync_1}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long) {#deletemessagesasync_27}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long) {#deletemessagesasync_33}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long) {#deletemessagesasync_59}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool) {#deletemessagesasync_57}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool) {#deletemessagesasync_25}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool) {#deletemessagesasync_60}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool) {#deletemessagesasync_28}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_4}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_36}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_7}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_39}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_37}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_5}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_40}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_8}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_15}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_23}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_47}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_55}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_14}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_22}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
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

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_46}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_54}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_50}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_18}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
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

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_53}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_21}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
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

---

## DeleteMessagesAsync(IConnection, int, int, CancellationToken) {#deletemessagesasync_3}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, CancellationToken) {#deletemessagesasync_31}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, CancellationToken) {#deletemessagesasync_35}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, CancellationToken) {#deletemessagesasync_63}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long, CancellationToken) {#deletemessagesasync_2}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
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

## DeleteMessagesAsync(IConnection, string, string, long, CancellationToken) {#deletemessagesasync_30}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
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

## DeleteMessagesAsync(int, int, long, CancellationToken) {#deletemessagesasync_34}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, CancellationToken) {#deletemessagesasync_62}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool, CancellationToken) {#deletemessagesasync_58}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool, CancellationToken) {#deletemessagesasync_26}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
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

## DeleteMessagesAsync(string, string, long, bool, CancellationToken) {#deletemessagesasync_61}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
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

## DeleteMessagesAsync(IConnection, string, string, long, bool, CancellationToken) {#deletemessagesasync_29}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
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

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_11}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_43}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_10}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_42}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_38}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_6}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_41}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_9}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#deletemessagesasync_12}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#deletemessagesasync_16}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;) {#deletemessagesasync_44}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;) {#deletemessagesasync_48}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessagesasync_13}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
