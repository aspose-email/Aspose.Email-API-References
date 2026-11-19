---
title: MapiAttachmentCollection
second_title: Aspose.Email for Java API Reference
description: The attachments of an Outlook item.
type: docs
weight: 406
url: /java/com.aspose.email/mapiattachmentcollection/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.List
```
public class MapiAttachmentCollection extends System.Collections.Generic.List<MapiAttachment>
```

The attachments of an Outlook item.

Returned by [MapiMessageItemBase.getAttachments()](../../com.aspose.email/mapimessageitembase\#getAttachments--). Besides the list operations, it adds files from memory, from a stream or from disk, embedded messages and reference (cloud) attachments.

This example attaches a file from disk, a file from memory and another message.

```

 try (MapiMessage msg = new MapiMessage("from@domain.com", "to@domain.com", "Report", "See the attachments.")) {
     // the file is read when the message is saved
     msg.getAttachments().addFile("report.pdf");

     msg.getAttachments().add("notes.txt", "Notes for the report".getBytes(StandardCharsets.UTF_8));

     MapiMessage original = MapiMessage.load("original.msg");
     msg.getAttachments().add("Original message", original);

     msg.save("report.msg");
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiAttachmentCollection()](#MapiAttachmentCollection--) | Initializes a new instance of the [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) class. |
| [MapiAttachmentCollection(MapiMessageItemBase owner)](#MapiAttachmentCollection-com.aspose.email.MapiMessageItemBase-) | Initializes a new instance of the [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) class that belongs to the specified item. |
## Methods

| Method | Description |
| --- | --- |
| [<T>fromJava(List<T> arg0)](#-T-fromJava-java.util.List-T--) |  |
| [<T>toArray(T[] arg0)](#-T-toArray-T---) |  |
| [<T>toJava(System.Collections.Generic.List<T> arg0)](#-T-toJava-com.aspose.ms.System.Collections.Generic.List-T--) |  |
| [<TOutput>convertAll(System.Converter<T,TOutput> arg0)](#-TOutput-convertAll-com.aspose.ms.System.Converter-T-TOutput--) |  |
| [add(T arg0)](#add-T-) |  |
| [add(int arg0, T arg1)](#add-int-T-) |  |
| [add(String name, byte[] data)](#add-java.lang.String-byte---) | Adds a file attachment with the content in memory. |
| [add(String name, MapiMessage msg)](#add-java.lang.String-com.aspose.email.MapiMessage-) | Attaches a message as an embedded message. |
| [add(String name, ReferenceAttachmentOptions options)](#add-java.lang.String-com.aspose.email.ReferenceAttachmentOptions-) | Adds a reference attachment to the collection using the specified name and configuration options. |
| [add(String name, InputStream content)](#add-java.lang.String-java.io.InputStream-) | Adds a new attachment whose content is read from a stream. |
| [add(String name, InputStream content, boolean leaveStreamOpen)](#add-java.lang.String-java.io.InputStream-boolean-) | Adds a new attachment whose content is read from a stream. |
| [addAll(int arg0, Collection<? extends T> arg1)](#addAll-int-java.util.Collection---extends-T--) |  |
| [addAll(Collection<? extends T> arg0)](#addAll-java.util.Collection---extends-T--) |  |
| [addFile(String filePath)](#addFile-java.lang.String-) | Adds a new attachment reading its content from a file. |
| [addFile(String filePath, String displayName)](#addFile-java.lang.String-java.lang.String-) | Adds a new attachment reading its content from a file. |
| [addItem(T arg0)](#addItem-T-) |  |
| [addMapiAttachment(MapiAttachment item)](#addMapiAttachment-com.aspose.email.MapiAttachment-) | Adds an existing attachment to the end of the collection. |
| [addRange(T[] arg0)](#addRange-T---) |  |
| [addRange(Iterable<T> arg0)](#addRange-java.lang.Iterable-T--) |  |
| [asReadOnly()](#asReadOnly--) |  |
| [binarySearch(T arg0)](#binarySearch-T-) |  |
| [binarySearch(T arg0, Comparator<T> arg1)](#binarySearch-T-java.util.Comparator-T--) |  |
| [binarySearch(int arg0, int arg1, T arg2, Comparator<T> arg3)](#binarySearch-int-int-T-java.util.Comparator-T--) |  |
| [clear()](#clear--) |  |
| [contains(Object arg0)](#contains-java.lang.Object-) |  |
| [containsAll(Collection<?> arg0)](#containsAll-java.util.Collection----) |  |
| [containsItem(T arg0)](#containsItem-T-) |  |
| [copyTo(T[] arg0)](#copyTo-T---) |  |
| [copyTo(System.Array arg0, int arg1)](#copyTo-com.aspose.ms.System.Array-int-) |  |
| [copyTo(int arg0, T[] arg1, int arg2, int arg3)](#copyTo-int-T---int-int-) |  |
| [copyToTArray(T[] arg0, int arg1)](#copyToTArray-T---int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exists(System.Predicate<T> arg0)](#exists-com.aspose.ms.System.Predicate-T--) |  |
| [find(System.Predicate<T> arg0)](#find-com.aspose.ms.System.Predicate-T--) |  |
| [findAll(System.Predicate<T> arg0)](#findAll-com.aspose.ms.System.Predicate-T--) |  |
| [findIndex(System.Predicate<T> arg0)](#findIndex-com.aspose.ms.System.Predicate-T--) |  |
| [findIndex(int arg0, System.Predicate<T> arg1)](#findIndex-int-com.aspose.ms.System.Predicate-T--) |  |
| [findIndex(int arg0, int arg1, System.Predicate<T> arg2)](#findIndex-int-int-com.aspose.ms.System.Predicate-T--) |  |
| [findLast(System.Predicate<T> arg0)](#findLast-com.aspose.ms.System.Predicate-T--) |  |
| [findLastIndex(System.Predicate<T> arg0)](#findLastIndex-com.aspose.ms.System.Predicate-T--) |  |
| [findLastIndex(int arg0, System.Predicate<T> arg1)](#findLastIndex-int-com.aspose.ms.System.Predicate-T--) |  |
| [findLastIndex(int arg0, int arg1, System.Predicate<T> arg2)](#findLastIndex-int-int-com.aspose.ms.System.Predicate-T--) |  |
| [forEach(System.Action<T> arg0)](#forEach-com.aspose.ms.System.Action-T--) |  |
| [fromPrimitiveArray(boolean[] arg0)](#fromPrimitiveArray-boolean---) |  |
| [fromPrimitiveArray(byte[] arg0)](#fromPrimitiveArray-byte---) |  |
| [fromPrimitiveArray(char[] arg0)](#fromPrimitiveArray-char---) |  |
| [fromPrimitiveArray(double[] arg0)](#fromPrimitiveArray-double---) |  |
| [fromPrimitiveArray(float[] arg0)](#fromPrimitiveArray-float---) |  |
| [fromPrimitiveArray(int[] arg0)](#fromPrimitiveArray-int---) |  |
| [fromPrimitiveArray(long[] arg0)](#fromPrimitiveArray-long---) |  |
| [fromPrimitiveArray(short[] arg0)](#fromPrimitiveArray-short---) |  |
| [get(int arg0)](#get-int-) |  |
| [getCapacity()](#getCapacity--) |  |
| [getClass()](#getClass--) |  |
| [getRange(int arg0, int arg1)](#getRange-int-int-) |  |
| [getSyncRoot()](#getSyncRoot--) |  |
| [get_Item(int arg0)](#get-Item-int-) |  |
| [hashCode()](#hashCode--) |  |
| [indexOf(T arg0, int arg1)](#indexOf-T-int-) |  |
| [indexOf(T arg0, int arg1, int arg2)](#indexOf-T-int-int-) |  |
| [indexOf(Object arg0)](#indexOf-java.lang.Object-) |  |
| [indexOfItem(T arg0)](#indexOfItem-T-) |  |
| [insert(int index, String name, MapiMessage msg)](#insert-int-java.lang.String-com.aspose.email.MapiMessage-) | Inserts a message as an embedded attachment at the specified position. |
| [insertItem(int arg0, T arg1)](#insertItem-int-T-) |  |
| [insertMapiAttachment(int index, MapiAttachment item)](#insertMapiAttachment-int-com.aspose.email.MapiAttachment-) | Inserts an attachment at the specified position. |
| [insertRange(int arg0, Iterable<T> arg1)](#insertRange-int-java.lang.Iterable-T--) |  |
| [isEmpty()](#isEmpty--) |  |
| [isFixedSize()](#isFixedSize--) |  |
| [isReadOnly()](#isReadOnly--) |  |
| [isSynchronized()](#isSynchronized--) |  |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [lastIndexOf(T arg0, int arg1)](#lastIndexOf-T-int-) |  |
| [lastIndexOf(T arg0, int arg1, int arg2)](#lastIndexOf-T-int-int-) |  |
| [lastIndexOf(Object arg0)](#lastIndexOf-java.lang.Object-) |  |
| [listIterator()](#listIterator--) |  |
| [listIterator(int arg0)](#listIterator-int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(int arg0)](#remove-int-) |  |
| [remove(Object arg0)](#remove-java.lang.Object-) |  |
| [removeAll(System.Predicate<T> arg0)](#removeAll-com.aspose.ms.System.Predicate-T--) |  |
| [removeAll(Collection<?> arg0)](#removeAll-java.util.Collection----) |  |
| [removeAt(int index)](#removeAt-int-) | Removes the attachment at the specified position. |
| [removeItem(T arg0)](#removeItem-T-) |  |
| [removeMapiAttachment(MapiAttachment item)](#removeMapiAttachment-com.aspose.email.MapiAttachment-) | Removes the first occurrence of the attachment from the collection. |
| [removeRange(int arg0, int arg1)](#removeRange-int-int-) |  |
| [replace(int index, String name, MapiMessage msg)](#replace-int-java.lang.String-com.aspose.email.MapiMessage-) | Replaces the attachment at the specified position with an embedded message. |
| [retainAll(Collection<?> arg0)](#retainAll-java.util.Collection----) |  |
| [reverse()](#reverse--) |  |
| [reverse(int arg0, int arg1)](#reverse-int-int-) |  |
| [set(int arg0, T arg1)](#set-int-T-) |  |
| [setCapacity(int arg0)](#setCapacity-int-) |  |
| [set_Item(int arg0, T arg1)](#set-Item-int-T-) |  |
| [size()](#size--) |  |
| [sort()](#sort--) |  |
| [sort(System.Comparison<T> arg0)](#sort-com.aspose.ms.System.Comparison-T--) |  |
| [sort(int arg0, int arg1, Comparator<T> arg2)](#sort-int-int-java.util.Comparator-T--) |  |
| [sort(Comparator<? super T> arg0)](#sort-java.util.Comparator---super-T--) |  |
| [subList(int arg0, int arg1)](#subList-int-int-) |  |
| [toArray()](#toArray--) |  |
| [toString()](#toString--) |  |
| [trimExcess()](#trimExcess--) |  |
| [trueForAll(System.Predicate<T> arg0)](#trueForAll-com.aspose.ms.System.Predicate-T--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiAttachmentCollection() {#MapiAttachmentCollection--}
```
public MapiAttachmentCollection()
```


Initializes a new instance of the [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) class.

### MapiAttachmentCollection(MapiMessageItemBase owner) {#MapiAttachmentCollection-com.aspose.email.MapiMessageItemBase-}
```
public MapiAttachmentCollection(MapiMessageItemBase owner)
```


Initializes a new instance of the [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) class that belongs to the specified item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| owner | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The item the attachments belong to. |

### <T>fromJava(List<T> arg0) {#-T-fromJava-java.util.List-T--}
```
public static System.Collections.Generic.List<T> <T>fromJava(List<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.util.List<T> |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<T>
### <T>toArray(T[] arg0) {#-T-toArray-T---}
```
public T[] <T>toArray(T[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T[] |  |

**Returns:**
T[]
### <T>toJava(System.Collections.Generic.List<T> arg0) {#-T-toJava-com.aspose.ms.System.Collections.Generic.List-T--}
```
public static List<T> <T>toJava(System.Collections.Generic.List<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.List<T> |  |

**Returns:**
java.util.List<T>
### <TOutput>convertAll(System.Converter<T,TOutput> arg0) {#-TOutput-convertAll-com.aspose.ms.System.Converter-T-TOutput--}
```
public System.Collections.Generic.List<TOutput> <TOutput>convertAll(System.Converter<T,TOutput> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Converter<T,TOutput> |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<TOutput>
### add(T arg0) {#add-T-}
```
public boolean add(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### add(int arg0, T arg1) {#add-int-T-}
```
public void add(int arg0, T arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### add(String name, byte[] data) {#add-java.lang.String-byte---}
```
public final MapiAttachment add(String name, byte[] data)
```


Adds a file attachment with the content in memory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The file name of the attachment. |
| data | byte[] | The content of the file. |

**Returns:**
[MapiAttachment](../../com.aspose.email/mapiattachment) - The new [MapiAttachment](../../com.aspose.email/mapiattachment).
### add(String name, MapiMessage msg) {#add-java.lang.String-com.aspose.email.MapiMessage-}
```
public final MapiAttachment add(String name, MapiMessage msg)
```


Attaches a message as an embedded message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the attachment. |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | The message to attach. |

**Returns:**
[MapiAttachment](../../com.aspose.email/mapiattachment) - The new [MapiAttachment](../../com.aspose.email/mapiattachment).
### add(String name, ReferenceAttachmentOptions options) {#add-java.lang.String-com.aspose.email.ReferenceAttachmentOptions-}
```
public final MapiAttachment add(String name, ReferenceAttachmentOptions options)
```


Adds a reference attachment to the collection using the specified name and configuration options.

This method adds a reference attachment to the message and applies additional properties based on the provided [ReferenceAttachmentOptions](../../com.aspose.email/referenceattachmentoptions) object. The additional properties include permission type, original permission type, folder indicator, provider endpoint URL, preview URL, and thumbnail URL.

The following example demonstrates how to use this method:

```

 ReferenceAttachmentOptions options = new ReferenceAttachmentOptions(
         "https://drive.google.com/file/d/1HJ-M3F2qq1oRrTZ2GZhUdErJNy2CT3DF/",
         "https://drive.google.com/drive/my-drive",
         "GoogleDrive");
 options.setPermissionType(AttachmentPermissionType.AnyoneCanEdit);
 options.setOriginalPermissionType(0);
 options.setFolder(false);

 msg.getAttachments().add("Document.pdf", options);
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the attachment to display in the message. |
| options | [ReferenceAttachmentOptions](../../com.aspose.email/referenceattachmentoptions) | An instance of [ReferenceAttachmentOptions](../../com.aspose.email/referenceattachmentoptions) containing the configuration details for the reference attachment, such as the shared link, URL, and provider name. |

**Returns:**
[MapiAttachment](../../com.aspose.email/mapiattachment) - The new [MapiAttachment](../../com.aspose.email/mapiattachment).
### add(String name, InputStream content) {#add-java.lang.String-java.io.InputStream-}
```
public final MapiAttachment add(String name, InputStream content)
```


Adds a new attachment whose content is read from a stream.

The content is not copied into memory: it is read from the stream on demand when the message is saved or when the attachment content is accessed. Modifying the contents of the stream between this call and reading the attachment gives undefined results.

Unlike [Attachment](../../com.aspose.email/attachment), which reads MIME content once into its own storage and therefore tolerates forward-only streams, this method requires a seekable stream: the content is read again on every save and its length must be known in advance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The file name of the attachment. |
| content | java.io.InputStream | The attachment content. The stream must be seekable and readable. Content is taken from the stream's current position to its end, and the range is fixed at the moment of this call. The stream must stay open until the message is saved or the attachment content is accessed, and the caller keeps ownership of it. |

**Returns:**
[MapiAttachment](../../com.aspose.email/mapiattachment) - The new [MapiAttachment](../../com.aspose.email/mapiattachment).
### add(String name, InputStream content, boolean leaveStreamOpen) {#add-java.lang.String-java.io.InputStream-boolean-}
```
public final MapiAttachment add(String name, InputStream content, boolean leaveStreamOpen)
```


Adds a new attachment whose content is read from a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The file name of the attachment. |
| content | java.io.InputStream | The attachment content. The stream must be seekable and readable. Content is taken from the stream's current position to its end, and the range is fixed at the moment of this call. The stream must stay open until the message is saved or the attachment content is accessed. |
| leaveStreamOpen | boolean | When  false , the stream is disposed together with the owning message, so the message must be disposed. When  true , the caller keeps ownership of the stream. |

**Returns:**
[MapiAttachment](../../com.aspose.email/mapiattachment) - The new [MapiAttachment](../../com.aspose.email/mapiattachment).
### addAll(int arg0, Collection<? extends T> arg1) {#addAll-int-java.util.Collection---extends-T--}
```
public boolean addAll(int arg0, Collection<? extends T> arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | java.util.Collection<? extends T> |  |

**Returns:**
boolean
### addAll(Collection<? extends T> arg0) {#addAll-java.util.Collection---extends-T--}
```
public boolean addAll(Collection<? extends T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.util.Collection<? extends T> |  |

**Returns:**
boolean
### addFile(String filePath) {#addFile-java.lang.String-}
```
public final MapiAttachment addFile(String filePath)
```


Adds a new attachment reading its content from a file. The file name is used as the display name of the attachment.

The file is opened for reading and stays open until the owning message is disposed, so the message must be disposed. The content is never copied into memory in full, which makes this the appropriate way to attach large files.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file to attach. |

**Returns:**
[MapiAttachment](../../com.aspose.email/mapiattachment) - The new [MapiAttachment](../../com.aspose.email/mapiattachment).
### addFile(String filePath, String displayName) {#addFile-java.lang.String-java.lang.String-}
```
public final MapiAttachment addFile(String filePath, String displayName)
```


Adds a new attachment reading its content from a file.

The file is opened for reading and stays open until the owning message is disposed, so the message must be disposed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file to attach. |
| displayName | java.lang.String | The name of attachment to display in the message. |

**Returns:**
[MapiAttachment](../../com.aspose.email/mapiattachment) - The new [MapiAttachment](../../com.aspose.email/mapiattachment).
### addItem(T arg0) {#addItem-T-}
```
public void addItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### addMapiAttachment(MapiAttachment item) {#addMapiAttachment-com.aspose.email.MapiAttachment-}
```
public final void addMapiAttachment(MapiAttachment item)
```


Adds an existing attachment to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [MapiAttachment](../../com.aspose.email/mapiattachment) | The attachment to add. |

### addRange(T[] arg0) {#addRange-T---}
```
public void addRange(T[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T[] |  |

### addRange(Iterable<T> arg0) {#addRange-java.lang.Iterable-T--}
```
public void addRange(Iterable<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Iterable<T> |  |

### asReadOnly() {#asReadOnly--}
```
public System.Collections.ObjectModel.ReadOnlyCollection<T> asReadOnly()
```




**Returns:**
com.aspose.ms.System.Collections.ObjectModel.ReadOnlyCollection<T>
### binarySearch(T arg0) {#binarySearch-T-}
```
public int binarySearch(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
int
### binarySearch(T arg0, Comparator<T> arg1) {#binarySearch-T-java.util.Comparator-T--}
```
public int binarySearch(T arg0, Comparator<T> arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |
| arg1 | java.util.Comparator<T> |  |

**Returns:**
int
### binarySearch(int arg0, int arg1, T arg2, Comparator<T> arg3) {#binarySearch-int-int-T-java.util.Comparator-T--}
```
public int binarySearch(int arg0, int arg1, T arg2, Comparator<T> arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | T |  |
| arg3 | java.util.Comparator<T> |  |

**Returns:**
int
### clear() {#clear--}
```
public void clear()
```




### contains(Object arg0) {#contains-java.lang.Object-}
```
public boolean contains(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### containsAll(Collection<?> arg0) {#containsAll-java.util.Collection----}
```
public boolean containsAll(Collection<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.util.Collection<?> |  |

**Returns:**
boolean
### containsItem(T arg0) {#containsItem-T-}
```
public boolean containsItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### copyTo(T[] arg0) {#copyTo-T---}
```
public void copyTo(T[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T[] |  |

### copyTo(System.Array arg0, int arg1) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Array |  |
| arg1 | int |  |

### copyTo(int arg0, T[] arg1, int arg2, int arg3) {#copyTo-int-T---int-int-}
```
public void copyTo(int arg0, T[] arg1, int arg2, int arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T[] |  |
| arg2 | int |  |
| arg3 | int |  |

### copyToTArray(T[] arg0, int arg1) {#copyToTArray-T---int-}
```
public void copyToTArray(T[] arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T[] |  |
| arg1 | int |  |

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
### exists(System.Predicate<T> arg0) {#exists-com.aspose.ms.System.Predicate-T--}
```
public boolean exists(System.Predicate<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
boolean
### find(System.Predicate<T> arg0) {#find-com.aspose.ms.System.Predicate-T--}
```
public T find(System.Predicate<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
T
### findAll(System.Predicate<T> arg0) {#findAll-com.aspose.ms.System.Predicate-T--}
```
public System.Collections.Generic.List<T> findAll(System.Predicate<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<T>
### findIndex(System.Predicate<T> arg0) {#findIndex-com.aspose.ms.System.Predicate-T--}
```
public int findIndex(System.Predicate<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### findIndex(int arg0, System.Predicate<T> arg1) {#findIndex-int-com.aspose.ms.System.Predicate-T--}
```
public int findIndex(int arg0, System.Predicate<T> arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### findIndex(int arg0, int arg1, System.Predicate<T> arg2) {#findIndex-int-int-com.aspose.ms.System.Predicate-T--}
```
public int findIndex(int arg0, int arg1, System.Predicate<T> arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### findLast(System.Predicate<T> arg0) {#findLast-com.aspose.ms.System.Predicate-T--}
```
public T findLast(System.Predicate<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
T
### findLastIndex(System.Predicate<T> arg0) {#findLastIndex-com.aspose.ms.System.Predicate-T--}
```
public int findLastIndex(System.Predicate<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### findLastIndex(int arg0, System.Predicate<T> arg1) {#findLastIndex-int-com.aspose.ms.System.Predicate-T--}
```
public int findLastIndex(int arg0, System.Predicate<T> arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### findLastIndex(int arg0, int arg1, System.Predicate<T> arg2) {#findLastIndex-int-int-com.aspose.ms.System.Predicate-T--}
```
public int findLastIndex(int arg0, int arg1, System.Predicate<T> arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### forEach(System.Action<T> arg0) {#forEach-com.aspose.ms.System.Action-T--}
```
public void forEach(System.Action<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Action<T> |  |

### fromPrimitiveArray(boolean[] arg0) {#fromPrimitiveArray-boolean---}
```
public static System.Collections.Generic.List<Boolean> fromPrimitiveArray(boolean[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean[] |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Boolean>
### fromPrimitiveArray(byte[] arg0) {#fromPrimitiveArray-byte---}
```
public static System.Collections.Generic.List<Byte> fromPrimitiveArray(byte[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | byte[] |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Byte>
### fromPrimitiveArray(char[] arg0) {#fromPrimitiveArray-char---}
```
public static System.Collections.Generic.List<Character> fromPrimitiveArray(char[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | char[] |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Character>
### fromPrimitiveArray(double[] arg0) {#fromPrimitiveArray-double---}
```
public static System.Collections.Generic.List<Double> fromPrimitiveArray(double[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | double[] |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Double>
### fromPrimitiveArray(float[] arg0) {#fromPrimitiveArray-float---}
```
public static System.Collections.Generic.List<Float> fromPrimitiveArray(float[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | float[] |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Float>
### fromPrimitiveArray(int[] arg0) {#fromPrimitiveArray-int---}
```
public static System.Collections.Generic.List<Integer> fromPrimitiveArray(int[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int[] |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer>
### fromPrimitiveArray(long[] arg0) {#fromPrimitiveArray-long---}
```
public static System.Collections.Generic.List<Long> fromPrimitiveArray(long[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long[] |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Long>
### fromPrimitiveArray(short[] arg0) {#fromPrimitiveArray-short---}
```
public static System.Collections.Generic.List<Short> fromPrimitiveArray(short[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | short[] |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Short>
### get(int arg0) {#get-int-}
```
public T get(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
T
### getCapacity() {#getCapacity--}
```
public int getCapacity()
```




**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getRange(int arg0, int arg1) {#getRange-int-int-}
```
public System.Collections.Generic.List<T> getRange(int arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<T>
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```




**Returns:**
java.lang.Object
### get_Item(int arg0) {#get-Item-int-}
```
public T get_Item(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
T
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(T arg0, int arg1) {#indexOf-T-int-}
```
public int indexOf(T arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |
| arg1 | int |  |

**Returns:**
int
### indexOf(T arg0, int arg1, int arg2) {#indexOf-T-int-int-}
```
public int indexOf(T arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |
| arg1 | int |  |
| arg2 | int |  |

**Returns:**
int
### indexOf(Object arg0) {#indexOf-java.lang.Object-}
```
public int indexOf(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
int
### indexOfItem(T arg0) {#indexOfItem-T-}
```
public int indexOfItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
int
### insert(int index, String name, MapiMessage msg) {#insert-int-java.lang.String-com.aspose.email.MapiMessage-}
```
public final void insert(int index, String name, MapiMessage msg)
```


Inserts a message as an embedded attachment at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based position to insert at. |
| name | java.lang.String | The name of the attachment. |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | The message to attach. |

### insertItem(int arg0, T arg1) {#insertItem-int-T-}
```
public void insertItem(int arg0, T arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### insertMapiAttachment(int index, MapiAttachment item) {#insertMapiAttachment-int-com.aspose.email.MapiAttachment-}
```
public final void insertMapiAttachment(int index, MapiAttachment item)
```


Inserts an attachment at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based position to insert at. |
| item | [MapiAttachment](../../com.aspose.email/mapiattachment) | The attachment to insert. |

### insertRange(int arg0, Iterable<T> arg1) {#insertRange-int-java.lang.Iterable-T--}
```
public void insertRange(int arg0, Iterable<T> arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | java.lang.Iterable<T> |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```




**Returns:**
boolean
### isFixedSize() {#isFixedSize--}
```
public boolean isFixedSize()
```




**Returns:**
boolean
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**Returns:**
boolean
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```




**Returns:**
boolean
### iterator() {#iterator--}
```
public System.Collections.Generic.List.Enumerator<T> iterator()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List.Enumerator<T>
### iteratorJava() {#iteratorJava--}
```
public System.Collections.Generic.List.EnumeratorJava<T> iteratorJava()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List.EnumeratorJava<T>
### lastIndexOf(T arg0, int arg1) {#lastIndexOf-T-int-}
```
public int lastIndexOf(T arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |
| arg1 | int |  |

**Returns:**
int
### lastIndexOf(T arg0, int arg1, int arg2) {#lastIndexOf-T-int-int-}
```
public int lastIndexOf(T arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |
| arg1 | int |  |
| arg2 | int |  |

**Returns:**
int
### lastIndexOf(Object arg0) {#lastIndexOf-java.lang.Object-}
```
public int lastIndexOf(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
int
### listIterator() {#listIterator--}
```
public ListIterator listIterator()
```




**Returns:**
java.util.ListIterator
### listIterator(int arg0) {#listIterator-int-}
```
public ListIterator listIterator(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
java.util.ListIterator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(int arg0) {#remove-int-}
```
public T remove(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
T
### remove(Object arg0) {#remove-java.lang.Object-}
```
public boolean remove(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### removeAll(System.Predicate<T> arg0) {#removeAll-com.aspose.ms.System.Predicate-T--}
```
public int removeAll(System.Predicate<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
int
### removeAll(Collection<?> arg0) {#removeAll-java.util.Collection----}
```
public boolean removeAll(Collection<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.util.Collection<?> |  |

**Returns:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the attachment at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based position of the attachment to remove. |

### removeItem(T arg0) {#removeItem-T-}
```
public boolean removeItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### removeMapiAttachment(MapiAttachment item) {#removeMapiAttachment-com.aspose.email.MapiAttachment-}
```
public final boolean removeMapiAttachment(MapiAttachment item)
```


Removes the first occurrence of the attachment from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [MapiAttachment](../../com.aspose.email/mapiattachment) | The attachment to remove. |

**Returns:**
boolean -  true  if the attachment was removed;  false  if it was not in the collection.
### removeRange(int arg0, int arg1) {#removeRange-int-int-}
```
public void removeRange(int arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

### replace(int index, String name, MapiMessage msg) {#replace-int-java.lang.String-com.aspose.email.MapiMessage-}
```
public final void replace(int index, String name, MapiMessage msg)
```


Replaces the attachment at the specified position with an embedded message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based position of the attachment to replace. |
| name | java.lang.String | The name of the new attachment. |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | The message to attach. |

### retainAll(Collection<?> arg0) {#retainAll-java.util.Collection----}
```
public boolean retainAll(Collection<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.util.Collection<?> |  |

**Returns:**
boolean
### reverse() {#reverse--}
```
public void reverse()
```




### reverse(int arg0, int arg1) {#reverse-int-int-}
```
public void reverse(int arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

### set(int arg0, T arg1) {#set-int-T-}
```
public T set(int arg0, T arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

**Returns:**
T
### setCapacity(int arg0) {#setCapacity-int-}
```
public void setCapacity(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### set_Item(int arg0, T arg1) {#set-Item-int-T-}
```
public void set_Item(int arg0, T arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### size() {#size--}
```
public int size()
```




**Returns:**
int
### sort() {#sort--}
```
public void sort()
```




### sort(System.Comparison<T> arg0) {#sort-com.aspose.ms.System.Comparison-T--}
```
public void sort(System.Comparison<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Comparison<T> |  |

### sort(int arg0, int arg1, Comparator<T> arg2) {#sort-int-int-java.util.Comparator-T--}
```
public void sort(int arg0, int arg1, Comparator<T> arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | java.util.Comparator<T> |  |

### sort(Comparator<? super T> arg0) {#sort-java.util.Comparator---super-T--}
```
public void sort(Comparator<? super T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.util.Comparator<? super T> |  |

### subList(int arg0, int arg1) {#subList-int-int-}
```
public List<T> subList(int arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

**Returns:**
java.util.List<T>
### toArray() {#toArray--}
```
public Object[] toArray()
```




**Returns:**
java.lang.Object[]
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### trimExcess() {#trimExcess--}
```
public void trimExcess()
```




### trueForAll(System.Predicate<T> arg0) {#trueForAll-com.aspose.ms.System.Predicate-T--}
```
public boolean trueForAll(System.Predicate<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Predicate<T> |  |

**Returns:**
boolean
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

