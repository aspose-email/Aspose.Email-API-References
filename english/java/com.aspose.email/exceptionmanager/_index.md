---
title: ExceptionManager
second_title: Aspose.Email for Java API Reference
description:  Provides the ability to ignore exceptions.
type: docs
weight: 184
url: /java/com.aspose.email/exceptionmanager/
---
**Inheritance:**
java.lang.Object
```
public class ExceptionManager
```

Provides the ability to ignore exceptions.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExceptionManager()](#ExceptionManager--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getIgnoreExceptionsHandler()](#getIgnoreExceptionsHandler--) | Provides possibility to handle Exceptions. |
| [setIgnoreExceptionsHandler(IgnoreExceptionsCallback value)](#setIgnoreExceptionsHandler-com.aspose.email.IgnoreExceptionsCallback-) | Provides possibility to handle Exceptions. |
| [getIgnoreExceptionsLogHandler()](#getIgnoreExceptionsLogHandler--) | Provides possibility to handle Ignored Exceptions Log. |
| [setIgnoreExceptionsLogHandler(IgnoreExceptionsLogCallback value)](#setIgnoreExceptionsLogHandler-com.aspose.email.IgnoreExceptionsLogCallback-) | Provides possibility to handle Ignored Exceptions Log. |
| [getIgnoreAll()](#getIgnoreAll--) | Ignore all exceptions. |
| [setIgnoreAll(boolean value)](#setIgnoreAll-boolean-) | Ignore all exceptions. |
| [getIgnoreList()](#getIgnoreList--) | List of exceptions to be ignored. |
### ExceptionManager() {#ExceptionManager--}
```
public ExceptionManager()
```


### getIgnoreExceptionsHandler() {#getIgnoreExceptionsHandler--}
```
public static IgnoreExceptionsCallback getIgnoreExceptionsHandler()
```


Provides possibility to handle Exceptions.

**Returns:**
[IgnoreExceptionsCallback](../../com.aspose.email/ignoreexceptionscallback)
### setIgnoreExceptionsHandler(IgnoreExceptionsCallback value) {#setIgnoreExceptionsHandler-com.aspose.email.IgnoreExceptionsCallback-}
```
public static void setIgnoreExceptionsHandler(IgnoreExceptionsCallback value)
```


Provides possibility to handle Exceptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IgnoreExceptionsCallback](../../com.aspose.email/ignoreexceptionscallback) |  |

### getIgnoreExceptionsLogHandler() {#getIgnoreExceptionsLogHandler--}
```
public static IgnoreExceptionsLogCallback getIgnoreExceptionsLogHandler()
```


Provides possibility to handle Ignored Exceptions Log.

**Returns:**
[IgnoreExceptionsLogCallback](../../com.aspose.email/ignoreexceptionslogcallback)
### setIgnoreExceptionsLogHandler(IgnoreExceptionsLogCallback value) {#setIgnoreExceptionsLogHandler-com.aspose.email.IgnoreExceptionsLogCallback-}
```
public static void setIgnoreExceptionsLogHandler(IgnoreExceptionsLogCallback value)
```


Provides possibility to handle Ignored Exceptions Log.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IgnoreExceptionsLogCallback](../../com.aspose.email/ignoreexceptionslogcallback) |  |

### getIgnoreAll() {#getIgnoreAll--}
```
public static boolean getIgnoreAll()
```


Ignore all exceptions.

**Returns:**
boolean
### setIgnoreAll(boolean value) {#setIgnoreAll-boolean-}
```
public static void setIgnoreAll(boolean value)
```


Ignore all exceptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIgnoreList() {#getIgnoreList--}
```
public static List<String> getIgnoreList()
```


List of exceptions to be ignored.

**Returns:**
java.util.List<java.lang.String>
