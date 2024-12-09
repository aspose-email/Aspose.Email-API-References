---
title: Class AutodiscoverServiceBase
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.AutodiscoverServiceBase class. Represents an abstract binding to an Autodiscover Service
type: docs
weight: 3110
url: /net/aspose.email.clients.exchange/autodiscoverservicebase/
---
## AutodiscoverServiceBase class

Represents an abstract binding to an Autodiscover Service.

```csharp
public abstract class AutodiscoverServiceBase
```

## Properties

| Name | Description |
| --- | --- |
| [AcceptGzipEncoding](../../aspose.email.clients.exchange/autodiscoverservicebase/acceptgzipencoding/) { get; set; } | Gets or sets a value indicating whether GZip compression encoding should be accepted. |
| [ClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/clientrequestid/) { get; set; } | Gets or sets the request id for the request. |
| [ConnectionGroupName](../../aspose.email.clients.exchange/autodiscoverservicebase/connectiongroupname/) { get; set; } | Gets or sets the name of the connection group for the request. |
| [CookieContainer](../../aspose.email.clients.exchange/autodiscoverservicebase/cookiecontainer/) { get; set; } | Gets or sets the cookie container. |
| [Credentials](../../aspose.email.clients.exchange/autodiscoverservicebase/credentials/) { get; set; } | Gets or sets the credentials used to authenticate with the Exchange Web Services. Setting the Credentials property automatically sets the UseDefaultCredentials to false. |
| [HttpHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpheaders/) { get; } | Gets a collection of HTTP headers that will be sent with each request to EWS. |
| [HttpResponseHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpresponseheaders/) { get; } | Gets a collection of HTTP headers from the last response. |
| [KeepAlive](../../aspose.email.clients.exchange/autodiscoverservicebase/keepalive/) { get; set; } | Gets or sets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive |
| [LogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/logfilename/) { get; set; } | Gets or sets log file name |
| [PreAuthenticate](../../aspose.email.clients.exchange/autodiscoverservicebase/preauthenticate/) { get; set; } | Gets or sets a value that indicates whether HTTP pre-authentication should be performed. |
| [RequestedServerVersion](../../aspose.email.clients.exchange/autodiscoverservicebase/requestedserverversion/) { get; } | Gets the requested server version. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/returnclientrequestid/) { get; set; } | Gets or sets a flag to indicate whether the client requires the server side to return the request id. |
| [SendClientLatencies](../../aspose.email.clients.exchange/autodiscoverservicebase/sendclientlatencies/) { get; set; } | Gets or sets a value indicating whether client latency info is push to server. |
| [ServerInfo](../../aspose.email.clients.exchange/autodiscoverservicebase/serverinfo/) { get; } | Gets information associated with the server that processed the last request. Will be null if no requests have been processed. |
| [Timeout](../../aspose.email.clients.exchange/autodiscoverservicebase/timeout/) { get; set; } | Gets or sets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. Defaults to 100000. |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/usedateinlogfilename/) { get; set; } | Gets or sets value which indicates if date has to be used in log file name. |
| [UseDefaultCredentials](../../aspose.email.clients.exchange/autodiscoverservicebase/usedefaultcredentials/) { get; set; } | Gets or sets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. Setting UseDefaultCredentials to true automatically sets the Credentials property to null. |
| [UserAgent](../../aspose.email.clients.exchange/autodiscoverservicebase/useragent/) { get; set; } | Gets or sets the user agent. |
| [WebProxy](../../aspose.email.clients.exchange/autodiscoverservicebase/webproxy/) { get; set; } | Gets or sets the web proxy that should be used when sending requests to EWS. Set this property to null to use the default web proxy. |

## Events

| Name | Description |
| --- | --- |
| event [OnSerializeCustomSoapHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/onserializecustomsoapheaders/) | Provides an event that applications can implement to emit custom SOAP headers in requests that are sent to Exchange. |

### See Also

* namespace [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange/)
* assembly [Aspose.Email](../../)


