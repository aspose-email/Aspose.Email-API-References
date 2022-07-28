---
title: DeleteMessages
second_title: Référence de l'API Aspose.Email pour .NET
description: Marque un message avec le numéro de séquence spécifié comme supprimé
type: docs
weight: 580
url: /fr/net/aspose.email.clients.imap/imapclient/deletemessages/
---
## DeleteMessages(IConnection, IEnumerable&lt;int&gt;) {#deletemessages_6}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;) {#deletemessages_8}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;) {#deletemessages_22}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;) {#deletemessages_24}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(IEnumerable<string> uidSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessages_7}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessages_10}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;, long) {#deletemessages_23}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long) {#deletemessages_26}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, bool) {#deletemessages_25}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessages_9}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long, bool) {#deletemessages_27}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessages_11}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int) {#deletemessages}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string) {#deletemessages_12}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(int, int) {#deletemessages_16}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(int startSequence, int endSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(string, string) {#deletemessages_28}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(string startUid, string endUid)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int, long) {#deletemessages_1}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long) {#deletemessages_14}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(int, int, long) {#deletemessages_17}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(int startSequence, int endSequence, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long) {#deletemessages_30}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(string, string, bool) {#deletemessages_29}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, bool) {#deletemessages_13}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long, bool) {#deletemessages_31}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long, bool) {#deletemessages_15}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_2}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_18}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_4}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_20}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_19}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_3}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_21}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, 
    bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_5}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
