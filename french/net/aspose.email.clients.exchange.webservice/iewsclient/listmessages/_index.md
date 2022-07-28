---
title: ListMessages
second_title: Référence de l'API Aspose.Email pour .NET
description: Liste les messages.
type: docs
weight: 1140
url: /fr/net/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---
## ListMessages(string) {#listmessages_2}

Liste les messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Le dossier. |

### Return_Value

UN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_3}

Liste les messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Le dossier. |
| options | ExchangeListMessagesOptions | Spécifie les paramètres de la liste |

### Return_Value

UN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_8}

Liste les messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Le dossier. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages |

### Return_Value

UN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_9}

Liste les messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Le dossier. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages |
| options | ExchangeListMessagesOptions | Spécifie les paramètres de la liste |

### Return_Value

UN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_13}

Lister les messages dans le dossier spécifié

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, bool recursive)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| mailbox | String | Boîte aux lettres utilisée pour initialiser la classe d'ID de dossier. |
| folder | String | Un dossier pour rechercher des messages dans |
| recursive | Boolean | Indique s'il s'agit d'une liste récursive ou non |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) qui contient des messages du dossier spécifié

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, string, MailQuery) {#listmessages_12}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, MailQuery query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| mailbox | String | Boîte aux lettres utilisée pour initialiser la classe d'ID de dossier. |
| folder | String | Un dossier dans lequel rechercher des messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente les critères de recherche de message. |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_7}

Lister les messages dans le dossier spécifié

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier pour rechercher des messages dans |
| recursive | Boolean | Indique s'il s'agit d'une liste récursive ou non |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) qui contient des messages du dossier spécifié

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) {#listmessages_4}

Lister les messages dans le dossier spécifié

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options, IEnumerable<PropertyDescriptor> extendedProperties)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier pour rechercher des messages dans |
| options | ExchangeListMessagesOptions | Spécifie les paramètres de la liste |
| extendedProperties | IEnumerable`1 | Propriétés étendues des messages récupérés |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) qui contient des messages du dossier spécifié

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery) {#listmessages_5}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente les critères de recherche de message. |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_6}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente les critères de recherche de message. |
| recursive | Boolean | Indique si la liste récursive ou non. |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery, bool) {#listmessages_11}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query, bool recursive)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente les critères de recherche de message. |
| recursive | Boolean | Indique s'il s'agit d'une liste récursive ou non. |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_1}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessageInfoCollection ListMessages(IEnumerable<string> iDs)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| iDs | IEnumerable`1 | Énumération des identifiants de message |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) qui contient des messages avec.

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Répertorier les messages dans le dossier de la boîte de réception.

```csharp
public ExchangeMessageInfoCollection ListMessages()
```

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) à partir du dossier de la boîte de réception.

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery) {#listmessages_10}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente les critères de recherche de message. |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
