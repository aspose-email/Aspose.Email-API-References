---
title: ActiveSyncTLClient
second_title: Aspose.Email für .NET-API-Referenz
description: Basisklasse für ActiveSync-Client-Implementierungen
type: docs
weight: 950
url: /de/net/aspose.email.clients.activesync.transportlayer/activesynctlclient/
---
## ActiveSyncTLClient class

Basisklasse für ActiveSync-Client-Implementierungen

```csharp
public class ActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/authenticationtype) { get; set; } | Ruft den vom ActiveSync-Client verwendeten Authentifizierungstyp ab oder legt ihn fest. |
| virtual [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscoveruri) { get; set; } | Ruft den Autodiscover-Dienst uri ab oder legt ihn fest |
| virtual [Credentials](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/credentials) { get; } | Anmeldeinformationen des Benutzers für Exchange server |
| virtual [DeviceID](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/deviceid) { get; set; } | Eine GUID, die das Gerät identifiziert. Die Geräte-ID wird durch den Teil der Device-id-spec-ABNF-Regel des Klartext-Abfragewerts angegeben. Der Wert, dargestellt durch die Geräte-ID-ABNF-Regel, ist eine Zeichenfolge, die das Gerät angibt. Jedes Gerät MUSS eine eindeutige Geräte-ID-Zeichenfolge haben. Jede Anfrage vom Gerät MUSS denselben Geräte-ID-String enthalten. |
| virtual [DeviceType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/devicetype) { get; set; } | Der Gerätetyp wird durch den Teil der Device-Type-Spec-ABNF-Regel des Klartext-Abfragewerts angegeben. Der Wert, dargestellt durch die Gerätetyp-ABNF-Regel, ist eine beliebige Zeichenfolge, die einen Gerätetyp angibt. „SP“ bezeichnet ein SmartPhone und „PPC“ bezeichnet einen PocketPC. Andere Client-Geräte senden eindeutige Zeichenfolgen für ihren spezifischen Gerätetyp. Jede Anfrage von einem Client-Gerät MUSS denselben Gerätetyp-String enthalten. |
| virtual [PolicyState](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/policystate) { get; set; } | Eine Ganzzahl ohne Vorzeichen, die den Status der Richtlinieneinstellungen auf dem Clientgerät angibt, wie in [MS-ASPROV] Abschnitt 2.2.2.41 angegeben. |
| virtual [Proxy](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/proxy) { get; set; } | Ruft den Proxy ab oder legt ihn fest. |
| virtual [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedservercommands) { get; } | Ruft die Versionen von ActiveSync-Befehlen ab, die unterstützt werden |
| virtual [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedserverprotocols) { get; } | Ruft die Versionen von ActiveSync-Protokollen ab, die unterstützt werden |
| virtual [Timeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/timeout) { get; set; } | Ruft die Anzahl der Millisekunden ab, die gewartet werden soll, bevor der Vorgang abläuft, oder legt diese fest. Der Standardwert ist 100.000 Millisekunden (100 Sekunden). |
| virtual [Uri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/uri) { get; } | Ruft die URL des ActiveSync-Dienstes ab |
| virtual [UserAgent](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/useragent) { get; set; } | Das User-Agent-Anforderungsheaderfeld enthält Informationen über den Benutzeragenten, der die Anforderung erstellt hat. Dies dient statistischen Zwecken, der Verfolgung von Protokollverstößen und der automatisierten Erkennung von Benutzerprogrammen zum Zweck der Anpassung von Antworten, um bestimmte Benutzerprogrammbeschränkungen zu vermeiden. Benutzeragenten SOLLTEN dieses Feld bei Anfragen einschließen. Das Feld kann mehrere Produkt-Token (Abschnitt 3.8) und Kommentare enthalten, die den Agenten und alle Unterprodukte identifizieren, die einen wesentlichen Teil des Benutzeragenten bilden. Per Konvention werden die Produkt-Token nach ihrer Bedeutung für die Identifizierung der Anwendung aufgelistet. Beispiel: User-Agent: CERN-LineMode/2.15 libwww/2.17b3 |
| virtual [Version](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/version) { get; } | Ruft die Version des Protokolls ab, das im ActiveSync-Client verwendet wird. |
| static [DefaultTimeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/defaulttimeout) { get; set; } | Ruft den Standardzeitüberschreitungswert für ActiveSync-Clientinstanzen ab oder legt ihn fest Der Standardwert ist 100.000 Millisekunden (100 Sekunden). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string) | Der Autodiscover-Befehl erleichtert die Erkennung von Core-Kontokonfigurationsinformationen, indem die SMTP-Adresse (Simple Mail Transfer Protocol) des Benutzers als primäre Eingabe verwendet wird. |
| [Dispose](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/dispose)() | Führt Aufgaben im Zusammenhang mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen aus. |
| static [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string, NetworkCredential, string) | Der Autodiscover-Befehl erleichtert die Erkennung von Core-Kontokonfigurationsinformationen, indem die SMTP-Adresse (Simple Mail Transfer Protocol) des Benutzers als primäre Eingabe verwendet wird. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance)(string, NetworkCredential) | Ruft eine Instanz des ActiveSync-Clients ab Die Version des ActiveSync-Protokolls wird automatisch entsprechend der Serverantwort ausgewählt. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance_1)(string, NetworkCredential, ASProtocolVersions) | Ruft eine Instanz des ActiveSync-Clients ab |
| static [GetOptions](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getoptions)(string, NetworkCredential, out string[], out string[]) | Die statische Methode GetOptions wird verwendet, um festzustellen, welche Protokollversionen unterstützt werden und welche Protokollbefehle auf dem Server unterstützt werden. Der Client verwendet die statische Methode GetOptions, um festzustellen, ob der Server dieselben Versionen des Protokolls unterstützt, die der Client unterstützt. |

### Siehe auch

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
