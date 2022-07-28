---
title: ForwardAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Transfère le message spécifié au destinataire
type: docs
weight: 140
url: /fr/net/aspose.email.clients.smtp/smtpclient/forwardasync/
---
## ForwardAsync(IConnection, string, string, MailMessage) {#forwardasync_4}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sender | String | Expéditeur du message transféré. |
| recipient | String | Destinataire du message transféré. |
| message | MailMessage | Le message pour un transfert. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage) {#forwardasync}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sender | String | Expéditeur du message transféré. |
| recipients | MailAddressCollection | Destinataires du message transféré. |
| message | MailMessage | Le message pour un transfert. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage) {#forwardasync_10}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sender | String | Expéditeur du message transféré. |
| recipient | String | Destinataire du message transféré. |
| message | MailMessage | Le message pour un transfert. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage) {#forwardasync_6}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sender | String | Expéditeur du message transféré. |
| recipients | MailAddressCollection | Destinataires du message transféré. |
| message | MailMessage | Le message pour un transfert. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream) {#forwardasync_2}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sender | String | Expéditeur du message transféré. |
| recipients | MailAddressCollection | Destinataires du message transféré. |
| messageStream | Stream | Le flux qui représente le message au format eml. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream) {#forwardasync_8}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sender | String | Expéditeur du message transféré. |
| recipients | MailAddressCollection | Destinataires du message transféré. |
| messageStream | Stream | Le flux qui représente le message au format eml. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, string, MailMessage, CancellationToken) {#forwardasync_5}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sender | String | Expéditeur du message transféré. |
| recipient | String | Destinataire du message transféré. |
| message | MailMessage | Le message pour un transfert. |
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

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_1}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sender | String | Expéditeur du message transféré. |
| recipients | MailAddressCollection | Destinataires du message transféré. |
| message | MailMessage | Le message pour un transfert. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage, CancellationToken) {#forwardasync_11}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sender | String | Expéditeur du message transféré. |
| recipient | String | Destinataire du message transféré. |
| message | MailMessage | Le message pour un transfert. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_7}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sender | String | Expéditeur du message transféré. |
| recipients | MailAddressCollection | Destinataires du message transféré. |
| message | MailMessage | Le message pour un transfert. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_3}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sender | String | Expéditeur du message transféré. |
| recipients | MailAddressCollection | Destinataires du message transféré. |
| messageStream | Stream | Le flux qui représente le message au format eml. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_9}

Transfère le message spécifié au destinataire

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sender | String | Expéditeur du message transféré. |
| recipients | MailAddressCollection | Destinataires du message transféré. |
| messageStream | Stream | Le flux qui représente le message au format eml. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* espace de noms [Aspose.Email.Clients.Smtp](../../smtpclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
