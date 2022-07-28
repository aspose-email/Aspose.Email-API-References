---
title: MarkAsJunk
second_title: Aspose.Email für .NET-API-Referenz
description: Die MarkAsJunk-Methode verschiebt E-Mail-Nachrichten in den Junk-E-Mail-Ordner und blockiert den Absender der Nachricht.
type: docs
weight: 1270
url: /de/net/aspose.email.clients.exchange.webservice/iewsclient/markasjunk/
---
## MarkAsJunk(bool, params string[]) {#markasjunk_3}

Die MarkAsJunk-Methode verschiebt E-Mail-Nachrichten in den Junk-E-Mail-Ordner und blockiert den Absender der Nachricht.

```csharp
public string[] MarkAsJunk(bool isJunk, params string[] messageUriEn)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isJunk | Boolean | Gibt an, ob Nachrichten als Junk-Mail markiert sind. Wenn der Wert „true“ ist, wird der Absender der Nachricht zur Sperrliste hinzugefügt. Wenn der Wert „false“ ist, wird der Absender der Nachricht aus der Sperrliste entfernt. |
| messageUriEn | String[] | Array von Nachrichten-URI |

### Rückgabewert

Gibt das Array von Nachrichten-IDs zurück, die in den Junk-Mail-Ordner verschoben werden.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, params string[]) {#markasjunk_1}

Die MarkAsJunk-Methode verschiebt E-Mail-Nachrichten in den Junk-E-Mail-Ordner und blockiert den Absender der Nachricht.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, params string[] messageUriEn)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isJunk | Boolean | Gibt an, ob Nachrichten als Junk-Mail markiert sind. Wenn der Wert „true“ ist, wird der Absender der Nachricht zur Sperrliste hinzugefügt. Wenn der Wert „false“ ist, wird der Absender der Nachricht aus der Sperrliste entfernt. |
| moveItem | Boolean | Gibt an, ob Nachrichten in den Junk-Mail-Ordner verschoben werden. |
| messageUriEn | String[] | Array von Nachrichten-URI |

### Rückgabewert

Gibt das Array von Nachrichten-IDs zurück, die in den Junk-Mail-Ordner verschoben werden.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## MarkAsJunk(bool, IEnumerable&lt;string&gt;) {#markasjunk_2}

Die MarkAsJunk-Methode verschiebt E-Mail-Nachrichten in den Junk-E-Mail-Ordner und blockiert den Absender der Nachricht.

```csharp
public string[] MarkAsJunk(bool isJunk, IEnumerable<string> messageUriEn)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isJunk | Boolean | Gibt an, ob Nachrichten als Junk-Mail markiert sind. Wenn der Wert „true“ ist, wird der Absender der Nachricht zur Sperrliste hinzugefügt. Wenn der Wert „false“ ist, wird der Absender der Nachricht aus der Sperrliste entfernt. |
| messageUriEn | IEnumerable`1 | Aufzählung der Nachrichten-URI |

### Rückgabewert

Gibt die Element-ID der als Junk-Mail markierten Nachricht zurück.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;) {#markasjunk}

Die MarkAsJunk-Methode verschiebt E-Mail-Nachrichten in den Junk-E-Mail-Ordner und blockiert den Absender der Nachricht.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isJunk | Boolean | Gibt an, ob Nachrichten als Junk-Mail markiert sind. Wenn der Wert „true“ ist, wird der Absender der Nachricht zur Sperrliste hinzugefügt. Wenn der Wert „false“ ist, wird der Absender der Nachricht aus der Sperrliste entfernt. |
| moveItem | Boolean | Gibt an, ob Nachrichten in den Junk-Mail-Ordner verschoben werden. |
| messageUriEn | IEnumerable`1 | Aufzählung der Nachrichten-URI |

### Rückgabewert

Gibt das Array von Nachrichten-IDs zurück, die in den Junk-Mail-Ordner verschoben werden.

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) {#markasjunk_4}

Die MarkAsJunk-Methode verschiebt E-Mail-Nachrichten in den Junk-E-Mail-Ordner und blockiert den Absender der Nachricht.

```csharp
public void MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn, 
    out string[] movedMessageIds, out string[] failedMessageIds, out string[] errorMessages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isJunk | Boolean | Gibt an, ob Nachrichten als Junk-Mail markiert sind. Wenn der Wert „true“ ist, wird der Absender der Nachricht zur Sperrliste hinzugefügt. Wenn der Wert „false“ ist, wird der Absender der Nachricht aus der Sperrliste entfernt. |
| moveItem | Boolean | Gibt an, ob Nachrichten in den Junk-Mail-Ordner verschoben werden. |
| messageUriEn | IEnumerable`1 | Aufzählung der Nachrichten-URI |
| movedMessageIds | String[]& | Gibt das Array von Nachrichten-IDs zurück, die in den Junk-Mail-Ordner verschoben werden. |
| failedMessageIds | String[]& | Gibt das Array von Nachrichten-IDs zurück, die nicht in den Junk-Mail-Ordner verschoben wurden. |
| errorMessages | String[]& | Fehlermeldungen für fehlgeschlagene Operationen |

### Siehe auch

* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
