---
title: CopyMessages
second_title: Référence de l'API Aspose.Email pour .NET
description: Copiez le message
type: docs
weight: 500
url: /fr/net/aspose.email.clients.imap/imapclient/copymessages/
---
## CopyMessages(IConnection, int, int, string) {#copymessages}

Copiez le message

```csharp
public void CopyMessages(IConnection connection, int startSequence, int endSequence, 
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

## CopyMessages(int, int, string) {#copymessages_5}

Copier les messages

```csharp
public void CopyMessages(int startSequence, int endSequence, string folderName)
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

## CopyMessages(IConnection, string, string, string) {#copymessages_4}

Copier les messages

```csharp
public void CopyMessages(IConnection connection, string startUid, string endUid, string folderName)
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

## CopyMessages(string, string, string) {#copymessages_10}

Copier les messages

```csharp
public void CopyMessages(string startUid, string endUid, string folderName)
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

## CopyMessages(IEnumerable&lt;int&gt;, string, bool) {#copymessages_8}

Copier les messages

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
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

## CopyMessages(IConnection, IEnumerable&lt;int&gt;, string) {#copymessages_2}

Copiez le message

```csharp
public void CopyMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
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

## CopyMessages(IEnumerable&lt;int&gt;, string) {#copymessages_7}

Copier les messages

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName)
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

## CopyMessages(IConnection, IEnumerable&lt;string&gt;, string) {#copymessages_3}

Copier les messages

```csharp
public void CopyMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
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

## CopyMessages(IEnumerable&lt;string&gt;, string) {#copymessages_9}

Copier les messages

```csharp
public void CopyMessages(IEnumerable<string> uidSet, string folderName)
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

## CopyMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_1}

Copier les messages

```csharp
public void CopyMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## CopyMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_6}

Copier les messages

```csharp
public void CopyMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
