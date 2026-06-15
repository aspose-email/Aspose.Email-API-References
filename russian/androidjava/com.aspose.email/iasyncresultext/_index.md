---
title: IAsyncResultExt
second_title: Aspose.Email for Android via Java API Reference
description: Представляет расширенный статус асинхронной операции.
type: docs
weight: 453
url: /ru/androidjava/com.aspose.email/iasyncresultext/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult
```
public interface IAsyncResultExt extends System.IAsyncResult
```

Представляет расширенный статус асинхронной операции.
## Methods

| Method | Описание |
| --- | --- |
| [getErrorInfo()](#getErrorInfo--) | Получает значение, представляющее ошибку операции. |
| [isCanceled()](#isCanceled--) | Получает значение, указывающее, завершилась ли асинхронная операция синхронно. |
### getErrorInfo() {#getErrorInfo--}
```
public abstract RuntimeException getErrorInfo()
```


Получает значение, представляющее ошибку операции.

**Returns:**
java.lang.RuntimeException
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Получает значение, указывающее, завершилась ли асинхронная операция синхронно.

**Returns:**
boolean
