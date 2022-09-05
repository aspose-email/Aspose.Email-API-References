---
title: ValidationResult
second_title: Aspose.Email for Android via Java API Reference
description:  Present the result of the email validating process.
type: docs
weight: 438
url: /java/com.aspose.email/validationresult/
---
**Inheritance:**
java.lang.Object
```
public class ValidationResult
```

Present the result of the email validating process.
## Constructors

| Constructor | Description |
| --- | --- |
| [ValidationResult()](#ValidationResult--) | Create an instance of the ValidationResult class |
| [ValidationResult(int responseCode)](#ValidationResult-int-) | Create an instance of the ValidationResult class, with the specified |
| [ValidationResult(int responseCode, RuntimeException lastException)](#ValidationResult-int-java.lang.RuntimeException-) | Create an instance of the ValidationResult class, with the specified , and the last exception. |
## Methods

| Method | Description |
| --- | --- |
| [getReturnCode()](#getReturnCode--) | Gets or ses the response code of the validating process. |
| [setReturnCode(int value)](#setReturnCode-int-) | Gets or ses the response code of the validating process. |
| [getMessage()](#getMessage--) | Gets the detail message about the result. |
| [getLastException()](#getLastException--) | The last error met in the validating process. |
| [setLastException(RuntimeException value)](#setLastException-java.lang.RuntimeException-) | The last error met in the validating process. |
### ValidationResult() {#ValidationResult--}
```
public ValidationResult()
```


Create an instance of the ValidationResult class

### ValidationResult(int responseCode) {#ValidationResult-int-}
```
public ValidationResult(int responseCode)
```


Create an instance of the ValidationResult class, with the specified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| responseCode | int | The response code of the validating process. |

### ValidationResult(int responseCode, RuntimeException lastException) {#ValidationResult-int-java.lang.RuntimeException-}
```
public ValidationResult(int responseCode, RuntimeException lastException)
```


Create an instance of the ValidationResult class, with the specified , and the last exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| responseCode | int | The response code of the validating process. |
| lastException | java.lang.RuntimeException | The last exception met in the validating process. |

### getReturnCode() {#getReturnCode--}
```
public final int getReturnCode()
```


Gets or ses the response code of the validating process.

**Returns:**
int
### setReturnCode(int value) {#setReturnCode-int-}
```
public final void setReturnCode(int value)
```


Gets or ses the response code of the validating process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Gets the detail message about the result.

**Returns:**
java.lang.String
### getLastException() {#getLastException--}
```
public final RuntimeException getLastException()
```


The last error met in the validating process.

**Returns:**
java.lang.RuntimeException
### setLastException(RuntimeException value) {#setLastException-java.lang.RuntimeException-}
```
public final void setLastException(RuntimeException value)
```


The last error met in the validating process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.RuntimeException |  |

