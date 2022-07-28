---
title: ListMessages
second_title: Référence de l'API Aspose.Email pour .NET
description: Liste les messages. Obtient une information pour chaque message
type: docs
weight: 290
url: /fr/net/aspose.email.clients.pop3/pop3client/listmessages/
---
## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_13}

Liste les messages. Obtient une information pour chaque message

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<string> uniqueIdLst)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueIdLst | IEnumerable`1 | Liste d'identifiants uniques pour[`Pop3MessageInfo`](../../pop3messageinfo) à récupérer sur un serveur. |

### Return_Value

Pop3MessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;int&gt;) {#listmessages_12}

Liste les messages. Obtient une information pour chaque message

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<int> sequenceNumberLst)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumberLst | IEnumerable`1 | liste de numéros de séquence pour[`Pop3MessageInfo`](../../pop3messageinfo) à récupérer sur un serveur. |

### Return_Value

Pop3MessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;string&gt;) {#listmessages_7}

Liste les messages. Obtient une information pour chaque message

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<string> uniqueIdLst)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueIdLst | IEnumerable`1 | Liste d'identifiants uniques pour[`Pop3MessageInfo`](../../pop3messageinfo) à récupérer sur un serveur. |

### Return_Value

Pop3MessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;int&gt;) {#listmessages_6}

Liste les messages. Obtient une information pour chaque message

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<int> sequenceNumberLst)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumberLst | IEnumerable`1 | liste de numéros de séquence pour[`Pop3MessageInfo`](../../pop3messageinfo) à récupérer sur un serveur. |

### Return_Value

Pop3MessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Liste les messages. Obtient une information pour chaque message

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |

### Return_Value

Pop3MessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_5}

Liste les messages. Obtient une information pour chaque message

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, bool closeTransaction)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |

### Return_Value

Pop3MessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_4}

Liste les messages.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, MailQuery query)
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

## ListMessages(IConnection, Pop3ListFields) {#listmessages_2}

Liste les messages.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |

### Return_Value

Pop3MessageInfoCollection

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

## ListMessages(IConnection, Pop3ListFields, bool, MailQuery) {#listmessages_3}

Liste les messages.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |
| query | MailQuery | La[`MailQuery`](../../../aspose.email.tools.search/mailquery) objet. |

### Return_Value

Pop3MessageInfoCollection

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Liste les messages. Obtient une information pour chaque message

```csharp
public Pop3MessageInfoCollection ListMessages()
```

### Return_Value

Pop3MessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_11}

Liste les messages. Obtient une information pour chaque message

```csharp
public Pop3MessageInfoCollection ListMessages(bool closeTransaction)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |

### Return_Value

Pop3MessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_10}

Liste les messages.

```csharp
public Pop3MessageInfoCollection ListMessages(MailQuery query)
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

## ListMessages(Pop3ListFields) {#listmessages_8}

Liste les messages.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |

### Return_Value

Pop3MessageInfoCollection

### Remarques

Notez que les messages marqués comme supprimés ne sont pas répertoriés

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields, bool, MailQuery) {#listmessages_9}

Liste les messages.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields, bool closeTransaction, 
    MailQuery query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fields | Pop3ListFields | Les champs que nous voulons obtenir |
| closeTransaction | Boolean | Indique si la transaction en cours doit être fermée, avant que la liste ne soit récupérée. |
| query | MailQuery | La[`MailQuery`](../../../aspose.email.tools.search/mailquery) objet. |

### Return_Value

Pop3MessageInfoCollection

### Voir également

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
