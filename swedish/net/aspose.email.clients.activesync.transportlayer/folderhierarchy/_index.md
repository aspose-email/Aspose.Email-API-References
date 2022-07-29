---
title: FolderHierarchy
second_title: Aspose.Email för .NET API-referens
description: FolderHierarchy namespace för ActiveSync-protokollet
type: docs
weight: 1250
url: /sv/net/aspose.email.clients.activesync.transportlayer/folderhierarchy/
---
## FolderHierarchy enumeration

FolderHierarchy namespace för ActiveSync-protokollet

```csharp
public enum FolderHierarchy
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| DisplayName | `7` | Anger namnet på mappen som visas för användaren. |
| ServerId | `8` | Identifierar en mapp på en server. |
| ParentId | `9` | Anger server-ID för den överordnade mappen för mappen på server |
| Type | `10` | Anger typen av mapp som ska skapas. |
| Status | `12` | Indikerar orsaken till misslyckandet i en kommandobegäran. |
| Changes | `14` | Innehåller ändringar av mapphierarkin. |
| Add | `15` | Skapar en ny mapp på client |
| Delete | `16` | Anger att en mapp på servern raderades sedan den senaste mappsynkroniseringen. |
| Update | `17` | Identifierar en mapp på servern som har uppdaterats (döpt om eller flyttat). |
| SyncKey | `18` | Den används av servern för att spåra klientens nuvarande tillstånd. |
| FolderCreate | `19` | FolderCreate-elementet är ett obligatoriskt element i FolderCreate-kommandoförfrågningar och FolderCreate-kommandosvar som identifierar kroppen av HTTP POST som innehållande ett FolderCreate-kommando (avsnitt 2.2.2.2). |
| FolderDelete | `20` | FolderDelete-elementet är ett obligatoriskt element i FolderDelete-kommandoförfrågningar och FolderDelete-kommandosvar som identifierar kroppen av HTTP POST som innehållande ett FolderDelete-kommando (avsnitt 2.2.2.3). |
| FolderUpdate | `21` | FolderUpdate-elementet är ett obligatoriskt element i FolderUpdate-kommandoförfrågningar och FolderUpdate-kommandosvar som identifierar kroppen av HTTP POST som innehållande ett FolderUpdate-kommando (avsnitt 2.2.2.5). |
| FolderSync | `22` | FolderSync-elementet är ett obligatoriskt element i FolderSync-kommandoförfrågningar och FolderSync-kommandosvar som identifierar kroppen av HTTP POST som innehållande ett FolderSync-kommando (avsnitt 2.2.2.4). |
| Count | `23` | Anger antalet tillagda, borttagna och uppdaterade mappar på servern sedan den senaste mappsynkroniseringen. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->