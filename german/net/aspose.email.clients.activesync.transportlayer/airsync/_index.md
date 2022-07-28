---
title: AirSync
second_title: Aspose.Email für .NET-API-Referenz
description: AirSync-Namespace des ActiveSync-Protokolls
type: docs
weight: 960
url: /de/net/aspose.email.clients.activesync.transportlayer/airsync/
---
## AirSync enumeration

AirSync-Namespace des ActiveSync-Protokolls

```csharp
public enum AirSync
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Sync | `5` | Das Sync-Element ist ein erforderliches Element in Sync-Befehlsanforderungen und -antworten, das den Hauptteil des HTTP POST als einen Sync-Befehl enthaltend identifiziert (Abschnitt 2.2.2.19). Es ist das oberste Element im XML-Stream. |
| Responses | `6` | Enthält Antworten auf Operationen, die vom Server verarbeitet werden. |
| Add | `7` | Erstellt ein neues Objekt in einer Sammlung auf dem Client oder auf dem Server. |
| Change | `8` | Ändert Eigenschaften eines vorhandenen Objekts auf dem Clientgerät oder dem Server. |
| Delete | `9` | Löscht ein Objekt auf dem Clientgerät oder dem Server. Das Objekt wird durch sein ServerId-Element identifiziert. |
| Fetch | `10` | Wird verwendet, um die Anwendungsdaten eines Elements anzufordern, das in einer Synchronisierungsantwort vom Server abgeschnitten wurde. |
| SyncKey | `11` | Enthält einen Wert, der vom Server verwendet wird, um den Synchronisierungsstatus einer Sammlung zu markieren. |
| ClientId | `12` | Enthält einen eindeutigen Bezeichner (normalerweise eine Ganzzahl), der vom Client generiert wird, um vorübergehend ein neues Objekt zu identifizieren, das mithilfe des Add-Elements erstellt wird. |
| ServerId | `13` | Stellt eine eindeutige Kennung dar, die vom Server jedem synchronisierbaren Objekt zugewiesen wird. |
| Status | `14` | Gibt den Grund für das Fehlschlagen einer Befehlsanforderung an. |
| Collection | `15` | Enthält Befehle und Optionen, die für eine bestimmte Sammlung gelten. |
| Class | `16` | Identifiziert die Klasse des Elements, das der Sammlung hinzugefügt wird. |
| CollectionId | `18` | Gibt die Server-ID des zu synchronisierenden Ordners an. |
| GetChanges | `19` | Fordert an, dass der Server alle ausstehenden Änderungen an der Sammlung, die durch das ServerId-Element (Abschnitt 2.2.3.151.6) angegeben ist, in seine Antwort aufnimmt. |
| MoreAvailable | `20` | Gibt an, dass es mehr Änderungen gibt, als im WindowSize-Element angefordert werden (Abschnitt 2.2.3.183). |
| WindowSize | `21` | Gibt eine maximale Anzahl geänderter Elemente in einer Sammlung oder einer Anforderung an, die in die Synchronisierungsantwort aufgenommen werden SOLLTEN. |
| Commands | `22` | Enthält Vorgänge, die für eine Sammlung gelten. |
| Options | `23` | Enthält Elemente, die bestimmte Aspekte der Durchführung der Synchronisierung steuern. |
| FilterType | `24` | Gibt ein optionales Zeitfenster für die Objekte an, die vom Server an den Client gesendet werden. Es gilt für E-Mail- und Kalendersammlungen. |
| Conflict | `27` | Gibt an, wie der Konflikt gelöst wird, der auftritt, wenn ein Objekt sowohl auf dem Client als auch auf dem Server geändert wurde. |
| Collections | `28` | Dient als Container für das Collection-Element. |
| ApplicationData | `29` | Enthält Daten für ein bestimmtes Objekt, z. B. einen Kontakt, eine E-Mail-Nachricht, einen Kalendertermin oder ein Aufgabenelement. Kann verwendet werden, um Elemente zu ändern, Elemente hinzuzufügen oder Elemente auf dem Clientgerät oder Server abzurufen. |
| DeletesAsMoves | `30` | Gibt an, dass alle gelöschten Elemente in den Ordner „Gelöschte Elemente“ verschoben werden SOLLTEN. |
| Supported | `32` | Gibt an, welche Kontakt- und Kalenderelemente in einer Synchronisierungsanforderung vom Client verwaltet werden. |
| SoftDelete | `33` | Löscht ein Objekt vom Client, wenn es außerhalb der FilterType-Ergebnisse (Abschnitt 2.2.3.64.2) liegt oder nicht mehr in den SyncOptions-Anweisungen (Abschnitt 2.2.3.115.5) enthalten ist. |
| MIMESupport | `34` | Aktiviert die MIME-Unterstützung für E-Mail-Elemente, die vom Server an den Client gesendet werden. |
| MIMETruncation | `35` | Gibt an, ob die MIME-Daten des E-Mail-Elements abgeschnitten werden SOLLTEN, wenn es vom Server an den Client gesendet wird. |
| Wait | `36` | Gibt die Anzahl der Minuten an, die der Server eine Antwort verzögern SOLLTE, wenn keine neuen Elemente zu den enthaltenen Ordnern hinzugefügt werden, wie in Abschnitt 3.1.5.4 angegeben. |
| Limit | `37` | Gibt entweder die maximale Anzahl von Sammlungen an, die synchronisiert werden können, oder den maximal/minimal zulässigen Wert für das Warteintervall (Abschnitt 2.2.3.182) oder das HeartbeatInterval-Intervall (Abschnitt 2.2.3.79.2). |
| Partial | `38` | Zeigt dem Server an, dass der Client eine unvollständige Liste von Sammlungen gesendet hat, in diesem Fall erhält der Server die restlichen Sammlungen aus seinem Cache. |
| ConversationMode | `39` | Gibt an, ob Elemente, die in der Konversationsmodalität enthalten sind, in die Ergebnisse der Synchronisierungsantwort eingeschlossen werden sollen. |
| MaxItems | `40` | Gibt die maximale Anzahl von Empfängern (d. h. die obersten N der am häufigsten verwendeten Empfänger) an, die aus dem Empfängerinformationscache synchronisiert werden sollen. |
| HeartbeatInterval | `41` | Gibt die Anzahl der Sekunden an, die der Server eine Antwort verzögern SOLLTE, wenn keine neuen Elemente zu den enthaltenen Ordnern hinzugefügt werden, wie in Abschnitt 3.1.5.4 angegeben. |

### Siehe auch

* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
