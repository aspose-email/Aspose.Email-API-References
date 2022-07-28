---
title: MarkAsJunk
second_title: Aspose.Email för .NET API-referens
description: MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren.
type: docs
weight: 1270
url: /sv/net/aspose.email.clients.exchange.webservice/iewsclient/markasjunk/
---
## MarkAsJunk(bool, params string[]) {#markasjunk_3}

MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren.

```csharp
public string[] MarkAsJunk(bool isJunk, params string[] messageUriEn)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isJunk | Boolean | Indikerar om meddelanden är markerade som skräppost. Om värdet på sant lägger till meddelandeavsändaren till blockeringslistan. Om värdet på false tar bort meddelandeavsändaren från blockeringslistan. |
| messageUriEn | String[] | Array av meddelande uri |

### Returvärde

Returnerar arrayen av meddelande-ID som har flyttats till skräppostmappen.

### Se även

* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, params string[]) {#markasjunk_1}

MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, params string[] messageUriEn)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isJunk | Boolean | Indikerar om meddelanden är markerade som skräppost. Om värdet på sant lägger till meddelandeavsändaren till blockeringslistan. Om värdet på false tar bort meddelandeavsändaren från blockeringslistan. |
| moveItem | Boolean | Indikerar om meddelanden har flyttats till skräppostmappen. |
| messageUriEn | String[] | Array av meddelande uri |

### Returvärde

Returnerar arrayen av meddelande-ID som har flyttats till skräppostmappen.

### Se även

* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## MarkAsJunk(bool, IEnumerable&lt;string&gt;) {#markasjunk_2}

MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren.

```csharp
public string[] MarkAsJunk(bool isJunk, IEnumerable<string> messageUriEn)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isJunk | Boolean | Indikerar om meddelanden är markerade som skräppost. Om värdet på sant lägger till meddelandeavsändaren till blockeringslistan. Om värdet på false tar bort meddelandeavsändaren från blockeringslistan. |
| messageUriEn | IEnumerable`1 | Uppräkning av meddelande-uri |

### Returvärde

Returnerar artikel-ID för meddelandet markerat som skräppost.

### Se även

* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;) {#markasjunk}

MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isJunk | Boolean | Indikerar om meddelanden är markerade som skräppost. Om värdet på sant lägger till meddelandeavsändaren till blockeringslistan. Om värdet på false tar bort meddelandeavsändaren från blockeringslistan. |
| moveItem | Boolean | Indikerar om meddelanden har flyttats till skräppostmappen. |
| messageUriEn | IEnumerable`1 | Uppräkning av meddelande-uri |

### Returvärde

Returnerar arrayen av meddelande-ID som har flyttats till skräppostmappen.

### Se även

* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) {#markasjunk_4}

MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren.

```csharp
public void MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn, 
    out string[] movedMessageIds, out string[] failedMessageIds, out string[] errorMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isJunk | Boolean | Indikerar om meddelanden är markerade som skräppost. Om värdet på sant lägger till meddelandeavsändaren till blockeringslistan. Om värdet på false tar bort meddelandeavsändaren från blockeringslistan. |
| moveItem | Boolean | Indikerar om meddelanden har flyttats till skräppostmappen. |
| messageUriEn | IEnumerable`1 | Uppräkning av meddelande-uri |
| movedMessageIds | String[]& | Returnerar arrayen av meddelande-ID som har flyttats till skräppostmappen. |
| failedMessageIds | String[]& | Returnerar arrayen av meddelande-ID som inte har flyttats till skräppostmappen. |
| errorMessages | String[]& | Felmeddelanden för misslyckade operationer |

### Se även

* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
