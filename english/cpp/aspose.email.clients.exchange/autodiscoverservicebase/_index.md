---
title: "Aspose::Email::Clients::Exchange::AutodiscoverServiceBase class"
linktitle: "AutodiscoverServiceBase"
articleTitle: "AutodiscoverServiceBase"
second_title: "Aspose.Email for C++"
description: "Represents an abstract binding to an Autodiscover Service."
type: docs
weight: 10
url: /cpp/aspose.email.clients.exchange/autodiscoverservicebase/
---

## AutodiscoverServiceBase class

Represents an abstract binding to an Autodiscover Service.

## Constructors

| Name | Description |
| --- | --- |
| [AutodiscoverServiceBase (2 overloads)](./autodiscoverservicebase/) | Initializes a new instance of the AutodiscoverServiceBase class. |

## Methods

| Name | Description |
| --- | --- |
| [CustomXmlSerializationDelegate](./customxmlserializationdelegate/) | Defines a delegate that is used to allow applications to emit custom XML when SOAP requests are sent to Exchange . |
| [DoOnSerializeCustomSoapHeaders](./doonserializecustomsoapheaders/) | Calls the custom SOAP header serialization event handlers, if defined. |
| [get_AcceptGzipEncoding](./get_acceptgzipencoding/) | Gets a value indicating whether GZip compression encoding should be accepted. |
| [get_ClientRequestId](./get_clientrequestid/) | Gets the request id for the request. |
| [get_ConnectionGroupName](./get_connectiongroupname/) | Gets the name of the connection group for the request. |
| [get_CookieContainer](./get_cookiecontainer/) | Gets the cookie container. |
| [get_Credentials](./get_credentials/) | Gets the credentials used to authenticate with the Exchange Web Services. Setting the Credentials property automatically sets the UseDefaultCredentials to false. |
| [get_HttpHeaders](./get_httpheaders/) | Gets a collection of HTTP headers that will be sent with each request to EWS. |
| [get_HttpResponseHeaders](./get_httpresponseheaders/) | Gets a collection of HTTP headers from the last response. |
| [get_KeepAlive](./get_keepalive/) | Gets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive |
| [get_LogFileName](./get_logfilename/) | Gets log file name |
| [get_Logger](./get_logger/) | Diagnostic logger |
| [get_PreAuthenticate](./get_preauthenticate/) | Gets a value that indicates whether HTTP pre-authentication should be performed. |
| [get_RequestedServerVersion](./get_requestedserverversion/) | Gets the requested server version. |
| [get_ReturnClientRequestId](./get_returnclientrequestid/) | Gets a flag to indicate whether the client requires the server side to return the request id. |
| [get_SendClientLatencies](./get_sendclientlatencies/) | Gets a value indicating whether client latency info is push to server. |
| [get_ServerInfo](./get_serverinfo/) | Gets information associated with the server that processed the last request. Will be null if no requests have been processed. |
| [get_SessionKey](./get_sessionkey/) | Gets the session key. |
| [get_SuppressXmlVersionHeader](./get_suppressxmlversionheader/) | For testing: suppresses generation of the SOAP version header. |
| [get_Timeout](./get_timeout/) | Gets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. Defaults to 100000. |
| [get_TimeZone](./get_timezone/) | Gets the time zone this service is scoped to. |
| [get_UseDateInLogFileName](./get_usedateinlogfilename/) | Gets value which indicates if date has to be used in log file name. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/) | Gets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. Setting UseDefaultCredentials to true automatically sets the Credentials property to null. |
| [get_UserAgent](./get_useragent/) | Gets the user agent. |
| [get_WebProxy](./get_webproxy/) | Gets the web proxy that should be used when sending requests to EWS. Set this property to null to use the default web proxy. |
| [initializeLogger](./initializelogger/) |  |
| [InternalProcessHttpErrorResponse](./internalprocesshttperrorresponse/) | Processes an HTTP error response |
| [Log (5 overloads)](./log/) |  |
| [PrepareHttpWebRequestForUrl](./preparehttpwebrequestforurl/) | Creates an HttpWebRequest instance and initializes it with the appropriate parameters, based on the configuration of this service object. |
| [SaveHttpResponseHeaders](./savehttpresponseheaders/) | Save the HTTP response headers. |
| [set_AcceptGzipEncoding](./set_acceptgzipencoding/) | Sets a value indicating whether GZip compression encoding should be accepted. |
| [set_ClientRequestId](./set_clientrequestid/) | Sets the request id for the request. |
| [set_ConnectionGroupName](./set_connectiongroupname/) | Sets the name of the connection group for the request. |
| [set_CookieContainer](./set_cookiecontainer/) | Sets the cookie container. |
| [set_Credentials](./set_credentials/) | Sets the credentials used to authenticate with the Exchange Web Services. Setting the Credentials property automatically sets the UseDefaultCredentials to false. |
| [set_KeepAlive](./set_keepalive/) | Sets if the request to the internet resource should contain a Connection HTTP header with the value Keep-alive |
| [set_LogFileName](./set_logfilename/) | Sets log file name |
| [set_PreAuthenticate](./set_preauthenticate/) | Sets a value that indicates whether HTTP pre-authentication should be performed. |
| [set_ReturnClientRequestId](./set_returnclientrequestid/) | Sets a flag to indicate whether the client requires the server side to return the request id. |
| [set_SendClientLatencies](./set_sendclientlatencies/) | Sets a value indicating whether client latency info is push to server. |
| [set_ServerInfo](./set_serverinfo/) | Gets information associated with the server that processed the last request. Will be null if no requests have been processed. |
| [set_SuppressXmlVersionHeader](./set_suppressxmlversionheader/) | For testing: suppresses generation of the SOAP version header. |
| [set_Timeout](./set_timeout/) | Sets the timeout used when sending HTTP requests and when receiving HTTP responses, in milliseconds. Defaults to 100000. |
| [set_UseDateInLogFileName](./set_usedateinlogfilename/) | Sets value which indicates if date has to be used in log file name. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/) | Sets a value indicating whether the credentials of the user currently logged into Windows should be used to authenticate with the Exchange Web Services. Setting UseDefaultCredentials to true automatically sets the Credentials property to null. |
| [set_UserAgent](./set_useragent/) | Sets the user agent. |
| [set_WebProxy](./set_webproxy/) | Sets the web proxy that should be used when sending requests to EWS. Set this property to null to use the default web proxy. |
| [AutodiscoverRequest](./autodiscoverrequest/) |  |
| [AutodiscoverService](./autodiscoverservice/) |  |
| [AccountIsLocked](./accountislocked/) | Special HTTP status code that indicates that the account is locked. |
| [OnSerializeCustomSoapHeaders](./onserializecustomsoapheaders/) | Provides an event that applications can implement to emit custom SOAP headers in requests that are sent to Exchange . |

