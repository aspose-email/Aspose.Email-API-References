---
title: DeleteMessageAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Marque un message avec le numéro de séquence spécifié comme supprimé
type: docs
weight: 570
url: /fr/net/aspose.email.clients.imap/imapclient/deletemessageasync/
---
## DeleteMessageAsync(IConnection, int) {#deletemessageasync}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Numéro de séquence d'un message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string) {#deletemessageasync_4}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(int) {#deletemessageasync_12}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Numéro de séquence d'un message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(string) {#deletemessageasync_16}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long) {#deletemessageasync_1}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Numéro de séquence d'un message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long) {#deletemessageasync_7}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long) {#deletemessageasync_13}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Numéro de séquence d'un message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long) {#deletemessageasync_19}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool) {#deletemessageasync_17}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool) {#deletemessageasync_5}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool) {#deletemessageasync_20}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool) {#deletemessageasync_8}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
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

## DeleteMessageAsync(IConnection, int, CancellationToken) {#deletemessageasync_3}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Numéro de séquence d'un message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, CancellationToken) {#deletemessageasync_11}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, CancellationToken) {#deletemessageasync_15}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Numéro de séquence d'un message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_23}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long, CancellationToken) {#deletemessageasync_2}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Numéro de séquence d'un message |
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

## DeleteMessageAsync(IConnection, string, long, CancellationToken) {#deletemessageasync_10}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
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

## DeleteMessageAsync(int, long, CancellationToken) {#deletemessageasync_14}

Marque un message avec le numéro de séquence spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Numéro de séquence d'un message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, CancellationToken) {#deletemessageasync_22}

Marque un message avec l'identifiant unique spécifié comme supprimé

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool, CancellationToken) {#deletemessageasync_18}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| commitNow | Boolean | Définit si le message doit être validé maintenant. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool, CancellationToken) {#deletemessageasync_6}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
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

## DeleteMessageAsync(string, long, bool, CancellationToken) {#deletemessageasync_21}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
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

## DeleteMessageAsync(IConnection, string, long, bool, CancellationToken) {#deletemessageasync_9}

Marque un message avec l'identifiant unique spécifié comme supprimé et valide les suppressions si l'utilisateur le spécifie. Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
