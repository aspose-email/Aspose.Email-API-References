---
title: "Aspose::Email::Clients namespace"
linktitle: "Aspose::Email::Clients"
articleTitle: "Aspose::Email::Clients"
second_title: "Aspose.Email for C++"
description: "The Aspose::Email::Clients namespace supplies core client abstractions and utilities for sending, receiving, and managing email communications."
type: docs
weight: 10
url: /cpp/aspose.email.clients/
---

## Aspose::Email::Clients namespace

It defines interfaces such as IConnection and ICommand, concrete client classes, proxy support, and asynchronous operation types, enabling developers to integrate email functionality across various protocols. Use these types to build robust email client applications with customizable networking and error handling.


## Classes

| Name | Description |
| --- | --- |
| [AsyncCommandResultEventArgs](./asynccommandresulteventargs/) | AsyncCommandResultEventArgs is containing event data. |
| [CommandStatus](./commandstatus/) | Indicates the result of an operation. |
| [Details_NetworkException](./details_networkexception/) | Thrown if there is a network connection failure. |
| [EmailClient](./emailclient/) | Represents the client that creates server connection by using the host credentia |
| [HttpProxy](./httpproxy/) | HTTP proxy client. |
| [IAsyncResultExt](./iasyncresultext/) | Represents the extended status of an asynchronous operation. |
| [ICommand](./icommand/) | Defines a command. |
| [IConnection](./iconnection/) | IConnectionAdapter allows to manage connection to a server. |
| [IMultipleServicesTokenProvider](./imultipleservicestokenprovider/) | Defines interface allowing to retrieve access token. |
| [ITokenProvider](./itokenprovider/) | Defines interface allowing to retrieve access token. |
| [MessageInfoBase](./messageinfobase/) | The MessageInfo represents the E-Mail message info fetched from the mail server. |
| [NameValuePair](./namevaluepair/) | An extended property. |
| [OAuthNetworkCredential](./oauthnetworkcredential/) | Represents the NetworkCredential for OAuth authentication. |
| [OAuthToken](./oauthtoken/) | Contains OAuth token data such like token value, token type, expiration date. |
| [PageInfo](./pageinfo/) | Contains information about retrieved page when paging methods are used. |
| [PipeliningStatus](./pipeliningstatus/) | Defines pipelining status for mail client. |
| [Proxy](./proxy/) | Base proxy client. |
| [SecurityOptionsExtensions](./securityoptionsextensions/) |  |
| [SocksProxy](./socksproxy/) | SOCKS proxy client. Supported versions of the protocol are SOCKS4 and SOCKS5. |
| [TokenProvider](./tokenprovider/) | Class TokenProvider allows to retrieve access token for mail services. |

## Enumerations

| Name | Description |
| --- | --- |
| [AsyncCommandResults](./asynccommandresults/) | The result of asynchronous command. |
| [CompressionType](./compressiontype/) | Compression types which are used by mail protocols |
| [ConnectionAsgmtType](./connectionasgmttype/) | Defines algorithm of connection allocation in multiple threads environment |
| [ConnectionState](./connectionstate/) | Describes the current state of the connection. |
| [HttpAuthenticationMethods](./httpauthenticationmethods/) | The authentication methods supported by the HTTP proxy |
| [MultiConnectionMode](./multiconnectionmode/) | Enumerate modes which indicates how client has to use multiple connections for h |
| [PipeliningMode](./pipeliningmode/) | Defines how mail client supports the pipelining |
| [SecurityOptions](./securityoptions/) | Security mode for a mail client |
| [SocksAuthenticationMethods](./socksauthenticationmethods/) | The authentication methods supported by the SOCKS protocol |
| [SocksVersion](./socksversion/) | Versions of the SOCKS protocol |
| [TokenType](./tokentype/) | Defines OAuth token types |

