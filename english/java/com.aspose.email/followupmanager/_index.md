---
title: FollowUpManager
second_title: Aspose.Email for Java API Reference
description: Manages Outlook follow-up flags reminders categories and voting buttons of a message.
type: docs
weight: 263
url: /java/com.aspose.email/followupmanager/
---

**Inheritance:**
java.lang.Object
```
public class FollowUpManager
```

Manages Outlook follow-up flags, reminders, categories and voting buttons of a message.

The methods work with any [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) \\u2014 a [MapiMessage](../../com.aspose.email/mapimessage), [MapiContact](../../com.aspose.email/mapicontact), [MapiTask](../../com.aspose.email/mapitask) and so on \\u2014 and write the same MAPI properties that Outlook uses, so the result is shown in Outlook as if it had been set there.

 *  follow-up flags: \#setFlag(MapiMessageItemBase, String).setFlag(MapiMessageItemBase, String), \#setFlagForRecipients(MapiMessageItemBase, String).setFlagForRecipients(MapiMessageItemBase, String), \#markAsCompleted(MapiMessageItemBase).markAsCompleted(MapiMessageItemBase), \#clearFlag(MapiMessageItemBase).clearFlag(MapiMessageItemBase);
 *  several settings at once: \#setOptions(MapiMessageItemBase, FollowUpOptions).setOptions(MapiMessageItemBase, FollowUpOptions) and \#getOptions(MapiMessageItemBase).getOptions(MapiMessageItemBase) with [FollowUpOptions](../../com.aspose.email/followupoptions);
 *  categories: \#addCategory(MapiMessageItemBase, String).addCategory(MapiMessageItemBase, String), \#removeCategory(MapiMessageItemBase, String).removeCategory(MapiMessageItemBase, String), \#getCategories(MapiMessageItemBase).getCategories(MapiMessageItemBase), \#clearCategories(MapiMessageItemBase).clearCategories(MapiMessageItemBase);
 *  voting buttons: \#addVotingButton(MapiMessageItemBase, String).addVotingButton(MapiMessageItemBase, String), \#removeVotingButton(MapiMessageItemBase, String).removeVotingButton(MapiMessageItemBase, String), \#getVotingButtons(MapiMessageItemBase).getVotingButtons(MapiMessageItemBase), \#clearVotingButtons(MapiMessageItemBase).clearVotingButtons(MapiMessageItemBase);
 *  reactions: \#getReactions(MapiMessageItemBase).getReactions(MapiMessageItemBase).

The following example shows how to use FollowUpManager to add follow-up flags and categories to a MAPI message.

