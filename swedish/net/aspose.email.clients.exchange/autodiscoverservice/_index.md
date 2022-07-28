---
title: AutodiscoverService
second_title: Aspose.Email för .NET API-referens
description: Representerar en bindning till Exchange Autodiscover Service.
type: docs
weight: 3090
url: /sv/net/aspose.email.clients.exchange/autodiscoverservice/
---
## AutodiscoverService class

Representerar en bindning till Exchange Autodiscover Service.

```csharp
public sealed class AutodiscoverService : AutodiscoverServiceBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [AutodiscoverService](autodiscoverservice#constructor)() | Initierar en ny instans av[`AutodiscoverService`](../autodiscoverservice) class. |
| [AutodiscoverService](autodiscoverservice#constructor_1)(ExchangeVersion) | Initierar en ny instans av[`AutodiscoverService`](../autodiscoverservice) class. |
| [AutodiscoverService](autodiscoverservice#constructor_2)(string) | Initierar en ny instans av[`AutodiscoverService`](../autodiscoverservice) class. |
| [AutodiscoverService](autodiscoverservice#constructor_4)(Uri) | Initierar en ny instans av[`AutodiscoverService`](../autodiscoverservice) class. |
| [AutodiscoverService](autodiscoverservice#constructor_3)(string, ExchangeVersion) | Initierar en ny instans av[`AutodiscoverService`](../autodiscoverservice) class. |
| [AutodiscoverService](autodiscoverservice#constructor_5)(Uri, ExchangeVersion) | Initierar en ny instans av[`AutodiscoverService`](../autodiscoverservice) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AcceptGzipEncoding](../../aspose.email.clients.exchange/autodiscoverservicebase/acceptgzipencoding) { get; set; } | Hämtar eller ställer in ett värde som anger om GZip-komprimeringskodning ska accepteras. |
| [ClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/clientrequestid) { get; set; } | Hämtar eller ställer in begäran-id för begäran. |
| [ConnectionGroupName](../../aspose.email.clients.exchange/autodiscoverservicebase/connectiongroupname) { get; set; } | Hämtar eller ställer in namnet på anslutningsgruppen för begäran. |
| [CookieContainer](../../aspose.email.clients.exchange/autodiscoverservicebase/cookiecontainer) { get; set; } | Hämtar eller ställer in cookie-behållaren. |
| [Credentials](../../aspose.email.clients.exchange/autodiscoverservicebase/credentials) { get; set; } | Hämtar eller ställer in de autentiseringsuppgifter som används för att autentisera med Exchange Web Services. Om du ställer in Credentials-egenskapen ställs UseDefaultCredentials automatiskt in på false. |
| [Domain](../../aspose.email.clients.exchange/autodiscoverservice/domain) { get; set; } | Hämtar eller ställer in den domän som denna tjänst är bunden till. När den här egenskapen har ställts in används namnet domän för att automatiskt fastställa URL:en för Autodiscover-tjänsten. |
| [EnableScpLookup](../../aspose.email.clients.exchange/autodiscoverservice/enablescplookup) { get; set; } | Hämtar eller ställer in ett värde som indikerar om AutodiscoverService ska utföra SCP (ServiceConnectionPoint)-postsökning vid fastställande av Autodiscover-tjänstens URL. |
| [HttpHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpheaders) { get; } | Får en samling HTTP-rubriker som kommer att skickas med varje begäran till EWS. |
| [HttpResponseHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpresponseheaders) { get; } | Hämtar en samling HTTP-rubriker från det senaste svaret. |
| [IsExternal](../../aspose.email.clients.exchange/autodiscoverservice/isexternal) { get; } | Får ett värde som anger om tjänsten Autodiscover som URL pekar på är intern (inuti företagsnätverket) eller extern (utanför företagsnätverket). |
| [KeepAlive](../../aspose.email.clients.exchange/autodiscoverservicebase/keepalive) { get; set; } | Hämtar eller ställer in om begäran till internetresursen ska innehålla en Connection HTTP-header med värdet Keep-alive |
| [LogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/logfilename) { get; set; } | Hämtar eller ställer in loggfilens namn |
| [PreAuthenticate](../../aspose.email.clients.exchange/autodiscoverservicebase/preauthenticate) { get; set; } | Hämtar eller ställer in ett värde som anger om HTTP-förautentisering ska utföras. |
| [RedirectionUrlValidationCallback](../../aspose.email.clients.exchange/autodiscoverservice/redirectionurlvalidationcallback) { get; set; } | Hämtar eller ställer in validering av omdirigeringsadressen. |
| [RequestedServerVersion](../../aspose.email.clients.exchange/autodiscoverservicebase/requestedserverversion) { get; } | Hämtar den begärda serverversionen. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/returnclientrequestid) { get; set; } | Hämtar eller sätter en flagga för att indikera om klienten kräver att serversidan returnerar begäran-id. |
| [SendClientLatencies](../../aspose.email.clients.exchange/autodiscoverservicebase/sendclientlatencies) { get; set; } | Hämtar eller ställer in ett värde som indikerar om klientens latensinformation är push till servern. |
| [ServerInfo](../../aspose.email.clients.exchange/autodiscoverservicebase/serverinfo) { get; } | Hämtar information kopplad till servern som behandlade den senaste begäran. Kommer att vara null om inga förfrågningar har behandlats. |
| [Timeout](../../aspose.email.clients.exchange/autodiscoverservicebase/timeout) { get; set; } | Hämtar eller ställer in timeout som används när HTTP-förfrågningar skickas och när HTTP-svar tas emot, i millisekunder. Standardinställningen är 100000. |
| [Url](../../aspose.email.clients.exchange/autodiscoverservice/url) { get; set; } | Hämtar eller ställer in webbadressen som denna tjänst är bunden till. |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/usedateinlogfilename) { get; set; } | Hämtar eller ställer in värde som indikerar om datum måste användas i loggfilens namn. |
| [UseDefaultCredentials](../../aspose.email.clients.exchange/autodiscoverservicebase/usedefaultcredentials) { get; set; } | Hämtar eller ställer in ett värde som anger om användaruppgifterna för den användare som för närvarande är inloggad på Windows ska användas för att autentisera med Exchange Web Services. Om du ställer in UseDefaultCredentials till true ställs egenskapen Credentials automatiskt in på null. |
| [UserAgent](../../aspose.email.clients.exchange/autodiscoverservicebase/useragent) { get; set; } | Hämtar eller ställer in användaragenten. |
| [WebProxy](../../aspose.email.clients.exchange/autodiscoverservicebase/webproxy) { get; set; } | Hämtar eller ställer in webbproxyn som ska användas när förfrågningar skickas till EWS. Ställ in den här egenskapen på null för att använda standardwebproxyn. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [GetUserSettings](../../aspose.email.clients.exchange/autodiscoverservice/getusersettings)(string, params UserSettingName[]) | Hämtar de angivna inställningarna för en enda SMTP-adress. |
| [GetUsersSettings](../../aspose.email.clients.exchange/autodiscoverservice/getuserssettings)(IEnumerable&lt;string&gt;, params UserSettingName[]) | Hämtar de angivna inställningarna för en uppsättning användare. |

### Se även

* class [AutodiscoverServiceBase](../autodiscoverservicebase)
* namnutrymme [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
