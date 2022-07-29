---
title: CheckUserAvailability
second_title: Référence de l'API Aspose.Email pour .NET
description: Vérifie la disponibilité de lutilisateur dans la fenêtre de temps spécifiée.
type: docs
weight: 420
url: /fr/net/aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability/
---
## CheckUserAvailability(string, DateRange) {#checkuseravailability}

Vérifie la disponibilité de l'utilisateur dans la fenêtre de temps spécifiée.

```csharp
public ExchangeUserAvailability CheckUserAvailability(string user, DateRange timeWindow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| user | String | Une adresse smtp d'utilisateur. |
| timeWindow | DateRange | Un intervalle de temps pour la disponibilité de l'utilisateur interrogé. |

### Return_Value

[`ExchangeUserAvailability`](../../exchangeuseravailability) contenant des informations sur la disponibilité des utilisateurs.

### Voir également

* class [ExchangeUserAvailability](../../exchangeuseravailability)
* class [DateRange](../../daterange)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## CheckUserAvailability(StringCollection, DateRange) {#checkuseravailability_1}

Vérifie la disponibilité des utilisateurs dans la fenêtre de temps spécifiée.

```csharp
public ExchangeUserAvailabilityCollection CheckUserAvailability(StringCollection users, 
    DateRange timeWindow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| users | StringCollection | Adresses SMTP d'un utilisateur. |
| timeWindow | DateRange | Un intervalle de temps pour la disponibilité de l'utilisateur interrogé. |

### Return_Value

[`ExchangeUserAvailabilityCollection`](../../exchangeuseravailabilitycollection) contenant les informations de disponibilité des utilisateurs.

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *timeWindow*ou*users* est`nul`. |

### Voir également

* class [ExchangeUserAvailabilityCollection](../../exchangeuseravailabilitycollection)
* class [DateRange](../../daterange)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->