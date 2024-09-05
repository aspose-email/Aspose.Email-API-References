---
title: OlmStorage
second_title: Aspose.Email for Java API Reference
description: Represents an Outlook for Mac .OLM storage file and provides functionality to access and manipulate the data within the file such as emails contacts calendars tasks and notes.
type: docs
weight: 561
url: /java/com.aspose.email/olmstorage/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class OlmStorage implements System.IDisposable, Closeable
```

Represents an Outlook for Mac (.OLM) storage file and provides functionality to access and manipulate the data within the file such as emails, contacts, calendars, tasks, and notes.

The OlmStorage class allows users to read from and interact with the contents of .OLM files typically used by Microsoft Outlook for Mac. This class handles the various data types stored within an .OLM file by providing methods to enumerate and extract information.

Example:

```

 try (OlmStorage olm = OlmStorage.fromFile("storage.olm")) {
     // Retrieve the total number of items in the OLM storage.
     int totalItemsCount = olm.getTotalItemsCount();
     System.out.println("Total items count: " + totalItemsCount);

     // Iterate through each folder in the OLM storage.
     for (OlmFolder olmFolder : olm.getFolders()) {
         // Print the name of the currently iterated folder and the count of messages it contains.
         System.out.println("Folder: " + olmFolder.getName());
         System.out.println("Total items: " + olmFolder.getMessageCount());

         // Iterate through each message in the current folder.
         for (OlmMessageInfo messageInfo : olmFolder.enumerateMessages()) {
             // Print the subject of the current message to the console.
             System.out.println("Subject: " + messageInfo.getSubject());

             // Extract the full message object from the OLM storage.
             MapiMessage msg = olm.extractMapiMessage(messageInfo);

             // Save the extracted message as a .msg file.
             msg.save(msg.getSubject() + ".msg");
         }
     }
 } catch (Exception e) {
     e.printStackTrace();
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [OlmStorage(TraversalExceptionsCallback callback)](#OlmStorage-com.aspose.email.TraversalExceptionsCallback-) | Initializes a new instance of the [OlmStorage](../../com.aspose.email/olmstorage) class. |
| [OlmStorage(String fileName)](#OlmStorage-java.lang.String-) | Initializes a new instance of the [OlmStorage](../../com.aspose.email/olmstorage) class. |
| [OlmStorage(InputStream stream)](#OlmStorage-java.io.InputStream-) | Initializes a new instance of the [OlmStorage](../../com.aspose.email/olmstorage) class. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [enumerateMessages(OlmFolder folder)](#enumerateMessages-com.aspose.email.OlmFolder-) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractMapiMessage(OlmMessageInfo messageInfo)](#extractMapiMessage-com.aspose.email.OlmMessageInfo-) | Get the message from OLM storage. |
| [extractMapiMessage(String id)](#extractMapiMessage-java.lang.String-) | Get the message from OLM. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Load OLM storage from file. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Load OLM from stream. |
| [getCategories()](#getCategories--) | Gets the supported item categories. |
| [getClass()](#getClass--) |  |
| [getFolder(String name, boolean ignoreCase)](#getFolder-java.lang.String-boolean-) | Gets the folder by name. |
| [getFolderHierarchy()](#getFolderHierarchy--) | Gets the folder hierarchy. |
| [getFolders()](#getFolders--) | Gets collection of folders. |
| [getTotalItemsCount()](#getTotalItemsCount--) | Gets the total items count. |
| [hashCode()](#hashCode--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | Load OLM storage from stream. |
| [load(String fileName)](#load-java.lang.String-) | Load OLM storage from file. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

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
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
### extractMapiMessage(String id) {#extractMapiMessage-java.lang.String-}
```
public final MapiMessage extractMapiMessage(String id)
```


Get the message from OLM.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | String representation of EntryId. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A [MapiMessage](../../com.aspose.email/mapimessage) object.
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
### getCategories() {#getCategories--}
```
public final List<OlmItemCategory> getCategories()
```


Gets the supported item categories.

**Returns:**
java.util.List<com.aspose.email.OlmItemCategory> - A list of [OlmItemCategory](../../com.aspose.email/olmitemcategory) objects.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getFolderHierarchy() {#getFolderHierarchy--}
```
public final List<OlmFolder> getFolderHierarchy()
```


Gets the folder hierarchy.

Value: The folder hierarchy.

**Returns:**
java.util.List<com.aspose.email.OlmFolder>
### getFolders() {#getFolders--}
```
public final List<OlmFolder> getFolders()
```


Gets collection of folders.

**Returns:**
java.util.List<com.aspose.email.OlmFolder> - The collection of folders that belong to the storage, i.e. the sub-folders of the current OLMStorage object.
### getTotalItemsCount() {#getTotalItemsCount--}
```
public final int getTotalItemsCount()
```


Gets the total items count. Returns the total number of message items contained in the OLM.

**Returns:**
int - Total message items count.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

