---
title: BounceResult
second_title: Aspose.Email for Android via Java API Reference
description: Представляет результат проверки сообщения как сообщение о возврате.
type: docs
weight: 60
url: /ru/androidjava/com.aspose.email/bounceresult/
---

**Inheritance:**
java.lang.Object
```
public class BounceResult
```

Представляет результат проверки сообщения как сообщение о возврате.
## Constructors

| Constructor | Описание |
| --- | --- |
| [BounceResult()](#BounceResult--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Указывает действие, выполненное в результате попытки доставить сообщение. |
| [getClass()](#getClass--) |  |
| [getOriginalMessage()](#getOriginalMessage--) | Содержит оригинальное сообщение. |
| [getReason()](#getReason--) | Для получателя со статусом "failed" или "delayed" содержит фактический диагностический код, выданный почтовой транспортной системой. |
| [getRecipient()](#getRecipient--) | Указывает оригинальный адрес получателя, указанный отправителем сообщения, для которого был выдан отчёт о сбое доставки. |
| [getStatus()](#getStatus--) | Содержит независимый от транспортного протокола код статуса, указывающий статус доставки сообщения этому получателю. |
| [hashCode()](#hashCode--) |  |
| [isBounced()](#isBounced--) | Истина, если электронное письмо является отчётом о сбое доставки или задержке доставки. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BounceResult() {#BounceResult--}
```
public BounceResult()
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
### getAction() {#getAction--}
```
public final int getAction()
```


Указывает действие, выполненное в результате попытки доставить сообщение.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOriginalMessage() {#getOriginalMessage--}
```
public final MailMessage getOriginalMessage()
```


Содержит оригинальное сообщение.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### getReason() {#getReason--}
```
public final String getReason()
```


Для получателя со статусом "failed" или "delayed" содержит фактический диагностический код, выданный почтовой транспортной системой.

**Returns:**
java.lang.String
### getRecipient() {#getRecipient--}
```
public final String getRecipient()
```


Указывает оригинальный адрес получателя, указанный отправителем сообщения, для которого был выдан отчёт о сбое доставки.

**Returns:**
java.lang.String
### getStatus() {#getStatus--}
```
public final String getStatus()
```


Содержит независимый от транспортного протокола код статуса, указывающий статус доставки сообщения этому получателю.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBounced() {#isBounced--}
```
public final boolean isBounced()
```


Истина, если электронное письмо является отчётом о сбое доставки или задержке доставки.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
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

