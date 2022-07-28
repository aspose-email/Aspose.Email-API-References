---
title: DeleteMessage
second_title: Aspose.Email för .NET API-referens
description: Markerar ett meddelande med det angivna sekvensnumret som borttaget
type: docs
weight: 560
url: /sv/net/aspose.email.clients.imap/imapclient/deletemessage/
---
## DeleteMessage(IConnection, int) {#deletemessage}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string) {#deletemessage_2}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public void DeleteMessage(IConnection connection, string uniqueId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessage(int) {#deletemessage_6}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessage(int sequenceNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessage(string) {#deletemessage_8}

Markerar ett meddelande med det angivna sekvensnumret som deleted

```csharp
public void DeleteMessage(string uniqueId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, int, long) {#deletemessage_1}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long) {#deletemessage_4}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessage(int, long) {#deletemessage_7}

Markerar ett meddelande med det angivna sekvensnumret som borttaget

```csharp
public void DeleteMessage(int sequenceNumber, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Sekvensnummer för ett meddelande |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessage(string, long) {#deletemessage_10}

Markerar ett meddelande med den angivna unika identifieraren som deleted

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessage(string, bool) {#deletemessage_9}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, bool) {#deletemessage_3}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessage(string, long, bool) {#deletemessage_11}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence, bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long, bool) {#deletemessage_5}

Markerar ett meddelande med den angivna unika identifieraren som borttagen och begår raderingarna om användaren anger detta. Den här metoden fungerar endast om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| modificationSequence | Int64 | Modifieringssekvens. Läs mer https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definierar om meddelandet måste commiteras nu. Läs mer https://tools.ietf.org/html/rfc4315 |

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
