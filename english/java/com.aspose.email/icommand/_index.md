---
title: ICommand
second_title: Aspose.Email for Java API Reference
description:  Defines a command.
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
| [execute()](#execute--) | Defines the method to be called when the command is invoked. |
| [close()](#close--) |  |
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
### execute() {#execute--}
```
public abstract ICommand execute()
```


Defines the method to be called when the command is invoked.

**Returns:**
[ICommand](../../com.aspose.email/icommand) - Returns next command to execute. By default returns itself.
### close() {#close--}
```
public void close()
```




