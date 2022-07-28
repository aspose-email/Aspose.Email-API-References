---
title: Record
second_title: Aspose.Email för .NET API-referens
description: Granskningsloggpost
type: docs
weight: 2720
url: /sv/net/aspose.email.clients.activity/record/
---
## Record class

Granskningsloggpost

```csharp
public class Record
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Record](record)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AzureActiveDirectoryEventType](../../aspose.email.clients.activity/record/azureactivedirectoryeventtype) { get; set; } | Hämtar eller ställer in typ av Azure AD-händelse. Obligatoriskt: Yes |
| [Client](../../aspose.email.clients.activity/record/client) { get; set; } | Hämtar eller ställer in detaljer om klientenheten, enhetens OS och enhetswebbläsaren som användes för kontoinloggningshändelsen. Obligatorisk: No |
| [ClientIP](../../aspose.email.clients.activity/record/clientip) { get; set; } | Hämtar eller ställer in IP-adressen för enheten som användes när aktiviteten loggades. IP-adressen visas i antingen ett IPv4- eller IPv6-adressformat. Obligatoriskt: Ja |
| [CreationTime](../../aspose.email.clients.activity/record/creationtime) { get; set; } | Hämtar eller ställer in datum och tid i Coordinated Universal Time (UTC) när användaren utförde aktiviteten. Obligatorisk: Yes |
| [ExtendedProperties](../../aspose.email.clients.activity/record/extendedproperties) { get; set; } | Hämtar eller ställer in en lista över utökade egenskaper för inställningen som ändras. Varje egenskap kommer att ha ett namn och ett värde. Obligatorisk: No |
| [Id](../../aspose.email.clients.activity/record/id) { get; set; } | Hämtar eller ställer in unik identifierare för en revisionspost. Obligatorisk: Ja |
| [LoginStatus](../../aspose.email.clients.activity/record/loginstatus) { get; set; } | Hämtar eller ställer in inloggningsstatus Obligatorisk: Yes |
| [ObjectId](../../aspose.email.clients.activity/record/objectid) { get; set; } | Hämtar eller ställer in objektidentifierare. För SharePoint- och OneDrive for Business-aktivitet, det fullständiga sökvägsnamnet för filen eller mappen som användaren kommer åt. För Exchange-administratörsrevisionsloggning, namnet på objektet som ändrades av cmdleten. Obligatoriskt: No |
| [Operation](../../aspose.email.clients.activity/record/operation) { get; set; } | Hämtar eller ställer in namnet på användaren eller administratörsaktiviteten. För en beskrivning av de vanligaste operationerna/aktiviteterna, se Sök i granskningsloggen i Office 365 Protection Center. För Exchange-administratörsaktivitet identifierar den här egenskapen namnet på den cmdlet som kördes. För Dlp-händelser kan detta vara "DlpRuleMatch", "DlpRuleUndo" eller "DlpInfo", som beskrivs under "DLP-schema" nedan. Obligatoriskt: Yes |
| [OrganizationId](../../aspose.email.clients.activity/record/organizationid) { get; set; } | Hämtar eller ställer in GUID för din organisations Office 365-klient. Detta värde kommer alltid att vara detsamma för din organisation, oavsett i vilken Office 365-tjänst det förekommer. Obligatoriskt: Yes |
| [RecordType](../../aspose.email.clients.activity/record/recordtype) { get; set; } | Hämtar eller ställer in typ av operation som indikeras av posten. Obligatorisk: Ja |
| [ResultStatus](../../aspose.email.clients.activity/record/resultstatus) { get; set; } | Hämtar eller ställer in ett värde som indikerar om åtgärden (anges i egenskapen Operation) lyckades eller inte. Obligatorisk: Nej |
| [UserDomain](../../aspose.email.clients.activity/record/userdomain) { get; set; } | Hämtar eller ställer in Tenant Identity Information (TII). Obligatorisk: Yes |
| [UserId](../../aspose.email.clients.activity/record/userid) { get; set; } | Hämtar eller ställer in UPN (User Principal Name) för användaren som utförde åtgärden (specificerad i Operation-egenskapen) som resulterade i att posten loggas; till exempel mitt_namn@mitt_domännamn. Observera att poster för aktivitet utförd av systemkonton (som SHAREPOINT\system eller NT AUTHORITY\SYSTEM) också ingår. Obligatorisk: Yes |
| [UserKey](../../aspose.email.clients.activity/record/userkey) { get; set; } | Hämtar eller ställer in ett alternativt ID för användaren som identifieras i UserId-egenskapen. Till exempel är den här egenskapen fylld med det unika pass-ID (PUID) för händelser som utförs av användare i SharePoint, OneDrive for Business och Exchange. Den här egenskapen kan också ange samma värde som UserID-egenskapen för händelser som inträffar i andra tjänster och händelser som utförs av systemkonton. Obligatorisk: Yes |
| [UserType](../../aspose.email.clients.activity/record/usertype) { get; set; } | Hämtar eller ställer in typ av användare som utförde operationen. Obligatorisk: Ja |
| [Workload](../../aspose.email.clients.activity/record/workload) { get; set; } | Hämtar eller ställer in Office 365-tjänsten där aktiviteten inträffade. Obligatorisk: Nej |

### Se även

* namnutrymme [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
