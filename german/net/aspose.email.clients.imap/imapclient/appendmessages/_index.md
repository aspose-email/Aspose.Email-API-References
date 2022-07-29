---
title: AppendMessages
second_title: Aspose.Email für .NET-API-Referenz
description: Lädt die E-Mail-Nachricht in den aktuellen Ordner hoch Wenn der aktuelle Ordner nicht angegeben wurde wird der Standardordner verwendet.
type: docs
weight: 380
url: /de/net/aspose.email.clients.imap/imapclient/appendmessages/
---
## AppendMessages(IConnection, IEnumerable&lt;MailMessage&gt;) {#appendmessages}

Lädt die E-Mail-Nachricht in den aktuellen Ordner hoch Wenn der aktuelle Ordner nicht angegeben wurde, wird der Standardordner verwendet.

```csharp
public AppendMessagesResult AppendMessages(IConnection connection, 
    IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| messages | IEnumerable`1 | Aufzählung der hochzuladenden E-Mail-Nachrichten |

### Rückgabewert

Eine eindeutige ID der angehängten Nachricht

### Siehe auch

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## AppendMessages(IConnection, string, IEnumerable&lt;MailMessage&gt;) {#appendmessages_1}

Lädt die E-Mail-Nachricht in den angegebenen Ordner hoch

```csharp
public AppendMessagesResult AppendMessages(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| folderName | String | Ordner, der die E-Mail-Nachricht empfängt |
| messages | IEnumerable`1 | Aufzählung der hochzuladenden E-Mail-Nachrichten |

### Rückgabewert

Eine eindeutige ID der angehängten Nachricht

### Siehe auch

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## AppendMessages(IEnumerable&lt;MailMessage&gt;) {#appendmessages_2}

Lädt die E-Mail-Nachricht in den aktuellen Ordner hoch Wenn der aktuelle Ordner nicht angegeben wurde, wird der Standardordner verwendet.

```csharp
public AppendMessagesResult AppendMessages(IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messages | IEnumerable`1 | Aufzählung der hochzuladenden E-Mail-Nachrichten |

### Rückgabewert

Eine eindeutige ID der angehängten Nachricht

### Siehe auch

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## AppendMessages(string, IEnumerable&lt;MailMessage&gt;) {#appendmessages_3}

Lädt die E-Mail-Nachricht in den angegebenen Ordner hoch

```csharp
public AppendMessagesResult AppendMessages(string folderName, IEnumerable<MailMessage> messages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderName | String | Ordner, der die E-Mail-Nachricht empfängt |
| messages | IEnumerable`1 | Aufzählung der hochzuladenden E-Mail-Nachrichten |

### Rückgabewert

Eine eindeutige ID der angehängten Nachricht

### Siehe auch

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->