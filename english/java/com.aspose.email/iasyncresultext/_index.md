---
title: IAsyncResultExt
second_title: Aspose.Email for Java API Reference
description:  Represents the extended status of an asynchronous operation.
type: docs
weight: 730
url: /java/com.aspose.email/iasyncresultext/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult
```
public interface IAsyncResultExt extends System.IAsyncResult
```

Represents the extended status of an asynchronous operation.
## Methods

| Method | Description |
| --- | --- |
| [isCanceled()](#isCanceled--) | Gets a value that indicates whether the asynchronous operation completed synchronously. |
| [getErrorInfo()](#getErrorInfo--) | Gets a value that represents operation error. |
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Gets a value that indicates whether the asynchronous operation completed synchronously.

**Returns:**
boolean
### getErrorInfo() {#getErrorInfo--}
```
public abstract RuntimeException getErrorInfo()
```


Gets a value that represents operation error.

**Returns:**
java.lang.RuntimeException
