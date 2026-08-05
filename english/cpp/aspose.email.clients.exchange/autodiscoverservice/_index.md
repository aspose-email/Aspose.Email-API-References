---
title: "Aspose::Email::Clients::Exchange::AutodiscoverService class"
linktitle: "AutodiscoverService"
articleTitle: "AutodiscoverService"
second_title: "Aspose.Email for C++"
description: "Represents a binding to the Exchange Autodiscover Service."
type: docs
weight: 10
url: /cpp/aspose.email.clients.exchange/autodiscoverservice/
---

## AutodiscoverService class

**Inherits:** Aspose::Email::Clients::Exchange::AutodiscoverServiceBase

Represents a binding to the Exchange Autodiscover Service.

## Constructors

| Name | Description |
| --- | --- |
| [AutodiscoverService (8 overloads)](./autodiscoverservice/) | Initializes a new instance of the AutodiscoverService class. |

## Methods

| Name | Description |
| --- | --- |
| [Func](./func/) |  |
| [FuncC](./funcc/) |  |
| [Assert](./assert/) |  |
| [CreateExceptionResponse](./createexceptionresponse/) |  |
| [get_DnsServerAddress](./get_dnsserveraddress/) | Gets the DNS server address. |
| [get_Domain](./get_domain/) | Gets the domain this service is bound to. When this property is set, the domain name is used to automatically determine the Autodiscover service URL. |
| [get_EnableScpLookup](./get_enablescplookup/) | Gets a value indicating whether the AutodiscoverService should perform SCP (ServiceConnectionPoint) record lookup when determining the Autodiscover service URL. |
| [get_GetScpUrlsForDomainCallback](./get_getscpurlsfordomaincallback/) | Gets the delegate used to resolve Autodiscover SCP urls for a specified domain. |
| [get_IsExternal](./get_isexternal/) | Gets a value indicating whether the Autodiscover service that URL points to is internal (inside the corporate network) or external (outside the corporate network). |
| [get_RedirectionUrlValidationCallback](./get_redirectionurlvalidationcallback/) | Gets the redirection URL validation callback. |
| [get_Url](./get_url/) | Gets the URL this service is bound to. |
| [GetAutodiscoverServiceHosts](./getautodiscoverservicehosts/) | Gets the list of autodiscover service hosts. |
| [GetAutodiscoverServiceUrls](./getautodiscoverserviceurls/) | Gets the list of autodiscover service URLs. |
| [GetDomainSettings (3 overloads)](./getdomainsettings/) | Retrieves the specified settings for a set of domains. |
| [GetLegacyUserSettings](./getlegacyusersettings/) | Calls the legacy Autodiscover service to retrieve configuration settings. |
| [GetRedirectionUrlFromDnsSrvRecord](./getredirectionurlfromdnssrvrecord/) | Get an autodiscover SRV record in DNS and construct autodiscover URL. |
| [GetUserSettings (2 overloads)](./getusersettings/) | Gets the user settings using Autodiscover SOAP service. |
| [GetUsersSettings](./getuserssettings/) | Retrieves the specified settings for a set of users. |
| [InternalGetLegacyUserSettings](./internalgetlegacyusersettings/) | Gets user settings from Autodiscover legacy endpoint. |
| [InternalGetSoapUserSettings](./internalgetsoapusersettings/) | Calls the SOAP Autodiscover service for user settings for a single SMTP address. |
| [PrepareHttpWebRequestForUrl](./preparehttpwebrequestforurl/) | Creates an HttpWebRequest instance and initializes it with the appropriate parameters, based on the configuration of this service object. |
| [ProcessHttpErrorResponse](./processhttperrorresponse/) | Processes an HTTP error response. |
| [set_DnsServerAddress](./set_dnsserveraddress/) | Sets the DNS server address. |
| [set_Domain](./set_domain/) | Sets the domain this service is bound to. When this property is set, the domain name is used to automatically determine the Autodiscover service URL. |
| [set_EnableScpLookup](./set_enablescplookup/) | Sets a value indicating whether the AutodiscoverService should perform SCP (ServiceConnectionPoint) record lookup when determining the Autodiscover service URL. |
| [set_GetScpUrlsForDomainCallback](./set_getscpurlsfordomaincallback/) | Sets the delegate used to resolve Autodiscover SCP urls for a specified domain. |
| [set_IsExternal](./set_isexternal/) | Gets a value indicating whether the Autodiscover service that URL points to is internal (inside the corporate network) or external (outside the corporate network). |
| [set_RedirectionUrlValidationCallback](./set_redirectionurlvalidationcallback/) | Sets the redirection URL validation callback. |
| [set_Url](./set_url/) | Sets the URL this service is bound to. |
| [TraceResponse](./traceresponse/) | Traces the response. |
| [ValidateParam](./validateparam/) |  |
| [AutodiscoverMaxRedirections](./autodiscovermaxredirections/) | Maximum number of Url (or address) redirections that will be followed by an Autodiscover call |

