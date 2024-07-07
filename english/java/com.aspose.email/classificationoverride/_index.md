---
title: ClassificationOverride
second_title: Aspose.Email for Java API Reference
description: Represents a users override for how incoming messages from a specific sender should always be classified as.
type: docs
weight: 106
url: /java/com.aspose.email/classificationoverride/
---

**Inheritance:**
java.lang.Object
```
public class ClassificationOverride
```

Represents a user's override for how incoming messages from a specific sender should always be classified as.
## Constructors

| Constructor | Description |
| --- | --- |
| [ClassificationOverride()](#ClassificationOverride--) | Initalizes static members of class [ClassificationOverride](../../com.aspose.email/classificationoverride). |
| [ClassificationOverride(MailAddress sender, int classifyAs)](#ClassificationOverride-com.aspose.email.MailAddress-int-) | Initalizes static members of class [ClassificationOverride](../../com.aspose.email/classificationoverride). |
| [ClassificationOverride(String id, MailAddress sender, int classifyAs)](#ClassificationOverride-java.lang.String-com.aspose.email.MailAddress-int-) | Initalizes static members of class [ClassificationOverride](../../com.aspose.email/classificationoverride). |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClassifyAs()](#getClassifyAs--) | Gets or sets value which specifies how incoming messages from a specific sender should always be classified as. |
| [getId()](#getId--) | Gets or sets unique identifier of the override. |
| [getSender()](#getSender--) | Gets or sets email address information of the sender for whom the override is created. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClassifyAs(int value)](#setClassifyAs-int-) | Gets or sets value which specifies how incoming messages from a specific sender should always be classified as. |
| [setId(String value)](#setId-java.lang.String-) | Gets or sets unique identifier of the override. |
| [setSender(MailAddress value)](#setSender-com.aspose.email.MailAddress-) | Gets or sets email address information of the sender for whom the override is created. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ClassificationOverride() {#ClassificationOverride--}
```
public ClassificationOverride()
```


Initalizes static members of class [ClassificationOverride](../../com.aspose.email/classificationoverride).

### ClassificationOverride(MailAddress sender, int classifyAs) {#ClassificationOverride-com.aspose.email.MailAddress-int-}
```
public ClassificationOverride(MailAddress sender, int classifyAs)
```


Initalizes static members of class [ClassificationOverride](../../com.aspose.email/classificationoverride).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | [MailAddress](../../com.aspose.email/mailaddress) | Email address information of the sender for whom the override is created. |
| classifyAs | int | Value which specifies how incoming messages from a specific sender should always be classified as. |

### ClassificationOverride(String id, MailAddress sender, int classifyAs) {#ClassificationOverride-java.lang.String-com.aspose.email.MailAddress-int-}
```
public ClassificationOverride(String id, MailAddress sender, int classifyAs)
```


Initalizes static members of class [ClassificationOverride](../../com.aspose.email/classificationoverride).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The unique identifier of the override. |
| sender | [MailAddress](../../com.aspose.email/mailaddress) | Email address information of the sender for whom the override is created. |
| classifyAs | int | Value which specifies how incoming messages from a specific sender should always be classified as. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassifyAs() {#getClassifyAs--}
```
public final int getClassifyAs()
```


Gets or sets value which specifies how incoming messages from a specific sender should always be classified as.

**Returns:**
int
### getId() {#getId--}
```
public final String getId()
```


Gets or sets unique identifier of the override.

**Returns:**
java.lang.String
### getSender() {#getSender--}
```
public final MailAddress getSender()
```


Gets or sets email address information of the sender for whom the override is created.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClassifyAs(int value) {#setClassifyAs-int-}
```
public final void setClassifyAs(int value)
```


Gets or sets value which specifies how incoming messages from a specific sender should always be classified as.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Gets or sets unique identifier of the override.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSender(MailAddress value) {#setSender-com.aspose.email.MailAddress-}
```
public final void setSender(MailAddress value)
```


Gets or sets email address information of the sender for whom the override is created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

