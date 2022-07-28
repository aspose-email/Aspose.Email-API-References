---
title: FetchMessageAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Récupère le message
type: docs
weight: 660
url: /fr/net/aspose.email.clients.imap/imapclient/fetchmessageasync/
---
## FetchMessageAsync(IConnection, int) {#fetchmessageasync}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, bool) {#fetchmessageasync_1}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| ignoreAttachment | Boolean | Une valeur qui définit si les pièces jointes ne doivent pas être chargées. S'il est défini sur`vrai` , seuls les en-têtes de message, le corps du message et les informations de pièce jointe sont récupérés. Le contenu de la pièce jointe n'est pas chargé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessageAsync(int) {#fetchmessageasync_6}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool) {#fetchmessageasync_7}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| ignoreAttachment | Boolean | Une valeur qui définit si les pièces jointes ne doivent pas être chargées. S'il est défini sur`vrai` , seuls les en-têtes de message, le corps du message et les informations de pièce jointe sont récupérés. Le contenu de la pièce jointe n'est pas chargé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string) {#fetchmessageasync_4}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'identifiant unique du message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessageAsync(string) {#fetchmessageasync_10}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'identifiant unique du message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, CancellationToken) {#fetchmessageasync_3}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, bool, CancellationToken) {#fetchmessageasync_2}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| ignoreAttachment | Boolean | Une valeur qui définit si les pièces jointes ne doivent pas être chargées. S'il est défini sur`vrai` , seuls les en-têtes de message, le corps du message et les informations de pièce jointe sont récupérés. Le contenu de la pièce jointe n'est pas chargé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessageAsync(int, CancellationToken) {#fetchmessageasync_9}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool, CancellationToken) {#fetchmessageasync_8}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| ignoreAttachment | Boolean | Une valeur qui définit si les pièces jointes ne doivent pas être chargées. S'il est défini sur`vrai` , seuls les en-têtes de message, le corps du message et les informations de pièce jointe sont récupérés. Le contenu de la pièce jointe n'est pas chargé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string, CancellationToken) {#fetchmessageasync_5}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'identifiant unique du message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessageAsync(string, CancellationToken) {#fetchmessageasync_11}

Récupère le message

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'identifiant unique du message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
