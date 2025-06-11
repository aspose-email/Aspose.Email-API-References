---
title: GraphCalendarInfo
second_title: Aspose.Email for Java API Reference
description: Represents information about calendar.
type: docs
weight: 284
url: /java/com.aspose.email/graphcalendarinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.BaseRestObject](../../com.aspose.email/baserestobject)
```
public class GraphCalendarInfo extends BaseRestObject
```

Represents information about calendar.
## Methods

| Method | Description |
| --- | --- |
| [canEdit()](#canEdit--) | true if the user can write to the calendar, false otherwise. |
| [canEdit(boolean value)](#canEdit-boolean-) | true if the user can write to the calendar, false otherwise. |
| [canShare()](#canShare--) | true if the user has the permission to share the calendar, false otherwise. |
| [canShare(boolean value)](#canShare-boolean-) | true if the user has the permission to share the calendar, false otherwise. |
| [canViewPrivateItems()](#canViewPrivateItems--) | true if the user can read calendar items that have been marked private, false otherwise. |
| [canViewPrivateItems(boolean value)](#canViewPrivateItems-boolean-) | true if the user can read calendar items that have been marked private, false otherwise. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Specifies the color theme to distinguish the calendar from other calendars in a UI. |
| [getDefaultOnlineMeetingProvider()](#getDefaultOnlineMeetingProvider--) | The default online meeting provider for meetings sent from this calendar. |
| [getItemId()](#getItemId--) | Gets string representation of entry ID. |
| [getName()](#getName--) | Gets or sets the name of Calendar. |
| [getOwner()](#getOwner--) | If set, this represents the user who created or added the calendar. |
| [getProperties()](#getProperties--) | Gets the mapi properties. |
| [hashCode()](#hashCode--) |  |
| [isDefaultCalendar()](#isDefaultCalendar--) | true if this is the default calendar where new events are created by default, false otherwise. |
| [isRemovable()](#isRemovable--) | Indicates whether this user calendar can be deleted from the user mailbox. |
| [isTallyingResponses()](#isTallyingResponses--) | Indicates whether this user calendar supports tracking of meeting responses. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(int value)](#setColor-int-) | Specifies the color theme to distinguish the calendar from other calendars in a UI. |
| [setDefaultCalendar(boolean value)](#setDefaultCalendar-boolean-) | true if this is the default calendar where new events are created by default, false otherwise. |
| [setDefaultOnlineMeetingProvider(int value)](#setDefaultOnlineMeetingProvider-int-) | The default online meeting provider for meetings sent from this calendar. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the name of Calendar. |
| [setOwner(MailAddress value)](#setOwner-com.aspose.email.MailAddress-) | If set, this represents the user who created or added the calendar. |
| [setRemovable(boolean value)](#setRemovable-boolean-) | Indicates whether this user calendar can be deleted from the user mailbox. |
| [setTallyingResponses(boolean value)](#setTallyingResponses-boolean-) | Indicates whether this user calendar supports tracking of meeting responses. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### canEdit() {#canEdit--}
```
public final boolean canEdit()
```


true if the user can write to the calendar, false otherwise.

**Returns:**
boolean
### canEdit(boolean value) {#canEdit-boolean-}
```
public final void canEdit(boolean value)
```


true if the user can write to the calendar, false otherwise.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### canShare() {#canShare--}
```
public final boolean canShare()
```


true if the user has the permission to share the calendar, false otherwise. Only the user who created the calendar can share it.

**Returns:**
boolean
### canShare(boolean value) {#canShare-boolean-}
```
public final void canShare(boolean value)
```


true if the user has the permission to share the calendar, false otherwise. Only the user who created the calendar can share it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### canViewPrivateItems() {#canViewPrivateItems--}
```
public final boolean canViewPrivateItems()
```


true if the user can read calendar items that have been marked private, false otherwise.

**Returns:**
boolean
### canViewPrivateItems(boolean value) {#canViewPrivateItems-boolean-}
```
public final void canViewPrivateItems(boolean value)
```


true if the user can read calendar items that have been marked private, false otherwise.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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
public final int getColor()
```


Specifies the color theme to distinguish the calendar from other calendars in a UI. The property values are: auto, lightBlue, lightGreen, lightOrange, lightGray, lightYellow, lightTeal, lightPink, lightBrown, lightRed, maxColor.

**Returns:**
int
### getDefaultOnlineMeetingProvider() {#getDefaultOnlineMeetingProvider--}
```
public final int getDefaultOnlineMeetingProvider()
```


The default online meeting provider for meetings sent from this calendar. Possible values are: unknown, skypeForBusiness, skypeForConsumer, teamsForBusiness.

**Returns:**
int
### getItemId() {#getItemId--}
```
public String getItemId()
```


Gets string representation of entry ID.

Value: The entry id string.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


Gets or sets the name of Calendar.

**Returns:**
java.lang.String
### getOwner() {#getOwner--}
```
public final MailAddress getOwner()
```


If set, this represents the user who created or added the calendar. For a calendar that the user created or added, the owner property is set to the user. For a calendar shared with the user, the owner property is set to the person who shared that calendar with the user.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Gets the mapi properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefaultCalendar() {#isDefaultCalendar--}
```
public final boolean isDefaultCalendar()
```


true if this is the default calendar where new events are created by default, false otherwise.

**Returns:**
boolean
### isRemovable() {#isRemovable--}
```
public final boolean isRemovable()
```


Indicates whether this user calendar can be deleted from the user mailbox.

**Returns:**
boolean
### isTallyingResponses() {#isTallyingResponses--}
```
public final boolean isTallyingResponses()
```


Indicates whether this user calendar supports tracking of meeting responses. Only meeting invites sent from users' primary calendars support tracking of meeting responses.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setColor(int value) {#setColor-int-}
```
public final void setColor(int value)
```


Specifies the color theme to distinguish the calendar from other calendars in a UI. The property values are: auto, lightBlue, lightGreen, lightOrange, lightGray, lightYellow, lightTeal, lightPink, lightBrown, lightRed, maxColor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDefaultCalendar(boolean value) {#setDefaultCalendar-boolean-}
```
public final void setDefaultCalendar(boolean value)
```


true if this is the default calendar where new events are created by default, false otherwise.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDefaultOnlineMeetingProvider(int value) {#setDefaultOnlineMeetingProvider-int-}
```
public final void setDefaultOnlineMeetingProvider(int value)
```


The default online meeting provider for meetings sent from this calendar. Possible values are: unknown, skypeForBusiness, skypeForConsumer, teamsForBusiness.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Gets or sets the name of Calendar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setOwner(MailAddress value) {#setOwner-com.aspose.email.MailAddress-}
```
public final void setOwner(MailAddress value)
```


If set, this represents the user who created or added the calendar. For a calendar that the user created or added, the owner property is set to the user. For a calendar shared with the user, the owner property is set to the person who shared that calendar with the user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setRemovable(boolean value) {#setRemovable-boolean-}
```
public final void setRemovable(boolean value)
```


Indicates whether this user calendar can be deleted from the user mailbox.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTallyingResponses(boolean value) {#setTallyingResponses-boolean-}
```
public final void setTallyingResponses(boolean value)
```


Indicates whether this user calendar supports tracking of meeting responses. Only meeting invites sent from users' primary calendars support tracking of meeting responses.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

