---
title: Aspose.Email.Clients.Exchange
second_title: Aspose.Email for .NET API Reference
description: The **Aspose.Email.Clients.Exchange** namespace provides classes for Microsofrt Exchange Server access.
type: docs
weight: 100
url: /net/aspose.email.clients.exchange/
---
The **Aspose.Email.Clients.Exchange** namespace provides classes for Microsofrt Exchange Server access.

## Classes

| Class | Description |
| --- | --- |
| class [AppointmentPageInfo](./appointmentpageinfo) | Contains information about retrieved page when paging methods are used. |
| class [AppointmentQueryBuilder](./appointmentquerybuilder) | Represents the builder of search expression that used by Exchange protocol. |
| delegate [AutodiscoverRedirectionUrlValidationCallback](./autodiscoverredirectionurlvalidationcallback) | Defines a delegate that is used by the AutodiscoverService to ask whether a redirectionUrl can be used. |
| abstract class [AutodiscoverResponse](./autodiscoverresponse) | Represents the base class for all responses returned by the Autodiscover service. |
| abstract class [AutodiscoverResponseCollection&lt;TResponse&gt;](./autodiscoverresponsecollection-1) | Represents a collection of responses to a call to the Autodiscover service. |
| class [AutodiscoverService](./autodiscoverservice) | Represents a binding to the Exchange Autodiscover Service. |
| abstract class [AutodiscoverServiceBase](./autodiscoverservicebase) | Represents an abstract binding to an Autodiscover Service. |
| class [ComparisonFieldAdapter](./comparisonfieldadapter) | Implements adapter for using [`ComparisonField`](aspose.email.tools.search/comparisonfield) according to their type |
| class [ContactQueryBuilder](./contactquerybuilder) | Represents the builder of search expression that used by Exchange protocol. |
| class [ExchangeAdvancedSyntaxMailQuery](./exchangeadvancedsyntaxmailquery) | Represents the search criteria, that are used to match several message properties in the mailbox. Implements an Advanced Query Syntax (AQS) search that is used by EWS. AQS described at https://docs.microsoft.com/exchange/client-developer/exchange-web-services/how-to-perform-an-aqs-search-by-using-ews-in-exchange. |
| class [ExchangeAdvancedSyntaxQueryBuilder](./exchangeadvancedsyntaxquerybuilder) | Represents the builder of search expression based on the Advanced Query Syntax (AQS) that used by Exchange protocol. AQS is an alternative to search filters for expressing search criteria. |
| class [ExchangeAttachmentInfo](./exchangeattachmentinfo) | Represents an attachment information transmitted over exchange protocols |
| class [ExchangeAttachmentInfoCollection](./exchangeattachmentinfocollection) | Represents the collection of [`ExchangeAttachmentInfo`](aspose.email.clients.exchange/exchangeattachmentinfo) |
| abstract class [ExchangeBasePermission](./exchangebasepermission) | Provides abstract base class for permissions to folders on Exchange Server. |
| class [ExchangeCalendarPermission](./exchangecalendarpermission) | Represents a permission on a calendar folder. |
| abstract class [ExchangeClientBase](./exchangeclientbase) | Provides the abstract base class to MS Exchange Server access. |
| class [ExchangeDistributionList](./exchangedistributionlist) | Represents a Distribution List properties |
| class [ExchangeFolderInfo](./exchangefolderinfo) | Provides information about an MS Exchange folder. |
| class [ExchangeFolderInfoCollection](./exchangefolderinfocollection) | Represents a collection of ExchangeMessageInfo objects. |
| class [ExchangeFolderPageInfo](./exchangefolderpageinfo) | Contains information about retrieved page when paging methods are used. |
| class [ExchangeFolderPermission](./exchangefolderpermission) | Represents a permission on a folder. |
| class [ExchangeFolderPermissionCollection](./exchangefolderpermissioncollection) | Represents the collection of [`ExchangeFolderPermission`](aspose.email.clients.exchange/exchangefolderpermission) |
| class [ExchangeFolderUserInfo](./exchangefolderuserinfo) | Represents a user who has folder access permissions |
| abstract class [ExchangeMailboxInfo](./exchangemailboxinfo) | Represents the mail box information of an exchange server. |
| abstract class [ExchangeMessageInfo](./exchangemessageinfo) | The ExchangeMessageInfo represents the E-Mail message info fetched from the Exchange Store. |
| class [ExchangeMessageInfoCollection](./exchangemessageinfocollection) | Represents a collection of ExchangeMessageInfo objects. |
| class [ExchangeMessagePageInfo](./exchangemessagepageinfo) | Contains information about retrieved page when paging methods are used. |
| class [ExchangePermissionCollection](./exchangepermissioncollection) | Represents the collection of [`ExchangeBasePermission`](aspose.email.clients.exchange/exchangebasepermission) |
| class [ExchangeQueryBuilder](./exchangequerybuilder) | Represents the builder of search expression based on search filters that used by Exchange protocol. |
| class [ExtendedPropertiesComparisonField](./extendedpropertiescomparisonfield) | Defines dictionary with pairs of property descriptors and comparison field to search by extended properties |
| class [GetUserSettingsResponse](./getusersettingsresponse) | Represents the response to a GetUsersSettings call for an individual user. |
| class [GetUserSettingsResponseCollection](./getusersettingsresponsecollection) | Represents a collection of responses to GetUserSettings |
| class [InboxRule](./inboxrule) | Represents a inbox rule |
| class [RuleActions](./ruleactions) | Represents the set of actions that are available to a rule. |
| class [RulePredicates](./rulepredicates) | Represents rule predicate |
| class [SizeRange](./sizerange) | Represents the size range |
| class [UserSettingError](./usersettingerror) | Represents an error from a GetUserSettings request. |
## Interfaces

