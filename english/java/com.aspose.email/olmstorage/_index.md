---
title: OlmStorage
second_title: Aspose.Email for Java API Reference
description: Represents Outlook for Mac storage .OLM file.
type: docs
weight: 540
url: /java/com.aspose.email/olmstorage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class OlmStorage implements System.IDisposable, Closeable
```

Represents Outlook for Mac storage (.OLM) file.
## Constructors

| Constructor | Description |
| --- | --- |
| [OlmStorage(TraversalExceptionsCallback callback)](#OlmStorage-com.aspose.email.TraversalExceptionsCallback-) | Initializes a new instance of the [OlmStorage](../../com.aspose.email/olmstorage) class. |
| [OlmStorage(String fileName)](#OlmStorage-java.lang.String-) | Initializes a new instance of the [OlmStorage](../../com.aspose.email/olmstorage) class. |
| [OlmStorage(InputStream stream)](#OlmStorage-java.io.InputStream-) | Initializes a new instance of the [OlmStorage](../../com.aspose.email/olmstorage) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFolderHierarchy()](#getFolderHierarchy--) | Gets the folder hierarchy. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Load OLM storage from stream. |
| [load(String fileName)](#load-java.lang.String-) | Load OLM storage from file. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Load OLM storage from file. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Load OLM from stream. |
| [getFolders()](#getFolders--) | Gets collection of folders. |
| [getFolder(String name, boolean ignoreCase)](#getFolder-java.lang.String-boolean-) | Gets the folder by name. |
| [extractMapiMessage(OlmMessageInfo messageInfo)](#extractMapiMessage-com.aspose.email.OlmMessageInfo-) | Get the message from OLM storage. |
| [enumerateMessages(OlmFolder folder)](#enumerateMessages-com.aspose.email.OlmFolder-) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [close()](#close--) |  |
### OlmStorage(TraversalExceptionsCallback callback) {#OlmStorage-com.aspose.email.TraversalExceptionsCallback-}
```
public OlmStorage(TraversalExceptionsCallback callback)
```


Initializes a new instance of the [OlmStorage](../../com.aspose.email/olmstorage) class. Allows setting a callback method for handling exceptions that occur during OLM storage traversal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [TraversalExceptionsCallback](../../com.aspose.email/traversalexceptionscallback) | The exception callback. |

### OlmStorage(String fileName) {#OlmStorage-java.lang.String-}
```
public OlmStorage(String fileName)
```


Initializes a new instance of the [OlmStorage](../../com.aspose.email/olmstorage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | OLM file name. |

### OlmStorage(InputStream stream) {#OlmStorage-java.io.InputStream-}
```
public OlmStorage(InputStream stream)
```


Initializes a new instance of the [OlmStorage](../../com.aspose.email/olmstorage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source stream java.io.InputStream with OLM storage data. |

### getFolderHierarchy() {#getFolderHierarchy--}
```
public final List<OlmFolder> getFolderHierarchy()
```


Gets the folder hierarchy.

Value: The folder hierarchy.

**Returns:**
java.util.List<com.aspose.email.OlmFolder>
### load(InputStream stream) {#load-java.io.InputStream-}
```
public final boolean load(InputStream stream)
```


Load OLM storage from stream. This method is used when a OlmStorage object is created using constructor with the TraversalExceptionsCallback parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |

**Returns:**
boolean - 'true' if the file has been loaded successfully and further traversal is possible; otherwise, false.
### load(String fileName) {#load-java.lang.String-}
```
public final boolean load(String fileName)
```


Load OLM storage from file. This method is used when a OlmStorage object is created using constructor with the TraversalExceptionsCallback parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |

**Returns:**
boolean - 'true' if the file has been loaded successfully and further traversal is possible; otherwise, false.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static OlmStorage fromFile(String fileName)
```


Load OLM storage from file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of .olm file. |

**Returns:**
[OlmStorage](../../com.aspose.email/olmstorage) - An OlmStorage object that represents the current OLM file.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static OlmStorage fromStream(InputStream stream)
```


Load OLM from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The System.IO.Stream. |

**Returns:**
[OlmStorage](../../com.aspose.email/olmstorage) - An OlmStorage object that represents the current OLM storage.
### getFolders() {#getFolders--}
```
public final List<OlmFolder> getFolders()
```


Gets collection of folders.

**Returns:**
java.util.List<com.aspose.email.OlmFolder> - The collection of folders that belong to the storage, i.e. the sub-folders of the current OLMStorage object.
### getFolder(String name, boolean ignoreCase) {#getFolder-java.lang.String-boolean-}
```
public final OlmFolder getFolder(String name, boolean ignoreCase)
```


Gets the folder by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of folder. |
| ignoreCase | boolean | A value that indicates whether the name to match is case insensitive. |

**Returns:**
[OlmFolder](../../com.aspose.email/olmfolder) - An OlmFolder object.
### extractMapiMessage(OlmMessageInfo messageInfo) {#extractMapiMessage-com.aspose.email.OlmMessageInfo-}
```
public final MapiMessage extractMapiMessage(OlmMessageInfo messageInfo)
```


Get the message from OLM storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfo | [OlmMessageInfo](../../com.aspose.email/olmmessageinfo) | An OlmMessageInfo object that represents information about message. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### enumerateMessages(OlmFolder folder) {#enumerateMessages-com.aspose.email.OlmFolder-}
```
public final System.Collections.Generic.IGenericEnumerable<MapiMessage> enumerateMessages(OlmFolder folder)
```


Exposes the enumerator, which supports an iteration of messages in folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | [OlmFolder](../../com.aspose.email/olmfolder) | [OlmFolder](../../com.aspose.email/olmfolder) that represents information about folder in OLM storage. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MapiMessage> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in folder.
### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### close() {#close--}
```
public void close()
```




