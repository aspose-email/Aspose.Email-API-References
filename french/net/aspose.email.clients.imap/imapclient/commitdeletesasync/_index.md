---
title: CommitDeletesAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Valider les suppressions
type: docs
weight: 470
url: /fr/net/aspose.email.clients.imap/imapclient/commitdeletesasync/
---
## CommitDeletesAsync(IConnection) {#commitdeletesasync_1}

Valider les suppressions

```csharp
public Task CommitDeletesAsync(IConnection connection)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int) {#commitdeletesasync_2}

Valider les suppressions

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sleep | Int32 | Temps d'attente pour terminer l'opération en millisecondes |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync() {#commitdeletesasync}

Valider les suppressions

```csharp
public Task CommitDeletesAsync()
```

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(int) {#commitdeletesasync_11}

Valider les suppressions

```csharp
public Task CommitDeletesAsync(int sleep)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sleep | Int32 | Temps d'attente pour terminer l'opération en millisecondes |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;) {#commitdeletesasync_13}

Valider les suppressions Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Ensemble d'identifiants uniques pour les messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(string) {#commitdeletesasync_15}

Valider les suppressions Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid d'un message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, string) {#commitdeletesasync_16}

Valider les suppressions Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid)
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

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;) {#commitdeletesasync_4}

Valider les suppressions Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | Ensemble d'identifiants uniques pour les messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string) {#commitdeletesasync_6}

Valider les suppressions

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid d'un message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, string) {#commitdeletesasync_7}

Valider les suppressions Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid)
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

## CommitDeletesAsync(IConnection, CancellationToken) {#commitdeletesasync_10}

Valider les suppressions

```csharp
public Task CommitDeletesAsync(IConnection connection, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int, CancellationToken) {#commitdeletesasync_3}

Valider les suppressions

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sleep | Int32 | Temps d'attente pour terminer l'opération en millisecondes |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(CancellationToken) {#commitdeletesasync_19}

Valider les suppressions

```csharp
public Task CommitDeletesAsync(CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(int, CancellationToken) {#commitdeletesasync_12}

Valider les suppressions

```csharp
public Task CommitDeletesAsync(int sleep, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sleep | Int32 | Temps d'attente pour terminer l'opération en millisecondes |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_14}

Valider les suppressions Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Ensemble d'identifiants uniques pour les messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, CancellationToken) {#commitdeletesasync_18}

Valider les suppressions Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'uid d'un message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, string, CancellationToken) {#commitdeletesasync_17}

Valider les suppressions Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid, CancellationToken token)
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

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_5}

Valider les suppressions Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uidSet | IEnumerable`1 | Ensemble d'identifiants uniques pour les messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, CancellationToken) {#commitdeletesasync_9}

Valider les suppressions

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'uid d'un message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, string, CancellationToken) {#commitdeletesasync_8}

Valider les suppressions Cette méthode ne fonctionne que si le serveur prend en charge l'extension UIDPLUS. S'il vous plaît, lisez plus https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid, 
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
