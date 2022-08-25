---
title: AsyncCommandResultEventArgs
second_title: Aspose.Email for Java API Reference
description:   is containing event data.
type: docs
weight: 62
url: /java/com.aspose.email/asynccommandresulteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class AsyncCommandResultEventArgs extends System.EventArgs
```

[AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) is containing event data.
## Constructors

| Constructor | Description |
| --- | --- |
| [AsyncCommandResultEventArgs()](#AsyncCommandResultEventArgs--) | Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class. |
| [AsyncCommandResultEventArgs(int result)](#AsyncCommandResultEventArgs-int-) | Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class. |
| [AsyncCommandResultEventArgs(int result, Throwable error)](#AsyncCommandResultEventArgs-int-java.lang.Throwable-) | Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class. |
## Methods

| Method | Description |
| --- | --- |
| [getResult()](#getResult--) | Operation state |
| [getError()](#getError--) | Operation error |
### AsyncCommandResultEventArgs() {#AsyncCommandResultEventArgs--}
```
public AsyncCommandResultEventArgs()
```


Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class.

### AsyncCommandResultEventArgs(int result) {#AsyncCommandResultEventArgs-int-}
```
public AsyncCommandResultEventArgs(int result)
```


Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | int | Contains operation result |

### AsyncCommandResultEventArgs(int result, Throwable error) {#AsyncCommandResultEventArgs-int-java.lang.Throwable-}
```
public AsyncCommandResultEventArgs(int result, Throwable error)
```


Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | int | Contains operation state |
| error | java.lang.Throwable | Contains operation error |

### getResult() {#getResult--}
```
public final int getResult()
```


Operation state

**Returns:**
int
### getError() {#getError--}
```
public final Throwable getError()
```


Operation error

**Returns:**
java.lang.Throwable
