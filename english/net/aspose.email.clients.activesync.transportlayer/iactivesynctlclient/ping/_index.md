---
title: Ping
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 140
url: /net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping/
---
## IActiveSyncTLClient.Ping method (1 of 6)

The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize.

```csharp
public string[] Ping(string serverId, FolderClass fClass)
```

| Parameter | Type | Description |
| --- | --- | --- |
| serverId | String | The Id element is a required child element of the Folder element in Ping command requests that specifies the server ID of the folder to be monitored. |
| fClass | FolderClass | The Class element is a required child element of the Folder element in Ping command requests that specifies the content class of the folder to be monitored. |

## Return Value

Array of folders where changes has been discovered

### See Also

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## IActiveSyncTLClient.Ping method (2 of 6)

The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize.

```csharp
public string[] Ping(int heartbeatInterval, string serverId, FolderClass fClass)
```

| Parameter | Type | Description |
| --- | --- | --- |
| heartbeatInterval | Int32 | The HeartbeatInterval specifies the length of time, in seconds, that the server SHOULD wait before sending a response if no new items are added to the specified set of folders. |
| serverId | String | The Id element is a required child element of the Folder element in Ping command requests that specifies the server ID of the folder to be monitored. |
| fClass | FolderClass | The Class element is a required child element of the Folder element in Ping command requests that specifies the content class of the folder to be monitored. |

## Return Value

Array of folders where changes has been discovered

### See Also

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## IActiveSyncTLClient.Ping method (3 of 6)

The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize.

```csharp
public string[] Ping(params PingParameter[] pingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pingParameters | PingParameter[] | Ping parameters |

## Return Value

Array of folders where changes has been discovered

### See Also

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## IActiveSyncTLClient.Ping method (4 of 6)

The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize.

```csharp
public string[] Ping(int heartbeatInterval, params PingParameter[] pingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| heartbeatInterval | Int32 | The HeartbeatInterval specifies the length of time, in seconds, that the server SHOULD wait before sending a response if no new items are added to the specified set of folders. |
| pingParameters | PingParameter[] | Ping parameters |

## Return Value

Array of folders where changes has been discovered

### See Also

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## IActiveSyncTLClient.Ping method (5 of 6)

The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize.

```csharp
public string[] Ping(IEnumerable<PingParameter> pingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pingParameters | IEnumerable`1 | Ping parameters |

## Return Value

Array of folders where changes has been discovered

### See Also

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## IActiveSyncTLClient.Ping method (6 of 6)

The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize.

```csharp
public string[] Ping(int heartbeatInterval, IEnumerable<PingParameter> pingParameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| heartbeatInterval | Int32 | The HeartbeatInterval specifies the length of time, in seconds, that the server SHOULD wait before sending a response if no new items are added to the specified set of folders. |
| pingParameters | IEnumerable`1 | Ping parameters |

## Return Value

Array of folders where changes has been discovered

### See Also

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
