---
title: MoveMessageAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Déplace le message
type: docs
weight: 940
url: /fr/net/aspose.email.clients.imap/imapclient/movemessageasync/
---
## MoveMessageAsync(int, string, bool) {#movemessageasync_9}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool) {#movemessageasync_13}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string) {#movemessageasync}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string) {#movemessageasync_4}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string) {#movemessageasync_8}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string) {#movemessageasync_12}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool, CancellationToken) {#movemessageasync_2}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool, CancellationToken) {#movemessageasync_6}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, bool, CancellationToken) {#movemessageasync_10}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool, CancellationToken) {#movemessageasync_14}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, CancellationToken) {#movemessageasync_3}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, CancellationToken) {#movemessageasync_7}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, CancellationToken) {#movemessageasync_11}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, CancellationToken) {#movemessageasync_15}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool) {#movemessageasync_1}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool) {#movemessageasync_5}

Déplace le message

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
