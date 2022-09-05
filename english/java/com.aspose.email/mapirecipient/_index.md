---
title: MapiRecipient
second_title: Aspose.Email for Java API Reference
description:  Represents the recipient information in the Microsoft Outlook Message.
type: docs
weight: 461
url: /java/com.aspose.email/mapirecipient/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer)
```
public class MapiRecipient extends MapiPropertyContainer
```

Represents the recipient information in the Microsoft Outlook Message.
## Methods

| Method | Description |
| --- | --- |
| [getDisplayName()](#getDisplayName--) | Gets or sets the display name of the message recipient or sender. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Gets or sets the display name of the message recipient or sender. |
| [getAddressType()](#getAddressType--) | Gets the type of the address of the message recipient or sender. |
| [getEmailAddress()](#getEmailAddress--) | Gets or sets the email address of the message recipient or sender. |
| [setEmailAddress(String value)](#setEmailAddress-java.lang.String-) | Gets or sets the email address of the message recipient or sender. |
| [getOrganizationEmailAddress()](#getOrganizationEmailAddress--) | Gets the organization email address. |
| [getRecipientType()](#getRecipientType--) | Gets the type of the recipient or sender. |
| [getRecipientClass()](#getRecipientClass--) | Gets the type of recipent. |
| [getPropertyStream()](#getPropertyStream--) | Gets the property stream. |
| [getSubStorages()](#getSubStorages--) | Gets the sub storages. |
| [getContent()](#getContent--) | Gets the content. |
| [getRecipientTrackStatus()](#getRecipientTrackStatus--) | Status of recipient\\u2019s response to a meeting request. |
| [setRecipientTrackStatus(int value)](#setRecipientTrackStatus-int-) | Status of recipient\\u2019s response to a meeting request. |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of message. |
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets or sets the display name of the message recipient or sender.

Value: The display name.

--------------------

When setting a value, the values of either MapiMessage.DisplayTo or MapiMessage.DisplayBcc or MapiMessage.DisplayCC are also updated depending on the type of recepient.

**Returns:**
java.lang.String
### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Gets or sets the display name of the message recipient or sender.

Value: The display name.

--------------------

When setting a value, the values of either MapiMessage.DisplayTo or MapiMessage.DisplayBcc or MapiMessage.DisplayCC are also updated depending on the type of recepient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAddressType() {#getAddressType--}
```
public final String getAddressType()
```


Gets the type of the address of the message recipient or sender.

Value: The address type.

--------------------

This property indicates the type for PR\_EMAIL\_ADDRESS mapi property.

**Returns:**
java.lang.String
### getEmailAddress() {#getEmailAddress--}
```
public final String getEmailAddress()
```


Gets or sets the email address of the message recipient or sender.

**Returns:**
java.lang.String
### setEmailAddress(String value) {#setEmailAddress-java.lang.String-}
```
public final void setEmailAddress(String value)
```


Gets or sets the email address of the message recipient or sender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOrganizationEmailAddress() {#getOrganizationEmailAddress--}
```
public final String getOrganizationEmailAddress()
```


Gets the organization email address.

Value: The organization email address.

**Returns:**
java.lang.String
### getRecipientType() {#getRecipientType--}
```
public final int getRecipientType()
```


Gets the type of the recipient or sender.

Value: The recipient type.

**Returns:**
int
### getRecipientClass() {#getRecipientClass--}
```
public final int getRecipientClass()
```


Gets the type of recipent.

Value: The recipient class.

**Returns:**
int
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Gets the property stream.

Value: The property stream.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream)
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Gets the sub storages.

Value: The sub storages.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getContent() {#getContent--}
```
public final Object getContent()
```


Gets the content.

Value: The content.

**Returns:**
java.lang.Object
### getRecipientTrackStatus() {#getRecipientTrackStatus--}
```
public final int getRecipientTrackStatus()
```


Status of recipient\\u2019s response to a meeting request.

**Returns:**
int
### setRecipientTrackStatus(int value) {#setRecipientTrackStatus-int-}
```
public final void setRecipientTrackStatus(int value)
```


Status of recipient\\u2019s response to a meeting request.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### createMapiNode(String key) {#createMapiNode-java.lang.String-}
```
public IMapiNode createMapiNode(String key)
```


Creates the mapi node.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The node key. |

**Returns:**
com.aspose.email.IMapiNode - The IMapiNode interface.
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of message.

Value: The collection of named properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
