---
title: IMapiMessageItem
second_title: Aspose.Email for Java API Reference
description: The common interface of Outlook items messages appointments tasks contacts notes journal entries and distribution lists.
type: docs
weight: 797
url: /java/com.aspose.email/imapimessageitem/
---
```
public interface IMapiMessageItem
```

The common interface of Outlook items: messages, appointments, tasks, contacts, notes, journal entries and distribution lists.

Implemented by [MapiMessage](../../com.aspose.email/mapimessage) and by the item classes derived from [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase). [MapiMessage.toMapiMessageItem()](../../com.aspose.email/mapimessage\#toMapiMessageItem--) returns the item class that matches the message class, so check \#getSupportedType().getSupportedType() or the run-time type of the result.
## Methods

| Method | Description |
| --- | --- |
| [getBody()](#getBody--) | Gets the plain-text body of the item. |
| [getMessageClass()](#getMessageClass--) | Gets the message class of the item, such as  IPM.Note  or  IPM.Contact . |
| [getSubject()](#getSubject--) | Gets the subject of the item. |
| [getSupportedType()](#getSupportedType--) | Gets the type of the item, as determined by its message class. |
| [setBody(String value)](#setBody-java.lang.String-) | Sets the plain-text body of the item. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the item. |
### getBody() {#getBody--}
```
public abstract String getBody()
```


Gets the plain-text body of the item.

**Returns:**
java.lang.String
### getMessageClass() {#getMessageClass--}
```
public abstract String getMessageClass()
```


Gets the message class of the item, such as  IPM.Note  or  IPM.Contact .

**Returns:**
java.lang.String
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Gets the subject of the item.

**Returns:**
java.lang.String
### getSupportedType() {#getSupportedType--}
```
public abstract int getSupportedType()
```


Gets the type of the item, as determined by its message class.

**Returns:**
int - The [MapiItemType](../../com.aspose.email/mapiitemtype).
### setBody(String value) {#setBody-java.lang.String-}
```
public abstract void setBody(String value)
```


Sets the plain-text body of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```


Sets the subject of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

