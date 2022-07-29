---
title: ResolveMapiContactsAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Résout les adresses e-mail et les noms daffichage ambigus Remarque  le nombre maximal de contacts renvoyés est de 100. Il sagit dune restriction de lopération EWS utilisée.
type: docs
weight: 590
url: /fr/net/aspose.email.clients.exchange.webservice/iasyncewsclient/resolvemapicontactsasync/
---
## IAsyncEwsClient.ResolveMapiContactsAsync method

Résout les adresses e-mail et les noms d'affichage ambigus Remarque : le nombre maximal de contacts renvoyés est de 100. Il s'agit d'une restriction de l'opération EWS utilisée.

```csharp
public Task<MapiContactCollection> ResolveMapiContactsAsync(string unresolvedEntry, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| unresolvedEntry | String | Un nom de contact pour résoudre |
| cancellationToken | CancellationToken | Le jeton d'annulation |

### Return_Value

UN[`MapiContactCollection`](../../../aspose.email.mapi/mapicontactcollection) qui représente les informations de contact

### Voir également

* class [MapiContactCollection](../../../aspose.email.mapi/mapicontactcollection)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->