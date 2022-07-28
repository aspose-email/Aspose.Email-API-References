---
title: AutodiscoverService
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt eine Bindung an den Exchange-AutoErmittlungsdienst dar.
type: docs
weight: 3090
url: /de/net/aspose.email.clients.exchange/autodiscoverservice/
---
## AutodiscoverService class

Stellt eine Bindung an den Exchange-AutoErmittlungsdienst dar.

```csharp
public sealed class AutodiscoverService : AutodiscoverServiceBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [AutodiscoverService](autodiscoverservice#constructor)() | Initialisiert eine neue Instanz von[`AutodiscoverService`](../autodiscoverservice) Klasse. |
| [AutodiscoverService](autodiscoverservice#constructor_1)(ExchangeVersion) | Initialisiert eine neue Instanz von[`AutodiscoverService`](../autodiscoverservice) Klasse. |
| [AutodiscoverService](autodiscoverservice#constructor_2)(string) | Initialisiert eine neue Instanz von[`AutodiscoverService`](../autodiscoverservice) Klasse. |
| [AutodiscoverService](autodiscoverservice#constructor_4)(Uri) | Initialisiert eine neue Instanz von[`AutodiscoverService`](../autodiscoverservice) Klasse. |
| [AutodiscoverService](autodiscoverservice#constructor_3)(string, ExchangeVersion) | Initialisiert eine neue Instanz von[`AutodiscoverService`](../autodiscoverservice) Klasse. |
| [AutodiscoverService](autodiscoverservice#constructor_5)(Uri, ExchangeVersion) | Initialisiert eine neue Instanz von[`AutodiscoverService`](../autodiscoverservice) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AcceptGzipEncoding](../../aspose.email.clients.exchange/autodiscoverservicebase/acceptgzipencoding) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die GZip-Komprimierungscodierung akzeptiert werden soll. |
| [ClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/clientrequestid) { get; set; } | Ruft die Anforderungs-ID für die Anforderung ab oder legt sie fest. |
| [ConnectionGroupName](../../aspose.email.clients.exchange/autodiscoverservicebase/connectiongroupname) { get; set; } | Ruft den Namen der Verbindungsgruppe für die Anforderung ab oder legt ihn fest. |
| [CookieContainer](../../aspose.email.clients.exchange/autodiscoverservicebase/cookiecontainer) { get; set; } | Ruft den Cookie-Container ab oder legt ihn fest. |
| [Credentials](../../aspose.email.clients.exchange/autodiscoverservicebase/credentials) { get; set; } | Ruft die zur Authentifizierung bei den Exchange-Webdiensten verwendeten Anmeldeinformationen ab oder legt diese fest. Durch Festlegen der Eigenschaft „Credentials “ wird „UseDefaultCredentials“ automatisch auf „false“ gesetzt. |
| [Domain](../../aspose.email.clients.exchange/autodiscoverservice/domain) { get; set; } | Ruft die Domäne ab oder legt sie fest, an die dieser Dienst gebunden ist. Wenn diese Eigenschaft festgelegt ist, wird der Name domain verwendet, um die URL des AutoErmittlungsdiensts automatisch zu ermitteln. |
| [EnableScpLookup](../../aspose.email.clients.exchange/autodiscoverservice/enablescplookup) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der AutodiscoverService eine SCP-Datensatzsuche (ServiceConnectionPoint) durchführen soll, wenn die URL des AutoErmittlungsdiensts ermittelt wird. |
| [HttpHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpheaders) { get; } | Ruft eine Sammlung von HTTP-Headern ab, die mit jeder Anfrage an EWS gesendet werden. |
| [HttpResponseHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpresponseheaders) { get; } | Ruft eine Sammlung von HTTP-Headern aus der letzten Antwort ab. |
| [IsExternal](../../aspose.email.clients.exchange/autodiscoverservice/isexternal) { get; } | Ruft einen Wert ab, der angibt, ob der AutoErmittlungsdienst, auf den die URL verweist, intern (innerhalb des Unternehmensnetzwerks) oder extern (außerhalb des Unternehmensnetzwerks) ist. |
| [KeepAlive](../../aspose.email.clients.exchange/autodiscoverservicebase/keepalive) { get; set; } | Ruft ab oder legt fest, ob die Anfrage an die Internetressource einen Verbindungs-HTTP-Header mit dem Wert Keep-alive enthalten soll |
| [LogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/logfilename) { get; set; } | Ruft den Protokolldateinamen ab oder legt ihn fest |
| [PreAuthenticate](../../aspose.email.clients.exchange/autodiscoverservicebase/preauthenticate) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob eine HTTP-Vorauthentifizierung durchgeführt werden soll. |
| [RedirectionUrlValidationCallback](../../aspose.email.clients.exchange/autodiscoverservice/redirectionurlvalidationcallback) { get; set; } | Ruft den Umleitungs-URL-Validierungsrückruf ab oder legt ihn fest. |
| [RequestedServerVersion](../../aspose.email.clients.exchange/autodiscoverservicebase/requestedserverversion) { get; } | Ruft die angeforderte Serverversion ab. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/returnclientrequestid) { get; set; } | Ruft ein Flag ab oder setzt es, um anzugeben, ob der Client verlangt, dass die Serverseite die Anforderungs-ID zurückgibt. |
| [SendClientLatencies](../../aspose.email.clients.exchange/autodiscoverservicebase/sendclientlatencies) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob Client-Latenzinformationen auf den Server übertragen werden. |
| [ServerInfo](../../aspose.email.clients.exchange/autodiscoverservicebase/serverinfo) { get; } | Ruft Informationen ab, die dem Server zugeordnet sind, der die letzte Anfrage verarbeitet hat. Ist null, wenn keine Anfragen verarbeitet wurden. |
| [Timeout](../../aspose.email.clients.exchange/autodiscoverservicebase/timeout) { get; set; } | Ruft das beim Senden von HTTP-Anforderungen und beim Empfangen von HTTP-Antworten verwendete Timeout in Millisekunden ab oder legt es fest. Standardmäßig 100000. |
| [Url](../../aspose.email.clients.exchange/autodiscoverservice/url) { get; set; } | Ruft die URL ab oder legt sie fest, an die dieser Dienst gebunden ist. |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/usedateinlogfilename) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob das Datum im Namen der Protokolldatei verwendet werden muss. |
| [UseDefaultCredentials](../../aspose.email.clients.exchange/autodiscoverservicebase/usedefaultcredentials) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Anmeldeinformationen des derzeit bei Windows angemeldeten Benutzers zur -Authentifizierung bei den Exchange-Webdiensten verwendet werden sollen. Wenn UseDefaultCredentials auf true gesetzt wird, wird die Eigenschaft Credentials automatisch auf null gesetzt. |
| [UserAgent](../../aspose.email.clients.exchange/autodiscoverservicebase/useragent) { get; set; } | Ruft den Benutzeragenten ab oder legt ihn fest. |
| [WebProxy](../../aspose.email.clients.exchange/autodiscoverservicebase/webproxy) { get; set; } | Ruft den Web-Proxy ab oder legt ihn fest, der beim Senden von Anforderungen an EWS verwendet werden soll. Legen Sie diese Eigenschaft auf null fest, um den Standard-Web-Proxy zu verwenden. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetUserSettings](../../aspose.email.clients.exchange/autodiscoverservice/getusersettings)(string, params UserSettingName[]) | Ruft die angegebenen Einstellungen für eine einzelne SMTP-Adresse ab. |
| [GetUsersSettings](../../aspose.email.clients.exchange/autodiscoverservice/getuserssettings)(IEnumerable&lt;string&gt;, params UserSettingName[]) | Ruft die angegebenen Einstellungen für eine Gruppe von Benutzern ab. |

### Siehe auch

* class [AutodiscoverServiceBase](../autodiscoverservicebase)
* namensraum [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
