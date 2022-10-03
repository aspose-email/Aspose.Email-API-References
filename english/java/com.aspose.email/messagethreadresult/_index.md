---
title: MessageThreadResult
second_title: Aspose.Email for Java API Reference
description: Contains result for SORT ot THREAD methods See more https//tools.ietf.org/html/rfc5256
type: docs
weight: 504
url: /java/com.aspose.email/messagethreadresult/
---
**Inheritance:**
java.lang.Object
```
public final class MessageThreadResult
```

Contains result for SORT ot THREAD methods See more: https://tools.ietf.org/html/rfc5256
## Constructors

| Constructor | Description |
| --- | --- |
| [MessageThreadResult()](#MessageThreadResult--) | Initializes a new instance of the [MessageThreadResult](../../com.aspose.email/messagethreadresult) class. |
## Methods

| Method | Description |
| --- | --- |
| [getUseUId()](#getUseUId--) | Gets value which is indicates whether UID kind of method has to be used. |
| [getSequenceNumber()](#getSequenceNumber--) | Gets the message sequence number. |
| [getUniqueId()](#getUniqueId--) | Gets the message unique ID. |
| [getChildMessages()](#getChildMessages--) | Child messages. |
| [getConversationId()](#getConversationId--) | Message thread identifier. |
| [setConversationId(String value)](#setConversationId-java.lang.String-) | Message thread identifier. |
| [toString()](#toString--) | To String |
### MessageThreadResult() {#MessageThreadResult--}
```
public MessageThreadResult()
```


Initializes a new instance of the [MessageThreadResult](../../com.aspose.email/messagethreadresult) class.

### getUseUId() {#getUseUId--}
```
public final boolean getUseUId()
```


Gets value which is indicates whether UID kind of method has to be used.

**Returns:**
boolean
### getSequenceNumber() {#getSequenceNumber--}
```
public final int getSequenceNumber()
```


Gets the message sequence number.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Gets the message unique ID.

**Returns:**
java.lang.String
### getChildMessages() {#getChildMessages--}
```
public final List<MessageThreadResult> getChildMessages()
```


Child messages.

**Returns:**
java.util.List<com.aspose.email.MessageThreadResult>
### getConversationId() {#getConversationId--}
```
public final String getConversationId()
```


Message thread identifier.

**Returns:**
java.lang.String
### setConversationId(String value) {#setConversationId-java.lang.String-}
```
public final void setConversationId(String value)
```


Message thread identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


To String

**Returns:**
java.lang.String - 
