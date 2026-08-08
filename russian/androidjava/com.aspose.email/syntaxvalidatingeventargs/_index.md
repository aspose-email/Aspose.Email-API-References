---
title: SyntaxValidatingEventArgs
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет данные для события SyntaxValidating.
type: docs
weight: 394
url: /ru/androidjava/com.aspose.email/syntaxvalidatingeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class SyntaxValidatingEventArgs extends System.EventArgs
```

Предоставляет данные для события SyntaxValidating.
## Constructors

| Constructor | Описание |
| --- | --- |
| [SyntaxValidatingEventArgs(String mail)](#SyntaxValidatingEventArgs-java.lang.String-) | Инициализирует новый экземпляр класса SyntaxValidatingEventArgs. |
## Поля

| Поле | Описание |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMail()](#getMail--) | Получает проверяемый адрес электронной почты. |
| [getResult()](#getResult--) | Получает или задает результат проверки. |
| [getSkip()](#getSkip--) | Указывает, следует ли игнорировать проверку. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setResult(ValidationResult value)](#setResult-com.aspose.email.ValidationResult-) | Получает или задает результат проверки. |
| [setSkip(boolean value)](#setSkip-boolean-) | Указывает, следует ли игнорировать проверку. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SyntaxValidatingEventArgs(String mail) {#SyntaxValidatingEventArgs-java.lang.String-}
```
public SyntaxValidatingEventArgs(String mail)
```


Инициализирует новый экземпляр класса SyntaxValidatingEventArgs.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mail | java.lang.String | Адрес электронной почты. |

### Empty {#Empty}
```
public static final System.EventArgs Empty
```


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
### getMail() {#getMail--}
```
public final String getMail()
```


Получает проверяемый адрес электронной почты.

**Returns:**
java.lang.String
### getResult() {#getResult--}
```
public final ValidationResult getResult()
```


Получает или задает результат проверки.

**Returns:**
[ValidationResult](../../com.aspose.email/validationresult)
### getSkip() {#getSkip--}
```
public final boolean getSkip()
```


Указывает, следует ли игнорировать проверку.

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


Получает или задает результат проверки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [ValidationResult](../../com.aspose.email/validationresult) |  |

### setSkip(boolean value) {#setSkip-boolean-}
```
public final void setSkip(boolean value)
```


Указывает, следует ли игнорировать проверку.

**Parameters:**
| Parameter | Type | Описание |
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

