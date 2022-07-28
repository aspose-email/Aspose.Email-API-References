---
title: ForwardAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Leitet die angegebene Nachricht an Empfänger weiter
type: docs
weight: 140
url: /de/net/aspose.email.clients.smtp/smtpclient/forwardasync/
---
## ForwardAsync(IConnection, string, string, MailMessage) {#forwardasync_4}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipient | String | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage) {#forwardasync}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage) {#forwardasync_10}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipient | String | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage) {#forwardasync_6}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream) {#forwardasync_2}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| messageStream | Stream | Der Stream, der die Nachricht im EML-Format darstellt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream) {#forwardasync_8}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| messageStream | Stream | Der Stream, der die Nachricht im EML-Format darstellt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, string, MailMessage, CancellationToken) {#forwardasync_5}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipient | String | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_1}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage, CancellationToken) {#forwardasync_11}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipient | String | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_7}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_3}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| messageStream | Stream | Der Stream, der die Nachricht im EML-Format darstellt. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_9}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| messageStream | Stream | Der Stream, der die Nachricht im EML-Format darstellt. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
