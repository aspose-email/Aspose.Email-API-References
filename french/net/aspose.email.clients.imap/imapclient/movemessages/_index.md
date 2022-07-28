---
title: MoveMessages
second_title: Référence de l'API Aspose.Email pour .NET
description: Déplace le message
type: docs
weight: 950
url: /fr/net/aspose.email.clients.imap/imapclient/movemessages/
---
## MoveMessages(IConnection, string, string, string) {#movemessages_8}

Déplace le message

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(string, string, string) {#movemessages_18}

Déplace le message

```csharp
public void MoveMessages(string startUid, string endUid, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string, bool) {#movemessages_7}

Déplace le message

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName, 
    bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string, bool) {#movemessages_17}

Déplace le message

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string) {#movemessages_6}

Déplace le message

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string) {#movemessages_16}

Déplace le message

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_3}

Déplace le message

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_13}

Déplace le message

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_2}

Déplace le message

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_12}

Déplace le message

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string, bool) {#movemessages_1}

Déplace le message

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(int, int, string, bool) {#movemessages_11}

Déplace le message

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string) {#movemessages}

Déplace le message

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(int, int, string) {#movemessages_10}

Déplace le message

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string, bool) {#movemessages_5}

Déplace le message

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string, bool) {#movemessages_15}

Déplace le message

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string) {#movemessages_4}

Déplace le message

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string) {#movemessages_14}

Déplace le message

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| folderName | String | Nom du dossier où un message doit être déplacé |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(IConnection, string, string, string, bool) {#movemessages_9}

Déplace le message

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## MoveMessages(string, string, string, bool) {#movemessages_19}

Déplace le message

```csharp
public void MoveMessages(string startUid, string endUid, string folderName, bool commitDeletions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| folderName | String | Nom du dossier où un message doit être déplacé |
| commitDeletions | Boolean | Spécifie si les suppressions doivent être validées. |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
