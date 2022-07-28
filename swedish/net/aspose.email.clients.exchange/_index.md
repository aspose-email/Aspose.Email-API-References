---
title: Aspose.Email.Clients.Exchange
second_title: Aspose.Email för .NET API-referens
description: Den Aspose.Email.Clients.Exchange namnutrymme tillhandahåller klasser för Microsoft Exchange Server-åtkomst.
type: docs
weight: 140
url: /sv/net/aspose.email.clients.exchange/
---
Den **Aspose.Email.Clients.Exchange** namnutrymme tillhandahåller klasser för Microsoft Exchange Server-åtkomst.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AppointmentPageInfo](./appointmentpageinfo) | Innehåller information om hämtad sida när personsökningsmetoder används. |
| [AppointmentQueryBuilder](./appointmentquerybuilder) | Representerar byggaren av sökuttryck som används av Exchange-protokollet. |
| [AutodiscoverRedirectionUrlValidationCallback](./autodiscoverredirectionurlvalidationcallback) | Definierar en delegat som används av AutodiscoverService för att fråga om en omdirigeringsurl kan användas. |
| [AutodiscoverResponse](./autodiscoverresponse) | Representerar basklassen för alla svar som returneras av Autodiscover-tjänsten. |
| [AutodiscoverResponseCollection&lt;TResponse&gt;](./autodiscoverresponsecollection-1) | Representerar en samling svar på ett samtal till Autodiscover-tjänsten. |
| [AutodiscoverService](./autodiscoverservice) | Representerar en bindning till Exchange Autodiscover Service. |
| [AutodiscoverServiceBase](./autodiscoverservicebase) | Representerar en abstrakt bindning till en Autodiscover-tjänst. |
| [ComparisonFieldAdapter](./comparisonfieldadapter) | Implementerar adapter för användning[`ComparisonField`](../aspose.email.tools.search/comparisonfield) enligt deras typ |
| [ContactQueryBuilder](./contactquerybuilder) | Representerar byggaren av sökuttryck som används av Exchange-protokollet. |
| [ExchangeAdvancedSyntaxMailQuery](./exchangeadvancedsyntaxmailquery) | Representerar sökkriterierna som används för att matcha flera meddelandeegenskaper i brevlådan. Implementerar en Advanced Query Syntax (AQS)-sökning som används av EWS. AQS som beskrivs på https://docs.microsoft.com/exchange/ client-developer/exchange-web-services/how-to-perform-an-aqs-search-by-using-ews-in-exchange. |
| [ExchangeAdvancedSyntaxQueryBuilder](./exchangeadvancedsyntaxquerybuilder) | Representerar byggaren av sökuttryck baserat på Advanced Query Syntax (AQS) som används av Exchange-protokollet. AQS är ett alternativ till sökfilter för att uttrycka sökkriterier. |
| [ExchangeAttachmentInfo](./exchangeattachmentinfo) | Representerar en bifogad information som överförs över utbytesprotokoll |
| [ExchangeAttachmentInfoCollection](./exchangeattachmentinfocollection) | Representerar samlingen av[`ExchangeAttachmentInfo`](../aspose.email.clients.exchange/exchangeattachmentinfo) |
| [ExchangeBasePermission](./exchangebasepermission) | Ger abstrakt basklass för behörigheter till mappar på Exchange Server. |
| [ExchangeCalendarPermission](./exchangecalendarpermission) | Representerar en behörighet för en kalendermapp. |
| [ExchangeClientBase](./exchangeclientbase) | Tillhandahåller den abstrakta basklassen till MS Exchange Server-åtkomst. |
| [ExchangeDistributionList](./exchangedistributionlist) | Representerar en distributionslista egenskaper |
| [ExchangeFolderInfo](./exchangefolderinfo) | Ger information om en MS Exchange-mapp. |
| [ExchangeFolderInfoCollection](./exchangefolderinfocollection) | Representerar en samling ExchangeMessageInfo-objekt. |
| [ExchangeFolderPageInfo](./exchangefolderpageinfo) | Innehåller information om hämtad sida när personsökningsmetoder används. |
| [ExchangeFolderPermission](./exchangefolderpermission) | Representerar en behörighet för en mapp. |
| [ExchangeFolderPermissionCollection](./exchangefolderpermissioncollection) | Representerar samlingen av[`ExchangeFolderPermission`](../aspose.email.clients.exchange/exchangefolderpermission) |
| [ExchangeFolderUserInfo](./exchangefolderuserinfo) | Representerar en användare som har mappåtkomstbehörigheter |
| [ExchangeMailboxInfo](./exchangemailboxinfo) | Representerar postlådeinformationen för en utbytesserver. |
| [ExchangeMessageInfo](./exchangemessageinfo) | ExchangeMessageInfo representerar informationen om e-postmeddelandet som hämtats från Exchange Store. |
| [ExchangeMessageInfoCollection](./exchangemessageinfocollection) | Representerar en samling ExchangeMessageInfo-objekt. |
| [ExchangeMessagePageInfo](./exchangemessagepageinfo) | Innehåller information om hämtad sida när personsökningsmetoder används. |
| [ExchangePermissionCollection](./exchangepermissioncollection) | Representerar samlingen av[`ExchangeBasePermission`](../aspose.email.clients.exchange/exchangebasepermission) |
| [ExchangeQueryBuilder](./exchangequerybuilder) | Representerar byggaren av sökuttryck baserat på sökfilter som används av Exchange-protokollet. |
| [ExtendedPropertiesComparisonField](./extendedpropertiescomparisonfield) | Definierar ordbok med par av egenskapsbeskrivningar och jämförelsefält för att söka efter utökade egenskaper |
| [GetUserSettingsResponse](./getusersettingsresponse) | Representerar svaret på ett GetUsersSettings-anrop för en enskild användare. |
| [GetUserSettingsResponseCollection](./getusersettingsresponsecollection) | Representerar en samling svar på GetUserSettings |
| [InboxRule](./inboxrule) | Representerar en inkorgsregel |
| [RuleActions](./ruleactions) | Representerar den uppsättning åtgärder som är tillgängliga för en regel. |
| [RulePredicates](./rulepredicates) | Representerar regelpredikat |
| [SizeRange](./sizerange) | Representerar storleksintervallet |
| [UserSettingError](./usersettingerror) | Representerar ett fel från en GetUserSettings-begäran. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IExchangeClientBase](./iexchangeclientbase) | Representerar gränssnittet för bas Exchange-klienter. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [AutodiscoverErrorCode](./autodiscovererrorcode) | Definierar felkoderna som kan returneras av Autodiscover-tjänsten. |
| [ExchangeCalendarPermissionLevel](./exchangecalendarpermissionlevel) | Anger behörighetsnivån som en användare har för en kalendermapp. |
| [ExchangeCalendarPermissionReadAccess](./exchangecalendarpermissionreadaccess) | Anger om en användare har behörighet att läsa objekt i en mapp. |
| [ExchangeFolderPermissionAction](./exchangefolderpermissionaction) | Definierar vilka objekt i en mapp en användare har behörighet att redigera eller ta bort. |
| [ExchangeFolderPermissionLevel](./exchangefolderpermissionlevel) | Anger behörighetsnivån som en användare har för en mapp. |
| [ExchangeFolderPermissionReadAccess](./exchangefolderpermissionreadaccess) | Anger om en användare har behörighet att läsa objekt i en mapp. |
| [ExchangeFolderType](./exchangefoldertype) | Räknar upp de olika mapptyperna. Dessa värden finns också i egenskapen PidTagContainerClass. |
| [ExchangeFolderUserType](./exchangefolderusertype) | Räknar upp de framstående användarkontona |
| [ExchangeListMessagesOptions](./exchangelistmessagesoptions) | Räknar upp listmeddelanden options |
| [ExchangeMessageFlag](./exchangemessageflag) | Representerar en flagga för meddelande. |
| [FlaggedForAction](./flaggedforaction) | Uppräkningar flaggade för action |
| [ImportanceChoices](./importancechoices) | Räknar upp nivåerna av betydelse för en artikel |
| [MessageInfoType](./messageinfotype) | Räknar upp meddelandetyperna. |
| [RulePredicateFlags](./rulepredicateflags) | Representerar regelpredikatflaggor |
| [SearchItemType](./searchitemtype) | Ger objekttypsvärdena för att begränsa sökresultat till endast en specifik typ av objekt. |
| [SensitivityChoices](./sensitivitychoices) | Räknar upp de känslighetsnivåtyper som är tillgängliga för ett objekt. |
| [UserSettingName](./usersettingname) | Användarinställningar som kan begäras med GetUserSettings. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
