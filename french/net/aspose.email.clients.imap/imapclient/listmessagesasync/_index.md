---
title: ListMessagesAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Obtient la liste des messages dans le dossier actuel.
type: docs
weight: 880
url: /fr/net/aspose.email.clients.imap/imapclient/listmessagesasync/
---
## ListMessagesAsync(int, CancellationToken) {#listmessagesasync_28}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* est négatif. |

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_17}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier pour récupérer les messages. |
| modificationSequence | Int64 | Séquence de modifications |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |
| messageExtraFields | IEnumerable`1 | Liste des paramètres supplémentaires pour un message qui sera demandé. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Obtient la liste des messages dans le dossier actuel

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string) {#listmessagesasync_12}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier pour récupérer les messages. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_6}

Obtient la liste des messages dans le dossier actuel

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long) {#listmessagesasync_10}

Obtient la liste des messages dans le dossier actuel qui ont une séquence de modification supérieure à la valeur spécifiée. S'il vous plaît, voir plus https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| modificationSequence | Int64 | Séquence de modifications |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool) {#listmessagesasync_15}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier pour récupérer les messages. |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Obtient la liste des messages dans le dossier actuel

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync()
```

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;) {#listmessagesasync_31}

Obtient la liste des messages dans le dossier actuel

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Liste des paramètres supplémentaires pour un message qui sera demandé. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_25}

Obtient la liste des messages dans le dossier actuel

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(string) {#listmessagesasync_33}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool) {#listmessagesasync_36}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_37}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |
| messageExtraFields | IEnumerable`1 | Liste des paramètres supplémentaires pour un message qui sera demandé. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(long) {#listmessagesasync_29}

Obtient la liste des messages dans le dossier actuel qui ont une séquence de modification supérieure à la valeur spécifiée. S'il vous plaît, voir plus https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| modificationSequence | Int64 | Séquence de modifications |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int) {#listmessagesasync_13}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Emplacement des messages |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_2}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int) {#listmessagesasync_3}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_21}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int) {#listmessagesasync_34}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Emplacement des messages |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int) {#listmessagesasync_22}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int) {#listmessagesasync_8}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* est négatif. |

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(int) {#listmessagesasync_27}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* est négatif. |

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_18}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier pour récupérer les messages. |
| modificationSequence | Int64 | Séquence de modifications |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |
| messageExtraFields | IEnumerable`1 | Liste des paramètres supplémentaires pour un message qui sera demandé. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_20}

Obtient la liste des messages dans le dossier actuel

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, CancellationToken) {#listmessagesasync_19}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier pour récupérer les messages. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_7}

Obtient la liste des messages dans le dossier actuel

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long, CancellationToken) {#listmessagesasync_11}

Obtient la liste des messages dans le dossier actuel qui ont une séquence de modification supérieure à la valeur spécifiée. S'il vous plaît, voir plus https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| modificationSequence | Int64 | Séquence de modifications |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool, CancellationToken) {#listmessagesasync_16}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier pour récupérer les messages. |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_41}

Obtient la liste des messages dans le dossier actuel

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_32}

Obtient la liste des messages dans le dossier actuel

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Liste des paramètres supplémentaires pour un message qui sera demandé. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_26}

Obtient la liste des messages dans le dossier actuel

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(string, CancellationToken) {#listmessagesasync_40}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, CancellationToken) {#listmessagesasync_39}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_38}

Obtient la liste des messages dans le dossier spécifié

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |
| messageExtraFields | IEnumerable`1 | Liste des paramètres supplémentaires pour un message qui sera demandé. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(long, CancellationToken) {#listmessagesasync_30}

Obtient la liste des messages dans le dossier actuel qui ont une séquence de modification supérieure à la valeur spécifiée. S'il vous plaît, voir plus https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| modificationSequence | Int64 | Séquence de modifications |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int, CancellationToken) {#listmessagesasync_14}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Emplacement des messages |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_5}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int, CancellationToken) {#listmessagesasync_4}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_24}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int, CancellationToken) {#listmessagesasync_35}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Emplacement des messages |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int, CancellationToken) {#listmessagesasync_23}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente la requête de recherche. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Collection d'objets ImapMessageInfo.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int, CancellationToken) {#listmessagesasync_9}

Obtient la liste des messages dans le dossier actuel.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* est négatif. |

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
