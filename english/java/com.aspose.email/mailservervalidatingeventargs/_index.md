---
title: MailServerValidatingEventArgs
second_title: Aspose.Email for Java API Reference
description: Provides data for the MailServerValidatingEvent event.
type: docs
weight: 392
url: /java/com.aspose.email/mailservervalidatingeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.aspose.email.SyntaxValidatingEventArgs](../../com.aspose.email/syntaxvalidatingeventargs), [com.aspose.email.DomainValidatingEventArgs](../../com.aspose.email/domainvalidatingeventargs)
```
public class MailServerValidatingEventArgs extends DomainValidatingEventArgs
```

Provides data for the MailServerValidatingEvent event.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailServerValidatingEventArgs(String mail, MailAddress mailaddress, String[] mailExchangeList)](#MailServerValidatingEventArgs-java.lang.String-com.aspose.email.MailAddress-java.lang.String---) | Initializes a new instance of the SyntaxValidatingEventArgs class. |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDomain()](#getDomain--) | Gets the domain. |
| [getMail()](#getMail--) | Gets the mail address is being validating. |
| [getMailAddress()](#getMailAddress--) | Gets the mail address. |
| [getMailExchangeServers()](#getMailExchangeServers--) | Gets the mail exchange server list. |
| [getMailExchangeServers_MailServerValidatingEventArgs_New()](#getMailExchangeServers-MailServerValidatingEventArgs-New--) | Gets the mail exchange server list. |
| [getResult()](#getResult--) | Gets or sets the validation result. |
| [getSkip()](#getSkip--) | Indicates whether to ignore the check. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setResult(ValidationResult value)](#setResult-com.aspose.email.ValidationResult-) | Gets or sets the validation result. |
| [setSkip(boolean value)](#setSkip-boolean-) | Indicates whether to ignore the check. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailServerValidatingEventArgs(String mail, MailAddress mailaddress, String[] mailExchangeList) {#MailServerValidatingEventArgs-java.lang.String-com.aspose.email.MailAddress-java.lang.String---}
```
public MailServerValidatingEventArgs(String mail, MailAddress mailaddress, String[] mailExchangeList)
```


Initializes a new instance of the SyntaxValidatingEventArgs class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mail | java.lang.String | A string contains the original copy of the mail address. |
| mailaddress | [MailAddress](../../com.aspose.email/mailaddress) | The MailAddress. |
| mailExchangeList | java.lang.String[] | A set of mail exchange server list. |

### Empty {#Empty}
```
public static final System.EventArgs Empty
```


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
### getDomain() {#getDomain--}
```
public final String getDomain()
```


Gets the domain.

**Returns:**
java.lang.String
### getMail() {#getMail--}
```
public final String getMail()
```


Gets the mail address is being validating.

**Returns:**
java.lang.String
### getMailAddress() {#getMailAddress--}
```
public final MailAddress getMailAddress()
```


Gets the mail address.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getMailExchangeServers() {#getMailExchangeServers--}
```
public final String[] getMailExchangeServers()
```


Gets the mail exchange server list.

**Returns:**
java.lang.String[]
### getMailExchangeServers_MailServerValidatingEventArgs_New() {#getMailExchangeServers-MailServerValidatingEventArgs-New--}
```
public final String[] getMailExchangeServers_MailServerValidatingEventArgs_New()
```


Gets the mail exchange server list.

**Returns:**
java.lang.String[]
### getResult() {#getResult--}
```
public final ValidationResult getResult()
```


Gets or sets the validation result.

**Returns:**
[ValidationResult](../../com.aspose.email/validationresult)
### getSkip() {#getSkip--}
```
public final boolean getSkip()
```


Indicates whether to ignore the check.

**Returns:**
boolean
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




### setResult(ValidationResult value) {#setResult-com.aspose.email.ValidationResult-}
```
public final void setResult(ValidationResult value)
```


Gets or sets the validation result.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ValidationResult](../../com.aspose.email/validationresult) |  |

### setSkip(boolean value) {#setSkip-boolean-}
```
public final void setSkip(boolean value)
```


Indicates whether to ignore the check.

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

