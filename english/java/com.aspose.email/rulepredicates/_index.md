---
title: RulePredicates
second_title: Aspose.Email for Java API Reference
description: Represents rule predicate
type: docs
weight: 615
url: /java/com.aspose.email/rulepredicates/
---

**Inheritance:**
java.lang.Object
```
public final class RulePredicates
```

Represents rule predicate
## Constructors

| Constructor | Description |
| --- | --- |
| [RulePredicates()](#RulePredicates--) | Initializes a new instance of the [RulePredicates](../../com.aspose.email/rulepredicates) class |
## Methods

| Method | Description |
| --- | --- |
| [containsBodyStrings()](#containsBodyStrings--) | Gets or sets the strings that appear in the body of incoming messages in order for the condition or exception to apply. |
| [containsBodyStrings(System.Collections.Specialized.StringCollection value)](#containsBodyStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets the strings that appear in the body of incoming messages in order for the condition or exception to apply. |
| [containsHeaderStrings()](#containsHeaderStrings--) | Gets or sets the strings that appear in the headers of incoming messages in order for the condition or exception to apply. |
| [containsHeaderStrings(System.Collections.Specialized.StringCollection value)](#containsHeaderStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets the strings that appear in the headers of incoming messages in order for the condition or exception to apply. |
| [containsRecipientStrings()](#containsRecipientStrings--) | Gets or sets the strings that appear in either the ToRecipients or CcRecipients properties of incoming messages in order for the condition or exception to apply. |
| [containsRecipientStrings(System.Collections.Specialized.StringCollection value)](#containsRecipientStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets the strings that appear in either the ToRecipients or CcRecipients properties of incoming messages in order for the condition or exception to apply. |
| [containsSenderStrings()](#containsSenderStrings--) | Gets or sets the strings that appears in the From property of incoming messages in order for the condition or exception to apply |
| [containsSenderStrings(System.Collections.Specialized.StringCollection value)](#containsSenderStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets the strings that appears in the From property of incoming messages in order for the condition or exception to apply |
| [containsSubjectOrBodyStrings()](#containsSubjectOrBodyStrings--) | Gets or sets the strings that appear in either the body or the subject of incoming messages in order for the condition or exception to apply. |
| [containsSubjectOrBodyStrings(System.Collections.Specialized.StringCollection value)](#containsSubjectOrBodyStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets the strings that appear in either the body or the subject of incoming messages in order for the condition or exception to apply. |
| [containsSubjectStrings()](#containsSubjectStrings--) | Gets or sets the strings that appear in the subject of incoming messages in order for the condition or exception to apply. |
| [containsSubjectStrings(System.Collections.Specialized.StringCollection value)](#containsSubjectStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets the strings that appear in the subject of incoming messages in order for the condition or exception to apply. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategories()](#getCategories--) | Gets or sets the categories that an incoming message is labeled with in order for the condition or exception to apply. |
| [getClass()](#getClass--) |  |
| [getFlaggedForAction()](#getFlaggedForAction--) | Gets or sets the flag for action value that appears on incoming messages in order for the condition or exception to apply. |
| [getFromAddresses()](#getFromAddresses--) | Gets or sets the e-mail addresses of the senders of incoming messages in order for the condition or exception to apply. |
| [getFromConnectedAccounts()](#getFromConnectedAccounts--) | Gets or sets the e-mail account names from which incoming messages have to have been aggregated in order for the condition or exception to apply. |
| [getImportance()](#getImportance--) | Gets or sets the importance that is stamped on incoming messages in order for the condition or exception to apply. |
| [getItemClasses()](#getItemClasses--) | Gets or sets the item classes that must be stamped on incoming messages in order for the condition or exception to apply. |
| [getMessageClassifications()](#getMessageClassifications--) | Gets or sets the message classifications that must be stamped on incoming messages in order for the condition or exception to apply. |
| [getRulePredicateFlags()](#getRulePredicateFlags--) | Gets or sets rule predicate flags |
| [getSensitivity()](#getSensitivity--) | Gets or sets the sensitivity that must be stamped on incoming messages in order for the condition or exception to apply. |
| [getSentToAddresses()](#getSentToAddresses--) | Gets or sets the e-mail addresses that incoming messages have to have been sent to in order for the condition or exception to apply. |
| [getWithinDateRange()](#getWithinDateRange--) | Gets or sets the date range within which incoming messages have to have been received in order for the condition or exception to apply. |
| [getWithinSizeRange()](#getWithinSizeRange--) | Gets or sets the minimum and maximum sizes that incoming messages have to have in order for the condition or exception to apply. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCategories(System.Collections.Specialized.StringCollection value)](#setCategories-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets the categories that an incoming message is labeled with in order for the condition or exception to apply. |
| [setFlaggedForAction(int value)](#setFlaggedForAction-int-) | Gets or sets the flag for action value that appears on incoming messages in order for the condition or exception to apply. |
| [setFromAddresses(MailAddressCollection value)](#setFromAddresses-com.aspose.email.MailAddressCollection-) | Gets or sets the e-mail addresses of the senders of incoming messages in order for the condition or exception to apply. |
| [setFromConnectedAccounts(System.Collections.Specialized.StringCollection value)](#setFromConnectedAccounts-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets the e-mail account names from which incoming messages have to have been aggregated in order for the condition or exception to apply. |
| [setImportance(int value)](#setImportance-int-) | Gets or sets the importance that is stamped on incoming messages in order for the condition or exception to apply. |
| [setItemClasses(System.Collections.Specialized.StringCollection value)](#setItemClasses-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets the item classes that must be stamped on incoming messages in order for the condition or exception to apply. |
| [setMessageClassifications(System.Collections.Specialized.StringCollection value)](#setMessageClassifications-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets the message classifications that must be stamped on incoming messages in order for the condition or exception to apply. |
| [setRulePredicateFlags(int value)](#setRulePredicateFlags-int-) | Gets or sets rule predicate flags |
| [setSensitivity(int value)](#setSensitivity-int-) | Gets or sets the sensitivity that must be stamped on incoming messages in order for the condition or exception to apply. |
| [setSentToAddresses(MailAddressCollection value)](#setSentToAddresses-com.aspose.email.MailAddressCollection-) | Gets or sets the e-mail addresses that incoming messages have to have been sent to in order for the condition or exception to apply. |
| [setWithinDateRange(DateRange value)](#setWithinDateRange-com.aspose.email.DateRange-) | Gets or sets the date range within which incoming messages have to have been received in order for the condition or exception to apply. |
| [setWithinSizeRange(SizeRange value)](#setWithinSizeRange-com.aspose.email.SizeRange-) | Gets or sets the minimum and maximum sizes that incoming messages have to have in order for the condition or exception to apply. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RulePredicates() {#RulePredicates--}
```
public RulePredicates()
```


Initializes a new instance of the [RulePredicates](../../com.aspose.email/rulepredicates) class

### containsBodyStrings() {#containsBodyStrings--}
```
public final System.Collections.Specialized.StringCollection containsBodyStrings()
```


Gets or sets the strings that appear in the body of incoming messages in order for the condition or exception to apply.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### containsBodyStrings(System.Collections.Specialized.StringCollection value) {#containsBodyStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void containsBodyStrings(System.Collections.Specialized.StringCollection value)
```


Gets or sets the strings that appear in the body of incoming messages in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### containsHeaderStrings() {#containsHeaderStrings--}
```
public final System.Collections.Specialized.StringCollection containsHeaderStrings()
```


Gets or sets the strings that appear in the headers of incoming messages in order for the condition or exception to apply.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### containsHeaderStrings(System.Collections.Specialized.StringCollection value) {#containsHeaderStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void containsHeaderStrings(System.Collections.Specialized.StringCollection value)
```


Gets or sets the strings that appear in the headers of incoming messages in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### containsRecipientStrings() {#containsRecipientStrings--}
```
public final System.Collections.Specialized.StringCollection containsRecipientStrings()
```


Gets or sets the strings that appear in either the ToRecipients or CcRecipients properties of incoming messages in order for the condition or exception to apply.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### containsRecipientStrings(System.Collections.Specialized.StringCollection value) {#containsRecipientStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void containsRecipientStrings(System.Collections.Specialized.StringCollection value)
```


Gets or sets the strings that appear in either the ToRecipients or CcRecipients properties of incoming messages in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### containsSenderStrings() {#containsSenderStrings--}
```
public final System.Collections.Specialized.StringCollection containsSenderStrings()
```


Gets or sets the strings that appears in the From property of incoming messages in order for the condition or exception to apply

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### containsSenderStrings(System.Collections.Specialized.StringCollection value) {#containsSenderStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void containsSenderStrings(System.Collections.Specialized.StringCollection value)
```


Gets or sets the strings that appears in the From property of incoming messages in order for the condition or exception to apply

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### containsSubjectOrBodyStrings() {#containsSubjectOrBodyStrings--}
```
public final System.Collections.Specialized.StringCollection containsSubjectOrBodyStrings()
```


Gets or sets the strings that appear in either the body or the subject of incoming messages in order for the condition or exception to apply.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### containsSubjectOrBodyStrings(System.Collections.Specialized.StringCollection value) {#containsSubjectOrBodyStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void containsSubjectOrBodyStrings(System.Collections.Specialized.StringCollection value)
```


Gets or sets the strings that appear in either the body or the subject of incoming messages in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### containsSubjectStrings() {#containsSubjectStrings--}
```
public final System.Collections.Specialized.StringCollection containsSubjectStrings()
```


Gets or sets the strings that appear in the subject of incoming messages in order for the condition or exception to apply.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### containsSubjectStrings(System.Collections.Specialized.StringCollection value) {#containsSubjectStrings-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void containsSubjectStrings(System.Collections.Specialized.StringCollection value)
```


Gets or sets the strings that appear in the subject of incoming messages in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

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
### getCategories() {#getCategories--}
```
public final System.Collections.Specialized.StringCollection getCategories()
```


Gets or sets the categories that an incoming message is labeled with in order for the condition or exception to apply.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFlaggedForAction() {#getFlaggedForAction--}
```
public final int getFlaggedForAction()
```


Gets or sets the flag for action value that appears on incoming messages in order for the condition or exception to apply.

**Returns:**
int
### getFromAddresses() {#getFromAddresses--}
```
public final MailAddressCollection getFromAddresses()
```


Gets or sets the e-mail addresses of the senders of incoming messages in order for the condition or exception to apply.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getFromConnectedAccounts() {#getFromConnectedAccounts--}
```
public final System.Collections.Specialized.StringCollection getFromConnectedAccounts()
```


Gets or sets the e-mail account names from which incoming messages have to have been aggregated in order for the condition or exception to apply.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getImportance() {#getImportance--}
```
public final int getImportance()
```


Gets or sets the importance that is stamped on incoming messages in order for the condition or exception to apply.

**Returns:**
int
### getItemClasses() {#getItemClasses--}
```
public final System.Collections.Specialized.StringCollection getItemClasses()
```


Gets or sets the item classes that must be stamped on incoming messages in order for the condition or exception to apply.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getMessageClassifications() {#getMessageClassifications--}
```
public final System.Collections.Specialized.StringCollection getMessageClassifications()
```


Gets or sets the message classifications that must be stamped on incoming messages in order for the condition or exception to apply.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getRulePredicateFlags() {#getRulePredicateFlags--}
```
public final int getRulePredicateFlags()
```


Gets or sets rule predicate flags

**Returns:**
int
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets or sets the sensitivity that must be stamped on incoming messages in order for the condition or exception to apply.

**Returns:**
int
### getSentToAddresses() {#getSentToAddresses--}
```
public final MailAddressCollection getSentToAddresses()
```


Gets or sets the e-mail addresses that incoming messages have to have been sent to in order for the condition or exception to apply.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getWithinDateRange() {#getWithinDateRange--}
```
public final DateRange getWithinDateRange()
```


Gets or sets the date range within which incoming messages have to have been received in order for the condition or exception to apply.

**Returns:**
[DateRange](../../com.aspose.email/daterange)
### getWithinSizeRange() {#getWithinSizeRange--}
```
public final SizeRange getWithinSizeRange()
```


Gets or sets the minimum and maximum sizes that incoming messages have to have in order for the condition or exception to apply.

**Returns:**
[SizeRange](../../com.aspose.email/sizerange)
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




### setCategories(System.Collections.Specialized.StringCollection value) {#setCategories-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setCategories(System.Collections.Specialized.StringCollection value)
```


Gets or sets the categories that an incoming message is labeled with in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### setFlaggedForAction(int value) {#setFlaggedForAction-int-}
```
public final void setFlaggedForAction(int value)
```


Gets or sets the flag for action value that appears on incoming messages in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFromAddresses(MailAddressCollection value) {#setFromAddresses-com.aspose.email.MailAddressCollection-}
```
public final void setFromAddresses(MailAddressCollection value)
```


Gets or sets the e-mail addresses of the senders of incoming messages in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setFromConnectedAccounts(System.Collections.Specialized.StringCollection value) {#setFromConnectedAccounts-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setFromConnectedAccounts(System.Collections.Specialized.StringCollection value)
```


Gets or sets the e-mail account names from which incoming messages have to have been aggregated in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### setImportance(int value) {#setImportance-int-}
```
public final void setImportance(int value)
```


Gets or sets the importance that is stamped on incoming messages in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setItemClasses(System.Collections.Specialized.StringCollection value) {#setItemClasses-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setItemClasses(System.Collections.Specialized.StringCollection value)
```


Gets or sets the item classes that must be stamped on incoming messages in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### setMessageClassifications(System.Collections.Specialized.StringCollection value) {#setMessageClassifications-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setMessageClassifications(System.Collections.Specialized.StringCollection value)
```


Gets or sets the message classifications that must be stamped on incoming messages in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### setRulePredicateFlags(int value) {#setRulePredicateFlags-int-}
```
public final void setRulePredicateFlags(int value)
```


Gets or sets rule predicate flags

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


Gets or sets the sensitivity that must be stamped on incoming messages in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSentToAddresses(MailAddressCollection value) {#setSentToAddresses-com.aspose.email.MailAddressCollection-}
```
public final void setSentToAddresses(MailAddressCollection value)
```


Gets or sets the e-mail addresses that incoming messages have to have been sent to in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setWithinDateRange(DateRange value) {#setWithinDateRange-com.aspose.email.DateRange-}
```
public final void setWithinDateRange(DateRange value)
```


Gets or sets the date range within which incoming messages have to have been received in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateRange](../../com.aspose.email/daterange) |  |

### setWithinSizeRange(SizeRange value) {#setWithinSizeRange-com.aspose.email.SizeRange-}
```
public final void setWithinSizeRange(SizeRange value)
```


Gets or sets the minimum and maximum sizes that incoming messages have to have in order for the condition or exception to apply.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeRange](../../com.aspose.email/sizerange) |  |

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

