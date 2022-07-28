---
title: AutodiscoverService
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente une liaison au service de découverte automatique Exchange.
type: docs
weight: 3090
url: /fr/net/aspose.email.clients.exchange/autodiscoverservice/
---
## AutodiscoverService class

Représente une liaison au service de découverte automatique Exchange.

```csharp
public sealed class AutodiscoverService : AutodiscoverServiceBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [AutodiscoverService](autodiscoverservice#constructor)() | Initialise une nouvelle instance du[`AutodiscoverService`](../autodiscoverservice) classe. |
| [AutodiscoverService](autodiscoverservice#constructor_1)(ExchangeVersion) | Initialise une nouvelle instance du[`AutodiscoverService`](../autodiscoverservice) classe. |
| [AutodiscoverService](autodiscoverservice#constructor_2)(string) | Initialise une nouvelle instance du[`AutodiscoverService`](../autodiscoverservice) classe. |
| [AutodiscoverService](autodiscoverservice#constructor_4)(Uri) | Initialise une nouvelle instance du[`AutodiscoverService`](../autodiscoverservice) classe. |
| [AutodiscoverService](autodiscoverservice#constructor_3)(string, ExchangeVersion) | Initialise une nouvelle instance du[`AutodiscoverService`](../autodiscoverservice) classe. |
| [AutodiscoverService](autodiscoverservice#constructor_5)(Uri, ExchangeVersion) | Initialise une nouvelle instance du[`AutodiscoverService`](../autodiscoverservice) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AcceptGzipEncoding](../../aspose.email.clients.exchange/autodiscoverservicebase/acceptgzipencoding) { get; set; } | Obtient ou définit une valeur indiquant si le codage de compression GZip doit être accepté. |
| [ClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/clientrequestid) { get; set; } | Obtient ou définit l'ID de requête pour la requête. |
| [ConnectionGroupName](../../aspose.email.clients.exchange/autodiscoverservicebase/connectiongroupname) { get; set; } | Obtient ou définit le nom du groupe de connexion pour la requête. |
| [CookieContainer](../../aspose.email.clients.exchange/autodiscoverservicebase/cookiecontainer) { get; set; } | Obtient ou définit le conteneur de cookies. |
| [Credentials](../../aspose.email.clients.exchange/autodiscoverservicebase/credentials) { get; set; } | Obtient ou définit les informations d'identification utilisées pour s'authentifier auprès des services Web Exchange. La définition de la propriété Credentials définit automatiquement UseDefaultCredentials sur false. |
| [Domain](../../aspose.email.clients.exchange/autodiscoverservice/domain) { get; set; } | Obtient ou définit le domaine auquel ce service est lié. Lorsque cette propriété est définie, le nom de domaine est utilisé pour déterminer automatiquement l'URL du service de découverte automatique. |
| [EnableScpLookup](../../aspose.email.clients.exchange/autodiscoverservice/enablescplookup) { get; set; } | Obtient ou définit une valeur indiquant si AutodiscoverService doit effectuer une recherche d'enregistrement SCP (ServiceConnectionPoint) lors de la détermination de l'URL du service de découverte automatique. |
| [HttpHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpheaders) { get; } | Obtient une collection d'en-têtes HTTP qui seront envoyés avec chaque demande à EWS. |
| [HttpResponseHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpresponseheaders) { get; } | Obtient une collection d'en-têtes HTTP de la dernière réponse. |
| [IsExternal](../../aspose.email.clients.exchange/autodiscoverservice/isexternal) { get; } | Obtient une valeur indiquant si le service de découverte automatique vers lequel l'URL pointe est interne (à l'intérieur du réseau d'entreprise) ou externe (à l'extérieur du réseau d'entreprise). |
| [KeepAlive](../../aspose.email.clients.exchange/autodiscoverservicebase/keepalive) { get; set; } | Obtient ou définit si la demande à la ressource Internet doit contenir un en-tête HTTP de connexion avec la valeur Keep-alive |
| [LogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/logfilename) { get; set; } | Obtient ou définit le nom du fichier journal |
| [PreAuthenticate](../../aspose.email.clients.exchange/autodiscoverservicebase/preauthenticate) { get; set; } | Obtient ou définit une valeur qui indique si la pré-authentification HTTP doit être effectuée. |
| [RedirectionUrlValidationCallback](../../aspose.email.clients.exchange/autodiscoverservice/redirectionurlvalidationcallback) { get; set; } | Obtient ou définit le rappel de validation de l'URL de redirection. |
| [RequestedServerVersion](../../aspose.email.clients.exchange/autodiscoverservicebase/requestedserverversion) { get; } | Obtient la version de serveur demandée. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/returnclientrequestid) { get; set; } | Obtient ou définit un indicateur pour indiquer si le client exige que le côté serveur renvoie l'ID de la demande. |
| [SendClientLatencies](../../aspose.email.clients.exchange/autodiscoverservicebase/sendclientlatencies) { get; set; } | Obtient ou définit une valeur indiquant si les informations de latence du client sont transmises au serveur. |
| [ServerInfo](../../aspose.email.clients.exchange/autodiscoverservicebase/serverinfo) { get; } | Obtient les informations associées au serveur qui a traité la dernière requête. Sera nul si aucune requête n'a été traitée. |
| [Timeout](../../aspose.email.clients.exchange/autodiscoverservicebase/timeout) { get; set; } | Obtient ou définit le délai d'attente utilisé lors de l'envoi de requêtes HTTP et lors de la réception de réponses HTTP, en millisecondes. La valeur par défaut est 100000. |
| [Url](../../aspose.email.clients.exchange/autodiscoverservice/url) { get; set; } | Obtient ou définit l'URL à laquelle ce service est lié. |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/usedateinlogfilename) { get; set; } | Obtient ou définit la valeur qui indique si la date doit être utilisée dans le nom du fichier journal. |
| [UseDefaultCredentials](../../aspose.email.clients.exchange/autodiscoverservicebase/usedefaultcredentials) { get; set; } | Obtient ou définit une valeur indiquant si les informations d'identification de l'utilisateur actuellement connecté à Windows doivent être utilisées pour s'authentifier auprès des services Web Exchange. Définir UseDefaultCredentials sur true définit automatiquement la propriété Credentials sur null. |
| [UserAgent](../../aspose.email.clients.exchange/autodiscoverservicebase/useragent) { get; set; } | Obtient ou définit l'agent utilisateur. |
| [WebProxy](../../aspose.email.clients.exchange/autodiscoverservicebase/webproxy) { get; set; } | Obtient ou définit le proxy Web qui doit être utilisé lors de l'envoi de demandes à EWS. Définissez cette propriété sur null pour utiliser le proxy Web par défaut. |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetUserSettings](../../aspose.email.clients.exchange/autodiscoverservice/getusersettings)(string, params UserSettingName[]) | Récupère les paramètres spécifiés pour une adresse SMTP unique. |
| [GetUsersSettings](../../aspose.email.clients.exchange/autodiscoverservice/getuserssettings)(IEnumerable&lt;string&gt;, params UserSettingName[]) | Récupère les paramètres spécifiés pour un ensemble d'utilisateurs. |

### Voir également

* class [AutodiscoverServiceBase](../autodiscoverservicebase)
* espace de noms [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
