---
title: Interface IGraphClientAsync
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Graph.IGraphClientAsync interface. Represents the interface with asynchronous operations for GraphClient
type: docs
weight: 14690
url: /net/aspose.email.clients.graph/igraphclientasync/
---
## IGraphClientAsync interface

Represents the interface with asynchronous operations for GraphClient.

```csharp
public interface IGraphClientAsync : IGraphClient
```

## Methods

| Name | Description |
| --- | --- |
| [CopyFolderAsync](../../aspose.email.clients.graph/igraphclientasync/copyfolderasync/)(string, string, CancellationToken) | Asynchronously copies a mailfolder and its contents to another mailfolder. |
| [CopyMessageAsync](../../aspose.email.clients.graph/igraphclientasync/copymessageasync/)(string, string, CancellationToken) | Asynchronously copies a message to a new parent folder. |
| [CopyNotebookAsync](../../aspose.email.clients.graph/igraphclientasync/copynotebookasync/)(string, string, string, CancellationToken) | Asynchronously copies a notebook. |
| [CreateAttachmentAsync](../../aspose.email.clients.graph/igraphclientasync/createattachmentasync/)(string, MapiAttachment, CancellationToken) | Asynchronously creates an attachment in the specified parent item. |
| [CreateCalendarItemAsync](../../aspose.email.clients.graph/igraphclientasync/createcalendaritemasync/)(string, MapiCalendar, CancellationToken) | Asynchronously creates MapiCalendar in specified calendar. |
| [CreateCategoryAsync](../../aspose.email.clients.graph/igraphclientasync/createcategoryasync/)(string, CategoryPreset, CancellationToken) | Asynchronously creates a new Outlook category. |
| [CreateContactAsync](../../aspose.email.clients.graph/igraphclientasync/createcontactasync/)(string, MapiContact, CancellationToken) | Asynchronously creates a contact in the specified folder. |
| [CreateFolderAsync](../../aspose.email.clients.graph/igraphclientasync/createfolderasync/#createfolderasync_1)(string, CancellationToken) | Asynchronously creates a new folder. |
| [CreateFolderAsync](../../aspose.email.clients.graph/igraphclientasync/createfolderasync/#createfolderasync)(string, string, CancellationToken) | Asynchronously creates a new folder under a parent folder. |
| [CreateMessageAsync](../../aspose.email.clients.graph/igraphclientasync/createmessageasync/#createmessageasync)(string, MailMessage, CancellationToken) | Asynchronously creates a mail message in the specified folder. |
| [CreateMessageAsync](../../aspose.email.clients.graph/igraphclientasync/createmessageasync/#createmessageasync_1)(string, MapiMessage, CancellationToken) | Asynchronously creates a message in the specified folder. |
| [CreateNotebookAsync](../../aspose.email.clients.graph/igraphclientasync/createnotebookasync/)(Notebook, CancellationToken) | Asynchronously creates a notebook. |
| [CreateOrUpdateOverrideAsync](../../aspose.email.clients.graph/igraphclientasync/createorupdateoverrideasync/#createorupdateoverrideasync)(ClassificationOverride, CancellationToken) | Asynchronously creates or updates a classification override. |
| [CreateOrUpdateOverrideAsync](../../aspose.email.clients.graph/igraphclientasync/createorupdateoverrideasync/#createorupdateoverrideasync_1)(MailAddress, ClassificationType, CancellationToken) | Asynchronously creates or updates a classification override for a sender. |
| [CreateRuleAsync](../../aspose.email.clients.graph/igraphclientasync/createruleasync/)(InboxRule, CancellationToken) | Asynchronously creates an inbox rule. |
| [CreateTaskAsync](../../aspose.email.clients.graph/igraphclientasync/createtaskasync/)(MapiTask, string, CancellationToken) | Asynchronously creates a task in the specified task list. |
| [CreateTaskListAsync](../../aspose.email.clients.graph/igraphclientasync/createtasklistasync/)(TaskListInfo, CancellationToken) | Asynchronously creates a task list. |
| [DeleteAsync](../../aspose.email.clients.graph/igraphclientasync/deleteasync/)(string, CancellationToken) | Asynchronously deletes an object by its ID. |
| [DeleteAttachmentAsync](../../aspose.email.clients.graph/igraphclientasync/deleteattachmentasync/)(string, CancellationToken) | Asynchronously deletes an attachment by its ID. |
| [DeleteTaskListAsync](../../aspose.email.clients.graph/igraphclientasync/deletetasklistasync/)(string, CancellationToken) | Asynchronously deletes a task list by its ID. |
| [FetchAttachmentAsync](../../aspose.email.clients.graph/igraphclientasync/fetchattachmentasync/)(string, CancellationToken) | Asynchronously fetches an attachment by its ID. |
| [FetchCalendarItemAsync](../../aspose.email.clients.graph/igraphclientasync/fetchcalendaritemasync/)(string, CancellationToken) | Asynchronously gets MapiCalendar for specified id. |
| [FetchCategoryAsync](../../aspose.email.clients.graph/igraphclientasync/fetchcategoryasync/)(string, CancellationToken) | Asynchronously fetches an Outlook category by its ID. |
| [FetchContactAsync](../../aspose.email.clients.graph/igraphclientasync/fetchcontactasync/)(string, CancellationToken) | Asynchronously gets MapiContact for specified id. |
| [FetchMessageAsync](../../aspose.email.clients.graph/igraphclientasync/fetchmessageasync/)(string, CancellationToken) | Asynchronously fetches a message by its ID. |
| [FetchNotebookAsync](../../aspose.email.clients.graph/igraphclientasync/fetchnotebookasync/)(string, CancellationToken) | Asynchronously fetches a notebook by its ID. |
| [FetchRuleAsync](../../aspose.email.clients.graph/igraphclientasync/fetchruleasync/)(string, CancellationToken) | Asynchronously fetches an inbox rule by its ID. |
| [FetchTaskAsync](../../aspose.email.clients.graph/igraphclientasync/fetchtaskasync/)(string, CancellationToken) | Asynchronously fetches a task by its ID. |
| [GetContactFolderAsync](../../aspose.email.clients.graph/igraphclientasync/getcontactfolderasync/)(CancellationToken) | Gets main contact folder. This method requires that at least one contact exists in the main contacts folder, otherwise it will return null. https://learn.microsoft.com/en-us/answers/questions/854621/how-to-get-folder-id-of-default-contacts-folder-wh |
| [GetFolderAsync](../../aspose.email.clients.graph/igraphclientasync/getfolderasync/)(string, CancellationToken) | Asynchronously gets a folder by its ID. |
| [GetOneNoteOperationStatusAsync](../../aspose.email.clients.graph/igraphclientasync/getonenoteoperationstatusasync/)(string, CancellationToken) | Asynchronously gets the status of a OneNote operation. |
| [GetTaskListAsync](../../aspose.email.clients.graph/igraphclientasync/gettasklistasync/)(string, CancellationToken) | Asynchronously fetches a task list by its ID. |
| [ListAttachmentsAsync](../../aspose.email.clients.graph/igraphclientasync/listattachmentsasync/)(string, ODataQueryBuilder, CancellationToken) | Asynchronously lists attachments for the specified item. |
| [ListCalendarItemsAsync](../../aspose.email.clients.graph/igraphclientasync/listcalendaritemsasync/)(string, ODataQueryBuilder, CancellationToken) | Asynchronously lists MapiCalendar items from the calendar. |
| [ListCalendarsAsync](../../aspose.email.clients.graph/igraphclientasync/listcalendarsasync/)(ODataQueryBuilder, CancellationToken) | Asynchronously lists CalendarInfo items. |
| [ListCategoriesAsync](../../aspose.email.clients.graph/igraphclientasync/listcategoriesasync/)(ODataQueryBuilder, CancellationToken) | Asynchronously lists Outlook categories. |
| [ListContactFoldersAsync](../../aspose.email.clients.graph/igraphclientasync/listcontactfoldersasync/)(ODataQueryBuilder, CancellationToken) | Asynchronously gets a collection of child folders under the root contact folder. |
| [ListContactsAsync](../../aspose.email.clients.graph/igraphclientasync/listcontactsasync/)(string, ODataQueryBuilder, CancellationToken) | Asynchronously lists MapiContact from the parent folder. |
| [ListFoldersAsync](../../aspose.email.clients.graph/igraphclientasync/listfoldersasync/#listfoldersasync)(ODataQueryBuilder, CancellationToken) | Asynchronously lists folders from the root folder. |
| [ListFoldersAsync](../../aspose.email.clients.graph/igraphclientasync/listfoldersasync/#listfoldersasync_1)(string, ODataQueryBuilder, CancellationToken) | Asynchronously lists folders from the parent folder. |
| [ListMessagesAsync](../../aspose.email.clients.graph/igraphclientasync/listmessagesasync/#listmessagesasync_1)(string, ODataQueryBuilder, CancellationToken) | Asynchronously lists MessageInfo from the parent folder. |
| [ListMessagesAsync](../../aspose.email.clients.graph/igraphclientasync/listmessagesasync/#listmessagesasync)(string, PageInfo, MailQuery, CancellationToken) | Asynchronously lists MessageInfo from the parent folder with paging and query. |
| [ListNotebooksAsync](../../aspose.email.clients.graph/igraphclientasync/listnotebooksasync/)(ODataQueryBuilder, CancellationToken) | Asynchronously lists notebooks. |
| [ListOverridesAsync](../../aspose.email.clients.graph/igraphclientasync/listoverridesasync/)(ODataQueryBuilder, CancellationToken) | Asynchronously lists classification overrides. |
| [ListRecentNotebooksAsync](../../aspose.email.clients.graph/igraphclientasync/listrecentnotebooksasync/)(bool, ODataQueryBuilder, CancellationToken) | Asynchronously lists recent notebooks. |
| [ListRulesAsync](../../aspose.email.clients.graph/igraphclientasync/listrulesasync/)(ODataQueryBuilder, CancellationToken) | Asynchronously lists inbox rules. |
| [ListTaskListsAsync](../../aspose.email.clients.graph/igraphclientasync/listtasklistsasync/)(ODataQueryBuilder, CancellationToken) | Asynchronously lists task lists. |
| [ListTasksAsync](../../aspose.email.clients.graph/igraphclientasync/listtasksasync/)(string, ODataQueryBuilder, CancellationToken) | Asynchronously lists tasks in the specified task list. |
| [MoveFolderAsync](../../aspose.email.clients.graph/igraphclientasync/movefolderasync/)(string, string, CancellationToken) | Asynchronously moves a mailfolder and its contents to another mailfolder. |
| [MoveMessageAsync](../../aspose.email.clients.graph/igraphclientasync/movemessageasync/)(string, string, CancellationToken) | Asynchronously moves a message to a new parent folder. |
| [SendAsMimeAsync](../../aspose.email.clients.graph/igraphclientasync/sendasmimeasync/)(MapiMessage, CancellationToken) | Asynchronously sends a [`MapiMessage`](../../aspose.email.mapi/mapimessage/) as MIME. |
| [SendAsync](../../aspose.email.clients.graph/igraphclientasync/sendasync/#sendasync)(MailMessage, CancellationToken) | Asynchronously sends a [`MailMessage`](../../aspose.email/mailmessage/). |
| [SendAsync](../../aspose.email.clients.graph/igraphclientasync/sendasync/#sendasync_2)(MapiMessage, CancellationToken) | Asynchronously sends a [`MapiMessage`](../../aspose.email.mapi/mapimessage/). |
| [SendAsync](../../aspose.email.clients.graph/igraphclientasync/sendasync/#sendasync_3)(string, CancellationToken) | Asynchronously sends a draft message by its ID. |
| [SendAsync](../../aspose.email.clients.graph/igraphclientasync/sendasync/#sendasync_1)(MapiMessage, bool, CancellationToken) | Asynchronously sends a [`MapiMessage`](../../aspose.email.mapi/mapimessage/) with an option to save to Sent Items. |
| [SetReadAsync](../../aspose.email.clients.graph/igraphclientasync/setreadasync/)(string, CancellationToken) | Asynchronously sets a message as read by its ID. |
| [UpdateCalendarItemAsync](../../aspose.email.clients.graph/igraphclientasync/updatecalendaritemasync/#updatecalendaritemasync_1)(MapiCalendar, CancellationToken) | Asynchronously creates MapiCalendar in specified calendar. |
| [UpdateCalendarItemAsync](../../aspose.email.clients.graph/igraphclientasync/updatecalendaritemasync/#updatecalendaritemasync)(MapiCalendar, UpdateSettings, CancellationToken) | Asynchronously updates MapiCalendar. |
| [UpdateCategoryAsync](../../aspose.email.clients.graph/igraphclientasync/updatecategoryasync/)(OutlookCategory, CancellationToken) | Asynchronously updates an Outlook category. |
| [UpdateContactAsync](../../aspose.email.clients.graph/igraphclientasync/updatecontactasync/)(MapiContact, CancellationToken) | Asynchronously updates a contact. |
| [UpdateFolderAsync](../../aspose.email.clients.graph/igraphclientasync/updatefolderasync/)(FolderInfo, CancellationToken) | Asynchronously updates a folder. |
| [UpdateMessageAsync](../../aspose.email.clients.graph/igraphclientasync/updatemessageasync/#updatemessageasync_1)(MailMessage, CancellationToken) | Asynchronously updates a mail message. |
| [UpdateMessageAsync](../../aspose.email.clients.graph/igraphclientasync/updatemessageasync/#updatemessageasync_3)(MapiMessage, CancellationToken) | Asynchronously updates a message. |
| [UpdateMessageAsync](../../aspose.email.clients.graph/igraphclientasync/updatemessageasync/#updatemessageasync)(MailMessage, UpdateSettings, CancellationToken) | Asynchronously updates a mail message with optional update settings. |
| [UpdateMessageAsync](../../aspose.email.clients.graph/igraphclientasync/updatemessageasync/#updatemessageasync_2)(MapiMessage, UpdateSettings, CancellationToken) | Asynchronously updates a message with optional update settings. |
| [UpdateOverrideAsync](../../aspose.email.clients.graph/igraphclientasync/updateoverrideasync/)(ClassificationOverride, CancellationToken) | Asynchronously updates a classification override. |
| [UpdateRuleAsync](../../aspose.email.clients.graph/igraphclientasync/updateruleasync/)(InboxRule, CancellationToken) | Asynchronously updates an inbox rule. |
| [UpdateTaskAsync](../../aspose.email.clients.graph/igraphclientasync/updatetaskasync/#updatetaskasync_1)(MapiTask, CancellationToken) | Asynchronously updates a task. |
| [UpdateTaskAsync](../../aspose.email.clients.graph/igraphclientasync/updatetaskasync/#updatetaskasync)(MapiTask, UpdateSettings, CancellationToken) | Asynchronously updates a task with optional update settings. |
| [UpdateTaskListAsync](../../aspose.email.clients.graph/igraphclientasync/updatetasklistasync/)(TaskListInfo, CancellationToken) | Asynchronously updates a task list. |

### See Also

* interface [IGraphClient](../igraphclient/)
* namespace [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph/)
* assembly [Aspose.Email](../../)


