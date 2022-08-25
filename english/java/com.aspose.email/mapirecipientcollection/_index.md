---
title: MapiRecipientCollection
second_title: Aspose.Email for Java API Reference
description:  Represents a collection of MapiRecipient objects.
type: docs
weight: 462
url: /java/com.aspose.email/mapirecipientcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection
```
public class MapiRecipientCollection extends System.Collections.ObjectModel.Collection<MapiRecipient>
```

Represents a collection of MapiRecipient objects.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiRecipientCollection()](#MapiRecipientCollection--) | Initializes a new instance of the [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) class. |
## Methods

| Method | Description |
| --- | --- |
| [add(String address, String displayName, int recipientType)](#add-java.lang.String-java.lang.String-int-) | Adds the new recipient. |
| [add(String address, String addressType, String displayName, int recipientType)](#add-java.lang.String-java.lang.String-java.lang.String-int-) | Adds the new recipient. |
| [addMapiRecipient(MapiRecipient item)](#addMapiRecipient-com.aspose.email.MapiRecipient-) | Adds an object to the end of the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\`. |
| [insertMapiRecipient(int index, MapiRecipient item)](#insertMapiRecipient-int-com.aspose.email.MapiRecipient-) | Inserts an element into the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\` at the specified index. |
### MapiRecipientCollection() {#MapiRecipientCollection--}
```
public MapiRecipientCollection()
```


Initializes a new instance of the [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) class.

### add(String address, String displayName, int recipientType) {#add-java.lang.String-java.lang.String-int-}
```
public final void add(String address, String displayName, int recipientType)
```


Adds the new recipient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The mail address of recipient. |
| displayName | java.lang.String | The display name of recipient. |
| recipientType | int | Type of the recipient.

--------------------

When adding a new recepient, the value of either MapiMessage.DisplayTo or MapiMessage.DisplayBcc or MapiMessage.DisplayCC is also updated depending on the type of recepient. |

### add(String address, String addressType, String displayName, int recipientType) {#add-java.lang.String-java.lang.String-java.lang.String-int-}
```
public final void add(String address, String addressType, String displayName, int recipientType)
```


Adds the new recipient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The mail address of recipient. |
| addressType | java.lang.String | The type of address. |
| displayName | java.lang.String | The display name of recipient. |
| recipientType | int | Type of the recipient.

--------------------

When adding a new recepient, the value of either MapiMessage.DisplayTo or MapiMessage.DisplayBcc or MapiMessage.DisplayCC is also updated depending on the type of recepient. |

### addMapiRecipient(MapiRecipient item) {#addMapiRecipient-com.aspose.email.MapiRecipient-}
```
public final void addMapiRecipient(MapiRecipient item)
```


Adds an object to the end of the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [MapiRecipient](../../com.aspose.email/mapirecipient) | The object to be added to the end of the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\`. The value can be null for reference types. |

### insertMapiRecipient(int index, MapiRecipient item) {#insertMapiRecipient-int-com.aspose.email.MapiRecipient-}
```
public final void insertMapiRecipient(int index, MapiRecipient item)
```


Inserts an element into the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\` at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which \`\`\` item \`\`\` should be inserted. |
| item | [MapiRecipient](../../com.aspose.email/mapirecipient) | The object to insert. The value can be null for reference types. |

