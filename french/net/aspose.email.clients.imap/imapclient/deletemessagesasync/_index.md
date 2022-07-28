---
title: DeleteMessagesAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Marque un message avec lidentifiant unique spécifié comme supprimé
type: docs
weight: 590
url: /fr/net/aspose.email.clients.imap/imapclient/deletemessagesasync/
---
## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessagesasync_19}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long) {#deletemessagesasync_45}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long) {#deletemessagesasync_51}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_49}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_17}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_52}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_20}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int) {#deletemessagesasync}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string) {#deletemessagesasync_24}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int) {#deletemessagesasync_32}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string) {#deletemessagesasync_56}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long) {#deletemessagesasync_1}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long) {#deletemessagesasync_27}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long) {#deletemessagesasync_33}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long) {#deletemessagesasync_59}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool) {#deletemessagesasync_57}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool) {#deletemessagesasync_25}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool) {#deletemessagesasync_60}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool) {#deletemessagesasync_28}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_4}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_36}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_7}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_39}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_37}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_5}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_40}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_8}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_15}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_23}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_47}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_55}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_14}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_22}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_46}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_54}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_50}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_18}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_53}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_21}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, CancellationToken) {#deletemessagesasync_3}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, CancellationToken) {#deletemessagesasync_31}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, CancellationToken) {#deletemessagesasync_35}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, CancellationToken) {#deletemessagesasync_63}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long, CancellationToken) {#deletemessagesasync_2}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, CancellationToken) {#deletemessagesasync_30}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long, CancellationToken) {#deletemessagesasync_34}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, CancellationToken) {#deletemessagesasync_62}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool, CancellationToken) {#deletemessagesasync_58}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool, CancellationToken) {#deletemessagesasync_26}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool, CancellationToken) {#deletemessagesasync_61}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool, CancellationToken) {#deletemessagesasync_29}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_11}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
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

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_43}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_10}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
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

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_42}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_38}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_6}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
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

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_41}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_9}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo pour la suppression |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#deletemessagesasync_12}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#deletemessagesasync_16}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;) {#deletemessagesasync_44}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;) {#deletemessagesasync_48}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessagesasync_13}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
