---
title: ExchangeMailboxAuditActivity
second_title: Aspose.Email für .NET-API-Referenz
description: 
type: docs
weight: 2520
url: /de/net/aspose.email.clients.activity/exchangemailboxauditactivity/
---
## ExchangeMailboxAuditActivity class

```csharp
public class ExchangeMailboxAuditActivity : Content
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ExchangeMailboxAuditActivity](exchangemailboxauditactivity)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | Die IP-Adresse des Geräts, das verwendet wurde, als die Aktivität protokolliert wurde. Die IP-Adresse wird entweder im IPv4- oder im IPv6-Adressformat angezeigt. Obligatorisch: Ja |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | Das Datum und die Uhrzeit in koordinierter Weltzeit (UTC), wann der Benutzer die Aktivität durchgeführt hat. Obligatorisch: Ja |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Eindeutige Kennung eines Prüfprotokolls. Obligatorisch: Ja |
| [Item](../../aspose.email.clients.activity/exchangemailboxauditactivity/item) { get; set; } | Stellt das Element dar, an dem die Operation durchgeführt wurde |
| [ModifiedProperties](../../aspose.email.clients.activity/exchangemailboxauditactivity/modifiedproperties) { get; set; } | TBD |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Für SharePoint- und OneDrive for Business-Aktivitäten der vollständige Pfadname der Datei oder des Ordners, auf die der Benutzer zugreift. Für die Exchange-Administratorüberwachungsprotokollierung der Name des Objekts, das durch das Cmdlet geändert wurde. Obligatorisch: Nein |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Der Name der Benutzer- oder Administratoraktivität. Eine Beschreibung der häufigsten Vorgänge/Aktivitäten finden Sie unter Durchsuchen des Überwachungsprotokolls im Office 365 Protection Center. Bei Exchange-Administratoraktivitäten gibt diese Eigenschaft den Namen des ausgeführten Cmdlets an. Für Dlp-Ereignisse kann dies „DlpRuleMatch“, „DlpRuleUndo“ oder „DlpInfo“ sein, die unten unter „DLP-Schema“ beschrieben werden. Obligatorisch: Ja |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Die GUID für den Office 365-Mandanten Ihrer Organisation. Dieser Wert ist für Ihre Organisation immer gleich, unabhängig vom Office 365-Dienst, in dem er vorkommt. Obligatorisch: Ja |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Der vom Datensatz angegebene Vorgangstyp. Obligatorisch: Ja |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Gibt an, ob die Aktion (angegeben in der Operation-Eigenschaft) erfolgreich war oder nicht. Mögliche Werte sind Succeeded, PartiallySucceded oder Failed. Für Exchange-Administratoraktivitäten ist der Wert entweder True oder False. Obligatorisch: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Wurde dieses Ereignis von einem gehosteten O365-Dienst oder einem lokalen Server erstellt? Mögliche Werte sind online und onprem. Beachten Sie, dass SharePoint die einzige Workload ist, die derzeit Ereignisse von lokal an Office 365 sendet. Obligatorisch: No |
| [SendAsUserMailboxGuid](../../aspose.email.clients.activity/exchangemailboxauditactivity/sendasusermailboxguid) { get; set; } | Die Exchange-GUID des Postfachs, auf das zugegriffen wurde, um E-Mails zu senden als. |
| [SendAsUserSmtp](../../aspose.email.clients.activity/exchangemailboxauditactivity/sendasusersmtp) { get; set; } | SMTP-Adresse des Benutzers, dessen Identität angenommen wird. |
| [SendonBehalfOfUserMailboxGuid](../../aspose.email.clients.activity/exchangemailboxauditactivity/sendonbehalfofusermailboxguid) { get; set; } | Die Exchange-GUID des Postfachs, auf das zugegriffen wurde, um E-Mails im Auftrag von zu senden. |
| [SendOnBehalfOfUserSmtp](../../aspose.email.clients.activity/exchangemailboxauditactivity/sendonbehalfofusersmtp) { get; set; } | SMTP-Adresse des Benutzers, in dessen Namen die E-Mail gesendet wird. |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | Der UPN (User Principal Name) des Benutzers, der die Aktion (angegeben in der Operation-Eigenschaft) ausgeführt hat, die zur Protokollierung des Datensatzes geführt hat; zum Beispiel mein_name@mein_domänenname. Beachten Sie, dass Datensätze für Aktivitäten, die von Systemkonten (wie SHAREPOINT\system oder NT AUTHORITY\SYSTEM) ausgeführt werden, ebenfalls enthalten sind. Obligatorisch: Ja |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Eine alternative ID für den in der UserId-Eigenschaft identifizierten Benutzer. Beispielsweise wird diese Eigenschaft mit der eindeutigen Passport-ID (PUID) für Ereignisse aufgefüllt, die von Benutzern in SharePoint, OneDrive for Business und Exchange durchgeführt werden. Diese Eigenschaft kann auch denselben Wert wie die UserID-Eigenschaft für Ereignisse angeben, die in anderen Diensten auftreten, und Ereignisse, die von Systemkonten ausgeführt werden. Obligatorisch: Ja |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Der Benutzertyp, der den Vorgang ausgeführt hat. Obligatorisch: Ja |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Der Office 365-Dienst, bei dem die Aktivität in der Workload-Zeichenfolge aufgetreten ist. Die möglichen Werte für diese Eigenschaft sind: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obligatorisch: No |

### Siehe auch

* class [Content](../content)
* namensraum [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
