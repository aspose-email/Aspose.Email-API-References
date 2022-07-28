---
title: ExchangeMailboxActivity
second_title: Aspose.Email für .NET-API-Referenz
description: Erweitert das allgemeine Schema um die Eigenschaften die für alle Exchange-Postfachüberwachungsdaten spezifisch sind.
type: docs
weight: 2510
url: /de/net/aspose.email.clients.activity/exchangemailboxactivity/
---
## ExchangeMailboxActivity class

Erweitert das allgemeine Schema um die Eigenschaften, die für alle Exchange-Postfachüberwachungsdaten spezifisch sind.

```csharp
public class ExchangeMailboxActivity : Content
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ExchangeMailboxActivity](exchangemailboxactivity)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ClientInfoString](../../aspose.email.clients.activity/exchangemailboxactivity/clientinfostring) { get; set; } | Informationen zum E-Mail-Client, der zum Ausführen des Vorgangs verwendet wurde, z. B. Browserversion, Outlook-Version und Informationen zum Mobilgerät. |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | Die IP-Adresse des Geräts, das verwendet wurde, als die Aktivität protokolliert wurde. Die IP-Adresse wird entweder im IPv4- oder im IPv6-Adressformat angezeigt. Obligatorisch: Ja |
| [ClientIPAddress](../../aspose.email.clients.activity/exchangemailboxactivity/clientipaddress) { get; set; } | Die IP-Adresse des Geräts, das verwendet wurde, als der Vorgang protokolliert wurde. Die IP-Adresse wird entweder im IPv4- oder im IPv6-Adressformat angezeigt. |
| [ClientMachineName](../../aspose.email.clients.activity/exchangemailboxactivity/clientmachinename) { get; set; } | Der Computername, der den Outlook-Client hostet. |
| [ClientProcessName](../../aspose.email.clients.activity/exchangemailboxactivity/clientprocessname) { get; set; } | Der E-Mail-Client, der für den Zugriff auf das Postfach verwendet wurde. |
| [ClientVersion](../../aspose.email.clients.activity/exchangemailboxactivity/clientversion) { get; set; } | Die Version des E-Mail-Clients. |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | Das Datum und die Uhrzeit in koordinierter Weltzeit (UTC), wann der Benutzer die Aktivität durchgeführt hat. Obligatorisch: Ja |
| [ExternalAccess](../../aspose.email.clients.activity/exchangemailboxactivity/externalaccess) { get; set; } | Dies gilt, wenn sich die Domäne des angemeldeten Benutzers von der Domäne des Postfachbesitzers unterscheidet. |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Eindeutige Kennung eines Prüfprotokolls. Obligatorisch: Ja |
| [InternalLogonType](../../aspose.email.clients.activity/exchangemailboxactivity/internallogontype) { get; set; } | Reserviert für den internen Gebrauch. |
| [LogonType](../../aspose.email.clients.activity/exchangemailboxactivity/logontype) { get; set; } | Gibt den Benutzertyp an, der auf das Postfach zugegriffen und den protokollierten Vorgang ausgeführt hat. |
| [LogonUserDisplayName](../../aspose.email.clients.activity/exchangemailboxactivity/logonuserdisplayname) { get; set; } | Der benutzerfreundliche Name des Benutzers, der die Operation durchgeführt hat. |
| [LogonUserSid](../../aspose.email.clients.activity/exchangemailboxactivity/logonusersid) { get; set; } | Die SID des Benutzers, der die Operation durchgeführt hat. |
| [MailboxGuid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxguid) { get; set; } | Die Exchange-GUID des Postfachs, auf das zugegriffen wurde. |
| [MailboxOwnerMasterAccountSid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownermasteraccountsid) { get; set; } | Hauptkonto-SID des Postfachbesitzerkontos. |
| [MailboxOwnerSid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownersid) { get; set; } | Die SID des Postfachbesitzers. |
| [MailboxOwnerUPN](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownerupn) { get; set; } | Die E-Mail-Adresse der Person, der das Postfach gehört, auf das zugegriffen wurde. |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Für SharePoint- und OneDrive for Business-Aktivitäten der vollständige Pfadname der Datei oder des Ordners, auf die der Benutzer zugreift. Für die Exchange-Administratorüberwachungsprotokollierung der Name des Objekts, das durch das Cmdlet geändert wurde. Obligatorisch: Nein |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Der Name der Benutzer- oder Administratoraktivität. Eine Beschreibung der häufigsten Vorgänge/Aktivitäten finden Sie unter Durchsuchen des Überwachungsprotokolls im Office 365 Protection Center. Bei Exchange-Administratoraktivitäten gibt diese Eigenschaft den Namen des ausgeführten Cmdlets an. Für Dlp-Ereignisse kann dies „DlpRuleMatch“, „DlpRuleUndo“ oder „DlpInfo“ sein, die unten unter „DLP-Schema“ beschrieben werden. Obligatorisch: Ja |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Die GUID für den Office 365-Mandanten Ihrer Organisation. Dieser Wert ist für Ihre Organisation immer gleich, unabhängig vom Office 365-Dienst, in dem er vorkommt. Obligatorisch: Ja |
| [OrganizationName](../../aspose.email.clients.activity/exchangemailboxactivity/organizationname) { get; set; } | Der Name des Mieters. |
| [OriginatingServer](../../aspose.email.clients.activity/exchangemailboxactivity/originatingserver) { get; set; } | Von hier stammt die Operation. |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Der vom Datensatz angegebene Vorgangstyp. Obligatorisch: Ja |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Gibt an, ob die Aktion (angegeben in der Operation-Eigenschaft) erfolgreich war oder nicht. Mögliche Werte sind Succeeded, PartiallySucceded oder Failed. Für Exchange-Administratoraktivitäten ist der Wert entweder True oder False. Obligatorisch: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Wurde dieses Ereignis von einem gehosteten O365-Dienst oder einem lokalen Server erstellt? Mögliche Werte sind online und onprem. Beachten Sie, dass SharePoint die einzige Workload ist, die derzeit Ereignisse von lokal an Office 365 sendet. Obligatorisch: No |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | Der UPN (User Principal Name) des Benutzers, der die Aktion (angegeben in der Operation-Eigenschaft) ausgeführt hat, die zur Protokollierung des Datensatzes geführt hat; zum Beispiel mein_name@mein_domänenname. Beachten Sie, dass Datensätze für Aktivitäten, die von Systemkonten (wie SHAREPOINT\system oder NT AUTHORITY\SYSTEM) ausgeführt werden, ebenfalls enthalten sind. Obligatorisch: Ja |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Eine alternative ID für den in der UserId-Eigenschaft identifizierten Benutzer. Beispielsweise wird diese Eigenschaft mit der eindeutigen Passport-ID (PUID) für Ereignisse aufgefüllt, die von Benutzern in SharePoint, OneDrive for Business und Exchange durchgeführt werden. Diese Eigenschaft kann auch denselben Wert wie die UserID-Eigenschaft für Ereignisse angeben, die in anderen Diensten auftreten, und Ereignisse, die von Systemkonten ausgeführt werden. Obligatorisch: Ja |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Der Benutzertyp, der den Vorgang ausgeführt hat. Obligatorisch: Ja |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Der Office 365-Dienst, bei dem die Aktivität in der Workload-Zeichenfolge aufgetreten ist. Die möglichen Werte für diese Eigenschaft sind: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obligatorisch: No |

### Siehe auch

* class [Content](../content)
* namensraum [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
