---
title: AppendMessageAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Télécharge le message électronique dans le dossier actuel Si le dossier actuel na pas été spécifié le dossier par défaut est utilisé.
type: docs
weight: 370
url: /fr/net/aspose.email.clients.imap/imapclient/appendmessageasync/
---
## AppendMessageAsync(IConnection, MailMessage) {#appendmessageasync}

Télécharge le message électronique dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| message | MailMessage | Message électronique à télécharger |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, MailMessage) {#appendmessageasync_3}

télécharge le message électronique dans le dossier spécifié

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, 
    MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier qui recevra le message électronique |
| message | MailMessage | Message électronique à télécharger |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string) {#appendmessageasync_2}

Télécharge le message électronique dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string fileName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| fileName | String | Nom de fichier (*.eml) du message électronique qui sera téléchargé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, string) {#appendmessageasync_5}

télécharge le message électronique dans le dossier spécifié

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, string fileName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier qui recevra le message électronique |
| fileName | String | Nom de fichier (*.eml) du message électronique qui sera téléchargé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(MailMessage) {#appendmessageasync_8}

Télécharge le message électronique dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<string> AppendMessageAsync(MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | MailMessage | Message électronique à télécharger |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(string, MailMessage) {#appendmessageasync_11}

télécharge le message électronique dans le dossier spécifié

```csharp
public Task<string> AppendMessageAsync(string folderName, MailMessage message)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier qui recevra le message électronique |
| message | MailMessage | Message électronique à télécharger |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(string) {#appendmessageasync_10}

Télécharge le message électronique dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<string> AppendMessageAsync(string fileName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fileName | String | Nom de fichier (*.eml) du message électronique qui sera téléchargé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(string, string) {#appendmessageasync_13}

télécharge le message électronique dans le dossier spécifié

```csharp
public Task<string> AppendMessageAsync(string folderName, string fileName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier qui recevra le message électronique |
| fileName | String | Nom de fichier (*.eml) du message électronique qui sera téléchargé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, MailMessage, CancellationToken) {#appendmessageasync_1}

Télécharge le message électronique dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, MailMessage message, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| message | MailMessage | Message électronique à télécharger |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, MailMessage, CancellationToken) {#appendmessageasync_4}

télécharge le message électronique dans le dossier spécifié

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, 
    MailMessage message, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier qui recevra le message électronique |
| message | MailMessage | Message électronique à télécharger |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, CancellationToken) {#appendmessageasync_7}

Télécharge le message électronique dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string fileName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| fileName | String | Nom de fichier (*.eml) du message électronique qui sera téléchargé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, string, CancellationToken) {#appendmessageasync_6}

télécharge le message électronique dans le dossier spécifié

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, string fileName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier qui recevra le message électronique |
| fileName | String | Nom de fichier (*.eml) du message électronique qui sera téléchargé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(MailMessage, CancellationToken) {#appendmessageasync_9}

Télécharge le message électronique dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<string> AppendMessageAsync(MailMessage message, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| message | MailMessage | Message électronique à télécharger |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(string, MailMessage, CancellationToken) {#appendmessageasync_12}

télécharge le message électronique dans le dossier spécifié

```csharp
public Task<string> AppendMessageAsync(string folderName, MailMessage message, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier qui recevra le message électronique |
| message | MailMessage | Message électronique à télécharger |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(string, CancellationToken) {#appendmessageasync_15}

Télécharge le message électronique dans le dossier actuel Si le dossier actuel n'a pas été spécifié, le dossier par défaut est utilisé.

```csharp
public Task<string> AppendMessageAsync(string fileName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fileName | String | Nom de fichier (*.eml) du message électronique qui sera téléchargé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## AppendMessageAsync(string, string, CancellationToken) {#appendmessageasync_14}

télécharge le message électronique dans le dossier spécifié

```csharp
public Task<string> AppendMessageAsync(string folderName, string fileName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier qui recevra le message électronique |
| fileName | String | Nom de fichier (*.eml) du message électronique qui sera téléchargé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
