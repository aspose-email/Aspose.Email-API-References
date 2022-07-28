---
title: ListMessages
second_title: Référence de l'API Aspose.Email pour .NET
description: Liste les messages.
type: docs
weight: 280
url: /fr/net/aspose.email.clients.exchange.dav/exchangeclient/listmessages/
---
## ListMessages(string) {#listmessages}

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
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_4}

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
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_7}

Liste les messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string messageClass, 
    bool recursive)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Le dossier. |
| messageClass | String | La classe de messages. |
| recursive | Boolean | si réglé sur`vrai` [récursif]. |

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_3}

Lister les messages dans le dossier spécifié

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Le dossier Uri |
| recursive | Boolean | Indique s'il s'agit d'une liste récursive ou non. |

### Return_Value

Une collection d'informations sur les messages

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, string) {#listmessages_6}

Liste les messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string query)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Le dossier. |
| query | String | La requête. |

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_2}

Liste les messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Uri du dossier contenant les messages. |
| query | MailQuery | La[`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente les critères de recherche. |
| recursive | Boolean | Indique s'il s'agit d'une liste récursive ou non. |

### Return_Value

La collection d'informations sur les messages.

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_1}

Répertorie le message électronique dans le dossier spécifié.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | L'url du dossier |
| options | ExchangeListMessagesOptions | Spécifie les paramètres de la liste |

### Return_Value

UN[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) le recueil.

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_5}

Lister les messages dans le dossier spécifié

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Le dossier Uri |
| maxNumberOfMessages | Int32 | Nombre maximal de messages |
| options | ExchangeListMessagesOptions | Spécifie les paramètres de la liste |

### Return_Value

Une collection d'informations sur les messages

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* espace de noms [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
