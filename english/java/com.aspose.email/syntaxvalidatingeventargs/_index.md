---
title: SyntaxValidatingEventArgs
second_title: Aspose.Email for Java API Reference
description:  Provides data for the SyntaxValidating event.
type: docs
weight: 654
url: /java/com.aspose.email/syntaxvalidatingeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class SyntaxValidatingEventArgs extends System.EventArgs
```

Provides data for the SyntaxValidating event.
## Constructors

| Constructor | Description |
| --- | --- |
| [SyntaxValidatingEventArgs(String mail)](#SyntaxValidatingEventArgs-java.lang.String-) | Initializes a new instance of the SyntaxValidatingEventArgs class. |
## Methods

| Method | Description |
| --- | --- |
| [getMail()](#getMail--) | Gets the mail address is being validating. |
| [getSkip()](#getSkip--) | Indicates whether to ignore the check. |
| [setSkip(boolean value)](#setSkip-boolean-) | Indicates whether to ignore the check. |
| [getResult()](#getResult--) | Gets or sets the validation result. |
| [setResult(ValidationResult value)](#setResult-com.aspose.email.ValidationResult-) | Gets or sets the validation result. |
### SyntaxValidatingEventArgs(String mail) {#SyntaxValidatingEventArgs-java.lang.String-}
```
public SyntaxValidatingEventArgs(String mail)
```


Initializes a new instance of the SyntaxValidatingEventArgs class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mail | java.lang.String | The mail address. |

### getMail() {#getMail--}
```
public final String getMail()
```


Gets the mail address is being validating.

**Returns:**
java.lang.String
### getSkip() {#getSkip--}
```
public final boolean getSkip()
```


Indicates whether to ignore the check.

**Returns:**
boolean
### setSkip(boolean value) {#setSkip-boolean-}
```
public final void setSkip(boolean value)
```


Indicates whether to ignore the check.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getResult() {#getResult--}
```
public final ValidationResult getResult()
```


Gets or sets the validation result.

**Returns:**
[ValidationResult](../../com.aspose.email/validationresult)
### setResult(ValidationResult value) {#setResult-com.aspose.email.ValidationResult-}
```
public final void setResult(ValidationResult value)
```


Gets or sets the validation result.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ValidationResult](../../com.aspose.email/validationresult) |  |

