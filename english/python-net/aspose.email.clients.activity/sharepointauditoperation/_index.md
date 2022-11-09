---
title: SharePointAuditOperation
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 450
url: /python-net/aspose.email.clients.activity/sharepointauditoperation/
---

## SharePointAuditOperation enumeration

SharePoint audit operations

## Members
| Member name | Description |
| :- | :- |
|ACCESS_INVITATION_ACCEPTED|This operation is in Preview.	<br/>            The recipient of an invitation to view or edit a shared file (or folder) has accessed the shared file by clicking on the link in the invitation.|
|ACCESS_INVITATION_CREATED|This operation is in Preview.	<br/>            User sends an invitation to another person (inside or outside their organization) to view or edit a shared file or folder on a SharePoint or OneDrive for Business site. <br/>            The details of the event entry identifies the name of the file that was shared, the user the invitation was sent to, <br/>            and the type of the sharing permission selected by the person who sent the invitation.|
|ACCESS_INVITATION_EXPIRED|This operation is in Preview.	<br/>            An invitation sent to an external user expires. By default, an invitation sent to a user outside of your organization expires after 7 days if the invitation isn't accepted.|
|ACCESS_INVITATION_REVOKED|This operation is in Preview.	<br/>            The site administrator or owner of a site or document in SharePoint or OneDrive for Business withdraws an invitation that was sent to a user outside your organization. <br/>            An invitation can be withdrawn only before it's accepted.|
|ACCESS_INVITATION_UPDATED|This operation is in Preview.	<br/>            The user who created and sent an invitation to another person to view or edit a shared file (or folder) on a SharePoint or OneDrive for Business site resends the invitation.|
|ACCESS_REQUEST_APPROVED|The site administrator or owner of a site or document in SharePoint or OneDrive for Business approves a user request to access the site or document.|
|ACCESS_REQUEST_CREATED|User requests access to a site or document in SharePoint or OneDrive for Business that they don't have permission to access.|
|ACCESS_REQUEST_REJECTED|This operation is in Preview.	<br/>            The site administrator or owner of a site or document in SharePoint declines a user request to access the site or document.|
|ACTIVATION_ENABLED|This operation is in Preview.	<br/>            Users can browser-enable form templates that don't contain form code, require full trust, enable rendering on a mobile device, or use a data connection managed by a server administrator.|
|ADMINISTRATOR_ADDED_TO_TERM_STORE|This operation is in Preview.	<br/>            Term store administrator added.|
|ADMINISTRATOR_DELETED_FROM_TERM_STORE|This operation is in Preview.	<br/>            Term store administrator deleted.|
|ALLOW_GROUP_CREATION_SET|This operation is in Preview.	<br/>            Site administrator or owner adds a permission level to a SharePoint or OneDrive for Business site that allows a user assigned that permission to create a group for that site.|
|APP_CATALOG_CREATED|This operation is in Preview.	<br/>            App catalog created to make custom business apps available for your SharePoint Environment.|
|AUDIT_POLICY_REMOVED|This operation is in Preview.	<br/>            Document LifeCycle Policy has been removed for a site collection.|
|AUDIT_POLICY_UPDATE|This operation is in Preview.	<br/>            Document LifeCycle Policy has been updated for a site collection.|
|AZURE_STREAMING_ENABLED_SET|This operation is in Preview.	<br/>            A video portal owner has allowed video streaming from Azure.|
|COLLABORATION_TYPE_MODIFIED|This operation is in Preview.	<br/>            The type of collaboration allowed on sites (for example, intranet, extranet, or public) has been modified.|
|CONNECTED_SITE_SETTING_MODIFIED|User has either created, modified or deleted the link between a project and a project site or the user modifies the synchronization setting on the link in Project Web App.|
|CREATE_SSO_APPLICATION|This operation is in Preview.	<br/>            Target application created in Secure store service.|
|CUSTOM_FIELD_OR_LOOKUP_TABLE_CREATED|User created a custom frield or lookup table/item in Project Web App.|
|CUSTOM_FIELD_OR_LOOKUP_TABLE_DELETED|User deleted a custom field or lookup table/item in Project Web App.|
|CUSTOM_FIELD_OR_LOOKUP_TABLE_MODIFIED|User modified a custom field or lookup table/item in Project Web App.|
|CUSTOMIZE_EXEMPT_USERS|This operation is in Preview.	<br/>            Global administrator customized the list of exempt user agents in SharePoint admin center. <br/>            You can specify which user agents to exempt from receiving an entire Web page to index. <br/>            This means when a user agent you've specified as exempt encounters an InfoPath form, the form will be returned as an XML file instead of an entire Web page. <br/>            This makes indexing InfoPath forms faster.|
|DEFAULT_LANGUAGE_CHANGED_IN_TERM_STORE|This operation is in Preview.	<br/>            Language setting changed in the terminology store.|
|DELEGATE_MODIFIED|User created or modified a security delegate in Project Web App.|
|DELEGATE_REMOVED|User deleted a security delegate in Project Web App.|
|DELETE_SSO_APPLICATION|This operation is in Preview.	<br/>            An SSO application was deleted.|
|E_DISCOVERY_HOLD_APPLIED|This operation is in Preview.	<br/>            An In-Place Hold was placed on a content source. In-Place Holds are managed by using an eDiscovery site collection (such as the eDiscovery Center) in SharePoint.|
|E_DISCOVERY_HOLD_REMOVED|This operation is in Preview.	<br/>            An In-Place Hold was removed from a content source. In-Place Holds are managed by using an eDiscovery site collection (such as the eDiscovery Center) in SharePoint.|
|E_DISCOVERY_SEARCH_PERFORMED|This operation is in Preview.	<br/>            An eDiscovery search was performed using an eDiscovery site collection in SharePoint.|
|ENGAGEMENT_ACCEPTED|User accepts a resource engagement in Project Web App.|
|ENGAGEMENT_MODIFIED|User modifies a resource engagement in Project Web App.|
|ENGAGEMENT_REJECTED|User rejects a resource engagement in Project Web App.|
|ENTERPRISE_CALENDAR_MODIFIED|User copies, modifies or delete an enterprise calendar in Project Web App.|
|ENTITY_DELETED|User deletes a timesheet in Project Web App.|
|ENTITY_FORCE_CHECKED_IN|User forces a checkin on a calendar, custom field or lookup table in Project Web App.|
|EXEMPT_USER_AGENT_SET|This operation is in Preview.	<br/>            Global administrator adds a user agent to the list of exempt user agents in the SharePoint admin center.|
|FILE_ACCESSED|User or system account accesses a file on a SharePoint or OneDrive for Business site. System accounts can also generate FileAccessed events.|
|FILE_CHECK_OUT_DISCARDED|This operation is in Preview.	<br/>            User discards (or undos) a checked out file. <br/>            That means any changes they made to the file when it was checked out are discarded, and not saved to the version of the document in the document library.|
|FILE_CHECKED_IN|This operation is in Preview.	<br/>            User checks in a document that they checked out from a SharePoint or OneDrive for Business document library.|
|FILE_CHECKED_OUT|This operation is in Preview.	<br/>            User checks out a document located in a SharePoint or OneDrive for Business document library. Users can check out and make changes to documents that have been shared with them.|
|FILE_COPIED|User copies a document from a SharePoint or OneDrive for Business site. The copied file can be saved to another folder on the site.|
|FILE_DELETED|User deletes a document from a SharePoint or OneDrive for Business site.|
|FILE_DELETED_FIRST_STAGE_RECYCLE_BIN|User deletes a file from the recycle bin on a SharePoint or OneDrive for Business site.|
|FILE_DELETED_SECOND_STAGE_RECYCLE_BIN|User deletes a file from the second-stage recycle bin on a SharePoint or OneDrive for Business site.|
|FILE_DOWNLOADED|User downloads a document from a SharePoint or OneDrive for Business site.|
|FILE_FETCHED|This event has been replaced by the FileAccessed event, and has been deprecated.|
|FILE_MODIFIED|User or system account modifies the content or the properties of a document located on a SharePoint or OneDrive for Business site.|
|FILE_MOVED|User moves a document from its current location on a SharePoint or OneDrive for Business site to a new location.|
|FILE_PREVIEWED|User previews a document on a SharePoint or OneDrive for Business site.|
|FILE_RENAMED|User renames a document on a SharePoint or OneDrive for Business site.|
|FILE_RESTORED|User restores a document from the recycle bin of a SharePoint or OneDrive for Business site.|
|FILE_SYNC_DOWNLOADED_FULL|User establishes a sync relationship and successfully downloads files for the first time to their computer from a SharePoint or OneDrive for Business document library.|
|FILE_SYNC_DOWNLOADED_PARTIAL|User successfully downloads any changes to files from SharePoint or OneDrive for Business document library. <br/>            This event indicates that any changes that were made to files in the document library were downloaded to the user's computer. <br/>            Only changes were downloaded because the document library was previously downloaded by the user (as indicated by the FileSyncDownloadedFull event).|
|FILE_SYNC_UPLOADED_FULL|This operation is in Preview.	<br/>            User establishes a sync relationship and successfully uploads files for the first time from their computer to a SharePoint or OneDrive for Business document library.|
|FILE_SYNC_UPLOADED_PARTIAL|This operation is in Preview.	<br/>            User successfully uploads changes to files on a SharePoint or OneDrive for Business document library. <br/>            This event indicates that any changes made to the local version of a file from a document library are successfully uploaded to the document library. <br/>            Only changes are unloaded because those files were previously uploaded by the user (as indicated by the FileSyncUploadedFull event).|
|FILE_UPLOADED|User uploads a document to a folder on a SharePoint or OneDrive for Business site.|
|FILE_VIEWED|This event has been replaced by the FileAccessed event, and has been deprecated.|
|FOLDER_COPIED|User copies a folder from a SharePoint or OneDrive for Business site to another location in SharePoint or OneDrive for Business.|
|FOLDER_CREATED|User creates a folder on a SharePoint or OneDrive for Business site.|
|FOLDER_DELETED|User deletes a folder from a SharePoint or OneDrive for Business site.|
|FOLDER_DELETED_FIRST_STAGE_RECYCLE_BIN|User deletes a folder from the recycle bin on a SharePoint or OneDrive for Business site .|
|FOLDER_DELETED_SECOND_STAGE_RECYCLE_BIN|User deletes a folder from the second-stage recycle bin on a SharePoint or OneDrive for Business site.|
|FOLDER_MODIFIED|User modifies a folder on a SharePoint or OneDrive for Business site. This event includes folder metadata changes, such as tags and properties.|
|FOLDER_MOVED|User moves a folder from a SharePoint or OneDrive for Business site.|
|FOLDER_RENAMED|User renames a folder on a SharePoint or OneDrive for Business site.|
|FOLDER_RESTORED|User restores a folder from the Recycle Bin on a SharePoint or OneDrive for Business site.|
|GROUP_ADDED|This operation is in Preview.	<br/>            Site administrator or owner creates a group for a SharePoint or OneDrive for Business site, or performs a task that results in a group being created. <br/>            For example, the first time a user creates a link to share a file, a system group is added to the user's OneDrive for Business site. <br/>            This event can also be a result of a user creating a link with edit permissions to a shared file.|
|GROUP_REMOVED|This operation is in Preview.	<br/>            User deletes a group from a SharePoint or OneDrive for Business site.|
|GROUP_UPDATED|This operation is in Preview.	<br/>            Site administrator or owner changes the settings of a group for a SharePoint or OneDrive for Business site. <br/>            This can include changing the group's name, who can view or edit the group membership, and how membership requests are handled.|
|LANGUAGE_ADDED_TO_TERM_STORE|This operation is in Preview.	<br/>            Language added to the terminology store.|
|LANGUAGE_REMOVED_FROM_TERM_STORE|This operation is in Preview.	<br/>            Language removed from the terminology store.|
|LEGACY_WORKFLOW_ENABLED_SET|This operation is in Preview.	<br/>            Site administrator or owner adds theSharePoint Workflow Task content type to the site. Global administrators can also enable work flows for the entire organization in theSharePoint admin center.|
|LOOK_AND_FEEL_MODIFIED|User modifies a quick launch, gantt chart formats, or group formats.  Or the user creats, modifies, or deletes a view in Project Web App.|
|MANAGED_SYNC_CLIENT_ALLOWED|User successfully establishes a sync relationship with a SharePoint or OneDrive for Business site. <br/>            The sync relationship is successful because the user's computer is a member of a domain <br/>            that's been added to the list of domains (called the safe recipients list) that can access document libraries in your organization. <br/>            For more information about this feature, see Use Windows PowerShell cmdlets to enable OneDrive sync for domains that are on the safe recipients list.|
|MAX_QUOTA_MODIFIED|This operation is in Preview.	<br/>            The maximum quota for a site has been modified.|
|MAX_RESOURCE_USAGE_MODIFIED|This operation is in Preview.	<br/>            The maximum allowable resource usage for a site has been modified.|
|MY_SITE_PUBLIC_ENABLED_SET|This operation is in Preview.	<br/>            The flag enabling users to have public MySites has been set by the SharePoint administrator.|
|NEWS_FEED_ENABLED_SET|This operation is in Preview.	<br/>            Site administrator or owner enables RSS feeds for a SharePoint or OneDrive for Business site. <br/>            Global administrators can enable RSS feeds for the entire organization in the SharePoint admin center.|
|ODB_NEXT_UX_SETTINGS|This operation is in Preview.	<br/>            New UI for OneDrive for Business has been enabled.|
|OFFICE_ON_DEMAND_SET|This operation is in Preview.	<br/>            Site administrator enables Office on Demand, which lets users access the latest version of Office desktop applications. <br/>            Office on Demand is enabled in the SharePoint admin center and requires an Office 365 subscription that includes full, installed Office applications.|
|PAGE_VIEWED|User views a page on a SharePoint site or OneDrive for Business site. <br/>            This does not include viewing document library files from a SharePoint site or One Drive for Business site on a browser.|
|PEOPLE_RESULTS_SCOPE_SET|This operation is in Preview.	<br/>            Site administrator creates or changes the result source for People Searches for a SharePoint site.|
|PERMISSION_SYNC_SETTING_MODIFIED|User modifies the project permission sync settings in Project Web App.|
|PERMISSION_TEMPLATE_MODIFIED|User creates, modifies or deletes a permissions template in Project Web App.|
|PORTFOLIO_DATA_ACCESSED|User accesses portfolio content (driver library, driver priortization, portfolio analyses) in Project Web App.|
|PORTFOLIO_DATA_MODIFIED|User creates, modifies, or deletes portfolio data (driver library, driver priortization, portfolio analyses) in Project Web App.|
|PREVIEW_MODE_ENABLED_SET|This operation is in Preview.	<br/>            Site administrator enables document preview for a SharePoint site.|
|PROJECT_ACCESSED|User accesses project content in Project Web App.|
|PROJECT_CHECKED_IN|User checks in a project that they checked out from a Project Web App.|
|PROJECT_CHECKED_OUT|User checks out a project located in a Project Web App. Users can check out and make changes to projects that they have permission to open.|
|PROJECT_CREATED|User creates a project in Project Web App.|
|PROJECT_DELETED|User deletes a project in Project Web App.|
|PROJECT_FORCE_CHECKED_IN|User forces a check in on a project in Project Web App.|
|PROJECT_MODIFIED|User modifies a project in Project Web App.|
|PROJECT_PUBLISHED|User publishes a project in Project Web App.|
|PROJECT_WORKFLOW_RESTARTED|User restarts a workflow in Project Web App.|
|PWA_SETTINGS_ACCESSED|User access the Project Web App settings via CSOM.|
|PWA_SETTINGS_MODIFIED|User modifies the a Project Web App configuration.|
|QUEUE_JOB_STATE_MODIFIED|User cancels or restarts a queue job in Project Web App.|
|QUOTA_WARNING_ENABLED_MODIFIED|This operation is in Preview.	<br/>            Storage quota warning modified.|
|RENDERING_ENABLED|This operation is in Preview.	<br/>            Browser-enabled form templates will be rendered by InfoPath forms services.|
|REPORTING_ACCESSED|User accessed the reporting endpoint in Project Web App.|
|REPORTING_SETTING_MODIFIED|User modifies the reporting configuration in Project Web App.|
|RESOURCE_ACCESSED|User accesses an enterprise resource content in Project Web App.|
|RESOURCE_CHECKED_IN|User checks in an enterprise resource that they checked out from Project Web App.|
|RESOURCE_CHECKED_OUT|User checks out an enterprise resource located in Project Web App.|
|RESOURCE_CREATED|User creates an enterprise resource in Project Web App.|
|RESOURCE_DELETED|User deletes an enterprise resource in Project Web App.|
|RESOURCE_FORCE_CHECKED_IN|User forces a checkin of an enterprise resource in Project Web App.|
|RESOURCE_MODIFIED|User modifies an enterprise resource in Project Web App.|
|RESOURCE_PLAN_CHECKED_IN_OR_OUT|User checks in or out a resource plan in Project Web App.|
|RESOURCE_PLAN_MODIFIED|User modifies a resource plan in Project Web App.|
|RESOURCE_PLAN_PUBLISHED|User publishes a resource plan in Project Web App.|
|RESOURCE_REDACTED|User redacts an enterprise resource removing all personal information in Project Web App.|
|RESOURCE_WARNING_ENABLED_MODIFIED|This operation is in Preview.	<br/>            Resource quota warning modified.|
|SSO_GROUP_CREDENTIALS_SET|This operation is in Preview.	<br/>            Group credentials set in Secure store service.|
|SSO_USER_CREDENTIALS_SET|This operation is in Preview.	<br/>            User credentials set in Secure store service.|
|SEARCH_CENTER_URL_SET|This operation is in Preview.	<br/>            Search center URL set.|
|SECONDARY_MY_SITE_OWNER_SET|This operation is in Preview.	<br/>            A user has added a secondary owner to their MySite.|
|SECURITY_CATEGORY_MODIFIED|User creates, modifies or deletes a security category in Project Web App.|
|SECURITY_GROUP_MODIFIED|User creates, modifies or deletes a security group in Project Web App.|
|SEND_TO_CONNECTION_ADDED|This operation is in Preview.	<br/>            Global administrator creates a new Send To connection on the Records management page in the SharePoint admin center. <br/>            A Send To connection specifies settings for a document repository or a records center. <br/>            When you create a Send To connection, a Content Organizer can submit documents to the specified location.|
|SEND_TO_CONNECTION_REMOVED|This operation is in Preview.	<br/>            Global administrator deletes a Send To connection on the Records management page in the SharePoint admin center.|
|SHARED_LINK_CREATED|User creates a link to a shared file in SharePoint or OneDrive for Business. <br/>            This link can be sent to other people to give them access to the file. <br/>            A user can create two types of links: a link that allows a user to view and edit the shared file, or a link that allows the user to just view the file.|
|SHARED_LINK_DISABLED|This operation is in Preview.	<br/>            User disables (permanently) a link that was created to share a file.|
|SHARING_INVITATION_ACCEPTED|This operation is in Preview.	<br/>            User accepts an invitation to share a file or folder. This event is logged when a user shares a file with other users.|
|SHARING_REVOKED|This operation is in Preview.	<br/>            User unshares a file or folder that was previously shared with other users. This event is logged when a user stops sharing a file with other users.|
|SHARING_SET|User shares a file or folder located in SharePoint or OneDrive for Business with another user inside their organization.|
|SITE_ADMIN_CHANGE_REQUEST|This operation is in Preview.	<br/>            User requests to be added as a site collection administrator for a SharePoint site collection. <br/>            Site collection administrators have full control permissions for the site collection and all subsites.|
|SITE_COLLECTION_ADMIN_ADDED|This operation is in Preview.	<br/>            Site collection administrator or owner adds a person as a site collection administrator for a SharePoint or OneDrive for Business site. <br/>            Site collection administrators have full control permissions for the site collection and all subsites.|
|SITE_COLLECTION_CREATED|This operation is in Preview.	<br/>            Global administrator creates a new site collection in your SharePoint organization.|
|SITE_RENAMED|This operation is in Preview.	<br/>            Site administrator or owner renames a SharePoint or OneDrive for Business site|
|STATUS_REPORT_MODIFIED|User creates, modifies or deletes a status report in Project Web App.|
|SYNC_GET_CHANGES|This operation is in Preview.	<br/>            User clicks Sync in the action tray on in SharePoint or OneDrive for Business to synchronize any changes to file in a document library to their computer.|
|TASK_STATUS_ACCESSED|User accesses the status of one or more tasks in Project Web App.|
|TASK_STATUS_APPROVED|User approves a status update of one or more tasks in Project Web App.|
|TASK_STATUS_REJECTED|User rejects a status update of one or more tasks in Project Web App.|
|TASK_STATUS_SAVED|User saves a status update of one or more tasks in Project Web App.|
|TASK_STATUS_SUBMITTED|User submits a status update of one or more tasks in Project Web App.|
|TIMESHEET_ACCESSED|User accesses a timesheet in Project Web App.|
|TIMESHEET_APPROVED|User approves timesheet in Project Web App.|
|TIMESHEET_REJECTED|User rejects a timesheet in Project Web App.|
|TIMESHEET_SAVED|User saves a timesheet in Project Web App.|
|TIMESHEET_SUBMITTED|User submits a status timesheet in Project Web App.|
|UNMANAGED_SYNC_CLIENT_BLOCKED|User tries to establish a sync relationship with a SharePoint or OneDrive for Business site <br/>            from a computer that isn't a member of your organization's domain or is a member of a domain <br/>            that hasn't been added to the list of domains (called the safe recipients list) that can access document libraries in your organization. <br/>            The sync relationship is not allowed, and the user's computer is blocked from syncing, downloading, or uploading files on a document library. <br/>            For information about this feature, see Use Windows PowerShell cmdlets to enable OneDrive sync for domains that are on the safe recipients list.|
|UPDATE_SSO_APPLICATION|This operation is in Preview.	<br/>            Target application updated in Secure store service.|
|USER_ADDED_TO_GROUP|This operation is in Preview.	<br/>            Site administrator or owner adds a person to a group on a SharePoint or OneDrive for Business site. <br/>            Adding a person to a group grants the user the permissions that were assigned to the group.|
|USER_REMOVED_FROM_GROUP|This operation is in Preview.	<br/>            Site administrator or owner removes a person from a group on a SharePoint or OneDrive for Business site. <br/>            After the person is removed, they no longer are granted the permissions that were assigned to the group.|
|WORKFLOW_MODIFIED|User creates, modifies, or deletes an Enterprise Project Type or Workflow phases or stages in Project Web App.|

### See Also

* namespace [aspose.email.clients.activity](/python-net/aspose.email.clients.activity/)
* assembly [Aspose.Email](/python-net/)

