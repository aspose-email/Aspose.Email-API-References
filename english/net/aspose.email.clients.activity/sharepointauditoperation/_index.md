---
title: SharePointAuditOperation
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 2760
url: /net/aspose.email.clients.activity/sharepointauditoperation/
---
## SharePointAuditOperation enumeration

SharePoint audit operations

```csharp
public enum SharePointAuditOperation
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| AccessInvitationAccepted | `0` | This operation is in Preview. The recipient of an invitation to view or edit a shared file (or folder) has accessed the shared file by clicking on the link in the invitation. |
| AccessInvitationCreated | `1` | This operation is in Preview. User sends an invitation to another person (inside or outside their organization) to view or edit a shared file or folder on a SharePoint or OneDrive for Business site. The details of the event entry identifies the name of the file that was shared, the user the invitation was sent to, and the type of the sharing permission selected by the person who sent the invitation. |
| AccessInvitationExpired | `2` | This operation is in Preview. An invitation sent to an external user expires. By default, an invitation sent to a user outside of your organization expires after 7 days if the invitation isn't accepted. |
| AccessInvitationRevoked | `3` | This operation is in Preview. The site administrator or owner of a site or document in SharePoint or OneDrive for Business withdraws an invitation that was sent to a user outside your organization. An invitation can be withdrawn only before it's accepted. |
| AccessInvitationUpdated | `4` | This operation is in Preview. The user who created and sent an invitation to another person to view or edit a shared file (or folder) on a SharePoint or OneDrive for Business site resends the invitation. |
| AccessRequestApproved | `5` | The site administrator or owner of a site or document in SharePoint or OneDrive for Business approves a user request to access the site or document. |
| AccessRequestCreated | `6` | User requests access to a site or document in SharePoint or OneDrive for Business that they don't have permission to access. |
| AccessRequestRejected | `7` | This operation is in Preview. The site administrator or owner of a site or document in SharePoint declines a user request to access the site or document. |
| ActivationEnabled | `8` | This operation is in Preview. Users can browser-enable form templates that don't contain form code, require full trust, enable rendering on a mobile device, or use a data connection managed by a server administrator. |
| AdministratorAddedToTermStore | `9` | This operation is in Preview. Term store administrator added. |
| AdministratorDeletedFromTermStore | `10` | This operation is in Preview. Term store administrator deleted. |
| AllowGroupCreationSet | `11` | This operation is in Preview. Site administrator or owner adds a permission level to a SharePoint or OneDrive for Business site that allows a user assigned that permission to create a group for that site. |
| AppCatalogCreated | `12` | This operation is in Preview. App catalog created to make custom business apps available for your SharePoint Environment. |
| AuditPolicyRemoved | `13` | This operation is in Preview. Document LifeCycle Policy has been removed for a site collection. |
| AuditPolicyUpdate | `14` | This operation is in Preview. Document LifeCycle Policy has been updated for a site collection. |
| AzureStreamingEnabledSet | `15` | This operation is in Preview. A video portal owner has allowed video streaming from Azure. |
| CollaborationTypeModified | `16` | This operation is in Preview. The type of collaboration allowed on sites (for example, intranet, extranet, or public) has been modified. |
| ConnectedSiteSettingModified | `17` | User has either created, modified or deleted the link between a project and a project site or the user modifies the synchronization setting on the link in Project Web App. |
| CreateSSOApplication | `18` | This operation is in Preview. Target application created in Secure store service. |
| CustomFieldOrLookupTableCreated | `19` | User created a custom frield or lookup table/item in Project Web App. |
| CustomFieldOrLookupTableDeleted | `20` | User deleted a custom field or lookup table/item in Project Web App. |
| CustomFieldOrLookupTableModified | `21` | User modified a custom field or lookup table/item in Project Web App. |
| CustomizeExemptUsers | `22` | This operation is in Preview. Global administrator customized the list of exempt user agents in SharePoint admin center. You can specify which user agents to exempt from receiving an entire Web page to index. This means when a user agent you've specified as exempt encounters an InfoPath form, the form will be returned as an XML file instead of an entire Web page. This makes indexing InfoPath forms faster. |
| DefaultLanguageChangedInTermStore | `23` | This operation is in Preview. Language setting changed in the terminology store. |
| DelegateModified | `24` | User created or modified a security delegate in Project Web App. |
| DelegateRemoved | `25` | User deleted a security delegate in Project Web App. |
| DeleteSSOApplication | `26` | This operation is in Preview. An SSO application was deleted. |
| eDiscoveryHoldApplied | `27` | This operation is in Preview. An In-Place Hold was placed on a content source. In-Place Holds are managed by using an eDiscovery site collection (such as the eDiscovery Center) in SharePoint. |
| eDiscoveryHoldRemoved | `28` | This operation is in Preview. An In-Place Hold was removed from a content source. In-Place Holds are managed by using an eDiscovery site collection (such as the eDiscovery Center) in SharePoint. |
| eDiscoverySearchPerformed | `29` | This operation is in Preview. An eDiscovery search was performed using an eDiscovery site collection in SharePoint. |
| EngagementAccepted | `30` | User accepts a resource engagement in Project Web App. |
| EngagementModified | `31` | User modifies a resource engagement in Project Web App. |
| EngagementRejected | `32` | User rejects a resource engagement in Project Web App. |
| EnterpriseCalendarModified | `33` | User copies, modifies or delete an enterprise calendar in Project Web App. |
| EntityDeleted | `34` | User deletes a timesheet in Project Web App. |
| EntityForceCheckedIn | `35` | User forces a checkin on a calendar, custom field or lookup table in Project Web App. |
| ExemptUserAgentSet | `36` | This operation is in Preview. Global administrator adds a user agent to the list of exempt user agents in the SharePoint admin center. |
| FileAccessed | `37` | User or system account accesses a file on a SharePoint or OneDrive for Business site. System accounts can also generate FileAccessed events. |
| FileCheckOutDiscarded | `38` | This operation is in Preview. User discards (or undos) a checked out file. That means any changes they made to the file when it was checked out are discarded, and not saved to the version of the document in the document library. |
| FileCheckedIn | `39` | This operation is in Preview. User checks in a document that they checked out from a SharePoint or OneDrive for Business document library. |
| FileCheckedOut | `40` | This operation is in Preview. User checks out a document located in a SharePoint or OneDrive for Business document library. Users can check out and make changes to documents that have been shared with them. |
| FileCopied | `41` | User copies a document from a SharePoint or OneDrive for Business site. The copied file can be saved to another folder on the site. |
| FileDeleted | `42` | User deletes a document from a SharePoint or OneDrive for Business site. |
| FileDeletedFirstStageRecycleBin | `43` | User deletes a file from the recycle bin on a SharePoint or OneDrive for Business site. |
| FileDeletedSecondStageRecycleBin | `44` | User deletes a file from the second-stage recycle bin on a SharePoint or OneDrive for Business site. |
| FileDownloaded | `45` | User downloads a document from a SharePoint or OneDrive for Business site. |
| FileFetched | `46` | This event has been replaced by the FileAccessed event, and has been deprecated. |
| FileModified | `47` | User or system account modifies the content or the properties of a document located on a SharePoint or OneDrive for Business site. |
| FileMoved | `48` | User moves a document from its current location on a SharePoint or OneDrive for Business site to a new location. |
| FilePreviewed | `49` | User previews a document on a SharePoint or OneDrive for Business site. |
| FileRenamed | `50` | User renames a document on a SharePoint or OneDrive for Business site. |
| FileRestored | `51` | User restores a document from the recycle bin of a SharePoint or OneDrive for Business site. |
| FileSyncDownloadedFull | `52` | User establishes a sync relationship and successfully downloads files for the first time to their computer from a SharePoint or OneDrive for Business document library. |
| FileSyncDownloadedPartial | `53` | User successfully downloads any changes to files from SharePoint or OneDrive for Business document library. This event indicates that any changes that were made to files in the document library were downloaded to the user's computer. Only changes were downloaded because the document library was previously downloaded by the user (as indicated by the FileSyncDownloadedFull event). |
| FileSyncUploadedFull | `54` | This operation is in Preview. User establishes a sync relationship and successfully uploads files for the first time from their computer to a SharePoint or OneDrive for Business document library. |
| FileSyncUploadedPartial | `55` | This operation is in Preview. User successfully uploads changes to files on a SharePoint or OneDrive for Business document library. This event indicates that any changes made to the local version of a file from a document library are successfully uploaded to the document library. Only changes are unloaded because those files were previously uploaded by the user (as indicated by the FileSyncUploadedFull event). |
| FileUploaded | `56` | User uploads a document to a folder on a SharePoint or OneDrive for Business site. |
| FileViewed | `57` | This event has been replaced by the FileAccessed event, and has been deprecated. |
| FolderCopied | `58` | User copies a folder from a SharePoint or OneDrive for Business site to another location in SharePoint or OneDrive for Business. |
| FolderCreated | `59` | User creates a folder on a SharePoint or OneDrive for Business site. |
| FolderDeleted | `60` | User deletes a folder from a SharePoint or OneDrive for Business site. |
| FolderDeletedFirstStageRecycleBin | `61` | User deletes a folder from the recycle bin on a SharePoint or OneDrive for Business site . |
| FolderDeletedSecondStageRecycleBin | `62` | User deletes a folder from the second-stage recycle bin on a SharePoint or OneDrive for Business site. |
| FolderModified | `63` | User modifies a folder on a SharePoint or OneDrive for Business site. This event includes folder metadata changes, such as tags and properties. |
| FolderMoved | `64` | User moves a folder from a SharePoint or OneDrive for Business site. |
| FolderRenamed | `65` | User renames a folder on a SharePoint or OneDrive for Business site. |
| FolderRestored | `66` | User restores a folder from the Recycle Bin on a SharePoint or OneDrive for Business site. |
| GroupAdded | `67` | This operation is in Preview. Site administrator or owner creates a group for a SharePoint or OneDrive for Business site, or performs a task that results in a group being created. For example, the first time a user creates a link to share a file, a system group is added to the user's OneDrive for Business site. This event can also be a result of a user creating a link with edit permissions to a shared file. |
| GroupRemoved | `68` | This operation is in Preview. User deletes a group from a SharePoint or OneDrive for Business site. |
| GroupUpdated | `69` | This operation is in Preview. Site administrator or owner changes the settings of a group for a SharePoint or OneDrive for Business site. This can include changing the group's name, who can view or edit the group membership, and how membership requests are handled. |
| LanguageAddedToTermStore | `70` | This operation is in Preview. Language added to the terminology store. |
| LanguageRemovedFromTermStore | `71` | This operation is in Preview. Language removed from the terminology store. |
| LegacyWorkflowEnabledSet | `72` | This operation is in Preview. Site administrator or owner adds theSharePoint Workflow Task content type to the site. Global administrators can also enable work flows for the entire organization in theSharePoint admin center. |
| LookAndFeelModified | `73` | User modifies a quick launch, gantt chart formats, or group formats. Or the user creats, modifies, or deletes a view in Project Web App. |
| ManagedSyncClientAllowed | `74` | User successfully establishes a sync relationship with a SharePoint or OneDrive for Business site. The sync relationship is successful because the user's computer is a member of a domain that's been added to the list of domains (called the safe recipients list) that can access document libraries in your organization. For more information about this feature, see Use Windows PowerShell cmdlets to enable OneDrive sync for domains that are on the safe recipients list. |
| MaxQuotaModified | `75` | This operation is in Preview. The maximum quota for a site has been modified. |
| MaxResourceUsageModified | `76` | This operation is in Preview. The maximum allowable resource usage for a site has been modified. |
| MySitePublicEnabledSet | `77` | This operation is in Preview. The flag enabling users to have public MySites has been set by the SharePoint administrator. |
| NewsFeedEnabledSet | `78` | This operation is in Preview. Site administrator or owner enables RSS feeds for a SharePoint or OneDrive for Business site. Global administrators can enable RSS feeds for the entire organization in the SharePoint admin center. |
| ODBNextUXSettings | `79` | This operation is in Preview. New UI for OneDrive for Business has been enabled. |
| OfficeOnDemandSet | `80` | This operation is in Preview. Site administrator enables Office on Demand, which lets users access the latest version of Office desktop applications. Office on Demand is enabled in the SharePoint admin center and requires an Office 365 subscription that includes full, installed Office applications. |
| PageViewed | `81` | User views a page on a SharePoint site or OneDrive for Business site. This does not include viewing document library files from a SharePoint site or One Drive for Business site on a browser. |
| PeopleResultsScopeSet | `82` | This operation is in Preview. Site administrator creates or changes the result source for People Searches for a SharePoint site. |
| PermissionSyncSettingModified | `83` | User modifies the project permission sync settings in Project Web App. |
| PermissionTemplateModified | `84` | User creates, modifies or deletes a permissions template in Project Web App. |
| PortfolioDataAccessed | `85` | User accesses portfolio content (driver library, driver priortization, portfolio analyses) in Project Web App. |
| PortfolioDataModified | `86` | User creates, modifies, or deletes portfolio data (driver library, driver priortization, portfolio analyses) in Project Web App. |
| PreviewModeEnabledSet | `87` | This operation is in Preview. Site administrator enables document preview for a SharePoint site. |
| ProjectAccessed | `88` | User accesses project content in Project Web App. |
| ProjectCheckedIn | `89` | User checks in a project that they checked out from a Project Web App. |
| ProjectCheckedOut | `90` | User checks out a project located in a Project Web App. Users can check out and make changes to projects that they have permission to open. |
| ProjectCreated | `91` | User creates a project in Project Web App. |
| ProjectDeleted | `92` | User deletes a project in Project Web App. |
| ProjectForceCheckedIn | `93` | User forces a check in on a project in Project Web App. |
| ProjectModified | `94` | User modifies a project in Project Web App. |
| ProjectPublished | `95` | User publishes a project in Project Web App. |
| ProjectWorkflowRestarted | `96` | User restarts a workflow in Project Web App. |
| PWASettingsAccessed | `97` | User access the Project Web App settings via CSOM. |
| PWASettingsModified | `98` | User modifies the a Project Web App configuration. |
| QueueJobStateModified | `99` | User cancels or restarts a queue job in Project Web App. |
| QuotaWarningEnabledModified | `100` | This operation is in Preview. Storage quota warning modified. |
| RenderingEnabled | `101` | This operation is in Preview. Browser-enabled form templates will be rendered by InfoPath forms services. |
| ReportingAccessed | `102` | User accessed the reporting endpoint in Project Web App. |
| ReportingSettingModified | `103` | User modifies the reporting configuration in Project Web App. |
| ResourceAccessed | `104` | User accesses an enterprise resource content in Project Web App. |
| ResourceCheckedIn | `105` | User checks in an enterprise resource that they checked out from Project Web App. |
| ResourceCheckedOut | `106` | User checks out an enterprise resource located in Project Web App. |
| ResourceCreated | `107` | User creates an enterprise resource in Project Web App. |
| ResourceDeleted | `108` | User deletes an enterprise resource in Project Web App. |
| ResourceForceCheckedIn | `109` | User forces a checkin of an enterprise resource in Project Web App. |
| ResourceModified | `110` | User modifies an enterprise resource in Project Web App. |
| ResourcePlanCheckedInOrOut | `111` | User checks in or out a resource plan in Project Web App. |
| ResourcePlanModified | `112` | User modifies a resource plan in Project Web App. |
| ResourcePlanPublished | `113` | User publishes a resource plan in Project Web App. |
| ResourceRedacted | `114` | User redacts an enterprise resource removing all personal information in Project Web App. |
| ResourceWarningEnabledModified | `115` | This operation is in Preview. Resource quota warning modified. |
| SSOGroupCredentialsSet | `116` | This operation is in Preview. Group credentials set in Secure store service. |
| SSOUserCredentialsSet | `117` | This operation is in Preview. User credentials set in Secure store service. |
| SearchCenterUrlSet | `118` | This operation is in Preview. Search center URL set. |
| SecondaryMySiteOwnerSet | `119` | This operation is in Preview. A user has added a secondary owner to their MySite. |
| SecurityCategoryModified | `120` | User creates, modifies or deletes a security category in Project Web App. |
| SecurityGroupModified | `121` | User creates, modifies or deletes a security group in Project Web App. |
| SendToConnectionAdded | `122` | This operation is in Preview. Global administrator creates a new Send To connection on the Records management page in the SharePoint admin center. A Send To connection specifies settings for a document repository or a records center. When you create a Send To connection, a Content Organizer can submit documents to the specified location. |
| SendToConnectionRemoved | `123` | This operation is in Preview. Global administrator deletes a Send To connection on the Records management page in the SharePoint admin center. |
| SharedLinkCreated | `124` | User creates a link to a shared file in SharePoint or OneDrive for Business. This link can be sent to other people to give them access to the file. A user can create two types of links: a link that allows a user to view and edit the shared file, or a link that allows the user to just view the file. |
| SharedLinkDisabled | `125` | This operation is in Preview. User disables (permanently) a link that was created to share a file. |
| SharingInvitationAccepted | `126` | This operation is in Preview. User accepts an invitation to share a file or folder. This event is logged when a user shares a file with other users. |
| SharingRevoked | `127` | This operation is in Preview. User unshares a file or folder that was previously shared with other users. This event is logged when a user stops sharing a file with other users. |
| SharingSet | `128` | User shares a file or folder located in SharePoint or OneDrive for Business with another user inside their organization. |
| SiteAdminChangeRequest | `129` | This operation is in Preview. User requests to be added as a site collection administrator for a SharePoint site collection. Site collection administrators have full control permissions for the site collection and all subsites. |
| SiteCollectionAdminAdded | `130` | This operation is in Preview. Site collection administrator or owner adds a person as a site collection administrator for a SharePoint or OneDrive for Business site. Site collection administrators have full control permissions for the site collection and all subsites. |
| SiteCollectionCreated | `131` | This operation is in Preview. Global administrator creates a new site collection in your SharePoint organization. |
| SiteRenamed | `132` | This operation is in Preview. Site administrator or owner renames a SharePoint or OneDrive for Business site |
| StatusReportModified | `133` | User creates, modifies or deletes a status report in Project Web App. |
| SyncGetChanges | `134` | This operation is in Preview. User clicks Sync in the action tray on in SharePoint or OneDrive for Business to synchronize any changes to file in a document library to their computer. |
| TaskStatusAccessed | `135` | User accesses the status of one or more tasks in Project Web App. |
| TaskStatusApproved | `136` | User approves a status update of one or more tasks in Project Web App. |
| TaskStatusRejected | `137` | User rejects a status update of one or more tasks in Project Web App. |
| TaskStatusSaved | `138` | User saves a status update of one or more tasks in Project Web App. |
| TaskStatusSubmitted | `139` | User submits a status update of one or more tasks in Project Web App. |
| TimesheetAccessed | `140` | User accesses a timesheet in Project Web App. |
| TimesheetApproved | `141` | User approves timesheet in Project Web App. |
| TimesheetRejected | `142` | User rejects a timesheet in Project Web App. |
| TimesheetSaved | `143` | User saves a timesheet in Project Web App. |
| TimesheetSubmitted | `144` | User submits a status timesheet in Project Web App. |
| UnmanagedSyncClientBlocked | `145` | User tries to establish a sync relationship with a SharePoint or OneDrive for Business site from a computer that isn't a member of your organization's domain or is a member of a domain that hasn't been added to the list of domains (called the safe recipients list) that can access document libraries in your organization. The sync relationship is not allowed, and the user's computer is blocked from syncing, downloading, or uploading files on a document library. For information about this feature, see Use Windows PowerShell cmdlets to enable OneDrive sync for domains that are on the safe recipients list. |
| UpdateSSOApplication | `146` | This operation is in Preview. Target application updated in Secure store service. |
| UserAddedToGroup | `147` | This operation is in Preview. Site administrator or owner adds a person to a group on a SharePoint or OneDrive for Business site. Adding a person to a group grants the user the permissions that were assigned to the group. |
| UserRemovedFromGroup | `148` | This operation is in Preview. Site administrator or owner removes a person from a group on a SharePoint or OneDrive for Business site. After the person is removed, they no longer are granted the permissions that were assigned to the group. |
| WorkflowModified | `149` | User creates, modifies, or deletes an Enterprise Project Type or Workflow phases or stages in Project Web App. |

### See Also

* namespace [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