| Interface | Description |
| --- | --- |
| interface [IExchangeClientBase](./iexchangeclientbase) | Represents the interface for base Exchange clients. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| enum [AutodiscoverErrorCode](./autodiscovererrorcode) | Defines the error codes that can be returned by the Autodiscover service. |
| enum [ExchangeCalendarPermissionLevel](./exchangecalendarpermissionlevel) | Specifies the permission level that a user has on a calendar folder. |
| enum [ExchangeCalendarPermissionReadAccess](./exchangecalendarpermissionreadaccess) | Sspecifies whether a user has permission to read items in a folder. |
| enum [ExchangeFolderPermissionAction](./exchangefolderpermissionaction) | Defines which items in a folder a user has permission to edit or delete. |
| enum [ExchangeFolderPermissionLevel](./exchangefolderpermissionlevel) | Specifies the permission level that a user has on a folder. |
| enum [ExchangeFolderPermissionReadAccess](./exchangefolderpermissionreadaccess) | Sspecifies whether a user has permission to read items in a folder. |
| enum [ExchangeFolderType](./exchangefoldertype) | Enumerates the distinguished folder types. This values also contained in PidTagContainerClass property. |
| enum [ExchangeFolderUserType](./exchangefolderusertype) | Enumerates the distinguished user accounts |
| enum [ExchangeListMessagesOptions](./exchangelistmessagesoptions) | Enumerates the list messages options |
| enum [ExchangeMessageFlag](./exchangemessageflag) | Represents a flags of message. |
| enum [FlaggedForAction](./flaggedforaction) | Enumerates flagged for action |
| enum [ImportanceChoices](./importancechoices) | Enumerates the levels of importance for an item |
| enum [MessageInfoType](./messageinfotype) | Enumerates the message types. |
| enum [RulePredicateFlags](./rulepredicateflags) | Represents the RulePredicate flags |
| enum [SearchItemType](./searchitemtype) | Provides the item type values to limit search results to only a specific type of item. |
| enum [SensitivityChoices](./sensitivitychoices) | Enumerates the sensitivity level types that are available for an item. |
| enum [UserSettingName](./usersettingname) | User settings that can be requested using GetUserSettings. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
