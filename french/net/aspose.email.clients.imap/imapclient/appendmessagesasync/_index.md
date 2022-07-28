---
title: AppendMessagesAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: télécharge les messages électroniques dans le dossier actuel
type: docs
weight: 390
url: /fr/net/aspose.email.clients.imap/imapclient/appendmessagesasync/
---
## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_2}

télécharge les messages électroniques dans le dossier actuel

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier qui recevra le message électronique |
| messages | IEnumerable`1 | Énumération des e-mails à télécharger |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_4}

Télécharge le message électronique dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messages | IEnumerable`1 | Énumération des e-mails à télécharger |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_6}

télécharge les messages électroniques dans le dossier actuel

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier qui recevra le message électronique |
| messages | IEnumerable`1 | Énumération des e-mails à télécharger |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_1}

Télécharge les messages électroniques dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messages | IEnumerable`1 | Énumération des e-mails à télécharger |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_3}

télécharge les messages électroniques dans le dossier actuel

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier qui recevra le message électronique |
| messages | IEnumerable`1 | Énumération des e-mails à télécharger |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_5}

Télécharge le message électronique dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messages | IEnumerable`1 | Énumération des e-mails à télécharger |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_7}

télécharge les messages électroniques dans le dossier actuel

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier qui recevra le message électronique |
| messages | IEnumerable`1 | Énumération des e-mails à télécharger |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync}

Télécharge les messages électroniques dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messages | IEnumerable`1 | Énumération des e-mails à télécharger |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
