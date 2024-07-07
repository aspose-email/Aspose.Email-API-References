---
title: DomainValidatingEventArgs
second_title: Aspose.Email for Java API Reference
description: Provides data for the DomainValidating event.
type: docs
weight: 161
url: /java/com.aspose.email/domainvalidatingeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.aspose.email.SyntaxValidatingEventArgs](../../com.aspose.email/syntaxvalidatingeventargs)
```
public class DomainValidatingEventArgs extends SyntaxValidatingEventArgs
```

Provides data for the DomainValidating event.
## Constructors

| Constructor | Description |
| --- | --- |
| [DomainValidatingEventArgs(String mail, MailAddress mailaddress)](#DomainValidatingEventArgs-java.lang.String-com.aspose.email.MailAddress-) | Initializes a new instance of the SyntaxValidatingEventArgs class. |
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
### DomainValidatingEventArgs(String mail, MailAddress mailaddress) {#DomainValidatingEventArgs-java.lang.String-com.aspose.email.MailAddress-}
```
public DomainValidatingEventArgs(String mail, MailAddress mailaddress)
```


Initializes a new instance of the SyntaxValidatingEventArgs class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mail | java.lang.String | The mail address. |
| mailaddress | [MailAddress](../../com.aspose.email/mailaddress) | The mail address. |

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

