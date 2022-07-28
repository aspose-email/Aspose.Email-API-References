---
title: ListMessagesAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Liste les messages. Obtient une information pour chaque message
type: docs
weight: 300
url: /fr/net/aspose.email.clients.pop3/pop3client/listmessagesasync/
---
## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Liste les messages. Obtient une information pour chaque message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_8}

Liste les messages. Obtient une information pour chaque message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_6}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| query | MailQuery | La[`MailQuery`](../../../aspose.email.tools.search/mailquery) objet. |

### Return_Value

Collection d'objets Pop3MessageInfo.

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields) {#listmessagesasync_2}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery) {#listmessagesasync_3}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |
| query | MailQuery | La[`MailQuery`](../../../aspose.email.tools.search/mailquery) objet. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Liste les messages. Obtient une information pour chaque message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync()
```

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_17}

Liste les messages. Obtient une information pour chaque message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_15}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| query | MailQuery | La[`MailQuery`](../../../aspose.email.tools.search/mailquery) objet. |

### Return_Value

Collection d'objets Pop3MessageInfo.

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields) {#listmessagesasync_11}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery) {#listmessagesasync_12}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |
| query | MailQuery | La[`MailQuery`](../../../aspose.email.tools.search/mailquery) objet. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_10}

Liste les messages. Obtient une information pour chaque message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_9}

Liste les messages. Obtient une information pour chaque message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_7}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| query | MailQuery | La[`MailQuery`](../../../aspose.email.tools.search/mailquery) objet. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Collection d'objets Pop3MessageInfo.

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, CancellationToken) {#listmessagesasync_5}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_4}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |
| query | MailQuery | La[`MailQuery`](../../../aspose.email.tools.search/mailquery) objet. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_19}

Liste les messages. Obtient une information pour chaque message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_18}

Liste les messages. Obtient une information pour chaque message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_16}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| query | MailQuery | La[`MailQuery`](../../../aspose.email.tools.search/mailquery) objet. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Collection d'objets Pop3MessageInfo.

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, CancellationToken) {#listmessagesasync_14}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_13}

Liste les messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |
| query | MailQuery | La[`MailQuery`](../../../aspose.email.tools.search/mailquery) objet. |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
