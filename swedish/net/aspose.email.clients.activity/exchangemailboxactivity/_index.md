---
title: ExchangeMailboxActivity
second_title: Aspose.Email för .NET API-referens
description: Utökar det gemensamma schemat med egenskaperna specifika för alla granskningsdata för Exchange-postlåde.
type: docs
weight: 2510
url: /sv/net/aspose.email.clients.activity/exchangemailboxactivity/
---
## ExchangeMailboxActivity class

Utökar det gemensamma schemat med egenskaperna specifika för alla granskningsdata för Exchange-postlåde.

```csharp
public class ExchangeMailboxActivity : Content
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ExchangeMailboxActivity](exchangemailboxactivity)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ClientInfoString](../../aspose.email.clients.activity/exchangemailboxactivity/clientinfostring) { get; set; } | Information om e-postklienten som användes för att utföra åtgärden, till exempel en webbläsarversion, Outlook-version och information om mobila enheter. |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | IP-adressen för enheten som användes när aktiviteten loggades. IP-adressen visas i antingen ett IPv4- eller IPv6-adressformat. Obligatoriskt: Ja |
| [ClientIPAddress](../../aspose.email.clients.activity/exchangemailboxactivity/clientipaddress) { get; set; } | IP-adressen för enheten som användes när operationen loggades. IP-adressen visas i antingen ett IPv4- eller IPv6-adressformat. |
| [ClientMachineName](../../aspose.email.clients.activity/exchangemailboxactivity/clientmachinename) { get; set; } | Maskinnamnet som är värd för Outlook-klienten. |
| [ClientProcessName](../../aspose.email.clients.activity/exchangemailboxactivity/clientprocessname) { get; set; } | E-postklienten som användes för att komma åt brevlådan. |
| [ClientVersion](../../aspose.email.clients.activity/exchangemailboxactivity/clientversion) { get; set; } | Versionen av e-postklienten. |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | Datum och tid i Coordinated Universal Time (UTC) när användaren utförde aktiviteten. Obligatorisk: Yes |
| [ExternalAccess](../../aspose.email.clients.activity/exchangemailboxactivity/externalaccess) { get; set; } | Detta gäller om inloggningsanvändarens domän skiljer sig från postlådeägarens domän. |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Unik identifierare för en revisionspost. Obligatorisk: Yes |
| [InternalLogonType](../../aspose.email.clients.activity/exchangemailboxactivity/internallogontype) { get; set; } | Reserverad för internt bruk. |
| [LogonType](../../aspose.email.clients.activity/exchangemailboxactivity/logontype) { get; set; } | Indikerar typen av användare som fick åtkomst till brevlådan och utförde operationen som loggades. |
| [LogonUserDisplayName](../../aspose.email.clients.activity/exchangemailboxactivity/logonuserdisplayname) { get; set; } | Det användarvänliga namnet på användaren som utförde operationen. |
| [LogonUserSid](../../aspose.email.clients.activity/exchangemailboxactivity/logonusersid) { get; set; } | SID för användaren som utförde åtgärden. |
| [MailboxGuid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxguid) { get; set; } | Exchange GUID för postlådan som var åtkomst. |
| [MailboxOwnerMasterAccountSid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownermasteraccountsid) { get; set; } | Postlådeägarkontots huvudkonto SID. |
| [MailboxOwnerSid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownersid) { get; set; } | SID för brevlådeägaren. |
| [MailboxOwnerUPN](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownerupn) { get; set; } | E-postadressen till personen som äger brevlådan som fick åtkomst. |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | För SharePoint- och OneDrive for Business-aktivitet, det fullständiga sökvägsnamnet för filen eller mappen som användaren kommer åt. För Exchange-administratörsrevisionsloggning, namnet på objektet som ändrades av cmdleten. Obligatoriskt: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Namnet på användaren eller administratörsaktiviteten. För en beskrivning av de vanligaste operationerna/aktiviteterna, se Sök i granskningsloggen i Office 365 Protection Center. För Exchange-administratörsaktivitet identifierar den här egenskapen namnet på den cmdlet som kördes. För Dlp-händelser kan detta vara "DlpRuleMatch", "DlpRuleUndo" eller "DlpInfo", som beskrivs under "DLP-schema" nedan. Obligatoriskt: Yes |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | GUID för din organisations Office 365-klient. Detta värde kommer alltid att vara detsamma för din organisation, oavsett i vilken Office 365-tjänst det förekommer. Obligatoriskt: Yes |
| [OrganizationName](../../aspose.email.clients.activity/exchangemailboxactivity/organizationname) { get; set; } | Hyresgästens namn. |
| [OriginatingServer](../../aspose.email.clients.activity/exchangemailboxactivity/originatingserver) { get; set; } | Det här är varifrån operationen kom. |
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
