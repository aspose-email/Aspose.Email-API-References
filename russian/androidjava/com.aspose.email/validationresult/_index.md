---
title: ValidationResult
second_title: Aspose.Email for Android via Java API Reference
description: Представьте результат процесса проверки электронной почты.
type: docs
weight: 444
url: /ru/androidjava/com.aspose.email/validationresult/
---

**Inheritance:**
java.lang.Object
```
public class ValidationResult
```

Представьте результат процесса проверки электронной почты.
## Constructors

| Constructor | Описание |
| --- | --- |
| [ValidationResult()](#ValidationResult--) | Создайте экземпляр класса ValidationResult. |
| [ValidationResult(int responseCode)](#ValidationResult-int-) | Создайте экземпляр класса ValidationResult с указанным |
| [ValidationResult(int responseCode, RuntimeException lastException)](#ValidationResult-int-java.lang.RuntimeException-) | Создайте экземпляр класса ValidationResult с указанным , и последним исключением. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLastException()](#getLastException--) | Последняя ошибка, возникшая в процессе проверки. |
| [getMessage()](#getMessage--) | Получает подробное сообщение о результате. |
| [getReturnCode()](#getReturnCode--) | Получает или задает код ответа процесса проверки. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLastException(RuntimeException value)](#setLastException-java.lang.RuntimeException-) | Последняя ошибка, возникшая в процессе проверки. |
| [setReturnCode(int value)](#setReturnCode-int-) | Получает или задает код ответа процесса проверки. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ValidationResult() {#ValidationResult--}
```
public ValidationResult()
```


Создайте экземпляр класса ValidationResult.

### ValidationResult(int responseCode) {#ValidationResult-int-}
```
public ValidationResult(int responseCode)
```


Создайте экземпляр класса ValidationResult с указанным

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| responseCode | int | Код ответа процесса проверки. |

### ValidationResult(int responseCode, RuntimeException lastException) {#ValidationResult-int-java.lang.RuntimeException-}
```
public ValidationResult(int responseCode, RuntimeException lastException)
```


Создайте экземпляр класса ValidationResult с указанным , и последним исключением.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| responseCode | int | Код ответа процесса проверки. |
| lastException | java.lang.RuntimeException | Последнее исключение, возникшее в процессе проверки. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Описание |
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


Последняя ошибка, возникшая в процессе проверки.

**Returns:**
java.lang.RuntimeException
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Получает подробное сообщение о результате.

**Returns:**
java.lang.String
### getReturnCode() {#getReturnCode--}
```
public final int getReturnCode()
```


Получает или задает код ответа процесса проверки.

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


Последняя ошибка, возникшая в процессе проверки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.RuntimeException |  |

### setReturnCode(int value) {#setReturnCode-int-}
```
public final void setReturnCode(int value)
```


Получает или задает код ответа процесса проверки.

**Parameters:**
| Parameter | Type | Описание |
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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

