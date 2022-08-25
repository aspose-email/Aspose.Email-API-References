---
title: MessageStore
second_title: Aspose.Email for Java API Reference
description:  Message store is the root of the PST 
 which is the rough equivalent of the top of a Mailbox.
type: docs
weight: 503
url: /java/com.aspose.email/messagestore/
---
**Inheritance:**
java.lang.Object
```
public class MessageStore
```

Message store is the root of the PST, which is the rough equivalent of the top of a Mailbox.
## Methods

| Method | Description |
| --- | --- |
| [getDisplayName()](#getDisplayName--) | Gets the display Name of PST. |
| [getProperties()](#getProperties--) | Gets the MAPI properties of message store object. |
| [isPasswordProtected()](#isPasswordProtected--) | Gets a value indicating whether the storage is password protected. |
| [isPasswordValid(String password)](#isPasswordValid-java.lang.String-) | Determines whether the specified string is a valid password for the storage. |
| [changeDisplayName(String newName)](#changeDisplayName-java.lang.String-) | Changes the pst display name. |
| [changePassword(String password)](#changePassword-java.lang.String-) | Sets the password. |
| [setProperty(MapiProperty property)](#setProperty-com.aspose.email.MapiProperty-) | Sets the property. |
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the display Name of PST.

Value: The string that represents display name.

**Returns:**
java.lang.String
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


Gets the MAPI properties of message store object. The message store contains the top-level PST settings and metadata that are required to access and manage the PST contents.

Value: The [MapiProperty](../../com.aspose.email/mapiproperty) collection.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Gets a value indicating whether the storage is password protected.

Value: \`\`\` true \`\`\` if the storage is password protected; otherwise, \`\`\` false \`\`\`.

**Returns:**
boolean
### isPasswordValid(String password) {#isPasswordValid-java.lang.String-}
```
public final boolean isPasswordValid(String password)
```


Determines whether the specified string is a valid password for the storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password string. |

**Returns:**
boolean
### changeDisplayName(String newName) {#changeDisplayName-java.lang.String-}
```
public final void changeDisplayName(String newName)
```


Changes the pst display name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newName | java.lang.String | The new display name of message store. |

### changePassword(String password) {#changePassword-java.lang.String-}
```
public final void changePassword(String password)
```


Sets the password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The string that represents the password. |

### setProperty(MapiProperty property) {#setProperty-com.aspose.email.MapiProperty-}
```
public final void setProperty(MapiProperty property)
```


Sets the property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | The property. |

