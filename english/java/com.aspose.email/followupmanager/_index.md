---
title: FollowUpManager
second_title: Aspose.Email for Java API Reference
description:  Provides the ability to set and handle follow-up Outlook flags and categories.
type: docs
weight: 257
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
| [setFlag(MapiMessage message, String flagRequest)](#setFlag-com.aspose.email.MapiMessage-java.lang.String-) | Sets the follow-up flag for a message. |
| [setFlag(MapiMessage message, String flagRequest, Date startDate, Date dueDate)](#setFlag-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-java.util.Date-) | Sets the follow-up flag for a message. |
| [setFlagForRecipients(MapiMessage message, String flagRequest)](#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-) | Sets the flag for a draft message to remind recipients to follow-up. |
| [setFlagForRecipients(MapiMessage message, String flagRequest, Date reminderTime)](#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-) | Sets the flag for a draft message to remind recipients to follow-up. |
| [markAsCompleted(MapiMessage message)](#markAsCompleted-com.aspose.email.MapiMessage-) | Marks the flagged message as completed. |
| [clearFlag(MapiMessage message)](#clearFlag-com.aspose.email.MapiMessage-) | Clears the follow-up flag and reminder. |
| [addCategory(MapiMessage message, String categoryName)](#addCategory-com.aspose.email.MapiMessage-java.lang.String-) | Adds the category for a message. |
| [removeCategory(MapiMessage message, String categoryName)](#removeCategory-com.aspose.email.MapiMessage-java.lang.String-) | Removes the category. |
| [clearCategories(MapiMessage message)](#clearCategories-com.aspose.email.MapiMessage-) | Clears the categories. |
| [getCategories(MapiMessage message)](#getCategories-com.aspose.email.MapiMessage-) | Get the available message categories. |
| [addVotingButton(MapiMessage message, String displayName)](#addVotingButton-com.aspose.email.MapiMessage-java.lang.String-) | Adds the voting button. |
| [clearVotingButtons(MapiMessage message)](#clearVotingButtons-com.aspose.email.MapiMessage-) | Deletes the voting buttons. |
| [removeVotingButton(MapiMessage message, String displayName)](#removeVotingButton-com.aspose.email.MapiMessage-java.lang.String-) | Removes the voting button. |
| [getVotingButtons(MapiMessage message)](#getVotingButtons-com.aspose.email.MapiMessage-) | Get the available message voting buttons. |
| [getVotingButtonsArray(MapiMessage message)](#getVotingButtonsArray-com.aspose.email.MapiMessage-) | Get the available message voting buttons. |
| [setOptions(MapiMessage message, FollowUpOptions options)](#setOptions-com.aspose.email.MapiMessage-com.aspose.email.FollowUpOptions-) | Sets the additional follow-up options for a message. |
| [getOptions(MapiMessage message)](#getOptions-com.aspose.email.MapiMessage-) | Gets the follow-up options of a message. |
### FollowUpManager() {#FollowUpManager--}
```
public FollowUpManager()
```


### setFlag(MapiMessage message, String flagRequest) {#setFlag-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void setFlag(MapiMessage message, String flagRequest)
```


Sets the follow-up flag for a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which a flag will be set. |
| flagRequest | java.lang.String | A string indicating the requested action for an e-mail message. |

### setFlag(MapiMessage message, String flagRequest, Date startDate, Date dueDate) {#setFlag-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-java.util.Date-}
```
public static void setFlag(MapiMessage message, String flagRequest, Date startDate, Date dueDate)
```


Sets the follow-up flag for a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which a flag will be set. |
| flagRequest | java.lang.String | A string indicating the requested action for an e-mail message. |
| startDate | java.util.Date | The start date. |
| dueDate | java.util.Date | The due date. |

### setFlagForRecipients(MapiMessage message, String flagRequest) {#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void setFlagForRecipients(MapiMessage message, String flagRequest)
```


Sets the flag for a draft message to remind recipients to follow-up.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which a flag will be set. |
| flagRequest | java.lang.String | A string indicating the requested action action for recipients of an e-mail message. |

### setFlagForRecipients(MapiMessage message, String flagRequest, Date reminderTime) {#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-}
```
public static void setFlagForRecipients(MapiMessage message, String flagRequest, Date reminderTime)
```


Sets the flag for a draft message to remind recipients to follow-up.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which a flag will be set. |
| flagRequest | java.lang.String | A string indicating the requested action action for recipients of an e-mail message. |
| reminderTime | java.util.Date | A date indicating the date and time at which the reminder should occur. |

### markAsCompleted(MapiMessage message) {#markAsCompleted-com.aspose.email.MapiMessage-}
```
public static void markAsCompleted(MapiMessage message)
```


Marks the flagged message as completed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which a flag is set. |

### clearFlag(MapiMessage message) {#clearFlag-com.aspose.email.MapiMessage-}
```
public static void clearFlag(MapiMessage message)
```


Clears the follow-up flag and reminder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which a flag is set. |

### addCategory(MapiMessage message, String categoryName) {#addCategory-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void addCategory(MapiMessage message, String categoryName)
```


Adds the category for a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which a category will be added. |
| categoryName | java.lang.String | Category name. |

### removeCategory(MapiMessage message, String categoryName) {#removeCategory-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void removeCategory(MapiMessage message, String categoryName)
```


Removes the category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The message. |
| categoryName | java.lang.String | Name of the category. |

### clearCategories(MapiMessage message) {#clearCategories-com.aspose.email.MapiMessage-}
```
public static void clearCategories(MapiMessage message)
```


Clears the categories.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which the categories will be cleared. |

### getCategories(MapiMessage message) {#getCategories-com.aspose.email.MapiMessage-}
```
public static System.Collections.IList getCategories(MapiMessage message)
```


Get the available message categories.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which the categories are added. |

**Returns:**
com.aspose.ms.System.Collections.IList - The list of added categories.
### addVotingButton(MapiMessage message, String displayName) {#addVotingButton-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void addVotingButton(MapiMessage message, String displayName)
```


Adds the voting button.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which the voting button is added. |
| displayName | java.lang.String | The display name of button. |

### clearVotingButtons(MapiMessage message) {#clearVotingButtons-com.aspose.email.MapiMessage-}
```
public static void clearVotingButtons(MapiMessage message)
```


Deletes the voting buttons.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which the categories will be cleared. |

### removeVotingButton(MapiMessage message, String displayName) {#removeVotingButton-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void removeVotingButton(MapiMessage message, String displayName)
```


Removes the voting button.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which the voting button is removed. |
| displayName | java.lang.String | The display name of button. |

### getVotingButtons(MapiMessage message) {#getVotingButtons-com.aspose.email.MapiMessage-}
```
public static System.Collections.IList getVotingButtons(MapiMessage message)
```


Get the available message voting buttons.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which the buttons are added. |

**Returns:**
com.aspose.ms.System.Collections.IList - The list of added voting buttons.
### getVotingButtonsArray(MapiMessage message) {#getVotingButtonsArray-com.aspose.email.MapiMessage-}
```
public static String[] getVotingButtonsArray(MapiMessage message)
```


Get the available message voting buttons.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The \`\`\` MapiMessage \`\`\` in which the buttons are added. |

**Returns:**
java.lang.String[] - The list of added voting buttons.
### setOptions(MapiMessage message, FollowUpOptions options) {#setOptions-com.aspose.email.MapiMessage-com.aspose.email.FollowUpOptions-}
```
public static void setOptions(MapiMessage message, FollowUpOptions options)
```


Sets the additional follow-up options for a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which a flag will be set. |
| options | [FollowUpOptions](../../com.aspose.email/followupoptions) | The [FollowUpOptions](../../com.aspose.email/followupoptions) that represents options for using follow-up flags and reminders. |

### getOptions(MapiMessage message) {#getOptions-com.aspose.email.MapiMessage-}
```
public static FollowUpOptions getOptions(MapiMessage message)
```


Gets the follow-up options of a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The [MapiMessage](../../com.aspose.email/mapimessage) in which options is set. |

**Returns:**
[FollowUpOptions](../../com.aspose.email/followupoptions) - The [FollowUpOptions](../../com.aspose.email/followupoptions) that represents options for using follow-up flags, reminders, category and voting buttons.
