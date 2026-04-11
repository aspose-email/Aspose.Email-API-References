---
title: DomainValidatingEventHandler
second_title: Aspose.Email for Android via Java API Reference
description: Представляет обработчик события для DomainValidatingEvent.
type: docs
weight: 113
url: /ru/androidjava/com.aspose.email/domainvalidatingeventhandler/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class DomainValidatingEventHandler extends System.MulticastDelegate
```

Представляет обработчик события для DomainValidatingEvent.
## Constructors

| Constructor | Описание |
| --- | --- |
| [DomainValidatingEventHandler()](#DomainValidatingEventHandler--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [beginInvoke(Object sender, DomainValidatingEventArgs e, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.Object-com.aspose.email.DomainValidatingEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | beginInvoke. |
| [combine(System.Delegate arg0, System.Delegate arg1)](#combine-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [combine(System.Delegate[] arg0)](#combine-com.aspose.ms.System.Delegate...-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) | endInvoke. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDelegateId()](#getDelegateId--) |  |
| [getInvocationList()](#getInvocationList--) |  |
| [hashCode()](#hashCode--) |  |
| [invoke(Object sender, DomainValidatingEventArgs e)](#invoke-java.lang.Object-com.aspose.email.DomainValidatingEventArgs-) | invoke. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(System.Delegate arg0, System.Delegate arg1)](#op-Equality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [op_Equality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)](#op-Equality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-) |  |
| [op_Inequality(System.Delegate arg0, System.Delegate arg1)](#op-Inequality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [op_Inequality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)](#op-Inequality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-) |  |
| [peekOutRefParam(int arg0)](#peekOutRefParam-int-) |  |
| [peekResult()](#peekResult--) |  |
| [remove(System.Delegate arg0, System.Delegate arg1)](#remove-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [removeAll(System.Delegate arg0, System.Delegate arg1)](#removeAll-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [setException(RuntimeException arg0)](#setException-java.lang.RuntimeException-) |  |
| [throwException()](#throwException--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DomainValidatingEventHandler() {#DomainValidatingEventHandler--}
```
public DomainValidatingEventHandler()
```


### beginInvoke(Object sender, DomainValidatingEventArgs e, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.Object-com.aspose.email.DomainValidatingEventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Object sender, DomainValidatingEventArgs e, System.AsyncCallback callback, Object state)
```


beginInvoke.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| отправитель | java.lang.Object | Объект java.lang.Object. |
| e | [DomainValidatingEventArgs](../../com.aspose.email/domainvalidatingeventargs) | Объект [DomainValidatingEventArgs](../../com.aspose.email/domainvalidatingeventargs). |
| обратный вызов | com.aspose.ms.System.AsyncCallback | Объект com.aspose.ms.System.AsyncCallback. |
| состояние | java.lang.Object | Объект java.lang.Object. |

**Returns:**
com.aspose.ms.System.IAsyncResult - объект com.aspose.ms.System.IAsyncResult.
### combine(System.Delegate arg0, System.Delegate arg1) {#combine-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate combine(System.Delegate arg0, System.Delegate arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Returns:**
com.aspose.ms.System.Delegate
### combine(System.Delegate[] arg0) {#combine-com.aspose.ms.System.Delegate...-}
```
public static System.Delegate combine(System.Delegate[] arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate[] |  |

**Returns:**
com.aspose.ms.System.Delegate
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```


endInvoke.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| результат | com.aspose.ms.System.IAsyncResult | Объект com.aspose.ms.System.IAsyncResult. |

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
### getDelegateId() {#getDelegateId--}
```
public String getDelegateId()
```




**Returns:**
java.lang.String
### getInvocationList() {#getInvocationList--}
```
public final System.Delegate[] getInvocationList()
```




**Returns:**
com.aspose.ms.System.Delegate[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### invoke(Object sender, DomainValidatingEventArgs e) {#invoke-java.lang.Object-com.aspose.email.DomainValidatingEventArgs-}
```
public abstract void invoke(Object sender, DomainValidatingEventArgs e)
```


invoke.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| отправитель | java.lang.Object | Объект java.lang.Object. |
| e | [DomainValidatingEventArgs](../../com.aspose.email/domainvalidatingeventargs) | Объект [DomainValidatingEventArgs](../../com.aspose.email/domainvalidatingeventargs). |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(System.Delegate arg0, System.Delegate arg1) {#op-Equality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static boolean op_Equality(System.Delegate arg0, System.Delegate arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Returns:**
boolean
### op_Equality(System.MulticastDelegate arg0, System.MulticastDelegate arg1) {#op-Equality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-}
```
public static boolean op_Equality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.MulticastDelegate |  |
| arg1 | com.aspose.ms.System.MulticastDelegate |  |

**Returns:**
boolean
### op_Inequality(System.Delegate arg0, System.Delegate arg1) {#op-Inequality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static boolean op_Inequality(System.Delegate arg0, System.Delegate arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Returns:**
boolean
### op_Inequality(System.MulticastDelegate arg0, System.MulticastDelegate arg1) {#op-Inequality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-}
```
public static boolean op_Inequality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.MulticastDelegate |  |
| arg1 | com.aspose.ms.System.MulticastDelegate |  |

**Returns:**
boolean
### peekOutRefParam(int arg0) {#peekOutRefParam-int-}
```
public Object peekOutRefParam(int arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
java.lang.Object
### peekResult() {#peekResult--}
```
public Object peekResult()
```




**Returns:**
java.lang.Object
### remove(System.Delegate arg0, System.Delegate arg1) {#remove-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate remove(System.Delegate arg0, System.Delegate arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Returns:**
com.aspose.ms.System.Delegate
### removeAll(System.Delegate arg0, System.Delegate arg1) {#removeAll-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate removeAll(System.Delegate arg0, System.Delegate arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Returns:**
com.aspose.ms.System.Delegate
### setException(RuntimeException arg0) {#setException-java.lang.RuntimeException-}
```
public void setException(RuntimeException arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.RuntimeException |  |

### throwException() {#throwException--}
```
public void throwException()
```




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

