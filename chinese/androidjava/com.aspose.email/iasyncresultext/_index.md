---
title: IAsyncResultExt
second_title: Aspose.Email for Android via Java API 参考
description: 表示异步操作的扩展状态。
type: docs
weight: 453
url: /zh/androidjava/com.aspose.email/iasyncresultext/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult
```
public interface IAsyncResultExt extends System.IAsyncResult
```

表示异步操作的扩展状态。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getErrorInfo()](#getErrorInfo--) | 获取表示操作错误的值。 |
| [isCanceled()](#isCanceled--) | 获取一个值，指示异步操作是否同步完成。 |
### getErrorInfo() {#getErrorInfo--}
```
public abstract RuntimeException getErrorInfo()
```


获取表示操作错误的值。

**Returns:**
java.lang.RuntimeException
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


获取一个值，指示异步操作是否同步完成。

**Returns:**
boolean
