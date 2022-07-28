---
title: O365EmailMessageActivity
second_title: Aspose.Email für .NET-API-Referenz
description: Erweitert das allgemeine Schema um die für Office 365 Advanced Threat Protection- und Threat Intelligence-Daten spezifischen Eigenschaften. Office 365 Advanced Threat Protection ATP- und Threat Intelligence-Ereignisse sind für Office 365-Kunden verfügbar die über ein ATP- Threat Intelligence- oder E5-Abonnement verfügen . Jedes Ereignis im ATP- und Threat-Intelligence-Feed entspricht Eine von einem Benutzer in der Organisation gesendete oder empfangene E-Mail-Nachricht bei der Nachrichten zum Zeitpunkt der Zustellung und ab der automatischen Bereinigung zur Stunde Null erkannt wurden.
type: docs
weight: 2660
url: /de/net/aspose.email.clients.activity/o365emailmessageactivity/
---
## O365EmailMessageActivity class

Erweitert das allgemeine Schema um die für Office 365 Advanced Threat Protection- und Threat Intelligence-Daten spezifischen Eigenschaften. Office 365 Advanced Threat Protection (ATP)- und Threat Intelligence-Ereignisse sind für Office 365-Kunden verfügbar, die über ein ATP-, Threat Intelligence- oder E5-Abonnement verfügen . Jedes Ereignis im ATP- und Threat-Intelligence-Feed entspricht Eine von einem Benutzer in der Organisation gesendete oder empfangene E-Mail-Nachricht, bei der Nachrichten zum Zeitpunkt der Zustellung und ab der automatischen Bereinigung zur Stunde Null erkannt wurden.

```csharp
public class O365EmailMessageActivity : Content
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [O365EmailMessageActivity](o365emailmessageactivity)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AttachmentData](../../aspose.email.clients.activity/o365emailmessageactivity/attachmentdata) { get; set; } | Daten zu Anhängen in der E-Mail-Nachricht, die das Ereignis ausgelöst haben. Obligatorisch: Nein |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | Die IP-Adresse des Geräts, das verwendet wurde, als die Aktivität protokolliert wurde. Die IP-Adresse wird entweder im IPv4- oder im IPv6-Adressformat angezeigt. Obligatorisch: Ja |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | Das Datum und die Uhrzeit in koordinierter Weltzeit (UTC), wann der Benutzer die Aktivität durchgeführt hat. Obligatorisch: Ja |
| [DetectionMethod](../../aspose.email.clients.activity/o365emailmessageactivity/detectionmethod) { get; set; } | Die Methode oder Technologie, die von Office 365 ATP für die Erkennung verwendet wird. Obligatorisch: Ja |
| [DetectionType](../../aspose.email.clients.activity/o365emailmessageactivity/detectiontype) { get; set; } | Art der Erkennung. Obligatorisch: Ja |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Eindeutige Kennung eines Prüfprotokolls. Obligatorisch: Ja |
| [InternetMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/internetmessageid) { get; set; } | Die Internetnachrichten-ID. Obligatorisch: Ja |
| [NetworkMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/networkmessageid) { get; set; } | Die Exchange Online-Netzwerknachrichten-ID. Obligatorisch: Ja |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Für SharePoint- und OneDrive for Business-Aktivitäten der vollständige Pfadname der Datei oder des Ordners, auf die der Benutzer zugreift. Für die Exchange-Administratorüberwachungsprotokollierung der Name des Objekts, das durch das Cmdlet geändert wurde. Obligatorisch: Nein |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Der Name der Benutzer- oder Administratoraktivität. Eine Beschreibung der häufigsten Vorgänge/Aktivitäten finden Sie unter Durchsuchen des Überwachungsprotokolls im Office 365 Protection Center. Bei Exchange-Administratoraktivitäten gibt diese Eigenschaft den Namen des ausgeführten Cmdlets an. Für Dlp-Ereignisse kann dies „DlpRuleMatch“, „DlpRuleUndo“ oder „DlpInfo“ sein, die unten unter „DLP-Schema“ beschrieben werden. Obligatorisch: Ja |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Die GUID für den Office 365-Mandanten Ihrer Organisation. Dieser Wert ist für Ihre Organisation immer gleich, unabhängig vom Office 365-Dienst, in dem er vorkommt. Obligatorisch: Ja |
| [P1Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p1sender) { get; set; } | Der Rückweg des Absenders der E-Mail-Nachricht. Obligatorisch: Ja |
| [P2Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p2sender) { get; set; } | Der Absender der E-Mail-Nachricht. Obligatorisch: Ja |
| [Recipients](../../aspose.email.clients.activity/o365emailmessageactivity/recipients) { get; set; } | Ein Array von Empfängern der E-Mail-Nachricht. Obligatorisch: Ja |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Der vom Datensatz angegebene Vorgangstyp. Obligatorisch: Ja |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Gibt an, ob die Aktion (angegeben in der Operation-Eigenschaft) erfolgreich war oder nicht. Mögliche Werte sind Succeeded, PartiallySucceded oder Failed. Für Exchange-Administratoraktivitäten ist der Wert entweder True oder False. Obligatorisch: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Wurde dieses Ereignis von einem gehosteten O365-Dienst oder einem lokalen Server erstellt? Mögliche Werte sind online und onprem. Beachten Sie, dass SharePoint die einzige Workload ist, die derzeit Ereignisse von lokal an Office 365 sendet. Obligatorisch: No |
| [SenderIp](../../aspose.email.clients.activity/o365emailmessageactivity/senderip) { get; set; } | Die IP-Adresse, die die E-Mail von Office 365 gesendet hat. Die IP-Adresse wird entweder im IPv4- oder im IPv6-Adressformat angezeigt. Obligatorisch: Ja |
| [Subject](../../aspose.email.clients.activity/o365emailmessageactivity/subject) { get; set; } | Die Betreffzeile der Nachricht. Obligatorisch: Ja |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | Der UPN (User Principal Name) des Benutzers, der die Aktion (angegeben in der Operation-Eigenschaft) ausgeführt hat, die zur Protokollierung des Datensatzes geführt hat; zum Beispiel mein_name@mein_domänenname. Beachten Sie, dass Datensätze für Aktivitäten, die von Systemkonten (wie SHAREPOINT\system oder NT AUTHORITY\SYSTEM) ausgeführt werden, ebenfalls enthalten sind. Obligatorisch: Ja |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Eine alternative ID für den in der UserId-Eigenschaft identifizierten Benutzer. Beispielsweise wird diese Eigenschaft mit der eindeutigen Passport-ID (PUID) für Ereignisse aufgefüllt, die von Benutzern in SharePoint, OneDrive for Business und Exchange durchgeführt werden. Diese Eigenschaft kann auch denselben Wert wie die UserID-Eigenschaft für Ereignisse angeben, die in anderen Diensten auftreten, und Ereignisse, die von Systemkonten ausgeführt werden. Obligatorisch: Ja |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Der Benutzertyp, der den Vorgang ausgeführt hat. Obligatorisch: Ja |
| [Verdict](../../aspose.email.clients.activity/o365emailmessageactivity/verdict) { get; set; } | Das Nachrichtenurteil. Obligatorisch: Ja |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Der Office 365-Dienst, bei dem die Aktivität in der Workload-Zeichenfolge aufgetreten ist. Die möglichen Werte für diese Eigenschaft sind: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obligatorisch: No |

### Siehe auch

* class [Content](../content)
* namensraum [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
