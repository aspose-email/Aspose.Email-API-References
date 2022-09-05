---
title: MapiObjectProperty
second_title: Aspose.Email for Java API Reference
description:  Represents a Custom object included in Outlook Message documents.
type: docs
weight: 452
url: /java/com.aspose.email/mapiobjectproperty/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MapiProperty](../../com.aspose.email/mapiproperty)
```
public class MapiObjectProperty extends MapiProperty
```

Represents a Custom object included in Outlook Message documents.
## Methods

| Method | Description |
| --- | --- |
| [isOutlookMessage()](#isOutlookMessage--) | Indicates whether the object property is an embedded outlook message. |
| [toMapiMessage()](#toMapiMessage--) | Creates the MapiMessage from object data. |
| [getOleDocumentFormat()](#getOleDocumentFormat--) | Gets the Ole format type. |
| [getDocumentName()](#getDocumentName--) | Gets the document name. |
| [getProperties()](#getProperties--) | Gets a collection of MAPI properties. |
### isOutlookMessage() {#isOutlookMessage--}
```
public final boolean isOutlookMessage()
```


Indicates whether the object property is an embedded outlook message.

**Returns:**
boolean
### toMapiMessage() {#toMapiMessage--}
```
public final MapiMessage toMapiMessage()
```


Creates the MapiMessage from object data.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The resultant [MapiMessage](../../com.aspose.email/mapimessage).
### getOleDocumentFormat() {#getOleDocumentFormat--}
```
public final OleDocumentFormat getOleDocumentFormat()
```


Gets the Ole format type.

**Returns:**
[OleDocumentFormat](../../com.aspose.email/oledocumentformat)
### getDocumentName() {#getDocumentName--}
```
public final String getDocumentName()
```


Gets the document name.

**Returns:**
java.lang.String
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


Gets a collection of MAPI properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
