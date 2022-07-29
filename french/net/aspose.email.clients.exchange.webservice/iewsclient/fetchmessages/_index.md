---
title: FetchMessages
second_title: Référence de l'API Aspose.Email pour .NET
description: Récupère les messages spécifiés
type: docs
weight: 820
url: /fr/net/aspose.email.clients.exchange.webservice/iewsclient/fetchmessages/
---
## FetchMessages(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) {#fetchmessages_2}

Récupère les messages spécifiés

```csharp
public MailMessageCollection FetchMessages(IEnumerable<string> uris, 
    IEnumerable<PropertyDescriptor> extendedProperties)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uris | IEnumerable`1 | UNStringCollection contenant les uris de message à récupérer |
| extendedProperties | IEnumerable`1 | Une énumération de propriétés étendues |

### Return_Value

UN[`MailMessageCollection`](../../../aspose.email/mailmessagecollection)contenant des messages récupérés

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *uris* est`nul` |

### Voir également

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessages(IEnumerable&lt;string&gt;) {#fetchmessages_1}

Récupère les messages spécifiés

```csharp
public MailMessageCollection FetchMessages(IEnumerable<string> uris)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uris | IEnumerable`1 | UNStringCollection contenant les uris de message à récupérer |

### Return_Value

UN[`MailMessageCollection`](../../../aspose.email/mailmessagecollection)contenant des messages récupérés

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *uris* est`nul` |

### Voir également

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessages(IEnumerable&lt;ExchangeMessageInfo&gt;) {#fetchmessages}

Récupère les messages spécifiés

```csharp
public MailMessageCollection FetchMessages(IEnumerable<ExchangeMessageInfo> messageInfos)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageInfos | IEnumerable`1 | AIEnumerable&lt;ExchangeMessageInfo&gt;"/&gt; de messages à récupérer |

### Return_Value

UN[`MailMessageCollection`](../../../aspose.email/mailmessagecollection)contenant des messages récupérés

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *messageInfos* est`nul` |

### Voir également

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [ExchangeMessageInfo](../../../aspose.email.clients.exchange/exchangemessageinfo)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessages(StringCollection) {#fetchmessages_3}

Récupère les messages spécifiés

```csharp
public MailMessageCollection FetchMessages(StringCollection messageUris)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| messageUris | StringCollection | UNStringCollection contenant les uris de message à récupérer |

### Return_Value

UN[`MailMessageCollection`](../../../aspose.email/mailmessagecollection)contenant des messages récupérés

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *messageUris* est`nul` |

### Voir également

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->