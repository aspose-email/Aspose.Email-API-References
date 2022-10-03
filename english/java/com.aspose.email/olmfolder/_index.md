---
title: OlmFolder
second_title: Aspose.Email for Java API Reference
description: Represents folder information in OLM storage.
type: docs
weight: 538
url: /java/com.aspose.email/olmfolder/
---
**Inheritance:**
java.lang.Object
```
public class OlmFolder
```

Represents folder information in OLM storage.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the folder name. |
| [getSubFolders()](#getSubFolders--) | Gets the list of sub-folders. |
| [hasMessages()](#hasMessages--) | Gets a value indicating whether the current folder has messages. |
| [getMessageCount()](#getMessageCount--) | Gets the message count. |
| [getPath()](#getPath--) | Gets the path. |
| [getSubFolder(String subfolderName, boolean ignoreCase)](#getSubFolder-java.lang.String-boolean-) | Gets the subfolder by name. |
| [enumerateMapiMessages()](#enumerateMapiMessages--) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [enumerateMessages()](#enumerateMessages--) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [enumerateMessages(int startIndex, int count)](#enumerateMessages-int-int-) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [enumerateMessages(MailQuery query)](#enumerateMessages-com.aspose.email.MailQuery-) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [toString()](#toString--) | Returns a String that represents this instance. |
### getName() {#getName--}
```
public final String getName()
```


Gets the folder name.

Value: The name.

**Returns:**
java.lang.String
### getSubFolders() {#getSubFolders--}
```
public final List<OlmFolder> getSubFolders()
```


Gets the list of sub-folders.

Value: The list of sub-folders.

**Returns:**
java.util.List<com.aspose.email.OlmFolder>
### hasMessages() {#hasMessages--}
```
public final boolean hasMessages()
```


Gets a value indicating whether the current folder has messages.

**Returns:**
boolean - true if the current folder has messages; otherwise, false.
### getMessageCount() {#getMessageCount--}
```
public final int getMessageCount()
```


Gets the message count.

Value: The message count.

**Returns:**
int
### getPath() {#getPath--}
```
public final String getPath()
```


Gets the path.

Value: The folder path.

**Returns:**
java.lang.String
### getSubFolder(String subfolderName, boolean ignoreCase) {#getSubFolder-java.lang.String-boolean-}
```
public final OlmFolder getSubFolder(String subfolderName, boolean ignoreCase)
```


Gets the subfolder by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subfolderName | java.lang.String | Name of subfolder. |
| ignoreCase | boolean | A value that indicates whether the name to match is case insensitive. |

**Returns:**
[OlmFolder](../../com.aspose.email/olmfolder) - An OlmFolder object.
### enumerateMapiMessages() {#enumerateMapiMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MapiMessage> enumerateMapiMessages()
```


Exposes the enumerator, which supports an iteration of messages in folder.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MapiMessage> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in folder.
### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<OlmMessageInfo> enumerateMessages()
```


Exposes the enumerator, which supports an iteration of messages in folder.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.OlmMessageInfo> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in folder.
### enumerateMessages(int startIndex, int count) {#enumerateMessages-int-int-}
```
public final System.Collections.Generic.IGenericEnumerable<OlmMessageInfo> enumerateMessages(int startIndex, int count)
```


Exposes the enumerator, which supports an iteration of messages in folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | The start message index. |
| count | int | The number of messages that will be retrieved.

--------------------

If "count" param is less than 0 or more than remained message count then remained message count will be returned. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.OlmMessageInfo> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in folder.
### enumerateMessages(MailQuery query) {#enumerateMessages-com.aspose.email.MailQuery-}
```
public final System.Collections.Generic.IGenericEnumerable<OlmMessageInfo> enumerateMessages(MailQuery query)
```


Exposes the enumerator, which supports an iteration of messages in folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents search query. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.OlmMessageInfo> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in folder.
### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
