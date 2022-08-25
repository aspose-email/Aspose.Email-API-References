---
title: FollowUpOptions
second_title: Aspose.Email for Android via Java API Reference
description:  Represents options for using follow-up flags and reminders in a message.
type: docs
weight: 145
url: /java/com.aspose.email/followupoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FollowUpOptions
```

Represents options for using follow-up flags and reminders in a message.
## Constructors

| Constructor | Description |
| --- | --- |
| [FollowUpOptions()](#FollowUpOptions--) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class. |
| [FollowUpOptions(String flagRequest)](#FollowUpOptions-java.lang.String-) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class. |
| [FollowUpOptions(String flagRequest, Date startDate, Date dueDate)](#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class. |
| [FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime)](#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-java.util.Date-) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFlagRequest()](#getFlagRequest--) | Gets or sets a string indicating the requested action for an e-mail message. |
| [setFlagRequest(String value)](#setFlagRequest-java.lang.String-) | Gets or sets a string indicating the requested action for an e-mail message. |
| [getStartDate()](#getStartDate--) | Gets or sets a date specifying the starting date and time for the flagged message. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets a date specifying the starting date and time for the flagged message. |
| [getDueDate()](#getDueDate--) | Gets or sets a date indicating the due date for the flagged message. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Gets or sets a date indicating the due date for the flagged message. |
| [getReminderTime()](#getReminderTime--) | Gets or sets a date indicating the date and time at which the reminder should occur. |
| [setReminderTime(Date value)](#setReminderTime-java.util.Date-) | Gets or sets a date indicating the date and time at which the reminder should occur. |
| [getRecipientsFlagRequest()](#getRecipientsFlagRequest--) | Gets or sets a string indicating the requested action for recipients of an e-mail message. |
| [setRecipientsFlagRequest(String value)](#setRecipientsFlagRequest-java.lang.String-) | Gets or sets a string indicating the requested action for recipients of an e-mail message. |
| [getRecipientsReminderTime()](#getRecipientsReminderTime--) | Gets or sets a date for recipients indicating the date and time at which the reminder should occur. |
| [setRecipientsReminderTime(Date value)](#setRecipientsReminderTime-java.util.Date-) | Gets or sets a date for recipients indicating the date and time at which the reminder should occur. |
| [isCompleted()](#isCompleted--) | Gets a value indicating whether the Message object was flagged as completed. |
| [getCategories()](#getCategories--) | Gets or sets string that represents list of the categories, separated by semicolons (;). |
| [setCategories(String value)](#setCategories-java.lang.String-) | Gets or sets string that represents list of the categories, separated by semicolons (;). |
| [getVotingButtons()](#getVotingButtons--) | Gets or sets string that represents list of the voting buttons names, separated by semicolons (;). |
| [setVotingButtons(String value)](#setVotingButtons-java.lang.String-) | Gets or sets string that represents list of the voting buttons names, separated by semicolons (;). |
| [getCodePage()](#getCodePage--) | Gets or sets the code page. |
| [setCodePage(int value)](#setCodePage-int-) | Gets or sets the code page. |
### FollowUpOptions() {#FollowUpOptions--}
```
public FollowUpOptions()
```


Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class.

### FollowUpOptions(String flagRequest) {#FollowUpOptions-java.lang.String-}
```
public FollowUpOptions(String flagRequest)
```


Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flagRequest | java.lang.String | The flag request. |

### FollowUpOptions(String flagRequest, Date startDate, Date dueDate) {#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-}
```
public FollowUpOptions(String flagRequest, Date startDate, Date dueDate)
```


Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flagRequest | java.lang.String | The flag request. |
| startDate | java.util.Date | The start Date. |
| dueDate | java.util.Date | The due Date. |

### FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime) {#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-java.util.Date-}
```
public FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime)
```


Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flagRequest | java.lang.String | The flag request. |
| startDate | java.util.Date | The start date. |
| dueDate | java.util.Date | The due date. |
| reminderTime | java.util.Date | The reminder time. |

### getFlagRequest() {#getFlagRequest--}
```
public final String getFlagRequest()
```


Gets or sets a string indicating the requested action for an e-mail message.

**Returns:**
java.lang.String
### setFlagRequest(String value) {#setFlagRequest-java.lang.String-}
```
public final void setFlagRequest(String value)
```


Gets or sets a string indicating the requested action for an e-mail message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets a date specifying the starting date and time for the flagged message.

**Returns:**
java.util.Date
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets a date specifying the starting date and time for the flagged message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


Gets or sets a date indicating the due date for the flagged message.

**Returns:**
java.util.Date
### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


Gets or sets a date indicating the due date for the flagged message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getReminderTime() {#getReminderTime--}
```
public final Date getReminderTime()
```


Gets or sets a date indicating the date and time at which the reminder should occur.

**Returns:**
java.util.Date
### setReminderTime(Date value) {#setReminderTime-java.util.Date-}
```
public final void setReminderTime(Date value)
```


Gets or sets a date indicating the date and time at which the reminder should occur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getRecipientsFlagRequest() {#getRecipientsFlagRequest--}
```
public final String getRecipientsFlagRequest()
```


Gets or sets a string indicating the requested action for recipients of an e-mail message.

**Returns:**
java.lang.String
### setRecipientsFlagRequest(String value) {#setRecipientsFlagRequest-java.lang.String-}
```
public final void setRecipientsFlagRequest(String value)
```


Gets or sets a string indicating the requested action for recipients of an e-mail message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRecipientsReminderTime() {#getRecipientsReminderTime--}
```
public final Date getRecipientsReminderTime()
```


Gets or sets a date for recipients indicating the date and time at which the reminder should occur.

**Returns:**
java.util.Date
### setRecipientsReminderTime(Date value) {#setRecipientsReminderTime-java.util.Date-}
```
public final void setRecipientsReminderTime(Date value)
```


Gets or sets a date for recipients indicating the date and time at which the reminder should occur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### isCompleted() {#isCompleted--}
```
public final boolean isCompleted()
```


Gets a value indicating whether the Message object was flagged as completed.

**Returns:**
boolean
### getCategories() {#getCategories--}
```
public final String getCategories()
```


Gets or sets string that represents list of the categories, separated by semicolons (;).

**Returns:**
java.lang.String
### setCategories(String value) {#setCategories-java.lang.String-}
```
public final void setCategories(String value)
```


Gets or sets string that represents list of the categories, separated by semicolons (;).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getVotingButtons() {#getVotingButtons--}
```
public final String getVotingButtons()
```


Gets or sets string that represents list of the voting buttons names, separated by semicolons (;).

**Returns:**
java.lang.String
### setVotingButtons(String value) {#setVotingButtons-java.lang.String-}
```
public final void setVotingButtons(String value)
```


Gets or sets string that represents list of the voting buttons names, separated by semicolons (;).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCodePage() {#getCodePage--}
```
public final int getCodePage()
```


Gets or sets the code page.

**Returns:**
int
### setCodePage(int value) {#setCodePage-int-}
```
public final void setCodePage(int value)
```


Gets or sets the code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

