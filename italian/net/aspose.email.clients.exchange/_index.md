---
title: Aspose.Email.Clients.Exchange
second_title: Aspose.Email per riferimento all'API .NET
description: Il Aspose.Email.Client.Exchange namespace fornisce classi per laccesso a Microsoft Exchange Server.
type: docs
weight: 140
url: /it/net/aspose.email.clients.exchange/
---
Il **Aspose.Email.Client.Exchange** namespace fornisce classi per l'accesso a Microsoft Exchange Server.

## Classi

| Classe | Descrizione |
| --- | --- |
| [AppointmentPageInfo](./appointmentpageinfo) | Contiene informazioni sulla pagina recuperata quando vengono utilizzati i metodi di paging. |
| [AppointmentQueryBuilder](./appointmentquerybuilder) | Rappresenta il builder dell'espressione di ricerca utilizzata dal protocollo Exchange. |
| [AutodiscoverRedirectionUrlValidationCallback](./autodiscoverredirectionurlvalidationcallback) | Definisce un delegato utilizzato da AutodiscoverService per chiedere se è possibile utilizzare un redirectionUrl. |
| [AutodiscoverResponse](./autodiscoverresponse) | Rappresenta la classe base per tutte le risposte restituite dal servizio di individuazione automatica. |
| [AutodiscoverResponseCollection&lt;TResponse&gt;](./autodiscoverresponsecollection-1) | Rappresenta una raccolta di risposte a una chiamata al servizio di individuazione automatica. |
| [AutodiscoverService](./autodiscoverservice) | Rappresenta un'associazione al servizio di individuazione automatica di Exchange. |
| [AutodiscoverServiceBase](./autodiscoverservicebase) | Rappresenta un'associazione astratta a un servizio di individuazione automatica. |
| [ComparisonFieldAdapter](./comparisonfieldadapter) | Implementa l'adattatore per l'utilizzo[`ComparisonField`](../aspose.email.tools.search/comparisonfield) secondo il loro tipo |
| [ContactQueryBuilder](./contactquerybuilder) | Rappresenta il generatore di espressioni di ricerca utilizzato dal protocollo Exchange. |
| [ExchangeAdvancedSyntaxMailQuery](./exchangeadvancedsyntaxmailquery) | Rappresenta i criteri di ricerca utilizzati per corrispondere a diverse proprietà dei messaggi nella cassetta postale. Implementa una ricerca AQS (Advanced Query Syntax) utilizzata da EWS. AQS descritta in https://docs.microsoft.com/exchange/ sviluppatore-client/servizi-web-di-exchange/come-eseguire-una-ricerca-aqs-usando-ews-in-exchange. |
| [ExchangeAdvancedSyntaxQueryBuilder](./exchangeadvancedsyntaxquerybuilder) | Rappresenta il generatore di espressioni di ricerca basato su la sintassi di query avanzata (AQS) utilizzata dal protocollo Exchange. AQS è un'alternativa ai filtri di ricerca per esprimere i criteri di ricerca. |
| [ExchangeAttachmentInfo](./exchangeattachmentinfo) | Rappresenta un'informazione di allegato trasmessa tramite protocolli di scambio |
| [ExchangeAttachmentInfoCollection](./exchangeattachmentinfocollection) | Rappresenta la raccolta di[`ExchangeAttachmentInfo`](../aspose.email.clients.exchange/exchangeattachmentinfo) |
| [ExchangeBasePermission](./exchangebasepermission) | Fornisce una classe base astratta per le autorizzazioni alle cartelle su Exchange Server. |
| [ExchangeCalendarPermission](./exchangecalendarpermission) | Rappresenta un'autorizzazione su una cartella del calendario. |
| [ExchangeClientBase](./exchangeclientbase) | Fornisce la classe base astratta per l'accesso a MS Exchange Server. |
| [ExchangeDistributionList](./exchangedistributionlist) | Rappresenta una lista di distribuzione properties |
| [ExchangeFolderInfo](./exchangefolderinfo) | Fornisce informazioni su una cartella MS Exchange. |
| [ExchangeFolderInfoCollection](./exchangefolderinfocollection) | Rappresenta una raccolta di oggetti ExchangeMessageInfo. |
| [ExchangeFolderPageInfo](./exchangefolderpageinfo) | Contiene informazioni sulla pagina recuperata quando vengono utilizzati i metodi di paging. |
| [ExchangeFolderPermission](./exchangefolderpermission) | Rappresenta un'autorizzazione su una cartella. |
| [ExchangeFolderPermissionCollection](./exchangefolderpermissioncollection) | Rappresenta la raccolta di[`ExchangeFolderPermission`](../aspose.email.clients.exchange/exchangefolderpermission) |
| [ExchangeFolderUserInfo](./exchangefolderuserinfo) | Rappresenta un utente che dispone dei permessi di accesso alla cartella |
| [ExchangeMailboxInfo](./exchangemailboxinfo) | Rappresenta le informazioni sulla casella di posta di un server di scambio. |
| [ExchangeMessageInfo](./exchangemessageinfo) | ExchangeMessageInfo rappresenta le informazioni sui messaggi di posta elettronica recuperate dall'archivio di Exchange. |
| [ExchangeMessageInfoCollection](./exchangemessageinfocollection) | Rappresenta una raccolta di oggetti ExchangeMessageInfo. |
| [ExchangeMessagePageInfo](./exchangemessagepageinfo) | Contiene informazioni sulla pagina recuperata quando vengono utilizzati i metodi di paging. |
| [ExchangePermissionCollection](./exchangepermissioncollection) | Rappresenta la raccolta di[`ExchangeBasePermission`](../aspose.email.clients.exchange/exchangebasepermission) |
| [ExchangeQueryBuilder](./exchangequerybuilder) | Rappresenta il builder dell'espressione di ricerca in base ai filtri di ricerca utilizzati dal protocollo Exchange. |
| [ExtendedPropertiesComparisonField](./extendedpropertiescomparisonfield) | Definisce il dizionario con coppie di descrittori di proprietà e campo di confronto per la ricerca di proprietà estese |
| [GetUserSettingsResponse](./getusersettingsresponse) | Rappresenta la risposta a una chiamata GetUsersSettings per un singolo utente. |
| [GetUserSettingsResponseCollection](./getusersettingsresponsecollection) | Rappresenta una raccolta di risposte a GetUserSettings |
| [InboxRule](./inboxrule) | Rappresenta una regola di posta in arrivo |
| [RuleActions](./ruleactions) | Rappresenta l'insieme di azioni disponibili per una regola. |
| [RulePredicates](./rulepredicates) | Rappresenta il predicato della regola |
| [SizeRange](./sizerange) | Rappresenta l'intervallo di dimensioni |
| [UserSettingError](./usersettingerror) | Rappresenta un errore da una richiesta GetUserSettings. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IExchangeClientBase](./iexchangeclientbase) | Rappresenta l'interfaccia per i client Exchange di base. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [AutodiscoverErrorCode](./autodiscovererrorcode) | Definisce i codici di errore che possono essere restituiti dal servizio di individuazione automatica. |
| [ExchangeCalendarPermissionLevel](./exchangecalendarpermissionlevel) | Specifica il livello di autorizzazione di un utente su una cartella del calendario. |
| [ExchangeCalendarPermissionReadAccess](./exchangecalendarpermissionreadaccess) | SSpecifica se un utente dispone dell'autorizzazione per leggere gli elementi in una cartella. |
| [ExchangeFolderPermissionAction](./exchangefolderpermissionaction) | Definisce quali elementi in una cartella un utente ha il permesso di modificare o eliminare. |
| [ExchangeFolderPermissionLevel](./exchangefolderpermissionlevel) | Specifica il livello di autorizzazione che un utente ha su una cartella. |
| [ExchangeFolderPermissionReadAccess](./exchangefolderpermissionreadaccess) | SSpecifica se un utente dispone dell'autorizzazione per leggere gli elementi in una cartella. |
| [ExchangeFolderType](./exchangefoldertype) | Enumera i tipi di cartelle distinti. Questi valori sono contenuti anche nella proprietà PidTagContainerClass. |
| [ExchangeFolderUserType](./exchangefolderusertype) | Enumera gli account utente distinti |
| [ExchangeListMessagesOptions](./exchangelistmessagesoptions) | Enumera le opzioni dei messaggi dell'elenco |
| [ExchangeMessageFlag](./exchangemessageflag) | Rappresenta un flag di messaggio. |
| [FlaggedForAction](./flaggedforaction) | Enumera contrassegnati per l'azione |
| [ImportanceChoices](./importancechoices) | Enumera i livelli di importanza per un elemento |
| [MessageInfoType](./messageinfotype) | Enumera i tipi di messaggio. |
| [RulePredicateFlags](./rulepredicateflags) | Rappresenta i flag RulePredicate |
| [SearchItemType](./searchitemtype) | Fornisce i valori del tipo di elemento per limitare i risultati della ricerca a un solo tipo specifico di elemento. |
| [SensitivityChoices](./sensitivitychoices) | Enumera i tipi di livello di sensibilità disponibili per un elemento. |
| [UserSettingName](./usersettingname) | Impostazioni utente che possono essere richieste utilizzando GetUserSettings. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
