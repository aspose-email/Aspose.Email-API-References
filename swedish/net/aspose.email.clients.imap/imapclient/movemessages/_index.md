---
title: MoveMessages
second_title: Aspose.Email för .NET API-referens
description: Flyttar meddelandet
type: docs
weight: 950
url: /sv/net/aspose.email.clients.imap/imapclient/movemessages/
---
## MoveMessages(IConnection, string, string, string) {#movemessages_8}

Flyttar meddelandet

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(string, string, string) {#movemessages_18}

Flyttar meddelandet

```csharp
public void MoveMessages(string startUid, string endUid, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string, bool) {#movemessages_7}

Flyttar meddelandet

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string, bool) {#movemessages_17}

Flyttar meddelandet

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string) {#movemessages_6}

Flyttar meddelandet

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string) {#movemessages_16}

Flyttar meddelandet

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättningen av UID för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_3}

Flyttar meddelandet

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_13}

Flyttar meddelandet

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_2}

Flyttar meddelandet

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_12}

Flyttar meddelandet

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Uppsättningen av ImapMessageInfo |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Se även

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string, bool) {#movemessages_1}

Flyttar meddelandet

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(int, int, string, bool) {#movemessages_11}

Flyttar meddelandet

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string) {#movemessages}

Flyttar meddelandet

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(int, int, string) {#movemessages_10}

Flyttar meddelandet

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startSequence | Int32 | Startsekvensnumret för en meddelandelista |
| endSequence | Int32 | Slutsekvensnumret för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string, bool) {#movemessages_5}

Flyttar meddelandet

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string, bool) {#movemessages_15}

Flyttar meddelandet

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string) {#movemessages_4}

Flyttar meddelandet

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string) {#movemessages_14}

Flyttar meddelandet

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Uppsättningen sekvensnummer för meddelanden |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(IConnection, string, string, string, bool) {#movemessages_9}

Flyttar meddelandet

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessages(string, string, string, bool) {#movemessages_19}

Flyttar meddelandet

```csharp
public void MoveMessages(string startUid, string endUid, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
