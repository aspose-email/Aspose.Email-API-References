---
title: ExchangeCalendarPermissionLevel
second_title: Aspose.Email for Java API Reference
description:  Specifies the permission level that a user has on a calendar folder.
type: docs
weight: 193
url: /java/com.aspose.email/exchangecalendarpermissionlevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExchangeCalendarPermissionLevel extends System.Enum
```

Specifies the permission level that a user has on a calendar folder.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | The user has no permissions on the folder. |
| [Owner](#Owner) | The user can create, read, edit, and delete all items in the folder and create subfolders. |
| [PublishingEditor](#PublishingEditor) | The user can create, read, edit, and delete all items in the folder, and create subfolders. |
| [Editor](#Editor) | The user can create, read, edit, and delete all items in the folder. |
| [PublishingAuthor](#PublishingAuthor) | The user can create and read all items in the folder, edit and delete only items that the user creates, and create subfolders. |
| [Author](#Author) | The user can create and read all items in the folder, and edit and delete only items that the user creates. |
| [NoneditingAuthor](#NoneditingAuthor) | The user can create and read all items in the folder, and delete only items that the user creates. |
| [Reviewer](#Reviewer) | The user can read all items in the folder. |
| [Contributor](#Contributor) | The user can create items in the folder. |
| [FreeBusyTimeOnly](#FreeBusyTimeOnly) | The user can view only free/busy time within the calendar. |
| [FreeBusyTimeAndSubjectAndLocation](#FreeBusyTimeAndSubjectAndLocation) | The user can view free/busy time within the calendar and the subject and location of appointments. |
| [Custom](#Custom) | The user has custom access permissions on the folder. |
### None {#None}
```
public static final int None
```


The user has no permissions on the folder.

### Owner {#Owner}
```
public static final int Owner
```


The user can create, read, edit, and delete all items in the folder and create subfolders. The user is both folder owner and folder contact.

### PublishingEditor {#PublishingEditor}
```
public static final int PublishingEditor
```


The user can create, read, edit, and delete all items in the folder, and create subfolders.

### Editor {#Editor}
```
public static final int Editor
```


The user can create, read, edit, and delete all items in the folder.

### PublishingAuthor {#PublishingAuthor}
```
public static final int PublishingAuthor
```


The user can create and read all items in the folder, edit and delete only items that the user creates, and create subfolders.

### Author {#Author}
```
public static final int Author
```


The user can create and read all items in the folder, and edit and delete only items that the user creates.

### NoneditingAuthor {#NoneditingAuthor}
```
public static final int NoneditingAuthor
```


The user can create and read all items in the folder, and delete only items that the user creates.

### Reviewer {#Reviewer}
```
public static final int Reviewer
```


The user can read all items in the folder.

### Contributor {#Contributor}
```
public static final int Contributor
```


The user can create items in the folder. The contents of the folder do not appear.

### FreeBusyTimeOnly {#FreeBusyTimeOnly}
```
public static final int FreeBusyTimeOnly
```


The user can view only free/busy time within the calendar.

### FreeBusyTimeAndSubjectAndLocation {#FreeBusyTimeAndSubjectAndLocation}
```
public static final int FreeBusyTimeAndSubjectAndLocation
```


The user can view free/busy time within the calendar and the subject and location of appointments.

### Custom {#Custom}
```
public static final int Custom
```


The user has custom access permissions on the folder.

