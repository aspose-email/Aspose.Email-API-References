---
title: Enum ExchangeFolderPermissionLevel
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.ExchangeFolderPermissionLevel enum. Specifies the permission level that a user has on a folder
type: docs
weight: 3320
url: /net/aspose.email.clients.exchange/exchangefolderpermissionlevel/
---
## ExchangeFolderPermissionLevel enumeration

Specifies the permission level that a user has on a folder.

```csharp
public enum ExchangeFolderPermissionLevel
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | The user has no permissions on the folder. |
| Owner | `983` | The user can create, read, edit, and delete all items in the folder and create subfolders. The user is both folder owner and folder contact. |
| PublishingEditor | `215` | The user can create, read, edit, and delete all items in the folder, and create subfolders. |
| Editor | `87` | The user can create, read, edit, and delete all items in the folder. |
| PublishingAuthor | `175` | The user can create and read all items in the folder, edit and delete only items that the user creates, and create subfolders. |
| Author | `47` | The user can create and read all items in the folder, and edit and delete only items that the user creates. |
| NoneditingAuthor | `15` | The user can create and read all items in the folder, and delete only items that the user creates. |
| Reviewer | `3` | The user can read all items in the folder. |
| Contributor | `5` | The user can create items in the folder. The contents of the folder do not appear. |
| Custom | `1073741824` | The user has custom access permissions on the folder. |

### See Also

* namespace [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange/)
* assembly [Aspose.Email](../../)


