---
title: Class AutodiscoverService
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.AutodiscoverService class. Represents a binding to the Exchange Autodiscover Service
type: docs
weight: 1650
url: /net/aspose.email.clients.exchange/autodiscoverservice/
---
## AutodiscoverService class

Represents a binding to the Exchange Autodiscover Service.

```csharp
public sealed class AutodiscoverService : AutodiscoverServiceBase
```

## Constructors

| Name | Description |
| --- | --- |
| [AutodiscoverService](autodiscoverservice/#constructor)() | Initializes a new instance of the `AutodiscoverService` class. |
| [AutodiscoverService](autodiscoverservice/#constructor_1)(ExchangeVersion) | Initializes a new instance of the `AutodiscoverService` class. |
| [AutodiscoverService](autodiscoverservice/#constructor_2)(string) | Initializes a new instance of the `AutodiscoverService` class. |
| [AutodiscoverService](autodiscoverservice/#constructor_4)(Uri) | Initializes a new instance of the `AutodiscoverService` class. |
| [AutodiscoverService](autodiscoverservice/#constructor_3)(string, ExchangeVersion) | Initializes a new instance of the `AutodiscoverService` class. |
| [AutodiscoverService](autodiscoverservice/#constructor_5)(Uri, ExchangeVersion) | Initializes a new instance of the `AutodiscoverService` class. |

## Properties

| Name | Description |
| --- | --- |
| [AcceptGzipEncoding](../../aspose.email.clients.exchange/autodiscoverservicebase/acceptgzipencoding/) { get; set; } | Gets or sets a value indicating whether GZip compression encoding should be accepted. |
| [ClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/clientrequestid/) { get; set; } | Gets or sets the request id for the request. |
| [ConnectionGroupName](../../aspose.email.clients.exchange/autodiscoverservicebase/connectiongroupname/) { get; set; } | Gets or sets the name of the connection group for the request. |
| [CookieContainer](../../aspose.email.clients.exchange/autodiscoverservicebase/cookiecontainer/) { get; set; } | Gets or sets the cookie container. |
| [Credentials](../../aspose.email.clients.exchange/autodiscoverservicebase/credentials/) { get; set; } | Gets or sets the credentials used to authenticate with the Exchange Web Services. Setting the Credentials property automatically sets the UseDefaultCredentials to false. |
| [Domain](../../aspose.email.clients.exchange/autodiscoverservice/domain/) { get; set; } | Gets or sets the domain this service is bound to. When this property is set, the domain name is used to automatically determine the Autodiscover service URL. |
| [EnableScpLookup](../../aspose.email.clients.exchange/autodiscoverservice/enablescplookup/) { get; set; } | Gets or sets a value indicating whether the AutodiscoverService should perform SCP (ServiceConnectionPoint) record lookup when determining the Autodiscover service URL. |
| [HttpHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpheaders/) { get; } | Gets a collection of HTTP headers that will be sent with each request to EWS. |
| [HttpResponseHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpresponseheaders/) { get; } | Gets a collection of HTTP headers from the last response. |
| [IsExternal](../../aspose.email.clients.exchange/autodiscoverservice/isexternal/) { get; } | Gets a value indicating whether the Autodiscover service that URL points to is internal (inside the corporate network) or external (outside the corporate network). |
| [KeepAlive](../../aspose.email.clients.exchange/autodiscoverservicebase/keepalive/) { get; set; } | Gets or sets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive |
| [LogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/logfilename/) { get; set; } | Gets or sets log file name |
| [PreAuthenticate](../../aspose.email.clients.exchange/autodiscoverservicebase/preauthenticate/) { get; set; } | Gets or sets a value that indicates whether HTTP pre-authentication should be performed. |
| [RedirectionUrlValidationCallback](../../aspose.email.clients.exchange/autodiscoverservice/redirectionurlvalidationcallback/) { get; set; } | Gets or sets the redirection URL validation callback. |
| [RequestedServerVersion](../../aspose.email.clients.exchange/autodiscoverservicebase/requestedserverversion/) { get; } | Gets the requested server version. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/returnclientrequestid/) { get; set; } | Gets or sets a flag to indicate whether the client requires the server side to return the request id. |
| [SendClientLatencies](../../aspose.email.clients.exchange/autodiscoverservicebase/sendclientlatencies/) { get; set; } | Gets or sets a value indicating whether client latency info is push to server. |
| [ServerInfo](../../aspose.email.clients.exchange/autodiscoverservicebase/serverinfo/) { get; } | Gets information associated with the server that processed the last request. Will be null if no requests have been processed. |
| [Timeout](../../aspose.email.clients.exchange/autodiscoverservicebase/timeout/) { get; set; } | Gets or sets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. Defaults to 100000. |
| [Url](../../aspose.email.clients.exchange/autodiscoverservice/url/) { get; set; } | Gets or sets the URL this service is bound to. |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/usedateinlogfilename/) { get; set; } | Gets or sets value which indicates if date has to be used in log file name. |
| [UseDefaultCredentials](../../aspose.email.clients.exchange/autodiscoverservicebase/usedefaultcredentials/) { get; set; } | Gets or sets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. Setting UseDefaultCredentials to true automatically sets the Credentials property to null. |
| [UserAgent](../../aspose.email.clients.exchange/autodiscoverservicebase/useragent/) { get; set; } | Gets or sets the user agent. |
| [WebProxy](../../aspose.email.clients.exchange/autodiscoverservicebase/webproxy/) { get; set; } | Gets or sets the web proxy that should be used when sending requests to EWS. Set this property to null to use the default web proxy. |

## Methods

| Name | Description |
| --- | --- |
| [GetUserSettings](../../aspose.email.clients.exchange/autodiscoverservice/getusersettings/)(string, params UserSettingName[]) | Retrieves the specified settings for single SMTP address. |
| [GetUsersSettings](../../aspose.email.clients.exchange/autodiscoverservice/getuserssettings/)(IEnumerable&lt;string&gt;, params UserSettingName[]) | Retrieves the specified settings for a set of users. |

## Events

| Name | Description |
| --- | --- |
| event [OnSerializeCustomSoapHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/onserializecustomsoapheaders/) | Provides an event that applications can implement to emit custom SOAP headers in requests that are sent to Exchange. |

### See Also

* class [AutodiscoverServiceBase](../autodiscoverservicebase/)
* namespace [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange/)
* assembly [Aspose.Email](../../)


