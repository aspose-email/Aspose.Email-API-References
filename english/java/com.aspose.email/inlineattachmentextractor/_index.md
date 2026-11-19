---
title: InlineAttachmentExtractor
second_title: Aspose.Email for Java API Reference
description: Extracts the files packed into an MSO package such as the oledata.mso attachment that Outlook adds to messages with embedded images or objects.
type: docs
weight: 355
url: /java/com.aspose.email/inlineattachmentextractor/
---

**Inheritance:**
java.lang.Object
```
public class InlineAttachmentExtractor
```

Extracts the files packed into an MSO package, such as the  oledata.mso  attachment that Outlook adds to messages with embedded images or objects.

This example finds the  oledata.mso  attachment of a message and saves every file it contains.

```

 MapiMessage msg = MapiMessage.load("message.msg");

 for (MapiAttachment attachment : msg.getAttachments()) {
     if (!"oledata.mso".equals(attachment.getLongFileName()))
         continue;

     try (InputStream package = attachment.openRead()) {
         IGenericDictionary files = InlineAttachmentExtractor.enumerateMsoPackage(package);
         for (KeyValuePair file : files) {
             // the key is the identifier the message body uses to refer to the file
             Files.write(Paths.get("output", file.getKey()), file.getValue());
         }
     }
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [InlineAttachmentExtractor()](#InlineAttachmentExtractor--) |  |
## Methods

| Method | Description |
| --- | --- |
| [enumerateMsoPackage(InputStream stream)](#enumerateMsoPackage-java.io.InputStream-) | Reads an MSO package and returns the files it contains. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InlineAttachmentExtractor() {#InlineAttachmentExtractor--}
```
public InlineAttachmentExtractor()
```


### enumerateMsoPackage(InputStream stream) {#enumerateMsoPackage-java.io.InputStream-}
```
public static System.Collections.Generic.IGenericDictionary<String,byte[]> enumerateMsoPackage(InputStream stream)
```


Reads an MSO package and returns the files it contains.

In evaluation mode only the first file of the package is extracted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The content of the package, for example the  oledata.mso  attachment. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,byte[]> - The files of the package: the key is the identifier of the file, which the message body uses to refer to it, and the value is its content.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

