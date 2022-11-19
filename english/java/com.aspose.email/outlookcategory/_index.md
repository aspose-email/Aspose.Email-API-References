---
title: OutlookCategory
second_title: Aspose.Email for Java API Reference
description: Represents a category by which a user can group Outlook items such as messages and events.
type: docs
weight: 545
url: /java/com.aspose.email/outlookcategory/
---

**Inheritance:**
java.lang.Object
```
public class OutlookCategory
```

Represents a category by which a user can group Outlook items such as messages and events. The user defines categories in a master list, and can apply one or more of these user-defined categories to an item. https://docs.microsoft.com/en-us/graph/api/resources/outlookcategory?view=graph-rest-1.0
## Constructors

| Constructor | Description |
| --- | --- |
| [OutlookCategory()](#OutlookCategory--) | Initializes a new instance of the [OutlookCategory](../../com.aspose.email/outlookcategory) class. |
| [OutlookCategory(String displayName, int preset)](#OutlookCategory-java.lang.String-int-) | Initializes a new instance of the [OutlookCategory](../../com.aspose.email/outlookcategory) class. |
| [OutlookCategory(String itemId, String displayName, int preset)](#OutlookCategory-java.lang.String-java.lang.String-int-) | Initializes a new instance of the [OutlookCategory](../../com.aspose.email/outlookcategory) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | String representation of a pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. |
| [getDisplayName()](#getDisplayName--) | A unique name that identifies a category in the user's mailbox. |
| [getId()](#getId--) | Category identifier |
| [getPreset()](#getPreset--) | A pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(String value)](#setColor-java.lang.String-) | String representation of a pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | A unique name that identifies a category in the user's mailbox. |
| [setId(String value)](#setId-java.lang.String-) | Category identifier |
| [setPreset(int value)](#setPreset-int-) | A pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OutlookCategory() {#OutlookCategory--}
```
public OutlookCategory()
```


Initializes a new instance of the [OutlookCategory](../../com.aspose.email/outlookcategory) class.

### OutlookCategory(String displayName, int preset) {#OutlookCategory-java.lang.String-int-}
```
public OutlookCategory(String displayName, int preset)
```


Initializes a new instance of the [OutlookCategory](../../com.aspose.email/outlookcategory) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| displayName | java.lang.String | A unique name that identifies a category in the user's mailbox. |
| preset | int | pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors |

### OutlookCategory(String itemId, String displayName, int preset) {#OutlookCategory-java.lang.String-java.lang.String-int-}
```
public OutlookCategory(String itemId, String displayName, int preset)
```


Initializes a new instance of the [OutlookCategory](../../com.aspose.email/outlookcategory) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemId | java.lang.String | Item id |
| displayName | java.lang.String | A unique name that identifies a category in the user's mailbox. |
| preset | int | pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors |

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
### getColor() {#getColor--}
```
public final String getColor()
```


String representation of a pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. The possible values for color are pre-set constants such as None, preset0 and preset1. Each pre-set constant is further mapped to a color; the actual color is dependent on the Outlook client that the categories are being displayed in.

**Returns:**
java.lang.String
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


A unique name that identifies a category in the user's mailbox. After a category is created, the name cannot be changed.

**Returns:**
java.lang.String
### getId() {#getId--}
```
public final String getId()
```


Category identifier

**Returns:**
java.lang.String
### getPreset() {#getPreset--}
```
public final int getPreset()
```


A pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. Each pre-set constant is further mapped to a color; the actual color is dependent on the Outlook client that the categories are being displayed in.

**Returns:**
int
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




### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


String representation of a pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. The possible values for color are pre-set constants such as None, preset0 and preset1. Each pre-set constant is further mapped to a color; the actual color is dependent on the Outlook client that the categories are being displayed in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


A unique name that identifies a category in the user's mailbox. After a category is created, the name cannot be changed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Category identifier

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```


A pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. Each pre-set constant is further mapped to a color; the actual color is dependent on the Outlook client that the categories are being displayed in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
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

