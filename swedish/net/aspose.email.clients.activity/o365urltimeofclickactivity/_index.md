---
title: O365URLTimeOfClickActivity
second_title: Aspose.Email för .NET API-referens
description: Utökar det gemensamma schemat med egenskaperna som är specifika för Office 365 Advanced Threat Protection och Threat Intelligence-data. Office 365 Advanced Threat Protection ATP och Threat Intelligence-händelser är tillgängliga för Office 365-kunder som har en ATP- Threat Intelligence- eller E5-prenumeration . Varje händelse i ATP- och Threat Intelligence-flödet motsvarar de webbadresser som en användare i organisationen klickade på och som upptäcktes som skadliga vid tidpunkten för klick baserat på Office 365 ATP Safe Links-skydd.
type: docs
weight: 2670
url: /sv/net/aspose.email.clients.activity/o365urltimeofclickactivity/
---
## O365URLTimeOfClickActivity class

Utökar det gemensamma schemat med egenskaperna som är specifika för Office 365 Advanced Threat Protection och Threat Intelligence-data. Office 365 Advanced Threat Protection (ATP) och Threat Intelligence-händelser är tillgängliga för Office 365-kunder som har en ATP-, Threat Intelligence- eller E5-prenumeration . Varje händelse i ATP- och Threat Intelligence-flödet motsvarar de webbadresser som en användare i organisationen klickade på och som upptäcktes som skadliga vid tidpunkten för klick baserat på Office 365 ATP Safe Links-skydd.

```csharp
public class O365URLTimeOfClickActivity : Content
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [O365URLTimeOfClickActivity](o365urltimeofclickactivity)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AppName](../../aspose.email.clients.activity/o365urltimeofclickactivity/appname) { get; set; } | Office 365-tjänst som webbadressen klickades från (t.ex. Mail). Obligatorisk: Ja |
| [Blocked](../../aspose.email.clients.activity/o365urltimeofclickactivity/blocked) { get; set; } | Detta är sant om URL-klicket blockeras av Office 365 ATP Safe Links-skydd. Obligatorisk: Yes |
| [ClickedThrough](../../aspose.email.clients.activity/o365urltimeofclickactivity/clickedthrough) { get; set; } | Detta är sant om URL-blocket klickas igenom (åtsidosätts) av användaren baserat på organisationens policyer för Office 365 ATP Safe Links-skydd. Obligatorisk: Ja |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | IP-adressen för enheten som användes när aktiviteten loggades. IP-adressen visas i antingen ett IPv4- eller IPv6-adressformat. Obligatoriskt: Ja |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | Datum och tid i Coordinated Universal Time (UTC) när användaren utförde aktiviteten. Obligatorisk: Yes |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Unik identifierare för en revisionspost. Obligatorisk: Yes |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | För SharePoint- och OneDrive for Business-aktivitet, det fullständiga sökvägsnamnet för filen eller mappen som användaren kommer åt. För Exchange-administratörsrevisionsloggning, namnet på objektet som ändrades av cmdleten. Obligatoriskt: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Namnet på användaren eller administratörsaktiviteten. För en beskrivning av de vanligaste operationerna/aktiviteterna, se Sök i granskningsloggen i Office 365 Protection Center. För Exchange-administratörsaktivitet identifierar den här egenskapen namnet på den cmdlet som kördes. För Dlp-händelser kan detta vara "DlpRuleMatch", "DlpRuleUndo" eller "DlpInfo", som beskrivs under "DLP-schema" nedan. Obligatoriskt: Yes |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | GUID för din organisations Office 365-klient. Detta värde kommer alltid att vara detsamma för din organisation, oavsett i vilken Office 365-tjänst det förekommer. Obligatoriskt: Yes |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Den typ av operation som anges av posten. Obligatorisk: Ja |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indikerar om åtgärden (anges i egenskapen Operation) lyckades eller inte. Möjliga värden är Succeeded, Partially Succeded eller Failed. För Exchange-administratörsaktivitet är värdet antingen True eller False. Obligatoriskt: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Skapades den här händelsen av en värd O365-tjänst eller en lokal server? Möjliga värden är online och onprem. Observera att SharePoint är den enda arbetsbelastningen som för närvarande skickar händelser från lokalt till O365. Obligatoriskt: No |
| [SourceId](../../aspose.email.clients.activity/o365urltimeofclickactivity/sourceid) { get; set; } | Identifierare för Office 365-tjänsten från vilken webbadressen klickades (t.ex. för Mail, detta är Exchange Online Network Message Id). Obligatorisk: Yes |
| [TimeOfClick](../../aspose.email.clients.activity/o365urltimeofclickactivity/timeofclick) { get; set; } | Datum och tid i Coordinated Universal Time (UTC) när användaren klickade på webbadressen. Obligatorisk: Yes |
| [URL](../../aspose.email.clients.activity/o365urltimeofclickactivity/url) { get; set; } | URL klickad av användaren. Obligatorisk: Ja |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | UPN (User Principal Name) för användaren som utförde åtgärden (specificerad i Operation-egenskapen) som resulterade i att posten loggades; till exempel mitt_namn@mitt_domännamn. Observera att poster för aktivitet utförd av systemkonton (som SHAREPOINT\system eller NT AUTHORITY\SYSTEM) också ingår. Obligatorisk: Yes |
| [UserIp](../../aspose.email.clients.activity/o365urltimeofclickactivity/userip) { get; set; } | IP-adressen för användaren som klickade på URL:en. IP-adressen visas i antingen ett IPv4- eller IPv6-adressformat. Obligatoriskt: Ja |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Ett alternativt ID för användaren som identifieras i UserId-egenskapen. Till exempel är den här egenskapen fylld med det unika pass-ID (PUID) för händelser som utförs av användare i SharePoint, OneDrive for Business och Exchange. Den här egenskapen kan också ange samma värde som UserID-egenskapen för händelser som inträffar i andra tjänster och händelser som utförs av systemkonton. Obligatorisk: Yes |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Typen av användare som utförde åtgärden. Obligatorisk: Ja |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Office 365-tjänsten där aktiviteten inträffade i arbetsbelastningssträngen. De möjliga värdena för den här egenskapen är: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obligatorisk: Nej_ |

### Se även

* class [Content](../content)
* namnutrymme [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
