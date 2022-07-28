---
title: SendAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Crée et envoie le message spécifié.
type: docs
weight: 180
url: /fr/net/aspose.email.clients.smtp/smtpclient/sendasync/
---
## SendAsync(string, string, string, string) {#sendasync_18}

Crée et envoie le message spécifié.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| from | String | Une chaîne qui contient l'adresse de l'expéditeur du message. |
| recipients | String | String qui contient l'adresse des destinataires. |
| subject | String | Un sujet de message. |
| body | String | Un corps de message. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(MailMessage) {#sendasync_11}

Envoyer le message spécifié.

```csharp
public Task SendAsync(MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | MailMessage | MailMessage qui représente un message électronique. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(params MailMessage[]) {#sendasync_15}

Envoyer le message spécifié.

```csharp
public Task SendAsync(params MailMessage[] messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messages | MailMessage[] | Le tableau de MailMessage qui représente un e-mail à envoyer. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection) {#sendasync_13}

Envoyer la collection de messages spécifiée.

```csharp
public Task SendAsync(MailMessageCollection messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messages | MailMessageCollection | La collection de messages. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;) {#sendasync_16}

Envoyer les messages spécifiés.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator qui prend en charge une itération de message. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string) {#sendasync_7}

Crée et envoie le message spécifié.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| from | String | Une chaîne qui contient l'adresse de l'expéditeur du message. |
| recipients | String | String qui contient l'adresse des destinataires. |
| subject | String | Un sujet de message. |
| body | String | Un corps de message. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage) {#sendasync}

Envoyer le message spécifié.

```csharp
public Task SendAsync(IConnection connection, MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| message | MailMessage | MailMessage qui représente un message électronique. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IConnection, params MailMessage[]) {#sendasync_4}

Envoyer le message spécifié.

```csharp
public Task SendAsync(IConnection connection, params MailMessage[] messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messages | MailMessage[] | Le tableau de MailMessage qui représente un e-mail à envoyer. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection) {#sendasync_2}

Envoyer la collection de messages spécifiée.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messages | MailMessageCollection | La collection de messages. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#sendasync_5}

Envoyer les messages spécifiés.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messages | IEnumerable`1 | IEnumerator qui prend en charge une itération de message. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(string, string, string, string, CancellationToken) {#sendasync_19}

Crée et envoie le message spécifié.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| from | String | Une chaîne qui contient l'adresse de l'expéditeur du message. |
| recipients | String | String qui contient l'adresse des destinataires. |
| subject | String | Un sujet de message. |
| body | String | Un corps de message. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(MailMessage, CancellationToken) {#sendasync_12}

Envoyer le message spécifié.

```csharp
public Task SendAsync(MailMessage message, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | MailMessage | MailMessage qui représente un message électronique. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(CancellationToken, params MailMessage[]) {#sendasync_20}

Envoyer le message spécifié.

```csharp
public Task SendAsync(CancellationToken token, params MailMessage[] messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |
| messages | MailMessage[] | Le tableau de MailMessage qui représente un e-mail à envoyer. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection, CancellationToken) {#sendasync_14}

Envoyer la collection de messages spécifiée.

```csharp
public Task SendAsync(MailMessageCollection messages, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messages | MailMessageCollection | La collection de messages. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_17}

Envoyer les messages spécifiés.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator qui prend en charge une itération de message. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string, CancellationToken) {#sendasync_8}

Crée et envoie le message spécifié.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| from | String | Une chaîne qui contient l'adresse de l'expéditeur du message. |
| recipients | String | String qui contient l'adresse des destinataires. |
| subject | String | Un sujet de message. |
| body | String | Un corps de message. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage, CancellationToken) {#sendasync_1}

Envoyer le message spécifié.

```csharp
public Task SendAsync(IConnection connection, MailMessage message, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| message | MailMessage | MailMessage qui représente un message électronique. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IConnection, CancellationToken, params MailMessage[]) {#sendasync_9}

Envoyer le message spécifié.

```csharp
public Task SendAsync(IConnection connection, CancellationToken token, 
    params MailMessage[] messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |
| messages | MailMessage[] | Le tableau de MailMessage qui représente un e-mail à envoyer. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection, CancellationToken) {#sendasync_3}

Envoyer la collection de messages spécifiée.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messages | MailMessageCollection | La collection de messages. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_6}

Envoyer les messages spécifiés.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messages | IEnumerable`1 | IEnumerator qui prend en charge une itération de message. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## SendAsync(SmtpSend) {#sendasync_10}

```csharp
public Task SendAsync(SmtpSend parameters)
```

### Voir également

* class [SmtpSend](../../../aspose.email.clients.smtp.models/smtpsend)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
