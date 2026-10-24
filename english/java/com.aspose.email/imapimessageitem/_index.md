---
title: IMapiMessageItem
second_title: Aspose.Email for Java API Reference
description: Defines the base interface for all Outlook message item types including messages appointments tasks contacts and notes.
type: docs
weight: 797
url: /java/com.aspose.email/imapimessageitem/
---
```
public interface IMapiMessageItem
```

Defines the base interface for all Outlook message item types including messages, appointments, tasks, contacts, and notes. This interface provides common properties for accessing message class, item type, body content, and subject across different Outlook item types.

--------------------

Implementing types include [MapiMessage](../../com.aspose.email/mapimessage), [MapiCalendar](../../com.aspose.email/mapicalendar), [MapiTask](../../com.aspose.email/mapitask), [MapiContact](../../com.aspose.email/mapicontact), and other message item types in the Aspose.Email library. The interface provides a consistent way to access common properties regardless of the specific Outlook item type.
## Methods

| Method | Description |
| --- | --- |
| [getBody()](#getBody--) | Gets message body |
| [getMessageClass()](#getMessageClass--) | Gets message class |
| [getSubject()](#getSubject--) | Gets message subject |
| [getSupportedType()](#getSupportedType--) | Gets the supported item type. |
| [setBody(String value)](#setBody-java.lang.String-) | Gets message body |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets message subject |
### getBody() {#getBody--}
```
public abstract String getBody()
```


Gets message body

**Returns:**
java.lang.String
### getMessageClass() {#getMessageClass--}
```
public abstract String getMessageClass()
```


Gets message class

**Returns:**
java.lang.String
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Gets message subject

**Returns:**
java.lang.String
### getSupportedType() {#getSupportedType--}
```
public abstract int getSupportedType()
```


Gets the supported item type.

Value: The [MapiItemType](../../com.aspose.email/mapiitemtype).

**Returns:**
int
### setBody(String value) {#setBody-java.lang.String-}
```
public abstract void setBody(String value)
```


Gets message body

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```


Gets message subject

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

