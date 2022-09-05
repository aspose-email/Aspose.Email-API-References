---
title: LinkedResourceCollection
second_title: Aspose.Email for Android via Java API Reference
description:  Represents a collection of LinkedResource objects
type: docs
weight: 178
url: /java/com.aspose.email/linkedresourcecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class LinkedResourceCollection extends System.Collections.ObjectModel.Collection<LinkedResource> implements System.IDisposable, Closeable
```

Represents a collection of LinkedResource objects
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [close()](#close--) |  |
| [removeAt(int index, boolean removeHtmlLink)](#removeAt-int-boolean-) | Removes the element at the specified index from this collection. |
| [clear(boolean removeHtmlLinks)](#clear-boolean-) | Removes all elements from this collection. |
| [insertItem(int index, LinkedResource item)](#insertItem-int-com.aspose.email.LinkedResource-) | Inserts an element into the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\` at the specified index. |
### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### close() {#close--}
```
public void close()
```




### removeAt(int index, boolean removeHtmlLink) {#removeAt-int-boolean-}
```
public final void removeAt(int index, boolean removeHtmlLink)
```


Removes the element at the specified index from this collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |
| removeHtmlLink | boolean | Defines need remove link from html body or not. |

### clear(boolean removeHtmlLinks) {#clear-boolean-}
```
public final void clear(boolean removeHtmlLinks)
```


Removes all elements from this collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeHtmlLinks | boolean | Defines need remove links from html body or not. |

### insertItem(int index, LinkedResource item) {#insertItem-int-com.aspose.email.LinkedResource-}
```
public void insertItem(int index, LinkedResource item)
```


Inserts an element into the \`\`\` System.Collections.ObjectModel.Collection\`1 \`\`\` at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which \`\`\` item \`\`\` should be inserted. |
| item | [LinkedResource](../../com.aspose.email/linkedresource) | The object to insert. The value can be null for reference types. |

