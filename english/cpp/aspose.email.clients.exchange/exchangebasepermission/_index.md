---
title: "Aspose::Email::Clients::Exchange::ExchangeBasePermission class"
linktitle: "ExchangeBasePermission"
articleTitle: "ExchangeBasePermission"
second_title: "Aspose.Email for C++"
description: "Provides abstract base class for permissions to folders on Exchange Server."
type: docs
weight: 10
url: /cpp/aspose.email.clients.exchange/exchangebasepermission/
---

## ExchangeBasePermission class

Provides abstract base class for permissions to folders on Exchange Server.

## Constructors

| Name | Description |
| --- | --- |
| [ExchangeBasePermission](./exchangebasepermission/) | Initializes a new instance of the ExchangeBasePermission class |

## Methods

| Name | Description |
| --- | --- |
| [get_CanCreateItems](./get_cancreateitems/) | Gets a value indicating whether a client can create items in a folder. |
| [get_CanCreateSubFolders](./get_cancreatesubfolders/) | Gets a value indicating whether the client can create subfolders. |
| [get_DeleteItems](./get_deleteitems/) | Gets a value indicating whether the client can delete items. |
| [get_EditItems](./get_edititems/) | Gets a value indicating whether a client can edit items. |
| [get_IsFolderContact](./get_isfoldercontact/) | Gets a value indicating whether a user is a contact for a folder. |
| [get_IsFolderOwner](./get_isfolderowner/) | Gets a value indicating whether the user is the owner of a folder. |
| [get_IsFolderVisible](./get_isfoldervisible/) | Gets a value indicating whether a user can view a folder. |
| [get_UserInfo](./get_userinfo/) | Gets a user or a delegate user who has folder access permissions |
| [set_CanCreateItems](./set_cancreateitems/) | Sets a value indicating whether a client can create items in a folder. |
| [set_CanCreateSubFolders](./set_cancreatesubfolders/) | Sets a value indicating whether the client can create subfolders. |
| [set_DeleteItems](./set_deleteitems/) | Sets a value indicating whether the client can delete items. |
| [set_EditItems](./set_edititems/) | Sets a value indicating whether a client can edit items. |
| [set_IsFolderContact](./set_isfoldercontact/) | Sets a value indicating whether a user is a contact for a folder. |
| [set_IsFolderOwner](./set_isfolderowner/) | Sets a value indicating whether the user is the owner of a folder. |
| [set_IsFolderVisible](./set_isfoldervisible/) | Sets a value indicating whether a user can view a folder. |
| [set_UserInfo](./set_userinfo/) | Sets a user or a delegate user who has folder access permissions |
| [ExchangeCalendarPermission](./exchangecalendarpermission/) |  |
| [ExchangeFolderPermission](./exchangefolderpermission/) |  |
| [permissionSet](./permissionset/) | Specifies a user permission level. The responsibility of bits: 0 - IsFolderVisible 1 - ReadItems 2 - CanCreateItems 3, 4 - DeleteItems 5, 6 - EditItems 7 - CanCreateSubFolders 8 - IsFolderContact 9 - IsFolderOwner 10 - FreeBusyTimeOnly 11 - FreeBusyTimeAndSubjectAndLocation |

