---
title: EmailValidator
second_title: Aspose.Email for Java API Reference
description: class provides the capability to validate e-mail addresses.
type: docs
weight: 174
url: /java/com.aspose.email/emailvalidator/
---

**Inheritance:**
java.lang.Object
```
public final class EmailValidator
```

[EmailValidator](../../com.aspose.email/emailvalidator) class provides the capability to validate e-mail addresses.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailValidator()](#EmailValidator--) | Create an instance of [EmailValidator](../../com.aspose.email/emailvalidator). |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDnsServers()](#getDnsServers--) | Gets the DNS server list to use in the email validation. |
| [getTimeout()](#getTimeout--) | Gets the length of time (in milliseconds) until the request times out. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDnsServers(String[] value)](#setDnsServers-java.lang.String---) | Sets the DNS server list to use in the email validation. |
| [setTimeout(int value)](#setTimeout-int-) | Sets the length of time (in milliseconds) until the request times out. |
| [toString()](#toString--) |  |
| [validate(String mailAddress, ValidationResult[] result)](#validate-java.lang.String-com.aspose.email.ValidationResult---) | Validate email address, with the MailServer validation policy. |
| [validate(String mailAddress, int policy, ValidationResult[] result)](#validate-java.lang.String-int-com.aspose.email.ValidationResult---) | Validating the email address. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmailValidator() {#EmailValidator--}
```
public EmailValidator()
```


Create an instance of [EmailValidator](../../com.aspose.email/emailvalidator).

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
### getDnsServers() {#getDnsServers--}
```
public final String[] getDnsServers()
```


Gets the DNS server list to use in the email validation.

**Returns:**
java.lang.String[]
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Gets the length of time (in milliseconds) until the request times out.

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




### setDnsServers(String[] value) {#setDnsServers-java.lang.String---}
```
public final void setDnsServers(String[] value)
```


Sets the DNS server list to use in the email validation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Sets the length of time (in milliseconds) until the request times out.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate(String mailAddress, ValidationResult[] result) {#validate-java.lang.String-com.aspose.email.ValidationResult---}
```
public final void validate(String mailAddress, ValidationResult[] result)
```


Validate email address, with the MailServer validation policy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailAddress | java.lang.String | The Email address to be validated. |
| result | [ValidationResult\[\]](../../com.aspose.email/validationresult) | The result of the validation. A one-element array; the result is returned in  result[0] . |

### validate(String mailAddress, int policy, ValidationResult[] result) {#validate-java.lang.String-int-com.aspose.email.ValidationResult---}
```
public final void validate(String mailAddress, int policy, ValidationResult[] result)
```


Validating the email address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailAddress | java.lang.String | The mail address to be validated. |
| policy | int | The policy of the validating process. |
| result | [ValidationResult\[\]](../../com.aspose.email/validationresult) | The result of the validating process. A one-element array; the result is returned in  result[0] . |

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

