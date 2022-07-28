---
title: DeleteMessages
second_title: Aspose.Email för .NET API-referens
description: Markerar ett meddelande med det angivna sekvensnumret som borttaget
type: docs
weight: 580
url: /sv/net/aspose.email.clients.imap/imapclient/deletemessages/
---
## DeleteMessages(IConnection, IEnumerable&lt;int&gt;) {#deletemessages_6}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;) {#deletemessages_8}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;) {#deletemessages_22}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;) {#deletemessages_24}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public void DeleteMessages(IEnumerable<string> uidSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessages_7}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessages_10}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;, long) {#deletemessages_23}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long) {#deletemessages_26}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, bool) {#deletemessages_25}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessages_9}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long, bool) {#deletemessages_27}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessages_11}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int) {#deletemessages}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string) {#deletemessages_12}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(int, int) {#deletemessages_16}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessages(int startSequence, int endSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(string, string) {#deletemessages_28}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public void DeleteMessages(string startUid, string endUid)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int, long) {#deletemessages_1}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long) {#deletemessages_14}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(int, int, long) {#deletemessages_17}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessages(int startSequence, int endSequence, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long) {#deletemessages_30}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(string, string, bool) {#deletemessages_29}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, bool) {#deletemessages_13}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long, bool) {#deletemessages_31}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long, bool) {#deletemessages_15}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_2}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_18}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_4}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_20}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_19}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_3}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_21}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_5}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo för radering |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
