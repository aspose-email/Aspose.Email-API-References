---
title: IActiveSyncTLClient
second_title: Aspose.Email für .NET-API-Referenz
description: ActiveSync-Client-Schnittstelle
type: docs
weight: 1310
url: /de/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/
---
## IActiveSyncTLClient interface

ActiveSync-Client-Schnittstelle

```csharp
public interface IActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AirSyncKeys](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/airsynckeys) { get; } | Enthält einen Wert, der vom Server verwendet wird, um den Synchronisierungsstatus jeder synchronisierten Sammlung zu markieren. Wobei der Wörterbuchschlüssel die Server-ID und der Wörterbuchwert SyncKey ist. Für GetItemEstimate- und Sync-Befehle. |
| [FoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderssynckey) { get; } | Wird vom Server verwendet, um den aktuellen Status des Clients zu verfolgen. Nur für Operationen mit Ordnern |
| [HeartbeatInterval](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/heartbeatinterval) { get; set; } | Das HeartbeatInterval-Element ist ein untergeordnetes Element des Ping-Elements in Ping-Befehlsanfragen und -antworten. In Ping-Befehlsanforderungen gibt es die Zeitspanne in Sekunden an, die der Server warten soll, bevor er eine Antwort sendet, wenn keine neuen Elemente zu den angegebenen Ordnern hinzugefügt werden, wie in Abschnitt 3.1.5.6 angegeben. Das HeartbeatInterval-Element wird ebenfalls vom Server mit einem Statuscode von 5 zurückgegeben und gibt entweder das minimale oder maximale Intervall an, das zulässig ist, wenn der Client ein Heartbeat-Intervall angefordert hat, das außerhalb des akzeptablen Bereichs liegt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FolderCreate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldercreate)(string, string, UserCreatedFolderTypes) | Das FolderCreate erstellt einen neuen Ordner als untergeordneten Ordner des angegebenen übergeordneten Ordners. |
| [FolderDelete](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderdelete)(string) | Löscht die Sammlung mit dem übereinstimmenden Bezeichner. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync)() | FolderSync synchronisiert die Sammlungshierarchie, aber nicht die Elemente in den Sammlungen selbst. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync_1)(bool) | FolderSync synchronisiert die Sammlungshierarchie, aber nicht die Elemente in den Sammlungen selbst. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate)(FolderInfo) | Der Befehl FolderUpdate verschiebt einen Ordner von einem Speicherort an einen anderen auf dem Server. Der Befehl wird auch verwendet, um einen Ordner umzubenennen. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate_1)(string, string, string) | Der Befehl FolderUpdate verschiebt einen Ordner von einem Speicherort an einen anderen auf dem Server. Der Befehl wird auch verwendet, um einen Ordner umzubenennen. |
| [GetAttachment](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getattachment)(string) | GetAttachment ruft einen E-Mail-Anhang vom Server ab. GetAttachment wird nicht unterstützt, wenn die Protokollversion 14.0 oder 14.1 ist. Verwenden Sie stattdessen das Fetch-Element des ItemOperations-Befehls. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_2)(IEnumerable&lt;ItemEstimateRequest&gt;) | Der Befehl GetItemEstimate ruft eine Schätzung der Anzahl der Elemente in einer Sammlung oder einem Ordner auf dem Server ab, die synchronisiert werden müssen. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate)(ItemEstimateRequest) | Der Befehl GetItemEstimate ruft eine Schätzung der Anzahl der Elemente in einer Sammlung oder einem Ordner auf dem Server ab, die synchronisiert werden müssen. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_1)(params ItemEstimateRequest[]) | Der Befehl GetItemEstimate ruft eine Schätzung der Anzahl der Elemente in einer Sammlung oder einem Ordner auf dem Server ab, die synchronisiert werden müssen. |
| [ItemOperations](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/itemoperations)(ItemOperationsRequest) | Die ItemOperations bieten eine stapelweise Online-Verarbeitung der Operationen Fetch, EmptyFolderContents und Move. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_3)(IEnumerable&lt;MeetingResponseRequest&gt;) | Nimmt eine Besprechungsanfrage im Ordner „Posteingang“ oder „Kalender“ des Benutzers an, nimmt sie mit Vorbehalt an oder lehnt sie ab. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_2)(params MeetingResponseRequest[]) | Nimmt eine Besprechungsanfrage im Ordner „Posteingang“ oder „Kalender“ des Benutzers an, nimmt sie mit Vorbehalt an oder lehnt sie ab. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse)(UserResponse, string, string) | Nimmt eine Besprechungsanfrage im Ordner „Posteingang“ oder „Kalender“ des Benutzers an, nimmt sie mit Vorbehalt an oder lehnt sie ab. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_1)(UserResponse, string, string, string, string) | Nimmt eine Besprechungsanfrage im Ordner „Posteingang“ oder „Kalender“ des Benutzers an, nimmt sie mit Vorbehalt an oder lehnt sie ab. |
| [MoveItem](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitem)(string, string, string) | Der MoveItems-Befehl verschiebt ein oder mehrere Elemente von einem Ordner auf dem Server in einen anderen. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems_1)(IEnumerable&lt;MoveItemData&gt;) | Der MoveItems-Befehl verschiebt ein oder mehrere Elemente von einem Ordner auf dem Server in einen anderen. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems)(params MoveItemData[]) | Der MoveItems-Befehl verschiebt ein oder mehrere Elemente von einem Ordner auf dem Server in einen anderen. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_4)(IEnumerable&lt;PingParameter&gt;) | Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping)(params PingParameter[]) | Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_2)(int, IEnumerable&lt;PingParameter&gt;) | Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_1)(int, params PingParameter[]) | Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_5)(string, FolderClass) | Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_3)(int, string, FolderClass) | Der Ping-Befehl wird verwendet, um anzufordern, dass der Server bestimmte Ordner auf Änderungen überwacht, die eine Neusynchronisierung des Clients erfordern würden. |
| [Provision](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/provision)(ProvisionRequest) | Der Bereitstellungsbefehl ermöglicht es Client-Geräten, vom Server die Sicherheitsrichtlinieneinstellungen anzufordern, die der Administrator festlegt, wie z. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey)() | SyncKeys für GetItemEstimate- und Sync-Vorgänge für alle Sammlungen zurücksetzen. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey_1)(string) | SyncKey für GetItemEstimate- und Sync-Vorgänge für definierte Sammlung zurücksetzen. |
| [ResetFoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetfolderssynckey)() | SyncKey für Operationen mit Ordnern zurücksetzen |
| [ResolveRecipients](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resolverecipients)(ResolveRecipientsRequest) | ResolveRecipients wird verwendet, um eine Liste bereitgestellter Empfänger aufzulösen, ihre Frei/Gebucht-Informationen abzurufen und optional ihre S/MIME-Zertifikate abzurufen, damit Clients verschlüsselte S/MIME-E-Mail-Nachrichten senden können. Abrufen von Frei/Gebucht-Informationen Die Verwendung des Availability-Elements im ResolveRecipients-Befehl wird nicht unterstützt, wenn die Protokollversion 12.1. ist. |
| [Search](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/search)(SearchRequest) | Die Suche wird verwendet, um Einträge in einem Adressbuch, Postfach oder einer Dokumentbibliothek (UNC oder Windows SharePoint Services) zu finden. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail)(string) | SendMail wird von Clients verwendet, um E-Mail-Nachrichten im MIME-Format an den Server zu senden. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_1)(string, bool) | SendMail wird von Clients verwendet, um E-Mail-Nachrichten im MIME-Format an den Server zu senden. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_2)(string, bool, string) | SendMail wird von Clients verwendet, um E-Mail-Nachrichten im MIME-Format an den Server zu senden. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_3)(string, bool, string, string) | SendMail wird von Clients verwendet, um E-Mail-Nachrichten im MIME-Format an den Server zu senden. |
| [Settings](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/settings)(SettingsRequest) | Die Einstellungen unterstützen Get- und Set-Vorgänge für globale Eigenschaften und Abwesenheitseinstellungen für den Benutzer. Die Einstellungen senden auch Geräteinformationen an den Server, implementieren die Wiederherstellung des Gerätekennworts/der persönlichen Identifikationsnummer (PIN) und rufen eine Liste der E-Mail-Adressen des Benutzers ab. |
| [SmartForward](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartforward)(SmartRequest) | Der SmartForward-Befehl wird von Clients verwendet, um Nachrichten weiterzuleiten, ohne die vollständige Originalnachricht vom Server abzurufen. |
| [SmartReply](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartreply)(SmartRequest) | Der SmartReply-Befehl wird von Clients verwendet, um auf Nachrichten zu antworten, ohne die vollständige Originalnachricht vom Server abzurufen. |
| [Sync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sync)(SyncRequest) | Die Synchronisierung synchronisiert Änderungen in einer Sammlung zwischen dem Client und dem Server. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert)(IEnumerable&lt;X509Certificate&gt;) | Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_4)(X509Certificate) | Der Befehl ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_1)(IEnumerable&lt;X509Certificate&gt;, bool) | Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_2)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) | Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_5)(X509Certificate, bool) | Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_6)(X509Certificate, IEnumerable&lt;X509Certificate&gt;) | Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_3)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) | Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_7)(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) | Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde. |

### Siehe auch

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
