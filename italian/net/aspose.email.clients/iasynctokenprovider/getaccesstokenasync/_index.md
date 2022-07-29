---
title: GetAccessTokenAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Ottiene il token di accesso oAuth.
type: docs
weight: 10
url: /it/net/aspose.email.clients/iasynctokenprovider/getaccesstokenasync/
---
## IAsyncTokenProvider.GetAccessTokenAsync method

Ottiene il token di accesso oAuth.

```csharp
public Task<OAuthToken> GetAccessTokenAsync(bool ignoreExistingToken = false, 
    CancellationToken cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ignoreExistingToken | Boolean | Se ignoreExistingToken è true, richiede un nuovo token da un server. Altrimenti il comportamento dipende dall'esistenza o meno del token. Se il token esiste e la sua data di scadenza non è scaduta restituisce il token corrente, altrimenti richiede un nuovo token da un server. |
| cancellationToken | CancellationToken | Il token di annullamento |

### Valore di ritorno

Restituisce il token di accesso oAuth

### Guarda anche

* class [OAuthToken](../../oauthtoken)
* interface [IAsyncTokenProvider](../../iasynctokenprovider)
* spazio dei nomi [Aspose.Email.Clients](../../iasynctokenprovider)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->