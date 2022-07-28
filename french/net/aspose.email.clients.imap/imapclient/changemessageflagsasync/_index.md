---
title: ChangeMessageFlagsAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Change les drapeaux du message
type: docs
weight: 430
url: /fr/net/aspose.email.clients.imap/imapclient/changemessageflagsasync/
---
## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#changemessageflagsasync_41}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#changemessageflagsasync_17}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#changemessageflagsasync_13}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#changemessageflagsasync_36}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| flags | ImapMessageFlags | Les drapeaux à changer |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#changemessageflagsasync_8}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| flags | ImapMessageFlags | Les drapeaux à changer |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#changemessageflagsasync_37}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#changemessageflagsasync_9}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_51}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| flags | ImapMessageFlags | Les drapeaux à changer |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_31}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_23}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| flags | ImapMessageFlags | Les drapeaux à changer |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_3}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_50}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_30}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_22}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_2}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_55}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_35}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_27}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_7}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_54}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_34}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_26}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_6}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_47}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_43}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_19}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_15}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_46}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_42}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_18}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_14}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_39}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| flags | ImapMessageFlags | Les drapeaux à changer |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_11}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| flags | ImapMessageFlags | Les drapeaux à changer |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_38}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_10}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| messageInfoSet | IEnumerable`1 | L'ensemble de ImapMessageInfo |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags) {#changemessageflagsasync_48}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| flags | ImapMessageFlags | Les drapeaux à changer |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags) {#changemessageflagsasync_28}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| flags | ImapMessageFlags | Les drapeaux à enlever |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#changemessageflagsasync_20}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| flags | ImapMessageFlags | Les drapeaux à changer |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#changemessageflagsasync}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| flags | ImapMessageFlags | Les drapeaux à enlever |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, long) {#changemessageflagsasync_49}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid du message |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, long) {#changemessageflagsasync_29}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#changemessageflagsasync_21}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid du message |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#changemessageflagsasync_1}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags) {#changemessageflagsasync_52}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à changer |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags) {#changemessageflagsasync_32}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#changemessageflagsasync_24}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à changer |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#changemessageflagsasync_4}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, long) {#changemessageflagsasync_53}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, long) {#changemessageflagsasync_33}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#changemessageflagsasync_25}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startUid | String | L'UID de départ d'une liste de messages |
| endUid | String | L'UID de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#changemessageflagsasync_5}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| startSequence | Int32 | Le numéro de séquence de début d'une liste de messages |
| endSequence | Int32 | Le numéro de séquence de fin d'une liste de messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#changemessageflagsasync_44}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| flags | ImapMessageFlags | Les drapeaux à changer |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#changemessageflagsasync_40}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#changemessageflagsasync_16}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| flags | ImapMessageFlags | Les drapeaux à changer |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#changemessageflagsasync_12}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceSet | IEnumerable`1 | L'ensemble des numéros de séquence pour les messages |
| flags | ImapMessageFlags | Les drapeaux à enlever |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#changemessageflagsasync_45}

Change les drapeaux du message

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'ensemble d'UID pour les messages |
| flags | ImapMessageFlags | Les drapeaux à changer |
| modificationSequence | Int64 | Séquence de modifications. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc7162 |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
