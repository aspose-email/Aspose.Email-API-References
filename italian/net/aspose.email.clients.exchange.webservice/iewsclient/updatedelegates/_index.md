---
title: UpdateDelegates
second_title: Aspose.Email per riferimento all'API .NET
description: Aggiorna le impostazioni degli utenti delegati a cui è concesso laccesso alla cassetta postale specificata.
type: docs
weight: 1470
url: /it/net/aspose.email.clients.exchange.webservice/iewsclient/updatedelegates/
---
## IEWSClient.UpdateDelegates method

Aggiorna le impostazioni degli utenti delegati a cui è concesso l'accesso alla cassetta postale specificata.

```csharp
public void UpdateDelegates(ExchangeDelegateUserCollection delegateUsers, string mailbox)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| delegateUsers | ExchangeDelegateUserCollection | UN[`ExchangeDelegateUserCollection`](../../exchangedelegateusercollection) contenente le nuove impostazioni dei delegati. |
| mailbox | String | Una cassetta postale a cui gli utenti delegati hanno accesso. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *delegateUsers* è`nullo`. |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *mailbox* è`nullo`o`vuoto`. |

### Guarda anche

* class [ExchangeDelegateUserCollection](../../exchangedelegateusercollection)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->