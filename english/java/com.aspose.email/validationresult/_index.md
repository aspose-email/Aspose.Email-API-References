---
title: ValidationResult
second_title: Aspose.Email for Java API Reference
description: Present the result of the email validating process.
type: docs
weight: 723
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLastException()](#getLastException--) | The last error met in the validating process. |
| [getMessage()](#getMessage--) | Gets the detail message about the result. |
| [getReturnCode()](#getReturnCode--) | Gets or ses the response code of the validating process. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLastException(RuntimeException value)](#setLastException-java.lang.RuntimeException-) | The last error met in the validating process. |
| [setReturnCode(int value)](#setReturnCode-int-) | Gets or ses the response code of the validating process. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getLastException() {#getLastException--}
```
public final RuntimeException getLastException()
```


The last error met in the validating process.

**Returns:**
java.lang.RuntimeException
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Gets the detail message about the result.

**Returns:**
java.lang.String
### getReturnCode() {#getReturnCode--}
```
public final int getReturnCode()
```


Gets or ses the response code of the validating process.

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




### setLastException(RuntimeException value) {#setLastException-java.lang.RuntimeException-}
```
public final void setLastException(RuntimeException value)
```


The last error met in the validating process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.RuntimeException |  |

### setReturnCode(int value) {#setReturnCode-int-}
```
public final void setReturnCode(int value)
```


Gets or ses the response code of the validating process.

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

