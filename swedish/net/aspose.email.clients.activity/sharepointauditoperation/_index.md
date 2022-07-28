---
title: SharePointAuditOperation
second_title: Aspose.Email för .NET API-referens
description: SharePoint granskningsåtgärder
type: docs
weight: 2760
url: /sv/net/aspose.email.clients.activity/sharepointauditoperation/
---
## SharePointAuditOperation enumeration

SharePoint granskningsåtgärder

```csharp
public enum SharePointAuditOperation
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| AccessInvitationAccepted | `0` | Denna operation är i förhandsgranskning. Mottagaren av en inbjudan att visa eller redigera en delad fil (eller mapp) har kommit åt den delade filen genom att klicka på länken i inbjudan. |
| AccessInvitationCreated | `1` | Denna operation är i förhandsgranskning. Användaren skickar en inbjudan till en annan person (inom eller utanför sin organisation) för att visa eller redigera en delad fil eller mapp på en SharePoint- eller OneDrive for Business-webbplats. Detaljerna för händelseposten identifierar namnet på filen som delades, användaren som inbjudan skickades till, och typen av delningsbehörighet som valts av personen som skickade inbjudan. |
| AccessInvitationExpired | `2` | Denna operation är i förhandsgranskning. En inbjudan som skickats till en extern användare löper ut. Som standard upphör en inbjudan som skickas till en användare utanför din organisation efter 7 dagar om inbjudan inte accepteras. |
| AccessInvitationRevoked | `3` | Denna operation är i förhandsgranskning. Webbplatsadministratören eller ägaren av en webbplats eller ett dokument i SharePoint eller OneDrive for Business drar tillbaka en inbjudan som skickats till en användare utanför din organisation. En inbjudan kan endast dras tillbaka innan den har accepterats. |
| AccessInvitationUpdated | `4` | Denna operation är i förhandsgranskning. Användaren som skapade och skickade en inbjudan till en annan person att visa eller redigera en delad fil (eller mapp) på en SharePoint- eller OneDrive for Business-webbplats skickar inbjudan igen. |
| AccessRequestApproved | `5` | Webbplatsadministratören eller ägaren av en webbplats eller ett dokument i SharePoint eller OneDrive for Business godkänner en användarbegäran om att få åtkomst till webbplatsen eller dokumentet. |
| AccessRequestCreated | `6` | Användare begär åtkomst till en webbplats eller ett dokument i SharePoint eller OneDrive for Business som de inte har behörighet att få åtkomst till. |
| AccessRequestRejected | `7` | Denna operation är i förhandsgranskning. Webbplatsadministratören eller ägaren av en webbplats eller ett dokument i SharePoint avslår en användarbegäran om att få åtkomst till webbplatsen eller dokumentet. |
| ActivationEnabled | `8` | Denna operation är i förhandsgranskning. Användare kan webbläsaraktivera formulärmallar som inte innehåller formulärkod, kräver fullt förtroende, aktivera rendering på en mobil enhet eller använda en dataanslutning som hanteras av en serveradministratör. |
| AdministratorAddedToTermStore | `9` | Denna operation är i förhandsgranskning. Term store administratör tillagd. |
| AdministratorDeletedFromTermStore | `10` | Denna operation är i förhandsgranskning. Term store administratör borttagen. |
| AllowGroupCreationSet | `11` | Denna operation är i förhandsgranskning. Webbplatsadministratör eller ägare lägger till en behörighetsnivå till en SharePoint- eller OneDrive for Business-webbplats som tillåter en användare som tilldelats den behörigheten att skapa en grupp för den webbplatsen. |
| AppCatalogCreated | `12` | Denna operation är i förhandsgranskning. Appkatalog skapad för att göra anpassade företagsappar tillgängliga för din SharePoint-miljö. |
| AuditPolicyRemoved | `13` | Denna operation är i förhandsgranskning. Document LifeCycle Policy har tagits bort för en webbplatssamling. |
| AuditPolicyUpdate | `14` | Denna operation är i förhandsgranskning. Document LifeCycle Policy har uppdaterats för en webbplatssamling. |
| AzureStreamingEnabledSet | `15` | Denna operation är i förhandsgranskning. En videoportalägare har tillåtit videoströmning från Azure. |
| CollaborationTypeModified | `16` | Denna operation är i förhandsgranskning. Typen av samarbete som tillåts på webbplatser (till exempel intranät, extranät eller offentligt) har ändrats. |
| ConnectedSiteSettingModified | `17` | Användaren har antingen skapat, ändrat eller tagit bort länken mellan ett projekt och en projektwebbplats eller så ändrar användaren synkroniseringsinställningen på länken i Project Web App. |
| CreateSSOApplication | `18` | Denna operation är i förhandsgranskning. Målapplikation skapad i Secure Store-tjänsten. |
| CustomFieldOrLookupTableCreated | `19` | Användaren skapade en anpassad vän eller uppslagstabell/objekt i Project Web App. |
| CustomFieldOrLookupTableDeleted | `20` | Användaren tog bort ett anpassat fält eller uppslagstabell/objekt i Project Web App. |
| CustomFieldOrLookupTableModified | `21` | Användaren ändrade ett anpassat fält eller uppslagstabell/objekt i Project Web App. |
| CustomizeExemptUsers | `22` | Denna operation är i förhandsgranskning. Global administratör anpassade listan över undantagna användaragenter i SharePoints administratörscenter. Du kan ange vilka användaragenter som ska undantas från att ta emot en hel webbsida att indexera. Detta innebär att när en användaragent som du har angett som undantagen stöter på ett InfoPath-formulär, kommer formuläret att returneras som en XML-fil istället för en hel webbsida. Detta gör indexering av InfoPath-formulär snabbare. |
| DefaultLanguageChangedInTermStore | `23` | Denna operation är i förhandsgranskning. Språkinställningen har ändrats i terminologiarkivet. |
| DelegateModified | `24` | Användaren skapade eller ändrade en säkerhetsombud i Project Web App. |
| DelegateRemoved | `25` | Användaren tog bort en säkerhetsombud i Project Web App. |
| DeleteSSOApplication | `26` | Denna operation är i förhandsgranskning. En SSO-applikation togs bort. |
| eDiscoveryHoldApplied | `27` | Denna operation är i förhandsgranskning. Ett In-Place Hold placerades på en innehållskälla. Spärrar på plats hanteras genom att använda en eDiscovery-webbplatssamling (som eDiscovery Center) i SharePoint. |
| eDiscoveryHoldRemoved | `28` | Denna operation är i förhandsgranskning. En In-Place Hold togs bort från en innehållskälla. Spärrar på plats hanteras genom att använda en eDiscovery-webbplatssamling (som eDiscovery Center) i SharePoint. |
| eDiscoverySearchPerformed | `29` | Denna operation är i förhandsgranskning. En eDiscovery-sökning utfördes med en eDiscovery-webbplatssamling i SharePoint. |
| EngagementAccepted | `30` | Användaren accepterar ett resursengagemang i Project Web App. |
| EngagementModified | `31` | Användaren ändrar ett resursengagemang i Project Web App. |
| EngagementRejected | `32` | Användaren avvisar ett resursengagemang i Project Web App. |
| EnterpriseCalendarModified | `33` | Användaren kopierar, ändrar eller tar bort en företagskalender i Project Web App. |
| EntityDeleted | `34` | Användaren tar bort en tidrapport i Project Web App. |
| EntityForceCheckedIn | `35` | Användaren tvingar in en incheckning på en kalender, ett anpassat fält eller en uppslagstabell i Project Web App. |
| ExemptUserAgentSet | `36` | Denna operation är i förhandsgranskning. Global administratör lägger till en användaragent i listan över undantagna användaragenter i SharePoints administratörscenter. |
| FileAccessed | `37` | Användar- eller systemkonto får åtkomst till en fil på en SharePoint- eller OneDrive for Business-webbplats. Systemkonton kan också generera FileAccessed-händelser. |
| FileCheckOutDiscarded | `38` | Denna operation är i förhandsgranskning. Användaren kastar (eller ångrar) en utcheckad fil. Det betyder att alla ändringar de gjorde i filen när den checkades ut kasseras och inte sparas i versionen av dokumentet i dokumentbiblioteket. |
| FileCheckedIn | `39` | Denna operation är i förhandsgranskning. Användaren checkar in ett dokument som de har checkat ut från ett SharePoint- eller OneDrive for Business-dokumentbibliotek. |
| FileCheckedOut | `40` | Denna operation är i förhandsgranskning. Användaren checkar ut ett dokument som finns i ett SharePoint- eller OneDrive for Business-dokumentbibliotek. Användare kan checka ut och göra ändringar i dokument som har delats med dem. |
| FileCopied | `41` | Användaren kopierar ett dokument från en SharePoint- eller OneDrive for Business-webbplats. Den kopierade filen kan sparas i en annan mapp på webbplatsen. |
| FileDeleted | `42` | Användaren tar bort ett dokument från en SharePoint- eller OneDrive for Business-webbplats. |
| FileDeletedFirstStageRecycleBin | `43` | Användaren tar bort en fil från papperskorgen på en SharePoint- eller OneDrive for Business-webbplats. |
| FileDeletedSecondStageRecycleBin | `44` | Användaren tar bort en fil från papperskorgen i andra steget på en SharePoint- eller OneDrive for Business-webbplats. |
| FileDownloaded | `45` | Användaren laddar ner ett dokument från en SharePoint- eller OneDrive for Business-webbplats. |
| FileFetched | `46` | Den här händelsen har ersatts av händelsen FileAccessed och har föråldrats. |
| FileModified | `47` | Användar- eller systemkonto ändrar innehållet eller egenskaperna för ett dokument som finns på en SharePoint- eller OneDrive for Business-webbplats. |
| FileMoved | `48` | Användaren flyttar ett dokument från sin nuvarande plats på en SharePoint- eller OneDrive for Business-webbplats till en ny plats. |
| FilePreviewed | `49` | Användaren förhandsgranskar ett dokument på en SharePoint- eller OneDrive for Business-webbplats. |
| FileRenamed | `50` | Användaren byter namn på ett dokument på en SharePoint- eller OneDrive for Business-webbplats. |
| FileRestored | `51` | Användaren återställer ett dokument från papperskorgen på en SharePoint- eller OneDrive for Business-webbplats. |
| FileSyncDownloadedFull | `52` | Användaren upprättar en synkroniseringsrelation och laddar ned filer för första gången till sin dator från ett SharePoint- eller OneDrive for Business-dokumentbibliotek. |
| FileSyncDownloadedPartial | `53` | Användaren laddar ned alla ändringar av filer från SharePoint eller OneDrive för företags dokumentbibliotek. Den här händelsen indikerar att alla ändringar som gjordes i filer i dokumentbiblioteket laddades ner till användarens dator. Endast ändringar laddades ner eftersom dokumentbiblioteket tidigare laddats ned av användaren (som indikeras av FileSyncDownloadedFull-händelsen). |
| FileSyncUploadedFull | `54` | Denna operation är i förhandsgranskning. Användaren upprättar en synkroniseringsrelation och laddar upp filer för första gången från sin dator till ett SharePoint- eller OneDrive for Business-dokumentbibliotek. |
| FileSyncUploadedPartial | `55` | Denna operation är i förhandsgranskning. Användaren laddar upp ändringar till filer på ett SharePoint- eller OneDrive for Business-dokumentbibliotek. Den här händelsen indikerar att alla ändringar som görs i den lokala versionen av en fil från ett dokumentbibliotek har laddats upp till dokumentbiblioteket. Endast ändringar laddas bort eftersom dessa filer tidigare laddats upp av användaren (vilket indikeras av FileSyncUploadedFull-händelsen). |
| FileUploaded | `56` | Användaren laddar upp ett dokument till en mapp på en SharePoint- eller OneDrive for Business-webbplats. |
| FileViewed | `57` | Den här händelsen har ersatts av händelsen FileAccessed och har föråldrats. |
| FolderCopied | `58` | Användaren kopierar en mapp från en SharePoint- eller OneDrive for Business-webbplats till en annan plats i SharePoint eller OneDrive for Business. |
| FolderCreated | `59` | Användaren skapar en mapp på en SharePoint- eller OneDrive for Business-webbplats. |
| FolderDeleted | `60` | Användaren tar bort en mapp från en SharePoint- eller OneDrive for Business-webbplats. |
| FolderDeletedFirstStageRecycleBin | `61` | Användaren tar bort en mapp från papperskorgen på en SharePoint- eller OneDrive for Business-webbplats . |
| FolderDeletedSecondStageRecycleBin | `62` | Användaren tar bort en mapp från papperskorgen i andra steget på en SharePoint- eller OneDrive for Business-webbplats. |
| FolderModified | `63` | Användaren ändrar en mapp på en SharePoint- eller OneDrive for Business-webbplats. Den här händelsen inkluderar ändringar av mappmetadata, såsom taggar och egenskaper. |
| FolderMoved | `64` | Användaren flyttar en mapp från en SharePoint- eller OneDrive for Business-webbplats. |
| FolderRenamed | `65` | Användaren byter namn på en mapp på en SharePoint- eller OneDrive for Business-webbplats. |
| FolderRestored | `66` | Användaren återställer en mapp från papperskorgen på en SharePoint- eller OneDrive for Business-webbplats. |
| GroupAdded | `67` | Denna operation är i förhandsgranskning. Webbplatsadministratör eller ägare skapar en grupp för en SharePoint- eller OneDrive for Business-webbplats, eller utför en uppgift som resulterar i att en grupp skapas. Till exempel, första gången en användare skapar en länk för att dela en fil, läggs en systemgrupp till på användarens OneDrive for Business-webbplats. Den här händelsen kan också vara ett resultat av att en användare skapar en länk med redigeringsbehörighet till en delad fil. |
| GroupRemoved | `68` | Denna operation är i förhandsgranskning. Användaren tar bort en grupp från en SharePoint- eller OneDrive for Business-webbplats. |
| GroupUpdated | `69` | Denna operation är i förhandsgranskning. Webbplatsadministratör eller ägare ändrar inställningarna för en grupp för en SharePoint- eller OneDrive for Business-webbplats. Detta kan innefatta att ändra gruppens namn, vem som kan se eller redigera gruppmedlemskapet och hur medlemsförfrågningar hanteras. |
| LanguageAddedToTermStore | `70` | Denna operation är i förhandsgranskning. Språket har lagts till i terminologiarkivet. |
| LanguageRemovedFromTermStore | `71` | Denna operation är i förhandsgranskning. Språket har tagits bort från terminologiarkivet. |
| LegacyWorkflowEnabledSet | `72` | Denna operation är i förhandsgranskning. Webbplatsadministratör eller ägare lägger till innehållstypen SharePoint Workflow Task på webbplatsen. Globala administratörer kan också aktivera arbetsflöden för hela organisationen i SharePoints admincenter. |
| LookAndFeelModified | `73` | Användaren ändrar en snabbstart, Gantt-diagramformat eller gruppformat. Eller användaren skapar, ändrar eller tar bort en vy i Project Web App. |
| ManagedSyncClientAllowed | `74` | Användaren har framgångsrikt upprättat en synkroniseringsrelation med en SharePoint- eller OneDrive for Business-webbplats. Synkroniseringsrelationen lyckades eftersom användarens dator är medlem i en domän som har lagts till i listan över domäner (kallad listan över säkra mottagare) som har åtkomst till dokumentbibliotek i din organisation. För mer information om den här funktionen, se Använd Windows PowerShell-cmdlets för att aktivera OneDrive-synkronisering för domäner som finns på listan över säkra mottagare. |
| MaxQuotaModified | `75` | Denna operation är i förhandsgranskning. Den maximala kvoten för en webbplats har ändrats. |
| MaxResourceUsageModified | `76` | Denna operation är i förhandsgranskning. Den maximala tillåtna resursanvändningen för en webbplats har ändrats. |
| MySitePublicEnabledSet | `77` | Denna operation är i förhandsgranskning. Flaggan som gör det möjligt för användare att ha offentliga MySites har ställts in av SharePoint-administratören. |
| NewsFeedEnabledSet | `78` | Denna operation är i förhandsgranskning. Webbplatsadministratör eller ägare aktiverar RSS-flöden för en SharePoint- eller OneDrive for Business-webbplats. Globala administratörer kan aktivera RSS-flöden för hela organisationen i SharePoints admincenter. |
| ODBNextUXSettings | `79` | Denna operation är i förhandsgranskning. Nytt gränssnitt för OneDrive for Business har aktiverats. |
| OfficeOnDemandSet | `80` | Denna operation är i förhandsgranskning. Webbplatsadministratören aktiverar Office on Demand, vilket låter användare komma åt den senaste versionen av Office-skrivbordsapplikationer. Office on Demand är aktiverat i SharePoints administratörscenter och kräver en Office 365-prenumeration som inkluderar kompletta, installerade Office-program. |
| PageViewed | `81` | Användaren visar en sida på en SharePoint-webbplats eller OneDrive for Business-webbplats. Detta inkluderar inte visning av dokumentbiblioteksfiler från en SharePoint-webbplats eller One Drive for Business-webbplats i en webbläsare. |
| PeopleResultsScopeSet | `82` | Denna operation är i förhandsgranskning. Webbplatsadministratören skapar eller ändrar resultatkällan för People Searches för en SharePoint-webbplats. |
| PermissionSyncSettingModified | `83` | Användaren ändrar synkroniseringsinställningarna för projektbehörighet i Project Web App. |
| PermissionTemplateModified | `84` | Användaren skapar, ändrar eller tar bort en behörighetsmall i Project Web App. |
| PortfolioDataAccessed | `85` | Användaren får åtkomst till portföljinnehåll (drivrutinsbibliotek, drivrutinsprioritering, portföljanalyser) i Project Web App. |
| PortfolioDataModified | `86` | Användaren skapar, ändrar eller tar bort portföljdata (drivrutinsbibliotek, drivrutinsprioritering, portföljanalyser) i Project Web App. |
| PreviewModeEnabledSet | `87` | Denna operation är i förhandsgranskning. Webbplatsadministratören aktiverar dokumentförhandsgranskning för en SharePoint-webbplats. |
| ProjectAccessed | `88` | Användaren kommer åt projektinnehåll i Project Web App. |
| ProjectCheckedIn | `89` | Användaren checkar in ett projekt som de checkat ut från en Project Web App. |
| ProjectCheckedOut | `90` | Användaren checkar ut ett projekt som finns i en Project Web App. Användare kan checka ut och göra ändringar i projekt som de har behörighet att öppna. |
| ProjectCreated | `91` | Användaren skapar ett projekt i Project Web App. |
| ProjectDeleted | `92` | Användaren tar bort ett projekt i Project Web App. |
| ProjectForceCheckedIn | `93` | Användaren tvingar in en incheckning på ett projekt i Project Web App. |
| ProjectModified | `94` | Användaren ändrar ett projekt i Project Web App. |
| ProjectPublished | `95` | Användaren publicerar ett projekt i Project Web App. |
| ProjectWorkflowRestarted | `96` | Användaren startar om ett arbetsflöde i Project Web App. |
| PWASettingsAccessed | `97` | Användaren får åtkomst till Project Web App-inställningar via CSOM. |
| PWASettingsModified | `98` | Användaren ändrar en Project Web App-konfiguration. |
| QueueJobStateModified | `99` | Användaren avbryter eller startar om ett köjobb i Project Web App. |
| QuotaWarningEnabledModified | `100` | Denna operation är i förhandsgranskning. Varning för lagringskvot har ändrats. |
| RenderingEnabled | `101` | Denna operation är i förhandsgranskning. Webbläsaraktiverade formulärmallar kommer att återges av InfoPath-formulärtjänster. |
| ReportingAccessed | `102` | Användaren fick åtkomst till rapporteringsslutpunkten i Project Web App. |
| ReportingSettingModified | `103` | Användaren ändrar rapporteringskonfigurationen i Project Web App. |
| ResourceAccessed | `104` | Användaren får åtkomst till ett företagsresursinnehåll i Project Web App. |
| ResourceCheckedIn | `105` | Användaren checkar in en företagsresurs som de checkat ut från Project Web App. |
| ResourceCheckedOut | `106` | Användaren checkar ut en företagsresurs som finns i Project Web App. |
| ResourceCreated | `107` | Användaren skapar en företagsresurs i Project Web App. |
| ResourceDeleted | `108` | Användaren tar bort en företagsresurs i Project Web App. |
| ResourceForceCheckedIn | `109` | Användaren tvingar in en incheckning av en företagsresurs i Project Web App. |
| ResourceModified | `110` | Användaren ändrar en företagsresurs i Project Web App. |
| ResourcePlanCheckedInOrOut | `111` | Användare checkar in eller ut en resursplan i Project Web App. |
| ResourcePlanModified | `112` | Användaren ändrar en resursplan i Project Web App. |
| ResourcePlanPublished | `113` | Användaren publicerar en resursplan i Project Web App. |
| ResourceRedacted | `114` | Användaren redigerar en företagsresurs och tar bort all personlig information i Project Web App. |
| ResourceWarningEnabledModified | `115` | Denna operation är i förhandsgranskning. Resurskvotsvarning modifierad. |
| SSOGroupCredentialsSet | `116` | Denna operation är i förhandsgranskning. Gruppuppgifter har ställts in i Secure Store-tjänsten. |
| SSOUserCredentialsSet | `117` | Denna operation är i förhandsgranskning. Användaruppgifter har ställts in i Secure Store-tjänsten. |
| SearchCenterUrlSet | `118` | Denna operation är i förhandsgranskning. Webbadress till sökcentret har angetts. |
| SecondaryMySiteOwnerSet | `119` | Denna operation är i förhandsgranskning. En användare har lagt till en sekundär ägare till sin MySite. |
| SecurityCategoryModified | `120` | Användaren skapar, ändrar eller tar bort en säkerhetskategori i Project Web App. |
| SecurityGroupModified | `121` | Användaren skapar, ändrar eller tar bort en säkerhetsgrupp i Project Web App. |
| SendToConnectionAdded | `122` | Denna operation är i förhandsgranskning. Global administratör skapar en ny Skicka till-anslutning på sidan Posthantering i SharePoints administratörscenter. En Skicka till-anslutning anger inställningar för ett dokumentarkiv eller en registercentral. När du skapar en Skicka till-anslutning kan en innehållsorganisatör skicka dokument till den angivna platsen. |
| SendToConnectionRemoved | `123` | Denna operation är i förhandsgranskning. Global administratör tar bort en Skicka till-anslutning på sidan Posthantering i SharePoints administratörscenter. |
| SharedLinkCreated | `124` | Användaren skapar en länk till en delad fil i SharePoint eller OneDrive for Business. Den här länken kan skickas till andra för att ge dem åtkomst till filen. En användare kan skapa två typer av länkar: en länk som gör att en användare kan visa och redigera den delade filen, eller en länk som låter användaren bara se filen. |
| SharedLinkDisabled | `125` | Denna operation är i förhandsgranskning. Användaren inaktiverar (permanent) en länk som skapades för att dela en fil. |
| SharingInvitationAccepted | `126` | Denna operation är i förhandsgranskning. Användaren accepterar en inbjudan att dela en fil eller mapp. Denna händelse loggas när en användare delar en fil med andra användare. |
| SharingRevoked | `127` | Denna operation är i förhandsgranskning. Användaren tar bort delning av en fil eller mapp som tidigare delats med andra användare. Denna händelse loggas när en användare slutar dela en fil med andra användare. |
| SharingSet | `128` | Användare delar en fil eller mapp i SharePoint eller OneDrive for Business med en annan användare inom sin organisation. |
| SiteAdminChangeRequest | `129` | Denna operation är i förhandsgranskning. Användaren begär att få läggas till som webbplatssamlingsadministratör för en SharePoint-webbplatssamling. Webbplatssamlingsadministratörer har full kontrollbehörighet för webbplatssamlingen och alla underwebbplatser. |
| SiteCollectionAdminAdded | `130` | Denna operation är i förhandsgranskning. Webbplatssamlingsadministratör eller ägare lägger till en person som webbplatssamlingsadministratör för en SharePoint- eller OneDrive for Business-webbplats. Webbplatssamlingsadministratörer har full kontrollbehörighet för webbplatssamlingen och alla underwebbplatser. |
| SiteCollectionCreated | `131` | Denna operation är i förhandsgranskning. Global administratör skapar en ny webbplatssamling i din SharePoint-organisation. |
| SiteRenamed | `132` | Denna operation är i förhandsgranskning. Webbplatsadministratör eller ägare byter namn på en SharePoint- eller OneDrive for Business-webbplats |
| StatusReportModified | `133` | Användaren skapar, ändrar eller tar bort en statusrapport i Project Web App. |
| SyncGetChanges | `134` | Denna operation är i förhandsgranskning. Användaren klickar på Synkronisera i åtgärdsfältet i SharePoint eller OneDrive for Business för att synkronisera eventuella ändringar av filen i ett dokumentbibliotek till sin dator. |
| TaskStatusAccessed | `135` | Användaren kommer åt status för en eller flera uppgifter i Project Web App. |
| TaskStatusApproved | `136` | Användaren godkänner en statusuppdatering av en eller flera uppgifter i Project Web App. |
| TaskStatusRejected | `137` | Användaren avvisar en statusuppdatering av en eller flera uppgifter i Project Web App. |
| TaskStatusSaved | `138` | Användaren sparar en statusuppdatering av en eller flera uppgifter i Project Web App. |
| TaskStatusSubmitted | `139` | Användaren skickar en statusuppdatering för en eller flera uppgifter i Project Web App. |
| TimesheetAccessed | `140` | Användaren kommer åt en tidrapport i Project Web App. |
| TimesheetApproved | `141` | Användaren godkänner tidrapport i Project Web App. |
| TimesheetRejected | `142` | Användaren avvisar en tidrapport i Project Web App. |
| TimesheetSaved | `143` | Användaren sparar en tidrapport i Project Web App. |
| TimesheetSubmitted | `144` | Användaren skickar in en statustidrapport i Project Web App. |
| UnmanagedSyncClientBlocked | `145` | Användaren försöker upprätta en synkroniseringsrelation med en SharePoint- eller OneDrive for Business-webbplats från en dator som inte är medlem i din organisations domän eller är medlem i en domän som inte har lagts till i listan över domäner ( kallas listan över säkra mottagare) som kan komma åt dokumentbibliotek i din organisation. Synkroniseringsrelationen är inte tillåten och användarens dator är blockerad från att synkronisera, ladda ner eller ladda upp filer på ett dokumentbibliotek. För information om den här funktionen, se Använd Windows PowerShell-cmdlets för att aktivera OneDrive-synkronisering för domäner som finns på listan över säkra mottagare. |
| UpdateSSOApplication | `146` | Denna operation är i förhandsgranskning. Målapplikation uppdaterad i Secure Store-tjänsten. |
| UserAddedToGroup | `147` | Denna operation är i förhandsgranskning. Webbplatsadministratör eller ägare lägger till en person i en grupp på en SharePoint- eller OneDrive for Business-webbplats. Att lägga till en person i en grupp ger användaren de behörigheter som tilldelats gruppen. |
| UserRemovedFromGroup | `148` | Denna operation är i förhandsgranskning. Webbplatsadministratör eller ägare tar bort en person från en grupp på en SharePoint- eller OneDrive for Business-webbplats. Efter att personen har tagits bort ges de inte längre de behörigheter som tilldelades gruppen. |
| WorkflowModified | `149` | Användaren skapar, ändrar eller tar bort en Enterprise Project Type eller Workflow-faser eller -stadier i Project Web App. |

### Se även

* namnutrymme [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
