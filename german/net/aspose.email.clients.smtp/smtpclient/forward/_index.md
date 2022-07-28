---
title: Forward
second_title: Aspose.Email für .NET-API-Referenz
description: Leitet die angegebene Nachricht an Empfänger weiter
type: docs
weight: 130
url: /de/net/aspose.email.clients.smtp/smtpclient/forward/
---
## Forward(IConnection, string, string, MailMessage) {#forward_2}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public void Forward(IConnection connection, string sender, string recipient, MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipient | String | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Forward(IConnection, string, MailAddressCollection, MailMessage) {#forward}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public void Forward(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Forward(string, string, MailMessage) {#forward_5}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public void Forward(string sender, string recipient, MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipient | String | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |

### Siehe auch

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Forward(string, MailAddressCollection, MailMessage) {#forward_3}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public void Forward(string sender, MailAddressCollection recipients, MailMessage message)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| message | MailMessage | Die Nachricht für eine Weiterleitung. |

### Siehe auch

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Forward(IConnection, string, MailAddressCollection, Stream) {#forward_1}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public void Forward(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| messageStream | Stream | Der Stream, der die Nachricht im EML-Format darstellt. |

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

---

## Forward(string, MailAddressCollection, Stream) {#forward_4}

Leitet die angegebene Nachricht an Empfänger weiter

```csharp
public void Forward(string sender, MailAddressCollection recipients, Stream messageStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sender | String | Absender der weitergeleiteten Nachricht. |
| recipients | MailAddressCollection | Empfänger der weitergeleiteten Nachricht. |
| messageStream | Stream | Der Stream, der die Nachricht im EML-Format darstellt. |

### Siehe auch

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
