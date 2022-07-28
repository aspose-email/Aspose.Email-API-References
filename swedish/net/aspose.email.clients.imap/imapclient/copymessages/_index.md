---
title: CopyMessages
second_title: Aspose.Email för .NET API-referens
description: Kopiera meddelandet
type: docs
weight: 500
url: /sv/net/aspose.email.clients.imap/imapclient/copymessages/
---
## CopyMessages(IConnection, int, int, string) {#copymessages}

Kopiera meddelandet

```csharp
public void CopyMessages(IConnection connection, int startSequence, int endSequence, 
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

## CopyMessages(int, int, string) {#copymessages_5}

Kopiera meddelanden

```csharp
public void CopyMessages(int startSequence, int endSequence, string folderName)
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

## CopyMessages(IConnection, string, string, string) {#copymessages_4}

Kopiera meddelanden

```csharp
public void CopyMessages(IConnection connection, string startUid, string endUid, string folderName)
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

## CopyMessages(string, string, string) {#copymessages_10}

Kopiera meddelanden

```csharp
public void CopyMessages(string startUid, string endUid, string folderName)
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

## CopyMessages(IEnumerable&lt;int&gt;, string, bool) {#copymessages_8}

Kopiera meddelanden

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
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

## CopyMessages(IConnection, IEnumerable&lt;int&gt;, string) {#copymessages_2}

Kopiera meddelandet

```csharp
public void CopyMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
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

## CopyMessages(IEnumerable&lt;int&gt;, string) {#copymessages_7}

Kopiera meddelanden

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName)
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

## CopyMessages(IConnection, IEnumerable&lt;string&gt;, string) {#copymessages_3}

Kopiera meddelanden

```csharp
public void CopyMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
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

## CopyMessages(IEnumerable&lt;string&gt;, string) {#copymessages_9}

Kopiera meddelanden

```csharp
public void CopyMessages(IEnumerable<string> uidSet, string folderName)
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

## CopyMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_1}

Kopiera meddelanden

```csharp
public void CopyMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## CopyMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_6}

Kopiera meddelanden

```csharp
public void CopyMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
