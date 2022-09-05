---
title: MessageAddedEventArgs
second_title: Aspose.Email for Java API Reference
description:  Provides data for the  event
type: docs
weight: 486
url: /java/com.aspose.email/messageaddedeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class MessageAddedEventArgs extends System.EventArgs
```

Provides data for the [FolderInfo\#MessageAddedDelegate](../../com.aspose.email/folderinfo\#MessageAddedDelegate) event
## Constructors

| Constructor | Description |
| --- | --- |
| [MessageAddedEventArgs(String entryId, MapiMessage message)](#MessageAddedEventArgs-java.lang.String-com.aspose.email.MapiMessage-) | Initializes a new instance of the [MessageAddedEventArgs](../../com.aspose.email/messageaddedeventargs) class. |
## Methods

| Method | Description |
| --- | --- |
| [getMessage()](#getMessage--) | Gets the message that has been added. |
| [getEntryId()](#getEntryId--) | Gets the string that represents the EntryId of the added message. |
### MessageAddedEventArgs(String entryId, MapiMessage message) {#MessageAddedEventArgs-java.lang.String-com.aspose.email.MapiMessage-}
```
public MessageAddedEventArgs(String entryId, MapiMessage message)
```


Initializes a new instance of the [MessageAddedEventArgs](../../com.aspose.email/messageaddedeventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry id. |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The message. |

### getMessage() {#getMessage--}
```
public final MapiMessage getMessage()
```


Gets the message that has been added.

Value: The message.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage)
### getEntryId() {#getEntryId--}
```
public final String getEntryId()
```


Gets the string that represents the EntryId of the added message.

Value: The entry id.

**Returns:**
java.lang.String
