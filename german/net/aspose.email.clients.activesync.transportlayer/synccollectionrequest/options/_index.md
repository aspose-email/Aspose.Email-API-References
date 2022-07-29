---
title: Options
second_title: Aspose.Email für .NET-API-Referenz
description: Gibt Optionen an die bestimmte Aspekte der Durchführung der Synchronisierung steuern. Zulässige Anzahl 0...2. Synchronisierungsoptionen ermöglichen es dem Client Kürzungs- und Inhaltseinstellungen anzugeben. Diese Einstellungen sind in einem untergeordneten airsyncbaseBodyPreference-Element gekapselt wie in MS-ASAIRS Abschnitt 2.2.2.7 angegeben. Da Synchronisierungsoptionen für eine Sammlung angegeben werden kann der Client einen eindeutigen airsyncbaseBodyPreference-Elementwert für jede zu synchronisierende Sammlung angeben. Weitere Einzelheiten zum airsyncbaseBodyPreference-Element finden Sie in MS-ASAIRS Abschnitt 2.2. 2.7. Der Server behält den Optionsblock über Anforderungen hinweg bei wobei er ein Konzept verwendet das als Sticky Options bezeichnet wird. Wenn der Optionsblock nicht in einer Anfrage enthalten ist wird der vorherige Optionsblock verwendet. Wenn der Client neue Optionen angibt indem er einen Optionsblock in die Anfrage einfügt MUSS der Server den ursprünglichen Optionsblock durch den neuen Optionsblock ersetzen. Wenn zwei Optionselemente in einer einzigen Sync-Befehlsanforderung enthalten sind MUSS eines der Optionselemente Geben Sie die Synchronisierungsoptionen für die SMS-Klasse an während das andere Optionselement die Optionen für die Standardklasse des angegebenen Ordners angibt.
type: docs
weight: 70
url: /de/net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/options/
---
## SyncCollectionRequest.Options property

Gibt Optionen an, die bestimmte Aspekte der Durchführung der Synchronisierung steuern. Zulässige Anzahl 0...2. Synchronisierungsoptionen ermöglichen es dem Client, Kürzungs- und Inhaltseinstellungen anzugeben. Diese Einstellungen sind in einem untergeordneten airsyncbase:BodyPreference-Element gekapselt, wie in [MS-ASAIRS] Abschnitt 2.2.2.7 angegeben. Da Synchronisierungsoptionen für eine Sammlung angegeben werden, kann der Client einen eindeutigen airsyncbase:BodyPreference-Elementwert für jede zu synchronisierende Sammlung angeben. Weitere Einzelheiten zum airsyncbase:BodyPreference-Element finden Sie in [MS-ASAIRS] Abschnitt 2.2. 2.7. Der Server behält den Optionsblock über Anforderungen hinweg bei, wobei er ein Konzept verwendet, das als "Sticky Options" bezeichnet wird. Wenn der Optionsblock nicht in einer Anfrage enthalten ist, wird der vorherige Optionsblock verwendet. Wenn der Client neue Optionen angibt, indem er einen Optionsblock in die Anfrage einfügt, MUSS der Server den ursprünglichen Optionsblock durch den neuen Optionsblock ersetzen. Wenn zwei Optionselemente in einer einzigen Sync-Befehlsanforderung enthalten sind, MUSS eines der Optionselemente Geben Sie die Synchronisierungsoptionen für die SMS-Klasse an, während das andere Optionselement die Optionen für die Standardklasse des angegebenen Ordners angibt.

```csharp
public List<SyncOptions> Options { get; }
```

### Siehe auch

* class [SyncOptions](../../syncoptions)
* class [SyncCollectionRequest](../../synccollectionrequest)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../synccollectionrequest)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->