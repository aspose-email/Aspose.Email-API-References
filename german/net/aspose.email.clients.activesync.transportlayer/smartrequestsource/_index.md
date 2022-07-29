---
title: SmartRequestSource
second_title: Aspose.Email für .NET-API-Referenz
description: Enthält Informationen über die Quellnachricht.
type: docs
weight: 2100
url: /de/net/aspose.email.clients.activesync.transportlayer/smartrequestsource/
---
## SmartRequestSource class

Enthält Informationen über die Quellnachricht.

```csharp
public class SmartRequestSource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SmartRequestSource](smartrequestsource)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FolderId](../../aspose.email.clients.activesync.transportlayer/smartrequestsource/folderid) { get; set; } | Gibt die Ordner-ID für die Quellnachricht an, die im FolderSync-Befehl zurückgegeben wird. Wenn die FolderId vorhanden ist, MUSS auch die ItemId vorhanden sein. Der FolderId-Wert kann bis zu 64 Zeichen lang sein. |
| [InstanceId](../../aspose.email.clients.activesync.transportlayer/smartrequestsource/instanceid) { get; set; } | Gibt die Instanz einer Wiederholung für das Quellelement an. Wenn die InstanceId vorhanden ist, SOLLTEN sowohl die FolderId als auch die ItemId vorhanden sein. |
| [ItemId](../../aspose.email.clients.activesync.transportlayer/smartrequestsource/itemid) { get; set; } | Gibt die Element-ID für die Quellnachricht an, die im Sync-Befehl zurückgegeben wird. Wenn die ItemId vorhanden ist, MUSS die FolderId ebenfalls vorhanden sein, wenn die weitergeleitete oder beantwortete Nachricht in einem anderen Ordner als dem Posteingangsordner gespeichert ist. Der ItemId-Elementwert kann bis zu 64 Zeichen lang sein. |
| [LongId](../../aspose.email.clients.activesync.transportlayer/smartrequestsource/longid) { get; set; } | Gibt die lange ID für die Quellnachricht an, die im Suchbefehl zurückgegeben wird. Wenn LongId vorhanden ist, sind FolderId, ItemId und InstanceId nicht vorhanden. Der LongId-Wert kann bis zu 256 Zeichen lang sein. |

### Siehe auch

* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->