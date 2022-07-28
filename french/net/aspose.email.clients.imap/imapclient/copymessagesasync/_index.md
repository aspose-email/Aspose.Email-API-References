---
title: CopyMessagesAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Copiez le message
type: docs
weight: 510
url: /fr/net/aspose.email.clients.imap/imapclient/copymessagesasync/
---
## CopyMessagesAsync(IConnection, int, int, string) {#copymessagesasync}

Copiez le message

```csharp
public Task CopyMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(int, int, string) {#copymessagesasync_10}

Copier les messages

```csharp
public Task CopyMessagesAsync(int startSequence, int endSequence, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, string, string, string) {#copymessagesasync_8}

Copier les messages

```csharp
public Task CopyMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(string, string, string) {#copymessagesasync_19}

Copier les messages

```csharp
public Task CopyMessagesAsync(string startUid, string endUid, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string) {#copymessagesasync_4}

Copiez le message

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;int&gt;, string) {#copymessagesasync_14}

Copier les messages

```csharp
public Task CopyMessagesAsync(IEnumerable<int> sequenceSet, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string) {#copymessagesasync_6}

Copier les messages

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;string&gt;, string) {#copymessagesasync_17}

Copier les messages

```csharp
public Task CopyMessagesAsync(IEnumerable<string> uidSet, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessagesasync_2}

Copier les messages

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessagesasync_12}

Copier les messages

```csharp
public Task CopyMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, int, int, string, CancellationToken) {#copymessagesasync_1}

Copiez le message

```csharp
public Task CopyMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
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

## CopyMessagesAsync(int, int, string, CancellationToken) {#copymessagesasync_11}

Copier les messages

```csharp
public Task CopyMessagesAsync(int startSequence, int endSequence, string folderName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, string, string, string, CancellationToken) {#copymessagesasync_9}

Copier les messages

```csharp
public Task CopyMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
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

## CopyMessagesAsync(string, string, string, CancellationToken) {#copymessagesasync_20}

Copier les messages

```csharp
public Task CopyMessagesAsync(string startUid, string endUid, string folderName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) {#copymessagesasync_5}

Copiez le message

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
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

## CopyMessagesAsync(IEnumerable&lt;int&gt;, string, CancellationToken) {#copymessagesasync_16}

Copier les messages

```csharp
public Task CopyMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) {#copymessagesasync_7}

Copier les messages

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
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

## CopyMessagesAsync(IEnumerable&lt;string&gt;, string, CancellationToken) {#copymessagesasync_18}

Copier les messages

```csharp
public Task CopyMessagesAsync(IEnumerable<string> uidSet, string folderName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#copymessagesasync_3}

Copier les messages

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| folderName | String | Nom du dossier où un message doit être déplacé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CopyMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#copymessagesasync_13}

Copier les messages

```csharp
public Task CopyMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| folderName | String | Nom du dossier où un message doit être déplacé |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
