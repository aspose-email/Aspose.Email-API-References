---
title: Ping
second_title: Aspose.Email för .NET API-referens
description: Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om.
type: docs
weight: 140
url: /sv/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping/
---
## Ping(string, FolderClass) {#ping_5}

Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om.

```csharp
public string[] Ping(string serverId, FolderClass fClass)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| serverId | String | Id-elementet är ett obligatoriskt underordnat element av Folder-elementet i Ping-kommandoförfrågningar som anger server-ID för mappen som ska övervakas. |
| fClass | FolderClass | Class-elementet är ett obligatoriskt underordnat element av Folder-elementet i Ping-kommandoförfrågningar som anger innehållsklassen för mappen som ska övervakas. |

### Returvärde

En rad mappar där ändringar har upptäckts

### Se även

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## Ping(int, string, FolderClass) {#ping_3}

Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om.

```csharp
public string[] Ping(int heartbeatInterval, string serverId, FolderClass fClass)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval anger hur lång tid, i sekunder, som servern SKA vänta innan den skickar ett svar om inga nya objekt läggs till i den angivna uppsättningen mappar. |
| serverId | String | Id-elementet är ett obligatoriskt underordnat element av Folder-elementet i Ping-kommandoförfrågningar som anger server-ID för mappen som ska övervakas. |
| fClass | FolderClass | Class-elementet är ett obligatoriskt underordnat element av Folder-elementet i Ping-kommandoförfrågningar som anger innehållsklassen för mappen som ska övervakas. |

### Returvärde

En rad mappar där ändringar har upptäckts

### Se även

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## Ping(params PingParameter[]) {#ping}

Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om.

```csharp
public string[] Ping(params PingParameter[] pingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pingParameters | PingParameter[] | Ping-parametrar |

### Returvärde

En rad mappar där ändringar har upptäckts

### Se även

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## Ping(int, params PingParameter[]) {#ping_1}

Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om.

```csharp
public string[] Ping(int heartbeatInterval, params PingParameter[] pingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval anger hur lång tid, i sekunder, som servern SKA vänta innan den skickar ett svar om inga nya objekt läggs till i den angivna uppsättningen mappar. |
| pingParameters | PingParameter[] | Ping-parametrar |

### Returvärde

En rad mappar där ändringar har upptäckts

### Se även

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## Ping(IEnumerable&lt;PingParameter&gt;) {#ping_4}

Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om.

```csharp
public string[] Ping(IEnumerable<PingParameter> pingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pingParameters | IEnumerable`1 | Ping-parametrar |

### Returvärde

En rad mappar där ändringar har upptäckts

### Se även

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## Ping(int, IEnumerable&lt;PingParameter&gt;) {#ping_2}

Ping-kommandot används för att begära att serverövervakaren angav mappar för ändringar som skulle kräva att klienten synkroniserar om.

```csharp
public string[] Ping(int heartbeatInterval, IEnumerable<PingParameter> pingParameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval anger hur lång tid, i sekunder, som servern SKA vänta innan den skickar ett svar om inga nya objekt läggs till i den angivna uppsättningen mappar. |
| pingParameters | IEnumerable`1 | Ping-parametrar |

### Returvärde

En rad mappar där ändringar har upptäckts

### Se även

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
