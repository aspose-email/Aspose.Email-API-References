---
title: Ping
second_title: Aspose.Email für .NET-API-Referenz
description: Der Ping-Befehl wird verwendet um anzufordern dass der Server bestimmte Ordner auf Änderungen überwacht die eine Neusynchronisierung des Clients erfordern würden.
type: docs
weight: 140
url: /de/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping/
---
## Ping(string, FolderClass) {#ping_5}

Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden.

```csharp
public string[] Ping(string serverId, FolderClass fClass)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| serverId | String | Das Id-Element ist ein erforderliches untergeordnetes Element des Folder-Elements in Ping-Befehlsanfragen, das die Server-ID des zu überwachenden Ordners angibt. |
| fClass | FolderClass | Das Class-Element ist ein erforderliches untergeordnetes Element des Folder-Elements in Ping-Befehlsanfragen, das die Inhaltsklasse des zu überwachenden Ordners angibt. |

### Rückgabewert

Array von Ordnern, in denen Änderungen erkannt wurden

### Siehe auch

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## Ping(int, string, FolderClass) {#ping_3}

Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden.

```csharp
public string[] Ping(int heartbeatInterval, string serverId, FolderClass fClass)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| heartbeatInterval | Int32 | Das HeartbeatInterval gibt die Zeitspanne in Sekunden an, die der Server warten SOLLTE, bevor er eine Antwort sendet, wenn dem angegebenen Ordnersatz keine neuen Elemente hinzugefügt werden. |
| serverId | String | Das Id-Element ist ein erforderliches untergeordnetes Element des Folder-Elements in Ping-Befehlsanfragen, das die Server-ID des zu überwachenden Ordners angibt. |
| fClass | FolderClass | Das Class-Element ist ein erforderliches untergeordnetes Element des Folder-Elements in Ping-Befehlsanfragen, das die Inhaltsklasse des zu überwachenden Ordners angibt. |

### Rückgabewert

Array von Ordnern, in denen Änderungen erkannt wurden

### Siehe auch

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## Ping(params PingParameter[]) {#ping}

Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden.

```csharp
public string[] Ping(params PingParameter[] pingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pingParameters | PingParameter[] | Ping-Parameter |

### Rückgabewert

Array von Ordnern, in denen Änderungen erkannt wurden

### Siehe auch

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## Ping(int, params PingParameter[]) {#ping_1}

Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden.

```csharp
public string[] Ping(int heartbeatInterval, params PingParameter[] pingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| heartbeatInterval | Int32 | Das HeartbeatInterval gibt die Zeitspanne in Sekunden an, die der Server warten SOLLTE, bevor er eine Antwort sendet, wenn dem angegebenen Ordnersatz keine neuen Elemente hinzugefügt werden. |
| pingParameters | PingParameter[] | Ping-Parameter |

### Rückgabewert

Array von Ordnern, in denen Änderungen erkannt wurden

### Siehe auch

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## Ping(IEnumerable&lt;PingParameter&gt;) {#ping_4}

Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden.

```csharp
public string[] Ping(IEnumerable<PingParameter> pingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pingParameters | IEnumerable`1 | Ping-Parameter |

### Rückgabewert

Array von Ordnern, in denen Änderungen erkannt wurden

### Siehe auch

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## Ping(int, IEnumerable&lt;PingParameter&gt;) {#ping_2}

Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden.

```csharp
public string[] Ping(int heartbeatInterval, IEnumerable<PingParameter> pingParameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| heartbeatInterval | Int32 | Das HeartbeatInterval gibt die Zeitspanne in Sekunden an, die der Server warten SOLLTE, bevor er eine Antwort sendet, wenn dem angegebenen Ordnersatz keine neuen Elemente hinzugefügt werden. |
| pingParameters | IEnumerable`1 | Ping-Parameter |

### Rückgabewert

Array von Ordnern, in denen Änderungen erkannt wurden

### Siehe auch

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