```

 // Create a MapiMessage from MailMessage
 MailMessage mailMessage = MailMessage.load("message.eml");
 MapiMessage mapiMessage = MapiMessage.fromMailMessage(mailMessage);

 // Set a follow-up flag
 FollowUpManager.setFlag(mapiMessage, "This is a follow-up message");

 // Set categories
 FollowUpManager.setCategory(mapiMessage, "Important");
 FollowUpManager.setCategory(mapiMessage, "Work");

 // Mark as complete
 FollowUpManager.markAsCompleted(mapiMessage);

 // Save the message with follow-up information
 mapiMessage.save("message_with_flag.msg", SaveOptions.getDefaultMsgUnicode());
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [FollowUpManager()](#FollowUpManager--) |  |
## Methods

| Method | Description |
| --- | --- |
| [addCategory(MapiMessageItemBase message, String categoryName)](#addCategory-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Adds a category to the message. |
| [addVotingButton(MapiMessageItemBase message, String displayName)](#addVotingButton-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Adds a voting button to the message. |
| [clearCategories(MapiMessageItemBase message)](#clearCategories-com.aspose.email.MapiMessageItemBase-) | Removes all categories from the message. |
| [clearFlag(MapiMessageItemBase message)](#clearFlag-com.aspose.email.MapiMessageItemBase-) | Removes the follow-up flag and the reminder from the message. |
| [clearVotingButtons(MapiMessageItemBase message)](#clearVotingButtons-com.aspose.email.MapiMessageItemBase-) | Removes all voting buttons from the message. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategories(MapiMessageItemBase message)](#getCategories-com.aspose.email.MapiMessageItemBase-) | Gets the categories of the message. |
| [getClass()](#getClass--) |  |
| [getOptions(MapiMessageItemBase message)](#getOptions-com.aspose.email.MapiMessageItemBase-) | Gets the follow-up flag, reminder, categories and voting buttons of the message. |
| [getReactions(MapiMessageItemBase message)](#getReactions-com.aspose.email.MapiMessageItemBase-) | Gets the reactions (like, heart and so on) that users have left on the message. |
| [getVotingButtons(MapiMessageItemBase message)](#getVotingButtons-com.aspose.email.MapiMessageItemBase-) | Gets the voting buttons of the message. |
| [getVotingButtonsArray(MapiMessageItemBase message)](#getVotingButtonsArray-com.aspose.email.MapiMessageItemBase-) | Get the available message voting buttons. |
| [hashCode()](#hashCode--) |  |
| [markAsCompleted(MapiMessageItemBase message)](#markAsCompleted-com.aspose.email.MapiMessageItemBase-) | Marks the follow-up flag of the message as completed. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCategory(MapiMessageItemBase message, String categoryName)](#removeCategory-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Removes a category from the message. |
| [removeVotingButton(MapiMessageItemBase message, String displayName)](#removeVotingButton-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Removes a voting button from the message. |
| [setFlag(MapiMessageItemBase message, String flagRequest)](#setFlag-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Sets a follow-up flag on the message. |
| [setFlag(MapiMessageItemBase message, String flagRequest, Date startDate, Date dueDate)](#setFlag-com.aspose.email.MapiMessageItemBase-java.lang.String-java.util.Date-java.util.Date-) | Sets a follow-up flag with a start date and a due date on the message. |
| [setFlagForRecipients(MapiMessageItemBase message, String flagRequest)](#setFlagForRecipients-com.aspose.email.MapiMessageItemBase-java.lang.String-) | Sets a flag on a draft message that reminds its recipients to follow up. |
| [setFlagForRecipients(MapiMessageItemBase message, String flagRequest, Date reminderTime)](#setFlagForRecipients-com.aspose.email.MapiMessageItemBase-java.lang.String-java.util.Date-) | Sets a flag with a reminder on a draft message that reminds its recipients to follow up. |
| [setOptions(MapiMessageItemBase message, FollowUpOptions options)](#setOptions-com.aspose.email.MapiMessageItemBase-com.aspose.email.FollowUpOptions-) | Sets the follow-up flag, reminder, categories and voting buttons of the message in one call. |
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


Adds a category to the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to categorize. |
| categoryName | java.lang.String | The name of the category. |

### addVotingButton(MapiMessageItemBase message, String displayName) {#addVotingButton-com.aspose.email.MapiMessageItemBase-java.lang.String-}
```
public static void addVotingButton(MapiMessageItemBase message, String displayName)
```


Adds a voting button to the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to add the button to. |
| displayName | java.lang.String | The text of the button, for example  Yes . |

### clearCategories(MapiMessageItemBase message) {#clearCategories-com.aspose.email.MapiMessageItemBase-}
```
public static void clearCategories(MapiMessageItemBase message)
```


Removes all categories from the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to clear. |

### clearFlag(MapiMessageItemBase message) {#clearFlag-com.aspose.email.MapiMessageItemBase-}
```
public static void clearFlag(MapiMessageItemBase message)
```


Removes the follow-up flag and the reminder from the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The flagged message. |

### clearVotingButtons(MapiMessageItemBase message) {#clearVotingButtons-com.aspose.email.MapiMessageItemBase-}
```
public static void clearVotingButtons(MapiMessageItemBase message)
```


Removes all voting buttons from the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to remove the buttons from. |

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


Gets the categories of the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to read. |

**Returns:**
com.aspose.ms.System.Collections.IList - The names of the categories; an empty list if the message has none.
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


Gets the follow-up flag, reminder, categories and voting buttons of the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to read. |

**Returns:**
[FollowUpOptions](../../com.aspose.email/followupoptions) - A [FollowUpOptions](../../com.aspose.email/followupoptions) with the follow-up settings of the message.
### getReactions(MapiMessageItemBase message) {#getReactions-com.aspose.email.MapiMessageItemBase-}
```
public static System.Collections.Generic.IGenericList<UserReaction> getReactions(MapiMessageItemBase message)
```


Gets the reactions (like, heart and so on) that users have left on the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to read. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.UserReaction> - The reactions of the message; an empty list if there are none.
### getVotingButtons(MapiMessageItemBase message) {#getVotingButtons-com.aspose.email.MapiMessageItemBase-}
```
public static System.Collections.IList getVotingButtons(MapiMessageItemBase message)
```


Gets the voting buttons of the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to read. |

**Returns:**
com.aspose.ms.System.Collections.IList - The texts of the voting buttons.
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


Marks the follow-up flag of the message as completed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The flagged message. |

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


Removes a category from the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to change. |
| categoryName | java.lang.String | The name of the category to remove. |

### removeVotingButton(MapiMessageItemBase message, String displayName) {#removeVotingButton-com.aspose.email.MapiMessageItemBase-java.lang.String-}
```
public static void removeVotingButton(MapiMessageItemBase message, String displayName)
```


Removes a voting button from the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to change. |
| displayName | java.lang.String | The text of the button to remove. |

### setFlag(MapiMessageItemBase message, String flagRequest) {#setFlag-com.aspose.email.MapiMessageItemBase-java.lang.String-}
```
public static void setFlag(MapiMessageItemBase message, String flagRequest)
```


Sets a follow-up flag on the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to flag. |
| flagRequest | java.lang.String | The requested action that Outlook shows with the flag, for example  Follow up . |

### setFlag(MapiMessageItemBase message, String flagRequest, Date startDate, Date dueDate) {#setFlag-com.aspose.email.MapiMessageItemBase-java.lang.String-java.util.Date-java.util.Date-}
```
public static void setFlag(MapiMessageItemBase message, String flagRequest, Date startDate, Date dueDate)
```


Sets a follow-up flag with a start date and a due date on the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to flag. |
| flagRequest | java.lang.String | The requested action that Outlook shows with the flag, for example  Follow up . |
| startDate | java.util.Date | The date the follow-up starts. |
| dueDate | java.util.Date | The date the follow-up is due. |

### setFlagForRecipients(MapiMessageItemBase message, String flagRequest) {#setFlagForRecipients-com.aspose.email.MapiMessageItemBase-java.lang.String-}
```
public static void setFlagForRecipients(MapiMessageItemBase message, String flagRequest)
```


Sets a flag on a draft message that reminds its recipients to follow up.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The draft message to flag. |
| flagRequest | java.lang.String | The requested action that recipients see with the flag. |

### setFlagForRecipients(MapiMessageItemBase message, String flagRequest, Date reminderTime) {#setFlagForRecipients-com.aspose.email.MapiMessageItemBase-java.lang.String-java.util.Date-}
```
public static void setFlagForRecipients(MapiMessageItemBase message, String flagRequest, Date reminderTime)
```


Sets a flag with a reminder on a draft message that reminds its recipients to follow up.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The draft message to flag. |
| flagRequest | java.lang.String | The requested action that recipients see with the flag. |
| reminderTime | java.util.Date | The date and time the recipients are reminded. |

### setOptions(MapiMessageItemBase message, FollowUpOptions options) {#setOptions-com.aspose.email.MapiMessageItemBase-com.aspose.email.FollowUpOptions-}
```
public static void setOptions(MapiMessageItemBase message, FollowUpOptions options)
```


Sets the follow-up flag, reminder, categories and voting buttons of the message in one call.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | The message to change. |
| options | [FollowUpOptions](../../com.aspose.email/followupoptions) | The settings to apply. |

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

