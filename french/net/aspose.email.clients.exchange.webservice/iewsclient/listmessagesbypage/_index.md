---
title: ListMessagesByPage
second_title: Référence de l'API Aspose.Email pour .NET
description: Liste les messages dans le dossier spécifié.
type: docs
weight: 1150
url: /fr/net/aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/
---
## ListMessagesByPage(string, int) {#listmessagesbypage_4}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| itemsPerPage | Int32 | Un certain nombre d'éléments dans la page |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int) {#listmessagesbypage_2}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente les critères de recherche. |
| itemsPerPage | Int32 | Un certain nombre d'éléments dans la page |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int) {#listmessagesbypage_5}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int offset)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| itemsPerPage | Int32 | Un certain nombre d'éléments dans la page |
| offset | Int32 | Un décalage de la page suivante en vue |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int, int) {#listmessagesbypage_3}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage, 
    int offset)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente les critères de recherche. |
| itemsPerPage | Int32 | Un certain nombre d'éléments dans la page |
| offset | Int32 | Un décalage de la page suivante en vue |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int, ExchangeListMessagesOptions) {#listmessagesbypage_6}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int pageOffset, 
    ExchangeListMessagesOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| itemsPerPage | Int32 | Un certain nombre d'éléments dans la page |
| pageOffset | Int32 | Un décalage de l'élément suivant dans la vue |
| options | ExchangeListMessagesOptions | Spécifie les paramètres de la liste |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo) {#listmessagesbypage}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| pageInfo | PageInfo | Une page d'informations |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo, ExchangeListMessagesOptions) {#listmessagesbypage_1}

Liste les messages dans le dossier spécifié.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo, 
    ExchangeListMessagesOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| pageInfo | PageInfo | Une page d'informations |
| options | ExchangeListMessagesOptions | Spécifie les paramètres de la liste |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
