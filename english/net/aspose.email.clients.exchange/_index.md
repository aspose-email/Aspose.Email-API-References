---
title: Aspose.Email.Clients.Exchange
second_title: Aspose.Email for .NET API Reference
description: The Aspose.Email.Clients.Exchange namespace provides classes for Microsofrt Exchange Server access.
type: docs
weight: 140
url: /net/aspose.email.clients.exchange/
---
The **Aspose.Email.Clients.Exchange** namespace provides classes for Microsofrt Exchange Server access.

## Classes

| Class | Description |
| --- | --- |
| [AppointmentPageInfo](./appointmentpageinfo) | Contains information about retrieved page when paging methods are used. |
| [AppointmentQueryBuilder](./appointmentquerybuilder) | Represents the builder of search expression that used by Exchange protocol. |
| [AutodiscoverRedirectionUrlValidationCallback](./autodiscoverredirectionurlvalidationcallback) | Defines a delegate that is used by the AutodiscoverService to ask whether a redirectionUrl can be used. |
| [AutodiscoverResponse](./autodiscoverresponse) | Represents the base class for all responses returned by the Autodiscover service. |
| [AutodiscoverResponseCollection&lt;TResponse&gt;](./autodiscoverresponsecollection-1) | Represents a collection of responses to a call to the Autodiscover service. |
| [AutodiscoverService](./autodiscoverservice) | Represents a binding to the Exchange Autodiscover Service. |
| [AutodiscoverServiceBase](./autodiscoverservicebase) | Represents an abstract binding to an Autodiscover Service. |
| [ComparisonFieldAdapter](./comparisonfieldadapter) | Implements adapter for using [`ComparisonField`](aspose.email.tools.search/comparisonfield) according to their type |
| [ContactQueryBuilder](./contactquerybuilder) | Represents the builder of search expression that used by Exchange protocol. |
| [ExchangeAdvancedSyntaxMailQuery](./exchangeadvancedsyntaxmailquery) | Represents the search criteria, that are used to match several message properties in the mailbox. Implements an Advanced Query Syntax (AQS) search that is used by EWS. AQS described at https://docs.microsoft.com/exchange/client-developer/exchange-web-services/how-to-perform-an-aqs-search-by-using-ews-in-exchange. |
| [ExchangeAdvancedSyntaxQueryBuilder](./exchangeadvancedsyntaxquerybuilder) | Represents the builder of search expression based on the Advanced Query Syntax (AQS) that used by Exchange protocol. AQS is an alternative to search filters for expressing search criteria. |
| [ExchangeAttachmentInfo](./exchangeattachmentinfo) | Represents an attachment information transmitted over exchange protocols |
| [ExchangeAttachmentInfoCollection](./exchangeattachmentinfocollection) | Represents the collection of [`ExchangeAttachmentInfo`](aspose.email.clients.exchange/exchangeattachmentinfo) |
| [ExchangeBasePermission](./exchangebasepermission) | Provides abstract base class for permissions to folders on Exchange Server. |
| [ExchangeCalendarPermission](./exchangecalendarpermission) | Represents a permission on a calendar folder. |
| [ExchangeClientBase](./exchangeclientbase) | Provides the abstract base class to MS Exchange Server access. |
| [ExchangeDistributionList](./exchangedistributionlist) | Represents a Distribution List properties |
| [ExchangeFolderInfo](./exchangefolderinfo) | Provides information about an MS Exchange folder. |
| [ExchangeFolderInfoCollection](./exchangefolderinfocollection) | Represents a collection of ExchangeMessageInfo objects. |
| [ExchangeFolderPageInfo](./exchangefolderpageinfo) | Contains information about retrieved page when paging methods are used. |
| [ExchangeFolderPermission](./exchangefolderpermission) | Represents a permission on a folder. |
| [ExchangeFolderPermissionCollection](./exchangefolderpermissioncollection) | Represents the collection of [`ExchangeFolderPermission`](aspose.email.clients.exchange/exchangefolderpermission) |
| [ExchangeFolderUserInfo](./exchangefolderuserinfo) | Represents a user who has folder access permissions |
| [ExchangeMailboxInfo](./exchangemailboxinfo) | Represents the mail box information of an exchange server. |
| [ExchangeMessageInfo](./exchangemessageinfo) | The ExchangeMessageInfo represents the E-Mail message info fetched from the Exchange Store. |
| [ExchangeMessageInfoCollection](./exchangemessageinfocollection) | Represents a collection of ExchangeMessageInfo objects. |
| [ExchangeMessagePageInfo](./exchangemessagepageinfo) | Contains information about retrieved page when paging methods are used. |
| [ExchangePermissionCollection](./exchangepermissioncollection) | Represents the collection of [`ExchangeBasePermission`](aspose.email.clients.exchange/exchangebasepermission) |
| [ExchangeQueryBuilder](./exchangequerybuilder) | Represents the builder of search expression based on search filters that used by Exchange protocol. |
| [ExtendedPropertiesComparisonField](./extendedpropertiescomparisonfield) | Defines dictionary with pairs of property descriptors and comparison field to search by extended properties |
| [GetUserSettingsResponse](./getusersettingsresponse) | Represents the response to a GetUsersSettings call for an individual user. |
| [GetUserSettingsResponseCollection](./getusersettingsresponsecollection) | Represents a collection of responses to GetUserSettings |
| [InboxRule](./inboxrule) | Represents a inbox rule |
| [RuleActions](./ruleactions) | Represents the set of actions that are available to a rule. |
| [RulePredicates](./rulepredicates) | Represents rule predicate |
| [SizeRange](./sizerange) | Represents the size range |
| [UserSettingError](./usersettingerror) | Represents an error from a GetUserSettings request. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IExchangeClientBase](./iexchangeclientbase) | Represents the interface for base Exchange clients. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [AutodiscoverErrorCode](./autodiscovererrorcode) | Defines the error codes that can be returned by the Autodiscover service. |
| [ExchangeCalendarPermissionLevel](./exchangecalendarpermissionlevel) | Specifies the permission level that a user has on a calendar folder. |
| [ExchangeCalendarPermissionReadAccess](./exchangecalendarpermissionreadaccess) | Sspecifies whether a user has permission to read items in a folder. |
| [ExchangeFolderPermissionAction](./exchangefolderpermissionaction) | Defines which items in a folder a user has permission to edit or delete. |
| [ExchangeFolderPermissionLevel](./exchangefolderpermissionlevel) | Specifies the permission level that a user has on a folder. |
| [ExchangeFolderPermissionReadAccess](./exchangefolderpermissionreadaccess) | Sspecifies whether a user has permission to read items in a folder. |
| [ExchangeFolderType](./exchangefoldertype) | Enumerates the distinguished folder types. This values also contained in PidTagContainerClass property. |
| [ExchangeFolderUserType](./exchangefolderusertype) | Enumerates the distinguished user accounts |
| [ExchangeListMessagesOptions](./exchangelistmessagesoptions) | Enumerates the list messages options |
| [ExchangeMessageFlag](./exchangemessageflag) | Represents a flags of message. |
| [FlaggedForAction](./flaggedforaction) | Enumerates flagged for action |
| [ImportanceChoices](./importancechoices) | Enumerates the levels of importance for an item |
| [MessageInfoType](./messageinfotype) | Enumerates the message types. |
| [RulePredicateFlags](./rulepredicateflags) | Represents the RulePredicate flags |
| [SearchItemType](./searchitemtype) | Provides the item type values to limit search results to only a specific type of item. |
| [SensitivityChoices](./sensitivitychoices) | Enumerates the sensitivity level types that are available for an item. |
| [UserSettingName](./usersettingname) | User settings that can be requested using GetUserSettings. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
