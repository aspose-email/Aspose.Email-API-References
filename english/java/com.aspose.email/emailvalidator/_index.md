---
title: EmailValidator
second_title: Aspose.Email for Java API Reference
description:  EmailValidator class provides the capability to validate e-mail addresses.
type: docs
weight: 169
url: /java/com.aspose.email/emailvalidator/
---
**Inheritance:**
java.lang.Object
```
public final class EmailValidator
```

EmailValidator class provides the capability to validate e-mail addresses.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailValidator()](#EmailValidator--) | Create an instance of EmailValidator. |
## Fields

| Field | Description |
| --- | --- |
| [SyntaxValidating](#SyntaxValidating) |  |
| [DomainValidating](#DomainValidating) |  |
| [MailServerValidating](#MailServerValidating) |  |
## Methods

| Method | Description |
| --- | --- |
| [getDnsServers()](#getDnsServers--) | Gets or sets the Dns server list to use in the email validation. |
| [setDnsServers(String[] value)](#setDnsServers-java.lang.String---) | Gets or sets the Dns server list to use in the email validation. |
| [getTimeout()](#getTimeout--) | Gets or sets the length of time (in milliseconds) until the request times out. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the length of time (in milliseconds) until the request times out. |
| [validate(String mailAddress, int policy, ValidationResult[] result)](#validate-java.lang.String-int-com.aspose.email.ValidationResult---) | Validating the email address |
| [validate(String mailAddress, ValidationResult[] result)](#validate-java.lang.String-com.aspose.email.ValidationResult---) | Validate email address, with the MailServer validation policy. |
| [beginValidate(String mailAddress, int policy, ValidationResult[] result, System.AsyncCallback asyncCallback, Object stateObject)](#beginValidate-java.lang.String-int-com.aspose.email.ValidationResult---com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins an asynchronous validating process for an email address. |
| [endValidate(ValidationResult[] validationResult, System.IAsyncResult asyncResult)](#endValidate-com.aspose.email.ValidationResult---com.aspose.ms.System.IAsyncResult-) | Ends an asynchronous validating process for an email address. |
### EmailValidator() {#EmailValidator--}
```
public EmailValidator()
```


Create an instance of EmailValidator.

### SyntaxValidating {#SyntaxValidating}
```
public final Event<SyntaxValidatingEventHandler> SyntaxValidating
```


### DomainValidating {#DomainValidating}
```
public final Event<DomainValidatingEventHandler> DomainValidating
```


### MailServerValidating {#MailServerValidating}
```
public final Event<MailServerValidatingEventHandler> MailServerValidating
```


### getDnsServers() {#getDnsServers--}
```
public final String[] getDnsServers()
```


Gets or sets the Dns server list to use in the email validation.

**Returns:**
java.lang.String[]
### setDnsServers(String[] value) {#setDnsServers-java.lang.String---}
```
public final void setDnsServers(String[] value)
```


Gets or sets the Dns server list to use in the email validation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Gets or sets the length of time (in milliseconds) until the request times out.

**Returns:**
int
### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Gets or sets the length of time (in milliseconds) until the request times out.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### validate(String mailAddress, int policy, ValidationResult[] result) {#validate-java.lang.String-int-com.aspose.email.ValidationResult---}
```
public final void validate(String mailAddress, int policy, ValidationResult[] result)
```


Validating the email address

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailAddress | java.lang.String | The mail address to be validated. |
| policy | int | The policy of the validating process. |
| result | com.aspose.email.ValidationResult[] | The result of the validating process. |

### validate(String mailAddress, ValidationResult[] result) {#validate-java.lang.String-com.aspose.email.ValidationResult---}
```
public final void validate(String mailAddress, ValidationResult[] result)
```


Validate email address, with the MailServer validation policy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailAddress | java.lang.String | The Email address to be validated. |
| result | com.aspose.email.ValidationResult[] | The result of the validation. |

### beginValidate(String mailAddress, int policy, ValidationResult[] result, System.AsyncCallback asyncCallback, Object stateObject) {#beginValidate-java.lang.String-int-com.aspose.email.ValidationResult---com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginValidate(String mailAddress, int policy, ValidationResult[] result, System.AsyncCallback asyncCallback, Object stateObject)
```


Begins an asynchronous validating process for an email address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailAddress | java.lang.String | The email address to be validated. |
| policy | int | The policy of the validating process. |
| result | com.aspose.email.ValidationResult[] | The result of the validating process. |
| asyncCallback | com.aspose.ms.System.AsyncCallback | The AsyncCallback delegate |
| stateObject | java.lang.Object | An object that contains state information for this request. |

**Returns:**
com.aspose.ms.System.IAsyncResult - An IAsyncResult that references the asynchronous connection.
### endValidate(ValidationResult[] validationResult, System.IAsyncResult asyncResult) {#endValidate-com.aspose.email.ValidationResult---com.aspose.ms.System.IAsyncResult-}
```
public final void endValidate(ValidationResult[] validationResult, System.IAsyncResult asyncResult)
```


Ends an asynchronous validating process for an email address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| validationResult | com.aspose.email.ValidationResult[] | The result of the validating process. |
| asyncResult | com.aspose.ms.System.IAsyncResult | An IAsyncResult that stores state information and any user defined data for this asynchronous operation. |

