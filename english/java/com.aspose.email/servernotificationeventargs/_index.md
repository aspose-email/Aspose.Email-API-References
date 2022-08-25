---
title: ServerNotificationEventArgs
second_title: Aspose.Email for Java API Reference
description:  Contains event data for server notification.
type: docs
weight: 628
url: /java/com.aspose.email/servernotificationeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ServerNotificationEventArgs extends System.EventArgs
```

Contains event data for server notification.
## Constructors

| Constructor | Description |
| --- | --- |
| [ServerNotificationEventArgs(int folder, int eventTypes)](#ServerNotificationEventArgs-int-int-) | Initializes a new instance of the [ServerNotificationEventArgs](../../com.aspose.email/servernotificationeventargs) class |
## Methods

| Method | Description |
| --- | --- |
| [getFolder()](#getFolder--) | Specifies the known Exchange server folder. |
| [getEventTypes()](#getEventTypes--) | Specifies event type |
### ServerNotificationEventArgs(int folder, int eventTypes) {#ServerNotificationEventArgs-int-int-}
```
public ServerNotificationEventArgs(int folder, int eventTypes)
```


Initializes a new instance of the [ServerNotificationEventArgs](../../com.aspose.email/servernotificationeventargs) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | int | Specifies the known Exchange server folders. |
| eventTypes | int | Specifies event type |

### getFolder() {#getFolder--}
```
public final int getFolder()
```


Specifies the known Exchange server folder.

**Returns:**
int
### getEventTypes() {#getEventTypes--}
```
public final int getEventTypes()
```


Specifies event type

**Returns:**
int
