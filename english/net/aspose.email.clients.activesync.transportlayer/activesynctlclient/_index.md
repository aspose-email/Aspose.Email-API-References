---
title: ActiveSyncTLClient
second_title: Aspose.Email for .NET API Reference
description: Basic class for ActiveSync client implementations
type: docs
weight: 950
url: /net/aspose.email.clients.activesync.transportlayer/activesynctlclient/
---
## ActiveSyncTLClient class

Basic class for ActiveSync client implementations

```csharp
public class ActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Properties

| Name | Description |
| --- | --- |
| virtual [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/authenticationtype) { get; set; } | Gets or sets the type of authentication is used by the ActiveSync client. |
| virtual [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscoveruri) { get; set; } | Gets or sets the autodiscover service uri |
| virtual [Credentials](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/credentials) { get; } | User's credentials for Exchange server |
| virtual [DeviceID](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/deviceid) { get; set; } | A GUID that identifies the device. The device ID is specified by the device-id-spec ABNF rule portion of the plain text query value. The value, represented by the device-id ABNF rule, is a string that specifies the device. Each device MUST have a unique device ID string. Each request from the device MUST include the same device ID string. |
| virtual [DeviceType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/devicetype) { get; set; } | The device type is specified by the device-type-spec ABNF rule portion of the plain text query value. The value, represented by the device-type ABNF rule, is any string that specifies a device type. "SP" specifies a SmartPhone and "PPC" specifies a PocketPC. Other client devices send unique strings for their specific device type. Each request from a client device MUST include the same device type string. |
| virtual [PolicyState](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/policystate) { get; set; } | An unsigned integer that indicates the state of policy settings on the client device, as specified in [MS-ASPROV] section 2.2.2.41. |
| virtual [Proxy](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/proxy) { get; set; } | Gets or sets the proxy. |
| virtual [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedservercommands) { get; } | Gets the versions of ActiveSync commands which are supported |
| virtual [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedserverprotocols) { get; } | Gets the versions of ActiveSync protocols which are supported |
| virtual [Timeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/timeout) { get; set; } | Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds). |
| virtual [Uri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/uri) { get; } | Gets the URL of ActiveSync service |
| virtual [UserAgent](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/useragent) { get; set; } | The User-Agent request-header field contains information about the user agent originating the request. This is for statistical purposes, the tracing of protocol violations, and automated recognition of user agents for the sake of tailoring responses to avoid particular user agent limitations. User agents SHOULD include this field with requests. The field can contain multiple product tokens (section 3.8) and comments identifying the agent and any subproducts which form a significant part of the user agent. By convention, the product tokens are listed in order of their significance for identifying the application. Example: User-Agent: CERN-LineMode/2.15 libwww/2.17b3 |
| virtual [Version](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/version) { get; } | Gets the version of the protocol which is used in ActiveSync client. |
| static [DefaultTimeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/defaulttimeout) { get; set; } | Gets or sets the default timeout value for ActiveSync client instances The default value is 100,000 milliseconds (100 seconds). |

## Methods

| Name | Description |
| --- | --- |
| virtual [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string) | The Autodiscover command facilitates the discovery of core account configuration information by using the user's Simple Mail Transfer Protocol (SMTP) address as the primary input. |
| [Dispose](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/dispose)() | Performs tasks associated with freeing, releasing, or resetting unmanaged resources. |
| static [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string, NetworkCredential, string) | The Autodiscover command facilitates the discovery of core account configuration information by using the user's Simple Mail Transfer Protocol (SMTP) address as the primary input. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance)(string, NetworkCredential) | Gets an instance of the ActiveSync client The version of the ActiveSync protocol is selected automatically according to server response. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance_1)(string, NetworkCredential, ASProtocolVersions) | Gets an instance of the ActiveSync client |
| static [GetOptions](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getoptions)(string, NetworkCredential, out string[], out string[]) | The GetOptions static method is used to discover what protocol versions are supported, and which protocol commands are supported on the server. The client uses the GetOptions static method to determine whether the server supports the same versions of the protocol that the client supports. |

### See Also

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
