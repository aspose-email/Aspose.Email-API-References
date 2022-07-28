---
title: ExchangeMailboxAuditGroupActivity
second_title: Aspose.Email för .NET API-referens
description: 
type: docs
weight: 2530
url: /sv/net/aspose.email.clients.activity/exchangemailboxauditgroupactivity/
---
## ExchangeMailboxAuditGroupActivity class

```csharp
public class ExchangeMailboxAuditGroupActivity : Content
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ExchangeMailboxAuditGroupActivity](exchangemailboxauditgroupactivity)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AffectedItems](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/affecteditems) { get; set; } | Information om varje objekt i gruppen. |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | IP-adressen för enheten som användes när aktiviteten loggades. IP-adressen visas i antingen ett IPv4- eller IPv6-adressformat. Obligatoriskt: Ja |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | Datum och tid i Coordinated Universal Time (UTC) när användaren utförde aktiviteten. Obligatorisk: Yes |
| [CrossMailboxOperations](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/crossmailboxoperations) { get; set; } | Indikerar om operationen involverade mer än en brevlåda. |
| [DestFolder](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destfolder) { get; set; } | Målmappen, för operationer som Move. |
| [DestMailboxId](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxid) { get; set; } | Ställ endast in om parametern CrossMailboxOperations är True. Anger målpostlådans GUID. |
| [DestMailboxOwnerMasterAccountSid](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownermasteraccountsid) { get; set; } | Ställ endast in om parametern CrossMailboxOperations är True. Anger SID för huvudkonto-SID för målpostlådeägaren. |
| [DestMailboxOwnerSid](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownersid) { get; set; } | Ställ endast in om parametern CrossMailboxOperations är True. Anger SID för målpostlådan. |
| [DestMailboxOwnerUPN](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownerupn) { get; set; } | Ställ endast in om parametern CrossMailboxOperations är True. Anger UPN för ägaren av målpostlådan. |
| [Folder](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/folder) { get; set; } | Mappen där en grupp objekt finns. |
| [Folders](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/folders) { get; set; } | Information om källmapparna som är involverade i en operation; till exempel om mappar är valda och sedan raderas. |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Unik identifierare för en revisionspost. Obligatorisk: Yes |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | För SharePoint- och OneDrive for Business-aktivitet, det fullständiga sökvägsnamnet för filen eller mappen som användaren kommer åt. För Exchange-administratörsrevisionsloggning, namnet på objektet som ändrades av cmdleten. Obligatoriskt: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Namnet på användaren eller administratörsaktiviteten. För en beskrivning av de vanligaste operationerna/aktiviteterna, se Sök i granskningsloggen i Office 365 Protection Center. För Exchange-administratörsaktivitet identifierar den här egenskapen namnet på den cmdlet som kördes. För Dlp-händelser kan detta vara "DlpRuleMatch", "DlpRuleUndo" eller "DlpInfo", som beskrivs under "DLP-schema" nedan. Obligatoriskt: Yes |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | GUID för din organisations Office 365-klient. Detta värde kommer alltid att vara detsamma för din organisation, oavsett i vilken Office 365-tjänst det förekommer. Obligatoriskt: Yes |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Den typ av operation som anges av posten. Obligatorisk: Ja |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indikerar om åtgärden (anges i egenskapen Operation) lyckades eller inte. Möjliga värden är Succeeded, Partially Succeded eller Failed. För Exchange-administratörsaktivitet är värdet antingen True eller False. Obligatoriskt: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Skapades den här händelsen av en värd O365-tjänst eller en lokal server? Möjliga värden är online och onprem. Observera att SharePoint är den enda arbetsbelastningen som för närvarande skickar händelser från lokalt till O365. Obligatoriskt: No |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | UPN (User Principal Name) för användaren som utförde åtgärden (specificerad i Operation-egenskapen) som resulterade i att posten loggades; till exempel mitt_namn@mitt_domännamn. Observera att poster för aktivitet utförd av systemkonton (som SHAREPOINT\system eller NT AUTHORITY\SYSTEM) också ingår. Obligatorisk: Yes |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Ett alternativt ID för användaren som identifieras i UserId-egenskapen. Till exempel är den här egenskapen fylld med det unika pass-ID (PUID) för händelser som utförs av användare i SharePoint, OneDrive for Business och Exchange. Den här egenskapen kan också ange samma värde som UserID-egenskapen för händelser som inträffar i andra tjänster och händelser som utförs av systemkonton. Obligatorisk: Yes |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Typen av användare som utförde åtgärden. Obligatorisk: Ja |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Office 365-tjänsten där aktiviteten inträffade i arbetsbelastningssträngen. De möjliga värdena för den här egenskapen är: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obligatorisk: Nej_ |

### Se även

* class [Content](../content)
* namnutrymme [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
