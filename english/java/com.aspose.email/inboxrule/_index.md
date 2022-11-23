---
title: InboxRule
second_title: Aspose.Email for Java API Reference
description: Represents a inbox rule
type: docs
weight: 333
url: /java/com.aspose.email/inboxrule/
---

**Inheritance:**
java.lang.Object
```
public final class InboxRule
```

Represents a inbox rule
## Constructors

| Constructor | Description |
| --- | --- |
| [InboxRule()](#InboxRule--) | Initializes a new instance of the [InboxRule](../../com.aspose.email/inboxrule) class |
## Methods

| Method | Description |
| --- | --- |
| [createRuleDeleteContaining(String[] filter)](#createRuleDeleteContaining-java.lang.String---) | Creates inbox rule that deletes messages containing the specified strings in either the body or the subject |
| [createRuleDeleteFrom(MailAddress from)](#createRuleDeleteFrom-com.aspose.email.MailAddress-) | Creates inbox rule that deletes messages from specified senders |
| [createRuleMoveContaining(String[] filter, String destinationFolderId)](#createRuleMoveContaining-java.lang.String---java.lang.String-) | Creates inbox rule that moves messages containing the specified strings in either the body or the subject into the specified folder |
| [createRuleMoveFrom(MailAddress from, String destinationFolderId)](#createRuleMoveFrom-com.aspose.email.MailAddress-java.lang.String-) | Creates inbox rule that moves messages from specified senders into the specified folder |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActions()](#getActions--) | Gets or sets the actions to be taken on a message when the conditions are fulfilled. |
| [getClass()](#getClass--) |  |
| [getConditions()](#getConditions--) | Gets or sets the conditions that, when fulfilled, will trigger the rule actions for that rule. |
| [getDisplayName()](#getDisplayName--) | Gets or sets the display name of a rule. |
| [getExceptions()](#getExceptions--) | Gets or sets the exceptions that represent all the available rule exception conditions for the inbox rule. |
| [getPriority()](#getPriority--) | Gets or sets a value that indicates the order in which a rule is to be run. |
| [getRuleId()](#getRuleId--) | Gets or sets the rule identifier. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Gets or sets a value indicating whether the rule is enabled. |
| [isInError()](#isInError--) | Gets a value indicating whether the rule is in an error condition. |
| [isNotSupported()](#isNotSupported--) | Gets a value indicating whether the rule cannot be modified with the managed code APIs. |
| [isReadOnly()](#isReadOnly--) | Gets or sets a value indicating whether the rule is read-only. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActions(RuleActions value)](#setActions-com.aspose.email.RuleActions-) | Gets or sets the actions to be taken on a message when the conditions are fulfilled. |
| [setConditions(RulePredicates value)](#setConditions-com.aspose.email.RulePredicates-) | Gets or sets the conditions that, when fulfilled, will trigger the rule actions for that rule. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Gets or sets the display name of a rule. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Gets or sets a value indicating whether the rule is enabled. |
| [setExceptions(RulePredicates value)](#setExceptions-com.aspose.email.RulePredicates-) | Gets or sets the exceptions that represent all the available rule exception conditions for the inbox rule. |
| [setPriority(int value)](#setPriority-int-) | Gets or sets a value that indicates the order in which a rule is to be run. |
| [setReadOnly(Boolean value)](#setReadOnly-java.lang.Boolean-) | Gets or sets a value indicating whether the rule is read-only. |
| [setRuleId(String value)](#setRuleId-java.lang.String-) | Gets or sets the rule identifier. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InboxRule() {#InboxRule--}
```
public InboxRule()
```


Initializes a new instance of the [InboxRule](../../com.aspose.email/inboxrule) class

### createRuleDeleteContaining(String[] filter) {#createRuleDeleteContaining-java.lang.String---}
```
public static InboxRule createRuleDeleteContaining(String[] filter)
```


Creates inbox rule that deletes messages containing the specified strings in either the body or the subject

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | java.lang.String[] | A strings to search |

**Returns:**
[InboxRule](../../com.aspose.email/inboxrule) - A created [InboxRule](../../com.aspose.email/inboxrule)
### createRuleDeleteFrom(MailAddress from) {#createRuleDeleteFrom-com.aspose.email.MailAddress-}
```
public static InboxRule createRuleDeleteFrom(MailAddress from)
```


Creates inbox rule that deletes messages from specified senders

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | [MailAddress](../../com.aspose.email/mailaddress) | A [EmailAddress](../../com.aspose.email/emailaddress) of sender |

**Returns:**
[InboxRule](../../com.aspose.email/inboxrule) - A created [InboxRule](../../com.aspose.email/inboxrule)
### createRuleMoveContaining(String[] filter, String destinationFolderId) {#createRuleMoveContaining-java.lang.String---java.lang.String-}
```
public static InboxRule createRuleMoveContaining(String[] filter, String destinationFolderId)
```


Creates inbox rule that moves messages containing the specified strings in either the body or the subject into the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | java.lang.String[] | A strings to search |
| destinationFolderId | java.lang.String | An id of folder in which messages will be moved |

**Returns:**
[InboxRule](../../com.aspose.email/inboxrule) - A created [InboxRule](../../com.aspose.email/inboxrule)
### createRuleMoveFrom(MailAddress from, String destinationFolderId) {#createRuleMoveFrom-com.aspose.email.MailAddress-java.lang.String-}
```
public static InboxRule createRuleMoveFrom(MailAddress from, String destinationFolderId)
```


Creates inbox rule that moves messages from specified senders into the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | [MailAddress](../../com.aspose.email/mailaddress) | A [EmailAddress](../../com.aspose.email/emailaddress) of sender |
| destinationFolderId | java.lang.String | An id of folder in which messages will be moved |

**Returns:**
[InboxRule](../../com.aspose.email/inboxrule) - A created [InboxRule](../../com.aspose.email/inboxrule)
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
### getActions() {#getActions--}
```
public final RuleActions getActions()
```


Gets or sets the actions to be taken on a message when the conditions are fulfilled.

**Returns:**
[RuleActions](../../com.aspose.email/ruleactions)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConditions() {#getConditions--}
```
public final RulePredicates getConditions()
```


Gets or sets the conditions that, when fulfilled, will trigger the rule actions for that rule.

**Returns:**
[RulePredicates](../../com.aspose.email/rulepredicates)
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets or sets the display name of a rule.

**Returns:**
java.lang.String
### getExceptions() {#getExceptions--}
```
public final RulePredicates getExceptions()
```


Gets or sets the exceptions that represent all the available rule exception conditions for the inbox rule.

**Returns:**
[RulePredicates](../../com.aspose.email/rulepredicates)
### getPriority() {#getPriority--}
```
public final int getPriority()
```


Gets or sets a value that indicates the order in which a rule is to be run.

**Returns:**
int
### getRuleId() {#getRuleId--}
```
public final String getRuleId()
```


Gets or sets the rule identifier.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Gets or sets a value indicating whether the rule is enabled.

**Returns:**
boolean
### isInError() {#isInError--}
```
public final boolean isInError()
```


Gets a value indicating whether the rule is in an error condition.

**Returns:**
boolean
### isNotSupported() {#isNotSupported--}
```
public final boolean isNotSupported()
```


Gets a value indicating whether the rule cannot be modified with the managed code APIs.

**Returns:**
boolean
### isReadOnly() {#isReadOnly--}
```
public final Boolean isReadOnly()
```


Gets or sets a value indicating whether the rule is read-only.

**Returns:**
java.lang.Boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setActions(RuleActions value) {#setActions-com.aspose.email.RuleActions-}
```
public final void setActions(RuleActions value)
```


Gets or sets the actions to be taken on a message when the conditions are fulfilled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RuleActions](../../com.aspose.email/ruleactions) |  |

### setConditions(RulePredicates value) {#setConditions-com.aspose.email.RulePredicates-}
```
public final void setConditions(RulePredicates value)
```


Gets or sets the conditions that, when fulfilled, will trigger the rule actions for that rule.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RulePredicates](../../com.aspose.email/rulepredicates) |  |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Gets or sets the display name of a rule.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Gets or sets a value indicating whether the rule is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setExceptions(RulePredicates value) {#setExceptions-com.aspose.email.RulePredicates-}
```
public final void setExceptions(RulePredicates value)
```


Gets or sets the exceptions that represent all the available rule exception conditions for the inbox rule.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RulePredicates](../../com.aspose.email/rulepredicates) |  |

### setPriority(int value) {#setPriority-int-}
```
public final void setPriority(int value)
```


Gets or sets a value that indicates the order in which a rule is to be run.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setReadOnly(Boolean value) {#setReadOnly-java.lang.Boolean-}
```
public final void setReadOnly(Boolean value)
```


Gets or sets a value indicating whether the rule is read-only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean |  |

### setRuleId(String value) {#setRuleId-java.lang.String-}
```
public final void setRuleId(String value)
```


Gets or sets the rule identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

