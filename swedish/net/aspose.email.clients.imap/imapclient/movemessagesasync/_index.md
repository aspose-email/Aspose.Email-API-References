---
title: MoveMessagesAsync
second_title: Aspose.Email för .NET API-referens
description: Flyttar meddelandet
type: docs
weight: 960
url: /sv/net/aspose.email.clients.imap/imapclient/movemessagesasync/
---
## MoveMessagesAsync(IConnection, int, int, string, bool) {#movemessagesasync_1}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, bool) {#movemessagesasync_21}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string) {#movemessagesasync}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string) {#movemessagesasync_20}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, bool) {#movemessagesasync_9}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, bool) {#movemessagesasync_29}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string) {#movemessagesasync_8}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string) {#movemessagesasync_28}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, bool) {#movemessagesasync_17}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, bool) {#movemessagesasync_37}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string) {#movemessagesasync_16}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string) {#movemessagesasync_36}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, bool) {#movemessagesasync_13}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, bool) {#movemessagesasync_33}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string) {#movemessagesasync_12}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string) {#movemessagesasync_32}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessagesasync_5}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessagesasync_25}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessagesasync_4}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessagesasync_24}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string, bool, CancellationToken) {#movemessagesasync_2}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, bool, CancellationToken) {#movemessagesasync_22}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string, CancellationToken) {#movemessagesasync_3}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, CancellationToken) {#movemessagesasync_23}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, bool, CancellationToken) {#movemessagesasync_10}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, bool, CancellationToken) {#movemessagesasync_30}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) {#movemessagesasync_11}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, CancellationToken) {#movemessagesasync_31}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, bool, CancellationToken) {#movemessagesasync_18}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, bool, CancellationToken) {#movemessagesasync_38}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, CancellationToken) {#movemessagesasync_19}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, CancellationToken) {#movemessagesasync_39}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, bool, CancellationToken) {#movemessagesasync_14}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, bool, CancellationToken) {#movemessagesasync_34}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) {#movemessagesasync_15}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, CancellationToken) {#movemessagesasync_35}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) {#movemessagesasync_6}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
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

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) {#movemessagesasync_26}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#movemessagesasync_7}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
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

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#movemessagesasync_27}

Flyttar meddelandet

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
