---
title: ListMessages
second_title: Référence de l'API Aspose.Email pour .NET
description: Liste les messages. Obtient une information pour chaque message
type: docs
weight: 870
url: /fr/net/aspose.email.clients.imap/imapclient/listmessages/
---
## ListMessages(string, ImapListFields, int) {#listmessages_21}

Liste les messages. Obtient une information pour chaque message

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, ImapListFields fieldsList, 
    int maxNumberOfMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |
| fieldsList | ImapListFields | Champs pouvant être récupérés depuis le serveur. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |

### Return_Value

ImapMessageInfoCollectionImapMessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, ImapListFields, int) {#listmessages_8}

Liste les messages. Obtient une information pour chaque message

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    ImapListFields fieldsList, int maxNumberOfMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier pour récupérer les messages. |
| fieldsList | ImapListFields | Champs pouvant être récupérés depuis le serveur. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |

### Return_Value

ImapMessageInfoCollectionImapMessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;string&gt;) {#listmessages_26}

Liste les messages. Obtient une information pour chaque message

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<string> uniqueIdLst)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |
| uniqueIdLst | IEnumerable`1 | Liste d'identifiants uniques pour[`ImapMessageInfo`](../../imapmessageinfo) à récupérer sur un serveur. |

### Return_Value

ImapMessageInfoCollectionImapMessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;int&gt;) {#listmessages_25}

Liste les messages. Obtient une information pour chaque message

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<int> sequenceNumberLst)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |
| sequenceNumberLst | IEnumerable`1 | liste de numéros de séquence pour[`ImapMessageInfo`](../../imapmessageinfo) à récupérer sur un serveur. |

### Return_Value

ImapMessageInfoCollectionImapMessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;string&gt;) {#listmessages_13}

Liste les messages. Obtient une information pour chaque message

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<string> uniqueIdLst)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier pour récupérer les messages. |
| uniqueIdLst | IEnumerable`1 | Liste d'identifiants uniques pour[`ImapMessageInfo`](../../imapmessageinfo) à récupérer sur un serveur. |

### Return_Value

ImapMessageInfoCollectionImapMessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;int&gt;) {#listmessages_12}

Liste les messages. Obtient une information pour chaque message

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<int> sequenceNumberLst)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier pour récupérer les messages. |
| sequenceNumberLst | IEnumerable`1 | liste de numéros de séquence pour[`ImapMessageInfo`](../../imapmessageinfo) à récupérer sur un serveur. |

### Return_Value

ImapMessageInfoCollectionImapMessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessages_11}

Obtient la liste des messages dans le dossier spécifié

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
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

Collection d'objets ImapMessageInfo

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Obtient la liste des messages dans le dossier actuel

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |

### Return_Value

Collection d'objets ImapMessageInfo

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, string) {#listmessages_7}

Obtient la liste des messages dans le dossier spécifié

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier pour récupérer les messages. |

### Return_Value

Collection d'objets ImapMessageInfo

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_4}

Obtient la liste des messages dans le dossier actuel

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, bool retrieveRecursively)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |

### Return_Value

Collection d'objets ImapMessageInfo

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, long) {#listmessages_6}

Obtient la liste des messages dans le dossier actuel qui ont une séquence de modification supérieure à la valeur spécifiée. S'il vous plaît, voir plus https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| modificationSequence | Int64 | Séquence de modifications |

### Return_Value

Collection de[`ImapMessageInfo`](../../imapmessageinfo) représentant les informations des messages.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, bool) {#listmessages_10}

Obtient la liste des messages dans le dossier spécifié

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| folderName | String | Dossier pour récupérer les messages. |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |

### Return_Value

Collection d'objets ImapMessageInfo

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Obtient la liste des messages dans le dossier actuel

```csharp
public ImapMessageInfoCollection ListMessages()
```

### Return_Value

Collection d'objets ImapMessageInfo

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_19}

Obtient la liste des messages dans le dossier actuel

```csharp
public ImapMessageInfoCollection ListMessages(IEnumerable<string> messageExtraFields)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Liste des paramètres supplémentaires pour un message qui sera demandé. |

### Return_Value

Collection d'objets ImapMessageInfo

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_16}

Obtient la liste des messages dans le dossier actuel

```csharp
public ImapMessageInfoCollection ListMessages(bool retrieveRecursively)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |

### Return_Value

Collection d'objets ImapMessageInfo

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string) {#listmessages_20}

Obtient la liste des messages dans le dossier spécifié

```csharp
public ImapMessageInfoCollection ListMessages(string folderName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |

### Return_Value

Collection d'objets ImapMessageInfo

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_23}

Obtient la liste des messages dans le dossier spécifié

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |

### Return_Value

Collection d'objets ImapMessageInfo

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, bool, IEnumerable&lt;string&gt;) {#listmessages_24}

Obtient la liste des messages dans le dossier spécifié

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively, 
    IEnumerable<string> messageExtraFields)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folderName | String | Dossier pour récupérer les messages. |
| retrieveRecursively | Boolean | Indique si les messages doivent être récupérés de manière récursive. |
| messageExtraFields | IEnumerable`1 | Liste des paramètres supplémentaires pour un message qui sera demandé. |

### Return_Value

Collection d'objets ImapMessageInfo

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(long) {#listmessages_18}

Obtient la liste des messages dans le dossier actuel qui ont une séquence de modification supérieure à la valeur spécifiée. S'il vous plaît, voir plus https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(long modificationSequence)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| modificationSequence | Int64 | Séquence de modifications |

### Return_Value

Collection de[`ImapMessageInfo`](../../imapmessageinfo) représentant les informations des messages.

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, MailQuery, int) {#listmessages_9}

Obtient la liste des messages dans le dossier actuel.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
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

## ListMessages(IConnection, MailQuery) {#listmessages_2}

Obtient la liste des messages dans le dossier actuel.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query)
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

## ListMessages(IConnection, MailQuery, int) {#listmessages_3}

Obtient la liste des messages dans le dossier actuel.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query, 
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

## ListMessages(MailQuery) {#listmessages_14}

Obtient la liste des messages dans le dossier actuel.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query)
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

## ListMessages(string, MailQuery, int) {#listmessages_22}

Obtient la liste des messages dans le dossier actuel.

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, MailQuery query, 
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

## ListMessages(MailQuery, int) {#listmessages_15}

Obtient la liste des messages dans le dossier actuel.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query, int maxNumberOfMessages)
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

## ListMessages(IConnection, int) {#listmessages_5}

Obtient la liste des messages dans le dossier actuel.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, int maxNumberOfMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |

### Return_Value

Collection de[`ImapMessageInfo`](../../imapmessageinfo) représentant les informations des messages.

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

## ListMessages(int) {#listmessages_17}

Obtient la liste des messages dans le dossier actuel.

```csharp
public ImapMessageInfoCollection ListMessages(int maxNumberOfMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |

### Return_Value

Collection de[`ImapMessageInfo`](../../imapmessageinfo) représentant les informations des messages.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* est négatif. |

### Voir également

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
