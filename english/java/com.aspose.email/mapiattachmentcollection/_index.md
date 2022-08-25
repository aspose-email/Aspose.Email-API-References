---
title: MapiAttachmentCollection
second_title: Aspose.Email for Java API Reference
description:  Represents a collection of MapiAttachment objects.
type: docs
weight: 385
url: /java/com.aspose.email/mapiattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.List
```
public class MapiAttachmentCollection extends System.Collections.Generic.List<MapiAttachment>
```

Represents a collection of MapiAttachment objects.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiAttachmentCollection()](#MapiAttachmentCollection--) | Initializes a new instance of the [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) class. |
| [MapiAttachmentCollection(MapiMessageItemBase owner)](#MapiAttachmentCollection-com.aspose.email.MapiMessageItemBase-) | Initializes a new instance of the MapiAttachmentCollection class. |
## Methods

| Method | Description |
| --- | --- |
| [add(String name, MapiMessage msg)](#add-java.lang.String-com.aspose.email.MapiMessage-) | Adds the new attachment as embedded message. |
| [add(String name, byte[] data)](#add-java.lang.String-byte---) | Adds the new attachment. |
| [addMapiAttachment(MapiAttachment item)](#addMapiAttachment-com.aspose.email.MapiAttachment-) | Adds an object to the end of the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\`. |
| [insertMapiAttachment(int index, MapiAttachment item)](#insertMapiAttachment-int-com.aspose.email.MapiAttachment-) | Inserts an element into the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\` at the specified index. |
| [insert(int index, String name, MapiMessage msg)](#insert-int-java.lang.String-com.aspose.email.MapiMessage-) | Inserts a message as attachment into the [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) at the specified index. |
| [replace(int index, String name, MapiMessage msg)](#replace-int-java.lang.String-com.aspose.email.MapiMessage-) | Replaces an element at the specified index. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the MapiAttachmentCollection. |
| [removeMapiAttachment(MapiAttachment item)](#removeMapiAttachment-com.aspose.email.MapiAttachment-) | Removes the first occurrence of a specific object from the MapiAttachmentCollection. |
### MapiAttachmentCollection() {#MapiAttachmentCollection--}
```
public MapiAttachmentCollection()
```


Initializes a new instance of the [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) class.

### MapiAttachmentCollection(MapiMessageItemBase owner) {#MapiAttachmentCollection-com.aspose.email.MapiMessageItemBase-}
```
public MapiAttachmentCollection(MapiMessageItemBase owner)
```


Initializes a new instance of the MapiAttachmentCollection class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| owner | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The owner message. |

### add(String name, MapiMessage msg) {#add-java.lang.String-com.aspose.email.MapiMessage-}
```
public final void add(String name, MapiMessage msg)
```


Adds the new attachment as embedded message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of attachment. |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) that represents the attached message. |

### add(String name, byte[] data) {#add-java.lang.String-byte---}
```
public final void add(String name, byte[] data)
```


Adds the new attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of attachment. |
| data | byte[] | The attachment data. |

### addMapiAttachment(MapiAttachment item) {#addMapiAttachment-com.aspose.email.MapiAttachment-}
```
public final void addMapiAttachment(MapiAttachment item)
```


Adds an object to the end of the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [MapiAttachment](../../com.aspose.email/mapiattachment) | The object to be added to the end of the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\`. The value can be null for reference types. |

### insertMapiAttachment(int index, MapiAttachment item) {#insertMapiAttachment-int-com.aspose.email.MapiAttachment-}
```
public final void insertMapiAttachment(int index, MapiAttachment item)
```


Inserts an element into the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\` at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which \`\`\` item \`\`\` should be inserted. |
| item | [MapiAttachment](../../com.aspose.email/mapiattachment) | The object to insert. The value can be null for reference types. |

### insert(int index, String name, MapiMessage msg) {#insert-int-java.lang.String-com.aspose.email.MapiMessage-}
```
public final void insert(int index, String name, MapiMessage msg)
```


Inserts a message as attachment into the [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which should be inserted. |
| name | java.lang.String | The name of attachment. |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) that represents the attached message. |

### replace(int index, String name, MapiMessage msg) {#replace-int-java.lang.String-com.aspose.email.MapiMessage-}
```
public final void replace(int index, String name, MapiMessage msg)
```


Replaces an element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which should be replaced. |
| name | java.lang.String | The name of attachment. |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) that represents the attached message. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the element at the specified index of the MapiAttachmentCollection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | he zero-based index of the element to remove. |

### removeMapiAttachment(MapiAttachment item) {#removeMapiAttachment-com.aspose.email.MapiAttachment-}
```
public final boolean removeMapiAttachment(MapiAttachment item)
```


Removes the first occurrence of a specific object from the MapiAttachmentCollection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [MapiAttachment](../../com.aspose.email/mapiattachment) | The object to remove from the MapiAttachmentCollection. |

**Returns:**
boolean - true if item is successfully removed; otherwise, false.
