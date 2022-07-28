---
title: Record
second_title: Aspose.Email für .NET-API-Referenz
description: Prüfprotokolldatensatz
type: docs
weight: 2720
url: /de/net/aspose.email.clients.activity/record/
---
## Record class

Prüfprotokolldatensatz

```csharp
public class Record
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Record](record)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AzureActiveDirectoryEventType](../../aspose.email.clients.activity/record/azureactivedirectoryeventtype) { get; set; } | Ruft den Typ des Azure AD-Ereignisses ab oder legt ihn fest. Obligatorisch: Ja |
| [Client](../../aspose.email.clients.activity/record/client) { get; set; } | Ruft Details über das Clientgerät, das Gerätebetriebssystem und den Gerätebrowser ab oder legt diese fest, die für das Anmeldeereignis des Kontos verwendet wurden. Obligatorisch: Nein |
| [ClientIP](../../aspose.email.clients.activity/record/clientip) { get; set; } | Ruft die IP-Adresse des Geräts ab oder legt sie fest, das verwendet wurde, als die Aktivität protokolliert wurde. Die IP-Adresse wird entweder im IPv4- oder im IPv6-Adressformat angezeigt. Obligatorisch: Ja |
| [CreationTime](../../aspose.email.clients.activity/record/creationtime) { get; set; } | Ruft Datum und Uhrzeit in koordinierter Weltzeit (UTC) ab oder legt sie fest, wann der Benutzer die Aktivität durchgeführt hat. Obligatorisch: Ja |
| [ExtendedProperties](../../aspose.email.clients.activity/record/extendedproperties) { get; set; } | Ruft eine Liste mit erweiterten Eigenschaften für die zu ändernde Einstellung ab oder legt sie fest. Jede Eigenschaft hat einen Namen und einen Wert. Obligatorisch: Nein |
| [Id](../../aspose.email.clients.activity/record/id) { get; set; } | Ruft die eindeutige Kennung eines Audit-Datensatzes ab oder legt sie fest. Obligatorisch: Ja |
| [LoginStatus](../../aspose.email.clients.activity/record/loginstatus) { get; set; } | Ruft den Anmeldestatus ab oder setzt ihn Obligatorisch: Ja |
| [ObjectId](../../aspose.email.clients.activity/record/objectid) { get; set; } | Ruft die Objektkennung ab oder legt sie fest. Für SharePoint- und OneDrive for Business-Aktivitäten der vollständige Pfadname der Datei oder des Ordners, auf die der Benutzer zugreift. Für die Exchange-Administratorüberwachungsprotokollierung der Name des Objekts, das durch das Cmdlet geändert wurde. Obligatorisch: Nein |
| [Operation](../../aspose.email.clients.activity/record/operation) { get; set; } | Ruft den Namen der Benutzer- oder Administratoraktivität ab oder legt ihn fest. Eine Beschreibung der häufigsten Vorgänge/Aktivitäten finden Sie unter Durchsuchen des Überwachungsprotokolls im Office 365 Protection Center. Bei Exchange-Administratoraktivitäten gibt diese Eigenschaft den Namen des ausgeführten Cmdlets an. Für Dlp-Ereignisse kann dies „DlpRuleMatch“, „DlpRuleUndo“ oder „DlpInfo“ sein, die unten unter „DLP-Schema“ beschrieben werden. Obligatorisch: Ja |
| [OrganizationId](../../aspose.email.clients.activity/record/organizationid) { get; set; } | Ruft die GUID für den Office 365-Mandanten Ihrer Organisation ab oder legt sie fest. Dieser Wert ist für Ihre Organisation immer gleich, unabhängig vom Office 365-Dienst, in dem er vorkommt. Obligatorisch: Ja |
| [RecordType](../../aspose.email.clients.activity/record/recordtype) { get; set; } | Ruft den vom Datensatz angegebenen Operationstyp ab oder legt ihn fest. Obligatorisch: Ja |
| [ResultStatus](../../aspose.email.clients.activity/record/resultstatus) { get; set; } | Ruft einen Wert ab oder legt diesen fest, der angibt, ob die Aktion (angegeben in der Eigenschaft Operation) erfolgreich war oder nicht. Obligatorisch: Nein |
| [UserDomain](../../aspose.email.clients.activity/record/userdomain) { get; set; } | Ruft Mandantenidentitätsinformationen (TII) ab oder legt sie fest. Obligatorisch: Ja |
| [UserId](../../aspose.email.clients.activity/record/userid) { get; set; } | Ruft den UPN (User Principal Name) des Benutzers ab oder legt ihn fest, der die Aktion (angegeben in der Operation-Eigenschaft) ausgeführt hat, die zur Protokollierung des Datensatzes geführt hat; zum Beispiel mein_name@mein_domänenname. Beachten Sie, dass Datensätze für Aktivitäten, die von Systemkonten (wie SHAREPOINT\system oder NT AUTHORITY\SYSTEM) ausgeführt werden, ebenfalls enthalten sind. Obligatorisch: Ja |
| [UserKey](../../aspose.email.clients.activity/record/userkey) { get; set; } | Ruft eine alternative ID für den in der UserId-Eigenschaft identifizierten Benutzer ab oder legt diese fest. Beispielsweise wird diese Eigenschaft mit der eindeutigen Passport-ID (PUID) für Ereignisse aufgefüllt, die von Benutzern in SharePoint, OneDrive for Business und Exchange durchgeführt werden. Diese Eigenschaft kann auch denselben Wert wie die UserID-Eigenschaft für Ereignisse angeben, die in anderen Diensten auftreten, und Ereignisse, die von Systemkonten ausgeführt werden. Obligatorisch: Ja |
| [UserType](../../aspose.email.clients.activity/record/usertype) { get; set; } | Ruft den Typ des Benutzers ab oder legt ihn fest, der die Operation ausgeführt hat. Obligatorisch: Ja |
| [Workload](../../aspose.email.clients.activity/record/workload) { get; set; } | Ruft den Office 365-Dienst ab oder legt ihn fest, in dem die Aktivität aufgetreten ist. Obligatorisch: Nein |

### Siehe auch

* namensraum [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
