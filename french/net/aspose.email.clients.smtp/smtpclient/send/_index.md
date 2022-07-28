---
title: Send
second_title: Référence de l'API Aspose.Email pour .NET
description: Crée et envoie le message spécifié.
type: docs
weight: 170
url: /fr/net/aspose.email.clients.smtp/smtpclient/send/
---
## Send(string, string, string, string) {#send_9}

Crée et envoie le message spécifié.

```csharp
public void Send(string from, string recipients, string subject, string body)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| from | String | Une chaîne qui contient l'adresse de l'expéditeur du message. |
| recipients | String | String qui contient l'adresse des destinataires. |
| subject | String | Un sujet de message. |
| body | String | Un corps de message. |

### Voir également

* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## Send(MailMessage) {#send_5}

Envoyer le message spécifié.

```csharp
public void Send(MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | MailMessage | MailMessage qui représente un message électronique. |

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## Send(params MailMessage[]) {#send_7}

Envoyer le message spécifié.

```csharp
public void Send(params MailMessage[] messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messages | MailMessage[] | Le tableau de MailMessage qui représente un e-mail à envoyer. |

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## Send(MailMessageCollection) {#send_6}

Envoyer la collection de messages spécifiée.

```csharp
public void Send(MailMessageCollection messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messages | MailMessageCollection | La collection de messages. |

### Voir également

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## Send(IEnumerable&lt;MailMessage&gt;) {#send_8}

Envoyer les messages spécifiés.

```csharp
public void Send(IEnumerable<MailMessage> messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator qui prend en charge une itération de message. |

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## Send(IConnection, string, string, string, string) {#send_4}

Crée et envoie le message spécifié.

```csharp
public void Send(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| from | String | Une chaîne qui contient l'adresse de l'expéditeur du message. |
| recipients | String | String qui contient l'adresse des destinataires. |
| subject | String | Un sujet de message. |
| body | String | Un corps de message. |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## Send(IConnection, MailMessage) {#send}

Envoyer le message spécifié.

```csharp
public void Send(IConnection connection, MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| message | MailMessage | MailMessage qui représente un message électronique. |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## Send(IConnection, params MailMessage[]) {#send_2}

Envoyer le message spécifié.

```csharp
public void Send(IConnection connection, params MailMessage[] messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messages | MailMessage[] | Le tableau de MailMessage qui représente un e-mail à envoyer. |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## Send(IConnection, MailMessageCollection) {#send_1}

Envoyer la collection de messages spécifiée.

```csharp
public void Send(IConnection connection, MailMessageCollection messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messages | MailMessageCollection | La collection de messages. |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## Send(IConnection, IEnumerable&lt;MailMessage&gt;) {#send_3}

Envoyer les messages spécifiés.

```csharp
public void Send(IConnection connection, IEnumerable<MailMessage> messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messages | IEnumerable`1 | IEnumerator qui prend en charge une itération de message. |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
