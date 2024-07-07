---
title: FollowUpManager
second_title: Aspose.Email for Java API Reference
description: Provides the ability to set and handle follow-up Outlook flags and categories.
type: docs
weight: 260
url: /java/com.aspose.email/followupmanager/
---

**Inheritance:**
java.lang.Object
```
public class FollowUpManager
```

Provides the ability to set and handle follow-up Outlook flags and categories. Supports the features to add and remove a flag in [MapiMessage](../../com.aspose.email/mapimessage), and mark it as completed as well.
## Constructors

| Constructor | Description |
| --- | --- |
| [FollowUpManager()](#FollowUpManager--) |  |
## Methods

| Method | Description |
| --- | --- |
| [addCategory(MapiMessageItemBase message, String categoryName)](#addCategory-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Adds the category for a message. |
| [addVotingButton(MapiMessageItemBase message, String displayName)](#addVotingButton-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Adds the voting button. |
| [clearCategories(MapiMessageItemBase message)](#clearCategories-com.aspose.email.MapiMessageItemBase-) | Clears the categories. |
| [clearFlag(MapiMessageItemBase message)](#clearFlag-com.aspose.email.MapiMessageItemBase-) | Clears the follow-up flag and reminder. |
| [clearVotingButtons(MapiMessageItemBase message)](#clearVotingButtons-com.aspose.email.MapiMessageItemBase-) | Deletes the voting buttons. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategories(MapiMessageItemBase message)](#getCategories-com.aspose.email.MapiMessageItemBase-) | Get the available message categories. |
| [getClass()](#getClass--) |  |
| [getOptions(MapiMessageItemBase message)](#getOptions-com.aspose.email.MapiMessageItemBase-) | Gets the follow-up options of a message. |
| [getVotingButtons(MapiMessageItemBase message)](#getVotingButtons-com.aspose.email.MapiMessageItemBase-) | Get the available message voting buttons. |
| [getVotingButtonsArray(MapiMessageItemBase message)](#getVotingButtonsArray-com.aspose.email.MapiMessageItemBase-) | Get the available message voting buttons. |
| [hashCode()](#hashCode--) |  |
| [markAsCompleted(MapiMessageItemBase message)](#markAsCompleted-com.aspose.email.MapiMessageItemBase-) | Marks the flagged message as completed. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCategory(MapiMessageItemBase message, String categoryName)](#removeCategory-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Removes the category. |
| [removeVotingButton(MapiMessageItemBase message, String displayName)](#removeVotingButton-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Removes the voting button. |
| [setFlag(MapiMessageItemBase message, String flagRequest)](#setFlag-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Sets the follow-up flag for a message. |
| [setFlag(MapiMessageItemBase message, String flagRequest, Date startDate, Date dueDate)](#setFlag-com.aspose.email.MapiMessageItemBase-java.lang.String-java.util.Date-java.util.Date-) | Sets the follow-up flag for a message. |
| [setFlagForRecipients(MapiMessageItemBase message, String flagRequest)](#setFlagForRecipients-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Sets the flag for a draft message to remind recipients to follow-up. |
| [setFlagForRecipients(MapiMessageItemBase message, String flagRequest, Date reminderTime)](#setFlagForRecipients-com.aspose.email.MapiMessageItemBase-java.lang.String-java.util.Date-) | Sets the flag for a draft message to remind recipients to follow-up. |
| [setOptions(MapiMessageItemBase message, FollowUpOptions options)](#setOptions-com.aspose.email.MapiMessageItemBase-com.aspose.email.FollowUpOptions-) | Sets the additional follow-up options for a message. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FollowUpManager() {#FollowUpManager--}
```
public FollowUpManager()
```


### addCategory(MapiMessageItemBase message, String categoryName) {#addCategory-com.aspose.email.MapiMessageItemBase-java.lang.String-}
```
public static void addCategory(MapiMessageItemBase message, String categoryName)
```


Adds the category for a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which a category will be added. |
| categoryName | java.lang.String | Category name. |

### addVotingButton(MapiMessageItemBase message, String displayName) {#addVotingButton-com.aspose.email.MapiMessageItemBase-java.lang.String-}
```
public static void addVotingButton(MapiMessageItemBase message, String displayName)
```


Adds the voting button.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which the voting button is added. |
| displayName | java.lang.String | The display name of button. |

### clearCategories(MapiMessageItemBase message) {#clearCategories-com.aspose.email.MapiMessageItemBase-}
```
public static void clearCategories(MapiMessageItemBase message)
```


Clears the categories.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which the categories will be cleared. |

### clearFlag(MapiMessageItemBase message) {#clearFlag-com.aspose.email.MapiMessageItemBase-}
```
public static void clearFlag(MapiMessageItemBase message)
```


Clears the follow-up flag and reminder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which a flag is set. |

### clearVotingButtons(MapiMessageItemBase message) {#clearVotingButtons-com.aspose.email.MapiMessageItemBase-}
```
public static void clearVotingButtons(MapiMessageItemBase message)
```


Deletes the voting buttons.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which the categories will be cleared. |

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
### getCategories(MapiMessageItemBase message) {#getCategories-com.aspose.email.MapiMessageItemBase-}
```
public static System.Collections.IList getCategories(MapiMessageItemBase message)
```


Get the available message categories.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which the categories are added. |

**Returns:**
com.aspose.ms.System.Collections.IList - The list of added categories.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOptions(MapiMessageItemBase message) {#getOptions-com.aspose.email.MapiMessageItemBase-}
```
public static FollowUpOptions getOptions(MapiMessageItemBase message)
```


Gets the follow-up options of a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which options is set. |

**Returns:**
[FollowUpOptions](../../com.aspose.email/followupoptions) - The [FollowUpOptions](../../com.aspose.email/followupoptions) that represents options for using follow-up flags, reminders, category and voting buttons.
### getVotingButtons(MapiMessageItemBase message) {#getVotingButtons-com.aspose.email.MapiMessageItemBase-}
```
public static System.Collections.IList getVotingButtons(MapiMessageItemBase message)
```


Get the available message voting buttons.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which the buttons are added. |

**Returns:**
com.aspose.ms.System.Collections.IList - The list of added voting buttons.
### getVotingButtonsArray(MapiMessageItemBase message) {#getVotingButtonsArray-com.aspose.email.MapiMessageItemBase-}
```
public static String[] getVotingButtonsArray(MapiMessageItemBase message)
```


Get the available message voting buttons.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The  MapiMessageItemBase  in which the buttons are added. |

**Returns:**
java.lang.String[] - The list of added voting buttons.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### markAsCompleted(MapiMessageItemBase message) {#markAsCompleted-com.aspose.email.MapiMessageItemBase-}
```
public static void markAsCompleted(MapiMessageItemBase message)
```


Marks the flagged message as completed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which a flag is set. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeCategory(MapiMessageItemBase message, String categoryName) {#removeCategory-com.aspose.email.MapiMessageItemBase-java.lang.String-}
```
public static void removeCategory(MapiMessageItemBase message, String categoryName)
```


Removes the category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message. |
| categoryName | java.lang.String | Name of the category. |

### removeVotingButton(MapiMessageItemBase message, String displayName) {#removeVotingButton-com.aspose.email.MapiMessageItemBase-java.lang.String-}
```
public static void removeVotingButton(MapiMessageItemBase message, String displayName)
```


Removes the voting button.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which the voting button is removed. |
| displayName | java.lang.String | The display name of button. |

### setFlag(MapiMessageItemBase message, String flagRequest) {#setFlag-com.aspose.email.MapiMessageItemBase-java.lang.String-}
```
public static void setFlag(MapiMessageItemBase message, String flagRequest)
```


Sets the follow-up flag for a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which a flag will be set. |
| flagRequest | java.lang.String | A string indicating the requested action for an e-mail message. |

### setFlag(MapiMessageItemBase message, String flagRequest, Date startDate, Date dueDate) {#setFlag-com.aspose.email.MapiMessageItemBase-java.lang.String-java.util.Date-java.util.Date-}
```
public static void setFlag(MapiMessageItemBase message, String flagRequest, Date startDate, Date dueDate)
```


Sets the follow-up flag for a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which a flag will be set. |
| flagRequest | java.lang.String | A string indicating the requested action for an e-mail message. |
| startDate | java.util.Date | The start date. |
| dueDate | java.util.Date | The due date. |

### setFlagForRecipients(MapiMessageItemBase message, String flagRequest) {#setFlagForRecipients-com.aspose.email.MapiMessageItemBase-java.lang.String-}
```
public static void setFlagForRecipients(MapiMessageItemBase message, String flagRequest)
```


Sets the flag for a draft message to remind recipients to follow-up.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which a flag will be set. |
| flagRequest | java.lang.String | A string indicating the requested action action for recipients of an e-mail message. |

### setFlagForRecipients(MapiMessageItemBase message, String flagRequest, Date reminderTime) {#setFlagForRecipients-com.aspose.email.MapiMessageItemBase-java.lang.String-java.util.Date-}
```
public static void setFlagForRecipients(MapiMessageItemBase message, String flagRequest, Date reminderTime)
```


Sets the flag for a draft message to remind recipients to follow-up.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which a flag will be set. |
| flagRequest | java.lang.String | A string indicating the requested action action for recipients of an e-mail message. |
| reminderTime | java.util.Date | A date indicating the date and time at which the reminder should occur. |

### setOptions(MapiMessageItemBase message, FollowUpOptions options) {#setOptions-com.aspose.email.MapiMessageItemBase-com.aspose.email.FollowUpOptions-}
```
public static void setOptions(MapiMessageItemBase message, FollowUpOptions options)
```


Sets the additional follow-up options for a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) in which a flag will be set. |
| options | [FollowUpOptions](../../com.aspose.email/followupoptions) | The [FollowUpOptions](../../com.aspose.email/followupoptions) that represents options for using follow-up flags and reminders. |

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

