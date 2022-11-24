---
title: ICommand
second_title: Aspose.Email for Java API Reference
description: Defines a command.
type: docs
weight: 297
url: /java/com.aspose.email/icommand/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public abstract class ICommand implements System.IDisposable, Closeable
```

Defines a command.
## Constructors

| Constructor | Description |
| --- | --- |
| [ICommand()](#ICommand--) |  |
## Methods

| Method | Description |
| --- | --- |
| [canExecute()](#canExecute--) | Defines the operator that determines whether the command can execute in its current state. |
| [close()](#close--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute()](#execute--) | Defines the method to be called when the command is invoked. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ICommand() {#ICommand--}
```
public ICommand()
```


### canExecute() {#canExecute--}
```
public abstract boolean canExecute()
```


Defines the operator that determines whether the command can execute in its current state.

**Returns:**
boolean
### close() {#close--}
```
public void close()
```




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
### execute() {#execute--}
```
public abstract ICommand execute()
```


Defines the method to be called when the command is invoked.

**Returns:**
[ICommand](../../com.aspose.email/icommand) - Returns next command to execute. By default returns itself.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

