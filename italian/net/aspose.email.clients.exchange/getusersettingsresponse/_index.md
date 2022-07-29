---
title: GetUserSettingsResponse
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta la risposta a una chiamata GetUsersSettings per un singolo utente.
type: docs
weight: 3470
url: /it/net/aspose.email.clients.exchange/getusersettingsresponse/
---
## GetUserSettingsResponse class

Rappresenta la risposta a una chiamata GetUsersSettings per un singolo utente.

```csharp
public sealed class GetUserSettingsResponse : AutodiscoverResponse
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GetUserSettingsResponse](getusersettingsresponse)() | Inizializza una nuova istanza di[`GetUserSettingsResponse`](../getusersettingsresponse) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ErrorCode](../../aspose.email.clients.exchange/autodiscoverresponse/errorcode) { get; } | Ottiene il codice di errore restituito dal servizio. |
| [ErrorMessage](../../aspose.email.clients.exchange/autodiscoverresponse/errormessage) { get; } | Ottiene il messaggio di errore restituito dal servizio. |
| [RedirectTarget](../../aspose.email.clients.exchange/getusersettingsresponse/redirecttarget) { get; } | Ottiene il redirectionTarget (URL o indirizzo email) |
| [Settings](../../aspose.email.clients.exchange/getusersettingsresponse/settings) { get; } | Ottiene le impostazioni richieste per l'utente. |
| [SmtpAddress](../../aspose.email.clients.exchange/getusersettingsresponse/smtpaddress) { get; } | Ottiene l'indirizzo SMTP a cui si applica questa risposta. |
| [UserSettingErrors](../../aspose.email.clients.exchange/getusersettingsresponse/usersettingerrors) { get; } | Ottiene informazioni sull'errore per le impostazioni che non è stato possibile restituire. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [TryGetSettingValue&lt;T&gt;](../../aspose.email.clients.exchange/getusersettingsresponse/trygetsettingvalue)(UserSettingName, out T) | Prova a ottenere il valore dell'impostazione utente. |

### Guarda anche

* class [AutodiscoverResponse](../autodiscoverresponse)
* spazio dei nomi [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->