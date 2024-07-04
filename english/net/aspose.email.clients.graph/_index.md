---
title: Aspose.Email.Clients.Graph
second_title: Aspose.Email for .NET API Reference
description: The Aspose.Email.Clients.Graph namespace provides classes for access to access to Microsoft 365 services by using REST API
type: docs
weight: 210
url: /net/aspose.email.clients.graph/
---
The **Aspose.Email.Clients.Graph** namespace provides classes for access to access to Microsoft 365 services by using REST API.

## Classes

| Class | Description |
| --- | --- |
| [BaseRestObject](./baserestobject/) | Represents functionality for base object. |
| [Bucket](./bucket/) | https://docs.microsoft.com/en-us/graph/api/resources/plannerbucket?view=graph-rest-1.0 The plannerBucket resource represents a bucket (or "custom column") for tasks in a plan in Office 365. It is contained in a plannerPlan and can have a collection of plannerTasks. |
| [CalendarInfo](./calendarinfo/) | Represents information about calendar. |
| [CalendarInfoCollection](./calendarinfocollection/) | Represents collection of GraphCalendarInfo. |
| [ClassificationOverride](./classificationoverride/) | Represents a user's override for how incoming messages from a specific sender should always be classified as. |
| [FolderInfo](./folderinfo/) | Represents information about personal folder. |
| [FolderInfoCollection](./folderinfocollection/) | Represents collection of GraphFolderInfo. |
| [GraphClient](./graphclient/) | Provides access to MS Exchange Server (Office365) by using REST API. |
| [GraphMessagePageInfo](./graphmessagepageinfo/) | Contains information about retrieved page when paging methods are used. |
| [GraphQueryBuilder](./graphquerybuilder/) | Represents the builder of search expression based on search filters that used by MS Graph protocol. |
| [Identity](./identity/) | https://docs.microsoft.com/en-us/graph/api/resources/identity?view=graph-rest-1.0 The Identity resource represents an identity of an actor. For example, an actor can be a user, device, or application. |
| [IdentitySet](./identityset/) | https://docs.microsoft.com/en-us/graph/api/resources/identityset?view=graph-rest-1.0 The IdentitySet resource is a keyed collection of identity resources. It is used to represent a set of identities associated with various events for an item, such as created by or last modified by. |
| [KnownFolders](./knownfolders/) | Well-known folders |
| [MessageInfo](./messageinfo/) | The MessageInfo represents the server item info fetched from the Graph service. |
| [MessageInfoCollection](./messageinfocollection/) | Represents collection of GraphMessageInfo. |
| [Notebook](./notebook/) | https://docs.microsoft.com/en-us/graph/api/resources/notebook?view=graph-rest-1.0 A OneNote notebook. |
| [NotebookCollection](./notebookcollection/) | Represents collection of Notebook. |
| [NotebookLinks](./notebooklinks/) | https://docs.microsoft.com/en-us/graph/api/resources/notebooklinks?view=graph-rest-1.0 Links for opening a OneNote notebook. |
| [OnenoteOperation](./onenoteoperation/) | The status of certain long-running OneNote operations. |
| [OutlookCategory](./outlookcategory/) | Represents a category by which a user can group Outlook items such as messages and events. The user defines categories in a master list, and can apply one or more of these user-defined categories to an item. https://docs.microsoft.com/en-us/graph/api/resources/outlookcategory?view=graph-rest-1.0 |
| [TaskListInfo](./tasklistinfo/) | Represents information about TaskList. |
| [TaskListInfoCollection](./tasklistinfocollection/) | Represents collection of TaskListInfo. |
| [Thumbnail](./thumbnail/) | https://docs.microsoft.com/en-us/graph/api/resources/thumbnail?view=graph-rest-1.0 The thumbnail resource type represents a thumbnail for an image, video, document, or any item that has a bitmap representation. |
| [ThumbnailSet](./thumbnailset/) | https://docs.microsoft.com/en-us/graph/api/resources/thumbnailset?view=graph-rest-1.0 The ThumbnailSet resource is a keyed collection of thumbnail resources. It is used to represent a set of thumbnails associated with a DriveItem. |
| [UpdateSettings](./updatesettings/) | Update settings |
## Interfaces

| Interface | Description |
| --- | --- |
| [IGraphClient](./igraphclient/) | Represents the interface for Exchange REST client. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [CalendarColor](./calendarcolor/) | Enumerates the color theme to distinguish the calendar from other calendars in a UI. The property values are: auto, lightBlue, lightGreen, lightOrange, lightGray, lightYellow, lightTeal, lightPink, lightBrown, lightRed, maxColor. |
| [CalendarRoleType](./calendarroletype/) | Represent sharing or delegating permission levels for the calendar. |
| [CategoryPreset](./categorypreset/) | A pre-set color enumeration that characterizes a categories, and that is mapped to one of 25 predefined colors. Note The possible values for color are pre-set constants such as None, preset0 and preset1. Each pre-set constant is further mapped to a color; the actual color is dependent on the Outlook client that the categories are being displayed in. |
| [ClassificationType](./classificationtype/) | https://docs.microsoft.com/en-us/graph/api/resources/enums?view=graph-rest-1.0 https://docs.microsoft.com/en-us/graph/api/resources/inferenceclassificationoverride?view=graph-rest-1.0 Specifies how incoming messages from a specific sender should always be classified as. |
| [OnlineMeetingProvider](./onlinemeetingprovider/) | The default online meeting provider for meetings sent from this calendar. Possible values are: unknown, skypeForBusiness, skypeForConsumer, teamsForBusiness. |
| [ResourceType](./resourcetype/) | The resource in Microsoft Graph that you're referencing. |
| [UserRole](./userrole/) | OneNote user role |
| [WellknownTaskListName](./wellknowntasklistname/) | Property indicating the list name if the given list is a well-known list. Possible values are: none, defaultList, flaggedEmails, unknownFutureValue. |


