---
title: IBaseActiveSyncTLClient
second_title: Aspose.Email für .NET-API-Referenz
description: Basis-ActiveSync-Client-Schnittstelle
type: docs
weight: 1320
url: /de/net/aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/
---
## IBaseActiveSyncTLClient interface

Basis-ActiveSync-Client-Schnittstelle

```csharp
public interface IBaseActiveSyncTLClient : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/authenticationtype) { get; set; } | Ruft den vom ActiveSync-Client verwendeten Authentifizierungstyp ab oder legt ihn fest. |
| [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/autodiscoveruri) { get; set; } | Ruft die AutoErmittlung uri ab |
| [Credentials](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/credentials) { get; } | Anmeldeinformationen des Benutzers für Exchange server |
| [DeviceID](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/deviceid) { get; set; } | Eine GUID, die das Gerät identifiziert. Die Geräte-ID wird durch den Teil der Device-id-spec-ABNF-Regel des Klartext-Abfragewerts angegeben. Der Wert, dargestellt durch die Geräte-ID-ABNF-Regel, ist eine Zeichenfolge, die das Gerät angibt. Jedes Gerät MUSS eine eindeutige Geräte-ID-Zeichenfolge haben. Jede Anfrage vom Gerät MUSS denselben Geräte-ID-String enthalten. |
| [DeviceType](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/devicetype) { get; set; } | Der Gerätetyp wird durch den Teil der Device-Type-Spec-ABNF-Regel des Klartext-Abfragewerts angegeben. Der Wert, dargestellt durch die Gerätetyp-ABNF-Regel, ist eine beliebige Zeichenfolge, die einen Gerätetyp angibt. „SP“ bezeichnet ein SmartPhone und „PPC“ bezeichnet einen PocketPC. Andere Client-Geräte senden eindeutige Zeichenfolgen für ihren spezifischen Gerätetyp. Jede Anfrage von einem Client-Gerät MUSS denselben Gerätetyp-String enthalten. |
| [PolicyState](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/policystate) { get; set; } | Eine Ganzzahl ohne Vorzeichen, die den Status der Richtlinieneinstellungen auf dem Clientgerät angibt, wie in [MS-ASPROV] Abschnitt 2.2.2.41 angegeben. |
| [Proxy](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/proxy) { get; set; } | Ruft den Proxy ab oder legt ihn fest. |
| [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/supportedservercommands) { get; } | Ruft die Versionen von ActiveSync-Befehlen ab, die vom Server unterstützt werden |
| [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/supportedserverprotocols) { get; } | Ruft die Versionen von ActiveSync-Protokollen ab, die vom Server unterstützt werden |
| [Timeout](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/timeout) { get; set; } | Ruft die Anzahl der Millisekunden ab, die gewartet werden soll, bevor der Vorgang abläuft, oder legt diese fest. Der Standardwert ist 100.000 Millisekunden (100 Sekunden). |
| [Uri](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/uri) { get; } | Ruft den Server uri ab |
| [UserAgent](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/useragent) { get; set; } | Das User-Agent-Anforderungsheaderfeld enthält Informationen über den Benutzeragenten, der die Anforderung erstellt hat. Dies dient statistischen Zwecken, der Verfolgung von Protokollverstößen und der automatisierten Erkennung von Benutzerprogrammen zum Zweck der Anpassung von Antworten, um bestimmte Benutzerprogrammbeschränkungen zu vermeiden. Benutzeragenten SOLLTEN dieses Feld bei Anfragen einschließen. Das Feld kann mehrere Produkt-Token (Abschnitt 3.8) und Kommentare enthalten, die den Agenten und alle Unterprodukte identifizieren, die einen wesentlichen Teil des Benutzeragenten bilden. Per Konvention werden die Produkt-Token nach ihrer Bedeutung für die Identifizierung der Anwendung aufgelistet. Beispiel: User-Agent: CERN-LineMode/2.15 libwww/2.17b3 |
| [Version](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/version) { get; } | Ruft die Version des Protokolls ab, das im ActiveSync-Client verwendet wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Autodiscover](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/autodiscover)(string) | Der Autodiscover-Befehl erleichtert die Erkennung von Core-Kontokonfigurationsinformationen, indem die SMTP-Adresse (Simple Mail Transfer Protocol) des Benutzers als primäre Eingabe verwendet wird. |

### Siehe auch

* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
